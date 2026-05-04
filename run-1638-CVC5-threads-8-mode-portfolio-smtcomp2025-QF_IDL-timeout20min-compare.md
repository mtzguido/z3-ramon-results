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
Job tag: CVC5-threads-8-mode-portfolio-smtcomp2025-QF_IDL-timeout20min
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
Job tag: CVC5-threads-8-mode-portfolio-smtcomp2025-QF_IDL-timeout20min
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
|scrambled100416.smt2                                                                        |1199.530s  |1199.530s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1199.836s  |1199.836s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1199.546s  |1199.546s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1199.704s  |1199.704s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1199.586s  |1199.586s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1199.602s  |1199.602s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1199.706s  |1199.706s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        |1200.053s  |1200.053s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1199.543s  |1199.543s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1199.971s  |1199.971s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1199.966s  |1199.966s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         |1199.838s  |1199.838s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1199.706s  |1199.706s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1199.838s  |1199.838s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1199.723s  |1199.723s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1199.910s  |1199.910s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1199.559s  |1199.559s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1199.530s  |1199.530s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1199.836s  |1199.836s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1199.546s  |1199.546s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1199.704s  |1199.704s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1199.586s  |1199.586s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1199.602s  |1199.602s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1199.706s  |1199.706s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        |1200.053s  |1200.053s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1199.543s  |1199.543s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1199.971s  |1199.971s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1199.966s  |1199.966s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         |1199.838s  |1199.838s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1199.706s  |1199.706s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1199.838s  |1199.838s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1199.723s  |1199.723s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1199.910s  |1199.910s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1199.559s  |1199.559s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1199.530s  |1199.530s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1199.836s  |1199.836s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1199.546s  |1199.546s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1199.704s  |1199.704s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1199.586s  |1199.586s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1199.602s  |1199.602s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1199.706s  |1199.706s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        |1200.053s  |1200.053s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1199.543s  |1199.543s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1199.971s  |1199.971s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1199.966s  |1199.966s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         |1199.838s  |1199.838s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1199.706s  |1199.706s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1199.838s  |1199.838s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1199.723s  |1199.723s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1199.910s  |1199.910s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1199.559s  |1199.559s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1199.530s  |1199.530s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1199.836s  |1199.836s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1199.546s  |1199.546s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1199.704s  |1199.704s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1199.586s  |1199.586s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1199.602s  |1199.602s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1199.706s  |1199.706s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        |1200.053s  |1200.053s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1199.543s  |1199.543s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1199.971s  |1199.971s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1199.966s  |1199.966s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         |1199.838s  |1199.838s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1199.706s  |1199.706s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1199.838s  |1199.838s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1199.723s  |1199.723s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1199.910s  |1199.910s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1199.559s  |1199.559s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled79181.smt2                                                                        |1200.210s |2140.0MiB|
|scrambled38610.smt2                                                                        |1200.064s |2703.0MiB|
|scrambled109208.smt2                                                                       |1200.063s |6449.0MiB|
|scrambled98799.smt2                                                                        |1200.053s |4480.0MiB|
|scrambled128361.smt2                                                                       |1200.053s |4235.0MiB|
|scrambled25140.smt2                                                                        |1200.049s |67.277GiB|
|scrambled92133.smt2                                                                        |1200.049s |7181.0MiB|
|scrambled41312.smt2                                                                        |1200.048s |2317.0MiB|
|scrambled122058.smt2                                                                       |1200.047s |5320.0MiB|
|scrambled82743.smt2                                                                        |1200.046s |5215.0MiB|
|scrambled42287.smt2                                                                        |1200.018s |2435.0MiB|
|scrambled62810.smt2                                                                        |1199.978s |2202.0MiB|
|scrambled62536.smt2                                                                        |1199.972s |5343.0MiB|
|scrambled1447.smt2                                                                         |1199.971s |2197.0MiB|
|scrambled14967.smt2                                                                        |1199.966s |2218.0MiB|
|scrambled78432.smt2                                                                        |1199.956s |4117.0MiB|
|scrambled9927.smt2                                                                         |1199.950s |4020.0MiB|
|scrambled27577.smt2                                                                        |1199.910s |2824.0MiB|
|scrambled4441.smt2                                                                         |1199.895s |4642.0MiB|
|scrambled78606.smt2                                                                        |1199.864s |3968.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled79181.smt2                                                                        |1200.210s |2140.0MiB|
|scrambled38610.smt2                                                                        |1200.064s |2703.0MiB|
|scrambled109208.smt2                                                                       |1200.063s |6449.0MiB|
|scrambled98799.smt2                                                                        |1200.053s |4480.0MiB|
|scrambled128361.smt2                                                                       |1200.053s |4235.0MiB|
|scrambled25140.smt2                                                                        |1200.049s |67.277GiB|
|scrambled92133.smt2                                                                        |1200.049s |7181.0MiB|
|scrambled41312.smt2                                                                        |1200.048s |2317.0MiB|
|scrambled122058.smt2                                                                       |1200.047s |5320.0MiB|
|scrambled82743.smt2                                                                        |1200.046s |5215.0MiB|
|scrambled42287.smt2                                                                        |1200.018s |2435.0MiB|
|scrambled62810.smt2                                                                        |1199.978s |2202.0MiB|
|scrambled62536.smt2                                                                        |1199.972s |5343.0MiB|
|scrambled1447.smt2                                                                         |1199.971s |2197.0MiB|
|scrambled14967.smt2                                                                        |1199.966s |2218.0MiB|
|scrambled78432.smt2                                                                        |1199.956s |4117.0MiB|
|scrambled9927.smt2                                                                         |1199.950s |4020.0MiB|
|scrambled27577.smt2                                                                        |1199.910s |2824.0MiB|
|scrambled4441.smt2                                                                         |1199.895s |4642.0MiB|
|scrambled78606.smt2                                                                        |1199.864s |3968.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |2117.0MiB|2117.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |3017.0MiB|3017.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |6449.0MiB|6449.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |1599.0MiB|1599.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |3108.0MiB|3108.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |1706.0MiB|1706.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |5320.0MiB|5320.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |2147.0MiB|2147.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |5013.0MiB|5013.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |4235.0MiB|4235.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |1542.0MiB|1542.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |2197.0MiB|2197.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |2218.0MiB|2218.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |1321.0MiB|1321.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |5695.0MiB|5695.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |2865.0MiB|2865.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |1324.0MiB|1324.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |67.277GiB|67.277GiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |2824.0MiB|2824.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |1830.0MiB|1830.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |2117.0MiB|2117.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |3017.0MiB|3017.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |6449.0MiB|6449.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |1599.0MiB|1599.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |3108.0MiB|3108.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |1706.0MiB|1706.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |5320.0MiB|5320.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |2147.0MiB|2147.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |5013.0MiB|5013.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |4235.0MiB|4235.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |1542.0MiB|1542.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |2197.0MiB|2197.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |2218.0MiB|2218.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |1321.0MiB|1321.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |5695.0MiB|5695.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |2865.0MiB|2865.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |1324.0MiB|1324.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |67.277GiB|67.277GiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |2824.0MiB|2824.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |1830.0MiB|1830.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |2117.0MiB|2117.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |3017.0MiB|3017.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |6449.0MiB|6449.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |1599.0MiB|1599.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |3108.0MiB|3108.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |1706.0MiB|1706.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |5320.0MiB|5320.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |2147.0MiB|2147.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |5013.0MiB|5013.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |4235.0MiB|4235.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |1542.0MiB|1542.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |2197.0MiB|2197.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |2218.0MiB|2218.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |1321.0MiB|1321.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |5695.0MiB|5695.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |2865.0MiB|2865.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |1324.0MiB|1324.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |67.277GiB|67.277GiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |2824.0MiB|2824.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |1830.0MiB|1830.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |2117.0MiB|2117.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |3017.0MiB|3017.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |6449.0MiB|6449.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |1599.0MiB|1599.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |3108.0MiB|3108.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |1706.0MiB|1706.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |5320.0MiB|5320.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |2147.0MiB|2147.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |5013.0MiB|5013.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |4235.0MiB|4235.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |1542.0MiB|1542.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |2197.0MiB|2197.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |2218.0MiB|2218.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |1321.0MiB|1321.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |5695.0MiB|5695.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |2865.0MiB|2865.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |1324.0MiB|1324.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |67.277GiB|67.277GiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |2824.0MiB|2824.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |1830.0MiB|1830.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1200.049s |67.277GiB|
|scrambled92133.smt2                                                                        |1200.049s |7181.0MiB|
|scrambled109208.smt2                                                                       |1200.063s |6449.0MiB|
|scrambled15552.smt2                                                                        |1199.706s |5695.0MiB|
|scrambled62536.smt2                                                                        |1199.972s |5343.0MiB|
|scrambled122058.smt2                                                                       |1200.047s |5320.0MiB|
|scrambled82743.smt2                                                                        |1200.046s |5215.0MiB|
|scrambled124624.smt2                                                                       |1199.706s |5013.0MiB|
|scrambled4441.smt2                                                                         |1199.895s |4642.0MiB|
|scrambled98799.smt2                                                                        |1200.053s |4480.0MiB|
|scrambled90733.smt2                                                                        |1199.691s |4299.0MiB|
|scrambled128361.smt2                                                                       |1200.053s |4235.0MiB|
|scrambled54073.smt2                                                                        |1199.692s |4150.0MiB|
|scrambled96514.smt2                                                                        | 802.480s |4149.0MiB|
|scrambled78432.smt2                                                                        |1199.956s |4117.0MiB|
|scrambled9927.smt2                                                                         |1199.950s |4020.0MiB|
|scrambled78606.smt2                                                                        |1199.864s |3968.0MiB|
|scrambled89071.smt2                                                                        |1199.664s |3836.0MiB|
|scrambled62859.smt2                                                                        |1199.609s |3125.0MiB|
|scrambled117178.smt2                                                                       |1199.704s |3108.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1200.049s |67.277GiB|
|scrambled92133.smt2                                                                        |1200.049s |7181.0MiB|
|scrambled109208.smt2                                                                       |1200.063s |6449.0MiB|
|scrambled15552.smt2                                                                        |1199.706s |5695.0MiB|
|scrambled62536.smt2                                                                        |1199.972s |5343.0MiB|
|scrambled122058.smt2                                                                       |1200.047s |5320.0MiB|
|scrambled82743.smt2                                                                        |1200.046s |5215.0MiB|
|scrambled124624.smt2                                                                       |1199.706s |5013.0MiB|
|scrambled4441.smt2                                                                         |1199.895s |4642.0MiB|
|scrambled98799.smt2                                                                        |1200.053s |4480.0MiB|
|scrambled90733.smt2                                                                        |1199.691s |4299.0MiB|
|scrambled128361.smt2                                                                       |1200.053s |4235.0MiB|
|scrambled54073.smt2                                                                        |1199.692s |4150.0MiB|
|scrambled96514.smt2                                                                        | 802.480s |4149.0MiB|
|scrambled78432.smt2                                                                        |1199.956s |4117.0MiB|
|scrambled9927.smt2                                                                         |1199.950s |4020.0MiB|
|scrambled78606.smt2                                                                        |1199.864s |3968.0MiB|
|scrambled89071.smt2                                                                        |1199.664s |3836.0MiB|
|scrambled62859.smt2                                                                        |1199.609s |3125.0MiB|
|scrambled117178.smt2                                                                       |1199.704s |3108.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1199.530s  |1199.530s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1199.836s  |1199.836s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1199.546s  |1199.546s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1199.704s  |1199.704s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1199.586s  |1199.586s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1199.602s  |1199.602s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1199.706s  |1199.706s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        |1200.053s  |1200.053s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1199.543s  |1199.543s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1199.971s  |1199.971s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1199.966s  |1199.966s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         |1199.838s  |1199.838s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1199.706s  |1199.706s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1199.838s  |1199.838s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1199.723s  |1199.723s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1199.910s  |1199.910s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1199.559s  |1199.559s  |   0.000s  | 0.0%|
|scrambled38610.smt2                                                                         |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled41312.smt2                                                                         |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled41773.smt2                                                                         |1199.754s  |1199.754s  |   0.000s  | 0.0%|
|scrambled41801.smt2                                                                         |1199.643s  |1199.643s  |   0.000s  | 0.0%|
|scrambled42287.smt2                                                                         |1200.018s  |1200.018s  |   0.000s  | 0.0%|
|scrambled4441.smt2                                                                          |1199.895s  |1199.895s  |   0.000s  | 0.0%|
|scrambled54073.smt2                                                                         |1199.692s  |1199.692s  |   0.000s  | 0.0%|
|scrambled58720.smt2                                                                         |1199.686s  |1199.686s  |   0.000s  | 0.0%|
|scrambled62536.smt2                                                                         |1199.972s  |1199.972s  |   0.000s  | 0.0%|
|scrambled62810.smt2                                                                         |1199.978s  |1199.978s  |   0.000s  | 0.0%|
|scrambled62859.smt2                                                                         |1199.609s  |1199.609s  |   0.000s  | 0.0%|
|scrambled6373.smt2                                                                          |1199.781s  |1199.781s  |   0.000s  | 0.0%|
|scrambled75206.smt2                                                                         |1199.755s  |1199.755s  |   0.000s  | 0.0%|
|scrambled78432.smt2                                                                         |1199.956s  |1199.956s  |   0.000s  | 0.0%|
|scrambled78606.smt2                                                                         |1199.864s  |1199.864s  |   0.000s  | 0.0%|
|scrambled79181.smt2                                                                         |1200.210s  |1200.210s  |   0.000s  | 0.0%|
|scrambled82743.smt2                                                                         |1200.046s  |1200.046s  |   0.000s  | 0.0%|
|scrambled89071.smt2                                                                         |1199.664s  |1199.664s  |   0.000s  | 0.0%|
|scrambled90733.smt2                                                                         |1199.691s  |1199.691s  |   0.000s  | 0.0%|
|scrambled92133.smt2                                                                         |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled96514.smt2                                                                         | 802.480s  | 802.480s  |   0.000s  | 0.0%|
|scrambled96733.smt2                                                                         |1199.773s  |1199.773s  |   0.000s  | 0.0%|
|scrambled97138.smt2                                                                         |1199.806s  |1199.806s  |   0.000s  | 0.0%|
|scrambled98799.smt2                                                                         |1200.053s  |1200.053s  |   0.000s  | 0.0%|
</details>
