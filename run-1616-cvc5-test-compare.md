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
Job tag: cvc5-test
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
|scrambled102166.smt2                                                                        |  10.095s  |  10.095s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  10.044s  |  10.044s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  10.150s  |  10.150s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  10.077s  |  10.077s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  10.079s  |  10.079s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  10.079s  |  10.079s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   9.675s  |   9.675s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   9.815s  |   9.815s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  10.080s  |  10.080s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  10.091s  |  10.091s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   9.972s  |   9.972s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  10.492s  |  10.492s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   9.973s  |   9.973s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  10.048s  |  10.048s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   9.769s  |   9.769s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   9.903s  |   9.903s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  10.095s  |  10.095s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   9.875s  |   9.875s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  10.762s  |  10.762s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  10.102s  |  10.102s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  10.095s  |  10.095s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  10.044s  |  10.044s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  10.150s  |  10.150s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  10.077s  |  10.077s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  10.079s  |  10.079s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  10.079s  |  10.079s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   9.675s  |   9.675s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   9.815s  |   9.815s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  10.080s  |  10.080s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  10.091s  |  10.091s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   9.972s  |   9.972s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  10.492s  |  10.492s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   9.973s  |   9.973s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  10.048s  |  10.048s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   9.769s  |   9.769s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   9.903s  |   9.903s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  10.095s  |  10.095s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   9.875s  |   9.875s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  10.762s  |  10.762s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  10.102s  |  10.102s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  10.095s  |  10.095s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  10.044s  |  10.044s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  10.150s  |  10.150s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  10.077s  |  10.077s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  10.079s  |  10.079s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  10.079s  |  10.079s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   9.675s  |   9.675s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   9.815s  |   9.815s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  10.080s  |  10.080s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  10.091s  |  10.091s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   9.972s  |   9.972s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  10.492s  |  10.492s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   9.973s  |   9.973s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  10.048s  |  10.048s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   9.769s  |   9.769s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   9.903s  |   9.903s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  10.095s  |  10.095s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   9.875s  |   9.875s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  10.762s  |  10.762s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  10.102s  |  10.102s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  10.095s  |  10.095s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  10.044s  |  10.044s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  10.150s  |  10.150s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  10.077s  |  10.077s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  10.079s  |  10.079s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  10.079s  |  10.079s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   9.675s  |   9.675s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   9.815s  |   9.815s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  10.080s  |  10.080s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  10.091s  |  10.091s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   9.972s  |   9.972s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  10.492s  |  10.492s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   9.973s  |   9.973s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  10.048s  |  10.048s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   9.769s  |   9.769s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   9.903s  |   9.903s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  10.095s  |  10.095s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   9.875s  |   9.875s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  10.762s  |  10.762s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  10.102s  |  10.102s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25238.smt2                                                                        |  10.762s |271.0MiB|
|scrambled128128.smt2                                                                       |  10.492s |197.0MiB|
|scrambled44911.smt2                                                                        |  10.299s |177.0MiB|
|scrambled55777.smt2                                                                        |  10.213s |146.0MiB|
|scrambled40621.smt2                                                                        |  10.166s |249.0MiB|
|scrambled107115.smt2                                                                       |  10.150s |731.0MiB|
|scrambled32836.smt2                                                                        |  10.141s |128.0MiB|
|scrambled79760.smt2                                                                        |  10.104s |474.0MiB|
|scrambled27843.smt2                                                                        |  10.102s |677.0MiB|
|scrambled43577.smt2                                                                        |  10.100s |484.0MiB|
|scrambled19335.smt2                                                                        |  10.095s |459.0MiB|
|scrambled102166.smt2                                                                       |  10.095s |390.0MiB|
|scrambled68944.smt2                                                                        |  10.092s |451.0MiB|
|scrambled125827.smt2                                                                       |  10.091s |154.0MiB|
|scrambled75189.smt2                                                                        |  10.088s |514.0MiB|
|scrambled61922.smt2                                                                        |  10.084s |487.0MiB|
|scrambled3854.smt2                                                                         |  10.082s |142.0MiB|
|scrambled94658.smt2                                                                        |  10.081s |425.0MiB|
|scrambled12042.smt2                                                                        |  10.080s |427.0MiB|
|scrambled111627.smt2                                                                       |  10.079s |487.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25238.smt2                                                                        |  10.762s |271.0MiB|
|scrambled128128.smt2                                                                       |  10.492s |197.0MiB|
|scrambled44911.smt2                                                                        |  10.299s |177.0MiB|
|scrambled55777.smt2                                                                        |  10.213s |146.0MiB|
|scrambled40621.smt2                                                                        |  10.166s |249.0MiB|
|scrambled107115.smt2                                                                       |  10.150s |731.0MiB|
|scrambled32836.smt2                                                                        |  10.141s |128.0MiB|
|scrambled79760.smt2                                                                        |  10.104s |474.0MiB|
|scrambled27843.smt2                                                                        |  10.102s |677.0MiB|
|scrambled43577.smt2                                                                        |  10.100s |484.0MiB|
|scrambled19335.smt2                                                                        |  10.095s |459.0MiB|
|scrambled102166.smt2                                                                       |  10.095s |390.0MiB|
|scrambled68944.smt2                                                                        |  10.092s |451.0MiB|
|scrambled125827.smt2                                                                       |  10.091s |154.0MiB|
|scrambled75189.smt2                                                                        |  10.088s |514.0MiB|
|scrambled61922.smt2                                                                        |  10.084s |487.0MiB|
|scrambled3854.smt2                                                                         |  10.082s |142.0MiB|
|scrambled94658.smt2                                                                        |  10.081s |425.0MiB|
|scrambled12042.smt2                                                                        |  10.080s |427.0MiB|
|scrambled111627.smt2                                                                       |  10.079s |487.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |390.0MiB|390.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |141.0MiB|141.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |731.0MiB|731.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |475.0MiB|475.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |385.0MiB|385.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |487.0MiB|487.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |76.944MiB|76.944MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |251.0MiB|251.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |427.0MiB|427.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |154.0MiB|154.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |92.792MiB|92.792MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |197.0MiB|197.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |141.0MiB|141.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |169.0MiB|169.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |195.0MiB|195.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |112.0MiB|112.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |459.0MiB|459.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |95.088MiB|95.088MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |271.0MiB|271.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |677.0MiB|677.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |390.0MiB|390.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |141.0MiB|141.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |731.0MiB|731.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |475.0MiB|475.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |385.0MiB|385.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |487.0MiB|487.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |76.944MiB|76.944MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |251.0MiB|251.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |427.0MiB|427.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |154.0MiB|154.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |92.792MiB|92.792MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |197.0MiB|197.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |141.0MiB|141.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |169.0MiB|169.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |195.0MiB|195.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |112.0MiB|112.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |459.0MiB|459.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |95.088MiB|95.088MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |271.0MiB|271.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |677.0MiB|677.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |390.0MiB|390.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |141.0MiB|141.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |731.0MiB|731.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |475.0MiB|475.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |385.0MiB|385.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |487.0MiB|487.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |76.944MiB|76.944MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |251.0MiB|251.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |427.0MiB|427.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |154.0MiB|154.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |92.792MiB|92.792MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |197.0MiB|197.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |141.0MiB|141.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |169.0MiB|169.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |195.0MiB|195.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |112.0MiB|112.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |459.0MiB|459.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |95.088MiB|95.088MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |271.0MiB|271.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |677.0MiB|677.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |390.0MiB|390.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |141.0MiB|141.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |731.0MiB|731.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |475.0MiB|475.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |385.0MiB|385.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |487.0MiB|487.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |76.944MiB|76.944MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |251.0MiB|251.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |427.0MiB|427.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |154.0MiB|154.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |92.792MiB|92.792MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |197.0MiB|197.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |141.0MiB|141.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |169.0MiB|169.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |195.0MiB|195.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |112.0MiB|112.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |459.0MiB|459.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |95.088MiB|95.088MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |271.0MiB|271.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |677.0MiB|677.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled107115.smt2                                                                       |  10.150s |731.0MiB|
|scrambled27843.smt2                                                                        |  10.102s |677.0MiB|
|scrambled75189.smt2                                                                        |  10.088s |514.0MiB|
|scrambled61922.smt2                                                                        |  10.084s |487.0MiB|
|scrambled111627.smt2                                                                       |  10.079s |487.0MiB|
|scrambled43577.smt2                                                                        |  10.100s |484.0MiB|
|scrambled107826.smt2                                                                       |  10.077s |475.0MiB|
|scrambled79760.smt2                                                                        |  10.104s |474.0MiB|
|scrambled19335.smt2                                                                        |  10.095s |459.0MiB|
|scrambled68944.smt2                                                                        |  10.092s |451.0MiB|
|scrambled4198.smt2                                                                         |  10.076s |429.0MiB|
|scrambled12042.smt2                                                                        |  10.080s |427.0MiB|
|scrambled94658.smt2                                                                        |  10.081s |425.0MiB|
|scrambled55680.smt2                                                                        |  10.071s |413.0MiB|
|scrambled102166.smt2                                                                       |  10.095s |390.0MiB|
|scrambled108840.smt2                                                                       |  10.079s |385.0MiB|
|scrambled4299.smt2                                                                         |  10.075s |378.0MiB|
|scrambled51053.smt2                                                                        |  10.064s |273.0MiB|
|scrambled7741.smt2                                                                         |   9.703s |273.0MiB|
|scrambled25238.smt2                                                                        |  10.762s |271.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled107115.smt2                                                                       |  10.150s |731.0MiB|
|scrambled27843.smt2                                                                        |  10.102s |677.0MiB|
|scrambled75189.smt2                                                                        |  10.088s |514.0MiB|
|scrambled61922.smt2                                                                        |  10.084s |487.0MiB|
|scrambled111627.smt2                                                                       |  10.079s |487.0MiB|
|scrambled43577.smt2                                                                        |  10.100s |484.0MiB|
|scrambled107826.smt2                                                                       |  10.077s |475.0MiB|
|scrambled79760.smt2                                                                        |  10.104s |474.0MiB|
|scrambled19335.smt2                                                                        |  10.095s |459.0MiB|
|scrambled68944.smt2                                                                        |  10.092s |451.0MiB|
|scrambled4198.smt2                                                                         |  10.076s |429.0MiB|
|scrambled12042.smt2                                                                        |  10.080s |427.0MiB|
|scrambled94658.smt2                                                                        |  10.081s |425.0MiB|
|scrambled55680.smt2                                                                        |  10.071s |413.0MiB|
|scrambled102166.smt2                                                                       |  10.095s |390.0MiB|
|scrambled108840.smt2                                                                       |  10.079s |385.0MiB|
|scrambled4299.smt2                                                                         |  10.075s |378.0MiB|
|scrambled51053.smt2                                                                        |  10.064s |273.0MiB|
|scrambled7741.smt2                                                                         |   9.703s |273.0MiB|
|scrambled25238.smt2                                                                        |  10.762s |271.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  10.095s  |  10.095s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  10.044s  |  10.044s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  10.150s  |  10.150s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  10.077s  |  10.077s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  10.079s  |  10.079s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  10.079s  |  10.079s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   9.675s  |   9.675s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   9.815s  |   9.815s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  10.080s  |  10.080s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  10.091s  |  10.091s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   9.972s  |   9.972s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  10.492s  |  10.492s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   9.973s  |   9.973s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  10.048s  |  10.048s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   9.769s  |   9.769s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   9.903s  |   9.903s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  10.095s  |  10.095s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   9.875s  |   9.875s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  10.762s  |  10.762s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  10.102s  |  10.102s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |  10.141s  |  10.141s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |  10.082s  |  10.082s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |  10.065s  |  10.065s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |  10.166s  |  10.166s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |  10.076s  |  10.076s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |  10.075s  |  10.075s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |  10.100s  |  10.100s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |  10.299s  |  10.299s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |  10.053s  |  10.053s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |  10.064s  |  10.064s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |  10.071s  |  10.071s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |  10.213s  |  10.213s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |  10.047s  |  10.047s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |  10.084s  |  10.084s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |  10.052s  |  10.052s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |  10.092s  |  10.092s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |   9.999s  |   9.999s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |  10.088s  |  10.088s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |   9.703s  |   9.703s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |  10.104s  |  10.104s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |  10.067s  |  10.067s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |  10.054s  |  10.054s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |  10.081s  |  10.081s  |   0.000s  | 0.0%|
</details>
