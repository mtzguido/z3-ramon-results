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
Job tag: smt-60-clausal-lookahead-sequential-qfnia-sat
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 7fb6497ce1162635e7e5f78fe35bf4d5b02d2dbd
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" smt.sls.enable=true smt.sls.parallel=false model_validate=true sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_UFNIA_SAT
Z3 commit message: fix return value when in external mode bool-flip

return null_bool_var instead of false (= 0).

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-60-clausal-lookahead-sequential-qfnia-sat
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 7fb6497ce1162635e7e5f78fe35bf4d5b02d2dbd
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" smt.sls.enable=true smt.sls.parallel=false model_validate=true sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_UFNIA_SAT
Z3 commit message: fix return value when in external mode bool-flip

return null_bool_var instead of false (= 0).

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00005.smt2                                                                                  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|00018.smt2                                                                                  |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|00035.smt2                                                                                  |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00149.smt2                                                                                  |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|00304.smt2                                                                                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.026s  |   0.026s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00005.smt2                                                                                  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|00018.smt2                                                                                  |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|00035.smt2                                                                                  |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00149.smt2                                                                                  |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|00304.smt2                                                                                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.026s  |   0.026s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00005.smt2                                                                                  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|00018.smt2                                                                                  |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|00035.smt2                                                                                  |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00149.smt2                                                                                  |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|00304.smt2                                                                                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.026s  |   0.026s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00005.smt2                                                                                  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|00018.smt2                                                                                  |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|00035.smt2                                                                                  |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00149.smt2                                                                                  |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|00304.smt2                                                                                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.026s  |   0.026s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|int_check_bvuge_bvlshr0_rtl.smt2                                                           |  59.999s |53.324MiB|
|int_check_ne_bvlshr1_ltr_inv_g.smt2                                                        |  59.998s |53.152MiB|
|int_check_ne_bvshl1_ltr_inv_g.smt2                                                         |  59.996s |53.024MiB|
|int_check_ne_bvudiv0_ltr_inv_g.smt2                                                        |  59.996s |53.444MiB|
|int_check_bvsge_bvurem1_rtl.smt2                                                           |   0.919s |55.084MiB|
|int_check_ne_bvashr1_ltr_inv_r.smt2                                                        |   0.526s |54.268MiB|
|qf_AddSub_1604_values_0.smt2                                                               |   0.521s |55.116MiB|
|int_check_bvslt_bvashr1_ltr_inv_g.smt2                                                     |   0.500s |54.428MiB|
|int_check_bvsge_bvashr0_rtl.smt2                                                           |   0.496s |55.448MiB|
|int_check_eq_bvshl0_rtl.smt2                                                               |   0.387s |54.088MiB|
|qf_Select_741_values_0.smt2                                                                |   0.353s |54.164MiB|
|qf_Select_740_values_0.smt2                                                                |   0.352s |54.064MiB|
|int_check_bvsle_bvashr1_ltr_inv_g.smt2                                                     |   0.326s |53.944MiB|
|qf_Select_746_values_0.smt2                                                                |   0.296s |53.684MiB|
|int_check_bvslt_bvmul_rtl.smt2                                                             |   0.272s |54.792MiB|
|qf_Select_747_values_0.smt2                                                                |   0.233s |54.288MiB|
|int_check_bvsgt_bvashr0_ltr_inv_g.smt2                                                     |   0.206s |54.252MiB|
|int_check_bvugt_bvshl0_rtl.smt2                                                            |   0.186s |53.892MiB|
|int_check_bvule_bvashr0_ltr_inv_g.smt2                                                     |   0.184s |54.032MiB|
|int_check_bvsle_bvudiv0_ltr_inv_g.smt2                                                     |   0.173s |53.964MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|int_check_bvuge_bvlshr0_rtl.smt2                                                           |  59.999s |53.324MiB|
|int_check_ne_bvlshr1_ltr_inv_g.smt2                                                        |  59.998s |53.152MiB|
|int_check_ne_bvshl1_ltr_inv_g.smt2                                                         |  59.996s |53.024MiB|
|int_check_ne_bvudiv0_ltr_inv_g.smt2                                                        |  59.996s |53.444MiB|
|int_check_bvsge_bvurem1_rtl.smt2                                                           |   0.919s |55.084MiB|
|int_check_ne_bvashr1_ltr_inv_r.smt2                                                        |   0.526s |54.268MiB|
|qf_AddSub_1604_values_0.smt2                                                               |   0.521s |55.116MiB|
|int_check_bvslt_bvashr1_ltr_inv_g.smt2                                                     |   0.500s |54.428MiB|
|int_check_bvsge_bvashr0_rtl.smt2                                                           |   0.496s |55.448MiB|
|int_check_eq_bvshl0_rtl.smt2                                                               |   0.387s |54.088MiB|
|qf_Select_741_values_0.smt2                                                                |   0.353s |54.164MiB|
|qf_Select_740_values_0.smt2                                                                |   0.352s |54.064MiB|
|int_check_bvsle_bvashr1_ltr_inv_g.smt2                                                     |   0.326s |53.944MiB|
|qf_Select_746_values_0.smt2                                                                |   0.296s |53.684MiB|
|int_check_bvslt_bvmul_rtl.smt2                                                             |   0.272s |54.792MiB|
|qf_Select_747_values_0.smt2                                                                |   0.233s |54.288MiB|
|int_check_bvsgt_bvashr0_ltr_inv_g.smt2                                                     |   0.206s |54.252MiB|
|int_check_bvugt_bvshl0_rtl.smt2                                                            |   0.186s |53.892MiB|
|int_check_bvule_bvashr0_ltr_inv_g.smt2                                                     |   0.184s |54.032MiB|
|int_check_bvsle_bvudiv0_ltr_inv_g.smt2                                                     |   0.173s |53.964MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |52.544MiB|52.544MiB|0B| 0.0%|
|00003.smt2                                                                                  |52.304MiB|52.304MiB|0B| 0.0%|
|00005.smt2                                                                                  |52.244MiB|52.244MiB|0B| 0.0%|
|00018.smt2                                                                                  |54.456MiB|54.456MiB|0B| 0.0%|
|00020.smt2                                                                                  |52.304MiB|52.304MiB|0B| 0.0%|
|00035.smt2                                                                                  |52.564MiB|52.564MiB|0B| 0.0%|
|00085.smt2                                                                                  |52.292MiB|52.292MiB|0B| 0.0%|
|00102.smt2                                                                                  |52.556MiB|52.556MiB|0B| 0.0%|
|00104.smt2                                                                                  |52.756MiB|52.756MiB|0B| 0.0%|
|00105.smt2                                                                                  |52.592MiB|52.592MiB|0B| 0.0%|
|00149.smt2                                                                                  |52.524MiB|52.524MiB|0B| 0.0%|
|00194.smt2                                                                                  |52.58MiB|52.58MiB|0B| 0.0%|
|00235.smt2                                                                                  |52.3MiB|52.3MiB|0B| 0.0%|
|00243.smt2                                                                                  |52.488MiB|52.488MiB|0B| 0.0%|
|00247.smt2                                                                                  |52.384MiB|52.384MiB|0B| 0.0%|
|00249.smt2                                                                                  |52.56MiB|52.56MiB|0B| 0.0%|
|00251.smt2                                                                                  |52.48MiB|52.48MiB|0B| 0.0%|
|00294.smt2                                                                                  |52.468MiB|52.468MiB|0B| 0.0%|
|00304.smt2                                                                                  |54.684MiB|54.684MiB|0B| 0.0%|
|00314.smt2                                                                                  |53.692MiB|53.692MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |52.544MiB|52.544MiB|0B| 0.0%|
|00003.smt2                                                                                  |52.304MiB|52.304MiB|0B| 0.0%|
|00005.smt2                                                                                  |52.244MiB|52.244MiB|0B| 0.0%|
|00018.smt2                                                                                  |54.456MiB|54.456MiB|0B| 0.0%|
|00020.smt2                                                                                  |52.304MiB|52.304MiB|0B| 0.0%|
|00035.smt2                                                                                  |52.564MiB|52.564MiB|0B| 0.0%|
|00085.smt2                                                                                  |52.292MiB|52.292MiB|0B| 0.0%|
|00102.smt2                                                                                  |52.556MiB|52.556MiB|0B| 0.0%|
|00104.smt2                                                                                  |52.756MiB|52.756MiB|0B| 0.0%|
|00105.smt2                                                                                  |52.592MiB|52.592MiB|0B| 0.0%|
|00149.smt2                                                                                  |52.524MiB|52.524MiB|0B| 0.0%|
|00194.smt2                                                                                  |52.58MiB|52.58MiB|0B| 0.0%|
|00235.smt2                                                                                  |52.3MiB|52.3MiB|0B| 0.0%|
|00243.smt2                                                                                  |52.488MiB|52.488MiB|0B| 0.0%|
|00247.smt2                                                                                  |52.384MiB|52.384MiB|0B| 0.0%|
|00249.smt2                                                                                  |52.56MiB|52.56MiB|0B| 0.0%|
|00251.smt2                                                                                  |52.48MiB|52.48MiB|0B| 0.0%|
|00294.smt2                                                                                  |52.468MiB|52.468MiB|0B| 0.0%|
|00304.smt2                                                                                  |54.684MiB|54.684MiB|0B| 0.0%|
|00314.smt2                                                                                  |53.692MiB|53.692MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |52.544MiB|52.544MiB|0B| 0.0%|
|00003.smt2                                                                                  |52.304MiB|52.304MiB|0B| 0.0%|
|00005.smt2                                                                                  |52.244MiB|52.244MiB|0B| 0.0%|
|00018.smt2                                                                                  |54.456MiB|54.456MiB|0B| 0.0%|
|00020.smt2                                                                                  |52.304MiB|52.304MiB|0B| 0.0%|
|00035.smt2                                                                                  |52.564MiB|52.564MiB|0B| 0.0%|
|00085.smt2                                                                                  |52.292MiB|52.292MiB|0B| 0.0%|
|00102.smt2                                                                                  |52.556MiB|52.556MiB|0B| 0.0%|
|00104.smt2                                                                                  |52.756MiB|52.756MiB|0B| 0.0%|
|00105.smt2                                                                                  |52.592MiB|52.592MiB|0B| 0.0%|
|00149.smt2                                                                                  |52.524MiB|52.524MiB|0B| 0.0%|
|00194.smt2                                                                                  |52.58MiB|52.58MiB|0B| 0.0%|
|00235.smt2                                                                                  |52.3MiB|52.3MiB|0B| 0.0%|
|00243.smt2                                                                                  |52.488MiB|52.488MiB|0B| 0.0%|
|00247.smt2                                                                                  |52.384MiB|52.384MiB|0B| 0.0%|
|00249.smt2                                                                                  |52.56MiB|52.56MiB|0B| 0.0%|
|00251.smt2                                                                                  |52.48MiB|52.48MiB|0B| 0.0%|
|00294.smt2                                                                                  |52.468MiB|52.468MiB|0B| 0.0%|
|00304.smt2                                                                                  |54.684MiB|54.684MiB|0B| 0.0%|
|00314.smt2                                                                                  |53.692MiB|53.692MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |52.544MiB|52.544MiB|0B| 0.0%|
|00003.smt2                                                                                  |52.304MiB|52.304MiB|0B| 0.0%|
|00005.smt2                                                                                  |52.244MiB|52.244MiB|0B| 0.0%|
|00018.smt2                                                                                  |54.456MiB|54.456MiB|0B| 0.0%|
|00020.smt2                                                                                  |52.304MiB|52.304MiB|0B| 0.0%|
|00035.smt2                                                                                  |52.564MiB|52.564MiB|0B| 0.0%|
|00085.smt2                                                                                  |52.292MiB|52.292MiB|0B| 0.0%|
|00102.smt2                                                                                  |52.556MiB|52.556MiB|0B| 0.0%|
|00104.smt2                                                                                  |52.756MiB|52.756MiB|0B| 0.0%|
|00105.smt2                                                                                  |52.592MiB|52.592MiB|0B| 0.0%|
|00149.smt2                                                                                  |52.524MiB|52.524MiB|0B| 0.0%|
|00194.smt2                                                                                  |52.58MiB|52.58MiB|0B| 0.0%|
|00235.smt2                                                                                  |52.3MiB|52.3MiB|0B| 0.0%|
|00243.smt2                                                                                  |52.488MiB|52.488MiB|0B| 0.0%|
|00247.smt2                                                                                  |52.384MiB|52.384MiB|0B| 0.0%|
|00249.smt2                                                                                  |52.56MiB|52.56MiB|0B| 0.0%|
|00251.smt2                                                                                  |52.48MiB|52.48MiB|0B| 0.0%|
|00294.smt2                                                                                  |52.468MiB|52.468MiB|0B| 0.0%|
|00304.smt2                                                                                  |54.684MiB|54.684MiB|0B| 0.0%|
|00314.smt2                                                                                  |53.692MiB|53.692MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|00793.smt2                                                                                 |   0.071s |58.32MiB|
|int_check_bvsge_bvashr0_rtl.smt2                                                           |   0.496s |55.448MiB|
|qf_AddSub_1604_values_0.smt2                                                               |   0.521s |55.116MiB|
|int_check_bvsge_bvurem1_rtl.smt2                                                           |   0.919s |55.084MiB|
|00379.smt2                                                                                 |   0.070s |54.936MiB|
|int_check_bvslt_bvmul_rtl.smt2                                                             |   0.272s |54.792MiB|
|00304.smt2                                                                                 |   0.031s |54.684MiB|
|00018.smt2                                                                                 |   0.043s |54.456MiB|
|int_check_bvslt_bvashr1_ltr_inv_g.smt2                                                     |   0.500s |54.428MiB|
|int_check_bvsge_bvashr0_ltr_inv_g.smt2                                                     |   0.122s |54.42MiB|
|qf_Select_747_values_0.smt2                                                                |   0.233s |54.288MiB|
|int_check_ne_bvashr1_ltr_inv_r.smt2                                                        |   0.526s |54.268MiB|
|int_check_bvsgt_bvashr0_ltr_inv_g.smt2                                                     |   0.206s |54.252MiB|
|qf_Select_741_values_0.smt2                                                                |   0.353s |54.164MiB|
|int_check_eq_bvshl0_rtl.smt2                                                               |   0.387s |54.088MiB|
|int_check_bvuge_bvlshr0_ltr_inv_g.smt2                                                     |   0.114s |54.08MiB|
|qf_Select_740_values_0.smt2                                                                |   0.352s |54.064MiB|
|int_check_bvsge_bvshl0_ltr_inv_g.smt2                                                      |   0.117s |54.056MiB|
|int_check_bvule_bvashr0_ltr_inv_g.smt2                                                     |   0.184s |54.032MiB|
|int_check_bvsle_bvudiv0_ltr_inv_g.smt2                                                     |   0.173s |53.964MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|00793.smt2                                                                                 |   0.071s |58.32MiB|
|int_check_bvsge_bvashr0_rtl.smt2                                                           |   0.496s |55.448MiB|
|qf_AddSub_1604_values_0.smt2                                                               |   0.521s |55.116MiB|
|int_check_bvsge_bvurem1_rtl.smt2                                                           |   0.919s |55.084MiB|
|00379.smt2                                                                                 |   0.070s |54.936MiB|
|int_check_bvslt_bvmul_rtl.smt2                                                             |   0.272s |54.792MiB|
|00304.smt2                                                                                 |   0.031s |54.684MiB|
|00018.smt2                                                                                 |   0.043s |54.456MiB|
|int_check_bvslt_bvashr1_ltr_inv_g.smt2                                                     |   0.500s |54.428MiB|
|int_check_bvsge_bvashr0_ltr_inv_g.smt2                                                     |   0.122s |54.42MiB|
|qf_Select_747_values_0.smt2                                                                |   0.233s |54.288MiB|
|int_check_ne_bvashr1_ltr_inv_r.smt2                                                        |   0.526s |54.268MiB|
|int_check_bvsgt_bvashr0_ltr_inv_g.smt2                                                     |   0.206s |54.252MiB|
|qf_Select_741_values_0.smt2                                                                |   0.353s |54.164MiB|
|int_check_eq_bvshl0_rtl.smt2                                                               |   0.387s |54.088MiB|
|int_check_bvuge_bvlshr0_ltr_inv_g.smt2                                                     |   0.114s |54.08MiB|
|qf_Select_740_values_0.smt2                                                                |   0.352s |54.064MiB|
|int_check_bvsge_bvshl0_ltr_inv_g.smt2                                                      |   0.117s |54.056MiB|
|int_check_bvule_bvashr0_ltr_inv_g.smt2                                                     |   0.184s |54.032MiB|
|int_check_bvsle_bvudiv0_ltr_inv_g.smt2                                                     |   0.173s |53.964MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00005.smt2                                                                                  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|00018.smt2                                                                                  |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|00035.smt2                                                                                  |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00149.smt2                                                                                  |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|00304.smt2                                                                                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|00324.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00402.smt2                                                                                  |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|00413.smt2                                                                                  |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|00415.smt2                                                                                  |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|00428.smt2                                                                                  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|00793.smt2                                                                                  |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|00967.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|01052.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|int_check_bvsge_bvadd_ltr_inv_r.smt2                                                        |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|int_check_bvsge_bvand_ltr_inv_g.smt2                                                        |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|int_check_bvsge_bvand_rtl.smt2                                                              |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|int_check_bvsge_bvashr0_ltr_inv_g.smt2                                                      |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|int_check_bvsge_bvashr0_rtl.smt2                                                            |   0.496s  |   0.496s  |   0.000s  | 0.0%|
|int_check_bvsge_bvashr1_ltr_inv_g.smt2                                                      |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|int_check_bvsge_bvlshr0_ltr_inv_r.smt2                                                      |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|int_check_bvsge_bvlshr1_rtl.smt2                                                            |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|int_check_bvsge_bvmul_rtl.smt2                                                              |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|int_check_bvsge_bvnot_ltr_inv_g.smt2                                                        |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|int_check_bvsge_bvor_ltr_inv_g.smt2                                                         |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|int_check_bvsge_bvor_rtl.smt2                                                               |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|int_check_bvsge_bvshl0_ltr_inv_g.smt2                                                       |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|int_check_bvsge_bvshl0_rtl.smt2                                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|int_check_bvsge_bvudiv0_rtl.smt2                                                            |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|int_check_bvsge_bvurem0_ltr_inv_g.smt2                                                      |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|int_check_bvsge_bvurem0_rtl.smt2                                                            |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|int_check_bvsge_bvurem1_rtl.smt2                                                            |   0.919s  |   0.919s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvadd_ltr_inv_g.smt2                                                        |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvadd_ltr_inv_r.smt2                                                        |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvand_ltr_inv_g.smt2                                                        |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvand_rtl.smt2                                                              |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvashr0_ltr_inv_g.smt2                                                      |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvashr1_rtl.smt2                                                            |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvlshr0_ltr_inv_r.smt2                                                      |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvmul_rtl.smt2                                                              |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvneg_ltr_inv_g.smt2                                                        |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvneg_rtl.smt2                                                              |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvnot_ltr_inv_g.smt2                                                        |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvnot_rtl.smt2                                                              |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvor_ltr_inv_g.smt2                                                         |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvor_rtl.smt2                                                               |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvudiv0_rtl.smt2                                                            |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvudiv1_rtl.smt2                                                            |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvurem0_ltr_inv_g.smt2                                                      |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvurem1_ltr_inv_g.smt2                                                      |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|int_check_bvsle_bvadd_ltr_inv_r.smt2                                                        |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|int_check_bvsle_bvand_ltr_inv_g.smt2                                                        |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|int_check_bvsle_bvand_rtl.smt2                                                              |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|int_check_bvsle_bvashr1_ltr_inv_g.smt2                                                      |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|int_check_bvsle_bvlshr0_rtl.smt2                                                            |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|int_check_bvsle_bvlshr1_ltr_inv_g.smt2                                                      |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|int_check_bvsle_bvlshr1_rtl.smt2                                                            |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|int_check_bvsle_bvneg_ltr_inv_g.smt2                                                        |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|int_check_bvsle_bvnot_ltr_inv_g.smt2                                                        |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|int_check_bvsle_bvor_ltr_inv_g.smt2                                                         |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|int_check_bvsle_bvor_rtl.smt2                                                               |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|int_check_bvsle_bvshl0_rtl.smt2                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|int_check_bvsle_bvshl1_rtl.smt2                                                             |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|int_check_bvsle_bvudiv0_ltr_inv_g.smt2                                                      |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|int_check_bvsle_bvudiv1_rtl.smt2                                                            |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|int_check_bvsle_bvurem0_ltr_inv_g.smt2                                                      |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|int_check_bvsle_bvurem0_rtl.smt2                                                            |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|int_check_bvsle_bvurem1_ltr_inv_r.smt2                                                      |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|int_check_bvsle_bvurem1_rtl.smt2                                                            |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|int_check_bvslt_bvadd_ltr_inv_g.smt2                                                        |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|int_check_bvslt_bvadd_ltr_inv_r.smt2                                                        |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|int_check_bvslt_bvadd_rtl.smt2                                                              |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|int_check_bvslt_bvand_ltr_inv_g.smt2                                                        |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|int_check_bvslt_bvand_rtl.smt2                                                              |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|int_check_bvslt_bvashr1_ltr_inv_g.smt2                                                      |   0.500s  |   0.500s  |   0.000s  | 0.0%|
|int_check_bvslt_bvlshr1_ltr_inv_g.smt2                                                      |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|int_check_bvslt_bvlshr1_rtl.smt2                                                            |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|int_check_bvslt_bvmul_rtl.smt2                                                              |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|int_check_bvslt_bvneg_ltr_inv_g.smt2                                                        |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|int_check_bvslt_bvneg_rtl.smt2                                                              |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|int_check_bvslt_bvnot_ltr_inv_g.smt2                                                        |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|int_check_bvslt_bvnot_rtl.smt2                                                              |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|int_check_bvslt_bvor_ltr_inv_g.smt2                                                         |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|int_check_bvslt_bvor_rtl.smt2                                                               |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|int_check_bvslt_bvshl0_rtl.smt2                                                             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|int_check_bvslt_bvshl1_rtl.smt2                                                             |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|int_check_bvslt_bvudiv0_rtl.smt2                                                            |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|int_check_bvslt_bvudiv1_rtl.smt2                                                            |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|int_check_bvslt_bvurem0_ltr_inv_r.smt2                                                      |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|int_check_bvslt_bvurem0_rtl.smt2                                                            |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|int_check_bvslt_bvurem1_ltr_inv_g.smt2                                                      |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|int_check_bvslt_bvurem1_rtl.smt2                                                            |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|int_check_bvuge_bvand_ltr_inv_g.smt2                                                        |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|int_check_bvuge_bvand_rtl.smt2                                                              |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|int_check_bvuge_bvashr0_ltr_inv_g.smt2                                                      |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|int_check_bvuge_bvlshr0_ltr_inv_g.smt2                                                      |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|int_check_bvuge_bvlshr0_rtl.smt2                                                            |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|int_check_bvuge_bvlshr1_rtl.smt2                                                            |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|int_check_bvuge_bvmul_rtl.smt2                                                              |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|int_check_bvuge_bvor_ltr_inv_g.smt2                                                         |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|int_check_bvuge_bvudiv0_rtl.smt2                                                            |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|int_check_bvuge_bvurem1_ltr_inv_g.smt2                                                      |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|int_check_bvuge_bvurem1_rtl.smt2                                                            |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|int_check_bvugt_bvand_ltr_inv_g.smt2                                                        |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|int_check_bvugt_bvand_rtl.smt2                                                              |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|int_check_bvugt_bvlshr0_rtl.smt2                                                            |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|int_check_bvugt_bvlshr1_rtl.smt2                                                            |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|int_check_bvugt_bvmul_rtl.smt2                                                              |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|int_check_bvugt_bvor_ltr_inv_g.smt2                                                         |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|int_check_bvugt_bvor_rtl.smt2                                                               |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|int_check_bvugt_bvshl0_rtl.smt2                                                             |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|int_check_bvule_bvand_ltr_inv_g.smt2                                                        |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|int_check_bvule_bvashr0_ltr_inv_g.smt2                                                      |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|int_check_bvule_bvashr1_ltr_inv_g.smt2                                                      |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|int_check_bvule_bvashr1_rtl.smt2                                                            |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|int_check_bvule_bvlshr0_ltr_inv_g.smt2                                                      |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|int_check_bvule_bvlshr1_ltr_inv_g.smt2                                                      |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|int_check_bvule_bvor_ltr_inv_g.smt2                                                         |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|int_check_bvule_bvor_rtl.smt2                                                               |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|int_check_bvule_bvshl1_ltr_inv_g.smt2                                                       |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|int_check_bvule_bvudiv0_ltr_inv_g.smt2                                                      |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|int_check_bvule_bvudiv0_rtl.smt2                                                            |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|int_check_bvule_bvudiv1_rtl.smt2                                                            |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|int_check_bvult_bvand_ltr_inv_g.smt2                                                        |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|int_check_bvult_bvand_rtl.smt2                                                              |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|int_check_bvult_bvashr0_ltr_inv_g.smt2                                                      |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|int_check_bvult_bvashr1_ltr_inv_g.smt2                                                      |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|int_check_bvult_bvlshr0_ltr_inv_g.smt2                                                      |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|int_check_bvult_bvlshr1_ltr_inv_g.smt2                                                      |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|int_check_bvult_bvor_ltr_inv_g.smt2                                                         |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|int_check_bvult_bvor_rtl.smt2                                                               |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|int_check_bvult_bvshl1_ltr_inv_g.smt2                                                       |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|int_check_bvult_bvudiv1_ltr_inv_g.smt2                                                      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|int_check_bvult_bvudiv1_rtl.smt2                                                            |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|int_check_eq_bvand_rtl.smt2                                                                 |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|int_check_eq_bvmul_rtl.smt2                                                                 |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|int_check_eq_bvor_rtl.smt2                                                                  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|int_check_eq_bvshl0_rtl.smt2                                                                |   0.387s  |   0.387s  |   0.000s  | 0.0%|
|int_check_eq_bvurem1_ltr_inv_g.smt2                                                         |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|int_check_eq_bvurem1_rtl.smt2                                                               |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|int_check_ne_bvadd_ltr_inv_g.smt2                                                           |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|int_check_ne_bvadd_ltr_inv_r.smt2                                                           |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|int_check_ne_bvand_ltr_inv_g.smt2                                                           |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|int_check_ne_bvand_rtl.smt2                                                                 |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|int_check_ne_bvashr1_ltr_inv_r.smt2                                                         |   0.526s  |   0.526s  |   0.000s  | 0.0%|
|int_check_ne_bvashr1_rtl.smt2                                                               |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|int_check_ne_bvlshr0_ltr_inv_g.smt2                                                         |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|int_check_ne_bvlshr0_rtl.smt2                                                               |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|int_check_ne_bvlshr1_ltr_inv_g.smt2                                                         |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|int_check_ne_bvlshr1_rtl.smt2                                                               |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|int_check_ne_bvneg_ltr_inv_g.smt2                                                           |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|int_check_ne_bvnot_ltr_inv_g.smt2                                                           |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|int_check_ne_bvor_ltr_inv_g.smt2                                                            |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|int_check_ne_bvor_rtl.smt2                                                                  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|int_check_ne_bvshl0_rtl.smt2                                                                |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|int_check_ne_bvshl1_ltr_inv_g.smt2                                                          |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|int_check_ne_bvudiv0_ltr_inv_g.smt2                                                         |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|int_check_ne_bvurem0_ltr_inv_g.smt2                                                         |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|n0-00001.smt2                                                                               |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|qf_AddSub_1040_values_0.smt2                                                                |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|qf_AddSub_1043_values_0.smt2                                                                |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_AddSub_1202_values_0.smt2                                                                |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|qf_AddSub_1295_values_0.smt2                                                                |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_AddSub_1560_values_0.smt2                                                                |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|qf_AddSub_1564_values_0.smt2                                                                |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|qf_AddSub_1599_values_0.smt2                                                                |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|qf_AddSub_1604_values_0.smt2                                                                |   0.521s  |   0.521s  |   0.000s  | 0.0%|
|qf_AddSub_1624_values_0.smt2                                                                |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_AndOrXor_1012_values_0.smt2                                                              |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|qf_AndOrXor_1230_values_0.smt2                                                              |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|qf_AndOrXor_1241_values_0.smt2                                                              |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_AndOrXor_1247_values_0.smt2                                                              |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|qf_AndOrXor_1253_values_0.smt2                                                              |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|qf_AndOrXor_1280_values_0.smt2                                                              |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|qf_AndOrXor_1288_values_0.smt2                                                              |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|qf_AndOrXor_1294_values_0.smt2                                                              |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|qf_AndOrXor_135_values_0.smt2                                                               |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|qf_AndOrXor_144_values_0.smt2                                                               |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|qf_AndOrXor_151_values_0.smt2                                                               |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|qf_AndOrXor_1733_values_0.smt2                                                              |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|qf_AndOrXor_1795_values_0.smt2                                                              |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|qf_AndOrXor_1864_values_0.smt2                                                              |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|qf_AndOrXor_1979_values_0.smt2                                                              |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|qf_AndOrXor_2008_values_0.smt2                                                              |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|qf_AndOrXor_2052_values_0.smt2                                                              |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|qf_AndOrXor_2063_values_0.smt2                                                              |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|qf_AndOrXor_2113_values_0.smt2                                                              |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|qf_AndOrXor_2118_values_0.smt2                                                              |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|qf_AndOrXor_2123_values_0.smt2                                                              |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_AndOrXor_2160_values_0.smt2                                                              |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|qf_AndOrXor_2188_values_0.smt2                                                              |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_AndOrXor_2231_values_0.smt2                                                              |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_AndOrXor_2243_values_0.smt2                                                              |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|qf_AndOrXor_2247_values_0.smt2                                                              |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|qf_AndOrXor_2263_values_0.smt2                                                              |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|qf_AndOrXor_2264_values_0.smt2                                                              |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|qf_AndOrXor_2265_values_0.smt2                                                              |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|qf_AndOrXor_2284_values_0.smt2                                                              |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|qf_AndOrXor_2285_values_0.smt2                                                              |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|qf_AndOrXor_2297_values_0.smt2                                                              |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_AndOrXor_2367_values_0.smt2                                                              |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|qf_AndOrXor_2416_values_0.smt2                                                              |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|qf_AndOrXor_2417_values_0.smt2                                                              |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|qf_AndOrXor_2429_values_0.smt2                                                              |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|qf_AndOrXor_2430_values_0.smt2                                                              |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|qf_AndOrXor_2475_values_0.smt2                                                              |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|qf_AndOrXor_2486_values_0.smt2                                                              |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|qf_AndOrXor_2515_values_0.smt2                                                              |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|qf_AndOrXor_2581_values_0.smt2                                                              |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|qf_AndOrXor_2587_values_0.smt2                                                              |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|qf_AndOrXor_2595_values_0.smt2                                                              |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|qf_AndOrXor_2607_values_0.smt2                                                              |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_AndOrXor_2617_values_0.smt2                                                              |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|qf_AndOrXor_2627_values_0.smt2                                                              |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_AndOrXor_2647_values_0.smt2                                                              |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|qf_AndOrXor_2658_values_0.smt2                                                              |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|qf_AndOrXor_273_values_7.smt2                                                               |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|qf_AndOrXor_280_values_3.smt2                                                               |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_AndOrXor_298_values_0.smt2                                                               |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|qf_AndOrXor_363_values_0.smt2                                                               |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|qf_AndOrXor_364_values_0.smt2                                                               |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|qf_AndOrXor_516_values_0.smt2                                                               |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|qf_AndOrXor_523_values_0.smt2                                                               |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|qf_AndOrXor_530_values_0.smt2                                                               |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|qf_AndOrXor_537_values_0.smt2                                                               |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|qf_AndOrXor_698_values_0.smt2                                                               |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|qf_AndOrXor_709_values_0.smt2                                                               |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_AndOrXor_716_values_0.smt2                                                               |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|qf_AndOrXor_732-1_values_0.smt2                                                             |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|qf_AndOrXor_732-2_values_0.smt2                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|qf_AndOrXor_745_values_0.smt2                                                               |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|qf_AndOrXor_757_values_0.smt2                                                               |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|qf_AndOrXor_819_values_0.smt2                                                               |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_AndOrXor_827_values_0.smt2                                                               |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|qf_AndOrXor_937_values_0.smt2                                                               |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|qf_InstCombineShift239_values_0.smt2                                                        |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|qf_InstCombineShift279_values_0.smt2                                                        |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|qf_InstCombineShift440_values_0.smt2                                                        |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|qf_InstCombineShift476_values_0.smt2                                                        |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|qf_Select_420_values_0.smt2                                                                 |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_Select_423_values_57.smt2                                                                |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|qf_Select_427_values_0.smt2                                                                 |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|qf_Select_430_values_60.smt2                                                                |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|qf_Select_433_values_0.smt2                                                                 |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|qf_Select_576a_values_0.smt2                                                                |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|qf_Select_576b_values_0.smt2                                                                |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|qf_Select_704_values_0.smt2                                                                 |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|qf_Select_740_values_0.smt2                                                                 |   0.352s  |   0.352s  |   0.000s  | 0.0%|
|qf_Select_741_values_0.smt2                                                                 |   0.353s  |   0.353s  |   0.000s  | 0.0%|
|qf_Select_746_values_0.smt2                                                                 |   0.296s  |   0.296s  |   0.000s  | 0.0%|
|qf_Select_747_values_0.smt2                                                                 |   0.233s  |   0.233s  |   0.000s  | 0.0%|
</details>
