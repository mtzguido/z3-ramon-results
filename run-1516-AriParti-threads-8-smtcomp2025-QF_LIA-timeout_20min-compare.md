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
Job tag: AriParti-threads-8-smtcomp2025-QF_LIA-timeout_20min
Runner: rise-runner-2
AriParti repo: shaowei-cai-group/AriParti
AriParti commit: 8f131f9ccdfff7303fa29d9eb28f5cd893c170d7
AriParti branch: main
AriParti options: "--engine=ariparti --ariparti-dir=. --ariparti-entry=bin/AriParti.py --ariparti-partitioner=bin/partitioner --ariparti-solver=bin/ariparti-solver --ariparti-max-running-tasks=8 --ariparti-time-limit=1200"
AriParti solver backend: z3
AriParti inputs: inputs/smt_comp_2025_parallel/QF_LIA
AriParti commit message: docs: updated 'Cite This Work' section in README with official citation.

</pre>
# RHS
<pre>
Ramon benchmark for AriParti
-
Job description: 
Job tag: AriParti-threads-8-smtcomp2025-QF_LIA-timeout_20min
Runner: rise-runner-2
AriParti repo: shaowei-cai-group/AriParti
AriParti commit: 8f131f9ccdfff7303fa29d9eb28f5cd893c170d7
AriParti branch: main
AriParti options: "--engine=ariparti --ariparti-dir=. --ariparti-entry=bin/AriParti.py --ariparti-partitioner=bin/partitioner --ariparti-solver=bin/ariparti-solver --ariparti-max-running-tasks=8 --ariparti-time-limit=1200"
AriParti solver backend: z3
AriParti inputs: inputs/smt_comp_2025_parallel/QF_LIA
AriParti commit message: docs: updated 'Cite This Work' section in README with official citation.

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.234s  |1200.234s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.276s  |1200.276s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.458s  |1200.458s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  84.088s  |  84.088s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.935s  |1200.935s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.485s  |1200.485s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  53.570s  |  53.570s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.426s  |1200.426s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1201.192s  |1201.192s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 356.773s  | 356.773s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 425.561s  | 425.561s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.656s  |1200.656s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.191s  |1200.191s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.692s  |1200.692s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.318s  |1200.318s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.480s  |1200.480s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 892.342s  | 892.342s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 388.403s  | 388.403s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.404s  |1200.404s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.234s  |1200.234s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.276s  |1200.276s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.458s  |1200.458s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  84.088s  |  84.088s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.935s  |1200.935s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.485s  |1200.485s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  53.570s  |  53.570s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.426s  |1200.426s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1201.192s  |1201.192s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 356.773s  | 356.773s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 425.561s  | 425.561s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.656s  |1200.656s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.191s  |1200.191s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.692s  |1200.692s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.318s  |1200.318s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.480s  |1200.480s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 892.342s  | 892.342s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 388.403s  | 388.403s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.404s  |1200.404s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.234s  |1200.234s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.276s  |1200.276s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.458s  |1200.458s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  84.088s  |  84.088s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.935s  |1200.935s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.485s  |1200.485s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  53.570s  |  53.570s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.426s  |1200.426s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1201.192s  |1201.192s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 356.773s  | 356.773s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 425.561s  | 425.561s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.656s  |1200.656s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.191s  |1200.191s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.692s  |1200.692s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.318s  |1200.318s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.480s  |1200.480s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 892.342s  | 892.342s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 388.403s  | 388.403s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.404s  |1200.404s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.234s  |1200.234s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.276s  |1200.276s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.458s  |1200.458s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  84.088s  |  84.088s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.935s  |1200.935s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.485s  |1200.485s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  53.570s  |  53.570s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.426s  |1200.426s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1201.192s  |1201.192s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 356.773s  | 356.773s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 425.561s  | 425.561s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.656s  |1200.656s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.191s  |1200.191s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.692s  |1200.692s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.318s  |1200.318s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.480s  |1200.480s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 892.342s  | 892.342s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 388.403s  | 388.403s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.404s  |1200.404s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled59713.smt2                                                                        |1201.201s |13.552GiB|
|scrambled4299.smt2                                                                         |1201.200s |10.319GiB|
|scrambled12042.smt2                                                                        |1201.192s |18.97GiB|
|scrambled79867.smt2                                                                        |1201.152s |13.81GiB|
|scrambled108840.smt2                                                                       |1200.935s |10.289GiB|
|scrambled45952.smt2                                                                        |1200.928s |13.374GiB|
|scrambled55680.smt2                                                                        |1200.926s |17.159GiB|
|scrambled75189.smt2                                                                        |1200.724s |9152.0MiB|
|scrambled128874.smt2                                                                       |1200.692s |3496.0MiB|
|scrambled40621.smt2                                                                        |1200.685s |4768.0MiB|
|scrambled94658.smt2                                                                        |1200.680s |20.6GiB|
|scrambled128128.smt2                                                                       |1200.656s |4608.0MiB|
|scrambled65181.smt2                                                                        |1200.656s |16.171GiB|
|scrambled79760.smt2                                                                        |1200.566s |9418.0MiB|
|scrambled43577.smt2                                                                        |1200.532s |10.22GiB|
|scrambled111627.smt2                                                                       |1200.485s |9709.0MiB|
|scrambled19335.smt2                                                                        |1200.480s |6180.0MiB|
|scrambled79766.smt2                                                                        |1200.465s |13.855GiB|
|scrambled107115.smt2                                                                       |1200.458s |6401.0MiB|
|scrambled119331.smt2                                                                       |1200.426s |5683.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled59713.smt2                                                                        |1201.201s |13.552GiB|
|scrambled4299.smt2                                                                         |1201.200s |10.319GiB|
|scrambled12042.smt2                                                                        |1201.192s |18.97GiB|
|scrambled79867.smt2                                                                        |1201.152s |13.81GiB|
|scrambled108840.smt2                                                                       |1200.935s |10.289GiB|
|scrambled45952.smt2                                                                        |1200.928s |13.374GiB|
|scrambled55680.smt2                                                                        |1200.926s |17.159GiB|
|scrambled75189.smt2                                                                        |1200.724s |9152.0MiB|
|scrambled128874.smt2                                                                       |1200.692s |3496.0MiB|
|scrambled40621.smt2                                                                        |1200.685s |4768.0MiB|
|scrambled94658.smt2                                                                        |1200.680s |20.6GiB|
|scrambled128128.smt2                                                                       |1200.656s |4608.0MiB|
|scrambled65181.smt2                                                                        |1200.656s |16.171GiB|
|scrambled79760.smt2                                                                        |1200.566s |9418.0MiB|
|scrambled43577.smt2                                                                        |1200.532s |10.22GiB|
|scrambled111627.smt2                                                                       |1200.485s |9709.0MiB|
|scrambled19335.smt2                                                                        |1200.480s |6180.0MiB|
|scrambled79766.smt2                                                                        |1200.465s |13.855GiB|
|scrambled107115.smt2                                                                       |1200.458s |6401.0MiB|
|scrambled119331.smt2                                                                       |1200.426s |5683.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |14.085GiB|14.085GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |13.672GiB|13.672GiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |6401.0MiB|6401.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |3603.0MiB|3603.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |10.289GiB|10.289GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |9709.0MiB|9709.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |827.0MiB|827.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |5683.0MiB|5683.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |18.97GiB|18.97GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |962.0MiB|962.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1269.0MiB|1269.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |4608.0MiB|4608.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |3641.0MiB|3641.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |3496.0MiB|3496.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |4960.0MiB|4960.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |547.0MiB|547.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |6180.0MiB|6180.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1427.0MiB|1427.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |4480.0MiB|4480.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |5681.0MiB|5681.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |14.085GiB|14.085GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |13.672GiB|13.672GiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |6401.0MiB|6401.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |3603.0MiB|3603.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |10.289GiB|10.289GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |9709.0MiB|9709.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |827.0MiB|827.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |5683.0MiB|5683.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |18.97GiB|18.97GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |962.0MiB|962.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1269.0MiB|1269.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |4608.0MiB|4608.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |3641.0MiB|3641.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |3496.0MiB|3496.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |4960.0MiB|4960.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |547.0MiB|547.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |6180.0MiB|6180.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1427.0MiB|1427.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |4480.0MiB|4480.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |5681.0MiB|5681.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |14.085GiB|14.085GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |13.672GiB|13.672GiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |6401.0MiB|6401.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |3603.0MiB|3603.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |10.289GiB|10.289GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |9709.0MiB|9709.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |827.0MiB|827.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |5683.0MiB|5683.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |18.97GiB|18.97GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |962.0MiB|962.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1269.0MiB|1269.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |4608.0MiB|4608.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |3641.0MiB|3641.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |3496.0MiB|3496.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |4960.0MiB|4960.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |547.0MiB|547.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |6180.0MiB|6180.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1427.0MiB|1427.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |4480.0MiB|4480.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |5681.0MiB|5681.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |14.085GiB|14.085GiB|0B| 0.0%|
|scrambled103783.smt2                                                                        |13.672GiB|13.672GiB|0B| 0.0%|
|scrambled107115.smt2                                                                        |6401.0MiB|6401.0MiB|0B| 0.0%|
|scrambled107826.smt2                                                                        |3603.0MiB|3603.0MiB|0B| 0.0%|
|scrambled108840.smt2                                                                        |10.289GiB|10.289GiB|0B| 0.0%|
|scrambled111627.smt2                                                                        |9709.0MiB|9709.0MiB|0B| 0.0%|
|scrambled118793.smt2                                                                        |827.0MiB|827.0MiB|0B| 0.0%|
|scrambled119331.smt2                                                                        |5683.0MiB|5683.0MiB|0B| 0.0%|
|scrambled12042.smt2                                                                         |18.97GiB|18.97GiB|0B| 0.0%|
|scrambled125827.smt2                                                                        |962.0MiB|962.0MiB|0B| 0.0%|
|scrambled125888.smt2                                                                        |1269.0MiB|1269.0MiB|0B| 0.0%|
|scrambled128128.smt2                                                                        |4608.0MiB|4608.0MiB|0B| 0.0%|
|scrambled128732.smt2                                                                        |3641.0MiB|3641.0MiB|0B| 0.0%|
|scrambled128874.smt2                                                                        |3496.0MiB|3496.0MiB|0B| 0.0%|
|scrambled131241.smt2                                                                        |4960.0MiB|4960.0MiB|0B| 0.0%|
|scrambled1417.smt2                                                                          |547.0MiB|547.0MiB|0B| 0.0%|
|scrambled19335.smt2                                                                         |6180.0MiB|6180.0MiB|0B| 0.0%|
|scrambled20101.smt2                                                                         |1427.0MiB|1427.0MiB|0B| 0.0%|
|scrambled25238.smt2                                                                         |4480.0MiB|4480.0MiB|0B| 0.0%|
|scrambled27843.smt2                                                                         |5681.0MiB|5681.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1200.680s |20.6GiB|
|scrambled12042.smt2                                                                        |1201.192s |18.97GiB|
|scrambled4198.smt2                                                                         |1200.255s |18.875GiB|
|scrambled55680.smt2                                                                        |1200.926s |17.159GiB|
|scrambled65181.smt2                                                                        |1200.656s |16.171GiB|
|scrambled39514.smt2                                                                        |1200.258s |14.848GiB|
|scrambled102166.smt2                                                                       |1200.234s |14.085GiB|
|scrambled79766.smt2                                                                        |1200.465s |13.855GiB|
|scrambled79867.smt2                                                                        |1201.152s |13.81GiB|
|scrambled103783.smt2                                                                       |1200.276s |13.672GiB|
|scrambled59713.smt2                                                                        |1201.201s |13.552GiB|
|scrambled45952.smt2                                                                        |1200.928s |13.374GiB|
|scrambled3854.smt2                                                                         |1200.229s |11.773GiB|
|scrambled4299.smt2                                                                         |1201.200s |10.319GiB|
|scrambled108840.smt2                                                                       |1200.935s |10.289GiB|
|scrambled43577.smt2                                                                        |1200.532s |10.22GiB|
|scrambled68944.smt2                                                                        |1200.355s |10.026GiB|
|scrambled111627.smt2                                                                       |1200.485s |9709.0MiB|
|scrambled79760.smt2                                                                        |1200.566s |9418.0MiB|
|scrambled75189.smt2                                                                        |1200.724s |9152.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled94658.smt2                                                                        |1200.680s |20.6GiB|
|scrambled12042.smt2                                                                        |1201.192s |18.97GiB|
|scrambled4198.smt2                                                                         |1200.255s |18.875GiB|
|scrambled55680.smt2                                                                        |1200.926s |17.159GiB|
|scrambled65181.smt2                                                                        |1200.656s |16.171GiB|
|scrambled39514.smt2                                                                        |1200.258s |14.848GiB|
|scrambled102166.smt2                                                                       |1200.234s |14.085GiB|
|scrambled79766.smt2                                                                        |1200.465s |13.855GiB|
|scrambled79867.smt2                                                                        |1201.152s |13.81GiB|
|scrambled103783.smt2                                                                       |1200.276s |13.672GiB|
|scrambled59713.smt2                                                                        |1201.201s |13.552GiB|
|scrambled45952.smt2                                                                        |1200.928s |13.374GiB|
|scrambled3854.smt2                                                                         |1200.229s |11.773GiB|
|scrambled4299.smt2                                                                         |1201.200s |10.319GiB|
|scrambled108840.smt2                                                                       |1200.935s |10.289GiB|
|scrambled43577.smt2                                                                        |1200.532s |10.22GiB|
|scrambled68944.smt2                                                                        |1200.355s |10.026GiB|
|scrambled111627.smt2                                                                       |1200.485s |9709.0MiB|
|scrambled79760.smt2                                                                        |1200.566s |9418.0MiB|
|scrambled75189.smt2                                                                        |1200.724s |9152.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled102166.smt2                                                                        |1200.234s  |1200.234s  |   0.000s  | 0.0%|
|scrambled103783.smt2                                                                        |1200.276s  |1200.276s  |   0.000s  | 0.0%|
|scrambled107115.smt2                                                                        |1200.458s  |1200.458s  |   0.000s  | 0.0%|
|scrambled107826.smt2                                                                        |  84.088s  |  84.088s  |   0.000s  | 0.0%|
|scrambled108840.smt2                                                                        |1200.935s  |1200.935s  |   0.000s  | 0.0%|
|scrambled111627.smt2                                                                        |1200.485s  |1200.485s  |   0.000s  | 0.0%|
|scrambled118793.smt2                                                                        |  53.570s  |  53.570s  |   0.000s  | 0.0%|
|scrambled119331.smt2                                                                        |1200.426s  |1200.426s  |   0.000s  | 0.0%|
|scrambled12042.smt2                                                                         |1201.192s  |1201.192s  |   0.000s  | 0.0%|
|scrambled125827.smt2                                                                        | 356.773s  | 356.773s  |   0.000s  | 0.0%|
|scrambled125888.smt2                                                                        | 425.561s  | 425.561s  |   0.000s  | 0.0%|
|scrambled128128.smt2                                                                        |1200.656s  |1200.656s  |   0.000s  | 0.0%|
|scrambled128732.smt2                                                                        |1200.191s  |1200.191s  |   0.000s  | 0.0%|
|scrambled128874.smt2                                                                        |1200.692s  |1200.692s  |   0.000s  | 0.0%|
|scrambled131241.smt2                                                                        |1200.318s  |1200.318s  |   0.000s  | 0.0%|
|scrambled1417.smt2                                                                          |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled19335.smt2                                                                         |1200.480s  |1200.480s  |   0.000s  | 0.0%|
|scrambled20101.smt2                                                                         | 892.342s  | 892.342s  |   0.000s  | 0.0%|
|scrambled25238.smt2                                                                         | 388.403s  | 388.403s  |   0.000s  | 0.0%|
|scrambled27843.smt2                                                                         |1200.404s  |1200.404s  |   0.000s  | 0.0%|
|scrambled32836.smt2                                                                         |1200.298s  |1200.298s  |   0.000s  | 0.0%|
|scrambled3854.smt2                                                                          |1200.229s  |1200.229s  |   0.000s  | 0.0%|
|scrambled39514.smt2                                                                         |1200.258s  |1200.258s  |   0.000s  | 0.0%|
|scrambled40621.smt2                                                                         |1200.685s  |1200.685s  |   0.000s  | 0.0%|
|scrambled4198.smt2                                                                          |1200.255s  |1200.255s  |   0.000s  | 0.0%|
|scrambled4299.smt2                                                                          |1201.200s  |1201.200s  |   0.000s  | 0.0%|
|scrambled43577.smt2                                                                         |1200.532s  |1200.532s  |   0.000s  | 0.0%|
|scrambled44911.smt2                                                                         |1200.259s  |1200.259s  |   0.000s  | 0.0%|
|scrambled45952.smt2                                                                         |1200.928s  |1200.928s  |   0.000s  | 0.0%|
|scrambled51053.smt2                                                                         |1006.929s  |1006.929s  |   0.000s  | 0.0%|
|scrambled55680.smt2                                                                         |1200.926s  |1200.926s  |   0.000s  | 0.0%|
|scrambled55777.smt2                                                                         |1200.140s  |1200.140s  |   0.000s  | 0.0%|
|scrambled59713.smt2                                                                         |1201.201s  |1201.201s  |   0.000s  | 0.0%|
|scrambled61922.smt2                                                                         | 463.010s  | 463.010s  |   0.000s  | 0.0%|
|scrambled65181.smt2                                                                         |1200.656s  |1200.656s  |   0.000s  | 0.0%|
|scrambled68944.smt2                                                                         |1200.355s  |1200.355s  |   0.000s  | 0.0%|
|scrambled72668.smt2                                                                         | 157.163s  | 157.163s  |   0.000s  | 0.0%|
|scrambled75189.smt2                                                                         |1200.724s  |1200.724s  |   0.000s  | 0.0%|
|scrambled7741.smt2                                                                          |1200.283s  |1200.283s  |   0.000s  | 0.0%|
|scrambled79760.smt2                                                                         |1200.566s  |1200.566s  |   0.000s  | 0.0%|
|scrambled79766.smt2                                                                         |1200.465s  |1200.465s  |   0.000s  | 0.0%|
|scrambled79867.smt2                                                                         |1201.152s  |1201.152s  |   0.000s  | 0.0%|
|scrambled94658.smt2                                                                         |1200.680s  |1200.680s  |   0.000s  | 0.0%|
</details>
