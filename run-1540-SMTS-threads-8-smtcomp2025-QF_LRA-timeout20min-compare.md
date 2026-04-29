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
|scrambled101086.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        | 603.364s  | 603.364s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |  78.134s  |  78.134s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 104.022s  | 104.022s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.108s  |1200.108s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.084s  |1200.084s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        | 510.675s  | 510.675s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |  61.540s  |  61.540s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        | 156.637s  | 156.637s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        |  17.568s  |  17.568s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |  39.217s  |  39.217s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.074s  |1200.074s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         | 496.776s  | 496.776s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.103s  |1200.103s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         | 494.945s  | 494.945s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         | 981.626s  | 981.626s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         | 208.825s  | 208.825s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        | 603.364s  | 603.364s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |  78.134s  |  78.134s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 104.022s  | 104.022s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.108s  |1200.108s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.084s  |1200.084s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        | 510.675s  | 510.675s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |  61.540s  |  61.540s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        | 156.637s  | 156.637s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        |  17.568s  |  17.568s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |  39.217s  |  39.217s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.074s  |1200.074s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         | 496.776s  | 496.776s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.103s  |1200.103s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         | 494.945s  | 494.945s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         | 981.626s  | 981.626s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         | 208.825s  | 208.825s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        | 603.364s  | 603.364s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |  78.134s  |  78.134s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 104.022s  | 104.022s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.108s  |1200.108s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.084s  |1200.084s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        | 510.675s  | 510.675s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |  61.540s  |  61.540s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        | 156.637s  | 156.637s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        |  17.568s  |  17.568s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |  39.217s  |  39.217s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.074s  |1200.074s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         | 496.776s  | 496.776s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.103s  |1200.103s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         | 494.945s  | 494.945s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         | 981.626s  | 981.626s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         | 208.825s  | 208.825s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        | 603.364s  | 603.364s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |  78.134s  |  78.134s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 104.022s  | 104.022s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.108s  |1200.108s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.084s  |1200.084s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        | 510.675s  | 510.675s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |  61.540s  |  61.540s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        | 156.637s  | 156.637s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        |  17.568s  |  17.568s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |  39.217s  |  39.217s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.074s  |1200.074s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         | 496.776s  | 496.776s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.103s  |1200.103s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         | 494.945s  | 494.945s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         | 981.626s  | 981.626s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         | 208.825s  | 208.825s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled103576.smt2                                                                       |1200.108s |1066.0MiB|
|scrambled13209.smt2                                                                        |1200.103s |7815.0MiB|
|scrambled104811.smt2                                                                       |1200.084s |2325.0MiB|
|scrambled124681.smt2                                                                       |1200.074s |836.0MiB|
|scrambled17583.smt2                                                                        |1200.064s |2850.0MiB|
|scrambled44527.smt2                                                                        |1200.063s |13.798GiB|
|scrambled92964.smt2                                                                        |1200.062s |1043.0MiB|
|scrambled49820.smt2                                                                        |1200.060s |1384.0MiB|
|scrambled77308.smt2                                                                        |1200.055s |2234.0MiB|
|scrambled76532.smt2                                                                        |1200.054s |481.0MiB|
|scrambled76525.smt2                                                                        |1200.051s |2034.0MiB|
|scrambled31085.smt2                                                                        |1200.048s |1578.0MiB|
|scrambled55845.smt2                                                                        |1200.048s |1459.0MiB|
|scrambled65517.smt2                                                                        |1200.042s |3275.0MiB|
|scrambled111949.smt2                                                                       |1200.039s |6908.0MiB|
|scrambled101086.smt2                                                                       |1200.035s |1221.0MiB|
|scrambled77008.smt2                                                                        |1012.707s |4830.0MiB|
|scrambled35077.smt2                                                                        | 981.626s |512.0MiB|
|scrambled101728.smt2                                                                       | 603.364s |3928.0MiB|
|scrambled95284.smt2                                                                        | 570.052s |2114.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled103576.smt2                                                                       |1200.108s |1066.0MiB|
|scrambled13209.smt2                                                                        |1200.103s |7815.0MiB|
|scrambled104811.smt2                                                                       |1200.084s |2325.0MiB|
|scrambled124681.smt2                                                                       |1200.074s |836.0MiB|
|scrambled17583.smt2                                                                        |1200.064s |2850.0MiB|
|scrambled44527.smt2                                                                        |1200.063s |13.798GiB|
|scrambled92964.smt2                                                                        |1200.062s |1043.0MiB|
|scrambled49820.smt2                                                                        |1200.060s |1384.0MiB|
|scrambled77308.smt2                                                                        |1200.055s |2234.0MiB|
|scrambled76532.smt2                                                                        |1200.054s |481.0MiB|
|scrambled76525.smt2                                                                        |1200.051s |2034.0MiB|
|scrambled31085.smt2                                                                        |1200.048s |1578.0MiB|
|scrambled55845.smt2                                                                        |1200.048s |1459.0MiB|
|scrambled65517.smt2                                                                        |1200.042s |3275.0MiB|
|scrambled111949.smt2                                                                       |1200.039s |6908.0MiB|
|scrambled101086.smt2                                                                       |1200.035s |1221.0MiB|
|scrambled77008.smt2                                                                        |1012.707s |4830.0MiB|
|scrambled35077.smt2                                                                        | 981.626s |512.0MiB|
|scrambled101728.smt2                                                                       | 603.364s |3928.0MiB|
|scrambled95284.smt2                                                                        | 570.052s |2114.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1221.0MiB|1221.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |3928.0MiB|3928.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |5979.0MiB|5979.0MiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |4308.0MiB|4308.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |1066.0MiB|1066.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |2325.0MiB|2325.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |2497.0MiB|2497.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |6908.0MiB|6908.0MiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |276.0MiB|276.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |1443.0MiB|1443.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |260.0MiB|260.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |1202.0MiB|1202.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |836.0MiB|836.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |7934.0MiB|7934.0MiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |7815.0MiB|7815.0MiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |2850.0MiB|2850.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |7246.0MiB|7246.0MiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |1578.0MiB|1578.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |512.0MiB|512.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |1584.0MiB|1584.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1221.0MiB|1221.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |3928.0MiB|3928.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |5979.0MiB|5979.0MiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |4308.0MiB|4308.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |1066.0MiB|1066.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |2325.0MiB|2325.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |2497.0MiB|2497.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |6908.0MiB|6908.0MiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |276.0MiB|276.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |1443.0MiB|1443.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |260.0MiB|260.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |1202.0MiB|1202.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |836.0MiB|836.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |7934.0MiB|7934.0MiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |7815.0MiB|7815.0MiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |2850.0MiB|2850.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |7246.0MiB|7246.0MiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |1578.0MiB|1578.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |512.0MiB|512.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |1584.0MiB|1584.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1221.0MiB|1221.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |3928.0MiB|3928.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |5979.0MiB|5979.0MiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |4308.0MiB|4308.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |1066.0MiB|1066.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |2325.0MiB|2325.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |2497.0MiB|2497.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |6908.0MiB|6908.0MiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |276.0MiB|276.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |1443.0MiB|1443.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |260.0MiB|260.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |1202.0MiB|1202.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |836.0MiB|836.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |7934.0MiB|7934.0MiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |7815.0MiB|7815.0MiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |2850.0MiB|2850.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |7246.0MiB|7246.0MiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |1578.0MiB|1578.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |512.0MiB|512.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |1584.0MiB|1584.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1221.0MiB|1221.0MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |3928.0MiB|3928.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |5979.0MiB|5979.0MiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |4308.0MiB|4308.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |1066.0MiB|1066.0MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |2325.0MiB|2325.0MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |2497.0MiB|2497.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |6908.0MiB|6908.0MiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |276.0MiB|276.0MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |1443.0MiB|1443.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |260.0MiB|260.0MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |1202.0MiB|1202.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |836.0MiB|836.0MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |7934.0MiB|7934.0MiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |7815.0MiB|7815.0MiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |2850.0MiB|2850.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |7246.0MiB|7246.0MiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |1578.0MiB|1578.0MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |512.0MiB|512.0MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |1584.0MiB|1584.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled44527.smt2                                                                        |1200.063s |13.798GiB|
|scrambled8163.smt2                                                                         | 521.049s |8282.0MiB|
|scrambled13169.smt2                                                                        | 496.776s |7934.0MiB|
|scrambled13209.smt2                                                                        |1200.103s |7815.0MiB|
|scrambled25695.smt2                                                                        | 494.945s |7246.0MiB|
|scrambled111949.smt2                                                                       |1200.039s |6908.0MiB|
|scrambled102621.smt2                                                                       |  78.134s |5979.0MiB|
|scrambled55850.smt2                                                                        | 185.128s |5748.0MiB|
|scrambled98986.smt2                                                                        | 143.107s |5354.0MiB|
|scrambled77008.smt2                                                                        |1012.707s |4830.0MiB|
|scrambled102680.smt2                                                                       | 104.022s |4308.0MiB|
|scrambled101728.smt2                                                                       | 603.364s |3928.0MiB|
|scrambled65517.smt2                                                                        |1200.042s |3275.0MiB|
|scrambled17583.smt2                                                                        |1200.064s |2850.0MiB|
|scrambled109307.smt2                                                                       | 510.675s |2497.0MiB|
|scrambled104811.smt2                                                                       |1200.084s |2325.0MiB|
|scrambled77308.smt2                                                                        |1200.055s |2234.0MiB|
|scrambled95284.smt2                                                                        | 570.052s |2114.0MiB|
|scrambled76525.smt2                                                                        |1200.051s |2034.0MiB|
|scrambled37260.smt2                                                                        | 208.825s |1584.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled44527.smt2                                                                        |1200.063s |13.798GiB|
|scrambled8163.smt2                                                                         | 521.049s |8282.0MiB|
|scrambled13169.smt2                                                                        | 496.776s |7934.0MiB|
|scrambled13209.smt2                                                                        |1200.103s |7815.0MiB|
|scrambled25695.smt2                                                                        | 494.945s |7246.0MiB|
|scrambled111949.smt2                                                                       |1200.039s |6908.0MiB|
|scrambled102621.smt2                                                                       |  78.134s |5979.0MiB|
|scrambled55850.smt2                                                                        | 185.128s |5748.0MiB|
|scrambled98986.smt2                                                                        | 143.107s |5354.0MiB|
|scrambled77008.smt2                                                                        |1012.707s |4830.0MiB|
|scrambled102680.smt2                                                                       | 104.022s |4308.0MiB|
|scrambled101728.smt2                                                                       | 603.364s |3928.0MiB|
|scrambled65517.smt2                                                                        |1200.042s |3275.0MiB|
|scrambled17583.smt2                                                                        |1200.064s |2850.0MiB|
|scrambled109307.smt2                                                                       | 510.675s |2497.0MiB|
|scrambled104811.smt2                                                                       |1200.084s |2325.0MiB|
|scrambled77308.smt2                                                                        |1200.055s |2234.0MiB|
|scrambled95284.smt2                                                                        | 570.052s |2114.0MiB|
|scrambled76525.smt2                                                                        |1200.051s |2034.0MiB|
|scrambled37260.smt2                                                                        | 208.825s |1584.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        | 603.364s  | 603.364s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |  78.134s  |  78.134s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 104.022s  | 104.022s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.108s  |1200.108s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.084s  |1200.084s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        | 510.675s  | 510.675s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |  61.540s  |  61.540s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        | 156.637s  | 156.637s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        |  17.568s  |  17.568s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |  39.217s  |  39.217s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.074s  |1200.074s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         | 496.776s  | 496.776s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.103s  |1200.103s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         | 494.945s  | 494.945s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         | 981.626s  | 981.626s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         | 208.825s  | 208.825s  |   0.000s  | 0.0%|
|scrambled44527.smt2                                                                         |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled46192.smt2                                                                         |  95.736s  |  95.736s  |   0.000s  | 0.0%|
|scrambled47581.smt2                                                                         |  75.894s  |  75.894s  |   0.000s  | 0.0%|
|scrambled49820.smt2                                                                         |1200.060s  |1200.060s  |   0.000s  | 0.0%|
|scrambled55845.smt2                                                                         |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled55850.smt2                                                                         | 185.128s  | 185.128s  |   0.000s  | 0.0%|
|scrambled59368.smt2                                                                         | 138.269s  | 138.269s  |   0.000s  | 0.0%|
|scrambled65517.smt2                                                                         |1200.042s  |1200.042s  |   0.000s  | 0.0%|
|scrambled71015.smt2                                                                         | 148.171s  | 148.171s  |   0.000s  | 0.0%|
|scrambled76525.smt2                                                                         |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled76532.smt2                                                                         |1200.054s  |1200.054s  |   0.000s  | 0.0%|
|scrambled77008.smt2                                                                         |1012.707s  |1012.707s  |   0.000s  | 0.0%|
|scrambled77308.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled8163.smt2                                                                          | 521.049s  | 521.049s  |   0.000s  | 0.0%|
|scrambled88927.smt2                                                                         |  61.972s  |  61.972s  |   0.000s  | 0.0%|
|scrambled92964.smt2                                                                         |1200.062s  |1200.062s  |   0.000s  | 0.0%|
|scrambled95284.smt2                                                                         | 570.052s  | 570.052s  |   0.000s  | 0.0%|
</details>
