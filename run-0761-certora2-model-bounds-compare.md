Comparing data and data


# SUMMARY
- LHS tests = 189
- RHS tests = 189
- LHS success = 167  (88.35978835978835%)
- RHS success = 167  (88.35978835978835%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: certora2-model-bounds
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: ee63585581cf7bd23fdb34821d6b055bdb582b20
Z3 branch: arie
Z3 options: "-T:30 smt.arith.nl.nra.model_bounds=true"
Z3 inputs: inputs/certora2
Z3 commit message: update model-guide heuristic

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: certora2-model-bounds
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: ee63585581cf7bd23fdb34821d6b055bdb582b20
Z3 branch: arie
Z3 options: "-T:30 smt.arith.nl.nra.model_bounds=true"
Z3 inputs: inputs/certora2
Z3 commit message: update model-guide heuristic

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |  30.140s  |  30.140s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   1.017s  |   1.017s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |   0.963s  |   0.963s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   2.594s  |   2.594s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |  30.128s  |  30.128s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   1.458s  |   1.458s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |   0.451s  |   0.451s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |   1.322s  |   1.322s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               |  30.063s  |  30.063s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |   1.139s  |   1.139s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |   1.156s  |   1.156s  |   0.000s  | 0.0%|
|auk-0015.smt2                                                                               |  30.171s  |  30.171s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.786s  |   0.786s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.511s  |   0.511s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   1.108s  |   1.108s  |   0.000s  | 0.0%|
|auk-0021.smt2                                                                               |   1.045s  |   1.045s  |   0.000s  | 0.0%|
|auk-0023.smt2                                                                               |   1.659s  |   1.659s  |   0.000s  | 0.0%|
|auk-0024.smt2                                                                               |   0.522s  |   0.522s  |   0.000s  | 0.0%|
|auk-0025.smt2                                                                               |   4.571s  |   4.571s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |  30.140s  |  30.140s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   1.017s  |   1.017s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |   0.963s  |   0.963s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   2.594s  |   2.594s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |  30.128s  |  30.128s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   1.458s  |   1.458s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |   0.451s  |   0.451s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |   1.322s  |   1.322s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               |  30.063s  |  30.063s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |   1.139s  |   1.139s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |   1.156s  |   1.156s  |   0.000s  | 0.0%|
|auk-0015.smt2                                                                               |  30.171s  |  30.171s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.786s  |   0.786s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.511s  |   0.511s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   1.108s  |   1.108s  |   0.000s  | 0.0%|
|auk-0021.smt2                                                                               |   1.045s  |   1.045s  |   0.000s  | 0.0%|
|auk-0023.smt2                                                                               |   1.659s  |   1.659s  |   0.000s  | 0.0%|
|auk-0024.smt2                                                                               |   0.522s  |   0.522s  |   0.000s  | 0.0%|
|auk-0025.smt2                                                                               |   4.571s  |   4.571s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |  30.140s  |  30.140s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   1.017s  |   1.017s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |   0.963s  |   0.963s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   2.594s  |   2.594s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |  30.128s  |  30.128s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   1.458s  |   1.458s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |   0.451s  |   0.451s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |   1.322s  |   1.322s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               |  30.063s  |  30.063s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |   1.139s  |   1.139s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |   1.156s  |   1.156s  |   0.000s  | 0.0%|
|auk-0015.smt2                                                                               |  30.171s  |  30.171s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.786s  |   0.786s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.511s  |   0.511s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   1.108s  |   1.108s  |   0.000s  | 0.0%|
|auk-0021.smt2                                                                               |   1.045s  |   1.045s  |   0.000s  | 0.0%|
|auk-0023.smt2                                                                               |   1.659s  |   1.659s  |   0.000s  | 0.0%|
|auk-0024.smt2                                                                               |   0.522s  |   0.522s  |   0.000s  | 0.0%|
|auk-0025.smt2                                                                               |   4.571s  |   4.571s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |  30.140s  |  30.140s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   1.017s  |   1.017s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |   0.963s  |   0.963s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   2.594s  |   2.594s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |  30.128s  |  30.128s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   1.458s  |   1.458s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |   0.451s  |   0.451s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |   1.322s  |   1.322s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               |  30.063s  |  30.063s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |   1.139s  |   1.139s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |   1.156s  |   1.156s  |   0.000s  | 0.0%|
|auk-0015.smt2                                                                               |  30.171s  |  30.171s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.786s  |   0.786s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.511s  |   0.511s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   1.108s  |   1.108s  |   0.000s  | 0.0%|
|auk-0021.smt2                                                                               |   1.045s  |   1.045s  |   0.000s  | 0.0%|
|auk-0023.smt2                                                                               |   1.659s  |   1.659s  |   0.000s  | 0.0%|
|auk-0024.smt2                                                                               |   0.522s  |   0.522s  |   0.000s  | 0.0%|
|auk-0025.smt2                                                                               |   4.571s  |   4.571s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|auk-0081.smt2                                                                              |  30.451s |34.556MiB|
|auk-0098.smt2                                                                              |  30.443s |115.0MiB|
|auk-0090.smt2                                                                              |  30.386s |54.408MiB|
|auk-0186.smt2                                                                              |  30.377s |55.776MiB|
|auk-0084.smt2                                                                              |  30.267s |54.784MiB|
|auk-0092.smt2                                                                              |  30.253s |54.84MiB|
|auk-0074.smt2                                                                              |  30.249s |32.236MiB|
|auk-0183.smt2                                                                              |  30.247s |55.684MiB|
|auk-0185.smt2                                                                              |  30.238s |49.012MiB|
|auk-0083.smt2                                                                              |  30.235s |74.796MiB|
|auk-0184.smt2                                                                              |  30.203s |38.512MiB|
|auk-0140.smt2                                                                              |  30.199s |35.22MiB|
|auk-0134.smt2                                                                              |  30.194s |33.568MiB|
|auk-0189.smt2                                                                              |  30.187s |49.036MiB|
|auk-0086.smt2                                                                              |  30.185s |55.128MiB|
|auk-0088.smt2                                                                              |  30.184s |59.696MiB|
|auk-0085.smt2                                                                              |  30.173s |76.156MiB|
|auk-0082.smt2                                                                              |  30.173s |77.988MiB|
|auk-0015.smt2                                                                              |  30.171s |38.36MiB|
|auk-0099.smt2                                                                              |  30.164s |118.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|auk-0081.smt2                                                                              |  30.451s |34.556MiB|
|auk-0098.smt2                                                                              |  30.443s |115.0MiB|
|auk-0090.smt2                                                                              |  30.386s |54.408MiB|
|auk-0186.smt2                                                                              |  30.377s |55.776MiB|
|auk-0084.smt2                                                                              |  30.267s |54.784MiB|
|auk-0092.smt2                                                                              |  30.253s |54.84MiB|
|auk-0074.smt2                                                                              |  30.249s |32.236MiB|
|auk-0183.smt2                                                                              |  30.247s |55.684MiB|
|auk-0185.smt2                                                                              |  30.238s |49.012MiB|
|auk-0083.smt2                                                                              |  30.235s |74.796MiB|
|auk-0184.smt2                                                                              |  30.203s |38.512MiB|
|auk-0140.smt2                                                                              |  30.199s |35.22MiB|
|auk-0134.smt2                                                                              |  30.194s |33.568MiB|
|auk-0189.smt2                                                                              |  30.187s |49.036MiB|
|auk-0086.smt2                                                                              |  30.185s |55.128MiB|
|auk-0088.smt2                                                                              |  30.184s |59.696MiB|
|auk-0085.smt2                                                                              |  30.173s |76.156MiB|
|auk-0082.smt2                                                                              |  30.173s |77.988MiB|
|auk-0015.smt2                                                                              |  30.171s |38.36MiB|
|auk-0099.smt2                                                                              |  30.164s |118.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |22.7MiB|22.7MiB|0B| 0.0%|
|auk-0002.smt2                                                                               |33.952MiB|33.952MiB|0B| 0.0%|
|auk-0003.smt2                                                                               |27.944MiB|27.944MiB|0B| 0.0%|
|auk-0004.smt2                                                                               |36.404MiB|36.404MiB|0B| 0.0%|
|auk-0005.smt2                                                                               |38.804MiB|38.804MiB|0B| 0.0%|
|auk-0006.smt2                                                                               |34.332MiB|34.332MiB|0B| 0.0%|
|auk-0008.smt2                                                                               |27.932MiB|27.932MiB|0B| 0.0%|
|auk-0010.smt2                                                                               |33.928MiB|33.928MiB|0B| 0.0%|
|auk-0011.smt2                                                                               |40.58MiB|40.58MiB|0B| 0.0%|
|auk-0012.smt2                                                                               |20.44MiB|20.44MiB|0B| 0.0%|
|auk-0013.smt2                                                                               |27.988MiB|27.988MiB|0B| 0.0%|
|auk-0014.smt2                                                                               |27.944MiB|27.944MiB|0B| 0.0%|
|auk-0015.smt2                                                                               |38.36MiB|38.36MiB|0B| 0.0%|
|auk-0016.smt2                                                                               |25.144MiB|25.144MiB|0B| 0.0%|
|auk-0019.smt2                                                                               |27.152MiB|27.152MiB|0B| 0.0%|
|auk-0020.smt2                                                                               |25.4MiB|25.4MiB|0B| 0.0%|
|auk-0021.smt2                                                                               |23.46MiB|23.46MiB|0B| 0.0%|
|auk-0023.smt2                                                                               |28.904MiB|28.904MiB|0B| 0.0%|
|auk-0024.smt2                                                                               |25.548MiB|25.548MiB|0B| 0.0%|
|auk-0025.smt2                                                                               |31.908MiB|31.908MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |22.7MiB|22.7MiB|0B| 0.0%|
|auk-0002.smt2                                                                               |33.952MiB|33.952MiB|0B| 0.0%|
|auk-0003.smt2                                                                               |27.944MiB|27.944MiB|0B| 0.0%|
|auk-0004.smt2                                                                               |36.404MiB|36.404MiB|0B| 0.0%|
|auk-0005.smt2                                                                               |38.804MiB|38.804MiB|0B| 0.0%|
|auk-0006.smt2                                                                               |34.332MiB|34.332MiB|0B| 0.0%|
|auk-0008.smt2                                                                               |27.932MiB|27.932MiB|0B| 0.0%|
|auk-0010.smt2                                                                               |33.928MiB|33.928MiB|0B| 0.0%|
|auk-0011.smt2                                                                               |40.58MiB|40.58MiB|0B| 0.0%|
|auk-0012.smt2                                                                               |20.44MiB|20.44MiB|0B| 0.0%|
|auk-0013.smt2                                                                               |27.988MiB|27.988MiB|0B| 0.0%|
|auk-0014.smt2                                                                               |27.944MiB|27.944MiB|0B| 0.0%|
|auk-0015.smt2                                                                               |38.36MiB|38.36MiB|0B| 0.0%|
|auk-0016.smt2                                                                               |25.144MiB|25.144MiB|0B| 0.0%|
|auk-0019.smt2                                                                               |27.152MiB|27.152MiB|0B| 0.0%|
|auk-0020.smt2                                                                               |25.4MiB|25.4MiB|0B| 0.0%|
|auk-0021.smt2                                                                               |23.46MiB|23.46MiB|0B| 0.0%|
|auk-0023.smt2                                                                               |28.904MiB|28.904MiB|0B| 0.0%|
|auk-0024.smt2                                                                               |25.548MiB|25.548MiB|0B| 0.0%|
|auk-0025.smt2                                                                               |31.908MiB|31.908MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |22.7MiB|22.7MiB|0B| 0.0%|
|auk-0002.smt2                                                                               |33.952MiB|33.952MiB|0B| 0.0%|
|auk-0003.smt2                                                                               |27.944MiB|27.944MiB|0B| 0.0%|
|auk-0004.smt2                                                                               |36.404MiB|36.404MiB|0B| 0.0%|
|auk-0005.smt2                                                                               |38.804MiB|38.804MiB|0B| 0.0%|
|auk-0006.smt2                                                                               |34.332MiB|34.332MiB|0B| 0.0%|
|auk-0008.smt2                                                                               |27.932MiB|27.932MiB|0B| 0.0%|
|auk-0010.smt2                                                                               |33.928MiB|33.928MiB|0B| 0.0%|
|auk-0011.smt2                                                                               |40.58MiB|40.58MiB|0B| 0.0%|
|auk-0012.smt2                                                                               |20.44MiB|20.44MiB|0B| 0.0%|
|auk-0013.smt2                                                                               |27.988MiB|27.988MiB|0B| 0.0%|
|auk-0014.smt2                                                                               |27.944MiB|27.944MiB|0B| 0.0%|
|auk-0015.smt2                                                                               |38.36MiB|38.36MiB|0B| 0.0%|
|auk-0016.smt2                                                                               |25.144MiB|25.144MiB|0B| 0.0%|
|auk-0019.smt2                                                                               |27.152MiB|27.152MiB|0B| 0.0%|
|auk-0020.smt2                                                                               |25.4MiB|25.4MiB|0B| 0.0%|
|auk-0021.smt2                                                                               |23.46MiB|23.46MiB|0B| 0.0%|
|auk-0023.smt2                                                                               |28.904MiB|28.904MiB|0B| 0.0%|
|auk-0024.smt2                                                                               |25.548MiB|25.548MiB|0B| 0.0%|
|auk-0025.smt2                                                                               |31.908MiB|31.908MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |22.7MiB|22.7MiB|0B| 0.0%|
|auk-0002.smt2                                                                               |33.952MiB|33.952MiB|0B| 0.0%|
|auk-0003.smt2                                                                               |27.944MiB|27.944MiB|0B| 0.0%|
|auk-0004.smt2                                                                               |36.404MiB|36.404MiB|0B| 0.0%|
|auk-0005.smt2                                                                               |38.804MiB|38.804MiB|0B| 0.0%|
|auk-0006.smt2                                                                               |34.332MiB|34.332MiB|0B| 0.0%|
|auk-0008.smt2                                                                               |27.932MiB|27.932MiB|0B| 0.0%|
|auk-0010.smt2                                                                               |33.928MiB|33.928MiB|0B| 0.0%|
|auk-0011.smt2                                                                               |40.58MiB|40.58MiB|0B| 0.0%|
|auk-0012.smt2                                                                               |20.44MiB|20.44MiB|0B| 0.0%|
|auk-0013.smt2                                                                               |27.988MiB|27.988MiB|0B| 0.0%|
|auk-0014.smt2                                                                               |27.944MiB|27.944MiB|0B| 0.0%|
|auk-0015.smt2                                                                               |38.36MiB|38.36MiB|0B| 0.0%|
|auk-0016.smt2                                                                               |25.144MiB|25.144MiB|0B| 0.0%|
|auk-0019.smt2                                                                               |27.152MiB|27.152MiB|0B| 0.0%|
|auk-0020.smt2                                                                               |25.4MiB|25.4MiB|0B| 0.0%|
|auk-0021.smt2                                                                               |23.46MiB|23.46MiB|0B| 0.0%|
|auk-0023.smt2                                                                               |28.904MiB|28.904MiB|0B| 0.0%|
|auk-0024.smt2                                                                               |25.548MiB|25.548MiB|0B| 0.0%|
|auk-0025.smt2                                                                               |31.908MiB|31.908MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|auk-0099.smt2                                                                              |  30.164s |118.0MiB|
|auk-0098.smt2                                                                              |  30.443s |115.0MiB|
|auk-0131.smt2                                                                              |   7.719s |90.156MiB|
|auk-0082.smt2                                                                              |  30.173s |77.988MiB|
|auk-0085.smt2                                                                              |  30.173s |76.156MiB|
|auk-0083.smt2                                                                              |  30.235s |74.796MiB|
|auk-0182.smt2                                                                              |  30.138s |68.54MiB|
|auk-0181.smt2                                                                              |  30.078s |65.18MiB|
|auk-0087.smt2                                                                              |  30.132s |61.972MiB|
|auk-0089.smt2                                                                              |  30.101s |60.428MiB|
|auk-0088.smt2                                                                              |  30.184s |59.696MiB|
|auk-0132.smt2                                                                              |   4.281s |56.224MiB|
|auk-0186.smt2                                                                              |  30.377s |55.776MiB|
|auk-0183.smt2                                                                              |  30.247s |55.684MiB|
|auk-0086.smt2                                                                              |  30.185s |55.128MiB|
|auk-0092.smt2                                                                              |  30.253s |54.84MiB|
|auk-0084.smt2                                                                              |  30.267s |54.784MiB|
|auk-0090.smt2                                                                              |  30.386s |54.408MiB|
|auk-0188.smt2                                                                              |  30.135s |51.076MiB|
|auk-0189.smt2                                                                              |  30.187s |49.036MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|auk-0099.smt2                                                                              |  30.164s |118.0MiB|
|auk-0098.smt2                                                                              |  30.443s |115.0MiB|
|auk-0131.smt2                                                                              |   7.719s |90.156MiB|
|auk-0082.smt2                                                                              |  30.173s |77.988MiB|
|auk-0085.smt2                                                                              |  30.173s |76.156MiB|
|auk-0083.smt2                                                                              |  30.235s |74.796MiB|
|auk-0182.smt2                                                                              |  30.138s |68.54MiB|
|auk-0181.smt2                                                                              |  30.078s |65.18MiB|
|auk-0087.smt2                                                                              |  30.132s |61.972MiB|
|auk-0089.smt2                                                                              |  30.101s |60.428MiB|
|auk-0088.smt2                                                                              |  30.184s |59.696MiB|
|auk-0132.smt2                                                                              |   4.281s |56.224MiB|
|auk-0186.smt2                                                                              |  30.377s |55.776MiB|
|auk-0183.smt2                                                                              |  30.247s |55.684MiB|
|auk-0086.smt2                                                                              |  30.185s |55.128MiB|
|auk-0092.smt2                                                                              |  30.253s |54.84MiB|
|auk-0084.smt2                                                                              |  30.267s |54.784MiB|
|auk-0090.smt2                                                                              |  30.386s |54.408MiB|
|auk-0188.smt2                                                                              |  30.135s |51.076MiB|
|auk-0189.smt2                                                                              |  30.187s |49.036MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|auk-0001.smt2                                                                               |  30.140s  |  30.140s  |   0.000s  | 0.0%|
|auk-0002.smt2                                                                               |   1.017s  |   1.017s  |   0.000s  | 0.0%|
|auk-0003.smt2                                                                               |   0.963s  |   0.963s  |   0.000s  | 0.0%|
|auk-0004.smt2                                                                               |   2.594s  |   2.594s  |   0.000s  | 0.0%|
|auk-0005.smt2                                                                               |  30.128s  |  30.128s  |   0.000s  | 0.0%|
|auk-0006.smt2                                                                               |   1.458s  |   1.458s  |   0.000s  | 0.0%|
|auk-0008.smt2                                                                               |   0.451s  |   0.451s  |   0.000s  | 0.0%|
|auk-0010.smt2                                                                               |   1.322s  |   1.322s  |   0.000s  | 0.0%|
|auk-0011.smt2                                                                               |  30.063s  |  30.063s  |   0.000s  | 0.0%|
|auk-0012.smt2                                                                               |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|auk-0013.smt2                                                                               |   1.139s  |   1.139s  |   0.000s  | 0.0%|
|auk-0014.smt2                                                                               |   1.156s  |   1.156s  |   0.000s  | 0.0%|
|auk-0015.smt2                                                                               |  30.171s  |  30.171s  |   0.000s  | 0.0%|
|auk-0016.smt2                                                                               |   0.786s  |   0.786s  |   0.000s  | 0.0%|
|auk-0019.smt2                                                                               |   0.511s  |   0.511s  |   0.000s  | 0.0%|
|auk-0020.smt2                                                                               |   1.108s  |   1.108s  |   0.000s  | 0.0%|
|auk-0021.smt2                                                                               |   1.045s  |   1.045s  |   0.000s  | 0.0%|
|auk-0023.smt2                                                                               |   1.659s  |   1.659s  |   0.000s  | 0.0%|
|auk-0024.smt2                                                                               |   0.522s  |   0.522s  |   0.000s  | 0.0%|
|auk-0025.smt2                                                                               |   4.571s  |   4.571s  |   0.000s  | 0.0%|
|auk-0026.smt2                                                                               |   0.510s  |   0.510s  |   0.000s  | 0.0%|
|auk-0028.smt2                                                                               |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|auk-0029.smt2                                                                               |   0.753s  |   0.753s  |   0.000s  | 0.0%|
|auk-0030.smt2                                                                               |   0.836s  |   0.836s  |   0.000s  | 0.0%|
|auk-0031.smt2                                                                               |   0.344s  |   0.344s  |   0.000s  | 0.0%|
|auk-0032.smt2                                                                               |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|auk-0033.smt2                                                                               |   0.613s  |   0.613s  |   0.000s  | 0.0%|
|auk-0034.smt2                                                                               |   0.903s  |   0.903s  |   0.000s  | 0.0%|
|auk-0035.smt2                                                                               |   0.492s  |   0.492s  |   0.000s  | 0.0%|
|auk-0037.smt2                                                                               |   1.336s  |   1.336s  |   0.000s  | 0.0%|
|auk-0038.smt2                                                                               |   0.300s  |   0.300s  |   0.000s  | 0.0%|
|auk-0039.smt2                                                                               |   0.366s  |   0.366s  |   0.000s  | 0.0%|
|auk-0040.smt2                                                                               |   0.334s  |   0.334s  |   0.000s  | 0.0%|
|auk-0041.smt2                                                                               |   0.495s  |   0.495s  |   0.000s  | 0.0%|
|auk-0043.smt2                                                                               |   0.304s  |   0.304s  |   0.000s  | 0.0%|
|auk-0044.smt2                                                                               |   0.373s  |   0.373s  |   0.000s  | 0.0%|
|auk-0045.smt2                                                                               |   1.407s  |   1.407s  |   0.000s  | 0.0%|
|auk-0046.smt2                                                                               |   0.457s  |   0.457s  |   0.000s  | 0.0%|
|auk-0047.smt2                                                                               |   0.520s  |   0.520s  |   0.000s  | 0.0%|
|auk-0048.smt2                                                                               |   0.814s  |   0.814s  |   0.000s  | 0.0%|
|auk-0049.smt2                                                                               |   1.238s  |   1.238s  |   0.000s  | 0.0%|
|auk-0050.smt2                                                                               |   0.408s  |   0.408s  |   0.000s  | 0.0%|
|auk-0051.smt2                                                                               |   0.560s  |   0.560s  |   0.000s  | 0.0%|
|auk-0052.smt2                                                                               |   0.524s  |   0.524s  |   0.000s  | 0.0%|
|auk-0054.smt2                                                                               |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|auk-0055.smt2                                                                               |   0.595s  |   0.595s  |   0.000s  | 0.0%|
|auk-0057.smt2                                                                               |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|auk-0058.smt2                                                                               |   0.330s  |   0.330s  |   0.000s  | 0.0%|
|auk-0059.smt2                                                                               |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|auk-0060.smt2                                                                               |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|auk-0061.smt2                                                                               |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|auk-0062.smt2                                                                               |   0.404s  |   0.404s  |   0.000s  | 0.0%|
|auk-0063.smt2                                                                               |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|auk-0065.smt2                                                                               |   0.434s  |   0.434s  |   0.000s  | 0.0%|
|auk-0066.smt2                                                                               |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|auk-0068.smt2                                                                               |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|auk-0069.smt2                                                                               |   0.358s  |   0.358s  |   0.000s  | 0.0%|
|auk-0070.smt2                                                                               |  15.232s  |  15.232s  |   0.000s  | 0.0%|
|auk-0071.smt2                                                                               |   5.536s  |   5.536s  |   0.000s  | 0.0%|
|auk-0072.smt2                                                                               |   1.953s  |   1.953s  |   0.000s  | 0.0%|
|auk-0073.smt2                                                                               |   6.759s  |   6.759s  |   0.000s  | 0.0%|
|auk-0074.smt2                                                                               |  30.249s  |  30.249s  |   0.000s  | 0.0%|
|auk-0075.smt2                                                                               |   5.746s  |   5.746s  |   0.000s  | 0.0%|
|auk-0076.smt2                                                                               |   2.843s  |   2.843s  |   0.000s  | 0.0%|
|auk-0077.smt2                                                                               |  10.744s  |  10.744s  |   0.000s  | 0.0%|
|auk-0078.smt2                                                                               |   6.531s  |   6.531s  |   0.000s  | 0.0%|
|auk-0079.smt2                                                                               |  16.799s  |  16.799s  |   0.000s  | 0.0%|
|auk-0080.smt2                                                                               |   1.408s  |   1.408s  |   0.000s  | 0.0%|
|auk-0081.smt2                                                                               |  30.451s  |  30.451s  |   0.000s  | 0.0%|
|auk-0082.smt2                                                                               |  30.173s  |  30.173s  |   0.000s  | 0.0%|
|auk-0083.smt2                                                                               |  30.235s  |  30.235s  |   0.000s  | 0.0%|
|auk-0084.smt2                                                                               |  30.267s  |  30.267s  |   0.000s  | 0.0%|
|auk-0085.smt2                                                                               |  30.173s  |  30.173s  |   0.000s  | 0.0%|
|auk-0086.smt2                                                                               |  30.185s  |  30.185s  |   0.000s  | 0.0%|
|auk-0087.smt2                                                                               |  30.132s  |  30.132s  |   0.000s  | 0.0%|
|auk-0088.smt2                                                                               |  30.184s  |  30.184s  |   0.000s  | 0.0%|
|auk-0089.smt2                                                                               |  30.101s  |  30.101s  |   0.000s  | 0.0%|
|auk-0090.smt2                                                                               |  30.386s  |  30.386s  |   0.000s  | 0.0%|
|auk-0091.smt2                                                                               |   1.752s  |   1.752s  |   0.000s  | 0.0%|
|auk-0092.smt2                                                                               |  30.253s  |  30.253s  |   0.000s  | 0.0%|
|auk-0094.smt2                                                                               |   2.197s  |   2.197s  |   0.000s  | 0.0%|
|auk-0095.smt2                                                                               |  22.048s  |  22.048s  |   0.000s  | 0.0%|
|auk-0097.smt2                                                                               |   1.007s  |   1.007s  |   0.000s  | 0.0%|
|auk-0098.smt2                                                                               |  30.443s  |  30.443s  |   0.000s  | 0.0%|
|auk-0099.smt2                                                                               |  30.164s  |  30.164s  |   0.000s  | 0.0%|
|auk-0100.smt2                                                                               |   0.398s  |   0.398s  |   0.000s  | 0.0%|
|auk-0101.smt2                                                                               |   4.157s  |   4.157s  |   0.000s  | 0.0%|
|auk-0102.smt2                                                                               |   0.508s  |   0.508s  |   0.000s  | 0.0%|
|auk-0104.smt2                                                                               |   1.139s  |   1.139s  |   0.000s  | 0.0%|
|auk-0105.smt2                                                                               |   0.473s  |   0.473s  |   0.000s  | 0.0%|
|auk-0106.smt2                                                                               |   0.957s  |   0.957s  |   0.000s  | 0.0%|
|auk-0107.smt2                                                                               |   0.956s  |   0.956s  |   0.000s  | 0.0%|
|auk-0108.smt2                                                                               |   1.512s  |   1.512s  |   0.000s  | 0.0%|
|auk-0109.smt2                                                                               |   1.843s  |   1.843s  |   0.000s  | 0.0%|
|auk-0110.smt2                                                                               |   0.932s  |   0.932s  |   0.000s  | 0.0%|
|auk-0111.smt2                                                                               |   0.707s  |   0.707s  |   0.000s  | 0.0%|
|auk-0112.smt2                                                                               |   0.670s  |   0.670s  |   0.000s  | 0.0%|
|auk-0113.smt2                                                                               |   2.029s  |   2.029s  |   0.000s  | 0.0%|
|auk-0114.smt2                                                                               |   1.867s  |   1.867s  |   0.000s  | 0.0%|
|auk-0115.smt2                                                                               |   1.190s  |   1.190s  |   0.000s  | 0.0%|
|auk-0116.smt2                                                                               |   1.924s  |   1.924s  |   0.000s  | 0.0%|
|auk-0118.smt2                                                                               |   0.535s  |   0.535s  |   0.000s  | 0.0%|
|auk-0119.smt2                                                                               |   2.449s  |   2.449s  |   0.000s  | 0.0%|
|auk-0121.smt2                                                                               |   0.391s  |   0.391s  |   0.000s  | 0.0%|
|auk-0123.smt2                                                                               |   1.565s  |   1.565s  |   0.000s  | 0.0%|
|auk-0124.smt2                                                                               |   0.455s  |   0.455s  |   0.000s  | 0.0%|
|auk-0126.smt2                                                                               |   0.562s  |   0.562s  |   0.000s  | 0.0%|
|auk-0127.smt2                                                                               |   1.389s  |   1.389s  |   0.000s  | 0.0%|
|auk-0128.smt2                                                                               |   2.238s  |   2.238s  |   0.000s  | 0.0%|
|auk-0129.smt2                                                                               |   1.211s  |   1.211s  |   0.000s  | 0.0%|
|auk-0131.smt2                                                                               |   7.719s  |   7.719s  |   0.000s  | 0.0%|
|auk-0132.smt2                                                                               |   4.281s  |   4.281s  |   0.000s  | 0.0%|
|auk-0133.smt2                                                                               |   7.063s  |   7.063s  |   0.000s  | 0.0%|
|auk-0134.smt2                                                                               |  30.194s  |  30.194s  |   0.000s  | 0.0%|
|auk-0135.smt2                                                                               |   3.163s  |   3.163s  |   0.000s  | 0.0%|
|auk-0137.smt2                                                                               |  30.079s  |  30.079s  |   0.000s  | 0.0%|
|auk-0138.smt2                                                                               |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|auk-0139.smt2                                                                               |   1.405s  |   1.405s  |   0.000s  | 0.0%|
|auk-0140.smt2                                                                               |  30.199s  |  30.199s  |   0.000s  | 0.0%|
|auk-0141.smt2                                                                               |  30.142s  |  30.142s  |   0.000s  | 0.0%|
|auk-0142.smt2                                                                               |  27.121s  |  27.121s  |   0.000s  | 0.0%|
|auk-0143.smt2                                                                               |   0.787s  |   0.787s  |   0.000s  | 0.0%|
|auk-0144.smt2                                                                               |  21.484s  |  21.484s  |   0.000s  | 0.0%|
|auk-0145.smt2                                                                               |   2.525s  |   2.525s  |   0.000s  | 0.0%|
|auk-0146.smt2                                                                               |   2.364s  |   2.364s  |   0.000s  | 0.0%|
|auk-0147.smt2                                                                               |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|auk-0148.smt2                                                                               |  16.072s  |  16.072s  |   0.000s  | 0.0%|
|auk-0149.smt2                                                                               |   3.699s  |   3.699s  |   0.000s  | 0.0%|
|auk-0150.smt2                                                                               |   1.051s  |   1.051s  |   0.000s  | 0.0%|
|auk-0151.smt2                                                                               |   0.909s  |   0.909s  |   0.000s  | 0.0%|
|auk-0152.smt2                                                                               |   0.508s  |   0.508s  |   0.000s  | 0.0%|
|auk-0153.smt2                                                                               |   1.225s  |   1.225s  |   0.000s  | 0.0%|
|auk-0154.smt2                                                                               |   0.668s  |   0.668s  |   0.000s  | 0.0%|
|auk-0155.smt2                                                                               |   0.410s  |   0.410s  |   0.000s  | 0.0%|
|auk-0156.smt2                                                                               |   0.415s  |   0.415s  |   0.000s  | 0.0%|
|auk-0157.smt2                                                                               |   1.092s  |   1.092s  |   0.000s  | 0.0%|
|auk-0158.smt2                                                                               |   0.661s  |   0.661s  |   0.000s  | 0.0%|
|auk-0159.smt2                                                                               |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|auk-0160.smt2                                                                               |   0.556s  |   0.556s  |   0.000s  | 0.0%|
|auk-0161.smt2                                                                               |   0.334s  |   0.334s  |   0.000s  | 0.0%|
|auk-0162.smt2                                                                               |   0.615s  |   0.615s  |   0.000s  | 0.0%|
|auk-0163.smt2                                                                               |   0.453s  |   0.453s  |   0.000s  | 0.0%|
|auk-0164.smt2                                                                               |   1.939s  |   1.939s  |   0.000s  | 0.0%|
|auk-0165.smt2                                                                               |   0.834s  |   0.834s  |   0.000s  | 0.0%|
|auk-0166.smt2                                                                               |   0.448s  |   0.448s  |   0.000s  | 0.0%|
|auk-0167.smt2                                                                               |   0.835s  |   0.835s  |   0.000s  | 0.0%|
|auk-0169.smt2                                                                               |   0.389s  |   0.389s  |   0.000s  | 0.0%|
|auk-0170.smt2                                                                               |   0.367s  |   0.367s  |   0.000s  | 0.0%|
|auk-0171.smt2                                                                               |   0.846s  |   0.846s  |   0.000s  | 0.0%|
|auk-0172.smt2                                                                               |   0.329s  |   0.329s  |   0.000s  | 0.0%|
|auk-0173.smt2                                                                               |   0.357s  |   0.357s  |   0.000s  | 0.0%|
|auk-0174.smt2                                                                               |   0.393s  |   0.393s  |   0.000s  | 0.0%|
|auk-0175.smt2                                                                               |   0.809s  |   0.809s  |   0.000s  | 0.0%|
|auk-0176.smt2                                                                               |   0.916s  |   0.916s  |   0.000s  | 0.0%|
|auk-0177.smt2                                                                               |   0.804s  |   0.804s  |   0.000s  | 0.0%|
|auk-0178.smt2                                                                               |   0.515s  |   0.515s  |   0.000s  | 0.0%|
|auk-0179.smt2                                                                               |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|auk-0180.smt2                                                                               |   1.599s  |   1.599s  |   0.000s  | 0.0%|
|auk-0181.smt2                                                                               |  30.078s  |  30.078s  |   0.000s  | 0.0%|
|auk-0182.smt2                                                                               |  30.138s  |  30.138s  |   0.000s  | 0.0%|
|auk-0183.smt2                                                                               |  30.247s  |  30.247s  |   0.000s  | 0.0%|
|auk-0184.smt2                                                                               |  30.203s  |  30.203s  |   0.000s  | 0.0%|
|auk-0185.smt2                                                                               |  30.238s  |  30.238s  |   0.000s  | 0.0%|
|auk-0186.smt2                                                                               |  30.377s  |  30.377s  |   0.000s  | 0.0%|
|auk-0187.smt2                                                                               |  30.121s  |  30.121s  |   0.000s  | 0.0%|
|auk-0188.smt2                                                                               |  30.135s  |  30.135s  |   0.000s  | 0.0%|
</details>
