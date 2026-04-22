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
Job tag: SMTS_opensmt-threads-8-smtcomp2025-QF_LIA-timeout_20min
Runner: rise-runner-2
SMTS repo: ilanashapiro/SMTS
SMTS commit: 6fbca23b525b880620030507e997cbbe14ae1a90
SMTS branch: master
SMTS options: "-o 8 -p -l"
SMTS solver mode: opensmt
SMTS timeout: 1200
SMTS inputs: inputs/smt_comp_2025_parallel/QF_LIA
SMTS commit message: fix more semantic bugs between SMTS+Z3 and the original SMTS+OpenSMT2

</pre>
# RHS
<pre>
Ramon benchmark for SMTS
-
Job description: 
Job tag: SMTS_opensmt-threads-8-smtcomp2025-QF_LIA-timeout_20min
Runner: rise-runner-2
SMTS repo: ilanashapiro/SMTS
SMTS commit: 6fbca23b525b880620030507e997cbbe14ae1a90
SMTS branch: master
SMTS options: "-o 8 -p -l"
SMTS solver mode: opensmt
SMTS timeout: 1200
SMTS inputs: inputs/smt_comp_2025_parallel/QF_LIA
SMTS commit message: fix more semantic bugs between SMTS+Z3 and the original SMTS+OpenSMT2

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.057s  |1200.057s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.147s  |1200.147s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.259s  |1200.259s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.061s  |1200.061s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.067s  |1200.067s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.046s  |1200.046s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   4.500s  |   4.500s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        | 809.427s  | 809.427s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |   1.808s  |   1.808s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   6.000s  |   6.000s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        | 234.501s  | 234.501s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.112s  |1200.112s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        | 152.492s  | 152.492s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  44.312s  |  44.312s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  86.563s  |  86.563s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  45.626s  |  45.626s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.070s  |1200.070s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.057s  |1200.057s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.147s  |1200.147s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.259s  |1200.259s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.061s  |1200.061s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.067s  |1200.067s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.046s  |1200.046s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   4.500s  |   4.500s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        | 809.427s  | 809.427s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |   1.808s  |   1.808s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   6.000s  |   6.000s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        | 234.501s  | 234.501s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.112s  |1200.112s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        | 152.492s  | 152.492s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  44.312s  |  44.312s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  86.563s  |  86.563s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  45.626s  |  45.626s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.070s  |1200.070s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.057s  |1200.057s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.147s  |1200.147s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.259s  |1200.259s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.061s  |1200.061s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.067s  |1200.067s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.046s  |1200.046s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   4.500s  |   4.500s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        | 809.427s  | 809.427s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |   1.808s  |   1.808s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   6.000s  |   6.000s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        | 234.501s  | 234.501s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.112s  |1200.112s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        | 152.492s  | 152.492s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  44.312s  |  44.312s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  86.563s  |  86.563s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  45.626s  |  45.626s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.070s  |1200.070s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.057s  |1200.057s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.147s  |1200.147s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.259s  |1200.259s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.061s  |1200.061s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.067s  |1200.067s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.046s  |1200.046s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   4.500s  |   4.500s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        | 809.427s  | 809.427s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |   1.808s  |   1.808s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   6.000s  |   6.000s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        | 234.501s  | 234.501s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.112s  |1200.112s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        | 152.492s  | 152.492s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  44.312s  |  44.312s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  86.563s  |  86.563s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  45.626s  |  45.626s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.070s  |1200.070s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled107115.smt2                                                                       |1200.259s |15.772GiB|
|scrambled103783.smt2                                                                       |1200.147s |51.192GiB|
|scrambled94658.smt2                                                                        |1200.134s |19.903GiB|
|scrambled3854.smt2                                                                         |1200.133s |50.445GiB|
|scrambled128732.smt2                                                                       |1200.112s |2426.0MiB|
|scrambled45952.smt2                                                                        |1200.101s |54.575GiB|
|scrambled65181.smt2                                                                        |1200.101s |48.493GiB|
|scrambled79867.smt2                                                                        |1200.092s |54.193GiB|
|scrambled4299.smt2                                                                         |1200.087s |11.362GiB|
|scrambled19335.smt2                                                                        |1200.085s |16.324GiB|
|scrambled75189.smt2                                                                        |1200.080s |11.496GiB|
|scrambled59713.smt2                                                                        |1200.078s |45.778GiB|
|scrambled4198.smt2                                                                         |1200.078s |23.985GiB|
|scrambled79760.smt2                                                                        |1200.073s |10.472GiB|
|scrambled27843.smt2                                                                        |1200.070s |9421.0MiB|
|scrambled43577.smt2                                                                        |1200.068s |12.49GiB|
|scrambled51053.smt2                                                                        |1200.068s |4843.0MiB|
|scrambled108840.smt2                                                                       |1200.067s |14.578GiB|
|scrambled12042.smt2                                                                        |1200.063s |21.698GiB|
|scrambled107826.smt2                                                                       |1200.061s |14.153GiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled107115.smt2                                                                       |1200.259s |15.772GiB|
|scrambled103783.smt2                                                                       |1200.147s |51.192GiB|
|scrambled94658.smt2                                                                        |1200.134s |19.903GiB|
|scrambled3854.smt2                                                                         |1200.133s |50.445GiB|
|scrambled128732.smt2                                                                       |1200.112s |2426.0MiB|
|scrambled45952.smt2                                                                        |1200.101s |54.575GiB|
|scrambled65181.smt2                                                                        |1200.101s |48.493GiB|
|scrambled79867.smt2                                                                        |1200.092s |54.193GiB|
|scrambled4299.smt2                                                                         |1200.087s |11.362GiB|
|scrambled19335.smt2                                                                        |1200.085s |16.324GiB|
|scrambled75189.smt2                                                                        |1200.080s |11.496GiB|
|scrambled59713.smt2                                                                        |1200.078s |45.778GiB|
|scrambled4198.smt2                                                                         |1200.078s |23.985GiB|
|scrambled79760.smt2                                                                        |1200.073s |10.472GiB|
|scrambled27843.smt2                                                                        |1200.070s |9421.0MiB|
|scrambled43577.smt2                                                                        |1200.068s |12.49GiB|
|scrambled51053.smt2                                                                        |1200.068s |4843.0MiB|
|scrambled108840.smt2                                                                       |1200.067s |14.578GiB|
|scrambled12042.smt2                                                                        |1200.063s |21.698GiB|
|scrambled107826.smt2                                                                       |1200.061s |14.153GiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |14.652GiB|14.652GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |51.192GiB|51.192GiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |15.772GiB|15.772GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.153GiB|14.153GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |14.578GiB|14.578GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |16.313GiB|16.313GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |241.0MiB|241.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |2341.0MiB|2341.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |21.698GiB|21.698GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |238.0MiB|238.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |328.0MiB|328.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |1722.0MiB|1722.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2426.0MiB|2426.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |988.0MiB|988.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |1322.0MiB|1322.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |3671.0MiB|3671.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |16.324GiB|16.324GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |678.0MiB|678.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |1410.0MiB|1410.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |9421.0MiB|9421.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |14.652GiB|14.652GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |51.192GiB|51.192GiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |15.772GiB|15.772GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.153GiB|14.153GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |14.578GiB|14.578GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |16.313GiB|16.313GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |241.0MiB|241.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |2341.0MiB|2341.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |21.698GiB|21.698GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |238.0MiB|238.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |328.0MiB|328.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |1722.0MiB|1722.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2426.0MiB|2426.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |988.0MiB|988.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |1322.0MiB|1322.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |3671.0MiB|3671.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |16.324GiB|16.324GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |678.0MiB|678.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |1410.0MiB|1410.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |9421.0MiB|9421.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |14.652GiB|14.652GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |51.192GiB|51.192GiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |15.772GiB|15.772GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.153GiB|14.153GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |14.578GiB|14.578GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |16.313GiB|16.313GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |241.0MiB|241.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |2341.0MiB|2341.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |21.698GiB|21.698GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |238.0MiB|238.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |328.0MiB|328.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |1722.0MiB|1722.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2426.0MiB|2426.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |988.0MiB|988.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |1322.0MiB|1322.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |3671.0MiB|3671.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |16.324GiB|16.324GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |678.0MiB|678.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |1410.0MiB|1410.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |9421.0MiB|9421.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |14.652GiB|14.652GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |51.192GiB|51.192GiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |15.772GiB|15.772GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |14.153GiB|14.153GiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |14.578GiB|14.578GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |16.313GiB|16.313GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |241.0MiB|241.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |2341.0MiB|2341.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |21.698GiB|21.698GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |238.0MiB|238.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |328.0MiB|328.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |1722.0MiB|1722.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |2426.0MiB|2426.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |988.0MiB|988.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |1322.0MiB|1322.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |3671.0MiB|3671.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |16.324GiB|16.324GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |678.0MiB|678.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |1410.0MiB|1410.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |9421.0MiB|9421.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled45952.smt2                                                                        |1200.101s |54.575GiB|
|scrambled79867.smt2                                                                        |1200.092s |54.193GiB|
|scrambled103783.smt2                                                                       |1200.147s |51.192GiB|
|scrambled3854.smt2                                                                         |1200.133s |50.445GiB|
|scrambled65181.smt2                                                                        |1200.101s |48.493GiB|
|scrambled39514.smt2                                                                        |1200.055s |47.367GiB|
|scrambled59713.smt2                                                                        |1200.078s |45.778GiB|
|scrambled79766.smt2                                                                        |1200.055s |45.12GiB|
|scrambled4198.smt2                                                                         |1200.078s |23.985GiB|
|scrambled12042.smt2                                                                        |1200.063s |21.698GiB|
|scrambled55680.smt2                                                                        |1200.058s |21.426GiB|
|scrambled94658.smt2                                                                        |1200.134s |19.903GiB|
|scrambled19335.smt2                                                                        |1200.085s |16.324GiB|
|scrambled111627.smt2                                                                       |1200.046s |16.313GiB|
|scrambled107115.smt2                                                                       |1200.259s |15.772GiB|
|scrambled102166.smt2                                                                       |1200.057s |14.652GiB|
|scrambled108840.smt2                                                                       |1200.067s |14.578GiB|
|scrambled107826.smt2                                                                       |1200.061s |14.153GiB|
|scrambled43577.smt2                                                                        |1200.068s |12.49GiB|
|scrambled61922.smt2                                                                        |1200.060s |11.723GiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled45952.smt2                                                                        |1200.101s |54.575GiB|
|scrambled79867.smt2                                                                        |1200.092s |54.193GiB|
|scrambled103783.smt2                                                                       |1200.147s |51.192GiB|
|scrambled3854.smt2                                                                         |1200.133s |50.445GiB|
|scrambled65181.smt2                                                                        |1200.101s |48.493GiB|
|scrambled39514.smt2                                                                        |1200.055s |47.367GiB|
|scrambled59713.smt2                                                                        |1200.078s |45.778GiB|
|scrambled79766.smt2                                                                        |1200.055s |45.12GiB|
|scrambled4198.smt2                                                                         |1200.078s |23.985GiB|
|scrambled12042.smt2                                                                        |1200.063s |21.698GiB|
|scrambled55680.smt2                                                                        |1200.058s |21.426GiB|
|scrambled94658.smt2                                                                        |1200.134s |19.903GiB|
|scrambled19335.smt2                                                                        |1200.085s |16.324GiB|
|scrambled111627.smt2                                                                       |1200.046s |16.313GiB|
|scrambled107115.smt2                                                                       |1200.259s |15.772GiB|
|scrambled102166.smt2                                                                       |1200.057s |14.652GiB|
|scrambled108840.smt2                                                                       |1200.067s |14.578GiB|
|scrambled107826.smt2                                                                       |1200.061s |14.153GiB|
|scrambled43577.smt2                                                                        |1200.068s |12.49GiB|
|scrambled61922.smt2                                                                        |1200.060s |11.723GiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.057s  |1200.057s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.147s  |1200.147s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.259s  |1200.259s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1200.061s  |1200.061s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.067s  |1200.067s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.046s  |1200.046s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |   4.500s  |   4.500s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        | 809.427s  | 809.427s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1200.063s  |1200.063s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |   1.808s  |   1.808s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   6.000s  |   6.000s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        | 234.501s  | 234.501s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.112s  |1200.112s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        | 152.492s  | 152.492s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  44.312s  |  44.312s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.045s  |1200.045s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.085s  |1200.085s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  86.563s  |  86.563s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  45.626s  |  45.626s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.070s  |1200.070s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         | 313.768s  | 313.768s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1200.133s  |1200.133s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1200.078s  |1200.078s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1200.087s  |1200.087s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |  79.269s  |  79.269s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1200.068s  |1200.068s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1200.058s  |1200.058s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1200.044s  |1200.044s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1200.078s  |1200.078s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1200.060s  |1200.060s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1200.056s  |1200.056s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         |  66.485s  |  66.485s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1200.080s  |1200.080s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          | 257.212s  | 257.212s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1200.073s  |1200.073s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1200.055s  |1200.055s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1200.092s  |1200.092s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1200.134s  |1200.134s  |   0.000s  | 0.0%|
</details>
