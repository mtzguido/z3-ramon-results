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
Job tag: CVC5-test
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
Job tag: CVC5-test
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
|scrambled102166.smt2                                                                        |  10.087s  |  10.087s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  10.042s  |  10.042s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  10.081s  |  10.081s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  10.061s  |  10.061s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  10.088s  |  10.088s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  10.084s  |  10.084s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  10.028s  |  10.028s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  10.074s  |  10.074s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  10.061s  |  10.061s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  10.047s  |  10.047s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  10.030s  |  10.030s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  10.042s  |  10.042s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  10.034s  |  10.034s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  10.037s  |  10.037s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  10.048s  |  10.048s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  10.046s  |  10.046s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  10.061s  |  10.061s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  10.049s  |  10.049s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  10.053s  |  10.053s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  10.113s  |  10.113s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  10.087s  |  10.087s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  10.042s  |  10.042s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  10.081s  |  10.081s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  10.061s  |  10.061s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  10.088s  |  10.088s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  10.084s  |  10.084s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  10.028s  |  10.028s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  10.074s  |  10.074s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  10.061s  |  10.061s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  10.047s  |  10.047s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  10.030s  |  10.030s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  10.042s  |  10.042s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  10.034s  |  10.034s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  10.037s  |  10.037s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  10.048s  |  10.048s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  10.046s  |  10.046s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  10.061s  |  10.061s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  10.049s  |  10.049s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  10.053s  |  10.053s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  10.113s  |  10.113s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  10.087s  |  10.087s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  10.042s  |  10.042s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  10.081s  |  10.081s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  10.061s  |  10.061s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  10.088s  |  10.088s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  10.084s  |  10.084s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  10.028s  |  10.028s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  10.074s  |  10.074s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  10.061s  |  10.061s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  10.047s  |  10.047s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  10.030s  |  10.030s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  10.042s  |  10.042s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  10.034s  |  10.034s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  10.037s  |  10.037s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  10.048s  |  10.048s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  10.046s  |  10.046s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  10.061s  |  10.061s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  10.049s  |  10.049s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  10.053s  |  10.053s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  10.113s  |  10.113s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  10.087s  |  10.087s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  10.042s  |  10.042s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  10.081s  |  10.081s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  10.061s  |  10.061s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  10.088s  |  10.088s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  10.084s  |  10.084s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  10.028s  |  10.028s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  10.074s  |  10.074s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  10.061s  |  10.061s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  10.047s  |  10.047s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  10.030s  |  10.030s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  10.042s  |  10.042s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  10.034s  |  10.034s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  10.037s  |  10.037s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  10.048s  |  10.048s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  10.046s  |  10.046s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  10.061s  |  10.061s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  10.049s  |  10.049s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  10.053s  |  10.053s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  10.113s  |  10.113s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled27843.smt2                                                                        |  10.113s |623.0MiB|
|scrambled79760.smt2                                                                        |  10.097s |471.0MiB|
|scrambled94658.smt2                                                                        |  10.091s |410.0MiB|
|scrambled108840.smt2                                                                       |  10.088s |378.0MiB|
|scrambled102166.smt2                                                                       |  10.087s |375.0MiB|
|scrambled61922.smt2                                                                        |  10.085s |462.0MiB|
|scrambled111627.smt2                                                                       |  10.084s |483.0MiB|
|scrambled43577.smt2                                                                        |  10.081s |473.0MiB|
|scrambled107115.smt2                                                                       |  10.081s |698.0MiB|
|scrambled40621.smt2                                                                        |  10.079s |313.0MiB|
|scrambled55680.smt2                                                                        |  10.078s |400.0MiB|
|scrambled68944.smt2                                                                        |  10.075s |450.0MiB|
|scrambled119331.smt2                                                                       |  10.074s |230.0MiB|
|scrambled4198.smt2                                                                         |  10.068s |419.0MiB|
|scrambled7741.smt2                                                                         |  10.064s |388.0MiB|
|scrambled75189.smt2                                                                        |  10.063s |448.0MiB|
|scrambled51053.smt2                                                                        |  10.062s |256.0MiB|
|scrambled39514.smt2                                                                        |  10.062s |145.0MiB|
|scrambled72668.smt2                                                                        |  10.061s |174.0MiB|
|scrambled107826.smt2                                                                       |  10.061s |475.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled27843.smt2                                                                        |  10.113s |623.0MiB|
|scrambled79760.smt2                                                                        |  10.097s |471.0MiB|
|scrambled94658.smt2                                                                        |  10.091s |410.0MiB|
|scrambled108840.smt2                                                                       |  10.088s |378.0MiB|
|scrambled102166.smt2                                                                       |  10.087s |375.0MiB|
|scrambled61922.smt2                                                                        |  10.085s |462.0MiB|
|scrambled111627.smt2                                                                       |  10.084s |483.0MiB|
|scrambled43577.smt2                                                                        |  10.081s |473.0MiB|
|scrambled107115.smt2                                                                       |  10.081s |698.0MiB|
|scrambled40621.smt2                                                                        |  10.079s |313.0MiB|
|scrambled55680.smt2                                                                        |  10.078s |400.0MiB|
|scrambled68944.smt2                                                                        |  10.075s |450.0MiB|
|scrambled119331.smt2                                                                       |  10.074s |230.0MiB|
|scrambled4198.smt2                                                                         |  10.068s |419.0MiB|
|scrambled7741.smt2                                                                         |  10.064s |388.0MiB|
|scrambled75189.smt2                                                                        |  10.063s |448.0MiB|
|scrambled51053.smt2                                                                        |  10.062s |256.0MiB|
|scrambled39514.smt2                                                                        |  10.062s |145.0MiB|
|scrambled72668.smt2                                                                        |  10.061s |174.0MiB|
|scrambled107826.smt2                                                                       |  10.061s |475.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |375.0MiB|375.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |140.0MiB|140.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |698.0MiB|698.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |475.0MiB|475.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |378.0MiB|378.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |483.0MiB|483.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |72.564MiB|72.564MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |230.0MiB|230.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |422.0MiB|422.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |77.788MiB|77.788MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |85.368MiB|85.368MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |241.0MiB|241.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |158.0MiB|158.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |155.0MiB|155.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |240.0MiB|240.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |63.908MiB|63.908MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |459.0MiB|459.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |87.312MiB|87.312MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |253.0MiB|253.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |623.0MiB|623.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |375.0MiB|375.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |140.0MiB|140.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |698.0MiB|698.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |475.0MiB|475.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |378.0MiB|378.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |483.0MiB|483.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |72.564MiB|72.564MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |230.0MiB|230.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |422.0MiB|422.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |77.788MiB|77.788MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |85.368MiB|85.368MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |241.0MiB|241.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |158.0MiB|158.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |155.0MiB|155.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |240.0MiB|240.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |63.908MiB|63.908MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |459.0MiB|459.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |87.312MiB|87.312MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |253.0MiB|253.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |623.0MiB|623.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |375.0MiB|375.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |140.0MiB|140.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |698.0MiB|698.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |475.0MiB|475.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |378.0MiB|378.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |483.0MiB|483.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |72.564MiB|72.564MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |230.0MiB|230.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |422.0MiB|422.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |77.788MiB|77.788MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |85.368MiB|85.368MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |241.0MiB|241.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |158.0MiB|158.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |155.0MiB|155.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |240.0MiB|240.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |63.908MiB|63.908MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |459.0MiB|459.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |87.312MiB|87.312MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |253.0MiB|253.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |623.0MiB|623.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |375.0MiB|375.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |140.0MiB|140.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |698.0MiB|698.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |475.0MiB|475.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |378.0MiB|378.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |483.0MiB|483.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |72.564MiB|72.564MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |230.0MiB|230.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |422.0MiB|422.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |77.788MiB|77.788MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |85.368MiB|85.368MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |241.0MiB|241.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |158.0MiB|158.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |155.0MiB|155.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |240.0MiB|240.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |63.908MiB|63.908MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |459.0MiB|459.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |87.312MiB|87.312MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |253.0MiB|253.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |623.0MiB|623.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled107115.smt2                                                                       |  10.081s |698.0MiB|
|scrambled27843.smt2                                                                        |  10.113s |623.0MiB|
|scrambled111627.smt2                                                                       |  10.084s |483.0MiB|
|scrambled107826.smt2                                                                       |  10.061s |475.0MiB|
|scrambled43577.smt2                                                                        |  10.081s |473.0MiB|
|scrambled79760.smt2                                                                        |  10.097s |471.0MiB|
|scrambled61922.smt2                                                                        |  10.085s |462.0MiB|
|scrambled19335.smt2                                                                        |  10.061s |459.0MiB|
|scrambled68944.smt2                                                                        |  10.075s |450.0MiB|
|scrambled75189.smt2                                                                        |  10.063s |448.0MiB|
|scrambled12042.smt2                                                                        |  10.061s |422.0MiB|
|scrambled4198.smt2                                                                         |  10.068s |419.0MiB|
|scrambled94658.smt2                                                                        |  10.091s |410.0MiB|
|scrambled55680.smt2                                                                        |  10.078s |400.0MiB|
|scrambled7741.smt2                                                                         |  10.064s |388.0MiB|
|scrambled108840.smt2                                                                       |  10.088s |378.0MiB|
|scrambled102166.smt2                                                                       |  10.087s |375.0MiB|
|scrambled4299.smt2                                                                         |  10.054s |367.0MiB|
|scrambled40621.smt2                                                                        |  10.079s |313.0MiB|
|scrambled51053.smt2                                                                        |  10.062s |256.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled107115.smt2                                                                       |  10.081s |698.0MiB|
|scrambled27843.smt2                                                                        |  10.113s |623.0MiB|
|scrambled111627.smt2                                                                       |  10.084s |483.0MiB|
|scrambled107826.smt2                                                                       |  10.061s |475.0MiB|
|scrambled43577.smt2                                                                        |  10.081s |473.0MiB|
|scrambled79760.smt2                                                                        |  10.097s |471.0MiB|
|scrambled61922.smt2                                                                        |  10.085s |462.0MiB|
|scrambled19335.smt2                                                                        |  10.061s |459.0MiB|
|scrambled68944.smt2                                                                        |  10.075s |450.0MiB|
|scrambled75189.smt2                                                                        |  10.063s |448.0MiB|
|scrambled12042.smt2                                                                        |  10.061s |422.0MiB|
|scrambled4198.smt2                                                                         |  10.068s |419.0MiB|
|scrambled94658.smt2                                                                        |  10.091s |410.0MiB|
|scrambled55680.smt2                                                                        |  10.078s |400.0MiB|
|scrambled7741.smt2                                                                         |  10.064s |388.0MiB|
|scrambled108840.smt2                                                                       |  10.088s |378.0MiB|
|scrambled102166.smt2                                                                       |  10.087s |375.0MiB|
|scrambled4299.smt2                                                                         |  10.054s |367.0MiB|
|scrambled40621.smt2                                                                        |  10.079s |313.0MiB|
|scrambled51053.smt2                                                                        |  10.062s |256.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  10.087s  |  10.087s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  10.042s  |  10.042s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  10.081s  |  10.081s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  10.061s  |  10.061s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  10.088s  |  10.088s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  10.084s  |  10.084s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  10.028s  |  10.028s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  10.074s  |  10.074s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  10.061s  |  10.061s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  10.047s  |  10.047s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  10.030s  |  10.030s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  10.042s  |  10.042s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  10.034s  |  10.034s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  10.037s  |  10.037s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  10.048s  |  10.048s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  10.046s  |  10.046s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  10.061s  |  10.061s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  10.049s  |  10.049s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  10.053s  |  10.053s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  10.113s  |  10.113s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |  10.061s  |  10.061s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |  10.037s  |  10.037s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |  10.062s  |  10.062s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |  10.079s  |  10.079s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |  10.068s  |  10.068s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |  10.054s  |  10.054s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |  10.081s  |  10.081s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |  10.058s  |  10.058s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |  10.052s  |  10.052s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |  10.062s  |  10.062s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |  10.078s  |  10.078s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |  10.040s  |  10.040s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |  10.060s  |  10.060s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |  10.085s  |  10.085s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |  10.034s  |  10.034s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |  10.075s  |  10.075s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |  10.061s  |  10.061s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |  10.063s  |  10.063s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |  10.064s  |  10.064s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |  10.097s  |  10.097s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |  10.055s  |  10.055s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |  10.034s  |  10.034s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |  10.091s  |  10.091s  |   0.000s  | 0.0%|
</details>
