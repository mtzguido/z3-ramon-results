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
Job tag: cvc5-parallel
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
Job tag: cvc5-parallel
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
|scrambled20101.smt2                                                                        |   0.052s |3984.0KiB|
|scrambled25238.smt2                                                                        |   0.051s |4284.0KiB|
|scrambled103783.smt2                                                                       |   0.051s |3980.0KiB|
|scrambled3854.smt2                                                                         |   0.048s |4276.0KiB|
|scrambled79867.smt2                                                                        |   0.042s |4092.0KiB|
|scrambled40621.smt2                                                                        |   0.042s |4124.0KiB|
|scrambled108840.smt2                                                                       |   0.042s |3744.0KiB|
|scrambled128128.smt2                                                                       |   0.042s |3764.0KiB|
|scrambled32836.smt2                                                                        |   0.042s |4332.0KiB|
|scrambled75189.smt2                                                                        |   0.040s |3692.0KiB|
|scrambled128874.smt2                                                                       |   0.040s |4116.0KiB|
|scrambled4299.smt2                                                                         |   0.039s |4024.0KiB|
|scrambled59713.smt2                                                                        |   0.038s |4060.0KiB|
|scrambled65181.smt2                                                                        |   0.038s |3636.0KiB|
|scrambled125888.smt2                                                                       |   0.038s |3796.0KiB|
|scrambled118793.smt2                                                                       |   0.037s |4208.0KiB|
|scrambled45952.smt2                                                                        |   0.037s |4336.0KiB|
|scrambled125827.smt2                                                                       |   0.037s |4220.0KiB|
|scrambled7741.smt2                                                                         |   0.036s |3820.0KiB|
|scrambled43577.smt2                                                                        |   0.036s |4144.0KiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled20101.smt2                                                                        |   0.052s |3984.0KiB|
|scrambled25238.smt2                                                                        |   0.051s |4284.0KiB|
|scrambled103783.smt2                                                                       |   0.051s |3980.0KiB|
|scrambled3854.smt2                                                                         |   0.048s |4276.0KiB|
|scrambled79867.smt2                                                                        |   0.042s |4092.0KiB|
|scrambled40621.smt2                                                                        |   0.042s |4124.0KiB|
|scrambled108840.smt2                                                                       |   0.042s |3744.0KiB|
|scrambled128128.smt2                                                                       |   0.042s |3764.0KiB|
|scrambled32836.smt2                                                                        |   0.042s |4332.0KiB|
|scrambled75189.smt2                                                                        |   0.040s |3692.0KiB|
|scrambled128874.smt2                                                                       |   0.040s |4116.0KiB|
|scrambled4299.smt2                                                                         |   0.039s |4024.0KiB|
|scrambled59713.smt2                                                                        |   0.038s |4060.0KiB|
|scrambled65181.smt2                                                                        |   0.038s |3636.0KiB|
|scrambled125888.smt2                                                                       |   0.038s |3796.0KiB|
|scrambled118793.smt2                                                                       |   0.037s |4208.0KiB|
|scrambled45952.smt2                                                                        |   0.037s |4336.0KiB|
|scrambled125827.smt2                                                                       |   0.037s |4220.0KiB|
|scrambled7741.smt2                                                                         |   0.036s |3820.0KiB|
|scrambled43577.smt2                                                                        |   0.036s |4144.0KiB|
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
|scrambled55777.smt2                                                                        |   0.035s |4348.0KiB|
|scrambled45952.smt2                                                                        |   0.037s |4336.0KiB|
|scrambled4198.smt2                                                                         |   0.033s |4336.0KiB|
|scrambled102166.smt2                                                                       |   0.025s |4336.0KiB|
|scrambled32836.smt2                                                                        |   0.042s |4332.0KiB|
|scrambled72668.smt2                                                                        |   0.034s |4324.0KiB|
|scrambled25238.smt2                                                                        |   0.051s |4284.0KiB|
|scrambled3854.smt2                                                                         |   0.048s |4276.0KiB|
|scrambled107826.smt2                                                                       |   0.028s |4236.0KiB|
|scrambled12042.smt2                                                                        |   0.028s |4232.0KiB|
|scrambled125827.smt2                                                                       |   0.037s |4220.0KiB|
|scrambled118793.smt2                                                                       |   0.037s |4208.0KiB|
|scrambled119331.smt2                                                                       |   0.036s |4204.0KiB|
|scrambled43577.smt2                                                                        |   0.036s |4144.0KiB|
|scrambled40621.smt2                                                                        |   0.042s |4124.0KiB|
|scrambled61922.smt2                                                                        |   0.035s |4124.0KiB|
|scrambled128874.smt2                                                                       |   0.040s |4116.0KiB|
|scrambled1417.smt2                                                                         |   0.025s |4116.0KiB|
|scrambled27843.smt2                                                                        |   0.034s |4108.0KiB|
|scrambled79867.smt2                                                                        |   0.042s |4092.0KiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled55777.smt2                                                                        |   0.035s |4348.0KiB|
|scrambled45952.smt2                                                                        |   0.037s |4336.0KiB|
|scrambled4198.smt2                                                                         |   0.033s |4336.0KiB|
|scrambled102166.smt2                                                                       |   0.025s |4336.0KiB|
|scrambled32836.smt2                                                                        |   0.042s |4332.0KiB|
|scrambled72668.smt2                                                                        |   0.034s |4324.0KiB|
|scrambled25238.smt2                                                                        |   0.051s |4284.0KiB|
|scrambled3854.smt2                                                                         |   0.048s |4276.0KiB|
|scrambled107826.smt2                                                                       |   0.028s |4236.0KiB|
|scrambled12042.smt2                                                                        |   0.028s |4232.0KiB|
|scrambled125827.smt2                                                                       |   0.037s |4220.0KiB|
|scrambled118793.smt2                                                                       |   0.037s |4208.0KiB|
|scrambled119331.smt2                                                                       |   0.036s |4204.0KiB|
|scrambled43577.smt2                                                                        |   0.036s |4144.0KiB|
|scrambled40621.smt2                                                                        |   0.042s |4124.0KiB|
|scrambled61922.smt2                                                                        |   0.035s |4124.0KiB|
|scrambled128874.smt2                                                                       |   0.040s |4116.0KiB|
|scrambled1417.smt2                                                                         |   0.025s |4116.0KiB|
|scrambled27843.smt2                                                                        |   0.034s |4108.0KiB|
|scrambled79867.smt2                                                                        |   0.042s |4092.0KiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>
