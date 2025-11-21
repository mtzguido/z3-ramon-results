Comparing data and data


# SUMMARY
- LHS tests = 189
- RHS tests = 189
- LHS success = 188  (99.47089947089947%)
- RHS success = 188  (99.47089947089947%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: certora2-parallel
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: ed84b14e6c7dfaf6efd1b740119ecb1631e8bdfb
Z3 branch: arie
Z3 options: "-T:30 smt.arith.nl.nra.poly=true smt.threads=4"
Z3 inputs: inputs/certora2
Z3 commit message: fixing coi bug

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: certora2-parallel
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: ed84b14e6c7dfaf6efd1b740119ecb1631e8bdfb
Z3 branch: arie
Z3 options: "-T:30 smt.arith.nl.nra.poly=true smt.threads=4"
Z3 inputs: inputs/certora2
Z3 commit message: fixing coi bug

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   0.311s  |   0.311s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   0.931s  |   0.931s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   0.503s  |   0.503s  |   0.000s  | 0.0%|
|auk-0007.smt2                                                                               |  30.123s  |  30.123s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|auk-0009.smt2                                                                               |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |   0.351s  |   0.351s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|auk-0017.smt2                                                                               |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|auk-0018.smt2                                                                               |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|auk-0021.smt2                                                                               |   0.193s  |   0.193s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   0.311s  |   0.311s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   0.931s  |   0.931s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   0.503s  |   0.503s  |   0.000s  | 0.0%|
|auk-0007.smt2                                                                               |  30.123s  |  30.123s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|auk-0009.smt2                                                                               |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |   0.351s  |   0.351s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|auk-0017.smt2                                                                               |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|auk-0018.smt2                                                                               |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|auk-0021.smt2                                                                               |   0.193s  |   0.193s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   0.311s  |   0.311s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   0.931s  |   0.931s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   0.503s  |   0.503s  |   0.000s  | 0.0%|
|auk-0007.smt2                                                                               |  30.123s  |  30.123s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|auk-0009.smt2                                                                               |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |   0.351s  |   0.351s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|auk-0017.smt2                                                                               |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|auk-0018.smt2                                                                               |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|auk-0021.smt2                                                                               |   0.193s  |   0.193s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   0.311s  |   0.311s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   0.931s  |   0.931s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   0.503s  |   0.503s  |   0.000s  | 0.0%|
|auk-0007.smt2                                                                               |  30.123s  |  30.123s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|auk-0009.smt2                                                                               |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |   0.351s  |   0.351s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|auk-0017.smt2                                                                               |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|auk-0018.smt2                                                                               |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|auk-0021.smt2                                                                               |   0.193s  |   0.193s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|auk-0099.smt2                                                                              |  30.127s |932.0MiB|
|auk-0007.smt2                                                                              |  30.123s |862.0MiB|
|auk-0098.smt2                                                                              |  30.118s |845.0MiB|
|auk-0088.smt2                                                                              |  30.062s |337.0MiB|
|auk-0085.smt2                                                                              |  30.057s |348.0MiB|
|auk-0086.smt2                                                                              |  30.054s |361.0MiB|
|auk-0092.smt2                                                                              |  30.050s |345.0MiB|
|auk-0188.smt2                                                                              |  30.046s |201.0MiB|
|auk-0147.smt2                                                                              |  30.045s |153.0MiB|
|auk-0011.smt2                                                                              |  30.042s |210.0MiB|
|auk-0005.smt2                                                                              |  30.036s |182.0MiB|
|auk-0187.smt2                                                                              |  30.034s |220.0MiB|
|auk-0074.smt2                                                                              |  30.031s |135.0MiB|
|auk-0081.smt2                                                                              |  28.294s |145.0MiB|
|auk-0141.smt2                                                                              |  24.617s |213.0MiB|
|auk-0015.smt2                                                                              |  22.537s |179.0MiB|
|auk-0189.smt2                                                                              |  19.091s |214.0MiB|
|auk-0185.smt2                                                                              |  17.988s |193.0MiB|
|auk-0137.smt2                                                                              |  15.124s |146.0MiB|
|auk-0140.smt2                                                                              |  12.758s |162.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|auk-0099.smt2                                                                              |  30.127s |932.0MiB|
|auk-0007.smt2                                                                              |  30.123s |862.0MiB|
|auk-0098.smt2                                                                              |  30.118s |845.0MiB|
|auk-0088.smt2                                                                              |  30.062s |337.0MiB|
|auk-0085.smt2                                                                              |  30.057s |348.0MiB|
|auk-0086.smt2                                                                              |  30.054s |361.0MiB|
|auk-0092.smt2                                                                              |  30.050s |345.0MiB|
|auk-0188.smt2                                                                              |  30.046s |201.0MiB|
|auk-0147.smt2                                                                              |  30.045s |153.0MiB|
|auk-0011.smt2                                                                              |  30.042s |210.0MiB|
|auk-0005.smt2                                                                              |  30.036s |182.0MiB|
|auk-0187.smt2                                                                              |  30.034s |220.0MiB|
|auk-0074.smt2                                                                              |  30.031s |135.0MiB|
|auk-0081.smt2                                                                              |  28.294s |145.0MiB|
|auk-0141.smt2                                                                              |  24.617s |213.0MiB|
|auk-0015.smt2                                                                              |  22.537s |179.0MiB|
|auk-0189.smt2                                                                              |  19.091s |214.0MiB|
|auk-0185.smt2                                                                              |  17.988s |193.0MiB|
|auk-0137.smt2                                                                              |  15.124s |146.0MiB|
|auk-0140.smt2                                                                              |  12.758s |162.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |96.996MiB|96.996MiB|0B| 0.0%|
|auk-0002.smt2                                                                               |130.0MiB|130.0MiB|0B| 0.0%|
|auk-0003.smt2                                                                               |116.0MiB|116.0MiB|0B| 0.0%|
|auk-0004.smt2                                                                               |148.0MiB|148.0MiB|0B| 0.0%|
|auk-0005.smt2                                                                               |182.0MiB|182.0MiB|0B| 0.0%|
|auk-0006.smt2                                                                               |142.0MiB|142.0MiB|0B| 0.0%|
|auk-0007.smt2                                                                               |862.0MiB|862.0MiB|0B| 0.0%|
|auk-0008.smt2                                                                               |116.0MiB|116.0MiB|0B| 0.0%|
|auk-0009.smt2                                                                               |93.988MiB|93.988MiB|0B| 0.0%|
|auk-0010.smt2                                                                               |137.0MiB|137.0MiB|0B| 0.0%|
|auk-0011.smt2                                                                               |210.0MiB|210.0MiB|0B| 0.0%|
|auk-0012.smt2                                                                               |94.748MiB|94.748MiB|0B| 0.0%|
|auk-0013.smt2                                                                               |116.0MiB|116.0MiB|0B| 0.0%|
|auk-0014.smt2                                                                               |116.0MiB|116.0MiB|0B| 0.0%|
|auk-0016.smt2                                                                               |106.0MiB|106.0MiB|0B| 0.0%|
|auk-0017.smt2                                                                               |118.0MiB|118.0MiB|0B| 0.0%|
|auk-0018.smt2                                                                               |110.0MiB|110.0MiB|0B| 0.0%|
|auk-0019.smt2                                                                               |110.0MiB|110.0MiB|0B| 0.0%|
|auk-0020.smt2                                                                               |109.0MiB|109.0MiB|0B| 0.0%|
|auk-0021.smt2                                                                               |100.0MiB|100.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |96.996MiB|96.996MiB|0B| 0.0%|
|auk-0002.smt2                                                                               |130.0MiB|130.0MiB|0B| 0.0%|
|auk-0003.smt2                                                                               |116.0MiB|116.0MiB|0B| 0.0%|
|auk-0004.smt2                                                                               |148.0MiB|148.0MiB|0B| 0.0%|
|auk-0005.smt2                                                                               |182.0MiB|182.0MiB|0B| 0.0%|
|auk-0006.smt2                                                                               |142.0MiB|142.0MiB|0B| 0.0%|
|auk-0007.smt2                                                                               |862.0MiB|862.0MiB|0B| 0.0%|
|auk-0008.smt2                                                                               |116.0MiB|116.0MiB|0B| 0.0%|
|auk-0009.smt2                                                                               |93.988MiB|93.988MiB|0B| 0.0%|
|auk-0010.smt2                                                                               |137.0MiB|137.0MiB|0B| 0.0%|
|auk-0011.smt2                                                                               |210.0MiB|210.0MiB|0B| 0.0%|
|auk-0012.smt2                                                                               |94.748MiB|94.748MiB|0B| 0.0%|
|auk-0013.smt2                                                                               |116.0MiB|116.0MiB|0B| 0.0%|
|auk-0014.smt2                                                                               |116.0MiB|116.0MiB|0B| 0.0%|
|auk-0016.smt2                                                                               |106.0MiB|106.0MiB|0B| 0.0%|
|auk-0017.smt2                                                                               |118.0MiB|118.0MiB|0B| 0.0%|
|auk-0018.smt2                                                                               |110.0MiB|110.0MiB|0B| 0.0%|
|auk-0019.smt2                                                                               |110.0MiB|110.0MiB|0B| 0.0%|
|auk-0020.smt2                                                                               |109.0MiB|109.0MiB|0B| 0.0%|
|auk-0021.smt2                                                                               |100.0MiB|100.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |96.996MiB|96.996MiB|0B| 0.0%|
|auk-0002.smt2                                                                               |130.0MiB|130.0MiB|0B| 0.0%|
|auk-0003.smt2                                                                               |116.0MiB|116.0MiB|0B| 0.0%|
|auk-0004.smt2                                                                               |148.0MiB|148.0MiB|0B| 0.0%|
|auk-0005.smt2                                                                               |182.0MiB|182.0MiB|0B| 0.0%|
|auk-0006.smt2                                                                               |142.0MiB|142.0MiB|0B| 0.0%|
|auk-0007.smt2                                                                               |862.0MiB|862.0MiB|0B| 0.0%|
|auk-0008.smt2                                                                               |116.0MiB|116.0MiB|0B| 0.0%|
|auk-0009.smt2                                                                               |93.988MiB|93.988MiB|0B| 0.0%|
|auk-0010.smt2                                                                               |137.0MiB|137.0MiB|0B| 0.0%|
|auk-0011.smt2                                                                               |210.0MiB|210.0MiB|0B| 0.0%|
|auk-0012.smt2                                                                               |94.748MiB|94.748MiB|0B| 0.0%|
|auk-0013.smt2                                                                               |116.0MiB|116.0MiB|0B| 0.0%|
|auk-0014.smt2                                                                               |116.0MiB|116.0MiB|0B| 0.0%|
|auk-0016.smt2                                                                               |106.0MiB|106.0MiB|0B| 0.0%|
|auk-0017.smt2                                                                               |118.0MiB|118.0MiB|0B| 0.0%|
|auk-0018.smt2                                                                               |110.0MiB|110.0MiB|0B| 0.0%|
|auk-0019.smt2                                                                               |110.0MiB|110.0MiB|0B| 0.0%|
|auk-0020.smt2                                                                               |109.0MiB|109.0MiB|0B| 0.0%|
|auk-0021.smt2                                                                               |100.0MiB|100.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |96.996MiB|96.996MiB|0B| 0.0%|
|auk-0002.smt2                                                                               |130.0MiB|130.0MiB|0B| 0.0%|
|auk-0003.smt2                                                                               |116.0MiB|116.0MiB|0B| 0.0%|
|auk-0004.smt2                                                                               |148.0MiB|148.0MiB|0B| 0.0%|
|auk-0005.smt2                                                                               |182.0MiB|182.0MiB|0B| 0.0%|
|auk-0006.smt2                                                                               |142.0MiB|142.0MiB|0B| 0.0%|
|auk-0007.smt2                                                                               |862.0MiB|862.0MiB|0B| 0.0%|
|auk-0008.smt2                                                                               |116.0MiB|116.0MiB|0B| 0.0%|
|auk-0009.smt2                                                                               |93.988MiB|93.988MiB|0B| 0.0%|
|auk-0010.smt2                                                                               |137.0MiB|137.0MiB|0B| 0.0%|
|auk-0011.smt2                                                                               |210.0MiB|210.0MiB|0B| 0.0%|
|auk-0012.smt2                                                                               |94.748MiB|94.748MiB|0B| 0.0%|
|auk-0013.smt2                                                                               |116.0MiB|116.0MiB|0B| 0.0%|
|auk-0014.smt2                                                                               |116.0MiB|116.0MiB|0B| 0.0%|
|auk-0016.smt2                                                                               |106.0MiB|106.0MiB|0B| 0.0%|
|auk-0017.smt2                                                                               |118.0MiB|118.0MiB|0B| 0.0%|
|auk-0018.smt2                                                                               |110.0MiB|110.0MiB|0B| 0.0%|
|auk-0019.smt2                                                                               |110.0MiB|110.0MiB|0B| 0.0%|
|auk-0020.smt2                                                                               |109.0MiB|109.0MiB|0B| 0.0%|
|auk-0021.smt2                                                                               |100.0MiB|100.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|auk-0099.smt2                                                                              |  30.127s |932.0MiB|
|auk-0007.smt2                                                                              |  30.123s |862.0MiB|
|auk-0098.smt2                                                                              |  30.118s |845.0MiB|
|auk-0086.smt2                                                                              |  30.054s |361.0MiB|
|auk-0085.smt2                                                                              |  30.057s |348.0MiB|
|auk-0092.smt2                                                                              |  30.050s |345.0MiB|
|auk-0088.smt2                                                                              |  30.062s |337.0MiB|
|auk-0083.smt2                                                                              |   3.192s |318.0MiB|
|auk-0082.smt2                                                                              |   3.137s |318.0MiB|
|auk-0131.smt2                                                                              |   2.536s |315.0MiB|
|auk-0183.smt2                                                                              |   5.942s |257.0MiB|
|auk-0186.smt2                                                                              |   4.748s |251.0MiB|
|auk-0182.smt2                                                                              |   4.786s |248.0MiB|
|auk-0087.smt2                                                                              |   9.118s |247.0MiB|
|auk-0181.smt2                                                                              |   3.498s |241.0MiB|
|auk-0089.smt2                                                                              |   5.500s |240.0MiB|
|auk-0090.smt2                                                                              |  11.420s |231.0MiB|
|auk-0187.smt2                                                                              |  30.034s |220.0MiB|
|auk-0189.smt2                                                                              |  19.091s |214.0MiB|
|auk-0084.smt2                                                                              |   4.218s |214.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|auk-0099.smt2                                                                              |  30.127s |932.0MiB|
|auk-0007.smt2                                                                              |  30.123s |862.0MiB|
|auk-0098.smt2                                                                              |  30.118s |845.0MiB|
|auk-0086.smt2                                                                              |  30.054s |361.0MiB|
|auk-0085.smt2                                                                              |  30.057s |348.0MiB|
|auk-0092.smt2                                                                              |  30.050s |345.0MiB|
|auk-0088.smt2                                                                              |  30.062s |337.0MiB|
|auk-0083.smt2                                                                              |   3.192s |318.0MiB|
|auk-0082.smt2                                                                              |   3.137s |318.0MiB|
|auk-0131.smt2                                                                              |   2.536s |315.0MiB|
|auk-0183.smt2                                                                              |   5.942s |257.0MiB|
|auk-0186.smt2                                                                              |   4.748s |251.0MiB|
|auk-0182.smt2                                                                              |   4.786s |248.0MiB|
|auk-0087.smt2                                                                              |   9.118s |247.0MiB|
|auk-0181.smt2                                                                              |   3.498s |241.0MiB|
|auk-0089.smt2                                                                              |   5.500s |240.0MiB|
|auk-0090.smt2                                                                              |  11.420s |231.0MiB|
|auk-0187.smt2                                                                              |  30.034s |220.0MiB|
|auk-0189.smt2                                                                              |  19.091s |214.0MiB|
|auk-0084.smt2                                                                              |   4.218s |214.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   0.311s  |   0.311s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   0.931s  |   0.931s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   0.503s  |   0.503s  |   0.000s  | 0.0%|
|auk-0007.smt2                                                                               |  30.123s  |  30.123s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|auk-0009.smt2                                                                               |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |   0.351s  |   0.351s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|auk-0017.smt2                                                                               |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|auk-0018.smt2                                                                               |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|auk-0021.smt2                                                                               |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|auk-0022.smt2                                                                               |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|auk-0023.smt2                                                                               |   0.342s  |   0.342s  |   0.000s  | 0.0%|
|auk-0024.smt2                                                                               |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|auk-0025.smt2                                                                               |   0.553s  |   0.553s  |   0.000s  | 0.0%|
|auk-0026.smt2                                                                               |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|auk-0027.smt2                                                                               |   4.049s  |   4.049s  |   0.000s  | 0.0%|
|auk-0028.smt2                                                                               |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|auk-0029.smt2                                                                               |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|auk-0030.smt2                                                                               |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|auk-0031.smt2                                                                               |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|auk-0032.smt2                                                                               |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|auk-0033.smt2                                                                               |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|auk-0034.smt2                                                                               |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|auk-0035.smt2                                                                               |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|auk-0036.smt2                                                                               |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|auk-0037.smt2                                                                               |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|auk-0038.smt2                                                                               |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|auk-0039.smt2                                                                               |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|auk-0040.smt2                                                                               |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|auk-0041.smt2                                                                               |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|auk-0042.smt2                                                                               |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|auk-0043.smt2                                                                               |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|auk-0044.smt2                                                                               |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|auk-0045.smt2                                                                               |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|auk-0046.smt2                                                                               |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|auk-0047.smt2                                                                               |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|auk-0048.smt2                                                                               |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|auk-0049.smt2                                                                               |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|auk-0050.smt2                                                                               |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|auk-0051.smt2                                                                               |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|auk-0052.smt2                                                                               |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|auk-0053.smt2                                                                               |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|auk-0054.smt2                                                                               |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|auk-0055.smt2                                                                               |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|auk-0056.smt2                                                                               |   0.863s  |   0.863s  |   0.000s  | 0.0%|
|auk-0057.smt2                                                                               |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|auk-0058.smt2                                                                               |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|auk-0059.smt2                                                                               |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|auk-0060.smt2                                                                               |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|auk-0061.smt2                                                                               |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|auk-0062.smt2                                                                               |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|auk-0063.smt2                                                                               |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|auk-0064.smt2                                                                               |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|auk-0065.smt2                                                                               |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|auk-0066.smt2                                                                               |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|auk-0067.smt2                                                                               |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|auk-0068.smt2                                                                               |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|auk-0069.smt2                                                                               |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|auk-0070.smt2                                                                               |   0.365s  |   0.365s  |   0.000s  | 0.0%|
|auk-0071.smt2                                                                               |   1.332s  |   1.332s  |   0.000s  | 0.0%|
|auk-0072.smt2                                                                               |   0.583s  |   0.583s  |   0.000s  | 0.0%|
|auk-0073.smt2                                                                               |   1.320s  |   1.320s  |   0.000s  | 0.0%|
|auk-0074.smt2                                                                               |  30.031s  |  30.031s  |   0.000s  | 0.0%|
|auk-0075.smt2                                                                               |   1.350s  |   1.350s  |   0.000s  | 0.0%|
|auk-0076.smt2                                                                               |   1.348s  |   1.348s  |   0.000s  | 0.0%|
|auk-0077.smt2                                                                               |   1.195s  |   1.195s  |   0.000s  | 0.0%|
|auk-0078.smt2                                                                               |   0.661s  |   0.661s  |   0.000s  | 0.0%|
|auk-0079.smt2                                                                               |   4.659s  |   4.659s  |   0.000s  | 0.0%|
|auk-0080.smt2                                                                               |   0.557s  |   0.557s  |   0.000s  | 0.0%|
|auk-0081.smt2                                                                               |  28.294s  |  28.294s  |   0.000s  | 0.0%|
|auk-0082.smt2                                                                               |   3.137s  |   3.137s  |   0.000s  | 0.0%|
|auk-0083.smt2                                                                               |   3.192s  |   3.192s  |   0.000s  | 0.0%|
|auk-0084.smt2                                                                               |   4.218s  |   4.218s  |   0.000s  | 0.0%|
|auk-0085.smt2                                                                               |  30.057s  |  30.057s  |   0.000s  | 0.0%|
|auk-0086.smt2                                                                               |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|auk-0087.smt2                                                                               |   9.118s  |   9.118s  |   0.000s  | 0.0%|
|auk-0088.smt2                                                                               |  30.062s  |  30.062s  |   0.000s  | 0.0%|
|auk-0089.smt2                                                                               |   5.500s  |   5.500s  |   0.000s  | 0.0%|
|auk-0090.smt2                                                                               |  11.420s  |  11.420s  |   0.000s  | 0.0%|
|auk-0091.smt2                                                                               |   0.795s  |   0.795s  |   0.000s  | 0.0%|
|auk-0092.smt2                                                                               |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|auk-0093.smt2                                                                               |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|auk-0094.smt2                                                                               |   0.750s  |   0.750s  |   0.000s  | 0.0%|
|auk-0095.smt2                                                                               |   2.251s  |   2.251s  |   0.000s  | 0.0%|
|auk-0096.smt2                                                                               |   0.552s  |   0.552s  |   0.000s  | 0.0%|
|auk-0097.smt2                                                                               |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|auk-0098.smt2                                                                               |  30.118s  |  30.118s  |   0.000s  | 0.0%|
|auk-0099.smt2                                                                               |  30.127s  |  30.127s  |   0.000s  | 0.0%|
|auk-0100.smt2                                                                               |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|auk-0101.smt2                                                                               |   1.094s  |   1.094s  |   0.000s  | 0.0%|
|auk-0102.smt2                                                                               |   0.241s  |   0.241s  |   0.000s  | 0.0%|
|auk-0103.smt2                                                                               |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|auk-0104.smt2                                                                               |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|auk-0105.smt2                                                                               |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|auk-0106.smt2                                                                               |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|auk-0107.smt2                                                                               |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|auk-0108.smt2                                                                               |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|auk-0109.smt2                                                                               |   0.704s  |   0.704s  |   0.000s  | 0.0%|
|auk-0110.smt2                                                                               |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|auk-0111.smt2                                                                               |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|auk-0112.smt2                                                                               |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|auk-0113.smt2                                                                               |   0.314s  |   0.314s  |   0.000s  | 0.0%|
|auk-0114.smt2                                                                               |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|auk-0115.smt2                                                                               |   0.520s  |   0.520s  |   0.000s  | 0.0%|
|auk-0116.smt2                                                                               |   0.349s  |   0.349s  |   0.000s  | 0.0%|
|auk-0117.smt2                                                                               |   0.301s  |   0.301s  |   0.000s  | 0.0%|
|auk-0118.smt2                                                                               |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|auk-0119.smt2                                                                               |   0.424s  |   0.424s  |   0.000s  | 0.0%|
|auk-0120.smt2                                                                               |   0.341s  |   0.341s  |   0.000s  | 0.0%|
|auk-0121.smt2                                                                               |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|auk-0122.smt2                                                                               |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|auk-0123.smt2                                                                               |   0.356s  |   0.356s  |   0.000s  | 0.0%|
|auk-0124.smt2                                                                               |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|auk-0125.smt2                                                                               |   0.246s  |   0.246s  |   0.000s  | 0.0%|
|auk-0126.smt2                                                                               |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|auk-0127.smt2                                                                               |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|auk-0128.smt2                                                                               |   0.366s  |   0.366s  |   0.000s  | 0.0%|
|auk-0129.smt2                                                                               |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|auk-0130.smt2                                                                               |   0.381s  |   0.381s  |   0.000s  | 0.0%|
|auk-0131.smt2                                                                               |   2.536s  |   2.536s  |   0.000s  | 0.0%|
|auk-0132.smt2                                                                               |   1.265s  |   1.265s  |   0.000s  | 0.0%|
|auk-0133.smt2                                                                               |   1.026s  |   1.026s  |   0.000s  | 0.0%|
|auk-0134.smt2                                                                               |   0.343s  |   0.343s  |   0.000s  | 0.0%|
|auk-0135.smt2                                                                               |   0.353s  |   0.353s  |   0.000s  | 0.0%|
|auk-0136.smt2                                                                               |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|auk-0137.smt2                                                                               |  15.124s  |  15.124s  |   0.000s  | 0.0%|
|auk-0138.smt2                                                                               |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|auk-0139.smt2                                                                               |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|auk-0140.smt2                                                                               |  12.758s  |  12.758s  |   0.000s  | 0.0%|
|auk-0141.smt2                                                                               |  24.617s  |  24.617s  |   0.000s  | 0.0%|
|auk-0142.smt2                                                                               |   4.262s  |   4.262s  |   0.000s  | 0.0%|
|auk-0143.smt2                                                                               |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|auk-0144.smt2                                                                               |   1.395s  |   1.395s  |   0.000s  | 0.0%|
|auk-0145.smt2                                                                               |   0.871s  |   0.871s  |   0.000s  | 0.0%|
|auk-0146.smt2                                                                               |   1.374s  |   1.374s  |   0.000s  | 0.0%|
|auk-0147.smt2                                                                               |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|auk-0148.smt2                                                                               |   2.608s  |   2.608s  |   0.000s  | 0.0%|
|auk-0149.smt2                                                                               |   1.861s  |   1.861s  |   0.000s  | 0.0%|
|auk-0150.smt2                                                                               |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|auk-0151.smt2                                                                               |   0.338s  |   0.338s  |   0.000s  | 0.0%|
|auk-0152.smt2                                                                               |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|auk-0153.smt2                                                                               |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|auk-0154.smt2                                                                               |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|auk-0155.smt2                                                                               |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|auk-0156.smt2                                                                               |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|auk-0157.smt2                                                                               |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|auk-0158.smt2                                                                               |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|auk-0159.smt2                                                                               |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|auk-0160.smt2                                                                               |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|auk-0161.smt2                                                                               |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|auk-0162.smt2                                                                               |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|auk-0163.smt2                                                                               |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|auk-0164.smt2                                                                               |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|auk-0165.smt2                                                                               |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|auk-0166.smt2                                                                               |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|auk-0167.smt2                                                                               |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|auk-0168.smt2                                                                               |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|auk-0169.smt2                                                                               |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|auk-0170.smt2                                                                               |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|auk-0171.smt2                                                                               |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|auk-0172.smt2                                                                               |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|auk-0173.smt2                                                                               |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|auk-0174.smt2                                                                               |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|auk-0175.smt2                                                                               |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|auk-0176.smt2                                                                               |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|auk-0177.smt2                                                                               |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|auk-0178.smt2                                                                               |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|auk-0179.smt2                                                                               |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|auk-0180.smt2                                                                               |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|auk-0181.smt2                                                                               |   3.498s  |   3.498s  |   0.000s  | 0.0%|
|auk-0182.smt2                                                                               |   4.786s  |   4.786s  |   0.000s  | 0.0%|
|auk-0183.smt2                                                                               |   5.942s  |   5.942s  |   0.000s  | 0.0%|
|auk-0184.smt2                                                                               |   1.227s  |   1.227s  |   0.000s  | 0.0%|
|auk-0185.smt2                                                                               |  17.988s  |  17.988s  |   0.000s  | 0.0%|
|auk-0186.smt2                                                                               |   4.748s  |   4.748s  |   0.000s  | 0.0%|
|auk-0187.smt2                                                                               |  30.034s  |  30.034s  |   0.000s  | 0.0%|
|auk-0188.smt2                                                                               |  30.046s  |  30.046s  |   0.000s  | 0.0%|
</details>
