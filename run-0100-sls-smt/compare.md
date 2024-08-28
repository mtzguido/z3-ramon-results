Comparing data and data


# SUMMARY
- LHS tests = 2447
- RHS tests = 2447
- LHS success = 0  (0.0%)
- RHS success = 0  (0.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: sls-smt
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: fa6f3f2dba89c2c44282f10c468e7482972a9bdd
Z3 branch: sls
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: inputs/QF_SLIA_SAT
Z3 commit message: fixing prop-queue

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: sls-smt
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: fa6f3f2dba89c2c44282f10c468e7482972a9bdd
Z3 branch: sls
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: inputs/QF_SLIA_SAT
Z3 commit message: fixing prop-queue

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|2380_attack.smt2                                                                           |   0.017s |18.444MiB|
|2857_attack.smt2                                                                           |   0.016s |18.416MiB|
|617_attack.smt2                                                                            |   0.016s |18.384MiB|
|2646_attack.smt2                                                                           |   0.016s |18.508MiB|
|854_attack.smt2                                                                            |   0.016s |18.508MiB|
|2961_attack.smt2                                                                           |   0.016s |18.372MiB|
|2045_attack.smt2                                                                           |   0.015s |18.36MiB|
|2726_attack.smt2                                                                           |   0.015s |18.512MiB|
|1096_attack.smt2                                                                           |   0.015s |18.528MiB|
|892_attack.smt2                                                                            |   0.015s |18.784MiB|
|933_attack.smt2                                                                            |   0.015s |18.78MiB|
|2677_attack.smt2                                                                           |   0.015s |18.812MiB|
|101_attack.smt2                                                                            |   0.015s |18.46MiB|
|1191_attack.smt2                                                                           |   0.015s |18.5MiB|
|2110_attack.smt2                                                                           |   0.015s |18.468MiB|
|1460_attack.smt2                                                                           |   0.015s |18.508MiB|
|1084_attack.smt2                                                                           |   0.015s |18.524MiB|
|865_attack.smt2                                                                            |   0.015s |18.472MiB|
|2665_attack.smt2                                                                           |   0.015s |18.512MiB|
|1055_attack.smt2                                                                           |   0.015s |18.332MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|2380_attack.smt2                                                                           |   0.017s |18.444MiB|
|2857_attack.smt2                                                                           |   0.016s |18.416MiB|
|617_attack.smt2                                                                            |   0.016s |18.384MiB|
|2646_attack.smt2                                                                           |   0.016s |18.508MiB|
|854_attack.smt2                                                                            |   0.016s |18.508MiB|
|2961_attack.smt2                                                                           |   0.016s |18.372MiB|
|2045_attack.smt2                                                                           |   0.015s |18.36MiB|
|2726_attack.smt2                                                                           |   0.015s |18.512MiB|
|1096_attack.smt2                                                                           |   0.015s |18.528MiB|
|892_attack.smt2                                                                            |   0.015s |18.784MiB|
|933_attack.smt2                                                                            |   0.015s |18.78MiB|
|2677_attack.smt2                                                                           |   0.015s |18.812MiB|
|101_attack.smt2                                                                            |   0.015s |18.46MiB|
|1191_attack.smt2                                                                           |   0.015s |18.5MiB|
|2110_attack.smt2                                                                           |   0.015s |18.468MiB|
|1460_attack.smt2                                                                           |   0.015s |18.508MiB|
|1084_attack.smt2                                                                           |   0.015s |18.524MiB|
|865_attack.smt2                                                                            |   0.015s |18.472MiB|
|2665_attack.smt2                                                                           |   0.015s |18.512MiB|
|1055_attack.smt2                                                                           |   0.015s |18.332MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|2387_attack.smt2                                                                           |   0.008s |18.912MiB|
|2919_attack.smt2                                                                           |   0.014s |18.884MiB|
|2925_attack.smt2                                                                           |   0.009s |18.848MiB|
|547_attack.smt2                                                                            |   0.012s |18.824MiB|
|2677_attack.smt2                                                                           |   0.015s |18.812MiB|
|487_attack.smt2                                                                            |   0.008s |18.808MiB|
|892_attack.smt2                                                                            |   0.015s |18.784MiB|
|879_attack.smt2                                                                            |   0.011s |18.784MiB|
|933_attack.smt2                                                                            |   0.015s |18.78MiB|
|793_attack.smt2                                                                            |   0.011s |18.776MiB|
|1222_attack.smt2                                                                           |   0.009s |18.776MiB|
|852_attack.smt2                                                                            |   0.012s |18.772MiB|
|773_attack.smt2                                                                            |   0.013s |18.768MiB|
|913_attack.smt2                                                                            |   0.011s |18.768MiB|
|849_attack.smt2                                                                            |   0.012s |18.764MiB|
|755_attack.smt2                                                                            |   0.012s |18.764MiB|
|890_attack.smt2                                                                            |   0.011s |18.764MiB|
|1442_attack.smt2                                                                           |   0.011s |18.764MiB|
|861_attack.smt2                                                                            |   0.011s |18.764MiB|
|808_attack.smt2                                                                            |   0.010s |18.764MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|2387_attack.smt2                                                                           |   0.008s |18.912MiB|
|2919_attack.smt2                                                                           |   0.014s |18.884MiB|
|2925_attack.smt2                                                                           |   0.009s |18.848MiB|
|547_attack.smt2                                                                            |   0.012s |18.824MiB|
|2677_attack.smt2                                                                           |   0.015s |18.812MiB|
|487_attack.smt2                                                                            |   0.008s |18.808MiB|
|892_attack.smt2                                                                            |   0.015s |18.784MiB|
|879_attack.smt2                                                                            |   0.011s |18.784MiB|
|933_attack.smt2                                                                            |   0.015s |18.78MiB|
|793_attack.smt2                                                                            |   0.011s |18.776MiB|
|1222_attack.smt2                                                                           |   0.009s |18.776MiB|
|852_attack.smt2                                                                            |   0.012s |18.772MiB|
|773_attack.smt2                                                                            |   0.013s |18.768MiB|
|913_attack.smt2                                                                            |   0.011s |18.768MiB|
|849_attack.smt2                                                                            |   0.012s |18.764MiB|
|755_attack.smt2                                                                            |   0.012s |18.764MiB|
|890_attack.smt2                                                                            |   0.011s |18.764MiB|
|1442_attack.smt2                                                                           |   0.011s |18.764MiB|
|861_attack.smt2                                                                            |   0.011s |18.764MiB|
|808_attack.smt2                                                                            |   0.010s |18.764MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>
