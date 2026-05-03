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
cvc5 mode: portfolio
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
cvc5 mode: portfolio
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
|scrambled102166.smt2                                                                        |   9.757s  |   9.757s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |   9.821s  |   9.821s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |   9.796s  |   9.796s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |   9.739s  |   9.739s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |   9.871s  |   9.871s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |   9.760s  |   9.760s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   9.702s  |   9.702s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   9.745s  |   9.745s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |   9.864s  |   9.864s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |   9.799s  |   9.799s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   9.815s  |   9.815s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |   9.720s  |   9.720s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   9.718s  |   9.718s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |   9.854s  |   9.854s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   9.737s  |   9.737s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   9.813s  |   9.813s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |   9.739s  |   9.739s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   9.719s  |   9.719s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |   9.750s  |   9.750s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |   9.780s  |   9.780s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |   9.757s  |   9.757s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |   9.821s  |   9.821s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |   9.796s  |   9.796s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |   9.739s  |   9.739s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |   9.871s  |   9.871s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |   9.760s  |   9.760s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   9.702s  |   9.702s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   9.745s  |   9.745s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |   9.864s  |   9.864s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |   9.799s  |   9.799s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   9.815s  |   9.815s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |   9.720s  |   9.720s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   9.718s  |   9.718s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |   9.854s  |   9.854s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   9.737s  |   9.737s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   9.813s  |   9.813s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |   9.739s  |   9.739s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   9.719s  |   9.719s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |   9.750s  |   9.750s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |   9.780s  |   9.780s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |   9.757s  |   9.757s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |   9.821s  |   9.821s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |   9.796s  |   9.796s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |   9.739s  |   9.739s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |   9.871s  |   9.871s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |   9.760s  |   9.760s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   9.702s  |   9.702s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   9.745s  |   9.745s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |   9.864s  |   9.864s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |   9.799s  |   9.799s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   9.815s  |   9.815s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |   9.720s  |   9.720s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   9.718s  |   9.718s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |   9.854s  |   9.854s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   9.737s  |   9.737s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   9.813s  |   9.813s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |   9.739s  |   9.739s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   9.719s  |   9.719s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |   9.750s  |   9.750s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |   9.780s  |   9.780s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |   9.757s  |   9.757s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |   9.821s  |   9.821s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |   9.796s  |   9.796s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |   9.739s  |   9.739s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |   9.871s  |   9.871s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |   9.760s  |   9.760s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   9.702s  |   9.702s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   9.745s  |   9.745s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |   9.864s  |   9.864s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |   9.799s  |   9.799s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   9.815s  |   9.815s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |   9.720s  |   9.720s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   9.718s  |   9.718s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |   9.854s  |   9.854s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   9.737s  |   9.737s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   9.813s  |   9.813s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |   9.739s  |   9.739s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   9.719s  |   9.719s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |   9.750s  |   9.750s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |   9.780s  |   9.780s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled79867.smt2                                                                        |   9.940s |957.0MiB|
|scrambled45952.smt2                                                                        |   9.937s |956.0MiB|
|scrambled79766.smt2                                                                        |   9.929s |955.0MiB|
|scrambled59713.smt2                                                                        |   9.929s |915.0MiB|
|scrambled65181.smt2                                                                        |   9.924s |955.0MiB|
|scrambled75189.smt2                                                                        |   9.872s |467.0MiB|
|scrambled108840.smt2                                                                       |   9.871s |371.0MiB|
|scrambled12042.smt2                                                                        |   9.864s |417.0MiB|
|scrambled55680.smt2                                                                        |   9.858s |392.0MiB|
|scrambled3854.smt2                                                                         |   9.857s |907.0MiB|
|scrambled43577.smt2                                                                        |   9.855s |385.0MiB|
|scrambled128874.smt2                                                                       |   9.854s |165.0MiB|
|scrambled40621.smt2                                                                        |   9.852s |331.0MiB|
|scrambled79760.smt2                                                                        |   9.844s |377.0MiB|
|scrambled32836.smt2                                                                        |   9.833s |156.0MiB|
|scrambled103783.smt2                                                                       |   9.821s |956.0MiB|
|scrambled125888.smt2                                                                       |   9.815s |90.908MiB|
|scrambled39514.smt2                                                                        |   9.814s |908.0MiB|
|scrambled1417.smt2                                                                         |   9.813s |52.792MiB|
|scrambled125827.smt2                                                                       |   9.799s |82.412MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled79867.smt2                                                                        |   9.940s |957.0MiB|
|scrambled45952.smt2                                                                        |   9.937s |956.0MiB|
|scrambled79766.smt2                                                                        |   9.929s |955.0MiB|
|scrambled59713.smt2                                                                        |   9.929s |915.0MiB|
|scrambled65181.smt2                                                                        |   9.924s |955.0MiB|
|scrambled75189.smt2                                                                        |   9.872s |467.0MiB|
|scrambled108840.smt2                                                                       |   9.871s |371.0MiB|
|scrambled12042.smt2                                                                        |   9.864s |417.0MiB|
|scrambled55680.smt2                                                                        |   9.858s |392.0MiB|
|scrambled3854.smt2                                                                         |   9.857s |907.0MiB|
|scrambled43577.smt2                                                                        |   9.855s |385.0MiB|
|scrambled128874.smt2                                                                       |   9.854s |165.0MiB|
|scrambled40621.smt2                                                                        |   9.852s |331.0MiB|
|scrambled79760.smt2                                                                        |   9.844s |377.0MiB|
|scrambled32836.smt2                                                                        |   9.833s |156.0MiB|
|scrambled103783.smt2                                                                       |   9.821s |956.0MiB|
|scrambled125888.smt2                                                                       |   9.815s |90.908MiB|
|scrambled39514.smt2                                                                        |   9.814s |908.0MiB|
|scrambled1417.smt2                                                                         |   9.813s |52.792MiB|
|scrambled125827.smt2                                                                       |   9.799s |82.412MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |367.0MiB|367.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |956.0MiB|956.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |623.0MiB|623.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |362.0MiB|362.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |371.0MiB|371.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |381.0MiB|381.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |76.0MiB|76.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |247.0MiB|247.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |417.0MiB|417.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |82.412MiB|82.412MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |90.908MiB|90.908MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |254.0MiB|254.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |167.0MiB|167.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |165.0MiB|165.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |253.0MiB|253.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |52.792MiB|52.792MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |358.0MiB|358.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |91.94MiB|91.94MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |267.0MiB|267.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |512.0MiB|512.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |367.0MiB|367.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |956.0MiB|956.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |623.0MiB|623.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |362.0MiB|362.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |371.0MiB|371.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |381.0MiB|381.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |76.0MiB|76.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |247.0MiB|247.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |417.0MiB|417.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |82.412MiB|82.412MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |90.908MiB|90.908MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |254.0MiB|254.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |167.0MiB|167.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |165.0MiB|165.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |253.0MiB|253.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |52.792MiB|52.792MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |358.0MiB|358.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |91.94MiB|91.94MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |267.0MiB|267.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |512.0MiB|512.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |367.0MiB|367.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |956.0MiB|956.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |623.0MiB|623.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |362.0MiB|362.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |371.0MiB|371.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |381.0MiB|381.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |76.0MiB|76.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |247.0MiB|247.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |417.0MiB|417.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |82.412MiB|82.412MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |90.908MiB|90.908MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |254.0MiB|254.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |167.0MiB|167.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |165.0MiB|165.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |253.0MiB|253.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |52.792MiB|52.792MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |358.0MiB|358.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |91.94MiB|91.94MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |267.0MiB|267.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |512.0MiB|512.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |367.0MiB|367.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |956.0MiB|956.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |623.0MiB|623.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |362.0MiB|362.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |371.0MiB|371.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |381.0MiB|381.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |76.0MiB|76.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |247.0MiB|247.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |417.0MiB|417.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |82.412MiB|82.412MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |90.908MiB|90.908MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |254.0MiB|254.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |167.0MiB|167.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |165.0MiB|165.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |253.0MiB|253.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |52.792MiB|52.792MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |358.0MiB|358.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |91.94MiB|91.94MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |267.0MiB|267.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |512.0MiB|512.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled79867.smt2                                                                        |   9.940s |957.0MiB|
|scrambled45952.smt2                                                                        |   9.937s |956.0MiB|
|scrambled103783.smt2                                                                       |   9.821s |956.0MiB|
|scrambled79766.smt2                                                                        |   9.929s |955.0MiB|
|scrambled65181.smt2                                                                        |   9.924s |955.0MiB|
|scrambled59713.smt2                                                                        |   9.929s |915.0MiB|
|scrambled39514.smt2                                                                        |   9.814s |908.0MiB|
|scrambled3854.smt2                                                                         |   9.857s |907.0MiB|
|scrambled107115.smt2                                                                       |   9.796s |623.0MiB|
|scrambled27843.smt2                                                                        |   9.780s |512.0MiB|
|scrambled61922.smt2                                                                        |   9.780s |494.0MiB|
|scrambled75189.smt2                                                                        |   9.872s |467.0MiB|
|scrambled12042.smt2                                                                        |   9.864s |417.0MiB|
|scrambled94658.smt2                                                                        |   9.753s |410.0MiB|
|scrambled4198.smt2                                                                         |   9.721s |403.0MiB|
|scrambled7741.smt2                                                                         |   9.737s |401.0MiB|
|scrambled55680.smt2                                                                        |   9.858s |392.0MiB|
|scrambled43577.smt2                                                                        |   9.855s |385.0MiB|
|scrambled111627.smt2                                                                       |   9.760s |381.0MiB|
|scrambled79760.smt2                                                                        |   9.844s |377.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled79867.smt2                                                                        |   9.940s |957.0MiB|
|scrambled45952.smt2                                                                        |   9.937s |956.0MiB|
|scrambled103783.smt2                                                                       |   9.821s |956.0MiB|
|scrambled79766.smt2                                                                        |   9.929s |955.0MiB|
|scrambled65181.smt2                                                                        |   9.924s |955.0MiB|
|scrambled59713.smt2                                                                        |   9.929s |915.0MiB|
|scrambled39514.smt2                                                                        |   9.814s |908.0MiB|
|scrambled3854.smt2                                                                         |   9.857s |907.0MiB|
|scrambled107115.smt2                                                                       |   9.796s |623.0MiB|
|scrambled27843.smt2                                                                        |   9.780s |512.0MiB|
|scrambled61922.smt2                                                                        |   9.780s |494.0MiB|
|scrambled75189.smt2                                                                        |   9.872s |467.0MiB|
|scrambled12042.smt2                                                                        |   9.864s |417.0MiB|
|scrambled94658.smt2                                                                        |   9.753s |410.0MiB|
|scrambled4198.smt2                                                                         |   9.721s |403.0MiB|
|scrambled7741.smt2                                                                         |   9.737s |401.0MiB|
|scrambled55680.smt2                                                                        |   9.858s |392.0MiB|
|scrambled43577.smt2                                                                        |   9.855s |385.0MiB|
|scrambled111627.smt2                                                                       |   9.760s |381.0MiB|
|scrambled79760.smt2                                                                        |   9.844s |377.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |   9.757s  |   9.757s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |   9.821s  |   9.821s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |   9.796s  |   9.796s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |   9.739s  |   9.739s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |   9.871s  |   9.871s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |   9.760s  |   9.760s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   9.702s  |   9.702s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   9.745s  |   9.745s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |   9.864s  |   9.864s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |   9.799s  |   9.799s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   9.815s  |   9.815s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |   9.720s  |   9.720s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   9.718s  |   9.718s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |   9.854s  |   9.854s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   9.737s  |   9.737s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   9.813s  |   9.813s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |   9.739s  |   9.739s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   9.719s  |   9.719s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |   9.750s  |   9.750s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |   9.780s  |   9.780s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |   9.833s  |   9.833s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |   9.857s  |   9.857s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |   9.814s  |   9.814s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |   9.852s  |   9.852s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |   9.721s  |   9.721s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |   9.764s  |   9.764s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |   9.855s  |   9.855s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |   9.717s  |   9.717s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |   9.937s  |   9.937s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |   9.755s  |   9.755s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |   9.858s  |   9.858s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |   9.708s  |   9.708s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |   9.929s  |   9.929s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |   9.780s  |   9.780s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |   9.924s  |   9.924s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |   9.758s  |   9.758s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |   9.746s  |   9.746s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |   9.872s  |   9.872s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |   9.737s  |   9.737s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |   9.844s  |   9.844s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |   9.929s  |   9.929s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |   9.940s  |   9.940s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |   9.753s  |   9.753s  |   0.000s  | 0.0%|
</details>
