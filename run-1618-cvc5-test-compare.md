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
Job tag: cvc5-test
Runner: rise-runner-2
cvc5 repo: cvc5/cvc5
cvc5 commit: e7e5bb6ea37ae6122da5c4f165b73c87089be765
cvc5 branch: main
cvc5 mode: sequential
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
cvc5 mode: sequential
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
|scrambled102166.smt2                                                                        |  10.061s  |  10.061s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  10.043s  |  10.043s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  10.106s  |  10.106s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  10.082s  |  10.082s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  10.065s  |  10.065s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  10.067s  |  10.067s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  10.028s  |  10.028s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  10.046s  |  10.046s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  10.069s  |  10.069s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  10.039s  |  10.039s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  10.042s  |  10.042s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  10.057s  |  10.057s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  10.043s  |  10.043s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  10.046s  |  10.046s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  10.041s  |  10.041s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  10.031s  |  10.031s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  10.072s  |  10.072s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  10.037s  |  10.037s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  10.075s  |  10.075s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  10.094s  |  10.094s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  10.061s  |  10.061s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  10.043s  |  10.043s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  10.106s  |  10.106s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  10.082s  |  10.082s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  10.065s  |  10.065s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  10.067s  |  10.067s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  10.028s  |  10.028s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  10.046s  |  10.046s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  10.069s  |  10.069s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  10.039s  |  10.039s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  10.042s  |  10.042s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  10.057s  |  10.057s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  10.043s  |  10.043s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  10.046s  |  10.046s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  10.041s  |  10.041s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  10.031s  |  10.031s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  10.072s  |  10.072s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  10.037s  |  10.037s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  10.075s  |  10.075s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  10.094s  |  10.094s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  10.061s  |  10.061s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  10.043s  |  10.043s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  10.106s  |  10.106s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  10.082s  |  10.082s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  10.065s  |  10.065s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  10.067s  |  10.067s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  10.028s  |  10.028s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  10.046s  |  10.046s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  10.069s  |  10.069s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  10.039s  |  10.039s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  10.042s  |  10.042s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  10.057s  |  10.057s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  10.043s  |  10.043s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  10.046s  |  10.046s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  10.041s  |  10.041s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  10.031s  |  10.031s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  10.072s  |  10.072s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  10.037s  |  10.037s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  10.075s  |  10.075s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  10.094s  |  10.094s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  10.061s  |  10.061s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  10.043s  |  10.043s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  10.106s  |  10.106s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  10.082s  |  10.082s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  10.065s  |  10.065s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  10.067s  |  10.067s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  10.028s  |  10.028s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  10.046s  |  10.046s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  10.069s  |  10.069s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  10.039s  |  10.039s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  10.042s  |  10.042s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  10.057s  |  10.057s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  10.043s  |  10.043s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  10.046s  |  10.046s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  10.041s  |  10.041s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  10.031s  |  10.031s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  10.072s  |  10.072s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  10.037s  |  10.037s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  10.075s  |  10.075s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  10.094s  |  10.094s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled107115.smt2                                                                       |  10.106s |698.0MiB|
|scrambled75189.smt2                                                                        |  10.100s |520.0MiB|
|scrambled27843.smt2                                                                        |  10.094s |695.0MiB|
|scrambled79760.smt2                                                                        |  10.082s |474.0MiB|
|scrambled107826.smt2                                                                       |  10.082s |475.0MiB|
|scrambled43577.smt2                                                                        |  10.081s |484.0MiB|
|scrambled55680.smt2                                                                        |  10.076s |411.0MiB|
|scrambled25238.smt2                                                                        |  10.075s |253.0MiB|
|scrambled61922.smt2                                                                        |  10.072s |462.0MiB|
|scrambled19335.smt2                                                                        |  10.072s |468.0MiB|
|scrambled12042.smt2                                                                        |  10.069s |430.0MiB|
|scrambled94658.smt2                                                                        |  10.068s |430.0MiB|
|scrambled4198.smt2                                                                         |  10.068s |431.0MiB|
|scrambled111627.smt2                                                                       |  10.067s |487.0MiB|
|scrambled4299.smt2                                                                         |  10.066s |378.0MiB|
|scrambled108840.smt2                                                                       |  10.065s |383.0MiB|
|scrambled68944.smt2                                                                        |  10.063s |451.0MiB|
|scrambled102166.smt2                                                                       |  10.061s |385.0MiB|
|scrambled65181.smt2                                                                        |  10.061s |141.0MiB|
|scrambled40621.smt2                                                                        |  10.060s |313.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled107115.smt2                                                                       |  10.106s |698.0MiB|
|scrambled75189.smt2                                                                        |  10.100s |520.0MiB|
|scrambled27843.smt2                                                                        |  10.094s |695.0MiB|
|scrambled79760.smt2                                                                        |  10.082s |474.0MiB|
|scrambled107826.smt2                                                                       |  10.082s |475.0MiB|
|scrambled43577.smt2                                                                        |  10.081s |484.0MiB|
|scrambled55680.smt2                                                                        |  10.076s |411.0MiB|
|scrambled25238.smt2                                                                        |  10.075s |253.0MiB|
|scrambled61922.smt2                                                                        |  10.072s |462.0MiB|
|scrambled19335.smt2                                                                        |  10.072s |468.0MiB|
|scrambled12042.smt2                                                                        |  10.069s |430.0MiB|
|scrambled94658.smt2                                                                        |  10.068s |430.0MiB|
|scrambled4198.smt2                                                                         |  10.068s |431.0MiB|
|scrambled111627.smt2                                                                       |  10.067s |487.0MiB|
|scrambled4299.smt2                                                                         |  10.066s |378.0MiB|
|scrambled108840.smt2                                                                       |  10.065s |383.0MiB|
|scrambled68944.smt2                                                                        |  10.063s |451.0MiB|
|scrambled102166.smt2                                                                       |  10.061s |385.0MiB|
|scrambled65181.smt2                                                                        |  10.061s |141.0MiB|
|scrambled40621.smt2                                                                        |  10.060s |313.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |385.0MiB|385.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |140.0MiB|140.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |698.0MiB|698.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |475.0MiB|475.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |383.0MiB|383.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |487.0MiB|487.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |72.364MiB|72.364MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |230.0MiB|230.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |430.0MiB|430.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |77.956MiB|77.956MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |85.356MiB|85.356MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |241.0MiB|241.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |158.0MiB|158.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |156.0MiB|156.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |240.0MiB|240.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |65.416MiB|65.416MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |468.0MiB|468.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |87.264MiB|87.264MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |253.0MiB|253.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |695.0MiB|695.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |385.0MiB|385.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |140.0MiB|140.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |698.0MiB|698.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |475.0MiB|475.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |383.0MiB|383.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |487.0MiB|487.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |72.364MiB|72.364MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |230.0MiB|230.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |430.0MiB|430.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |77.956MiB|77.956MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |85.356MiB|85.356MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |241.0MiB|241.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |158.0MiB|158.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |156.0MiB|156.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |240.0MiB|240.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |65.416MiB|65.416MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |468.0MiB|468.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |87.264MiB|87.264MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |253.0MiB|253.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |695.0MiB|695.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |385.0MiB|385.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |140.0MiB|140.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |698.0MiB|698.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |475.0MiB|475.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |383.0MiB|383.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |487.0MiB|487.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |72.364MiB|72.364MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |230.0MiB|230.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |430.0MiB|430.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |77.956MiB|77.956MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |85.356MiB|85.356MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |241.0MiB|241.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |158.0MiB|158.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |156.0MiB|156.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |240.0MiB|240.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |65.416MiB|65.416MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |468.0MiB|468.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |87.264MiB|87.264MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |253.0MiB|253.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |695.0MiB|695.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |385.0MiB|385.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |140.0MiB|140.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |698.0MiB|698.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |475.0MiB|475.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |383.0MiB|383.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |487.0MiB|487.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |72.364MiB|72.364MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |230.0MiB|230.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |430.0MiB|430.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |77.956MiB|77.956MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |85.356MiB|85.356MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |241.0MiB|241.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |158.0MiB|158.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |156.0MiB|156.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |240.0MiB|240.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |65.416MiB|65.416MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |468.0MiB|468.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |87.264MiB|87.264MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |253.0MiB|253.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |695.0MiB|695.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled107115.smt2                                                                       |  10.106s |698.0MiB|
|scrambled27843.smt2                                                                        |  10.094s |695.0MiB|
|scrambled75189.smt2                                                                        |  10.100s |520.0MiB|
|scrambled111627.smt2                                                                       |  10.067s |487.0MiB|
|scrambled43577.smt2                                                                        |  10.081s |484.0MiB|
|scrambled107826.smt2                                                                       |  10.082s |475.0MiB|
|scrambled79760.smt2                                                                        |  10.082s |474.0MiB|
|scrambled19335.smt2                                                                        |  10.072s |468.0MiB|
|scrambled61922.smt2                                                                        |  10.072s |462.0MiB|
|scrambled68944.smt2                                                                        |  10.063s |451.0MiB|
|scrambled4198.smt2                                                                         |  10.068s |431.0MiB|
|scrambled12042.smt2                                                                        |  10.069s |430.0MiB|
|scrambled94658.smt2                                                                        |  10.068s |430.0MiB|
|scrambled55680.smt2                                                                        |  10.076s |411.0MiB|
|scrambled7741.smt2                                                                         |  10.053s |388.0MiB|
|scrambled102166.smt2                                                                       |  10.061s |385.0MiB|
|scrambled108840.smt2                                                                       |  10.065s |383.0MiB|
|scrambled4299.smt2                                                                         |  10.066s |378.0MiB|
|scrambled40621.smt2                                                                        |  10.060s |313.0MiB|
|scrambled51053.smt2                                                                        |  10.050s |256.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled107115.smt2                                                                       |  10.106s |698.0MiB|
|scrambled27843.smt2                                                                        |  10.094s |695.0MiB|
|scrambled75189.smt2                                                                        |  10.100s |520.0MiB|
|scrambled111627.smt2                                                                       |  10.067s |487.0MiB|
|scrambled43577.smt2                                                                        |  10.081s |484.0MiB|
|scrambled107826.smt2                                                                       |  10.082s |475.0MiB|
|scrambled79760.smt2                                                                        |  10.082s |474.0MiB|
|scrambled19335.smt2                                                                        |  10.072s |468.0MiB|
|scrambled61922.smt2                                                                        |  10.072s |462.0MiB|
|scrambled68944.smt2                                                                        |  10.063s |451.0MiB|
|scrambled4198.smt2                                                                         |  10.068s |431.0MiB|
|scrambled12042.smt2                                                                        |  10.069s |430.0MiB|
|scrambled94658.smt2                                                                        |  10.068s |430.0MiB|
|scrambled55680.smt2                                                                        |  10.076s |411.0MiB|
|scrambled7741.smt2                                                                         |  10.053s |388.0MiB|
|scrambled102166.smt2                                                                       |  10.061s |385.0MiB|
|scrambled108840.smt2                                                                       |  10.065s |383.0MiB|
|scrambled4299.smt2                                                                         |  10.066s |378.0MiB|
|scrambled40621.smt2                                                                        |  10.060s |313.0MiB|
|scrambled51053.smt2                                                                        |  10.050s |256.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  10.061s  |  10.061s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  10.043s  |  10.043s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  10.106s  |  10.106s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  10.082s  |  10.082s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  10.065s  |  10.065s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  10.067s  |  10.067s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  10.028s  |  10.028s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  10.046s  |  10.046s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  10.069s  |  10.069s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  10.039s  |  10.039s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  10.042s  |  10.042s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  10.057s  |  10.057s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  10.043s  |  10.043s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  10.046s  |  10.046s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  10.041s  |  10.041s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  10.031s  |  10.031s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  10.072s  |  10.072s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  10.037s  |  10.037s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  10.075s  |  10.075s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  10.094s  |  10.094s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |  10.057s  |  10.057s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |  10.054s  |  10.054s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |  10.045s  |  10.045s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |  10.060s  |  10.060s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |  10.068s  |  10.068s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |  10.066s  |  10.066s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |  10.081s  |  10.081s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |  10.047s  |  10.047s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |  10.035s  |  10.035s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |  10.050s  |  10.050s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |  10.076s  |  10.076s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |  10.045s  |  10.045s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |  10.034s  |  10.034s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |  10.072s  |  10.072s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |  10.061s  |  10.061s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |  10.063s  |  10.063s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |  10.040s  |  10.040s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |  10.100s  |  10.100s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |  10.053s  |  10.053s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |  10.082s  |  10.082s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |  10.042s  |  10.042s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |  10.057s  |  10.057s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |  10.068s  |  10.068s  |   0.000s  | 0.0%|
</details>
