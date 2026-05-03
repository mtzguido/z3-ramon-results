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
Ramon benchmark for cvc5
-
Job description: 
Job tag: CVC5-threads-1-mode-sequential-smtcomp2025-QF_NRA-timeout20min
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
cvc5 inputs: inputs/smt_comp_2025_parallel/QF_NRA
cvc5 commit message: Alethe add INTS_LOG2 and INTS_ISPOW2 (#12626)

These two operators do appear in the proofs of bit-vector benchmarks.

Co-authored-by: Haniel Barbosa <hanielbbarbosa@gmail.com>

</pre>
# RHS
<pre>
Ramon benchmark for cvc5
-
Job description: 
Job tag: CVC5-threads-1-mode-sequential-smtcomp2025-QF_NRA-timeout20min
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
cvc5 inputs: inputs/smt_comp_2025_parallel/QF_NRA
cvc5 commit message: Alethe add INTS_LOG2 and INTS_ISPOW2 (#12626)

These two operators do appear in the proofs of bit-vector benchmarks.

Co-authored-by: Haniel Barbosa <hanielbbarbosa@gmail.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1183.207s  |1183.207s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.025s  |1200.025s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.072s  |1200.072s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |1200.094s  |1200.094s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.025s  |1200.025s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.124s  |1200.124s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1183.207s  |1183.207s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.025s  |1200.025s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.072s  |1200.072s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |1200.094s  |1200.094s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.025s  |1200.025s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.124s  |1200.124s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1183.207s  |1183.207s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.025s  |1200.025s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.072s  |1200.072s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |1200.094s  |1200.094s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.025s  |1200.025s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.124s  |1200.124s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1183.207s  |1183.207s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.025s  |1200.025s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.072s  |1200.072s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |1200.094s  |1200.094s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.025s  |1200.025s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.124s  |1200.124s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled32701.smt2                                                                        |1200.124s |766.0MiB|
|scrambled94768.smt2                                                                        |1200.112s |645.0MiB|
|scrambled14880.smt2                                                                        |1200.101s |563.0MiB|
|scrambled124828.smt2                                                                       |1200.097s |821.0MiB|
|scrambled14368.smt2                                                                        |1200.094s |644.0MiB|
|scrambled14016.smt2                                                                        |1200.082s |386.0MiB|
|scrambled58292.smt2                                                                        |1200.082s |722.0MiB|
|scrambled5797.smt2                                                                         |1200.082s |341.0MiB|
|scrambled94319.smt2                                                                        |1200.073s |560.0MiB|
|scrambled118224.smt2                                                                       |1200.072s |766.0MiB|
|scrambled85895.smt2                                                                        |1200.068s |236.0MiB|
|scrambled36539.smt2                                                                        |1200.065s |233.0MiB|
|scrambled91241.smt2                                                                        |1200.065s |275.0MiB|
|scrambled28630.smt2                                                                        |1200.065s |202.0MiB|
|scrambled82241.smt2                                                                        |1200.063s |229.0MiB|
|scrambled29556.smt2                                                                        |1200.059s |312.0MiB|
|scrambled61896.smt2                                                                        |1200.055s |164.0MiB|
|scrambled60239.smt2                                                                        |1200.054s |189.0MiB|
|scrambled41575.smt2                                                                        |1200.051s |234.0MiB|
|scrambled112144.smt2                                                                       |1200.050s |272.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled32701.smt2                                                                        |1200.124s |766.0MiB|
|scrambled94768.smt2                                                                        |1200.112s |645.0MiB|
|scrambled14880.smt2                                                                        |1200.101s |563.0MiB|
|scrambled124828.smt2                                                                       |1200.097s |821.0MiB|
|scrambled14368.smt2                                                                        |1200.094s |644.0MiB|
|scrambled14016.smt2                                                                        |1200.082s |386.0MiB|
|scrambled58292.smt2                                                                        |1200.082s |722.0MiB|
|scrambled5797.smt2                                                                         |1200.082s |341.0MiB|
|scrambled94319.smt2                                                                        |1200.073s |560.0MiB|
|scrambled118224.smt2                                                                       |1200.072s |766.0MiB|
|scrambled85895.smt2                                                                        |1200.068s |236.0MiB|
|scrambled36539.smt2                                                                        |1200.065s |233.0MiB|
|scrambled91241.smt2                                                                        |1200.065s |275.0MiB|
|scrambled28630.smt2                                                                        |1200.065s |202.0MiB|
|scrambled82241.smt2                                                                        |1200.063s |229.0MiB|
|scrambled29556.smt2                                                                        |1200.059s |312.0MiB|
|scrambled61896.smt2                                                                        |1200.055s |164.0MiB|
|scrambled60239.smt2                                                                        |1200.054s |189.0MiB|
|scrambled41575.smt2                                                                        |1200.051s |234.0MiB|
|scrambled112144.smt2                                                                       |1200.050s |272.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |51.152MiB|51.152MiB|0B| 0.0%|
|scrambled112083.smt2                                                                        |37.52MiB|37.52MiB|0B| 0.0%|
|scrambled112144.smt2                                                                        |272.0MiB|272.0MiB|0B| 0.0%|
|scrambled114923.smt2                                                                        |1461.0MiB|1461.0MiB|0B| 0.0%|
|scrambled117334.smt2                                                                        |46.572MiB|46.572MiB|0B| 0.0%|
|scrambled117944.smt2                                                                        |61.388MiB|61.388MiB|0B| 0.0%|
|scrambled118224.smt2                                                                        |766.0MiB|766.0MiB|0B| 0.0%|
|scrambled121780.smt2                                                                        |196.0MiB|196.0MiB|0B| 0.0%|
|scrambled124828.smt2                                                                        |821.0MiB|821.0MiB|0B| 0.0%|
|scrambled14016.smt2                                                                         |386.0MiB|386.0MiB|0B| 0.0%|
|scrambled14368.smt2                                                                         |644.0MiB|644.0MiB|0B| 0.0%|
|scrambled14880.smt2                                                                         |563.0MiB|563.0MiB|0B| 0.0%|
|scrambled18831.smt2                                                                         |170.0MiB|170.0MiB|0B| 0.0%|
|scrambled21647.smt2                                                                         |351.0MiB|351.0MiB|0B| 0.0%|
|scrambled22492.smt2                                                                         |97.604MiB|97.604MiB|0B| 0.0%|
|scrambled27426.smt2                                                                         |207.0MiB|207.0MiB|0B| 0.0%|
|scrambled28630.smt2                                                                         |202.0MiB|202.0MiB|0B| 0.0%|
|scrambled29556.smt2                                                                         |312.0MiB|312.0MiB|0B| 0.0%|
|scrambled32269.smt2                                                                         |63.604MiB|63.604MiB|0B| 0.0%|
|scrambled32701.smt2                                                                         |766.0MiB|766.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |51.152MiB|51.152MiB|0B| 0.0%|
|scrambled112083.smt2                                                                        |37.52MiB|37.52MiB|0B| 0.0%|
|scrambled112144.smt2                                                                        |272.0MiB|272.0MiB|0B| 0.0%|
|scrambled114923.smt2                                                                        |1461.0MiB|1461.0MiB|0B| 0.0%|
|scrambled117334.smt2                                                                        |46.572MiB|46.572MiB|0B| 0.0%|
|scrambled117944.smt2                                                                        |61.388MiB|61.388MiB|0B| 0.0%|
|scrambled118224.smt2                                                                        |766.0MiB|766.0MiB|0B| 0.0%|
|scrambled121780.smt2                                                                        |196.0MiB|196.0MiB|0B| 0.0%|
|scrambled124828.smt2                                                                        |821.0MiB|821.0MiB|0B| 0.0%|
|scrambled14016.smt2                                                                         |386.0MiB|386.0MiB|0B| 0.0%|
|scrambled14368.smt2                                                                         |644.0MiB|644.0MiB|0B| 0.0%|
|scrambled14880.smt2                                                                         |563.0MiB|563.0MiB|0B| 0.0%|
|scrambled18831.smt2                                                                         |170.0MiB|170.0MiB|0B| 0.0%|
|scrambled21647.smt2                                                                         |351.0MiB|351.0MiB|0B| 0.0%|
|scrambled22492.smt2                                                                         |97.604MiB|97.604MiB|0B| 0.0%|
|scrambled27426.smt2                                                                         |207.0MiB|207.0MiB|0B| 0.0%|
|scrambled28630.smt2                                                                         |202.0MiB|202.0MiB|0B| 0.0%|
|scrambled29556.smt2                                                                         |312.0MiB|312.0MiB|0B| 0.0%|
|scrambled32269.smt2                                                                         |63.604MiB|63.604MiB|0B| 0.0%|
|scrambled32701.smt2                                                                         |766.0MiB|766.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |51.152MiB|51.152MiB|0B| 0.0%|
|scrambled112083.smt2                                                                        |37.52MiB|37.52MiB|0B| 0.0%|
|scrambled112144.smt2                                                                        |272.0MiB|272.0MiB|0B| 0.0%|
|scrambled114923.smt2                                                                        |1461.0MiB|1461.0MiB|0B| 0.0%|
|scrambled117334.smt2                                                                        |46.572MiB|46.572MiB|0B| 0.0%|
|scrambled117944.smt2                                                                        |61.388MiB|61.388MiB|0B| 0.0%|
|scrambled118224.smt2                                                                        |766.0MiB|766.0MiB|0B| 0.0%|
|scrambled121780.smt2                                                                        |196.0MiB|196.0MiB|0B| 0.0%|
|scrambled124828.smt2                                                                        |821.0MiB|821.0MiB|0B| 0.0%|
|scrambled14016.smt2                                                                         |386.0MiB|386.0MiB|0B| 0.0%|
|scrambled14368.smt2                                                                         |644.0MiB|644.0MiB|0B| 0.0%|
|scrambled14880.smt2                                                                         |563.0MiB|563.0MiB|0B| 0.0%|
|scrambled18831.smt2                                                                         |170.0MiB|170.0MiB|0B| 0.0%|
|scrambled21647.smt2                                                                         |351.0MiB|351.0MiB|0B| 0.0%|
|scrambled22492.smt2                                                                         |97.604MiB|97.604MiB|0B| 0.0%|
|scrambled27426.smt2                                                                         |207.0MiB|207.0MiB|0B| 0.0%|
|scrambled28630.smt2                                                                         |202.0MiB|202.0MiB|0B| 0.0%|
|scrambled29556.smt2                                                                         |312.0MiB|312.0MiB|0B| 0.0%|
|scrambled32269.smt2                                                                         |63.604MiB|63.604MiB|0B| 0.0%|
|scrambled32701.smt2                                                                         |766.0MiB|766.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |51.152MiB|51.152MiB|0B| 0.0%|
|scrambled112083.smt2                                                                        |37.52MiB|37.52MiB|0B| 0.0%|
|scrambled112144.smt2                                                                        |272.0MiB|272.0MiB|0B| 0.0%|
|scrambled114923.smt2                                                                        |1461.0MiB|1461.0MiB|0B| 0.0%|
|scrambled117334.smt2                                                                        |46.572MiB|46.572MiB|0B| 0.0%|
|scrambled117944.smt2                                                                        |61.388MiB|61.388MiB|0B| 0.0%|
|scrambled118224.smt2                                                                        |766.0MiB|766.0MiB|0B| 0.0%|
|scrambled121780.smt2                                                                        |196.0MiB|196.0MiB|0B| 0.0%|
|scrambled124828.smt2                                                                        |821.0MiB|821.0MiB|0B| 0.0%|
|scrambled14016.smt2                                                                         |386.0MiB|386.0MiB|0B| 0.0%|
|scrambled14368.smt2                                                                         |644.0MiB|644.0MiB|0B| 0.0%|
|scrambled14880.smt2                                                                         |563.0MiB|563.0MiB|0B| 0.0%|
|scrambled18831.smt2                                                                         |170.0MiB|170.0MiB|0B| 0.0%|
|scrambled21647.smt2                                                                         |351.0MiB|351.0MiB|0B| 0.0%|
|scrambled22492.smt2                                                                         |97.604MiB|97.604MiB|0B| 0.0%|
|scrambled27426.smt2                                                                         |207.0MiB|207.0MiB|0B| 0.0%|
|scrambled28630.smt2                                                                         |202.0MiB|202.0MiB|0B| 0.0%|
|scrambled29556.smt2                                                                         |312.0MiB|312.0MiB|0B| 0.0%|
|scrambled32269.smt2                                                                         |63.604MiB|63.604MiB|0B| 0.0%|
|scrambled32701.smt2                                                                         |766.0MiB|766.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled114923.smt2                                                                       |1183.207s |1461.0MiB|
|scrambled124828.smt2                                                                       |1200.097s |821.0MiB|
|scrambled32701.smt2                                                                        |1200.124s |766.0MiB|
|scrambled118224.smt2                                                                       |1200.072s |766.0MiB|
|scrambled58292.smt2                                                                        |1200.082s |722.0MiB|
|scrambled94768.smt2                                                                        |1200.112s |645.0MiB|
|scrambled14368.smt2                                                                        |1200.094s |644.0MiB|
|scrambled14880.smt2                                                                        |1200.101s |563.0MiB|
|scrambled94319.smt2                                                                        |1200.073s |560.0MiB|
|scrambled14016.smt2                                                                        |1200.082s |386.0MiB|
|scrambled21647.smt2                                                                        |1200.035s |351.0MiB|
|scrambled5797.smt2                                                                         |1200.082s |341.0MiB|
|scrambled70990.smt2                                                                        |1200.037s |324.0MiB|
|scrambled29556.smt2                                                                        |1200.059s |312.0MiB|
|scrambled91241.smt2                                                                        |1200.065s |275.0MiB|
|scrambled112144.smt2                                                                       |1200.050s |272.0MiB|
|scrambled7923.smt2                                                                         |1200.034s |257.0MiB|
|scrambled85895.smt2                                                                        |1200.068s |236.0MiB|
|scrambled41575.smt2                                                                        |1200.051s |234.0MiB|
|scrambled36539.smt2                                                                        |1200.065s |233.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled114923.smt2                                                                       |1183.207s |1461.0MiB|
|scrambled124828.smt2                                                                       |1200.097s |821.0MiB|
|scrambled32701.smt2                                                                        |1200.124s |766.0MiB|
|scrambled118224.smt2                                                                       |1200.072s |766.0MiB|
|scrambled58292.smt2                                                                        |1200.082s |722.0MiB|
|scrambled94768.smt2                                                                        |1200.112s |645.0MiB|
|scrambled14368.smt2                                                                        |1200.094s |644.0MiB|
|scrambled14880.smt2                                                                        |1200.101s |563.0MiB|
|scrambled94319.smt2                                                                        |1200.073s |560.0MiB|
|scrambled14016.smt2                                                                        |1200.082s |386.0MiB|
|scrambled21647.smt2                                                                        |1200.035s |351.0MiB|
|scrambled5797.smt2                                                                         |1200.082s |341.0MiB|
|scrambled70990.smt2                                                                        |1200.037s |324.0MiB|
|scrambled29556.smt2                                                                        |1200.059s |312.0MiB|
|scrambled91241.smt2                                                                        |1200.065s |275.0MiB|
|scrambled112144.smt2                                                                       |1200.050s |272.0MiB|
|scrambled7923.smt2                                                                         |1200.034s |257.0MiB|
|scrambled85895.smt2                                                                        |1200.068s |236.0MiB|
|scrambled41575.smt2                                                                        |1200.051s |234.0MiB|
|scrambled36539.smt2                                                                        |1200.065s |233.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100912.smt2                                                                        |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled112083.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled112144.smt2                                                                        |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled114923.smt2                                                                        |1183.207s  |1183.207s  |   0.000s  | 0.0%|
|scrambled117334.smt2                                                                        |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled117944.smt2                                                                        |1200.025s  |1200.025s  |   0.000s  | 0.0%|
|scrambled118224.smt2                                                                        |1200.072s  |1200.072s  |   0.000s  | 0.0%|
|scrambled121780.smt2                                                                        |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled124828.smt2                                                                        |1200.097s  |1200.097s  |   0.000s  | 0.0%|
|scrambled14016.smt2                                                                         |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled14368.smt2                                                                         |1200.094s  |1200.094s  |   0.000s  | 0.0%|
|scrambled14880.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled18831.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled21647.smt2                                                                         |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled22492.smt2                                                                         |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled27426.smt2                                                                         |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled28630.smt2                                                                         |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled29556.smt2                                                                         |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled32269.smt2                                                                         |1200.025s  |1200.025s  |   0.000s  | 0.0%|
|scrambled32701.smt2                                                                         |1200.124s  |1200.124s  |   0.000s  | 0.0%|
|scrambled34121.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled36539.smt2                                                                         |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled41575.smt2                                                                         |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled42946.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled54263.smt2                                                                         |1200.026s  |1200.026s  |   0.000s  | 0.0%|
|scrambled5797.smt2                                                                          |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled58292.smt2                                                                         |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled60239.smt2                                                                         |1200.054s  |1200.054s  |   0.000s  | 0.0%|
|scrambled61896.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled6476.smt2                                                                          |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled65757.smt2                                                                         |1200.023s  |1200.023s  |   0.000s  | 0.0%|
|scrambled70990.smt2                                                                         |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled73220.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
|scrambled74869.smt2                                                                         |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled7586.smt2                                                                          |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled78428.smt2                                                                         |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled7923.smt2                                                                          |1200.034s  |1200.034s  |   0.000s  | 0.0%|
|scrambled80728.smt2                                                                         |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled82241.smt2                                                                         |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled85895.smt2                                                                         |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled91241.smt2                                                                         |1200.065s  |1200.065s  |   0.000s  | 0.0%|
|scrambled94319.smt2                                                                         |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled94768.smt2                                                                         |1200.112s  |1200.112s  |   0.000s  | 0.0%|
</details>
