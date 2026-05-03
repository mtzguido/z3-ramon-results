Comparing data and data


# SUMMARY
- LHS tests = 44
- RHS tests = 44
- LHS success = 0  (0.0%)
- RHS success = 0  (0.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for cvc5
-
Job description: 
Job tag: cvc5-test
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
cvc5 timeout: 10
cvc5 inputs: inputs/smt_comp_2025_parallel/QF_LIA
cvc5 commit message: Alethe add INTS_LOG2 and INTS_ISPOW2 (#12626)

These two operators do appear in the proofs of bit-vector benchmarks.

Co-authored-by: Haniel Barbosa <hanielbbarbosa@gmail.com>

</pre>
# RHS
<pre>
Ramon benchmark for cvc5
-
Job description: 
Job tag: cvc5-test
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
cvc5 timeout: 10
cvc5 inputs: inputs/smt_comp_2025_parallel/QF_LIA
cvc5 commit message: Alethe add INTS_LOG2 and INTS_ISPOW2 (#12626)

These two operators do appear in the proofs of bit-vector benchmarks.

Co-authored-by: Haniel Barbosa <hanielbbarbosa@gmail.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled75189.smt2                                                                        |   0.042s |3064.0KiB|
|scrambled128874.smt2                                                                       |   0.042s |2948.0KiB|
|scrambled79867.smt2                                                                        |   0.041s |3356.0KiB|
|scrambled32836.smt2                                                                        |   0.040s |3100.0KiB|
|scrambled102166.smt2                                                                       |   0.037s |3088.0KiB|
|scrambled1417.smt2                                                                         |   0.036s |3044.0KiB|
|scrambled79766.smt2                                                                        |   0.034s |3208.0KiB|
|scrambled3854.smt2                                                                         |   0.034s |3472.0KiB|
|scrambled68944.smt2                                                                        |   0.023s |2832.0KiB|
|scrambled118793.smt2                                                                       |   0.023s |2992.0KiB|
|scrambled79760.smt2                                                                        |   0.023s |3108.0KiB|
|scrambled111627.smt2                                                                       |   0.023s |2816.0KiB|
|scrambled51053.smt2                                                                        |   0.023s |3120.0KiB|
|scrambled43577.smt2                                                                        |   0.022s |2796.0KiB|
|scrambled95803.smt2                                                                        |   0.022s |2856.0KiB|
|scrambled45952.smt2                                                                        |   0.022s |2868.0KiB|
|scrambled131241.smt2                                                                       |   0.022s |2572.0KiB|
|scrambled107115.smt2                                                                       |   0.022s |2588.0KiB|
|scrambled125888.smt2                                                                       |   0.022s |2932.0KiB|
|scrambled7741.smt2                                                                         |   0.021s |3060.0KiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled75189.smt2                                                                        |   0.042s |3064.0KiB|
|scrambled128874.smt2                                                                       |   0.042s |2948.0KiB|
|scrambled79867.smt2                                                                        |   0.041s |3356.0KiB|
|scrambled32836.smt2                                                                        |   0.040s |3100.0KiB|
|scrambled102166.smt2                                                                       |   0.037s |3088.0KiB|
|scrambled1417.smt2                                                                         |   0.036s |3044.0KiB|
|scrambled79766.smt2                                                                        |   0.034s |3208.0KiB|
|scrambled3854.smt2                                                                         |   0.034s |3472.0KiB|
|scrambled68944.smt2                                                                        |   0.023s |2832.0KiB|
|scrambled118793.smt2                                                                       |   0.023s |2992.0KiB|
|scrambled79760.smt2                                                                        |   0.023s |3108.0KiB|
|scrambled111627.smt2                                                                       |   0.023s |2816.0KiB|
|scrambled51053.smt2                                                                        |   0.023s |3120.0KiB|
|scrambled43577.smt2                                                                        |   0.022s |2796.0KiB|
|scrambled95803.smt2                                                                        |   0.022s |2856.0KiB|
|scrambled45952.smt2                                                                        |   0.022s |2868.0KiB|
|scrambled131241.smt2                                                                       |   0.022s |2572.0KiB|
|scrambled107115.smt2                                                                       |   0.022s |2588.0KiB|
|scrambled125888.smt2                                                                       |   0.022s |2932.0KiB|
|scrambled7741.smt2                                                                         |   0.021s |3060.0KiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled3854.smt2                                                                         |   0.034s |3472.0KiB|
|scrambled20101.smt2                                                                        |   0.019s |3388.0KiB|
|scrambled79867.smt2                                                                        |   0.041s |3356.0KiB|
|scrambled72668.smt2                                                                        |   0.016s |3280.0KiB|
|scrambled128732.smt2                                                                       |   0.018s |3276.0KiB|
|scrambled44911.smt2                                                                        |   0.014s |3236.0KiB|
|scrambled79766.smt2                                                                        |   0.034s |3208.0KiB|
|scrambled27843.smt2                                                                        |   0.021s |3160.0KiB|
|scrambled107826.smt2                                                                       |   0.015s |3136.0KiB|
|scrambled51053.smt2                                                                        |   0.023s |3120.0KiB|
|scrambled128128.smt2                                                                       |   0.016s |3116.0KiB|
|scrambled79760.smt2                                                                        |   0.023s |3108.0KiB|
|scrambled32836.smt2                                                                        |   0.040s |3100.0KiB|
|scrambled102166.smt2                                                                       |   0.037s |3088.0KiB|
|scrambled55777.smt2                                                                        |   0.014s |3072.0KiB|
|scrambled75189.smt2                                                                        |   0.042s |3064.0KiB|
|scrambled7741.smt2                                                                         |   0.021s |3060.0KiB|
|scrambled119331.smt2                                                                       |   0.021s |3056.0KiB|
|scrambled19335.smt2                                                                        |   0.014s |3056.0KiB|
|scrambled1417.smt2                                                                         |   0.036s |3044.0KiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled3854.smt2                                                                         |   0.034s |3472.0KiB|
|scrambled20101.smt2                                                                        |   0.019s |3388.0KiB|
|scrambled79867.smt2                                                                        |   0.041s |3356.0KiB|
|scrambled72668.smt2                                                                        |   0.016s |3280.0KiB|
|scrambled128732.smt2                                                                       |   0.018s |3276.0KiB|
|scrambled44911.smt2                                                                        |   0.014s |3236.0KiB|
|scrambled79766.smt2                                                                        |   0.034s |3208.0KiB|
|scrambled27843.smt2                                                                        |   0.021s |3160.0KiB|
|scrambled107826.smt2                                                                       |   0.015s |3136.0KiB|
|scrambled51053.smt2                                                                        |   0.023s |3120.0KiB|
|scrambled128128.smt2                                                                       |   0.016s |3116.0KiB|
|scrambled79760.smt2                                                                        |   0.023s |3108.0KiB|
|scrambled32836.smt2                                                                        |   0.040s |3100.0KiB|
|scrambled102166.smt2                                                                       |   0.037s |3088.0KiB|
|scrambled55777.smt2                                                                        |   0.014s |3072.0KiB|
|scrambled75189.smt2                                                                        |   0.042s |3064.0KiB|
|scrambled7741.smt2                                                                         |   0.021s |3060.0KiB|
|scrambled119331.smt2                                                                       |   0.021s |3056.0KiB|
|scrambled19335.smt2                                                                        |   0.014s |3056.0KiB|
|scrambled1417.smt2                                                                         |   0.036s |3044.0KiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>
