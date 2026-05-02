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
Job tag: cvc5-partition-threads-4-test
Runner: rise-runner-2
cvc5 repo: cvc5/cvc5
cvc5 commit: e7e5bb6ea37ae6122da5c4f165b73c87089be765
cvc5 branch: main
cvc5 mode: partition
cvc5 portfolio mode: graduated
cvc5 portfolio strategies: "decision-scatter decision-cube"
cvc5 partition budget: 4
cvc5 partitioning options: "--partition-when=tlimit --partition-start-time=3 --partition-time-interval=0.1 --partition-check=standard"
cvc5 portfolio options: ""
cvc5 solver options: ""
cvc5 solver jobs: 4
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
Job tag: cvc5-partition-threads-4-test
Runner: rise-runner-2
cvc5 repo: cvc5/cvc5
cvc5 commit: e7e5bb6ea37ae6122da5c4f165b73c87089be765
cvc5 branch: main
cvc5 mode: partition
cvc5 portfolio mode: graduated
cvc5 portfolio strategies: "decision-scatter decision-cube"
cvc5 partition budget: 4
cvc5 partitioning options: "--partition-when=tlimit --partition-start-time=3 --partition-time-interval=0.1 --partition-check=standard"
cvc5 portfolio options: ""
cvc5 solver options: ""
cvc5 solver jobs: 4
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
|scrambled102166.smt2                                                                        |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled32836.smt2                                                                        |   0.044s |4008.0KiB|
|scrambled75189.smt2                                                                        |   0.043s |4324.0KiB|
|scrambled128874.smt2                                                                       |   0.043s |4368.0KiB|
|scrambled65181.smt2                                                                        |   0.042s |3988.0KiB|
|scrambled79867.smt2                                                                        |   0.041s |3880.0KiB|
|scrambled128128.smt2                                                                       |   0.034s |3484.0KiB|
|scrambled118793.smt2                                                                       |   0.033s |3388.0KiB|
|scrambled79766.smt2                                                                        |   0.033s |3444.0KiB|
|scrambled19335.smt2                                                                        |   0.032s |3432.0KiB|
|scrambled43577.smt2                                                                        |   0.031s |3336.0KiB|
|scrambled12042.smt2                                                                        |   0.031s |3540.0KiB|
|scrambled4299.smt2                                                                         |   0.030s |3348.0KiB|
|scrambled55680.smt2                                                                        |   0.030s |3628.0KiB|
|scrambled131241.smt2                                                                       |   0.030s |3420.0KiB|
|scrambled111627.smt2                                                                       |   0.029s |3208.0KiB|
|scrambled125827.smt2                                                                       |   0.029s |3428.0KiB|
|scrambled107826.smt2                                                                       |   0.029s |3936.0KiB|
|scrambled107115.smt2                                                                       |   0.029s |3596.0KiB|
|scrambled125888.smt2                                                                       |   0.029s |3436.0KiB|
|scrambled7741.smt2                                                                         |   0.028s |3792.0KiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled32836.smt2                                                                        |   0.044s |4008.0KiB|
|scrambled75189.smt2                                                                        |   0.043s |4324.0KiB|
|scrambled128874.smt2                                                                       |   0.043s |4368.0KiB|
|scrambled65181.smt2                                                                        |   0.042s |3988.0KiB|
|scrambled79867.smt2                                                                        |   0.041s |3880.0KiB|
|scrambled128128.smt2                                                                       |   0.034s |3484.0KiB|
|scrambled118793.smt2                                                                       |   0.033s |3388.0KiB|
|scrambled79766.smt2                                                                        |   0.033s |3444.0KiB|
|scrambled19335.smt2                                                                        |   0.032s |3432.0KiB|
|scrambled43577.smt2                                                                        |   0.031s |3336.0KiB|
|scrambled12042.smt2                                                                        |   0.031s |3540.0KiB|
|scrambled4299.smt2                                                                         |   0.030s |3348.0KiB|
|scrambled55680.smt2                                                                        |   0.030s |3628.0KiB|
|scrambled131241.smt2                                                                       |   0.030s |3420.0KiB|
|scrambled111627.smt2                                                                       |   0.029s |3208.0KiB|
|scrambled125827.smt2                                                                       |   0.029s |3428.0KiB|
|scrambled107826.smt2                                                                       |   0.029s |3936.0KiB|
|scrambled107115.smt2                                                                       |   0.029s |3596.0KiB|
|scrambled125888.smt2                                                                       |   0.029s |3436.0KiB|
|scrambled7741.smt2                                                                         |   0.028s |3792.0KiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |3888.0KiB|3888.0KiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |4432.0KiB|4432.0KiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |3596.0KiB|3596.0KiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |3936.0KiB|3936.0KiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |3992.0KiB|3992.0KiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |3208.0KiB|3208.0KiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |3388.0KiB|3388.0KiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3920.0KiB|3920.0KiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |3540.0KiB|3540.0KiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |3428.0KiB|3428.0KiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |3436.0KiB|3436.0KiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |3484.0KiB|3484.0KiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |3204.0KiB|3204.0KiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4368.0KiB|4368.0KiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |3420.0KiB|3420.0KiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |3708.0KiB|3708.0KiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |3432.0KiB|3432.0KiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |3328.0KiB|3328.0KiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |3180.0KiB|3180.0KiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |3320.0KiB|3320.0KiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |3888.0KiB|3888.0KiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |4432.0KiB|4432.0KiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |3596.0KiB|3596.0KiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |3936.0KiB|3936.0KiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |3992.0KiB|3992.0KiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |3208.0KiB|3208.0KiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |3388.0KiB|3388.0KiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3920.0KiB|3920.0KiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |3540.0KiB|3540.0KiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |3428.0KiB|3428.0KiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |3436.0KiB|3436.0KiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |3484.0KiB|3484.0KiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |3204.0KiB|3204.0KiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4368.0KiB|4368.0KiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |3420.0KiB|3420.0KiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |3708.0KiB|3708.0KiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |3432.0KiB|3432.0KiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |3328.0KiB|3328.0KiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |3180.0KiB|3180.0KiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |3320.0KiB|3320.0KiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |3888.0KiB|3888.0KiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |4432.0KiB|4432.0KiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |3596.0KiB|3596.0KiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |3936.0KiB|3936.0KiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |3992.0KiB|3992.0KiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |3208.0KiB|3208.0KiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |3388.0KiB|3388.0KiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3920.0KiB|3920.0KiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |3540.0KiB|3540.0KiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |3428.0KiB|3428.0KiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |3436.0KiB|3436.0KiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |3484.0KiB|3484.0KiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |3204.0KiB|3204.0KiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4368.0KiB|4368.0KiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |3420.0KiB|3420.0KiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |3708.0KiB|3708.0KiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |3432.0KiB|3432.0KiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |3328.0KiB|3328.0KiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |3180.0KiB|3180.0KiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |3320.0KiB|3320.0KiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |3888.0KiB|3888.0KiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |4432.0KiB|4432.0KiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |3596.0KiB|3596.0KiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |3936.0KiB|3936.0KiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |3992.0KiB|3992.0KiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |3208.0KiB|3208.0KiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |3388.0KiB|3388.0KiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3920.0KiB|3920.0KiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |3540.0KiB|3540.0KiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |3428.0KiB|3428.0KiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |3436.0KiB|3436.0KiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |3484.0KiB|3484.0KiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |3204.0KiB|3204.0KiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |4368.0KiB|4368.0KiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |3420.0KiB|3420.0KiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |3708.0KiB|3708.0KiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |3432.0KiB|3432.0KiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |3328.0KiB|3328.0KiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |3180.0KiB|3180.0KiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |3320.0KiB|3320.0KiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled45952.smt2                                                                        |   0.020s |4444.0KiB|
|scrambled103783.smt2                                                                       |   0.023s |4432.0KiB|
|scrambled128874.smt2                                                                       |   0.043s |4368.0KiB|
|scrambled75189.smt2                                                                        |   0.043s |4324.0KiB|
|scrambled68944.smt2                                                                        |   0.022s |4192.0KiB|
|scrambled94658.smt2                                                                        |   0.023s |4164.0KiB|
|scrambled72668.smt2                                                                        |   0.019s |4084.0KiB|
|scrambled32836.smt2                                                                        |   0.044s |4008.0KiB|
|scrambled108840.smt2                                                                       |   0.027s |3992.0KiB|
|scrambled65181.smt2                                                                        |   0.042s |3988.0KiB|
|scrambled59713.smt2                                                                        |   0.027s |3940.0KiB|
|scrambled107826.smt2                                                                       |   0.029s |3936.0KiB|
|scrambled119331.smt2                                                                       |   0.023s |3920.0KiB|
|scrambled95803.smt2                                                                        |   0.021s |3916.0KiB|
|scrambled102166.smt2                                                                       |   0.026s |3888.0KiB|
|scrambled79867.smt2                                                                        |   0.041s |3880.0KiB|
|scrambled40621.smt2                                                                        |   0.025s |3860.0KiB|
|scrambled79760.smt2                                                                        |   0.024s |3828.0KiB|
|scrambled7741.smt2                                                                         |   0.028s |3792.0KiB|
|scrambled39514.smt2                                                                        |   0.022s |3784.0KiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled45952.smt2                                                                        |   0.020s |4444.0KiB|
|scrambled103783.smt2                                                                       |   0.023s |4432.0KiB|
|scrambled128874.smt2                                                                       |   0.043s |4368.0KiB|
|scrambled75189.smt2                                                                        |   0.043s |4324.0KiB|
|scrambled68944.smt2                                                                        |   0.022s |4192.0KiB|
|scrambled94658.smt2                                                                        |   0.023s |4164.0KiB|
|scrambled72668.smt2                                                                        |   0.019s |4084.0KiB|
|scrambled32836.smt2                                                                        |   0.044s |4008.0KiB|
|scrambled108840.smt2                                                                       |   0.027s |3992.0KiB|
|scrambled65181.smt2                                                                        |   0.042s |3988.0KiB|
|scrambled59713.smt2                                                                        |   0.027s |3940.0KiB|
|scrambled107826.smt2                                                                       |   0.029s |3936.0KiB|
|scrambled119331.smt2                                                                       |   0.023s |3920.0KiB|
|scrambled95803.smt2                                                                        |   0.021s |3916.0KiB|
|scrambled102166.smt2                                                                       |   0.026s |3888.0KiB|
|scrambled79867.smt2                                                                        |   0.041s |3880.0KiB|
|scrambled40621.smt2                                                                        |   0.025s |3860.0KiB|
|scrambled79760.smt2                                                                        |   0.024s |3828.0KiB|
|scrambled7741.smt2                                                                         |   0.028s |3792.0KiB|
|scrambled39514.smt2                                                                        |   0.022s |3784.0KiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |   0.023s  |   0.023s  |   0.000s  | 0.0%|
</details>
