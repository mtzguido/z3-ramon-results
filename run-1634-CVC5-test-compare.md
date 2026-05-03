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
Job tag: CVC5-test
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
|scrambled102166.smt2                                                                        |   9.891s  |   9.891s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |   9.955s  |   9.955s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |   9.884s  |   9.884s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |   9.430s  |   9.430s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |   9.412s  |   9.412s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |   9.806s  |   9.806s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   9.649s  |   9.649s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   9.838s  |   9.838s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |   9.445s  |   9.445s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |   9.311s  |   9.311s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   9.225s  |   9.225s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |   9.393s  |   9.393s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   9.750s  |   9.750s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |   9.314s  |   9.314s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   9.725s  |   9.725s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   9.706s  |   9.706s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |   9.783s  |   9.783s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   9.766s  |   9.766s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  10.017s  |  10.017s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |   9.860s  |   9.860s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |   9.891s  |   9.891s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |   9.955s  |   9.955s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |   9.884s  |   9.884s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |   9.430s  |   9.430s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |   9.412s  |   9.412s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |   9.806s  |   9.806s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   9.649s  |   9.649s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   9.838s  |   9.838s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |   9.445s  |   9.445s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |   9.311s  |   9.311s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   9.225s  |   9.225s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |   9.393s  |   9.393s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   9.750s  |   9.750s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |   9.314s  |   9.314s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   9.725s  |   9.725s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   9.706s  |   9.706s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |   9.783s  |   9.783s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   9.766s  |   9.766s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  10.017s  |  10.017s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |   9.860s  |   9.860s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |   9.891s  |   9.891s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |   9.955s  |   9.955s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |   9.884s  |   9.884s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |   9.430s  |   9.430s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |   9.412s  |   9.412s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |   9.806s  |   9.806s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   9.649s  |   9.649s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   9.838s  |   9.838s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |   9.445s  |   9.445s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |   9.311s  |   9.311s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   9.225s  |   9.225s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |   9.393s  |   9.393s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   9.750s  |   9.750s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |   9.314s  |   9.314s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   9.725s  |   9.725s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   9.706s  |   9.706s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |   9.783s  |   9.783s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   9.766s  |   9.766s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  10.017s  |  10.017s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |   9.860s  |   9.860s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |   9.891s  |   9.891s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |   9.955s  |   9.955s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |   9.884s  |   9.884s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |   9.430s  |   9.430s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |   9.412s  |   9.412s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |   9.806s  |   9.806s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   9.649s  |   9.649s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   9.838s  |   9.838s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |   9.445s  |   9.445s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |   9.311s  |   9.311s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   9.225s  |   9.225s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |   9.393s  |   9.393s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   9.750s  |   9.750s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |   9.314s  |   9.314s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   9.725s  |   9.725s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   9.706s  |   9.706s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |   9.783s  |   9.783s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   9.766s  |   9.766s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  10.017s  |  10.017s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |   9.860s  |   9.860s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled3854.smt2                                                                         |  10.138s |5010.0MiB|
|scrambled25238.smt2                                                                        |  10.017s |1502.0MiB|
|scrambled79766.smt2                                                                        |   9.958s |5021.0MiB|
|scrambled103783.smt2                                                                       |   9.955s |5246.0MiB|
|scrambled39514.smt2                                                                        |   9.895s |5258.0MiB|
|scrambled102166.smt2                                                                       |   9.891s |2782.0MiB|
|scrambled107115.smt2                                                                       |   9.884s |4360.0MiB|
|scrambled61922.smt2                                                                        |   9.866s |3468.0MiB|
|scrambled27843.smt2                                                                        |   9.860s |3502.0MiB|
|scrambled94658.smt2                                                                        |   9.853s |3089.0MiB|
|scrambled4198.smt2                                                                         |   9.846s |3125.0MiB|
|scrambled68944.smt2                                                                        |   9.843s |2420.0MiB|
|scrambled119331.smt2                                                                       |   9.838s |1850.0MiB|
|scrambled43577.smt2                                                                        |   9.831s |2543.0MiB|
|scrambled79760.smt2                                                                        |   9.827s |2455.0MiB|
|scrambled55777.smt2                                                                        |   9.820s |1231.0MiB|
|scrambled111627.smt2                                                                       |   9.806s |2501.0MiB|
|scrambled7741.smt2                                                                         |   9.785s |1554.0MiB|
|scrambled19335.smt2                                                                        |   9.783s |2608.0MiB|
|scrambled72668.smt2                                                                        |   9.771s |1201.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled3854.smt2                                                                         |  10.138s |5010.0MiB|
|scrambled25238.smt2                                                                        |  10.017s |1502.0MiB|
|scrambled79766.smt2                                                                        |   9.958s |5021.0MiB|
|scrambled103783.smt2                                                                       |   9.955s |5246.0MiB|
|scrambled39514.smt2                                                                        |   9.895s |5258.0MiB|
|scrambled102166.smt2                                                                       |   9.891s |2782.0MiB|
|scrambled107115.smt2                                                                       |   9.884s |4360.0MiB|
|scrambled61922.smt2                                                                        |   9.866s |3468.0MiB|
|scrambled27843.smt2                                                                        |   9.860s |3502.0MiB|
|scrambled94658.smt2                                                                        |   9.853s |3089.0MiB|
|scrambled4198.smt2                                                                         |   9.846s |3125.0MiB|
|scrambled68944.smt2                                                                        |   9.843s |2420.0MiB|
|scrambled119331.smt2                                                                       |   9.838s |1850.0MiB|
|scrambled43577.smt2                                                                        |   9.831s |2543.0MiB|
|scrambled79760.smt2                                                                        |   9.827s |2455.0MiB|
|scrambled55777.smt2                                                                        |   9.820s |1231.0MiB|
|scrambled111627.smt2                                                                       |   9.806s |2501.0MiB|
|scrambled7741.smt2                                                                         |   9.785s |1554.0MiB|
|scrambled19335.smt2                                                                        |   9.783s |2608.0MiB|
|scrambled72668.smt2                                                                        |   9.771s |1201.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |2782.0MiB|2782.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |5246.0MiB|5246.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |4360.0MiB|4360.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |2441.0MiB|2441.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |2611.0MiB|2611.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |2501.0MiB|2501.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |498.0MiB|498.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |1850.0MiB|1850.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |2879.0MiB|2879.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |543.0MiB|543.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |592.0MiB|592.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |1444.0MiB|1444.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |1132.0MiB|1132.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |1150.0MiB|1150.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |1396.0MiB|1396.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |310.0MiB|310.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |2608.0MiB|2608.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |656.0MiB|656.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |1502.0MiB|1502.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |3502.0MiB|3502.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |2782.0MiB|2782.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |5246.0MiB|5246.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |4360.0MiB|4360.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |2441.0MiB|2441.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |2611.0MiB|2611.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |2501.0MiB|2501.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |498.0MiB|498.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |1850.0MiB|1850.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |2879.0MiB|2879.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |543.0MiB|543.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |592.0MiB|592.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |1444.0MiB|1444.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |1132.0MiB|1132.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |1150.0MiB|1150.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |1396.0MiB|1396.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |310.0MiB|310.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |2608.0MiB|2608.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |656.0MiB|656.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |1502.0MiB|1502.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |3502.0MiB|3502.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |2782.0MiB|2782.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |5246.0MiB|5246.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |4360.0MiB|4360.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |2441.0MiB|2441.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |2611.0MiB|2611.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |2501.0MiB|2501.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |498.0MiB|498.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |1850.0MiB|1850.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |2879.0MiB|2879.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |543.0MiB|543.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |592.0MiB|592.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |1444.0MiB|1444.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |1132.0MiB|1132.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |1150.0MiB|1150.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |1396.0MiB|1396.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |310.0MiB|310.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |2608.0MiB|2608.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |656.0MiB|656.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |1502.0MiB|1502.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |3502.0MiB|3502.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |2782.0MiB|2782.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |5246.0MiB|5246.0MiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |4360.0MiB|4360.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |2441.0MiB|2441.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |2611.0MiB|2611.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |2501.0MiB|2501.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |498.0MiB|498.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |1850.0MiB|1850.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |2879.0MiB|2879.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |543.0MiB|543.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |592.0MiB|592.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |1444.0MiB|1444.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |1132.0MiB|1132.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |1150.0MiB|1150.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |1396.0MiB|1396.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |310.0MiB|310.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |2608.0MiB|2608.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |656.0MiB|656.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |1502.0MiB|1502.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |3502.0MiB|3502.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled39514.smt2                                                                        |   9.895s |5258.0MiB|
|scrambled103783.smt2                                                                       |   9.955s |5246.0MiB|
|scrambled79766.smt2                                                                        |   9.958s |5021.0MiB|
|scrambled3854.smt2                                                                         |  10.138s |5010.0MiB|
|scrambled79867.smt2                                                                        |   9.530s |4741.0MiB|
|scrambled65181.smt2                                                                        |   9.496s |4734.0MiB|
|scrambled59713.smt2                                                                        |   9.498s |4509.0MiB|
|scrambled45952.smt2                                                                        |   9.480s |4471.0MiB|
|scrambled107115.smt2                                                                       |   9.884s |4360.0MiB|
|scrambled27843.smt2                                                                        |   9.860s |3502.0MiB|
|scrambled61922.smt2                                                                        |   9.866s |3468.0MiB|
|scrambled4198.smt2                                                                         |   9.846s |3125.0MiB|
|scrambled94658.smt2                                                                        |   9.853s |3089.0MiB|
|scrambled12042.smt2                                                                        |   9.445s |2879.0MiB|
|scrambled55680.smt2                                                                        |   9.407s |2810.0MiB|
|scrambled102166.smt2                                                                       |   9.891s |2782.0MiB|
|scrambled75189.smt2                                                                        |   9.409s |2641.0MiB|
|scrambled108840.smt2                                                                       |   9.412s |2611.0MiB|
|scrambled19335.smt2                                                                        |   9.783s |2608.0MiB|
|scrambled4299.smt2                                                                         |   9.383s |2560.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled39514.smt2                                                                        |   9.895s |5258.0MiB|
|scrambled103783.smt2                                                                       |   9.955s |5246.0MiB|
|scrambled79766.smt2                                                                        |   9.958s |5021.0MiB|
|scrambled3854.smt2                                                                         |  10.138s |5010.0MiB|
|scrambled79867.smt2                                                                        |   9.530s |4741.0MiB|
|scrambled65181.smt2                                                                        |   9.496s |4734.0MiB|
|scrambled59713.smt2                                                                        |   9.498s |4509.0MiB|
|scrambled45952.smt2                                                                        |   9.480s |4471.0MiB|
|scrambled107115.smt2                                                                       |   9.884s |4360.0MiB|
|scrambled27843.smt2                                                                        |   9.860s |3502.0MiB|
|scrambled61922.smt2                                                                        |   9.866s |3468.0MiB|
|scrambled4198.smt2                                                                         |   9.846s |3125.0MiB|
|scrambled94658.smt2                                                                        |   9.853s |3089.0MiB|
|scrambled12042.smt2                                                                        |   9.445s |2879.0MiB|
|scrambled55680.smt2                                                                        |   9.407s |2810.0MiB|
|scrambled102166.smt2                                                                       |   9.891s |2782.0MiB|
|scrambled75189.smt2                                                                        |   9.409s |2641.0MiB|
|scrambled108840.smt2                                                                       |   9.412s |2611.0MiB|
|scrambled19335.smt2                                                                        |   9.783s |2608.0MiB|
|scrambled4299.smt2                                                                         |   9.383s |2560.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |   9.891s  |   9.891s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |   9.955s  |   9.955s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |   9.884s  |   9.884s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |   9.430s  |   9.430s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |   9.412s  |   9.412s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |   9.806s  |   9.806s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   9.649s  |   9.649s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |   9.838s  |   9.838s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |   9.445s  |   9.445s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |   9.311s  |   9.311s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   9.225s  |   9.225s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |   9.393s  |   9.393s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |   9.750s  |   9.750s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |   9.314s  |   9.314s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |   9.725s  |   9.725s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |   9.706s  |   9.706s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |   9.783s  |   9.783s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |   9.766s  |   9.766s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  10.017s  |  10.017s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |   9.860s  |   9.860s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |   9.291s  |   9.291s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |  10.138s  |  10.138s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |   9.895s  |   9.895s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |   9.380s  |   9.380s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |   9.846s  |   9.846s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |   9.383s  |   9.383s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |   9.831s  |   9.831s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |   9.754s  |   9.754s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |   9.480s  |   9.480s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |   9.766s  |   9.766s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |   9.407s  |   9.407s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |   9.820s  |   9.820s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |   9.498s  |   9.498s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |   9.866s  |   9.866s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |   9.496s  |   9.496s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |   9.843s  |   9.843s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |   9.771s  |   9.771s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |   9.409s  |   9.409s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |   9.785s  |   9.785s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |   9.827s  |   9.827s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |   9.958s  |   9.958s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |   9.530s  |   9.530s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |   9.853s  |   9.853s  |   0.000s  | 0.0%|
</details>
