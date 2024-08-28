Comparing data and data


# SUMMARY
- LHS tests = 2500
- RHS tests = 2500
- LHS success = 221  (8.84%)
- RHS success = 221  (8.84%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: fa6f3f2dba89c2c44282f10c468e7482972a9bdd
Z3 branch: sls
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: inputs/QF_S_SAT
Z3 commit message: fixing prop-queue

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: fa6f3f2dba89c2c44282f10c468e7482972a9bdd
Z3 branch: sls
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: inputs/QF_S_SAT
Z3 commit message: fixing prop-queue

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01_track_124.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|01_track_127.smt2                                                                           |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|01_track_142.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|01_track_157.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_164.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_176.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|01_track_180.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|01_track_185.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_21.smt2                                                                            |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|01_track_37.smt2                                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_52.smt2                                                                            |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|01_track_62.smt2                                                                            |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|01_track_89.smt2                                                                            |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|01_track_90.smt2                                                                            |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|01_track_91.smt2                                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance00086.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00159.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance00180.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance00302.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance00349.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01_track_124.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|01_track_127.smt2                                                                           |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|01_track_142.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|01_track_157.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_164.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_176.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|01_track_180.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|01_track_185.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_21.smt2                                                                            |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|01_track_37.smt2                                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_52.smt2                                                                            |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|01_track_62.smt2                                                                            |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|01_track_89.smt2                                                                            |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|01_track_90.smt2                                                                            |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|01_track_91.smt2                                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance00086.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00159.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance00180.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance00302.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance00349.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01_track_124.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|01_track_127.smt2                                                                           |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|01_track_142.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|01_track_157.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_164.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_176.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|01_track_180.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|01_track_185.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_21.smt2                                                                            |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|01_track_37.smt2                                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_52.smt2                                                                            |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|01_track_62.smt2                                                                            |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|01_track_89.smt2                                                                            |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|01_track_90.smt2                                                                            |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|01_track_91.smt2                                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance00086.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00159.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance00180.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance00302.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance00349.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01_track_124.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|01_track_127.smt2                                                                           |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|01_track_142.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|01_track_157.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_164.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_176.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|01_track_180.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|01_track_185.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_21.smt2                                                                            |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|01_track_37.smt2                                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_52.smt2                                                                            |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|01_track_62.smt2                                                                            |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|01_track_89.smt2                                                                            |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|01_track_90.smt2                                                                            |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|01_track_91.smt2                                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance00086.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00159.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance00180.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance00302.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance00349.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|instance08809.smt2                                                                         |   0.067s |18.772MiB|
|instance13442.smt2                                                                         |   0.038s |18.828MiB|
|instance11051.smt2                                                                         |   0.034s |18.972MiB|
|instance12659.smt2                                                                         |   0.034s |18.984MiB|
|instance13315.smt2                                                                         |   0.033s |19.024MiB|
|instance13321.smt2                                                                         |   0.031s |18.836MiB|
|instance07230.smt2                                                                         |   0.030s |18.908MiB|
|instance13818.smt2                                                                         |   0.029s |18.652MiB|
|instance02530.smt2                                                                         |   0.027s |18.844MiB|
|instance13811.smt2                                                                         |   0.023s |18.964MiB|
|instance08134.smt2                                                                         |   0.018s |18.508MiB|
|instance14195.smt2                                                                         |   0.018s |19.448MiB|
|instance09159.smt2                                                                         |   0.017s |18.888MiB|
|instance07179.smt2                                                                         |   0.017s |18.784MiB|
|instance05568.smt2                                                                         |   0.016s |18.316MiB|
|instance09965.smt2                                                                         |   0.016s |18.76MiB|
|instance07936.smt2                                                                         |   0.016s |18.616MiB|
|instance11524.smt2                                                                         |   0.016s |18.464MiB|
|instance03581.smt2                                                                         |   0.016s |18.468MiB|
|instance08116.smt2                                                                         |   0.016s |18.464MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|instance08809.smt2                                                                         |   0.067s |18.772MiB|
|instance13442.smt2                                                                         |   0.038s |18.828MiB|
|instance11051.smt2                                                                         |   0.034s |18.972MiB|
|instance12659.smt2                                                                         |   0.034s |18.984MiB|
|instance13315.smt2                                                                         |   0.033s |19.024MiB|
|instance13321.smt2                                                                         |   0.031s |18.836MiB|
|instance07230.smt2                                                                         |   0.030s |18.908MiB|
|instance13818.smt2                                                                         |   0.029s |18.652MiB|
|instance02530.smt2                                                                         |   0.027s |18.844MiB|
|instance13811.smt2                                                                         |   0.023s |18.964MiB|
|instance08134.smt2                                                                         |   0.018s |18.508MiB|
|instance14195.smt2                                                                         |   0.018s |19.448MiB|
|instance09159.smt2                                                                         |   0.017s |18.888MiB|
|instance07179.smt2                                                                         |   0.017s |18.784MiB|
|instance05568.smt2                                                                         |   0.016s |18.316MiB|
|instance09965.smt2                                                                         |   0.016s |18.76MiB|
|instance07936.smt2                                                                         |   0.016s |18.616MiB|
|instance11524.smt2                                                                         |   0.016s |18.464MiB|
|instance03581.smt2                                                                         |   0.016s |18.468MiB|
|instance08116.smt2                                                                         |   0.016s |18.464MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01_track_124.smt2                                                                           |18.452MiB|18.452MiB|0B| 0.0%|
|01_track_127.smt2                                                                           |18.512MiB|18.512MiB|0B| 0.0%|
|01_track_142.smt2                                                                           |18.424MiB|18.424MiB|0B| 0.0%|
|01_track_157.smt2                                                                           |18.564MiB|18.564MiB|0B| 0.0%|
|01_track_164.smt2                                                                           |18.556MiB|18.556MiB|0B| 0.0%|
|01_track_176.smt2                                                                           |18.324MiB|18.324MiB|0B| 0.0%|
|01_track_180.smt2                                                                           |18.528MiB|18.528MiB|0B| 0.0%|
|01_track_185.smt2                                                                           |18.252MiB|18.252MiB|0B| 0.0%|
|01_track_21.smt2                                                                            |18.376MiB|18.376MiB|0B| 0.0%|
|01_track_37.smt2                                                                            |18.264MiB|18.264MiB|0B| 0.0%|
|01_track_52.smt2                                                                            |18.496MiB|18.496MiB|0B| 0.0%|
|01_track_62.smt2                                                                            |18.252MiB|18.252MiB|0B| 0.0%|
|01_track_89.smt2                                                                            |18.46MiB|18.46MiB|0B| 0.0%|
|01_track_90.smt2                                                                            |18.344MiB|18.344MiB|0B| 0.0%|
|01_track_91.smt2                                                                            |18.5MiB|18.5MiB|0B| 0.0%|
|instance00086.smt2                                                                          |18.252MiB|18.252MiB|0B| 0.0%|
|instance00159.smt2                                                                          |18.396MiB|18.396MiB|0B| 0.0%|
|instance00180.smt2                                                                          |18.432MiB|18.432MiB|0B| 0.0%|
|instance00302.smt2                                                                          |18.252MiB|18.252MiB|0B| 0.0%|
|instance00349.smt2                                                                          |18.252MiB|18.252MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01_track_124.smt2                                                                           |18.452MiB|18.452MiB|0B| 0.0%|
|01_track_127.smt2                                                                           |18.512MiB|18.512MiB|0B| 0.0%|
|01_track_142.smt2                                                                           |18.424MiB|18.424MiB|0B| 0.0%|
|01_track_157.smt2                                                                           |18.564MiB|18.564MiB|0B| 0.0%|
|01_track_164.smt2                                                                           |18.556MiB|18.556MiB|0B| 0.0%|
|01_track_176.smt2                                                                           |18.324MiB|18.324MiB|0B| 0.0%|
|01_track_180.smt2                                                                           |18.528MiB|18.528MiB|0B| 0.0%|
|01_track_185.smt2                                                                           |18.252MiB|18.252MiB|0B| 0.0%|
|01_track_21.smt2                                                                            |18.376MiB|18.376MiB|0B| 0.0%|
|01_track_37.smt2                                                                            |18.264MiB|18.264MiB|0B| 0.0%|
|01_track_52.smt2                                                                            |18.496MiB|18.496MiB|0B| 0.0%|
|01_track_62.smt2                                                                            |18.252MiB|18.252MiB|0B| 0.0%|
|01_track_89.smt2                                                                            |18.46MiB|18.46MiB|0B| 0.0%|
|01_track_90.smt2                                                                            |18.344MiB|18.344MiB|0B| 0.0%|
|01_track_91.smt2                                                                            |18.5MiB|18.5MiB|0B| 0.0%|
|instance00086.smt2                                                                          |18.252MiB|18.252MiB|0B| 0.0%|
|instance00159.smt2                                                                          |18.396MiB|18.396MiB|0B| 0.0%|
|instance00180.smt2                                                                          |18.432MiB|18.432MiB|0B| 0.0%|
|instance00302.smt2                                                                          |18.252MiB|18.252MiB|0B| 0.0%|
|instance00349.smt2                                                                          |18.252MiB|18.252MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01_track_124.smt2                                                                           |18.452MiB|18.452MiB|0B| 0.0%|
|01_track_127.smt2                                                                           |18.512MiB|18.512MiB|0B| 0.0%|
|01_track_142.smt2                                                                           |18.424MiB|18.424MiB|0B| 0.0%|
|01_track_157.smt2                                                                           |18.564MiB|18.564MiB|0B| 0.0%|
|01_track_164.smt2                                                                           |18.556MiB|18.556MiB|0B| 0.0%|
|01_track_176.smt2                                                                           |18.324MiB|18.324MiB|0B| 0.0%|
|01_track_180.smt2                                                                           |18.528MiB|18.528MiB|0B| 0.0%|
|01_track_185.smt2                                                                           |18.252MiB|18.252MiB|0B| 0.0%|
|01_track_21.smt2                                                                            |18.376MiB|18.376MiB|0B| 0.0%|
|01_track_37.smt2                                                                            |18.264MiB|18.264MiB|0B| 0.0%|
|01_track_52.smt2                                                                            |18.496MiB|18.496MiB|0B| 0.0%|
|01_track_62.smt2                                                                            |18.252MiB|18.252MiB|0B| 0.0%|
|01_track_89.smt2                                                                            |18.46MiB|18.46MiB|0B| 0.0%|
|01_track_90.smt2                                                                            |18.344MiB|18.344MiB|0B| 0.0%|
|01_track_91.smt2                                                                            |18.5MiB|18.5MiB|0B| 0.0%|
|instance00086.smt2                                                                          |18.252MiB|18.252MiB|0B| 0.0%|
|instance00159.smt2                                                                          |18.396MiB|18.396MiB|0B| 0.0%|
|instance00180.smt2                                                                          |18.432MiB|18.432MiB|0B| 0.0%|
|instance00302.smt2                                                                          |18.252MiB|18.252MiB|0B| 0.0%|
|instance00349.smt2                                                                          |18.252MiB|18.252MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01_track_124.smt2                                                                           |18.452MiB|18.452MiB|0B| 0.0%|
|01_track_127.smt2                                                                           |18.512MiB|18.512MiB|0B| 0.0%|
|01_track_142.smt2                                                                           |18.424MiB|18.424MiB|0B| 0.0%|
|01_track_157.smt2                                                                           |18.564MiB|18.564MiB|0B| 0.0%|
|01_track_164.smt2                                                                           |18.556MiB|18.556MiB|0B| 0.0%|
|01_track_176.smt2                                                                           |18.324MiB|18.324MiB|0B| 0.0%|
|01_track_180.smt2                                                                           |18.528MiB|18.528MiB|0B| 0.0%|
|01_track_185.smt2                                                                           |18.252MiB|18.252MiB|0B| 0.0%|
|01_track_21.smt2                                                                            |18.376MiB|18.376MiB|0B| 0.0%|
|01_track_37.smt2                                                                            |18.264MiB|18.264MiB|0B| 0.0%|
|01_track_52.smt2                                                                            |18.496MiB|18.496MiB|0B| 0.0%|
|01_track_62.smt2                                                                            |18.252MiB|18.252MiB|0B| 0.0%|
|01_track_89.smt2                                                                            |18.46MiB|18.46MiB|0B| 0.0%|
|01_track_90.smt2                                                                            |18.344MiB|18.344MiB|0B| 0.0%|
|01_track_91.smt2                                                                            |18.5MiB|18.5MiB|0B| 0.0%|
|instance00086.smt2                                                                          |18.252MiB|18.252MiB|0B| 0.0%|
|instance00159.smt2                                                                          |18.396MiB|18.396MiB|0B| 0.0%|
|instance00180.smt2                                                                          |18.432MiB|18.432MiB|0B| 0.0%|
|instance00302.smt2                                                                          |18.252MiB|18.252MiB|0B| 0.0%|
|instance00349.smt2                                                                          |18.252MiB|18.252MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|instance14195.smt2                                                                         |   0.018s |19.448MiB|
|instance13315.smt2                                                                         |   0.033s |19.024MiB|
|instance15934.smt2                                                                         |   0.014s |19.0MiB|
|instance12659.smt2                                                                         |   0.034s |18.984MiB|
|instance11051.smt2                                                                         |   0.034s |18.972MiB|
|instance13811.smt2                                                                         |   0.023s |18.964MiB|
|instance07230.smt2                                                                         |   0.030s |18.908MiB|
|instance09159.smt2                                                                         |   0.017s |18.888MiB|
|instance01899.smt2                                                                         |   0.009s |18.88MiB|
|instance07573.smt2                                                                         |   0.013s |18.864MiB|
|instance02530.smt2                                                                         |   0.027s |18.844MiB|
|instance14466.smt2                                                                         |   0.007s |18.844MiB|
|instance13321.smt2                                                                         |   0.031s |18.836MiB|
|instance03510.smt2                                                                         |   0.008s |18.832MiB|
|instance13442.smt2                                                                         |   0.038s |18.828MiB|
|instance06364.smt2                                                                         |   0.013s |18.824MiB|
|instance08582.smt2                                                                         |   0.012s |18.824MiB|
|instance11710.smt2                                                                         |   0.010s |18.816MiB|
|instance15327.smt2                                                                         |   0.013s |18.8MiB|
|instance13909.smt2                                                                         |   0.013s |18.792MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|instance14195.smt2                                                                         |   0.018s |19.448MiB|
|instance13315.smt2                                                                         |   0.033s |19.024MiB|
|instance15934.smt2                                                                         |   0.014s |19.0MiB|
|instance12659.smt2                                                                         |   0.034s |18.984MiB|
|instance11051.smt2                                                                         |   0.034s |18.972MiB|
|instance13811.smt2                                                                         |   0.023s |18.964MiB|
|instance07230.smt2                                                                         |   0.030s |18.908MiB|
|instance09159.smt2                                                                         |   0.017s |18.888MiB|
|instance01899.smt2                                                                         |   0.009s |18.88MiB|
|instance07573.smt2                                                                         |   0.013s |18.864MiB|
|instance02530.smt2                                                                         |   0.027s |18.844MiB|
|instance14466.smt2                                                                         |   0.007s |18.844MiB|
|instance13321.smt2                                                                         |   0.031s |18.836MiB|
|instance03510.smt2                                                                         |   0.008s |18.832MiB|
|instance13442.smt2                                                                         |   0.038s |18.828MiB|
|instance06364.smt2                                                                         |   0.013s |18.824MiB|
|instance08582.smt2                                                                         |   0.012s |18.824MiB|
|instance11710.smt2                                                                         |   0.010s |18.816MiB|
|instance15327.smt2                                                                         |   0.013s |18.8MiB|
|instance13909.smt2                                                                         |   0.013s |18.792MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01_track_124.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|01_track_127.smt2                                                                           |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|01_track_142.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|01_track_157.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_164.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_176.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|01_track_180.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|01_track_185.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_21.smt2                                                                            |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|01_track_37.smt2                                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|01_track_52.smt2                                                                            |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|01_track_62.smt2                                                                            |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|01_track_89.smt2                                                                            |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|01_track_90.smt2                                                                            |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|01_track_91.smt2                                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance00086.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00159.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance00180.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance00302.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance00349.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00586.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00611.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00617.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance00640.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance00722.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance00847.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01028.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01056.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01101.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01107.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance01235.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance01298.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance01325.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance01412.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance01447.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01478.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance01484.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance01492.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01614.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance01617.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance01725.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance01732.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01746.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01758.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance01779.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance01814.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01859.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance01904.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance01960.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance01985.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance02006.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance02064.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance02074.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance02179.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance02184.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance02212.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance02231.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance02399.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance02427.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance02481.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance02507.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance02520.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance02686.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance02816.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance02844.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance02918.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance02920.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance02971.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance03163.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance03234.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance03246.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance03264.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance03331.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance03342.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance03370.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance03416.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance03433.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance03554.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance03594.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance03677.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance03683.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance04063.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance04110.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance04156.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance04261.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance04372.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance04435.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance04466.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance04478.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance04517.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance04545.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance04659.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance04732.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance04750.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance04829.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance04842.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance04893.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance05004.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance05008.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance05022.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance05124.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance05210.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance05253.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance05259.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance05273.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance05291.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|instance05318.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance05424.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance05447.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance05470.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance05494.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance05806.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance05820.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance05856.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance05896.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance05978.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance05982.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance06217.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance06277.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance06278.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance06488.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance06575.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance06701.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance06780.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance06800.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance06901.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance06928.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance07018.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance07073.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance07076.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance07091.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance07107.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance07200.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance07225.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance07592.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance07646.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance07770.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance07937.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance07960.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance08053.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance08116.smt2                                                                          |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|instance08148.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance08220.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance08320.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance08380.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance08400.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance08768.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance08790.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance09000.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance09294.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance10004.smt2                                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|instance10092.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance10134.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance10167.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance10214.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance10304.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance10366.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance10585.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance10781.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance10922.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance10967.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance11018.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance11055.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance11156.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance11211.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance11274.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance11351.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance11355.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance11388.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance11560.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance11622.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance11671.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance11684.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance12003.smt2                                                                          |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|instance12019.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance12475.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance12589.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance12733.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance12784.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance12807.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance12965.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance13052.smt2                                                                          |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|instance13104.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance13140.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance13265.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance13563.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance13642.smt2                                                                          |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|instance13646.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance13655.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance13660.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance13815.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance13895.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance14110.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance14114.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance14195.smt2                                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|instance14388.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance14521.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance14667.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance14796.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance14893.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance15052.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance15077.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance15089.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance15098.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance15275.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance15301.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance15322.smt2                                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|instance15327.smt2                                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|instance15351.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance15356.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance15433.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance15458.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance15552.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance15562.smt2                                                                          |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|instance15577.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|instance15649.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance15715.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance15724.smt2                                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|instance15857.smt2                                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|instance15869.smt2                                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
</details>
