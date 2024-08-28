Comparing data and data


# SUMMARY
- LHS tests = 2000
- RHS tests = 2000
- LHS success = 1965  (98.25%)
- RHS success = 1965  (98.25%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls-sat
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: fbf30128640767911223f9e9c9a20ee1cdac9b79
Z3 branch: sls
Z3 options: "-T:20 -v:2 smt.sls.enable=true sat.smt=true -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" model_validate=true"
Z3 inputs: inputs/QF_BV_SAT
Z3 commit message: add virtual destructor

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls-sat
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: fbf30128640767911223f9e9c9a20ee1cdac9b79
Z3 branch: sls
Z3 options: "-T:20 -v:2 smt.sls.enable=true sat.smt=true -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" model_validate=true"
Z3 inputs: inputs/QF_BV_SAT
Z3 commit message: add virtual destructor

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |  20.769s  |  20.769s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  21.254s  |  21.254s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  20.774s  |  20.774s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  20.445s  |  20.445s  |   0.000s  | 0.0%|
|111.smt2                                                                                    |  20.813s  |  20.813s  |   0.000s  | 0.0%|
|113.smt2                                                                                    |   6.174s  |   6.174s  |   0.000s  | 0.0%|
|115.smt2                                                                                    |   9.314s  |   9.314s  |   0.000s  | 0.0%|
|15.smt2                                                                                     |  20.659s  |  20.659s  |   0.000s  | 0.0%|
|162.smt2                                                                                    |  21.033s  |  21.033s  |   0.000s  | 0.0%|
|170.smt2                                                                                    |  20.746s  |  20.746s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |  21.703s  |  21.703s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  21.707s  |  21.707s  |   0.000s  | 0.0%|
|29.smt2                                                                                     |  20.545s  |  20.545s  |   0.000s  | 0.0%|
|33.smt2                                                                                     |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|64.smt2                                                                                     |  21.366s  |  21.366s  |   0.000s  | 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |  21.491s  |  21.491s  |   0.000s  | 0.0%|
|80.smt2                                                                                     |  20.627s  |  20.627s  |   0.000s  | 0.0%|
|90.smt2                                                                                     |  21.139s  |  21.139s  |   0.000s  | 0.0%|
|94.smt2                                                                                     |  20.219s  |  20.219s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |  20.769s  |  20.769s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  21.254s  |  21.254s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  20.774s  |  20.774s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  20.445s  |  20.445s  |   0.000s  | 0.0%|
|111.smt2                                                                                    |  20.813s  |  20.813s  |   0.000s  | 0.0%|
|113.smt2                                                                                    |   6.174s  |   6.174s  |   0.000s  | 0.0%|
|115.smt2                                                                                    |   9.314s  |   9.314s  |   0.000s  | 0.0%|
|15.smt2                                                                                     |  20.659s  |  20.659s  |   0.000s  | 0.0%|
|162.smt2                                                                                    |  21.033s  |  21.033s  |   0.000s  | 0.0%|
|170.smt2                                                                                    |  20.746s  |  20.746s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |  21.703s  |  21.703s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  21.707s  |  21.707s  |   0.000s  | 0.0%|
|29.smt2                                                                                     |  20.545s  |  20.545s  |   0.000s  | 0.0%|
|33.smt2                                                                                     |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|64.smt2                                                                                     |  21.366s  |  21.366s  |   0.000s  | 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |  21.491s  |  21.491s  |   0.000s  | 0.0%|
|80.smt2                                                                                     |  20.627s  |  20.627s  |   0.000s  | 0.0%|
|90.smt2                                                                                     |  21.139s  |  21.139s  |   0.000s  | 0.0%|
|94.smt2                                                                                     |  20.219s  |  20.219s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |  20.769s  |  20.769s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  21.254s  |  21.254s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  20.774s  |  20.774s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  20.445s  |  20.445s  |   0.000s  | 0.0%|
|111.smt2                                                                                    |  20.813s  |  20.813s  |   0.000s  | 0.0%|
|113.smt2                                                                                    |   6.174s  |   6.174s  |   0.000s  | 0.0%|
|115.smt2                                                                                    |   9.314s  |   9.314s  |   0.000s  | 0.0%|
|15.smt2                                                                                     |  20.659s  |  20.659s  |   0.000s  | 0.0%|
|162.smt2                                                                                    |  21.033s  |  21.033s  |   0.000s  | 0.0%|
|170.smt2                                                                                    |  20.746s  |  20.746s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |  21.703s  |  21.703s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  21.707s  |  21.707s  |   0.000s  | 0.0%|
|29.smt2                                                                                     |  20.545s  |  20.545s  |   0.000s  | 0.0%|
|33.smt2                                                                                     |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|64.smt2                                                                                     |  21.366s  |  21.366s  |   0.000s  | 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |  21.491s  |  21.491s  |   0.000s  | 0.0%|
|80.smt2                                                                                     |  20.627s  |  20.627s  |   0.000s  | 0.0%|
|90.smt2                                                                                     |  21.139s  |  21.139s  |   0.000s  | 0.0%|
|94.smt2                                                                                     |  20.219s  |  20.219s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |  20.769s  |  20.769s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  21.254s  |  21.254s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  20.774s  |  20.774s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  20.445s  |  20.445s  |   0.000s  | 0.0%|
|111.smt2                                                                                    |  20.813s  |  20.813s  |   0.000s  | 0.0%|
|113.smt2                                                                                    |   6.174s  |   6.174s  |   0.000s  | 0.0%|
|115.smt2                                                                                    |   9.314s  |   9.314s  |   0.000s  | 0.0%|
|15.smt2                                                                                     |  20.659s  |  20.659s  |   0.000s  | 0.0%|
|162.smt2                                                                                    |  21.033s  |  21.033s  |   0.000s  | 0.0%|
|170.smt2                                                                                    |  20.746s  |  20.746s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |  21.703s  |  21.703s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  21.707s  |  21.707s  |   0.000s  | 0.0%|
|29.smt2                                                                                     |  20.545s  |  20.545s  |   0.000s  | 0.0%|
|33.smt2                                                                                     |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|64.smt2                                                                                     |  21.366s  |  21.366s  |   0.000s  | 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |  21.491s  |  21.491s  |   0.000s  | 0.0%|
|80.smt2                                                                                     |  20.627s  |  20.627s  |   0.000s  | 0.0%|
|90.smt2                                                                                     |  21.139s  |  21.139s  |   0.000s  | 0.0%|
|94.smt2                                                                                     |  20.219s  |  20.219s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|bench_1907.smt2                                                                            |  34.438s |105.0MiB|
|bench_1981.smt2                                                                            |  32.745s |104.0MiB|
|bench_5526.smt2                                                                            |  31.710s |105.0MiB|
|bench_2174.smt2                                                                            |  30.825s |98.98MiB|
|bench_1286.smt2                                                                            |  30.656s |101.0MiB|
|Sz512_15128_1.smt2                                                                         |  30.061s |115.0MiB|
|bench_1447.smt2                                                                            |  28.190s |99.0MiB|
|bench_3326.smt2                                                                            |  26.762s |100.0MiB|
|bench_3588.smt2                                                                            |  26.091s |107.0MiB|
|bench_3246.smt2                                                                            |  25.513s |231.0MiB|
|bin_libmsrpc_vc1225900.smt2                                                                |  24.895s |558.0MiB|
|gryzzles.8.lp.smt2                                                                         |  24.153s |120.0MiB|
|bench_5358.smt2                                                                            |  23.762s |84.292MiB|
|bench_5137.smt2                                                                            |  23.586s |82.408MiB|
|bench_232.smt2                                                                             |  23.309s |99.0MiB|
|bench_6665.smt2                                                                            |  23.058s |98.0MiB|
|bench_7306.smt2                                                                            |  22.903s |95.62MiB|
|bench_2831.smt2                                                                            |  22.865s |100.0MiB|
|bench_17335.smt2                                                                           |  22.813s |458.0MiB|
|bench_1522.smt2                                                                            |  22.580s |95.648MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|bench_1907.smt2                                                                            |  34.438s |105.0MiB|
|bench_1981.smt2                                                                            |  32.745s |104.0MiB|
|bench_5526.smt2                                                                            |  31.710s |105.0MiB|
|bench_2174.smt2                                                                            |  30.825s |98.98MiB|
|bench_1286.smt2                                                                            |  30.656s |101.0MiB|
|Sz512_15128_1.smt2                                                                         |  30.061s |115.0MiB|
|bench_1447.smt2                                                                            |  28.190s |99.0MiB|
|bench_3326.smt2                                                                            |  26.762s |100.0MiB|
|bench_3588.smt2                                                                            |  26.091s |107.0MiB|
|bench_3246.smt2                                                                            |  25.513s |231.0MiB|
|bin_libmsrpc_vc1225900.smt2                                                                |  24.895s |558.0MiB|
|gryzzles.8.lp.smt2                                                                         |  24.153s |120.0MiB|
|bench_5358.smt2                                                                            |  23.762s |84.292MiB|
|bench_5137.smt2                                                                            |  23.586s |82.408MiB|
|bench_232.smt2                                                                             |  23.309s |99.0MiB|
|bench_6665.smt2                                                                            |  23.058s |98.0MiB|
|bench_7306.smt2                                                                            |  22.903s |95.62MiB|
|bench_2831.smt2                                                                            |  22.865s |100.0MiB|
|bench_17335.smt2                                                                           |  22.813s |458.0MiB|
|bench_1522.smt2                                                                            |  22.580s |95.648MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |264.0MiB|264.0MiB|0B| 0.0%|
|100.smt2                                                                                    |296.0MiB|296.0MiB|0B| 0.0%|
|102.smt2                                                                                    |382.0MiB|382.0MiB|0B| 0.0%|
|108.smt2                                                                                    |802.0MiB|802.0MiB|0B| 0.0%|
|111.smt2                                                                                    |799.0MiB|799.0MiB|0B| 0.0%|
|113.smt2                                                                                    |191.0MiB|191.0MiB|0B| 0.0%|
|115.smt2                                                                                    |357.0MiB|357.0MiB|0B| 0.0%|
|15.smt2                                                                                     |219.0MiB|219.0MiB|0B| 0.0%|
|162.smt2                                                                                    |513.0MiB|513.0MiB|0B| 0.0%|
|170.smt2                                                                                    |522.0MiB|522.0MiB|0B| 0.0%|
|20.smt2                                                                                     |288.0MiB|288.0MiB|0B| 0.0%|
|26.smt2                                                                                     |276.0MiB|276.0MiB|0B| 0.0%|
|29.smt2                                                                                     |290.0MiB|290.0MiB|0B| 0.0%|
|33.smt2                                                                                     |235.0MiB|235.0MiB|0B| 0.0%|
|41.smt2                                                                                     |246.0MiB|246.0MiB|0B| 0.0%|
|64.smt2                                                                                     |334.0MiB|334.0MiB|0B| 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |78.72MiB|78.72MiB|0B| 0.0%|
|80.smt2                                                                                     |328.0MiB|328.0MiB|0B| 0.0%|
|90.smt2                                                                                     |334.0MiB|334.0MiB|0B| 0.0%|
|94.smt2                                                                                     |377.0MiB|377.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |264.0MiB|264.0MiB|0B| 0.0%|
|100.smt2                                                                                    |296.0MiB|296.0MiB|0B| 0.0%|
|102.smt2                                                                                    |382.0MiB|382.0MiB|0B| 0.0%|
|108.smt2                                                                                    |802.0MiB|802.0MiB|0B| 0.0%|
|111.smt2                                                                                    |799.0MiB|799.0MiB|0B| 0.0%|
|113.smt2                                                                                    |191.0MiB|191.0MiB|0B| 0.0%|
|115.smt2                                                                                    |357.0MiB|357.0MiB|0B| 0.0%|
|15.smt2                                                                                     |219.0MiB|219.0MiB|0B| 0.0%|
|162.smt2                                                                                    |513.0MiB|513.0MiB|0B| 0.0%|
|170.smt2                                                                                    |522.0MiB|522.0MiB|0B| 0.0%|
|20.smt2                                                                                     |288.0MiB|288.0MiB|0B| 0.0%|
|26.smt2                                                                                     |276.0MiB|276.0MiB|0B| 0.0%|
|29.smt2                                                                                     |290.0MiB|290.0MiB|0B| 0.0%|
|33.smt2                                                                                     |235.0MiB|235.0MiB|0B| 0.0%|
|41.smt2                                                                                     |246.0MiB|246.0MiB|0B| 0.0%|
|64.smt2                                                                                     |334.0MiB|334.0MiB|0B| 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |78.72MiB|78.72MiB|0B| 0.0%|
|80.smt2                                                                                     |328.0MiB|328.0MiB|0B| 0.0%|
|90.smt2                                                                                     |334.0MiB|334.0MiB|0B| 0.0%|
|94.smt2                                                                                     |377.0MiB|377.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |264.0MiB|264.0MiB|0B| 0.0%|
|100.smt2                                                                                    |296.0MiB|296.0MiB|0B| 0.0%|
|102.smt2                                                                                    |382.0MiB|382.0MiB|0B| 0.0%|
|108.smt2                                                                                    |802.0MiB|802.0MiB|0B| 0.0%|
|111.smt2                                                                                    |799.0MiB|799.0MiB|0B| 0.0%|
|113.smt2                                                                                    |191.0MiB|191.0MiB|0B| 0.0%|
|115.smt2                                                                                    |357.0MiB|357.0MiB|0B| 0.0%|
|15.smt2                                                                                     |219.0MiB|219.0MiB|0B| 0.0%|
|162.smt2                                                                                    |513.0MiB|513.0MiB|0B| 0.0%|
|170.smt2                                                                                    |522.0MiB|522.0MiB|0B| 0.0%|
|20.smt2                                                                                     |288.0MiB|288.0MiB|0B| 0.0%|
|26.smt2                                                                                     |276.0MiB|276.0MiB|0B| 0.0%|
|29.smt2                                                                                     |290.0MiB|290.0MiB|0B| 0.0%|
|33.smt2                                                                                     |235.0MiB|235.0MiB|0B| 0.0%|
|41.smt2                                                                                     |246.0MiB|246.0MiB|0B| 0.0%|
|64.smt2                                                                                     |334.0MiB|334.0MiB|0B| 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |78.72MiB|78.72MiB|0B| 0.0%|
|80.smt2                                                                                     |328.0MiB|328.0MiB|0B| 0.0%|
|90.smt2                                                                                     |334.0MiB|334.0MiB|0B| 0.0%|
|94.smt2                                                                                     |377.0MiB|377.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |264.0MiB|264.0MiB|0B| 0.0%|
|100.smt2                                                                                    |296.0MiB|296.0MiB|0B| 0.0%|
|102.smt2                                                                                    |382.0MiB|382.0MiB|0B| 0.0%|
|108.smt2                                                                                    |802.0MiB|802.0MiB|0B| 0.0%|
|111.smt2                                                                                    |799.0MiB|799.0MiB|0B| 0.0%|
|113.smt2                                                                                    |191.0MiB|191.0MiB|0B| 0.0%|
|115.smt2                                                                                    |357.0MiB|357.0MiB|0B| 0.0%|
|15.smt2                                                                                     |219.0MiB|219.0MiB|0B| 0.0%|
|162.smt2                                                                                    |513.0MiB|513.0MiB|0B| 0.0%|
|170.smt2                                                                                    |522.0MiB|522.0MiB|0B| 0.0%|
|20.smt2                                                                                     |288.0MiB|288.0MiB|0B| 0.0%|
|26.smt2                                                                                     |276.0MiB|276.0MiB|0B| 0.0%|
|29.smt2                                                                                     |290.0MiB|290.0MiB|0B| 0.0%|
|33.smt2                                                                                     |235.0MiB|235.0MiB|0B| 0.0%|
|41.smt2                                                                                     |246.0MiB|246.0MiB|0B| 0.0%|
|64.smt2                                                                                     |334.0MiB|334.0MiB|0B| 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |78.72MiB|78.72MiB|0B| 0.0%|
|80.smt2                                                                                     |328.0MiB|328.0MiB|0B| 0.0%|
|90.smt2                                                                                     |334.0MiB|334.0MiB|0B| 0.0%|
|94.smt2                                                                                     |377.0MiB|377.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|unconstrained10.smt2                                                                       |  19.510s |6374.0MiB|
|unconstrained07.smt2                                                                       |  19.554s |6372.0MiB|
|unconstrained08.smt2                                                                       |  19.260s |6372.0MiB|
|smulov4bw1024.smt2                                                                         |  19.991s |5475.0MiB|
|bench_3945.smt2                                                                            |  20.062s |5418.0MiB|
|unconstrained04.smt2                                                                       |  19.045s |3195.0MiB|
|bench_8495.smt2                                                                            |  19.688s |2249.0MiB|
|bench_1756.smt2                                                                            |   3.011s |1003.0MiB|
|servers_slapd_a_vc149789.smt2                                                              |  19.541s |897.0MiB|
|bench_102.smt2                                                                             |  20.053s |881.0MiB|
|108.smt2                                                                                   |  20.445s |802.0MiB|
|111.smt2                                                                                   |  20.813s |799.0MiB|
|div.c.20.smt2                                                                              |  21.689s |755.0MiB|
|div3.c.20.smt2                                                                             |  20.855s |745.0MiB|
|ndist.b.27984.smt2                                                                         |  19.337s |731.0MiB|
|ndist.b.28982.smt2                                                                         |   3.262s |706.0MiB|
|src_wget_vc17911.smt2                                                                      |  21.094s |703.0MiB|
|src_wget_vc17913.smt2                                                                      |  17.473s |702.0MiB|
|src_wget_vc17912.smt2                                                                      |  19.809s |699.0MiB|
|bench_10144.smt2                                                                           |  21.312s |597.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|unconstrained10.smt2                                                                       |  19.510s |6374.0MiB|
|unconstrained07.smt2                                                                       |  19.554s |6372.0MiB|
|unconstrained08.smt2                                                                       |  19.260s |6372.0MiB|
|smulov4bw1024.smt2                                                                         |  19.991s |5475.0MiB|
|bench_3945.smt2                                                                            |  20.062s |5418.0MiB|
|unconstrained04.smt2                                                                       |  19.045s |3195.0MiB|
|bench_8495.smt2                                                                            |  19.688s |2249.0MiB|
|bench_1756.smt2                                                                            |   3.011s |1003.0MiB|
|servers_slapd_a_vc149789.smt2                                                              |  19.541s |897.0MiB|
|bench_102.smt2                                                                             |  20.053s |881.0MiB|
|108.smt2                                                                                   |  20.445s |802.0MiB|
|111.smt2                                                                                   |  20.813s |799.0MiB|
|div.c.20.smt2                                                                              |  21.689s |755.0MiB|
|div3.c.20.smt2                                                                             |  20.855s |745.0MiB|
|ndist.b.27984.smt2                                                                         |  19.337s |731.0MiB|
|ndist.b.28982.smt2                                                                         |   3.262s |706.0MiB|
|src_wget_vc17911.smt2                                                                      |  21.094s |703.0MiB|
|src_wget_vc17913.smt2                                                                      |  17.473s |702.0MiB|
|src_wget_vc17912.smt2                                                                      |  19.809s |699.0MiB|
|bench_10144.smt2                                                                           |  21.312s |597.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |  20.769s  |  20.769s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  21.254s  |  21.254s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  20.774s  |  20.774s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  20.445s  |  20.445s  |   0.000s  | 0.0%|
|111.smt2                                                                                    |  20.813s  |  20.813s  |   0.000s  | 0.0%|
|113.smt2                                                                                    |   6.174s  |   6.174s  |   0.000s  | 0.0%|
|115.smt2                                                                                    |   9.314s  |   9.314s  |   0.000s  | 0.0%|
|15.smt2                                                                                     |  20.659s  |  20.659s  |   0.000s  | 0.0%|
|162.smt2                                                                                    |  21.033s  |  21.033s  |   0.000s  | 0.0%|
|170.smt2                                                                                    |  20.746s  |  20.746s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |  21.703s  |  21.703s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  21.707s  |  21.707s  |   0.000s  | 0.0%|
|29.smt2                                                                                     |  20.545s  |  20.545s  |   0.000s  | 0.0%|
|33.smt2                                                                                     |  19.989s  |  19.989s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|64.smt2                                                                                     |  21.366s  |  21.366s  |   0.000s  | 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |  21.491s  |  21.491s  |   0.000s  | 0.0%|
|80.smt2                                                                                     |  20.627s  |  20.627s  |   0.000s  | 0.0%|
|90.smt2                                                                                     |  21.139s  |  21.139s  |   0.000s  | 0.0%|
|94.smt2                                                                                     |  20.219s  |  20.219s  |   0.000s  | 0.0%|
|98.smt2                                                                                     |  20.844s  |  20.844s  |   0.000s  | 0.0%|
|Example_16.txt.smt2                                                                         |  21.833s  |  21.833s  |   0.000s  | 0.0%|
|Example_17.txt.smt2                                                                         |  22.576s  |  22.576s  |   0.000s  | 0.0%|
|Example_9.txt.smt2                                                                          |  19.814s  |  19.814s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_cyclic_scheduler.2.prop1_cc_ref_max.smt2                                       |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_cyclic_scheduler.4.prop1_cc_ref_max.smt2                                       |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_schedule_world.1.prop1_cc_ref_max.smt2                                         |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_swap_three_cc_ref_max.smt2                                                     |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_cyclic_scheduler.2.prop1_cc_ref_max.smt2                                        |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_eq_sdp_v4_cc_ref_max.smt2                                                       |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_resistance.2.prop1_cc_ref_max.smt2                                              |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_swap_two_cc_ref_max.smt2                                                        |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_synabs_cc_ref_max.smt2                                                          |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|QF_BV_counter_v_cc_ref_max.smt2                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|QF_BV_eq_sdp_v5_cc_ref_max.smt2                                                             |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|QF_BV_protocols.1.prop1_cc_ref_max.smt2                                                     |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|QF_BV_v_Unidec_cc_ref_max.smt2                                                              |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|Sz512_15128_0.smt2                                                                          |  21.263s  |  21.263s  |   0.000s  | 0.0%|
|Sz512_15128_1.smt2                                                                          |  30.061s  |  30.061s  |   0.000s  | 0.0%|
|Sz512_15128_2.smt2                                                                          |  21.044s  |  21.044s  |   0.000s  | 0.0%|
|Sz512_15128_3.smt2                                                                          |  20.931s  |  20.931s  |   0.000s  | 0.0%|
|VS3-benchmark-S1.smt2                                                                       |  21.120s  |  21.120s  |   0.000s  | 0.0%|
|a128test0016.smt2                                                                           |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|a164test0005.smt2                                                                           |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|a167test0001.smt2                                                                           |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|a185test0001.smt2                                                                           |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|a208test0005.smt2                                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|a213test0012.smt2                                                                           |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|a214test0017.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|a217test0011.smt2                                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|a218test0003.smt2                                                                           |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|a222test0008.smt2                                                                           |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|a324test0010.smt2                                                                           |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|a330test0007.smt2                                                                           |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|a331test0008.smt2                                                                           |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|a333test0009.smt2                                                                           |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|a335test0041.smt2                                                                           |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|a392test0051.smt2                                                                           |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|a393test0014.smt2                                                                           |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|a397test0029.smt2                                                                           |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|a402test0032.smt2                                                                           |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|a406test0030.smt2                                                                           |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|a407test0024.smt2                                                                           |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|a409test0002.smt2                                                                           |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|a421test0007.smt2                                                                           |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|a423test0008.smt2                                                                           |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|a430test0028.smt2                                                                           |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|a434test0027.smt2                                                                           |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|a448test0003.smt2                                                                           |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|a479test0010.smt2                                                                           |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|a494test0007.smt2                                                                           |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|a497test0020.smt2                                                                           |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|a503test0089.smt2                                                                           |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|a55test0003.smt2                                                                            |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|a58test0007.smt2                                                                            |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|a600test0040.smt2                                                                           |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|a601test0056.smt2                                                                           |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|a603test0055.smt2                                                                           |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|a605test0062.smt2                                                                           |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|a60test0004.smt2                                                                            |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|a611test0014.smt2                                                                           |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|a613test0087.smt2                                                                           |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|a614test0091.smt2                                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|a616test0001.smt2                                                                           |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|a620test0100.smt2                                                                           |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|a623test0035.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|a625test0095.smt2                                                                           |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|a628test0066.smt2                                                                           |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|a631test0073.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|a640test0019.smt2                                                                           |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|a649test0047.smt2                                                                           |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|a653test0023.smt2                                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|a657test0107.smt2                                                                           |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|a658test0026.smt2                                                                           |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|a663test0096.smt2                                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|a664test0013.smt2                                                                           |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|a665test0064.smt2                                                                           |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|a668test0098.smt2                                                                           |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|a669test0063.smt2                                                                           |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|a674test0008.smt2                                                                           |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|a676test0004.smt2                                                                           |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|a681test0048.smt2                                                                           |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|a683test0094.smt2                                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|a685test0080.smt2                                                                           |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|a689test0069.smt2                                                                           |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|a695test0015.smt2                                                                           |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|a97test0001.smt2                                                                            |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|adpcm.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|b188test0002.smt2                                                                           |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|b265test0001.smt2                                                                           |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|b26test0001.smt2                                                                            |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_1.smt2                                                                                |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|bench_10033.smt2                                                                            |  20.599s  |  20.599s  |   0.000s  | 0.0%|
|bench_10096.smt2                                                                            |  21.183s  |  21.183s  |   0.000s  | 0.0%|
|bench_10111.smt2                                                                            |  19.969s  |  19.969s  |   0.000s  | 0.0%|
|bench_1012.smt2                                                                             |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|bench_10127.smt2                                                                            |  19.427s  |  19.427s  |   0.000s  | 0.0%|
|bench_1013.smt2                                                                             |  21.236s  |  21.236s  |   0.000s  | 0.0%|
|bench_10144.smt2                                                                            |  21.312s  |  21.312s  |   0.000s  | 0.0%|
|bench_1017.smt2                                                                             |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bench_102.smt2                                                                              |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|bench_10228.smt2                                                                            |   0.792s  |   0.792s  |   0.000s  | 0.0%|
|bench_10306.smt2                                                                            |  22.082s  |  22.082s  |   0.000s  | 0.0%|
|bench_1041.smt2                                                                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_1043.smt2                                                                             |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|bench_10451.smt2                                                                            |   3.554s  |   3.554s  |   0.000s  | 0.0%|
|bench_1050.smt2                                                                             |  21.393s  |  21.393s  |   0.000s  | 0.0%|
|bench_1053.smt2                                                                             |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench_1055.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_10579.smt2                                                                            |  20.522s  |  20.522s  |   0.000s  | 0.0%|
|bench_1059.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_1063.smt2                                                                             |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|bench_10696.smt2                                                                            |  19.541s  |  19.541s  |   0.000s  | 0.0%|
|bench_10714.smt2                                                                            |   0.598s  |   0.598s  |   0.000s  | 0.0%|
|bench_10726.smt2                                                                            |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|bench_10737.smt2                                                                            |  21.910s  |  21.910s  |   0.000s  | 0.0%|
|bench_10784.smt2                                                                            |  21.551s  |  21.551s  |   0.000s  | 0.0%|
|bench_10791.smt2                                                                            |  20.541s  |  20.541s  |   0.000s  | 0.0%|
|bench_10800.smt2                                                                            |  20.393s  |  20.393s  |   0.000s  | 0.0%|
|bench_1081.smt2                                                                             |  20.590s  |  20.590s  |   0.000s  | 0.0%|
|bench_10815.smt2                                                                            |  21.423s  |  21.423s  |   0.000s  | 0.0%|
|bench_1082.smt2                                                                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_10832.smt2                                                                            |   1.352s  |   1.352s  |   0.000s  | 0.0%|
|bench_10841.smt2                                                                            |  19.841s  |  19.841s  |   0.000s  | 0.0%|
|bench_1088.smt2                                                                             |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench_1093.smt2                                                                             |  20.313s  |  20.313s  |   0.000s  | 0.0%|
|bench_1094.smt2                                                                             |   0.882s  |   0.882s  |   0.000s  | 0.0%|
|bench_10940.smt2                                                                            |  19.950s  |  19.950s  |   0.000s  | 0.0%|
|bench_1099.smt2                                                                             |  20.839s  |  20.839s  |   0.000s  | 0.0%|
|bench_11014.smt2                                                                            |  20.992s  |  20.992s  |   0.000s  | 0.0%|
|bench_11027.smt2                                                                            |   0.420s  |   0.420s  |   0.000s  | 0.0%|
|bench_11032.smt2                                                                            |   1.380s  |   1.380s  |   0.000s  | 0.0%|
|bench_11033.smt2                                                                            |  21.038s  |  21.038s  |   0.000s  | 0.0%|
|bench_1106.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_1111.smt2                                                                             |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bench_11110.smt2                                                                            |  20.327s  |  20.327s  |   0.000s  | 0.0%|
|bench_1113.smt2                                                                             |  21.531s  |  21.531s  |   0.000s  | 0.0%|
|bench_11151.smt2                                                                            |  21.124s  |  21.124s  |   0.000s  | 0.0%|
|bench_112.smt2                                                                              |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|bench_1123.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_11232.smt2                                                                            |  19.705s  |  19.705s  |   0.000s  | 0.0%|
|bench_113.smt2                                                                              |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_11341.smt2                                                                            |   1.497s  |   1.497s  |   0.000s  | 0.0%|
|bench_11357.smt2                                                                            |   2.676s  |   2.676s  |   0.000s  | 0.0%|
|bench_1136.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_11408.smt2                                                                            |  19.496s  |  19.496s  |   0.000s  | 0.0%|
|bench_1143.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_1145.smt2                                                                             |  20.296s  |  20.296s  |   0.000s  | 0.0%|
|bench_11473.smt2                                                                            |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|bench_1159.smt2                                                                             |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|bench_1166.smt2                                                                             |  21.020s  |  21.020s  |   0.000s  | 0.0%|
|bench_1168.smt2                                                                             |  20.900s  |  20.900s  |   0.000s  | 0.0%|
|bench_11696.smt2                                                                            |  21.672s  |  21.672s  |   0.000s  | 0.0%|
|bench_11708.smt2                                                                            |  21.189s  |  21.189s  |   0.000s  | 0.0%|
|bench_11736.smt2                                                                            |  20.383s  |  20.383s  |   0.000s  | 0.0%|
|bench_1179.smt2                                                                             |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|bench_1180.smt2                                                                             |  20.899s  |  20.899s  |   0.000s  | 0.0%|
|bench_11811.smt2                                                                            |   2.076s  |   2.076s  |   0.000s  | 0.0%|
|bench_11826.smt2                                                                            |  16.329s  |  16.329s  |   0.000s  | 0.0%|
|bench_1184.smt2                                                                             |  21.570s  |  21.570s  |   0.000s  | 0.0%|
|bench_1187.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_119.smt2                                                                              |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_11931.smt2                                                                            |   2.638s  |   2.638s  |   0.000s  | 0.0%|
|bench_1196.smt2                                                                             |  21.661s  |  21.661s  |   0.000s  | 0.0%|
|bench_11971.smt2                                                                            |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|bench_1199.smt2                                                                             |  19.736s  |  19.736s  |   0.000s  | 0.0%|
|bench_120.smt2                                                                              |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_12006.smt2                                                                            |  20.868s  |  20.868s  |   0.000s  | 0.0%|
|bench_1201.smt2                                                                             |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|bench_1202.smt2                                                                             |   0.698s  |   0.698s  |   0.000s  | 0.0%|
|bench_1204.smt2                                                                             |  20.497s  |  20.497s  |   0.000s  | 0.0%|
|bench_12059.smt2                                                                            |  22.145s  |  22.145s  |   0.000s  | 0.0%|
|bench_12158.smt2                                                                            |  20.122s  |  20.122s  |   0.000s  | 0.0%|
|bench_1218.smt2                                                                             |  21.674s  |  21.674s  |   0.000s  | 0.0%|
|bench_12204.smt2                                                                            |   1.773s  |   1.773s  |   0.000s  | 0.0%|
|bench_1222.smt2                                                                             |  20.662s  |  20.662s  |   0.000s  | 0.0%|
|bench_12224.smt2                                                                            |  20.491s  |  20.491s  |   0.000s  | 0.0%|
|bench_12246.smt2                                                                            |  20.613s  |  20.613s  |   0.000s  | 0.0%|
|bench_1228.smt2                                                                             |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bench_1229.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_1233.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_1235.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_1236.smt2                                                                             |  19.621s  |  19.621s  |   0.000s  | 0.0%|
|bench_12422.smt2                                                                            |   3.297s  |   3.297s  |   0.000s  | 0.0%|
|bench_12473.smt2                                                                            |  20.852s  |  20.852s  |   0.000s  | 0.0%|
|bench_1249.smt2                                                                             |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|bench_1250.smt2                                                                             |  20.600s  |  20.600s  |   0.000s  | 0.0%|
|bench_1252.smt2                                                                             |  21.252s  |  21.252s  |   0.000s  | 0.0%|
|bench_1253.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_1256.smt2                                                                             |  21.143s  |  21.143s  |   0.000s  | 0.0%|
|bench_12625.smt2                                                                            |   0.628s  |   0.628s  |   0.000s  | 0.0%|
|bench_12655.smt2                                                                            |  21.343s  |  21.343s  |   0.000s  | 0.0%|
|bench_1266.smt2                                                                             |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|bench_1270.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_1278.smt2                                                                             |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|bench_1280.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_12821.smt2                                                                            |   0.670s  |   0.670s  |   0.000s  | 0.0%|
|bench_1283.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_1285.smt2                                                                             |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bench_1286.smt2                                                                             |  30.656s  |  30.656s  |   0.000s  | 0.0%|
|bench_129.smt2                                                                              |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_1306.smt2                                                                             |  20.111s  |  20.111s  |   0.000s  | 0.0%|
|bench_1307.smt2                                                                             |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|bench_13129.smt2                                                                            |  21.251s  |  21.251s  |   0.000s  | 0.0%|
|bench_13147.smt2                                                                            |   5.999s  |   5.999s  |   0.000s  | 0.0%|
|bench_1318.smt2                                                                             |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|bench_1323.smt2                                                                             |  20.624s  |  20.624s  |   0.000s  | 0.0%|
|bench_13284.smt2                                                                            |   0.732s  |   0.732s  |   0.000s  | 0.0%|
|bench_1329.smt2                                                                             |   0.920s  |   0.920s  |   0.000s  | 0.0%|
|bench_1332.smt2                                                                             |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench_13336.smt2                                                                            |   2.562s  |   2.562s  |   0.000s  | 0.0%|
|bench_1335.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_1336.smt2                                                                             |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|bench_1338.smt2                                                                             |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|bench_13483.smt2                                                                            |  21.383s  |  21.383s  |   0.000s  | 0.0%|
|bench_1349.smt2                                                                             |  20.571s  |  20.571s  |   0.000s  | 0.0%|
|bench_135.smt2                                                                              |  19.846s  |  19.846s  |   0.000s  | 0.0%|
|bench_1350.smt2                                                                             |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|bench_1355.smt2                                                                             |  21.448s  |  21.448s  |   0.000s  | 0.0%|
|bench_1359.smt2                                                                             |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|bench_1361.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_1365.smt2                                                                             |  21.339s  |  21.339s  |   0.000s  | 0.0%|
|bench_1367.smt2                                                                             |   0.322s  |   0.322s  |   0.000s  | 0.0%|
|bench_1374.smt2                                                                             |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|bench_13744.smt2                                                                            |   2.149s  |   2.149s  |   0.000s  | 0.0%|
|bench_13773.smt2                                                                            |  21.214s  |  21.214s  |   0.000s  | 0.0%|
|bench_1379.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_13790.smt2                                                                            |  20.757s  |  20.757s  |   0.000s  | 0.0%|
|bench_1386.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_1388.smt2                                                                             |  21.160s  |  21.160s  |   0.000s  | 0.0%|
|bench_1389.smt2                                                                             |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|bench_1391.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_1400.smt2                                                                             |   7.365s  |   7.365s  |   0.000s  | 0.0%|
|bench_1401.smt2                                                                             |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|bench_1405.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_141.smt2                                                                              |  19.297s  |  19.297s  |   0.000s  | 0.0%|
|bench_1412.smt2                                                                             |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|bench_1414.smt2                                                                             |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|bench_14156.smt2                                                                            |  20.166s  |  20.166s  |   0.000s  | 0.0%|
|bench_14161.smt2                                                                            |  20.317s  |  20.317s  |   0.000s  | 0.0%|
|bench_14165.smt2                                                                            |  20.982s  |  20.982s  |   0.000s  | 0.0%|
|bench_1417.smt2                                                                             |   1.081s  |   1.081s  |   0.000s  | 0.0%|
|bench_142.smt2                                                                              |  11.433s  |  11.433s  |   0.000s  | 0.0%|
|bench_14209.smt2                                                                            |  21.035s  |  21.035s  |   0.000s  | 0.0%|
|bench_1424.smt2                                                                             |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|bench_14284.smt2                                                                            |  21.140s  |  21.140s  |   0.000s  | 0.0%|
|bench_143.smt2                                                                              |  20.189s  |  20.189s  |   0.000s  | 0.0%|
|bench_1434.smt2                                                                             |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|bench_14358.smt2                                                                            |  21.241s  |  21.241s  |   0.000s  | 0.0%|
|bench_1440.smt2                                                                             |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|bench_1441.smt2                                                                             |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|bench_1442.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_1445.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_1446.smt2                                                                             |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|bench_14461.smt2                                                                            |  21.522s  |  21.522s  |   0.000s  | 0.0%|
|bench_1447.smt2                                                                             |  28.190s  |  28.190s  |   0.000s  | 0.0%|
|bench_14486.smt2                                                                            |  20.479s  |  20.479s  |   0.000s  | 0.0%|
|bench_145.smt2                                                                              |  20.918s  |  20.918s  |   0.000s  | 0.0%|
|bench_1453.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_1455.smt2                                                                             |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|bench_14595.smt2                                                                            |   0.656s  |   0.656s  |   0.000s  | 0.0%|
|bench_14598.smt2                                                                            |  13.968s  |  13.968s  |   0.000s  | 0.0%|
|bench_1465.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_1467.smt2                                                                             |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench_1470.smt2                                                                             |   2.064s  |   2.064s  |   0.000s  | 0.0%|
|bench_14720.smt2                                                                            |   2.126s  |   2.126s  |   0.000s  | 0.0%|
|bench_1476.smt2                                                                             |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|bench_1477.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_1478.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_1481.smt2                                                                             |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|bench_14817.smt2                                                                            |  19.304s  |  19.304s  |   0.000s  | 0.0%|
|bench_14861.smt2                                                                            |  18.119s  |  18.119s  |   0.000s  | 0.0%|
|bench_14875.smt2                                                                            |  19.918s  |  19.918s  |   0.000s  | 0.0%|
|bench_14885.smt2                                                                            |  20.388s  |  20.388s  |   0.000s  | 0.0%|
|bench_14932.smt2                                                                            |  21.691s  |  21.691s  |   0.000s  | 0.0%|
|bench_14941.smt2                                                                            |  21.351s  |  21.351s  |   0.000s  | 0.0%|
|bench_1495.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_1496.smt2                                                                             |  20.812s  |  20.812s  |   0.000s  | 0.0%|
|bench_1498.smt2                                                                             |  20.803s  |  20.803s  |   0.000s  | 0.0%|
|bench_14984.smt2                                                                            |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|bench_15.smt2                                                                               |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_1504.smt2                                                                             |  21.200s  |  21.200s  |   0.000s  | 0.0%|
|bench_15105.smt2                                                                            |  20.130s  |  20.130s  |   0.000s  | 0.0%|
|bench_15128.smt2                                                                            |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|bench_1522.smt2                                                                             |  22.580s  |  22.580s  |   0.000s  | 0.0%|
|bench_1523.smt2                                                                             |  22.495s  |  22.495s  |   0.000s  | 0.0%|
|bench_15255.smt2                                                                            |  20.552s  |  20.552s  |   0.000s  | 0.0%|
|bench_1532.smt2                                                                             |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|bench_15365.smt2                                                                            |  20.011s  |  20.011s  |   0.000s  | 0.0%|
|bench_154.smt2                                                                              |  20.400s  |  20.400s  |   0.000s  | 0.0%|
|bench_1545.smt2                                                                             |   0.304s  |   0.304s  |   0.000s  | 0.0%|
|bench_1549.smt2                                                                             |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|bench_15547.smt2                                                                            |  20.596s  |  20.596s  |   0.000s  | 0.0%|
|bench_1555.smt2                                                                             |  21.676s  |  21.676s  |   0.000s  | 0.0%|
|bench_1559.smt2                                                                             |  21.712s  |  21.712s  |   0.000s  | 0.0%|
|bench_1560.smt2                                                                             |  21.435s  |  21.435s  |   0.000s  | 0.0%|
|bench_1567.smt2                                                                             |  20.897s  |  20.897s  |   0.000s  | 0.0%|
|bench_1568.smt2                                                                             |   0.988s  |   0.988s  |   0.000s  | 0.0%|
|bench_15711.smt2                                                                            |  20.482s  |  20.482s  |   0.000s  | 0.0%|
|bench_15719.smt2                                                                            |  21.264s  |  21.264s  |   0.000s  | 0.0%|
|bench_1573.smt2                                                                             |   1.596s  |   1.596s  |   0.000s  | 0.0%|
|bench_1578.smt2                                                                             |  20.489s  |  20.489s  |   0.000s  | 0.0%|
|bench_15783.smt2                                                                            |  21.790s  |  21.790s  |   0.000s  | 0.0%|
|bench_1583.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_15833.smt2                                                                            |  20.618s  |  20.618s  |   0.000s  | 0.0%|
|bench_1585.smt2                                                                             |  20.830s  |  20.830s  |   0.000s  | 0.0%|
|bench_1586.smt2                                                                             |  21.789s  |  21.789s  |   0.000s  | 0.0%|
|bench_1588.smt2                                                                             |   2.151s  |   2.151s  |   0.000s  | 0.0%|
|bench_160.smt2                                                                              |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_1603.smt2                                                                             |   3.496s  |   3.496s  |   0.000s  | 0.0%|
|bench_16064.smt2                                                                            |   0.881s  |   0.881s  |   0.000s  | 0.0%|
|bench_1608.smt2                                                                             |  20.154s  |  20.154s  |   0.000s  | 0.0%|
|bench_1610.smt2                                                                             |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|bench_1614.smt2                                                                             |  22.217s  |  22.217s  |   0.000s  | 0.0%|
|bench_1621.smt2                                                                             |  20.909s  |  20.909s  |   0.000s  | 0.0%|
|bench_16245.smt2                                                                            |  21.086s  |  21.086s  |   0.000s  | 0.0%|
|bench_1627.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_1629.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_163.smt2                                                                              |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_1630.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_1636.smt2                                                                             |   3.511s  |   3.511s  |   0.000s  | 0.0%|
|bench_16382.smt2                                                                            |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|bench_16409.smt2                                                                            |  21.131s  |  21.131s  |   0.000s  | 0.0%|
|bench_1643.smt2                                                                             |  21.678s  |  21.678s  |   0.000s  | 0.0%|
|bench_16467.smt2                                                                            |  20.198s  |  20.198s  |   0.000s  | 0.0%|
|bench_165.smt2                                                                              |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_1652.smt2                                                                             |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|bench_1657.smt2                                                                             |  20.362s  |  20.362s  |   0.000s  | 0.0%|
|bench_16594.smt2                                                                            |  20.205s  |  20.205s  |   0.000s  | 0.0%|
|bench_166.smt2                                                                              |  19.750s  |  19.750s  |   0.000s  | 0.0%|
|bench_1663.smt2                                                                             |  21.116s  |  21.116s  |   0.000s  | 0.0%|
|bench_16640.smt2                                                                            |  12.568s  |  12.568s  |   0.000s  | 0.0%|
|bench_1665.smt2                                                                             |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|bench_1670.smt2                                                                             |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|bench_16707.smt2                                                                            |  22.260s  |  22.260s  |   0.000s  | 0.0%|
|bench_1674.smt2                                                                             |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|bench_168.smt2                                                                              |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_1680.smt2                                                                             |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|bench_1686.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_16862.smt2                                                                            |  21.131s  |  21.131s  |   0.000s  | 0.0%|
|bench_1697.smt2                                                                             |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|bench_17033.smt2                                                                            |  20.170s  |  20.170s  |   0.000s  | 0.0%|
|bench_1707.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_17082.smt2                                                                            |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|bench_171.smt2                                                                              |  19.625s  |  19.625s  |   0.000s  | 0.0%|
|bench_1710.smt2                                                                             |  21.340s  |  21.340s  |   0.000s  | 0.0%|
|bench_1712.smt2                                                                             |  20.969s  |  20.969s  |   0.000s  | 0.0%|
|bench_1717.smt2                                                                             |  21.772s  |  21.772s  |   0.000s  | 0.0%|
|bench_1720.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_1721.smt2                                                                             |  20.484s  |  20.484s  |   0.000s  | 0.0%|
|bench_1724.smt2                                                                             |  20.476s  |  20.476s  |   0.000s  | 0.0%|
|bench_17324.smt2                                                                            |   2.657s  |   2.657s  |   0.000s  | 0.0%|
|bench_17335.smt2                                                                            |  22.813s  |  22.813s  |   0.000s  | 0.0%|
|bench_1739.smt2                                                                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_1748.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_1756.smt2                                                                             |   3.011s  |   3.011s  |   0.000s  | 0.0%|
|bench_1757.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_1759.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_1760.smt2                                                                             |  20.725s  |  20.725s  |   0.000s  | 0.0%|
|bench_1761.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_1763.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_1769.smt2                                                                             |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|bench_1770.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_17759.smt2                                                                            |  20.572s  |  20.572s  |   0.000s  | 0.0%|
|bench_1778.smt2                                                                             |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|bench_179.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1802.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_1810.smt2                                                                             |  20.945s  |  20.945s  |   0.000s  | 0.0%|
|bench_1811.smt2                                                                             |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|bench_1816.smt2                                                                             |  20.274s  |  20.274s  |   0.000s  | 0.0%|
|bench_1822.smt2                                                                             |  20.909s  |  20.909s  |   0.000s  | 0.0%|
|bench_1829.smt2                                                                             |  21.309s  |  21.309s  |   0.000s  | 0.0%|
|bench_183.smt2                                                                              |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bench_1837.smt2                                                                             |  20.469s  |  20.469s  |   0.000s  | 0.0%|
|bench_1839.smt2                                                                             |  20.852s  |  20.852s  |   0.000s  | 0.0%|
|bench_1841.smt2                                                                             |  20.403s  |  20.403s  |   0.000s  | 0.0%|
|bench_1844.smt2                                                                             |  20.688s  |  20.688s  |   0.000s  | 0.0%|
|bench_1851.smt2                                                                             |  20.991s  |  20.991s  |   0.000s  | 0.0%|
|bench_1858.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_1863.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_1864.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_1869.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_187.smt2                                                                              |  21.516s  |  21.516s  |   0.000s  | 0.0%|
|bench_1872.smt2                                                                             |  21.477s  |  21.477s  |   0.000s  | 0.0%|
|bench_1873.smt2                                                                             |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench_1878.smt2                                                                             |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|bench_1880.smt2                                                                             |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|bench_1882.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_1888.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_1897.smt2                                                                             |  20.426s  |  20.426s  |   0.000s  | 0.0%|
|bench_1900.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_1904.smt2                                                                             |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|bench_1905.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_1907.smt2                                                                             |  34.438s  |  34.438s  |   0.000s  | 0.0%|
|bench_1909.smt2                                                                             |  20.984s  |  20.984s  |   0.000s  | 0.0%|
|bench_1937.smt2                                                                             |  21.020s  |  21.020s  |   0.000s  | 0.0%|
|bench_1942.smt2                                                                             |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|bench_1946.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_1953.smt2                                                                             |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|bench_1957.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_1958.smt2                                                                             |  20.724s  |  20.724s  |   0.000s  | 0.0%|
|bench_1961.smt2                                                                             |  19.504s  |  19.504s  |   0.000s  | 0.0%|
|bench_1963.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_1976.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_1977.smt2                                                                             |  20.099s  |  20.099s  |   0.000s  | 0.0%|
|bench_1981.smt2                                                                             |  32.745s  |  32.745s  |   0.000s  | 0.0%|
|bench_1985.smt2                                                                             |  21.420s  |  21.420s  |   0.000s  | 0.0%|
|bench_1992.smt2                                                                             |  21.325s  |  21.325s  |   0.000s  | 0.0%|
|bench_1993.smt2                                                                             |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|bench_1996.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_200.smt2                                                                              |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_2021.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_2022.smt2                                                                             |  20.807s  |  20.807s  |   0.000s  | 0.0%|
|bench_2034.smt2                                                                             |  21.402s  |  21.402s  |   0.000s  | 0.0%|
|bench_204.smt2                                                                              |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_2044.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_2050.smt2                                                                             |  21.148s  |  21.148s  |   0.000s  | 0.0%|
|bench_2059.smt2                                                                             |  20.703s  |  20.703s  |   0.000s  | 0.0%|
|bench_2067.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_2070.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_2072.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_2075.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_2076.smt2                                                                             |  20.913s  |  20.913s  |   0.000s  | 0.0%|
|bench_2077.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_208.smt2                                                                              |   5.178s  |   5.178s  |   0.000s  | 0.0%|
|bench_2083.smt2                                                                             |  20.889s  |  20.889s  |   0.000s  | 0.0%|
|bench_2097.smt2                                                                             |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|bench_2099.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_2102.smt2                                                                             |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|bench_2108.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_2113.smt2                                                                             |   1.127s  |   1.127s  |   0.000s  | 0.0%|
|bench_2115.smt2                                                                             |  20.690s  |  20.690s  |   0.000s  | 0.0%|
|bench_2117.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_2121.smt2                                                                             |  21.453s  |  21.453s  |   0.000s  | 0.0%|
|bench_2122.smt2                                                                             |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|bench_2129.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_214.smt2                                                                              |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_2141.smt2                                                                             |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|bench_2144.smt2                                                                             |  20.605s  |  20.605s  |   0.000s  | 0.0%|
|bench_2148.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_2149.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2150.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_2152.smt2                                                                             |  20.906s  |  20.906s  |   0.000s  | 0.0%|
|bench_2155.smt2                                                                             |  20.166s  |  20.166s  |   0.000s  | 0.0%|
|bench_2161.smt2                                                                             |  21.519s  |  21.519s  |   0.000s  | 0.0%|
|bench_2162.smt2                                                                             |  20.785s  |  20.785s  |   0.000s  | 0.0%|
|bench_2167.smt2                                                                             |  20.889s  |  20.889s  |   0.000s  | 0.0%|
|bench_2169.smt2                                                                             |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|bench_2170.smt2                                                                             |   2.112s  |   2.112s  |   0.000s  | 0.0%|
|bench_2174.smt2                                                                             |  30.825s  |  30.825s  |   0.000s  | 0.0%|
|bench_2175.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_2183.smt2                                                                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|bench_2188.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_2189.smt2                                                                             |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|bench_2192.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_2197.smt2                                                                             |  20.538s  |  20.538s  |   0.000s  | 0.0%|
|bench_2202.smt2                                                                             |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|bench_2207.smt2                                                                             |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|bench_2211.smt2                                                                             |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|bench_2221.smt2                                                                             |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|bench_2225.smt2                                                                             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|bench_2229.smt2                                                                             |  14.537s  |  14.537s  |   0.000s  | 0.0%|
|bench_2233.smt2                                                                             |   1.449s  |   1.449s  |   0.000s  | 0.0%|
|bench_224.smt2                                                                              |   0.909s  |   0.909s  |   0.000s  | 0.0%|
|bench_2248.smt2                                                                             |  21.553s  |  21.553s  |   0.000s  | 0.0%|
|bench_225.smt2                                                                              |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|bench_2257.smt2                                                                             |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|bench_2258.smt2                                                                             |  20.715s  |  20.715s  |   0.000s  | 0.0%|
|bench_2261.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_2263.smt2                                                                             |  21.492s  |  21.492s  |   0.000s  | 0.0%|
|bench_2264.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_2265.smt2                                                                             |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|bench_2268.smt2                                                                             |  20.807s  |  20.807s  |   0.000s  | 0.0%|
|bench_2269.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_2272.smt2                                                                             |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|bench_2278.smt2                                                                             |  20.200s  |  20.200s  |   0.000s  | 0.0%|
|bench_228.smt2                                                                              |  11.419s  |  11.419s  |   0.000s  | 0.0%|
|bench_2284.smt2                                                                             |  19.740s  |  19.740s  |   0.000s  | 0.0%|
|bench_2291.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_2293.smt2                                                                             |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|bench_2295.smt2                                                                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|bench_230.smt2                                                                              |   4.679s  |   4.679s  |   0.000s  | 0.0%|
|bench_2304.smt2                                                                             |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|bench_2308.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_2309.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_2312.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_232.smt2                                                                              |  23.309s  |  23.309s  |   0.000s  | 0.0%|
|bench_2325.smt2                                                                             |  21.193s  |  21.193s  |   0.000s  | 0.0%|
|bench_2326.smt2                                                                             |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|bench_2327.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_2330.smt2                                                                             |  21.627s  |  21.627s  |   0.000s  | 0.0%|
|bench_234.smt2                                                                              |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_2349.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_2351.smt2                                                                             |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|bench_2358.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_2360.smt2                                                                             |  20.149s  |  20.149s  |   0.000s  | 0.0%|
|bench_238.smt2                                                                              |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_2380.smt2                                                                             |  20.404s  |  20.404s  |   0.000s  | 0.0%|
|bench_2384.smt2                                                                             |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|bench_2386.smt2                                                                             |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|bench_2395.smt2                                                                             |  12.132s  |  12.132s  |   0.000s  | 0.0%|
|bench_2397.smt2                                                                             |  21.275s  |  21.275s  |   0.000s  | 0.0%|
|bench_2400.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_2406.smt2                                                                             |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|bench_2407.smt2                                                                             |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|bench_2420.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2425.smt2                                                                             |  21.115s  |  21.115s  |   0.000s  | 0.0%|
|bench_2428.smt2                                                                             |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|bench_243.smt2                                                                              |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_2431.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_2432.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_2433.smt2                                                                             |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|bench_2435.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_2436.smt2                                                                             |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|bench_2443.smt2                                                                             |  21.282s  |  21.282s  |   0.000s  | 0.0%|
|bench_2463.smt2                                                                             |  21.138s  |  21.138s  |   0.000s  | 0.0%|
|bench_2469.smt2                                                                             |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|bench_247.smt2                                                                              |   2.813s  |   2.813s  |   0.000s  | 0.0%|
|bench_2475.smt2                                                                             |  21.940s  |  21.940s  |   0.000s  | 0.0%|
|bench_248.smt2                                                                              |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_2493.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_2499.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_2503.smt2                                                                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_2507.smt2                                                                             |   2.591s  |   2.591s  |   0.000s  | 0.0%|
|bench_2514.smt2                                                                             |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bench_2517.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_2521.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_2524.smt2                                                                             |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|bench_253.smt2                                                                              |   4.056s  |   4.056s  |   0.000s  | 0.0%|
|bench_2547.smt2                                                                             |  21.934s  |  21.934s  |   0.000s  | 0.0%|
|bench_2548.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_2550.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_2551.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_2552.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_2558.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_2566.smt2                                                                             |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|bench_2567.smt2                                                                             |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|bench_2573.smt2                                                                             |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bench_2574.smt2                                                                             |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|bench_2579.smt2                                                                             |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|bench_2580.smt2                                                                             |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|bench_2582.smt2                                                                             |  10.179s  |  10.179s  |   0.000s  | 0.0%|
|bench_2586.smt2                                                                             |  13.236s  |  13.236s  |   0.000s  | 0.0%|
|bench_259.smt2                                                                              |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bench_2594.smt2                                                                             |  21.130s  |  21.130s  |   0.000s  | 0.0%|
|bench_2599.smt2                                                                             |  20.539s  |  20.539s  |   0.000s  | 0.0%|
|bench_2602.smt2                                                                             |   8.082s  |   8.082s  |   0.000s  | 0.0%|
|bench_2606.smt2                                                                             |  21.962s  |  21.962s  |   0.000s  | 0.0%|
|bench_261.smt2                                                                              |  19.677s  |  19.677s  |   0.000s  | 0.0%|
|bench_2612.smt2                                                                             |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench_2613.smt2                                                                             |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|bench_2620.smt2                                                                             |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|bench_2621.smt2                                                                             |  21.500s  |  21.500s  |   0.000s  | 0.0%|
|bench_2628.smt2                                                                             |  20.891s  |  20.891s  |   0.000s  | 0.0%|
|bench_2629.smt2                                                                             |  20.696s  |  20.696s  |   0.000s  | 0.0%|
|bench_2635.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_2639.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_2642.smt2                                                                             |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench_2644.smt2                                                                             |  21.626s  |  21.626s  |   0.000s  | 0.0%|
|bench_2645.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_2646.smt2                                                                             |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|bench_2650.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_2653.smt2                                                                             |  21.946s  |  21.946s  |   0.000s  | 0.0%|
|bench_2659.smt2                                                                             |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|bench_267.smt2                                                                              |   4.340s  |   4.340s  |   0.000s  | 0.0%|
|bench_2671.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_2675.smt2                                                                             |   3.759s  |   3.759s  |   0.000s  | 0.0%|
|bench_2676.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_2682.smt2                                                                             |  21.354s  |  21.354s  |   0.000s  | 0.0%|
|bench_2688.smt2                                                                             |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|bench_270.smt2                                                                              |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|bench_2701.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_2704.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_2710.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_2717.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_2724.smt2                                                                             |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|bench_2727.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_2729.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_2735.smt2                                                                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_2737.smt2                                                                             |   0.300s  |   0.300s  |   0.000s  | 0.0%|
|bench_2747.smt2                                                                             |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|bench_2750.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_2755.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_2757.smt2                                                                             |  21.324s  |  21.324s  |   0.000s  | 0.0%|
|bench_276.smt2                                                                              |  20.992s  |  20.992s  |   0.000s  | 0.0%|
|bench_2767.smt2                                                                             |  20.884s  |  20.884s  |   0.000s  | 0.0%|
|bench_2773.smt2                                                                             |  21.468s  |  21.468s  |   0.000s  | 0.0%|
|bench_2779.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_2789.smt2                                                                             |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|bench_279.smt2                                                                              |  19.543s  |  19.543s  |   0.000s  | 0.0%|
|bench_2798.smt2                                                                             |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|bench_28.smt2                                                                               |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bench_281.smt2                                                                              |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_2811.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_2817.smt2                                                                             |  21.116s  |  21.116s  |   0.000s  | 0.0%|
|bench_2826.smt2                                                                             |  20.650s  |  20.650s  |   0.000s  | 0.0%|
|bench_2831.smt2                                                                             |  22.865s  |  22.865s  |   0.000s  | 0.0%|
|bench_2832.smt2                                                                             |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|bench_2839.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_2841.smt2                                                                             |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|bench_2842.smt2                                                                             |  21.917s  |  21.917s  |   0.000s  | 0.0%|
|bench_2844.smt2                                                                             |  22.090s  |  22.090s  |   0.000s  | 0.0%|
|bench_2846.smt2                                                                             |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|bench_2849.smt2                                                                             |  21.461s  |  21.461s  |   0.000s  | 0.0%|
|bench_285.smt2                                                                              |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|bench_2855.smt2                                                                             |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|bench_2858.smt2                                                                             |  20.706s  |  20.706s  |   0.000s  | 0.0%|
|bench_2864.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_2866.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_2867.smt2                                                                             |  20.823s  |  20.823s  |   0.000s  | 0.0%|
|bench_2868.smt2                                                                             |  20.199s  |  20.199s  |   0.000s  | 0.0%|
|bench_2875.smt2                                                                             |  20.637s  |  20.637s  |   0.000s  | 0.0%|
|bench_2876.smt2                                                                             |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench_288.smt2                                                                              |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_2880.smt2                                                                             |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench_2897.smt2                                                                             |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|bench_29.smt2                                                                               |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|bench_290.smt2                                                                              |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_2915.smt2                                                                             |  21.785s  |  21.785s  |   0.000s  | 0.0%|
|bench_2917.smt2                                                                             |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|bench_2931.smt2                                                                             |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|bench_295.smt2                                                                              |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_2957.smt2                                                                             |   3.296s  |   3.296s  |   0.000s  | 0.0%|
|bench_296.smt2                                                                              |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_2961.smt2                                                                             |   5.412s  |   5.412s  |   0.000s  | 0.0%|
|bench_2962.smt2                                                                             |   6.667s  |   6.667s  |   0.000s  | 0.0%|
|bench_2965.smt2                                                                             |   4.563s  |   4.563s  |   0.000s  | 0.0%|
|bench_2974.smt2                                                                             |   3.370s  |   3.370s  |   0.000s  | 0.0%|
|bench_2983.smt2                                                                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_299.smt2                                                                              |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_2992.smt2                                                                             |  19.981s  |  19.981s  |   0.000s  | 0.0%|
|bench_2994.smt2                                                                             |   6.009s  |   6.009s  |   0.000s  | 0.0%|
|bench_2995.smt2                                                                             |   4.287s  |   4.287s  |   0.000s  | 0.0%|
|bench_301.smt2                                                                              |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_3010.smt2                                                                             |  21.122s  |  21.122s  |   0.000s  | 0.0%|
|bench_3011.smt2                                                                             |   4.956s  |   4.956s  |   0.000s  | 0.0%|
|bench_3015.smt2                                                                             |  20.884s  |  20.884s  |   0.000s  | 0.0%|
|bench_3018.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_3019.smt2                                                                             |  21.574s  |  21.574s  |   0.000s  | 0.0%|
|bench_302.smt2                                                                              |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_303.smt2                                                                              |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_3031.smt2                                                                             |   4.011s  |   4.011s  |   0.000s  | 0.0%|
|bench_3032.smt2                                                                             |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|bench_3041.smt2                                                                             |  20.497s  |  20.497s  |   0.000s  | 0.0%|
|bench_3048.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_3058.smt2                                                                             |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|bench_306.smt2                                                                              |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_3062.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_3065.smt2                                                                             |  21.241s  |  21.241s  |   0.000s  | 0.0%|
|bench_3068.smt2                                                                             |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|bench_3080.smt2                                                                             |  20.956s  |  20.956s  |   0.000s  | 0.0%|
|bench_3082.smt2                                                                             |  21.126s  |  21.126s  |   0.000s  | 0.0%|
|bench_3087.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_3091.smt2                                                                             |   2.475s  |   2.475s  |   0.000s  | 0.0%|
|bench_3093.smt2                                                                             |  19.708s  |  19.708s  |   0.000s  | 0.0%|
|bench_3094.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_3099.smt2                                                                             |   3.726s  |   3.726s  |   0.000s  | 0.0%|
|bench_3103.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3105.smt2                                                                             |  20.885s  |  20.885s  |   0.000s  | 0.0%|
|bench_3111.smt2                                                                             |  21.294s  |  21.294s  |   0.000s  | 0.0%|
|bench_3113.smt2                                                                             |  20.406s  |  20.406s  |   0.000s  | 0.0%|
|bench_3114.smt2                                                                             |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|bench_3121.smt2                                                                             |   3.090s  |   3.090s  |   0.000s  | 0.0%|
|bench_313.smt2                                                                              |  11.229s  |  11.229s  |   0.000s  | 0.0%|
|bench_3145.smt2                                                                             |  20.451s  |  20.451s  |   0.000s  | 0.0%|
|bench_3156.smt2                                                                             |   2.650s  |   2.650s  |   0.000s  | 0.0%|
|bench_3159.smt2                                                                             |  22.078s  |  22.078s  |   0.000s  | 0.0%|
|bench_3168.smt2                                                                             |  20.795s  |  20.795s  |   0.000s  | 0.0%|
|bench_3169.smt2                                                                             |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|bench_317.smt2                                                                              |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_3171.smt2                                                                             |  20.893s  |  20.893s  |   0.000s  | 0.0%|
|bench_3173.smt2                                                                             |  21.400s  |  21.400s  |   0.000s  | 0.0%|
|bench_3174.smt2                                                                             |  20.538s  |  20.538s  |   0.000s  | 0.0%|
|bench_3177.smt2                                                                             |  20.558s  |  20.558s  |   0.000s  | 0.0%|
|bench_3181.smt2                                                                             |  19.642s  |  19.642s  |   0.000s  | 0.0%|
|bench_3182.smt2                                                                             |  20.140s  |  20.140s  |   0.000s  | 0.0%|
|bench_3191.smt2                                                                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_3194.smt2                                                                             |  21.100s  |  21.100s  |   0.000s  | 0.0%|
|bench_3196.smt2                                                                             |  19.134s  |  19.134s  |   0.000s  | 0.0%|
|bench_3206.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_3207.smt2                                                                             |  21.034s  |  21.034s  |   0.000s  | 0.0%|
|bench_3209.smt2                                                                             |  20.822s  |  20.822s  |   0.000s  | 0.0%|
|bench_3218.smt2                                                                             |  21.402s  |  21.402s  |   0.000s  | 0.0%|
|bench_3221.smt2                                                                             |  19.963s  |  19.963s  |   0.000s  | 0.0%|
|bench_3223.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_323.smt2                                                                              |  20.769s  |  20.769s  |   0.000s  | 0.0%|
|bench_3239.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_3240.smt2                                                                             |  20.977s  |  20.977s  |   0.000s  | 0.0%|
|bench_3246.smt2                                                                             |  25.513s  |  25.513s  |   0.000s  | 0.0%|
|bench_325.smt2                                                                              |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|bench_3263.smt2                                                                             |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bench_3266.smt2                                                                             |  21.741s  |  21.741s  |   0.000s  | 0.0%|
|bench_3268.smt2                                                                             |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bench_3275.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_3279.smt2                                                                             |  19.583s  |  19.583s  |   0.000s  | 0.0%|
|bench_3295.smt2                                                                             |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|bench_3297.smt2                                                                             |  20.413s  |  20.413s  |   0.000s  | 0.0%|
|bench_3307.smt2                                                                             |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|bench_3308.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_3311.smt2                                                                             |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|bench_3317.smt2                                                                             |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench_3320.smt2                                                                             |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|bench_3326.smt2                                                                             |  26.762s  |  26.762s  |   0.000s  | 0.0%|
|bench_3329.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_3333.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_3335.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_3338.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_3339.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_334.smt2                                                                              |  20.896s  |  20.896s  |   0.000s  | 0.0%|
|bench_335.smt2                                                                              |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|bench_3351.smt2                                                                             |  19.891s  |  19.891s  |   0.000s  | 0.0%|
|bench_3352.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_3358.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_3360.smt2                                                                             |  19.353s  |  19.353s  |   0.000s  | 0.0%|
|bench_3367.smt2                                                                             |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|bench_3379.smt2                                                                             |  21.628s  |  21.628s  |   0.000s  | 0.0%|
|bench_3394.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_3411.smt2                                                                             |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|bench_3415.smt2                                                                             |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|bench_3416.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_3420.smt2                                                                             |   2.817s  |   2.817s  |   0.000s  | 0.0%|
|bench_3421.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_3431.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_3434.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_3437.smt2                                                                             |  21.155s  |  21.155s  |   0.000s  | 0.0%|
|bench_3446.smt2                                                                             |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench_3451.smt2                                                                             |  20.890s  |  20.890s  |   0.000s  | 0.0%|
|bench_3460.smt2                                                                             |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|bench_3461.smt2                                                                             |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|bench_3465.smt2                                                                             |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|bench_3469.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_347.smt2                                                                              |  19.751s  |  19.751s  |   0.000s  | 0.0%|
|bench_3475.smt2                                                                             |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bench_3476.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_348.smt2                                                                              |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_3484.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_3485.smt2                                                                             |  22.198s  |  22.198s  |   0.000s  | 0.0%|
|bench_3489.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_3499.smt2                                                                             |  20.899s  |  20.899s  |   0.000s  | 0.0%|
|bench_3500.smt2                                                                             |   9.130s  |   9.130s  |   0.000s  | 0.0%|
|bench_3502.smt2                                                                             |  20.884s  |  20.884s  |   0.000s  | 0.0%|
|bench_3509.smt2                                                                             |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bench_3516.smt2                                                                             |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|bench_3521.smt2                                                                             |  20.517s  |  20.517s  |   0.000s  | 0.0%|
|bench_3522.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_3524.smt2                                                                             |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|bench_353.smt2                                                                              |  22.210s  |  22.210s  |   0.000s  | 0.0%|
|bench_3538.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_3539.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_3541.smt2                                                                             |   2.744s  |   2.744s  |   0.000s  | 0.0%|
|bench_3548.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_3551.smt2                                                                             |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|bench_3557.smt2                                                                             |  20.677s  |  20.677s  |   0.000s  | 0.0%|
|bench_3558.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_3561.smt2                                                                             |  21.193s  |  21.193s  |   0.000s  | 0.0%|
|bench_3575.smt2                                                                             |  21.951s  |  21.951s  |   0.000s  | 0.0%|
|bench_3578.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_3587.smt2                                                                             |   1.997s  |   1.997s  |   0.000s  | 0.0%|
|bench_3588.smt2                                                                             |  26.091s  |  26.091s  |   0.000s  | 0.0%|
|bench_3598.smt2                                                                             |   0.771s  |   0.771s  |   0.000s  | 0.0%|
|bench_36.smt2                                                                               |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|bench_360.smt2                                                                              |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|bench_3603.smt2                                                                             |  20.442s  |  20.442s  |   0.000s  | 0.0%|
|bench_3623.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_3636.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_3637.smt2                                                                             |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|bench_3642.smt2                                                                             |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|bench_365.smt2                                                                              |   4.098s  |   4.098s  |   0.000s  | 0.0%|
|bench_366.smt2                                                                              |   2.150s  |   2.150s  |   0.000s  | 0.0%|
|bench_3671.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_3672.smt2                                                                             |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|bench_3675.smt2                                                                             |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|bench_368.smt2                                                                              |   4.065s  |   4.065s  |   0.000s  | 0.0%|
|bench_3681.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_3688.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_3689.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_369.smt2                                                                              |   3.454s  |   3.454s  |   0.000s  | 0.0%|
|bench_3697.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_3699.smt2                                                                             |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|bench_3707.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_3715.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_3716.smt2                                                                             |  21.231s  |  21.231s  |   0.000s  | 0.0%|
|bench_3719.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_372.smt2                                                                              |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_3721.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_3739.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_375.smt2                                                                              |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_3750.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_3754.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_3755.smt2                                                                             |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bench_3757.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_3765.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_3787.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_3788.smt2                                                                             |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bench_3789.smt2                                                                             |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|bench_379.smt2                                                                              |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|bench_3794.smt2                                                                             |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|bench_3795.smt2                                                                             |  20.872s  |  20.872s  |   0.000s  | 0.0%|
|bench_3799.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_3813.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_3815.smt2                                                                             |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|bench_3818.smt2                                                                             |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bench_3819.smt2                                                                             |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|bench_3832.smt2                                                                             |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|bench_3834.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_3838.smt2                                                                             |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench_3846.smt2                                                                             |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|bench_3847.smt2                                                                             |  21.409s  |  21.409s  |   0.000s  | 0.0%|
|bench_385.smt2                                                                              |   2.215s  |   2.215s  |   0.000s  | 0.0%|
|bench_3866.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_387.smt2                                                                              |   5.070s  |   5.070s  |   0.000s  | 0.0%|
|bench_3879.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_388.smt2                                                                              |   2.661s  |   2.661s  |   0.000s  | 0.0%|
|bench_3881.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_3882.smt2                                                                             |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|bench_3885.smt2                                                                             |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|bench_3886.smt2                                                                             |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|bench_3888.smt2                                                                             |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|bench_3890.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_3894.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_390.smt2                                                                              |   2.752s  |   2.752s  |   0.000s  | 0.0%|
|bench_3906.smt2                                                                             |  20.861s  |  20.861s  |   0.000s  | 0.0%|
|bench_3915.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_3926.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_3936.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_3937.smt2                                                                             |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bench_3943.smt2                                                                             |  20.969s  |  20.969s  |   0.000s  | 0.0%|
|bench_3945.smt2                                                                             |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|bench_3951.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_3953.smt2                                                                             |  21.021s  |  21.021s  |   0.000s  | 0.0%|
|bench_3963.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_3964.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_3968.smt2                                                                             |  21.873s  |  21.873s  |   0.000s  | 0.0%|
|bench_3992.smt2                                                                             |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|bench_3995.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_3997.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_4007.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_4010.smt2                                                                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_4015.smt2                                                                             |  20.070s  |  20.070s  |   0.000s  | 0.0%|
|bench_4019.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_402.smt2                                                                              |   2.379s  |   2.379s  |   0.000s  | 0.0%|
|bench_4021.smt2                                                                             |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|bench_4023.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_4031.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_4037.smt2                                                                             |  20.413s  |  20.413s  |   0.000s  | 0.0%|
|bench_404.smt2                                                                              |   2.828s  |   2.828s  |   0.000s  | 0.0%|
|bench_4040.smt2                                                                             |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|bench_4046.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_4051.smt2                                                                             |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|bench_4058.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_4065.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_4069.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_4097.smt2                                                                             |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|bench_4099.smt2                                                                             |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|bench_4100.smt2                                                                             |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench_4112.smt2                                                                             |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|bench_4115.smt2                                                                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_4137.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_414.smt2                                                                              |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bench_4141.smt2                                                                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_4143.smt2                                                                             |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|bench_4154.smt2                                                                             |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench_4156.smt2                                                                             |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bench_4157.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_4160.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_4164.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_4170.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_4173.smt2                                                                             |   5.998s  |   5.998s  |   0.000s  | 0.0%|
|bench_4175.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_4192.smt2                                                                             |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|bench_4208.smt2                                                                             |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|bench_4219.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_4220.smt2                                                                             |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bench_4231.smt2                                                                             |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|bench_4233.smt2                                                                             |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|bench_424.smt2                                                                              |   4.172s  |   4.172s  |   0.000s  | 0.0%|
|bench_4253.smt2                                                                             |  21.464s  |  21.464s  |   0.000s  | 0.0%|
|bench_4256.smt2                                                                             |  21.031s  |  21.031s  |   0.000s  | 0.0%|
|bench_4261.smt2                                                                             |  19.792s  |  19.792s  |   0.000s  | 0.0%|
|bench_4273.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_4275.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_4279.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_4289.smt2                                                                             |  20.542s  |  20.542s  |   0.000s  | 0.0%|
|bench_4304.smt2                                                                             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|bench_4312.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_4313.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_4319.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_4321.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_4340.smt2                                                                             |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|bench_4346.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_4350.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_4352.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_4356.smt2                                                                             |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|bench_4359.smt2                                                                             |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|bench_436.smt2                                                                              |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_4368.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_437.smt2                                                                              |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|bench_4375.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_4385.smt2                                                                             |  20.534s  |  20.534s  |   0.000s  | 0.0%|
|bench_4387.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_4390.smt2                                                                             |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|bench_4397.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_4399.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_440.smt2                                                                              |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|bench_4405.smt2                                                                             |  20.698s  |  20.698s  |   0.000s  | 0.0%|
|bench_4412.smt2                                                                             |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|bench_4435.smt2                                                                             |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bench_4444.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_4447.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_445.smt2                                                                              |  19.217s  |  19.217s  |   0.000s  | 0.0%|
|bench_4461.smt2                                                                             |   2.138s  |   2.138s  |   0.000s  | 0.0%|
|bench_4467.smt2                                                                             |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|bench_4472.smt2                                                                             |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bench_4477.smt2                                                                             |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|bench_4481.smt2                                                                             |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bench_449.smt2                                                                              |  19.588s  |  19.588s  |   0.000s  | 0.0%|
|bench_4494.smt2                                                                             |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bench_4505.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_4508.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_451.smt2                                                                              |  19.181s  |  19.181s  |   0.000s  | 0.0%|
|bench_4516.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_4518.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_452.smt2                                                                              |  19.497s  |  19.497s  |   0.000s  | 0.0%|
|bench_4520.smt2                                                                             |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bench_4522.smt2                                                                             |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bench_4526.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_4553.smt2                                                                             |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench_4555.smt2                                                                             |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bench_456.smt2                                                                              |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_4560.smt2                                                                             |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|bench_4565.smt2                                                                             |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|bench_4568.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_457.smt2                                                                              |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_4570.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_4576.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_4580.smt2                                                                             |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|bench_4581.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4583.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_4588.smt2                                                                             |  20.607s  |  20.607s  |   0.000s  | 0.0%|
|bench_4594.smt2                                                                             |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|bench_46.smt2                                                                               |   8.568s  |   8.568s  |   0.000s  | 0.0%|
|bench_4605.smt2                                                                             |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|bench_4607.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_4614.smt2                                                                             |  20.912s  |  20.912s  |   0.000s  | 0.0%|
|bench_4617.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_4626.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_4627.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_4628.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_4635.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_4642.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_4644.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_4650.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_4654.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_4662.smt2                                                                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_4669.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_4689.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_4692.smt2                                                                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_4696.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_4706.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_4710.smt2                                                                             |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|bench_472.smt2                                                                              |  13.585s  |  13.585s  |   0.000s  | 0.0%|
|bench_4724.smt2                                                                             |  21.449s  |  21.449s  |   0.000s  | 0.0%|
|bench_4725.smt2                                                                             |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|bench_4728.smt2                                                                             |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|bench_4738.smt2                                                                             |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|bench_4740.smt2                                                                             |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|bench_4753.smt2                                                                             |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|bench_4755.smt2                                                                             |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|bench_4759.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_4768.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_4775.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_4788.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_479.smt2                                                                              |   1.929s  |   1.929s  |   0.000s  | 0.0%|
|bench_480.smt2                                                                              |  19.503s  |  19.503s  |   0.000s  | 0.0%|
|bench_4813.smt2                                                                             |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|bench_4818.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_4820.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_4822.smt2                                                                             |  20.985s  |  20.985s  |   0.000s  | 0.0%|
|bench_4834.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_4838.smt2                                                                             |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|bench_4839.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_4840.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_4873.smt2                                                                             |  21.856s  |  21.856s  |   0.000s  | 0.0%|
|bench_4879.smt2                                                                             |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|bench_4888.smt2                                                                             |  21.522s  |  21.522s  |   0.000s  | 0.0%|
|bench_489.smt2                                                                              |  21.152s  |  21.152s  |   0.000s  | 0.0%|
|bench_4890.smt2                                                                             |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|bench_4893.smt2                                                                             |  21.364s  |  21.364s  |   0.000s  | 0.0%|
|bench_4894.smt2                                                                             |  20.831s  |  20.831s  |   0.000s  | 0.0%|
|bench_4900.smt2                                                                             |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|bench_4906.smt2                                                                             |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench_4908.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_4919.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_4920.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_4921.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_4933.smt2                                                                             |  20.253s  |  20.253s  |   0.000s  | 0.0%|
|bench_4937.smt2                                                                             |  21.085s  |  21.085s  |   0.000s  | 0.0%|
|bench_494.smt2                                                                              |  19.041s  |  19.041s  |   0.000s  | 0.0%|
|bench_4954.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_4957.smt2                                                                             |  20.949s  |  20.949s  |   0.000s  | 0.0%|
|bench_4963.smt2                                                                             |  21.827s  |  21.827s  |   0.000s  | 0.0%|
|bench_4964.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_4965.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_4968.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_497.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_4971.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_498.smt2                                                                              |  20.119s  |  20.119s  |   0.000s  | 0.0%|
|bench_4985.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_4990.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_5.smt2                                                                                |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_50.smt2                                                                               |  19.436s  |  19.436s  |   0.000s  | 0.0%|
|bench_500.smt2                                                                              |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_5005.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_5019.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_502.smt2                                                                              |  19.288s  |  19.288s  |   0.000s  | 0.0%|
|bench_5030.smt2                                                                             |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bench_5034.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_5036.smt2                                                                             |  21.651s  |  21.651s  |   0.000s  | 0.0%|
|bench_5037.smt2                                                                             |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|bench_5041.smt2                                                                             |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|bench_5077.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_5081.smt2                                                                             |  20.075s  |  20.075s  |   0.000s  | 0.0%|
|bench_5084.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_5086.smt2                                                                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_5096.smt2                                                                             |  20.366s  |  20.366s  |   0.000s  | 0.0%|
|bench_51.smt2                                                                               |  19.603s  |  19.603s  |   0.000s  | 0.0%|
|bench_5123.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_5127.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_5131.smt2                                                                             |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|bench_5136.smt2                                                                             |  21.620s  |  21.620s  |   0.000s  | 0.0%|
|bench_5137.smt2                                                                             |  23.586s  |  23.586s  |   0.000s  | 0.0%|
|bench_5139.smt2                                                                             |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|bench_5150.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_5153.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_5154.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_5155.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_5157.smt2                                                                             |  20.870s  |  20.870s  |   0.000s  | 0.0%|
|bench_5159.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_5165.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_5170.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_5183.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_5187.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_5188.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_5190.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_5191.smt2                                                                             |  21.344s  |  21.344s  |   0.000s  | 0.0%|
|bench_5192.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_52.smt2                                                                               |  20.975s  |  20.975s  |   0.000s  | 0.0%|
|bench_5209.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_5210.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_5218.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_5222.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_5223.smt2                                                                             |  20.395s  |  20.395s  |   0.000s  | 0.0%|
|bench_5234.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_5236.smt2                                                                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_5238.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_525.smt2                                                                              |   0.396s  |   0.396s  |   0.000s  | 0.0%|
|bench_5257.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_5261.smt2                                                                             |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bench_527.smt2                                                                              |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_5270.smt2                                                                             |  19.378s  |  19.378s  |   0.000s  | 0.0%|
|bench_528.smt2                                                                              |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|bench_5284.smt2                                                                             |  20.523s  |  20.523s  |   0.000s  | 0.0%|
|bench_5292.smt2                                                                             |  21.087s  |  21.087s  |   0.000s  | 0.0%|
|bench_5296.smt2                                                                             |  20.678s  |  20.678s  |   0.000s  | 0.0%|
|bench_5301.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_5302.smt2                                                                             |  20.528s  |  20.528s  |   0.000s  | 0.0%|
|bench_5303.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_5309.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_531.smt2                                                                              |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|bench_5326.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_5329.smt2                                                                             |   0.782s  |   0.782s  |   0.000s  | 0.0%|
|bench_5332.smt2                                                                             |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|bench_5340.smt2                                                                             |  22.142s  |  22.142s  |   0.000s  | 0.0%|
|bench_5349.smt2                                                                             |  20.432s  |  20.432s  |   0.000s  | 0.0%|
|bench_535.smt2                                                                              |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_5358.smt2                                                                             |  23.762s  |  23.762s  |   0.000s  | 0.0%|
|bench_536.smt2                                                                              |  20.325s  |  20.325s  |   0.000s  | 0.0%|
|bench_5360.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_5365.smt2                                                                             |   5.218s  |   5.218s  |   0.000s  | 0.0%|
|bench_5371.smt2                                                                             |   4.024s  |   4.024s  |   0.000s  | 0.0%|
|bench_5373.smt2                                                                             |   2.342s  |   2.342s  |   0.000s  | 0.0%|
|bench_5377.smt2                                                                             |   3.989s  |   3.989s  |   0.000s  | 0.0%|
|bench_5392.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_5395.smt2                                                                             |  20.105s  |  20.105s  |   0.000s  | 0.0%|
|bench_5401.smt2                                                                             |   2.138s  |   2.138s  |   0.000s  | 0.0%|
|bench_5408.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_5417.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_542.smt2                                                                              |  22.356s  |  22.356s  |   0.000s  | 0.0%|
|bench_5421.smt2                                                                             |  20.953s  |  20.953s  |   0.000s  | 0.0%|
|bench_5424.smt2                                                                             |  21.339s  |  21.339s  |   0.000s  | 0.0%|
|bench_5432.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_5435.smt2                                                                             |  20.567s  |  20.567s  |   0.000s  | 0.0%|
|bench_5440.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_5445.smt2                                                                             |   4.408s  |   4.408s  |   0.000s  | 0.0%|
|bench_5449.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_5457.smt2                                                                             |   2.662s  |   2.662s  |   0.000s  | 0.0%|
|bench_5459.smt2                                                                             |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|bench_5466.smt2                                                                             |  21.228s  |  21.228s  |   0.000s  | 0.0%|
|bench_5492.smt2                                                                             |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|bench_5499.smt2                                                                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|bench_5503.smt2                                                                             |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|bench_5509.smt2                                                                             |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|bench_5517.smt2                                                                             |  20.204s  |  20.204s  |   0.000s  | 0.0%|
|bench_5525.smt2                                                                             |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|bench_5526.smt2                                                                             |  31.710s  |  31.710s  |   0.000s  | 0.0%|
|bench_5532.smt2                                                                             |   3.164s  |   3.164s  |   0.000s  | 0.0%|
|bench_5536.smt2                                                                             |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|bench_5543.smt2                                                                             |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|bench_5545.smt2                                                                             |   5.524s  |   5.524s  |   0.000s  | 0.0%|
|bench_556.smt2                                                                              |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|bench_5575.smt2                                                                             |  21.454s  |  21.454s  |   0.000s  | 0.0%|
|bench_5581.smt2                                                                             |  21.109s  |  21.109s  |   0.000s  | 0.0%|
|bench_559.smt2                                                                              |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|bench_5590.smt2                                                                             |   2.089s  |   2.089s  |   0.000s  | 0.0%|
|bench_5593.smt2                                                                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|bench_561.smt2                                                                              |  19.576s  |  19.576s  |   0.000s  | 0.0%|
|bench_5613.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_5623.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_5636.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_5645.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_5649.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_565.smt2                                                                              |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_5658.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_5662.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_5666.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_5674.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_571.smt2                                                                              |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_5718.smt2                                                                             |   2.983s  |   2.983s  |   0.000s  | 0.0%|
|bench_5722.smt2                                                                             |   3.365s  |   3.365s  |   0.000s  | 0.0%|
|bench_5723.smt2                                                                             |   4.148s  |   4.148s  |   0.000s  | 0.0%|
|bench_5733.smt2                                                                             |   2.259s  |   2.259s  |   0.000s  | 0.0%|
|bench_5744.smt2                                                                             |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|bench_5752.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_5765.smt2                                                                             |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|bench_5779.smt2                                                                             |   8.389s  |   8.389s  |   0.000s  | 0.0%|
|bench_581.smt2                                                                              |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|bench_5898.smt2                                                                             |  21.252s  |  21.252s  |   0.000s  | 0.0%|
|bench_5944.smt2                                                                             |   2.069s  |   2.069s  |   0.000s  | 0.0%|
|bench_5974.smt2                                                                             |  21.900s  |  21.900s  |   0.000s  | 0.0%|
|bench_6012.smt2                                                                             |  20.735s  |  20.735s  |   0.000s  | 0.0%|
|bench_6016.smt2                                                                             |  20.655s  |  20.655s  |   0.000s  | 0.0%|
|bench_607.smt2                                                                              |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|bench_609.smt2                                                                              |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|bench_6097.smt2                                                                             |   0.652s  |   0.652s  |   0.000s  | 0.0%|
|bench_613.smt2                                                                              |  19.377s  |  19.377s  |   0.000s  | 0.0%|
|bench_619.smt2                                                                              |  19.908s  |  19.908s  |   0.000s  | 0.0%|
|bench_620.smt2                                                                              |   8.846s  |   8.846s  |   0.000s  | 0.0%|
|bench_6215.smt2                                                                             |  19.103s  |  19.103s  |   0.000s  | 0.0%|
|bench_629.smt2                                                                              |  19.259s  |  19.259s  |   0.000s  | 0.0%|
|bench_630.smt2                                                                              |  19.486s  |  19.486s  |   0.000s  | 0.0%|
|bench_631.smt2                                                                              |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_637.smt2                                                                              |  19.399s  |  19.399s  |   0.000s  | 0.0%|
|bench_639.smt2                                                                              |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_640.smt2                                                                              |   0.540s  |   0.540s  |   0.000s  | 0.0%|
|bench_6408.smt2                                                                             |  20.362s  |  20.362s  |   0.000s  | 0.0%|
|bench_6458.smt2                                                                             |  21.451s  |  21.451s  |   0.000s  | 0.0%|
|bench_6462.smt2                                                                             |  21.187s  |  21.187s  |   0.000s  | 0.0%|
|bench_650.smt2                                                                              |   3.862s  |   3.862s  |   0.000s  | 0.0%|
|bench_6560.smt2                                                                             |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|bench_657.smt2                                                                              |   2.017s  |   2.017s  |   0.000s  | 0.0%|
|bench_658.smt2                                                                              |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|bench_659.smt2                                                                              |   2.175s  |   2.175s  |   0.000s  | 0.0%|
|bench_66.smt2                                                                               |  19.527s  |  19.527s  |   0.000s  | 0.0%|
|bench_6606.smt2                                                                             |  21.062s  |  21.062s  |   0.000s  | 0.0%|
|bench_6614.smt2                                                                             |  21.729s  |  21.729s  |   0.000s  | 0.0%|
|bench_663.smt2                                                                              |  19.816s  |  19.816s  |   0.000s  | 0.0%|
|bench_6665.smt2                                                                             |  23.058s  |  23.058s  |   0.000s  | 0.0%|
|bench_668.smt2                                                                              |   2.033s  |   2.033s  |   0.000s  | 0.0%|
|bench_6691.smt2                                                                             |  20.793s  |  20.793s  |   0.000s  | 0.0%|
|bench_6696.smt2                                                                             |  19.784s  |  19.784s  |   0.000s  | 0.0%|
|bench_6699.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_6713.smt2                                                                             |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench_6731.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_6734.smt2                                                                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_674.smt2                                                                              |   5.853s  |   5.853s  |   0.000s  | 0.0%|
|bench_6742.smt2                                                                             |  21.470s  |  21.470s  |   0.000s  | 0.0%|
|bench_6756.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_6765.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_6791.smt2                                                                             |   5.306s  |   5.306s  |   0.000s  | 0.0%|
|bench_6813.smt2                                                                             |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|bench_6826.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_6828.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_6830.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_6837.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_6843.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_6848.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_685.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_6854.smt2                                                                             |   0.895s  |   0.895s  |   0.000s  | 0.0%|
|bench_6857.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_6861.smt2                                                                             |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|bench_6866.smt2                                                                             |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|bench_6867.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_6882.smt2                                                                             |  20.938s  |  20.938s  |   0.000s  | 0.0%|
|bench_6886.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_6898.smt2                                                                             |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|bench_690.smt2                                                                              |  19.651s  |  19.651s  |   0.000s  | 0.0%|
|bench_6901.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_6902.smt2                                                                             |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bench_6906.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_6908.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_6911.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_6917.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_6923.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_6924.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_6929.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_6938.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_6943.smt2                                                                             |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|bench_6953.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_6954.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_6966.smt2                                                                             |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bench_6973.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_6986.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_6987.smt2                                                                             |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|bench_6998.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_700.smt2                                                                              |  19.247s  |  19.247s  |   0.000s  | 0.0%|
|bench_7005.smt2                                                                             |  20.325s  |  20.325s  |   0.000s  | 0.0%|
|bench_702.smt2                                                                              |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_7021.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_7024.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_7030.smt2                                                                             |  20.673s  |  20.673s  |   0.000s  | 0.0%|
|bench_7033.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_704.smt2                                                                              |  19.652s  |  19.652s  |   0.000s  | 0.0%|
|bench_705.smt2                                                                              |  19.646s  |  19.646s  |   0.000s  | 0.0%|
|bench_7056.smt2                                                                             |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|bench_706.smt2                                                                              |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_7070.smt2                                                                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_7076.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_7081.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_7082.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_7083.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_7085.smt2                                                                             |  20.823s  |  20.823s  |   0.000s  | 0.0%|
|bench_7086.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_7088.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_709.smt2                                                                              |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bench_7095.smt2                                                                             |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bench_710.smt2                                                                              |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|bench_7116.smt2                                                                             |  21.132s  |  21.132s  |   0.000s  | 0.0%|
|bench_7119.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_712.smt2                                                                              |   0.283s  |   0.283s  |   0.000s  | 0.0%|
|bench_7127.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_7138.smt2                                                                             |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bench_7139.smt2                                                                             |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|bench_7140.smt2                                                                             |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bench_7142.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_7146.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_7150.smt2                                                                             |   2.530s  |   2.530s  |   0.000s  | 0.0%|
|bench_7152.smt2                                                                             |  20.701s  |  20.701s  |   0.000s  | 0.0%|
|bench_7166.smt2                                                                             |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bench_717.smt2                                                                              |  22.304s  |  22.304s  |   0.000s  | 0.0%|
|bench_7171.smt2                                                                             |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|bench_7182.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_7185.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_7188.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_720.smt2                                                                              |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_721.smt2                                                                              |  19.878s  |  19.878s  |   0.000s  | 0.0%|
|bench_7219.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_7229.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_7233.smt2                                                                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_7242.smt2                                                                             |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench_7270.smt2                                                                             |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|bench_7274.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_7278.smt2                                                                             |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bench_7304.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_7306.smt2                                                                             |  22.903s  |  22.903s  |   0.000s  | 0.0%|
|bench_7310.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_7314.smt2                                                                             |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bench_7319.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_7329.smt2                                                                             |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|bench_7331.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_7339.smt2                                                                             |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|bench_7357.smt2                                                                             |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|bench_7375.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_7382.smt2                                                                             |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|bench_7383.smt2                                                                             |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|bench_7388.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_7406.smt2                                                                             |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|bench_7412.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_7415.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_7421.smt2                                                                             |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|bench_743.smt2                                                                              |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_7438.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_7454.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_746.smt2                                                                              |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_7465.smt2                                                                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_748.smt2                                                                              |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_7489.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_749.smt2                                                                              |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_7494.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_7495.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_7496.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_7498.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_7517.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_7523.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_7528.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_753.smt2                                                                              |   0.609s  |   0.609s  |   0.000s  | 0.0%|
|bench_7532.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_7534.smt2                                                                             |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|bench_7537.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_7539.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_7550.smt2                                                                             |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|bench_7552.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_7556.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_7563.smt2                                                                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_7565.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_7573.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7575.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_76.smt2                                                                               |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench_760.smt2                                                                              |   1.063s  |   1.063s  |   0.000s  | 0.0%|
|bench_7601.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_7612.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_7627.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_7633.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_7636.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_7641.smt2                                                                             |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bench_7642.smt2                                                                             |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|bench_7655.smt2                                                                             |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bench_7663.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_7669.smt2                                                                             |   2.401s  |   2.401s  |   0.000s  | 0.0%|
|bench_7670.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_7671.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_7673.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_7686.smt2                                                                             |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_7696.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_7705.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_7708.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_7714.smt2                                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_7729.smt2                                                                             |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|bench_7736.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_7749.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_7754.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7758.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_7765.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_778.smt2                                                                              |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|bench_78.smt2                                                                               |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_7800.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7807.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_7811.smt2                                                                             |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_7819.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_7823.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7826.smt2                                                                             |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|bench_7828.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_7832.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_7833.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_7834.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_7835.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_7842.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_7851.smt2                                                                             |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|bench_7862.smt2                                                                             |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|bench_7863.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_7867.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_787.smt2                                                                              |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|bench_7872.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_7878.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_7881.smt2                                                                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_789.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_791.smt2                                                                              |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench_793.smt2                                                                              |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_7943.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_796.smt2                                                                              |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_797.smt2                                                                              |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|bench_7973.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_8019.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_8030.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_8042.smt2                                                                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_8049.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_8051.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_8053.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_8054.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_8055.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_8070.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_8073.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_808.smt2                                                                              |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_8082.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_8084.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_8088.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_8093.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_8103.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_8110.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_8116.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_8117.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_8147.smt2                                                                             |  21.400s  |  21.400s  |   0.000s  | 0.0%|
|bench_815.smt2                                                                              |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|bench_8165.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_8170.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_8178.smt2                                                                             |  21.925s  |  21.925s  |   0.000s  | 0.0%|
|bench_820.smt2                                                                              |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench_8200.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_8228.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_823.smt2                                                                              |  19.975s  |  19.975s  |   0.000s  | 0.0%|
|bench_8234.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_824.smt2                                                                              |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_8245.smt2                                                                             |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bench_825.smt2                                                                              |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|bench_826.smt2                                                                              |  19.392s  |  19.392s  |   0.000s  | 0.0%|
|bench_8260.smt2                                                                             |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bench_8271.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_8282.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_8283.smt2                                                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_8289.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_8294.smt2                                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|bench_8296.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_8298.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_830.smt2                                                                              |  19.529s  |  19.529s  |   0.000s  | 0.0%|
|bench_8306.smt2                                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_8309.smt2                                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|bench_831.smt2                                                                              |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bench_8315.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_8320.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|bench_8342.smt2                                                                             |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|bench_8344.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|bench_8357.smt2                                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_8379.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_838.smt2                                                                              |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bench_8393.smt2                                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|bench_8394.smt2                                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_8461.smt2                                                                             |  20.265s  |  20.265s  |   0.000s  | 0.0%|
|bench_8462.smt2                                                                             |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|bench_8478.smt2                                                                             |   0.483s  |   0.483s  |   0.000s  | 0.0%|
|bench_8487.smt2                                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_8492.smt2                                                                             |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|bench_8495.smt2                                                                             |  19.688s  |  19.688s  |   0.000s  | 0.0%|
|bench_8507.smt2                                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_8512.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_856.smt2                                                                              |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|bench_8562.smt2                                                                             |   0.547s  |   0.547s  |   0.000s  | 0.0%|
|bench_8564.smt2                                                                             |   1.369s  |   1.369s  |   0.000s  | 0.0%|
|bench_8579.smt2                                                                             |  20.153s  |  20.153s  |   0.000s  | 0.0%|
|bench_858.smt2                                                                              |  19.611s  |  19.611s  |   0.000s  | 0.0%|
|bench_86.smt2                                                                               |  10.247s  |  10.247s  |   0.000s  | 0.0%|
|bench_864.smt2                                                                              |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_868.smt2                                                                              |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_875.smt2                                                                              |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_881.smt2                                                                              |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bench_883.smt2                                                                              |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_888.smt2                                                                              |  19.608s  |  19.608s  |   0.000s  | 0.0%|
|bench_894.smt2                                                                              |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bench_900.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_9009.smt2                                                                             |  20.762s  |  20.762s  |   0.000s  | 0.0%|
|bench_905.smt2                                                                              |   2.575s  |   2.575s  |   0.000s  | 0.0%|
|bench_91.smt2                                                                               |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_914.smt2                                                                              |  21.369s  |  21.369s  |   0.000s  | 0.0%|
|bench_9173.smt2                                                                             |  22.116s  |  22.116s  |   0.000s  | 0.0%|
|bench_919.smt2                                                                              |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_92.smt2                                                                               |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|bench_924.smt2                                                                              |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|bench_926.smt2                                                                              |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bench_9280.smt2                                                                             |  12.638s  |  12.638s  |   0.000s  | 0.0%|
|bench_9299.smt2                                                                             |  20.620s  |  20.620s  |   0.000s  | 0.0%|
|bench_930.smt2                                                                              |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bench_9301.smt2                                                                             |  20.807s  |  20.807s  |   0.000s  | 0.0%|
|bench_9337.smt2                                                                             |   2.394s  |   2.394s  |   0.000s  | 0.0%|
|bench_9343.smt2                                                                             |  20.090s  |  20.090s  |   0.000s  | 0.0%|
|bench_9360.smt2                                                                             |   0.399s  |   0.399s  |   0.000s  | 0.0%|
|bench_938.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_941.smt2                                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|bench_944.smt2                                                                              |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_945.smt2                                                                              |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|bench_9535.smt2                                                                             |  20.552s  |  20.552s  |   0.000s  | 0.0%|
|bench_954.smt2                                                                              |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_957.smt2                                                                              |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|bench_961.smt2                                                                              |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|bench_964.smt2                                                                              |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|bench_965.smt2                                                                              |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|bench_9653.smt2                                                                             |  20.162s  |  20.162s  |   0.000s  | 0.0%|
|bench_97.smt2                                                                               |  19.475s  |  19.475s  |   0.000s  | 0.0%|
|bench_972.smt2                                                                              |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|bench_974.smt2                                                                              |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|bench_975.smt2                                                                              |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_979.smt2                                                                              |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|bench_98.smt2                                                                               |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|bench_981.smt2                                                                              |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bench_983.smt2                                                                              |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bench_9846.smt2                                                                             |  20.656s  |  20.656s  |   0.000s  | 0.0%|
|bench_985.smt2                                                                              |  12.295s  |  12.295s  |   0.000s  | 0.0%|
|bench_988.smt2                                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|bench_991.smt2                                                                              |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|bench_992.smt2                                                                              |  20.981s  |  20.981s  |   0.000s  | 0.0%|
|bench_993.smt2                                                                              |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|bench_994.smt2                                                                              |  10.289s  |  10.289s  |   0.000s  | 0.0%|
|bench_9946.smt2                                                                             |  22.375s  |  22.375s  |   0.000s  | 0.0%|
|bench_996.smt2                                                                              |  20.914s  |  20.914s  |   0.000s  | 0.0%|
|bench_997.smt2                                                                              |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|bgpd_bgpd_vc76751.smt2                                                                      |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|bgpd_bgpd_vc76752.smt2                                                                      |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc330950.smt2                                                               |   1.323s  |   1.323s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc330976.smt2                                                               |   2.402s  |   2.402s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc330978.smt2                                                               |   0.596s  |   0.596s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331001.smt2                                                               |   0.420s  |   0.420s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331002.smt2                                                               |   1.082s  |   1.082s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331003.smt2                                                               |   0.354s  |   0.354s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331007.smt2                                                               |   0.583s  |   0.583s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331044.smt2                                                               |   2.863s  |   2.863s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331052.smt2                                                               |  13.603s  |  13.603s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331054.smt2                                                               |   5.562s  |   5.562s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331082.smt2                                                               |   5.263s  |   5.263s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331086.smt2                                                               |   2.921s  |   2.921s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331088.smt2                                                               |   0.921s  |   0.921s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331089.smt2                                                               |   0.367s  |   0.367s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331092.smt2                                                               |   7.675s  |   7.675s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331097.smt2                                                               |   8.653s  |   8.653s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331106.smt2                                                               |   7.578s  |   7.578s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331114.smt2                                                               |   5.843s  |   5.843s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331126.smt2                                                               |   5.971s  |   5.971s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331137.smt2                                                               |  10.538s  |  10.538s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331146.smt2                                                               |  20.918s  |  20.918s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331148.smt2                                                               |   7.547s  |   7.547s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331154.smt2                                                               |   6.486s  |   6.486s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331156.smt2                                                               |  10.046s  |  10.046s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331161.smt2                                                               |  12.032s  |  12.032s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331166.smt2                                                               |  20.497s  |  20.497s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331167.smt2                                                               |   4.896s  |   4.896s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331169.smt2                                                               |  12.068s  |  12.068s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc351344.smt2                                                               |   2.206s  |   2.206s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc351348.smt2                                                               |   2.394s  |   2.394s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc352293.smt2                                                               |   2.000s  |   2.000s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc352355.smt2                                                               |   2.448s  |   2.448s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225139.smt2                                                                 |   2.166s  |   2.166s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225280.smt2                                                                 |  21.116s  |  21.116s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225299.smt2                                                                 |   7.392s  |   7.392s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225305.smt2                                                                 |  11.510s  |  11.510s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225312.smt2                                                                 |   6.232s  |   6.232s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225316.smt2                                                                 |  12.843s  |  12.843s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225318.smt2                                                                 |  21.674s  |  21.674s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225320.smt2                                                                 |  10.376s  |  10.376s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225324.smt2                                                                 |  12.310s  |  12.310s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225330.smt2                                                                 |   9.892s  |   9.892s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225332.smt2                                                                 |  21.046s  |  21.046s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225336.smt2                                                                 |  13.991s  |  13.991s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225346.smt2                                                                 |  17.462s  |  17.462s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225380.smt2                                                                 |  20.261s  |  20.261s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225392.smt2                                                                 |  20.960s  |  20.960s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225394.smt2                                                                 |   9.136s  |   9.136s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225395.smt2                                                                 |  15.827s  |  15.827s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225399.smt2                                                                 |  20.074s  |  20.074s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225405.smt2                                                                 |  19.357s  |  19.357s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225412.smt2                                                                 |  10.645s  |  10.645s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225454.smt2                                                                 |  19.682s  |  19.682s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225601.smt2                                                                 |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225745.smt2                                                                 |   0.636s  |   0.636s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225756.smt2                                                                 |   7.888s  |   7.888s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225779.smt2                                                                 |   7.004s  |   7.004s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225786.smt2                                                                 |   3.306s  |   3.306s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225800.smt2                                                                 |   3.489s  |   3.489s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225815.smt2                                                                 |   5.525s  |   5.525s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225816.smt2                                                                 |   6.799s  |   6.799s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225820.smt2                                                                 |   5.793s  |   5.793s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225824.smt2                                                                 |   6.800s  |   6.800s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225843.smt2                                                                 |  11.635s  |  11.635s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225858.smt2                                                                 |  12.392s  |  12.392s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225895.smt2                                                                 |  12.816s  |  12.816s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225900.smt2                                                                 |  24.895s  |  24.895s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225910.smt2                                                                 |  11.601s  |  11.601s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225912.smt2                                                                 |  11.375s  |  11.375s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225939.smt2                                                                 |  15.477s  |  15.477s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228446.smt2                                                                 |   8.064s  |   8.064s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228463.smt2                                                                 |   8.293s  |   8.293s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228474.smt2                                                                 |   8.787s  |   8.787s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228478.smt2                                                                 |   8.444s  |   8.444s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228479.smt2                                                                 |   1.863s  |   1.863s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228487.smt2                                                                 |  10.065s  |  10.065s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228491.smt2                                                                 |  14.903s  |  14.903s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228492.smt2                                                                 |   6.488s  |   6.488s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228509.smt2                                                                 |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228512.smt2                                                                 |  18.912s  |  18.912s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228514.smt2                                                                 |  11.373s  |  11.373s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228524.smt2                                                                 |  20.825s  |  20.825s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228527.smt2                                                                 |  15.610s  |  15.610s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228571.smt2                                                                 |  11.381s  |  11.381s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228577.smt2                                                                 |  18.573s  |  18.573s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228610.smt2                                                                 |  11.571s  |  11.571s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232002.smt2                                                                 |   2.413s  |   2.413s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232007.smt2                                                                 |   4.257s  |   4.257s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232013.smt2                                                                 |  10.691s  |  10.691s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232030.smt2                                                                 |   9.087s  |   9.087s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232034.smt2                                                                 |   7.710s  |   7.710s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232036.smt2                                                                 |  18.876s  |  18.876s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232066.smt2                                                                 |  10.158s  |  10.158s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232071.smt2                                                                 |   6.225s  |   6.225s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232117.smt2                                                                 |  20.856s  |  20.856s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232137.smt2                                                                 |  10.323s  |  10.323s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232138.smt2                                                                 |   8.367s  |   8.367s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225164.smt2                                                             |   0.476s  |   0.476s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225211.smt2                                                             |  18.455s  |  18.455s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225213.smt2                                                             |   3.790s  |   3.790s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225231.smt2                                                             |   2.737s  |   2.737s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225236.smt2                                                             |   7.065s  |   7.065s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225237.smt2                                                             |   2.334s  |   2.334s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225238.smt2                                                             |  20.102s  |  20.102s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225246.smt2                                                             |   3.705s  |   3.705s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225256.smt2                                                             |  16.685s  |  16.685s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225257.smt2                                                             |  12.368s  |  12.368s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225263.smt2                                                             |  21.313s  |  21.313s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225264.smt2                                                             |   4.048s  |   4.048s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225271.smt2                                                             |  11.725s  |  11.725s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225275.smt2                                                             |  10.089s  |  10.089s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225279.smt2                                                             |   9.718s  |   9.718s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225303.smt2                                                             |   6.702s  |   6.702s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225668.smt2                                                             |   0.732s  |   0.732s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225676.smt2                                                             |   5.531s  |   5.531s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225689.smt2                                                             |   4.105s  |   4.105s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225692.smt2                                                             |   5.955s  |   5.955s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225731.smt2                                                             |   6.265s  |   6.265s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225733.smt2                                                             |   4.888s  |   4.888s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225736.smt2                                                             |  16.854s  |  16.854s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225745.smt2                                                             |  10.374s  |  10.374s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225748.smt2                                                             |  20.223s  |  20.223s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225758.smt2                                                             |  12.912s  |  12.912s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225761.smt2                                                             |  21.537s  |  21.537s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225764.smt2                                                             |  18.315s  |  18.315s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225771.smt2                                                             |  15.909s  |  15.909s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225773.smt2                                                             |  19.996s  |  19.996s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225779.smt2                                                             |  14.871s  |  14.871s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225783.smt2                                                             |  20.479s  |  20.479s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225826.smt2                                                             |   9.898s  |   9.898s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225841.smt2                                                             |  12.867s  |  12.867s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225860.smt2                                                             |  20.583s  |  20.583s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225887.smt2                                                             |  14.223s  |  14.223s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228430.smt2                                                             |  20.628s  |  20.628s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228442.smt2                                                             |  21.822s  |  21.822s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228448.smt2                                                             |  21.954s  |  21.954s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228452.smt2                                                             |  12.052s  |  12.052s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228479.smt2                                                             |  17.469s  |  17.469s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228491.smt2                                                             |  17.283s  |  17.283s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228496.smt2                                                             |  14.671s  |  14.671s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228508.smt2                                                             |  13.362s  |  13.362s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228531.smt2                                                             |  13.169s  |  13.169s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc4243.smt2                                                            |   1.990s  |   1.990s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc4289.smt2                                                            |   5.009s  |   5.009s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc4773.smt2                                                            |   0.641s  |   0.641s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc4791.smt2                                                            |   9.600s  |   9.600s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5285.smt2                                                            |   4.054s  |   4.054s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5327.smt2                                                            |   3.920s  |   3.920s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5331.smt2                                                            |   5.480s  |   5.480s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5680.smt2                                                            |   4.806s  |   4.806s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5689.smt2                                                            |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5711.smt2                                                            |   5.623s  |   5.623s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5712.smt2                                                            |  13.145s  |  13.145s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5735.smt2                                                            |   0.356s  |   0.356s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5742.smt2                                                            |  10.231s  |  10.231s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5748.smt2                                                            |  12.163s  |  12.163s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5749.smt2                                                            |  12.913s  |  12.913s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5751.smt2                                                            |   5.498s  |   5.498s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5769.smt2                                                            |   1.946s  |   1.946s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5771.smt2                                                            |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5782.smt2                                                            |   4.105s  |   4.105s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5793.smt2                                                            |   3.408s  |   3.408s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5806.smt2                                                            |   5.518s  |   5.518s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5817.smt2                                                            |   6.422s  |   6.422s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5840.smt2                                                            |   3.261s  |   3.261s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5848.smt2                                                            |   2.684s  |   2.684s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6049.smt2                                                            |   3.437s  |   3.437s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6074.smt2                                                            |   5.432s  |   5.432s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6105.smt2                                                            |   6.422s  |   6.422s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6120.smt2                                                            |   3.996s  |   3.996s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6139.smt2                                                            |   4.461s  |   4.461s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6150.smt2                                                            |   0.583s  |   0.583s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6161.smt2                                                            |   6.396s  |   6.396s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6178.smt2                                                            |   6.429s  |   6.429s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6181.smt2                                                            |  10.156s  |  10.156s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6195.smt2                                                            |  20.449s  |  20.449s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6199.smt2                                                            |  19.801s  |  19.801s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6205.smt2                                                            |  21.045s  |  21.045s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6217.smt2                                                            |  20.870s  |  20.870s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6229.smt2                                                            |  13.601s  |  13.601s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6241.smt2                                                            |   3.451s  |   3.451s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6242.smt2                                                            |   5.614s  |   5.614s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6250.smt2                                                            |  11.325s  |  11.325s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6255.smt2                                                            |  12.845s  |  12.845s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6270.smt2                                                            |  20.483s  |  20.483s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6271.smt2                                                            |   0.501s  |   0.501s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6272.smt2                                                            |   3.026s  |   3.026s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6280.smt2                                                            |  21.002s  |  21.002s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6287.smt2                                                            |  21.243s  |  21.243s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6288.smt2                                                            |  13.077s  |  13.077s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6291.smt2                                                            |   8.151s  |   8.151s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6295.smt2                                                            |  19.687s  |  19.687s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6298.smt2                                                            |  21.027s  |  21.027s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6299.smt2                                                            |  17.102s  |  17.102s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6305.smt2                                                            |  11.492s  |  11.492s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6308.smt2                                                            |  20.966s  |  20.966s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6314.smt2                                                            |  20.423s  |  20.423s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6315.smt2                                                            |  16.161s  |  16.161s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6325.smt2                                                            |  12.982s  |  12.982s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6328.smt2                                                            |  15.090s  |  15.090s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6336.smt2                                                            |   8.942s  |   8.942s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6339.smt2                                                            |  18.310s  |  18.310s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6346.smt2                                                            |   6.271s  |   6.271s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6845.smt2                                                            |   2.776s  |   2.776s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7060.smt2                                                            |   0.357s  |   0.357s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7064.smt2                                                            |   0.499s  |   0.499s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7068.smt2                                                            |   6.000s  |   6.000s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7086.smt2                                                            |   8.251s  |   8.251s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7087.smt2                                                            |  12.273s  |  12.273s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7094.smt2                                                            |   8.794s  |   8.794s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7104.smt2                                                            |   5.226s  |   5.226s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7105.smt2                                                            |  11.775s  |  11.775s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7116.smt2                                                            |   9.522s  |   9.522s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7117.smt2                                                            |   9.276s  |   9.276s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7120.smt2                                                            |   9.827s  |   9.827s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7124.smt2                                                            |   7.834s  |   7.834s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7130.smt2                                                            |   6.987s  |   6.987s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7131.smt2                                                            |   8.121s  |   8.121s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7133.smt2                                                            |  12.302s  |  12.302s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7225.smt2                                                            |   2.457s  |   2.457s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7285.smt2                                                            |   3.064s  |   3.064s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7296.smt2                                                            |   0.603s  |   0.603s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7636.smt2                                                            |   9.972s  |   9.972s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7637.smt2                                                            |  13.747s  |  13.747s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7643.smt2                                                            |  20.047s  |  20.047s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7644.smt2                                                            |  20.453s  |  20.453s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7652.smt2                                                            |   1.839s  |   1.839s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7727.smt2                                                            |  19.037s  |  19.037s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7750.smt2                                                            |  21.588s  |  21.588s  |   0.000s  | 0.0%|
|bitops7.smt2                                                                                |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bv-term-small-rw_1391.smt2                                                                  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|bv-term-small-rw_1516.smt2                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|bv-term-small-rw_166.smt2                                                                   |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bv-term-small-rw_207.smt2                                                                   |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|bv-term-small-rw_230.smt2                                                                   |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|bv-term-small-rw_250.smt2                                                                   |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|bv-term-small-rw_260.smt2                                                                   |  19.877s  |  19.877s  |   0.000s  | 0.0%|
|bv-term-small-rw_314.smt2                                                                   |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bv-term-small-rw_318.smt2                                                                   |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|bv-term-small-rw_327.smt2                                                                   |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|bv-term-small-rw_337.smt2                                                                   |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|bv-term-small-rw_356.smt2                                                                   |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|bv-term-small-rw_36.smt2                                                                    |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|bv-term-small-rw_45.smt2                                                                    |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|bv-term-small-rw_465.smt2                                                                   |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|bv-term-small-rw_47.smt2                                                                    |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|bv-term-small-rw_521.smt2                                                                   |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|bv-term-small-rw_720.smt2                                                                   |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|bv-term-small-rw_904.smt2                                                                   |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|bvsdiv.smt2                                                                                 |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|cvs_vc105322.smt2                                                                           |   3.095s  |   3.095s  |   0.000s  | 0.0%|
|cvs_vc105323.smt2                                                                           |   2.648s  |   2.648s  |   0.000s  | 0.0%|
|cvs_vc105357.smt2                                                                           |   1.718s  |   1.718s  |   0.000s  | 0.0%|
|cvs_vc105369.smt2                                                                           |   3.958s  |   3.958s  |   0.000s  | 0.0%|
|cvs_vc105422.smt2                                                                           |   1.426s  |   1.426s  |   0.000s  | 0.0%|
|cvs_vc105458.smt2                                                                           |   2.897s  |   2.897s  |   0.000s  | 0.0%|
|div.c.20.smt2                                                                               |  21.689s  |  21.689s  |   0.000s  | 0.0%|
|div3.c.20.smt2                                                                              |  20.855s  |  20.855s  |   0.000s  | 0.0%|
|e1_1.c.smt2                                                                                 |   2.105s  |   2.105s  |   0.000s  | 0.0%|
|e2_2.c.smt2                                                                                 |   0.587s  |   0.587s  |   0.000s  | 0.0%|
|f23.smt2                                                                                    |  20.773s  |  20.773s  |   0.000s  | 0.0%|
|fig5.phx.smt2                                                                               |   2.181s  |   2.181s  |   0.000s  | 0.0%|
|gryzzles.22.lp.smt2                                                                         |  20.665s  |  20.665s  |   0.000s  | 0.0%|
|gryzzles.8.lp.smt2                                                                          |  24.153s  |  24.153s  |   0.000s  | 0.0%|
|inf1.smt2                                                                                   |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|innd_innd_vc32473.smt2                                                                      |   4.663s  |   4.663s  |   0.000s  | 0.0%|
|innd_innd_vc32492.smt2                                                                      |   0.989s  |   0.989s  |   0.000s  | 0.0%|
|innd_innd_vc32642.smt2                                                                      |   7.123s  |   7.123s  |   0.000s  | 0.0%|
|innd_innd_vc32648.smt2                                                                      |  19.153s  |  19.153s  |   0.000s  | 0.0%|
|innd_innd_vc32659.smt2                                                                      |  11.590s  |  11.590s  |   0.000s  | 0.0%|
|innd_innd_vc32740.smt2                                                                      |   7.281s  |   7.281s  |   0.000s  | 0.0%|
|innd_innd_vc33153.smt2                                                                      |   5.988s  |   5.988s  |   0.000s  | 0.0%|
|innd_innd_vc33158.smt2                                                                      |  20.392s  |  20.392s  |   0.000s  | 0.0%|
|innd_innd_vc33162.smt2                                                                      |  13.521s  |  13.521s  |   0.000s  | 0.0%|
|innd_innd_vc33342.smt2                                                                      |   7.984s  |   7.984s  |   0.000s  | 0.0%|
|innd_innd_vc33343.smt2                                                                      |   6.812s  |   6.812s  |   0.000s  | 0.0%|
|innd_innd_vc33347.smt2                                                                      |  21.332s  |  21.332s  |   0.000s  | 0.0%|
|innd_innd_vc33349.smt2                                                                      |  10.875s  |  10.875s  |   0.000s  | 0.0%|
|innd_innd_vc33528.smt2                                                                      |   7.073s  |   7.073s  |   0.000s  | 0.0%|
|innd_innd_vc33538.smt2                                                                      |   6.622s  |   6.622s  |   0.000s  | 0.0%|
|innd_innd_vc33544.smt2                                                                      |   9.632s  |   9.632s  |   0.000s  | 0.0%|
|innd_innd_vc33561.smt2                                                                      |  20.791s  |  20.791s  |   0.000s  | 0.0%|
|innd_innd_vc33564.smt2                                                                      |   6.999s  |   6.999s  |   0.000s  | 0.0%|
|innd_innd_vc33728.smt2                                                                      |   1.783s  |   1.783s  |   0.000s  | 0.0%|
|innd_innd_vc33732.smt2                                                                      |   6.710s  |   6.710s  |   0.000s  | 0.0%|
|innd_innd_vc33738.smt2                                                                      |  10.543s  |  10.543s  |   0.000s  | 0.0%|
|innd_innd_vc33741.smt2                                                                      |   7.621s  |   7.621s  |   0.000s  | 0.0%|
|innd_innd_vc33743.smt2                                                                      |   9.740s  |   9.740s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc24623.smt2                                                               |   2.763s  |   2.763s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc24627.smt2                                                               |  11.288s  |  11.288s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc24797.smt2                                                               |  13.189s  |  13.189s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc24827.smt2                                                               |  19.767s  |  19.767s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc24828.smt2                                                               |  10.439s  |  10.439s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc25420.smt2                                                               |   6.942s  |   6.942s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc25433.smt2                                                               |   5.976s  |   5.976s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc25444.smt2                                                               |  12.857s  |  12.857s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc25456.smt2                                                               |   9.081s  |   9.081s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc36443.smt2                                                                |   3.579s  |   3.579s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc36459.smt2                                                                |   7.197s  |   7.197s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc36461.smt2                                                                |   5.993s  |   5.993s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc36634.smt2                                                                |  20.079s  |  20.079s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc37055.smt2                                                                |  21.439s  |  21.439s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc37058.smt2                                                                |  14.873s  |  14.873s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc37224.smt2                                                                |   5.354s  |   5.354s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc37255.smt2                                                                |  11.563s  |  11.563s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc37260.smt2                                                                |  11.185s  |  11.185s  |   0.000s  | 0.0%|
|knightTour.in01.smt2                                                                        |  20.463s  |  20.463s  |   0.000s  | 0.0%|
|matrixsqrt.smt2                                                                             |   1.481s  |   1.481s  |   0.000s  | 0.0%|
|mobiledevice_bit8_na6_nr3_twocond.smt2                                                      |  20.539s  |  20.539s  |   0.000s  | 0.0%|
|mult1.c.20.smt2                                                                             |  20.537s  |  20.537s  |   0.000s  | 0.0%|
|ndist.b.21996.smt2                                                                          |  19.419s  |  19.419s  |   0.000s  | 0.0%|
|ndist.b.27984.smt2                                                                          |  19.337s  |  19.337s  |   0.000s  | 0.0%|
|ndist.b.28982.smt2                                                                          |   3.262s  |   3.262s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc20411.smt2                                                                    |  22.201s  |  22.201s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21034.smt2                                                                    |   9.244s  |   9.244s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21209.smt2                                                                    |   8.753s  |   8.753s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21211.smt2                                                                    |   6.987s  |   6.987s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21221.smt2                                                                    |   8.540s  |   8.540s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21229.smt2                                                                    |   7.393s  |   7.393s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21232.smt2                                                                    |   7.325s  |   7.325s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21244.smt2                                                                    |  10.833s  |  10.833s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21422.smt2                                                                    |   8.674s  |   8.674s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21427.smt2                                                                    |  11.958s  |  11.958s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21428.smt2                                                                    |   7.723s  |   7.723s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21434.smt2                                                                    |   5.981s  |   5.981s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21435.smt2                                                                    |  18.649s  |  18.649s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21446.smt2                                                                    |   6.651s  |   6.651s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21451.smt2                                                                    |   2.808s  |   2.808s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21636.smt2                                                                    |   8.286s  |   8.286s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21648.smt2                                                                    |  20.209s  |  20.209s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21666.smt2                                                                    |   9.002s  |   9.002s  |   0.000s  | 0.0%|
|predicate_1245.smt2                                                                         |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|predicate_1246.smt2                                                                         |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|predicate_169_0.smt2                                                                        |   2.107s  |   2.107s  |   0.000s  | 0.0%|
|predicate_1898.smt2                                                                         |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|predicate_2077.smt2                                                                         |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|predicate_275.smt2                                                                          |  11.449s  |  11.449s  |   0.000s  | 0.0%|
|predicate_2801.smt2                                                                         |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|predicate_484.smt2                                                                          |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|predicate_490.smt2                                                                          |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|predicate_493.smt2                                                                          |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|predicate_496.smt2                                                                          |   1.135s  |   1.135s  |   0.000s  | 0.0%|
|predicate_602.smt2                                                                          |  19.223s  |  19.223s  |   0.000s  | 0.0%|
|predicate_735.smt2                                                                          |  19.255s  |  19.255s  |   0.000s  | 0.0%|
|problem_1.smt2                                                                              |   0.341s  |   0.341s  |   0.000s  | 0.0%|
|problem_7.smt2                                                                              |  20.964s  |  20.964s  |   0.000s  | 0.0%|
|problem_8.smt2                                                                              |  20.378s  |  20.378s  |   0.000s  | 0.0%|
|problem_9.smt2                                                                              |   0.882s  |   0.882s  |   0.000s  | 0.0%|
|rand_100_400_1159666138_9.lp.smt2                                                           |  21.073s  |  21.073s  |   0.000s  | 0.0%|
|rand_150_600_1159731678_14.lp.smt2                                                          |  21.124s  |  21.124s  |   0.000s  | 0.0%|
|rand_150_600_1159731678_15.lp.smt2                                                          |  21.184s  |  21.184s  |   0.000s  | 0.0%|
|rand_200_800_1159728969_10.lp.smt2                                                          |  20.588s  |  20.588s  |   0.000s  | 0.0%|
|rand_20_100_1235851242_0_k-3_v-15_e-25_sat.gph.smt2                                         |  21.297s  |  21.297s  |   0.000s  | 0.0%|
|rand_65_500_1235857888_0_k-6_sat.gph.smt2                                                   |  20.764s  |  20.764s  |   0.000s  | 0.0%|
|rand_80_500_1235848939_0_k-9_sat.gph.smt2                                                   |  22.095s  |  22.095s  |   0.000s  | 0.0%|
|rfunit_flat-64.smt2                                                                         |   0.640s  |   0.640s  |   0.000s  | 0.0%|
|run_00000.trace.Alloc_zero__011273.smt2                                                     |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|run_00000.trace.Alloc_zero__018344.smt2                                                     |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|run_00000.trace.Alloc_zero__019220.smt2                                                     |   0.505s  |   0.505s  |   0.000s  | 0.0%|
|run_00000.trace.Alloc_zero__020079.smt2                                                     |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|run_00000.trace.cond_016653_0x95026e6_00.smt2                                               |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|run_00000.trace.cond_017116_0x950130a_00.smt2                                               |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|run_00000.trace.cond_017924_0x950130a_00.smt2                                               |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|run_00000.trace.cond_018783_0x950130a_00.smt2                                               |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|run_00000.trace.cond_019196_0x95026e6_00.smt2                                               |   0.260s  |   0.260s  |   0.000s  | 0.0%|
|run_00000.trace.cond_019659_0x950130a_00.smt2                                               |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|run_00000.trace.cond_020055_0x95026e6_00.smt2                                               |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|run_00000.trace.cond_285172_0xe7af40_00.smt2                                                |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|run_00000.trace.cond_285198_0xe7af87_00.smt2                                                |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|run_00000.trace.cond_455476_0xe7af69_00.smt2                                                |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|run_00012.trace.cond_057573_0x16388_00.smt2                                                 |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|run_03230.trace.cond_000028_0x40201f_00.smt2                                                |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|run_03230.trace.cond_000032_0x40248d_00.smt2                                                |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|run_03230.trace.cond_011742_0x4066e2_00.smt2                                                |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|run_03230.trace.cond_011923_0x4182b4_00.smt2                                                |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|run_03230.trace.cond_011951_0x4182b4_00.smt2                                                |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|run_03230.trace.cond_011955_0x4182de_00.smt2                                                |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|run_03230.trace.cond_011969_0x4182de_00.smt2                                                |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|run_03230.trace.cond_012011_0x4182de_00.smt2                                                |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|run_03230.trace.cond_012035_0x4182b4_00.smt2                                                |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|run_03230.trace.cond_012053_0x4182de_00.smt2                                                |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|run_03230.trace.cond_012133_0x4182b4_00.smt2                                                |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|run_03230.trace.cond_012161_0x4182b4_00.smt2                                                |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|run_03230.trace.cond_012175_0x4182b4_00.smt2                                                |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025314_0x41821d_00.smt2                                                |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025405_0x418209_00.smt2                                                |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025439_0x418209_00.smt2                                                |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025442_0x41821d_00.smt2                                                |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025454_0x418209_00.smt2                                                |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025469_0x418209_00.smt2                                                |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025506_0x41821d_00.smt2                                                |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025552_0x41820e_00.smt2                                                |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025570_0x41821d_00.smt2                                                |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025582_0x418209_00.smt2                                                |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025597_0x418209_00.smt2                                                |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025600_0x41821d_00.smt2                                                |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025616_0x41820e_00.smt2                                                |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025638_0x41821d_00.smt2                                                |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|send-more-money.smt2                                                                        |   0.874s  |   0.874s  |   0.000s  | 0.0%|
|servers_slapd_a_vc149572.smt2                                                               |   2.621s  |   2.621s  |   0.000s  | 0.0%|
|servers_slapd_a_vc149789.smt2                                                               |  19.541s  |  19.541s  |   0.000s  | 0.0%|
|simple_bit8_na1_nr1_twocond.smt2                                                            |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|smulov4bw1024.smt2                                                                          |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|sort.smt2                                                                                   |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|src_wget_vc17453.smt2                                                                       |   1.209s  |   1.209s  |   0.000s  | 0.0%|
|src_wget_vc17891.smt2                                                                       |   8.661s  |   8.661s  |   0.000s  | 0.0%|
|src_wget_vc17906.smt2                                                                       |  20.578s  |  20.578s  |   0.000s  | 0.0%|
|src_wget_vc17911.smt2                                                                       |  21.094s  |  21.094s  |   0.000s  | 0.0%|
|src_wget_vc17912.smt2                                                                       |  19.809s  |  19.809s  |   0.000s  | 0.0%|
|src_wget_vc17913.smt2                                                                       |  17.473s  |  17.473s  |   0.000s  | 0.0%|
|src_wget_vc18169.smt2                                                                       |  19.917s  |  19.917s  |   0.000s  | 0.0%|
|src_wget_vc18506.smt2                                                                       |  20.445s  |  20.445s  |   0.000s  | 0.0%|
|test_v3_r3_vr10_c1_s24300.smt2                                                              |  20.372s  |  20.372s  |   0.000s  | 0.0%|
|try3_noof_functions_dwp_stty.visible.il.dwp.smt2                                            |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|try3_noof_functions_dwp_touch.yyerror.il.dwp.smt2                                           |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|try5_small_noof_functions_dwp_cut.hash_int.il.dwp.smt2                                      |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|try5_small_noof_functions_dwp_expr.nomoreargs.il.dwp.smt2                                   |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|try5_small_noof_functions_dwp_stty.visible.il.dwp.smt2                                      |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_cat.quoting_options_from_style.il.flanagansaxe.smt2  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_chgrp.quoting_options_from_style.il.flanagansaxe.smt2  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_cut.hash_int.il.flanagansaxe.smt2                    |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_echo.quoting_options_from_style.il.flanagansaxe.smt2  |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_env.quoting_options_from_style.il.flanagansaxe.smt2  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_fold.quoting_options_from_style.il.flanagansaxe.smt2  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_hostid.quoting_options_from_style.il.flanagansaxe.smt2  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_kill.quoting_options_from_style.il.flanagansaxe.smt2  |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_link.quoting_options_from_style.il.flanagansaxe.smt2  |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_mkfifo.quoting_options_from_style.il.flanagansaxe.smt2  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_nice.quoting_options_from_style.il.flanagansaxe.smt2  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_nl.quoting_options_from_style.il.flanagansaxe.smt2   |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_pinky.quoting_options_from_style.il.flanagansaxe.smt2  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_ptx.quoting_options_from_style.il.flanagansaxe.smt2  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_seq.quoting_options_from_style.il.flanagansaxe.smt2  |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_sleep.quoting_options_from_style.il.flanagansaxe.smt2  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_sum.quoting_options_from_style.il.flanagansaxe.smt2  |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_tac.quoting_options_from_style.il.flanagansaxe.smt2  |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_test.quoting_options_from_style.il.flanagansaxe.smt2  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_touch.quoting_options_from_style.il.flanagansaxe.smt2  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_true.quoting_options_from_style.il.flanagansaxe.smt2  |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_tsort.quoting_options_from_style.il.flanagansaxe.smt2  |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_tty.quoting_options_from_style.il.flanagansaxe.smt2  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_unexpand.quoting_options_from_style.il.flanagansaxe.smt2  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_users.quoting_options_from_style.il.flanagansaxe.smt2  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_vdir.quoting_options_from_style.il.flanagansaxe.smt2  |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_wc.quoting_options_from_style.il.flanagansaxe.smt2   |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|try5_small_noof_functions_fse-bfs_shuf.input_numbers_option_used.il.fse-bfs.smt2            |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|try5_small_true_functions_dwp_stty.visible.il.dwp.smt2                                      |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|try5_small_true_functions_dwp_yes.close_stdout_set_file_name.il.dwp.smt2                    |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_chgrp.i_ring_init.il.flanagansaxe.smt2               |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_join.initseq.il.flanagansaxe.smt2                    |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_md5sum.md5_init_ctx.il.flanagansaxe.smt2             |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_sha1sum.sha1_read_ctx.il.flanagansaxe.smt2           |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_stty.visible.il.flanagansaxe.smt2                    |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_tac.rpl_re_set_syntax.il.flanagansaxe.smt2           |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_vdir.hash_get_n_entries.il.flanagansaxe.smt2         |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_vdir.unsigned_file_size.il.flanagansaxe.smt2         |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|try5_small_true_functions_fse-bfs_stty.visible.il.fse-bfs.smt2                              |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|unconstrained04.smt2                                                                        |  19.045s  |  19.045s  |   0.000s  | 0.0%|
|unconstrained07.smt2                                                                        |  19.554s  |  19.554s  |   0.000s  | 0.0%|
|unconstrained08.smt2                                                                        |  19.260s  |  19.260s  |   0.000s  | 0.0%|
</details>
