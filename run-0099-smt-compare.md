Comparing data and data


# SUMMARY
- LHS tests = 2500
- RHS tests = 2500
- LHS success = 2500  (100.0%)
- RHS success = 2500  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: fa6f3f2dba89c2c44282f10c468e7482972a9bdd
Z3 branch: sls
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" model_validate=true"
Z3 inputs: inputs/QF_S_SAT
Z3 commit message: fixing prop-queue

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: fa6f3f2dba89c2c44282f10c468e7482972a9bdd
Z3 branch: sls
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" model_validate=true"
Z3 inputs: inputs/QF_S_SAT
Z3 commit message: fixing prop-queue

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01_track_100.smt2                                                                           |   0.788s  |   0.788s  |   0.000s  | 0.0%|
|01_track_106.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|01_track_117.smt2                                                                           |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|01_track_124.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|01_track_127.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|01_track_131.smt2                                                                           |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|01_track_135.smt2                                                                           |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|01_track_142.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|01_track_154.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|01_track_157.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_164.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_172.smt2                                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|01_track_176.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|01_track_178.smt2                                                                           |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|01_track_180.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_185.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_186.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|01_track_187.smt2                                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|01_track_21.smt2                                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_23.smt2                                                                            |   0.009s  |   0.009s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01_track_100.smt2                                                                           |   0.788s  |   0.788s  |   0.000s  | 0.0%|
|01_track_106.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|01_track_117.smt2                                                                           |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|01_track_124.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|01_track_127.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|01_track_131.smt2                                                                           |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|01_track_135.smt2                                                                           |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|01_track_142.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|01_track_154.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|01_track_157.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_164.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_172.smt2                                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|01_track_176.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|01_track_178.smt2                                                                           |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|01_track_180.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_185.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_186.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|01_track_187.smt2                                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|01_track_21.smt2                                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_23.smt2                                                                            |   0.009s  |   0.009s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01_track_100.smt2                                                                           |   0.788s  |   0.788s  |   0.000s  | 0.0%|
|01_track_106.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|01_track_117.smt2                                                                           |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|01_track_124.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|01_track_127.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|01_track_131.smt2                                                                           |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|01_track_135.smt2                                                                           |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|01_track_142.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|01_track_154.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|01_track_157.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_164.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_172.smt2                                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|01_track_176.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|01_track_178.smt2                                                                           |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|01_track_180.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_185.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_186.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|01_track_187.smt2                                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|01_track_21.smt2                                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_23.smt2                                                                            |   0.009s  |   0.009s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01_track_100.smt2                                                                           |   0.788s  |   0.788s  |   0.000s  | 0.0%|
|01_track_106.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|01_track_117.smt2                                                                           |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|01_track_124.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|01_track_127.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|01_track_131.smt2                                                                           |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|01_track_135.smt2                                                                           |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|01_track_142.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|01_track_154.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|01_track_157.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_164.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_172.smt2                                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|01_track_176.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|01_track_178.smt2                                                                           |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|01_track_180.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_185.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_186.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|01_track_187.smt2                                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|01_track_21.smt2                                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_23.smt2                                                                            |   0.009s  |   0.009s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|instance06624.smt2                                                                         |  20.016s |636.0MiB|
|instance15510.smt2                                                                         |  20.012s |287.0MiB|
|instance08883.smt2                                                                         |  20.010s |597.0MiB|
|instance06545.smt2                                                                         |  20.006s |141.0MiB|
|instance13818.smt2                                                                         |  20.004s |117.0MiB|
|instance10051.smt2                                                                         |  20.001s |117.0MiB|
|instance09465.smt2                                                                         |  19.999s |77.04MiB|
|instance01742.smt2                                                                         |  19.998s |47.532MiB|
|instance10388.smt2                                                                         |  19.995s |118.0MiB|
|instance08943.smt2                                                                         |  19.141s |1013.0MiB|
|instance14636.smt2                                                                         |  18.879s |91.376MiB|
|instance07936.smt2                                                                         |  17.545s |96.336MiB|
|instance10785.smt2                                                                         |  12.976s |57.428MiB|
|instance08887.smt2                                                                         |  11.615s |57.196MiB|
|instance08102.smt2                                                                         |   9.475s |131.0MiB|
|instance00237.smt2                                                                         |   8.793s |83.464MiB|
|instance13811.smt2                                                                         |   8.611s |27.868MiB|
|instance14124.smt2                                                                         |   7.624s |46.824MiB|
|instance01203.smt2                                                                         |   7.588s |841.0MiB|
|instance05526.smt2                                                                         |   5.871s |77.5MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|instance06624.smt2                                                                         |  20.016s |636.0MiB|
|instance15510.smt2                                                                         |  20.012s |287.0MiB|
|instance08883.smt2                                                                         |  20.010s |597.0MiB|
|instance06545.smt2                                                                         |  20.006s |141.0MiB|
|instance13818.smt2                                                                         |  20.004s |117.0MiB|
|instance10051.smt2                                                                         |  20.001s |117.0MiB|
|instance09465.smt2                                                                         |  19.999s |77.04MiB|
|instance01742.smt2                                                                         |  19.998s |47.532MiB|
|instance10388.smt2                                                                         |  19.995s |118.0MiB|
|instance08943.smt2                                                                         |  19.141s |1013.0MiB|
|instance14636.smt2                                                                         |  18.879s |91.376MiB|
|instance07936.smt2                                                                         |  17.545s |96.336MiB|
|instance10785.smt2                                                                         |  12.976s |57.428MiB|
|instance08887.smt2                                                                         |  11.615s |57.196MiB|
|instance08102.smt2                                                                         |   9.475s |131.0MiB|
|instance00237.smt2                                                                         |   8.793s |83.464MiB|
|instance13811.smt2                                                                         |   8.611s |27.868MiB|
|instance14124.smt2                                                                         |   7.624s |46.824MiB|
|instance01203.smt2                                                                         |   7.588s |841.0MiB|
|instance05526.smt2                                                                         |   5.871s |77.5MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01_track_100.smt2                                                                           |26.572MiB|26.572MiB|0B| 0.0%|
|01_track_106.smt2                                                                           |19.424MiB|19.424MiB|0B| 0.0%|
|01_track_117.smt2                                                                           |20.168MiB|20.168MiB|0B| 0.0%|
|01_track_124.smt2                                                                           |18.508MiB|18.508MiB|0B| 0.0%|
|01_track_127.smt2                                                                           |18.508MiB|18.508MiB|0B| 0.0%|
|01_track_131.smt2                                                                           |24.62MiB|24.62MiB|0B| 0.0%|
|01_track_135.smt2                                                                           |23.244MiB|23.244MiB|0B| 0.0%|
|01_track_142.smt2                                                                           |18.252MiB|18.252MiB|0B| 0.0%|
|01_track_154.smt2                                                                           |19.02MiB|19.02MiB|0B| 0.0%|
|01_track_157.smt2                                                                           |18.408MiB|18.408MiB|0B| 0.0%|
|01_track_164.smt2                                                                           |18.236MiB|18.236MiB|0B| 0.0%|
|01_track_172.smt2                                                                           |19.276MiB|19.276MiB|0B| 0.0%|
|01_track_176.smt2                                                                           |18.252MiB|18.252MiB|0B| 0.0%|
|01_track_178.smt2                                                                           |22.088MiB|22.088MiB|0B| 0.0%|
|01_track_180.smt2                                                                           |18.308MiB|18.308MiB|0B| 0.0%|
|01_track_185.smt2                                                                           |18.252MiB|18.252MiB|0B| 0.0%|
|01_track_186.smt2                                                                           |19.456MiB|19.456MiB|0B| 0.0%|
|01_track_187.smt2                                                                           |19.276MiB|19.276MiB|0B| 0.0%|
|01_track_21.smt2                                                                            |18.388MiB|18.388MiB|0B| 0.0%|
|01_track_23.smt2                                                                            |19.02MiB|19.02MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01_track_100.smt2                                                                           |26.572MiB|26.572MiB|0B| 0.0%|
|01_track_106.smt2                                                                           |19.424MiB|19.424MiB|0B| 0.0%|
|01_track_117.smt2                                                                           |20.168MiB|20.168MiB|0B| 0.0%|
|01_track_124.smt2                                                                           |18.508MiB|18.508MiB|0B| 0.0%|
|01_track_127.smt2                                                                           |18.508MiB|18.508MiB|0B| 0.0%|
|01_track_131.smt2                                                                           |24.62MiB|24.62MiB|0B| 0.0%|
|01_track_135.smt2                                                                           |23.244MiB|23.244MiB|0B| 0.0%|
|01_track_142.smt2                                                                           |18.252MiB|18.252MiB|0B| 0.0%|
|01_track_154.smt2                                                                           |19.02MiB|19.02MiB|0B| 0.0%|
|01_track_157.smt2                                                                           |18.408MiB|18.408MiB|0B| 0.0%|
|01_track_164.smt2                                                                           |18.236MiB|18.236MiB|0B| 0.0%|
|01_track_172.smt2                                                                           |19.276MiB|19.276MiB|0B| 0.0%|
|01_track_176.smt2                                                                           |18.252MiB|18.252MiB|0B| 0.0%|
|01_track_178.smt2                                                                           |22.088MiB|22.088MiB|0B| 0.0%|
|01_track_180.smt2                                                                           |18.308MiB|18.308MiB|0B| 0.0%|
|01_track_185.smt2                                                                           |18.252MiB|18.252MiB|0B| 0.0%|
|01_track_186.smt2                                                                           |19.456MiB|19.456MiB|0B| 0.0%|
|01_track_187.smt2                                                                           |19.276MiB|19.276MiB|0B| 0.0%|
|01_track_21.smt2                                                                            |18.388MiB|18.388MiB|0B| 0.0%|
|01_track_23.smt2                                                                            |19.02MiB|19.02MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01_track_100.smt2                                                                           |26.572MiB|26.572MiB|0B| 0.0%|
|01_track_106.smt2                                                                           |19.424MiB|19.424MiB|0B| 0.0%|
|01_track_117.smt2                                                                           |20.168MiB|20.168MiB|0B| 0.0%|
|01_track_124.smt2                                                                           |18.508MiB|18.508MiB|0B| 0.0%|
|01_track_127.smt2                                                                           |18.508MiB|18.508MiB|0B| 0.0%|
|01_track_131.smt2                                                                           |24.62MiB|24.62MiB|0B| 0.0%|
|01_track_135.smt2                                                                           |23.244MiB|23.244MiB|0B| 0.0%|
|01_track_142.smt2                                                                           |18.252MiB|18.252MiB|0B| 0.0%|
|01_track_154.smt2                                                                           |19.02MiB|19.02MiB|0B| 0.0%|
|01_track_157.smt2                                                                           |18.408MiB|18.408MiB|0B| 0.0%|
|01_track_164.smt2                                                                           |18.236MiB|18.236MiB|0B| 0.0%|
|01_track_172.smt2                                                                           |19.276MiB|19.276MiB|0B| 0.0%|
|01_track_176.smt2                                                                           |18.252MiB|18.252MiB|0B| 0.0%|
|01_track_178.smt2                                                                           |22.088MiB|22.088MiB|0B| 0.0%|
|01_track_180.smt2                                                                           |18.308MiB|18.308MiB|0B| 0.0%|
|01_track_185.smt2                                                                           |18.252MiB|18.252MiB|0B| 0.0%|
|01_track_186.smt2                                                                           |19.456MiB|19.456MiB|0B| 0.0%|
|01_track_187.smt2                                                                           |19.276MiB|19.276MiB|0B| 0.0%|
|01_track_21.smt2                                                                            |18.388MiB|18.388MiB|0B| 0.0%|
|01_track_23.smt2                                                                            |19.02MiB|19.02MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01_track_100.smt2                                                                           |26.572MiB|26.572MiB|0B| 0.0%|
|01_track_106.smt2                                                                           |19.424MiB|19.424MiB|0B| 0.0%|
|01_track_117.smt2                                                                           |20.168MiB|20.168MiB|0B| 0.0%|
|01_track_124.smt2                                                                           |18.508MiB|18.508MiB|0B| 0.0%|
|01_track_127.smt2                                                                           |18.508MiB|18.508MiB|0B| 0.0%|
|01_track_131.smt2                                                                           |24.62MiB|24.62MiB|0B| 0.0%|
|01_track_135.smt2                                                                           |23.244MiB|23.244MiB|0B| 0.0%|
|01_track_142.smt2                                                                           |18.252MiB|18.252MiB|0B| 0.0%|
|01_track_154.smt2                                                                           |19.02MiB|19.02MiB|0B| 0.0%|
|01_track_157.smt2                                                                           |18.408MiB|18.408MiB|0B| 0.0%|
|01_track_164.smt2                                                                           |18.236MiB|18.236MiB|0B| 0.0%|
|01_track_172.smt2                                                                           |19.276MiB|19.276MiB|0B| 0.0%|
|01_track_176.smt2                                                                           |18.252MiB|18.252MiB|0B| 0.0%|
|01_track_178.smt2                                                                           |22.088MiB|22.088MiB|0B| 0.0%|
|01_track_180.smt2                                                                           |18.308MiB|18.308MiB|0B| 0.0%|
|01_track_185.smt2                                                                           |18.252MiB|18.252MiB|0B| 0.0%|
|01_track_186.smt2                                                                           |19.456MiB|19.456MiB|0B| 0.0%|
|01_track_187.smt2                                                                           |19.276MiB|19.276MiB|0B| 0.0%|
|01_track_21.smt2                                                                            |18.388MiB|18.388MiB|0B| 0.0%|
|01_track_23.smt2                                                                            |19.02MiB|19.02MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|instance08943.smt2                                                                         |  19.141s |1013.0MiB|
|instance01203.smt2                                                                         |   7.588s |841.0MiB|
|instance06624.smt2                                                                         |  20.016s |636.0MiB|
|instance08883.smt2                                                                         |  20.010s |597.0MiB|
|instance15510.smt2                                                                         |  20.012s |287.0MiB|
|instance02462.smt2                                                                         |   0.717s |155.0MiB|
|instance06545.smt2                                                                         |  20.006s |141.0MiB|
|instance08102.smt2                                                                         |   9.475s |131.0MiB|
|instance10388.smt2                                                                         |  19.995s |118.0MiB|
|instance13818.smt2                                                                         |  20.004s |117.0MiB|
|instance10051.smt2                                                                         |  20.001s |117.0MiB|
|instance07258.smt2                                                                         |   2.801s |110.0MiB|
|instance07936.smt2                                                                         |  17.545s |96.336MiB|
|instance14961.smt2                                                                         |   4.670s |92.6MiB|
|instance14636.smt2                                                                         |  18.879s |91.376MiB|
|instance04961.smt2                                                                         |   1.046s |86.468MiB|
|instance05549.smt2                                                                         |   1.441s |83.496MiB|
|instance00237.smt2                                                                         |   8.793s |83.464MiB|
|instance10567.smt2                                                                         |   1.596s |83.46MiB|
|instance08288.smt2                                                                         |   5.477s |82.764MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|instance08943.smt2                                                                         |  19.141s |1013.0MiB|
|instance01203.smt2                                                                         |   7.588s |841.0MiB|
|instance06624.smt2                                                                         |  20.016s |636.0MiB|
|instance08883.smt2                                                                         |  20.010s |597.0MiB|
|instance15510.smt2                                                                         |  20.012s |287.0MiB|
|instance02462.smt2                                                                         |   0.717s |155.0MiB|
|instance06545.smt2                                                                         |  20.006s |141.0MiB|
|instance08102.smt2                                                                         |   9.475s |131.0MiB|
|instance10388.smt2                                                                         |  19.995s |118.0MiB|
|instance13818.smt2                                                                         |  20.004s |117.0MiB|
|instance10051.smt2                                                                         |  20.001s |117.0MiB|
|instance07258.smt2                                                                         |   2.801s |110.0MiB|
|instance07936.smt2                                                                         |  17.545s |96.336MiB|
|instance14961.smt2                                                                         |   4.670s |92.6MiB|
|instance14636.smt2                                                                         |  18.879s |91.376MiB|
|instance04961.smt2                                                                         |   1.046s |86.468MiB|
|instance05549.smt2                                                                         |   1.441s |83.496MiB|
|instance00237.smt2                                                                         |   8.793s |83.464MiB|
|instance10567.smt2                                                                         |   1.596s |83.46MiB|
|instance08288.smt2                                                                         |   5.477s |82.764MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01_track_100.smt2                                                                           |   0.788s  |   0.788s  |   0.000s  | 0.0%|
|01_track_106.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|01_track_117.smt2                                                                           |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|01_track_124.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|01_track_127.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|01_track_131.smt2                                                                           |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|01_track_135.smt2                                                                           |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|01_track_142.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|01_track_154.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|01_track_157.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_164.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_172.smt2                                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|01_track_176.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|01_track_178.smt2                                                                           |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|01_track_180.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_185.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_186.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|01_track_187.smt2                                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|01_track_21.smt2                                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_23.smt2                                                                            |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|01_track_24.smt2                                                                            |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|01_track_28.smt2                                                                            |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|01_track_29.smt2                                                                            |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|01_track_36.smt2                                                                            |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|01_track_37.smt2                                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_47.smt2                                                                            |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|01_track_52.smt2                                                                            |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|01_track_56.smt2                                                                            |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|01_track_62.smt2                                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_7.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|01_track_72.smt2                                                                            |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|01_track_87.smt2                                                                            |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|01_track_89.smt2                                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_90.smt2                                                                            |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|01_track_91.smt2                                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance00001.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance00002.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance00004.smt2                                                                          |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|instance00010.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance00012.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance00020.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance00023.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance00026.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance00028.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance00032.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance00035.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance00036.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance00037.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance00042.smt2                                                                          |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|instance00049.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00050.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00054.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance00063.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00075.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00076.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance00084.smt2                                                                          |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|instance00086.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance00089.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00092.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance00097.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00098.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance00100.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance00107.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00117.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00120.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00125.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance00131.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance00134.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance00140.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance00143.smt2                                                                          |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|instance00145.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance00155.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00156.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00157.smt2                                                                          |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|instance00158.smt2                                                                          |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|instance00159.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|instance00164.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance00166.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance00172.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00173.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance00177.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance00178.smt2                                                                          |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|instance00180.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance00181.smt2                                                                          |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|instance00187.smt2                                                                          |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|instance00190.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance00191.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance00194.smt2                                                                          |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|instance00197.smt2                                                                          |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|instance00198.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00204.smt2                                                                          |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|instance00205.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance00208.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance00212.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance00213.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance00220.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance00221.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance00230.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance00237.smt2                                                                          |   8.793s  |   8.793s  |   0.000s  | 0.0%|
|instance00240.smt2                                                                          |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|instance00241.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance00243.smt2                                                                          |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|instance00245.smt2                                                                          |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|instance00246.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance00258.smt2                                                                          |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|instance00261.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance00262.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance00263.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance00266.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance00270.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance00274.smt2                                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|instance00276.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance00285.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance00289.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00290.smt2                                                                          |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|instance00293.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance00295.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance00302.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance00303.smt2                                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|instance00304.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance00305.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance00310.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance00314.smt2                                                                          |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|instance00320.smt2                                                                          |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|instance00323.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance00333.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance00339.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance00341.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00344.smt2                                                                          |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|instance00349.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance00351.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00358.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance00363.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00368.smt2                                                                          |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|instance00372.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance00375.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance00383.smt2                                                                          |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|instance00387.smt2                                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|instance00390.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|instance00391.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00396.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00408.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance00410.smt2                                                                          |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|instance00411.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance00413.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance00417.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance00418.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00419.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance00431.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance00436.smt2                                                                          |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|instance00441.smt2                                                                          |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|instance00442.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance00443.smt2                                                                          |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|instance00444.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance00452.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00454.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance00455.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance00459.smt2                                                                          |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|instance00462.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance00484.smt2                                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|instance00486.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance00488.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance00493.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance00498.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00508.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00511.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|instance00541.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance00547.smt2                                                                          |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|instance00549.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance00551.smt2                                                                          |   0.433s  |   0.433s  |   0.000s  | 0.0%|
|instance00552.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance00553.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance00572.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance00580.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00586.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance00587.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance00601.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance00602.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00603.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance00610.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance00611.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance00612.smt2                                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|instance00613.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance00615.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance00616.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance00617.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance00618.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance00626.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance00633.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance00638.smt2                                                                          |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|instance00640.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance00649.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance00654.smt2                                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|instance00662.smt2                                                                          |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|instance00667.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance00668.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance00669.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00673.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|instance00681.smt2                                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|instance00684.smt2                                                                          |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|instance00687.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance00689.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance00692.smt2                                                                          |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|instance00698.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance00706.smt2                                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|instance00711.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance00712.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance00714.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00717.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance00720.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance00722.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance00724.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance00731.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00732.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance00733.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance00737.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance00738.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance00739.smt2                                                                          |   0.271s  |   0.271s  |   0.000s  | 0.0%|
|instance00746.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance00750.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance00755.smt2                                                                          |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|instance00762.smt2                                                                          |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|instance00763.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance00767.smt2                                                                          |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|instance00769.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance00775.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00776.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00779.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance00780.smt2                                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|instance00785.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance00789.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance00800.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance00801.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00815.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance00826.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance00828.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance00837.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00838.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance00840.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance00846.smt2                                                                          |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|instance00847.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance00850.smt2                                                                          |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|instance00851.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance00855.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance00857.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance00882.smt2                                                                          |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|instance00883.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance00884.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance00889.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance00892.smt2                                                                          |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|instance00893.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance00896.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance00901.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00906.smt2                                                                          |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|instance00907.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance00912.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00917.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00924.smt2                                                                          |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|instance00927.smt2                                                                          |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|instance00937.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance00938.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance00944.smt2                                                                          |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|instance00959.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance00964.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance00969.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance00973.smt2                                                                          |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|instance00974.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance00976.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance00977.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00978.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00981.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance00982.smt2                                                                          |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|instance00985.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00991.smt2                                                                          |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|instance00994.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00996.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00999.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01000.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance01003.smt2                                                                          |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|instance01006.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01012.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01019.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance01020.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance01024.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance01028.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance01034.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01050.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance01051.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance01055.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance01056.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance01061.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance01065.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance01076.smt2                                                                          |   0.414s  |   0.414s  |   0.000s  | 0.0%|
|instance01083.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance01084.smt2                                                                          |   1.705s  |   1.705s  |   0.000s  | 0.0%|
|instance01091.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01096.smt2                                                                          |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|instance01097.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance01101.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance01102.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance01106.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01107.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance01115.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01119.smt2                                                                          |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|instance01120.smt2                                                                          |   2.357s  |   2.357s  |   0.000s  | 0.0%|
|instance01123.smt2                                                                          |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|instance01124.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance01125.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance01127.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance01135.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01144.smt2                                                                          |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|instance01146.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance01148.smt2                                                                          |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|instance01151.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01155.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance01156.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01157.smt2                                                                          |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|instance01159.smt2                                                                          |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|instance01161.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance01163.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance01167.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance01170.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance01172.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance01180.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance01183.smt2                                                                          |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|instance01185.smt2                                                                          |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|instance01186.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance01188.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance01196.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance01200.smt2                                                                          |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|instance01203.smt2                                                                          |   7.588s  |   7.588s  |   0.000s  | 0.0%|
|instance01212.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance01214.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance01215.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance01216.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance01219.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance01220.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance01224.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance01225.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance01226.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance01227.smt2                                                                          |   1.384s  |   1.384s  |   0.000s  | 0.0%|
|instance01228.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance01229.smt2                                                                          |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|instance01230.smt2                                                                          |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|instance01235.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance01256.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance01262.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01263.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance01265.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance01267.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01271.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance01278.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance01289.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01291.smt2                                                                          |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|instance01292.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance01293.smt2                                                                          |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|instance01295.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01296.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance01298.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance01307.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance01309.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01310.smt2                                                                          |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|instance01318.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance01323.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance01325.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance01328.smt2                                                                          |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|instance01331.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance01337.smt2                                                                          |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|instance01342.smt2                                                                          |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|instance01349.smt2                                                                          |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|instance01350.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance01352.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance01354.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance01359.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01365.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance01366.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance01367.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01369.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01370.smt2                                                                          |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|instance01382.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01385.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance01387.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance01390.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance01391.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance01395.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01405.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01406.smt2                                                                          |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|instance01412.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance01415.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance01418.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance01421.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance01424.smt2                                                                          |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|instance01428.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance01432.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance01436.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance01438.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance01443.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance01444.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance01447.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance01451.smt2                                                                          |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|instance01454.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance01456.smt2                                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|instance01460.smt2                                                                          |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|instance01468.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance01473.smt2                                                                          |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|instance01478.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance01479.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance01482.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01484.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|instance01492.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance01496.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01497.smt2                                                                          |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|instance01498.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance01507.smt2                                                                          |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|instance01510.smt2                                                                          |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|instance01517.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01529.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance01530.smt2                                                                          |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|instance01541.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance01560.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance01561.smt2                                                                          |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|instance01562.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance01570.smt2                                                                          |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|instance01575.smt2                                                                          |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|instance01591.smt2                                                                          |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|instance01594.smt2                                                                          |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|instance01614.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance01617.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance01618.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01619.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance01620.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01623.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance01627.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01630.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01631.smt2                                                                          |   0.611s  |   0.611s  |   0.000s  | 0.0%|
|instance01633.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01634.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance01635.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance01637.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance01638.smt2                                                                          |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|instance01640.smt2                                                                          |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|instance01646.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance01649.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01664.smt2                                                                          |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|instance01671.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance01672.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance01678.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance01679.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance01689.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance01691.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance01692.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance01694.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance01697.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01702.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance01703.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance01707.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance01712.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance01713.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance01714.smt2                                                                          |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|instance01725.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance01732.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance01736.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance01742.smt2                                                                          |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|instance01746.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance01754.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance01755.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance01758.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance01759.smt2                                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|instance01768.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance01771.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance01773.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance01778.smt2                                                                          |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|instance01779.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance01783.smt2                                                                          |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|instance01792.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance01794.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance01796.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01797.smt2                                                                          |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|instance01801.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance01802.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance01805.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01806.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance01808.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance01814.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|instance01815.smt2                                                                          |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|instance01822.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance01825.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance01827.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance01832.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01835.smt2                                                                          |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|instance01839.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance01840.smt2                                                                          |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|instance01842.smt2                                                                          |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|instance01845.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01846.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01855.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01859.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance01861.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance01868.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance01872.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance01875.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance01876.smt2                                                                          |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|instance01878.smt2                                                                          |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|instance01882.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance01890.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance01891.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance01899.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance01903.smt2                                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|instance01904.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance01905.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance01911.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance01920.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance01921.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance01942.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance01946.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance01948.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance01951.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance01954.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance01957.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance01960.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance01978.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance01981.smt2                                                                          |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|instance01985.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance01987.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance01994.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance01995.smt2                                                                          |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|instance01998.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance01999.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance02000.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance02006.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance02019.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance02023.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|instance02043.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance02046.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance02051.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance02053.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance02054.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance02057.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance02064.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance02070.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance02072.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance02074.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance02075.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance02078.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance02084.smt2                                                                          |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|instance02095.smt2                                                                          |   3.492s  |   3.492s  |   0.000s  | 0.0%|
|instance02096.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance02097.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance02104.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance02115.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance02118.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance02123.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance02125.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance02126.smt2                                                                          |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|instance02131.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance02134.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance02135.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance02138.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance02139.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance02149.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance02150.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance02154.smt2                                                                          |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|instance02158.smt2                                                                          |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|instance02163.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance02167.smt2                                                                          |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|instance02171.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance02174.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|instance02176.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance02179.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance02181.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance02182.smt2                                                                          |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|instance02184.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance02185.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance02186.smt2                                                                          |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|instance02189.smt2                                                                          |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|instance02194.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance02212.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance02222.smt2                                                                          |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|instance02223.smt2                                                                          |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|instance02228.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance02231.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance02236.smt2                                                                          |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|instance02237.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance02239.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance02245.smt2                                                                          |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|instance02246.smt2                                                                          |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|instance02247.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance02249.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance02252.smt2                                                                          |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|instance02256.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance02265.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance02277.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance02278.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance02280.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance02281.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance02298.smt2                                                                          |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|instance02305.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance02314.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance02323.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance02326.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance02328.smt2                                                                          |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|instance02332.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance02333.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance02342.smt2                                                                          |   0.622s  |   0.622s  |   0.000s  | 0.0%|
|instance02345.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance02352.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance02355.smt2                                                                          |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|instance02359.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance02362.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance02369.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance02380.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance02384.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance02385.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance02389.smt2                                                                          |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|instance02394.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance02399.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance02415.smt2                                                                          |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|instance02424.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance02426.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance02427.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance02433.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance02437.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance02438.smt2                                                                          |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|instance02440.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance02443.smt2                                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|instance02448.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance02455.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance02460.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance02462.smt2                                                                          |   0.717s  |   0.717s  |   0.000s  | 0.0%|
|instance02465.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance02477.smt2                                                                          |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|instance02481.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance02486.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance02491.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance02493.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance02495.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance02500.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance02507.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance02509.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance02512.smt2                                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|instance02514.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance02520.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance02527.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance02530.smt2                                                                          |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|instance02533.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance02538.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance02550.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance02551.smt2                                                                          |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|instance02552.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance02556.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance02563.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|instance02571.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance02576.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance02580.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance02585.smt2                                                                          |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|instance02587.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance02589.smt2                                                                          |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|instance02593.smt2                                                                          |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|instance02594.smt2                                                                          |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|instance02599.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance02607.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance02612.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance02613.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance02615.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance02617.smt2                                                                          |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|instance02619.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance02622.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance02624.smt2                                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|instance02629.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance02631.smt2                                                                          |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|instance02633.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance02634.smt2                                                                          |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|instance02635.smt2                                                                          |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|instance02640.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance02645.smt2                                                                          |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|instance02648.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance02656.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance02657.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance02660.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance02662.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance02663.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance02664.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance02665.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance02670.smt2                                                                          |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|instance02673.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance02675.smt2                                                                          |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|instance02676.smt2                                                                          |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|instance02682.smt2                                                                          |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|instance02685.smt2                                                                          |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|instance02686.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance02693.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance02698.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance02701.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance02705.smt2                                                                          |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|instance02712.smt2                                                                          |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|instance02713.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance02718.smt2                                                                          |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|instance02730.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance02731.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance02734.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance02735.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance02736.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance02752.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance02762.smt2                                                                          |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|instance02763.smt2                                                                          |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|instance02764.smt2                                                                          |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|instance02766.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance02767.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance02772.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance02774.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance02779.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance02780.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance02784.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance02785.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance02786.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance02788.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance02796.smt2                                                                          |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|instance02801.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance02807.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance02809.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance02815.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance02816.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance02819.smt2                                                                          |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|instance02820.smt2                                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|instance02823.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance02825.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance02827.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance02831.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance02834.smt2                                                                          |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|instance02836.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance02839.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance02840.smt2                                                                          |   0.955s  |   0.955s  |   0.000s  | 0.0%|
|instance02844.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance02845.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance02847.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance02849.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance02853.smt2                                                                          |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|instance02855.smt2                                                                          |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|instance02860.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance02866.smt2                                                                          |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|instance02875.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance02885.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance02893.smt2                                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|instance02898.smt2                                                                          |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|instance02903.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance02905.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance02908.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance02918.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance02920.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance02925.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance02926.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance02927.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance02931.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance02941.smt2                                                                          |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|instance02957.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance02958.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance02960.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance02961.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance02971.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance02981.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance02988.smt2                                                                          |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|instance02990.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance02992.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance03007.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance03016.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance03018.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance03022.smt2                                                                          |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|instance03024.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance03026.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance03028.smt2                                                                          |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|instance03029.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance03041.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance03046.smt2                                                                          |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|instance03056.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance03066.smt2                                                                          |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|instance03067.smt2                                                                          |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|instance03070.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance03072.smt2                                                                          |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|instance03074.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance03078.smt2                                                                          |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|instance03081.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance03096.smt2                                                                          |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|instance03100.smt2                                                                          |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|instance03101.smt2                                                                          |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|instance03105.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance03106.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance03107.smt2                                                                          |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|instance03120.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance03122.smt2                                                                          |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|instance03132.smt2                                                                          |   1.044s  |   1.044s  |   0.000s  | 0.0%|
|instance03136.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance03137.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance03139.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance03140.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance03153.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance03158.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance03163.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|instance03165.smt2                                                                          |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|instance03168.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance03170.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance03172.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance03173.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance03174.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance03175.smt2                                                                          |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|instance03180.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance03204.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance03209.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance03211.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance03218.smt2                                                                          |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|instance03228.smt2                                                                          |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|instance03229.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance03230.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance03233.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance03234.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance03237.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance03241.smt2                                                                          |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|instance03245.smt2                                                                          |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|instance03246.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance03254.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance03261.smt2                                                                          |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|instance03264.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance03269.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance03272.smt2                                                                          |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|instance03273.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance03283.smt2                                                                          |   0.826s  |   0.826s  |   0.000s  | 0.0%|
|instance03284.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance03286.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance03287.smt2                                                                          |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|instance03308.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance03315.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance03319.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance03321.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance03327.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance03331.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance03342.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance03345.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance03348.smt2                                                                          |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|instance03349.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance03353.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance03362.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance03370.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance03371.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance03376.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance03383.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance03384.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance03391.smt2                                                                          |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|instance03392.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance03395.smt2                                                                          |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|instance03397.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance03398.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance03404.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance03407.smt2                                                                          |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|instance03408.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance03415.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance03416.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance03418.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance03424.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance03425.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance03430.smt2                                                                          |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|instance03433.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|instance03439.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance03442.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance03449.smt2                                                                          |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|instance03455.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance03456.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance03458.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance03462.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance03468.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance03470.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance03476.smt2                                                                          |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|instance03485.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance03490.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance03491.smt2                                                                          |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|instance03494.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance03496.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance03497.smt2                                                                          |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|instance03499.smt2                                                                          |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|instance03509.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance03510.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance03514.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance03516.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance03520.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance03527.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance03529.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance03530.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance03531.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance03532.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance03541.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance03543.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance03548.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance03553.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance03554.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance03555.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance03560.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance03563.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance03568.smt2                                                                          |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|instance03581.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance03585.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance03590.smt2                                                                          |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|instance03594.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance03596.smt2                                                                          |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|instance03607.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance03612.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|instance03618.smt2                                                                          |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|instance03619.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance03621.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance03623.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance03630.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance03636.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance03638.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance03640.smt2                                                                          |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|instance03643.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance03647.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance03649.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance03652.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance03655.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance03657.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance03660.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance03667.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance03668.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance03674.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance03675.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance03677.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance03678.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance03682.smt2                                                                          |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|instance03683.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance03690.smt2                                                                          |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|instance03697.smt2                                                                          |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|instance03699.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance03708.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance03709.smt2                                                                          |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|instance03711.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance03714.smt2                                                                          |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|instance03721.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance03727.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance03729.smt2                                                                          |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|instance03731.smt2                                                                          |   0.611s  |   0.611s  |   0.000s  | 0.0%|
|instance03732.smt2                                                                          |   1.041s  |   1.041s  |   0.000s  | 0.0%|
|instance03737.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance03738.smt2                                                                          |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|instance03739.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance03741.smt2                                                                          |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|instance03747.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance03750.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance03758.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance03775.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance03777.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance03779.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance03780.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance03782.smt2                                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|instance03783.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance03792.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance03794.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance03798.smt2                                                                          |   1.512s  |   1.512s  |   0.000s  | 0.0%|
|instance03806.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance03812.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance03813.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance03815.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance03817.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance03826.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance03827.smt2                                                                          |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|instance03838.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance03840.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance03841.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance03847.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance03849.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance03852.smt2                                                                          |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|instance03854.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance03858.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance03859.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance03879.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance03884.smt2                                                                          |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|instance03887.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance03898.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance03900.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance03908.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance03911.smt2                                                                          |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|instance03918.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance03919.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance03920.smt2                                                                          |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|instance03925.smt2                                                                          |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|instance03926.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance03929.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance03935.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance03939.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance03942.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance03946.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance03950.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance03951.smt2                                                                          |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|instance03954.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance03957.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance03959.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance03963.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance03966.smt2                                                                          |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|instance03972.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance03987.smt2                                                                          |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|instance03991.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance03998.smt2                                                                          |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|instance04000.smt2                                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|instance04003.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance04006.smt2                                                                          |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|instance04011.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance04015.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance04016.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance04020.smt2                                                                          |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|instance04036.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance04039.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance04041.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance04042.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance04043.smt2                                                                          |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|instance04044.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance04047.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance04048.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance04061.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance04062.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance04063.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance04074.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance04075.smt2                                                                          |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|instance04084.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance04092.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance04094.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance04097.smt2                                                                          |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|instance04107.smt2                                                                          |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|instance04108.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance04110.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance04115.smt2                                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|instance04138.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance04139.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance04143.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance04145.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance04148.smt2                                                                          |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|instance04150.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance04155.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance04156.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance04170.smt2                                                                          |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|instance04174.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance04177.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance04182.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance04212.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance04217.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance04218.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance04226.smt2                                                                          |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|instance04228.smt2                                                                          |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|instance04230.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance04237.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance04238.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|instance04240.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance04241.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance04245.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance04252.smt2                                                                          |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|instance04253.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance04256.smt2                                                                          |   0.928s  |   0.928s  |   0.000s  | 0.0%|
|instance04258.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance04259.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance04261.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance04269.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance04271.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance04278.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance04280.smt2                                                                          |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|instance04281.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance04282.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance04284.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance04294.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance04297.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance04308.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance04311.smt2                                                                          |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|instance04312.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance04324.smt2                                                                          |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|instance04327.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance04330.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance04333.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance04336.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance04342.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance04349.smt2                                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|instance04350.smt2                                                                          |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|instance04351.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance04358.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance04359.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance04361.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance04362.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance04369.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance04372.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance04378.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance04392.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance04397.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance04398.smt2                                                                          |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|instance04399.smt2                                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|instance04400.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance04412.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance04413.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance04415.smt2                                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|instance04416.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance04418.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance04422.smt2                                                                          |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|instance04428.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance04435.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance04436.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance04444.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance04456.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance04461.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance04466.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance04467.smt2                                                                          |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|instance04471.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance04478.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance04484.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance04490.smt2                                                                          |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|instance04499.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance04502.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance04507.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance04514.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance04517.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance04519.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance04520.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance04523.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance04526.smt2                                                                          |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|instance04530.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|instance04531.smt2                                                                          |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|instance04532.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance04536.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance04537.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance04545.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance04551.smt2                                                                          |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|instance04556.smt2                                                                          |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|instance04560.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance04561.smt2                                                                          |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|instance04565.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance04567.smt2                                                                          |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|instance04569.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance04572.smt2                                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|instance04574.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance04575.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance04576.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance04577.smt2                                                                          |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|instance04586.smt2                                                                          |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|instance04587.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance04589.smt2                                                                          |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|instance04591.smt2                                                                          |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|instance04592.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance04593.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance04594.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance04603.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance04605.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance04607.smt2                                                                          |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|instance04610.smt2                                                                          |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|instance04612.smt2                                                                          |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|instance04627.smt2                                                                          |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|instance04637.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|instance04638.smt2                                                                          |   0.278s  |   0.278s  |   0.000s  | 0.0%|
|instance04644.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance04645.smt2                                                                          |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|instance04650.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance04653.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|instance04657.smt2                                                                          |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|instance04659.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance04666.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance04670.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance04671.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance04675.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance04677.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance04678.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance04688.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance04691.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance04699.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance04704.smt2                                                                          |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|instance04707.smt2                                                                          |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|instance04708.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance04717.smt2                                                                          |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|instance04719.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance04721.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance04723.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance04724.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance04725.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance04726.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance04732.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance04738.smt2                                                                          |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|instance04748.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance04750.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance04760.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance04762.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance04763.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance04764.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance04774.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance04780.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance04781.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance04783.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance04784.smt2                                                                          |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|instance04799.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance04803.smt2                                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|instance04806.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance04809.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance04810.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance04822.smt2                                                                          |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|instance04824.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance04825.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance04829.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance04837.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance04839.smt2                                                                          |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|instance04841.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance04842.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance04843.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance04851.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance04860.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance04861.smt2                                                                          |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|instance04867.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance04873.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance04880.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance04885.smt2                                                                          |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|instance04891.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance04893.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance04894.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance04898.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance04900.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance04903.smt2                                                                          |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|instance04917.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance04941.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance04950.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance04953.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance04961.smt2                                                                          |   1.046s  |   1.046s  |   0.000s  | 0.0%|
|instance04968.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance04976.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance04980.smt2                                                                          |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|instance04993.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance04994.smt2                                                                          |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|instance04996.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance05004.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance05008.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance05012.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance05013.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance05014.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance05015.smt2                                                                          |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|instance05022.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance05025.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance05027.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance05028.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance05030.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance05038.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance05040.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance05041.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance05045.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance05057.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance05061.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance05066.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance05072.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance05073.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance05074.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance05078.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance05085.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance05087.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance05090.smt2                                                                          |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|instance05096.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance05098.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance05099.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance05101.smt2                                                                          |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|instance05103.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance05107.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance05115.smt2                                                                          |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|instance05116.smt2                                                                          |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|instance05124.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance05126.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance05130.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance05132.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance05135.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance05136.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance05140.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance05146.smt2                                                                          |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|instance05149.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance05151.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance05152.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance05161.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance05162.smt2                                                                          |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|instance05166.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance05167.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance05189.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance05194.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance05195.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance05199.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance05200.smt2                                                                          |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|instance05202.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance05203.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance05209.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance05210.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance05217.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance05218.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance05220.smt2                                                                          |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|instance05231.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance05234.smt2                                                                          |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|instance05241.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance05244.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance05253.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance05259.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|instance05261.smt2                                                                          |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|instance05262.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance05271.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance05273.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance05284.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance05290.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance05291.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance05295.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance05297.smt2                                                                          |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|instance05303.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance05305.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance05309.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance05315.smt2                                                                          |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|instance05316.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance05318.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance05325.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance05330.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance05332.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance05337.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance05351.smt2                                                                          |   0.288s  |   0.288s  |   0.000s  | 0.0%|
|instance05355.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance05359.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance05362.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance05363.smt2                                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|instance05370.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance05382.smt2                                                                          |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|instance05394.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance05395.smt2                                                                          |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|instance05406.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance05413.smt2                                                                          |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|instance05418.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance05422.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance05424.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance05425.smt2                                                                          |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|instance05426.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance05430.smt2                                                                          |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|instance05431.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance05441.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance05447.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance05453.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance05458.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance05461.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance05463.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance05467.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance05468.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance05470.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance05471.smt2                                                                          |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|instance05481.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance05483.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance05486.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance05489.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance05490.smt2                                                                          |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|instance05494.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|instance05495.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance05498.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance05526.smt2                                                                          |   5.871s  |   5.871s  |   0.000s  | 0.0%|
|instance05528.smt2                                                                          |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|instance05529.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance05531.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|instance05533.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance05535.smt2                                                                          |   1.016s  |   1.016s  |   0.000s  | 0.0%|
|instance05539.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance05541.smt2                                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|instance05545.smt2                                                                          |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|instance05546.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance05548.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance05549.smt2                                                                          |   1.441s  |   1.441s  |   0.000s  | 0.0%|
|instance05550.smt2                                                                          |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|instance05552.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance05554.smt2                                                                          |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|instance05562.smt2                                                                          |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|instance05568.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance05571.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance05579.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance05582.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance05584.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance05585.smt2                                                                          |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|instance05590.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance05592.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance05597.smt2                                                                          |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|instance05607.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance05609.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance05610.smt2                                                                          |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|instance05620.smt2                                                                          |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|instance05623.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance05630.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance05647.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance05648.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance05652.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance05654.smt2                                                                          |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|instance05662.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance05665.smt2                                                                          |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|instance05685.smt2                                                                          |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|instance05686.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance05696.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance05702.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance05705.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance05707.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance05708.smt2                                                                          |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|instance05713.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance05718.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance05721.smt2                                                                          |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|instance05722.smt2                                                                          |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|instance05724.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance05726.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance05730.smt2                                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|instance05732.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance05735.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance05736.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|instance05739.smt2                                                                          |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|instance05743.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance05748.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance05749.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance05750.smt2                                                                          |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|instance05759.smt2                                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|instance05760.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance05765.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance05768.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance05773.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance05777.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance05779.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance05781.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance05792.smt2                                                                          |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|instance05806.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance05815.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance05820.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance05822.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance05827.smt2                                                                          |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|instance05835.smt2                                                                          |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|instance05841.smt2                                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|instance05847.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance05853.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance05856.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance05858.smt2                                                                          |   0.359s  |   0.359s  |   0.000s  | 0.0%|
|instance05860.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance05862.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance05876.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance05877.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance05883.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance05884.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance05885.smt2                                                                          |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|instance05888.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance05890.smt2                                                                          |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|instance05893.smt2                                                                          |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|instance05896.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance05898.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance05902.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance05909.smt2                                                                          |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|instance05922.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance05926.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance05931.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance05933.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance05943.smt2                                                                          |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|instance05974.smt2                                                                          |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|instance05978.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance05982.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance05985.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance05988.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance05990.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance05993.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance06033.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance06038.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance06041.smt2                                                                          |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|instance06065.smt2                                                                          |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|instance06070.smt2                                                                          |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|instance06076.smt2                                                                          |   0.342s  |   0.342s  |   0.000s  | 0.0%|
|instance06081.smt2                                                                          |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|instance06082.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|instance06086.smt2                                                                          |   0.492s  |   0.492s  |   0.000s  | 0.0%|
|instance06089.smt2                                                                          |   2.389s  |   2.389s  |   0.000s  | 0.0%|
|instance06119.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance06131.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance06133.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance06144.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance06146.smt2                                                                          |   0.403s  |   0.403s  |   0.000s  | 0.0%|
|instance06158.smt2                                                                          |   0.554s  |   0.554s  |   0.000s  | 0.0%|
|instance06159.smt2                                                                          |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|instance06163.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance06205.smt2                                                                          |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|instance06209.smt2                                                                          |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|instance06213.smt2                                                                          |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|instance06217.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance06221.smt2                                                                          |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|instance06229.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance06234.smt2                                                                          |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|instance06237.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance06244.smt2                                                                          |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|instance06247.smt2                                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|instance06267.smt2                                                                          |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|instance06269.smt2                                                                          |   0.301s  |   0.301s  |   0.000s  | 0.0%|
|instance06271.smt2                                                                          |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|instance06276.smt2                                                                          |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|instance06277.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance06278.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance06279.smt2                                                                          |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|instance06292.smt2                                                                          |   0.776s  |   0.776s  |   0.000s  | 0.0%|
|instance06295.smt2                                                                          |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|instance06332.smt2                                                                          |   0.506s  |   0.506s  |   0.000s  | 0.0%|
|instance06345.smt2                                                                          |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|instance06364.smt2                                                                          |   2.392s  |   2.392s  |   0.000s  | 0.0%|
|instance06367.smt2                                                                          |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|instance06375.smt2                                                                          |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|instance06379.smt2                                                                          |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|instance06389.smt2                                                                          |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|instance06427.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance06433.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance06437.smt2                                                                          |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|instance06442.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance06443.smt2                                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|instance06457.smt2                                                                          |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|instance06480.smt2                                                                          |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|instance06488.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance06501.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance06511.smt2                                                                          |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|instance06520.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance06534.smt2                                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|instance06540.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance06542.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance06545.smt2                                                                          |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|instance06550.smt2                                                                          |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|instance06575.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance06579.smt2                                                                          |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|instance06588.smt2                                                                          |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|instance06591.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance06617.smt2                                                                          |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|instance06624.smt2                                                                          |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|instance06642.smt2                                                                          |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|instance06671.smt2                                                                          |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|instance06672.smt2                                                                          |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|instance06675.smt2                                                                          |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|instance06680.smt2                                                                          |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|instance06682.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance06690.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance06701.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance06713.smt2                                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|instance06714.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance06720.smt2                                                                          |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|instance06724.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance06738.smt2                                                                          |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|instance06744.smt2                                                                          |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|instance06745.smt2                                                                          |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|instance06747.smt2                                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|instance06749.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance06752.smt2                                                                          |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|instance06761.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance06777.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance06780.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance06781.smt2                                                                          |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|instance06783.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance06800.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance06830.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance06837.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance06838.smt2                                                                          |   0.401s  |   0.401s  |   0.000s  | 0.0%|
|instance06847.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance06856.smt2                                                                          |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|instance06879.smt2                                                                          |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|instance06880.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance06882.smt2                                                                          |   0.710s  |   0.710s  |   0.000s  | 0.0%|
|instance06901.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance06905.smt2                                                                          |   0.315s  |   0.315s  |   0.000s  | 0.0%|
|instance06928.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance06934.smt2                                                                          |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|instance06940.smt2                                                                          |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|instance06941.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance06942.smt2                                                                          |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|instance06943.smt2                                                                          |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|instance06975.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance06979.smt2                                                                          |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|instance06981.smt2                                                                          |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|instance06983.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance06993.smt2                                                                          |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|instance07009.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance07010.smt2                                                                          |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|instance07013.smt2                                                                          |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|instance07018.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance07022.smt2                                                                          |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|instance07035.smt2                                                                          |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|instance07043.smt2                                                                          |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|instance07046.smt2                                                                          |   0.486s  |   0.486s  |   0.000s  | 0.0%|
|instance07056.smt2                                                                          |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|instance07073.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance07076.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance07091.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance07107.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance07115.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance07117.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance07119.smt2                                                                          |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|instance07123.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance07134.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance07139.smt2                                                                          |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|instance07148.smt2                                                                          |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|instance07149.smt2                                                                          |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|instance07165.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance07171.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance07172.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance07179.smt2                                                                          |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|instance07200.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance07201.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance07204.smt2                                                                          |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|instance07207.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance07212.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance07225.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance07227.smt2                                                                          |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|instance07230.smt2                                                                          |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|instance07237.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance07244.smt2                                                                          |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|instance07255.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance07258.smt2                                                                          |   2.801s  |   2.801s  |   0.000s  | 0.0%|
|instance07265.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance07266.smt2                                                                          |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|instance07277.smt2                                                                          |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|instance07306.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance07312.smt2                                                                          |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|instance07317.smt2                                                                          |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|instance07340.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance07356.smt2                                                                          |   0.586s  |   0.586s  |   0.000s  | 0.0%|
|instance07366.smt2                                                                          |   0.383s  |   0.383s  |   0.000s  | 0.0%|
|instance07371.smt2                                                                          |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|instance07376.smt2                                                                          |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|instance07380.smt2                                                                          |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|instance07409.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance07418.smt2                                                                          |   1.504s  |   1.504s  |   0.000s  | 0.0%|
|instance07422.smt2                                                                          |   0.780s  |   0.780s  |   0.000s  | 0.0%|
|instance07426.smt2                                                                          |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|instance07435.smt2                                                                          |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|instance07446.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance07457.smt2                                                                          |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|instance07459.smt2                                                                          |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|instance07476.smt2                                                                          |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|instance07478.smt2                                                                          |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|instance07483.smt2                                                                          |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|instance07511.smt2                                                                          |   0.508s  |   0.508s  |   0.000s  | 0.0%|
|instance07520.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance07531.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance07552.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance07553.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance07570.smt2                                                                          |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|instance07571.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance07573.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance07574.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance07576.smt2                                                                          |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|instance07590.smt2                                                                          |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|instance07592.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance07601.smt2                                                                          |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|instance07614.smt2                                                                          |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|instance07643.smt2                                                                          |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|instance07646.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance07651.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance07657.smt2                                                                          |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|instance07665.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance07673.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance07678.smt2                                                                          |   1.391s  |   1.391s  |   0.000s  | 0.0%|
|instance07680.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance07712.smt2                                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|instance07714.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance07730.smt2                                                                          |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|instance07747.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance07748.smt2                                                                          |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|instance07754.smt2                                                                          |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|instance07758.smt2                                                                          |   0.758s  |   0.758s  |   0.000s  | 0.0%|
|instance07768.smt2                                                                          |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|instance07770.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance07771.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance07783.smt2                                                                          |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|instance07795.smt2                                                                          |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|instance07817.smt2                                                                          |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|instance07826.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance07841.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance07852.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance07854.smt2                                                                          |   0.462s  |   0.462s  |   0.000s  | 0.0%|
|instance07867.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance07868.smt2                                                                          |   0.257s  |   0.257s  |   0.000s  | 0.0%|
|instance07877.smt2                                                                          |   0.432s  |   0.432s  |   0.000s  | 0.0%|
|instance07885.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance07903.smt2                                                                          |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|instance07921.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance07923.smt2                                                                          |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|instance07926.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance07936.smt2                                                                          |  17.545s  |  17.545s  |   0.000s  | 0.0%|
|instance07937.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance07942.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance07944.smt2                                                                          |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|instance07949.smt2                                                                          |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|instance07960.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance07971.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance07973.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance07981.smt2                                                                          |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|instance07995.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance08012.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance08017.smt2                                                                          |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|instance08027.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance08032.smt2                                                                          |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|instance08044.smt2                                                                          |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|instance08053.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance08066.smt2                                                                          |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|instance08070.smt2                                                                          |   0.840s  |   0.840s  |   0.000s  | 0.0%|
|instance08085.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance08100.smt2                                                                          |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|instance08102.smt2                                                                          |   9.475s  |   9.475s  |   0.000s  | 0.0%|
|instance08110.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance08115.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance08116.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance08119.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance08134.smt2                                                                          |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|instance08144.smt2                                                                          |   0.539s  |   0.539s  |   0.000s  | 0.0%|
|instance08148.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance08149.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance08157.smt2                                                                          |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|instance08167.smt2                                                                          |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|instance08198.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance08199.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance08201.smt2                                                                          |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|instance08220.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance08231.smt2                                                                          |   0.273s  |   0.273s  |   0.000s  | 0.0%|
|instance08238.smt2                                                                          |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|instance08261.smt2                                                                          |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|instance08269.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance08271.smt2                                                                          |   0.475s  |   0.475s  |   0.000s  | 0.0%|
|instance08275.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance08287.smt2                                                                          |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|instance08288.smt2                                                                          |   5.477s  |   5.477s  |   0.000s  | 0.0%|
|instance08289.smt2                                                                          |   0.473s  |   0.473s  |   0.000s  | 0.0%|
|instance08293.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance08308.smt2                                                                          |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|instance08312.smt2                                                                          |   0.440s  |   0.440s  |   0.000s  | 0.0%|
|instance08320.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance08326.smt2                                                                          |   2.770s  |   2.770s  |   0.000s  | 0.0%|
|instance08332.smt2                                                                          |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|instance08339.smt2                                                                          |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|instance08348.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance08356.smt2                                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|instance08360.smt2                                                                          |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|instance08367.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance08377.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance08380.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance08385.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance08395.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance08397.smt2                                                                          |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|instance08400.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance08405.smt2                                                                          |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|instance08409.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|instance08441.smt2                                                                          |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|instance08444.smt2                                                                          |   0.901s  |   0.901s  |   0.000s  | 0.0%|
|instance08450.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance08462.smt2                                                                          |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|instance08466.smt2                                                                          |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|instance08471.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance08498.smt2                                                                          |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|instance08503.smt2                                                                          |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|instance08511.smt2                                                                          |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|instance08544.smt2                                                                          |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|instance08549.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance08552.smt2                                                                          |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|instance08555.smt2                                                                          |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|instance08580.smt2                                                                          |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|instance08582.smt2                                                                          |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|instance08588.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance08604.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance08608.smt2                                                                          |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|instance08611.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance08646.smt2                                                                          |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|instance08658.smt2                                                                          |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|instance08659.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance08668.smt2                                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|instance08683.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance08713.smt2                                                                          |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|instance08730.smt2                                                                          |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|instance08732.smt2                                                                          |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|instance08733.smt2                                                                          |   0.431s  |   0.431s  |   0.000s  | 0.0%|
|instance08734.smt2                                                                          |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|instance08743.smt2                                                                          |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|instance08762.smt2                                                                          |   1.036s  |   1.036s  |   0.000s  | 0.0%|
|instance08768.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance08771.smt2                                                                          |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|instance08775.smt2                                                                          |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|instance08790.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance08802.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|instance08809.smt2                                                                          |   0.747s  |   0.747s  |   0.000s  | 0.0%|
|instance08816.smt2                                                                          |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|instance08818.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance08832.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance08850.smt2                                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|instance08853.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance08859.smt2                                                                          |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|instance08873.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance08883.smt2                                                                          |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|instance08887.smt2                                                                          |  11.615s  |  11.615s  |   0.000s  | 0.0%|
|instance08900.smt2                                                                          |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|instance08916.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance08926.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance08933.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|instance08934.smt2                                                                          |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|instance08942.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance08943.smt2                                                                          |  19.141s  |  19.141s  |   0.000s  | 0.0%|
|instance08947.smt2                                                                          |   0.406s  |   0.406s  |   0.000s  | 0.0%|
|instance08958.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance08959.smt2                                                                          |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|instance08970.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance08974.smt2                                                                          |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|instance09000.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance09010.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance09019.smt2                                                                          |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|instance09020.smt2                                                                          |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|instance09021.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance09023.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance09030.smt2                                                                          |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|instance09040.smt2                                                                          |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|instance09052.smt2                                                                          |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|instance09055.smt2                                                                          |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|instance09058.smt2                                                                          |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|instance09085.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance09086.smt2                                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|instance09088.smt2                                                                          |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|instance09110.smt2                                                                          |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|instance09114.smt2                                                                          |   0.322s  |   0.322s  |   0.000s  | 0.0%|
|instance09134.smt2                                                                          |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|instance09139.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance09154.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance09159.smt2                                                                          |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|instance09168.smt2                                                                          |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|instance09169.smt2                                                                          |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|instance09177.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance09186.smt2                                                                          |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|instance09194.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance09216.smt2                                                                          |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|instance09238.smt2                                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|instance09243.smt2                                                                          |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|instance09248.smt2                                                                          |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|instance09261.smt2                                                                          |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|instance09272.smt2                                                                          |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|instance09279.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance09294.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance09314.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance09320.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance09341.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance09368.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance09424.smt2                                                                          |   0.283s  |   0.283s  |   0.000s  | 0.0%|
|instance09460.smt2                                                                          |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|instance09465.smt2                                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|instance09474.smt2                                                                          |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|instance09487.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance09502.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance09503.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance09505.smt2                                                                          |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|instance09516.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance09551.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance09561.smt2                                                                          |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|instance09586.smt2                                                                          |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|instance09589.smt2                                                                          |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|instance09604.smt2                                                                          |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|instance09605.smt2                                                                          |   0.608s  |   0.608s  |   0.000s  | 0.0%|
|instance09612.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance09638.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance09669.smt2                                                                          |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|instance09674.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance09675.smt2                                                                          |   1.400s  |   1.400s  |   0.000s  | 0.0%|
|instance09679.smt2                                                                          |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|instance09705.smt2                                                                          |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|instance09706.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance09736.smt2                                                                          |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|instance09750.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|instance09752.smt2                                                                          |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|instance09760.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance09773.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance09774.smt2                                                                          |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|instance09775.smt2                                                                          |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|instance09780.smt2                                                                          |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|instance09789.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance09808.smt2                                                                          |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|instance09822.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance09836.smt2                                                                          |   3.296s  |   3.296s  |   0.000s  | 0.0%|
|instance09848.smt2                                                                          |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|instance09849.smt2                                                                          |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|instance09865.smt2                                                                          |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|instance09869.smt2                                                                          |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|instance09880.smt2                                                                          |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|instance09888.smt2                                                                          |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|instance09890.smt2                                                                          |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|instance09894.smt2                                                                          |   0.316s  |   0.316s  |   0.000s  | 0.0%|
|instance09895.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance09896.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance09909.smt2                                                                          |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|instance09912.smt2                                                                          |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|instance09949.smt2                                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|instance09951.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance09965.smt2                                                                          |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|instance09984.smt2                                                                          |   0.321s  |   0.321s  |   0.000s  | 0.0%|
|instance09990.smt2                                                                          |   1.276s  |   1.276s  |   0.000s  | 0.0%|
|instance09999.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance10004.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance10044.smt2                                                                          |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|instance10047.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance10051.smt2                                                                          |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|instance10057.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance10061.smt2                                                                          |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|instance10065.smt2                                                                          |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|instance10073.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance10085.smt2                                                                          |   0.311s  |   0.311s  |   0.000s  | 0.0%|
|instance10092.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance10106.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance10112.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance10114.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance10128.smt2                                                                          |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|instance10131.smt2                                                                          |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|instance10134.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance10135.smt2                                                                          |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|instance10144.smt2                                                                          |   1.257s  |   1.257s  |   0.000s  | 0.0%|
|instance10147.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance10167.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance10173.smt2                                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|instance10176.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance10202.smt2                                                                          |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|instance10203.smt2                                                                          |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|instance10214.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance10215.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance10219.smt2                                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|instance10230.smt2                                                                          |   0.573s  |   0.573s  |   0.000s  | 0.0%|
|instance10237.smt2                                                                          |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|instance10251.smt2                                                                          |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|instance10264.smt2                                                                          |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|instance10271.smt2                                                                          |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|instance10276.smt2                                                                          |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|instance10288.smt2                                                                          |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|instance10298.smt2                                                                          |   1.918s  |   1.918s  |   0.000s  | 0.0%|
|instance10303.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance10304.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance10353.smt2                                                                          |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|instance10356.smt2                                                                          |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|instance10357.smt2                                                                          |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|instance10359.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance10366.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|instance10372.smt2                                                                          |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|instance10379.smt2                                                                          |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|instance10388.smt2                                                                          |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|instance10389.smt2                                                                          |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|instance10397.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance10398.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance10407.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance10414.smt2                                                                          |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|instance10462.smt2                                                                          |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|instance10471.smt2                                                                          |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|instance10474.smt2                                                                          |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|instance10477.smt2                                                                          |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|instance10481.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|instance10482.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|instance10483.smt2                                                                          |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|instance10484.smt2                                                                          |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|instance10487.smt2                                                                          |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|instance10490.smt2                                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|instance10515.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance10537.smt2                                                                          |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|instance10551.smt2                                                                          |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|instance10553.smt2                                                                          |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|instance10567.smt2                                                                          |   1.596s  |   1.596s  |   0.000s  | 0.0%|
|instance10579.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance10585.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance10586.smt2                                                                          |   1.142s  |   1.142s  |   0.000s  | 0.0%|
|instance10605.smt2                                                                          |   0.393s  |   0.393s  |   0.000s  | 0.0%|
|instance10611.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance10613.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance10616.smt2                                                                          |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|instance10627.smt2                                                                          |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|instance10631.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance10646.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance10650.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|instance10699.smt2                                                                          |   0.650s  |   0.650s  |   0.000s  | 0.0%|
|instance10700.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|instance10714.smt2                                                                          |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|instance10735.smt2                                                                          |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|instance10749.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance10757.smt2                                                                          |   0.456s  |   0.456s  |   0.000s  | 0.0%|
|instance10767.smt2                                                                          |   0.638s  |   0.638s  |   0.000s  | 0.0%|
|instance10775.smt2                                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|instance10778.smt2                                                                          |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|instance10781.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance10785.smt2                                                                          |  12.976s  |  12.976s  |   0.000s  | 0.0%|
|instance10789.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance10797.smt2                                                                          |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|instance10799.smt2                                                                          |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|instance10805.smt2                                                                          |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|instance10848.smt2                                                                          |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|instance10849.smt2                                                                          |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|instance10880.smt2                                                                          |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|instance10895.smt2                                                                          |   0.383s  |   0.383s  |   0.000s  | 0.0%|
|instance10903.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance10922.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance10934.smt2                                                                          |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|instance10941.smt2                                                                          |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|instance10945.smt2                                                                          |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|instance10948.smt2                                                                          |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|instance10967.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance10987.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance10997.smt2                                                                          |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|instance11004.smt2                                                                          |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|instance11012.smt2                                                                          |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|instance11018.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance11031.smt2                                                                          |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|instance11048.smt2                                                                          |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|instance11051.smt2                                                                          |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|instance11055.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance11063.smt2                                                                          |   1.310s  |   1.310s  |   0.000s  | 0.0%|
|instance11073.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance11081.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance11095.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance11099.smt2                                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|instance11101.smt2                                                                          |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|instance11105.smt2                                                                          |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|instance11127.smt2                                                                          |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|instance11147.smt2                                                                          |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|instance11156.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance11167.smt2                                                                          |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|instance11171.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance11211.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance11235.smt2                                                                          |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|instance11242.smt2                                                                          |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|instance11245.smt2                                                                          |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|instance11248.smt2                                                                          |   0.443s  |   0.443s  |   0.000s  | 0.0%|
|instance11266.smt2                                                                          |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|instance11274.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance11291.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance11342.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance11346.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|instance11349.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance11351.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance11355.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance11368.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance11377.smt2                                                                          |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|instance11388.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance11392.smt2                                                                          |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|instance11394.smt2                                                                          |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|instance11396.smt2                                                                          |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|instance11399.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance11422.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance11428.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance11433.smt2                                                                          |   1.105s  |   1.105s  |   0.000s  | 0.0%|
|instance11443.smt2                                                                          |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|instance11447.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance11461.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance11463.smt2                                                                          |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|instance11473.smt2                                                                          |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|instance11475.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance11480.smt2                                                                          |   1.174s  |   1.174s  |   0.000s  | 0.0%|
|instance11481.smt2                                                                          |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|instance11492.smt2                                                                          |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|instance11494.smt2                                                                          |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|instance11521.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance11522.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance11524.smt2                                                                          |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|instance11558.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance11560.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance11563.smt2                                                                          |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|instance11570.smt2                                                                          |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|instance11571.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance11583.smt2                                                                          |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|instance11584.smt2                                                                          |   0.327s  |   0.327s  |   0.000s  | 0.0%|
|instance11592.smt2                                                                          |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|instance11593.smt2                                                                          |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|instance11622.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance11632.smt2                                                                          |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|instance11642.smt2                                                                          |   0.406s  |   0.406s  |   0.000s  | 0.0%|
|instance11662.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance11665.smt2                                                                          |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|instance11671.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance11684.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance11710.smt2                                                                          |   0.266s  |   0.266s  |   0.000s  | 0.0%|
|instance11735.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance11738.smt2                                                                          |   0.503s  |   0.503s  |   0.000s  | 0.0%|
|instance11741.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance11742.smt2                                                                          |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|instance11750.smt2                                                                          |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|instance11751.smt2                                                                          |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|instance11754.smt2                                                                          |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|instance11771.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance11774.smt2                                                                          |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|instance11785.smt2                                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|instance11792.smt2                                                                          |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|instance11807.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance11808.smt2                                                                          |   0.673s  |   0.673s  |   0.000s  | 0.0%|
|instance11815.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance11816.smt2                                                                          |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|instance11839.smt2                                                                          |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|instance11850.smt2                                                                          |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|instance11856.smt2                                                                          |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|instance11870.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance11872.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance11909.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance11941.smt2                                                                          |   1.336s  |   1.336s  |   0.000s  | 0.0%|
|instance11944.smt2                                                                          |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|instance11950.smt2                                                                          |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|instance11958.smt2                                                                          |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|instance11996.smt2                                                                          |   0.514s  |   0.514s  |   0.000s  | 0.0%|
|instance12003.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance12019.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance12044.smt2                                                                          |   0.498s  |   0.498s  |   0.000s  | 0.0%|
|instance12052.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance12055.smt2                                                                          |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|instance12081.smt2                                                                          |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|instance12122.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance12143.smt2                                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|instance12151.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance12156.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance12163.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance12169.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance12176.smt2                                                                          |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|instance12199.smt2                                                                          |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|instance12213.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance12229.smt2                                                                          |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|instance12230.smt2                                                                          |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|instance12232.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance12236.smt2                                                                          |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|instance12266.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance12290.smt2                                                                          |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|instance12307.smt2                                                                          |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|instance12315.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance12317.smt2                                                                          |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|instance12329.smt2                                                                          |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|instance12351.smt2                                                                          |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|instance12355.smt2                                                                          |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|instance12358.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance12372.smt2                                                                          |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|instance12396.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance12403.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance12420.smt2                                                                          |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|instance12430.smt2                                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|instance12437.smt2                                                                          |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|instance12474.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance12475.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance12491.smt2                                                                          |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|instance12493.smt2                                                                          |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|instance12506.smt2                                                                          |   0.815s  |   0.815s  |   0.000s  | 0.0%|
|instance12511.smt2                                                                          |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|instance12512.smt2                                                                          |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|instance12517.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance12519.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance12520.smt2                                                                          |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|instance12531.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance12534.smt2                                                                          |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|instance12551.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance12553.smt2                                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|instance12589.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance12593.smt2                                                                          |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|instance12618.smt2                                                                          |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|instance12620.smt2                                                                          |   0.408s  |   0.408s  |   0.000s  | 0.0%|
|instance12621.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance12625.smt2                                                                          |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|instance12630.smt2                                                                          |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|instance12634.smt2                                                                          |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|instance12643.smt2                                                                          |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|instance12659.smt2                                                                          |   0.531s  |   0.531s  |   0.000s  | 0.0%|
|instance12660.smt2                                                                          |   0.440s  |   0.440s  |   0.000s  | 0.0%|
|instance12666.smt2                                                                          |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|instance12683.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance12685.smt2                                                                          |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|instance12688.smt2                                                                          |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|instance12699.smt2                                                                          |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|instance12714.smt2                                                                          |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|instance12720.smt2                                                                          |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|instance12733.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance12767.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance12770.smt2                                                                          |   0.400s  |   0.400s  |   0.000s  | 0.0%|
|instance12784.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance12790.smt2                                                                          |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|instance12793.smt2                                                                          |   2.519s  |   2.519s  |   0.000s  | 0.0%|
|instance12807.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance12815.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance12866.smt2                                                                          |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|instance12886.smt2                                                                          |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|instance12894.smt2                                                                          |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|instance12896.smt2                                                                          |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|instance12900.smt2                                                                          |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|instance12903.smt2                                                                          |   1.993s  |   1.993s  |   0.000s  | 0.0%|
|instance12905.smt2                                                                          |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|instance12909.smt2                                                                          |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|instance12917.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance12922.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance12927.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance12931.smt2                                                                          |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|instance12941.smt2                                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|instance12957.smt2                                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|instance12960.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance12965.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance12966.smt2                                                                          |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|instance12977.smt2                                                                          |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|instance13002.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance13019.smt2                                                                          |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|instance13020.smt2                                                                          |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|instance13035.smt2                                                                          |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|instance13049.smt2                                                                          |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|instance13052.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance13053.smt2                                                                          |   0.458s  |   0.458s  |   0.000s  | 0.0%|
|instance13056.smt2                                                                          |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|instance13072.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance13078.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance13092.smt2                                                                          |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|instance13102.smt2                                                                          |   0.482s  |   0.482s  |   0.000s  | 0.0%|
|instance13103.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance13104.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance13105.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance13108.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance13114.smt2                                                                          |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|instance13126.smt2                                                                          |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|instance13129.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance13140.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance13143.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance13147.smt2                                                                          |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|instance13150.smt2                                                                          |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|instance13152.smt2                                                                          |   0.511s  |   0.511s  |   0.000s  | 0.0%|
|instance13157.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance13168.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance13200.smt2                                                                          |   0.351s  |   0.351s  |   0.000s  | 0.0%|
|instance13201.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance13220.smt2                                                                          |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|instance13230.smt2                                                                          |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|instance13240.smt2                                                                          |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|instance13253.smt2                                                                          |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|instance13265.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance13277.smt2                                                                          |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|instance13293.smt2                                                                          |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|instance13315.smt2                                                                          |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|instance13321.smt2                                                                          |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|instance13326.smt2                                                                          |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|instance13346.smt2                                                                          |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|instance13357.smt2                                                                          |   0.402s  |   0.402s  |   0.000s  | 0.0%|
|instance13371.smt2                                                                          |   0.300s  |   0.300s  |   0.000s  | 0.0%|
|instance13374.smt2                                                                          |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|instance13376.smt2                                                                          |   0.575s  |   0.575s  |   0.000s  | 0.0%|
|instance13415.smt2                                                                          |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|instance13419.smt2                                                                          |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|instance13420.smt2                                                                          |   0.304s  |   0.304s  |   0.000s  | 0.0%|
|instance13424.smt2                                                                          |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|instance13434.smt2                                                                          |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|instance13442.smt2                                                                          |   1.219s  |   1.219s  |   0.000s  | 0.0%|
|instance13445.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance13451.smt2                                                                          |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|instance13455.smt2                                                                          |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|instance13460.smt2                                                                          |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|instance13463.smt2                                                                          |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|instance13464.smt2                                                                          |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|instance13480.smt2                                                                          |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|instance13514.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance13527.smt2                                                                          |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|instance13536.smt2                                                                          |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|instance13557.smt2                                                                          |   0.368s  |   0.368s  |   0.000s  | 0.0%|
|instance13561.smt2                                                                          |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|instance13563.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance13568.smt2                                                                          |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|instance13588.smt2                                                                          |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|instance13594.smt2                                                                          |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|instance13604.smt2                                                                          |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|instance13613.smt2                                                                          |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|instance13642.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance13646.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance13651.smt2                                                                          |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|instance13655.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance13660.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance13689.smt2                                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|instance13693.smt2                                                                          |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|instance13698.smt2                                                                          |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|instance13707.smt2                                                                          |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|instance13712.smt2                                                                          |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|instance13721.smt2                                                                          |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|instance13729.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance13742.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance13743.smt2                                                                          |   0.567s  |   0.567s  |   0.000s  | 0.0%|
|instance13744.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|instance13746.smt2                                                                          |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|instance13748.smt2                                                                          |   0.314s  |   0.314s  |   0.000s  | 0.0%|
|instance13756.smt2                                                                          |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|instance13767.smt2                                                                          |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|instance13769.smt2                                                                          |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|instance13772.smt2                                                                          |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|instance13785.smt2                                                                          |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|instance13797.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance13807.smt2                                                                          |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|instance13811.smt2                                                                          |   8.611s  |   8.611s  |   0.000s  | 0.0%|
|instance13815.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance13816.smt2                                                                          |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|instance13818.smt2                                                                          |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|instance13865.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance13866.smt2                                                                          |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|instance13871.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance13889.smt2                                                                          |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|instance13895.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance13900.smt2                                                                          |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|instance13909.smt2                                                                          |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|instance13911.smt2                                                                          |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|instance13936.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance13949.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance13962.smt2                                                                          |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|instance13976.smt2                                                                          |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|instance13984.smt2                                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|instance13987.smt2                                                                          |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|instance13996.smt2                                                                          |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|instance14001.smt2                                                                          |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|instance14009.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance14011.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance14012.smt2                                                                          |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|instance14051.smt2                                                                          |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|instance14088.smt2                                                                          |   1.226s  |   1.226s  |   0.000s  | 0.0%|
|instance14089.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance14110.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance14114.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance14120.smt2                                                                          |   0.841s  |   0.841s  |   0.000s  | 0.0%|
|instance14121.smt2                                                                          |   1.271s  |   1.271s  |   0.000s  | 0.0%|
|instance14124.smt2                                                                          |   7.624s  |   7.624s  |   0.000s  | 0.0%|
|instance14127.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance14176.smt2                                                                          |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|instance14182.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance14185.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|instance14190.smt2                                                                          |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|instance14193.smt2                                                                          |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|instance14195.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance14200.smt2                                                                          |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|instance14208.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance14230.smt2                                                                          |   0.311s  |   0.311s  |   0.000s  | 0.0%|
|instance14237.smt2                                                                          |   0.790s  |   0.790s  |   0.000s  | 0.0%|
|instance14268.smt2                                                                          |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|instance14274.smt2                                                                          |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|instance14298.smt2                                                                          |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|instance14299.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance14313.smt2                                                                          |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|instance14322.smt2                                                                          |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|instance14342.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance14344.smt2                                                                          |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|instance14388.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance14394.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|instance14407.smt2                                                                          |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|instance14411.smt2                                                                          |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|instance14424.smt2                                                                          |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|instance14430.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance14434.smt2                                                                          |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|instance14449.smt2                                                                          |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|instance14466.smt2                                                                          |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|instance14482.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance14485.smt2                                                                          |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|instance14486.smt2                                                                          |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|instance14510.smt2                                                                          |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|instance14521.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance14526.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance14528.smt2                                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|instance14531.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance14571.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance14573.smt2                                                                          |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|instance14585.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance14595.smt2                                                                          |   2.585s  |   2.585s  |   0.000s  | 0.0%|
|instance14612.smt2                                                                          |   0.700s  |   0.700s  |   0.000s  | 0.0%|
|instance14625.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance14635.smt2                                                                          |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|instance14636.smt2                                                                          |  18.879s  |  18.879s  |   0.000s  | 0.0%|
|instance14639.smt2                                                                          |   1.099s  |   1.099s  |   0.000s  | 0.0%|
|instance14665.smt2                                                                          |   2.638s  |   2.638s  |   0.000s  | 0.0%|
|instance14667.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance14685.smt2                                                                          |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|instance14691.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance14706.smt2                                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|instance14708.smt2                                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|instance14721.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance14728.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance14742.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance14748.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance14764.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance14782.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance14783.smt2                                                                          |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|instance14796.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance14798.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance14809.smt2                                                                          |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|instance14815.smt2                                                                          |   0.885s  |   0.885s  |   0.000s  | 0.0%|
|instance14823.smt2                                                                          |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|instance14841.smt2                                                                          |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|instance14846.smt2                                                                          |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|instance14847.smt2                                                                          |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|instance14865.smt2                                                                          |   0.342s  |   0.342s  |   0.000s  | 0.0%|
|instance14874.smt2                                                                          |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|instance14880.smt2                                                                          |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|instance14885.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance14893.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance14894.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance14899.smt2                                                                          |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|instance14900.smt2                                                                          |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|instance14910.smt2                                                                          |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|instance14925.smt2                                                                          |   0.535s  |   0.535s  |   0.000s  | 0.0%|
|instance14933.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance14934.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance14936.smt2                                                                          |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|instance14939.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance14943.smt2                                                                          |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|instance14944.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance14949.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance14952.smt2                                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|instance14953.smt2                                                                          |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|instance14959.smt2                                                                          |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|instance14961.smt2                                                                          |   4.670s  |   4.670s  |   0.000s  | 0.0%|
|instance14970.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance14971.smt2                                                                          |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|instance14978.smt2                                                                          |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|instance14994.smt2                                                                          |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|instance14995.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|instance14996.smt2                                                                          |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|instance15009.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance15014.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance15019.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance15025.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance15034.smt2                                                                          |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|instance15035.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance15039.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance15052.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance15054.smt2                                                                          |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|instance15062.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance15072.smt2                                                                          |   0.338s  |   0.338s  |   0.000s  | 0.0%|
|instance15077.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance15089.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance15098.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance15104.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance15108.smt2                                                                          |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|instance15110.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance15115.smt2                                                                          |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|instance15116.smt2                                                                          |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|instance15123.smt2                                                                          |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|instance15128.smt2                                                                          |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|instance15143.smt2                                                                          |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|instance15147.smt2                                                                          |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|instance15160.smt2                                                                          |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|instance15169.smt2                                                                          |   0.338s  |   0.338s  |   0.000s  | 0.0%|
|instance15186.smt2                                                                          |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|instance15214.smt2                                                                          |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|instance15222.smt2                                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|instance15226.smt2                                                                          |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|instance15234.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance15237.smt2                                                                          |   0.364s  |   0.364s  |   0.000s  | 0.0%|
|instance15241.smt2                                                                          |   0.321s  |   0.321s  |   0.000s  | 0.0%|
|instance15243.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance15251.smt2                                                                          |   0.375s  |   0.375s  |   0.000s  | 0.0%|
|instance15275.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance15296.smt2                                                                          |   0.912s  |   0.912s  |   0.000s  | 0.0%|
|instance15301.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance15312.smt2                                                                          |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|instance15313.smt2                                                                          |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|instance15319.smt2                                                                          |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|instance15322.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance15327.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance15337.smt2                                                                          |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|instance15351.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance15356.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance15360.smt2                                                                          |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|instance15385.smt2                                                                          |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|instance15422.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance15424.smt2                                                                          |   0.323s  |   0.323s  |   0.000s  | 0.0%|
|instance15431.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance15433.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance15443.smt2                                                                          |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|instance15450.smt2                                                                          |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|instance15456.smt2                                                                          |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|instance15458.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance15469.smt2                                                                          |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|instance15471.smt2                                                                          |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|instance15494.smt2                                                                          |   0.267s  |   0.267s  |   0.000s  | 0.0%|
|instance15499.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|instance15510.smt2                                                                          |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|instance15523.smt2                                                                          |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|instance15528.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance15537.smt2                                                                          |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|instance15551.smt2                                                                          |   1.442s  |   1.442s  |   0.000s  | 0.0%|
|instance15552.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance15560.smt2                                                                          |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|instance15562.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance15566.smt2                                                                          |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|instance15577.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance15612.smt2                                                                          |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|instance15624.smt2                                                                          |   0.528s  |   0.528s  |   0.000s  | 0.0%|
|instance15628.smt2                                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|instance15631.smt2                                                                          |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|instance15632.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance15639.smt2                                                                          |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|instance15646.smt2                                                                          |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|instance15649.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|instance15655.smt2                                                                          |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|instance15664.smt2                                                                          |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|instance15682.smt2                                                                          |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|instance15689.smt2                                                                          |   0.338s  |   0.338s  |   0.000s  | 0.0%|
|instance15691.smt2                                                                          |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|instance15710.smt2                                                                          |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|instance15715.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance15719.smt2                                                                          |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|instance15724.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance15725.smt2                                                                          |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|instance15730.smt2                                                                          |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|instance15732.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance15760.smt2                                                                          |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|instance15777.smt2                                                                          |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|instance15786.smt2                                                                          |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|instance15787.smt2                                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|instance15824.smt2                                                                          |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|instance15843.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance15844.smt2                                                                          |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|instance15851.smt2                                                                          |   0.695s  |   0.695s  |   0.000s  | 0.0%|
|instance15857.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance15864.smt2                                                                          |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|instance15866.smt2                                                                          |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|instance15869.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance15901.smt2                                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|instance15902.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance15931.smt2                                                                          |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|instance15934.smt2                                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|instance15946.smt2                                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|instance15956.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance15973.smt2                                                                          |   1.197s  |   1.197s  |   0.000s  | 0.0%|
|instance15981.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance15986.smt2                                                                          |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|instance15988.smt2                                                                          |   1.091s  |   1.091s  |   0.000s  | 0.0%|
</details>
