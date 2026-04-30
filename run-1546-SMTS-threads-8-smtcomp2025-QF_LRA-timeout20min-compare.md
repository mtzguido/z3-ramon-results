Comparing data and data


# SUMMARY
- LHS tests = 38
- RHS tests = 38
- LHS success = 38  (100.0%)
- RHS success = 38  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for SMTS
-
Job description: 
Job tag: SMTS-threads-8-smtcomp2025-QF_LRA-timeout20min
Runner: rise-runner-2
SMTS repo: usi-verification-and-security/SMTS
SMTS commit: 33750b9094495eb1b86c1d7b796a0340ccf03822
SMTS branch: master
SMTS options: "-o 8 -p -l"
SMTS timeout: 1200
SMTS inputs: inputs/smt_comp_2025_parallel/QF_LRA
SMTS commit message: Reduced number of building cores in CircleCI

</pre>
# RHS
<pre>
Ramon benchmark for SMTS
-
Job description: 
Job tag: SMTS-threads-8-smtcomp2025-QF_LRA-timeout20min
Runner: rise-runner-2
SMTS repo: usi-verification-and-security/SMTS
SMTS commit: 33750b9094495eb1b86c1d7b796a0340ccf03822
SMTS branch: master
SMTS options: "-o 8 -p -l"
SMTS timeout: 1200
SMTS inputs: inputs/smt_comp_2025_parallel/QF_LRA
SMTS commit message: Reduced number of building cores in CircleCI

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.067s  |1200.067s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |  59.639s  |  59.639s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 279.065s  | 279.065s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        | 517.081s  | 517.081s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        | 102.394s  | 102.394s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        | 120.507s  | 120.507s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        |  19.361s  |  19.361s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |  34.537s  |  34.537s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.052s  |1200.052s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         | 520.344s  | 520.344s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         | 430.878s  | 430.878s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         | 749.062s  | 749.062s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.067s  |1200.067s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |  59.639s  |  59.639s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 279.065s  | 279.065s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        | 517.081s  | 517.081s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        | 102.394s  | 102.394s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        | 120.507s  | 120.507s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        |  19.361s  |  19.361s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |  34.537s  |  34.537s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.052s  |1200.052s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         | 520.344s  | 520.344s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         | 430.878s  | 430.878s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         | 749.062s  | 749.062s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.067s  |1200.067s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |  59.639s  |  59.639s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 279.065s  | 279.065s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        | 517.081s  | 517.081s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        | 102.394s  | 102.394s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        | 120.507s  | 120.507s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        |  19.361s  |  19.361s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |  34.537s  |  34.537s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.052s  |1200.052s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         | 520.344s  | 520.344s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         | 430.878s  | 430.878s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         | 749.062s  | 749.062s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.067s  |1200.067s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |  59.639s  |  59.639s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 279.065s  | 279.065s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        | 517.081s  | 517.081s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        | 102.394s  | 102.394s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        | 120.507s  | 120.507s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        |  19.361s  |  19.361s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |  34.537s  |  34.537s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.052s  |1200.052s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         | 520.344s  | 520.344s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         | 430.878s  | 430.878s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         | 749.062s  | 749.062s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled44527.smt2                                                                        |1200.123s |13.745GiB|
|scrambled65517.smt2                                                                        |1200.123s |3272.0MiB|
|scrambled76525.smt2                                                                        |1200.110s |2076.0MiB|
|scrambled95284.smt2                                                                        |1200.078s |2350.0MiB|
|scrambled55845.smt2                                                                        |1200.074s |1513.0MiB|
|scrambled49820.smt2                                                                        |1200.069s |1341.0MiB|
|scrambled92964.smt2                                                                        |1200.068s |1030.0MiB|
|scrambled101086.smt2                                                                       |1200.067s |1203.0MiB|
|scrambled111949.smt2                                                                       |1200.063s |6807.0MiB|
|scrambled77008.smt2                                                                        |1200.061s |4865.0MiB|
|scrambled76532.smt2                                                                        |1200.055s |490.0MiB|
|scrambled124681.smt2                                                                       |1200.052s |956.0MiB|
|scrambled13209.smt2                                                                        |1200.048s |7907.0MiB|
|scrambled77308.smt2                                                                        |1200.048s |2354.0MiB|
|scrambled35077.smt2                                                                        |1200.045s |494.0MiB|
|scrambled31085.smt2                                                                        |1200.044s |1651.0MiB|
|scrambled104811.smt2                                                                       |1200.042s |2225.0MiB|
|scrambled17583.smt2                                                                        |1200.042s |2891.0MiB|
|scrambled101728.smt2                                                                       |1200.040s |4209.0MiB|
|scrambled103576.smt2                                                                       |1200.037s |983.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled44527.smt2                                                                        |1200.123s |13.745GiB|
|scrambled65517.smt2                                                                        |1200.123s |3272.0MiB|
|scrambled76525.smt2                                                                        |1200.110s |2076.0MiB|
|scrambled95284.smt2                                                                        |1200.078s |2350.0MiB|
|scrambled55845.smt2                                                                        |1200.074s |1513.0MiB|
|scrambled49820.smt2                                                                        |1200.069s |1341.0MiB|
|scrambled92964.smt2                                                                        |1200.068s |1030.0MiB|
|scrambled101086.smt2                                                                       |1200.067s |1203.0MiB|
|scrambled111949.smt2                                                                       |1200.063s |6807.0MiB|
|scrambled77008.smt2                                                                        |1200.061s |4865.0MiB|
|scrambled76532.smt2                                                                        |1200.055s |490.0MiB|
|scrambled124681.smt2                                                                       |1200.052s |956.0MiB|
|scrambled13209.smt2                                                                        |1200.048s |7907.0MiB|
|scrambled77308.smt2                                                                        |1200.048s |2354.0MiB|
|scrambled35077.smt2                                                                        |1200.045s |494.0MiB|
|scrambled31085.smt2                                                                        |1200.044s |1651.0MiB|
|scrambled104811.smt2                                                                       |1200.042s |2225.0MiB|
|scrambled17583.smt2                                                                        |1200.042s |2891.0MiB|
|scrambled101728.smt2                                                                       |1200.040s |4209.0MiB|
|scrambled103576.smt2                                                                       |1200.037s |983.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1203.0MiB|1203.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |4209.0MiB|4209.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |5796.0MiB|5796.0MiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |4673.0MiB|4673.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |983.0MiB|983.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |2225.0MiB|2225.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |2554.0MiB|2554.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |6807.0MiB|6807.0MiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |342.0MiB|342.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |1421.0MiB|1421.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |254.0MiB|254.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |1181.0MiB|1181.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |956.0MiB|956.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |7959.0MiB|7959.0MiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |7907.0MiB|7907.0MiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |2891.0MiB|2891.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |7071.0MiB|7071.0MiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |1651.0MiB|1651.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |494.0MiB|494.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |2069.0MiB|2069.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1203.0MiB|1203.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |4209.0MiB|4209.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |5796.0MiB|5796.0MiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |4673.0MiB|4673.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |983.0MiB|983.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |2225.0MiB|2225.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |2554.0MiB|2554.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |6807.0MiB|6807.0MiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |342.0MiB|342.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |1421.0MiB|1421.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |254.0MiB|254.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |1181.0MiB|1181.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |956.0MiB|956.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |7959.0MiB|7959.0MiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |7907.0MiB|7907.0MiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |2891.0MiB|2891.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |7071.0MiB|7071.0MiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |1651.0MiB|1651.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |494.0MiB|494.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |2069.0MiB|2069.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1203.0MiB|1203.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |4209.0MiB|4209.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |5796.0MiB|5796.0MiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |4673.0MiB|4673.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |983.0MiB|983.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |2225.0MiB|2225.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |2554.0MiB|2554.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |6807.0MiB|6807.0MiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |342.0MiB|342.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |1421.0MiB|1421.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |254.0MiB|254.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |1181.0MiB|1181.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |956.0MiB|956.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |7959.0MiB|7959.0MiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |7907.0MiB|7907.0MiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |2891.0MiB|2891.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |7071.0MiB|7071.0MiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |1651.0MiB|1651.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |494.0MiB|494.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |2069.0MiB|2069.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1203.0MiB|1203.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |4209.0MiB|4209.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |5796.0MiB|5796.0MiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |4673.0MiB|4673.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |983.0MiB|983.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |2225.0MiB|2225.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |2554.0MiB|2554.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |6807.0MiB|6807.0MiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |342.0MiB|342.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |1421.0MiB|1421.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |254.0MiB|254.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |1181.0MiB|1181.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |956.0MiB|956.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |7959.0MiB|7959.0MiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |7907.0MiB|7907.0MiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |2891.0MiB|2891.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |7071.0MiB|7071.0MiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |1651.0MiB|1651.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |494.0MiB|494.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |2069.0MiB|2069.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled44527.smt2                                                                        |1200.123s |13.745GiB|
|scrambled8163.smt2                                                                         | 481.509s |8094.0MiB|
|scrambled13169.smt2                                                                        | 520.344s |7959.0MiB|
|scrambled13209.smt2                                                                        |1200.048s |7907.0MiB|
|scrambled25695.smt2                                                                        | 430.878s |7071.0MiB|
|scrambled111949.smt2                                                                       |1200.063s |6807.0MiB|
|scrambled102621.smt2                                                                       |  59.639s |5796.0MiB|
|scrambled55850.smt2                                                                        | 183.544s |5639.0MiB|
|scrambled98986.smt2                                                                        | 146.188s |5378.0MiB|
|scrambled77008.smt2                                                                        |1200.061s |4865.0MiB|
|scrambled102680.smt2                                                                       | 279.065s |4673.0MiB|
|scrambled101728.smt2                                                                       |1200.040s |4209.0MiB|
|scrambled65517.smt2                                                                        |1200.123s |3272.0MiB|
|scrambled17583.smt2                                                                        |1200.042s |2891.0MiB|
|scrambled109307.smt2                                                                       | 517.081s |2554.0MiB|
|scrambled77308.smt2                                                                        |1200.048s |2354.0MiB|
|scrambled95284.smt2                                                                        |1200.078s |2350.0MiB|
|scrambled104811.smt2                                                                       |1200.042s |2225.0MiB|
|scrambled76525.smt2                                                                        |1200.110s |2076.0MiB|
|scrambled37260.smt2                                                                        | 749.062s |2069.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled44527.smt2                                                                        |1200.123s |13.745GiB|
|scrambled8163.smt2                                                                         | 481.509s |8094.0MiB|
|scrambled13169.smt2                                                                        | 520.344s |7959.0MiB|
|scrambled13209.smt2                                                                        |1200.048s |7907.0MiB|
|scrambled25695.smt2                                                                        | 430.878s |7071.0MiB|
|scrambled111949.smt2                                                                       |1200.063s |6807.0MiB|
|scrambled102621.smt2                                                                       |  59.639s |5796.0MiB|
|scrambled55850.smt2                                                                        | 183.544s |5639.0MiB|
|scrambled98986.smt2                                                                        | 146.188s |5378.0MiB|
|scrambled77008.smt2                                                                        |1200.061s |4865.0MiB|
|scrambled102680.smt2                                                                       | 279.065s |4673.0MiB|
|scrambled101728.smt2                                                                       |1200.040s |4209.0MiB|
|scrambled65517.smt2                                                                        |1200.123s |3272.0MiB|
|scrambled17583.smt2                                                                        |1200.042s |2891.0MiB|
|scrambled109307.smt2                                                                       | 517.081s |2554.0MiB|
|scrambled77308.smt2                                                                        |1200.048s |2354.0MiB|
|scrambled95284.smt2                                                                        |1200.078s |2350.0MiB|
|scrambled104811.smt2                                                                       |1200.042s |2225.0MiB|
|scrambled76525.smt2                                                                        |1200.110s |2076.0MiB|
|scrambled37260.smt2                                                                        | 749.062s |2069.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.067s  |1200.067s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.040s  |1200.040s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |  59.639s  |  59.639s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 279.065s  | 279.065s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        | 517.081s  | 517.081s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        | 102.394s  | 102.394s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        | 120.507s  | 120.507s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        |  19.361s  |  19.361s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |  34.537s  |  34.537s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.052s  |1200.052s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         | 520.344s  | 520.344s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         | 430.878s  | 430.878s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         | 749.062s  | 749.062s  |   0.000s  | 0.0%|
|scrambled44527.smt2                                                                         |1200.123s  |1200.123s  |   0.000s  | 0.0%|
|scrambled46192.smt2                                                                         |  74.132s  |  74.132s  |   0.000s  | 0.0%|
|scrambled47581.smt2                                                                         |  58.532s  |  58.532s  |   0.000s  | 0.0%|
|scrambled49820.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled55845.smt2                                                                         |1200.074s  |1200.074s  |   0.000s  | 0.0%|
|scrambled55850.smt2                                                                         | 183.544s  | 183.544s  |   0.000s  | 0.0%|
|scrambled59368.smt2                                                                         | 112.282s  | 112.282s  |   0.000s  | 0.0%|
|scrambled65517.smt2                                                                         |1200.123s  |1200.123s  |   0.000s  | 0.0%|
|scrambled71015.smt2                                                                         | 147.938s  | 147.938s  |   0.000s  | 0.0%|
|scrambled76525.smt2                                                                         |1200.110s  |1200.110s  |   0.000s  | 0.0%|
|scrambled76532.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled77008.smt2                                                                         |1200.061s  |1200.061s  |   0.000s  | 0.0%|
|scrambled77308.smt2                                                                         |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled8163.smt2                                                                          | 481.509s  | 481.509s  |   0.000s  | 0.0%|
|scrambled88927.smt2                                                                         |  74.095s  |  74.095s  |   0.000s  | 0.0%|
|scrambled92964.smt2                                                                         |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled95284.smt2                                                                         |1200.078s  |1200.078s  |   0.000s  | 0.0%|
</details>
