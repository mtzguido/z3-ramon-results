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
Job tag: CVC5-threads-8-mode-portfolio-smtcomp2025-QF_RDL-timeout20min
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
Job tag: CVC5-threads-8-mode-portfolio-smtcomp2025-QF_RDL-timeout20min
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
|scrambled103130.smt2                                                                        |1199.969s  |1199.969s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1199.961s  |1199.961s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.007s  |1200.007s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1199.929s  |1199.929s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1199.878s  |1199.878s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1199.869s  |1199.869s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1199.857s  |1199.857s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1199.919s  |1199.919s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1199.809s  |1199.809s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         |1199.931s  |1199.931s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1199.999s  |1199.999s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.007s  |1200.007s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1199.840s  |1199.840s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1199.855s  |1199.855s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1199.778s  |1199.778s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1199.926s  |1199.926s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1199.882s  |1199.882s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1199.969s  |1199.969s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1199.961s  |1199.961s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.007s  |1200.007s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1199.929s  |1199.929s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1199.878s  |1199.878s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1199.869s  |1199.869s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1199.857s  |1199.857s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1199.919s  |1199.919s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1199.809s  |1199.809s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         |1199.931s  |1199.931s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1199.999s  |1199.999s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.007s  |1200.007s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1199.840s  |1199.840s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1199.855s  |1199.855s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1199.778s  |1199.778s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1199.926s  |1199.926s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1199.882s  |1199.882s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1199.969s  |1199.969s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1199.961s  |1199.961s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.007s  |1200.007s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1199.929s  |1199.929s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1199.878s  |1199.878s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1199.869s  |1199.869s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1199.857s  |1199.857s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1199.919s  |1199.919s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1199.809s  |1199.809s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         |1199.931s  |1199.931s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1199.999s  |1199.999s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.007s  |1200.007s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1199.840s  |1199.840s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1199.855s  |1199.855s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1199.778s  |1199.778s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1199.926s  |1199.926s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1199.882s  |1199.882s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1199.969s  |1199.969s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1199.961s  |1199.961s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.007s  |1200.007s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1199.929s  |1199.929s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1199.878s  |1199.878s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1199.869s  |1199.869s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1199.857s  |1199.857s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1199.919s  |1199.919s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1199.809s  |1199.809s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         |1199.931s  |1199.931s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1199.999s  |1199.999s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.007s  |1200.007s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1199.840s  |1199.840s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1199.855s  |1199.855s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1199.778s  |1199.778s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1199.926s  |1199.926s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1199.882s  |1199.882s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled64619.smt2                                                                        |1200.047s |1999.0MiB|
|scrambled68857.smt2                                                                        |1200.044s |1946.0MiB|
|scrambled120626.smt2                                                                       |1200.041s |2031.0MiB|
|scrambled106386.smt2                                                                       |1200.007s |1923.0MiB|
|scrambled36692.smt2                                                                        |1200.007s |2078.0MiB|
|scrambled36439.smt2                                                                        |1199.999s |1963.0MiB|
|scrambled103130.smt2                                                                       |1199.969s |830.0MiB|
|scrambled103636.smt2                                                                       |1199.961s |799.0MiB|
|scrambled95269.smt2                                                                        |1199.942s |817.0MiB|
|scrambled23753.smt2                                                                        |1199.931s |779.0MiB|
|scrambled111948.smt2                                                                       |1199.929s |818.0MiB|
|scrambled73226.smt2                                                                        |1199.926s |813.0MiB|
|scrambled55916.smt2                                                                        |1199.926s |808.0MiB|
|scrambled12077.smt2                                                                        |1199.919s |818.0MiB|
|scrambled7069.smt2                                                                         |1199.918s |847.0MiB|
|scrambled57711.smt2                                                                        |1199.882s |1955.0MiB|
|scrambled114492.smt2                                                                       |1199.878s |1963.0MiB|
|scrambled116502.smt2                                                                       |1199.869s |1930.0MiB|
|scrambled118796.smt2                                                                       |1199.857s |841.0MiB|
|scrambled43798.smt2                                                                        |1199.855s |850.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled64619.smt2                                                                        |1200.047s |1999.0MiB|
|scrambled68857.smt2                                                                        |1200.044s |1946.0MiB|
|scrambled120626.smt2                                                                       |1200.041s |2031.0MiB|
|scrambled106386.smt2                                                                       |1200.007s |1923.0MiB|
|scrambled36692.smt2                                                                        |1200.007s |2078.0MiB|
|scrambled36439.smt2                                                                        |1199.999s |1963.0MiB|
|scrambled103130.smt2                                                                       |1199.969s |830.0MiB|
|scrambled103636.smt2                                                                       |1199.961s |799.0MiB|
|scrambled95269.smt2                                                                        |1199.942s |817.0MiB|
|scrambled23753.smt2                                                                        |1199.931s |779.0MiB|
|scrambled111948.smt2                                                                       |1199.929s |818.0MiB|
|scrambled73226.smt2                                                                        |1199.926s |813.0MiB|
|scrambled55916.smt2                                                                        |1199.926s |808.0MiB|
|scrambled12077.smt2                                                                        |1199.919s |818.0MiB|
|scrambled7069.smt2                                                                         |1199.918s |847.0MiB|
|scrambled57711.smt2                                                                        |1199.882s |1955.0MiB|
|scrambled114492.smt2                                                                       |1199.878s |1963.0MiB|
|scrambled116502.smt2                                                                       |1199.869s |1930.0MiB|
|scrambled118796.smt2                                                                       |1199.857s |841.0MiB|
|scrambled43798.smt2                                                                        |1199.855s |850.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |830.0MiB|830.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |799.0MiB|799.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |1923.0MiB|1923.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |818.0MiB|818.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |1963.0MiB|1963.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |1930.0MiB|1930.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |841.0MiB|841.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |2031.0MiB|2031.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |818.0MiB|818.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |2005.0MiB|2005.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |779.0MiB|779.0MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |1963.0MiB|1963.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |2078.0MiB|2078.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |1978.0MiB|1978.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |850.0MiB|850.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |866.0MiB|866.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |808.0MiB|808.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |1955.0MiB|1955.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |1999.0MiB|1999.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |1946.0MiB|1946.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |830.0MiB|830.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |799.0MiB|799.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |1923.0MiB|1923.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |818.0MiB|818.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |1963.0MiB|1963.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |1930.0MiB|1930.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |841.0MiB|841.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |2031.0MiB|2031.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |818.0MiB|818.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |2005.0MiB|2005.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |779.0MiB|779.0MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |1963.0MiB|1963.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |2078.0MiB|2078.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |1978.0MiB|1978.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |850.0MiB|850.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |866.0MiB|866.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |808.0MiB|808.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |1955.0MiB|1955.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |1999.0MiB|1999.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |1946.0MiB|1946.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |830.0MiB|830.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |799.0MiB|799.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |1923.0MiB|1923.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |818.0MiB|818.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |1963.0MiB|1963.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |1930.0MiB|1930.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |841.0MiB|841.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |2031.0MiB|2031.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |818.0MiB|818.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |2005.0MiB|2005.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |779.0MiB|779.0MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |1963.0MiB|1963.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |2078.0MiB|2078.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |1978.0MiB|1978.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |850.0MiB|850.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |866.0MiB|866.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |808.0MiB|808.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |1955.0MiB|1955.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |1999.0MiB|1999.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |1946.0MiB|1946.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |830.0MiB|830.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |799.0MiB|799.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |1923.0MiB|1923.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |818.0MiB|818.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |1963.0MiB|1963.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |1930.0MiB|1930.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |841.0MiB|841.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |2031.0MiB|2031.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |818.0MiB|818.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |2005.0MiB|2005.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |779.0MiB|779.0MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |1963.0MiB|1963.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |2078.0MiB|2078.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |1978.0MiB|1978.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |850.0MiB|850.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |866.0MiB|866.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |808.0MiB|808.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |1955.0MiB|1955.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |1999.0MiB|1999.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |1946.0MiB|1946.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled36692.smt2                                                                        |1200.007s |2078.0MiB|
|scrambled120626.smt2                                                                       |1200.041s |2031.0MiB|
|scrambled19322.smt2                                                                        |1199.809s |2005.0MiB|
|scrambled64619.smt2                                                                        |1200.047s |1999.0MiB|
|scrambled43005.smt2                                                                        |1199.840s |1978.0MiB|
|scrambled36439.smt2                                                                        |1199.999s |1963.0MiB|
|scrambled114492.smt2                                                                       |1199.878s |1963.0MiB|
|scrambled57711.smt2                                                                        |1199.882s |1955.0MiB|
|scrambled68857.smt2                                                                        |1200.044s |1946.0MiB|
|scrambled116502.smt2                                                                       |1199.869s |1930.0MiB|
|scrambled106386.smt2                                                                       |1200.007s |1923.0MiB|
|scrambled69775.smt2                                                                        |1199.849s |868.0MiB|
|scrambled5175.smt2                                                                         |1199.778s |866.0MiB|
|scrambled43798.smt2                                                                        |1199.855s |850.0MiB|
|scrambled7069.smt2                                                                         |1199.918s |847.0MiB|
|scrambled118796.smt2                                                                       |1199.857s |841.0MiB|
|scrambled103130.smt2                                                                       |1199.969s |830.0MiB|
|scrambled111948.smt2                                                                       |1199.929s |818.0MiB|
|scrambled12077.smt2                                                                        |1199.919s |818.0MiB|
|scrambled95269.smt2                                                                        |1199.942s |817.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled36692.smt2                                                                        |1200.007s |2078.0MiB|
|scrambled120626.smt2                                                                       |1200.041s |2031.0MiB|
|scrambled19322.smt2                                                                        |1199.809s |2005.0MiB|
|scrambled64619.smt2                                                                        |1200.047s |1999.0MiB|
|scrambled43005.smt2                                                                        |1199.840s |1978.0MiB|
|scrambled36439.smt2                                                                        |1199.999s |1963.0MiB|
|scrambled114492.smt2                                                                       |1199.878s |1963.0MiB|
|scrambled57711.smt2                                                                        |1199.882s |1955.0MiB|
|scrambled68857.smt2                                                                        |1200.044s |1946.0MiB|
|scrambled116502.smt2                                                                       |1199.869s |1930.0MiB|
|scrambled106386.smt2                                                                       |1200.007s |1923.0MiB|
|scrambled69775.smt2                                                                        |1199.849s |868.0MiB|
|scrambled5175.smt2                                                                         |1199.778s |866.0MiB|
|scrambled43798.smt2                                                                        |1199.855s |850.0MiB|
|scrambled7069.smt2                                                                         |1199.918s |847.0MiB|
|scrambled118796.smt2                                                                       |1199.857s |841.0MiB|
|scrambled103130.smt2                                                                       |1199.969s |830.0MiB|
|scrambled111948.smt2                                                                       |1199.929s |818.0MiB|
|scrambled12077.smt2                                                                        |1199.919s |818.0MiB|
|scrambled95269.smt2                                                                        |1199.942s |817.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1199.969s  |1199.969s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1199.961s  |1199.961s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1200.007s  |1200.007s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1199.929s  |1199.929s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1199.878s  |1199.878s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1199.869s  |1199.869s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1199.857s  |1199.857s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1199.919s  |1199.919s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1199.809s  |1199.809s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         |1199.931s  |1199.931s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1199.999s  |1199.999s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1200.007s  |1200.007s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1199.840s  |1199.840s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1199.855s  |1199.855s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1199.778s  |1199.778s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1199.926s  |1199.926s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1199.882s  |1199.882s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1200.047s  |1200.047s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
|scrambled69775.smt2                                                                         |1199.849s  |1199.849s  |   0.000s  | 0.0%|
|scrambled7069.smt2                                                                          |1199.918s  |1199.918s  |   0.000s  | 0.0%|
|scrambled73226.smt2                                                                         |1199.926s  |1199.926s  |   0.000s  | 0.0%|
</details>
