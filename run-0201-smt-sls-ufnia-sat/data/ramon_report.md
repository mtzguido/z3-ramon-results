Comparing data and data


# SUMMARY
- LHS tests = 267
- RHS tests = 267
- LHS success = 266  (99.62546816479401%)
- RHS success = 266  (99.62546816479401%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls-ufnia-sat
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 7fc59b65ad92dce6f06fa889f72d3ee24c10ef28
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_UFNIA_SAT
Z3 commit message: add recursive updates to lookahead

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls-ufnia-sat
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 7fc59b65ad92dce6f06fa889f72d3ee24c10ef28
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_UFNIA_SAT
Z3 commit message: add recursive updates to lookahead

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00005.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00018.smt2                                                                                  |  35.277s  |  35.277s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00035.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|00149.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|00324.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00005.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00018.smt2                                                                                  |  35.277s  |  35.277s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00035.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|00149.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|00324.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00005.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00018.smt2                                                                                  |  35.277s  |  35.277s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00035.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|00149.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|00324.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00005.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00018.smt2                                                                                  |  35.277s  |  35.277s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00035.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|00149.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|00324.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|qf_AddSub_1599_values_0.smt2                                                               |  60.628s |19.072MiB|
|int_check_bvule_bvlshr1_ltr_inv_g.smt2                                                     |  60.042s |18.772MiB|
|int_check_bvsgt_bvlshr0_ltr_inv_r.smt2                                                     |  60.022s |19.056MiB|
|int_check_ne_bvshl1_ltr_inv_g.smt2                                                         |  60.008s |18.788MiB|
|int_check_bvsle_bvlshr0_rtl.smt2                                                           |  60.005s |19.108MiB|
|int_check_bvslt_bvudiv0_rtl.smt2                                                           |  60.003s |18.816MiB|
|int_check_bvsle_bvlshr1_ltr_inv_g.smt2                                                     |  60.003s |18.832MiB|
|int_check_bvult_bvudiv1_ltr_inv_g.smt2                                                     |  60.003s |18.792MiB|
|int_check_bvsgt_bvudiv0_rtl.smt2                                                           |  60.002s |19.068MiB|
|int_check_bvuge_bvmul_rtl.smt2                                                             |  60.002s |20.604MiB|
|qf_Select_704_values_0.smt2                                                                |  60.001s |18.864MiB|
|int_check_bvsge_bvshl0_ltr_inv_g.smt2                                                      |  60.001s |18.84MiB|
|int_check_bvule_bvlshr0_ltr_inv_g.smt2                                                     |  60.001s |20.808MiB|
|int_check_bvule_bvudiv0_ltr_inv_g.smt2                                                     |  60.001s |20.828MiB|
|int_check_bvsgt_bvudiv1_rtl.smt2                                                           |  60.000s |18.864MiB|
|int_check_bvslt_bvlshr1_rtl.smt2                                                           |  60.000s |18.84MiB|
|qf_AndOrXor_1012_values_0.smt2                                                             |  60.000s |19.08MiB|
|int_check_bvslt_bvadd_rtl.smt2                                                             |  60.000s |19.048MiB|
|int_check_bvugt_bvshl0_rtl.smt2                                                            |  60.000s |18.784MiB|
|int_check_bvsgt_bvadd_ltr_inv_g.smt2                                                       |  60.000s |19.104MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|qf_AddSub_1599_values_0.smt2                                                               |  60.628s |19.072MiB|
|int_check_bvule_bvlshr1_ltr_inv_g.smt2                                                     |  60.042s |18.772MiB|
|int_check_bvsgt_bvlshr0_ltr_inv_r.smt2                                                     |  60.022s |19.056MiB|
|int_check_ne_bvshl1_ltr_inv_g.smt2                                                         |  60.008s |18.788MiB|
|int_check_bvsle_bvlshr0_rtl.smt2                                                           |  60.005s |19.108MiB|
|int_check_bvslt_bvudiv0_rtl.smt2                                                           |  60.003s |18.816MiB|
|int_check_bvsle_bvlshr1_ltr_inv_g.smt2                                                     |  60.003s |18.832MiB|
|int_check_bvult_bvudiv1_ltr_inv_g.smt2                                                     |  60.003s |18.792MiB|
|int_check_bvsgt_bvudiv0_rtl.smt2                                                           |  60.002s |19.068MiB|
|int_check_bvuge_bvmul_rtl.smt2                                                             |  60.002s |20.604MiB|
|qf_Select_704_values_0.smt2                                                                |  60.001s |18.864MiB|
|int_check_bvsge_bvshl0_ltr_inv_g.smt2                                                      |  60.001s |18.84MiB|
|int_check_bvule_bvlshr0_ltr_inv_g.smt2                                                     |  60.001s |20.808MiB|
|int_check_bvule_bvudiv0_ltr_inv_g.smt2                                                     |  60.001s |20.828MiB|
|int_check_bvsgt_bvudiv1_rtl.smt2                                                           |  60.000s |18.864MiB|
|int_check_bvslt_bvlshr1_rtl.smt2                                                           |  60.000s |18.84MiB|
|qf_AndOrXor_1012_values_0.smt2                                                             |  60.000s |19.08MiB|
|int_check_bvslt_bvadd_rtl.smt2                                                             |  60.000s |19.048MiB|
|int_check_bvugt_bvshl0_rtl.smt2                                                            |  60.000s |18.784MiB|
|int_check_bvsgt_bvadd_ltr_inv_g.smt2                                                       |  60.000s |19.104MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |18.968MiB|18.968MiB|0B| 0.0%|
|00003.smt2                                                                                  |18.528MiB|18.528MiB|0B| 0.0%|
|00005.smt2                                                                                  |18.836MiB|18.836MiB|0B| 0.0%|
|00018.smt2                                                                                  |22.76MiB|22.76MiB|0B| 0.0%|
|00020.smt2                                                                                  |18.764MiB|18.764MiB|0B| 0.0%|
|00035.smt2                                                                                  |19.088MiB|19.088MiB|0B| 0.0%|
|00085.smt2                                                                                  |18.612MiB|18.612MiB|0B| 0.0%|
|00102.smt2                                                                                  |18.764MiB|18.764MiB|0B| 0.0%|
|00104.smt2                                                                                  |18.992MiB|18.992MiB|0B| 0.0%|
|00105.smt2                                                                                  |19.028MiB|19.028MiB|0B| 0.0%|
|00149.smt2                                                                                  |18.996MiB|18.996MiB|0B| 0.0%|
|00194.smt2                                                                                  |19.02MiB|19.02MiB|0B| 0.0%|
|00235.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00243.smt2                                                                                  |18.764MiB|18.764MiB|0B| 0.0%|
|00247.smt2                                                                                  |18.456MiB|18.456MiB|0B| 0.0%|
|00249.smt2                                                                                  |18.784MiB|18.784MiB|0B| 0.0%|
|00251.smt2                                                                                  |18.976MiB|18.976MiB|0B| 0.0%|
|00294.smt2                                                                                  |18.996MiB|18.996MiB|0B| 0.0%|
|00314.smt2                                                                                  |19.28MiB|19.28MiB|0B| 0.0%|
|00324.smt2                                                                                  |18.764MiB|18.764MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |18.968MiB|18.968MiB|0B| 0.0%|
|00003.smt2                                                                                  |18.528MiB|18.528MiB|0B| 0.0%|
|00005.smt2                                                                                  |18.836MiB|18.836MiB|0B| 0.0%|
|00018.smt2                                                                                  |22.76MiB|22.76MiB|0B| 0.0%|
|00020.smt2                                                                                  |18.764MiB|18.764MiB|0B| 0.0%|
|00035.smt2                                                                                  |19.088MiB|19.088MiB|0B| 0.0%|
|00085.smt2                                                                                  |18.612MiB|18.612MiB|0B| 0.0%|
|00102.smt2                                                                                  |18.764MiB|18.764MiB|0B| 0.0%|
|00104.smt2                                                                                  |18.992MiB|18.992MiB|0B| 0.0%|
|00105.smt2                                                                                  |19.028MiB|19.028MiB|0B| 0.0%|
|00149.smt2                                                                                  |18.996MiB|18.996MiB|0B| 0.0%|
|00194.smt2                                                                                  |19.02MiB|19.02MiB|0B| 0.0%|
|00235.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00243.smt2                                                                                  |18.764MiB|18.764MiB|0B| 0.0%|
|00247.smt2                                                                                  |18.456MiB|18.456MiB|0B| 0.0%|
|00249.smt2                                                                                  |18.784MiB|18.784MiB|0B| 0.0%|
|00251.smt2                                                                                  |18.976MiB|18.976MiB|0B| 0.0%|
|00294.smt2                                                                                  |18.996MiB|18.996MiB|0B| 0.0%|
|00314.smt2                                                                                  |19.28MiB|19.28MiB|0B| 0.0%|
|00324.smt2                                                                                  |18.764MiB|18.764MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |18.968MiB|18.968MiB|0B| 0.0%|
|00003.smt2                                                                                  |18.528MiB|18.528MiB|0B| 0.0%|
|00005.smt2                                                                                  |18.836MiB|18.836MiB|0B| 0.0%|
|00018.smt2                                                                                  |22.76MiB|22.76MiB|0B| 0.0%|
|00020.smt2                                                                                  |18.764MiB|18.764MiB|0B| 0.0%|
|00035.smt2                                                                                  |19.088MiB|19.088MiB|0B| 0.0%|
|00085.smt2                                                                                  |18.612MiB|18.612MiB|0B| 0.0%|
|00102.smt2                                                                                  |18.764MiB|18.764MiB|0B| 0.0%|
|00104.smt2                                                                                  |18.992MiB|18.992MiB|0B| 0.0%|
|00105.smt2                                                                                  |19.028MiB|19.028MiB|0B| 0.0%|
|00149.smt2                                                                                  |18.996MiB|18.996MiB|0B| 0.0%|
|00194.smt2                                                                                  |19.02MiB|19.02MiB|0B| 0.0%|
|00235.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00243.smt2                                                                                  |18.764MiB|18.764MiB|0B| 0.0%|
|00247.smt2                                                                                  |18.456MiB|18.456MiB|0B| 0.0%|
|00249.smt2                                                                                  |18.784MiB|18.784MiB|0B| 0.0%|
|00251.smt2                                                                                  |18.976MiB|18.976MiB|0B| 0.0%|
|00294.smt2                                                                                  |18.996MiB|18.996MiB|0B| 0.0%|
|00314.smt2                                                                                  |19.28MiB|19.28MiB|0B| 0.0%|
|00324.smt2                                                                                  |18.764MiB|18.764MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |18.968MiB|18.968MiB|0B| 0.0%|
|00003.smt2                                                                                  |18.528MiB|18.528MiB|0B| 0.0%|
|00005.smt2                                                                                  |18.836MiB|18.836MiB|0B| 0.0%|
|00018.smt2                                                                                  |22.76MiB|22.76MiB|0B| 0.0%|
|00020.smt2                                                                                  |18.764MiB|18.764MiB|0B| 0.0%|
|00035.smt2                                                                                  |19.088MiB|19.088MiB|0B| 0.0%|
|00085.smt2                                                                                  |18.612MiB|18.612MiB|0B| 0.0%|
|00102.smt2                                                                                  |18.764MiB|18.764MiB|0B| 0.0%|
|00104.smt2                                                                                  |18.992MiB|18.992MiB|0B| 0.0%|
|00105.smt2                                                                                  |19.028MiB|19.028MiB|0B| 0.0%|
|00149.smt2                                                                                  |18.996MiB|18.996MiB|0B| 0.0%|
|00194.smt2                                                                                  |19.02MiB|19.02MiB|0B| 0.0%|
|00235.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00243.smt2                                                                                  |18.764MiB|18.764MiB|0B| 0.0%|
|00247.smt2                                                                                  |18.456MiB|18.456MiB|0B| 0.0%|
|00249.smt2                                                                                  |18.784MiB|18.784MiB|0B| 0.0%|
|00251.smt2                                                                                  |18.976MiB|18.976MiB|0B| 0.0%|
|00294.smt2                                                                                  |18.996MiB|18.996MiB|0B| 0.0%|
|00314.smt2                                                                                  |19.28MiB|19.28MiB|0B| 0.0%|
|00324.smt2                                                                                  |18.764MiB|18.764MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|00793.smt2                                                                                 |   0.039s |23.188MiB|
|00018.smt2                                                                                 |  35.277s |22.76MiB|
|int_check_bvule_bvudiv0_ltr_inv_g.smt2                                                     |  60.001s |20.828MiB|
|int_check_bvule_bvlshr0_ltr_inv_g.smt2                                                     |  60.001s |20.808MiB|
|qf_AndOrXor_298_values_0.smt2                                                              |  59.999s |20.668MiB|
|int_check_bvsle_bvurem1_rtl.smt2                                                           |  59.983s |20.628MiB|
|int_check_bvsge_bvand_ltr_inv_g.smt2                                                       |  59.998s |20.612MiB|
|int_check_bvuge_bvashr0_ltr_inv_g.smt2                                                     |  59.928s |20.612MiB|
|int_check_bvsge_bvadd_ltr_inv_r.smt2                                                       |  60.000s |20.608MiB|
|int_check_bvslt_bvand_rtl.smt2                                                             |  59.964s |20.608MiB|
|int_check_bvuge_bvmul_rtl.smt2                                                             |  60.002s |20.604MiB|
|int_check_ne_bvurem0_ltr_inv_g.smt2                                                        |  59.991s |20.6MiB|
|int_check_ne_bvudiv0_ltr_inv_g.smt2                                                        |  59.974s |20.6MiB|
|int_check_bvsle_bvand_rtl.smt2                                                             |  59.984s |20.576MiB|
|int_check_ne_bvlshr0_rtl.smt2                                                              |  59.996s |20.572MiB|
|int_check_bvult_bvshl1_ltr_inv_g.smt2                                                      |  59.767s |20.568MiB|
|qf_AndOrXor_1241_values_0.smt2                                                             |  59.976s |20.544MiB|
|int_check_ne_bvnot_ltr_inv_g.smt2                                                          |  59.984s |20.536MiB|
|00413.smt2                                                                                 |   3.270s |20.488MiB|
|00379.smt2                                                                                 |   0.009s |20.372MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|00793.smt2                                                                                 |   0.039s |23.188MiB|
|00018.smt2                                                                                 |  35.277s |22.76MiB|
|int_check_bvule_bvudiv0_ltr_inv_g.smt2                                                     |  60.001s |20.828MiB|
|int_check_bvule_bvlshr0_ltr_inv_g.smt2                                                     |  60.001s |20.808MiB|
|qf_AndOrXor_298_values_0.smt2                                                              |  59.999s |20.668MiB|
|int_check_bvsle_bvurem1_rtl.smt2                                                           |  59.983s |20.628MiB|
|int_check_bvsge_bvand_ltr_inv_g.smt2                                                       |  59.998s |20.612MiB|
|int_check_bvuge_bvashr0_ltr_inv_g.smt2                                                     |  59.928s |20.612MiB|
|int_check_bvsge_bvadd_ltr_inv_r.smt2                                                       |  60.000s |20.608MiB|
|int_check_bvslt_bvand_rtl.smt2                                                             |  59.964s |20.608MiB|
|int_check_bvuge_bvmul_rtl.smt2                                                             |  60.002s |20.604MiB|
|int_check_ne_bvurem0_ltr_inv_g.smt2                                                        |  59.991s |20.6MiB|
|int_check_ne_bvudiv0_ltr_inv_g.smt2                                                        |  59.974s |20.6MiB|
|int_check_bvsle_bvand_rtl.smt2                                                             |  59.984s |20.576MiB|
|int_check_ne_bvlshr0_rtl.smt2                                                              |  59.996s |20.572MiB|
|int_check_bvult_bvshl1_ltr_inv_g.smt2                                                      |  59.767s |20.568MiB|
|qf_AndOrXor_1241_values_0.smt2                                                             |  59.976s |20.544MiB|
|int_check_ne_bvnot_ltr_inv_g.smt2                                                          |  59.984s |20.536MiB|
|00413.smt2                                                                                 |   3.270s |20.488MiB|
|00379.smt2                                                                                 |   0.009s |20.372MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00005.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00018.smt2                                                                                  |  35.277s  |  35.277s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00035.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|00149.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.005s  |   0.005s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|00324.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|00379.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00402.smt2                                                                                  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|00413.smt2                                                                                  |   3.270s  |   3.270s  |   0.000s  | 0.0%|
|00415.smt2                                                                                  |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|00428.smt2                                                                                  |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|00793.smt2                                                                                  |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|00967.smt2                                                                                  |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|01052.smt2                                                                                  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|int_check_bvsge_bvadd_ltr_inv_r.smt2                                                        |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|int_check_bvsge_bvand_ltr_inv_g.smt2                                                        |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|int_check_bvsge_bvand_rtl.smt2                                                              |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|int_check_bvsge_bvashr0_ltr_inv_g.smt2                                                      |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|int_check_bvsge_bvashr0_rtl.smt2                                                            |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|int_check_bvsge_bvashr1_ltr_inv_g.smt2                                                      |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|int_check_bvsge_bvlshr0_ltr_inv_r.smt2                                                      |  59.766s  |  59.766s  |   0.000s  | 0.0%|
|int_check_bvsge_bvlshr1_rtl.smt2                                                            |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|int_check_bvsge_bvmul_rtl.smt2                                                              |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|int_check_bvsge_bvnot_ltr_inv_g.smt2                                                        |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|int_check_bvsge_bvor_ltr_inv_g.smt2                                                         |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|int_check_bvsge_bvor_rtl.smt2                                                               |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|int_check_bvsge_bvshl0_ltr_inv_g.smt2                                                       |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|int_check_bvsge_bvshl0_rtl.smt2                                                             |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|int_check_bvsge_bvudiv0_rtl.smt2                                                            |  59.930s  |  59.930s  |   0.000s  | 0.0%|
|int_check_bvsge_bvurem0_ltr_inv_g.smt2                                                      |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|int_check_bvsge_bvurem0_rtl.smt2                                                            |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|int_check_bvsge_bvurem1_rtl.smt2                                                            |  59.987s  |  59.987s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvadd_ltr_inv_g.smt2                                                        |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvadd_ltr_inv_r.smt2                                                        |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvand_ltr_inv_g.smt2                                                        |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvand_rtl.smt2                                                              |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvashr0_ltr_inv_g.smt2                                                      |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvashr1_rtl.smt2                                                            |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvlshr0_ltr_inv_r.smt2                                                      |  60.022s  |  60.022s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvmul_rtl.smt2                                                              |  59.972s  |  59.972s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvneg_ltr_inv_g.smt2                                                        |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvneg_rtl.smt2                                                              |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvnot_ltr_inv_g.smt2                                                        |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvnot_rtl.smt2                                                              |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvor_ltr_inv_g.smt2                                                         |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvor_rtl.smt2                                                               |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvudiv0_rtl.smt2                                                            |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvudiv1_rtl.smt2                                                            |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvurem0_ltr_inv_g.smt2                                                      |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvurem1_ltr_inv_g.smt2                                                      |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|int_check_bvsle_bvadd_ltr_inv_r.smt2                                                        |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|int_check_bvsle_bvand_ltr_inv_g.smt2                                                        |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|int_check_bvsle_bvand_rtl.smt2                                                              |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|int_check_bvsle_bvashr1_ltr_inv_g.smt2                                                      |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|int_check_bvsle_bvlshr0_rtl.smt2                                                            |  60.005s  |  60.005s  |   0.000s  | 0.0%|
|int_check_bvsle_bvlshr1_ltr_inv_g.smt2                                                      |  60.003s  |  60.003s  |   0.000s  | 0.0%|
|int_check_bvsle_bvlshr1_rtl.smt2                                                            |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|int_check_bvsle_bvneg_ltr_inv_g.smt2                                                        |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|int_check_bvsle_bvnot_ltr_inv_g.smt2                                                        |  59.963s  |  59.963s  |   0.000s  | 0.0%|
|int_check_bvsle_bvor_ltr_inv_g.smt2                                                         |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|int_check_bvsle_bvor_rtl.smt2                                                               |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|int_check_bvsle_bvshl0_rtl.smt2                                                             |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|int_check_bvsle_bvshl1_rtl.smt2                                                             |   1.208s  |   1.208s  |   0.000s  | 0.0%|
|int_check_bvsle_bvudiv0_ltr_inv_g.smt2                                                      |  15.136s  |  15.136s  |   0.000s  | 0.0%|
|int_check_bvsle_bvudiv1_rtl.smt2                                                            |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|int_check_bvsle_bvurem0_ltr_inv_g.smt2                                                      |   0.364s  |   0.364s  |   0.000s  | 0.0%|
|int_check_bvsle_bvurem0_rtl.smt2                                                            |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|int_check_bvsle_bvurem1_ltr_inv_r.smt2                                                      |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|int_check_bvsle_bvurem1_rtl.smt2                                                            |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|int_check_bvslt_bvadd_ltr_inv_g.smt2                                                        |   0.295s  |   0.295s  |   0.000s  | 0.0%|
|int_check_bvslt_bvadd_ltr_inv_r.smt2                                                        |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|int_check_bvslt_bvadd_rtl.smt2                                                              |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|int_check_bvslt_bvand_ltr_inv_g.smt2                                                        |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|int_check_bvslt_bvand_rtl.smt2                                                              |  59.964s  |  59.964s  |   0.000s  | 0.0%|
|int_check_bvslt_bvashr1_ltr_inv_g.smt2                                                      |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|int_check_bvslt_bvlshr1_ltr_inv_g.smt2                                                      |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|int_check_bvslt_bvlshr1_rtl.smt2                                                            |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|int_check_bvslt_bvmul_rtl.smt2                                                              |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|int_check_bvslt_bvneg_ltr_inv_g.smt2                                                        |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|int_check_bvslt_bvneg_rtl.smt2                                                              |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|int_check_bvslt_bvnot_ltr_inv_g.smt2                                                        |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|int_check_bvslt_bvnot_rtl.smt2                                                              |  59.916s  |  59.916s  |   0.000s  | 0.0%|
|int_check_bvslt_bvor_ltr_inv_g.smt2                                                         |   0.328s  |   0.328s  |   0.000s  | 0.0%|
|int_check_bvslt_bvor_rtl.smt2                                                               |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|int_check_bvslt_bvshl0_rtl.smt2                                                             |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|int_check_bvslt_bvshl1_rtl.smt2                                                             |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|int_check_bvslt_bvudiv0_rtl.smt2                                                            |  60.003s  |  60.003s  |   0.000s  | 0.0%|
|int_check_bvslt_bvudiv1_rtl.smt2                                                            |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|int_check_bvslt_bvurem0_ltr_inv_r.smt2                                                      |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|int_check_bvslt_bvurem0_rtl.smt2                                                            |  59.905s  |  59.905s  |   0.000s  | 0.0%|
|int_check_bvslt_bvurem1_ltr_inv_g.smt2                                                      |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|int_check_bvslt_bvurem1_rtl.smt2                                                            |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|int_check_bvuge_bvand_ltr_inv_g.smt2                                                        |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|int_check_bvuge_bvand_rtl.smt2                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|int_check_bvuge_bvashr0_ltr_inv_g.smt2                                                      |  59.928s  |  59.928s  |   0.000s  | 0.0%|
|int_check_bvuge_bvlshr0_ltr_inv_g.smt2                                                      |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|int_check_bvuge_bvlshr0_rtl.smt2                                                            |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|int_check_bvuge_bvlshr1_rtl.smt2                                                            |  59.510s  |  59.510s  |   0.000s  | 0.0%|
|int_check_bvuge_bvmul_rtl.smt2                                                              |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|int_check_bvuge_bvor_ltr_inv_g.smt2                                                         |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|int_check_bvuge_bvudiv0_rtl.smt2                                                            |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|int_check_bvuge_bvurem1_ltr_inv_g.smt2                                                      |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|int_check_bvuge_bvurem1_rtl.smt2                                                            |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|int_check_bvugt_bvand_ltr_inv_g.smt2                                                        |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|int_check_bvugt_bvand_rtl.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|int_check_bvugt_bvlshr0_rtl.smt2                                                            |  59.915s  |  59.915s  |   0.000s  | 0.0%|
|int_check_bvugt_bvlshr1_rtl.smt2                                                            |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|int_check_bvugt_bvmul_rtl.smt2                                                              |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|int_check_bvugt_bvor_ltr_inv_g.smt2                                                         |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|int_check_bvugt_bvor_rtl.smt2                                                               |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|int_check_bvugt_bvshl0_rtl.smt2                                                             |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|int_check_bvule_bvand_ltr_inv_g.smt2                                                        |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|int_check_bvule_bvashr0_ltr_inv_g.smt2                                                      |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|int_check_bvule_bvashr1_ltr_inv_g.smt2                                                      |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|int_check_bvule_bvashr1_rtl.smt2                                                            |  59.874s  |  59.874s  |   0.000s  | 0.0%|
|int_check_bvule_bvlshr0_ltr_inv_g.smt2                                                      |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|int_check_bvule_bvlshr1_ltr_inv_g.smt2                                                      |  60.042s  |  60.042s  |   0.000s  | 0.0%|
|int_check_bvule_bvor_ltr_inv_g.smt2                                                         |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|int_check_bvule_bvor_rtl.smt2                                                               |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|int_check_bvule_bvshl1_ltr_inv_g.smt2                                                       |  59.442s  |  59.442s  |   0.000s  | 0.0%|
|int_check_bvule_bvudiv0_ltr_inv_g.smt2                                                      |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|int_check_bvule_bvudiv0_rtl.smt2                                                            |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|int_check_bvule_bvudiv1_rtl.smt2                                                            |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|int_check_bvult_bvand_ltr_inv_g.smt2                                                        |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|int_check_bvult_bvand_rtl.smt2                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|int_check_bvult_bvashr0_ltr_inv_g.smt2                                                      |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|int_check_bvult_bvashr1_ltr_inv_g.smt2                                                      |   0.285s  |   0.285s  |   0.000s  | 0.0%|
|int_check_bvult_bvlshr0_ltr_inv_g.smt2                                                      |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|int_check_bvult_bvlshr1_ltr_inv_g.smt2                                                      |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|int_check_bvult_bvor_ltr_inv_g.smt2                                                         |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|int_check_bvult_bvor_rtl.smt2                                                               |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|int_check_bvult_bvshl1_ltr_inv_g.smt2                                                       |  59.767s  |  59.767s  |   0.000s  | 0.0%|
|int_check_bvult_bvudiv1_ltr_inv_g.smt2                                                      |  60.003s  |  60.003s  |   0.000s  | 0.0%|
|int_check_bvult_bvudiv1_rtl.smt2                                                            |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|int_check_eq_bvand_rtl.smt2                                                                 |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|int_check_eq_bvmul_rtl.smt2                                                                 |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|int_check_eq_bvor_rtl.smt2                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|int_check_eq_bvshl0_rtl.smt2                                                                |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|int_check_eq_bvurem1_ltr_inv_g.smt2                                                         |   0.405s  |   0.405s  |   0.000s  | 0.0%|
|int_check_eq_bvurem1_rtl.smt2                                                               |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|int_check_ne_bvadd_ltr_inv_g.smt2                                                           |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|int_check_ne_bvadd_ltr_inv_r.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|int_check_ne_bvand_ltr_inv_g.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|int_check_ne_bvand_rtl.smt2                                                                 |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|int_check_ne_bvashr1_ltr_inv_r.smt2                                                         |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|int_check_ne_bvashr1_rtl.smt2                                                               |   9.114s  |   9.114s  |   0.000s  | 0.0%|
|int_check_ne_bvlshr0_ltr_inv_g.smt2                                                         |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|int_check_ne_bvlshr0_rtl.smt2                                                               |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|int_check_ne_bvlshr1_ltr_inv_g.smt2                                                         |   0.551s  |   0.551s  |   0.000s  | 0.0%|
|int_check_ne_bvlshr1_rtl.smt2                                                               |  59.823s  |  59.823s  |   0.000s  | 0.0%|
|int_check_ne_bvneg_ltr_inv_g.smt2                                                           |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|int_check_ne_bvnot_ltr_inv_g.smt2                                                           |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|int_check_ne_bvor_ltr_inv_g.smt2                                                            |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|int_check_ne_bvor_rtl.smt2                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|int_check_ne_bvshl0_rtl.smt2                                                                |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|int_check_ne_bvshl1_ltr_inv_g.smt2                                                          |  60.008s  |  60.008s  |   0.000s  | 0.0%|
|int_check_ne_bvudiv0_ltr_inv_g.smt2                                                         |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|int_check_ne_bvurem0_ltr_inv_g.smt2                                                         |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|n0-00001.smt2                                                                               |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|qf_AddSub_1040_values_0.smt2                                                                |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|qf_AddSub_1043_values_0.smt2                                                                |  59.867s  |  59.867s  |   0.000s  | 0.0%|
|qf_AddSub_1202_values_0.smt2                                                                |  59.971s  |  59.971s  |   0.000s  | 0.0%|
|qf_AddSub_1295_values_0.smt2                                                                |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_AddSub_1560_values_0.smt2                                                                |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|qf_AddSub_1564_values_0.smt2                                                                |  59.895s  |  59.895s  |   0.000s  | 0.0%|
|qf_AddSub_1599_values_0.smt2                                                                |  60.628s  |  60.628s  |   0.000s  | 0.0%|
|qf_AddSub_1604_values_0.smt2                                                                |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|qf_AddSub_1624_values_0.smt2                                                                |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|qf_AndOrXor_1012_values_0.smt2                                                              |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|qf_AndOrXor_1230_values_0.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AndOrXor_1241_values_0.smt2                                                              |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|qf_AndOrXor_1247_values_0.smt2                                                              |  59.958s  |  59.958s  |   0.000s  | 0.0%|
|qf_AndOrXor_1253_values_0.smt2                                                              |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|qf_AndOrXor_1280_values_0.smt2                                                              |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|qf_AndOrXor_1288_values_0.smt2                                                              |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|qf_AndOrXor_1294_values_0.smt2                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AndOrXor_135_values_0.smt2                                                               |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|qf_AndOrXor_144_values_0.smt2                                                               |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|qf_AndOrXor_151_values_0.smt2                                                               |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|qf_AndOrXor_1733_values_0.smt2                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_1795_values_0.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AndOrXor_1864_values_0.smt2                                                              |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|qf_AndOrXor_1979_values_0.smt2                                                              |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|qf_AndOrXor_2008_values_0.smt2                                                              |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|qf_AndOrXor_2052_values_0.smt2                                                              |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|qf_AndOrXor_2063_values_0.smt2                                                              |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|qf_AndOrXor_2113_values_0.smt2                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_2118_values_0.smt2                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AndOrXor_2123_values_0.smt2                                                              |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|qf_AndOrXor_2160_values_0.smt2                                                              |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|qf_AndOrXor_2188_values_0.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AndOrXor_2231_values_0.smt2                                                              |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|qf_AndOrXor_2243_values_0.smt2                                                              |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|qf_AndOrXor_2247_values_0.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AndOrXor_2263_values_0.smt2                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AndOrXor_2264_values_0.smt2                                                              |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|qf_AndOrXor_2265_values_0.smt2                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AndOrXor_2284_values_0.smt2                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_2285_values_0.smt2                                                              |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|qf_AndOrXor_2297_values_0.smt2                                                              |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|qf_AndOrXor_2367_values_0.smt2                                                              |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|qf_AndOrXor_2416_values_0.smt2                                                              |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|qf_AndOrXor_2417_values_0.smt2                                                              |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|qf_AndOrXor_2429_values_0.smt2                                                              |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_AndOrXor_2430_values_0.smt2                                                              |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|qf_AndOrXor_2475_values_0.smt2                                                              |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|qf_AndOrXor_2486_values_0.smt2                                                              |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|qf_AndOrXor_2515_values_0.smt2                                                              |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|qf_AndOrXor_2581_values_0.smt2                                                              |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_AndOrXor_2587_values_0.smt2                                                              |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|qf_AndOrXor_2595_values_0.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AndOrXor_2607_values_0.smt2                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_2617_values_0.smt2                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AndOrXor_2627_values_0.smt2                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_2647_values_0.smt2                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_2658_values_0.smt2                                                              |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|qf_AndOrXor_273_values_7.smt2                                                               |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|qf_AndOrXor_280_values_3.smt2                                                               |  59.973s  |  59.973s  |   0.000s  | 0.0%|
|qf_AndOrXor_298_values_0.smt2                                                               |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|qf_AndOrXor_363_values_0.smt2                                                               |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|qf_AndOrXor_364_values_0.smt2                                                               |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|qf_AndOrXor_516_values_0.smt2                                                               |   3.274s  |   3.274s  |   0.000s  | 0.0%|
|qf_AndOrXor_523_values_0.smt2                                                               |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|qf_AndOrXor_530_values_0.smt2                                                               |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|qf_AndOrXor_537_values_0.smt2                                                               |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|qf_AndOrXor_698_values_0.smt2                                                               |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|qf_AndOrXor_709_values_0.smt2                                                               |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_AndOrXor_716_values_0.smt2                                                               |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|qf_AndOrXor_732-1_values_0.smt2                                                             |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|qf_AndOrXor_732-2_values_0.smt2                                                             |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|qf_AndOrXor_745_values_0.smt2                                                               |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|qf_AndOrXor_757_values_0.smt2                                                               |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|qf_AndOrXor_819_values_0.smt2                                                               |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|qf_AndOrXor_827_values_0.smt2                                                               |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_AndOrXor_937_values_0.smt2                                                               |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|qf_InstCombineShift239_values_0.smt2                                                        |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|qf_InstCombineShift279_values_0.smt2                                                        |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|qf_InstCombineShift440_values_0.smt2                                                        |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|qf_InstCombineShift476_values_0.smt2                                                        |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|qf_Select_420_values_0.smt2                                                                 |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|qf_Select_423_values_57.smt2                                                                |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|qf_Select_427_values_0.smt2                                                                 |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|qf_Select_430_values_60.smt2                                                                |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|qf_Select_433_values_0.smt2                                                                 |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|qf_Select_576a_values_0.smt2                                                                |   0.838s  |   0.838s  |   0.000s  | 0.0%|
|qf_Select_576b_values_0.smt2                                                                |   0.428s  |   0.428s  |   0.000s  | 0.0%|
|qf_Select_704_values_0.smt2                                                                 |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|qf_Select_740_values_0.smt2                                                                 |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|qf_Select_741_values_0.smt2                                                                 |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|qf_Select_746_values_0.smt2                                                                 |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|qf_Select_747_values_0.smt2                                                                 |  59.999s  |  59.999s  |   0.000s  | 0.0%|
</details>
