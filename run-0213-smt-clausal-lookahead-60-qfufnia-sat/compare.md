Comparing data and data


# SUMMARY
- LHS tests = 267
- RHS tests = 267
- LHS success = 265  (99.25093632958801%)
- RHS success = 265  (99.25093632958801%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-clausal-lookahead-60-qfufnia-sat
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: d3bf25ce856f3ea316b69e82dd762f907dbd8e4b
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" smt.sls.enable=true smt.sls.parallel=false model_validate=true sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_UFNIA_SAT
Z3 commit message: throttle value smt -> sls

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-clausal-lookahead-60-qfufnia-sat
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: d3bf25ce856f3ea316b69e82dd762f907dbd8e4b
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" smt.sls.enable=true smt.sls.parallel=false model_validate=true sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_UFNIA_SAT
Z3 commit message: throttle value smt -> sls

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|00005.smt2                                                                                  |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|00018.smt2                                                                                  |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|00035.smt2                                                                                  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|00149.smt2                                                                                  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|00304.smt2                                                                                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.030s  |   0.030s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|00005.smt2                                                                                  |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|00018.smt2                                                                                  |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|00035.smt2                                                                                  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|00149.smt2                                                                                  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|00304.smt2                                                                                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.030s  |   0.030s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|00005.smt2                                                                                  |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|00018.smt2                                                                                  |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|00035.smt2                                                                                  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|00149.smt2                                                                                  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|00304.smt2                                                                                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.030s  |   0.030s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|00005.smt2                                                                                  |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|00018.smt2                                                                                  |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|00035.smt2                                                                                  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|00149.smt2                                                                                  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|00304.smt2                                                                                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.030s  |   0.030s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|qf_Select_740_values_0.smt2                                                                |   0.394s |54.044MiB|
|int_check_bvsge_bvurem1_rtl.smt2                                                           |   0.312s |53.836MiB|
|qf_Select_741_values_0.smt2                                                                |   0.299s |54.084MiB|
|int_check_bvslt_bvashr1_ltr_inv_g.smt2                                                     |   0.258s |53.844MiB|
|int_check_bvsle_bvashr1_ltr_inv_g.smt2                                                     |   0.255s |53.668MiB|
|int_check_bvsge_bvlshr1_rtl.smt2                                                           |   0.217s |53.812MiB|
|qf_Select_746_values_0.smt2                                                                |   0.204s |54.008MiB|
|int_check_ne_bvudiv0_ltr_inv_g.smt2                                                        |   0.204s |53.688MiB|
|int_check_bvule_bvashr0_ltr_inv_g.smt2                                                     |   0.194s |54.0MiB|
|int_check_bvugt_bvshl0_rtl.smt2                                                            |   0.177s |54.044MiB|
|int_check_bvult_bvashr1_ltr_inv_g.smt2                                                     |   0.155s |53.78MiB|
|int_check_bvsle_bvudiv0_ltr_inv_g.smt2                                                     |   0.153s |53.784MiB|
|qf_muldivrem_876_values_0.smt2                                                             |   0.136s |53.624MiB|
|int_check_bvult_bvashr0_ltr_inv_g.smt2                                                     |   0.129s |53.56MiB|
|int_check_bvslt_bvlshr1_ltr_inv_g.smt2                                                     |   0.127s |53.948MiB|
|int_check_bvsgt_bvudiv1_rtl.smt2                                                           |   0.125s |53.784MiB|
|int_check_bvsge_bvashr1_ltr_inv_g.smt2                                                     |   0.118s |53.712MiB|
|int_check_bvsgt_bvashr0_ltr_inv_g.smt2                                                     |   0.117s |54.068MiB|
|int_check_bvslt_bvshl0_rtl.smt2                                                            |   0.105s |53.8MiB|
|int_check_bvsle_bvlshr0_rtl.smt2                                                           |   0.102s |53.572MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|qf_Select_740_values_0.smt2                                                                |   0.394s |54.044MiB|
|int_check_bvsge_bvurem1_rtl.smt2                                                           |   0.312s |53.836MiB|
|qf_Select_741_values_0.smt2                                                                |   0.299s |54.084MiB|
|int_check_bvslt_bvashr1_ltr_inv_g.smt2                                                     |   0.258s |53.844MiB|
|int_check_bvsle_bvashr1_ltr_inv_g.smt2                                                     |   0.255s |53.668MiB|
|int_check_bvsge_bvlshr1_rtl.smt2                                                           |   0.217s |53.812MiB|
|qf_Select_746_values_0.smt2                                                                |   0.204s |54.008MiB|
|int_check_ne_bvudiv0_ltr_inv_g.smt2                                                        |   0.204s |53.688MiB|
|int_check_bvule_bvashr0_ltr_inv_g.smt2                                                     |   0.194s |54.0MiB|
|int_check_bvugt_bvshl0_rtl.smt2                                                            |   0.177s |54.044MiB|
|int_check_bvult_bvashr1_ltr_inv_g.smt2                                                     |   0.155s |53.78MiB|
|int_check_bvsle_bvudiv0_ltr_inv_g.smt2                                                     |   0.153s |53.784MiB|
|qf_muldivrem_876_values_0.smt2                                                             |   0.136s |53.624MiB|
|int_check_bvult_bvashr0_ltr_inv_g.smt2                                                     |   0.129s |53.56MiB|
|int_check_bvslt_bvlshr1_ltr_inv_g.smt2                                                     |   0.127s |53.948MiB|
|int_check_bvsgt_bvudiv1_rtl.smt2                                                           |   0.125s |53.784MiB|
|int_check_bvsge_bvashr1_ltr_inv_g.smt2                                                     |   0.118s |53.712MiB|
|int_check_bvsgt_bvashr0_ltr_inv_g.smt2                                                     |   0.117s |54.068MiB|
|int_check_bvslt_bvshl0_rtl.smt2                                                            |   0.105s |53.8MiB|
|int_check_bvsle_bvlshr0_rtl.smt2                                                           |   0.102s |53.572MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |52.552MiB|52.552MiB|0B| 0.0%|
|00003.smt2                                                                                  |52.352MiB|52.352MiB|0B| 0.0%|
|00005.smt2                                                                                  |52.412MiB|52.412MiB|0B| 0.0%|
|00018.smt2                                                                                  |54.24MiB|54.24MiB|0B| 0.0%|
|00020.smt2                                                                                  |52.436MiB|52.436MiB|0B| 0.0%|
|00035.smt2                                                                                  |52.516MiB|52.516MiB|0B| 0.0%|
|00085.smt2                                                                                  |52.42MiB|52.42MiB|0B| 0.0%|
|00102.smt2                                                                                  |52.488MiB|52.488MiB|0B| 0.0%|
|00104.smt2                                                                                  |52.792MiB|52.792MiB|0B| 0.0%|
|00105.smt2                                                                                  |52.684MiB|52.684MiB|0B| 0.0%|
|00149.smt2                                                                                  |52.44MiB|52.44MiB|0B| 0.0%|
|00194.smt2                                                                                  |52.56MiB|52.56MiB|0B| 0.0%|
|00235.smt2                                                                                  |52.436MiB|52.436MiB|0B| 0.0%|
|00243.smt2                                                                                  |52.42MiB|52.42MiB|0B| 0.0%|
|00247.smt2                                                                                  |52.304MiB|52.304MiB|0B| 0.0%|
|00249.smt2                                                                                  |52.56MiB|52.56MiB|0B| 0.0%|
|00251.smt2                                                                                  |52.364MiB|52.364MiB|0B| 0.0%|
|00294.smt2                                                                                  |52.46MiB|52.46MiB|0B| 0.0%|
|00304.smt2                                                                                  |54.796MiB|54.796MiB|0B| 0.0%|
|00314.smt2                                                                                  |53.612MiB|53.612MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |52.552MiB|52.552MiB|0B| 0.0%|
|00003.smt2                                                                                  |52.352MiB|52.352MiB|0B| 0.0%|
|00005.smt2                                                                                  |52.412MiB|52.412MiB|0B| 0.0%|
|00018.smt2                                                                                  |54.24MiB|54.24MiB|0B| 0.0%|
|00020.smt2                                                                                  |52.436MiB|52.436MiB|0B| 0.0%|
|00035.smt2                                                                                  |52.516MiB|52.516MiB|0B| 0.0%|
|00085.smt2                                                                                  |52.42MiB|52.42MiB|0B| 0.0%|
|00102.smt2                                                                                  |52.488MiB|52.488MiB|0B| 0.0%|
|00104.smt2                                                                                  |52.792MiB|52.792MiB|0B| 0.0%|
|00105.smt2                                                                                  |52.684MiB|52.684MiB|0B| 0.0%|
|00149.smt2                                                                                  |52.44MiB|52.44MiB|0B| 0.0%|
|00194.smt2                                                                                  |52.56MiB|52.56MiB|0B| 0.0%|
|00235.smt2                                                                                  |52.436MiB|52.436MiB|0B| 0.0%|
|00243.smt2                                                                                  |52.42MiB|52.42MiB|0B| 0.0%|
|00247.smt2                                                                                  |52.304MiB|52.304MiB|0B| 0.0%|
|00249.smt2                                                                                  |52.56MiB|52.56MiB|0B| 0.0%|
|00251.smt2                                                                                  |52.364MiB|52.364MiB|0B| 0.0%|
|00294.smt2                                                                                  |52.46MiB|52.46MiB|0B| 0.0%|
|00304.smt2                                                                                  |54.796MiB|54.796MiB|0B| 0.0%|
|00314.smt2                                                                                  |53.612MiB|53.612MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |52.552MiB|52.552MiB|0B| 0.0%|
|00003.smt2                                                                                  |52.352MiB|52.352MiB|0B| 0.0%|
|00005.smt2                                                                                  |52.412MiB|52.412MiB|0B| 0.0%|
|00018.smt2                                                                                  |54.24MiB|54.24MiB|0B| 0.0%|
|00020.smt2                                                                                  |52.436MiB|52.436MiB|0B| 0.0%|
|00035.smt2                                                                                  |52.516MiB|52.516MiB|0B| 0.0%|
|00085.smt2                                                                                  |52.42MiB|52.42MiB|0B| 0.0%|
|00102.smt2                                                                                  |52.488MiB|52.488MiB|0B| 0.0%|
|00104.smt2                                                                                  |52.792MiB|52.792MiB|0B| 0.0%|
|00105.smt2                                                                                  |52.684MiB|52.684MiB|0B| 0.0%|
|00149.smt2                                                                                  |52.44MiB|52.44MiB|0B| 0.0%|
|00194.smt2                                                                                  |52.56MiB|52.56MiB|0B| 0.0%|
|00235.smt2                                                                                  |52.436MiB|52.436MiB|0B| 0.0%|
|00243.smt2                                                                                  |52.42MiB|52.42MiB|0B| 0.0%|
|00247.smt2                                                                                  |52.304MiB|52.304MiB|0B| 0.0%|
|00249.smt2                                                                                  |52.56MiB|52.56MiB|0B| 0.0%|
|00251.smt2                                                                                  |52.364MiB|52.364MiB|0B| 0.0%|
|00294.smt2                                                                                  |52.46MiB|52.46MiB|0B| 0.0%|
|00304.smt2                                                                                  |54.796MiB|54.796MiB|0B| 0.0%|
|00314.smt2                                                                                  |53.612MiB|53.612MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |52.552MiB|52.552MiB|0B| 0.0%|
|00003.smt2                                                                                  |52.352MiB|52.352MiB|0B| 0.0%|
|00005.smt2                                                                                  |52.412MiB|52.412MiB|0B| 0.0%|
|00018.smt2                                                                                  |54.24MiB|54.24MiB|0B| 0.0%|
|00020.smt2                                                                                  |52.436MiB|52.436MiB|0B| 0.0%|
|00035.smt2                                                                                  |52.516MiB|52.516MiB|0B| 0.0%|
|00085.smt2                                                                                  |52.42MiB|52.42MiB|0B| 0.0%|
|00102.smt2                                                                                  |52.488MiB|52.488MiB|0B| 0.0%|
|00104.smt2                                                                                  |52.792MiB|52.792MiB|0B| 0.0%|
|00105.smt2                                                                                  |52.684MiB|52.684MiB|0B| 0.0%|
|00149.smt2                                                                                  |52.44MiB|52.44MiB|0B| 0.0%|
|00194.smt2                                                                                  |52.56MiB|52.56MiB|0B| 0.0%|
|00235.smt2                                                                                  |52.436MiB|52.436MiB|0B| 0.0%|
|00243.smt2                                                                                  |52.42MiB|52.42MiB|0B| 0.0%|
|00247.smt2                                                                                  |52.304MiB|52.304MiB|0B| 0.0%|
|00249.smt2                                                                                  |52.56MiB|52.56MiB|0B| 0.0%|
|00251.smt2                                                                                  |52.364MiB|52.364MiB|0B| 0.0%|
|00294.smt2                                                                                  |52.46MiB|52.46MiB|0B| 0.0%|
|00304.smt2                                                                                  |54.796MiB|54.796MiB|0B| 0.0%|
|00314.smt2                                                                                  |53.612MiB|53.612MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|00793.smt2                                                                                 |   0.091s |58.344MiB|
|00379.smt2                                                                                 |   0.084s |55.04MiB|
|00304.smt2                                                                                 |   0.031s |54.796MiB|
|00018.smt2                                                                                 |   0.048s |54.24MiB|
|qf_Select_741_values_0.smt2                                                                |   0.299s |54.084MiB|
|int_check_bvsgt_bvashr0_ltr_inv_g.smt2                                                     |   0.117s |54.068MiB|
|qf_Select_740_values_0.smt2                                                                |   0.394s |54.044MiB|
|int_check_bvugt_bvshl0_rtl.smt2                                                            |   0.177s |54.044MiB|
|int_check_bvslt_bvmul_rtl.smt2                                                             |   0.086s |54.024MiB|
|qf_Select_746_values_0.smt2                                                                |   0.204s |54.008MiB|
|int_check_bvule_bvashr0_ltr_inv_g.smt2                                                     |   0.194s |54.0MiB|
|int_check_bvslt_bvlshr1_ltr_inv_g.smt2                                                     |   0.127s |53.948MiB|
|int_check_bvsgt_bvurem1_ltr_inv_g.smt2                                                     |   0.061s |53.908MiB|
|int_check_bvslt_bvashr1_ltr_inv_g.smt2                                                     |   0.258s |53.844MiB|
|int_check_bvsge_bvurem1_rtl.smt2                                                           |   0.312s |53.836MiB|
|int_check_bvsge_bvashr0_ltr_inv_g.smt2                                                     |   0.095s |53.828MiB|
|int_check_bvsge_bvlshr1_rtl.smt2                                                           |   0.217s |53.812MiB|
|int_check_bvslt_bvshl0_rtl.smt2                                                            |   0.105s |53.8MiB|
|int_check_bvsle_bvudiv0_ltr_inv_g.smt2                                                     |   0.153s |53.784MiB|
|int_check_bvsgt_bvudiv1_rtl.smt2                                                           |   0.125s |53.784MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|00793.smt2                                                                                 |   0.091s |58.344MiB|
|00379.smt2                                                                                 |   0.084s |55.04MiB|
|00304.smt2                                                                                 |   0.031s |54.796MiB|
|00018.smt2                                                                                 |   0.048s |54.24MiB|
|qf_Select_741_values_0.smt2                                                                |   0.299s |54.084MiB|
|int_check_bvsgt_bvashr0_ltr_inv_g.smt2                                                     |   0.117s |54.068MiB|
|qf_Select_740_values_0.smt2                                                                |   0.394s |54.044MiB|
|int_check_bvugt_bvshl0_rtl.smt2                                                            |   0.177s |54.044MiB|
|int_check_bvslt_bvmul_rtl.smt2                                                             |   0.086s |54.024MiB|
|qf_Select_746_values_0.smt2                                                                |   0.204s |54.008MiB|
|int_check_bvule_bvashr0_ltr_inv_g.smt2                                                     |   0.194s |54.0MiB|
|int_check_bvslt_bvlshr1_ltr_inv_g.smt2                                                     |   0.127s |53.948MiB|
|int_check_bvsgt_bvurem1_ltr_inv_g.smt2                                                     |   0.061s |53.908MiB|
|int_check_bvslt_bvashr1_ltr_inv_g.smt2                                                     |   0.258s |53.844MiB|
|int_check_bvsge_bvurem1_rtl.smt2                                                           |   0.312s |53.836MiB|
|int_check_bvsge_bvashr0_ltr_inv_g.smt2                                                     |   0.095s |53.828MiB|
|int_check_bvsge_bvlshr1_rtl.smt2                                                           |   0.217s |53.812MiB|
|int_check_bvslt_bvshl0_rtl.smt2                                                            |   0.105s |53.8MiB|
|int_check_bvsle_bvudiv0_ltr_inv_g.smt2                                                     |   0.153s |53.784MiB|
|int_check_bvsgt_bvudiv1_rtl.smt2                                                           |   0.125s |53.784MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|00005.smt2                                                                                  |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|00018.smt2                                                                                  |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|00035.smt2                                                                                  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|00149.smt2                                                                                  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|00304.smt2                                                                                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|00324.smt2                                                                                  |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|00402.smt2                                                                                  |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|00413.smt2                                                                                  |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|00415.smt2                                                                                  |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|00428.smt2                                                                                  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|00793.smt2                                                                                  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|00967.smt2                                                                                  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|01052.smt2                                                                                  |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|int_check_bvsge_bvadd_ltr_inv_r.smt2                                                        |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|int_check_bvsge_bvand_ltr_inv_g.smt2                                                        |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|int_check_bvsge_bvand_rtl.smt2                                                              |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|int_check_bvsge_bvashr0_ltr_inv_g.smt2                                                      |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|int_check_bvsge_bvashr0_rtl.smt2                                                            |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|int_check_bvsge_bvashr1_ltr_inv_g.smt2                                                      |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|int_check_bvsge_bvlshr0_ltr_inv_r.smt2                                                      |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|int_check_bvsge_bvlshr1_rtl.smt2                                                            |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|int_check_bvsge_bvmul_rtl.smt2                                                              |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|int_check_bvsge_bvnot_ltr_inv_g.smt2                                                        |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|int_check_bvsge_bvor_ltr_inv_g.smt2                                                         |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|int_check_bvsge_bvor_rtl.smt2                                                               |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|int_check_bvsge_bvshl0_rtl.smt2                                                             |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|int_check_bvsge_bvudiv0_rtl.smt2                                                            |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|int_check_bvsge_bvurem0_ltr_inv_g.smt2                                                      |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|int_check_bvsge_bvurem0_rtl.smt2                                                            |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|int_check_bvsge_bvurem1_rtl.smt2                                                            |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvadd_ltr_inv_g.smt2                                                        |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvadd_ltr_inv_r.smt2                                                        |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvand_ltr_inv_g.smt2                                                        |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvand_rtl.smt2                                                              |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvashr0_ltr_inv_g.smt2                                                      |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvashr1_rtl.smt2                                                            |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvlshr0_ltr_inv_r.smt2                                                      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvmul_rtl.smt2                                                              |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvneg_ltr_inv_g.smt2                                                        |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvneg_rtl.smt2                                                              |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvnot_ltr_inv_g.smt2                                                        |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvnot_rtl.smt2                                                              |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvor_ltr_inv_g.smt2                                                         |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvor_rtl.smt2                                                               |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvudiv0_rtl.smt2                                                            |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvudiv1_rtl.smt2                                                            |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvurem0_ltr_inv_g.smt2                                                      |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvurem1_ltr_inv_g.smt2                                                      |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|int_check_bvsle_bvadd_ltr_inv_r.smt2                                                        |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|int_check_bvsle_bvand_ltr_inv_g.smt2                                                        |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|int_check_bvsle_bvand_rtl.smt2                                                              |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|int_check_bvsle_bvashr1_ltr_inv_g.smt2                                                      |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|int_check_bvsle_bvlshr0_rtl.smt2                                                            |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|int_check_bvsle_bvlshr1_ltr_inv_g.smt2                                                      |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|int_check_bvsle_bvlshr1_rtl.smt2                                                            |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|int_check_bvsle_bvneg_ltr_inv_g.smt2                                                        |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|int_check_bvsle_bvnot_ltr_inv_g.smt2                                                        |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|int_check_bvsle_bvor_ltr_inv_g.smt2                                                         |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|int_check_bvsle_bvor_rtl.smt2                                                               |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|int_check_bvsle_bvshl0_rtl.smt2                                                             |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|int_check_bvsle_bvshl1_rtl.smt2                                                             |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|int_check_bvsle_bvudiv0_ltr_inv_g.smt2                                                      |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|int_check_bvsle_bvudiv1_rtl.smt2                                                            |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|int_check_bvsle_bvurem0_ltr_inv_g.smt2                                                      |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|int_check_bvsle_bvurem0_rtl.smt2                                                            |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|int_check_bvsle_bvurem1_ltr_inv_r.smt2                                                      |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|int_check_bvsle_bvurem1_rtl.smt2                                                            |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|int_check_bvslt_bvadd_ltr_inv_g.smt2                                                        |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|int_check_bvslt_bvadd_ltr_inv_r.smt2                                                        |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|int_check_bvslt_bvadd_rtl.smt2                                                              |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|int_check_bvslt_bvand_ltr_inv_g.smt2                                                        |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|int_check_bvslt_bvand_rtl.smt2                                                              |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|int_check_bvslt_bvashr1_ltr_inv_g.smt2                                                      |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|int_check_bvslt_bvlshr1_ltr_inv_g.smt2                                                      |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|int_check_bvslt_bvlshr1_rtl.smt2                                                            |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|int_check_bvslt_bvmul_rtl.smt2                                                              |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|int_check_bvslt_bvneg_ltr_inv_g.smt2                                                        |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|int_check_bvslt_bvneg_rtl.smt2                                                              |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|int_check_bvslt_bvnot_ltr_inv_g.smt2                                                        |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|int_check_bvslt_bvnot_rtl.smt2                                                              |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|int_check_bvslt_bvor_ltr_inv_g.smt2                                                         |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|int_check_bvslt_bvor_rtl.smt2                                                               |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|int_check_bvslt_bvshl0_rtl.smt2                                                             |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|int_check_bvslt_bvshl1_rtl.smt2                                                             |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|int_check_bvslt_bvudiv0_rtl.smt2                                                            |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|int_check_bvslt_bvudiv1_rtl.smt2                                                            |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|int_check_bvslt_bvurem0_ltr_inv_r.smt2                                                      |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|int_check_bvslt_bvurem0_rtl.smt2                                                            |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|int_check_bvslt_bvurem1_ltr_inv_g.smt2                                                      |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|int_check_bvslt_bvurem1_rtl.smt2                                                            |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|int_check_bvuge_bvand_ltr_inv_g.smt2                                                        |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|int_check_bvuge_bvand_rtl.smt2                                                              |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|int_check_bvuge_bvashr0_ltr_inv_g.smt2                                                      |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|int_check_bvuge_bvlshr0_ltr_inv_g.smt2                                                      |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|int_check_bvuge_bvlshr0_rtl.smt2                                                            |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|int_check_bvuge_bvlshr1_rtl.smt2                                                            |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|int_check_bvuge_bvmul_rtl.smt2                                                              |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|int_check_bvuge_bvor_ltr_inv_g.smt2                                                         |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|int_check_bvuge_bvudiv0_rtl.smt2                                                            |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|int_check_bvuge_bvurem1_ltr_inv_g.smt2                                                      |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|int_check_bvuge_bvurem1_rtl.smt2                                                            |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|int_check_bvugt_bvand_ltr_inv_g.smt2                                                        |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|int_check_bvugt_bvand_rtl.smt2                                                              |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|int_check_bvugt_bvlshr0_rtl.smt2                                                            |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|int_check_bvugt_bvlshr1_rtl.smt2                                                            |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|int_check_bvugt_bvmul_rtl.smt2                                                              |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|int_check_bvugt_bvor_ltr_inv_g.smt2                                                         |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|int_check_bvugt_bvor_rtl.smt2                                                               |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|int_check_bvugt_bvshl0_rtl.smt2                                                             |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|int_check_bvule_bvand_ltr_inv_g.smt2                                                        |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|int_check_bvule_bvashr0_ltr_inv_g.smt2                                                      |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|int_check_bvule_bvashr1_ltr_inv_g.smt2                                                      |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|int_check_bvule_bvashr1_rtl.smt2                                                            |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|int_check_bvule_bvlshr0_ltr_inv_g.smt2                                                      |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|int_check_bvule_bvlshr1_ltr_inv_g.smt2                                                      |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|int_check_bvule_bvor_ltr_inv_g.smt2                                                         |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|int_check_bvule_bvor_rtl.smt2                                                               |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|int_check_bvule_bvshl1_ltr_inv_g.smt2                                                       |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|int_check_bvule_bvudiv0_ltr_inv_g.smt2                                                      |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|int_check_bvule_bvudiv0_rtl.smt2                                                            |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|int_check_bvule_bvudiv1_rtl.smt2                                                            |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|int_check_bvult_bvand_ltr_inv_g.smt2                                                        |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|int_check_bvult_bvand_rtl.smt2                                                              |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|int_check_bvult_bvashr0_ltr_inv_g.smt2                                                      |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|int_check_bvult_bvashr1_ltr_inv_g.smt2                                                      |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|int_check_bvult_bvlshr0_ltr_inv_g.smt2                                                      |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|int_check_bvult_bvlshr1_ltr_inv_g.smt2                                                      |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|int_check_bvult_bvor_ltr_inv_g.smt2                                                         |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|int_check_bvult_bvor_rtl.smt2                                                               |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|int_check_bvult_bvshl1_ltr_inv_g.smt2                                                       |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|int_check_bvult_bvudiv1_ltr_inv_g.smt2                                                      |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|int_check_bvult_bvudiv1_rtl.smt2                                                            |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|int_check_eq_bvand_rtl.smt2                                                                 |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|int_check_eq_bvmul_rtl.smt2                                                                 |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|int_check_eq_bvor_rtl.smt2                                                                  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|int_check_eq_bvshl0_rtl.smt2                                                                |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|int_check_eq_bvurem1_ltr_inv_g.smt2                                                         |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|int_check_eq_bvurem1_rtl.smt2                                                               |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|int_check_ne_bvadd_ltr_inv_g.smt2                                                           |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|int_check_ne_bvadd_ltr_inv_r.smt2                                                           |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|int_check_ne_bvand_ltr_inv_g.smt2                                                           |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|int_check_ne_bvand_rtl.smt2                                                                 |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|int_check_ne_bvashr1_ltr_inv_r.smt2                                                         |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|int_check_ne_bvashr1_rtl.smt2                                                               |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|int_check_ne_bvlshr0_ltr_inv_g.smt2                                                         |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|int_check_ne_bvlshr0_rtl.smt2                                                               |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|int_check_ne_bvlshr1_ltr_inv_g.smt2                                                         |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|int_check_ne_bvlshr1_rtl.smt2                                                               |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|int_check_ne_bvneg_ltr_inv_g.smt2                                                           |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|int_check_ne_bvnot_ltr_inv_g.smt2                                                           |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|int_check_ne_bvor_ltr_inv_g.smt2                                                            |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|int_check_ne_bvor_rtl.smt2                                                                  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|int_check_ne_bvshl0_rtl.smt2                                                                |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|int_check_ne_bvshl1_ltr_inv_g.smt2                                                          |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|int_check_ne_bvudiv0_ltr_inv_g.smt2                                                         |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|int_check_ne_bvurem0_ltr_inv_g.smt2                                                         |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|n0-00001.smt2                                                                               |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|qf_AddSub_1040_values_0.smt2                                                                |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|qf_AddSub_1043_values_0.smt2                                                                |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|qf_AddSub_1202_values_0.smt2                                                                |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|qf_AddSub_1295_values_0.smt2                                                                |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|qf_AddSub_1560_values_0.smt2                                                                |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|qf_AddSub_1564_values_0.smt2                                                                |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|qf_AddSub_1599_values_0.smt2                                                                |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|qf_AddSub_1604_values_0.smt2                                                                |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|qf_AddSub_1624_values_0.smt2                                                                |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|qf_AndOrXor_1012_values_0.smt2                                                              |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|qf_AndOrXor_1230_values_0.smt2                                                              |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|qf_AndOrXor_1241_values_0.smt2                                                              |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|qf_AndOrXor_1247_values_0.smt2                                                              |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|qf_AndOrXor_1253_values_0.smt2                                                              |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_AndOrXor_1280_values_0.smt2                                                              |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|qf_AndOrXor_1288_values_0.smt2                                                              |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|qf_AndOrXor_1294_values_0.smt2                                                              |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|qf_AndOrXor_135_values_0.smt2                                                               |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|qf_AndOrXor_144_values_0.smt2                                                               |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|qf_AndOrXor_151_values_0.smt2                                                               |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|qf_AndOrXor_1733_values_0.smt2                                                              |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|qf_AndOrXor_1795_values_0.smt2                                                              |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|qf_AndOrXor_1864_values_0.smt2                                                              |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|qf_AndOrXor_1979_values_0.smt2                                                              |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|qf_AndOrXor_2008_values_0.smt2                                                              |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|qf_AndOrXor_2052_values_0.smt2                                                              |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|qf_AndOrXor_2063_values_0.smt2                                                              |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|qf_AndOrXor_2113_values_0.smt2                                                              |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|qf_AndOrXor_2118_values_0.smt2                                                              |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|qf_AndOrXor_2123_values_0.smt2                                                              |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|qf_AndOrXor_2160_values_0.smt2                                                              |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|qf_AndOrXor_2188_values_0.smt2                                                              |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|qf_AndOrXor_2231_values_0.smt2                                                              |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|qf_AndOrXor_2243_values_0.smt2                                                              |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|qf_AndOrXor_2247_values_0.smt2                                                              |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|qf_AndOrXor_2263_values_0.smt2                                                              |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|qf_AndOrXor_2264_values_0.smt2                                                              |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|qf_AndOrXor_2265_values_0.smt2                                                              |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|qf_AndOrXor_2284_values_0.smt2                                                              |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|qf_AndOrXor_2285_values_0.smt2                                                              |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|qf_AndOrXor_2297_values_0.smt2                                                              |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|qf_AndOrXor_2367_values_0.smt2                                                              |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|qf_AndOrXor_2416_values_0.smt2                                                              |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|qf_AndOrXor_2417_values_0.smt2                                                              |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|qf_AndOrXor_2429_values_0.smt2                                                              |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|qf_AndOrXor_2430_values_0.smt2                                                              |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|qf_AndOrXor_2475_values_0.smt2                                                              |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|qf_AndOrXor_2486_values_0.smt2                                                              |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|qf_AndOrXor_2515_values_0.smt2                                                              |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|qf_AndOrXor_2581_values_0.smt2                                                              |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|qf_AndOrXor_2587_values_0.smt2                                                              |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|qf_AndOrXor_2595_values_0.smt2                                                              |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|qf_AndOrXor_2607_values_0.smt2                                                              |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|qf_AndOrXor_2617_values_0.smt2                                                              |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|qf_AndOrXor_2627_values_0.smt2                                                              |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|qf_AndOrXor_2647_values_0.smt2                                                              |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|qf_AndOrXor_2658_values_0.smt2                                                              |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|qf_AndOrXor_273_values_7.smt2                                                               |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|qf_AndOrXor_280_values_3.smt2                                                               |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|qf_AndOrXor_298_values_0.smt2                                                               |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|qf_AndOrXor_363_values_0.smt2                                                               |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|qf_AndOrXor_364_values_0.smt2                                                               |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|qf_AndOrXor_516_values_0.smt2                                                               |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|qf_AndOrXor_523_values_0.smt2                                                               |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|qf_AndOrXor_530_values_0.smt2                                                               |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|qf_AndOrXor_537_values_0.smt2                                                               |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|qf_AndOrXor_698_values_0.smt2                                                               |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|qf_AndOrXor_709_values_0.smt2                                                               |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|qf_AndOrXor_716_values_0.smt2                                                               |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|qf_AndOrXor_732-1_values_0.smt2                                                             |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|qf_AndOrXor_732-2_values_0.smt2                                                             |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|qf_AndOrXor_745_values_0.smt2                                                               |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|qf_AndOrXor_757_values_0.smt2                                                               |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|qf_AndOrXor_819_values_0.smt2                                                               |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|qf_AndOrXor_827_values_0.smt2                                                               |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|qf_AndOrXor_937_values_0.smt2                                                               |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|qf_InstCombineShift239_values_0.smt2                                                        |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|qf_InstCombineShift279_values_0.smt2                                                        |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|qf_InstCombineShift440_values_0.smt2                                                        |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|qf_InstCombineShift476_values_0.smt2                                                        |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|qf_Select_420_values_0.smt2                                                                 |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|qf_Select_423_values_57.smt2                                                                |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_Select_427_values_0.smt2                                                                 |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|qf_Select_430_values_60.smt2                                                                |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|qf_Select_433_values_0.smt2                                                                 |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|qf_Select_576a_values_0.smt2                                                                |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|qf_Select_576b_values_0.smt2                                                                |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|qf_Select_704_values_0.smt2                                                                 |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|qf_Select_740_values_0.smt2                                                                 |   0.394s  |   0.394s  |   0.000s  | 0.0%|
|qf_Select_741_values_0.smt2                                                                 |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|qf_Select_746_values_0.smt2                                                                 |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|qf_Select_747_values_0.smt2                                                                 |   0.024s  |   0.024s  |   0.000s  | 0.0%|
</details>
