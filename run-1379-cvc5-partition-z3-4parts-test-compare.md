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
Job tag: cvc5-partition-z3-4parts-test
Runner: rise-runner-2
cvc5 repo: cvc5/cvc5
cvc5 commit: f1618718655df0cfff843c813f96f6b26f544baf
cvc5 branch: main
cvc5 mode: partition
cvc5 portfolio mode: graduated
cvc5 portfolio strategies: "decision-cube"
cvc5 partition budget: 4
cvc5 partitioning options: "--partition-when=tlimit --partition-start-time=3 --partition-time-interval=0.1"
cvc5 native portfolio options: ""
cvc5 solver options: ""
cvc5 solver jobs: 4
cvc5 timeout: 1
cvc5 inputs: inputs/smt_comp_2025_parallel/QF_LIA
cvc5 commit message: random: Refactor to use Mersenne-Twister engine. (#12612)

This refactors the random number generator to be based on the STL
Mersenne-Twister engine. Its interface is now expanded with templated
functions to allow more flexibility in terms of types.

</pre>
# RHS
<pre>
Ramon benchmark for cvc5
-
Job description: 
Job tag: cvc5-partition-z3-4parts-test
Runner: rise-runner-2
cvc5 repo: cvc5/cvc5
cvc5 commit: f1618718655df0cfff843c813f96f6b26f544baf
cvc5 branch: main
cvc5 mode: partition
cvc5 portfolio mode: graduated
cvc5 portfolio strategies: "decision-cube"
cvc5 partition budget: 4
cvc5 partitioning options: "--partition-when=tlimit --partition-start-time=3 --partition-time-interval=0.1"
cvc5 native portfolio options: ""
cvc5 solver options: ""
cvc5 solver jobs: 4
cvc5 timeout: 1
cvc5 inputs: inputs/smt_comp_2025_parallel/QF_LIA
cvc5 commit message: random: Refactor to use Mersenne-Twister engine. (#12612)

This refactors the random number generator to be based on the STL
Mersenne-Twister engine. Its interface is now expanded with templated
functions to allow more flexibility in terms of types.

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |   0.021s  |   0.021s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |   0.021s  |   0.021s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |   0.021s  |   0.021s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |   0.021s  |   0.021s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled75189.smt2                                                                        |   0.041s |2632.0KiB|
|scrambled32836.smt2                                                                        |   0.041s |2568.0KiB|
|scrambled4299.smt2                                                                         |   0.040s |3112.0KiB|
|scrambled125827.smt2                                                                       |   0.040s |2808.0KiB|
|scrambled108840.smt2                                                                       |   0.040s |3120.0KiB|
|scrambled79867.smt2                                                                        |   0.039s |2492.0KiB|
|scrambled128874.smt2                                                                       |   0.037s |2884.0KiB|
|scrambled125888.smt2                                                                       |   0.037s |2628.0KiB|
|scrambled65181.smt2                                                                        |   0.036s |2772.0KiB|
|scrambled45952.smt2                                                                        |   0.034s |2776.0KiB|
|scrambled59713.smt2                                                                        |   0.033s |2516.0KiB|
|scrambled12042.smt2                                                                        |   0.033s |2648.0KiB|
|scrambled7741.smt2                                                                         |   0.030s |2684.0KiB|
|scrambled55680.smt2                                                                        |   0.030s |2640.0KiB|
|scrambled51053.smt2                                                                        |   0.029s |2448.0KiB|
|scrambled128128.smt2                                                                       |   0.027s |2240.0KiB|
|scrambled19335.smt2                                                                        |   0.026s |2360.0KiB|
|scrambled107826.smt2                                                                       |   0.025s |2376.0KiB|
|scrambled107115.smt2                                                                       |   0.025s |2536.0KiB|
|scrambled102166.smt2                                                                       |   0.024s |2976.0KiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled75189.smt2                                                                        |   0.041s |2632.0KiB|
|scrambled32836.smt2                                                                        |   0.041s |2568.0KiB|
|scrambled4299.smt2                                                                         |   0.040s |3112.0KiB|
|scrambled125827.smt2                                                                       |   0.040s |2808.0KiB|
|scrambled108840.smt2                                                                       |   0.040s |3120.0KiB|
|scrambled79867.smt2                                                                        |   0.039s |2492.0KiB|
|scrambled128874.smt2                                                                       |   0.037s |2884.0KiB|
|scrambled125888.smt2                                                                       |   0.037s |2628.0KiB|
|scrambled65181.smt2                                                                        |   0.036s |2772.0KiB|
|scrambled45952.smt2                                                                        |   0.034s |2776.0KiB|
|scrambled59713.smt2                                                                        |   0.033s |2516.0KiB|
|scrambled12042.smt2                                                                        |   0.033s |2648.0KiB|
|scrambled7741.smt2                                                                         |   0.030s |2684.0KiB|
|scrambled55680.smt2                                                                        |   0.030s |2640.0KiB|
|scrambled51053.smt2                                                                        |   0.029s |2448.0KiB|
|scrambled128128.smt2                                                                       |   0.027s |2240.0KiB|
|scrambled19335.smt2                                                                        |   0.026s |2360.0KiB|
|scrambled107826.smt2                                                                       |   0.025s |2376.0KiB|
|scrambled107115.smt2                                                                       |   0.025s |2536.0KiB|
|scrambled102166.smt2                                                                       |   0.024s |2976.0KiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |2976.0KiB|2976.0KiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |2564.0KiB|2564.0KiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |2536.0KiB|2536.0KiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |2376.0KiB|2376.0KiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |3120.0KiB|3120.0KiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |2960.0KiB|2960.0KiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |2576.0KiB|2576.0KiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |2460.0KiB|2460.0KiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |2648.0KiB|2648.0KiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |2808.0KiB|2808.0KiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |2628.0KiB|2628.0KiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2240.0KiB|2240.0KiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2780.0KiB|2780.0KiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2884.0KiB|2884.0KiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2488.0KiB|2488.0KiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |3076.0KiB|3076.0KiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |2360.0KiB|2360.0KiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |2672.0KiB|2672.0KiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |2764.0KiB|2764.0KiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |2920.0KiB|2920.0KiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |2976.0KiB|2976.0KiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |2564.0KiB|2564.0KiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |2536.0KiB|2536.0KiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |2376.0KiB|2376.0KiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |3120.0KiB|3120.0KiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |2960.0KiB|2960.0KiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |2576.0KiB|2576.0KiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |2460.0KiB|2460.0KiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |2648.0KiB|2648.0KiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |2808.0KiB|2808.0KiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |2628.0KiB|2628.0KiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2240.0KiB|2240.0KiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2780.0KiB|2780.0KiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2884.0KiB|2884.0KiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2488.0KiB|2488.0KiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |3076.0KiB|3076.0KiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |2360.0KiB|2360.0KiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |2672.0KiB|2672.0KiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |2764.0KiB|2764.0KiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |2920.0KiB|2920.0KiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |2976.0KiB|2976.0KiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |2564.0KiB|2564.0KiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |2536.0KiB|2536.0KiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |2376.0KiB|2376.0KiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |3120.0KiB|3120.0KiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |2960.0KiB|2960.0KiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |2576.0KiB|2576.0KiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |2460.0KiB|2460.0KiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |2648.0KiB|2648.0KiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |2808.0KiB|2808.0KiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |2628.0KiB|2628.0KiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2240.0KiB|2240.0KiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2780.0KiB|2780.0KiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2884.0KiB|2884.0KiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2488.0KiB|2488.0KiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |3076.0KiB|3076.0KiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |2360.0KiB|2360.0KiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |2672.0KiB|2672.0KiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |2764.0KiB|2764.0KiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |2920.0KiB|2920.0KiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |2976.0KiB|2976.0KiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |2564.0KiB|2564.0KiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |2536.0KiB|2536.0KiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |2376.0KiB|2376.0KiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |3120.0KiB|3120.0KiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |2960.0KiB|2960.0KiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |2576.0KiB|2576.0KiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |2460.0KiB|2460.0KiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |2648.0KiB|2648.0KiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |2808.0KiB|2808.0KiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |2628.0KiB|2628.0KiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2240.0KiB|2240.0KiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2780.0KiB|2780.0KiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |2884.0KiB|2884.0KiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |2488.0KiB|2488.0KiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |3076.0KiB|3076.0KiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |2360.0KiB|2360.0KiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |2672.0KiB|2672.0KiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |2764.0KiB|2764.0KiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |2920.0KiB|2920.0KiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled43577.smt2                                                                        |   0.018s |3336.0KiB|
|scrambled108840.smt2                                                                       |   0.040s |3120.0KiB|
|scrambled4299.smt2                                                                         |   0.040s |3112.0KiB|
|scrambled40621.smt2                                                                        |   0.020s |3104.0KiB|
|scrambled44911.smt2                                                                        |   0.022s |3100.0KiB|
|scrambled1417.smt2                                                                         |   0.021s |3076.0KiB|
|scrambled95803.smt2                                                                        |   0.023s |3016.0KiB|
|scrambled68944.smt2                                                                        |   0.022s |3016.0KiB|
|scrambled102166.smt2                                                                       |   0.024s |2976.0KiB|
|scrambled111627.smt2                                                                       |   0.019s |2960.0KiB|
|scrambled94658.smt2                                                                        |   0.022s |2940.0KiB|
|scrambled4198.smt2                                                                         |   0.022s |2932.0KiB|
|scrambled27843.smt2                                                                        |   0.021s |2920.0KiB|
|scrambled128874.smt2                                                                       |   0.037s |2884.0KiB|
|scrambled61922.smt2                                                                        |   0.021s |2816.0KiB|
|scrambled125827.smt2                                                                       |   0.040s |2808.0KiB|
|scrambled128732.smt2                                                                       |   0.022s |2780.0KiB|
|scrambled45952.smt2                                                                        |   0.034s |2776.0KiB|
|scrambled65181.smt2                                                                        |   0.036s |2772.0KiB|
|scrambled25238.smt2                                                                        |   0.022s |2764.0KiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled43577.smt2                                                                        |   0.018s |3336.0KiB|
|scrambled108840.smt2                                                                       |   0.040s |3120.0KiB|
|scrambled4299.smt2                                                                         |   0.040s |3112.0KiB|
|scrambled40621.smt2                                                                        |   0.020s |3104.0KiB|
|scrambled44911.smt2                                                                        |   0.022s |3100.0KiB|
|scrambled1417.smt2                                                                         |   0.021s |3076.0KiB|
|scrambled95803.smt2                                                                        |   0.023s |3016.0KiB|
|scrambled68944.smt2                                                                        |   0.022s |3016.0KiB|
|scrambled102166.smt2                                                                       |   0.024s |2976.0KiB|
|scrambled111627.smt2                                                                       |   0.019s |2960.0KiB|
|scrambled94658.smt2                                                                        |   0.022s |2940.0KiB|
|scrambled4198.smt2                                                                         |   0.022s |2932.0KiB|
|scrambled27843.smt2                                                                        |   0.021s |2920.0KiB|
|scrambled128874.smt2                                                                       |   0.037s |2884.0KiB|
|scrambled61922.smt2                                                                        |   0.021s |2816.0KiB|
|scrambled125827.smt2                                                                       |   0.040s |2808.0KiB|
|scrambled128732.smt2                                                                       |   0.022s |2780.0KiB|
|scrambled45952.smt2                                                                        |   0.034s |2776.0KiB|
|scrambled65181.smt2                                                                        |   0.036s |2772.0KiB|
|scrambled25238.smt2                                                                        |   0.022s |2764.0KiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |   0.022s  |   0.022s  |   0.000s  | 0.0%|
</details>
