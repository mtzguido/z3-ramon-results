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
Job tag: SMTS_threads-4-smtcomp2025-QF_LIA-timeout_20min
Runner: rise-runner-2
SMTS repo: usi-verification-and-security/SMTS
SMTS commit: 33750b9094495eb1b86c1d7b796a0340ccf03822
SMTS branch: master
SMTS options: "-o 4 -p -l"
SMTS timeout: 1260
SMTS inputs: inputs/smt_comp_2025_parallel/QF_LIA
SMTS commit message: Reduced number of building cores in CircleCI

</pre>
# RHS
<pre>
Ramon benchmark for SMTS
-
Job description: 
Job tag: SMTS_threads-4-smtcomp2025-QF_LIA-timeout_20min
Runner: rise-runner-2
SMTS repo: usi-verification-and-security/SMTS
SMTS commit: 33750b9094495eb1b86c1d7b796a0340ccf03822
SMTS branch: master
SMTS options: "-o 4 -p -l"
SMTS timeout: 1260
SMTS inputs: inputs/smt_comp_2025_parallel/QF_LIA
SMTS commit message: Reduced number of building cores in CircleCI

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1260.033s  |1260.033s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.060s  |1260.060s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.109s  |1260.109s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1260.133s  |1260.133s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1260.047s  |1260.047s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1260.126s  |1260.126s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  30.220s  |  30.220s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.133s  |1260.133s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1260.150s  |1260.150s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  43.916s  |  43.916s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   7.677s  |   7.677s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        | 230.339s  | 230.339s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.047s  |1260.047s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        | 968.021s  | 968.021s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  29.336s  |  29.336s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.090s  |1260.090s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1260.155s  |1260.155s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  55.660s  |  55.660s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  58.155s  |  58.155s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1260.058s  |1260.058s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1260.033s  |1260.033s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.060s  |1260.060s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.109s  |1260.109s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1260.133s  |1260.133s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1260.047s  |1260.047s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1260.126s  |1260.126s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  30.220s  |  30.220s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.133s  |1260.133s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1260.150s  |1260.150s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  43.916s  |  43.916s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   7.677s  |   7.677s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        | 230.339s  | 230.339s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.047s  |1260.047s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        | 968.021s  | 968.021s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  29.336s  |  29.336s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.090s  |1260.090s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1260.155s  |1260.155s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  55.660s  |  55.660s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  58.155s  |  58.155s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1260.058s  |1260.058s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1260.033s  |1260.033s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.060s  |1260.060s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.109s  |1260.109s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1260.133s  |1260.133s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1260.047s  |1260.047s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1260.126s  |1260.126s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  30.220s  |  30.220s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.133s  |1260.133s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1260.150s  |1260.150s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  43.916s  |  43.916s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   7.677s  |   7.677s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        | 230.339s  | 230.339s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.047s  |1260.047s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        | 968.021s  | 968.021s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  29.336s  |  29.336s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.090s  |1260.090s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1260.155s  |1260.155s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  55.660s  |  55.660s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  58.155s  |  58.155s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1260.058s  |1260.058s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1260.033s  |1260.033s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.060s  |1260.060s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.109s  |1260.109s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1260.133s  |1260.133s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1260.047s  |1260.047s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1260.126s  |1260.126s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  30.220s  |  30.220s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.133s  |1260.133s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1260.150s  |1260.150s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  43.916s  |  43.916s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   7.677s  |   7.677s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        | 230.339s  | 230.339s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.047s  |1260.047s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        | 968.021s  | 968.021s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  29.336s  |  29.336s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.090s  |1260.090s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1260.155s  |1260.155s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  55.660s  |  55.660s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  58.155s  |  58.155s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1260.058s  |1260.058s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1260.259s |12.541GiB|
|scrambled55680.smt2                                                                        |1260.156s |10.748GiB|
|scrambled19335.smt2                                                                        |1260.155s |8184.0MiB|
|scrambled12042.smt2                                                                        |1260.150s |11.57GiB|
|scrambled3854.smt2                                                                         |1260.140s |24.644GiB|
|scrambled45952.smt2                                                                        |1260.139s |26.07GiB|
|scrambled65181.smt2                                                                        |1260.135s |24.923GiB|
|scrambled107826.smt2                                                                       |1260.133s |7996.0MiB|
|scrambled119331.smt2                                                                       |1260.133s |1358.0MiB|
|scrambled111627.smt2                                                                       |1260.126s |8220.0MiB|
|scrambled68944.smt2                                                                        |1260.123s |5245.0MiB|
|scrambled51053.smt2                                                                        |1260.115s |2459.0MiB|
|scrambled4299.smt2                                                                         |1260.114s |5706.0MiB|
|scrambled107115.smt2                                                                       |1260.109s |8202.0MiB|
|scrambled40621.smt2                                                                        |1260.099s |1383.0MiB|
|scrambled4198.smt2                                                                         |1260.099s |15.08GiB|
|scrambled1417.smt2                                                                         |1260.090s |2217.0MiB|
|scrambled43577.smt2                                                                        |1260.089s |6375.0MiB|
|scrambled79760.smt2                                                                        |1260.068s |5263.0MiB|
|scrambled79867.smt2                                                                        |1260.065s |25.116GiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1260.259s |12.541GiB|
|scrambled55680.smt2                                                                        |1260.156s |10.748GiB|
|scrambled19335.smt2                                                                        |1260.155s |8184.0MiB|
|scrambled12042.smt2                                                                        |1260.150s |11.57GiB|
|scrambled3854.smt2                                                                         |1260.140s |24.644GiB|
|scrambled45952.smt2                                                                        |1260.139s |26.07GiB|
|scrambled65181.smt2                                                                        |1260.135s |24.923GiB|
|scrambled107826.smt2                                                                       |1260.133s |7996.0MiB|
|scrambled119331.smt2                                                                       |1260.133s |1358.0MiB|
|scrambled111627.smt2                                                                       |1260.126s |8220.0MiB|
|scrambled68944.smt2                                                                        |1260.123s |5245.0MiB|
|scrambled51053.smt2                                                                        |1260.115s |2459.0MiB|
|scrambled4299.smt2                                                                         |1260.114s |5706.0MiB|
|scrambled107115.smt2                                                                       |1260.109s |8202.0MiB|
|scrambled40621.smt2                                                                        |1260.099s |1383.0MiB|
|scrambled4198.smt2                                                                         |1260.099s |15.08GiB|
|scrambled1417.smt2                                                                         |1260.090s |2217.0MiB|
|scrambled43577.smt2                                                                        |1260.089s |6375.0MiB|
|scrambled79760.smt2                                                                        |1260.068s |5263.0MiB|
|scrambled79867.smt2                                                                        |1260.065s |25.116GiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |7333.0MiB|7333.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |24.448GiB|24.448GiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |8202.0MiB|8202.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |7996.0MiB|7996.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |7344.0MiB|7344.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |8220.0MiB|8220.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |202.0MiB|202.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |1358.0MiB|1358.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |11.57GiB|11.57GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |250.0MiB|250.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |182.0MiB|182.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |855.0MiB|855.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |1266.0MiB|1266.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |856.0MiB|856.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |669.0MiB|669.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |2217.0MiB|2217.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |8184.0MiB|8184.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |276.0MiB|276.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |737.0MiB|737.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |4728.0MiB|4728.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |7333.0MiB|7333.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |24.448GiB|24.448GiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |8202.0MiB|8202.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |7996.0MiB|7996.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |7344.0MiB|7344.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |8220.0MiB|8220.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |202.0MiB|202.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |1358.0MiB|1358.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |11.57GiB|11.57GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |250.0MiB|250.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |182.0MiB|182.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |855.0MiB|855.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |1266.0MiB|1266.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |856.0MiB|856.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |669.0MiB|669.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |2217.0MiB|2217.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |8184.0MiB|8184.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |276.0MiB|276.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |737.0MiB|737.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |4728.0MiB|4728.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |7333.0MiB|7333.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |24.448GiB|24.448GiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |8202.0MiB|8202.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |7996.0MiB|7996.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |7344.0MiB|7344.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |8220.0MiB|8220.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |202.0MiB|202.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |1358.0MiB|1358.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |11.57GiB|11.57GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |250.0MiB|250.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |182.0MiB|182.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |855.0MiB|855.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |1266.0MiB|1266.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |856.0MiB|856.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |669.0MiB|669.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |2217.0MiB|2217.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |8184.0MiB|8184.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |276.0MiB|276.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |737.0MiB|737.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |4728.0MiB|4728.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |7333.0MiB|7333.0MiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |24.448GiB|24.448GiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |8202.0MiB|8202.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |7996.0MiB|7996.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |7344.0MiB|7344.0MiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |8220.0MiB|8220.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |202.0MiB|202.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |1358.0MiB|1358.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |11.57GiB|11.57GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |250.0MiB|250.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |182.0MiB|182.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |855.0MiB|855.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |1266.0MiB|1266.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |856.0MiB|856.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |669.0MiB|669.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |2217.0MiB|2217.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |8184.0MiB|8184.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |276.0MiB|276.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |737.0MiB|737.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |4728.0MiB|4728.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled59713.smt2                                                                        |1260.043s |27.377GiB|
|scrambled45952.smt2                                                                        |1260.139s |26.07GiB|
|scrambled39514.smt2                                                                        |1260.053s |25.397GiB|
|scrambled79867.smt2                                                                        |1260.065s |25.116GiB|
|scrambled65181.smt2                                                                        |1260.135s |24.923GiB|
|scrambled3854.smt2                                                                         |1260.140s |24.644GiB|
|scrambled103783.smt2                                                                       |1260.060s |24.448GiB|
|scrambled79766.smt2                                                                        |1260.049s |22.051GiB|
|scrambled4198.smt2                                                                         |1260.099s |15.08GiB|
|scrambled94658.smt2                                                                        |1260.259s |12.541GiB|
|scrambled12042.smt2                                                                        |1260.150s |11.57GiB|
|scrambled55680.smt2                                                                        |1260.156s |10.748GiB|
|scrambled111627.smt2                                                                       |1260.126s |8220.0MiB|
|scrambled107115.smt2                                                                       |1260.109s |8202.0MiB|
|scrambled19335.smt2                                                                        |1260.155s |8184.0MiB|
|scrambled107826.smt2                                                                       |1260.133s |7996.0MiB|
|scrambled108840.smt2                                                                       |1260.047s |7344.0MiB|
|scrambled102166.smt2                                                                       |1260.033s |7333.0MiB|
|scrambled43577.smt2                                                                        |1260.089s |6375.0MiB|
|scrambled61922.smt2                                                                        |1260.051s |5882.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled59713.smt2                                                                        |1260.043s |27.377GiB|
|scrambled45952.smt2                                                                        |1260.139s |26.07GiB|
|scrambled39514.smt2                                                                        |1260.053s |25.397GiB|
|scrambled79867.smt2                                                                        |1260.065s |25.116GiB|
|scrambled65181.smt2                                                                        |1260.135s |24.923GiB|
|scrambled3854.smt2                                                                         |1260.140s |24.644GiB|
|scrambled103783.smt2                                                                       |1260.060s |24.448GiB|
|scrambled79766.smt2                                                                        |1260.049s |22.051GiB|
|scrambled4198.smt2                                                                         |1260.099s |15.08GiB|
|scrambled94658.smt2                                                                        |1260.259s |12.541GiB|
|scrambled12042.smt2                                                                        |1260.150s |11.57GiB|
|scrambled55680.smt2                                                                        |1260.156s |10.748GiB|
|scrambled111627.smt2                                                                       |1260.126s |8220.0MiB|
|scrambled107115.smt2                                                                       |1260.109s |8202.0MiB|
|scrambled19335.smt2                                                                        |1260.155s |8184.0MiB|
|scrambled107826.smt2                                                                       |1260.133s |7996.0MiB|
|scrambled108840.smt2                                                                       |1260.047s |7344.0MiB|
|scrambled102166.smt2                                                                       |1260.033s |7333.0MiB|
|scrambled43577.smt2                                                                        |1260.089s |6375.0MiB|
|scrambled61922.smt2                                                                        |1260.051s |5882.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1260.033s  |1260.033s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1260.060s  |1260.060s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1260.109s  |1260.109s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |1260.133s  |1260.133s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1260.047s  |1260.047s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1260.126s  |1260.126s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  30.220s  |  30.220s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1260.133s  |1260.133s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1260.150s  |1260.150s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  43.916s  |  43.916s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        |   7.677s  |   7.677s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        | 230.339s  | 230.339s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1260.047s  |1260.047s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        | 968.021s  | 968.021s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |  29.336s  |  29.336s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1260.090s  |1260.090s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1260.155s  |1260.155s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  55.660s  |  55.660s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         |  58.155s  |  58.155s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1260.058s  |1260.058s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         | 633.902s  | 633.902s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1260.140s  |1260.140s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1260.053s  |1260.053s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1260.099s  |1260.099s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1260.099s  |1260.099s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1260.114s  |1260.114s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1260.089s  |1260.089s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         | 130.736s  | 130.736s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1260.139s  |1260.139s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1260.115s  |1260.115s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1260.156s  |1260.156s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1260.047s  |1260.047s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1260.043s  |1260.043s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |1260.051s  |1260.051s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1260.135s  |1260.135s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1260.123s  |1260.123s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         | 268.102s  | 268.102s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1260.038s  |1260.038s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          | 444.990s  | 444.990s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1260.068s  |1260.068s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1260.049s  |1260.049s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1260.065s  |1260.065s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1260.259s  |1260.259s  |   0.000s  | 0.0%|
</details>
