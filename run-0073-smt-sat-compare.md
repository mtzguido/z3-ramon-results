Comparing data and data


# SUMMARY
- LHS tests = 2000
- RHS tests = 2000
- LHS success = 2000  (100.0%)
- RHS success = 2000  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sat
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 289f8360f2875138132187496a407a238ac56dd7
Z3 branch: sls
Z3 options: "-T:20 -v:2 smt.sls.enable=false sat.smt=true -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" model_validate=true"
Z3 inputs: inputs/QF_BV_SAT
Z3 commit message: fix non-termination

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sat
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 289f8360f2875138132187496a407a238ac56dd7
Z3 branch: sls
Z3 options: "-T:20 -v:2 smt.sls.enable=false sat.smt=true -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" model_validate=true"
Z3 inputs: inputs/QF_BV_SAT
Z3 commit message: fix non-termination

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|111.smt2                                                                                    |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|113.smt2                                                                                    |   2.847s  |   2.847s  |   0.000s  | 0.0%|
|115.smt2                                                                                    |   3.956s  |   3.956s  |   0.000s  | 0.0%|
|15.smt2                                                                                     |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|162.smt2                                                                                    |  14.376s  |  14.376s  |   0.000s  | 0.0%|
|170.smt2                                                                                    |   7.510s  |   7.510s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|29.smt2                                                                                     |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|33.smt2                                                                                     |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  19.835s  |  19.835s  |   0.000s  | 0.0%|
|64.smt2                                                                                     |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|80.smt2                                                                                     |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|90.smt2                                                                                     |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|94.smt2                                                                                     |  19.965s  |  19.965s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|111.smt2                                                                                    |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|113.smt2                                                                                    |   2.847s  |   2.847s  |   0.000s  | 0.0%|
|115.smt2                                                                                    |   3.956s  |   3.956s  |   0.000s  | 0.0%|
|15.smt2                                                                                     |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|162.smt2                                                                                    |  14.376s  |  14.376s  |   0.000s  | 0.0%|
|170.smt2                                                                                    |   7.510s  |   7.510s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|29.smt2                                                                                     |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|33.smt2                                                                                     |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  19.835s  |  19.835s  |   0.000s  | 0.0%|
|64.smt2                                                                                     |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|80.smt2                                                                                     |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|90.smt2                                                                                     |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|94.smt2                                                                                     |  19.965s  |  19.965s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|111.smt2                                                                                    |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|113.smt2                                                                                    |   2.847s  |   2.847s  |   0.000s  | 0.0%|
|115.smt2                                                                                    |   3.956s  |   3.956s  |   0.000s  | 0.0%|
|15.smt2                                                                                     |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|162.smt2                                                                                    |  14.376s  |  14.376s  |   0.000s  | 0.0%|
|170.smt2                                                                                    |   7.510s  |   7.510s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|29.smt2                                                                                     |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|33.smt2                                                                                     |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  19.835s  |  19.835s  |   0.000s  | 0.0%|
|64.smt2                                                                                     |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|80.smt2                                                                                     |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|90.smt2                                                                                     |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|94.smt2                                                                                     |  19.965s  |  19.965s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|111.smt2                                                                                    |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|113.smt2                                                                                    |   2.847s  |   2.847s  |   0.000s  | 0.0%|
|115.smt2                                                                                    |   3.956s  |   3.956s  |   0.000s  | 0.0%|
|15.smt2                                                                                     |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|162.smt2                                                                                    |  14.376s  |  14.376s  |   0.000s  | 0.0%|
|170.smt2                                                                                    |   7.510s  |   7.510s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|29.smt2                                                                                     |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|33.smt2                                                                                     |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  19.835s  |  19.835s  |   0.000s  | 0.0%|
|64.smt2                                                                                     |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|80.smt2                                                                                     |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|90.smt2                                                                                     |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|94.smt2                                                                                     |  19.965s  |  19.965s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|bench_4724.smt2                                                                            |  20.151s |4603.0MiB|
|smulov4bw1024.smt2                                                                         |  20.147s |4760.0MiB|
|bench_7150.smt2                                                                            |  20.142s |4674.0MiB|
|bench_11357.smt2                                                                           |  20.133s |4842.0MiB|
|bench_3945.smt2                                                                            |  20.105s |4780.0MiB|
|bench_10451.smt2                                                                           |  20.104s |5152.0MiB|
|bench_8495.smt2                                                                            |  20.099s |1970.0MiB|
|bench_8564.smt2                                                                            |  20.088s |2002.0MiB|
|bench_12422.smt2                                                                           |  20.084s |1968.0MiB|
|bench_4173.smt2                                                                            |  20.077s |4846.0MiB|
|bench_13483.smt2                                                                           |  20.054s |1047.0MiB|
|bench_11931.smt2                                                                           |  20.054s |4812.0MiB|
|bench_7669.smt2                                                                            |  20.052s |616.0MiB|
|div.c.20.smt2                                                                              |  20.050s |670.0MiB|
|108.smt2                                                                                   |  20.048s |689.0MiB|
|bench_12204.smt2                                                                           |  20.039s |1975.0MiB|
|111.smt2                                                                                   |  20.038s |702.0MiB|
|bench_5944.smt2                                                                            |  20.035s |421.0MiB|
|ndist.b.27984.smt2                                                                         |  20.034s |578.0MiB|
|bench_102.smt2                                                                             |  20.032s |812.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|bench_4724.smt2                                                                            |  20.151s |4603.0MiB|
|smulov4bw1024.smt2                                                                         |  20.147s |4760.0MiB|
|bench_7150.smt2                                                                            |  20.142s |4674.0MiB|
|bench_11357.smt2                                                                           |  20.133s |4842.0MiB|
|bench_3945.smt2                                                                            |  20.105s |4780.0MiB|
|bench_10451.smt2                                                                           |  20.104s |5152.0MiB|
|bench_8495.smt2                                                                            |  20.099s |1970.0MiB|
|bench_8564.smt2                                                                            |  20.088s |2002.0MiB|
|bench_12422.smt2                                                                           |  20.084s |1968.0MiB|
|bench_4173.smt2                                                                            |  20.077s |4846.0MiB|
|bench_13483.smt2                                                                           |  20.054s |1047.0MiB|
|bench_11931.smt2                                                                           |  20.054s |4812.0MiB|
|bench_7669.smt2                                                                            |  20.052s |616.0MiB|
|div.c.20.smt2                                                                              |  20.050s |670.0MiB|
|108.smt2                                                                                   |  20.048s |689.0MiB|
|bench_12204.smt2                                                                           |  20.039s |1975.0MiB|
|111.smt2                                                                                   |  20.038s |702.0MiB|
|bench_5944.smt2                                                                            |  20.035s |421.0MiB|
|ndist.b.27984.smt2                                                                         |  20.034s |578.0MiB|
|bench_102.smt2                                                                             |  20.032s |812.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |307.0MiB|307.0MiB|0B| 0.0%|
|100.smt2                                                                                    |294.0MiB|294.0MiB|0B| 0.0%|
|102.smt2                                                                                    |396.0MiB|396.0MiB|0B| 0.0%|
|108.smt2                                                                                    |689.0MiB|689.0MiB|0B| 0.0%|
|111.smt2                                                                                    |702.0MiB|702.0MiB|0B| 0.0%|
|113.smt2                                                                                    |158.0MiB|158.0MiB|0B| 0.0%|
|115.smt2                                                                                    |326.0MiB|326.0MiB|0B| 0.0%|
|15.smt2                                                                                     |261.0MiB|261.0MiB|0B| 0.0%|
|162.smt2                                                                                    |524.0MiB|524.0MiB|0B| 0.0%|
|170.smt2                                                                                    |475.0MiB|475.0MiB|0B| 0.0%|
|20.smt2                                                                                     |345.0MiB|345.0MiB|0B| 0.0%|
|26.smt2                                                                                     |319.0MiB|319.0MiB|0B| 0.0%|
|29.smt2                                                                                     |327.0MiB|327.0MiB|0B| 0.0%|
|33.smt2                                                                                     |280.0MiB|280.0MiB|0B| 0.0%|
|41.smt2                                                                                     |239.0MiB|239.0MiB|0B| 0.0%|
|64.smt2                                                                                     |357.0MiB|357.0MiB|0B| 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |52.152MiB|52.152MiB|0B| 0.0%|
|80.smt2                                                                                     |354.0MiB|354.0MiB|0B| 0.0%|
|90.smt2                                                                                     |350.0MiB|350.0MiB|0B| 0.0%|
|94.smt2                                                                                     |359.0MiB|359.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |307.0MiB|307.0MiB|0B| 0.0%|
|100.smt2                                                                                    |294.0MiB|294.0MiB|0B| 0.0%|
|102.smt2                                                                                    |396.0MiB|396.0MiB|0B| 0.0%|
|108.smt2                                                                                    |689.0MiB|689.0MiB|0B| 0.0%|
|111.smt2                                                                                    |702.0MiB|702.0MiB|0B| 0.0%|
|113.smt2                                                                                    |158.0MiB|158.0MiB|0B| 0.0%|
|115.smt2                                                                                    |326.0MiB|326.0MiB|0B| 0.0%|
|15.smt2                                                                                     |261.0MiB|261.0MiB|0B| 0.0%|
|162.smt2                                                                                    |524.0MiB|524.0MiB|0B| 0.0%|
|170.smt2                                                                                    |475.0MiB|475.0MiB|0B| 0.0%|
|20.smt2                                                                                     |345.0MiB|345.0MiB|0B| 0.0%|
|26.smt2                                                                                     |319.0MiB|319.0MiB|0B| 0.0%|
|29.smt2                                                                                     |327.0MiB|327.0MiB|0B| 0.0%|
|33.smt2                                                                                     |280.0MiB|280.0MiB|0B| 0.0%|
|41.smt2                                                                                     |239.0MiB|239.0MiB|0B| 0.0%|
|64.smt2                                                                                     |357.0MiB|357.0MiB|0B| 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |52.152MiB|52.152MiB|0B| 0.0%|
|80.smt2                                                                                     |354.0MiB|354.0MiB|0B| 0.0%|
|90.smt2                                                                                     |350.0MiB|350.0MiB|0B| 0.0%|
|94.smt2                                                                                     |359.0MiB|359.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |307.0MiB|307.0MiB|0B| 0.0%|
|100.smt2                                                                                    |294.0MiB|294.0MiB|0B| 0.0%|
|102.smt2                                                                                    |396.0MiB|396.0MiB|0B| 0.0%|
|108.smt2                                                                                    |689.0MiB|689.0MiB|0B| 0.0%|
|111.smt2                                                                                    |702.0MiB|702.0MiB|0B| 0.0%|
|113.smt2                                                                                    |158.0MiB|158.0MiB|0B| 0.0%|
|115.smt2                                                                                    |326.0MiB|326.0MiB|0B| 0.0%|
|15.smt2                                                                                     |261.0MiB|261.0MiB|0B| 0.0%|
|162.smt2                                                                                    |524.0MiB|524.0MiB|0B| 0.0%|
|170.smt2                                                                                    |475.0MiB|475.0MiB|0B| 0.0%|
|20.smt2                                                                                     |345.0MiB|345.0MiB|0B| 0.0%|
|26.smt2                                                                                     |319.0MiB|319.0MiB|0B| 0.0%|
|29.smt2                                                                                     |327.0MiB|327.0MiB|0B| 0.0%|
|33.smt2                                                                                     |280.0MiB|280.0MiB|0B| 0.0%|
|41.smt2                                                                                     |239.0MiB|239.0MiB|0B| 0.0%|
|64.smt2                                                                                     |357.0MiB|357.0MiB|0B| 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |52.152MiB|52.152MiB|0B| 0.0%|
|80.smt2                                                                                     |354.0MiB|354.0MiB|0B| 0.0%|
|90.smt2                                                                                     |350.0MiB|350.0MiB|0B| 0.0%|
|94.smt2                                                                                     |359.0MiB|359.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |307.0MiB|307.0MiB|0B| 0.0%|
|100.smt2                                                                                    |294.0MiB|294.0MiB|0B| 0.0%|
|102.smt2                                                                                    |396.0MiB|396.0MiB|0B| 0.0%|
|108.smt2                                                                                    |689.0MiB|689.0MiB|0B| 0.0%|
|111.smt2                                                                                    |702.0MiB|702.0MiB|0B| 0.0%|
|113.smt2                                                                                    |158.0MiB|158.0MiB|0B| 0.0%|
|115.smt2                                                                                    |326.0MiB|326.0MiB|0B| 0.0%|
|15.smt2                                                                                     |261.0MiB|261.0MiB|0B| 0.0%|
|162.smt2                                                                                    |524.0MiB|524.0MiB|0B| 0.0%|
|170.smt2                                                                                    |475.0MiB|475.0MiB|0B| 0.0%|
|20.smt2                                                                                     |345.0MiB|345.0MiB|0B| 0.0%|
|26.smt2                                                                                     |319.0MiB|319.0MiB|0B| 0.0%|
|29.smt2                                                                                     |327.0MiB|327.0MiB|0B| 0.0%|
|33.smt2                                                                                     |280.0MiB|280.0MiB|0B| 0.0%|
|41.smt2                                                                                     |239.0MiB|239.0MiB|0B| 0.0%|
|64.smt2                                                                                     |357.0MiB|357.0MiB|0B| 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |52.152MiB|52.152MiB|0B| 0.0%|
|80.smt2                                                                                     |354.0MiB|354.0MiB|0B| 0.0%|
|90.smt2                                                                                     |350.0MiB|350.0MiB|0B| 0.0%|
|94.smt2                                                                                     |359.0MiB|359.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|unconstrained04.smt2                                                                       |  20.019s |6372.0MiB|
|unconstrained07.smt2                                                                       |  20.011s |6372.0MiB|
|unconstrained08.smt2                                                                       |  20.026s |6371.0MiB|
|bench_10451.smt2                                                                           |  20.104s |5152.0MiB|
|bench_4173.smt2                                                                            |  20.077s |4846.0MiB|
|bench_11357.smt2                                                                           |  20.133s |4842.0MiB|
|bench_11931.smt2                                                                           |  20.054s |4812.0MiB|
|bench_3945.smt2                                                                            |  20.105s |4780.0MiB|
|smulov4bw1024.smt2                                                                         |  20.147s |4760.0MiB|
|bench_7150.smt2                                                                            |  20.142s |4674.0MiB|
|bench_4724.smt2                                                                            |  20.151s |4603.0MiB|
|bench_8564.smt2                                                                            |  20.088s |2002.0MiB|
|bench_12204.smt2                                                                           |  20.039s |1975.0MiB|
|bench_8495.smt2                                                                            |  20.099s |1970.0MiB|
|bench_12422.smt2                                                                           |  20.084s |1968.0MiB|
|servers_slapd_a_vc149789.smt2                                                              |  20.024s |1465.0MiB|
|bench_13483.smt2                                                                           |  20.054s |1047.0MiB|
|bench_102.smt2                                                                             |  20.032s |812.0MiB|
|bench_1756.smt2                                                                            |  19.935s |791.0MiB|
|div3.c.20.smt2                                                                             |  16.789s |714.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|unconstrained04.smt2                                                                       |  20.019s |6372.0MiB|
|unconstrained07.smt2                                                                       |  20.011s |6372.0MiB|
|unconstrained08.smt2                                                                       |  20.026s |6371.0MiB|
|bench_10451.smt2                                                                           |  20.104s |5152.0MiB|
|bench_4173.smt2                                                                            |  20.077s |4846.0MiB|
|bench_11357.smt2                                                                           |  20.133s |4842.0MiB|
|bench_11931.smt2                                                                           |  20.054s |4812.0MiB|
|bench_3945.smt2                                                                            |  20.105s |4780.0MiB|
|smulov4bw1024.smt2                                                                         |  20.147s |4760.0MiB|
|bench_7150.smt2                                                                            |  20.142s |4674.0MiB|
|bench_4724.smt2                                                                            |  20.151s |4603.0MiB|
|bench_8564.smt2                                                                            |  20.088s |2002.0MiB|
|bench_12204.smt2                                                                           |  20.039s |1975.0MiB|
|bench_8495.smt2                                                                            |  20.099s |1970.0MiB|
|bench_12422.smt2                                                                           |  20.084s |1968.0MiB|
|servers_slapd_a_vc149789.smt2                                                              |  20.024s |1465.0MiB|
|bench_13483.smt2                                                                           |  20.054s |1047.0MiB|
|bench_102.smt2                                                                             |  20.032s |812.0MiB|
|bench_1756.smt2                                                                            |  19.935s |791.0MiB|
|div3.c.20.smt2                                                                             |  16.789s |714.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|111.smt2                                                                                    |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|113.smt2                                                                                    |   2.847s  |   2.847s  |   0.000s  | 0.0%|
|115.smt2                                                                                    |   3.956s  |   3.956s  |   0.000s  | 0.0%|
|15.smt2                                                                                     |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|162.smt2                                                                                    |  14.376s  |  14.376s  |   0.000s  | 0.0%|
|170.smt2                                                                                    |   7.510s  |   7.510s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|29.smt2                                                                                     |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|33.smt2                                                                                     |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  19.835s  |  19.835s  |   0.000s  | 0.0%|
|64.smt2                                                                                     |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|80.smt2                                                                                     |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|90.smt2                                                                                     |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|94.smt2                                                                                     |  19.965s  |  19.965s  |   0.000s  | 0.0%|
|98.smt2                                                                                     |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|Example_16.txt.smt2                                                                         |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|Example_17.txt.smt2                                                                         |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|Example_9.txt.smt2                                                                          |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_cyclic_scheduler.2.prop1_cc_ref_max.smt2                                       |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_cyclic_scheduler.4.prop1_cc_ref_max.smt2                                       |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_schedule_world.1.prop1_cc_ref_max.smt2                                         |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_swap_three_cc_ref_max.smt2                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_cyclic_scheduler.2.prop1_cc_ref_max.smt2                                        |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_eq_sdp_v4_cc_ref_max.smt2                                                       |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_resistance.2.prop1_cc_ref_max.smt2                                              |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_swap_two_cc_ref_max.smt2                                                        |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_synabs_cc_ref_max.smt2                                                          |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_BV_counter_v_cc_ref_max.smt2                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_BV_eq_sdp_v5_cc_ref_max.smt2                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|QF_BV_protocols.1.prop1_cc_ref_max.smt2                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_BV_v_Unidec_cc_ref_max.smt2                                                              |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|Sz512_15128_0.smt2                                                                          |  19.979s  |  19.979s  |   0.000s  | 0.0%|
|Sz512_15128_1.smt2                                                                          |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|Sz512_15128_2.smt2                                                                          |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|Sz512_15128_3.smt2                                                                          |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|VS3-benchmark-S1.smt2                                                                       |  20.015s  |  20.015s  |   0.000s  | 0.0%|
|a128test0016.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a164test0005.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|a167test0001.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a185test0001.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a208test0005.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a213test0012.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a214test0017.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a217test0011.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a218test0003.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a222test0008.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a324test0010.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a330test0007.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a331test0008.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|a333test0009.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a335test0041.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a392test0051.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a393test0014.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a397test0029.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a402test0032.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|a406test0030.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a407test0024.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a409test0002.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a421test0007.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a423test0008.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a430test0028.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|a434test0027.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a448test0003.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|a479test0010.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|a494test0007.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|a497test0020.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|a503test0089.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a55test0003.smt2                                                                            |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|a58test0007.smt2                                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a600test0040.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a601test0056.smt2                                                                           |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|a603test0055.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|a605test0062.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|a60test0004.smt2                                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a611test0014.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a613test0087.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|a614test0091.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a616test0001.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a620test0100.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a623test0035.smt2                                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|a625test0095.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a628test0066.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|a631test0073.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a640test0019.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a649test0047.smt2                                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|a653test0023.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a657test0107.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a658test0026.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a663test0096.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a664test0013.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a665test0064.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|a668test0098.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|a669test0063.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|a674test0008.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a676test0004.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|a681test0048.smt2                                                                           |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|a683test0094.smt2                                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|a685test0080.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a689test0069.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|a695test0015.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|a97test0001.smt2                                                                            |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|adpcm.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|b188test0002.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|b265test0001.smt2                                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|b26test0001.smt2                                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1.smt2                                                                                |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|bench_10033.smt2                                                                            |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|bench_10096.smt2                                                                            |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|bench_10111.smt2                                                                            |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|bench_1012.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_10127.smt2                                                                            |   1.056s  |   1.056s  |   0.000s  | 0.0%|
|bench_1013.smt2                                                                             |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|bench_10144.smt2                                                                            |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|bench_1017.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_102.smt2                                                                              |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|bench_10228.smt2                                                                            |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|bench_10306.smt2                                                                            |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|bench_1041.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_1043.smt2                                                                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|bench_10451.smt2                                                                            |  20.104s  |  20.104s  |   0.000s  | 0.0%|
|bench_1050.smt2                                                                             |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|bench_1053.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_1055.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_10579.smt2                                                                            |   4.549s  |   4.549s  |   0.000s  | 0.0%|
|bench_1059.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1063.smt2                                                                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_10696.smt2                                                                            |   4.180s  |   4.180s  |   0.000s  | 0.0%|
|bench_10714.smt2                                                                            |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|bench_10726.smt2                                                                            |   5.369s  |   5.369s  |   0.000s  | 0.0%|
|bench_10737.smt2                                                                            |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|bench_10784.smt2                                                                            |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|bench_10791.smt2                                                                            |  19.964s  |  19.964s  |   0.000s  | 0.0%|
|bench_10800.smt2                                                                            |   1.603s  |   1.603s  |   0.000s  | 0.0%|
|bench_1081.smt2                                                                             |  19.983s  |  19.983s  |   0.000s  | 0.0%|
|bench_10815.smt2                                                                            |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|bench_1082.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_10832.smt2                                                                            |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|bench_10841.smt2                                                                            |   4.884s  |   4.884s  |   0.000s  | 0.0%|
|bench_1088.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_1093.smt2                                                                             |  15.467s  |  15.467s  |   0.000s  | 0.0%|
|bench_1094.smt2                                                                             |   0.347s  |   0.347s  |   0.000s  | 0.0%|
|bench_10940.smt2                                                                            |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|bench_1099.smt2                                                                             |  19.969s  |  19.969s  |   0.000s  | 0.0%|
|bench_11014.smt2                                                                            |   8.414s  |   8.414s  |   0.000s  | 0.0%|
|bench_11027.smt2                                                                            |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|bench_11032.smt2                                                                            |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|bench_11033.smt2                                                                            |   2.040s  |   2.040s  |   0.000s  | 0.0%|
|bench_1106.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_1111.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_11110.smt2                                                                            |   3.538s  |   3.538s  |   0.000s  | 0.0%|
|bench_1113.smt2                                                                             |  19.961s  |  19.961s  |   0.000s  | 0.0%|
|bench_11151.smt2                                                                            |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|bench_112.smt2                                                                              |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_1123.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_11232.smt2                                                                            |   3.689s  |   3.689s  |   0.000s  | 0.0%|
|bench_113.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_11341.smt2                                                                            |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|bench_11357.smt2                                                                            |  20.133s  |  20.133s  |   0.000s  | 0.0%|
|bench_1136.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_11408.smt2                                                                            |   5.826s  |   5.826s  |   0.000s  | 0.0%|
|bench_1143.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1145.smt2                                                                             |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|bench_11473.smt2                                                                            |   4.551s  |   4.551s  |   0.000s  | 0.0%|
|bench_1159.smt2                                                                             |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|bench_1166.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|bench_1168.smt2                                                                             |  19.968s  |  19.968s  |   0.000s  | 0.0%|
|bench_11696.smt2                                                                            |   9.258s  |   9.258s  |   0.000s  | 0.0%|
|bench_11708.smt2                                                                            |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|bench_11736.smt2                                                                            |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|bench_1179.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_1180.smt2                                                                             |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|bench_11811.smt2                                                                            |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|bench_11826.smt2                                                                            |   4.855s  |   4.855s  |   0.000s  | 0.0%|
|bench_1184.smt2                                                                             |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|bench_1187.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_119.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_11931.smt2                                                                            |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|bench_1196.smt2                                                                             |  19.929s  |  19.929s  |   0.000s  | 0.0%|
|bench_11971.smt2                                                                            |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|bench_1199.smt2                                                                             |   0.581s  |   0.581s  |   0.000s  | 0.0%|
|bench_120.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_12006.smt2                                                                            |   4.407s  |   4.407s  |   0.000s  | 0.0%|
|bench_1201.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1202.smt2                                                                             |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|bench_1204.smt2                                                                             |  19.104s  |  19.104s  |   0.000s  | 0.0%|
|bench_12059.smt2                                                                            |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|bench_12158.smt2                                                                            |  19.957s  |  19.957s  |   0.000s  | 0.0%|
|bench_1218.smt2                                                                             |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|bench_12204.smt2                                                                            |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|bench_1222.smt2                                                                             |   8.609s  |   8.609s  |   0.000s  | 0.0%|
|bench_12224.smt2                                                                            |   6.720s  |   6.720s  |   0.000s  | 0.0%|
|bench_12246.smt2                                                                            |   4.958s  |   4.958s  |   0.000s  | 0.0%|
|bench_1228.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_1229.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_1233.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1235.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_1236.smt2                                                                             |   2.426s  |   2.426s  |   0.000s  | 0.0%|
|bench_12422.smt2                                                                            |  20.084s  |  20.084s  |   0.000s  | 0.0%|
|bench_12473.smt2                                                                            |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|bench_1249.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_1250.smt2                                                                             |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|bench_1252.smt2                                                                             |  19.974s  |  19.974s  |   0.000s  | 0.0%|
|bench_1253.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_1256.smt2                                                                             |  19.937s  |  19.937s  |   0.000s  | 0.0%|
|bench_12625.smt2                                                                            |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|bench_12655.smt2                                                                            |  19.971s  |  19.971s  |   0.000s  | 0.0%|
|bench_1266.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_1270.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_1278.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_1280.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_12821.smt2                                                                            |   1.491s  |   1.491s  |   0.000s  | 0.0%|
|bench_1283.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1285.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1286.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|bench_129.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_1306.smt2                                                                             |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|bench_1307.smt2                                                                             |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bench_13129.smt2                                                                            |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|bench_13147.smt2                                                                            |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|bench_1318.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_1323.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|bench_13284.smt2                                                                            |   0.858s  |   0.858s  |   0.000s  | 0.0%|
|bench_1329.smt2                                                                             |   6.773s  |   6.773s  |   0.000s  | 0.0%|
|bench_1332.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_13336.smt2                                                                            |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|bench_1335.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_1336.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_1338.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_13483.smt2                                                                            |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|bench_1349.smt2                                                                             |   8.392s  |   8.392s  |   0.000s  | 0.0%|
|bench_135.smt2                                                                              |   0.743s  |   0.743s  |   0.000s  | 0.0%|
|bench_1350.smt2                                                                             |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|bench_1355.smt2                                                                             |  20.009s  |  20.009s  |   0.000s  | 0.0%|
|bench_1359.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_1361.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_1365.smt2                                                                             |  19.933s  |  19.933s  |   0.000s  | 0.0%|
|bench_1367.smt2                                                                             |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|bench_1374.smt2                                                                             |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|bench_13744.smt2                                                                            |   8.504s  |   8.504s  |   0.000s  | 0.0%|
|bench_13773.smt2                                                                            |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|bench_1379.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_13790.smt2                                                                            |   5.703s  |   5.703s  |   0.000s  | 0.0%|
|bench_1386.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1388.smt2                                                                             |  19.961s  |  19.961s  |   0.000s  | 0.0%|
|bench_1389.smt2                                                                             |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|bench_1391.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1400.smt2                                                                             |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|bench_1401.smt2                                                                             |   0.290s  |   0.290s  |   0.000s  | 0.0%|
|bench_1405.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_141.smt2                                                                              |   0.658s  |   0.658s  |   0.000s  | 0.0%|
|bench_1412.smt2                                                                             |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|bench_1414.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_14156.smt2                                                                            |   3.682s  |   3.682s  |   0.000s  | 0.0%|
|bench_14161.smt2                                                                            |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|bench_14165.smt2                                                                            |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|bench_1417.smt2                                                                             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|bench_142.smt2                                                                              |   0.904s  |   0.904s  |   0.000s  | 0.0%|
|bench_14209.smt2                                                                            |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|bench_1424.smt2                                                                             |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|bench_14284.smt2                                                                            |   4.068s  |   4.068s  |   0.000s  | 0.0%|
|bench_143.smt2                                                                              |   1.620s  |   1.620s  |   0.000s  | 0.0%|
|bench_1434.smt2                                                                             |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|bench_14358.smt2                                                                            |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|bench_1440.smt2                                                                             |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|bench_1441.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_1442.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1445.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1446.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_14461.smt2                                                                            |   5.997s  |   5.997s  |   0.000s  | 0.0%|
|bench_1447.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|bench_14486.smt2                                                                            |   8.592s  |   8.592s  |   0.000s  | 0.0%|
|bench_145.smt2                                                                              |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|bench_1453.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1455.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_14595.smt2                                                                            |  15.091s  |  15.091s  |   0.000s  | 0.0%|
|bench_14598.smt2                                                                            |   6.377s  |   6.377s  |   0.000s  | 0.0%|
|bench_1465.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_1467.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_1470.smt2                                                                             |   0.790s  |   0.790s  |   0.000s  | 0.0%|
|bench_14720.smt2                                                                            |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|bench_1476.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_1477.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_1478.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_1481.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_14817.smt2                                                                            |   2.200s  |   2.200s  |   0.000s  | 0.0%|
|bench_14861.smt2                                                                            |  20.009s  |  20.009s  |   0.000s  | 0.0%|
|bench_14875.smt2                                                                            |   4.196s  |   4.196s  |   0.000s  | 0.0%|
|bench_14885.smt2                                                                            |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|bench_14932.smt2                                                                            |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|bench_14941.smt2                                                                            |  14.128s  |  14.128s  |   0.000s  | 0.0%|
|bench_1495.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_1496.smt2                                                                             |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|bench_1498.smt2                                                                             |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|bench_14984.smt2                                                                            |   6.804s  |   6.804s  |   0.000s  | 0.0%|
|bench_15.smt2                                                                               |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1504.smt2                                                                             |   5.910s  |   5.910s  |   0.000s  | 0.0%|
|bench_15105.smt2                                                                            |   2.857s  |   2.857s  |   0.000s  | 0.0%|
|bench_15128.smt2                                                                            |   7.042s  |   7.042s  |   0.000s  | 0.0%|
|bench_1522.smt2                                                                             |  19.539s  |  19.539s  |   0.000s  | 0.0%|
|bench_1523.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|bench_15255.smt2                                                                            |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|bench_1532.smt2                                                                             |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|bench_15365.smt2                                                                            |   4.363s  |   4.363s  |   0.000s  | 0.0%|
|bench_154.smt2                                                                              |  19.959s  |  19.959s  |   0.000s  | 0.0%|
|bench_1545.smt2                                                                             |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|bench_1549.smt2                                                                             |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|bench_15547.smt2                                                                            |  19.875s  |  19.875s  |   0.000s  | 0.0%|
|bench_1555.smt2                                                                             |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|bench_1559.smt2                                                                             |   7.778s  |   7.778s  |   0.000s  | 0.0%|
|bench_1560.smt2                                                                             |  19.967s  |  19.967s  |   0.000s  | 0.0%|
|bench_1567.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|bench_1568.smt2                                                                             |   0.358s  |   0.358s  |   0.000s  | 0.0%|
|bench_15711.smt2                                                                            |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|bench_15719.smt2                                                                            |  11.808s  |  11.808s  |   0.000s  | 0.0%|
|bench_1573.smt2                                                                             |   0.918s  |   0.918s  |   0.000s  | 0.0%|
|bench_1578.smt2                                                                             |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|bench_15783.smt2                                                                            |  11.773s  |  11.773s  |   0.000s  | 0.0%|
|bench_1583.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_15833.smt2                                                                            |   7.979s  |   7.979s  |   0.000s  | 0.0%|
|bench_1585.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|bench_1586.smt2                                                                             |  19.945s  |  19.945s  |   0.000s  | 0.0%|
|bench_1588.smt2                                                                             |   1.018s  |   1.018s  |   0.000s  | 0.0%|
|bench_160.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1603.smt2                                                                             |   1.043s  |   1.043s  |   0.000s  | 0.0%|
|bench_16064.smt2                                                                            |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|bench_1608.smt2                                                                             |  20.009s  |  20.009s  |   0.000s  | 0.0%|
|bench_1610.smt2                                                                             |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|bench_1614.smt2                                                                             |  19.967s  |  19.967s  |   0.000s  | 0.0%|
|bench_1621.smt2                                                                             |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|bench_16245.smt2                                                                            |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|bench_1627.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1629.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_163.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1630.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1636.smt2                                                                             |   1.175s  |   1.175s  |   0.000s  | 0.0%|
|bench_16382.smt2                                                                            |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|bench_16409.smt2                                                                            |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|bench_1643.smt2                                                                             |  20.015s  |  20.015s  |   0.000s  | 0.0%|
|bench_16467.smt2                                                                            |   7.043s  |   7.043s  |   0.000s  | 0.0%|
|bench_165.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1652.smt2                                                                             |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|bench_1657.smt2                                                                             |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|bench_16594.smt2                                                                            |   3.512s  |   3.512s  |   0.000s  | 0.0%|
|bench_166.smt2                                                                              |   1.026s  |   1.026s  |   0.000s  | 0.0%|
|bench_1663.smt2                                                                             |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|bench_16640.smt2                                                                            |   6.683s  |   6.683s  |   0.000s  | 0.0%|
|bench_1665.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_1670.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_16707.smt2                                                                            |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|bench_1674.smt2                                                                             |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench_168.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1680.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_1686.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_16862.smt2                                                                            |  19.959s  |  19.959s  |   0.000s  | 0.0%|
|bench_1697.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_17033.smt2                                                                            |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|bench_1707.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_17082.smt2                                                                            |   7.933s  |   7.933s  |   0.000s  | 0.0%|
|bench_171.smt2                                                                              |   0.772s  |   0.772s  |   0.000s  | 0.0%|
|bench_1710.smt2                                                                             |  19.946s  |  19.946s  |   0.000s  | 0.0%|
|bench_1712.smt2                                                                             |  13.980s  |  13.980s  |   0.000s  | 0.0%|
|bench_1717.smt2                                                                             |  14.491s  |  14.491s  |   0.000s  | 0.0%|
|bench_1720.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1721.smt2                                                                             |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|bench_1724.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|bench_17324.smt2                                                                            |   0.945s  |   0.945s  |   0.000s  | 0.0%|
|bench_17335.smt2                                                                            |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|bench_1739.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1748.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1756.smt2                                                                             |  19.935s  |  19.935s  |   0.000s  | 0.0%|
|bench_1757.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_1759.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1760.smt2                                                                             |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|bench_1761.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_1763.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1769.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_1770.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_17759.smt2                                                                            |   6.094s  |   6.094s  |   0.000s  | 0.0%|
|bench_1778.smt2                                                                             |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|bench_179.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1802.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1810.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|bench_1811.smt2                                                                             |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|bench_1816.smt2                                                                             |   2.621s  |   2.621s  |   0.000s  | 0.0%|
|bench_1822.smt2                                                                             |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|bench_1829.smt2                                                                             |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|bench_183.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_1837.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|bench_1839.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|bench_1841.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|bench_1844.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|bench_1851.smt2                                                                             |  19.907s  |  19.907s  |   0.000s  | 0.0%|
|bench_1858.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1863.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1864.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1869.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_187.smt2                                                                              |  19.939s  |  19.939s  |   0.000s  | 0.0%|
|bench_1872.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|bench_1873.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_1878.smt2                                                                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_1880.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_1882.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1888.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_1897.smt2                                                                             |  19.953s  |  19.953s  |   0.000s  | 0.0%|
|bench_1900.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1904.smt2                                                                             |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|bench_1905.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_1907.smt2                                                                             |  18.994s  |  18.994s  |   0.000s  | 0.0%|
|bench_1909.smt2                                                                             |  18.384s  |  18.384s  |   0.000s  | 0.0%|
|bench_1937.smt2                                                                             |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|bench_1942.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1946.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1953.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1957.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1958.smt2                                                                             |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|bench_1961.smt2                                                                             |   0.309s  |   0.309s  |   0.000s  | 0.0%|
|bench_1963.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1976.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1977.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|bench_1981.smt2                                                                             |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|bench_1985.smt2                                                                             |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|bench_1992.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|bench_1993.smt2                                                                             |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|bench_1996.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_200.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2021.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_2022.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|bench_2034.smt2                                                                             |  16.354s  |  16.354s  |   0.000s  | 0.0%|
|bench_204.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2044.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2050.smt2                                                                             |  19.934s  |  19.934s  |   0.000s  | 0.0%|
|bench_2059.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|bench_2067.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2070.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2072.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2075.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2076.smt2                                                                             |  19.950s  |  19.950s  |   0.000s  | 0.0%|
|bench_2077.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_208.smt2                                                                              |   1.447s  |   1.447s  |   0.000s  | 0.0%|
|bench_2083.smt2                                                                             |  19.922s  |  19.922s  |   0.000s  | 0.0%|
|bench_2097.smt2                                                                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|bench_2099.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2102.smt2                                                                             |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|bench_2108.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2113.smt2                                                                             |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|bench_2115.smt2                                                                             |  19.913s  |  19.913s  |   0.000s  | 0.0%|
|bench_2117.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2121.smt2                                                                             |  19.958s  |  19.958s  |   0.000s  | 0.0%|
|bench_2122.smt2                                                                             |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench_2129.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_214.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2141.smt2                                                                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_2144.smt2                                                                             |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|bench_2148.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2149.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2150.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2152.smt2                                                                             |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|bench_2155.smt2                                                                             |   4.656s  |   4.656s  |   0.000s  | 0.0%|
|bench_2161.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|bench_2162.smt2                                                                             |   6.810s  |   6.810s  |   0.000s  | 0.0%|
|bench_2167.smt2                                                                             |  10.353s  |  10.353s  |   0.000s  | 0.0%|
|bench_2169.smt2                                                                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_2170.smt2                                                                             |   0.682s  |   0.682s  |   0.000s  | 0.0%|
|bench_2174.smt2                                                                             |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|bench_2175.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2183.smt2                                                                             |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|bench_2188.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2189.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2192.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2197.smt2                                                                             |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|bench_2202.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_2207.smt2                                                                             |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|bench_2211.smt2                                                                             |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|bench_2221.smt2                                                                             |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|bench_2225.smt2                                                                             |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|bench_2229.smt2                                                                             |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|bench_2233.smt2                                                                             |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench_224.smt2                                                                              |   2.435s  |   2.435s  |   0.000s  | 0.0%|
|bench_2248.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|bench_225.smt2                                                                              |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_2257.smt2                                                                             |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|bench_2258.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|bench_2261.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2263.smt2                                                                             |  19.962s  |  19.962s  |   0.000s  | 0.0%|
|bench_2264.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2265.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_2268.smt2                                                                             |  13.984s  |  13.984s  |   0.000s  | 0.0%|
|bench_2269.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_2272.smt2                                                                             |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bench_2278.smt2                                                                             |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|bench_228.smt2                                                                              |   2.216s  |   2.216s  |   0.000s  | 0.0%|
|bench_2284.smt2                                                                             |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|bench_2291.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2293.smt2                                                                             |   0.301s  |   0.301s  |   0.000s  | 0.0%|
|bench_2295.smt2                                                                             |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|bench_230.smt2                                                                              |   1.306s  |   1.306s  |   0.000s  | 0.0%|
|bench_2304.smt2                                                                             |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|bench_2308.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2309.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2312.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_232.smt2                                                                              |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|bench_2325.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|bench_2326.smt2                                                                             |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|bench_2327.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2330.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|bench_234.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2349.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_2351.smt2                                                                             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|bench_2358.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2360.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|bench_238.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_2380.smt2                                                                             |   9.758s  |   9.758s  |   0.000s  | 0.0%|
|bench_2384.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2386.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2395.smt2                                                                             |   5.507s  |   5.507s  |   0.000s  | 0.0%|
|bench_2397.smt2                                                                             |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|bench_2400.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2406.smt2                                                                             |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|bench_2407.smt2                                                                             |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|bench_2420.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2425.smt2                                                                             |  19.985s  |  19.985s  |   0.000s  | 0.0%|
|bench_2428.smt2                                                                             |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|bench_243.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2431.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2432.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2433.smt2                                                                             |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|bench_2435.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2436.smt2                                                                             |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|bench_2443.smt2                                                                             |   6.873s  |   6.873s  |   0.000s  | 0.0%|
|bench_2463.smt2                                                                             |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|bench_2469.smt2                                                                             |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|bench_247.smt2                                                                              |   1.120s  |   1.120s  |   0.000s  | 0.0%|
|bench_2475.smt2                                                                             |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|bench_248.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_2493.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_2499.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2503.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_2507.smt2                                                                             |   0.994s  |   0.994s  |   0.000s  | 0.0%|
|bench_2514.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_2517.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2521.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2524.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_253.smt2                                                                              |   1.345s  |   1.345s  |   0.000s  | 0.0%|
|bench_2547.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|bench_2548.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2550.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_2551.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2552.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2558.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2566.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_2567.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_2573.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_2574.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_2579.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_2580.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_2582.smt2                                                                             |   2.805s  |   2.805s  |   0.000s  | 0.0%|
|bench_2586.smt2                                                                             |   5.182s  |   5.182s  |   0.000s  | 0.0%|
|bench_259.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2594.smt2                                                                             |  19.952s  |  19.952s  |   0.000s  | 0.0%|
|bench_2599.smt2                                                                             |  19.974s  |  19.974s  |   0.000s  | 0.0%|
|bench_2602.smt2                                                                             |   2.722s  |   2.722s  |   0.000s  | 0.0%|
|bench_2606.smt2                                                                             |   6.064s  |   6.064s  |   0.000s  | 0.0%|
|bench_261.smt2                                                                              |   0.704s  |   0.704s  |   0.000s  | 0.0%|
|bench_2612.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2613.smt2                                                                             |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|bench_2620.smt2                                                                             |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bench_2621.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|bench_2628.smt2                                                                             |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|bench_2629.smt2                                                                             |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|bench_2635.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_2639.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_2642.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2644.smt2                                                                             |  19.968s  |  19.968s  |   0.000s  | 0.0%|
|bench_2645.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2646.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_2650.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2653.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|bench_2659.smt2                                                                             |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|bench_267.smt2                                                                              |   1.470s  |   1.470s  |   0.000s  | 0.0%|
|bench_2671.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_2675.smt2                                                                             |   1.501s  |   1.501s  |   0.000s  | 0.0%|
|bench_2676.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2682.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|bench_2688.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_270.smt2                                                                              |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_2701.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2704.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2710.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2717.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2724.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_2727.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2729.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2735.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_2737.smt2                                                                             |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|bench_2747.smt2                                                                             |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|bench_2750.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2755.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2757.smt2                                                                             |  19.924s  |  19.924s  |   0.000s  | 0.0%|
|bench_276.smt2                                                                              |   4.029s  |   4.029s  |   0.000s  | 0.0%|
|bench_2767.smt2                                                                             |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|bench_2773.smt2                                                                             |   5.196s  |   5.196s  |   0.000s  | 0.0%|
|bench_2779.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2789.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_279.smt2                                                                              |   1.037s  |   1.037s  |   0.000s  | 0.0%|
|bench_2798.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_28.smt2                                                                               |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_281.smt2                                                                              |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_2811.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2817.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|bench_2826.smt2                                                                             |  17.670s  |  17.670s  |   0.000s  | 0.0%|
|bench_2831.smt2                                                                             |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|bench_2832.smt2                                                                             |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|bench_2839.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_2841.smt2                                                                             |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|bench_2842.smt2                                                                             |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|bench_2844.smt2                                                                             |   6.281s  |   6.281s  |   0.000s  | 0.0%|
|bench_2846.smt2                                                                             |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|bench_2849.smt2                                                                             |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|bench_285.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2855.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_2858.smt2                                                                             |  19.975s  |  19.975s  |   0.000s  | 0.0%|
|bench_2864.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2866.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2867.smt2                                                                             |  14.362s  |  14.362s  |   0.000s  | 0.0%|
|bench_2868.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|bench_2875.smt2                                                                             |  19.953s  |  19.953s  |   0.000s  | 0.0%|
|bench_2876.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_288.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2880.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_2897.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_29.smt2                                                                               |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|bench_290.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2915.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|bench_2917.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_2931.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_295.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2957.smt2                                                                             |   1.482s  |   1.482s  |   0.000s  | 0.0%|
|bench_296.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_2961.smt2                                                                             |   1.569s  |   1.569s  |   0.000s  | 0.0%|
|bench_2962.smt2                                                                             |   3.759s  |   3.759s  |   0.000s  | 0.0%|
|bench_2965.smt2                                                                             |   1.490s  |   1.490s  |   0.000s  | 0.0%|
|bench_2974.smt2                                                                             |   1.592s  |   1.592s  |   0.000s  | 0.0%|
|bench_2983.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_299.smt2                                                                              |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_2992.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|bench_2994.smt2                                                                             |   1.318s  |   1.318s  |   0.000s  | 0.0%|
|bench_2995.smt2                                                                             |   1.147s  |   1.147s  |   0.000s  | 0.0%|
|bench_301.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3010.smt2                                                                             |  19.926s  |  19.926s  |   0.000s  | 0.0%|
|bench_3011.smt2                                                                             |   1.378s  |   1.378s  |   0.000s  | 0.0%|
|bench_3015.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|bench_3018.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3019.smt2                                                                             |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|bench_302.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_303.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3031.smt2                                                                             |   1.370s  |   1.370s  |   0.000s  | 0.0%|
|bench_3032.smt2                                                                             |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|bench_3041.smt2                                                                             |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|bench_3048.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3058.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_306.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3062.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3065.smt2                                                                             |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|bench_3068.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_3080.smt2                                                                             |  19.940s  |  19.940s  |   0.000s  | 0.0%|
|bench_3082.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|bench_3087.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3091.smt2                                                                             |   1.030s  |   1.030s  |   0.000s  | 0.0%|
|bench_3093.smt2                                                                             |   1.168s  |   1.168s  |   0.000s  | 0.0%|
|bench_3094.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_3099.smt2                                                                             |   0.986s  |   0.986s  |   0.000s  | 0.0%|
|bench_3103.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3105.smt2                                                                             |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|bench_3111.smt2                                                                             |   6.213s  |   6.213s  |   0.000s  | 0.0%|
|bench_3113.smt2                                                                             |  14.926s  |  14.926s  |   0.000s  | 0.0%|
|bench_3114.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_3121.smt2                                                                             |   0.781s  |   0.781s  |   0.000s  | 0.0%|
|bench_313.smt2                                                                              |   3.915s  |   3.915s  |   0.000s  | 0.0%|
|bench_3145.smt2                                                                             |  19.967s  |  19.967s  |   0.000s  | 0.0%|
|bench_3156.smt2                                                                             |   0.871s  |   0.871s  |   0.000s  | 0.0%|
|bench_3159.smt2                                                                             |  19.976s  |  19.976s  |   0.000s  | 0.0%|
|bench_3168.smt2                                                                             |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|bench_3169.smt2                                                                             |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|bench_317.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3171.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|bench_3173.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|bench_3174.smt2                                                                             |  19.969s  |  19.969s  |   0.000s  | 0.0%|
|bench_3177.smt2                                                                             |  13.607s  |  13.607s  |   0.000s  | 0.0%|
|bench_3181.smt2                                                                             |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|bench_3182.smt2                                                                             |   6.220s  |   6.220s  |   0.000s  | 0.0%|
|bench_3191.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_3194.smt2                                                                             |  19.951s  |  19.951s  |   0.000s  | 0.0%|
|bench_3196.smt2                                                                             |   0.933s  |   0.933s  |   0.000s  | 0.0%|
|bench_3206.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3207.smt2                                                                             |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|bench_3209.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|bench_3218.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|bench_3221.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|bench_3223.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_323.smt2                                                                              |   5.124s  |   5.124s  |   0.000s  | 0.0%|
|bench_3239.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_3240.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|bench_3246.smt2                                                                             |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|bench_325.smt2                                                                              |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_3263.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_3266.smt2                                                                             |  19.960s  |  19.960s  |   0.000s  | 0.0%|
|bench_3268.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3275.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3279.smt2                                                                             |   1.273s  |   1.273s  |   0.000s  | 0.0%|
|bench_3295.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3297.smt2                                                                             |  19.880s  |  19.880s  |   0.000s  | 0.0%|
|bench_3307.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3308.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3311.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_3317.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_3320.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_3326.smt2                                                                             |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|bench_3329.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_3333.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3335.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3338.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3339.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_334.smt2                                                                              |   5.559s  |   5.559s  |   0.000s  | 0.0%|
|bench_335.smt2                                                                              |   0.351s  |   0.351s  |   0.000s  | 0.0%|
|bench_3351.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|bench_3352.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3358.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3360.smt2                                                                             |   1.179s  |   1.179s  |   0.000s  | 0.0%|
|bench_3367.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_3379.smt2                                                                             |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|bench_3394.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3411.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_3415.smt2                                                                             |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bench_3416.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3420.smt2                                                                             |   1.112s  |   1.112s  |   0.000s  | 0.0%|
|bench_3421.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3431.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3434.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_3437.smt2                                                                             |  19.971s  |  19.971s  |   0.000s  | 0.0%|
|bench_3446.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_3451.smt2                                                                             |  19.988s  |  19.988s  |   0.000s  | 0.0%|
|bench_3460.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_3461.smt2                                                                             |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|bench_3465.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_3469.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_347.smt2                                                                              |   0.685s  |   0.685s  |   0.000s  | 0.0%|
|bench_3475.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3476.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_348.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_3484.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3485.smt2                                                                             |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|bench_3489.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3499.smt2                                                                             |  19.957s  |  19.957s  |   0.000s  | 0.0%|
|bench_3500.smt2                                                                             |   2.294s  |   2.294s  |   0.000s  | 0.0%|
|bench_3502.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|bench_3509.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3516.smt2                                                                             |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|bench_3521.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|bench_3522.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_3524.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_353.smt2                                                                              |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|bench_3538.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_3539.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3541.smt2                                                                             |   1.031s  |   1.031s  |   0.000s  | 0.0%|
|bench_3548.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3551.smt2                                                                             |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|bench_3557.smt2                                                                             |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|bench_3558.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3561.smt2                                                                             |  19.972s  |  19.972s  |   0.000s  | 0.0%|
|bench_3575.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|bench_3578.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3587.smt2                                                                             |   0.936s  |   0.936s  |   0.000s  | 0.0%|
|bench_3588.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|bench_3598.smt2                                                                             |   0.382s  |   0.382s  |   0.000s  | 0.0%|
|bench_36.smt2                                                                               |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bench_360.smt2                                                                              |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bench_3603.smt2                                                                             |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|bench_3623.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3636.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3637.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_3642.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_365.smt2                                                                              |   1.240s  |   1.240s  |   0.000s  | 0.0%|
|bench_366.smt2                                                                              |   0.868s  |   0.868s  |   0.000s  | 0.0%|
|bench_3671.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3672.smt2                                                                             |   0.300s  |   0.300s  |   0.000s  | 0.0%|
|bench_3675.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_368.smt2                                                                              |   1.285s  |   1.285s  |   0.000s  | 0.0%|
|bench_3681.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3688.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_3689.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_369.smt2                                                                              |   1.103s  |   1.103s  |   0.000s  | 0.0%|
|bench_3697.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_3699.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_3707.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3715.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3716.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|bench_3719.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_372.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3721.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_3739.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_375.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3750.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3754.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3755.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3757.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3765.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3787.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_3788.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_3789.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_379.smt2                                                                              |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_3794.smt2                                                                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_3795.smt2                                                                             |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|bench_3799.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_3813.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_3815.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_3818.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_3819.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_3832.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_3834.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_3838.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_3846.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_3847.smt2                                                                             |   5.860s  |   5.860s  |   0.000s  | 0.0%|
|bench_385.smt2                                                                              |   0.981s  |   0.981s  |   0.000s  | 0.0%|
|bench_3866.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_387.smt2                                                                              |   1.020s  |   1.020s  |   0.000s  | 0.0%|
|bench_3879.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_388.smt2                                                                              |   1.223s  |   1.223s  |   0.000s  | 0.0%|
|bench_3881.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3882.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3885.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_3886.smt2                                                                             |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|bench_3888.smt2                                                                             |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|bench_3890.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_3894.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_390.smt2                                                                              |   1.139s  |   1.139s  |   0.000s  | 0.0%|
|bench_3906.smt2                                                                             |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|bench_3915.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3926.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3936.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3937.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_3943.smt2                                                                             |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|bench_3945.smt2                                                                             |  20.105s  |  20.105s  |   0.000s  | 0.0%|
|bench_3951.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3953.smt2                                                                             |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|bench_3963.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3964.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_3968.smt2                                                                             |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|bench_3992.smt2                                                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|bench_3995.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_3997.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4007.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4010.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4015.smt2                                                                             |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|bench_4019.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_402.smt2                                                                              |   0.838s  |   0.838s  |   0.000s  | 0.0%|
|bench_4021.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4023.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4031.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_4037.smt2                                                                             |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|bench_404.smt2                                                                              |   0.851s  |   0.851s  |   0.000s  | 0.0%|
|bench_4040.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_4046.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4051.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_4058.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4065.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4069.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4097.smt2                                                                             |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|bench_4099.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_4100.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_4112.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4115.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_4137.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_414.smt2                                                                              |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_4141.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_4143.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_4154.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_4156.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_4157.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4160.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4164.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4170.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4173.smt2                                                                             |  20.077s  |  20.077s  |   0.000s  | 0.0%|
|bench_4175.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4192.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_4208.smt2                                                                             |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|bench_4219.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4220.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_4231.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_4233.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_424.smt2                                                                              |   0.955s  |   0.955s  |   0.000s  | 0.0%|
|bench_4253.smt2                                                                             |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|bench_4256.smt2                                                                             |   6.136s  |   6.136s  |   0.000s  | 0.0%|
|bench_4261.smt2                                                                             |  19.973s  |  19.973s  |   0.000s  | 0.0%|
|bench_4273.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4275.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_4279.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4289.smt2                                                                             |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|bench_4304.smt2                                                                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|bench_4312.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4313.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4319.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4321.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4340.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_4346.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4350.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4352.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_4356.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_4359.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_436.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4368.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_437.smt2                                                                              |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_4375.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4385.smt2                                                                             |   4.512s  |   4.512s  |   0.000s  | 0.0%|
|bench_4387.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4390.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4397.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_4399.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_440.smt2                                                                              |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|bench_4405.smt2                                                                             |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|bench_4412.smt2                                                                             |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|bench_4435.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_4444.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_4447.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_445.smt2                                                                              |   1.081s  |   1.081s  |   0.000s  | 0.0%|
|bench_4461.smt2                                                                             |   1.268s  |   1.268s  |   0.000s  | 0.0%|
|bench_4467.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_4472.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_4477.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_4481.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_449.smt2                                                                              |   1.049s  |   1.049s  |   0.000s  | 0.0%|
|bench_4494.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4505.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4508.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_451.smt2                                                                              |   0.960s  |   0.960s  |   0.000s  | 0.0%|
|bench_4516.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4518.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_452.smt2                                                                              |   0.871s  |   0.871s  |   0.000s  | 0.0%|
|bench_4520.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4522.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4526.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4553.smt2                                                                             |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|bench_4555.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_456.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4560.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_4565.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_4568.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_457.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4570.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_4576.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4580.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4581.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4583.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4588.smt2                                                                             |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|bench_4594.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_46.smt2                                                                               |   1.494s  |   1.494s  |   0.000s  | 0.0%|
|bench_4605.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_4607.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_4614.smt2                                                                             |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|bench_4617.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4626.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4627.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4628.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4635.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4642.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4644.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4650.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4654.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4662.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4669.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_4689.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4692.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4696.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4706.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4710.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_472.smt2                                                                              |   2.427s  |   2.427s  |   0.000s  | 0.0%|
|bench_4724.smt2                                                                             |  20.151s  |  20.151s  |   0.000s  | 0.0%|
|bench_4725.smt2                                                                             |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|bench_4728.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_4738.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_4740.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_4753.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_4755.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_4759.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4768.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4775.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4788.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_479.smt2                                                                              |   0.973s  |   0.973s  |   0.000s  | 0.0%|
|bench_480.smt2                                                                              |   1.028s  |   1.028s  |   0.000s  | 0.0%|
|bench_4813.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_4818.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4820.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4822.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|bench_4834.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4838.smt2                                                                             |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|bench_4839.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4840.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4873.smt2                                                                             |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|bench_4879.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4888.smt2                                                                             |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|bench_489.smt2                                                                              |  20.009s  |  20.009s  |   0.000s  | 0.0%|
|bench_4890.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_4893.smt2                                                                             |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|bench_4894.smt2                                                                             |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|bench_4900.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_4906.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4908.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4919.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4920.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4921.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4933.smt2                                                                             |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|bench_4937.smt2                                                                             |  20.009s  |  20.009s  |   0.000s  | 0.0%|
|bench_494.smt2                                                                              |   1.382s  |   1.382s  |   0.000s  | 0.0%|
|bench_4954.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4957.smt2                                                                             |  19.961s  |  19.961s  |   0.000s  | 0.0%|
|bench_4963.smt2                                                                             |  19.984s  |  19.984s  |   0.000s  | 0.0%|
|bench_4964.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_4965.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4968.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_497.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4971.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_498.smt2                                                                              |   1.003s  |   1.003s  |   0.000s  | 0.0%|
|bench_4985.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4990.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_5.smt2                                                                                |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_50.smt2                                                                               |   1.090s  |   1.090s  |   0.000s  | 0.0%|
|bench_500.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_5005.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5019.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_502.smt2                                                                              |   1.185s  |   1.185s  |   0.000s  | 0.0%|
|bench_5030.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_5034.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_5036.smt2                                                                             |  19.890s  |  19.890s  |   0.000s  | 0.0%|
|bench_5037.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_5041.smt2                                                                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_5077.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_5081.smt2                                                                             |  13.379s  |  13.379s  |   0.000s  | 0.0%|
|bench_5084.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_5086.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5096.smt2                                                                             |  19.958s  |  19.958s  |   0.000s  | 0.0%|
|bench_51.smt2                                                                               |   0.917s  |   0.917s  |   0.000s  | 0.0%|
|bench_5123.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5127.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5131.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5136.smt2                                                                             |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|bench_5137.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|bench_5139.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_5150.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5153.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_5154.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5155.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5157.smt2                                                                             |  19.369s  |  19.369s  |   0.000s  | 0.0%|
|bench_5159.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5165.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_5170.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_5183.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5187.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_5188.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5190.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5191.smt2                                                                             |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|bench_5192.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_52.smt2                                                                               |   5.804s  |   5.804s  |   0.000s  | 0.0%|
|bench_5209.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5210.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5218.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5222.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5223.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|bench_5234.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_5236.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_5238.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_525.smt2                                                                              |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|bench_5257.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_5261.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_527.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5270.smt2                                                                             |   3.311s  |   3.311s  |   0.000s  | 0.0%|
|bench_528.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_5284.smt2                                                                             |  17.872s  |  17.872s  |   0.000s  | 0.0%|
|bench_5292.smt2                                                                             |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|bench_5296.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|bench_5301.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_5302.smt2                                                                             |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|bench_5303.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_5309.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_531.smt2                                                                              |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|bench_5326.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_5329.smt2                                                                             |  19.980s  |  19.980s  |   0.000s  | 0.0%|
|bench_5332.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5340.smt2                                                                             |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|bench_5349.smt2                                                                             |  19.954s  |  19.954s  |   0.000s  | 0.0%|
|bench_535.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_5358.smt2                                                                             |  19.522s  |  19.522s  |   0.000s  | 0.0%|
|bench_536.smt2                                                                              |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|bench_5360.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_5365.smt2                                                                             |   1.318s  |   1.318s  |   0.000s  | 0.0%|
|bench_5371.smt2                                                                             |   1.576s  |   1.576s  |   0.000s  | 0.0%|
|bench_5373.smt2                                                                             |   1.085s  |   1.085s  |   0.000s  | 0.0%|
|bench_5377.smt2                                                                             |   1.108s  |   1.108s  |   0.000s  | 0.0%|
|bench_5392.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_5395.smt2                                                                             |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|bench_5401.smt2                                                                             |   0.755s  |   0.755s  |   0.000s  | 0.0%|
|bench_5408.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_5417.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_542.smt2                                                                              |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|bench_5421.smt2                                                                             |  12.012s  |  12.012s  |   0.000s  | 0.0%|
|bench_5424.smt2                                                                             |  20.006s  |  20.006s  |   0.000s  | 0.0%|
|bench_5432.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5435.smt2                                                                             |  19.978s  |  19.978s  |   0.000s  | 0.0%|
|bench_5440.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_5445.smt2                                                                             |   1.252s  |   1.252s  |   0.000s  | 0.0%|
|bench_5449.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_5457.smt2                                                                             |   1.139s  |   1.139s  |   0.000s  | 0.0%|
|bench_5459.smt2                                                                             |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|bench_5466.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|bench_5492.smt2                                                                             |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|bench_5499.smt2                                                                             |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|bench_5503.smt2                                                                             |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|bench_5509.smt2                                                                             |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|bench_5517.smt2                                                                             |  19.911s  |  19.911s  |   0.000s  | 0.0%|
|bench_5525.smt2                                                                             |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|bench_5526.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|bench_5532.smt2                                                                             |   0.949s  |   0.949s  |   0.000s  | 0.0%|
|bench_5536.smt2                                                                             |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|bench_5543.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_5545.smt2                                                                             |   1.605s  |   1.605s  |   0.000s  | 0.0%|
|bench_556.smt2                                                                              |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_5575.smt2                                                                             |  19.955s  |  19.955s  |   0.000s  | 0.0%|
|bench_5581.smt2                                                                             |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|bench_559.smt2                                                                              |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_5590.smt2                                                                             |   1.016s  |   1.016s  |   0.000s  | 0.0%|
|bench_5593.smt2                                                                             |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bench_561.smt2                                                                              |   0.557s  |   0.557s  |   0.000s  | 0.0%|
|bench_5613.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5623.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_5636.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5645.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5649.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_565.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5658.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5662.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_5666.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_5674.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_571.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_5718.smt2                                                                             |   1.045s  |   1.045s  |   0.000s  | 0.0%|
|bench_5722.smt2                                                                             |   1.096s  |   1.096s  |   0.000s  | 0.0%|
|bench_5723.smt2                                                                             |   1.004s  |   1.004s  |   0.000s  | 0.0%|
|bench_5733.smt2                                                                             |   0.908s  |   0.908s  |   0.000s  | 0.0%|
|bench_5744.smt2                                                                             |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|bench_5752.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_5765.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_5779.smt2                                                                             |   2.040s  |   2.040s  |   0.000s  | 0.0%|
|bench_581.smt2                                                                              |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_5898.smt2                                                                             |   2.840s  |   2.840s  |   0.000s  | 0.0%|
|bench_5944.smt2                                                                             |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|bench_5974.smt2                                                                             |  20.015s  |  20.015s  |   0.000s  | 0.0%|
|bench_6012.smt2                                                                             |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|bench_6016.smt2                                                                             |  19.969s  |  19.969s  |   0.000s  | 0.0%|
|bench_607.smt2                                                                              |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|bench_609.smt2                                                                              |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench_6097.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|bench_613.smt2                                                                              |   0.836s  |   0.836s  |   0.000s  | 0.0%|
|bench_619.smt2                                                                              |   2.848s  |   2.848s  |   0.000s  | 0.0%|
|bench_620.smt2                                                                              |   2.325s  |   2.325s  |   0.000s  | 0.0%|
|bench_6215.smt2                                                                             |   2.543s  |   2.543s  |   0.000s  | 0.0%|
|bench_629.smt2                                                                              |   1.246s  |   1.246s  |   0.000s  | 0.0%|
|bench_630.smt2                                                                              |   1.709s  |   1.709s  |   0.000s  | 0.0%|
|bench_631.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_637.smt2                                                                              |  17.599s  |  17.599s  |   0.000s  | 0.0%|
|bench_639.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_640.smt2                                                                              |   0.553s  |   0.553s  |   0.000s  | 0.0%|
|bench_6408.smt2                                                                             |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|bench_6458.smt2                                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|bench_6462.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|bench_650.smt2                                                                              |   0.799s  |   0.799s  |   0.000s  | 0.0%|
|bench_6560.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_657.smt2                                                                              |   0.973s  |   0.973s  |   0.000s  | 0.0%|
|bench_658.smt2                                                                              |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench_659.smt2                                                                              |   0.897s  |   0.897s  |   0.000s  | 0.0%|
|bench_66.smt2                                                                               |   1.083s  |   1.083s  |   0.000s  | 0.0%|
|bench_6606.smt2                                                                             |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|bench_6614.smt2                                                                             |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|bench_663.smt2                                                                              |   0.892s  |   0.892s  |   0.000s  | 0.0%|
|bench_6665.smt2                                                                             |  19.993s  |  19.993s  |   0.000s  | 0.0%|
|bench_668.smt2                                                                              |   1.031s  |   1.031s  |   0.000s  | 0.0%|
|bench_6691.smt2                                                                             |  19.982s  |  19.982s  |   0.000s  | 0.0%|
|bench_6696.smt2                                                                             |   4.534s  |   4.534s  |   0.000s  | 0.0%|
|bench_6699.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_6713.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_6731.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_6734.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_674.smt2                                                                              |   1.752s  |   1.752s  |   0.000s  | 0.0%|
|bench_6742.smt2                                                                             |   8.126s  |   8.126s  |   0.000s  | 0.0%|
|bench_6756.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_6765.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_6791.smt2                                                                             |   1.088s  |   1.088s  |   0.000s  | 0.0%|
|bench_6813.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_6826.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_6828.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_6830.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6837.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_6843.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6848.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_685.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_6854.smt2                                                                             |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|bench_6857.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_6861.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_6866.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_6867.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_6882.smt2                                                                             |  19.990s  |  19.990s  |   0.000s  | 0.0%|
|bench_6886.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_6898.smt2                                                                             |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|bench_690.smt2                                                                              |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|bench_6901.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_6902.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_6906.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_6908.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_6911.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_6917.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_6923.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_6924.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_6929.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_6938.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_6943.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_6953.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_6954.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_6966.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_6973.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_6986.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_6987.smt2                                                                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_6998.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_700.smt2                                                                              |   0.829s  |   0.829s  |   0.000s  | 0.0%|
|bench_7005.smt2                                                                             |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|bench_702.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7021.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7024.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7030.smt2                                                                             |  20.015s  |  20.015s  |   0.000s  | 0.0%|
|bench_7033.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_704.smt2                                                                              |   0.720s  |   0.720s  |   0.000s  | 0.0%|
|bench_705.smt2                                                                              |   0.878s  |   0.878s  |   0.000s  | 0.0%|
|bench_7056.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_706.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7070.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7076.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7081.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7082.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7083.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7085.smt2                                                                             |   8.022s  |   8.022s  |   0.000s  | 0.0%|
|bench_7086.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7088.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_709.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_7095.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_710.smt2                                                                              |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_7116.smt2                                                                             |  19.966s  |  19.966s  |   0.000s  | 0.0%|
|bench_7119.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_712.smt2                                                                              |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|bench_7127.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_7138.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7139.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_7140.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7142.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7146.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7150.smt2                                                                             |  20.142s  |  20.142s  |   0.000s  | 0.0%|
|bench_7152.smt2                                                                             |   6.384s  |   6.384s  |   0.000s  | 0.0%|
|bench_7166.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_717.smt2                                                                              |  19.994s  |  19.994s  |   0.000s  | 0.0%|
|bench_7171.smt2                                                                             |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|bench_7182.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7185.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7188.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_720.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_721.smt2                                                                              |   4.110s  |   4.110s  |   0.000s  | 0.0%|
|bench_7219.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7229.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7233.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7242.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7270.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7274.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7278.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7304.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7306.smt2                                                                             |   7.804s  |   7.804s  |   0.000s  | 0.0%|
|bench_7310.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7314.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_7319.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7329.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7331.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7339.smt2                                                                             |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|bench_7357.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_7375.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7382.smt2                                                                             |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|bench_7383.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_7388.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7406.smt2                                                                             |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|bench_7412.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_7415.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7421.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_743.smt2                                                                              |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_7438.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_7454.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_746.smt2                                                                              |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_7465.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_748.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7489.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_749.smt2                                                                              |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_7494.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7495.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7496.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7498.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7517.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7523.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7528.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_753.smt2                                                                              |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|bench_7532.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7534.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7537.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7539.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7550.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7552.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7556.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7563.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_7565.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7573.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7575.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_76.smt2                                                                               |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_760.smt2                                                                              |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|bench_7601.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7612.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7627.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7633.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7636.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7641.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7642.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7655.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7663.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7669.smt2                                                                             |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|bench_7670.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7671.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7673.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7686.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7696.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7705.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7708.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_7714.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7729.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7736.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7749.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_7754.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7758.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_7765.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_778.smt2                                                                              |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_78.smt2                                                                               |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7800.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7807.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7811.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7819.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7823.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7826.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7828.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7832.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7833.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7834.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7835.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7842.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7851.smt2                                                                             |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bench_7862.smt2                                                                             |   4.669s  |   4.669s  |   0.000s  | 0.0%|
|bench_7863.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7867.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_787.smt2                                                                              |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|bench_7872.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7878.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7881.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_789.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_791.smt2                                                                              |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_793.smt2                                                                              |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_7943.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_796.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_797.smt2                                                                              |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_7973.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_8019.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_8030.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_8042.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_8049.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_8051.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_8053.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_8054.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_8055.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8070.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_8073.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_808.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_8082.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_8084.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8088.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_8093.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_8103.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_8110.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_8116.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_8117.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_8147.smt2                                                                             |   4.694s  |   4.694s  |   0.000s  | 0.0%|
|bench_815.smt2                                                                              |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|bench_8165.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_8170.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_8178.smt2                                                                             |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|bench_820.smt2                                                                              |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_8200.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_8228.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_823.smt2                                                                              |   0.692s  |   0.692s  |   0.000s  | 0.0%|
|bench_8234.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_824.smt2                                                                              |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_8245.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_825.smt2                                                                              |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_826.smt2                                                                              |   0.600s  |   0.600s  |   0.000s  | 0.0%|
|bench_8260.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_8271.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_8282.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_8283.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_8289.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_8294.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_8296.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_8298.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_830.smt2                                                                              |   0.662s  |   0.662s  |   0.000s  | 0.0%|
|bench_8306.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_8309.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_831.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_8315.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_8320.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_8342.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_8344.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_8357.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_8379.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_838.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_8393.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_8394.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_8461.smt2                                                                             |  13.497s  |  13.497s  |   0.000s  | 0.0%|
|bench_8462.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_8478.smt2                                                                             |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|bench_8487.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_8492.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_8495.smt2                                                                             |  20.099s  |  20.099s  |   0.000s  | 0.0%|
|bench_8507.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_8512.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_856.smt2                                                                              |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_8562.smt2                                                                             |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|bench_8564.smt2                                                                             |  20.088s  |  20.088s  |   0.000s  | 0.0%|
|bench_8579.smt2                                                                             |   7.077s  |   7.077s  |   0.000s  | 0.0%|
|bench_858.smt2                                                                              |   0.522s  |   0.522s  |   0.000s  | 0.0%|
|bench_86.smt2                                                                               |   1.657s  |   1.657s  |   0.000s  | 0.0%|
|bench_864.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_868.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_875.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_881.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_883.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_888.smt2                                                                              |   0.647s  |   0.647s  |   0.000s  | 0.0%|
|bench_894.smt2                                                                              |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_900.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_9009.smt2                                                                             |  20.010s  |  20.010s  |   0.000s  | 0.0%|
|bench_905.smt2                                                                              |   1.133s  |   1.133s  |   0.000s  | 0.0%|
|bench_91.smt2                                                                               |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_914.smt2                                                                              |   4.440s  |   4.440s  |   0.000s  | 0.0%|
|bench_9173.smt2                                                                             |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|bench_919.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_92.smt2                                                                               |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_924.smt2                                                                              |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|bench_926.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_9280.smt2                                                                             |   2.894s  |   2.894s  |   0.000s  | 0.0%|
|bench_9299.smt2                                                                             |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|bench_930.smt2                                                                              |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_9301.smt2                                                                             |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|bench_9337.smt2                                                                             |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|bench_9343.smt2                                                                             |  20.000s  |  20.000s  |   0.000s  | 0.0%|
|bench_9360.smt2                                                                             |  19.995s  |  19.995s  |   0.000s  | 0.0%|
|bench_938.smt2                                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_941.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_944.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_945.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_9535.smt2                                                                             |  20.001s  |  20.001s  |   0.000s  | 0.0%|
|bench_954.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_957.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_961.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_964.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_965.smt2                                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_9653.smt2                                                                             |  13.156s  |  13.156s  |   0.000s  | 0.0%|
|bench_97.smt2                                                                               |   0.855s  |   0.855s  |   0.000s  | 0.0%|
|bench_972.smt2                                                                              |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|bench_974.smt2                                                                              |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bench_975.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_979.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_98.smt2                                                                               |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_981.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_983.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_9846.smt2                                                                             |   3.115s  |   3.115s  |   0.000s  | 0.0%|
|bench_985.smt2                                                                              |  13.505s  |  13.505s  |   0.000s  | 0.0%|
|bench_988.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_991.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_992.smt2                                                                              |   5.536s  |   5.536s  |   0.000s  | 0.0%|
|bench_993.smt2                                                                              |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bench_994.smt2                                                                              |   1.444s  |   1.444s  |   0.000s  | 0.0%|
|bench_9946.smt2                                                                             |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|bench_996.smt2                                                                              |  20.007s  |  20.007s  |   0.000s  | 0.0%|
|bench_997.smt2                                                                              |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|bgpd_bgpd_vc76751.smt2                                                                      |   0.908s  |   0.908s  |   0.000s  | 0.0%|
|bgpd_bgpd_vc76752.smt2                                                                      |   0.371s  |   0.371s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc330950.smt2                                                               |   0.620s  |   0.620s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc330976.smt2                                                               |   0.315s  |   0.315s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc330978.smt2                                                               |   0.381s  |   0.381s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331001.smt2                                                               |   0.827s  |   0.827s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331002.smt2                                                               |   0.735s  |   0.735s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331003.smt2                                                               |   0.844s  |   0.844s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331007.smt2                                                               |   1.331s  |   1.331s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331044.smt2                                                               |   2.722s  |   2.722s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331052.smt2                                                               |   1.606s  |   1.606s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331054.smt2                                                               |   1.776s  |   1.776s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331082.smt2                                                               |   1.896s  |   1.896s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331086.smt2                                                               |   5.739s  |   5.739s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331088.smt2                                                               |   0.476s  |   0.476s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331089.smt2                                                               |   0.371s  |   0.371s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331092.smt2                                                               |   6.962s  |   6.962s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331097.smt2                                                               |   2.291s  |   2.291s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331106.smt2                                                               |   2.383s  |   2.383s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331114.smt2                                                               |   2.585s  |   2.585s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331126.smt2                                                               |   4.062s  |   4.062s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331137.smt2                                                               |   3.292s  |   3.292s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331146.smt2                                                               |   5.253s  |   5.253s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331148.smt2                                                               |   3.117s  |   3.117s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331154.smt2                                                               |   5.106s  |   5.106s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331156.smt2                                                               |   3.588s  |   3.588s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331161.smt2                                                               |   6.417s  |   6.417s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331166.smt2                                                               |   2.240s  |   2.240s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331167.smt2                                                               |   3.156s  |   3.156s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331169.smt2                                                               |   7.973s  |   7.973s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc351277.smt2                                                               |   0.744s  |   0.744s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc351344.smt2                                                               |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc351348.smt2                                                               |   1.558s  |   1.558s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc352293.smt2                                                               |   0.820s  |   0.820s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc352302.smt2                                                               |   0.728s  |   0.728s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc352355.smt2                                                               |   0.465s  |   0.465s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225139.smt2                                                                 |   0.975s  |   0.975s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225280.smt2                                                                 |   2.241s  |   2.241s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225299.smt2                                                                 |   2.533s  |   2.533s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225305.smt2                                                                 |   6.295s  |   6.295s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225312.smt2                                                                 |   2.248s  |   2.248s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225316.smt2                                                                 |   2.880s  |   2.880s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225318.smt2                                                                 |  10.674s  |  10.674s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225320.smt2                                                                 |   6.489s  |   6.489s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225324.smt2                                                                 |   2.120s  |   2.120s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225330.smt2                                                                 |   5.950s  |   5.950s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225332.smt2                                                                 |   6.168s  |   6.168s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225336.smt2                                                                 |   2.490s  |   2.490s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225346.smt2                                                                 |   4.253s  |   4.253s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225380.smt2                                                                 |   4.884s  |   4.884s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225392.smt2                                                                 |   5.212s  |   5.212s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225394.smt2                                                                 |   3.407s  |   3.407s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225395.smt2                                                                 |   3.419s  |   3.419s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225399.smt2                                                                 |   4.771s  |   4.771s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225405.smt2                                                                 |  10.651s  |  10.651s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225408.smt2                                                                 |   4.059s  |   4.059s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225412.smt2                                                                 |   3.224s  |   3.224s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225454.smt2                                                                 |   5.797s  |   5.797s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225601.smt2                                                                 |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225626.smt2                                                                 |   0.845s  |   0.845s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225628.smt2                                                                 |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225745.smt2                                                                 |   0.321s  |   0.321s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225756.smt2                                                                 |   2.036s  |   2.036s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225762.smt2                                                                 |   2.540s  |   2.540s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225779.smt2                                                                 |   1.639s  |   1.639s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225786.smt2                                                                 |   3.939s  |   3.939s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225800.smt2                                                                 |   3.084s  |   3.084s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225806.smt2                                                                 |   2.085s  |   2.085s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225815.smt2                                                                 |   3.181s  |   3.181s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225816.smt2                                                                 |   1.847s  |   1.847s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225820.smt2                                                                 |   2.444s  |   2.444s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225824.smt2                                                                 |   2.158s  |   2.158s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225843.smt2                                                                 |   3.406s  |   3.406s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225858.smt2                                                                 |   3.291s  |   3.291s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225895.smt2                                                                 |   3.748s  |   3.748s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225900.smt2                                                                 |   3.942s  |   3.942s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225910.smt2                                                                 |  10.774s  |  10.774s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225912.smt2                                                                 |   3.851s  |   3.851s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225939.smt2                                                                 |  18.590s  |  18.590s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228446.smt2                                                                 |   2.427s  |   2.427s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228463.smt2                                                                 |   3.270s  |   3.270s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228472.smt2                                                                 |   2.672s  |   2.672s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228474.smt2                                                                 |   2.699s  |   2.699s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228478.smt2                                                                 |   2.711s  |   2.711s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228479.smt2                                                                 |   2.574s  |   2.574s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228487.smt2                                                                 |   2.853s  |   2.853s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228491.smt2                                                                 |   2.983s  |   2.983s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228492.smt2                                                                 |   0.930s  |   0.930s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228509.smt2                                                                 |   4.493s  |   4.493s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228512.smt2                                                                 |   4.090s  |   4.090s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228514.smt2                                                                 |   3.801s  |   3.801s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228524.smt2                                                                 |   8.048s  |   8.048s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228527.smt2                                                                 |   4.962s  |   4.962s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228571.smt2                                                                 |   4.125s  |   4.125s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228577.smt2                                                                 |   4.580s  |   4.580s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228610.smt2                                                                 |   3.442s  |   3.442s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232002.smt2                                                                 |   2.628s  |   2.628s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232007.smt2                                                                 |   0.661s  |   0.661s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232013.smt2                                                                 |   2.562s  |   2.562s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232030.smt2                                                                 |   2.351s  |   2.351s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232034.smt2                                                                 |   6.080s  |   6.080s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232036.smt2                                                                 |   4.744s  |   4.744s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232066.smt2                                                                 |   3.013s  |   3.013s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232071.smt2                                                                 |   5.397s  |   5.397s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232117.smt2                                                                 |   2.440s  |   2.440s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232128.smt2                                                                 |   2.967s  |   2.967s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232137.smt2                                                                 |   4.610s  |   4.610s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232138.smt2                                                                 |   3.142s  |   3.142s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225164.smt2                                                             |   0.884s  |   0.884s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225207.smt2                                                             |   2.555s  |   2.555s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225211.smt2                                                             |   5.236s  |   5.236s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225213.smt2                                                             |   3.250s  |   3.250s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225231.smt2                                                             |   4.428s  |   4.428s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225236.smt2                                                             |   2.789s  |   2.789s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225237.smt2                                                             |   2.739s  |   2.739s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225238.smt2                                                             |   2.992s  |   2.992s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225246.smt2                                                             |   3.109s  |   3.109s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225256.smt2                                                             |   5.995s  |   5.995s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225257.smt2                                                             |   4.965s  |   4.965s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225263.smt2                                                             |   4.876s  |   4.876s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225264.smt2                                                             |   3.321s  |   3.321s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225271.smt2                                                             |   4.533s  |   4.533s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225275.smt2                                                             |   3.583s  |   3.583s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225279.smt2                                                             |   4.330s  |   4.330s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225303.smt2                                                             |   3.190s  |   3.190s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225668.smt2                                                             |   1.050s  |   1.050s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225676.smt2                                                             |   2.034s  |   2.034s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225689.smt2                                                             |   1.609s  |   1.609s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225692.smt2                                                             |   2.071s  |   2.071s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225731.smt2                                                             |   6.363s  |   6.363s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225733.smt2                                                             |   2.006s  |   2.006s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225736.smt2                                                             |   2.939s  |   2.939s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225745.smt2                                                             |   2.632s  |   2.632s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225748.smt2                                                             |   2.274s  |   2.274s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225758.smt2                                                             |   5.579s  |   5.579s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225761.smt2                                                             |  10.957s  |  10.957s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225764.smt2                                                             |   4.168s  |   4.168s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225771.smt2                                                             |  14.356s  |  14.356s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225773.smt2                                                             |   6.319s  |   6.319s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225779.smt2                                                             |   3.926s  |   3.926s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225783.smt2                                                             |   4.335s  |   4.335s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225826.smt2                                                             |   4.020s  |   4.020s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225835.smt2                                                             |   5.402s  |   5.402s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225841.smt2                                                             |   9.826s  |   9.826s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225860.smt2                                                             |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225887.smt2                                                             |   3.698s  |   3.698s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228430.smt2                                                             |   3.400s  |   3.400s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228442.smt2                                                             |   7.040s  |   7.040s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228448.smt2                                                             |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228452.smt2                                                             |   8.036s  |   8.036s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228479.smt2                                                             |   3.588s  |   3.588s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228491.smt2                                                             |   4.260s  |   4.260s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228496.smt2                                                             |   3.680s  |   3.680s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228508.smt2                                                             |   3.932s  |   3.932s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228531.smt2                                                             |   3.835s  |   3.835s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc4232.smt2                                                            |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc4243.smt2                                                            |   0.693s  |   0.693s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc4289.smt2                                                            |   1.147s  |   1.147s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc4296.smt2                                                            |   1.525s  |   1.525s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc4297.smt2                                                            |   1.022s  |   1.022s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc4773.smt2                                                            |   1.261s  |   1.261s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc4791.smt2                                                            |   1.436s  |   1.436s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5285.smt2                                                            |   1.968s  |   1.968s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5327.smt2                                                            |   1.828s  |   1.828s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5331.smt2                                                            |   0.783s  |   0.783s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5680.smt2                                                            |   2.350s  |   2.350s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5689.smt2                                                            |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5711.smt2                                                            |   2.512s  |   2.512s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5712.smt2                                                            |   1.580s  |   1.580s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5729.smt2                                                            |   0.599s  |   0.599s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5733.smt2                                                            |   1.709s  |   1.709s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5735.smt2                                                            |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5742.smt2                                                            |   2.920s  |   2.920s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5748.smt2                                                            |   2.667s  |   2.667s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5749.smt2                                                            |   3.145s  |   3.145s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5751.smt2                                                            |   0.614s  |   0.614s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5769.smt2                                                            |   0.543s  |   0.543s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5771.smt2                                                            |   0.377s  |   0.377s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5782.smt2                                                            |   1.659s  |   1.659s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5793.smt2                                                            |   3.407s  |   3.407s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5794.smt2                                                            |   0.738s  |   0.738s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5806.smt2                                                            |   1.784s  |   1.784s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5817.smt2                                                            |   1.277s  |   1.277s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5840.smt2                                                            |   1.041s  |   1.041s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5848.smt2                                                            |   0.993s  |   0.993s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6049.smt2                                                            |   0.424s  |   0.424s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6074.smt2                                                            |   3.829s  |   3.829s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6105.smt2                                                            |   3.931s  |   3.931s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6117.smt2                                                            |   1.927s  |   1.927s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6120.smt2                                                            |   1.734s  |   1.734s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6139.smt2                                                            |   3.678s  |   3.678s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6150.smt2                                                            |   1.142s  |   1.142s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6161.smt2                                                            |   4.299s  |   4.299s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6178.smt2                                                            |   2.422s  |   2.422s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6181.smt2                                                            |   6.125s  |   6.125s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6182.smt2                                                            |   2.304s  |   2.304s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6195.smt2                                                            |   4.051s  |   4.051s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6199.smt2                                                            |   3.619s  |   3.619s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6205.smt2                                                            |   3.618s  |   3.618s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6217.smt2                                                            |   5.342s  |   5.342s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6229.smt2                                                            |   4.441s  |   4.441s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6241.smt2                                                            |   3.026s  |   3.026s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6242.smt2                                                            |   2.676s  |   2.676s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6250.smt2                                                            |   4.424s  |   4.424s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6255.smt2                                                            |  18.005s  |  18.005s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6266.smt2                                                            |   3.353s  |   3.353s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6270.smt2                                                            |   3.354s  |   3.354s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6271.smt2                                                            |   0.952s  |   0.952s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6272.smt2                                                            |   1.195s  |   1.195s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6280.smt2                                                            |   2.911s  |   2.911s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6287.smt2                                                            |   6.195s  |   6.195s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6288.smt2                                                            |   6.359s  |   6.359s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6289.smt2                                                            |   1.838s  |   1.838s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6291.smt2                                                            |   8.727s  |   8.727s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6295.smt2                                                            |  15.365s  |  15.365s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6297.smt2                                                            |   3.506s  |   3.506s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6298.smt2                                                            |   4.859s  |   4.859s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6299.smt2                                                            |   4.372s  |   4.372s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6305.smt2                                                            |   4.789s  |   4.789s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6308.smt2                                                            |   3.158s  |   3.158s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6309.smt2                                                            |   4.720s  |   4.720s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6314.smt2                                                            |   4.700s  |   4.700s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6315.smt2                                                            |   2.150s  |   2.150s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6325.smt2                                                            |   5.244s  |   5.244s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6328.smt2                                                            |   6.941s  |   6.941s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6336.smt2                                                            |   3.263s  |   3.263s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6339.smt2                                                            |   4.276s  |   4.276s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6343.smt2                                                            |  15.160s  |  15.160s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6346.smt2                                                            |  10.234s  |  10.234s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6845.smt2                                                            |   0.508s  |   0.508s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7060.smt2                                                            |   0.655s  |   0.655s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7064.smt2                                                            |   0.789s  |   0.789s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7068.smt2                                                            |   0.661s  |   0.661s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7072.smt2                                                            |   1.496s  |   1.496s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7086.smt2                                                            |   0.703s  |   0.703s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7087.smt2                                                            |   1.604s  |   1.604s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7094.smt2                                                            |   2.258s  |   2.258s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7104.smt2                                                            |   1.980s  |   1.980s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7105.smt2                                                            |   2.495s  |   2.495s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7116.smt2                                                            |   2.231s  |   2.231s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7117.smt2                                                            |   3.110s  |   3.110s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7119.smt2                                                            |   1.935s  |   1.935s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7120.smt2                                                            |   4.395s  |   4.395s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7124.smt2                                                            |   1.818s  |   1.818s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7130.smt2                                                            |   2.009s  |   2.009s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7131.smt2                                                            |   4.966s  |   4.966s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7133.smt2                                                            |   2.242s  |   2.242s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7225.smt2                                                            |   0.728s  |   0.728s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7281.smt2                                                            |   1.467s  |   1.467s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7285.smt2                                                            |   1.008s  |   1.008s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7296.smt2                                                            |   0.970s  |   0.970s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7636.smt2                                                            |   5.461s  |   5.461s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7637.smt2                                                            |   2.411s  |   2.411s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7643.smt2                                                            |   8.470s  |   8.470s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7644.smt2                                                            |   2.822s  |   2.822s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7652.smt2                                                            |   0.778s  |   0.778s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7666.smt2                                                            |   4.429s  |   4.429s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7727.smt2                                                            |   5.501s  |   5.501s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7750.smt2                                                            |   4.989s  |   4.989s  |   0.000s  | 0.0%|
|bitops7.smt2                                                                                |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bv-term-small-rw_1391.smt2                                                                  |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bv-term-small-rw_1516.smt2                                                                  |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bv-term-small-rw_166.smt2                                                                   |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bv-term-small-rw_207.smt2                                                                   |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bv-term-small-rw_230.smt2                                                                   |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|bv-term-small-rw_250.smt2                                                                   |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bv-term-small-rw_260.smt2                                                                   |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|bv-term-small-rw_314.smt2                                                                   |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bv-term-small-rw_318.smt2                                                                   |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bv-term-small-rw_327.smt2                                                                   |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bv-term-small-rw_337.smt2                                                                   |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bv-term-small-rw_356.smt2                                                                   |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bv-term-small-rw_36.smt2                                                                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bv-term-small-rw_45.smt2                                                                    |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bv-term-small-rw_465.smt2                                                                   |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|bv-term-small-rw_47.smt2                                                                    |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bv-term-small-rw_521.smt2                                                                   |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bv-term-small-rw_720.smt2                                                                   |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bv-term-small-rw_904.smt2                                                                   |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bvsdiv.smt2                                                                                 |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|cvs_vc105319.smt2                                                                           |   2.052s  |   2.052s  |   0.000s  | 0.0%|
|cvs_vc105322.smt2                                                                           |   1.987s  |   1.987s  |   0.000s  | 0.0%|
|cvs_vc105323.smt2                                                                           |   2.141s  |   2.141s  |   0.000s  | 0.0%|
|cvs_vc105357.smt2                                                                           |   1.848s  |   1.848s  |   0.000s  | 0.0%|
|cvs_vc105369.smt2                                                                           |   2.344s  |   2.344s  |   0.000s  | 0.0%|
|cvs_vc105421.smt2                                                                           |   3.249s  |   3.249s  |   0.000s  | 0.0%|
|cvs_vc105422.smt2                                                                           |   1.764s  |   1.764s  |   0.000s  | 0.0%|
|cvs_vc105458.smt2                                                                           |   2.695s  |   2.695s  |   0.000s  | 0.0%|
|div.c.20.smt2                                                                               |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|div3.c.20.smt2                                                                              |  16.789s  |  16.789s  |   0.000s  | 0.0%|
|e1_1.c.smt2                                                                                 |   0.849s  |   0.849s  |   0.000s  | 0.0%|
|e2_2.c.smt2                                                                                 |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|f23.smt2                                                                                    |  19.992s  |  19.992s  |   0.000s  | 0.0%|
|fig5.phx.smt2                                                                               |   1.020s  |   1.020s  |   0.000s  | 0.0%|
|gryzzles.22.lp.smt2                                                                         |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|gryzzles.8.lp.smt2                                                                          |  19.483s  |  19.483s  |   0.000s  | 0.0%|
|inf1.smt2                                                                                   |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|innd_innd_vc32473.smt2                                                                      |   5.262s  |   5.262s  |   0.000s  | 0.0%|
|innd_innd_vc32478.smt2                                                                      |   1.801s  |   1.801s  |   0.000s  | 0.0%|
|innd_innd_vc32492.smt2                                                                      |   1.846s  |   1.846s  |   0.000s  | 0.0%|
|innd_innd_vc32642.smt2                                                                      |   2.385s  |   2.385s  |   0.000s  | 0.0%|
|innd_innd_vc32648.smt2                                                                      |   2.857s  |   2.857s  |   0.000s  | 0.0%|
|innd_innd_vc32659.smt2                                                                      |   9.388s  |   9.388s  |   0.000s  | 0.0%|
|innd_innd_vc32740.smt2                                                                      |   3.068s  |   3.068s  |   0.000s  | 0.0%|
|innd_innd_vc33153.smt2                                                                      |   2.495s  |   2.495s  |   0.000s  | 0.0%|
|innd_innd_vc33158.smt2                                                                      |   2.437s  |   2.437s  |   0.000s  | 0.0%|
|innd_innd_vc33162.smt2                                                                      |   2.516s  |   2.516s  |   0.000s  | 0.0%|
|innd_innd_vc33342.smt2                                                                      |   4.040s  |   4.040s  |   0.000s  | 0.0%|
|innd_innd_vc33343.smt2                                                                      |   2.811s  |   2.811s  |   0.000s  | 0.0%|
|innd_innd_vc33347.smt2                                                                      |  15.803s  |  15.803s  |   0.000s  | 0.0%|
|innd_innd_vc33349.smt2                                                                      |   3.098s  |   3.098s  |   0.000s  | 0.0%|
|innd_innd_vc33528.smt2                                                                      |   5.057s  |   5.057s  |   0.000s  | 0.0%|
|innd_innd_vc33538.smt2                                                                      |   5.120s  |   5.120s  |   0.000s  | 0.0%|
|innd_innd_vc33544.smt2                                                                      |   2.547s  |   2.547s  |   0.000s  | 0.0%|
|innd_innd_vc33561.smt2                                                                      |   3.224s  |   3.224s  |   0.000s  | 0.0%|
|innd_innd_vc33564.smt2                                                                      |   5.993s  |   5.993s  |   0.000s  | 0.0%|
|innd_innd_vc33728.smt2                                                                      |   5.872s  |   5.872s  |   0.000s  | 0.0%|
|innd_innd_vc33732.smt2                                                                      |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|innd_innd_vc33738.smt2                                                                      |  16.289s  |  16.289s  |   0.000s  | 0.0%|
|innd_innd_vc33741.smt2                                                                      |   2.015s  |   2.015s  |   0.000s  | 0.0%|
|innd_innd_vc33743.smt2                                                                      |   3.475s  |   3.475s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc24623.smt2                                                               |   1.072s  |   1.072s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc24627.smt2                                                               |   1.762s  |   1.762s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc24797.smt2                                                               |   3.486s  |   3.486s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc24827.smt2                                                               |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc24828.smt2                                                               |   3.787s  |   3.787s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc24829.smt2                                                               |  19.977s  |  19.977s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc24830.smt2                                                               |  20.008s  |  20.008s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc25420.smt2                                                               |   2.752s  |   2.752s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc25433.smt2                                                               |   2.114s  |   2.114s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc25444.smt2                                                               |   4.586s  |   4.586s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc25456.smt2                                                               |   4.154s  |   4.154s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc36443.smt2                                                                |   1.452s  |   1.452s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc36459.smt2                                                                |  14.759s  |  14.759s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc36461.smt2                                                                |   2.461s  |   2.461s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc36615.smt2                                                                |   7.334s  |   7.334s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc36634.smt2                                                                |   8.078s  |   8.078s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc37055.smt2                                                                |   3.855s  |   3.855s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc37058.smt2                                                                |  19.998s  |  19.998s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc37224.smt2                                                                |   7.482s  |   7.482s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc37255.smt2                                                                |   3.456s  |   3.456s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc37260.smt2                                                                |   3.490s  |   3.490s  |   0.000s  | 0.0%|
|knightTour.in01.smt2                                                                        |  20.002s  |  20.002s  |   0.000s  | 0.0%|
|matrixsqrt.smt2                                                                             |   0.544s  |   0.544s  |   0.000s  | 0.0%|
|mobiledevice_bit8_na6_nr3_twocond.smt2                                                      |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|mult1.c.20.smt2                                                                             |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|mult2.c.10.smt2                                                                             |  17.139s  |  17.139s  |   0.000s  | 0.0%|
|ndist.b.21996.smt2                                                                          |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|ndist.b.27984.smt2                                                                          |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|ndist.b.28982.smt2                                                                          |  20.015s  |  20.015s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc20411.smt2                                                                    |  20.005s  |  20.005s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21034.smt2                                                                    |   3.267s  |   3.267s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21209.smt2                                                                    |   2.619s  |   2.619s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21211.smt2                                                                    |   2.537s  |   2.537s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21221.smt2                                                                    |   6.044s  |   6.044s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21229.smt2                                                                    |   2.332s  |   2.332s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21232.smt2                                                                    |   2.429s  |   2.429s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21244.smt2                                                                    |   1.593s  |   1.593s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21422.smt2                                                                    |   3.426s  |   3.426s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21427.smt2                                                                    |   2.292s  |   2.292s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21428.smt2                                                                    |   4.166s  |   4.166s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21434.smt2                                                                    |   2.474s  |   2.474s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21435.smt2                                                                    |   4.017s  |   4.017s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21446.smt2                                                                    |  15.529s  |  15.529s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21451.smt2                                                                    |   3.770s  |   3.770s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21636.smt2                                                                    |   4.155s  |   4.155s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21648.smt2                                                                    |   3.914s  |   3.914s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21666.smt2                                                                    |   2.985s  |   2.985s  |   0.000s  | 0.0%|
|predicate_1245.smt2                                                                         |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|predicate_1246.smt2                                                                         |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|predicate_169_0.smt2                                                                        |   1.113s  |   1.113s  |   0.000s  | 0.0%|
|predicate_1898.smt2                                                                         |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|predicate_2077.smt2                                                                         |   0.872s  |   0.872s  |   0.000s  | 0.0%|
|predicate_275.smt2                                                                          |   1.420s  |   1.420s  |   0.000s  | 0.0%|
|predicate_2801.smt2                                                                         |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|predicate_484.smt2                                                                          |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|predicate_490.smt2                                                                          |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|predicate_493.smt2                                                                          |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|predicate_496.smt2                                                                          |   0.452s  |   0.452s  |   0.000s  | 0.0%|
|predicate_602.smt2                                                                          |   1.383s  |   1.383s  |   0.000s  | 0.0%|
|predicate_735.smt2                                                                          |   1.593s  |   1.593s  |   0.000s  | 0.0%|
|problem_1.smt2                                                                              |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|problem_7.smt2                                                                              |  19.969s  |  19.969s  |   0.000s  | 0.0%|
|problem_8.smt2                                                                              |  19.970s  |  19.970s  |   0.000s  | 0.0%|
|problem_9.smt2                                                                              |   0.280s  |   0.280s  |   0.000s  | 0.0%|
|rand_100_400_1159666138_9.lp.smt2                                                           |  19.997s  |  19.997s  |   0.000s  | 0.0%|
|rand_150_600_1159731678_14.lp.smt2                                                          |  19.975s  |  19.975s  |   0.000s  | 0.0%|
|rand_150_600_1159731678_15.lp.smt2                                                          |  20.003s  |  20.003s  |   0.000s  | 0.0%|
|rand_200_800_1159728969_10.lp.smt2                                                          |  19.999s  |  19.999s  |   0.000s  | 0.0%|
|rand_20_100_1235851242_0_k-3_v-15_e-25_sat.gph.smt2                                         |  19.949s  |  19.949s  |   0.000s  | 0.0%|
|rand_65_500_1235857888_0_k-6_sat.gph.smt2                                                   |  19.925s  |  19.925s  |   0.000s  | 0.0%|
|rand_80_500_1235848939_0_k-9_sat.gph.smt2                                                   |  15.863s  |  15.863s  |   0.000s  | 0.0%|
|rfunit_flat-64.smt2                                                                         |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|run_00000.trace.Alloc_zero__011273.smt2                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|run_00000.trace.Alloc_zero__018344.smt2                                                     |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|run_00000.trace.Alloc_zero__019220.smt2                                                     |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|run_00000.trace.Alloc_zero__020079.smt2                                                     |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|run_00000.trace.cond_016653_0x95026e6_00.smt2                                               |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|run_00000.trace.cond_017116_0x950130a_00.smt2                                               |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|run_00000.trace.cond_017924_0x950130a_00.smt2                                               |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|run_00000.trace.cond_018783_0x950130a_00.smt2                                               |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|run_00000.trace.cond_019196_0x95026e6_00.smt2                                               |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|run_00000.trace.cond_019659_0x950130a_00.smt2                                               |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|run_00000.trace.cond_020055_0x95026e6_00.smt2                                               |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|run_00000.trace.cond_285172_0xe7af40_00.smt2                                                |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|run_00000.trace.cond_285198_0xe7af87_00.smt2                                                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|run_00000.trace.cond_455476_0xe7af69_00.smt2                                                |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|run_00012.trace.cond_057573_0x16388_00.smt2                                                 |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|run_03230.trace.cond_000028_0x40201f_00.smt2                                                |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|run_03230.trace.cond_000032_0x40248d_00.smt2                                                |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|run_03230.trace.cond_011742_0x4066e2_00.smt2                                                |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|run_03230.trace.cond_011923_0x4182b4_00.smt2                                                |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|run_03230.trace.cond_011951_0x4182b4_00.smt2                                                |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|run_03230.trace.cond_011955_0x4182de_00.smt2                                                |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|run_03230.trace.cond_011969_0x4182de_00.smt2                                                |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|run_03230.trace.cond_012011_0x4182de_00.smt2                                                |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|run_03230.trace.cond_012035_0x4182b4_00.smt2                                                |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|run_03230.trace.cond_012053_0x4182de_00.smt2                                                |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|run_03230.trace.cond_012133_0x4182b4_00.smt2                                                |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|run_03230.trace.cond_012161_0x4182b4_00.smt2                                                |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|run_03230.trace.cond_012175_0x4182b4_00.smt2                                                |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025314_0x41821d_00.smt2                                                |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025405_0x418209_00.smt2                                                |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025439_0x418209_00.smt2                                                |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025442_0x41821d_00.smt2                                                |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025454_0x418209_00.smt2                                                |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025469_0x418209_00.smt2                                                |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025506_0x41821d_00.smt2                                                |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025552_0x41820e_00.smt2                                                |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025570_0x41821d_00.smt2                                                |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025582_0x418209_00.smt2                                                |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025597_0x418209_00.smt2                                                |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025600_0x41821d_00.smt2                                                |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025616_0x41820e_00.smt2                                                |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025638_0x41821d_00.smt2                                                |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|send-more-money.smt2                                                                        |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|servers_slapd_a_vc149572.smt2                                                               |   2.244s  |   2.244s  |   0.000s  | 0.0%|
|servers_slapd_a_vc149789.smt2                                                               |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|simple_bit8_na1_nr1_twocond.smt2                                                            |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|smulov4bw1024.smt2                                                                          |  20.147s  |  20.147s  |   0.000s  | 0.0%|
|sort.smt2                                                                                   |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|src_wget_vc17453.smt2                                                                       |   0.580s  |   0.580s  |   0.000s  | 0.0%|
|src_wget_vc17891.smt2                                                                       |   2.969s  |   2.969s  |   0.000s  | 0.0%|
|src_wget_vc17906.smt2                                                                       |   6.136s  |   6.136s  |   0.000s  | 0.0%|
|src_wget_vc17911.smt2                                                                       |  19.987s  |  19.987s  |   0.000s  | 0.0%|
|src_wget_vc17912.smt2                                                                       |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|src_wget_vc17913.smt2                                                                       |  12.759s  |  12.759s  |   0.000s  | 0.0%|
|src_wget_vc18169.smt2                                                                       |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|src_wget_vc18506.smt2                                                                       |   9.788s  |   9.788s  |   0.000s  | 0.0%|
|test_v3_r3_vr10_c1_s24300.smt2                                                              |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|try3_noof_functions_dwp_stty.visible.il.dwp.smt2                                            |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|try3_noof_functions_dwp_touch.yyerror.il.dwp.smt2                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_noof_functions_dwp_cut.hash_int.il.dwp.smt2                                      |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|try5_small_noof_functions_dwp_expr.nomoreargs.il.dwp.smt2                                   |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_noof_functions_dwp_stty.visible.il.dwp.smt2                                      |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_cat.quoting_options_from_style.il.flanagansaxe.smt2  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_chgrp.quoting_options_from_style.il.flanagansaxe.smt2  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_cut.hash_int.il.flanagansaxe.smt2                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_echo.quoting_options_from_style.il.flanagansaxe.smt2  |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_env.quoting_options_from_style.il.flanagansaxe.smt2  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_fold.quoting_options_from_style.il.flanagansaxe.smt2  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_hostid.quoting_options_from_style.il.flanagansaxe.smt2  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_kill.quoting_options_from_style.il.flanagansaxe.smt2  |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_link.quoting_options_from_style.il.flanagansaxe.smt2  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_mkfifo.quoting_options_from_style.il.flanagansaxe.smt2  |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_nice.quoting_options_from_style.il.flanagansaxe.smt2  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_nl.quoting_options_from_style.il.flanagansaxe.smt2   |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_pinky.quoting_options_from_style.il.flanagansaxe.smt2  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_ptx.quoting_options_from_style.il.flanagansaxe.smt2  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_seq.quoting_options_from_style.il.flanagansaxe.smt2  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_sleep.quoting_options_from_style.il.flanagansaxe.smt2  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_sum.quoting_options_from_style.il.flanagansaxe.smt2  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_tac.quoting_options_from_style.il.flanagansaxe.smt2  |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_test.quoting_options_from_style.il.flanagansaxe.smt2  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_touch.quoting_options_from_style.il.flanagansaxe.smt2  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_true.quoting_options_from_style.il.flanagansaxe.smt2  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_tsort.quoting_options_from_style.il.flanagansaxe.smt2  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_tty.quoting_options_from_style.il.flanagansaxe.smt2  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_unexpand.quoting_options_from_style.il.flanagansaxe.smt2  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_users.quoting_options_from_style.il.flanagansaxe.smt2  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_vdir.quoting_options_from_style.il.flanagansaxe.smt2  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_wc.quoting_options_from_style.il.flanagansaxe.smt2   |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|try5_small_noof_functions_fse-bfs_shuf.input_numbers_option_used.il.fse-bfs.smt2            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|try5_small_true_functions_dwp_stty.visible.il.dwp.smt2                                      |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|try5_small_true_functions_dwp_yes.close_stdout_set_file_name.il.dwp.smt2                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_chgrp.i_ring_init.il.flanagansaxe.smt2               |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_join.initseq.il.flanagansaxe.smt2                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_md5sum.md5_init_ctx.il.flanagansaxe.smt2             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_sha1sum.sha1_read_ctx.il.flanagansaxe.smt2           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_stty.visible.il.flanagansaxe.smt2                    |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_tac.rpl_re_set_syntax.il.flanagansaxe.smt2           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_vdir.hash_get_n_entries.il.flanagansaxe.smt2         |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_vdir.unsigned_file_size.il.flanagansaxe.smt2         |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|try5_small_true_functions_fse-bfs_stty.visible.il.fse-bfs.smt2                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|unconstrained04.smt2                                                                        |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|unconstrained07.smt2                                                                        |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|unconstrained08.smt2                                                                        |  20.026s  |  20.026s  |   0.000s  | 0.0%|
</details>
