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
Job tag: CVC5-threads-8-mode-portfolio-smtcomp2025-QF_LRA-timeout20min
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
Job tag: CVC5-threads-8-mode-portfolio-smtcomp2025-QF_LRA-timeout20min
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
|scrambled101086.smt2                                                                        |1199.862s  |1199.862s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1199.841s  |1199.841s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1199.425s  |1199.425s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1199.762s  |1199.762s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1199.953s  |1199.953s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        | 782.232s  | 782.232s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1199.708s  |1199.708s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1199.823s  |1199.823s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 679.686s  | 679.686s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1199.738s  |1199.738s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1199.712s  |1199.712s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1199.772s  |1199.772s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1199.669s  |1199.669s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1199.746s  |1199.746s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1199.175s  |1199.175s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1199.794s  |1199.794s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1199.862s  |1199.862s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1199.841s  |1199.841s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1199.425s  |1199.425s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1199.762s  |1199.762s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1199.953s  |1199.953s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        | 782.232s  | 782.232s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1199.708s  |1199.708s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1199.823s  |1199.823s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 679.686s  | 679.686s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1199.738s  |1199.738s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1199.712s  |1199.712s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1199.772s  |1199.772s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1199.669s  |1199.669s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1199.746s  |1199.746s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1199.175s  |1199.175s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1199.794s  |1199.794s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1199.862s  |1199.862s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1199.841s  |1199.841s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1199.425s  |1199.425s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1199.762s  |1199.762s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1199.953s  |1199.953s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        | 782.232s  | 782.232s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1199.708s  |1199.708s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1199.823s  |1199.823s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 679.686s  | 679.686s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1199.738s  |1199.738s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1199.712s  |1199.712s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1199.772s  |1199.772s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1199.669s  |1199.669s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1199.746s  |1199.746s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1199.175s  |1199.175s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1199.794s  |1199.794s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1199.862s  |1199.862s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1199.841s  |1199.841s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1199.425s  |1199.425s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1199.762s  |1199.762s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1199.953s  |1199.953s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        | 782.232s  | 782.232s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1199.708s  |1199.708s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1199.823s  |1199.823s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 679.686s  | 679.686s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1199.738s  |1199.738s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1199.712s  |1199.712s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1199.772s  |1199.772s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1199.669s  |1199.669s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1199.746s  |1199.746s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1199.175s  |1199.175s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1199.794s  |1199.794s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled77308.smt2                                                                        |1200.310s |5045.0MiB|
|scrambled13209.smt2                                                                        |1200.068s |13.061GiB|
|scrambled98986.smt2                                                                        |1200.055s |9195.0MiB|
|scrambled13169.smt2                                                                        |1200.055s |12.359GiB|
|scrambled55850.smt2                                                                        |1200.052s |9609.0MiB|
|scrambled102621.smt2                                                                       |1200.050s |10.294GiB|
|scrambled8163.smt2                                                                         |1200.050s |12.718GiB|
|scrambled111949.smt2                                                                       |1200.041s |11.012GiB|
|scrambled65517.smt2                                                                        |1200.029s |4252.0MiB|
|scrambled77008.smt2                                                                        |1199.973s |5564.0MiB|
|scrambled104811.smt2                                                                       |1199.953s |4727.0MiB|
|scrambled101086.smt2                                                                       |1199.862s |2254.0MiB|
|scrambled101728.smt2                                                                       |1199.841s |5340.0MiB|
|scrambled117897.smt2                                                                       |1199.823s |2641.0MiB|
|scrambled92964.smt2                                                                        |1199.814s |1730.0MiB|
|scrambled49820.smt2                                                                        |1199.809s |1960.0MiB|
|scrambled76525.smt2                                                                        |1199.796s |2329.0MiB|
|scrambled37260.smt2                                                                        |1199.794s |2394.0MiB|
|scrambled95284.smt2                                                                        |1199.787s |2436.0MiB|
|scrambled17583.smt2                                                                        |1199.772s |2460.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled77308.smt2                                                                        |1200.310s |5045.0MiB|
|scrambled13209.smt2                                                                        |1200.068s |13.061GiB|
|scrambled98986.smt2                                                                        |1200.055s |9195.0MiB|
|scrambled13169.smt2                                                                        |1200.055s |12.359GiB|
|scrambled55850.smt2                                                                        |1200.052s |9609.0MiB|
|scrambled102621.smt2                                                                       |1200.050s |10.294GiB|
|scrambled8163.smt2                                                                         |1200.050s |12.718GiB|
|scrambled111949.smt2                                                                       |1200.041s |11.012GiB|
|scrambled65517.smt2                                                                        |1200.029s |4252.0MiB|
|scrambled77008.smt2                                                                        |1199.973s |5564.0MiB|
|scrambled104811.smt2                                                                       |1199.953s |4727.0MiB|
|scrambled101086.smt2                                                                       |1199.862s |2254.0MiB|
|scrambled101728.smt2                                                                       |1199.841s |5340.0MiB|
|scrambled117897.smt2                                                                       |1199.823s |2641.0MiB|
|scrambled92964.smt2                                                                        |1199.814s |1730.0MiB|
|scrambled49820.smt2                                                                        |1199.809s |1960.0MiB|
|scrambled76525.smt2                                                                        |1199.796s |2329.0MiB|
|scrambled37260.smt2                                                                        |1199.794s |2394.0MiB|
|scrambled95284.smt2                                                                        |1199.787s |2436.0MiB|
|scrambled17583.smt2                                                                        |1199.772s |2460.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |2254.0MiB|2254.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |5340.0MiB|5340.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |10.294GiB|10.294GiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |8002.0MiB|8002.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |1069.0MiB|1069.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |4727.0MiB|4727.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |3390.0MiB|3390.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |11.012GiB|11.012GiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |972.0MiB|972.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |2641.0MiB|2641.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |747.0MiB|747.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |2296.0MiB|2296.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |1567.0MiB|1567.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |12.359GiB|12.359GiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |13.061GiB|13.061GiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |2460.0MiB|2460.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |12.026GiB|12.026GiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |1448.0MiB|1448.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |497.0MiB|497.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |2394.0MiB|2394.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |2254.0MiB|2254.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |5340.0MiB|5340.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |10.294GiB|10.294GiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |8002.0MiB|8002.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |1069.0MiB|1069.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |4727.0MiB|4727.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |3390.0MiB|3390.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |11.012GiB|11.012GiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |972.0MiB|972.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |2641.0MiB|2641.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |747.0MiB|747.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |2296.0MiB|2296.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |1567.0MiB|1567.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |12.359GiB|12.359GiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |13.061GiB|13.061GiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |2460.0MiB|2460.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |12.026GiB|12.026GiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |1448.0MiB|1448.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |497.0MiB|497.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |2394.0MiB|2394.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |2254.0MiB|2254.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |5340.0MiB|5340.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |10.294GiB|10.294GiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |8002.0MiB|8002.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |1069.0MiB|1069.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |4727.0MiB|4727.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |3390.0MiB|3390.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |11.012GiB|11.012GiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |972.0MiB|972.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |2641.0MiB|2641.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |747.0MiB|747.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |2296.0MiB|2296.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |1567.0MiB|1567.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |12.359GiB|12.359GiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |13.061GiB|13.061GiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |2460.0MiB|2460.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |12.026GiB|12.026GiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |1448.0MiB|1448.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |497.0MiB|497.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |2394.0MiB|2394.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |2254.0MiB|2254.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |5340.0MiB|5340.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |10.294GiB|10.294GiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |8002.0MiB|8002.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |1069.0MiB|1069.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |4727.0MiB|4727.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |3390.0MiB|3390.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |11.012GiB|11.012GiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |972.0MiB|972.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |2641.0MiB|2641.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |747.0MiB|747.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |2296.0MiB|2296.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |1567.0MiB|1567.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |12.359GiB|12.359GiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |13.061GiB|13.061GiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |2460.0MiB|2460.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |12.026GiB|12.026GiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |1448.0MiB|1448.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |497.0MiB|497.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |2394.0MiB|2394.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled44527.smt2                                                                        | 353.167s |19.049GiB|
|scrambled13209.smt2                                                                        |1200.068s |13.061GiB|
|scrambled8163.smt2                                                                         |1200.050s |12.718GiB|
|scrambled13169.smt2                                                                        |1200.055s |12.359GiB|
|scrambled25695.smt2                                                                        |1199.669s |12.026GiB|
|scrambled111949.smt2                                                                       |1200.041s |11.012GiB|
|scrambled102621.smt2                                                                       |1200.050s |10.294GiB|
|scrambled55850.smt2                                                                        |1200.052s |9609.0MiB|
|scrambled98986.smt2                                                                        |1200.055s |9195.0MiB|
|scrambled102680.smt2                                                                       |1199.425s |8002.0MiB|
|scrambled77008.smt2                                                                        |1199.973s |5564.0MiB|
|scrambled101728.smt2                                                                       |1199.841s |5340.0MiB|
|scrambled77308.smt2                                                                        |1200.310s |5045.0MiB|
|scrambled104811.smt2                                                                       |1199.953s |4727.0MiB|
|scrambled65517.smt2                                                                        |1200.029s |4252.0MiB|
|scrambled109307.smt2                                                                       | 782.232s |3390.0MiB|
|scrambled117897.smt2                                                                       |1199.823s |2641.0MiB|
|scrambled17583.smt2                                                                        |1199.772s |2460.0MiB|
|scrambled95284.smt2                                                                        |1199.787s |2436.0MiB|
|scrambled37260.smt2                                                                        |1199.794s |2394.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled44527.smt2                                                                        | 353.167s |19.049GiB|
|scrambled13209.smt2                                                                        |1200.068s |13.061GiB|
|scrambled8163.smt2                                                                         |1200.050s |12.718GiB|
|scrambled13169.smt2                                                                        |1200.055s |12.359GiB|
|scrambled25695.smt2                                                                        |1199.669s |12.026GiB|
|scrambled111949.smt2                                                                       |1200.041s |11.012GiB|
|scrambled102621.smt2                                                                       |1200.050s |10.294GiB|
|scrambled55850.smt2                                                                        |1200.052s |9609.0MiB|
|scrambled98986.smt2                                                                        |1200.055s |9195.0MiB|
|scrambled102680.smt2                                                                       |1199.425s |8002.0MiB|
|scrambled77008.smt2                                                                        |1199.973s |5564.0MiB|
|scrambled101728.smt2                                                                       |1199.841s |5340.0MiB|
|scrambled77308.smt2                                                                        |1200.310s |5045.0MiB|
|scrambled104811.smt2                                                                       |1199.953s |4727.0MiB|
|scrambled65517.smt2                                                                        |1200.029s |4252.0MiB|
|scrambled109307.smt2                                                                       | 782.232s |3390.0MiB|
|scrambled117897.smt2                                                                       |1199.823s |2641.0MiB|
|scrambled17583.smt2                                                                        |1199.772s |2460.0MiB|
|scrambled95284.smt2                                                                        |1199.787s |2436.0MiB|
|scrambled37260.smt2                                                                        |1199.794s |2394.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1199.862s  |1199.862s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1199.841s  |1199.841s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        |1199.425s  |1199.425s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1199.762s  |1199.762s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1199.953s  |1199.953s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        | 782.232s  | 782.232s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1199.708s  |1199.708s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1199.823s  |1199.823s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 679.686s  | 679.686s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1199.738s  |1199.738s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1199.712s  |1199.712s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1199.772s  |1199.772s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1199.669s  |1199.669s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1199.746s  |1199.746s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1199.175s  |1199.175s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1199.794s  |1199.794s  |   0.000s  | 0.0%|
|scrambled44527.smt2                                                                         | 353.167s  | 353.167s  |   0.000s  | 0.0%|
|scrambled46192.smt2                                                                         |1199.727s  |1199.727s  |   0.000s  | 0.0%|
|scrambled47581.smt2                                                                         |1199.649s  |1199.649s  |   0.000s  | 0.0%|
|scrambled49820.smt2                                                                         |1199.809s  |1199.809s  |   0.000s  | 0.0%|
|scrambled55845.smt2                                                                         |1199.747s  |1199.747s  |   0.000s  | 0.0%|
|scrambled55850.smt2                                                                         |1200.052s  |1200.052s  |   0.000s  | 0.0%|
|scrambled59368.smt2                                                                         |1199.705s  |1199.705s  |   0.000s  | 0.0%|
|scrambled65517.smt2                                                                         |1200.029s  |1200.029s  |   0.000s  | 0.0%|
|scrambled71015.smt2                                                                         | 578.079s  | 578.079s  |   0.000s  | 0.0%|
|scrambled76525.smt2                                                                         |1199.796s  |1199.796s  |   0.000s  | 0.0%|
|scrambled76532.smt2                                                                         |1199.554s  |1199.554s  |   0.000s  | 0.0%|
|scrambled77008.smt2                                                                         |1199.973s  |1199.973s  |   0.000s  | 0.0%|
|scrambled77308.smt2                                                                         |1200.310s  |1200.310s  |   0.000s  | 0.0%|
|scrambled8163.smt2                                                                          |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled88927.smt2                                                                         | 958.381s  | 958.381s  |   0.000s  | 0.0%|
|scrambled92964.smt2                                                                         |1199.814s  |1199.814s  |   0.000s  | 0.0%|
|scrambled95284.smt2                                                                         |1199.787s  |1199.787s  |   0.000s  | 0.0%|
</details>
