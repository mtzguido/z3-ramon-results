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
Ramon benchmark for SMTS
-
Job description: 
Job tag: SMTS_z3-threads-8-test
Runner: rise-runner-2
SMTS repo: ilanashapiro/SMTS
SMTS commit: 6fbca23b525b880620030507e997cbbe14ae1a90
SMTS branch: master
SMTS options: "-oz 8 -p -l"
SMTS solver mode: z3
SMTS timeout: 65
SMTS inputs: inputs/smt_comp_2025_parallel/QF_LIA
SMTS commit message: fix more semantic bugs between SMTS+Z3 and the original SMTS+OpenSMT2

</pre>
# RHS
<pre>
Ramon benchmark for SMTS
-
Job description: 
Job tag: SMTS_z3-threads-8-test
Runner: rise-runner-2
SMTS repo: ilanashapiro/SMTS
SMTS commit: 6fbca23b525b880620030507e997cbbe14ae1a90
SMTS branch: master
SMTS options: "-oz 8 -p -l"
SMTS solver mode: z3
SMTS timeout: 65
SMTS inputs: inputs/smt_comp_2025_parallel/QF_LIA
SMTS commit message: fix more semantic bugs between SMTS+Z3 and the original SMTS+OpenSMT2

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  65.032s  |  65.032s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  65.039s  |  65.039s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  65.103s  |  65.103s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  65.335s  |  65.335s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  65.325s  |  65.325s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  65.127s  |  65.127s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  65.053s  |  65.053s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  65.053s  |  65.053s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  65.335s  |  65.335s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  65.047s  |  65.047s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  65.118s  |  65.118s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  65.325s  |  65.325s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  65.076s  |  65.076s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  65.067s  |  65.067s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  65.102s  |  65.102s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  65.027s  |  65.027s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  65.110s  |  65.110s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  65.245s  |  65.245s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  65.042s  |  65.042s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  65.085s  |  65.085s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  65.032s  |  65.032s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  65.039s  |  65.039s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  65.103s  |  65.103s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  65.335s  |  65.335s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  65.325s  |  65.325s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  65.127s  |  65.127s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  65.053s  |  65.053s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  65.053s  |  65.053s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  65.335s  |  65.335s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  65.047s  |  65.047s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  65.118s  |  65.118s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  65.325s  |  65.325s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  65.076s  |  65.076s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  65.067s  |  65.067s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  65.102s  |  65.102s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  65.027s  |  65.027s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  65.110s  |  65.110s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  65.245s  |  65.245s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  65.042s  |  65.042s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  65.085s  |  65.085s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  65.032s  |  65.032s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  65.039s  |  65.039s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  65.103s  |  65.103s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  65.335s  |  65.335s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  65.325s  |  65.325s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  65.127s  |  65.127s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  65.053s  |  65.053s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  65.053s  |  65.053s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  65.335s  |  65.335s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  65.047s  |  65.047s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  65.118s  |  65.118s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  65.325s  |  65.325s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  65.076s  |  65.076s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  65.067s  |  65.067s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  65.102s  |  65.102s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  65.027s  |  65.027s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  65.110s  |  65.110s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  65.245s  |  65.245s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  65.042s  |  65.042s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  65.085s  |  65.085s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  65.032s  |  65.032s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  65.039s  |  65.039s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  65.103s  |  65.103s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  65.335s  |  65.335s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  65.325s  |  65.325s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  65.127s  |  65.127s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  65.053s  |  65.053s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  65.053s  |  65.053s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  65.335s  |  65.335s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  65.047s  |  65.047s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  65.118s  |  65.118s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  65.325s  |  65.325s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  65.076s  |  65.076s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  65.067s  |  65.067s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  65.102s  |  65.102s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  65.027s  |  65.027s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  65.110s  |  65.110s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  65.245s  |  65.245s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  65.042s  |  65.042s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  65.085s  |  65.085s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled79867.smt2                                                                        |  65.373s |12.496GiB|
|scrambled75189.smt2                                                                        |  65.373s |2252.0MiB|
|scrambled45952.smt2                                                                        |  65.339s |12.407GiB|
|scrambled40621.smt2                                                                        |  65.335s |333.0MiB|
|scrambled59713.smt2                                                                        |  65.335s |12.274GiB|
|scrambled4299.smt2                                                                         |  65.335s |3248.0MiB|
|scrambled55680.smt2                                                                        |  65.335s |4292.0MiB|
|scrambled107826.smt2                                                                       |  65.335s |2664.0MiB|
|scrambled12042.smt2                                                                        |  65.335s |5208.0MiB|
|scrambled65181.smt2                                                                        |  65.335s |11.828GiB|
|scrambled108840.smt2                                                                       |  65.325s |3393.0MiB|
|scrambled128128.smt2                                                                       |  65.325s |239.0MiB|
|scrambled20101.smt2                                                                        |  65.245s |109.0MiB|
|scrambled79760.smt2                                                                        |  65.173s |2749.0MiB|
|scrambled95803.smt2                                                                        |  65.157s |149.0MiB|
|scrambled51053.smt2                                                                        |  65.140s |935.0MiB|
|scrambled111627.smt2                                                                       |  65.127s |2774.0MiB|
|scrambled125888.smt2                                                                       |  65.118s |105.0MiB|
|scrambled4198.smt2                                                                         |  65.112s |5372.0MiB|
|scrambled19335.smt2                                                                        |  65.110s |2651.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled79867.smt2                                                                        |  65.373s |12.496GiB|
|scrambled75189.smt2                                                                        |  65.373s |2252.0MiB|
|scrambled45952.smt2                                                                        |  65.339s |12.407GiB|
|scrambled40621.smt2                                                                        |  65.335s |333.0MiB|
|scrambled59713.smt2                                                                        |  65.335s |12.274GiB|
|scrambled4299.smt2                                                                         |  65.335s |3248.0MiB|
|scrambled55680.smt2                                                                        |  65.335s |4292.0MiB|
|scrambled107826.smt2                                                                       |  65.335s |2664.0MiB|
|scrambled12042.smt2                                                                        |  65.335s |5208.0MiB|
|scrambled65181.smt2                                                                        |  65.335s |11.828GiB|
|scrambled108840.smt2                                                                       |  65.325s |3393.0MiB|
|scrambled128128.smt2                                                                       |  65.325s |239.0MiB|
|scrambled20101.smt2                                                                        |  65.245s |109.0MiB|
|scrambled79760.smt2                                                                        |  65.173s |2749.0MiB|
|scrambled95803.smt2                                                                        |  65.157s |149.0MiB|
|scrambled51053.smt2                                                                        |  65.140s |935.0MiB|
|scrambled111627.smt2                                                                       |  65.127s |2774.0MiB|
|scrambled125888.smt2                                                                       |  65.118s |105.0MiB|
|scrambled4198.smt2                                                                         |  65.112s |5372.0MiB|
|scrambled19335.smt2                                                                        |  65.110s |2651.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |3470.0MiB|3470.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |11.71GiB|11.71GiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |1058.0MiB|1058.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |2664.0MiB|2664.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |3393.0MiB|3393.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |2774.0MiB|2774.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |81.24MiB|81.24MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |323.0MiB|323.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |5208.0MiB|5208.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |88.752MiB|88.752MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |105.0MiB|105.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |239.0MiB|239.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |192.0MiB|192.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |188.0MiB|188.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |229.0MiB|229.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |34.792MiB|34.792MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |2651.0MiB|2651.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |109.0MiB|109.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |243.0MiB|243.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |1805.0MiB|1805.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |3470.0MiB|3470.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |11.71GiB|11.71GiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |1058.0MiB|1058.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |2664.0MiB|2664.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |3393.0MiB|3393.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |2774.0MiB|2774.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |81.24MiB|81.24MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |323.0MiB|323.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |5208.0MiB|5208.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |88.752MiB|88.752MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |105.0MiB|105.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |239.0MiB|239.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |192.0MiB|192.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |188.0MiB|188.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |229.0MiB|229.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |34.792MiB|34.792MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |2651.0MiB|2651.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |109.0MiB|109.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |243.0MiB|243.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |1805.0MiB|1805.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |3470.0MiB|3470.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |11.71GiB|11.71GiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |1058.0MiB|1058.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |2664.0MiB|2664.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |3393.0MiB|3393.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |2774.0MiB|2774.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |81.24MiB|81.24MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |323.0MiB|323.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |5208.0MiB|5208.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |88.752MiB|88.752MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |105.0MiB|105.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |239.0MiB|239.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |192.0MiB|192.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |188.0MiB|188.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |229.0MiB|229.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |34.792MiB|34.792MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |2651.0MiB|2651.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |109.0MiB|109.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |243.0MiB|243.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |1805.0MiB|1805.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |3470.0MiB|3470.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |11.71GiB|11.71GiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |1058.0MiB|1058.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |2664.0MiB|2664.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |3393.0MiB|3393.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |2774.0MiB|2774.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |81.24MiB|81.24MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |323.0MiB|323.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |5208.0MiB|5208.0MiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |88.752MiB|88.752MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |105.0MiB|105.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |239.0MiB|239.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |192.0MiB|192.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |188.0MiB|188.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |229.0MiB|229.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |34.792MiB|34.792MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |2651.0MiB|2651.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |109.0MiB|109.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |243.0MiB|243.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |1805.0MiB|1805.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled39514.smt2                                                                        |  65.034s |12.708GiB|
|scrambled79867.smt2                                                                        |  65.373s |12.496GiB|
|scrambled45952.smt2                                                                        |  65.339s |12.407GiB|
|scrambled59713.smt2                                                                        |  65.335s |12.274GiB|
|scrambled79766.smt2                                                                        |  65.052s |12.013GiB|
|scrambled3854.smt2                                                                         |  65.023s |12.01GiB|
|scrambled65181.smt2                                                                        |  65.335s |11.828GiB|
|scrambled103783.smt2                                                                       |  65.039s |11.71GiB|
|scrambled4198.smt2                                                                         |  65.112s |5372.0MiB|
|scrambled12042.smt2                                                                        |  65.335s |5208.0MiB|
|scrambled94658.smt2                                                                        |  65.066s |5018.0MiB|
|scrambled55680.smt2                                                                        |  65.335s |4292.0MiB|
|scrambled102166.smt2                                                                       |  65.032s |3470.0MiB|
|scrambled108840.smt2                                                                       |  65.325s |3393.0MiB|
|scrambled4299.smt2                                                                         |  65.335s |3248.0MiB|
|scrambled43577.smt2                                                                        |  65.038s |2814.0MiB|
|scrambled111627.smt2                                                                       |  65.127s |2774.0MiB|
|scrambled79760.smt2                                                                        |  65.173s |2749.0MiB|
|scrambled107826.smt2                                                                       |  65.335s |2664.0MiB|
|scrambled19335.smt2                                                                        |  65.110s |2651.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled39514.smt2                                                                        |  65.034s |12.708GiB|
|scrambled79867.smt2                                                                        |  65.373s |12.496GiB|
|scrambled45952.smt2                                                                        |  65.339s |12.407GiB|
|scrambled59713.smt2                                                                        |  65.335s |12.274GiB|
|scrambled79766.smt2                                                                        |  65.052s |12.013GiB|
|scrambled3854.smt2                                                                         |  65.023s |12.01GiB|
|scrambled65181.smt2                                                                        |  65.335s |11.828GiB|
|scrambled103783.smt2                                                                       |  65.039s |11.71GiB|
|scrambled4198.smt2                                                                         |  65.112s |5372.0MiB|
|scrambled12042.smt2                                                                        |  65.335s |5208.0MiB|
|scrambled94658.smt2                                                                        |  65.066s |5018.0MiB|
|scrambled55680.smt2                                                                        |  65.335s |4292.0MiB|
|scrambled102166.smt2                                                                       |  65.032s |3470.0MiB|
|scrambled108840.smt2                                                                       |  65.325s |3393.0MiB|
|scrambled4299.smt2                                                                         |  65.335s |3248.0MiB|
|scrambled43577.smt2                                                                        |  65.038s |2814.0MiB|
|scrambled111627.smt2                                                                       |  65.127s |2774.0MiB|
|scrambled79760.smt2                                                                        |  65.173s |2749.0MiB|
|scrambled107826.smt2                                                                       |  65.335s |2664.0MiB|
|scrambled19335.smt2                                                                        |  65.110s |2651.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |  65.032s  |  65.032s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |  65.039s  |  65.039s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |  65.103s  |  65.103s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  65.335s  |  65.335s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |  65.325s  |  65.325s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |  65.127s  |  65.127s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  65.053s  |  65.053s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |  65.053s  |  65.053s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |  65.335s  |  65.335s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  65.047s  |  65.047s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |  65.118s  |  65.118s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  65.325s  |  65.325s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |  65.076s  |  65.076s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |  65.067s  |  65.067s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  65.102s  |  65.102s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |  65.027s  |  65.027s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |  65.110s  |  65.110s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  65.245s  |  65.245s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  65.042s  |  65.042s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |  65.085s  |  65.085s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |  65.061s  |  65.061s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |  65.023s  |  65.023s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |  65.034s  |  65.034s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |  65.335s  |  65.335s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |  65.112s  |  65.112s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |  65.335s  |  65.335s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |  65.038s  |  65.038s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |  65.041s  |  65.041s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |  65.339s  |  65.339s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |  65.140s  |  65.140s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |  65.335s  |  65.335s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |  65.063s  |  65.063s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |  65.335s  |  65.335s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |  65.097s  |  65.097s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |  65.335s  |  65.335s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |  65.067s  |  65.067s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |  65.039s  |  65.039s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |  65.373s  |  65.373s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |  65.042s  |  65.042s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |  65.173s  |  65.173s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |  65.052s  |  65.052s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |  65.373s  |  65.373s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |  65.066s  |  65.066s  |   0.000s  | 0.0%|
</details>
