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
Job tag: smt-60-qfnia-sat
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 04d0e9492b0066675c75fc5fb1df6b23b79607e5
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" model_validate=true"
Z3 inputs: inputs/QF_UFNIA_SAT
Z3 commit message: set log level of revert repair down to 3

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-60-qfnia-sat
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 04d0e9492b0066675c75fc5fb1df6b23b79607e5
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" model_validate=true"
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
|00003.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00005.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00018.smt2                                                                                  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00035.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00149.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00304.smt2                                                                                  |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.017s  |   0.017s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00005.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00018.smt2                                                                                  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00035.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00149.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00304.smt2                                                                                  |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.017s  |   0.017s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00005.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00018.smt2                                                                                  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00035.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00149.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00304.smt2                                                                                  |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.017s  |   0.017s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00005.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00018.smt2                                                                                  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00035.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00149.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00304.smt2                                                                                  |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.017s  |   0.017s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|int_check_bvslt_bvshl1_rtl.smt2                                                            |   1.175s |23.708MiB|
|int_check_bvslt_bvmul_rtl.smt2                                                             |   0.837s |23.348MiB|
|int_check_bvsge_bvshl0_ltr_inv_g.smt2                                                      |   0.574s |23.62MiB|
|int_check_bvsgt_bvlshr0_ltr_inv_r.smt2                                                     |   0.549s |22.872MiB|
|qf_AndOrXor_2515_values_0.smt2                                                             |   0.361s |21.18MiB|
|int_check_bvsle_bvshl1_rtl.smt2                                                            |   0.301s |20.568MiB|
|int_check_bvsge_bvashr0_rtl.smt2                                                           |   0.272s |21.7MiB|
|int_check_eq_bvshl0_rtl.smt2                                                               |   0.247s |20.28MiB|
|int_check_ne_bvlshr0_ltr_inv_g.smt2                                                        |   0.246s |20.288MiB|
|int_check_bvsgt_bvurem1_ltr_inv_g.smt2                                                     |   0.230s |21.288MiB|
|qf_AddSub_1599_values_0.smt2                                                               |   0.189s |20.844MiB|
|int_check_bvsle_bvlshr0_rtl.smt2                                                           |   0.185s |20.724MiB|
|int_check_bvsgt_bvmul_rtl.smt2                                                             |   0.183s |20.78MiB|
|qf_Select_576a_values_0.smt2                                                               |   0.172s |21.056MiB|
|int_check_bvslt_bvshl0_rtl.smt2                                                            |   0.169s |20.544MiB|
|int_check_bvsgt_bvashr1_rtl.smt2                                                           |   0.165s |21.108MiB|
|qf_Select_576b_values_0.smt2                                                               |   0.144s |20.848MiB|
|int_check_bvugt_bvshl0_rtl.smt2                                                            |   0.134s |20.18MiB|
|qf_AddSub_1564_values_0.smt2                                                               |   0.134s |20.148MiB|
|int_check_eq_bvurem1_ltr_inv_g.smt2                                                        |   0.123s |20.76MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|int_check_bvslt_bvshl1_rtl.smt2                                                            |   1.175s |23.708MiB|
|int_check_bvslt_bvmul_rtl.smt2                                                             |   0.837s |23.348MiB|
|int_check_bvsge_bvshl0_ltr_inv_g.smt2                                                      |   0.574s |23.62MiB|
|int_check_bvsgt_bvlshr0_ltr_inv_r.smt2                                                     |   0.549s |22.872MiB|
|qf_AndOrXor_2515_values_0.smt2                                                             |   0.361s |21.18MiB|
|int_check_bvsle_bvshl1_rtl.smt2                                                            |   0.301s |20.568MiB|
|int_check_bvsge_bvashr0_rtl.smt2                                                           |   0.272s |21.7MiB|
|int_check_eq_bvshl0_rtl.smt2                                                               |   0.247s |20.28MiB|
|int_check_ne_bvlshr0_ltr_inv_g.smt2                                                        |   0.246s |20.288MiB|
|int_check_bvsgt_bvurem1_ltr_inv_g.smt2                                                     |   0.230s |21.288MiB|
|qf_AddSub_1599_values_0.smt2                                                               |   0.189s |20.844MiB|
|int_check_bvsle_bvlshr0_rtl.smt2                                                           |   0.185s |20.724MiB|
|int_check_bvsgt_bvmul_rtl.smt2                                                             |   0.183s |20.78MiB|
|qf_Select_576a_values_0.smt2                                                               |   0.172s |21.056MiB|
|int_check_bvslt_bvshl0_rtl.smt2                                                            |   0.169s |20.544MiB|
|int_check_bvsgt_bvashr1_rtl.smt2                                                           |   0.165s |21.108MiB|
|qf_Select_576b_values_0.smt2                                                               |   0.144s |20.848MiB|
|int_check_bvugt_bvshl0_rtl.smt2                                                            |   0.134s |20.18MiB|
|qf_AddSub_1564_values_0.smt2                                                               |   0.134s |20.148MiB|
|int_check_eq_bvurem1_ltr_inv_g.smt2                                                        |   0.123s |20.76MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |18.984MiB|18.984MiB|0B| 0.0%|
|00003.smt2                                                                                  |18.768MiB|18.768MiB|0B| 0.0%|
|00005.smt2                                                                                  |18.688MiB|18.688MiB|0B| 0.0%|
|00018.smt2                                                                                  |20.024MiB|20.024MiB|0B| 0.0%|
|00020.smt2                                                                                  |18.764MiB|18.764MiB|0B| 0.0%|
|00035.smt2                                                                                  |18.772MiB|18.772MiB|0B| 0.0%|
|00085.smt2                                                                                  |18.876MiB|18.876MiB|0B| 0.0%|
|00102.smt2                                                                                  |18.7MiB|18.7MiB|0B| 0.0%|
|00104.smt2                                                                                  |19.024MiB|19.024MiB|0B| 0.0%|
|00105.smt2                                                                                  |19.004MiB|19.004MiB|0B| 0.0%|
|00149.smt2                                                                                  |18.724MiB|18.724MiB|0B| 0.0%|
|00194.smt2                                                                                  |18.948MiB|18.948MiB|0B| 0.0%|
|00235.smt2                                                                                  |18.768MiB|18.768MiB|0B| 0.0%|
|00243.smt2                                                                                  |18.896MiB|18.896MiB|0B| 0.0%|
|00247.smt2                                                                                  |18.648MiB|18.648MiB|0B| 0.0%|
|00249.smt2                                                                                  |18.924MiB|18.924MiB|0B| 0.0%|
|00251.smt2                                                                                  |18.732MiB|18.732MiB|0B| 0.0%|
|00294.smt2                                                                                  |18.764MiB|18.764MiB|0B| 0.0%|
|00304.smt2                                                                                  |20.56MiB|20.56MiB|0B| 0.0%|
|00314.smt2                                                                                  |19.544MiB|19.544MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |18.984MiB|18.984MiB|0B| 0.0%|
|00003.smt2                                                                                  |18.768MiB|18.768MiB|0B| 0.0%|
|00005.smt2                                                                                  |18.688MiB|18.688MiB|0B| 0.0%|
|00018.smt2                                                                                  |20.024MiB|20.024MiB|0B| 0.0%|
|00020.smt2                                                                                  |18.764MiB|18.764MiB|0B| 0.0%|
|00035.smt2                                                                                  |18.772MiB|18.772MiB|0B| 0.0%|
|00085.smt2                                                                                  |18.876MiB|18.876MiB|0B| 0.0%|
|00102.smt2                                                                                  |18.7MiB|18.7MiB|0B| 0.0%|
|00104.smt2                                                                                  |19.024MiB|19.024MiB|0B| 0.0%|
|00105.smt2                                                                                  |19.004MiB|19.004MiB|0B| 0.0%|
|00149.smt2                                                                                  |18.724MiB|18.724MiB|0B| 0.0%|
|00194.smt2                                                                                  |18.948MiB|18.948MiB|0B| 0.0%|
|00235.smt2                                                                                  |18.768MiB|18.768MiB|0B| 0.0%|
|00243.smt2                                                                                  |18.896MiB|18.896MiB|0B| 0.0%|
|00247.smt2                                                                                  |18.648MiB|18.648MiB|0B| 0.0%|
|00249.smt2                                                                                  |18.924MiB|18.924MiB|0B| 0.0%|
|00251.smt2                                                                                  |18.732MiB|18.732MiB|0B| 0.0%|
|00294.smt2                                                                                  |18.764MiB|18.764MiB|0B| 0.0%|
|00304.smt2                                                                                  |20.56MiB|20.56MiB|0B| 0.0%|
|00314.smt2                                                                                  |19.544MiB|19.544MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |18.984MiB|18.984MiB|0B| 0.0%|
|00003.smt2                                                                                  |18.768MiB|18.768MiB|0B| 0.0%|
|00005.smt2                                                                                  |18.688MiB|18.688MiB|0B| 0.0%|
|00018.smt2                                                                                  |20.024MiB|20.024MiB|0B| 0.0%|
|00020.smt2                                                                                  |18.764MiB|18.764MiB|0B| 0.0%|
|00035.smt2                                                                                  |18.772MiB|18.772MiB|0B| 0.0%|
|00085.smt2                                                                                  |18.876MiB|18.876MiB|0B| 0.0%|
|00102.smt2                                                                                  |18.7MiB|18.7MiB|0B| 0.0%|
|00104.smt2                                                                                  |19.024MiB|19.024MiB|0B| 0.0%|
|00105.smt2                                                                                  |19.004MiB|19.004MiB|0B| 0.0%|
|00149.smt2                                                                                  |18.724MiB|18.724MiB|0B| 0.0%|
|00194.smt2                                                                                  |18.948MiB|18.948MiB|0B| 0.0%|
|00235.smt2                                                                                  |18.768MiB|18.768MiB|0B| 0.0%|
|00243.smt2                                                                                  |18.896MiB|18.896MiB|0B| 0.0%|
|00247.smt2                                                                                  |18.648MiB|18.648MiB|0B| 0.0%|
|00249.smt2                                                                                  |18.924MiB|18.924MiB|0B| 0.0%|
|00251.smt2                                                                                  |18.732MiB|18.732MiB|0B| 0.0%|
|00294.smt2                                                                                  |18.764MiB|18.764MiB|0B| 0.0%|
|00304.smt2                                                                                  |20.56MiB|20.56MiB|0B| 0.0%|
|00314.smt2                                                                                  |19.544MiB|19.544MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |18.984MiB|18.984MiB|0B| 0.0%|
|00003.smt2                                                                                  |18.768MiB|18.768MiB|0B| 0.0%|
|00005.smt2                                                                                  |18.688MiB|18.688MiB|0B| 0.0%|
|00018.smt2                                                                                  |20.024MiB|20.024MiB|0B| 0.0%|
|00020.smt2                                                                                  |18.764MiB|18.764MiB|0B| 0.0%|
|00035.smt2                                                                                  |18.772MiB|18.772MiB|0B| 0.0%|
|00085.smt2                                                                                  |18.876MiB|18.876MiB|0B| 0.0%|
|00102.smt2                                                                                  |18.7MiB|18.7MiB|0B| 0.0%|
|00104.smt2                                                                                  |19.024MiB|19.024MiB|0B| 0.0%|
|00105.smt2                                                                                  |19.004MiB|19.004MiB|0B| 0.0%|
|00149.smt2                                                                                  |18.724MiB|18.724MiB|0B| 0.0%|
|00194.smt2                                                                                  |18.948MiB|18.948MiB|0B| 0.0%|
|00235.smt2                                                                                  |18.768MiB|18.768MiB|0B| 0.0%|
|00243.smt2                                                                                  |18.896MiB|18.896MiB|0B| 0.0%|
|00247.smt2                                                                                  |18.648MiB|18.648MiB|0B| 0.0%|
|00249.smt2                                                                                  |18.924MiB|18.924MiB|0B| 0.0%|
|00251.smt2                                                                                  |18.732MiB|18.732MiB|0B| 0.0%|
|00294.smt2                                                                                  |18.764MiB|18.764MiB|0B| 0.0%|
|00304.smt2                                                                                  |20.56MiB|20.56MiB|0B| 0.0%|
|00314.smt2                                                                                  |19.544MiB|19.544MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|int_check_bvslt_bvshl1_rtl.smt2                                                            |   1.175s |23.708MiB|
|int_check_bvsge_bvshl0_ltr_inv_g.smt2                                                      |   0.574s |23.62MiB|
|int_check_bvslt_bvmul_rtl.smt2                                                             |   0.837s |23.348MiB|
|int_check_bvsgt_bvlshr0_ltr_inv_r.smt2                                                     |   0.549s |22.872MiB|
|00793.smt2                                                                                 |   0.051s |22.424MiB|
|int_check_bvsge_bvashr0_rtl.smt2                                                           |   0.272s |21.7MiB|
|int_check_bvsgt_bvurem1_ltr_inv_g.smt2                                                     |   0.230s |21.288MiB|
|qf_AndOrXor_2515_values_0.smt2                                                             |   0.361s |21.18MiB|
|int_check_bvsgt_bvashr1_rtl.smt2                                                           |   0.165s |21.108MiB|
|qf_Select_576a_values_0.smt2                                                               |   0.172s |21.056MiB|
|qf_Select_576b_values_0.smt2                                                               |   0.144s |20.848MiB|
|qf_AddSub_1599_values_0.smt2                                                               |   0.189s |20.844MiB|
|int_check_bvsgt_bvmul_rtl.smt2                                                             |   0.183s |20.78MiB|
|int_check_eq_bvurem1_ltr_inv_g.smt2                                                        |   0.123s |20.76MiB|
|int_check_bvsle_bvlshr0_rtl.smt2                                                           |   0.185s |20.724MiB|
|qf_InstCombineShift239_values_0.smt2                                                       |   0.110s |20.688MiB|
|int_check_ne_bvashr1_ltr_inv_r.smt2                                                        |   0.081s |20.592MiB|
|int_check_bvslt_bvashr1_ltr_inv_g.smt2                                                     |   0.039s |20.572MiB|
|int_check_bvsle_bvshl1_rtl.smt2                                                            |   0.301s |20.568MiB|
|00304.smt2                                                                                 |   0.024s |20.56MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|int_check_bvslt_bvshl1_rtl.smt2                                                            |   1.175s |23.708MiB|
|int_check_bvsge_bvshl0_ltr_inv_g.smt2                                                      |   0.574s |23.62MiB|
|int_check_bvslt_bvmul_rtl.smt2                                                             |   0.837s |23.348MiB|
|int_check_bvsgt_bvlshr0_ltr_inv_r.smt2                                                     |   0.549s |22.872MiB|
|00793.smt2                                                                                 |   0.051s |22.424MiB|
|int_check_bvsge_bvashr0_rtl.smt2                                                           |   0.272s |21.7MiB|
|int_check_bvsgt_bvurem1_ltr_inv_g.smt2                                                     |   0.230s |21.288MiB|
|qf_AndOrXor_2515_values_0.smt2                                                             |   0.361s |21.18MiB|
|int_check_bvsgt_bvashr1_rtl.smt2                                                           |   0.165s |21.108MiB|
|qf_Select_576a_values_0.smt2                                                               |   0.172s |21.056MiB|
|qf_Select_576b_values_0.smt2                                                               |   0.144s |20.848MiB|
|qf_AddSub_1599_values_0.smt2                                                               |   0.189s |20.844MiB|
|int_check_bvsgt_bvmul_rtl.smt2                                                             |   0.183s |20.78MiB|
|int_check_eq_bvurem1_ltr_inv_g.smt2                                                        |   0.123s |20.76MiB|
|int_check_bvsle_bvlshr0_rtl.smt2                                                           |   0.185s |20.724MiB|
|qf_InstCombineShift239_values_0.smt2                                                       |   0.110s |20.688MiB|
|int_check_ne_bvashr1_ltr_inv_r.smt2                                                        |   0.081s |20.592MiB|
|int_check_bvslt_bvashr1_ltr_inv_g.smt2                                                     |   0.039s |20.572MiB|
|int_check_bvsle_bvshl1_rtl.smt2                                                            |   0.301s |20.568MiB|
|00304.smt2                                                                                 |   0.024s |20.56MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00005.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00018.smt2                                                                                  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00035.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00149.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00304.smt2                                                                                  |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|00324.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00379.smt2                                                                                  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|00402.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00413.smt2                                                                                  |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|00415.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|00428.smt2                                                                                  |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|00793.smt2                                                                                  |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|00967.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|01052.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|int_check_bvsge_bvadd_ltr_inv_r.smt2                                                        |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|int_check_bvsge_bvand_ltr_inv_g.smt2                                                        |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|int_check_bvsge_bvand_rtl.smt2                                                              |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|int_check_bvsge_bvashr0_ltr_inv_g.smt2                                                      |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|int_check_bvsge_bvashr0_rtl.smt2                                                            |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|int_check_bvsge_bvashr1_ltr_inv_g.smt2                                                      |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|int_check_bvsge_bvlshr0_ltr_inv_r.smt2                                                      |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|int_check_bvsge_bvlshr1_rtl.smt2                                                            |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|int_check_bvsge_bvmul_rtl.smt2                                                              |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|int_check_bvsge_bvnot_ltr_inv_g.smt2                                                        |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|int_check_bvsge_bvor_ltr_inv_g.smt2                                                         |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|int_check_bvsge_bvor_rtl.smt2                                                               |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|int_check_bvsge_bvshl0_ltr_inv_g.smt2                                                       |   0.574s  |   0.574s  |   0.000s  | 0.0%|
|int_check_bvsge_bvshl0_rtl.smt2                                                             |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|int_check_bvsge_bvudiv0_rtl.smt2                                                            |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|int_check_bvsge_bvurem0_ltr_inv_g.smt2                                                      |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|int_check_bvsge_bvurem0_rtl.smt2                                                            |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|int_check_bvsge_bvurem1_rtl.smt2                                                            |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvadd_ltr_inv_g.smt2                                                        |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvadd_ltr_inv_r.smt2                                                        |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvand_ltr_inv_g.smt2                                                        |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvand_rtl.smt2                                                              |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvashr0_ltr_inv_g.smt2                                                      |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvashr1_rtl.smt2                                                            |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvlshr0_ltr_inv_r.smt2                                                      |   0.549s  |   0.549s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvmul_rtl.smt2                                                              |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvneg_ltr_inv_g.smt2                                                        |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvneg_rtl.smt2                                                              |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvnot_ltr_inv_g.smt2                                                        |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvnot_rtl.smt2                                                              |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvor_ltr_inv_g.smt2                                                         |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvor_rtl.smt2                                                               |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvudiv0_rtl.smt2                                                            |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvudiv1_rtl.smt2                                                            |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvurem0_ltr_inv_g.smt2                                                      |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvurem1_ltr_inv_g.smt2                                                      |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|int_check_bvsle_bvadd_ltr_inv_r.smt2                                                        |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|int_check_bvsle_bvand_ltr_inv_g.smt2                                                        |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|int_check_bvsle_bvand_rtl.smt2                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|int_check_bvsle_bvashr1_ltr_inv_g.smt2                                                      |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|int_check_bvsle_bvlshr0_rtl.smt2                                                            |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|int_check_bvsle_bvlshr1_ltr_inv_g.smt2                                                      |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|int_check_bvsle_bvlshr1_rtl.smt2                                                            |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|int_check_bvsle_bvneg_ltr_inv_g.smt2                                                        |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|int_check_bvsle_bvnot_ltr_inv_g.smt2                                                        |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|int_check_bvsle_bvor_ltr_inv_g.smt2                                                         |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|int_check_bvsle_bvor_rtl.smt2                                                               |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|int_check_bvsle_bvshl0_rtl.smt2                                                             |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|int_check_bvsle_bvshl1_rtl.smt2                                                             |   0.301s  |   0.301s  |   0.000s  | 0.0%|
|int_check_bvsle_bvudiv0_ltr_inv_g.smt2                                                      |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|int_check_bvsle_bvudiv1_rtl.smt2                                                            |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|int_check_bvsle_bvurem0_ltr_inv_g.smt2                                                      |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|int_check_bvsle_bvurem0_rtl.smt2                                                            |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|int_check_bvsle_bvurem1_ltr_inv_r.smt2                                                      |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|int_check_bvsle_bvurem1_rtl.smt2                                                            |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|int_check_bvslt_bvadd_ltr_inv_g.smt2                                                        |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|int_check_bvslt_bvadd_ltr_inv_r.smt2                                                        |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|int_check_bvslt_bvadd_rtl.smt2                                                              |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|int_check_bvslt_bvand_ltr_inv_g.smt2                                                        |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|int_check_bvslt_bvand_rtl.smt2                                                              |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|int_check_bvslt_bvashr1_ltr_inv_g.smt2                                                      |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|int_check_bvslt_bvlshr1_ltr_inv_g.smt2                                                      |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|int_check_bvslt_bvlshr1_rtl.smt2                                                            |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|int_check_bvslt_bvmul_rtl.smt2                                                              |   0.837s  |   0.837s  |   0.000s  | 0.0%|
|int_check_bvslt_bvneg_ltr_inv_g.smt2                                                        |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|int_check_bvslt_bvneg_rtl.smt2                                                              |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|int_check_bvslt_bvnot_ltr_inv_g.smt2                                                        |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|int_check_bvslt_bvnot_rtl.smt2                                                              |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|int_check_bvslt_bvor_ltr_inv_g.smt2                                                         |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|int_check_bvslt_bvor_rtl.smt2                                                               |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|int_check_bvslt_bvshl0_rtl.smt2                                                             |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|int_check_bvslt_bvshl1_rtl.smt2                                                             |   1.175s  |   1.175s  |   0.000s  | 0.0%|
|int_check_bvslt_bvudiv0_rtl.smt2                                                            |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|int_check_bvslt_bvudiv1_rtl.smt2                                                            |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|int_check_bvslt_bvurem0_ltr_inv_r.smt2                                                      |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|int_check_bvslt_bvurem0_rtl.smt2                                                            |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|int_check_bvslt_bvurem1_ltr_inv_g.smt2                                                      |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|int_check_bvslt_bvurem1_rtl.smt2                                                            |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|int_check_bvuge_bvand_ltr_inv_g.smt2                                                        |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|int_check_bvuge_bvand_rtl.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|int_check_bvuge_bvashr0_ltr_inv_g.smt2                                                      |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|int_check_bvuge_bvlshr0_ltr_inv_g.smt2                                                      |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|int_check_bvuge_bvlshr0_rtl.smt2                                                            |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|int_check_bvuge_bvlshr1_rtl.smt2                                                            |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|int_check_bvuge_bvmul_rtl.smt2                                                              |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|int_check_bvuge_bvor_ltr_inv_g.smt2                                                         |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|int_check_bvuge_bvudiv0_rtl.smt2                                                            |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|int_check_bvuge_bvurem1_ltr_inv_g.smt2                                                      |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|int_check_bvuge_bvurem1_rtl.smt2                                                            |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|int_check_bvugt_bvand_ltr_inv_g.smt2                                                        |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|int_check_bvugt_bvand_rtl.smt2                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|int_check_bvugt_bvlshr0_rtl.smt2                                                            |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|int_check_bvugt_bvlshr1_rtl.smt2                                                            |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|int_check_bvugt_bvmul_rtl.smt2                                                              |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|int_check_bvugt_bvor_ltr_inv_g.smt2                                                         |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|int_check_bvugt_bvor_rtl.smt2                                                               |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|int_check_bvugt_bvshl0_rtl.smt2                                                             |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|int_check_bvule_bvand_ltr_inv_g.smt2                                                        |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|int_check_bvule_bvashr0_ltr_inv_g.smt2                                                      |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|int_check_bvule_bvashr1_ltr_inv_g.smt2                                                      |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|int_check_bvule_bvashr1_rtl.smt2                                                            |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|int_check_bvule_bvlshr0_ltr_inv_g.smt2                                                      |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|int_check_bvule_bvlshr1_ltr_inv_g.smt2                                                      |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|int_check_bvule_bvor_ltr_inv_g.smt2                                                         |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|int_check_bvule_bvor_rtl.smt2                                                               |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|int_check_bvule_bvshl1_ltr_inv_g.smt2                                                       |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|int_check_bvule_bvudiv0_ltr_inv_g.smt2                                                      |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|int_check_bvule_bvudiv0_rtl.smt2                                                            |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|int_check_bvule_bvudiv1_rtl.smt2                                                            |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|int_check_bvult_bvand_ltr_inv_g.smt2                                                        |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|int_check_bvult_bvand_rtl.smt2                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|int_check_bvult_bvashr0_ltr_inv_g.smt2                                                      |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|int_check_bvult_bvashr1_ltr_inv_g.smt2                                                      |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|int_check_bvult_bvlshr0_ltr_inv_g.smt2                                                      |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|int_check_bvult_bvlshr1_ltr_inv_g.smt2                                                      |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|int_check_bvult_bvor_ltr_inv_g.smt2                                                         |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|int_check_bvult_bvor_rtl.smt2                                                               |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|int_check_bvult_bvshl1_ltr_inv_g.smt2                                                       |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|int_check_bvult_bvudiv1_ltr_inv_g.smt2                                                      |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|int_check_bvult_bvudiv1_rtl.smt2                                                            |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|int_check_eq_bvand_rtl.smt2                                                                 |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|int_check_eq_bvmul_rtl.smt2                                                                 |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|int_check_eq_bvor_rtl.smt2                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|int_check_eq_bvshl0_rtl.smt2                                                                |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|int_check_eq_bvurem1_ltr_inv_g.smt2                                                         |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|int_check_eq_bvurem1_rtl.smt2                                                               |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|int_check_ne_bvadd_ltr_inv_g.smt2                                                           |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|int_check_ne_bvadd_ltr_inv_r.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|int_check_ne_bvand_ltr_inv_g.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|int_check_ne_bvand_rtl.smt2                                                                 |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|int_check_ne_bvashr1_ltr_inv_r.smt2                                                         |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|int_check_ne_bvashr1_rtl.smt2                                                               |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|int_check_ne_bvlshr0_ltr_inv_g.smt2                                                         |   0.246s  |   0.246s  |   0.000s  | 0.0%|
|int_check_ne_bvlshr0_rtl.smt2                                                               |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|int_check_ne_bvlshr1_ltr_inv_g.smt2                                                         |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|int_check_ne_bvlshr1_rtl.smt2                                                               |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|int_check_ne_bvneg_ltr_inv_g.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|int_check_ne_bvnot_ltr_inv_g.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|int_check_ne_bvor_ltr_inv_g.smt2                                                            |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|int_check_ne_bvor_rtl.smt2                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|int_check_ne_bvshl0_rtl.smt2                                                                |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|int_check_ne_bvshl1_ltr_inv_g.smt2                                                          |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|int_check_ne_bvudiv0_ltr_inv_g.smt2                                                         |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|int_check_ne_bvurem0_ltr_inv_g.smt2                                                         |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|n0-00001.smt2                                                                               |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AddSub_1040_values_0.smt2                                                                |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|qf_AddSub_1043_values_0.smt2                                                                |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|qf_AddSub_1202_values_0.smt2                                                                |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|qf_AddSub_1295_values_0.smt2                                                                |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|qf_AddSub_1560_values_0.smt2                                                                |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|qf_AddSub_1564_values_0.smt2                                                                |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|qf_AddSub_1599_values_0.smt2                                                                |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|qf_AddSub_1604_values_0.smt2                                                                |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|qf_AddSub_1624_values_0.smt2                                                                |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|qf_AndOrXor_1012_values_0.smt2                                                              |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|qf_AndOrXor_1230_values_0.smt2                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AndOrXor_1241_values_0.smt2                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AndOrXor_1247_values_0.smt2                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_1253_values_0.smt2                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_1280_values_0.smt2                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AndOrXor_1288_values_0.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AndOrXor_1294_values_0.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AndOrXor_135_values_0.smt2                                                               |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_144_values_0.smt2                                                               |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_151_values_0.smt2                                                               |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|qf_AndOrXor_1733_values_0.smt2                                                              |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|qf_AndOrXor_1795_values_0.smt2                                                              |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|qf_AndOrXor_1864_values_0.smt2                                                              |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|qf_AndOrXor_1979_values_0.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AndOrXor_2008_values_0.smt2                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_2052_values_0.smt2                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AndOrXor_2063_values_0.smt2                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AndOrXor_2113_values_0.smt2                                                              |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|qf_AndOrXor_2118_values_0.smt2                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AndOrXor_2123_values_0.smt2                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_2160_values_0.smt2                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AndOrXor_2188_values_0.smt2                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_2231_values_0.smt2                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_2243_values_0.smt2                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_2247_values_0.smt2                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AndOrXor_2263_values_0.smt2                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AndOrXor_2264_values_0.smt2                                                              |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|qf_AndOrXor_2265_values_0.smt2                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_2284_values_0.smt2                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_2285_values_0.smt2                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_2297_values_0.smt2                                                              |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|qf_AndOrXor_2367_values_0.smt2                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_2416_values_0.smt2                                                              |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|qf_AndOrXor_2417_values_0.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AndOrXor_2429_values_0.smt2                                                              |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|qf_AndOrXor_2430_values_0.smt2                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_2475_values_0.smt2                                                              |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|qf_AndOrXor_2486_values_0.smt2                                                              |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_AndOrXor_2515_values_0.smt2                                                              |   0.361s  |   0.361s  |   0.000s  | 0.0%|
|qf_AndOrXor_2581_values_0.smt2                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_2587_values_0.smt2                                                              |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|qf_AndOrXor_2595_values_0.smt2                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_2607_values_0.smt2                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AndOrXor_2617_values_0.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AndOrXor_2627_values_0.smt2                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AndOrXor_2647_values_0.smt2                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_2658_values_0.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AndOrXor_273_values_7.smt2                                                               |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|qf_AndOrXor_280_values_3.smt2                                                               |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|qf_AndOrXor_298_values_0.smt2                                                               |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|qf_AndOrXor_363_values_0.smt2                                                               |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|qf_AndOrXor_364_values_0.smt2                                                               |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|qf_AndOrXor_516_values_0.smt2                                                               |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|qf_AndOrXor_523_values_0.smt2                                                               |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|qf_AndOrXor_530_values_0.smt2                                                               |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|qf_AndOrXor_537_values_0.smt2                                                               |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|qf_AndOrXor_698_values_0.smt2                                                               |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_709_values_0.smt2                                                               |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AndOrXor_716_values_0.smt2                                                               |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AndOrXor_732-1_values_0.smt2                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|qf_AndOrXor_732-2_values_0.smt2                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AndOrXor_745_values_0.smt2                                                               |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AndOrXor_757_values_0.smt2                                                               |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AndOrXor_819_values_0.smt2                                                               |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|qf_AndOrXor_827_values_0.smt2                                                               |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_937_values_0.smt2                                                               |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|qf_InstCombineShift239_values_0.smt2                                                        |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|qf_InstCombineShift279_values_0.smt2                                                        |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|qf_InstCombineShift440_values_0.smt2                                                        |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|qf_InstCombineShift476_values_0.smt2                                                        |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|qf_Select_420_values_0.smt2                                                                 |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|qf_Select_423_values_57.smt2                                                                |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|qf_Select_427_values_0.smt2                                                                 |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|qf_Select_430_values_60.smt2                                                                |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|qf_Select_433_values_0.smt2                                                                 |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|qf_Select_576a_values_0.smt2                                                                |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|qf_Select_576b_values_0.smt2                                                                |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|qf_Select_704_values_0.smt2                                                                 |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|qf_Select_740_values_0.smt2                                                                 |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|qf_Select_741_values_0.smt2                                                                 |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|qf_Select_746_values_0.smt2                                                                 |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|qf_Select_747_values_0.smt2                                                                 |   0.052s  |   0.052s  |   0.000s  | 0.0%|
</details>
