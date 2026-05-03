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
Job tag: CVC5-threads-1-mode-sequential-smtcomp2025-QF_IDL-timeout20min
Runner: rise-runner-2
cvc5 repo: cvc5/cvc5
cvc5 commit: e7e5bb6ea37ae6122da5c4f165b73c87089be765
cvc5 branch: main
cvc5 mode: sequential
cvc5 portfolio mode: graduated
cvc5 portfolio strategies: "decision-scatter decision-cube"
cvc5 partition budget: 1
cvc5 partitioning options: "--partition-when=tlimit --partition-start-time=3 --partition-time-interval=0.1 --partition-check=standard"
cvc5 portfolio options: ""
cvc5 solver options: ""
cvc5 solver jobs: 1
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
Job tag: CVC5-threads-1-mode-sequential-smtcomp2025-QF_IDL-timeout20min
Runner: rise-runner-2
cvc5 repo: cvc5/cvc5
cvc5 commit: e7e5bb6ea37ae6122da5c4f165b73c87089be765
cvc5 branch: main
cvc5 mode: sequential
cvc5 portfolio mode: graduated
cvc5 portfolio strategies: "decision-scatter decision-cube"
cvc5 partition budget: 1
cvc5 partitioning options: "--partition-when=tlimit --partition-start-time=3 --partition-time-interval=0.1 --partition-check=standard"
cvc5 portfolio options: ""
cvc5 solver options: ""
cvc5 solver jobs: 1
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
|scrambled100416.smt2                                                                        |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.205s  |1200.205s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.140s  |1200.140s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.179s  |1200.179s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        |1200.135s  |1200.135s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         |1200.094s  |1200.094s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.209s  |1200.209s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.125s  |1200.125s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1201.036s  |1201.036s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.095s  |1200.095s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.049s  |1200.049s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.205s  |1200.205s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.140s  |1200.140s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.179s  |1200.179s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        |1200.135s  |1200.135s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         |1200.094s  |1200.094s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.209s  |1200.209s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.125s  |1200.125s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1201.036s  |1201.036s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.095s  |1200.095s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.049s  |1200.049s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.205s  |1200.205s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.140s  |1200.140s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.179s  |1200.179s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        |1200.135s  |1200.135s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         |1200.094s  |1200.094s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.209s  |1200.209s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.125s  |1200.125s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1201.036s  |1201.036s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.095s  |1200.095s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.049s  |1200.049s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.205s  |1200.205s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.140s  |1200.140s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.179s  |1200.179s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        |1200.135s  |1200.135s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         |1200.094s  |1200.094s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.209s  |1200.209s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.125s  |1200.125s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1201.036s  |1201.036s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.095s  |1200.095s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.049s  |1200.049s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1201.036s |10.848GiB|
|scrambled15552.smt2                                                                        |1200.209s |1400.0MiB|
|scrambled109208.smt2                                                                       |1200.205s |1369.0MiB|
|scrambled122058.smt2                                                                       |1200.179s |1204.0MiB|
|scrambled92133.smt2                                                                        |1200.175s |992.0MiB|
|scrambled90733.smt2                                                                        |1200.145s |688.0MiB|
|scrambled117178.smt2                                                                       |1200.140s |957.0MiB|
|scrambled82743.smt2                                                                        |1200.139s |628.0MiB|
|scrambled54073.smt2                                                                        |1200.136s |573.0MiB|
|scrambled128361.smt2                                                                       |1200.135s |609.0MiB|
|scrambled58720.smt2                                                                        |1200.130s |591.0MiB|
|scrambled78432.smt2                                                                        |1200.127s |531.0MiB|
|scrambled21544.smt2                                                                        |1200.125s |491.0MiB|
|scrambled62859.smt2                                                                        |1200.124s |427.0MiB|
|scrambled122413.smt2                                                                       |1200.122s |480.0MiB|
|scrambled4441.smt2                                                                         |1200.122s |652.0MiB|
|scrambled79181.smt2                                                                        |1200.118s |451.0MiB|
|scrambled98799.smt2                                                                        |1200.118s |622.0MiB|
|scrambled78606.smt2                                                                        |1200.115s |569.0MiB|
|scrambled14967.smt2                                                                        |1200.110s |509.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1201.036s |10.848GiB|
|scrambled15552.smt2                                                                        |1200.209s |1400.0MiB|
|scrambled109208.smt2                                                                       |1200.205s |1369.0MiB|
|scrambled122058.smt2                                                                       |1200.179s |1204.0MiB|
|scrambled92133.smt2                                                                        |1200.175s |992.0MiB|
|scrambled90733.smt2                                                                        |1200.145s |688.0MiB|
|scrambled117178.smt2                                                                       |1200.140s |957.0MiB|
|scrambled82743.smt2                                                                        |1200.139s |628.0MiB|
|scrambled54073.smt2                                                                        |1200.136s |573.0MiB|
|scrambled128361.smt2                                                                       |1200.135s |609.0MiB|
|scrambled58720.smt2                                                                        |1200.130s |591.0MiB|
|scrambled78432.smt2                                                                        |1200.127s |531.0MiB|
|scrambled21544.smt2                                                                        |1200.125s |491.0MiB|
|scrambled62859.smt2                                                                        |1200.124s |427.0MiB|
|scrambled122413.smt2                                                                       |1200.122s |480.0MiB|
|scrambled4441.smt2                                                                         |1200.122s |652.0MiB|
|scrambled79181.smt2                                                                        |1200.118s |451.0MiB|
|scrambled98799.smt2                                                                        |1200.118s |622.0MiB|
|scrambled78606.smt2                                                                        |1200.115s |569.0MiB|
|scrambled14967.smt2                                                                        |1200.110s |509.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |430.0MiB|430.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |409.0MiB|409.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |1369.0MiB|1369.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |266.0MiB|266.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |957.0MiB|957.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |233.0MiB|233.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |1204.0MiB|1204.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |480.0MiB|480.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |696.0MiB|696.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |609.0MiB|609.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |228.0MiB|228.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |397.0MiB|397.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |509.0MiB|509.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |293.0MiB|293.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |1400.0MiB|1400.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |491.0MiB|491.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |194.0MiB|194.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |10.848GiB|10.848GiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |282.0MiB|282.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |316.0MiB|316.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |430.0MiB|430.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |409.0MiB|409.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |1369.0MiB|1369.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |266.0MiB|266.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |957.0MiB|957.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |233.0MiB|233.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |1204.0MiB|1204.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |480.0MiB|480.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |696.0MiB|696.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |609.0MiB|609.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |228.0MiB|228.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |397.0MiB|397.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |509.0MiB|509.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |293.0MiB|293.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |1400.0MiB|1400.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |491.0MiB|491.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |194.0MiB|194.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |10.848GiB|10.848GiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |282.0MiB|282.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |316.0MiB|316.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |430.0MiB|430.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |409.0MiB|409.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |1369.0MiB|1369.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |266.0MiB|266.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |957.0MiB|957.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |233.0MiB|233.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |1204.0MiB|1204.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |480.0MiB|480.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |696.0MiB|696.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |609.0MiB|609.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |228.0MiB|228.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |397.0MiB|397.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |509.0MiB|509.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |293.0MiB|293.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |1400.0MiB|1400.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |491.0MiB|491.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |194.0MiB|194.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |10.848GiB|10.848GiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |282.0MiB|282.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |316.0MiB|316.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |430.0MiB|430.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |409.0MiB|409.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |1369.0MiB|1369.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |266.0MiB|266.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |957.0MiB|957.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |233.0MiB|233.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |1204.0MiB|1204.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |480.0MiB|480.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |696.0MiB|696.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |609.0MiB|609.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |228.0MiB|228.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |397.0MiB|397.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |509.0MiB|509.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |293.0MiB|293.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |1400.0MiB|1400.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |491.0MiB|491.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |194.0MiB|194.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |10.848GiB|10.848GiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |282.0MiB|282.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |316.0MiB|316.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1201.036s |10.848GiB|
|scrambled15552.smt2                                                                        |1200.209s |1400.0MiB|
|scrambled109208.smt2                                                                       |1200.205s |1369.0MiB|
|scrambled122058.smt2                                                                       |1200.179s |1204.0MiB|
|scrambled92133.smt2                                                                        |1200.175s |992.0MiB|
|scrambled117178.smt2                                                                       |1200.140s |957.0MiB|
|scrambled124624.smt2                                                                       |1200.090s |696.0MiB|
|scrambled90733.smt2                                                                        |1200.145s |688.0MiB|
|scrambled4441.smt2                                                                         |1200.122s |652.0MiB|
|scrambled82743.smt2                                                                        |1200.139s |628.0MiB|
|scrambled98799.smt2                                                                        |1200.118s |622.0MiB|
|scrambled128361.smt2                                                                       |1200.135s |609.0MiB|
|scrambled58720.smt2                                                                        |1200.130s |591.0MiB|
|scrambled89071.smt2                                                                        |1177.411s |574.0MiB|
|scrambled54073.smt2                                                                        |1200.136s |573.0MiB|
|scrambled78606.smt2                                                                        |1200.115s |569.0MiB|
|scrambled9927.smt2                                                                         |1200.082s |569.0MiB|
|scrambled78432.smt2                                                                        |1200.127s |531.0MiB|
|scrambled14967.smt2                                                                        |1200.110s |509.0MiB|
|scrambled21544.smt2                                                                        |1200.125s |491.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1201.036s |10.848GiB|
|scrambled15552.smt2                                                                        |1200.209s |1400.0MiB|
|scrambled109208.smt2                                                                       |1200.205s |1369.0MiB|
|scrambled122058.smt2                                                                       |1200.179s |1204.0MiB|
|scrambled92133.smt2                                                                        |1200.175s |992.0MiB|
|scrambled117178.smt2                                                                       |1200.140s |957.0MiB|
|scrambled124624.smt2                                                                       |1200.090s |696.0MiB|
|scrambled90733.smt2                                                                        |1200.145s |688.0MiB|
|scrambled4441.smt2                                                                         |1200.122s |652.0MiB|
|scrambled82743.smt2                                                                        |1200.139s |628.0MiB|
|scrambled98799.smt2                                                                        |1200.118s |622.0MiB|
|scrambled128361.smt2                                                                       |1200.135s |609.0MiB|
|scrambled58720.smt2                                                                        |1200.130s |591.0MiB|
|scrambled89071.smt2                                                                        |1177.411s |574.0MiB|
|scrambled54073.smt2                                                                        |1200.136s |573.0MiB|
|scrambled78606.smt2                                                                        |1200.115s |569.0MiB|
|scrambled9927.smt2                                                                         |1200.082s |569.0MiB|
|scrambled78432.smt2                                                                        |1200.127s |531.0MiB|
|scrambled14967.smt2                                                                        |1200.110s |509.0MiB|
|scrambled21544.smt2                                                                        |1200.125s |491.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.205s  |1200.205s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |1200.140s  |1200.140s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.179s  |1200.179s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        |1200.135s  |1200.135s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.090s  |1200.090s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         |1200.094s  |1200.094s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.209s  |1200.209s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.125s  |1200.125s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1201.036s  |1201.036s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.095s  |1200.095s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled38610.smt2                                                                         |1200.105s  |1200.105s  |   0.000s  | 0.0%|
|scrambled41312.smt2                                                                         |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled41773.smt2                                                                         |1200.092s  |1200.092s  |   0.000s  | 0.0%|
|scrambled41801.smt2                                                                         |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled42287.smt2                                                                         |1200.107s  |1200.107s  |   0.000s  | 0.0%|
|scrambled4441.smt2                                                                          |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled54073.smt2                                                                         |1200.136s  |1200.136s  |   0.000s  | 0.0%|
|scrambled58720.smt2                                                                         |1200.130s  |1200.130s  |   0.000s  | 0.0%|
|scrambled62536.smt2                                                                         |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled62810.smt2                                                                         |1200.099s  |1200.099s  |   0.000s  | 0.0%|
|scrambled62859.smt2                                                                         |1200.124s  |1200.124s  |   0.000s  | 0.0%|
|scrambled6373.smt2                                                                          |1200.109s  |1200.109s  |   0.000s  | 0.0%|
|scrambled75206.smt2                                                                         |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled78432.smt2                                                                         |1200.127s  |1200.127s  |   0.000s  | 0.0%|
|scrambled78606.smt2                                                                         |1200.115s  |1200.115s  |   0.000s  | 0.0%|
|scrambled79181.smt2                                                                         |1200.118s  |1200.118s  |   0.000s  | 0.0%|
|scrambled82743.smt2                                                                         |1200.139s  |1200.139s  |   0.000s  | 0.0%|
|scrambled89071.smt2                                                                         |1177.411s  |1177.411s  |   0.000s  | 0.0%|
|scrambled90733.smt2                                                                         |1200.145s  |1200.145s  |   0.000s  | 0.0%|
|scrambled92133.smt2                                                                         |1200.175s  |1200.175s  |   0.000s  | 0.0%|
|scrambled96514.smt2                                                                         | 597.201s  | 597.201s  |   0.000s  | 0.0%|
|scrambled96733.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled97138.smt2                                                                         |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled98799.smt2                                                                         |1200.118s  |1200.118s  |   0.000s  | 0.0%|
</details>
