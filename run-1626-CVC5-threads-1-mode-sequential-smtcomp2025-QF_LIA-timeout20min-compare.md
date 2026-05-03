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
Job tag: CVC5-threads-1-mode-sequential-smtcomp2025-QF_LIA-timeout20min
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
Job tag: CVC5-threads-1-mode-sequential-smtcomp2025-QF_LIA-timeout20min
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
|scrambled102166.smt2                                                                        |1200.355s  |1200.355s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.060s  |1200.060s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.373s  |1200.373s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.467s  |1200.467s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.579s  |1200.579s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.471s  |1200.471s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1200.053s  |1200.053s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.112s  |1200.112s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.611s  |1200.611s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 390.432s  | 390.432s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.075s  |1200.075s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.171s  |1200.171s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.861s  |1200.861s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.340s  |1200.340s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1200.099s  |1200.099s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.381s  |1200.381s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.355s  |1200.355s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.060s  |1200.060s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.373s  |1200.373s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.467s  |1200.467s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.579s  |1200.579s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.471s  |1200.471s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1200.053s  |1200.053s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.112s  |1200.112s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.611s  |1200.611s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 390.432s  | 390.432s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.075s  |1200.075s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.171s  |1200.171s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.861s  |1200.861s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.340s  |1200.340s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1200.099s  |1200.099s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.381s  |1200.381s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.355s  |1200.355s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.060s  |1200.060s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.373s  |1200.373s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.467s  |1200.467s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.579s  |1200.579s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.471s  |1200.471s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1200.053s  |1200.053s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.112s  |1200.112s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.611s  |1200.611s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 390.432s  | 390.432s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.075s  |1200.075s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.171s  |1200.171s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.861s  |1200.861s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.340s  |1200.340s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1200.099s  |1200.099s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.381s  |1200.381s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.355s  |1200.355s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.060s  |1200.060s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.373s  |1200.373s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.467s  |1200.467s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.579s  |1200.579s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.471s  |1200.471s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1200.053s  |1200.053s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.112s  |1200.112s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.611s  |1200.611s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 390.432s  | 390.432s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.075s  |1200.075s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.171s  |1200.171s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.861s  |1200.861s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.340s  |1200.340s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1200.099s  |1200.099s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.381s  |1200.381s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled1417.smt2                                                                         |1200.861s |4493.0MiB|
|scrambled4198.smt2                                                                         |1200.655s |4138.0MiB|
|scrambled94658.smt2                                                                        |1200.653s |4036.0MiB|
|scrambled12042.smt2                                                                        |1200.611s |4097.0MiB|
|scrambled55680.smt2                                                                        |1200.597s |3724.0MiB|
|scrambled108840.smt2                                                                       |1200.579s |3353.0MiB|
|scrambled43577.smt2                                                                        |1200.577s |3114.0MiB|
|scrambled75189.smt2                                                                        |1200.531s |2905.0MiB|
|scrambled4299.smt2                                                                         |1200.518s |5207.0MiB|
|scrambled111627.smt2                                                                       |1200.471s |2168.0MiB|
|scrambled107826.smt2                                                                       |1200.467s |3112.0MiB|
|scrambled27843.smt2                                                                        |1200.381s |1745.0MiB|
|scrambled107115.smt2                                                                       |1200.373s |2383.0MiB|
|scrambled79760.smt2                                                                        |1200.358s |3092.0MiB|
|scrambled102166.smt2                                                                       |1200.355s |3401.0MiB|
|scrambled19335.smt2                                                                        |1200.340s |3064.0MiB|
|scrambled68944.smt2                                                                        |1200.318s |3015.0MiB|
|scrambled61922.smt2                                                                        |1200.204s |822.0MiB|
|scrambled131241.smt2                                                                       |1200.171s |613.0MiB|
|scrambled44911.smt2                                                                        |1200.136s |346.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled1417.smt2                                                                         |1200.861s |4493.0MiB|
|scrambled4198.smt2                                                                         |1200.655s |4138.0MiB|
|scrambled94658.smt2                                                                        |1200.653s |4036.0MiB|
|scrambled12042.smt2                                                                        |1200.611s |4097.0MiB|
|scrambled55680.smt2                                                                        |1200.597s |3724.0MiB|
|scrambled108840.smt2                                                                       |1200.579s |3353.0MiB|
|scrambled43577.smt2                                                                        |1200.577s |3114.0MiB|
|scrambled75189.smt2                                                                        |1200.531s |2905.0MiB|
|scrambled4299.smt2                                                                         |1200.518s |5207.0MiB|
|scrambled111627.smt2                                                                       |1200.471s |2168.0MiB|
|scrambled107826.smt2                                                                       |1200.467s |3112.0MiB|
|scrambled27843.smt2                                                                        |1200.381s |1745.0MiB|
|scrambled107115.smt2                                                                       |1200.373s |2383.0MiB|
|scrambled79760.smt2                                                                        |1200.358s |3092.0MiB|
|scrambled102166.smt2                                                                       |1200.355s |3401.0MiB|
|scrambled19335.smt2                                                                        |1200.340s |3064.0MiB|
|scrambled68944.smt2                                                                        |1200.318s |3015.0MiB|
|scrambled61922.smt2                                                                        |1200.204s |822.0MiB|
|scrambled131241.smt2                                                                       |1200.171s |613.0MiB|
|scrambled44911.smt2                                                                        |1200.136s |346.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |3401.0MiB|3401.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |140.0MiB|140.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |2383.0MiB|2383.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |3112.0MiB|3112.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |3353.0MiB|3353.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |2168.0MiB|2168.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |102.0MiB|102.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |421.0MiB|421.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |4097.0MiB|4097.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |111.0MiB|111.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |126.0MiB|126.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |366.0MiB|366.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |351.0MiB|351.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |231.0MiB|231.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |613.0MiB|613.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |4493.0MiB|4493.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |3064.0MiB|3064.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |159.0MiB|159.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |379.0MiB|379.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |1745.0MiB|1745.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |3401.0MiB|3401.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |140.0MiB|140.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |2383.0MiB|2383.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |3112.0MiB|3112.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |3353.0MiB|3353.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |2168.0MiB|2168.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |102.0MiB|102.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |421.0MiB|421.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |4097.0MiB|4097.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |111.0MiB|111.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |126.0MiB|126.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |366.0MiB|366.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |351.0MiB|351.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |231.0MiB|231.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |613.0MiB|613.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |4493.0MiB|4493.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |3064.0MiB|3064.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |159.0MiB|159.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |379.0MiB|379.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |1745.0MiB|1745.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |3401.0MiB|3401.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |140.0MiB|140.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |2383.0MiB|2383.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |3112.0MiB|3112.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |3353.0MiB|3353.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |2168.0MiB|2168.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |102.0MiB|102.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |421.0MiB|421.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |4097.0MiB|4097.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |111.0MiB|111.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |126.0MiB|126.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |366.0MiB|366.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |351.0MiB|351.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |231.0MiB|231.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |613.0MiB|613.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |4493.0MiB|4493.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |3064.0MiB|3064.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |159.0MiB|159.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |379.0MiB|379.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |1745.0MiB|1745.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |3401.0MiB|3401.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |140.0MiB|140.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |2383.0MiB|2383.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |3112.0MiB|3112.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |3353.0MiB|3353.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |2168.0MiB|2168.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |102.0MiB|102.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |421.0MiB|421.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |4097.0MiB|4097.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |111.0MiB|111.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |126.0MiB|126.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |366.0MiB|366.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |351.0MiB|351.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |231.0MiB|231.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |613.0MiB|613.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |4493.0MiB|4493.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |3064.0MiB|3064.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |159.0MiB|159.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |379.0MiB|379.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |1745.0MiB|1745.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled4299.smt2                                                                         |1200.518s |5207.0MiB|
|scrambled1417.smt2                                                                         |1200.861s |4493.0MiB|
|scrambled4198.smt2                                                                         |1200.655s |4138.0MiB|
|scrambled12042.smt2                                                                        |1200.611s |4097.0MiB|
|scrambled94658.smt2                                                                        |1200.653s |4036.0MiB|
|scrambled55680.smt2                                                                        |1200.597s |3724.0MiB|
|scrambled102166.smt2                                                                       |1200.355s |3401.0MiB|
|scrambled108840.smt2                                                                       |1200.579s |3353.0MiB|
|scrambled43577.smt2                                                                        |1200.577s |3114.0MiB|
|scrambled107826.smt2                                                                       |1200.467s |3112.0MiB|
|scrambled79760.smt2                                                                        |1200.358s |3092.0MiB|
|scrambled19335.smt2                                                                        |1200.340s |3064.0MiB|
|scrambled68944.smt2                                                                        |1200.318s |3015.0MiB|
|scrambled75189.smt2                                                                        |1200.531s |2905.0MiB|
|scrambled107115.smt2                                                                       |1200.373s |2383.0MiB|
|scrambled111627.smt2                                                                       |1200.471s |2168.0MiB|
|scrambled27843.smt2                                                                        |1200.381s |1745.0MiB|
|scrambled61922.smt2                                                                        |1200.204s |822.0MiB|
|scrambled131241.smt2                                                                       |1200.171s |613.0MiB|
|scrambled40621.smt2                                                                        |1200.069s |472.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled4299.smt2                                                                         |1200.518s |5207.0MiB|
|scrambled1417.smt2                                                                         |1200.861s |4493.0MiB|
|scrambled4198.smt2                                                                         |1200.655s |4138.0MiB|
|scrambled12042.smt2                                                                        |1200.611s |4097.0MiB|
|scrambled94658.smt2                                                                        |1200.653s |4036.0MiB|
|scrambled55680.smt2                                                                        |1200.597s |3724.0MiB|
|scrambled102166.smt2                                                                       |1200.355s |3401.0MiB|
|scrambled108840.smt2                                                                       |1200.579s |3353.0MiB|
|scrambled43577.smt2                                                                        |1200.577s |3114.0MiB|
|scrambled107826.smt2                                                                       |1200.467s |3112.0MiB|
|scrambled79760.smt2                                                                        |1200.358s |3092.0MiB|
|scrambled19335.smt2                                                                        |1200.340s |3064.0MiB|
|scrambled68944.smt2                                                                        |1200.318s |3015.0MiB|
|scrambled75189.smt2                                                                        |1200.531s |2905.0MiB|
|scrambled107115.smt2                                                                       |1200.373s |2383.0MiB|
|scrambled111627.smt2                                                                       |1200.471s |2168.0MiB|
|scrambled27843.smt2                                                                        |1200.381s |1745.0MiB|
|scrambled61922.smt2                                                                        |1200.204s |822.0MiB|
|scrambled131241.smt2                                                                       |1200.171s |613.0MiB|
|scrambled40621.smt2                                                                        |1200.069s |472.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.355s  |1200.355s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.060s  |1200.060s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.373s  |1200.373s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.467s  |1200.467s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.579s  |1200.579s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.471s  |1200.471s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1200.053s  |1200.053s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.112s  |1200.112s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.611s  |1200.611s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 390.432s  | 390.432s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.093s  |1200.093s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.075s  |1200.075s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.171s  |1200.171s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.861s  |1200.861s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.340s  |1200.340s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1200.099s  |1200.099s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |1200.121s  |1200.121s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.381s  |1200.381s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1200.096s  |1200.096s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1200.103s  |1200.103s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1200.655s  |1200.655s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1200.518s  |1200.518s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1200.577s  |1200.577s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1200.136s  |1200.136s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1200.046s  |1200.046s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1200.071s  |1200.071s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1200.597s  |1200.597s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1200.204s  |1200.204s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1200.062s  |1200.062s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1200.318s  |1200.318s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1200.531s  |1200.531s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1200.089s  |1200.089s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1200.358s  |1200.358s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1200.653s  |1200.653s  |   0.000s  | 0.0%|
</details>
