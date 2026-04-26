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
Ramon benchmark for AriParti
-
Job description: 
Job tag: AriParti-threads-64-smtcomp2025-QF_LIA-timeout_20min
Runner: rise-runner-2
AriParti repo: shaowei-cai-group/AriParti
AriParti commit: 8f131f9ccdfff7303fa29d9eb28f5cd893c170d7
AriParti branch: main
AriParti options: "--engine=ariparti --ariparti-dir=. --ariparti-entry=bin/AriParti.py --ariparti-partitioner=bin/partitioner --ariparti-solver=bin/ariparti-solver --ariparti-max-running-tasks=64 --ariparti-time-limit=1200"
AriParti solver backend: z3
AriParti inputs: inputs/smt_comp_2025_parallel/QF_LIA
AriParti commit message: docs: updated 'Cite This Work' section in README with official citation.

</pre>
# RHS
<pre>
Ramon benchmark for AriParti
-
Job description: 
Job tag: AriParti-threads-64-smtcomp2025-QF_LIA-timeout_20min
Runner: rise-runner-2
AriParti repo: shaowei-cai-group/AriParti
AriParti commit: 8f131f9ccdfff7303fa29d9eb28f5cd893c170d7
AriParti branch: main
AriParti options: "--engine=ariparti --ariparti-dir=. --ariparti-entry=bin/AriParti.py --ariparti-partitioner=bin/partitioner --ariparti-solver=bin/ariparti-solver --ariparti-max-running-tasks=64 --ariparti-time-limit=1200"
AriParti solver backend: z3
AriParti inputs: inputs/smt_comp_2025_parallel/QF_LIA
AriParti commit message: docs: updated 'Cite This Work' section in README with official citation.

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1201.390s  |1201.390s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1201.669s  |1201.669s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.914s  |1200.914s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  28.638s  |  28.638s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1201.953s  |1201.953s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1201.479s  |1201.479s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  33.082s  |  33.082s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.863s  |1200.863s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1203.621s  |1203.621s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  27.049s  |  27.049s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 123.908s  | 123.908s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  31.068s  |  31.068s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1035.436s  |1035.436s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.985s  |1200.985s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.690s  |1200.690s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.300s  |1200.300s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1201.840s  |1201.840s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  73.161s  |  73.161s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 149.528s  | 149.528s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1201.590s  |1201.590s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1201.390s  |1201.390s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1201.669s  |1201.669s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.914s  |1200.914s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  28.638s  |  28.638s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1201.953s  |1201.953s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1201.479s  |1201.479s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  33.082s  |  33.082s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.863s  |1200.863s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1203.621s  |1203.621s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  27.049s  |  27.049s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 123.908s  | 123.908s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  31.068s  |  31.068s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1035.436s  |1035.436s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.985s  |1200.985s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.690s  |1200.690s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.300s  |1200.300s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1201.840s  |1201.840s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  73.161s  |  73.161s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 149.528s  | 149.528s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1201.590s  |1201.590s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1201.390s  |1201.390s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1201.669s  |1201.669s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.914s  |1200.914s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  28.638s  |  28.638s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1201.953s  |1201.953s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1201.479s  |1201.479s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  33.082s  |  33.082s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.863s  |1200.863s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1203.621s  |1203.621s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  27.049s  |  27.049s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 123.908s  | 123.908s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  31.068s  |  31.068s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1035.436s  |1035.436s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.985s  |1200.985s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.690s  |1200.690s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.300s  |1200.300s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1201.840s  |1201.840s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  73.161s  |  73.161s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 149.528s  | 149.528s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1201.590s  |1201.590s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1201.390s  |1201.390s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1201.669s  |1201.669s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.914s  |1200.914s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  28.638s  |  28.638s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1201.953s  |1201.953s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1201.479s  |1201.479s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  33.082s  |  33.082s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.863s  |1200.863s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1203.621s  |1203.621s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  27.049s  |  27.049s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 123.908s  | 123.908s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  31.068s  |  31.068s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1035.436s  |1035.436s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.985s  |1200.985s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.690s  |1200.690s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.300s  |1200.300s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1201.840s  |1201.840s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  73.161s  |  73.161s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 149.528s  | 149.528s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1201.590s  |1201.590s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1203.783s |133.0GiB|
|scrambled12042.smt2                                                                        |1203.621s |120.0GiB|
|scrambled55680.smt2                                                                        |1203.274s |116.0GiB|
|scrambled65181.smt2                                                                        |1202.292s |106.0GiB|
|scrambled39514.smt2                                                                        |1202.037s |108.0GiB|
|scrambled108840.smt2                                                                       |1201.953s |64.935GiB|
|scrambled19335.smt2                                                                        |1201.840s |41.492GiB|
|scrambled43577.smt2                                                                        |1201.815s |52.937GiB|
|scrambled79766.smt2                                                                        |1201.707s |107.0GiB|
|scrambled103783.smt2                                                                       |1201.669s |111.0GiB|
|scrambled3854.smt2                                                                         |1201.652s |103.0GiB|
|scrambled27843.smt2                                                                        |1201.590s |31.446GiB|
|scrambled59713.smt2                                                                        |1201.527s |99.0GiB|
|scrambled111627.smt2                                                                       |1201.479s |50.605GiB|
|scrambled102166.smt2                                                                       |1201.390s |92.879GiB|
|scrambled79760.smt2                                                                        |1201.378s |70.595GiB|
|scrambled79867.smt2                                                                        |1201.351s |100.0GiB|
|scrambled75189.smt2                                                                        |1201.286s |50.567GiB|
|scrambled68944.smt2                                                                        |1201.258s |62.403GiB|
|scrambled40621.smt2                                                                        |1201.256s |43.036GiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1203.783s |133.0GiB|
|scrambled12042.smt2                                                                        |1203.621s |120.0GiB|
|scrambled55680.smt2                                                                        |1203.274s |116.0GiB|
|scrambled65181.smt2                                                                        |1202.292s |106.0GiB|
|scrambled39514.smt2                                                                        |1202.037s |108.0GiB|
|scrambled108840.smt2                                                                       |1201.953s |64.935GiB|
|scrambled19335.smt2                                                                        |1201.840s |41.492GiB|
|scrambled43577.smt2                                                                        |1201.815s |52.937GiB|
|scrambled79766.smt2                                                                        |1201.707s |107.0GiB|
|scrambled103783.smt2                                                                       |1201.669s |111.0GiB|
|scrambled3854.smt2                                                                         |1201.652s |103.0GiB|
|scrambled27843.smt2                                                                        |1201.590s |31.446GiB|
|scrambled59713.smt2                                                                        |1201.527s |99.0GiB|
|scrambled111627.smt2                                                                       |1201.479s |50.605GiB|
|scrambled102166.smt2                                                                       |1201.390s |92.879GiB|
|scrambled79760.smt2                                                                        |1201.378s |70.595GiB|
|scrambled79867.smt2                                                                        |1201.351s |100.0GiB|
|scrambled75189.smt2                                                                        |1201.286s |50.567GiB|
|scrambled68944.smt2                                                                        |1201.258s |62.403GiB|
|scrambled40621.smt2                                                                        |1201.256s |43.036GiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |92.879GiB|92.879GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |111.0GiB|111.0GiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |38.755GiB|38.755GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |9629.0MiB|9629.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |64.935GiB|64.935GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |50.605GiB|50.605GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |6070.0MiB|6070.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |44.91GiB|44.91GiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |120.0GiB|120.0GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |6560.0MiB|6560.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |8905.0MiB|8905.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |16.002GiB|16.002GiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |26.832GiB|26.832GiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |27.291GiB|27.291GiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |37.812GiB|37.812GiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |3768.0MiB|3768.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |41.492GiB|41.492GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |8767.0MiB|8767.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |27.384GiB|27.384GiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |31.446GiB|31.446GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |92.879GiB|92.879GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |111.0GiB|111.0GiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |38.755GiB|38.755GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |9629.0MiB|9629.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |64.935GiB|64.935GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |50.605GiB|50.605GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |6070.0MiB|6070.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |44.91GiB|44.91GiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |120.0GiB|120.0GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |6560.0MiB|6560.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |8905.0MiB|8905.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |16.002GiB|16.002GiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |26.832GiB|26.832GiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |27.291GiB|27.291GiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |37.812GiB|37.812GiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |3768.0MiB|3768.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |41.492GiB|41.492GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |8767.0MiB|8767.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |27.384GiB|27.384GiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |31.446GiB|31.446GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |92.879GiB|92.879GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |111.0GiB|111.0GiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |38.755GiB|38.755GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |9629.0MiB|9629.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |64.935GiB|64.935GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |50.605GiB|50.605GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |6070.0MiB|6070.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |44.91GiB|44.91GiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |120.0GiB|120.0GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |6560.0MiB|6560.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |8905.0MiB|8905.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |16.002GiB|16.002GiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |26.832GiB|26.832GiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |27.291GiB|27.291GiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |37.812GiB|37.812GiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |3768.0MiB|3768.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |41.492GiB|41.492GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |8767.0MiB|8767.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |27.384GiB|27.384GiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |31.446GiB|31.446GiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |92.879GiB|92.879GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |111.0GiB|111.0GiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |38.755GiB|38.755GiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |9629.0MiB|9629.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |64.935GiB|64.935GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |50.605GiB|50.605GiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |6070.0MiB|6070.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |44.91GiB|44.91GiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |120.0GiB|120.0GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |6560.0MiB|6560.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |8905.0MiB|8905.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |16.002GiB|16.002GiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |26.832GiB|26.832GiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |27.291GiB|27.291GiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |37.812GiB|37.812GiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |3768.0MiB|3768.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |41.492GiB|41.492GiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |8767.0MiB|8767.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |27.384GiB|27.384GiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |31.446GiB|31.446GiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1203.783s |133.0GiB|
|scrambled12042.smt2                                                                        |1203.621s |120.0GiB|
|scrambled55680.smt2                                                                        |1203.274s |116.0GiB|
|scrambled103783.smt2                                                                       |1201.669s |111.0GiB|
|scrambled39514.smt2                                                                        |1202.037s |108.0GiB|
|scrambled79766.smt2                                                                        |1201.707s |107.0GiB|
|scrambled65181.smt2                                                                        |1202.292s |106.0GiB|
|scrambled3854.smt2                                                                         |1201.652s |103.0GiB|
|scrambled79867.smt2                                                                        |1201.351s |100.0GiB|
|scrambled45952.smt2                                                                        |1200.755s |99.085GiB|
|scrambled59713.smt2                                                                        |1201.527s |99.0GiB|
|scrambled102166.smt2                                                                       |1201.390s |92.879GiB|
|scrambled79760.smt2                                                                        |1201.378s |70.595GiB|
|scrambled108840.smt2                                                                       |1201.953s |64.935GiB|
|scrambled68944.smt2                                                                        |1201.258s |62.403GiB|
|scrambled4198.smt2                                                                         |  62.633s |53.11GiB|
|scrambled43577.smt2                                                                        |1201.815s |52.937GiB|
|scrambled111627.smt2                                                                       |1201.479s |50.605GiB|
|scrambled75189.smt2                                                                        |1201.286s |50.567GiB|
|scrambled119331.smt2                                                                       |1200.863s |44.91GiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1203.783s |133.0GiB|
|scrambled12042.smt2                                                                        |1203.621s |120.0GiB|
|scrambled55680.smt2                                                                        |1203.274s |116.0GiB|
|scrambled103783.smt2                                                                       |1201.669s |111.0GiB|
|scrambled39514.smt2                                                                        |1202.037s |108.0GiB|
|scrambled79766.smt2                                                                        |1201.707s |107.0GiB|
|scrambled65181.smt2                                                                        |1202.292s |106.0GiB|
|scrambled3854.smt2                                                                         |1201.652s |103.0GiB|
|scrambled79867.smt2                                                                        |1201.351s |100.0GiB|
|scrambled45952.smt2                                                                        |1200.755s |99.085GiB|
|scrambled59713.smt2                                                                        |1201.527s |99.0GiB|
|scrambled102166.smt2                                                                       |1201.390s |92.879GiB|
|scrambled79760.smt2                                                                        |1201.378s |70.595GiB|
|scrambled108840.smt2                                                                       |1201.953s |64.935GiB|
|scrambled68944.smt2                                                                        |1201.258s |62.403GiB|
|scrambled4198.smt2                                                                         |  62.633s |53.11GiB|
|scrambled43577.smt2                                                                        |1201.815s |52.937GiB|
|scrambled111627.smt2                                                                       |1201.479s |50.605GiB|
|scrambled75189.smt2                                                                        |1201.286s |50.567GiB|
|scrambled119331.smt2                                                                       |1200.863s |44.91GiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1201.390s  |1201.390s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1201.669s  |1201.669s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.914s  |1200.914s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  28.638s  |  28.638s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1201.953s  |1201.953s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1201.479s  |1201.479s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  33.082s  |  33.082s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.863s  |1200.863s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1203.621s  |1203.621s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        |  27.049s  |  27.049s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 123.908s  | 123.908s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |  31.068s  |  31.068s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1035.436s  |1035.436s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.985s  |1200.985s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.690s  |1200.690s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.300s  |1200.300s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1201.840s  |1201.840s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         |  73.161s  |  73.161s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 149.528s  | 149.528s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1201.590s  |1201.590s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |1200.735s  |1200.735s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1201.652s  |1201.652s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1202.037s  |1202.037s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1201.256s  |1201.256s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |  62.633s  |  62.633s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |  34.722s  |  34.722s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1201.815s  |1201.815s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |  91.458s  |  91.458s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1200.755s  |1200.755s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         | 293.247s  | 293.247s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1203.274s  |1203.274s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1200.580s  |1200.580s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1201.527s  |1201.527s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         |   7.714s  |   7.714s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1202.292s  |1202.292s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1201.258s  |1201.258s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         | 172.361s  | 172.361s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1201.286s  |1201.286s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1200.732s  |1200.732s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1201.378s  |1201.378s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1201.707s  |1201.707s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1201.351s  |1201.351s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1203.783s  |1203.783s  |   0.000s  | 0.0%|
</details>
