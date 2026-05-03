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
Job tag: CVC5-threads-8-mode-partition-smtcomp2025-QF_RDL-timeout20min
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
Job tag: CVC5-threads-8-mode-partition-smtcomp2025-QF_RDL-timeout20min
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
|scrambled103130.smt2                                                                        |1199.918s  |1199.918s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1199.920s  |1199.920s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1199.974s  |1199.974s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1199.867s  |1199.867s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1199.915s  |1199.915s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1199.964s  |1199.964s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1199.841s  |1199.841s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1199.998s  |1199.998s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1199.872s  |1199.872s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1199.923s  |1199.923s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         |1199.859s  |1199.859s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1199.813s  |1199.813s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1199.950s  |1199.950s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1199.964s  |1199.964s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1199.876s  |1199.876s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1199.860s  |1199.860s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1199.857s  |1199.857s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1199.931s  |1199.931s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1199.969s  |1199.969s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.004s  |1200.004s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1199.918s  |1199.918s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1199.920s  |1199.920s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1199.974s  |1199.974s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1199.867s  |1199.867s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1199.915s  |1199.915s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1199.964s  |1199.964s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1199.841s  |1199.841s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1199.998s  |1199.998s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1199.872s  |1199.872s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1199.923s  |1199.923s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         |1199.859s  |1199.859s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1199.813s  |1199.813s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1199.950s  |1199.950s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1199.964s  |1199.964s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1199.876s  |1199.876s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1199.860s  |1199.860s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1199.857s  |1199.857s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1199.931s  |1199.931s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1199.969s  |1199.969s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.004s  |1200.004s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1199.918s  |1199.918s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1199.920s  |1199.920s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1199.974s  |1199.974s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1199.867s  |1199.867s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1199.915s  |1199.915s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1199.964s  |1199.964s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1199.841s  |1199.841s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1199.998s  |1199.998s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1199.872s  |1199.872s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1199.923s  |1199.923s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         |1199.859s  |1199.859s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1199.813s  |1199.813s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1199.950s  |1199.950s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1199.964s  |1199.964s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1199.876s  |1199.876s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1199.860s  |1199.860s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1199.857s  |1199.857s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1199.931s  |1199.931s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1199.969s  |1199.969s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.004s  |1200.004s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1199.918s  |1199.918s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1199.920s  |1199.920s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1199.974s  |1199.974s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1199.867s  |1199.867s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1199.915s  |1199.915s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1199.964s  |1199.964s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1199.841s  |1199.841s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1199.998s  |1199.998s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1199.872s  |1199.872s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1199.923s  |1199.923s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         |1199.859s  |1199.859s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1199.813s  |1199.813s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1199.950s  |1199.950s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1199.964s  |1199.964s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1199.876s  |1199.876s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1199.860s  |1199.860s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1199.857s  |1199.857s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1199.931s  |1199.931s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1199.969s  |1199.969s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.004s  |1200.004s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled68857.smt2                                                                        |1200.004s |2048.0MiB|
|scrambled120626.smt2                                                                       |1199.998s |2011.0MiB|
|scrambled106386.smt2                                                                       |1199.974s |2046.0MiB|
|scrambled64619.smt2                                                                        |1199.969s |2007.0MiB|
|scrambled116502.smt2                                                                       |1199.964s |2032.0MiB|
|scrambled43005.smt2                                                                        |1199.964s |2044.0MiB|
|scrambled36692.smt2                                                                        |1199.950s |1976.0MiB|
|scrambled57711.smt2                                                                        |1199.931s |2086.0MiB|
|scrambled19322.smt2                                                                        |1199.923s |2062.0MiB|
|scrambled103636.smt2                                                                       |1199.920s |1000.0MiB|
|scrambled103130.smt2                                                                       |1199.918s |1022.0MiB|
|scrambled7069.smt2                                                                         |1199.915s |1140.0MiB|
|scrambled114492.smt2                                                                       |1199.915s |2039.0MiB|
|scrambled73226.smt2                                                                        |1199.877s |1009.0MiB|
|scrambled43798.smt2                                                                        |1199.876s |768.0MiB|
|scrambled12077.smt2                                                                        |1199.872s |1058.0MiB|
|scrambled111948.smt2                                                                       |1199.867s |746.0MiB|
|scrambled5175.smt2                                                                         |1199.860s |580.0MiB|
|scrambled23753.smt2                                                                        |1199.859s |925.0MiB|
|scrambled55916.smt2                                                                        |1199.857s |1023.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled68857.smt2                                                                        |1200.004s |2048.0MiB|
|scrambled120626.smt2                                                                       |1199.998s |2011.0MiB|
|scrambled106386.smt2                                                                       |1199.974s |2046.0MiB|
|scrambled64619.smt2                                                                        |1199.969s |2007.0MiB|
|scrambled116502.smt2                                                                       |1199.964s |2032.0MiB|
|scrambled43005.smt2                                                                        |1199.964s |2044.0MiB|
|scrambled36692.smt2                                                                        |1199.950s |1976.0MiB|
|scrambled57711.smt2                                                                        |1199.931s |2086.0MiB|
|scrambled19322.smt2                                                                        |1199.923s |2062.0MiB|
|scrambled103636.smt2                                                                       |1199.920s |1000.0MiB|
|scrambled103130.smt2                                                                       |1199.918s |1022.0MiB|
|scrambled7069.smt2                                                                         |1199.915s |1140.0MiB|
|scrambled114492.smt2                                                                       |1199.915s |2039.0MiB|
|scrambled73226.smt2                                                                        |1199.877s |1009.0MiB|
|scrambled43798.smt2                                                                        |1199.876s |768.0MiB|
|scrambled12077.smt2                                                                        |1199.872s |1058.0MiB|
|scrambled111948.smt2                                                                       |1199.867s |746.0MiB|
|scrambled5175.smt2                                                                         |1199.860s |580.0MiB|
|scrambled23753.smt2                                                                        |1199.859s |925.0MiB|
|scrambled55916.smt2                                                                        |1199.857s |1023.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1022.0MiB|1022.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |1000.0MiB|1000.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |2046.0MiB|2046.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |746.0MiB|746.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |2039.0MiB|2039.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |2032.0MiB|2032.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |1085.0MiB|1085.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |2011.0MiB|2011.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |1058.0MiB|1058.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |2062.0MiB|2062.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |925.0MiB|925.0MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |2005.0MiB|2005.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |1976.0MiB|1976.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |2044.0MiB|2044.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |768.0MiB|768.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |580.0MiB|580.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |1023.0MiB|1023.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |2086.0MiB|2086.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |2007.0MiB|2007.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |2048.0MiB|2048.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1022.0MiB|1022.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |1000.0MiB|1000.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |2046.0MiB|2046.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |746.0MiB|746.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |2039.0MiB|2039.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |2032.0MiB|2032.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |1085.0MiB|1085.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |2011.0MiB|2011.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |1058.0MiB|1058.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |2062.0MiB|2062.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |925.0MiB|925.0MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |2005.0MiB|2005.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |1976.0MiB|1976.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |2044.0MiB|2044.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |768.0MiB|768.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |580.0MiB|580.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |1023.0MiB|1023.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |2086.0MiB|2086.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |2007.0MiB|2007.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |2048.0MiB|2048.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1022.0MiB|1022.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |1000.0MiB|1000.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |2046.0MiB|2046.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |746.0MiB|746.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |2039.0MiB|2039.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |2032.0MiB|2032.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |1085.0MiB|1085.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |2011.0MiB|2011.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |1058.0MiB|1058.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |2062.0MiB|2062.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |925.0MiB|925.0MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |2005.0MiB|2005.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |1976.0MiB|1976.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |2044.0MiB|2044.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |768.0MiB|768.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |580.0MiB|580.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |1023.0MiB|1023.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |2086.0MiB|2086.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |2007.0MiB|2007.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |2048.0MiB|2048.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1022.0MiB|1022.0MiB|0B| 0.0%|
|scrambled103636.smt2                                                                        |1000.0MiB|1000.0MiB|0B| 0.0%|
|scrambled106386.smt2                                                                        |2046.0MiB|2046.0MiB|0B| 0.0%|
|scrambled111948.smt2                                                                        |746.0MiB|746.0MiB|0B| 0.0%|
|scrambled114492.smt2                                                                        |2039.0MiB|2039.0MiB|0B| 0.0%|
|scrambled116502.smt2                                                                        |2032.0MiB|2032.0MiB|0B| 0.0%|
|scrambled118796.smt2                                                                        |1085.0MiB|1085.0MiB|0B| 0.0%|
|scrambled120626.smt2                                                                        |2011.0MiB|2011.0MiB|0B| 0.0%|
|scrambled12077.smt2                                                                         |1058.0MiB|1058.0MiB|0B| 0.0%|
|scrambled19322.smt2                                                                         |2062.0MiB|2062.0MiB|0B| 0.0%|
|scrambled23753.smt2                                                                         |925.0MiB|925.0MiB|0B| 0.0%|
|scrambled36439.smt2                                                                         |2005.0MiB|2005.0MiB|0B| 0.0%|
|scrambled36692.smt2                                                                         |1976.0MiB|1976.0MiB|0B| 0.0%|
|scrambled43005.smt2                                                                         |2044.0MiB|2044.0MiB|0B| 0.0%|
|scrambled43798.smt2                                                                         |768.0MiB|768.0MiB|0B| 0.0%|
|scrambled5175.smt2                                                                          |580.0MiB|580.0MiB|0B| 0.0%|
|scrambled55916.smt2                                                                         |1023.0MiB|1023.0MiB|0B| 0.0%|
|scrambled57711.smt2                                                                         |2086.0MiB|2086.0MiB|0B| 0.0%|
|scrambled64619.smt2                                                                         |2007.0MiB|2007.0MiB|0B| 0.0%|
|scrambled68857.smt2                                                                         |2048.0MiB|2048.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled57711.smt2                                                                        |1199.931s |2086.0MiB|
|scrambled19322.smt2                                                                        |1199.923s |2062.0MiB|
|scrambled68857.smt2                                                                        |1200.004s |2048.0MiB|
|scrambled106386.smt2                                                                       |1199.974s |2046.0MiB|
|scrambled43005.smt2                                                                        |1199.964s |2044.0MiB|
|scrambled114492.smt2                                                                       |1199.915s |2039.0MiB|
|scrambled116502.smt2                                                                       |1199.964s |2032.0MiB|
|scrambled120626.smt2                                                                       |1199.998s |2011.0MiB|
|scrambled64619.smt2                                                                        |1199.969s |2007.0MiB|
|scrambled36439.smt2                                                                        |1199.813s |2005.0MiB|
|scrambled36692.smt2                                                                        |1199.950s |1976.0MiB|
|scrambled7069.smt2                                                                         |1199.915s |1140.0MiB|
|scrambled118796.smt2                                                                       |1199.841s |1085.0MiB|
|scrambled12077.smt2                                                                        |1199.872s |1058.0MiB|
|scrambled55916.smt2                                                                        |1199.857s |1023.0MiB|
|scrambled103130.smt2                                                                       |1199.918s |1022.0MiB|
|scrambled73226.smt2                                                                        |1199.877s |1009.0MiB|
|scrambled103636.smt2                                                                       |1199.920s |1000.0MiB|
|scrambled23753.smt2                                                                        |1199.859s |925.0MiB|
|scrambled69775.smt2                                                                        |1199.824s |824.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled57711.smt2                                                                        |1199.931s |2086.0MiB|
|scrambled19322.smt2                                                                        |1199.923s |2062.0MiB|
|scrambled68857.smt2                                                                        |1200.004s |2048.0MiB|
|scrambled106386.smt2                                                                       |1199.974s |2046.0MiB|
|scrambled43005.smt2                                                                        |1199.964s |2044.0MiB|
|scrambled114492.smt2                                                                       |1199.915s |2039.0MiB|
|scrambled116502.smt2                                                                       |1199.964s |2032.0MiB|
|scrambled120626.smt2                                                                       |1199.998s |2011.0MiB|
|scrambled64619.smt2                                                                        |1199.969s |2007.0MiB|
|scrambled36439.smt2                                                                        |1199.813s |2005.0MiB|
|scrambled36692.smt2                                                                        |1199.950s |1976.0MiB|
|scrambled7069.smt2                                                                         |1199.915s |1140.0MiB|
|scrambled118796.smt2                                                                       |1199.841s |1085.0MiB|
|scrambled12077.smt2                                                                        |1199.872s |1058.0MiB|
|scrambled55916.smt2                                                                        |1199.857s |1023.0MiB|
|scrambled103130.smt2                                                                       |1199.918s |1022.0MiB|
|scrambled73226.smt2                                                                        |1199.877s |1009.0MiB|
|scrambled103636.smt2                                                                       |1199.920s |1000.0MiB|
|scrambled23753.smt2                                                                        |1199.859s |925.0MiB|
|scrambled69775.smt2                                                                        |1199.824s |824.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled103130.smt2                                                                        |1199.918s  |1199.918s  |   0.000s  | 0.0%|
|scrambled103636.smt2                                                                        |1199.920s  |1199.920s  |   0.000s  | 0.0%|
|scrambled106386.smt2                                                                        |1199.974s  |1199.974s  |   0.000s  | 0.0%|
|scrambled111948.smt2                                                                        |1199.867s  |1199.867s  |   0.000s  | 0.0%|
|scrambled114492.smt2                                                                        |1199.915s  |1199.915s  |   0.000s  | 0.0%|
|scrambled116502.smt2                                                                        |1199.964s  |1199.964s  |   0.000s  | 0.0%|
|scrambled118796.smt2                                                                        |1199.841s  |1199.841s  |   0.000s  | 0.0%|
|scrambled120626.smt2                                                                        |1199.998s  |1199.998s  |   0.000s  | 0.0%|
|scrambled12077.smt2                                                                         |1199.872s  |1199.872s  |   0.000s  | 0.0%|
|scrambled19322.smt2                                                                         |1199.923s  |1199.923s  |   0.000s  | 0.0%|
|scrambled23753.smt2                                                                         |1199.859s  |1199.859s  |   0.000s  | 0.0%|
|scrambled36439.smt2                                                                         |1199.813s  |1199.813s  |   0.000s  | 0.0%|
|scrambled36692.smt2                                                                         |1199.950s  |1199.950s  |   0.000s  | 0.0%|
|scrambled43005.smt2                                                                         |1199.964s  |1199.964s  |   0.000s  | 0.0%|
|scrambled43798.smt2                                                                         |1199.876s  |1199.876s  |   0.000s  | 0.0%|
|scrambled5175.smt2                                                                          |1199.860s  |1199.860s  |   0.000s  | 0.0%|
|scrambled55916.smt2                                                                         |1199.857s  |1199.857s  |   0.000s  | 0.0%|
|scrambled57711.smt2                                                                         |1199.931s  |1199.931s  |   0.000s  | 0.0%|
|scrambled64619.smt2                                                                         |1199.969s  |1199.969s  |   0.000s  | 0.0%|
|scrambled68857.smt2                                                                         |1200.004s  |1200.004s  |   0.000s  | 0.0%|
|scrambled69775.smt2                                                                         |1199.824s  |1199.824s  |   0.000s  | 0.0%|
|scrambled7069.smt2                                                                          |1199.915s  |1199.915s  |   0.000s  | 0.0%|
|scrambled73226.smt2                                                                         |1199.877s  |1199.877s  |   0.000s  | 0.0%|
</details>
