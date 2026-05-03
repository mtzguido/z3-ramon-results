Comparing data and data


# SUMMARY
- LHS tests = 24
- RHS tests = 24
- LHS success = 24  (100.0%)
- RHS success = 24  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for cvc5
-
Job description: 
Job tag: CVC5-threads-1-mode-sequential-smtcomp2025-QF_RDL-timeout20min
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
cvc5 inputs: inputs/smt_comp_2025_parallel/QF_RDL
cvc5 commit message: Alethe add INTS_LOG2 and INTS_ISPOW2 (#12626)

These two operators do appear in the proofs of bit-vector benchmarks.

Co-authored-by: Haniel Barbosa <hanielbbarbosa@gmail.com>

</pre>
# RHS
<pre>
Ramon benchmark for cvc5
-
Job description: 
Job tag: CVC5-threads-1-mode-sequential-smtcomp2025-QF_RDL-timeout20min
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
cvc5 inputs: inputs/smt_comp_2025_parallel/QF_RDL
cvc5 commit message: Alethe add INTS_LOG2 and INTS_ISPOW2 (#12626)

These two operators do appear in the proofs of bit-vector benchmarks.

Co-authored-by: Haniel Barbosa <hanielbbarbosa@gmail.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.062s  |1200.062s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.062s  |1200.062s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.077s  |1200.077s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.062s  |1200.062s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.062s  |1200.062s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.077s  |1200.077s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.062s  |1200.062s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.062s  |1200.062s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.077s  |1200.077s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.062s  |1200.062s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.062s  |1200.062s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.077s  |1200.077s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled64619.smt2                                                                        |1200.077s |256.0MiB|
|scrambled120626.smt2                                                                       |1200.069s |259.0MiB|
|scrambled68857.smt2                                                                        |1200.069s |259.0MiB|
|scrambled103130.smt2                                                                       |1200.064s |172.0MiB|
|scrambled57711.smt2                                                                        |1200.063s |258.0MiB|
|scrambled19322.smt2                                                                        |1200.063s |258.0MiB|
|scrambled103636.smt2                                                                       |1200.062s |160.0MiB|
|scrambled106386.smt2                                                                       |1200.062s |260.0MiB|
|scrambled7069.smt2                                                                         |1200.052s |161.0MiB|
|scrambled95269.smt2                                                                        |1200.051s |159.0MiB|
|scrambled73226.smt2                                                                        |1200.051s |156.0MiB|
|scrambled36692.smt2                                                                        |1200.050s |265.0MiB|
|scrambled23753.smt2                                                                        |1200.050s |147.0MiB|
|scrambled36439.smt2                                                                        |1200.050s |262.0MiB|
|scrambled116502.smt2                                                                       |1200.049s |267.0MiB|
|scrambled69775.smt2                                                                        |1200.049s |155.0MiB|
|scrambled114492.smt2                                                                       |1200.049s |262.0MiB|
|scrambled43798.smt2                                                                        |1200.047s |133.0MiB|
|scrambled12077.smt2                                                                        |1200.047s |157.0MiB|
|scrambled43005.smt2                                                                        |1200.047s |263.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled64619.smt2                                                                        |1200.077s |256.0MiB|
|scrambled120626.smt2                                                                       |1200.069s |259.0MiB|
|scrambled68857.smt2                                                                        |1200.069s |259.0MiB|
|scrambled103130.smt2                                                                       |1200.064s |172.0MiB|
|scrambled57711.smt2                                                                        |1200.063s |258.0MiB|
|scrambled19322.smt2                                                                        |1200.063s |258.0MiB|
|scrambled103636.smt2                                                                       |1200.062s |160.0MiB|
|scrambled106386.smt2                                                                       |1200.062s |260.0MiB|
|scrambled7069.smt2                                                                         |1200.052s |161.0MiB|
|scrambled95269.smt2                                                                        |1200.051s |159.0MiB|
|scrambled73226.smt2                                                                        |1200.051s |156.0MiB|
|scrambled36692.smt2                                                                        |1200.050s |265.0MiB|
|scrambled23753.smt2                                                                        |1200.050s |147.0MiB|
|scrambled36439.smt2                                                                        |1200.050s |262.0MiB|
|scrambled116502.smt2                                                                       |1200.049s |267.0MiB|
|scrambled69775.smt2                                                                        |1200.049s |155.0MiB|
|scrambled114492.smt2                                                                       |1200.049s |262.0MiB|
|scrambled43798.smt2                                                                        |1200.047s |133.0MiB|
|scrambled12077.smt2                                                                        |1200.047s |157.0MiB|
|scrambled43005.smt2                                                                        |1200.047s |263.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |172.0MiB|172.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |160.0MiB|160.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |260.0MiB|260.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |151.0MiB|151.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |262.0MiB|262.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |267.0MiB|267.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |155.0MiB|155.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |259.0MiB|259.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |157.0MiB|157.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |258.0MiB|258.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |147.0MiB|147.0MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |262.0MiB|262.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |265.0MiB|265.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |263.0MiB|263.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |133.0MiB|133.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |146.0MiB|146.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |151.0MiB|151.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |258.0MiB|258.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |256.0MiB|256.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |259.0MiB|259.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |172.0MiB|172.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |160.0MiB|160.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |260.0MiB|260.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |151.0MiB|151.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |262.0MiB|262.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |267.0MiB|267.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |155.0MiB|155.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |259.0MiB|259.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |157.0MiB|157.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |258.0MiB|258.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |147.0MiB|147.0MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |262.0MiB|262.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |265.0MiB|265.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |263.0MiB|263.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |133.0MiB|133.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |146.0MiB|146.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |151.0MiB|151.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |258.0MiB|258.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |256.0MiB|256.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |259.0MiB|259.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |172.0MiB|172.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |160.0MiB|160.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |260.0MiB|260.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |151.0MiB|151.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |262.0MiB|262.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |267.0MiB|267.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |155.0MiB|155.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |259.0MiB|259.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |157.0MiB|157.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |258.0MiB|258.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |147.0MiB|147.0MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |262.0MiB|262.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |265.0MiB|265.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |263.0MiB|263.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |133.0MiB|133.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |146.0MiB|146.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |151.0MiB|151.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |258.0MiB|258.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |256.0MiB|256.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |259.0MiB|259.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |172.0MiB|172.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |160.0MiB|160.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |260.0MiB|260.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |151.0MiB|151.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |262.0MiB|262.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |267.0MiB|267.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |155.0MiB|155.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |259.0MiB|259.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |157.0MiB|157.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |258.0MiB|258.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |147.0MiB|147.0MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |262.0MiB|262.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |265.0MiB|265.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |263.0MiB|263.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |133.0MiB|133.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |146.0MiB|146.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |151.0MiB|151.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |258.0MiB|258.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |256.0MiB|256.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |259.0MiB|259.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled116502.smt2                                                                       |1200.049s |267.0MiB|
|scrambled36692.smt2                                                                        |1200.050s |265.0MiB|
|scrambled43005.smt2                                                                        |1200.047s |263.0MiB|
|scrambled36439.smt2                                                                        |1200.050s |262.0MiB|
|scrambled114492.smt2                                                                       |1200.049s |262.0MiB|
|scrambled106386.smt2                                                                       |1200.062s |260.0MiB|
|scrambled120626.smt2                                                                       |1200.069s |259.0MiB|
|scrambled68857.smt2                                                                        |1200.069s |259.0MiB|
|scrambled57711.smt2                                                                        |1200.063s |258.0MiB|
|scrambled19322.smt2                                                                        |1200.063s |258.0MiB|
|scrambled64619.smt2                                                                        |1200.077s |256.0MiB|
|scrambled103130.smt2                                                                       |1200.064s |172.0MiB|
|scrambled7069.smt2                                                                         |1200.052s |161.0MiB|
|scrambled103636.smt2                                                                       |1200.062s |160.0MiB|
|scrambled95269.smt2                                                                        |1200.051s |159.0MiB|
|scrambled12077.smt2                                                                        |1200.047s |157.0MiB|
|scrambled73226.smt2                                                                        |1200.051s |156.0MiB|
|scrambled69775.smt2                                                                        |1200.049s |155.0MiB|
|scrambled118796.smt2                                                                       |1200.039s |155.0MiB|
|scrambled55916.smt2                                                                        |1200.045s |151.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled116502.smt2                                                                       |1200.049s |267.0MiB|
|scrambled36692.smt2                                                                        |1200.050s |265.0MiB|
|scrambled43005.smt2                                                                        |1200.047s |263.0MiB|
|scrambled36439.smt2                                                                        |1200.050s |262.0MiB|
|scrambled114492.smt2                                                                       |1200.049s |262.0MiB|
|scrambled106386.smt2                                                                       |1200.062s |260.0MiB|
|scrambled120626.smt2                                                                       |1200.069s |259.0MiB|
|scrambled68857.smt2                                                                        |1200.069s |259.0MiB|
|scrambled57711.smt2                                                                        |1200.063s |258.0MiB|
|scrambled19322.smt2                                                                        |1200.063s |258.0MiB|
|scrambled64619.smt2                                                                        |1200.077s |256.0MiB|
|scrambled103130.smt2                                                                       |1200.064s |172.0MiB|
|scrambled7069.smt2                                                                         |1200.052s |161.0MiB|
|scrambled103636.smt2                                                                       |1200.062s |160.0MiB|
|scrambled95269.smt2                                                                        |1200.051s |159.0MiB|
|scrambled12077.smt2                                                                        |1200.047s |157.0MiB|
|scrambled73226.smt2                                                                        |1200.051s |156.0MiB|
|scrambled69775.smt2                                                                        |1200.049s |155.0MiB|
|scrambled118796.smt2                                                                       |1200.039s |155.0MiB|
|scrambled55916.smt2                                                                        |1200.045s |151.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1200.062s  |1200.062s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.062s  |1200.062s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1200.043s  |1200.043s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.077s  |1200.077s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled69775.smt2                                                                         |1200.049s  |1200.049s  |   0.000s  | 0.0%|
|scrambled7069.smt2                                                                          |1200.052s  |1200.052s  |   0.000s  | 0.0%|
|scrambled73226.smt2                                                                         |1200.051s  |1200.051s  |   0.000s  | 0.0%|
</details>
