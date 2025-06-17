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
Job description: check for square free polynomials in nlsat_explain
Job tag: sqf_check
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 8f88bf9998570007162fcbf5030979788e90f223
Z3 branch: 
Z3 options: "-T:600 -st"
Z3 inputs: inputs/QF_BV_SAT
Z3 commit message: use is_square_free_at_sample instead of is_well_oriented

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: check for square free polynomials in nlsat_explain
Job tag: sqf_check
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 8f88bf9998570007162fcbf5030979788e90f223
Z3 branch: 
Z3 options: "-T:600 -st"
Z3 inputs: inputs/QF_BV_SAT
Z3 commit message: use is_square_free_at_sample instead of is_well_oriented

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |  76.986s  |  76.986s  |   0.000s  | 0.0%|
|100.smt2                                                                                    | 599.664s  | 599.664s  |   0.000s  | 0.0%|
|102.smt2                                                                                    | 599.567s  | 599.567s  |   0.000s  | 0.0%|
|108.smt2                                                                                    | 599.898s  | 599.898s  |   0.000s  | 0.0%|
|111.smt2                                                                                    | 548.710s  | 548.710s  |   0.000s  | 0.0%|
|113.smt2                                                                                    |   1.685s  |   1.685s  |   0.000s  | 0.0%|
|115.smt2                                                                                    |   6.448s  |   6.448s  |   0.000s  | 0.0%|
|15.smt2                                                                                     |  44.101s  |  44.101s  |   0.000s  | 0.0%|
|162.smt2                                                                                    |   9.720s  |   9.720s  |   0.000s  | 0.0%|
|170.smt2                                                                                    |  17.429s  |  17.429s  |   0.000s  | 0.0%|
|20.smt2                                                                                     | 599.203s  | 599.203s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  55.933s  |  55.933s  |   0.000s  | 0.0%|
|29.smt2                                                                                     | 598.402s  | 598.402s  |   0.000s  | 0.0%|
|33.smt2                                                                                     | 376.434s  | 376.434s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  55.897s  |  55.897s  |   0.000s  | 0.0%|
|64.smt2                                                                                     | 599.238s  | 599.238s  |   0.000s  | 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |   5.217s  |   5.217s  |   0.000s  | 0.0%|
|80.smt2                                                                                     | 599.412s  | 599.412s  |   0.000s  | 0.0%|
|90.smt2                                                                                     | 589.670s  | 589.670s  |   0.000s  | 0.0%|
|94.smt2                                                                                     | 143.325s  | 143.325s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |  76.986s  |  76.986s  |   0.000s  | 0.0%|
|100.smt2                                                                                    | 599.664s  | 599.664s  |   0.000s  | 0.0%|
|102.smt2                                                                                    | 599.567s  | 599.567s  |   0.000s  | 0.0%|
|108.smt2                                                                                    | 599.898s  | 599.898s  |   0.000s  | 0.0%|
|111.smt2                                                                                    | 548.710s  | 548.710s  |   0.000s  | 0.0%|
|113.smt2                                                                                    |   1.685s  |   1.685s  |   0.000s  | 0.0%|
|115.smt2                                                                                    |   6.448s  |   6.448s  |   0.000s  | 0.0%|
|15.smt2                                                                                     |  44.101s  |  44.101s  |   0.000s  | 0.0%|
|162.smt2                                                                                    |   9.720s  |   9.720s  |   0.000s  | 0.0%|
|170.smt2                                                                                    |  17.429s  |  17.429s  |   0.000s  | 0.0%|
|20.smt2                                                                                     | 599.203s  | 599.203s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  55.933s  |  55.933s  |   0.000s  | 0.0%|
|29.smt2                                                                                     | 598.402s  | 598.402s  |   0.000s  | 0.0%|
|33.smt2                                                                                     | 376.434s  | 376.434s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  55.897s  |  55.897s  |   0.000s  | 0.0%|
|64.smt2                                                                                     | 599.238s  | 599.238s  |   0.000s  | 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |   5.217s  |   5.217s  |   0.000s  | 0.0%|
|80.smt2                                                                                     | 599.412s  | 599.412s  |   0.000s  | 0.0%|
|90.smt2                                                                                     | 589.670s  | 589.670s  |   0.000s  | 0.0%|
|94.smt2                                                                                     | 143.325s  | 143.325s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |  76.986s  |  76.986s  |   0.000s  | 0.0%|
|100.smt2                                                                                    | 599.664s  | 599.664s  |   0.000s  | 0.0%|
|102.smt2                                                                                    | 599.567s  | 599.567s  |   0.000s  | 0.0%|
|108.smt2                                                                                    | 599.898s  | 599.898s  |   0.000s  | 0.0%|
|111.smt2                                                                                    | 548.710s  | 548.710s  |   0.000s  | 0.0%|
|113.smt2                                                                                    |   1.685s  |   1.685s  |   0.000s  | 0.0%|
|115.smt2                                                                                    |   6.448s  |   6.448s  |   0.000s  | 0.0%|
|15.smt2                                                                                     |  44.101s  |  44.101s  |   0.000s  | 0.0%|
|162.smt2                                                                                    |   9.720s  |   9.720s  |   0.000s  | 0.0%|
|170.smt2                                                                                    |  17.429s  |  17.429s  |   0.000s  | 0.0%|
|20.smt2                                                                                     | 599.203s  | 599.203s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  55.933s  |  55.933s  |   0.000s  | 0.0%|
|29.smt2                                                                                     | 598.402s  | 598.402s  |   0.000s  | 0.0%|
|33.smt2                                                                                     | 376.434s  | 376.434s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  55.897s  |  55.897s  |   0.000s  | 0.0%|
|64.smt2                                                                                     | 599.238s  | 599.238s  |   0.000s  | 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |   5.217s  |   5.217s  |   0.000s  | 0.0%|
|80.smt2                                                                                     | 599.412s  | 599.412s  |   0.000s  | 0.0%|
|90.smt2                                                                                     | 589.670s  | 589.670s  |   0.000s  | 0.0%|
|94.smt2                                                                                     | 143.325s  | 143.325s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |  76.986s  |  76.986s  |   0.000s  | 0.0%|
|100.smt2                                                                                    | 599.664s  | 599.664s  |   0.000s  | 0.0%|
|102.smt2                                                                                    | 599.567s  | 599.567s  |   0.000s  | 0.0%|
|108.smt2                                                                                    | 599.898s  | 599.898s  |   0.000s  | 0.0%|
|111.smt2                                                                                    | 548.710s  | 548.710s  |   0.000s  | 0.0%|
|113.smt2                                                                                    |   1.685s  |   1.685s  |   0.000s  | 0.0%|
|115.smt2                                                                                    |   6.448s  |   6.448s  |   0.000s  | 0.0%|
|15.smt2                                                                                     |  44.101s  |  44.101s  |   0.000s  | 0.0%|
|162.smt2                                                                                    |   9.720s  |   9.720s  |   0.000s  | 0.0%|
|170.smt2                                                                                    |  17.429s  |  17.429s  |   0.000s  | 0.0%|
|20.smt2                                                                                     | 599.203s  | 599.203s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  55.933s  |  55.933s  |   0.000s  | 0.0%|
|29.smt2                                                                                     | 598.402s  | 598.402s  |   0.000s  | 0.0%|
|33.smt2                                                                                     | 376.434s  | 376.434s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  55.897s  |  55.897s  |   0.000s  | 0.0%|
|64.smt2                                                                                     | 599.238s  | 599.238s  |   0.000s  | 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |   5.217s  |   5.217s  |   0.000s  | 0.0%|
|80.smt2                                                                                     | 599.412s  | 599.412s  |   0.000s  | 0.0%|
|90.smt2                                                                                     | 589.670s  | 589.670s  |   0.000s  | 0.0%|
|94.smt2                                                                                     | 143.325s  | 143.325s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|servers_slapd_a_vc149789.smt2                                                              | 601.273s |3325.0MiB|
|108.smt2                                                                                   | 599.898s |683.0MiB|
|bench_7669.smt2                                                                            | 599.894s |732.0MiB|
|bench_5581.smt2                                                                            | 599.800s |154.0MiB|
|bench_3945.smt2                                                                            | 599.792s |3594.0MiB|
|bench_17033.smt2                                                                           | 599.783s |194.0MiB|
|bench_14161.smt2                                                                           | 599.764s |354.0MiB|
|bench_10832.smt2                                                                           | 599.762s |345.0MiB|
|bench_996.smt2                                                                             | 599.718s |320.0MiB|
|bench_6097.smt2                                                                            | 599.698s |227.0MiB|
|bench_8478.smt2                                                                            | 599.686s |170.0MiB|
|VS3-benchmark-S1.smt2                                                                      | 599.679s |109.0MiB|
|bench_4933.smt2                                                                            | 599.671s |292.0MiB|
|100.smt2                                                                                   | 599.664s |247.0MiB|
|bench_16862.smt2                                                                           | 599.663s |147.0MiB|
|bench_6606.smt2                                                                            | 599.648s |287.0MiB|
|bench_1250.smt2                                                                            | 599.624s |76.816MiB|
|bench_13129.smt2                                                                           | 599.620s |292.0MiB|
|bench_2258.smt2                                                                            | 599.610s |79.048MiB|
|bench_3218.smt2                                                                            | 599.594s |76.896MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|servers_slapd_a_vc149789.smt2                                                              | 601.273s |3325.0MiB|
|108.smt2                                                                                   | 599.898s |683.0MiB|
|bench_7669.smt2                                                                            | 599.894s |732.0MiB|
|bench_5581.smt2                                                                            | 599.800s |154.0MiB|
|bench_3945.smt2                                                                            | 599.792s |3594.0MiB|
|bench_17033.smt2                                                                           | 599.783s |194.0MiB|
|bench_14161.smt2                                                                           | 599.764s |354.0MiB|
|bench_10832.smt2                                                                           | 599.762s |345.0MiB|
|bench_996.smt2                                                                             | 599.718s |320.0MiB|
|bench_6097.smt2                                                                            | 599.698s |227.0MiB|
|bench_8478.smt2                                                                            | 599.686s |170.0MiB|
|VS3-benchmark-S1.smt2                                                                      | 599.679s |109.0MiB|
|bench_4933.smt2                                                                            | 599.671s |292.0MiB|
|100.smt2                                                                                   | 599.664s |247.0MiB|
|bench_16862.smt2                                                                           | 599.663s |147.0MiB|
|bench_6606.smt2                                                                            | 599.648s |287.0MiB|
|bench_1250.smt2                                                                            | 599.624s |76.816MiB|
|bench_13129.smt2                                                                           | 599.620s |292.0MiB|
|bench_2258.smt2                                                                            | 599.610s |79.048MiB|
|bench_3218.smt2                                                                            | 599.594s |76.896MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |110.0MiB|110.0MiB|0B| 0.0%|
|100.smt2                                                                                    |247.0MiB|247.0MiB|0B| 0.0%|
|102.smt2                                                                                    |369.0MiB|369.0MiB|0B| 0.0%|
|108.smt2                                                                                    |683.0MiB|683.0MiB|0B| 0.0%|
|111.smt2                                                                                    |673.0MiB|673.0MiB|0B| 0.0%|
|113.smt2                                                                                    |61.156MiB|61.156MiB|0B| 0.0%|
|115.smt2                                                                                    |212.0MiB|212.0MiB|0B| 0.0%|
|15.smt2                                                                                     |108.0MiB|108.0MiB|0B| 0.0%|
|162.smt2                                                                                    |351.0MiB|351.0MiB|0B| 0.0%|
|170.smt2                                                                                    |353.0MiB|353.0MiB|0B| 0.0%|
|20.smt2                                                                                     |220.0MiB|220.0MiB|0B| 0.0%|
|26.smt2                                                                                     |156.0MiB|156.0MiB|0B| 0.0%|
|29.smt2                                                                                     |170.0MiB|170.0MiB|0B| 0.0%|
|33.smt2                                                                                     |125.0MiB|125.0MiB|0B| 0.0%|
|41.smt2                                                                                     |115.0MiB|115.0MiB|0B| 0.0%|
|64.smt2                                                                                     |369.0MiB|369.0MiB|0B| 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |31.436MiB|31.436MiB|0B| 0.0%|
|80.smt2                                                                                     |369.0MiB|369.0MiB|0B| 0.0%|
|90.smt2                                                                                     |369.0MiB|369.0MiB|0B| 0.0%|
|94.smt2                                                                                     |369.0MiB|369.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |110.0MiB|110.0MiB|0B| 0.0%|
|100.smt2                                                                                    |247.0MiB|247.0MiB|0B| 0.0%|
|102.smt2                                                                                    |369.0MiB|369.0MiB|0B| 0.0%|
|108.smt2                                                                                    |683.0MiB|683.0MiB|0B| 0.0%|
|111.smt2                                                                                    |673.0MiB|673.0MiB|0B| 0.0%|
|113.smt2                                                                                    |61.156MiB|61.156MiB|0B| 0.0%|
|115.smt2                                                                                    |212.0MiB|212.0MiB|0B| 0.0%|
|15.smt2                                                                                     |108.0MiB|108.0MiB|0B| 0.0%|
|162.smt2                                                                                    |351.0MiB|351.0MiB|0B| 0.0%|
|170.smt2                                                                                    |353.0MiB|353.0MiB|0B| 0.0%|
|20.smt2                                                                                     |220.0MiB|220.0MiB|0B| 0.0%|
|26.smt2                                                                                     |156.0MiB|156.0MiB|0B| 0.0%|
|29.smt2                                                                                     |170.0MiB|170.0MiB|0B| 0.0%|
|33.smt2                                                                                     |125.0MiB|125.0MiB|0B| 0.0%|
|41.smt2                                                                                     |115.0MiB|115.0MiB|0B| 0.0%|
|64.smt2                                                                                     |369.0MiB|369.0MiB|0B| 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |31.436MiB|31.436MiB|0B| 0.0%|
|80.smt2                                                                                     |369.0MiB|369.0MiB|0B| 0.0%|
|90.smt2                                                                                     |369.0MiB|369.0MiB|0B| 0.0%|
|94.smt2                                                                                     |369.0MiB|369.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |110.0MiB|110.0MiB|0B| 0.0%|
|100.smt2                                                                                    |247.0MiB|247.0MiB|0B| 0.0%|
|102.smt2                                                                                    |369.0MiB|369.0MiB|0B| 0.0%|
|108.smt2                                                                                    |683.0MiB|683.0MiB|0B| 0.0%|
|111.smt2                                                                                    |673.0MiB|673.0MiB|0B| 0.0%|
|113.smt2                                                                                    |61.156MiB|61.156MiB|0B| 0.0%|
|115.smt2                                                                                    |212.0MiB|212.0MiB|0B| 0.0%|
|15.smt2                                                                                     |108.0MiB|108.0MiB|0B| 0.0%|
|162.smt2                                                                                    |351.0MiB|351.0MiB|0B| 0.0%|
|170.smt2                                                                                    |353.0MiB|353.0MiB|0B| 0.0%|
|20.smt2                                                                                     |220.0MiB|220.0MiB|0B| 0.0%|
|26.smt2                                                                                     |156.0MiB|156.0MiB|0B| 0.0%|
|29.smt2                                                                                     |170.0MiB|170.0MiB|0B| 0.0%|
|33.smt2                                                                                     |125.0MiB|125.0MiB|0B| 0.0%|
|41.smt2                                                                                     |115.0MiB|115.0MiB|0B| 0.0%|
|64.smt2                                                                                     |369.0MiB|369.0MiB|0B| 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |31.436MiB|31.436MiB|0B| 0.0%|
|80.smt2                                                                                     |369.0MiB|369.0MiB|0B| 0.0%|
|90.smt2                                                                                     |369.0MiB|369.0MiB|0B| 0.0%|
|94.smt2                                                                                     |369.0MiB|369.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |110.0MiB|110.0MiB|0B| 0.0%|
|100.smt2                                                                                    |247.0MiB|247.0MiB|0B| 0.0%|
|102.smt2                                                                                    |369.0MiB|369.0MiB|0B| 0.0%|
|108.smt2                                                                                    |683.0MiB|683.0MiB|0B| 0.0%|
|111.smt2                                                                                    |673.0MiB|673.0MiB|0B| 0.0%|
|113.smt2                                                                                    |61.156MiB|61.156MiB|0B| 0.0%|
|115.smt2                                                                                    |212.0MiB|212.0MiB|0B| 0.0%|
|15.smt2                                                                                     |108.0MiB|108.0MiB|0B| 0.0%|
|162.smt2                                                                                    |351.0MiB|351.0MiB|0B| 0.0%|
|170.smt2                                                                                    |353.0MiB|353.0MiB|0B| 0.0%|
|20.smt2                                                                                     |220.0MiB|220.0MiB|0B| 0.0%|
|26.smt2                                                                                     |156.0MiB|156.0MiB|0B| 0.0%|
|29.smt2                                                                                     |170.0MiB|170.0MiB|0B| 0.0%|
|33.smt2                                                                                     |125.0MiB|125.0MiB|0B| 0.0%|
|41.smt2                                                                                     |115.0MiB|115.0MiB|0B| 0.0%|
|64.smt2                                                                                     |369.0MiB|369.0MiB|0B| 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |31.436MiB|31.436MiB|0B| 0.0%|
|80.smt2                                                                                     |369.0MiB|369.0MiB|0B| 0.0%|
|90.smt2                                                                                     |369.0MiB|369.0MiB|0B| 0.0%|
|94.smt2                                                                                     |369.0MiB|369.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|smulov4bw1024.smt2                                                                         | 592.420s |4662.0MiB|
|bench_3945.smt2                                                                            | 599.792s |3594.0MiB|
|servers_slapd_a_vc149789.smt2                                                              | 601.273s |3325.0MiB|
|bench_8495.smt2                                                                            | 599.360s |3076.0MiB|
|src_wget_vc17912.smt2                                                                      | 347.678s |1057.0MiB|
|src_wget_vc17911.smt2                                                                      | 152.623s |1057.0MiB|
|src_wget_vc17913.smt2                                                                      |  34.927s |1056.0MiB|
|bench_3082.smt2                                                                            | 599.316s |963.0MiB|
|bench_102.smt2                                                                             | 599.426s |884.0MiB|
|bin_libsmbclient_vc1225263.smt2                                                            |  28.274s |866.0MiB|
|bin_libmsrpc_vc1228577.smt2                                                                |  39.822s |865.0MiB|
|bin_libsmbclient_vc1225279.smt2                                                            |  28.617s |865.0MiB|
|bin_libmsrpc_vc1225412.smt2                                                                |  27.233s |863.0MiB|
|bin_libsmbsharemodes_vc6314.smt2                                                           |  27.836s |850.0MiB|
|bin_libsmbsharemodes_vc6325.smt2                                                           |  31.727s |849.0MiB|
|bin_libsmbsharemodes_vc6229.smt2                                                           |  38.984s |840.0MiB|
|bin_eventlogadm_vc331156.smt2                                                              |  29.071s |836.0MiB|
|bin_eventlogadm_vc331167.smt2                                                              |  20.283s |834.0MiB|
|bin_eventlogadm_vc331146.smt2                                                              |  41.625s |833.0MiB|
|src_wget_vc17906.smt2                                                                      |  42.592s |825.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|smulov4bw1024.smt2                                                                         | 592.420s |4662.0MiB|
|bench_3945.smt2                                                                            | 599.792s |3594.0MiB|
|servers_slapd_a_vc149789.smt2                                                              | 601.273s |3325.0MiB|
|bench_8495.smt2                                                                            | 599.360s |3076.0MiB|
|src_wget_vc17912.smt2                                                                      | 347.678s |1057.0MiB|
|src_wget_vc17911.smt2                                                                      | 152.623s |1057.0MiB|
|src_wget_vc17913.smt2                                                                      |  34.927s |1056.0MiB|
|bench_3082.smt2                                                                            | 599.316s |963.0MiB|
|bench_102.smt2                                                                             | 599.426s |884.0MiB|
|bin_libsmbclient_vc1225263.smt2                                                            |  28.274s |866.0MiB|
|bin_libmsrpc_vc1228577.smt2                                                                |  39.822s |865.0MiB|
|bin_libsmbclient_vc1225279.smt2                                                            |  28.617s |865.0MiB|
|bin_libmsrpc_vc1225412.smt2                                                                |  27.233s |863.0MiB|
|bin_libsmbsharemodes_vc6314.smt2                                                           |  27.836s |850.0MiB|
|bin_libsmbsharemodes_vc6325.smt2                                                           |  31.727s |849.0MiB|
|bin_libsmbsharemodes_vc6229.smt2                                                           |  38.984s |840.0MiB|
|bin_eventlogadm_vc331156.smt2                                                              |  29.071s |836.0MiB|
|bin_eventlogadm_vc331167.smt2                                                              |  20.283s |834.0MiB|
|bin_eventlogadm_vc331146.smt2                                                              |  41.625s |833.0MiB|
|src_wget_vc17906.smt2                                                                      |  42.592s |825.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|10.smt2                                                                                     |  76.986s  |  76.986s  |   0.000s  | 0.0%|
|100.smt2                                                                                    | 599.664s  | 599.664s  |   0.000s  | 0.0%|
|102.smt2                                                                                    | 599.567s  | 599.567s  |   0.000s  | 0.0%|
|108.smt2                                                                                    | 599.898s  | 599.898s  |   0.000s  | 0.0%|
|111.smt2                                                                                    | 548.710s  | 548.710s  |   0.000s  | 0.0%|
|113.smt2                                                                                    |   1.685s  |   1.685s  |   0.000s  | 0.0%|
|115.smt2                                                                                    |   6.448s  |   6.448s  |   0.000s  | 0.0%|
|15.smt2                                                                                     |  44.101s  |  44.101s  |   0.000s  | 0.0%|
|162.smt2                                                                                    |   9.720s  |   9.720s  |   0.000s  | 0.0%|
|170.smt2                                                                                    |  17.429s  |  17.429s  |   0.000s  | 0.0%|
|20.smt2                                                                                     | 599.203s  | 599.203s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  55.933s  |  55.933s  |   0.000s  | 0.0%|
|29.smt2                                                                                     | 598.402s  | 598.402s  |   0.000s  | 0.0%|
|33.smt2                                                                                     | 376.434s  | 376.434s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  55.897s  |  55.897s  |   0.000s  | 0.0%|
|64.smt2                                                                                     | 599.238s  | 599.238s  |   0.000s  | 0.0%|
|6moves_mti_7-Atd_00004_bmc.smt2                                                             |   5.217s  |   5.217s  |   0.000s  | 0.0%|
|80.smt2                                                                                     | 599.412s  | 599.412s  |   0.000s  | 0.0%|
|90.smt2                                                                                     | 589.670s  | 589.670s  |   0.000s  | 0.0%|
|94.smt2                                                                                     | 143.325s  | 143.325s  |   0.000s  | 0.0%|
|98.smt2                                                                                     | 599.548s  | 599.548s  |   0.000s  | 0.0%|
|Example_16.txt.smt2                                                                         |   2.678s  |   2.678s  |   0.000s  | 0.0%|
|Example_17.txt.smt2                                                                         |   2.496s  |   2.496s  |   0.000s  | 0.0%|
|Example_9.txt.smt2                                                                          |   3.128s  |   3.128s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_cyclic_scheduler.2.prop1_cc_ref_max.smt2                                       |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_cyclic_scheduler.4.prop1_cc_ref_max.smt2                                       |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_schedule_world.1.prop1_cc_ref_max.smt2                                         |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|QF_BV_bv8_bv_swap_three_cc_ref_max.smt2                                                     |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_cyclic_scheduler.2.prop1_cc_ref_max.smt2                                        |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_eq_sdp_v4_cc_ref_max.smt2                                                       |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_resistance.2.prop1_cc_ref_max.smt2                                              |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_swap_two_cc_ref_max.smt2                                                        |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|QF_BV_bv_bv_synabs_cc_ref_max.smt2                                                          |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|QF_BV_counter_v_cc_ref_max.smt2                                                             |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|QF_BV_eq_sdp_v5_cc_ref_max.smt2                                                             |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|QF_BV_protocols.1.prop1_cc_ref_max.smt2                                                     |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|QF_BV_v_Unidec_cc_ref_max.smt2                                                              |   0.330s  |   0.330s  |   0.000s  | 0.0%|
|Sz512_15128_0.smt2                                                                          | 599.184s  | 599.184s  |   0.000s  | 0.0%|
|Sz512_15128_1.smt2                                                                          | 598.848s  | 598.848s  |   0.000s  | 0.0%|
|Sz512_15128_2.smt2                                                                          | 598.892s  | 598.892s  |   0.000s  | 0.0%|
|Sz512_15128_3.smt2                                                                          |   0.962s  |   0.962s  |   0.000s  | 0.0%|
|VS3-benchmark-S1.smt2                                                                       | 599.679s  | 599.679s  |   0.000s  | 0.0%|
|a128test0016.smt2                                                                           |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|a164test0005.smt2                                                                           |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|a167test0001.smt2                                                                           |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|a185test0001.smt2                                                                           |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|a208test0005.smt2                                                                           |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|a213test0012.smt2                                                                           |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|a214test0017.smt2                                                                           |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|a217test0011.smt2                                                                           |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|a218test0003.smt2                                                                           |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|a222test0008.smt2                                                                           |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|a324test0010.smt2                                                                           |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|a330test0007.smt2                                                                           |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|a331test0008.smt2                                                                           |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|a333test0009.smt2                                                                           |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|a335test0041.smt2                                                                           |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|a392test0051.smt2                                                                           |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|a393test0014.smt2                                                                           |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|a397test0029.smt2                                                                           |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|a402test0032.smt2                                                                           |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|a406test0030.smt2                                                                           |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|a407test0024.smt2                                                                           |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|a409test0002.smt2                                                                           |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|a421test0007.smt2                                                                           |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|a423test0008.smt2                                                                           |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|a430test0028.smt2                                                                           |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|a434test0027.smt2                                                                           |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|a448test0003.smt2                                                                           |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|a479test0010.smt2                                                                           |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|a494test0007.smt2                                                                           |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|a497test0020.smt2                                                                           |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|a503test0089.smt2                                                                           |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|a55test0003.smt2                                                                            |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|a58test0007.smt2                                                                            |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|a600test0040.smt2                                                                           |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|a601test0056.smt2                                                                           |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|a603test0055.smt2                                                                           |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|a605test0062.smt2                                                                           |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|a60test0004.smt2                                                                            |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|a611test0014.smt2                                                                           |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|a613test0087.smt2                                                                           |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|a614test0091.smt2                                                                           |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|a616test0001.smt2                                                                           |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|a620test0100.smt2                                                                           |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|a623test0035.smt2                                                                           |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|a625test0095.smt2                                                                           |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|a628test0066.smt2                                                                           |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|a631test0073.smt2                                                                           |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|a640test0019.smt2                                                                           |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|a649test0047.smt2                                                                           |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|a653test0023.smt2                                                                           |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|a657test0107.smt2                                                                           |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|a658test0026.smt2                                                                           |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|a663test0096.smt2                                                                           |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|a664test0013.smt2                                                                           |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|a665test0064.smt2                                                                           |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|a668test0098.smt2                                                                           |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|a669test0063.smt2                                                                           |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|a674test0008.smt2                                                                           |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|a676test0004.smt2                                                                           |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|a681test0048.smt2                                                                           |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|a683test0094.smt2                                                                           |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|a685test0080.smt2                                                                           |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|a689test0069.smt2                                                                           |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|a695test0015.smt2                                                                           |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|a97test0001.smt2                                                                            |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|adpcm.smt2                                                                                  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|b188test0002.smt2                                                                           |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|b265test0001.smt2                                                                           |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|b26test0001.smt2                                                                            |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|bench_1.smt2                                                                                |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|bench_10033.smt2                                                                            |  94.804s  |  94.804s  |   0.000s  | 0.0%|
|bench_10096.smt2                                                                            | 599.081s  | 599.081s  |   0.000s  | 0.0%|
|bench_10111.smt2                                                                            |  54.927s  |  54.927s  |   0.000s  | 0.0%|
|bench_1012.smt2                                                                             |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|bench_10127.smt2                                                                            |   3.114s  |   3.114s  |   0.000s  | 0.0%|
|bench_1013.smt2                                                                             | 599.521s  | 599.521s  |   0.000s  | 0.0%|
|bench_10144.smt2                                                                            | 599.240s  | 599.240s  |   0.000s  | 0.0%|
|bench_1017.smt2                                                                             |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|bench_102.smt2                                                                              | 599.426s  | 599.426s  |   0.000s  | 0.0%|
|bench_10228.smt2                                                                            | 419.842s  | 419.842s  |   0.000s  | 0.0%|
|bench_10306.smt2                                                                            | 250.931s  | 250.931s  |   0.000s  | 0.0%|
|bench_1041.smt2                                                                             |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|bench_1043.smt2                                                                             |   0.338s  |   0.338s  |   0.000s  | 0.0%|
|bench_10451.smt2                                                                            |   3.322s  |   3.322s  |   0.000s  | 0.0%|
|bench_1050.smt2                                                                             | 170.939s  | 170.939s  |   0.000s  | 0.0%|
|bench_1053.smt2                                                                             |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|bench_1055.smt2                                                                             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|bench_10579.smt2                                                                            |  18.898s  |  18.898s  |   0.000s  | 0.0%|
|bench_1059.smt2                                                                             |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|bench_1063.smt2                                                                             |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|bench_10696.smt2                                                                            |  12.814s  |  12.814s  |   0.000s  | 0.0%|
|bench_10714.smt2                                                                            | 293.411s  | 293.411s  |   0.000s  | 0.0%|
|bench_10726.smt2                                                                            |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|bench_10737.smt2                                                                            |  72.221s  |  72.221s  |   0.000s  | 0.0%|
|bench_10784.smt2                                                                            | 118.774s  | 118.774s  |   0.000s  | 0.0%|
|bench_10791.smt2                                                                            | 599.492s  | 599.492s  |   0.000s  | 0.0%|
|bench_10800.smt2                                                                            |   2.937s  |   2.937s  |   0.000s  | 0.0%|
|bench_1081.smt2                                                                             |  38.349s  |  38.349s  |   0.000s  | 0.0%|
|bench_10815.smt2                                                                            | 298.687s  | 298.687s  |   0.000s  | 0.0%|
|bench_1082.smt2                                                                             |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|bench_10832.smt2                                                                            | 599.762s  | 599.762s  |   0.000s  | 0.0%|
|bench_10841.smt2                                                                            |   8.267s  |   8.267s  |   0.000s  | 0.0%|
|bench_1088.smt2                                                                             |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|bench_1093.smt2                                                                             | 224.019s  | 224.019s  |   0.000s  | 0.0%|
|bench_1094.smt2                                                                             |   5.050s  |   5.050s  |   0.000s  | 0.0%|
|bench_10940.smt2                                                                            | 599.495s  | 599.495s  |   0.000s  | 0.0%|
|bench_1099.smt2                                                                             | 150.388s  | 150.388s  |   0.000s  | 0.0%|
|bench_11014.smt2                                                                            |  80.400s  |  80.400s  |   0.000s  | 0.0%|
|bench_11027.smt2                                                                            | 383.991s  | 383.991s  |   0.000s  | 0.0%|
|bench_11032.smt2                                                                            | 599.568s  | 599.568s  |   0.000s  | 0.0%|
|bench_11033.smt2                                                                            |   2.219s  |   2.219s  |   0.000s  | 0.0%|
|bench_1106.smt2                                                                             |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|bench_1111.smt2                                                                             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|bench_11110.smt2                                                                            |  15.352s  |  15.352s  |   0.000s  | 0.0%|
|bench_1113.smt2                                                                             | 223.723s  | 223.723s  |   0.000s  | 0.0%|
|bench_11151.smt2                                                                            | 596.984s  | 596.984s  |   0.000s  | 0.0%|
|bench_112.smt2                                                                              |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|bench_1123.smt2                                                                             |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|bench_11232.smt2                                                                            |   7.146s  |   7.146s  |   0.000s  | 0.0%|
|bench_113.smt2                                                                              |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|bench_11341.smt2                                                                            | 301.676s  | 301.676s  |   0.000s  | 0.0%|
|bench_11357.smt2                                                                            |  12.190s  |  12.190s  |   0.000s  | 0.0%|
|bench_1136.smt2                                                                             |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|bench_11408.smt2                                                                            |  12.192s  |  12.192s  |   0.000s  | 0.0%|
|bench_1143.smt2                                                                             |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|bench_1145.smt2                                                                             | 169.221s  | 169.221s  |   0.000s  | 0.0%|
|bench_11473.smt2                                                                            |   0.552s  |   0.552s  |   0.000s  | 0.0%|
|bench_1159.smt2                                                                             |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|bench_1166.smt2                                                                             | 149.730s  | 149.730s  |   0.000s  | 0.0%|
|bench_1168.smt2                                                                             | 271.847s  | 271.847s  |   0.000s  | 0.0%|
|bench_11696.smt2                                                                            |  27.921s  |  27.921s  |   0.000s  | 0.0%|
|bench_11708.smt2                                                                            |  78.188s  |  78.188s  |   0.000s  | 0.0%|
|bench_11736.smt2                                                                            |  96.307s  |  96.307s  |   0.000s  | 0.0%|
|bench_1179.smt2                                                                             |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|bench_1180.smt2                                                                             |  69.175s  |  69.175s  |   0.000s  | 0.0%|
|bench_11811.smt2                                                                            | 599.170s  | 599.170s  |   0.000s  | 0.0%|
|bench_11826.smt2                                                                            |  76.139s  |  76.139s  |   0.000s  | 0.0%|
|bench_1184.smt2                                                                             | 305.672s  | 305.672s  |   0.000s  | 0.0%|
|bench_1187.smt2                                                                             |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|bench_119.smt2                                                                              |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|bench_11931.smt2                                                                            |  11.595s  |  11.595s  |   0.000s  | 0.0%|
|bench_1196.smt2                                                                             | 311.963s  | 311.963s  |   0.000s  | 0.0%|
|bench_11971.smt2                                                                            | 162.390s  | 162.390s  |   0.000s  | 0.0%|
|bench_1199.smt2                                                                             |   4.242s  |   4.242s  |   0.000s  | 0.0%|
|bench_120.smt2                                                                              |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|bench_12006.smt2                                                                            |  13.211s  |  13.211s  |   0.000s  | 0.0%|
|bench_1201.smt2                                                                             |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|bench_1202.smt2                                                                             | 232.601s  | 232.601s  |   0.000s  | 0.0%|
|bench_1204.smt2                                                                             |  51.206s  |  51.206s  |   0.000s  | 0.0%|
|bench_12059.smt2                                                                            | 599.301s  | 599.301s  |   0.000s  | 0.0%|
|bench_12158.smt2                                                                            | 599.514s  | 599.514s  |   0.000s  | 0.0%|
|bench_1218.smt2                                                                             |  81.374s  |  81.374s  |   0.000s  | 0.0%|
|bench_12204.smt2                                                                            |   1.854s  |   1.854s  |   0.000s  | 0.0%|
|bench_1222.smt2                                                                             | 459.655s  | 459.655s  |   0.000s  | 0.0%|
|bench_12224.smt2                                                                            |  22.024s  |  22.024s  |   0.000s  | 0.0%|
|bench_12246.smt2                                                                            |  15.459s  |  15.459s  |   0.000s  | 0.0%|
|bench_1228.smt2                                                                             |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|bench_1229.smt2                                                                             |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|bench_1233.smt2                                                                             |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|bench_1235.smt2                                                                             |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|bench_1236.smt2                                                                             |   5.900s  |   5.900s  |   0.000s  | 0.0%|
|bench_12422.smt2                                                                            |   1.867s  |   1.867s  |   0.000s  | 0.0%|
|bench_12473.smt2                                                                            | 126.906s  | 126.906s  |   0.000s  | 0.0%|
|bench_1249.smt2                                                                             |   0.241s  |   0.241s  |   0.000s  | 0.0%|
|bench_1250.smt2                                                                             | 599.624s  | 599.624s  |   0.000s  | 0.0%|
|bench_1252.smt2                                                                             | 175.261s  | 175.261s  |   0.000s  | 0.0%|
|bench_1253.smt2                                                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|bench_1256.smt2                                                                             |  78.417s  |  78.417s  |   0.000s  | 0.0%|
|bench_12625.smt2                                                                            | 342.400s  | 342.400s  |   0.000s  | 0.0%|
|bench_12655.smt2                                                                            | 479.063s  | 479.063s  |   0.000s  | 0.0%|
|bench_1266.smt2                                                                             |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|bench_1270.smt2                                                                             |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|bench_1278.smt2                                                                             |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|bench_1280.smt2                                                                             |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|bench_12821.smt2                                                                            |   3.195s  |   3.195s  |   0.000s  | 0.0%|
|bench_1283.smt2                                                                             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|bench_1285.smt2                                                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|bench_1286.smt2                                                                             | 177.995s  | 177.995s  |   0.000s  | 0.0%|
|bench_129.smt2                                                                              |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|bench_1306.smt2                                                                             | 224.372s  | 224.372s  |   0.000s  | 0.0%|
|bench_1307.smt2                                                                             |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|bench_13129.smt2                                                                            | 599.620s  | 599.620s  |   0.000s  | 0.0%|
|bench_13147.smt2                                                                            | 599.573s  | 599.573s  |   0.000s  | 0.0%|
|bench_1318.smt2                                                                             |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|bench_1323.smt2                                                                             | 598.663s  | 598.663s  |   0.000s  | 0.0%|
|bench_13284.smt2                                                                            |   5.507s  |   5.507s  |   0.000s  | 0.0%|
|bench_1329.smt2                                                                             |  33.322s  |  33.322s  |   0.000s  | 0.0%|
|bench_1332.smt2                                                                             |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|bench_13336.smt2                                                                            | 585.293s  | 585.293s  |   0.000s  | 0.0%|
|bench_1335.smt2                                                                             |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|bench_1336.smt2                                                                             |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|bench_1338.smt2                                                                             |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|bench_13483.smt2                                                                            |   6.899s  |   6.899s  |   0.000s  | 0.0%|
|bench_1349.smt2                                                                             |   3.033s  |   3.033s  |   0.000s  | 0.0%|
|bench_135.smt2                                                                              |   3.730s  |   3.730s  |   0.000s  | 0.0%|
|bench_1350.smt2                                                                             |  39.972s  |  39.972s  |   0.000s  | 0.0%|
|bench_1355.smt2                                                                             |  24.088s  |  24.088s  |   0.000s  | 0.0%|
|bench_1359.smt2                                                                             |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|bench_1361.smt2                                                                             |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|bench_1365.smt2                                                                             |  12.519s  |  12.519s  |   0.000s  | 0.0%|
|bench_1367.smt2                                                                             |   0.333s  |   0.333s  |   0.000s  | 0.0%|
|bench_1374.smt2                                                                             |   0.362s  |   0.362s  |   0.000s  | 0.0%|
|bench_13744.smt2                                                                            |  29.479s  |  29.479s  |   0.000s  | 0.0%|
|bench_13773.smt2                                                                            | 459.850s  | 459.850s  |   0.000s  | 0.0%|
|bench_1379.smt2                                                                             |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|bench_13790.smt2                                                                            |  10.190s  |  10.190s  |   0.000s  | 0.0%|
|bench_1386.smt2                                                                             |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|bench_1388.smt2                                                                             | 272.778s  | 272.778s  |   0.000s  | 0.0%|
|bench_1389.smt2                                                                             |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|bench_1391.smt2                                                                             |   0.278s  |   0.278s  |   0.000s  | 0.0%|
|bench_1400.smt2                                                                             |   1.320s  |   1.320s  |   0.000s  | 0.0%|
|bench_1401.smt2                                                                             |   1.097s  |   1.097s  |   0.000s  | 0.0%|
|bench_1405.smt2                                                                             |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|bench_141.smt2                                                                              |   4.202s  |   4.202s  |   0.000s  | 0.0%|
|bench_1412.smt2                                                                             |   0.735s  |   0.735s  |   0.000s  | 0.0%|
|bench_1414.smt2                                                                             |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|bench_14156.smt2                                                                            |  17.508s  |  17.508s  |   0.000s  | 0.0%|
|bench_14161.smt2                                                                            | 599.764s  | 599.764s  |   0.000s  | 0.0%|
|bench_14165.smt2                                                                            | 104.328s  | 104.328s  |   0.000s  | 0.0%|
|bench_1417.smt2                                                                             |   0.702s  |   0.702s  |   0.000s  | 0.0%|
|bench_142.smt2                                                                              |   3.119s  |   3.119s  |   0.000s  | 0.0%|
|bench_14209.smt2                                                                            | 515.082s  | 515.082s  |   0.000s  | 0.0%|
|bench_1424.smt2                                                                             |   0.324s  |   0.324s  |   0.000s  | 0.0%|
|bench_14284.smt2                                                                            |  11.165s  |  11.165s  |   0.000s  | 0.0%|
|bench_143.smt2                                                                              |   2.092s  |   2.092s  |   0.000s  | 0.0%|
|bench_1434.smt2                                                                             |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|bench_14358.smt2                                                                            | 103.936s  | 103.936s  |   0.000s  | 0.0%|
|bench_1440.smt2                                                                             |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|bench_1441.smt2                                                                             |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|bench_1442.smt2                                                                             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|bench_1445.smt2                                                                             |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|bench_1446.smt2                                                                             |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|bench_14461.smt2                                                                            |   7.087s  |   7.087s  |   0.000s  | 0.0%|
|bench_1447.smt2                                                                             |  29.758s  |  29.758s  |   0.000s  | 0.0%|
|bench_14486.smt2                                                                            |  13.050s  |  13.050s  |   0.000s  | 0.0%|
|bench_145.smt2                                                                              | 256.996s  | 256.996s  |   0.000s  | 0.0%|
|bench_1453.smt2                                                                             |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|bench_1455.smt2                                                                             |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|bench_14595.smt2                                                                            |  17.980s  |  17.980s  |   0.000s  | 0.0%|
|bench_14598.smt2                                                                            |   7.563s  |   7.563s  |   0.000s  | 0.0%|
|bench_1465.smt2                                                                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|bench_1467.smt2                                                                             |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|bench_1470.smt2                                                                             |   1.752s  |   1.752s  |   0.000s  | 0.0%|
|bench_14720.smt2                                                                            | 599.356s  | 599.356s  |   0.000s  | 0.0%|
|bench_1476.smt2                                                                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|bench_1477.smt2                                                                             |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|bench_1478.smt2                                                                             |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|bench_1481.smt2                                                                             |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|bench_14817.smt2                                                                            |   5.919s  |   5.919s  |   0.000s  | 0.0%|
|bench_14861.smt2                                                                            | 599.505s  | 599.505s  |   0.000s  | 0.0%|
|bench_14875.smt2                                                                            |  10.568s  |  10.568s  |   0.000s  | 0.0%|
|bench_14885.smt2                                                                            | 156.204s  | 156.204s  |   0.000s  | 0.0%|
|bench_14932.smt2                                                                            | 255.241s  | 255.241s  |   0.000s  | 0.0%|
|bench_14941.smt2                                                                            |  14.848s  |  14.848s  |   0.000s  | 0.0%|
|bench_1495.smt2                                                                             |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|bench_1496.smt2                                                                             | 214.401s  | 214.401s  |   0.000s  | 0.0%|
|bench_1498.smt2                                                                             | 404.635s  | 404.635s  |   0.000s  | 0.0%|
|bench_14984.smt2                                                                            |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|bench_15.smt2                                                                               |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|bench_1504.smt2                                                                             |  23.814s  |  23.814s  |   0.000s  | 0.0%|
|bench_15105.smt2                                                                            |  10.020s  |  10.020s  |   0.000s  | 0.0%|
|bench_15128.smt2                                                                            |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|bench_1522.smt2                                                                             | 180.469s  | 180.469s  |   0.000s  | 0.0%|
|bench_1523.smt2                                                                             |   6.856s  |   6.856s  |   0.000s  | 0.0%|
|bench_15255.smt2                                                                            | 159.956s  | 159.956s  |   0.000s  | 0.0%|
|bench_1532.smt2                                                                             |   0.666s  |   0.666s  |   0.000s  | 0.0%|
|bench_15365.smt2                                                                            |   7.460s  |   7.460s  |   0.000s  | 0.0%|
|bench_154.smt2                                                                              |  31.436s  |  31.436s  |   0.000s  | 0.0%|
|bench_1545.smt2                                                                             |   1.177s  |   1.177s  |   0.000s  | 0.0%|
|bench_1549.smt2                                                                             |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|bench_15547.smt2                                                                            |  97.859s  |  97.859s  |   0.000s  | 0.0%|
|bench_1555.smt2                                                                             |  25.246s  |  25.246s  |   0.000s  | 0.0%|
|bench_1559.smt2                                                                             |  52.055s  |  52.055s  |   0.000s  | 0.0%|
|bench_1560.smt2                                                                             | 257.313s  | 257.313s  |   0.000s  | 0.0%|
|bench_1567.smt2                                                                             | 187.855s  | 187.855s  |   0.000s  | 0.0%|
|bench_1568.smt2                                                                             |   4.097s  |   4.097s  |   0.000s  | 0.0%|
|bench_15711.smt2                                                                            |  16.718s  |  16.718s  |   0.000s  | 0.0%|
|bench_15719.smt2                                                                            |  26.755s  |  26.755s  |   0.000s  | 0.0%|
|bench_1573.smt2                                                                             |   4.988s  |   4.988s  |   0.000s  | 0.0%|
|bench_1578.smt2                                                                             | 127.390s  | 127.390s  |   0.000s  | 0.0%|
|bench_15783.smt2                                                                            |   1.431s  |   1.431s  |   0.000s  | 0.0%|
|bench_1583.smt2                                                                             |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|bench_15833.smt2                                                                            |   4.994s  |   4.994s  |   0.000s  | 0.0%|
|bench_1585.smt2                                                                             | 117.193s  | 117.193s  |   0.000s  | 0.0%|
|bench_1586.smt2                                                                             | 213.126s  | 213.126s  |   0.000s  | 0.0%|
|bench_1588.smt2                                                                             |   4.182s  |   4.182s  |   0.000s  | 0.0%|
|bench_160.smt2                                                                              |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|bench_1603.smt2                                                                             |   4.090s  |   4.090s  |   0.000s  | 0.0%|
|bench_16064.smt2                                                                            |   2.451s  |   2.451s  |   0.000s  | 0.0%|
|bench_1608.smt2                                                                             | 178.516s  | 178.516s  |   0.000s  | 0.0%|
|bench_1610.smt2                                                                             |   0.267s  |   0.267s  |   0.000s  | 0.0%|
|bench_1614.smt2                                                                             | 298.408s  | 298.408s  |   0.000s  | 0.0%|
|bench_1621.smt2                                                                             | 173.916s  | 173.916s  |   0.000s  | 0.0%|
|bench_16245.smt2                                                                            | 161.536s  | 161.536s  |   0.000s  | 0.0%|
|bench_1627.smt2                                                                             |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|bench_1629.smt2                                                                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|bench_163.smt2                                                                              |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|bench_1630.smt2                                                                             |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|bench_1636.smt2                                                                             |   4.234s  |   4.234s  |   0.000s  | 0.0%|
|bench_16382.smt2                                                                            |   0.278s  |   0.278s  |   0.000s  | 0.0%|
|bench_16409.smt2                                                                            | 119.834s  | 119.834s  |   0.000s  | 0.0%|
|bench_1643.smt2                                                                             | 136.347s  | 136.347s  |   0.000s  | 0.0%|
|bench_16467.smt2                                                                            |  10.566s  |  10.566s  |   0.000s  | 0.0%|
|bench_165.smt2                                                                              |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|bench_1652.smt2                                                                             |   0.703s  |   0.703s  |   0.000s  | 0.0%|
|bench_1657.smt2                                                                             |  41.433s  |  41.433s  |   0.000s  | 0.0%|
|bench_16594.smt2                                                                            |  10.844s  |  10.844s  |   0.000s  | 0.0%|
|bench_166.smt2                                                                              |   4.700s  |   4.700s  |   0.000s  | 0.0%|
|bench_1663.smt2                                                                             | 168.877s  | 168.877s  |   0.000s  | 0.0%|
|bench_16640.smt2                                                                            |   6.661s  |   6.661s  |   0.000s  | 0.0%|
|bench_1665.smt2                                                                             |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|bench_1670.smt2                                                                             |   0.279s  |   0.279s  |   0.000s  | 0.0%|
|bench_16707.smt2                                                                            | 598.777s  | 598.777s  |   0.000s  | 0.0%|
|bench_1674.smt2                                                                             |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|bench_168.smt2                                                                              |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|bench_1680.smt2                                                                             |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|bench_1686.smt2                                                                             |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|bench_16862.smt2                                                                            | 599.663s  | 599.663s  |   0.000s  | 0.0%|
|bench_1697.smt2                                                                             |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|bench_17033.smt2                                                                            | 599.783s  | 599.783s  |   0.000s  | 0.0%|
|bench_1707.smt2                                                                             |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|bench_17082.smt2                                                                            |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|bench_171.smt2                                                                              |   7.609s  |   7.609s  |   0.000s  | 0.0%|
|bench_1710.smt2                                                                             | 289.918s  | 289.918s  |   0.000s  | 0.0%|
|bench_1712.smt2                                                                             |  10.572s  |  10.572s  |   0.000s  | 0.0%|
|bench_1717.smt2                                                                             |  38.175s  |  38.175s  |   0.000s  | 0.0%|
|bench_1720.smt2                                                                             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|bench_1721.smt2                                                                             | 214.752s  | 214.752s  |   0.000s  | 0.0%|
|bench_1724.smt2                                                                             | 252.710s  | 252.710s  |   0.000s  | 0.0%|
|bench_17324.smt2                                                                            |  10.898s  |  10.898s  |   0.000s  | 0.0%|
|bench_17335.smt2                                                                            | 599.210s  | 599.210s  |   0.000s  | 0.0%|
|bench_1739.smt2                                                                             |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|bench_1748.smt2                                                                             |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|bench_1756.smt2                                                                             | 599.444s  | 599.444s  |   0.000s  | 0.0%|
|bench_1757.smt2                                                                             |   0.436s  |   0.436s  |   0.000s  | 0.0%|
|bench_1759.smt2                                                                             |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|bench_1760.smt2                                                                             |  29.626s  |  29.626s  |   0.000s  | 0.0%|
|bench_1761.smt2                                                                             |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|bench_1763.smt2                                                                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|bench_1769.smt2                                                                             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|bench_1770.smt2                                                                             |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|bench_17759.smt2                                                                            |  12.228s  |  12.228s  |   0.000s  | 0.0%|
|bench_1778.smt2                                                                             |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|bench_179.smt2                                                                              |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|bench_1802.smt2                                                                             |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|bench_1810.smt2                                                                             | 262.803s  | 262.803s  |   0.000s  | 0.0%|
|bench_1811.smt2                                                                             |   0.540s  |   0.540s  |   0.000s  | 0.0%|
|bench_1816.smt2                                                                             |   0.637s  |   0.637s  |   0.000s  | 0.0%|
|bench_1822.smt2                                                                             |   6.830s  |   6.830s  |   0.000s  | 0.0%|
|bench_1829.smt2                                                                             |  22.143s  |  22.143s  |   0.000s  | 0.0%|
|bench_183.smt2                                                                              |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|bench_1837.smt2                                                                             |  21.538s  |  21.538s  |   0.000s  | 0.0%|
|bench_1839.smt2                                                                             | 138.629s  | 138.629s  |   0.000s  | 0.0%|
|bench_1841.smt2                                                                             | 360.434s  | 360.434s  |   0.000s  | 0.0%|
|bench_1844.smt2                                                                             | 431.350s  | 431.350s  |   0.000s  | 0.0%|
|bench_1851.smt2                                                                             | 321.788s  | 321.788s  |   0.000s  | 0.0%|
|bench_1858.smt2                                                                             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|bench_1863.smt2                                                                             |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|bench_1864.smt2                                                                             |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|bench_1869.smt2                                                                             |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|bench_187.smt2                                                                              |   4.216s  |   4.216s  |   0.000s  | 0.0%|
|bench_1872.smt2                                                                             |  15.095s  |  15.095s  |   0.000s  | 0.0%|
|bench_1873.smt2                                                                             |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|bench_1878.smt2                                                                             |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|bench_1880.smt2                                                                             |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|bench_1882.smt2                                                                             |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|bench_1888.smt2                                                                             |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|bench_1897.smt2                                                                             | 182.139s  | 182.139s  |   0.000s  | 0.0%|
|bench_1900.smt2                                                                             |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|bench_1904.smt2                                                                             |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|bench_1905.smt2                                                                             |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|bench_1907.smt2                                                                             | 389.785s  | 389.785s  |   0.000s  | 0.0%|
|bench_1909.smt2                                                                             |  72.511s  |  72.511s  |   0.000s  | 0.0%|
|bench_1937.smt2                                                                             | 343.389s  | 343.389s  |   0.000s  | 0.0%|
|bench_1942.smt2                                                                             |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|bench_1946.smt2                                                                             |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|bench_1953.smt2                                                                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|bench_1957.smt2                                                                             |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|bench_1958.smt2                                                                             | 227.073s  | 227.073s  |   0.000s  | 0.0%|
|bench_1961.smt2                                                                             |   1.594s  |   1.594s  |   0.000s  | 0.0%|
|bench_1963.smt2                                                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|bench_1976.smt2                                                                             |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|bench_1977.smt2                                                                             |  21.353s  |  21.353s  |   0.000s  | 0.0%|
|bench_1981.smt2                                                                             | 199.586s  | 199.586s  |   0.000s  | 0.0%|
|bench_1985.smt2                                                                             | 118.028s  | 118.028s  |   0.000s  | 0.0%|
|bench_1992.smt2                                                                             | 470.645s  | 470.645s  |   0.000s  | 0.0%|
|bench_1993.smt2                                                                             |   0.394s  |   0.394s  |   0.000s  | 0.0%|
|bench_1996.smt2                                                                             |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|bench_200.smt2                                                                              |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|bench_2021.smt2                                                                             |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|bench_2022.smt2                                                                             |  36.943s  |  36.943s  |   0.000s  | 0.0%|
|bench_2034.smt2                                                                             | 350.357s  | 350.357s  |   0.000s  | 0.0%|
|bench_204.smt2                                                                              |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|bench_2044.smt2                                                                             |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|bench_2050.smt2                                                                             |  53.985s  |  53.985s  |   0.000s  | 0.0%|
|bench_2059.smt2                                                                             | 101.468s  | 101.468s  |   0.000s  | 0.0%|
|bench_2067.smt2                                                                             |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|bench_2070.smt2                                                                             |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|bench_2072.smt2                                                                             |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|bench_2075.smt2                                                                             |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|bench_2076.smt2                                                                             | 161.674s  | 161.674s  |   0.000s  | 0.0%|
|bench_2077.smt2                                                                             |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|bench_208.smt2                                                                              |   4.052s  |   4.052s  |   0.000s  | 0.0%|
|bench_2083.smt2                                                                             | 201.749s  | 201.749s  |   0.000s  | 0.0%|
|bench_2097.smt2                                                                             |   0.763s  |   0.763s  |   0.000s  | 0.0%|
|bench_2099.smt2                                                                             |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|bench_2102.smt2                                                                             |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|bench_2108.smt2                                                                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|bench_2113.smt2                                                                             |   2.492s  |   2.492s  |   0.000s  | 0.0%|
|bench_2115.smt2                                                                             | 204.439s  | 204.439s  |   0.000s  | 0.0%|
|bench_2117.smt2                                                                             |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|bench_2121.smt2                                                                             |  93.787s  |  93.787s  |   0.000s  | 0.0%|
|bench_2122.smt2                                                                             |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|bench_2129.smt2                                                                             |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|bench_214.smt2                                                                              |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|bench_2141.smt2                                                                             |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|bench_2144.smt2                                                                             | 110.732s  | 110.732s  |   0.000s  | 0.0%|
|bench_2148.smt2                                                                             |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|bench_2149.smt2                                                                             |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|bench_2150.smt2                                                                             |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|bench_2152.smt2                                                                             | 132.473s  | 132.473s  |   0.000s  | 0.0%|
|bench_2155.smt2                                                                             |  17.205s  |  17.205s  |   0.000s  | 0.0%|
|bench_2161.smt2                                                                             |  19.494s  |  19.494s  |   0.000s  | 0.0%|
|bench_2162.smt2                                                                             | 170.556s  | 170.556s  |   0.000s  | 0.0%|
|bench_2167.smt2                                                                             | 573.933s  | 573.933s  |   0.000s  | 0.0%|
|bench_2169.smt2                                                                             |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|bench_2170.smt2                                                                             | 599.145s  | 599.145s  |   0.000s  | 0.0%|
|bench_2174.smt2                                                                             | 255.908s  | 255.908s  |   0.000s  | 0.0%|
|bench_2175.smt2                                                                             |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|bench_2183.smt2                                                                             |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|bench_2188.smt2                                                                             |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|bench_2189.smt2                                                                             |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|bench_2192.smt2                                                                             |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|bench_2197.smt2                                                                             | 146.816s  | 146.816s  |   0.000s  | 0.0%|
|bench_2202.smt2                                                                             |   0.288s  |   0.288s  |   0.000s  | 0.0%|
|bench_2207.smt2                                                                             |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|bench_2211.smt2                                                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|bench_2221.smt2                                                                             |   0.298s  |   0.298s  |   0.000s  | 0.0%|
|bench_2225.smt2                                                                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|bench_2229.smt2                                                                             |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|bench_2233.smt2                                                                             |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|bench_224.smt2                                                                              |  11.732s  |  11.732s  |   0.000s  | 0.0%|
|bench_2248.smt2                                                                             | 576.057s  | 576.057s  |   0.000s  | 0.0%|
|bench_225.smt2                                                                              |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|bench_2257.smt2                                                                             |   0.398s  |   0.398s  |   0.000s  | 0.0%|
|bench_2258.smt2                                                                             | 599.610s  | 599.610s  |   0.000s  | 0.0%|
|bench_2261.smt2                                                                             |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|bench_2263.smt2                                                                             |   3.910s  |   3.910s  |   0.000s  | 0.0%|
|bench_2264.smt2                                                                             |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|bench_2265.smt2                                                                             |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|bench_2268.smt2                                                                             | 112.785s  | 112.785s  |   0.000s  | 0.0%|
|bench_2269.smt2                                                                             |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|bench_2272.smt2                                                                             |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|bench_2278.smt2                                                                             | 218.998s  | 218.998s  |   0.000s  | 0.0%|
|bench_228.smt2                                                                              |   4.139s  |   4.139s  |   0.000s  | 0.0%|
|bench_2284.smt2                                                                             | 363.171s  | 363.171s  |   0.000s  | 0.0%|
|bench_2291.smt2                                                                             |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|bench_2293.smt2                                                                             |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|bench_2295.smt2                                                                             |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|bench_230.smt2                                                                              |   5.502s  |   5.502s  |   0.000s  | 0.0%|
|bench_2304.smt2                                                                             |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|bench_2308.smt2                                                                             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|bench_2309.smt2                                                                             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|bench_2312.smt2                                                                             |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|bench_232.smt2                                                                              | 215.388s  | 215.388s  |   0.000s  | 0.0%|
|bench_2325.smt2                                                                             | 175.733s  | 175.733s  |   0.000s  | 0.0%|
|bench_2326.smt2                                                                             |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|bench_2327.smt2                                                                             |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|bench_2330.smt2                                                                             |  52.993s  |  52.993s  |   0.000s  | 0.0%|
|bench_234.smt2                                                                              |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|bench_2349.smt2                                                                             |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|bench_2351.smt2                                                                             |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|bench_2358.smt2                                                                             |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|bench_2360.smt2                                                                             | 599.399s  | 599.399s  |   0.000s  | 0.0%|
|bench_238.smt2                                                                              |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|bench_2380.smt2                                                                             |  19.042s  |  19.042s  |   0.000s  | 0.0%|
|bench_2384.smt2                                                                             |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|bench_2386.smt2                                                                             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|bench_2395.smt2                                                                             |  89.820s  |  89.820s  |   0.000s  | 0.0%|
|bench_2397.smt2                                                                             | 136.562s  | 136.562s  |   0.000s  | 0.0%|
|bench_2400.smt2                                                                             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|bench_2406.smt2                                                                             |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|bench_2407.smt2                                                                             |   0.769s  |   0.769s  |   0.000s  | 0.0%|
|bench_2420.smt2                                                                             |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|bench_2425.smt2                                                                             | 266.522s  | 266.522s  |   0.000s  | 0.0%|
|bench_2428.smt2                                                                             |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|bench_243.smt2                                                                              |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|bench_2431.smt2                                                                             |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|bench_2432.smt2                                                                             |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|bench_2433.smt2                                                                             |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|bench_2435.smt2                                                                             |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|bench_2436.smt2                                                                             |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|bench_2443.smt2                                                                             |  65.357s  |  65.357s  |   0.000s  | 0.0%|
|bench_2463.smt2                                                                             |   4.240s  |   4.240s  |   0.000s  | 0.0%|
|bench_2469.smt2                                                                             |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|bench_247.smt2                                                                              |   3.659s  |   3.659s  |   0.000s  | 0.0%|
|bench_2475.smt2                                                                             | 310.599s  | 310.599s  |   0.000s  | 0.0%|
|bench_248.smt2                                                                              |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|bench_2493.smt2                                                                             |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|bench_2499.smt2                                                                             |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|bench_2503.smt2                                                                             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|bench_2507.smt2                                                                             |   4.966s  |   4.966s  |   0.000s  | 0.0%|
|bench_2514.smt2                                                                             |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|bench_2517.smt2                                                                             |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|bench_2521.smt2                                                                             |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|bench_2524.smt2                                                                             |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|bench_253.smt2                                                                              |   5.751s  |   5.751s  |   0.000s  | 0.0%|
|bench_2547.smt2                                                                             |  63.771s  |  63.771s  |   0.000s  | 0.0%|
|bench_2548.smt2                                                                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|bench_2550.smt2                                                                             |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|bench_2551.smt2                                                                             |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|bench_2552.smt2                                                                             |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|bench_2558.smt2                                                                             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|bench_2566.smt2                                                                             |   0.335s  |   0.335s  |   0.000s  | 0.0%|
|bench_2567.smt2                                                                             |   0.257s  |   0.257s  |   0.000s  | 0.0%|
|bench_2573.smt2                                                                             |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|bench_2574.smt2                                                                             |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|bench_2579.smt2                                                                             |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|bench_2580.smt2                                                                             |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|bench_2582.smt2                                                                             |  14.446s  |  14.446s  |   0.000s  | 0.0%|
|bench_2586.smt2                                                                             |   9.706s  |   9.706s  |   0.000s  | 0.0%|
|bench_259.smt2                                                                              |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|bench_2594.smt2                                                                             | 225.176s  | 225.176s  |   0.000s  | 0.0%|
|bench_2599.smt2                                                                             | 269.083s  | 269.083s  |   0.000s  | 0.0%|
|bench_2602.smt2                                                                             |  11.476s  |  11.476s  |   0.000s  | 0.0%|
|bench_2606.smt2                                                                             |  96.990s  |  96.990s  |   0.000s  | 0.0%|
|bench_261.smt2                                                                              |   3.636s  |   3.636s  |   0.000s  | 0.0%|
|bench_2612.smt2                                                                             |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|bench_2613.smt2                                                                             |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|bench_2620.smt2                                                                             |   0.241s  |   0.241s  |   0.000s  | 0.0%|
|bench_2621.smt2                                                                             | 116.591s  | 116.591s  |   0.000s  | 0.0%|
|bench_2628.smt2                                                                             | 137.933s  | 137.933s  |   0.000s  | 0.0%|
|bench_2629.smt2                                                                             | 106.281s  | 106.281s  |   0.000s  | 0.0%|
|bench_2635.smt2                                                                             |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|bench_2639.smt2                                                                             |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|bench_2642.smt2                                                                             |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|bench_2644.smt2                                                                             | 106.653s  | 106.653s  |   0.000s  | 0.0%|
|bench_2645.smt2                                                                             |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|bench_2646.smt2                                                                             |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|bench_2650.smt2                                                                             |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|bench_2653.smt2                                                                             | 237.729s  | 237.729s  |   0.000s  | 0.0%|
|bench_2659.smt2                                                                             |   0.266s  |   0.266s  |   0.000s  | 0.0%|
|bench_267.smt2                                                                              |   4.168s  |   4.168s  |   0.000s  | 0.0%|
|bench_2671.smt2                                                                             |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|bench_2675.smt2                                                                             | 378.416s  | 378.416s  |   0.000s  | 0.0%|
|bench_2676.smt2                                                                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|bench_2682.smt2                                                                             | 172.429s  | 172.429s  |   0.000s  | 0.0%|
|bench_2688.smt2                                                                             |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|bench_270.smt2                                                                              |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|bench_2701.smt2                                                                             |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|bench_2704.smt2                                                                             |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|bench_2710.smt2                                                                             |   0.285s  |   0.285s  |   0.000s  | 0.0%|
|bench_2717.smt2                                                                             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|bench_2724.smt2                                                                             |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|bench_2727.smt2                                                                             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|bench_2729.smt2                                                                             |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|bench_2735.smt2                                                                             |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|bench_2737.smt2                                                                             |   0.246s  |   0.246s  |   0.000s  | 0.0%|
|bench_2747.smt2                                                                             |   0.265s  |   0.265s  |   0.000s  | 0.0%|
|bench_2750.smt2                                                                             |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|bench_2755.smt2                                                                             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|bench_2757.smt2                                                                             |   9.197s  |   9.197s  |   0.000s  | 0.0%|
|bench_276.smt2                                                                              |   1.004s  |   1.004s  |   0.000s  | 0.0%|
|bench_2767.smt2                                                                             |  68.370s  |  68.370s  |   0.000s  | 0.0%|
|bench_2773.smt2                                                                             |  16.139s  |  16.139s  |   0.000s  | 0.0%|
|bench_2779.smt2                                                                             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|bench_2789.smt2                                                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|bench_279.smt2                                                                              |   3.193s  |   3.193s  |   0.000s  | 0.0%|
|bench_2798.smt2                                                                             |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|bench_28.smt2                                                                               |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|bench_281.smt2                                                                              |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|bench_2811.smt2                                                                             |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|bench_2817.smt2                                                                             |  24.185s  |  24.185s  |   0.000s  | 0.0%|
|bench_2826.smt2                                                                             |  48.636s  |  48.636s  |   0.000s  | 0.0%|
|bench_2831.smt2                                                                             | 209.448s  | 209.448s  |   0.000s  | 0.0%|
|bench_2832.smt2                                                                             |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|bench_2839.smt2                                                                             |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|bench_2841.smt2                                                                             |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|bench_2842.smt2                                                                             | 319.986s  | 319.986s  |   0.000s  | 0.0%|
|bench_2844.smt2                                                                             | 184.738s  | 184.738s  |   0.000s  | 0.0%|
|bench_2846.smt2                                                                             |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|bench_2849.smt2                                                                             |  99.931s  |  99.931s  |   0.000s  | 0.0%|
|bench_285.smt2                                                                              |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|bench_2855.smt2                                                                             |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|bench_2858.smt2                                                                             | 599.549s  | 599.549s  |   0.000s  | 0.0%|
|bench_2864.smt2                                                                             |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|bench_2866.smt2                                                                             |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|bench_2867.smt2                                                                             | 321.727s  | 321.727s  |   0.000s  | 0.0%|
|bench_2868.smt2                                                                             | 173.623s  | 173.623s  |   0.000s  | 0.0%|
|bench_2875.smt2                                                                             | 387.189s  | 387.189s  |   0.000s  | 0.0%|
|bench_2876.smt2                                                                             |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|bench_288.smt2                                                                              |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|bench_2880.smt2                                                                             |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|bench_2897.smt2                                                                             |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|bench_29.smt2                                                                               |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|bench_290.smt2                                                                              |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|bench_2915.smt2                                                                             |  53.561s  |  53.561s  |   0.000s  | 0.0%|
|bench_2917.smt2                                                                             |   0.286s  |   0.286s  |   0.000s  | 0.0%|
|bench_2931.smt2                                                                             |   0.265s  |   0.265s  |   0.000s  | 0.0%|
|bench_295.smt2                                                                              |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|bench_2957.smt2                                                                             |   5.010s  |   5.010s  |   0.000s  | 0.0%|
|bench_296.smt2                                                                              |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|bench_2961.smt2                                                                             |   4.303s  |   4.303s  |   0.000s  | 0.0%|
|bench_2962.smt2                                                                             |   5.929s  |   5.929s  |   0.000s  | 0.0%|
|bench_2965.smt2                                                                             |   5.709s  |   5.709s  |   0.000s  | 0.0%|
|bench_2974.smt2                                                                             |   6.329s  |   6.329s  |   0.000s  | 0.0%|
|bench_2983.smt2                                                                             |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|bench_299.smt2                                                                              |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|bench_2992.smt2                                                                             | 201.039s  | 201.039s  |   0.000s  | 0.0%|
|bench_2994.smt2                                                                             |   4.096s  |   4.096s  |   0.000s  | 0.0%|
|bench_2995.smt2                                                                             |   8.123s  |   8.123s  |   0.000s  | 0.0%|
|bench_301.smt2                                                                              |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|bench_3010.smt2                                                                             | 433.567s  | 433.567s  |   0.000s  | 0.0%|
|bench_3011.smt2                                                                             |   3.779s  |   3.779s  |   0.000s  | 0.0%|
|bench_3015.smt2                                                                             |  98.670s  |  98.670s  |   0.000s  | 0.0%|
|bench_3018.smt2                                                                             |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|bench_3019.smt2                                                                             |  73.222s  |  73.222s  |   0.000s  | 0.0%|
|bench_302.smt2                                                                              |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|bench_303.smt2                                                                              |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|bench_3031.smt2                                                                             |   7.620s  |   7.620s  |   0.000s  | 0.0%|
|bench_3032.smt2                                                                             |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|bench_3041.smt2                                                                             | 239.475s  | 239.475s  |   0.000s  | 0.0%|
|bench_3048.smt2                                                                             |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|bench_3058.smt2                                                                             |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|bench_306.smt2                                                                              |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|bench_3062.smt2                                                                             |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|bench_3065.smt2                                                                             |  72.442s  |  72.442s  |   0.000s  | 0.0%|
|bench_3068.smt2                                                                             |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|bench_3080.smt2                                                                             |  36.418s  |  36.418s  |   0.000s  | 0.0%|
|bench_3082.smt2                                                                             | 599.316s  | 599.316s  |   0.000s  | 0.0%|
|bench_3087.smt2                                                                             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|bench_3091.smt2                                                                             |   6.456s  |   6.456s  |   0.000s  | 0.0%|
|bench_3093.smt2                                                                             |   2.965s  |   2.965s  |   0.000s  | 0.0%|
|bench_3094.smt2                                                                             |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|bench_3099.smt2                                                                             |   3.145s  |   3.145s  |   0.000s  | 0.0%|
|bench_3103.smt2                                                                             |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|bench_3105.smt2                                                                             | 593.487s  | 593.487s  |   0.000s  | 0.0%|
|bench_3111.smt2                                                                             | 137.545s  | 137.545s  |   0.000s  | 0.0%|
|bench_3113.smt2                                                                             | 205.814s  | 205.814s  |   0.000s  | 0.0%|
|bench_3114.smt2                                                                             |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|bench_3121.smt2                                                                             |   3.351s  |   3.351s  |   0.000s  | 0.0%|
|bench_313.smt2                                                                              |  23.206s  |  23.206s  |   0.000s  | 0.0%|
|bench_3145.smt2                                                                             | 172.950s  | 172.950s  |   0.000s  | 0.0%|
|bench_3156.smt2                                                                             |   3.516s  |   3.516s  |   0.000s  | 0.0%|
|bench_3159.smt2                                                                             | 229.421s  | 229.421s  |   0.000s  | 0.0%|
|bench_3168.smt2                                                                             | 281.982s  | 281.982s  |   0.000s  | 0.0%|
|bench_3169.smt2                                                                             |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|bench_317.smt2                                                                              |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|bench_3171.smt2                                                                             | 179.158s  | 179.158s  |   0.000s  | 0.0%|
|bench_3173.smt2                                                                             |  30.776s  |  30.776s  |   0.000s  | 0.0%|
|bench_3174.smt2                                                                             |   4.462s  |   4.462s  |   0.000s  | 0.0%|
|bench_3177.smt2                                                                             | 425.685s  | 425.685s  |   0.000s  | 0.0%|
|bench_3181.smt2                                                                             | 413.120s  | 413.120s  |   0.000s  | 0.0%|
|bench_3182.smt2                                                                             |  10.427s  |  10.427s  |   0.000s  | 0.0%|
|bench_3191.smt2                                                                             |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|bench_3194.smt2                                                                             | 110.262s  | 110.262s  |   0.000s  | 0.0%|
|bench_3196.smt2                                                                             |   4.779s  |   4.779s  |   0.000s  | 0.0%|
|bench_3206.smt2                                                                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|bench_3207.smt2                                                                             | 359.843s  | 359.843s  |   0.000s  | 0.0%|
|bench_3209.smt2                                                                             | 195.289s  | 195.289s  |   0.000s  | 0.0%|
|bench_3218.smt2                                                                             | 599.594s  | 599.594s  |   0.000s  | 0.0%|
|bench_3221.smt2                                                                             |  37.421s  |  37.421s  |   0.000s  | 0.0%|
|bench_3223.smt2                                                                             |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|bench_323.smt2                                                                              | 137.070s  | 137.070s  |   0.000s  | 0.0%|
|bench_3239.smt2                                                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|bench_3240.smt2                                                                             |  63.203s  |  63.203s  |   0.000s  | 0.0%|
|bench_3246.smt2                                                                             |  94.501s  |  94.501s  |   0.000s  | 0.0%|
|bench_325.smt2                                                                              |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|bench_3263.smt2                                                                             |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|bench_3266.smt2                                                                             | 407.411s  | 407.411s  |   0.000s  | 0.0%|
|bench_3268.smt2                                                                             |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|bench_3275.smt2                                                                             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|bench_3279.smt2                                                                             |   3.480s  |   3.480s  |   0.000s  | 0.0%|
|bench_3295.smt2                                                                             |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|bench_3297.smt2                                                                             |  85.172s  |  85.172s  |   0.000s  | 0.0%|
|bench_3307.smt2                                                                             |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|bench_3308.smt2                                                                             |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|bench_3311.smt2                                                                             |   0.345s  |   0.345s  |   0.000s  | 0.0%|
|bench_3317.smt2                                                                             |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|bench_3320.smt2                                                                             |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|bench_3326.smt2                                                                             | 260.897s  | 260.897s  |   0.000s  | 0.0%|
|bench_3329.smt2                                                                             |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|bench_3333.smt2                                                                             |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|bench_3335.smt2                                                                             |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|bench_3338.smt2                                                                             |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|bench_3339.smt2                                                                             |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|bench_334.smt2                                                                              |  10.557s  |  10.557s  |   0.000s  | 0.0%|
|bench_335.smt2                                                                              |   0.544s  |   0.544s  |   0.000s  | 0.0%|
|bench_3351.smt2                                                                             | 277.143s  | 277.143s  |   0.000s  | 0.0%|
|bench_3352.smt2                                                                             |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|bench_3358.smt2                                                                             |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|bench_3360.smt2                                                                             |   5.174s  |   5.174s  |   0.000s  | 0.0%|
|bench_3367.smt2                                                                             |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|bench_3379.smt2                                                                             |  18.442s  |  18.442s  |   0.000s  | 0.0%|
|bench_3394.smt2                                                                             |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|bench_3411.smt2                                                                             |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|bench_3415.smt2                                                                             |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|bench_3416.smt2                                                                             |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|bench_3420.smt2                                                                             |  45.255s  |  45.255s  |   0.000s  | 0.0%|
|bench_3421.smt2                                                                             |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|bench_3431.smt2                                                                             |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|bench_3434.smt2                                                                             |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|bench_3437.smt2                                                                             | 598.447s  | 598.447s  |   0.000s  | 0.0%|
|bench_3446.smt2                                                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|bench_3451.smt2                                                                             | 453.852s  | 453.852s  |   0.000s  | 0.0%|
|bench_3460.smt2                                                                             |   0.297s  |   0.297s  |   0.000s  | 0.0%|
|bench_3461.smt2                                                                             |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|bench_3465.smt2                                                                             |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|bench_3469.smt2                                                                             |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|bench_347.smt2                                                                              |   2.014s  |   2.014s  |   0.000s  | 0.0%|
|bench_3475.smt2                                                                             |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|bench_3476.smt2                                                                             |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|bench_348.smt2                                                                              |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|bench_3484.smt2                                                                             |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|bench_3485.smt2                                                                             |  87.148s  |  87.148s  |   0.000s  | 0.0%|
|bench_3489.smt2                                                                             |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|bench_3499.smt2                                                                             |  77.696s  |  77.696s  |   0.000s  | 0.0%|
|bench_3500.smt2                                                                             |  42.284s  |  42.284s  |   0.000s  | 0.0%|
|bench_3502.smt2                                                                             | 266.177s  | 266.177s  |   0.000s  | 0.0%|
|bench_3509.smt2                                                                             |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|bench_3516.smt2                                                                             | 445.954s  | 445.954s  |   0.000s  | 0.0%|
|bench_3521.smt2                                                                             |  99.051s  |  99.051s  |   0.000s  | 0.0%|
|bench_3522.smt2                                                                             |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|bench_3524.smt2                                                                             |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|bench_353.smt2                                                                              | 467.783s  | 467.783s  |   0.000s  | 0.0%|
|bench_3538.smt2                                                                             |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|bench_3539.smt2                                                                             |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|bench_3541.smt2                                                                             |   6.716s  |   6.716s  |   0.000s  | 0.0%|
|bench_3548.smt2                                                                             |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|bench_3551.smt2                                                                             |   0.362s  |   0.362s  |   0.000s  | 0.0%|
|bench_3557.smt2                                                                             | 288.302s  | 288.302s  |   0.000s  | 0.0%|
|bench_3558.smt2                                                                             |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|bench_3561.smt2                                                                             | 281.981s  | 281.981s  |   0.000s  | 0.0%|
|bench_3575.smt2                                                                             | 599.382s  | 599.382s  |   0.000s  | 0.0%|
|bench_3578.smt2                                                                             |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|bench_3587.smt2                                                                             |   4.718s  |   4.718s  |   0.000s  | 0.0%|
|bench_3588.smt2                                                                             | 479.836s  | 479.836s  |   0.000s  | 0.0%|
|bench_3598.smt2                                                                             |   4.776s  |   4.776s  |   0.000s  | 0.0%|
|bench_36.smt2                                                                               |   0.305s  |   0.305s  |   0.000s  | 0.0%|
|bench_360.smt2                                                                              |   0.357s  |   0.357s  |   0.000s  | 0.0%|
|bench_3603.smt2                                                                             | 411.804s  | 411.804s  |   0.000s  | 0.0%|
|bench_3623.smt2                                                                             |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|bench_3636.smt2                                                                             |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|bench_3637.smt2                                                                             |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|bench_3642.smt2                                                                             |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|bench_365.smt2                                                                              |   3.598s  |   3.598s  |   0.000s  | 0.0%|
|bench_366.smt2                                                                              |   4.105s  |   4.105s  |   0.000s  | 0.0%|
|bench_3671.smt2                                                                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|bench_3672.smt2                                                                             |   7.329s  |   7.329s  |   0.000s  | 0.0%|
|bench_3675.smt2                                                                             |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|bench_368.smt2                                                                              |   4.785s  |   4.785s  |   0.000s  | 0.0%|
|bench_3681.smt2                                                                             |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|bench_3688.smt2                                                                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|bench_3689.smt2                                                                             |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|bench_369.smt2                                                                              |   3.468s  |   3.468s  |   0.000s  | 0.0%|
|bench_3697.smt2                                                                             |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|bench_3699.smt2                                                                             |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|bench_3707.smt2                                                                             |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|bench_3715.smt2                                                                             |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|bench_3716.smt2                                                                             |  12.503s  |  12.503s  |   0.000s  | 0.0%|
|bench_3719.smt2                                                                             |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|bench_372.smt2                                                                              |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|bench_3721.smt2                                                                             |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|bench_3739.smt2                                                                             |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|bench_375.smt2                                                                              |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|bench_3750.smt2                                                                             |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|bench_3754.smt2                                                                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|bench_3755.smt2                                                                             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|bench_3757.smt2                                                                             |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|bench_3765.smt2                                                                             |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|bench_3787.smt2                                                                             |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|bench_3788.smt2                                                                             |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|bench_3789.smt2                                                                             |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|bench_379.smt2                                                                              |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|bench_3794.smt2                                                                             |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|bench_3795.smt2                                                                             |   6.462s  |   6.462s  |   0.000s  | 0.0%|
|bench_3799.smt2                                                                             |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|bench_3813.smt2                                                                             |   0.266s  |   0.266s  |   0.000s  | 0.0%|
|bench_3815.smt2                                                                             |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|bench_3818.smt2                                                                             |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|bench_3819.smt2                                                                             |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|bench_3832.smt2                                                                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|bench_3834.smt2                                                                             |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|bench_3838.smt2                                                                             |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|bench_3846.smt2                                                                             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|bench_3847.smt2                                                                             |   8.423s  |   8.423s  |   0.000s  | 0.0%|
|bench_385.smt2                                                                              |   4.776s  |   4.776s  |   0.000s  | 0.0%|
|bench_3866.smt2                                                                             |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|bench_387.smt2                                                                              |   3.358s  |   3.358s  |   0.000s  | 0.0%|
|bench_3879.smt2                                                                             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|bench_388.smt2                                                                              |  19.528s  |  19.528s  |   0.000s  | 0.0%|
|bench_3881.smt2                                                                             |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|bench_3882.smt2                                                                             |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|bench_3885.smt2                                                                             |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|bench_3886.smt2                                                                             |   0.413s  |   0.413s  |   0.000s  | 0.0%|
|bench_3888.smt2                                                                             |   3.020s  |   3.020s  |   0.000s  | 0.0%|
|bench_3890.smt2                                                                             |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|bench_3894.smt2                                                                             |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|bench_390.smt2                                                                              |   5.043s  |   5.043s  |   0.000s  | 0.0%|
|bench_3906.smt2                                                                             | 599.180s  | 599.180s  |   0.000s  | 0.0%|
|bench_3915.smt2                                                                             |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|bench_3926.smt2                                                                             |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|bench_3936.smt2                                                                             |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|bench_3937.smt2                                                                             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|bench_3943.smt2                                                                             | 599.323s  | 599.323s  |   0.000s  | 0.0%|
|bench_3945.smt2                                                                             | 599.792s  | 599.792s  |   0.000s  | 0.0%|
|bench_3951.smt2                                                                             |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|bench_3953.smt2                                                                             |  16.542s  |  16.542s  |   0.000s  | 0.0%|
|bench_3963.smt2                                                                             |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|bench_3964.smt2                                                                             |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|bench_3968.smt2                                                                             | 159.836s  | 159.836s  |   0.000s  | 0.0%|
|bench_3992.smt2                                                                             |   0.827s  |   0.827s  |   0.000s  | 0.0%|
|bench_3995.smt2                                                                             |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|bench_3997.smt2                                                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|bench_4007.smt2                                                                             |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|bench_4010.smt2                                                                             |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|bench_4015.smt2                                                                             | 182.693s  | 182.693s  |   0.000s  | 0.0%|
|bench_4019.smt2                                                                             |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|bench_402.smt2                                                                              |   4.058s  |   4.058s  |   0.000s  | 0.0%|
|bench_4021.smt2                                                                             |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|bench_4023.smt2                                                                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|bench_4031.smt2                                                                             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|bench_4037.smt2                                                                             | 252.255s  | 252.255s  |   0.000s  | 0.0%|
|bench_404.smt2                                                                              |   3.302s  |   3.302s  |   0.000s  | 0.0%|
|bench_4040.smt2                                                                             |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|bench_4046.smt2                                                                             |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|bench_4051.smt2                                                                             |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|bench_4058.smt2                                                                             |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|bench_4065.smt2                                                                             |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|bench_4069.smt2                                                                             |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|bench_4097.smt2                                                                             |   1.698s  |   1.698s  |   0.000s  | 0.0%|
|bench_4099.smt2                                                                             |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|bench_4100.smt2                                                                             |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|bench_4112.smt2                                                                             |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|bench_4115.smt2                                                                             |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|bench_4137.smt2                                                                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|bench_414.smt2                                                                              |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|bench_4141.smt2                                                                             |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|bench_4143.smt2                                                                             |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|bench_4154.smt2                                                                             |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|bench_4156.smt2                                                                             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|bench_4157.smt2                                                                             |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|bench_4160.smt2                                                                             |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|bench_4164.smt2                                                                             |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|bench_4170.smt2                                                                             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|bench_4173.smt2                                                                             |   3.688s  |   3.688s  |   0.000s  | 0.0%|
|bench_4175.smt2                                                                             |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|bench_4192.smt2                                                                             |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|bench_4208.smt2                                                                             |   0.398s  |   0.398s  |   0.000s  | 0.0%|
|bench_4219.smt2                                                                             |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|bench_4220.smt2                                                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|bench_4231.smt2                                                                             |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|bench_4233.smt2                                                                             |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|bench_424.smt2                                                                              |   5.759s  |   5.759s  |   0.000s  | 0.0%|
|bench_4253.smt2                                                                             | 599.165s  | 599.165s  |   0.000s  | 0.0%|
|bench_4256.smt2                                                                             |   6.239s  |   6.239s  |   0.000s  | 0.0%|
|bench_4261.smt2                                                                             | 599.009s  | 599.009s  |   0.000s  | 0.0%|
|bench_4273.smt2                                                                             |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|bench_4275.smt2                                                                             |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|bench_4279.smt2                                                                             |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|bench_4289.smt2                                                                             | 259.027s  | 259.027s  |   0.000s  | 0.0%|
|bench_4304.smt2                                                                             |   0.328s  |   0.328s  |   0.000s  | 0.0%|
|bench_4312.smt2                                                                             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|bench_4313.smt2                                                                             |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|bench_4319.smt2                                                                             |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|bench_4321.smt2                                                                             |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|bench_4340.smt2                                                                             |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|bench_4346.smt2                                                                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|bench_4350.smt2                                                                             |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|bench_4352.smt2                                                                             |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|bench_4356.smt2                                                                             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|bench_4359.smt2                                                                             |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|bench_436.smt2                                                                              |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|bench_4368.smt2                                                                             |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|bench_437.smt2                                                                              |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|bench_4375.smt2                                                                             |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|bench_4385.smt2                                                                             |  17.182s  |  17.182s  |   0.000s  | 0.0%|
|bench_4387.smt2                                                                             |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|bench_4390.smt2                                                                             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|bench_4397.smt2                                                                             |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|bench_4399.smt2                                                                             |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|bench_440.smt2                                                                              |   0.772s  |   0.772s  |   0.000s  | 0.0%|
|bench_4405.smt2                                                                             | 599.329s  | 599.329s  |   0.000s  | 0.0%|
|bench_4412.smt2                                                                             |   0.423s  |   0.423s  |   0.000s  | 0.0%|
|bench_4435.smt2                                                                             |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|bench_4444.smt2                                                                             |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|bench_4447.smt2                                                                             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|bench_445.smt2                                                                              |   5.418s  |   5.418s  |   0.000s  | 0.0%|
|bench_4461.smt2                                                                             |   4.614s  |   4.614s  |   0.000s  | 0.0%|
|bench_4467.smt2                                                                             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|bench_4472.smt2                                                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|bench_4477.smt2                                                                             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|bench_4481.smt2                                                                             |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|bench_449.smt2                                                                              |   3.913s  |   3.913s  |   0.000s  | 0.0%|
|bench_4494.smt2                                                                             |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|bench_4505.smt2                                                                             |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|bench_4508.smt2                                                                             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|bench_451.smt2                                                                              |   3.672s  |   3.672s  |   0.000s  | 0.0%|
|bench_4516.smt2                                                                             |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|bench_4518.smt2                                                                             |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|bench_452.smt2                                                                              |   3.376s  |   3.376s  |   0.000s  | 0.0%|
|bench_4520.smt2                                                                             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|bench_4522.smt2                                                                             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|bench_4526.smt2                                                                             |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|bench_4553.smt2                                                                             |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|bench_4555.smt2                                                                             |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|bench_456.smt2                                                                              |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|bench_4560.smt2                                                                             |   0.282s  |   0.282s  |   0.000s  | 0.0%|
|bench_4565.smt2                                                                             |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|bench_4568.smt2                                                                             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|bench_457.smt2                                                                              |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|bench_4570.smt2                                                                             |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|bench_4576.smt2                                                                             |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|bench_4580.smt2                                                                             |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|bench_4581.smt2                                                                             |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|bench_4583.smt2                                                                             |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|bench_4588.smt2                                                                             |   3.815s  |   3.815s  |   0.000s  | 0.0%|
|bench_4594.smt2                                                                             |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|bench_46.smt2                                                                               |   6.748s  |   6.748s  |   0.000s  | 0.0%|
|bench_4605.smt2                                                                             |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|bench_4607.smt2                                                                             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|bench_4614.smt2                                                                             |  15.267s  |  15.267s  |   0.000s  | 0.0%|
|bench_4617.smt2                                                                             |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|bench_4626.smt2                                                                             |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|bench_4627.smt2                                                                             |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|bench_4628.smt2                                                                             |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|bench_4635.smt2                                                                             |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|bench_4642.smt2                                                                             |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|bench_4644.smt2                                                                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|bench_4650.smt2                                                                             |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|bench_4654.smt2                                                                             |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|bench_4662.smt2                                                                             |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|bench_4669.smt2                                                                             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|bench_4689.smt2                                                                             |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|bench_4692.smt2                                                                             |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|bench_4696.smt2                                                                             |   0.309s  |   0.309s  |   0.000s  | 0.0%|
|bench_4706.smt2                                                                             |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|bench_4710.smt2                                                                             |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|bench_472.smt2                                                                              |   6.757s  |   6.757s  |   0.000s  | 0.0%|
|bench_4724.smt2                                                                             |   3.455s  |   3.455s  |   0.000s  | 0.0%|
|bench_4725.smt2                                                                             |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|bench_4728.smt2                                                                             |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|bench_4738.smt2                                                                             |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|bench_4740.smt2                                                                             |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|bench_4753.smt2                                                                             |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|bench_4755.smt2                                                                             |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|bench_4759.smt2                                                                             |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|bench_4768.smt2                                                                             |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|bench_4775.smt2                                                                             |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|bench_4788.smt2                                                                             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|bench_479.smt2                                                                              |   2.873s  |   2.873s  |   0.000s  | 0.0%|
|bench_480.smt2                                                                              |   3.323s  |   3.323s  |   0.000s  | 0.0%|
|bench_4813.smt2                                                                             |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|bench_4818.smt2                                                                             |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|bench_4820.smt2                                                                             |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|bench_4822.smt2                                                                             | 404.472s  | 404.472s  |   0.000s  | 0.0%|
|bench_4834.smt2                                                                             |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|bench_4838.smt2                                                                             |   0.379s  |   0.379s  |   0.000s  | 0.0%|
|bench_4839.smt2                                                                             |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|bench_4840.smt2                                                                             |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|bench_4873.smt2                                                                             |   4.410s  |   4.410s  |   0.000s  | 0.0%|
|bench_4879.smt2                                                                             |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|bench_4888.smt2                                                                             | 599.476s  | 599.476s  |   0.000s  | 0.0%|
|bench_489.smt2                                                                              |  50.826s  |  50.826s  |   0.000s  | 0.0%|
|bench_4890.smt2                                                                             |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|bench_4893.smt2                                                                             | 316.252s  | 316.252s  |   0.000s  | 0.0%|
|bench_4894.smt2                                                                             |  39.995s  |  39.995s  |   0.000s  | 0.0%|
|bench_4900.smt2                                                                             |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|bench_4906.smt2                                                                             |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|bench_4908.smt2                                                                             |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|bench_4919.smt2                                                                             |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|bench_4920.smt2                                                                             |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|bench_4921.smt2                                                                             |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|bench_4933.smt2                                                                             | 599.671s  | 599.671s  |   0.000s  | 0.0%|
|bench_4937.smt2                                                                             | 468.385s  | 468.385s  |   0.000s  | 0.0%|
|bench_494.smt2                                                                              |   6.197s  |   6.197s  |   0.000s  | 0.0%|
|bench_4954.smt2                                                                             |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|bench_4957.smt2                                                                             | 216.453s  | 216.453s  |   0.000s  | 0.0%|
|bench_4963.smt2                                                                             | 256.121s  | 256.121s  |   0.000s  | 0.0%|
|bench_4964.smt2                                                                             |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|bench_4965.smt2                                                                             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|bench_4968.smt2                                                                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|bench_497.smt2                                                                              |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|bench_4971.smt2                                                                             |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|bench_498.smt2                                                                              |  10.590s  |  10.590s  |   0.000s  | 0.0%|
|bench_4985.smt2                                                                             |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|bench_4990.smt2                                                                             |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|bench_5.smt2                                                                                |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|bench_50.smt2                                                                               |   3.817s  |   3.817s  |   0.000s  | 0.0%|
|bench_500.smt2                                                                              |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|bench_5005.smt2                                                                             |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|bench_5019.smt2                                                                             |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|bench_502.smt2                                                                              |   5.138s  |   5.138s  |   0.000s  | 0.0%|
|bench_5030.smt2                                                                             |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|bench_5034.smt2                                                                             |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|bench_5036.smt2                                                                             |  53.253s  |  53.253s  |   0.000s  | 0.0%|
|bench_5037.smt2                                                                             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|bench_5041.smt2                                                                             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|bench_5077.smt2                                                                             |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|bench_5081.smt2                                                                             |  62.654s  |  62.654s  |   0.000s  | 0.0%|
|bench_5084.smt2                                                                             |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|bench_5086.smt2                                                                             |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|bench_5096.smt2                                                                             | 257.669s  | 257.669s  |   0.000s  | 0.0%|
|bench_51.smt2                                                                               |   2.997s  |   2.997s  |   0.000s  | 0.0%|
|bench_5123.smt2                                                                             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|bench_5127.smt2                                                                             |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|bench_5131.smt2                                                                             |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|bench_5136.smt2                                                                             | 203.338s  | 203.338s  |   0.000s  | 0.0%|
|bench_5137.smt2                                                                             |  70.259s  |  70.259s  |   0.000s  | 0.0%|
|bench_5139.smt2                                                                             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|bench_5150.smt2                                                                             |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|bench_5153.smt2                                                                             |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|bench_5154.smt2                                                                             |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|bench_5155.smt2                                                                             |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|bench_5157.smt2                                                                             | 215.598s  | 215.598s  |   0.000s  | 0.0%|
|bench_5159.smt2                                                                             |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|bench_5165.smt2                                                                             |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|bench_5170.smt2                                                                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|bench_5183.smt2                                                                             |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|bench_5187.smt2                                                                             |   0.268s  |   0.268s  |   0.000s  | 0.0%|
|bench_5188.smt2                                                                             |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|bench_5190.smt2                                                                             |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|bench_5191.smt2                                                                             | 120.452s  | 120.452s  |   0.000s  | 0.0%|
|bench_5192.smt2                                                                             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|bench_52.smt2                                                                               |   4.543s  |   4.543s  |   0.000s  | 0.0%|
|bench_5209.smt2                                                                             |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|bench_5210.smt2                                                                             |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|bench_5218.smt2                                                                             |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|bench_5222.smt2                                                                             |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|bench_5223.smt2                                                                             |  24.851s  |  24.851s  |   0.000s  | 0.0%|
|bench_5234.smt2                                                                             |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|bench_5236.smt2                                                                             |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|bench_5238.smt2                                                                             |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|bench_525.smt2                                                                              |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|bench_5257.smt2                                                                             |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|bench_5261.smt2                                                                             |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|bench_527.smt2                                                                              |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|bench_5270.smt2                                                                             |   5.981s  |   5.981s  |   0.000s  | 0.0%|
|bench_528.smt2                                                                              |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|bench_5284.smt2                                                                             |  19.698s  |  19.698s  |   0.000s  | 0.0%|
|bench_5292.smt2                                                                             | 209.077s  | 209.077s  |   0.000s  | 0.0%|
|bench_5296.smt2                                                                             | 116.482s  | 116.482s  |   0.000s  | 0.0%|
|bench_5301.smt2                                                                             |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|bench_5302.smt2                                                                             |  97.431s  |  97.431s  |   0.000s  | 0.0%|
|bench_5303.smt2                                                                             |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|bench_5309.smt2                                                                             |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|bench_531.smt2                                                                              |   0.260s  |   0.260s  |   0.000s  | 0.0%|
|bench_5326.smt2                                                                             |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|bench_5329.smt2                                                                             | 421.585s  | 421.585s  |   0.000s  | 0.0%|
|bench_5332.smt2                                                                             |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|bench_5340.smt2                                                                             |  88.113s  |  88.113s  |   0.000s  | 0.0%|
|bench_5349.smt2                                                                             |  18.319s  |  18.319s  |   0.000s  | 0.0%|
|bench_535.smt2                                                                              |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|bench_5358.smt2                                                                             | 399.191s  | 399.191s  |   0.000s  | 0.0%|
|bench_536.smt2                                                                              | 106.681s  | 106.681s  |   0.000s  | 0.0%|
|bench_5360.smt2                                                                             |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|bench_5365.smt2                                                                             |   3.991s  |   3.991s  |   0.000s  | 0.0%|
|bench_5371.smt2                                                                             |   5.744s  |   5.744s  |   0.000s  | 0.0%|
|bench_5373.smt2                                                                             |   6.613s  |   6.613s  |   0.000s  | 0.0%|
|bench_5377.smt2                                                                             |   4.651s  |   4.651s  |   0.000s  | 0.0%|
|bench_5392.smt2                                                                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|bench_5395.smt2                                                                             |  51.607s  |  51.607s  |   0.000s  | 0.0%|
|bench_5401.smt2                                                                             |   6.293s  |   6.293s  |   0.000s  | 0.0%|
|bench_5408.smt2                                                                             |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|bench_5417.smt2                                                                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|bench_542.smt2                                                                              |   6.121s  |   6.121s  |   0.000s  | 0.0%|
|bench_5421.smt2                                                                             | 121.628s  | 121.628s  |   0.000s  | 0.0%|
|bench_5424.smt2                                                                             | 203.929s  | 203.929s  |   0.000s  | 0.0%|
|bench_5432.smt2                                                                             |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|bench_5435.smt2                                                                             |  69.375s  |  69.375s  |   0.000s  | 0.0%|
|bench_5440.smt2                                                                             |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|bench_5445.smt2                                                                             |   3.763s  |   3.763s  |   0.000s  | 0.0%|
|bench_5449.smt2                                                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|bench_5457.smt2                                                                             |   4.159s  |   4.159s  |   0.000s  | 0.0%|
|bench_5459.smt2                                                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|bench_5466.smt2                                                                             | 363.609s  | 363.609s  |   0.000s  | 0.0%|
|bench_5492.smt2                                                                             |   0.891s  |   0.891s  |   0.000s  | 0.0%|
|bench_5499.smt2                                                                             |   0.673s  |   0.673s  |   0.000s  | 0.0%|
|bench_5503.smt2                                                                             |   0.859s  |   0.859s  |   0.000s  | 0.0%|
|bench_5509.smt2                                                                             |   0.825s  |   0.825s  |   0.000s  | 0.0%|
|bench_5517.smt2                                                                             |   7.801s  |   7.801s  |   0.000s  | 0.0%|
|bench_5525.smt2                                                                             |   0.826s  |   0.826s  |   0.000s  | 0.0%|
|bench_5526.smt2                                                                             |  82.712s  |  82.712s  |   0.000s  | 0.0%|
|bench_5532.smt2                                                                             |   7.708s  |   7.708s  |   0.000s  | 0.0%|
|bench_5536.smt2                                                                             |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|bench_5543.smt2                                                                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|bench_5545.smt2                                                                             |   4.382s  |   4.382s  |   0.000s  | 0.0%|
|bench_556.smt2                                                                              |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|bench_5575.smt2                                                                             | 169.755s  | 169.755s  |   0.000s  | 0.0%|
|bench_5581.smt2                                                                             | 599.800s  | 599.800s  |   0.000s  | 0.0%|
|bench_559.smt2                                                                              |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|bench_5590.smt2                                                                             |   5.867s  |   5.867s  |   0.000s  | 0.0%|
|bench_5593.smt2                                                                             |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|bench_561.smt2                                                                              |   1.950s  |   1.950s  |   0.000s  | 0.0%|
|bench_5613.smt2                                                                             |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|bench_5623.smt2                                                                             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|bench_5636.smt2                                                                             |   0.351s  |   0.351s  |   0.000s  | 0.0%|
|bench_5645.smt2                                                                             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|bench_5649.smt2                                                                             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|bench_565.smt2                                                                              |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|bench_5658.smt2                                                                             |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|bench_5662.smt2                                                                             |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|bench_5666.smt2                                                                             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|bench_5674.smt2                                                                             |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|bench_571.smt2                                                                              |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|bench_5718.smt2                                                                             |   4.198s  |   4.198s  |   0.000s  | 0.0%|
|bench_5722.smt2                                                                             |   4.376s  |   4.376s  |   0.000s  | 0.0%|
|bench_5723.smt2                                                                             |   4.039s  |   4.039s  |   0.000s  | 0.0%|
|bench_5733.smt2                                                                             |   7.652s  |   7.652s  |   0.000s  | 0.0%|
|bench_5744.smt2                                                                             |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|bench_5752.smt2                                                                             |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|bench_5765.smt2                                                                             |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|bench_5779.smt2                                                                             |   4.042s  |   4.042s  |   0.000s  | 0.0%|
|bench_581.smt2                                                                              |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|bench_5898.smt2                                                                             |  10.098s  |  10.098s  |   0.000s  | 0.0%|
|bench_5944.smt2                                                                             | 599.353s  | 599.353s  |   0.000s  | 0.0%|
|bench_5974.smt2                                                                             |  23.452s  |  23.452s  |   0.000s  | 0.0%|
|bench_6012.smt2                                                                             | 498.495s  | 498.495s  |   0.000s  | 0.0%|
|bench_6016.smt2                                                                             |  12.357s  |  12.357s  |   0.000s  | 0.0%|
|bench_607.smt2                                                                              |   1.251s  |   1.251s  |   0.000s  | 0.0%|
|bench_609.smt2                                                                              |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|bench_6097.smt2                                                                             | 599.698s  | 599.698s  |   0.000s  | 0.0%|
|bench_613.smt2                                                                              |   5.157s  |   5.157s  |   0.000s  | 0.0%|
|bench_619.smt2                                                                              |   3.497s  |   3.497s  |   0.000s  | 0.0%|
|bench_620.smt2                                                                              |  29.364s  |  29.364s  |   0.000s  | 0.0%|
|bench_6215.smt2                                                                             |   4.960s  |   4.960s  |   0.000s  | 0.0%|
|bench_629.smt2                                                                              |   4.846s  |   4.846s  |   0.000s  | 0.0%|
|bench_630.smt2                                                                              |   3.248s  |   3.248s  |   0.000s  | 0.0%|
|bench_631.smt2                                                                              |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|bench_637.smt2                                                                              |   3.635s  |   3.635s  |   0.000s  | 0.0%|
|bench_639.smt2                                                                              |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|bench_640.smt2                                                                              |   1.840s  |   1.840s  |   0.000s  | 0.0%|
|bench_6408.smt2                                                                             | 123.593s  | 123.593s  |   0.000s  | 0.0%|
|bench_6458.smt2                                                                             |  88.240s  |  88.240s  |   0.000s  | 0.0%|
|bench_6462.smt2                                                                             | 118.451s  | 118.451s  |   0.000s  | 0.0%|
|bench_650.smt2                                                                              |   3.871s  |   3.871s  |   0.000s  | 0.0%|
|bench_6560.smt2                                                                             |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|bench_657.smt2                                                                              |   4.714s  |   4.714s  |   0.000s  | 0.0%|
|bench_658.smt2                                                                              |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|bench_659.smt2                                                                              |   4.948s  |   4.948s  |   0.000s  | 0.0%|
|bench_66.smt2                                                                               |   5.335s  |   5.335s  |   0.000s  | 0.0%|
|bench_6606.smt2                                                                             | 599.648s  | 599.648s  |   0.000s  | 0.0%|
|bench_6614.smt2                                                                             |  72.230s  |  72.230s  |   0.000s  | 0.0%|
|bench_663.smt2                                                                              |   4.667s  |   4.667s  |   0.000s  | 0.0%|
|bench_6665.smt2                                                                             |  69.838s  |  69.838s  |   0.000s  | 0.0%|
|bench_668.smt2                                                                              |   4.294s  |   4.294s  |   0.000s  | 0.0%|
|bench_6691.smt2                                                                             | 580.169s  | 580.169s  |   0.000s  | 0.0%|
|bench_6696.smt2                                                                             |  10.135s  |  10.135s  |   0.000s  | 0.0%|
|bench_6699.smt2                                                                             |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|bench_6713.smt2                                                                             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|bench_6731.smt2                                                                             |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|bench_6734.smt2                                                                             |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|bench_674.smt2                                                                              |   9.137s  |   9.137s  |   0.000s  | 0.0%|
|bench_6742.smt2                                                                             |  60.926s  |  60.926s  |   0.000s  | 0.0%|
|bench_6756.smt2                                                                             |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|bench_6765.smt2                                                                             |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|bench_6791.smt2                                                                             | 589.795s  | 589.795s  |   0.000s  | 0.0%|
|bench_6813.smt2                                                                             |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|bench_6826.smt2                                                                             |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|bench_6828.smt2                                                                             |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|bench_6830.smt2                                                                             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|bench_6837.smt2                                                                             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|bench_6843.smt2                                                                             |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|bench_6848.smt2                                                                             |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|bench_685.smt2                                                                              |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|bench_6854.smt2                                                                             |   0.630s  |   0.630s  |   0.000s  | 0.0%|
|bench_6857.smt2                                                                             |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|bench_6861.smt2                                                                             |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|bench_6866.smt2                                                                             |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|bench_6867.smt2                                                                             |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|bench_6882.smt2                                                                             | 144.311s  | 144.311s  |   0.000s  | 0.0%|
|bench_6886.smt2                                                                             |   0.413s  |   0.413s  |   0.000s  | 0.0%|
|bench_6898.smt2                                                                             |   0.267s  |   0.267s  |   0.000s  | 0.0%|
|bench_690.smt2                                                                              |   0.534s  |   0.534s  |   0.000s  | 0.0%|
|bench_6901.smt2                                                                             |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|bench_6902.smt2                                                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|bench_6906.smt2                                                                             |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|bench_6908.smt2                                                                             |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|bench_6911.smt2                                                                             |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|bench_6917.smt2                                                                             |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|bench_6923.smt2                                                                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|bench_6924.smt2                                                                             |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|bench_6929.smt2                                                                             |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|bench_6938.smt2                                                                             |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|bench_6943.smt2                                                                             |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|bench_6953.smt2                                                                             |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|bench_6954.smt2                                                                             |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|bench_6966.smt2                                                                             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|bench_6973.smt2                                                                             |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|bench_6986.smt2                                                                             |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|bench_6987.smt2                                                                             |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|bench_6998.smt2                                                                             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|bench_700.smt2                                                                              |   2.875s  |   2.875s  |   0.000s  | 0.0%|
|bench_7005.smt2                                                                             | 452.379s  | 452.379s  |   0.000s  | 0.0%|
|bench_702.smt2                                                                              |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|bench_7021.smt2                                                                             |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|bench_7024.smt2                                                                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|bench_7030.smt2                                                                             | 599.358s  | 599.358s  |   0.000s  | 0.0%|
|bench_7033.smt2                                                                             |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|bench_704.smt2                                                                              |   4.701s  |   4.701s  |   0.000s  | 0.0%|
|bench_705.smt2                                                                              |   2.572s  |   2.572s  |   0.000s  | 0.0%|
|bench_7056.smt2                                                                             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|bench_706.smt2                                                                              |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|bench_7070.smt2                                                                             |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|bench_7076.smt2                                                                             |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|bench_7081.smt2                                                                             |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|bench_7082.smt2                                                                             |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|bench_7083.smt2                                                                             |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|bench_7085.smt2                                                                             |  18.494s  |  18.494s  |   0.000s  | 0.0%|
|bench_7086.smt2                                                                             |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|bench_7088.smt2                                                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|bench_709.smt2                                                                              |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|bench_7095.smt2                                                                             |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|bench_710.smt2                                                                              |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|bench_7116.smt2                                                                             | 598.777s  | 598.777s  |   0.000s  | 0.0%|
|bench_7119.smt2                                                                             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|bench_712.smt2                                                                              |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|bench_7127.smt2                                                                             |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|bench_7138.smt2                                                                             |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|bench_7139.smt2                                                                             |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|bench_7140.smt2                                                                             |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|bench_7142.smt2                                                                             |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|bench_7146.smt2                                                                             |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|bench_7150.smt2                                                                             |   4.771s  |   4.771s  |   0.000s  | 0.0%|
|bench_7152.smt2                                                                             |  19.491s  |  19.491s  |   0.000s  | 0.0%|
|bench_7166.smt2                                                                             |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|bench_717.smt2                                                                              |   3.020s  |   3.020s  |   0.000s  | 0.0%|
|bench_7171.smt2                                                                             |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|bench_7182.smt2                                                                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|bench_7185.smt2                                                                             |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|bench_7188.smt2                                                                             |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|bench_720.smt2                                                                              |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|bench_721.smt2                                                                              |   5.391s  |   5.391s  |   0.000s  | 0.0%|
|bench_7219.smt2                                                                             |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|bench_7229.smt2                                                                             |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|bench_7233.smt2                                                                             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|bench_7242.smt2                                                                             |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|bench_7270.smt2                                                                             |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|bench_7274.smt2                                                                             |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|bench_7278.smt2                                                                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|bench_7304.smt2                                                                             |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|bench_7306.smt2                                                                             |   4.830s  |   4.830s  |   0.000s  | 0.0%|
|bench_7310.smt2                                                                             |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|bench_7314.smt2                                                                             |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|bench_7319.smt2                                                                             |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|bench_7329.smt2                                                                             |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|bench_7331.smt2                                                                             |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|bench_7339.smt2                                                                             |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|bench_7357.smt2                                                                             |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|bench_7375.smt2                                                                             |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|bench_7382.smt2                                                                             |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|bench_7383.smt2                                                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|bench_7388.smt2                                                                             |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|bench_7406.smt2                                                                             |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|bench_7412.smt2                                                                             |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|bench_7415.smt2                                                                             |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|bench_7421.smt2                                                                             |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|bench_743.smt2                                                                              |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|bench_7438.smt2                                                                             |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|bench_7454.smt2                                                                             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|bench_746.smt2                                                                              |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|bench_7465.smt2                                                                             |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|bench_748.smt2                                                                              |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|bench_7489.smt2                                                                             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|bench_749.smt2                                                                              |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|bench_7494.smt2                                                                             |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|bench_7495.smt2                                                                             |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|bench_7496.smt2                                                                             |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|bench_7498.smt2                                                                             |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|bench_7517.smt2                                                                             |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|bench_7523.smt2                                                                             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|bench_7528.smt2                                                                             |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|bench_753.smt2                                                                              |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|bench_7532.smt2                                                                             |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|bench_7534.smt2                                                                             |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|bench_7537.smt2                                                                             |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|bench_7539.smt2                                                                             |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|bench_7550.smt2                                                                             |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|bench_7552.smt2                                                                             |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|bench_7556.smt2                                                                             |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|bench_7563.smt2                                                                             |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|bench_7565.smt2                                                                             |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|bench_7573.smt2                                                                             |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|bench_7575.smt2                                                                             |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|bench_76.smt2                                                                               |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|bench_760.smt2                                                                              |   1.491s  |   1.491s  |   0.000s  | 0.0%|
|bench_7601.smt2                                                                             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|bench_7612.smt2                                                                             |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|bench_7627.smt2                                                                             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|bench_7633.smt2                                                                             |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|bench_7636.smt2                                                                             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|bench_7641.smt2                                                                             |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|bench_7642.smt2                                                                             |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|bench_7655.smt2                                                                             |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|bench_7663.smt2                                                                             |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|bench_7669.smt2                                                                             | 599.894s  | 599.894s  |   0.000s  | 0.0%|
|bench_7670.smt2                                                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|bench_7671.smt2                                                                             |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|bench_7673.smt2                                                                             |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|bench_7686.smt2                                                                             |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|bench_7696.smt2                                                                             |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|bench_7705.smt2                                                                             |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|bench_7708.smt2                                                                             |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|bench_7714.smt2                                                                             |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|bench_7729.smt2                                                                             |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|bench_7736.smt2                                                                             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|bench_7749.smt2                                                                             |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|bench_7754.smt2                                                                             |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|bench_7758.smt2                                                                             |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|bench_7765.smt2                                                                             |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|bench_778.smt2                                                                              |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|bench_78.smt2                                                                               |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|bench_7800.smt2                                                                             |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|bench_7807.smt2                                                                             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|bench_7811.smt2                                                                             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|bench_7819.smt2                                                                             |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|bench_7823.smt2                                                                             |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|bench_7826.smt2                                                                             |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|bench_7828.smt2                                                                             |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|bench_7832.smt2                                                                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|bench_7833.smt2                                                                             |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|bench_7834.smt2                                                                             |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|bench_7835.smt2                                                                             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|bench_7842.smt2                                                                             |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|bench_7851.smt2                                                                             |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|bench_7862.smt2                                                                             |   0.376s  |   0.376s  |   0.000s  | 0.0%|
|bench_7863.smt2                                                                             |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|bench_7867.smt2                                                                             |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|bench_787.smt2                                                                              |   0.380s  |   0.380s  |   0.000s  | 0.0%|
|bench_7872.smt2                                                                             |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|bench_7878.smt2                                                                             |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|bench_7881.smt2                                                                             |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|bench_789.smt2                                                                              |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|bench_791.smt2                                                                              |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|bench_793.smt2                                                                              |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|bench_7943.smt2                                                                             |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|bench_796.smt2                                                                              |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|bench_797.smt2                                                                              |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|bench_7973.smt2                                                                             |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|bench_8019.smt2                                                                             |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|bench_8030.smt2                                                                             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|bench_8042.smt2                                                                             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|bench_8049.smt2                                                                             |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|bench_8051.smt2                                                                             |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|bench_8053.smt2                                                                             |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|bench_8054.smt2                                                                             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|bench_8055.smt2                                                                             |   0.446s  |   0.446s  |   0.000s  | 0.0%|
|bench_8070.smt2                                                                             |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|bench_8073.smt2                                                                             |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|bench_808.smt2                                                                              |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|bench_8082.smt2                                                                             |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|bench_8084.smt2                                                                             |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|bench_8088.smt2                                                                             |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|bench_8093.smt2                                                                             |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|bench_8103.smt2                                                                             |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|bench_8110.smt2                                                                             |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|bench_8116.smt2                                                                             |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|bench_8117.smt2                                                                             |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|bench_8147.smt2                                                                             | 599.525s  | 599.525s  |   0.000s  | 0.0%|
|bench_815.smt2                                                                              |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|bench_8165.smt2                                                                             |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|bench_8170.smt2                                                                             |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|bench_8178.smt2                                                                             | 595.679s  | 595.679s  |   0.000s  | 0.0%|
|bench_820.smt2                                                                              |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|bench_8200.smt2                                                                             |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|bench_8228.smt2                                                                             |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|bench_823.smt2                                                                              |   2.843s  |   2.843s  |   0.000s  | 0.0%|
|bench_8234.smt2                                                                             |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|bench_824.smt2                                                                              |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|bench_8245.smt2                                                                             |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|bench_825.smt2                                                                              |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|bench_826.smt2                                                                              |   2.880s  |   2.880s  |   0.000s  | 0.0%|
|bench_8260.smt2                                                                             |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|bench_8271.smt2                                                                             |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|bench_8282.smt2                                                                             |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|bench_8283.smt2                                                                             |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|bench_8289.smt2                                                                             |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|bench_8294.smt2                                                                             |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|bench_8296.smt2                                                                             |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|bench_8298.smt2                                                                             |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|bench_830.smt2                                                                              |   2.644s  |   2.644s  |   0.000s  | 0.0%|
|bench_8306.smt2                                                                             |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|bench_8309.smt2                                                                             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|bench_831.smt2                                                                              |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|bench_8315.smt2                                                                             |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|bench_8320.smt2                                                                             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|bench_8342.smt2                                                                             |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|bench_8344.smt2                                                                             |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|bench_8357.smt2                                                                             |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|bench_8379.smt2                                                                             |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|bench_838.smt2                                                                              |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|bench_8393.smt2                                                                             |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|bench_8394.smt2                                                                             |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|bench_8461.smt2                                                                             |  33.196s  |  33.196s  |   0.000s  | 0.0%|
|bench_8462.smt2                                                                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|bench_8478.smt2                                                                             | 599.686s  | 599.686s  |   0.000s  | 0.0%|
|bench_8487.smt2                                                                             |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|bench_8492.smt2                                                                             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|bench_8495.smt2                                                                             | 599.360s  | 599.360s  |   0.000s  | 0.0%|
|bench_8507.smt2                                                                             |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|bench_8512.smt2                                                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|bench_856.smt2                                                                              |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|bench_8562.smt2                                                                             | 599.394s  | 599.394s  |   0.000s  | 0.0%|
|bench_8564.smt2                                                                             |   1.719s  |   1.719s  |   0.000s  | 0.0%|
|bench_8579.smt2                                                                             |  11.566s  |  11.566s  |   0.000s  | 0.0%|
|bench_858.smt2                                                                              |   5.191s  |   5.191s  |   0.000s  | 0.0%|
|bench_86.smt2                                                                               |   4.236s  |   4.236s  |   0.000s  | 0.0%|
|bench_864.smt2                                                                              |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|bench_868.smt2                                                                              |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|bench_875.smt2                                                                              |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|bench_881.smt2                                                                              |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|bench_883.smt2                                                                              |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|bench_888.smt2                                                                              |   2.427s  |   2.427s  |   0.000s  | 0.0%|
|bench_894.smt2                                                                              |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|bench_900.smt2                                                                              |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|bench_9009.smt2                                                                             | 599.206s  | 599.206s  |   0.000s  | 0.0%|
|bench_905.smt2                                                                              |   4.271s  |   4.271s  |   0.000s  | 0.0%|
|bench_91.smt2                                                                               |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|bench_914.smt2                                                                              |  23.205s  |  23.205s  |   0.000s  | 0.0%|
|bench_9173.smt2                                                                             |  13.408s  |  13.408s  |   0.000s  | 0.0%|
|bench_919.smt2                                                                              |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|bench_92.smt2                                                                               |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|bench_924.smt2                                                                              |   0.417s  |   0.417s  |   0.000s  | 0.0%|
|bench_926.smt2                                                                              |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|bench_9280.smt2                                                                             | 134.585s  | 134.585s  |   0.000s  | 0.0%|
|bench_9299.smt2                                                                             |  73.156s  |  73.156s  |   0.000s  | 0.0%|
|bench_930.smt2                                                                              |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|bench_9301.smt2                                                                             |  15.776s  |  15.776s  |   0.000s  | 0.0%|
|bench_9337.smt2                                                                             | 599.359s  | 599.359s  |   0.000s  | 0.0%|
|bench_9343.smt2                                                                             | 146.199s  | 146.199s  |   0.000s  | 0.0%|
|bench_9360.smt2                                                                             |  19.282s  |  19.282s  |   0.000s  | 0.0%|
|bench_938.smt2                                                                              |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|bench_941.smt2                                                                              |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|bench_944.smt2                                                                              |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|bench_945.smt2                                                                              |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|bench_9535.smt2                                                                             | 599.591s  | 599.591s  |   0.000s  | 0.0%|
|bench_954.smt2                                                                              |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|bench_957.smt2                                                                              |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|bench_961.smt2                                                                              |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|bench_964.smt2                                                                              |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|bench_965.smt2                                                                              |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|bench_9653.smt2                                                                             |  57.991s  |  57.991s  |   0.000s  | 0.0%|
|bench_97.smt2                                                                               |   5.446s  |   5.446s  |   0.000s  | 0.0%|
|bench_972.smt2                                                                              |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|bench_974.smt2                                                                              |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|bench_975.smt2                                                                              |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|bench_979.smt2                                                                              |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|bench_98.smt2                                                                               |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|bench_981.smt2                                                                              |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|bench_983.smt2                                                                              |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|bench_9846.smt2                                                                             |  13.397s  |  13.397s  |   0.000s  | 0.0%|
|bench_985.smt2                                                                              |  10.499s  |  10.499s  |   0.000s  | 0.0%|
|bench_988.smt2                                                                              |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|bench_991.smt2                                                                              |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|bench_992.smt2                                                                              |  33.878s  |  33.878s  |   0.000s  | 0.0%|
|bench_993.smt2                                                                              |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|bench_994.smt2                                                                              |   7.804s  |   7.804s  |   0.000s  | 0.0%|
|bench_9946.smt2                                                                             |  67.360s  |  67.360s  |   0.000s  | 0.0%|
|bench_996.smt2                                                                              | 599.718s  | 599.718s  |   0.000s  | 0.0%|
|bench_997.smt2                                                                              |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|bgpd_bgpd_vc76751.smt2                                                                      |   2.495s  |   2.495s  |   0.000s  | 0.0%|
|bgpd_bgpd_vc76752.smt2                                                                      |  18.222s  |  18.222s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc330950.smt2                                                               |   7.315s  |   7.315s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc330976.smt2                                                               |  11.256s  |  11.256s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc330978.smt2                                                               |  11.924s  |  11.924s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331001.smt2                                                               |  10.561s  |  10.561s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331002.smt2                                                               |   9.597s  |   9.597s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331003.smt2                                                               |  11.182s  |  11.182s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331007.smt2                                                               |  11.699s  |  11.699s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331044.smt2                                                               |  16.030s  |  16.030s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331052.smt2                                                               |  22.629s  |  22.629s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331054.smt2                                                               |  16.183s  |  16.183s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331082.smt2                                                               |  18.196s  |  18.196s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331086.smt2                                                               |  31.410s  |  31.410s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331088.smt2                                                               |  12.142s  |  12.142s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331089.smt2                                                               |  18.935s  |  18.935s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331092.smt2                                                               |  16.478s  |  16.478s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331097.smt2                                                               |  18.258s  |  18.258s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331106.smt2                                                               |  19.475s  |  19.475s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331114.smt2                                                               |  16.990s  |  16.990s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331126.smt2                                                               |  32.685s  |  32.685s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331137.smt2                                                               |  45.220s  |  45.220s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331146.smt2                                                               |  41.625s  |  41.625s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331148.smt2                                                               |  23.170s  |  23.170s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331154.smt2                                                               |  23.623s  |  23.623s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331156.smt2                                                               |  29.071s  |  29.071s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331161.smt2                                                               |  31.160s  |  31.160s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331166.smt2                                                               |  34.485s  |  34.485s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331167.smt2                                                               |  20.283s  |  20.283s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc331169.smt2                                                               |  15.250s  |  15.250s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc351277.smt2                                                               |   2.966s  |   2.966s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc351344.smt2                                                               |   3.875s  |   3.875s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc351348.smt2                                                               |   8.730s  |   8.730s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc352293.smt2                                                               |   5.042s  |   5.042s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc352302.smt2                                                               |   2.744s  |   2.744s  |   0.000s  | 0.0%|
|bin_eventlogadm_vc352355.smt2                                                               |   7.720s  |   7.720s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225139.smt2                                                                 |   7.232s  |   7.232s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225280.smt2                                                                 |  10.613s  |  10.613s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225299.smt2                                                                 |  24.403s  |  24.403s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225305.smt2                                                                 |  36.023s  |  36.023s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225312.smt2                                                                 |  12.313s  |  12.313s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225316.smt2                                                                 |  18.382s  |  18.382s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225318.smt2                                                                 |   8.818s  |   8.818s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225320.smt2                                                                 |   8.583s  |   8.583s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225324.smt2                                                                 |  10.121s  |  10.121s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225330.smt2                                                                 |  37.686s  |  37.686s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225332.smt2                                                                 |  26.757s  |  26.757s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225336.smt2                                                                 |  18.698s  |  18.698s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225346.smt2                                                                 |  27.856s  |  27.856s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225380.smt2                                                                 |  33.468s  |  33.468s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225392.smt2                                                                 |  23.739s  |  23.739s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225394.smt2                                                                 |  22.592s  |  22.592s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225395.smt2                                                                 |  13.255s  |  13.255s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225399.smt2                                                                 |  28.687s  |  28.687s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225405.smt2                                                                 |  36.997s  |  36.997s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225408.smt2                                                                 |  42.256s  |  42.256s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225412.smt2                                                                 |  27.233s  |  27.233s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225454.smt2                                                                 |  24.847s  |  24.847s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225601.smt2                                                                 |   1.758s  |   1.758s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225626.smt2                                                                 |   3.793s  |   3.793s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225628.smt2                                                                 |   3.216s  |   3.216s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225745.smt2                                                                 |   4.608s  |   4.608s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225756.smt2                                                                 |  17.793s  |  17.793s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225762.smt2                                                                 |  25.131s  |  25.131s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225779.smt2                                                                 |   7.331s  |   7.331s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225786.smt2                                                                 |  24.993s  |  24.993s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225800.smt2                                                                 |  27.297s  |  27.297s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225806.smt2                                                                 |   6.741s  |   6.741s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225815.smt2                                                                 |  19.967s  |  19.967s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225816.smt2                                                                 |   5.170s  |   5.170s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225820.smt2                                                                 |  15.831s  |  15.831s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225824.smt2                                                                 |  19.050s  |  19.050s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225843.smt2                                                                 |  33.116s  |  33.116s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225858.smt2                                                                 |  26.458s  |  26.458s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225895.smt2                                                                 |  30.628s  |  30.628s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225900.smt2                                                                 |  44.055s  |  44.055s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225910.smt2                                                                 |  40.726s  |  40.726s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225912.smt2                                                                 |  71.319s  |  71.319s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1225939.smt2                                                                 |  17.032s  |  17.032s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228446.smt2                                                                 |  21.458s  |  21.458s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228463.smt2                                                                 |   7.603s  |   7.603s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228472.smt2                                                                 |   8.447s  |   8.447s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228474.smt2                                                                 |  19.517s  |  19.517s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228478.smt2                                                                 |  20.608s  |  20.608s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228479.smt2                                                                 |  19.509s  |  19.509s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228487.smt2                                                                 |  15.512s  |  15.512s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228491.smt2                                                                 |  16.725s  |  16.725s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228492.smt2                                                                 |   6.753s  |   6.753s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228509.smt2                                                                 |  25.656s  |  25.656s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228512.smt2                                                                 |  29.769s  |  29.769s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228514.smt2                                                                 |  24.701s  |  24.701s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228524.smt2                                                                 |  28.329s  |  28.329s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228527.smt2                                                                 |  38.271s  |  38.271s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228571.smt2                                                                 |  45.295s  |  45.295s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228577.smt2                                                                 |  39.822s  |  39.822s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1228610.smt2                                                                 |  48.931s  |  48.931s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232002.smt2                                                                 |  12.195s  |  12.195s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232007.smt2                                                                 |  13.628s  |  13.628s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232013.smt2                                                                 |  10.404s  |  10.404s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232030.smt2                                                                 |  17.464s  |  17.464s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232034.smt2                                                                 |  11.540s  |  11.540s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232036.smt2                                                                 |  34.852s  |  34.852s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232066.smt2                                                                 |  22.649s  |  22.649s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232071.smt2                                                                 |  28.977s  |  28.977s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232117.smt2                                                                 |  22.312s  |  22.312s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232128.smt2                                                                 |  20.184s  |  20.184s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232137.smt2                                                                 |  34.808s  |  34.808s  |   0.000s  | 0.0%|
|bin_libmsrpc_vc1232138.smt2                                                                 |  20.429s  |  20.429s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225164.smt2                                                             |   4.244s  |   4.244s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225207.smt2                                                             |  16.184s  |  16.184s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225211.smt2                                                             |  14.748s  |  14.748s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225213.smt2                                                             |   9.833s  |   9.833s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225231.smt2                                                             |  30.771s  |  30.771s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225236.smt2                                                             |  26.252s  |  26.252s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225237.smt2                                                             |  22.559s  |  22.559s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225238.smt2                                                             |  22.482s  |  22.482s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225246.smt2                                                             |   8.719s  |   8.719s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225256.smt2                                                             |  28.414s  |  28.414s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225257.smt2                                                             |  40.247s  |  40.247s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225263.smt2                                                             |  28.274s  |  28.274s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225264.smt2                                                             |  24.510s  |  24.510s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225271.smt2                                                             |  23.261s  |  23.261s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225275.smt2                                                             |  27.099s  |  27.099s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225279.smt2                                                             |  28.617s  |  28.617s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225303.smt2                                                             |  48.071s  |  48.071s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225668.smt2                                                             |   6.704s  |   6.704s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225676.smt2                                                             |  17.998s  |  17.998s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225689.smt2                                                             |   8.986s  |   8.986s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225692.smt2                                                             |  16.046s  |  16.046s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225731.smt2                                                             |  25.390s  |  25.390s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225733.smt2                                                             |  11.477s  |  11.477s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225736.smt2                                                             |  33.210s  |  33.210s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225745.smt2                                                             |  34.520s  |  34.520s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225748.smt2                                                             |  15.468s  |  15.468s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225758.smt2                                                             |  28.065s  |  28.065s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225761.smt2                                                             |  62.277s  |  62.277s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225764.smt2                                                             |  11.703s  |  11.703s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225771.smt2                                                             |  36.351s  |  36.351s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225773.smt2                                                             |  45.409s  |  45.409s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225779.smt2                                                             |  20.550s  |  20.550s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225783.smt2                                                             |  38.921s  |  38.921s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225826.smt2                                                             |  21.662s  |  21.662s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225835.smt2                                                             |  37.733s  |  37.733s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225841.smt2                                                             |  24.198s  |  24.198s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225860.smt2                                                             |  53.530s  |  53.530s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1225887.smt2                                                             |  11.299s  |  11.299s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228430.smt2                                                             |  40.360s  |  40.360s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228442.smt2                                                             |  49.714s  |  49.714s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228448.smt2                                                             |  45.389s  |  45.389s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228452.smt2                                                             |  47.871s  |  47.871s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228479.smt2                                                             |  21.839s  |  21.839s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228491.smt2                                                             |  12.770s  |  12.770s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228496.smt2                                                             |  38.705s  |  38.705s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228508.smt2                                                             |  20.581s  |  20.581s  |   0.000s  | 0.0%|
|bin_libsmbclient_vc1228531.smt2                                                             |  22.382s  |  22.382s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc4232.smt2                                                            |   3.843s  |   3.843s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc4243.smt2                                                            |   3.161s  |   3.161s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc4289.smt2                                                            |   3.519s  |   3.519s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc4296.smt2                                                            |   8.860s  |   8.860s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc4297.smt2                                                            |   1.922s  |   1.922s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc4773.smt2                                                            |   8.159s  |   8.159s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc4791.smt2                                                            |   4.709s  |   4.709s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5285.smt2                                                            |   8.618s  |   8.618s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5327.smt2                                                            |  17.672s  |  17.672s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5331.smt2                                                            |  14.560s  |  14.560s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5680.smt2                                                            |   9.511s  |   9.511s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5689.smt2                                                            |   3.566s  |   3.566s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5711.smt2                                                            |   7.970s  |   7.970s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5712.smt2                                                            |   7.723s  |   7.723s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5729.smt2                                                            |   8.038s  |   8.038s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5733.smt2                                                            |   6.554s  |   6.554s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5735.smt2                                                            |   4.378s  |   4.378s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5742.smt2                                                            |  17.889s  |  17.889s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5748.smt2                                                            |   9.718s  |   9.718s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5749.smt2                                                            |   8.660s  |   8.660s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5751.smt2                                                            |   6.990s  |   6.990s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5769.smt2                                                            |   8.276s  |   8.276s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5771.smt2                                                            |   3.547s  |   3.547s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5782.smt2                                                            |  12.479s  |  12.479s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5793.smt2                                                            |  10.391s  |  10.391s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5794.smt2                                                            |   7.165s  |   7.165s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5806.smt2                                                            |   7.337s  |   7.337s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5817.smt2                                                            |   8.274s  |   8.274s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5840.smt2                                                            |   3.313s  |   3.313s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc5848.smt2                                                            |   2.834s  |   2.834s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6049.smt2                                                            |  13.838s  |  13.838s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6074.smt2                                                            |   8.991s  |   8.991s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6105.smt2                                                            |  11.794s  |  11.794s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6117.smt2                                                            |  22.064s  |  22.064s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6120.smt2                                                            |   8.052s  |   8.052s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6139.smt2                                                            |  14.299s  |  14.299s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6150.smt2                                                            |   9.517s  |   9.517s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6161.smt2                                                            |  11.329s  |  11.329s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6178.smt2                                                            |  10.534s  |  10.534s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6181.smt2                                                            |  25.940s  |  25.940s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6182.smt2                                                            |  19.986s  |  19.986s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6195.smt2                                                            |  20.657s  |  20.657s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6199.smt2                                                            |  14.580s  |  14.580s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6205.smt2                                                            |  24.668s  |  24.668s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6217.smt2                                                            |  23.700s  |  23.700s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6229.smt2                                                            |  38.984s  |  38.984s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6241.smt2                                                            |  26.092s  |  26.092s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6242.smt2                                                            |  25.678s  |  25.678s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6250.smt2                                                            |  27.721s  |  27.721s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6255.smt2                                                            |  27.124s  |  27.124s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6266.smt2                                                            |  35.066s  |  35.066s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6270.smt2                                                            |  27.220s  |  27.220s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6271.smt2                                                            |  15.200s  |  15.200s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6272.smt2                                                            |  13.300s  |  13.300s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6280.smt2                                                            |  33.511s  |  33.511s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6287.smt2                                                            |  22.578s  |  22.578s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6288.smt2                                                            |  21.520s  |  21.520s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6289.smt2                                                            |  16.799s  |  16.799s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6291.smt2                                                            |  19.710s  |  19.710s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6295.smt2                                                            |  25.537s  |  25.537s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6297.smt2                                                            |  12.010s  |  12.010s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6298.smt2                                                            |  25.468s  |  25.468s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6299.smt2                                                            |  23.544s  |  23.544s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6305.smt2                                                            |  22.301s  |  22.301s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6308.smt2                                                            |  23.799s  |  23.799s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6309.smt2                                                            |  14.330s  |  14.330s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6314.smt2                                                            |  27.836s  |  27.836s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6315.smt2                                                            |  18.382s  |  18.382s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6325.smt2                                                            |  31.727s  |  31.727s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6328.smt2                                                            |  27.787s  |  27.787s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6336.smt2                                                            |  25.679s  |  25.679s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6339.smt2                                                            |  19.648s  |  19.648s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6343.smt2                                                            |  29.170s  |  29.170s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6346.smt2                                                            |  30.786s  |  30.786s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc6845.smt2                                                            |   5.205s  |   5.205s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7060.smt2                                                            |   5.049s  |   5.049s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7064.smt2                                                            |   5.346s  |   5.346s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7068.smt2                                                            |  13.101s  |  13.101s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7072.smt2                                                            |  10.806s  |  10.806s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7086.smt2                                                            |  10.202s  |  10.202s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7087.smt2                                                            |  18.011s  |  18.011s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7094.smt2                                                            |  11.268s  |  11.268s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7104.smt2                                                            |  11.018s  |  11.018s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7105.smt2                                                            |  11.222s  |  11.222s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7116.smt2                                                            |  17.742s  |  17.742s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7117.smt2                                                            |  23.053s  |  23.053s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7119.smt2                                                            |   6.785s  |   6.785s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7120.smt2                                                            |  14.551s  |  14.551s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7124.smt2                                                            |   9.510s  |   9.510s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7130.smt2                                                            |  10.075s  |  10.075s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7131.smt2                                                            |  12.744s  |  12.744s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7133.smt2                                                            |  11.444s  |  11.444s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7225.smt2                                                            |   3.748s  |   3.748s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7281.smt2                                                            |   4.613s  |   4.613s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7285.smt2                                                            |  14.268s  |  14.268s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7296.smt2                                                            |   7.598s  |   7.598s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7636.smt2                                                            |  15.776s  |  15.776s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7637.smt2                                                            |  13.788s  |  13.788s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7643.smt2                                                            |  24.932s  |  24.932s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7644.smt2                                                            |   8.476s  |   8.476s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7652.smt2                                                            |   9.609s  |   9.609s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7666.smt2                                                            |  30.386s  |  30.386s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7727.smt2                                                            |  14.023s  |  14.023s  |   0.000s  | 0.0%|
|bin_libsmbsharemodes_vc7750.smt2                                                            |  35.199s  |  35.199s  |   0.000s  | 0.0%|
|bitops7.smt2                                                                                |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|bv-term-small-rw_1391.smt2                                                                  |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|bv-term-small-rw_1516.smt2                                                                  |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|bv-term-small-rw_166.smt2                                                                   |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|bv-term-small-rw_207.smt2                                                                   |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|bv-term-small-rw_230.smt2                                                                   |   0.354s  |   0.354s  |   0.000s  | 0.0%|
|bv-term-small-rw_250.smt2                                                                   |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|bv-term-small-rw_260.smt2                                                                   |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|bv-term-small-rw_314.smt2                                                                   |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|bv-term-small-rw_318.smt2                                                                   |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|bv-term-small-rw_327.smt2                                                                   |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|bv-term-small-rw_337.smt2                                                                   |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|bv-term-small-rw_356.smt2                                                                   |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|bv-term-small-rw_36.smt2                                                                    |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|bv-term-small-rw_45.smt2                                                                    |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|bv-term-small-rw_465.smt2                                                                   |   0.405s  |   0.405s  |   0.000s  | 0.0%|
|bv-term-small-rw_47.smt2                                                                    |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|bv-term-small-rw_521.smt2                                                                   |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|bv-term-small-rw_720.smt2                                                                   |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|bv-term-small-rw_904.smt2                                                                   |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|bvsdiv.smt2                                                                                 |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|cvs_vc105319.smt2                                                                           |   3.639s  |   3.639s  |   0.000s  | 0.0%|
|cvs_vc105322.smt2                                                                           |   2.453s  |   2.453s  |   0.000s  | 0.0%|
|cvs_vc105323.smt2                                                                           |   1.909s  |   1.909s  |   0.000s  | 0.0%|
|cvs_vc105357.smt2                                                                           |   4.144s  |   4.144s  |   0.000s  | 0.0%|
|cvs_vc105369.smt2                                                                           |   2.072s  |   2.072s  |   0.000s  | 0.0%|
|cvs_vc105421.smt2                                                                           |   1.493s  |   1.493s  |   0.000s  | 0.0%|
|cvs_vc105422.smt2                                                                           |   8.650s  |   8.650s  |   0.000s  | 0.0%|
|cvs_vc105458.smt2                                                                           |   4.580s  |   4.580s  |   0.000s  | 0.0%|
|div.c.20.smt2                                                                               | 125.965s  | 125.965s  |   0.000s  | 0.0%|
|div3.c.20.smt2                                                                              | 599.507s  | 599.507s  |   0.000s  | 0.0%|
|e1_1.c.smt2                                                                                 |   0.278s  |   0.278s  |   0.000s  | 0.0%|
|e2_2.c.smt2                                                                                 |   0.635s  |   0.635s  |   0.000s  | 0.0%|
|f23.smt2                                                                                    |   7.888s  |   7.888s  |   0.000s  | 0.0%|
|fig5.phx.smt2                                                                               |   1.948s  |   1.948s  |   0.000s  | 0.0%|
|gryzzles.22.lp.smt2                                                                         |   4.520s  |   4.520s  |   0.000s  | 0.0%|
|gryzzles.8.lp.smt2                                                                          |   3.989s  |   3.989s  |   0.000s  | 0.0%|
|inf1.smt2                                                                                   |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|innd_innd_vc32473.smt2                                                                      |  19.853s  |  19.853s  |   0.000s  | 0.0%|
|innd_innd_vc32478.smt2                                                                      |  10.893s  |  10.893s  |   0.000s  | 0.0%|
|innd_innd_vc32492.smt2                                                                      |  13.094s  |  13.094s  |   0.000s  | 0.0%|
|innd_innd_vc32642.smt2                                                                      |  28.717s  |  28.717s  |   0.000s  | 0.0%|
|innd_innd_vc32648.smt2                                                                      |  17.599s  |  17.599s  |   0.000s  | 0.0%|
|innd_innd_vc32659.smt2                                                                      |  21.104s  |  21.104s  |   0.000s  | 0.0%|
|innd_innd_vc32740.smt2                                                                      |  14.472s  |  14.472s  |   0.000s  | 0.0%|
|innd_innd_vc33153.smt2                                                                      |  24.615s  |  24.615s  |   0.000s  | 0.0%|
|innd_innd_vc33158.smt2                                                                      |  31.004s  |  31.004s  |   0.000s  | 0.0%|
|innd_innd_vc33162.smt2                                                                      |  51.453s  |  51.453s  |   0.000s  | 0.0%|
|innd_innd_vc33342.smt2                                                                      |  10.409s  |  10.409s  |   0.000s  | 0.0%|
|innd_innd_vc33343.smt2                                                                      |  28.097s  |  28.097s  |   0.000s  | 0.0%|
|innd_innd_vc33347.smt2                                                                      |  13.580s  |  13.580s  |   0.000s  | 0.0%|
|innd_innd_vc33349.smt2                                                                      |  21.685s  |  21.685s  |   0.000s  | 0.0%|
|innd_innd_vc33528.smt2                                                                      |  25.040s  |  25.040s  |   0.000s  | 0.0%|
|innd_innd_vc33538.smt2                                                                      |  22.242s  |  22.242s  |   0.000s  | 0.0%|
|innd_innd_vc33544.smt2                                                                      |  22.311s  |  22.311s  |   0.000s  | 0.0%|
|innd_innd_vc33561.smt2                                                                      |  99.078s  |  99.078s  |   0.000s  | 0.0%|
|innd_innd_vc33564.smt2                                                                      | 239.387s  | 239.387s  |   0.000s  | 0.0%|
|innd_innd_vc33728.smt2                                                                      |  28.898s  |  28.898s  |   0.000s  | 0.0%|
|innd_innd_vc33732.smt2                                                                      |  15.139s  |  15.139s  |   0.000s  | 0.0%|
|innd_innd_vc33738.smt2                                                                      |  12.962s  |  12.962s  |   0.000s  | 0.0%|
|innd_innd_vc33741.smt2                                                                      |  26.333s  |  26.333s  |   0.000s  | 0.0%|
|innd_innd_vc33743.smt2                                                                      |  15.161s  |  15.161s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc24623.smt2                                                               |   6.422s  |   6.422s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc24627.smt2                                                               |   9.313s  |   9.313s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc24797.smt2                                                               |  14.465s  |  14.465s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc24827.smt2                                                               |  74.497s  |  74.497s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc24828.smt2                                                               |  19.779s  |  19.779s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc24829.smt2                                                               |  22.519s  |  22.519s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc24830.smt2                                                               |  23.470s  |  23.470s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc25420.smt2                                                               |  37.004s  |  37.004s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc25433.smt2                                                               |  14.749s  |  14.749s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc25444.smt2                                                               |  12.426s  |  12.426s  |   0.000s  | 0.0%|
|innfeed_imapfeed_vc25456.smt2                                                               |  51.208s  |  51.208s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc36443.smt2                                                                |   9.530s  |   9.530s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc36459.smt2                                                                |  23.111s  |  23.111s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc36461.smt2                                                                |  16.639s  |  16.639s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc36615.smt2                                                                |  49.672s  |  49.672s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc36634.smt2                                                                |  19.067s  |  19.067s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc37055.smt2                                                                |  16.140s  |  16.140s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc37058.smt2                                                                |  16.577s  |  16.577s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc37224.smt2                                                                |  20.786s  |  20.786s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc37255.smt2                                                                |  25.639s  |  25.639s  |   0.000s  | 0.0%|
|innfeed_innfeed_vc37260.smt2                                                                |  22.369s  |  22.369s  |   0.000s  | 0.0%|
|knightTour.in01.smt2                                                                        |   5.088s  |   5.088s  |   0.000s  | 0.0%|
|matrixsqrt.smt2                                                                             |   2.984s  |   2.984s  |   0.000s  | 0.0%|
|mobiledevice_bit8_na6_nr3_twocond.smt2                                                      |   5.387s  |   5.387s  |   0.000s  | 0.0%|
|mult1.c.20.smt2                                                                             |  19.690s  |  19.690s  |   0.000s  | 0.0%|
|mult2.c.10.smt2                                                                             |  13.624s  |  13.624s  |   0.000s  | 0.0%|
|ndist.b.21996.smt2                                                                          |  11.499s  |  11.499s  |   0.000s  | 0.0%|
|ndist.b.27984.smt2                                                                          |  21.821s  |  21.821s  |   0.000s  | 0.0%|
|ndist.b.28982.smt2                                                                          |  13.946s  |  13.946s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc20411.smt2                                                                    |  14.215s  |  14.215s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21034.smt2                                                                    |  18.044s  |  18.044s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21209.smt2                                                                    |  11.952s  |  11.952s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21211.smt2                                                                    |  16.336s  |  16.336s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21221.smt2                                                                    |  25.214s  |  25.214s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21229.smt2                                                                    |  23.227s  |  23.227s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21232.smt2                                                                    |  20.372s  |  20.372s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21244.smt2                                                                    |  26.541s  |  26.541s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21422.smt2                                                                    |  16.625s  |  16.625s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21427.smt2                                                                    |  62.361s  |  62.361s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21428.smt2                                                                    |  17.334s  |  17.334s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21434.smt2                                                                    |  23.703s  |  23.703s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21435.smt2                                                                    |  20.449s  |  20.449s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21446.smt2                                                                    |  57.560s  |  57.560s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21451.smt2                                                                    |  40.435s  |  40.435s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21636.smt2                                                                    |  63.129s  |  63.129s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21648.smt2                                                                    |  25.179s  |  25.179s  |   0.000s  | 0.0%|
|nnrpd_nnrpd_vc21666.smt2                                                                    |  33.327s  |  33.327s  |   0.000s  | 0.0%|
|predicate_1245.smt2                                                                         |   0.603s  |   0.603s  |   0.000s  | 0.0%|
|predicate_1246.smt2                                                                         |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|predicate_169_0.smt2                                                                        |  13.487s  |  13.487s  |   0.000s  | 0.0%|
|predicate_1898.smt2                                                                         |   8.553s  |   8.553s  |   0.000s  | 0.0%|
|predicate_2077.smt2                                                                         |   6.321s  |   6.321s  |   0.000s  | 0.0%|
|predicate_275.smt2                                                                          |  10.755s  |  10.755s  |   0.000s  | 0.0%|
|predicate_2801.smt2                                                                         |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|predicate_484.smt2                                                                          |   0.375s  |   0.375s  |   0.000s  | 0.0%|
|predicate_490.smt2                                                                          |   0.335s  |   0.335s  |   0.000s  | 0.0%|
|predicate_493.smt2                                                                          |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|predicate_496.smt2                                                                          |   3.627s  |   3.627s  |   0.000s  | 0.0%|
|predicate_602.smt2                                                                          |  19.650s  |  19.650s  |   0.000s  | 0.0%|
|predicate_735.smt2                                                                          |  11.383s  |  11.383s  |   0.000s  | 0.0%|
|problem_1.smt2                                                                              |   0.432s  |   0.432s  |   0.000s  | 0.0%|
|problem_7.smt2                                                                              | 233.108s  | 233.108s  |   0.000s  | 0.0%|
|problem_8.smt2                                                                              | 188.370s  | 188.370s  |   0.000s  | 0.0%|
|problem_9.smt2                                                                              |   0.865s  |   0.865s  |   0.000s  | 0.0%|
|rand_100_400_1159666138_9.lp.smt2                                                           |  15.183s  |  15.183s  |   0.000s  | 0.0%|
|rand_150_600_1159731678_14.lp.smt2                                                          |  19.613s  |  19.613s  |   0.000s  | 0.0%|
|rand_150_600_1159731678_15.lp.smt2                                                          |  66.441s  |  66.441s  |   0.000s  | 0.0%|
|rand_200_800_1159728969_10.lp.smt2                                                          | 146.836s  | 146.836s  |   0.000s  | 0.0%|
|rand_20_100_1235851242_0_k-3_v-15_e-25_sat.gph.smt2                                         | 192.159s  | 192.159s  |   0.000s  | 0.0%|
|rand_65_500_1235857888_0_k-6_sat.gph.smt2                                                   |  16.324s  |  16.324s  |   0.000s  | 0.0%|
|rand_80_500_1235848939_0_k-9_sat.gph.smt2                                                   |  68.552s  |  68.552s  |   0.000s  | 0.0%|
|rfunit_flat-64.smt2                                                                         |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|run_00000.trace.Alloc_zero__011273.smt2                                                     |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|run_00000.trace.Alloc_zero__018344.smt2                                                     |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|run_00000.trace.Alloc_zero__019220.smt2                                                     |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|run_00000.trace.Alloc_zero__020079.smt2                                                     |   0.314s  |   0.314s  |   0.000s  | 0.0%|
|run_00000.trace.cond_016653_0x95026e6_00.smt2                                               |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|run_00000.trace.cond_017116_0x950130a_00.smt2                                               |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|run_00000.trace.cond_017924_0x950130a_00.smt2                                               |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|run_00000.trace.cond_018783_0x950130a_00.smt2                                               |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|run_00000.trace.cond_019196_0x95026e6_00.smt2                                               |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|run_00000.trace.cond_019659_0x950130a_00.smt2                                               |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|run_00000.trace.cond_020055_0x95026e6_00.smt2                                               |   0.347s  |   0.347s  |   0.000s  | 0.0%|
|run_00000.trace.cond_285172_0xe7af40_00.smt2                                                |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|run_00000.trace.cond_285198_0xe7af87_00.smt2                                                |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|run_00000.trace.cond_455476_0xe7af69_00.smt2                                                |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|run_00012.trace.cond_057573_0x16388_00.smt2                                                 |   0.385s  |   0.385s  |   0.000s  | 0.0%|
|run_03230.trace.cond_000028_0x40201f_00.smt2                                                |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|run_03230.trace.cond_000032_0x40248d_00.smt2                                                |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|run_03230.trace.cond_011742_0x4066e2_00.smt2                                                |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|run_03230.trace.cond_011923_0x4182b4_00.smt2                                                |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|run_03230.trace.cond_011951_0x4182b4_00.smt2                                                |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|run_03230.trace.cond_011955_0x4182de_00.smt2                                                |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|run_03230.trace.cond_011969_0x4182de_00.smt2                                                |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|run_03230.trace.cond_012011_0x4182de_00.smt2                                                |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|run_03230.trace.cond_012035_0x4182b4_00.smt2                                                |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|run_03230.trace.cond_012053_0x4182de_00.smt2                                                |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|run_03230.trace.cond_012133_0x4182b4_00.smt2                                                |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|run_03230.trace.cond_012161_0x4182b4_00.smt2                                                |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|run_03230.trace.cond_012175_0x4182b4_00.smt2                                                |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025314_0x41821d_00.smt2                                                |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025405_0x418209_00.smt2                                                |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025439_0x418209_00.smt2                                                |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025442_0x41821d_00.smt2                                                |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025454_0x418209_00.smt2                                                |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025469_0x418209_00.smt2                                                |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025506_0x41821d_00.smt2                                                |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025552_0x41820e_00.smt2                                                |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025570_0x41821d_00.smt2                                                |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025582_0x418209_00.smt2                                                |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025597_0x418209_00.smt2                                                |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025600_0x41821d_00.smt2                                                |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025616_0x41820e_00.smt2                                                |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|run_03230.trace.cond_025638_0x41821d_00.smt2                                                |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|send-more-money.smt2                                                                        |   0.497s  |   0.497s  |   0.000s  | 0.0%|
|servers_slapd_a_vc149572.smt2                                                               |   8.833s  |   8.833s  |   0.000s  | 0.0%|
|servers_slapd_a_vc149789.smt2                                                               | 601.273s  | 601.273s  |   0.000s  | 0.0%|
|simple_bit8_na1_nr1_twocond.smt2                                                            |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|smulov4bw1024.smt2                                                                          | 592.420s  | 592.420s  |   0.000s  | 0.0%|
|sort.smt2                                                                                   |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|src_wget_vc17453.smt2                                                                       |   5.766s  |   5.766s  |   0.000s  | 0.0%|
|src_wget_vc17891.smt2                                                                       | 120.111s  | 120.111s  |   0.000s  | 0.0%|
|src_wget_vc17906.smt2                                                                       |  42.592s  |  42.592s  |   0.000s  | 0.0%|
|src_wget_vc17911.smt2                                                                       | 152.623s  | 152.623s  |   0.000s  | 0.0%|
|src_wget_vc17912.smt2                                                                       | 347.678s  | 347.678s  |   0.000s  | 0.0%|
|src_wget_vc17913.smt2                                                                       |  34.927s  |  34.927s  |   0.000s  | 0.0%|
|src_wget_vc18169.smt2                                                                       |   2.861s  |   2.861s  |   0.000s  | 0.0%|
|src_wget_vc18506.smt2                                                                       |  24.414s  |  24.414s  |   0.000s  | 0.0%|
|test_v3_r3_vr10_c1_s24300.smt2                                                              |   6.443s  |   6.443s  |   0.000s  | 0.0%|
|try3_noof_functions_dwp_stty.visible.il.dwp.smt2                                            |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|try3_noof_functions_dwp_touch.yyerror.il.dwp.smt2                                           |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|try5_small_noof_functions_dwp_cut.hash_int.il.dwp.smt2                                      |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|try5_small_noof_functions_dwp_expr.nomoreargs.il.dwp.smt2                                   |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|try5_small_noof_functions_dwp_stty.visible.il.dwp.smt2                                      |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_cat.quoting_options_from_style.il.flanagansaxe.smt2  |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_chgrp.quoting_options_from_style.il.flanagansaxe.smt2  |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_cut.hash_int.il.flanagansaxe.smt2                    |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_echo.quoting_options_from_style.il.flanagansaxe.smt2  |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_env.quoting_options_from_style.il.flanagansaxe.smt2  |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_fold.quoting_options_from_style.il.flanagansaxe.smt2  |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_hostid.quoting_options_from_style.il.flanagansaxe.smt2  |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_kill.quoting_options_from_style.il.flanagansaxe.smt2  |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_link.quoting_options_from_style.il.flanagansaxe.smt2  |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_mkfifo.quoting_options_from_style.il.flanagansaxe.smt2  |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_nice.quoting_options_from_style.il.flanagansaxe.smt2  |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_nl.quoting_options_from_style.il.flanagansaxe.smt2   |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_pinky.quoting_options_from_style.il.flanagansaxe.smt2  |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_ptx.quoting_options_from_style.il.flanagansaxe.smt2  |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_seq.quoting_options_from_style.il.flanagansaxe.smt2  |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_sleep.quoting_options_from_style.il.flanagansaxe.smt2  |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_sum.quoting_options_from_style.il.flanagansaxe.smt2  |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_tac.quoting_options_from_style.il.flanagansaxe.smt2  |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_test.quoting_options_from_style.il.flanagansaxe.smt2  |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_touch.quoting_options_from_style.il.flanagansaxe.smt2  |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_true.quoting_options_from_style.il.flanagansaxe.smt2  |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_tsort.quoting_options_from_style.il.flanagansaxe.smt2  |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_tty.quoting_options_from_style.il.flanagansaxe.smt2  |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_unexpand.quoting_options_from_style.il.flanagansaxe.smt2  |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_users.quoting_options_from_style.il.flanagansaxe.smt2  |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_vdir.quoting_options_from_style.il.flanagansaxe.smt2  |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|try5_small_noof_functions_flanagansaxe_wc.quoting_options_from_style.il.flanagansaxe.smt2   |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|try5_small_noof_functions_fse-bfs_shuf.input_numbers_option_used.il.fse-bfs.smt2            |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|try5_small_true_functions_dwp_stty.visible.il.dwp.smt2                                      |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|try5_small_true_functions_dwp_yes.close_stdout_set_file_name.il.dwp.smt2                    |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_chgrp.i_ring_init.il.flanagansaxe.smt2               |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_join.initseq.il.flanagansaxe.smt2                    |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_md5sum.md5_init_ctx.il.flanagansaxe.smt2             |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_sha1sum.sha1_read_ctx.il.flanagansaxe.smt2           |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_stty.visible.il.flanagansaxe.smt2                    |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_tac.rpl_re_set_syntax.il.flanagansaxe.smt2           |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_vdir.hash_get_n_entries.il.flanagansaxe.smt2         |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|try5_small_true_functions_flanagansaxe_vdir.unsigned_file_size.il.flanagansaxe.smt2         |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|try5_small_true_functions_fse-bfs_stty.visible.il.fse-bfs.smt2                              |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|unconstrained04.smt2                                                                        |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|unconstrained07.smt2                                                                        |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|unconstrained08.smt2                                                                        |   0.109s  |   0.109s  |   0.000s  | 0.0%|
</details>
