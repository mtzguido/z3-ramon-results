Comparing data and data


# SUMMARY
- LHS tests = 267
- RHS tests = 267
- LHS success = 267  (100.0%)
- RHS success = 267  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls-ufnia-sat
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 04d0e9492b0066675c75fc5fb1df6b23b79607e5
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_UFNIA_SAT
Z3 commit message: set log level of revert repair down to 3

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls-ufnia-sat
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 04d0e9492b0066675c75fc5fb1df6b23b79607e5
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_UFNIA_SAT
Z3 commit message: set log level of revert repair down to 3

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00005.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00018.smt2                                                                                  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00035.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00149.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00304.smt2                                                                                  |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.012s  |   0.012s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00005.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00018.smt2                                                                                  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00035.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00149.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00304.smt2                                                                                  |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.012s  |   0.012s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00005.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00018.smt2                                                                                  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00035.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00149.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00304.smt2                                                                                  |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.012s  |   0.012s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00005.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00018.smt2                                                                                  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00035.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00149.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00304.smt2                                                                                  |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.012s  |   0.012s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|int_check_eq_bvshl0_rtl.smt2                                                               |  60.071s |19.048MiB|
|int_check_ne_bvudiv0_ltr_inv_g.smt2                                                        |  60.017s |18.8MiB|
|int_check_bvule_bvashr1_ltr_inv_g.smt2                                                     |  60.004s |19.068MiB|
|int_check_bvult_bvashr0_ltr_inv_g.smt2                                                     |  60.003s |19.072MiB|
|qf_muldivrem_876_values_0.smt2                                                             |  60.003s |19.056MiB|
|int_check_bvslt_bvand_rtl.smt2                                                             |  60.002s |18.808MiB|
|int_check_bvsge_bvurem1_rtl.smt2                                                           |  60.002s |18.888MiB|
|int_check_bvugt_bvlshr1_rtl.smt2                                                           |  60.002s |18.788MiB|
|int_check_bvult_bvlshr1_ltr_inv_g.smt2                                                     |  60.001s |18.768MiB|
|int_check_ne_bvurem0_ltr_inv_g.smt2                                                        |  60.001s |18.904MiB|
|int_check_bvsge_bvashr0_rtl.smt2                                                           |  60.001s |18.916MiB|
|int_check_bvslt_bvshl0_rtl.smt2                                                            |  60.000s |18.844MiB|
|int_check_bvsgt_bvmul_rtl.smt2                                                             |  60.000s |18.856MiB|
|qf_Select_740_values_0.smt2                                                                |  60.000s |18.82MiB|
|qf_AndOrXor_732-2_values_0.smt2                                                            |  60.000s |19.012MiB|
|int_check_bvslt_bvlshr1_ltr_inv_g.smt2                                                     |  60.000s |19.072MiB|
|int_check_bvsge_bvadd_ltr_inv_r.smt2                                                       |  60.000s |18.82MiB|
|int_check_bvsgt_bvashr1_rtl.smt2                                                           |  60.000s |18.868MiB|
|int_check_bvsge_bvurem0_ltr_inv_g.smt2                                                     |  60.000s |18.788MiB|
|qf_Select_433_values_0.smt2                                                                |  60.000s |19.036MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|int_check_eq_bvshl0_rtl.smt2                                                               |  60.071s |19.048MiB|
|int_check_ne_bvudiv0_ltr_inv_g.smt2                                                        |  60.017s |18.8MiB|
|int_check_bvule_bvashr1_ltr_inv_g.smt2                                                     |  60.004s |19.068MiB|
|int_check_bvult_bvashr0_ltr_inv_g.smt2                                                     |  60.003s |19.072MiB|
|qf_muldivrem_876_values_0.smt2                                                             |  60.003s |19.056MiB|
|int_check_bvslt_bvand_rtl.smt2                                                             |  60.002s |18.808MiB|
|int_check_bvsge_bvurem1_rtl.smt2                                                           |  60.002s |18.888MiB|
|int_check_bvugt_bvlshr1_rtl.smt2                                                           |  60.002s |18.788MiB|
|int_check_bvult_bvlshr1_ltr_inv_g.smt2                                                     |  60.001s |18.768MiB|
|int_check_ne_bvurem0_ltr_inv_g.smt2                                                        |  60.001s |18.904MiB|
|int_check_bvsge_bvashr0_rtl.smt2                                                           |  60.001s |18.916MiB|
|int_check_bvslt_bvshl0_rtl.smt2                                                            |  60.000s |18.844MiB|
|int_check_bvsgt_bvmul_rtl.smt2                                                             |  60.000s |18.856MiB|
|qf_Select_740_values_0.smt2                                                                |  60.000s |18.82MiB|
|qf_AndOrXor_732-2_values_0.smt2                                                            |  60.000s |19.012MiB|
|int_check_bvslt_bvlshr1_ltr_inv_g.smt2                                                     |  60.000s |19.072MiB|
|int_check_bvsge_bvadd_ltr_inv_r.smt2                                                       |  60.000s |18.82MiB|
|int_check_bvsgt_bvashr1_rtl.smt2                                                           |  60.000s |18.868MiB|
|int_check_bvsge_bvurem0_ltr_inv_g.smt2                                                     |  60.000s |18.788MiB|
|qf_Select_433_values_0.smt2                                                                |  60.000s |19.036MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |18.9MiB|18.9MiB|0B| 0.0%|
|00003.smt2                                                                                  |18.38MiB|18.38MiB|0B| 0.0%|
|00005.smt2                                                                                  |18.488MiB|18.488MiB|0B| 0.0%|
|00018.smt2                                                                                  |22.408MiB|22.408MiB|0B| 0.0%|
|00020.smt2                                                                                  |18.892MiB|18.892MiB|0B| 0.0%|
|00035.smt2                                                                                  |18.768MiB|18.768MiB|0B| 0.0%|
|00085.smt2                                                                                  |18.5MiB|18.5MiB|0B| 0.0%|
|00102.smt2                                                                                  |18.764MiB|18.764MiB|0B| 0.0%|
|00104.smt2                                                                                  |19.82MiB|19.82MiB|0B| 0.0%|
|00105.smt2                                                                                  |20.116MiB|20.116MiB|0B| 0.0%|
|00149.smt2                                                                                  |18.892MiB|18.892MiB|0B| 0.0%|
|00194.smt2                                                                                  |19.236MiB|19.236MiB|0B| 0.0%|
|00235.smt2                                                                                  |18.496MiB|18.496MiB|0B| 0.0%|
|00243.smt2                                                                                  |18.476MiB|18.476MiB|0B| 0.0%|
|00247.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00249.smt2                                                                                  |19.456MiB|19.456MiB|0B| 0.0%|
|00251.smt2                                                                                  |19.092MiB|19.092MiB|0B| 0.0%|
|00294.smt2                                                                                  |18.68MiB|18.68MiB|0B| 0.0%|
|00304.smt2                                                                                  |21.024MiB|21.024MiB|0B| 0.0%|
|00314.smt2                                                                                  |19.788MiB|19.788MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |18.9MiB|18.9MiB|0B| 0.0%|
|00003.smt2                                                                                  |18.38MiB|18.38MiB|0B| 0.0%|
|00005.smt2                                                                                  |18.488MiB|18.488MiB|0B| 0.0%|
|00018.smt2                                                                                  |22.408MiB|22.408MiB|0B| 0.0%|
|00020.smt2                                                                                  |18.892MiB|18.892MiB|0B| 0.0%|
|00035.smt2                                                                                  |18.768MiB|18.768MiB|0B| 0.0%|
|00085.smt2                                                                                  |18.5MiB|18.5MiB|0B| 0.0%|
|00102.smt2                                                                                  |18.764MiB|18.764MiB|0B| 0.0%|
|00104.smt2                                                                                  |19.82MiB|19.82MiB|0B| 0.0%|
|00105.smt2                                                                                  |20.116MiB|20.116MiB|0B| 0.0%|
|00149.smt2                                                                                  |18.892MiB|18.892MiB|0B| 0.0%|
|00194.smt2                                                                                  |19.236MiB|19.236MiB|0B| 0.0%|
|00235.smt2                                                                                  |18.496MiB|18.496MiB|0B| 0.0%|
|00243.smt2                                                                                  |18.476MiB|18.476MiB|0B| 0.0%|
|00247.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00249.smt2                                                                                  |19.456MiB|19.456MiB|0B| 0.0%|
|00251.smt2                                                                                  |19.092MiB|19.092MiB|0B| 0.0%|
|00294.smt2                                                                                  |18.68MiB|18.68MiB|0B| 0.0%|
|00304.smt2                                                                                  |21.024MiB|21.024MiB|0B| 0.0%|
|00314.smt2                                                                                  |19.788MiB|19.788MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |18.9MiB|18.9MiB|0B| 0.0%|
|00003.smt2                                                                                  |18.38MiB|18.38MiB|0B| 0.0%|
|00005.smt2                                                                                  |18.488MiB|18.488MiB|0B| 0.0%|
|00018.smt2                                                                                  |22.408MiB|22.408MiB|0B| 0.0%|
|00020.smt2                                                                                  |18.892MiB|18.892MiB|0B| 0.0%|
|00035.smt2                                                                                  |18.768MiB|18.768MiB|0B| 0.0%|
|00085.smt2                                                                                  |18.5MiB|18.5MiB|0B| 0.0%|
|00102.smt2                                                                                  |18.764MiB|18.764MiB|0B| 0.0%|
|00104.smt2                                                                                  |19.82MiB|19.82MiB|0B| 0.0%|
|00105.smt2                                                                                  |20.116MiB|20.116MiB|0B| 0.0%|
|00149.smt2                                                                                  |18.892MiB|18.892MiB|0B| 0.0%|
|00194.smt2                                                                                  |19.236MiB|19.236MiB|0B| 0.0%|
|00235.smt2                                                                                  |18.496MiB|18.496MiB|0B| 0.0%|
|00243.smt2                                                                                  |18.476MiB|18.476MiB|0B| 0.0%|
|00247.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00249.smt2                                                                                  |19.456MiB|19.456MiB|0B| 0.0%|
|00251.smt2                                                                                  |19.092MiB|19.092MiB|0B| 0.0%|
|00294.smt2                                                                                  |18.68MiB|18.68MiB|0B| 0.0%|
|00304.smt2                                                                                  |21.024MiB|21.024MiB|0B| 0.0%|
|00314.smt2                                                                                  |19.788MiB|19.788MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |18.9MiB|18.9MiB|0B| 0.0%|
|00003.smt2                                                                                  |18.38MiB|18.38MiB|0B| 0.0%|
|00005.smt2                                                                                  |18.488MiB|18.488MiB|0B| 0.0%|
|00018.smt2                                                                                  |22.408MiB|22.408MiB|0B| 0.0%|
|00020.smt2                                                                                  |18.892MiB|18.892MiB|0B| 0.0%|
|00035.smt2                                                                                  |18.768MiB|18.768MiB|0B| 0.0%|
|00085.smt2                                                                                  |18.5MiB|18.5MiB|0B| 0.0%|
|00102.smt2                                                                                  |18.764MiB|18.764MiB|0B| 0.0%|
|00104.smt2                                                                                  |19.82MiB|19.82MiB|0B| 0.0%|
|00105.smt2                                                                                  |20.116MiB|20.116MiB|0B| 0.0%|
|00149.smt2                                                                                  |18.892MiB|18.892MiB|0B| 0.0%|
|00194.smt2                                                                                  |19.236MiB|19.236MiB|0B| 0.0%|
|00235.smt2                                                                                  |18.496MiB|18.496MiB|0B| 0.0%|
|00243.smt2                                                                                  |18.476MiB|18.476MiB|0B| 0.0%|
|00247.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00249.smt2                                                                                  |19.456MiB|19.456MiB|0B| 0.0%|
|00251.smt2                                                                                  |19.092MiB|19.092MiB|0B| 0.0%|
|00294.smt2                                                                                  |18.68MiB|18.68MiB|0B| 0.0%|
|00304.smt2                                                                                  |21.024MiB|21.024MiB|0B| 0.0%|
|00314.smt2                                                                                  |19.788MiB|19.788MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|00793.smt2                                                                                 |   0.207s |54.168MiB|
|00413.smt2                                                                                 |   0.487s |35.648MiB|
|00402.smt2                                                                                 |   0.070s |23.184MiB|
|00018.smt2                                                                                 |   0.075s |22.408MiB|
|00304.smt2                                                                                 |   0.139s |21.024MiB|
|00415.smt2                                                                                 |   0.015s |20.564MiB|
|00105.smt2                                                                                 |   0.021s |20.116MiB|
|00428.smt2                                                                                 |   0.021s |20.004MiB|
|00104.smt2                                                                                 |   0.018s |19.82MiB|
|00314.smt2                                                                                 |   0.012s |19.788MiB|
|00379.smt2                                                                                 |   0.012s |19.672MiB|
|00249.smt2                                                                                 |   0.014s |19.456MiB|
|qf_Select_423_values_57.smt2                                                               |   0.011s |19.256MiB|
|00194.smt2                                                                                 |   0.011s |19.236MiB|
|int_check_bvslt_bvashr1_ltr_inv_g.smt2                                                     |  59.999s |19.108MiB|
|int_check_bvsgt_bvudiv0_rtl.smt2                                                           |  59.999s |19.092MiB|
|00251.smt2                                                                                 |   0.011s |19.092MiB|
|int_check_bvsle_bvashr1_ltr_inv_g.smt2                                                     |  59.995s |19.088MiB|
|int_check_bvsle_bvlshr1_ltr_inv_g.smt2                                                     |  59.963s |19.08MiB|
|int_check_bvslt_bvudiv1_rtl.smt2                                                           |  59.989s |19.076MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|00793.smt2                                                                                 |   0.207s |54.168MiB|
|00413.smt2                                                                                 |   0.487s |35.648MiB|
|00402.smt2                                                                                 |   0.070s |23.184MiB|
|00018.smt2                                                                                 |   0.075s |22.408MiB|
|00304.smt2                                                                                 |   0.139s |21.024MiB|
|00415.smt2                                                                                 |   0.015s |20.564MiB|
|00105.smt2                                                                                 |   0.021s |20.116MiB|
|00428.smt2                                                                                 |   0.021s |20.004MiB|
|00104.smt2                                                                                 |   0.018s |19.82MiB|
|00314.smt2                                                                                 |   0.012s |19.788MiB|
|00379.smt2                                                                                 |   0.012s |19.672MiB|
|00249.smt2                                                                                 |   0.014s |19.456MiB|
|qf_Select_423_values_57.smt2                                                               |   0.011s |19.256MiB|
|00194.smt2                                                                                 |   0.011s |19.236MiB|
|int_check_bvslt_bvashr1_ltr_inv_g.smt2                                                     |  59.999s |19.108MiB|
|int_check_bvsgt_bvudiv0_rtl.smt2                                                           |  59.999s |19.092MiB|
|00251.smt2                                                                                 |   0.011s |19.092MiB|
|int_check_bvsle_bvashr1_ltr_inv_g.smt2                                                     |  59.995s |19.088MiB|
|int_check_bvsle_bvlshr1_ltr_inv_g.smt2                                                     |  59.963s |19.08MiB|
|int_check_bvslt_bvudiv1_rtl.smt2                                                           |  59.989s |19.076MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00005.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00018.smt2                                                                                  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00035.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00149.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00304.smt2                                                                                  |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|00324.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00379.smt2                                                                                  |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|00402.smt2                                                                                  |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|00413.smt2                                                                                  |   0.487s  |   0.487s  |   0.000s  | 0.0%|
|00415.smt2                                                                                  |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|00428.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00793.smt2                                                                                  |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|00967.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|01052.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|int_check_bvsge_bvadd_ltr_inv_r.smt2                                                        |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|int_check_bvsge_bvand_ltr_inv_g.smt2                                                        |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|int_check_bvsge_bvand_rtl.smt2                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|int_check_bvsge_bvashr0_ltr_inv_g.smt2                                                      |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|int_check_bvsge_bvashr0_rtl.smt2                                                            |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|int_check_bvsge_bvashr1_ltr_inv_g.smt2                                                      |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|int_check_bvsge_bvlshr0_ltr_inv_r.smt2                                                      |  58.950s  |  58.950s  |   0.000s  | 0.0%|
|int_check_bvsge_bvlshr1_rtl.smt2                                                            |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|int_check_bvsge_bvmul_rtl.smt2                                                              |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|int_check_bvsge_bvnot_ltr_inv_g.smt2                                                        |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|int_check_bvsge_bvor_ltr_inv_g.smt2                                                         |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|int_check_bvsge_bvor_rtl.smt2                                                               |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|int_check_bvsge_bvshl0_ltr_inv_g.smt2                                                       |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|int_check_bvsge_bvshl0_rtl.smt2                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|int_check_bvsge_bvudiv0_rtl.smt2                                                            |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|int_check_bvsge_bvurem0_ltr_inv_g.smt2                                                      |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|int_check_bvsge_bvurem0_rtl.smt2                                                            |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|int_check_bvsge_bvurem1_rtl.smt2                                                            |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvadd_ltr_inv_g.smt2                                                        |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvadd_ltr_inv_r.smt2                                                        |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvand_ltr_inv_g.smt2                                                        |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvand_rtl.smt2                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvashr0_ltr_inv_g.smt2                                                      |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvashr1_rtl.smt2                                                            |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvlshr0_ltr_inv_r.smt2                                                      |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvmul_rtl.smt2                                                              |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvneg_ltr_inv_g.smt2                                                        |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvneg_rtl.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvnot_ltr_inv_g.smt2                                                        |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvnot_rtl.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvor_ltr_inv_g.smt2                                                         |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvor_rtl.smt2                                                               |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvudiv0_rtl.smt2                                                            |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvudiv1_rtl.smt2                                                            |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvurem0_ltr_inv_g.smt2                                                      |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvurem1_ltr_inv_g.smt2                                                      |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|int_check_bvsle_bvadd_ltr_inv_r.smt2                                                        |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|int_check_bvsle_bvand_ltr_inv_g.smt2                                                        |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|int_check_bvsle_bvand_rtl.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|int_check_bvsle_bvashr1_ltr_inv_g.smt2                                                      |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|int_check_bvsle_bvlshr0_rtl.smt2                                                            |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|int_check_bvsle_bvlshr1_ltr_inv_g.smt2                                                      |  59.963s  |  59.963s  |   0.000s  | 0.0%|
|int_check_bvsle_bvlshr1_rtl.smt2                                                            |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|int_check_bvsle_bvneg_ltr_inv_g.smt2                                                        |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|int_check_bvsle_bvnot_ltr_inv_g.smt2                                                        |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|int_check_bvsle_bvor_ltr_inv_g.smt2                                                         |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|int_check_bvsle_bvor_rtl.smt2                                                               |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|int_check_bvsle_bvshl0_rtl.smt2                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|int_check_bvsle_bvshl1_rtl.smt2                                                             |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|int_check_bvsle_bvudiv0_ltr_inv_g.smt2                                                      |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|int_check_bvsle_bvudiv1_rtl.smt2                                                            |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|int_check_bvsle_bvurem0_ltr_inv_g.smt2                                                      |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|int_check_bvsle_bvurem0_rtl.smt2                                                            |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|int_check_bvsle_bvurem1_ltr_inv_r.smt2                                                      |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|int_check_bvsle_bvurem1_rtl.smt2                                                            |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|int_check_bvslt_bvadd_ltr_inv_g.smt2                                                        |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|int_check_bvslt_bvadd_ltr_inv_r.smt2                                                        |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|int_check_bvslt_bvadd_rtl.smt2                                                              |  59.816s  |  59.816s  |   0.000s  | 0.0%|
|int_check_bvslt_bvand_ltr_inv_g.smt2                                                        |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|int_check_bvslt_bvand_rtl.smt2                                                              |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|int_check_bvslt_bvashr1_ltr_inv_g.smt2                                                      |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|int_check_bvslt_bvlshr1_ltr_inv_g.smt2                                                      |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|int_check_bvslt_bvlshr1_rtl.smt2                                                            |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|int_check_bvslt_bvmul_rtl.smt2                                                              |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|int_check_bvslt_bvneg_ltr_inv_g.smt2                                                        |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|int_check_bvslt_bvneg_rtl.smt2                                                              |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|int_check_bvslt_bvnot_ltr_inv_g.smt2                                                        |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|int_check_bvslt_bvnot_rtl.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|int_check_bvslt_bvor_ltr_inv_g.smt2                                                         |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|int_check_bvslt_bvor_rtl.smt2                                                               |  59.911s  |  59.911s  |   0.000s  | 0.0%|
|int_check_bvslt_bvshl0_rtl.smt2                                                             |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|int_check_bvslt_bvshl1_rtl.smt2                                                             |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|int_check_bvslt_bvudiv0_rtl.smt2                                                            |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|int_check_bvslt_bvudiv1_rtl.smt2                                                            |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|int_check_bvslt_bvurem0_ltr_inv_r.smt2                                                      |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|int_check_bvslt_bvurem0_rtl.smt2                                                            |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|int_check_bvslt_bvurem1_ltr_inv_g.smt2                                                      |  59.888s  |  59.888s  |   0.000s  | 0.0%|
|int_check_bvslt_bvurem1_rtl.smt2                                                            |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|int_check_bvuge_bvand_ltr_inv_g.smt2                                                        |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|int_check_bvuge_bvand_rtl.smt2                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|int_check_bvuge_bvashr0_ltr_inv_g.smt2                                                      |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|int_check_bvuge_bvlshr0_ltr_inv_g.smt2                                                      |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|int_check_bvuge_bvlshr0_rtl.smt2                                                            |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|int_check_bvuge_bvlshr1_rtl.smt2                                                            |  59.539s  |  59.539s  |   0.000s  | 0.0%|
|int_check_bvuge_bvmul_rtl.smt2                                                              |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|int_check_bvuge_bvor_ltr_inv_g.smt2                                                         |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|int_check_bvuge_bvudiv0_rtl.smt2                                                            |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|int_check_bvuge_bvurem1_ltr_inv_g.smt2                                                      |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|int_check_bvuge_bvurem1_rtl.smt2                                                            |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|int_check_bvugt_bvand_ltr_inv_g.smt2                                                        |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|int_check_bvugt_bvand_rtl.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|int_check_bvugt_bvlshr0_rtl.smt2                                                            |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|int_check_bvugt_bvlshr1_rtl.smt2                                                            |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|int_check_bvugt_bvmul_rtl.smt2                                                              |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|int_check_bvugt_bvor_ltr_inv_g.smt2                                                         |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|int_check_bvugt_bvor_rtl.smt2                                                               |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|int_check_bvugt_bvshl0_rtl.smt2                                                             |  59.948s  |  59.948s  |   0.000s  | 0.0%|
|int_check_bvule_bvand_ltr_inv_g.smt2                                                        |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|int_check_bvule_bvashr0_ltr_inv_g.smt2                                                      |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|int_check_bvule_bvashr1_ltr_inv_g.smt2                                                      |  60.004s  |  60.004s  |   0.000s  | 0.0%|
|int_check_bvule_bvashr1_rtl.smt2                                                            |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|int_check_bvule_bvlshr0_ltr_inv_g.smt2                                                      |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|int_check_bvule_bvlshr1_ltr_inv_g.smt2                                                      |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|int_check_bvule_bvor_ltr_inv_g.smt2                                                         |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|int_check_bvule_bvor_rtl.smt2                                                               |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|int_check_bvule_bvshl1_ltr_inv_g.smt2                                                       |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|int_check_bvule_bvudiv0_ltr_inv_g.smt2                                                      |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|int_check_bvule_bvudiv0_rtl.smt2                                                            |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|int_check_bvule_bvudiv1_rtl.smt2                                                            |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|int_check_bvult_bvand_ltr_inv_g.smt2                                                        |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|int_check_bvult_bvand_rtl.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|int_check_bvult_bvashr0_ltr_inv_g.smt2                                                      |  60.003s  |  60.003s  |   0.000s  | 0.0%|
|int_check_bvult_bvashr1_ltr_inv_g.smt2                                                      |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|int_check_bvult_bvlshr0_ltr_inv_g.smt2                                                      |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|int_check_bvult_bvlshr1_ltr_inv_g.smt2                                                      |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|int_check_bvult_bvor_ltr_inv_g.smt2                                                         |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|int_check_bvult_bvor_rtl.smt2                                                               |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|int_check_bvult_bvshl1_ltr_inv_g.smt2                                                       |  59.778s  |  59.778s  |   0.000s  | 0.0%|
|int_check_bvult_bvudiv1_ltr_inv_g.smt2                                                      |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|int_check_bvult_bvudiv1_rtl.smt2                                                            |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|int_check_eq_bvand_rtl.smt2                                                                 |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|int_check_eq_bvmul_rtl.smt2                                                                 |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|int_check_eq_bvor_rtl.smt2                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|int_check_eq_bvshl0_rtl.smt2                                                                |  60.071s  |  60.071s  |   0.000s  | 0.0%|
|int_check_eq_bvurem1_ltr_inv_g.smt2                                                         |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|int_check_eq_bvurem1_rtl.smt2                                                               |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|int_check_ne_bvadd_ltr_inv_g.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|int_check_ne_bvadd_ltr_inv_r.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|int_check_ne_bvand_ltr_inv_g.smt2                                                           |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|int_check_ne_bvand_rtl.smt2                                                                 |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|int_check_ne_bvashr1_ltr_inv_r.smt2                                                         |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|int_check_ne_bvashr1_rtl.smt2                                                               |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|int_check_ne_bvlshr0_ltr_inv_g.smt2                                                         |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|int_check_ne_bvlshr0_rtl.smt2                                                               |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|int_check_ne_bvlshr1_ltr_inv_g.smt2                                                         |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|int_check_ne_bvlshr1_rtl.smt2                                                               |  59.961s  |  59.961s  |   0.000s  | 0.0%|
|int_check_ne_bvneg_ltr_inv_g.smt2                                                           |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|int_check_ne_bvnot_ltr_inv_g.smt2                                                           |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|int_check_ne_bvor_ltr_inv_g.smt2                                                            |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|int_check_ne_bvor_rtl.smt2                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|int_check_ne_bvshl0_rtl.smt2                                                                |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|int_check_ne_bvshl1_ltr_inv_g.smt2                                                          |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|int_check_ne_bvudiv0_ltr_inv_g.smt2                                                         |  60.017s  |  60.017s  |   0.000s  | 0.0%|
|int_check_ne_bvurem0_ltr_inv_g.smt2                                                         |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|n0-00001.smt2                                                                               |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AddSub_1040_values_0.smt2                                                                |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AddSub_1043_values_0.smt2                                                                |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AddSub_1202_values_0.smt2                                                                |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AddSub_1295_values_0.smt2                                                                |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AddSub_1560_values_0.smt2                                                                |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AddSub_1564_values_0.smt2                                                                |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AddSub_1599_values_0.smt2                                                                |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|qf_AddSub_1604_values_0.smt2                                                                |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|qf_AddSub_1624_values_0.smt2                                                                |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_1012_values_0.smt2                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AndOrXor_1230_values_0.smt2                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|qf_AndOrXor_1241_values_0.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AndOrXor_1247_values_0.smt2                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AndOrXor_1253_values_0.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AndOrXor_1280_values_0.smt2                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|qf_AndOrXor_1288_values_0.smt2                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|qf_AndOrXor_1294_values_0.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AndOrXor_135_values_0.smt2                                                               |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AndOrXor_144_values_0.smt2                                                               |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_151_values_0.smt2                                                               |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|qf_AndOrXor_1733_values_0.smt2                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|qf_AndOrXor_1795_values_0.smt2                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AndOrXor_1864_values_0.smt2                                                              |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|qf_AndOrXor_1979_values_0.smt2                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|qf_AndOrXor_2008_values_0.smt2                                                              |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|qf_AndOrXor_2052_values_0.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AndOrXor_2063_values_0.smt2                                                              |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|qf_AndOrXor_2113_values_0.smt2                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|qf_AndOrXor_2118_values_0.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AndOrXor_2123_values_0.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AndOrXor_2160_values_0.smt2                                                              |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|qf_AndOrXor_2188_values_0.smt2                                                              |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|qf_AndOrXor_2231_values_0.smt2                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|qf_AndOrXor_2243_values_0.smt2                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_2247_values_0.smt2                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AndOrXor_2263_values_0.smt2                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AndOrXor_2264_values_0.smt2                                                              |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|qf_AndOrXor_2265_values_0.smt2                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AndOrXor_2284_values_0.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AndOrXor_2285_values_0.smt2                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AndOrXor_2297_values_0.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AndOrXor_2367_values_0.smt2                                                              |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|qf_AndOrXor_2416_values_0.smt2                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_2417_values_0.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AndOrXor_2429_values_0.smt2                                                              |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|qf_AndOrXor_2430_values_0.smt2                                                              |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|qf_AndOrXor_2475_values_0.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AndOrXor_2486_values_0.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AndOrXor_2515_values_0.smt2                                                              |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|qf_AndOrXor_2581_values_0.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AndOrXor_2587_values_0.smt2                                                              |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|qf_AndOrXor_2595_values_0.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AndOrXor_2607_values_0.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AndOrXor_2617_values_0.smt2                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AndOrXor_2627_values_0.smt2                                                              |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|qf_AndOrXor_2647_values_0.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AndOrXor_2658_values_0.smt2                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_273_values_7.smt2                                                               |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|qf_AndOrXor_280_values_3.smt2                                                               |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AndOrXor_298_values_0.smt2                                                               |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|qf_AndOrXor_363_values_0.smt2                                                               |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|qf_AndOrXor_364_values_0.smt2                                                               |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|qf_AndOrXor_516_values_0.smt2                                                               |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_523_values_0.smt2                                                               |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|qf_AndOrXor_530_values_0.smt2                                                               |  59.966s  |  59.966s  |   0.000s  | 0.0%|
|qf_AndOrXor_537_values_0.smt2                                                               |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|qf_AndOrXor_698_values_0.smt2                                                               |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|qf_AndOrXor_709_values_0.smt2                                                               |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AndOrXor_716_values_0.smt2                                                               |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AndOrXor_732-1_values_0.smt2                                                             |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|qf_AndOrXor_732-2_values_0.smt2                                                             |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|qf_AndOrXor_745_values_0.smt2                                                               |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|qf_AndOrXor_757_values_0.smt2                                                               |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_819_values_0.smt2                                                               |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|qf_AndOrXor_827_values_0.smt2                                                               |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|qf_AndOrXor_937_values_0.smt2                                                               |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|qf_InstCombineShift239_values_0.smt2                                                        |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_InstCombineShift279_values_0.smt2                                                        |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_InstCombineShift440_values_0.smt2                                                        |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|qf_InstCombineShift476_values_0.smt2                                                        |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|qf_Select_420_values_0.smt2                                                                 |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_Select_423_values_57.smt2                                                                |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|qf_Select_427_values_0.smt2                                                                 |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|qf_Select_430_values_60.smt2                                                                |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|qf_Select_433_values_0.smt2                                                                 |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|qf_Select_576a_values_0.smt2                                                                |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_Select_576b_values_0.smt2                                                                |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_Select_704_values_0.smt2                                                                 |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|qf_Select_740_values_0.smt2                                                                 |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|qf_Select_741_values_0.smt2                                                                 |  59.835s  |  59.835s  |   0.000s  | 0.0%|
|qf_Select_746_values_0.smt2                                                                 |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|qf_Select_747_values_0.smt2                                                                 |  60.000s  |  60.000s  |   0.000s  | 0.0%|
</details>
