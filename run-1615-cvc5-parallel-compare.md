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
|scrambled102166.smt2                                                                        |  10.091s  |  10.091s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  10.070s  |  10.070s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  10.107s  |  10.107s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  10.082s  |  10.082s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  10.079s  |  10.079s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  10.081s  |  10.081s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   9.666s  |   9.666s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   9.794s  |   9.794s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  10.077s  |  10.077s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  10.034s  |  10.034s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  10.063s  |  10.063s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  10.342s  |  10.342s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   9.951s  |   9.951s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |   9.947s  |   9.947s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   9.585s  |   9.585s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   9.893s  |   9.893s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  10.075s  |  10.075s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   9.898s  |   9.898s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  10.731s  |  10.731s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  10.096s  |  10.096s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  10.091s  |  10.091s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  10.070s  |  10.070s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  10.107s  |  10.107s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  10.082s  |  10.082s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  10.079s  |  10.079s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  10.081s  |  10.081s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   9.666s  |   9.666s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   9.794s  |   9.794s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  10.077s  |  10.077s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  10.034s  |  10.034s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  10.063s  |  10.063s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  10.342s  |  10.342s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   9.951s  |   9.951s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |   9.947s  |   9.947s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   9.585s  |   9.585s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   9.893s  |   9.893s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  10.075s  |  10.075s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   9.898s  |   9.898s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  10.731s  |  10.731s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  10.096s  |  10.096s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  10.091s  |  10.091s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  10.070s  |  10.070s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  10.107s  |  10.107s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  10.082s  |  10.082s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  10.079s  |  10.079s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  10.081s  |  10.081s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   9.666s  |   9.666s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   9.794s  |   9.794s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  10.077s  |  10.077s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  10.034s  |  10.034s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  10.063s  |  10.063s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  10.342s  |  10.342s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   9.951s  |   9.951s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |   9.947s  |   9.947s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   9.585s  |   9.585s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   9.893s  |   9.893s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  10.075s  |  10.075s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   9.898s  |   9.898s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  10.731s  |  10.731s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  10.096s  |  10.096s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  10.091s  |  10.091s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  10.070s  |  10.070s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  10.107s  |  10.107s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  10.082s  |  10.082s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  10.079s  |  10.079s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  10.081s  |  10.081s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   9.666s  |   9.666s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   9.794s  |   9.794s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  10.077s  |  10.077s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  10.034s  |  10.034s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  10.063s  |  10.063s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  10.342s  |  10.342s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   9.951s  |   9.951s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |   9.947s  |   9.947s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   9.585s  |   9.585s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   9.893s  |   9.893s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  10.075s  |  10.075s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   9.898s  |   9.898s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  10.731s  |  10.731s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  10.096s  |  10.096s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25238.smt2                                                                        |  10.731s |270.0MiB|
|scrambled128128.smt2                                                                       |  10.342s |197.0MiB|
|scrambled44911.smt2                                                                        |  10.320s |177.0MiB|
|scrambled55777.smt2                                                                        |  10.246s |146.0MiB|
|scrambled32836.smt2                                                                        |  10.215s |128.0MiB|
|scrambled40621.smt2                                                                        |  10.147s |248.0MiB|
|scrambled107115.smt2                                                                       |  10.107s |731.0MiB|
|scrambled94658.smt2                                                                        |  10.100s |427.0MiB|
|scrambled75189.smt2                                                                        |  10.096s |505.0MiB|
|scrambled27843.smt2                                                                        |  10.096s |677.0MiB|
|scrambled4198.smt2                                                                         |  10.096s |426.0MiB|
|scrambled102166.smt2                                                                       |  10.091s |388.0MiB|
|scrambled61922.smt2                                                                        |  10.087s |487.0MiB|
|scrambled107826.smt2                                                                       |  10.082s |478.0MiB|
|scrambled43577.smt2                                                                        |  10.081s |484.0MiB|
|scrambled111627.smt2                                                                       |  10.081s |487.0MiB|
|scrambled79760.smt2                                                                        |  10.079s |474.0MiB|
|scrambled108840.smt2                                                                       |  10.079s |384.0MiB|
|scrambled4299.smt2                                                                         |  10.078s |377.0MiB|
|scrambled55680.smt2                                                                        |  10.077s |410.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25238.smt2                                                                        |  10.731s |270.0MiB|
|scrambled128128.smt2                                                                       |  10.342s |197.0MiB|
|scrambled44911.smt2                                                                        |  10.320s |177.0MiB|
|scrambled55777.smt2                                                                        |  10.246s |146.0MiB|
|scrambled32836.smt2                                                                        |  10.215s |128.0MiB|
|scrambled40621.smt2                                                                        |  10.147s |248.0MiB|
|scrambled107115.smt2                                                                       |  10.107s |731.0MiB|
|scrambled94658.smt2                                                                        |  10.100s |427.0MiB|
|scrambled75189.smt2                                                                        |  10.096s |505.0MiB|
|scrambled27843.smt2                                                                        |  10.096s |677.0MiB|
|scrambled4198.smt2                                                                         |  10.096s |426.0MiB|
|scrambled102166.smt2                                                                       |  10.091s |388.0MiB|
|scrambled61922.smt2                                                                        |  10.087s |487.0MiB|
|scrambled107826.smt2                                                                       |  10.082s |478.0MiB|
|scrambled43577.smt2                                                                        |  10.081s |484.0MiB|
|scrambled111627.smt2                                                                       |  10.081s |487.0MiB|
|scrambled79760.smt2                                                                        |  10.079s |474.0MiB|
|scrambled108840.smt2                                                                       |  10.079s |384.0MiB|
|scrambled4299.smt2                                                                         |  10.078s |377.0MiB|
|scrambled55680.smt2                                                                        |  10.077s |410.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |388.0MiB|388.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |141.0MiB|141.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |731.0MiB|731.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |478.0MiB|478.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |384.0MiB|384.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |487.0MiB|487.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |77.224MiB|77.224MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |251.0MiB|251.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |426.0MiB|426.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |105.0MiB|105.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |92.576MiB|92.576MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |197.0MiB|197.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |141.0MiB|141.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |168.0MiB|168.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |195.0MiB|195.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |111.0MiB|111.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |465.0MiB|465.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |94.952MiB|94.952MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |270.0MiB|270.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |677.0MiB|677.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |388.0MiB|388.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |141.0MiB|141.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |731.0MiB|731.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |478.0MiB|478.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |384.0MiB|384.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |487.0MiB|487.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |77.224MiB|77.224MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |251.0MiB|251.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |426.0MiB|426.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |105.0MiB|105.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |92.576MiB|92.576MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |197.0MiB|197.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |141.0MiB|141.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |168.0MiB|168.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |195.0MiB|195.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |111.0MiB|111.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |465.0MiB|465.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |94.952MiB|94.952MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |270.0MiB|270.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |677.0MiB|677.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |388.0MiB|388.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |141.0MiB|141.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |731.0MiB|731.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |478.0MiB|478.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |384.0MiB|384.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |487.0MiB|487.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |77.224MiB|77.224MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |251.0MiB|251.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |426.0MiB|426.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |105.0MiB|105.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |92.576MiB|92.576MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |197.0MiB|197.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |141.0MiB|141.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |168.0MiB|168.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |195.0MiB|195.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |111.0MiB|111.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |465.0MiB|465.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |94.952MiB|94.952MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |270.0MiB|270.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |677.0MiB|677.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |388.0MiB|388.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |141.0MiB|141.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |731.0MiB|731.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |478.0MiB|478.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |384.0MiB|384.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |487.0MiB|487.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |77.224MiB|77.224MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |251.0MiB|251.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |426.0MiB|426.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |105.0MiB|105.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |92.576MiB|92.576MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |197.0MiB|197.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |141.0MiB|141.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |168.0MiB|168.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |195.0MiB|195.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |111.0MiB|111.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |465.0MiB|465.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |94.952MiB|94.952MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |270.0MiB|270.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |677.0MiB|677.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled107115.smt2                                                                       |  10.107s |731.0MiB|
|scrambled27843.smt2                                                                        |  10.096s |677.0MiB|
|scrambled75189.smt2                                                                        |  10.096s |505.0MiB|
|scrambled61922.smt2                                                                        |  10.087s |487.0MiB|
|scrambled111627.smt2                                                                       |  10.081s |487.0MiB|
|scrambled43577.smt2                                                                        |  10.081s |484.0MiB|
|scrambled107826.smt2                                                                       |  10.082s |478.0MiB|
|scrambled79760.smt2                                                                        |  10.079s |474.0MiB|
|scrambled19335.smt2                                                                        |  10.075s |465.0MiB|
|scrambled68944.smt2                                                                        |  10.072s |451.0MiB|
|scrambled94658.smt2                                                                        |  10.100s |427.0MiB|
|scrambled4198.smt2                                                                         |  10.096s |426.0MiB|
|scrambled12042.smt2                                                                        |  10.077s |426.0MiB|
|scrambled55680.smt2                                                                        |  10.077s |410.0MiB|
|scrambled102166.smt2                                                                       |  10.091s |388.0MiB|
|scrambled108840.smt2                                                                       |  10.079s |384.0MiB|
|scrambled4299.smt2                                                                         |  10.078s |377.0MiB|
|scrambled7741.smt2                                                                         |   9.690s |274.0MiB|
|scrambled51053.smt2                                                                        |  10.051s |272.0MiB|
|scrambled25238.smt2                                                                        |  10.731s |270.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled107115.smt2                                                                       |  10.107s |731.0MiB|
|scrambled27843.smt2                                                                        |  10.096s |677.0MiB|
|scrambled75189.smt2                                                                        |  10.096s |505.0MiB|
|scrambled61922.smt2                                                                        |  10.087s |487.0MiB|
|scrambled111627.smt2                                                                       |  10.081s |487.0MiB|
|scrambled43577.smt2                                                                        |  10.081s |484.0MiB|
|scrambled107826.smt2                                                                       |  10.082s |478.0MiB|
|scrambled79760.smt2                                                                        |  10.079s |474.0MiB|
|scrambled19335.smt2                                                                        |  10.075s |465.0MiB|
|scrambled68944.smt2                                                                        |  10.072s |451.0MiB|
|scrambled94658.smt2                                                                        |  10.100s |427.0MiB|
|scrambled4198.smt2                                                                         |  10.096s |426.0MiB|
|scrambled12042.smt2                                                                        |  10.077s |426.0MiB|
|scrambled55680.smt2                                                                        |  10.077s |410.0MiB|
|scrambled102166.smt2                                                                       |  10.091s |388.0MiB|
|scrambled108840.smt2                                                                       |  10.079s |384.0MiB|
|scrambled4299.smt2                                                                         |  10.078s |377.0MiB|
|scrambled7741.smt2                                                                         |   9.690s |274.0MiB|
|scrambled51053.smt2                                                                        |  10.051s |272.0MiB|
|scrambled25238.smt2                                                                        |  10.731s |270.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  10.091s  |  10.091s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  10.070s  |  10.070s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  10.107s  |  10.107s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  10.082s  |  10.082s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  10.079s  |  10.079s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  10.081s  |  10.081s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   9.666s  |   9.666s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   9.794s  |   9.794s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  10.077s  |  10.077s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  10.034s  |  10.034s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  10.063s  |  10.063s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  10.342s  |  10.342s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   9.951s  |   9.951s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |   9.947s  |   9.947s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   9.585s  |   9.585s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   9.893s  |   9.893s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  10.075s  |  10.075s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   9.898s  |   9.898s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  10.731s  |  10.731s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  10.096s  |  10.096s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |  10.215s  |  10.215s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |  10.060s  |  10.060s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |  10.064s  |  10.064s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |  10.147s  |  10.147s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |  10.096s  |  10.096s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |  10.078s  |  10.078s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |  10.081s  |  10.081s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |  10.320s  |  10.320s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |  10.056s  |  10.056s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |  10.051s  |  10.051s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |  10.077s  |  10.077s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |  10.246s  |  10.246s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |  10.054s  |  10.054s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |  10.087s  |  10.087s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |  10.056s  |  10.056s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |  10.072s  |  10.072s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |   9.972s  |   9.972s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |  10.096s  |  10.096s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |   9.690s  |   9.690s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |  10.079s  |  10.079s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |  10.041s  |  10.041s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |  10.057s  |  10.057s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |  10.100s  |  10.100s  |   0.000s  | 0.0%|
</details>
