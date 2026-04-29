Comparing data and data


# SUMMARY
- LHS tests = 45
- RHS tests = 45
- LHS success = 45  (100.0%)
- RHS success = 45  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for SMTS
-
Job description: 
Job tag: SMTS-threads-8-smtcomp2025-QF_IDL-timeout20min
Runner: rise-runner-2
SMTS repo: usi-verification-and-security/SMTS
SMTS commit: 33750b9094495eb1b86c1d7b796a0340ccf03822
SMTS branch: master
SMTS options: "-o 8 -p -l"
SMTS timeout: 1200
SMTS inputs: inputs/smt_comp_2025_parallel/QF_IDL
SMTS commit message: Reduced number of building cores in CircleCI

</pre>
# RHS
<pre>
Ramon benchmark for SMTS
-
Job description: 
Job tag: SMTS-threads-8-smtcomp2025-QF_IDL-timeout20min
Runner: rise-runner-2
SMTS repo: usi-verification-and-security/SMTS
SMTS commit: 33750b9094495eb1b86c1d7b796a0340ccf03822
SMTS branch: master
SMTS options: "-o 8 -p -l"
SMTS timeout: 1200
SMTS inputs: inputs/smt_comp_2025_parallel/QF_IDL
SMTS commit message: Reduced number of building cores in CircleCI

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.081s  |1200.081s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.054s  |1200.054s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.054s  |1200.054s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |  74.145s  |  74.145s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        | 133.365s  | 133.365s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        |1200.046s  |1200.046s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |  66.088s  |  66.088s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.022s  |1200.022s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         | 481.015s  | 481.015s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1105.822s  |1105.822s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1200.144s  |1200.144s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.051s  |1200.051s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.081s  |1200.081s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.054s  |1200.054s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.054s  |1200.054s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |  74.145s  |  74.145s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        | 133.365s  | 133.365s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        |1200.046s  |1200.046s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |  66.088s  |  66.088s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.022s  |1200.022s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         | 481.015s  | 481.015s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1105.822s  |1105.822s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1200.144s  |1200.144s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.051s  |1200.051s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.081s  |1200.081s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.054s  |1200.054s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.054s  |1200.054s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |  74.145s  |  74.145s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        | 133.365s  | 133.365s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        |1200.046s  |1200.046s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |  66.088s  |  66.088s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.022s  |1200.022s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         | 481.015s  | 481.015s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1105.822s  |1105.822s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1200.144s  |1200.144s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.051s  |1200.051s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.081s  |1200.081s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.054s  |1200.054s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.054s  |1200.054s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |  74.145s  |  74.145s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        | 133.365s  | 133.365s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        |1200.046s  |1200.046s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |  66.088s  |  66.088s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.022s  |1200.022s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         | 481.015s  | 481.015s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1105.822s  |1105.822s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1200.144s  |1200.144s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.051s  |1200.051s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1200.144s |15.28GiB|
|scrambled92133.smt2                                                                        |1200.140s |1967.0MiB|
|scrambled122413.smt2                                                                       |1200.106s |975.0MiB|
|scrambled4441.smt2                                                                         |1200.103s |1368.0MiB|
|scrambled21544.smt2                                                                        |1200.101s |1485.0MiB|
|scrambled78606.smt2                                                                        |1200.098s |1726.0MiB|
|scrambled78432.smt2                                                                        |1200.095s |1632.0MiB|
|scrambled6373.smt2                                                                         |1200.091s |1178.0MiB|
|scrambled96733.smt2                                                                        |1200.088s |616.0MiB|
|scrambled97138.smt2                                                                        |1200.086s |492.0MiB|
|scrambled42287.smt2                                                                        |1200.085s |496.0MiB|
|scrambled1447.smt2                                                                         |1200.082s |849.0MiB|
|scrambled103851.smt2                                                                       |1200.081s |572.0MiB|
|scrambled90733.smt2                                                                        |1200.079s |1625.0MiB|
|scrambled89071.smt2                                                                        |1200.078s |1746.0MiB|
|scrambled58720.smt2                                                                        |1200.077s |1248.0MiB|
|scrambled62859.smt2                                                                        |1200.074s |649.0MiB|
|scrambled79181.smt2                                                                        |1200.073s |1376.0MiB|
|scrambled27577.smt2                                                                        |1200.069s |2078.0MiB|
|scrambled15552.smt2                                                                        |1200.069s |1246.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1200.144s |15.28GiB|
|scrambled92133.smt2                                                                        |1200.140s |1967.0MiB|
|scrambled122413.smt2                                                                       |1200.106s |975.0MiB|
|scrambled4441.smt2                                                                         |1200.103s |1368.0MiB|
|scrambled21544.smt2                                                                        |1200.101s |1485.0MiB|
|scrambled78606.smt2                                                                        |1200.098s |1726.0MiB|
|scrambled78432.smt2                                                                        |1200.095s |1632.0MiB|
|scrambled6373.smt2                                                                         |1200.091s |1178.0MiB|
|scrambled96733.smt2                                                                        |1200.088s |616.0MiB|
|scrambled97138.smt2                                                                        |1200.086s |492.0MiB|
|scrambled42287.smt2                                                                        |1200.085s |496.0MiB|
|scrambled1447.smt2                                                                         |1200.082s |849.0MiB|
|scrambled103851.smt2                                                                       |1200.081s |572.0MiB|
|scrambled90733.smt2                                                                        |1200.079s |1625.0MiB|
|scrambled89071.smt2                                                                        |1200.078s |1746.0MiB|
|scrambled58720.smt2                                                                        |1200.077s |1248.0MiB|
|scrambled62859.smt2                                                                        |1200.074s |649.0MiB|
|scrambled79181.smt2                                                                        |1200.073s |1376.0MiB|
|scrambled27577.smt2                                                                        |1200.069s |2078.0MiB|
|scrambled15552.smt2                                                                        |1200.069s |1246.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |776.0MiB|776.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |572.0MiB|572.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |1872.0MiB|1872.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |662.0MiB|662.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |342.0MiB|342.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |376.0MiB|376.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |1451.0MiB|1451.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |975.0MiB|975.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |1418.0MiB|1418.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |1659.0MiB|1659.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |377.0MiB|377.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |849.0MiB|849.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |748.0MiB|748.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |734.0MiB|734.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |1246.0MiB|1246.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |1485.0MiB|1485.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |1389.0MiB|1389.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |15.28GiB|15.28GiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |2078.0MiB|2078.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |748.0MiB|748.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |776.0MiB|776.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |572.0MiB|572.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |1872.0MiB|1872.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |662.0MiB|662.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |342.0MiB|342.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |376.0MiB|376.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |1451.0MiB|1451.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |975.0MiB|975.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |1418.0MiB|1418.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |1659.0MiB|1659.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |377.0MiB|377.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |849.0MiB|849.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |748.0MiB|748.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |734.0MiB|734.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |1246.0MiB|1246.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |1485.0MiB|1485.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |1389.0MiB|1389.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |15.28GiB|15.28GiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |2078.0MiB|2078.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |748.0MiB|748.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |776.0MiB|776.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |572.0MiB|572.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |1872.0MiB|1872.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |662.0MiB|662.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |342.0MiB|342.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |376.0MiB|376.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |1451.0MiB|1451.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |975.0MiB|975.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |1418.0MiB|1418.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |1659.0MiB|1659.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |377.0MiB|377.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |849.0MiB|849.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |748.0MiB|748.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |734.0MiB|734.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |1246.0MiB|1246.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |1485.0MiB|1485.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |1389.0MiB|1389.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |15.28GiB|15.28GiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |2078.0MiB|2078.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |748.0MiB|748.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |776.0MiB|776.0MiB|0B| 0.0%|
|scrambled103851.smt2                                                                        |572.0MiB|572.0MiB|0B| 0.0%|
|scrambled109208.smt2                                                                        |1872.0MiB|1872.0MiB|0B| 0.0%|
|scrambled116992.smt2                                                                        |662.0MiB|662.0MiB|0B| 0.0%|
|scrambled117178.smt2                                                                        |342.0MiB|342.0MiB|0B| 0.0%|
|scrambled119992.smt2                                                                        |376.0MiB|376.0MiB|0B| 0.0%|
|scrambled122058.smt2                                                                        |1451.0MiB|1451.0MiB|0B| 0.0%|
|scrambled122413.smt2                                                                        |975.0MiB|975.0MiB|0B| 0.0%|
|scrambled124624.smt2                                                                        |1418.0MiB|1418.0MiB|0B| 0.0%|
|scrambled128361.smt2                                                                        |1659.0MiB|1659.0MiB|0B| 0.0%|
|scrambled1379.smt2                                                                          |377.0MiB|377.0MiB|0B| 0.0%|
|scrambled1447.smt2                                                                          |849.0MiB|849.0MiB|0B| 0.0%|
|scrambled14967.smt2                                                                         |748.0MiB|748.0MiB|0B| 0.0%|
|scrambled15284.smt2                                                                         |734.0MiB|734.0MiB|0B| 0.0%|
|scrambled15552.smt2                                                                         |1246.0MiB|1246.0MiB|0B| 0.0%|
|scrambled21544.smt2                                                                         |1485.0MiB|1485.0MiB|0B| 0.0%|
|scrambled23483.smt2                                                                         |1389.0MiB|1389.0MiB|0B| 0.0%|
|scrambled25140.smt2                                                                         |15.28GiB|15.28GiB|0B| 0.0%|
|scrambled27577.smt2                                                                         |2078.0MiB|2078.0MiB|0B| 0.0%|
|scrambled35345.smt2                                                                         |748.0MiB|748.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1200.144s |15.28GiB|
|scrambled96514.smt2                                                                        |1200.064s |11.095GiB|
|scrambled62536.smt2                                                                        | 442.884s |10.253GiB|
|scrambled27577.smt2                                                                        |1200.069s |2078.0MiB|
|scrambled92133.smt2                                                                        |1200.140s |1967.0MiB|
|scrambled109208.smt2                                                                       |1200.054s |1872.0MiB|
|scrambled98799.smt2                                                                        |1200.042s |1797.0MiB|
|scrambled89071.smt2                                                                        |1200.078s |1746.0MiB|
|scrambled54073.smt2                                                                        |1200.063s |1746.0MiB|
|scrambled78606.smt2                                                                        |1200.098s |1726.0MiB|
|scrambled128361.smt2                                                                       |1200.046s |1659.0MiB|
|scrambled78432.smt2                                                                        |1200.095s |1632.0MiB|
|scrambled90733.smt2                                                                        |1200.079s |1625.0MiB|
|scrambled82743.smt2                                                                        |1200.027s |1623.0MiB|
|scrambled9927.smt2                                                                         |1200.047s |1544.0MiB|
|scrambled21544.smt2                                                                        |1200.101s |1485.0MiB|
|scrambled122058.smt2                                                                       |1200.031s |1451.0MiB|
|scrambled124624.smt2                                                                       |1200.048s |1418.0MiB|
|scrambled23483.smt2                                                                        |1105.822s |1389.0MiB|
|scrambled79181.smt2                                                                        |1200.073s |1376.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled25140.smt2                                                                        |1200.144s |15.28GiB|
|scrambled96514.smt2                                                                        |1200.064s |11.095GiB|
|scrambled62536.smt2                                                                        | 442.884s |10.253GiB|
|scrambled27577.smt2                                                                        |1200.069s |2078.0MiB|
|scrambled92133.smt2                                                                        |1200.140s |1967.0MiB|
|scrambled109208.smt2                                                                       |1200.054s |1872.0MiB|
|scrambled98799.smt2                                                                        |1200.042s |1797.0MiB|
|scrambled89071.smt2                                                                        |1200.078s |1746.0MiB|
|scrambled54073.smt2                                                                        |1200.063s |1746.0MiB|
|scrambled78606.smt2                                                                        |1200.098s |1726.0MiB|
|scrambled128361.smt2                                                                       |1200.046s |1659.0MiB|
|scrambled78432.smt2                                                                        |1200.095s |1632.0MiB|
|scrambled90733.smt2                                                                        |1200.079s |1625.0MiB|
|scrambled82743.smt2                                                                        |1200.027s |1623.0MiB|
|scrambled9927.smt2                                                                         |1200.047s |1544.0MiB|
|scrambled21544.smt2                                                                        |1200.101s |1485.0MiB|
|scrambled122058.smt2                                                                       |1200.031s |1451.0MiB|
|scrambled124624.smt2                                                                       |1200.048s |1418.0MiB|
|scrambled23483.smt2                                                                        |1105.822s |1389.0MiB|
|scrambled79181.smt2                                                                        |1200.073s |1376.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled100416.smt2                                                                        |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled103851.smt2                                                                        |1200.081s  |1200.081s  |   0.000s  | 0.0%|
|scrambled109208.smt2                                                                        |1200.054s  |1200.054s  |   0.000s  | 0.0%|
|scrambled116992.smt2                                                                        |1200.054s  |1200.054s  |   0.000s  | 0.0%|
|scrambled117178.smt2                                                                        |  74.145s  |  74.145s  |   0.000s  | 0.0%|
|scrambled119992.smt2                                                                        | 133.365s  | 133.365s  |   0.000s  | 0.0%|
|scrambled122058.smt2                                                                        |1200.031s  |1200.031s  |   0.000s  | 0.0%|
|scrambled122413.smt2                                                                        |1200.106s  |1200.106s  |   0.000s  | 0.0%|
|scrambled124624.smt2                                                                        |1200.048s  |1200.048s  |   0.000s  | 0.0%|
|scrambled128361.smt2                                                                        |1200.046s  |1200.046s  |   0.000s  | 0.0%|
|scrambled1379.smt2                                                                          |  66.088s  |  66.088s  |   0.000s  | 0.0%|
|scrambled1447.smt2                                                                          |1200.082s  |1200.082s  |   0.000s  | 0.0%|
|scrambled14967.smt2                                                                         |1200.022s  |1200.022s  |   0.000s  | 0.0%|
|scrambled15284.smt2                                                                         | 481.015s  | 481.015s  |   0.000s  | 0.0%|
|scrambled15552.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled21544.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled23483.smt2                                                                         |1105.822s  |1105.822s  |   0.000s  | 0.0%|
|scrambled25140.smt2                                                                         |1200.144s  |1200.144s  |   0.000s  | 0.0%|
|scrambled27577.smt2                                                                         |1200.069s  |1200.069s  |   0.000s  | 0.0%|
|scrambled35345.smt2                                                                         |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled38610.smt2                                                                         |1200.050s  |1200.050s  |   0.000s  | 0.0%|
|scrambled41312.smt2                                                                         |1200.051s  |1200.051s  |   0.000s  | 0.0%|
|scrambled41773.smt2                                                                         |1023.482s  |1023.482s  |   0.000s  | 0.0%|
|scrambled41801.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled42287.smt2                                                                         |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled4441.smt2                                                                          |1200.103s  |1200.103s  |   0.000s  | 0.0%|
|scrambled54073.smt2                                                                         |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled58720.smt2                                                                         |1200.077s  |1200.077s  |   0.000s  | 0.0%|
|scrambled62536.smt2                                                                         | 442.884s  | 442.884s  |   0.000s  | 0.0%|
|scrambled62810.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled62859.smt2                                                                         |1200.074s  |1200.074s  |   0.000s  | 0.0%|
|scrambled6373.smt2                                                                          |1200.091s  |1200.091s  |   0.000s  | 0.0%|
|scrambled75206.smt2                                                                         | 656.946s  | 656.946s  |   0.000s  | 0.0%|
|scrambled78432.smt2                                                                         |1200.095s  |1200.095s  |   0.000s  | 0.0%|
|scrambled78606.smt2                                                                         |1200.098s  |1200.098s  |   0.000s  | 0.0%|
|scrambled79181.smt2                                                                         |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled82743.smt2                                                                         |1200.027s  |1200.027s  |   0.000s  | 0.0%|
|scrambled89071.smt2                                                                         |1200.078s  |1200.078s  |   0.000s  | 0.0%|
|scrambled90733.smt2                                                                         |1200.079s  |1200.079s  |   0.000s  | 0.0%|
|scrambled92133.smt2                                                                         |1200.140s  |1200.140s  |   0.000s  | 0.0%|
|scrambled96514.smt2                                                                         |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled96733.smt2                                                                         |1200.088s  |1200.088s  |   0.000s  | 0.0%|
|scrambled97138.smt2                                                                         |1200.086s  |1200.086s  |   0.000s  | 0.0%|
|scrambled98799.smt2                                                                         |1200.042s  |1200.042s  |   0.000s  | 0.0%|
</details>
