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
Job tag: CVC5-threads-8-mode-portfolio-smtcomp2025-QF_LIA-timeout20min
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
Job tag: CVC5-threads-8-mode-portfolio-smtcomp2025-QF_LIA-timeout20min
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
|scrambled102166.smt2                                                                        |1200.083s  |1200.083s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.072s  |1200.072s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.131s  |1200.131s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.088s  |1200.088s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1199.571s  |1199.571s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1199.973s  |1199.973s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |1199.740s  |1199.740s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 488.863s  | 488.863s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1199.857s  |1199.857s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1199.656s  |1199.656s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1199.699s  |1199.699s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1199.973s  |1199.973s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.466s  |1200.466s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1199.480s  |1199.480s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 121.052s  | 121.052s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.098s  |1200.098s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.083s  |1200.083s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.072s  |1200.072s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.131s  |1200.131s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.088s  |1200.088s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1199.571s  |1199.571s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1199.973s  |1199.973s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |1199.740s  |1199.740s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 488.863s  | 488.863s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1199.857s  |1199.857s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1199.656s  |1199.656s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1199.699s  |1199.699s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1199.973s  |1199.973s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.466s  |1200.466s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1199.480s  |1199.480s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 121.052s  | 121.052s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.098s  |1200.098s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.083s  |1200.083s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.072s  |1200.072s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.131s  |1200.131s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.088s  |1200.088s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1199.571s  |1199.571s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1199.973s  |1199.973s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |1199.740s  |1199.740s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 488.863s  | 488.863s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1199.857s  |1199.857s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1199.656s  |1199.656s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1199.699s  |1199.699s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1199.973s  |1199.973s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.466s  |1200.466s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1199.480s  |1199.480s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 121.052s  | 121.052s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.098s  |1200.098s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.083s  |1200.083s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.072s  |1200.072s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.131s  |1200.131s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.088s  |1200.088s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1199.571s  |1199.571s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1199.973s  |1199.973s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |1199.740s  |1199.740s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 488.863s  | 488.863s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1199.857s  |1199.857s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1199.656s  |1199.656s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1199.699s  |1199.699s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1199.973s  |1199.973s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.466s  |1200.466s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1199.480s  |1199.480s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 121.052s  | 121.052s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.098s  |1200.098s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled1417.smt2                                                                         |1200.466s |15.143GiB|
|scrambled79766.smt2                                                                        |1200.211s |14.717GiB|
|scrambled43577.smt2                                                                        |1200.149s |19.082GiB|
|scrambled107115.smt2                                                                       |1200.131s |9411.0MiB|
|scrambled79760.smt2                                                                        |1200.123s |23.012GiB|
|scrambled19335.smt2                                                                        |1200.122s |16.48GiB|
|scrambled68944.smt2                                                                        |1200.103s |15.874GiB|
|scrambled27843.smt2                                                                        |1200.098s |11.186GiB|
|scrambled111627.smt2                                                                       |1200.088s |17.403GiB|
|scrambled39514.smt2                                                                        |1200.085s |15.201GiB|
|scrambled94658.smt2                                                                        |1200.084s |27.047GiB|
|scrambled102166.smt2                                                                       |1200.083s |21.232GiB|
|scrambled4198.smt2                                                                         |1200.075s |28.344GiB|
|scrambled103783.smt2                                                                       |1200.072s |14.676GiB|
|scrambled65181.smt2                                                                        |1200.071s |14.454GiB|
|scrambled75189.smt2                                                                        |1200.070s |15.016GiB|
|scrambled3854.smt2                                                                         |1200.070s |14.741GiB|
|scrambled107826.smt2                                                                       |1200.059s |14.793GiB|
|scrambled108840.smt2                                                                       |1200.059s |20.875GiB|
|scrambled59713.smt2                                                                        |1200.058s |14.953GiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled1417.smt2                                                                         |1200.466s |15.143GiB|
|scrambled79766.smt2                                                                        |1200.211s |14.717GiB|
|scrambled43577.smt2                                                                        |1200.149s |19.082GiB|
|scrambled107115.smt2                                                                       |1200.131s |9411.0MiB|
|scrambled79760.smt2                                                                        |1200.123s |23.012GiB|
|scrambled19335.smt2                                                                        |1200.122s |16.48GiB|
|scrambled68944.smt2                                                                        |1200.103s |15.874GiB|
|scrambled27843.smt2                                                                        |1200.098s |11.186GiB|
|scrambled111627.smt2                                                                       |1200.088s |17.403GiB|
|scrambled39514.smt2                                                                        |1200.085s |15.201GiB|
|scrambled94658.smt2                                                                        |1200.084s |27.047GiB|
|scrambled102166.smt2                                                                       |1200.083s |21.232GiB|
|scrambled4198.smt2                                                                         |1200.075s |28.344GiB|
|scrambled103783.smt2                                                                       |1200.072s |14.676GiB|
|scrambled65181.smt2                                                                        |1200.071s |14.454GiB|
|scrambled75189.smt2                                                                        |1200.070s |15.016GiB|
|scrambled3854.smt2                                                                         |1200.070s |14.741GiB|
|scrambled107826.smt2                                                                       |1200.059s |14.793GiB|
|scrambled108840.smt2                                                                       |1200.059s |20.875GiB|
|scrambled59713.smt2                                                                        |1200.058s |14.953GiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |21.232GiB|21.232GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |14.676GiB|14.676GiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |9411.0MiB|9411.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.793GiB|14.793GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |20.875GiB|20.875GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |17.403GiB|17.403GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |712.0MiB|712.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3160.0MiB|3160.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |28.349GiB|28.349GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |753.0MiB|753.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |907.0MiB|907.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2552.0MiB|2552.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2262.0MiB|2262.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |1827.0MiB|1827.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |3265.0MiB|3265.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |15.143GiB|15.143GiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |16.48GiB|16.48GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1152.0MiB|1152.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |2136.0MiB|2136.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.186GiB|11.186GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |21.232GiB|21.232GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |14.676GiB|14.676GiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |9411.0MiB|9411.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.793GiB|14.793GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |20.875GiB|20.875GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |17.403GiB|17.403GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |712.0MiB|712.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3160.0MiB|3160.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |28.349GiB|28.349GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |753.0MiB|753.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |907.0MiB|907.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2552.0MiB|2552.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2262.0MiB|2262.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |1827.0MiB|1827.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |3265.0MiB|3265.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |15.143GiB|15.143GiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |16.48GiB|16.48GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1152.0MiB|1152.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |2136.0MiB|2136.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.186GiB|11.186GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |21.232GiB|21.232GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |14.676GiB|14.676GiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |9411.0MiB|9411.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.793GiB|14.793GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |20.875GiB|20.875GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |17.403GiB|17.403GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |712.0MiB|712.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3160.0MiB|3160.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |28.349GiB|28.349GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |753.0MiB|753.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |907.0MiB|907.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2552.0MiB|2552.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2262.0MiB|2262.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |1827.0MiB|1827.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |3265.0MiB|3265.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |15.143GiB|15.143GiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |16.48GiB|16.48GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1152.0MiB|1152.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |2136.0MiB|2136.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.186GiB|11.186GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |21.232GiB|21.232GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |14.676GiB|14.676GiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |9411.0MiB|9411.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.793GiB|14.793GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |20.875GiB|20.875GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |17.403GiB|17.403GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |712.0MiB|712.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |3160.0MiB|3160.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |28.349GiB|28.349GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |753.0MiB|753.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |907.0MiB|907.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |2552.0MiB|2552.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2262.0MiB|2262.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |1827.0MiB|1827.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |3265.0MiB|3265.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |15.143GiB|15.143GiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |16.48GiB|16.48GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1152.0MiB|1152.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |2136.0MiB|2136.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |11.186GiB|11.186GiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled12042.smt2                                                                        |1200.055s |28.349GiB|
|scrambled4198.smt2                                                                         |1200.075s |28.344GiB|
|scrambled94658.smt2                                                                        |1200.084s |27.047GiB|
|scrambled55680.smt2                                                                        |1200.054s |23.938GiB|
|scrambled79760.smt2                                                                        |1200.123s |23.012GiB|
|scrambled102166.smt2                                                                       |1200.083s |21.232GiB|
|scrambled108840.smt2                                                                       |1200.059s |20.875GiB|
|scrambled43577.smt2                                                                        |1200.149s |19.082GiB|
|scrambled4299.smt2                                                                         |1200.055s |18.891GiB|
|scrambled111627.smt2                                                                       |1200.088s |17.403GiB|
|scrambled19335.smt2                                                                        |1200.122s |16.48GiB|
|scrambled68944.smt2                                                                        |1200.103s |15.874GiB|
|scrambled39514.smt2                                                                        |1200.085s |15.201GiB|
|scrambled1417.smt2                                                                         |1200.466s |15.143GiB|
|scrambled75189.smt2                                                                        |1200.070s |15.016GiB|
|scrambled59713.smt2                                                                        |1200.058s |14.953GiB|
|scrambled79867.smt2                                                                        |1130.758s |14.874GiB|
|scrambled45952.smt2                                                                        |1200.057s |14.808GiB|
|scrambled107826.smt2                                                                       |1200.059s |14.793GiB|
|scrambled3854.smt2                                                                         |1200.070s |14.741GiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled12042.smt2                                                                        |1200.055s |28.349GiB|
|scrambled4198.smt2                                                                         |1200.075s |28.344GiB|
|scrambled94658.smt2                                                                        |1200.084s |27.047GiB|
|scrambled55680.smt2                                                                        |1200.054s |23.938GiB|
|scrambled79760.smt2                                                                        |1200.123s |23.012GiB|
|scrambled102166.smt2                                                                       |1200.083s |21.232GiB|
|scrambled108840.smt2                                                                       |1200.059s |20.875GiB|
|scrambled43577.smt2                                                                        |1200.149s |19.082GiB|
|scrambled4299.smt2                                                                         |1200.055s |18.891GiB|
|scrambled111627.smt2                                                                       |1200.088s |17.403GiB|
|scrambled19335.smt2                                                                        |1200.122s |16.48GiB|
|scrambled68944.smt2                                                                        |1200.103s |15.874GiB|
|scrambled39514.smt2                                                                        |1200.085s |15.201GiB|
|scrambled1417.smt2                                                                         |1200.466s |15.143GiB|
|scrambled75189.smt2                                                                        |1200.070s |15.016GiB|
|scrambled59713.smt2                                                                        |1200.058s |14.953GiB|
|scrambled79867.smt2                                                                        |1130.758s |14.874GiB|
|scrambled45952.smt2                                                                        |1200.057s |14.808GiB|
|scrambled107826.smt2                                                                       |1200.059s |14.793GiB|
|scrambled3854.smt2                                                                         |1200.070s |14.741GiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.083s  |1200.083s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.072s  |1200.072s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.131s  |1200.131s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.059s  |1200.059s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.088s  |1200.088s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |1199.571s  |1199.571s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1199.973s  |1199.973s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |1199.740s  |1199.740s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 488.863s  | 488.863s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1199.857s  |1199.857s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1199.656s  |1199.656s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1199.699s  |1199.699s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1199.973s  |1199.973s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.466s  |1200.466s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.122s  |1200.122s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |1199.480s  |1199.480s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 121.052s  | 121.052s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.098s  |1200.098s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |1199.655s  |1199.655s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1199.806s  |1199.806s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1200.075s  |1200.075s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1200.149s  |1200.149s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1199.624s  |1199.624s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1200.057s  |1200.057s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1199.870s  |1199.870s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1200.054s  |1200.054s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1199.970s  |1199.970s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1200.071s  |1200.071s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1200.103s  |1200.103s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |1199.644s  |1199.644s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1200.011s  |1200.011s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1200.123s  |1200.123s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1200.211s  |1200.211s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1130.758s  |1130.758s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1200.084s  |1200.084s  |   0.000s  | 0.0%|
</details>
