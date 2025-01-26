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
Z3 commit: 04d0e9492b0066675c75fc5fb1df6b23b79607e5
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" smt.sls.enable=true smt.sls.parallel=false model_validate=true sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_UFNIA_SAT
Z3 commit message: set log level of revert repair down to 3

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-clausal-lookahead-60-qfufnia-sat
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 04d0e9492b0066675c75fc5fb1df6b23b79607e5
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" smt.sls.enable=true smt.sls.parallel=false model_validate=true sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_UFNIA_SAT
Z3 commit message: set log level of revert repair down to 3

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|00005.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00018.smt2                                                                                  |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|00035.smt2                                                                                  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|00149.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00304.smt2                                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.027s  |   0.027s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|00005.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00018.smt2                                                                                  |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|00035.smt2                                                                                  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|00149.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00304.smt2                                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.027s  |   0.027s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|00005.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00018.smt2                                                                                  |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|00035.smt2                                                                                  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|00149.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00304.smt2                                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.027s  |   0.027s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|00005.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00018.smt2                                                                                  |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|00035.smt2                                                                                  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|00149.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00304.smt2                                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.027s  |   0.027s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|int_check_bvuge_bvlshr0_rtl.smt2                                                           |  60.000s |53.328MiB|
|int_check_ne_bvshl1_ltr_inv_g.smt2                                                         |  59.998s |53.012MiB|
|int_check_ne_bvlshr1_ltr_inv_g.smt2                                                        |  59.997s |53.148MiB|
|int_check_ne_bvashr1_rtl.smt2                                                              |  59.996s |53.464MiB|
|int_check_ne_bvudiv0_ltr_inv_g.smt2                                                        |  59.993s |53.448MiB|
|int_check_bvsge_bvurem1_rtl.smt2                                                           |   0.918s |55.124MiB|
|int_check_ne_bvashr1_ltr_inv_r.smt2                                                        |   0.577s |54.432MiB|
|qf_AddSub_1604_values_0.smt2                                                               |   0.511s |54.828MiB|
|int_check_bvslt_bvashr1_ltr_inv_g.smt2                                                     |   0.496s |54.52MiB|
|int_check_bvsge_bvashr0_rtl.smt2                                                           |   0.463s |55.508MiB|
|int_check_eq_bvshl0_rtl.smt2                                                               |   0.404s |54.036MiB|
|qf_Select_740_values_0.smt2                                                                |   0.364s |54.188MiB|
|int_check_bvsle_bvashr1_ltr_inv_g.smt2                                                     |   0.359s |54.072MiB|
|qf_Select_741_values_0.smt2                                                                |   0.352s |54.06MiB|
|int_check_bvslt_bvmul_rtl.smt2                                                             |   0.275s |54.716MiB|
|qf_Select_746_values_0.smt2                                                                |   0.268s |53.984MiB|
|qf_Select_747_values_0.smt2                                                                |   0.246s |53.844MiB|
|int_check_bvsgt_bvashr0_ltr_inv_g.smt2                                                     |   0.186s |54.256MiB|
|int_check_bvule_bvashr0_ltr_inv_g.smt2                                                     |   0.183s |54.112MiB|
|int_check_bvugt_bvshl0_rtl.smt2                                                            |   0.178s |53.824MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|int_check_bvuge_bvlshr0_rtl.smt2                                                           |  60.000s |53.328MiB|
|int_check_ne_bvshl1_ltr_inv_g.smt2                                                         |  59.998s |53.012MiB|
|int_check_ne_bvlshr1_ltr_inv_g.smt2                                                        |  59.997s |53.148MiB|
|int_check_ne_bvashr1_rtl.smt2                                                              |  59.996s |53.464MiB|
|int_check_ne_bvudiv0_ltr_inv_g.smt2                                                        |  59.993s |53.448MiB|
|int_check_bvsge_bvurem1_rtl.smt2                                                           |   0.918s |55.124MiB|
|int_check_ne_bvashr1_ltr_inv_r.smt2                                                        |   0.577s |54.432MiB|
|qf_AddSub_1604_values_0.smt2                                                               |   0.511s |54.828MiB|
|int_check_bvslt_bvashr1_ltr_inv_g.smt2                                                     |   0.496s |54.52MiB|
|int_check_bvsge_bvashr0_rtl.smt2                                                           |   0.463s |55.508MiB|
|int_check_eq_bvshl0_rtl.smt2                                                               |   0.404s |54.036MiB|
|qf_Select_740_values_0.smt2                                                                |   0.364s |54.188MiB|
|int_check_bvsle_bvashr1_ltr_inv_g.smt2                                                     |   0.359s |54.072MiB|
|qf_Select_741_values_0.smt2                                                                |   0.352s |54.06MiB|
|int_check_bvslt_bvmul_rtl.smt2                                                             |   0.275s |54.716MiB|
|qf_Select_746_values_0.smt2                                                                |   0.268s |53.984MiB|
|qf_Select_747_values_0.smt2                                                                |   0.246s |53.844MiB|
|int_check_bvsgt_bvashr0_ltr_inv_g.smt2                                                     |   0.186s |54.256MiB|
|int_check_bvule_bvashr0_ltr_inv_g.smt2                                                     |   0.183s |54.112MiB|
|int_check_bvugt_bvshl0_rtl.smt2                                                            |   0.178s |53.824MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |52.64MiB|52.64MiB|0B| 0.0%|
|00003.smt2                                                                                  |52.284MiB|52.284MiB|0B| 0.0%|
|00005.smt2                                                                                  |52.404MiB|52.404MiB|0B| 0.0%|
|00018.smt2                                                                                  |54.26MiB|54.26MiB|0B| 0.0%|
|00020.smt2                                                                                  |52.448MiB|52.448MiB|0B| 0.0%|
|00035.smt2                                                                                  |52.48MiB|52.48MiB|0B| 0.0%|
|00085.smt2                                                                                  |52.264MiB|52.264MiB|0B| 0.0%|
|00102.smt2                                                                                  |52.556MiB|52.556MiB|0B| 0.0%|
|00104.smt2                                                                                  |52.576MiB|52.576MiB|0B| 0.0%|
|00105.smt2                                                                                  |52.816MiB|52.816MiB|0B| 0.0%|
|00149.smt2                                                                                  |52.56MiB|52.56MiB|0B| 0.0%|
|00194.smt2                                                                                  |52.404MiB|52.404MiB|0B| 0.0%|
|00235.smt2                                                                                  |52.232MiB|52.232MiB|0B| 0.0%|
|00243.smt2                                                                                  |52.308MiB|52.308MiB|0B| 0.0%|
|00247.smt2                                                                                  |52.252MiB|52.252MiB|0B| 0.0%|
|00249.smt2                                                                                  |52.56MiB|52.56MiB|0B| 0.0%|
|00251.smt2                                                                                  |52.468MiB|52.468MiB|0B| 0.0%|
|00294.smt2                                                                                  |52.364MiB|52.364MiB|0B| 0.0%|
|00304.smt2                                                                                  |54.608MiB|54.608MiB|0B| 0.0%|
|00314.smt2                                                                                  |53.58MiB|53.58MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |52.64MiB|52.64MiB|0B| 0.0%|
|00003.smt2                                                                                  |52.284MiB|52.284MiB|0B| 0.0%|
|00005.smt2                                                                                  |52.404MiB|52.404MiB|0B| 0.0%|
|00018.smt2                                                                                  |54.26MiB|54.26MiB|0B| 0.0%|
|00020.smt2                                                                                  |52.448MiB|52.448MiB|0B| 0.0%|
|00035.smt2                                                                                  |52.48MiB|52.48MiB|0B| 0.0%|
|00085.smt2                                                                                  |52.264MiB|52.264MiB|0B| 0.0%|
|00102.smt2                                                                                  |52.556MiB|52.556MiB|0B| 0.0%|
|00104.smt2                                                                                  |52.576MiB|52.576MiB|0B| 0.0%|
|00105.smt2                                                                                  |52.816MiB|52.816MiB|0B| 0.0%|
|00149.smt2                                                                                  |52.56MiB|52.56MiB|0B| 0.0%|
|00194.smt2                                                                                  |52.404MiB|52.404MiB|0B| 0.0%|
|00235.smt2                                                                                  |52.232MiB|52.232MiB|0B| 0.0%|
|00243.smt2                                                                                  |52.308MiB|52.308MiB|0B| 0.0%|
|00247.smt2                                                                                  |52.252MiB|52.252MiB|0B| 0.0%|
|00249.smt2                                                                                  |52.56MiB|52.56MiB|0B| 0.0%|
|00251.smt2                                                                                  |52.468MiB|52.468MiB|0B| 0.0%|
|00294.smt2                                                                                  |52.364MiB|52.364MiB|0B| 0.0%|
|00304.smt2                                                                                  |54.608MiB|54.608MiB|0B| 0.0%|
|00314.smt2                                                                                  |53.58MiB|53.58MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |52.64MiB|52.64MiB|0B| 0.0%|
|00003.smt2                                                                                  |52.284MiB|52.284MiB|0B| 0.0%|
|00005.smt2                                                                                  |52.404MiB|52.404MiB|0B| 0.0%|
|00018.smt2                                                                                  |54.26MiB|54.26MiB|0B| 0.0%|
|00020.smt2                                                                                  |52.448MiB|52.448MiB|0B| 0.0%|
|00035.smt2                                                                                  |52.48MiB|52.48MiB|0B| 0.0%|
|00085.smt2                                                                                  |52.264MiB|52.264MiB|0B| 0.0%|
|00102.smt2                                                                                  |52.556MiB|52.556MiB|0B| 0.0%|
|00104.smt2                                                                                  |52.576MiB|52.576MiB|0B| 0.0%|
|00105.smt2                                                                                  |52.816MiB|52.816MiB|0B| 0.0%|
|00149.smt2                                                                                  |52.56MiB|52.56MiB|0B| 0.0%|
|00194.smt2                                                                                  |52.404MiB|52.404MiB|0B| 0.0%|
|00235.smt2                                                                                  |52.232MiB|52.232MiB|0B| 0.0%|
|00243.smt2                                                                                  |52.308MiB|52.308MiB|0B| 0.0%|
|00247.smt2                                                                                  |52.252MiB|52.252MiB|0B| 0.0%|
|00249.smt2                                                                                  |52.56MiB|52.56MiB|0B| 0.0%|
|00251.smt2                                                                                  |52.468MiB|52.468MiB|0B| 0.0%|
|00294.smt2                                                                                  |52.364MiB|52.364MiB|0B| 0.0%|
|00304.smt2                                                                                  |54.608MiB|54.608MiB|0B| 0.0%|
|00314.smt2                                                                                  |53.58MiB|53.58MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |52.64MiB|52.64MiB|0B| 0.0%|
|00003.smt2                                                                                  |52.284MiB|52.284MiB|0B| 0.0%|
|00005.smt2                                                                                  |52.404MiB|52.404MiB|0B| 0.0%|
|00018.smt2                                                                                  |54.26MiB|54.26MiB|0B| 0.0%|
|00020.smt2                                                                                  |52.448MiB|52.448MiB|0B| 0.0%|
|00035.smt2                                                                                  |52.48MiB|52.48MiB|0B| 0.0%|
|00085.smt2                                                                                  |52.264MiB|52.264MiB|0B| 0.0%|
|00102.smt2                                                                                  |52.556MiB|52.556MiB|0B| 0.0%|
|00104.smt2                                                                                  |52.576MiB|52.576MiB|0B| 0.0%|
|00105.smt2                                                                                  |52.816MiB|52.816MiB|0B| 0.0%|
|00149.smt2                                                                                  |52.56MiB|52.56MiB|0B| 0.0%|
|00194.smt2                                                                                  |52.404MiB|52.404MiB|0B| 0.0%|
|00235.smt2                                                                                  |52.232MiB|52.232MiB|0B| 0.0%|
|00243.smt2                                                                                  |52.308MiB|52.308MiB|0B| 0.0%|
|00247.smt2                                                                                  |52.252MiB|52.252MiB|0B| 0.0%|
|00249.smt2                                                                                  |52.56MiB|52.56MiB|0B| 0.0%|
|00251.smt2                                                                                  |52.468MiB|52.468MiB|0B| 0.0%|
|00294.smt2                                                                                  |52.364MiB|52.364MiB|0B| 0.0%|
|00304.smt2                                                                                  |54.608MiB|54.608MiB|0B| 0.0%|
|00314.smt2                                                                                  |53.58MiB|53.58MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|00793.smt2                                                                                 |   0.084s |58.26MiB|
|int_check_bvsge_bvashr0_rtl.smt2                                                           |   0.463s |55.508MiB|
|int_check_bvsge_bvurem1_rtl.smt2                                                           |   0.918s |55.124MiB|
|00379.smt2                                                                                 |   0.086s |55.068MiB|
|qf_AddSub_1604_values_0.smt2                                                               |   0.511s |54.828MiB|
|int_check_bvslt_bvmul_rtl.smt2                                                             |   0.275s |54.716MiB|
|00304.smt2                                                                                 |   0.033s |54.608MiB|
|int_check_bvslt_bvashr1_ltr_inv_g.smt2                                                     |   0.496s |54.52MiB|
|int_check_ne_bvashr1_ltr_inv_r.smt2                                                        |   0.577s |54.432MiB|
|00018.smt2                                                                                 |   0.040s |54.26MiB|
|int_check_bvsgt_bvashr0_ltr_inv_g.smt2                                                     |   0.186s |54.256MiB|
|qf_Select_740_values_0.smt2                                                                |   0.364s |54.188MiB|
|int_check_bvsge_bvashr0_ltr_inv_g.smt2                                                     |   0.117s |54.18MiB|
|int_check_bvule_bvashr0_ltr_inv_g.smt2                                                     |   0.183s |54.112MiB|
|int_check_bvsle_bvashr1_ltr_inv_g.smt2                                                     |   0.359s |54.072MiB|
|qf_Select_741_values_0.smt2                                                                |   0.352s |54.06MiB|
|int_check_eq_bvshl0_rtl.smt2                                                               |   0.404s |54.036MiB|
|int_check_bvuge_bvlshr0_ltr_inv_g.smt2                                                     |   0.112s |54.028MiB|
|int_check_bvsle_bvudiv0_ltr_inv_g.smt2                                                     |   0.161s |54.008MiB|
|qf_Select_746_values_0.smt2                                                                |   0.268s |53.984MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|00793.smt2                                                                                 |   0.084s |58.26MiB|
|int_check_bvsge_bvashr0_rtl.smt2                                                           |   0.463s |55.508MiB|
|int_check_bvsge_bvurem1_rtl.smt2                                                           |   0.918s |55.124MiB|
|00379.smt2                                                                                 |   0.086s |55.068MiB|
|qf_AddSub_1604_values_0.smt2                                                               |   0.511s |54.828MiB|
|int_check_bvslt_bvmul_rtl.smt2                                                             |   0.275s |54.716MiB|
|00304.smt2                                                                                 |   0.033s |54.608MiB|
|int_check_bvslt_bvashr1_ltr_inv_g.smt2                                                     |   0.496s |54.52MiB|
|int_check_ne_bvashr1_ltr_inv_r.smt2                                                        |   0.577s |54.432MiB|
|00018.smt2                                                                                 |   0.040s |54.26MiB|
|int_check_bvsgt_bvashr0_ltr_inv_g.smt2                                                     |   0.186s |54.256MiB|
|qf_Select_740_values_0.smt2                                                                |   0.364s |54.188MiB|
|int_check_bvsge_bvashr0_ltr_inv_g.smt2                                                     |   0.117s |54.18MiB|
|int_check_bvule_bvashr0_ltr_inv_g.smt2                                                     |   0.183s |54.112MiB|
|int_check_bvsle_bvashr1_ltr_inv_g.smt2                                                     |   0.359s |54.072MiB|
|qf_Select_741_values_0.smt2                                                                |   0.352s |54.06MiB|
|int_check_eq_bvshl0_rtl.smt2                                                               |   0.404s |54.036MiB|
|int_check_bvuge_bvlshr0_ltr_inv_g.smt2                                                     |   0.112s |54.028MiB|
|int_check_bvsle_bvudiv0_ltr_inv_g.smt2                                                     |   0.161s |54.008MiB|
|qf_Select_746_values_0.smt2                                                                |   0.268s |53.984MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00002.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|00005.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00018.smt2                                                                                  |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|00035.smt2                                                                                  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|00149.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|00304.smt2                                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|00324.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00402.smt2                                                                                  |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|00413.smt2                                                                                  |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|00415.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00428.smt2                                                                                  |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|00793.smt2                                                                                  |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|00967.smt2                                                                                  |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|01052.smt2                                                                                  |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|int_check_bvsge_bvadd_ltr_inv_r.smt2                                                        |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|int_check_bvsge_bvand_ltr_inv_g.smt2                                                        |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|int_check_bvsge_bvand_rtl.smt2                                                              |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|int_check_bvsge_bvashr0_ltr_inv_g.smt2                                                      |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|int_check_bvsge_bvashr0_rtl.smt2                                                            |   0.463s  |   0.463s  |   0.000s  | 0.0%|
|int_check_bvsge_bvashr1_ltr_inv_g.smt2                                                      |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|int_check_bvsge_bvlshr0_ltr_inv_r.smt2                                                      |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|int_check_bvsge_bvlshr1_rtl.smt2                                                            |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|int_check_bvsge_bvmul_rtl.smt2                                                              |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|int_check_bvsge_bvnot_ltr_inv_g.smt2                                                        |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|int_check_bvsge_bvor_ltr_inv_g.smt2                                                         |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|int_check_bvsge_bvor_rtl.smt2                                                               |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|int_check_bvsge_bvshl0_rtl.smt2                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|int_check_bvsge_bvudiv0_rtl.smt2                                                            |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|int_check_bvsge_bvurem0_ltr_inv_g.smt2                                                      |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|int_check_bvsge_bvurem0_rtl.smt2                                                            |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|int_check_bvsge_bvurem1_rtl.smt2                                                            |   0.918s  |   0.918s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvadd_ltr_inv_g.smt2                                                        |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvadd_ltr_inv_r.smt2                                                        |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvand_ltr_inv_g.smt2                                                        |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvand_rtl.smt2                                                              |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvashr0_ltr_inv_g.smt2                                                      |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvashr1_rtl.smt2                                                            |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvlshr0_ltr_inv_r.smt2                                                      |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvmul_rtl.smt2                                                              |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvneg_ltr_inv_g.smt2                                                        |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvneg_rtl.smt2                                                              |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvnot_ltr_inv_g.smt2                                                        |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvnot_rtl.smt2                                                              |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvor_ltr_inv_g.smt2                                                         |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvor_rtl.smt2                                                               |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvudiv0_rtl.smt2                                                            |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvudiv1_rtl.smt2                                                            |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvurem0_ltr_inv_g.smt2                                                      |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|int_check_bvsgt_bvurem1_ltr_inv_g.smt2                                                      |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|int_check_bvsle_bvadd_ltr_inv_r.smt2                                                        |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|int_check_bvsle_bvand_ltr_inv_g.smt2                                                        |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|int_check_bvsle_bvand_rtl.smt2                                                              |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|int_check_bvsle_bvashr1_ltr_inv_g.smt2                                                      |   0.359s  |   0.359s  |   0.000s  | 0.0%|
|int_check_bvsle_bvlshr0_rtl.smt2                                                            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|int_check_bvsle_bvlshr1_ltr_inv_g.smt2                                                      |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|int_check_bvsle_bvlshr1_rtl.smt2                                                            |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|int_check_bvsle_bvneg_ltr_inv_g.smt2                                                        |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|int_check_bvsle_bvnot_ltr_inv_g.smt2                                                        |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|int_check_bvsle_bvor_ltr_inv_g.smt2                                                         |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|int_check_bvsle_bvor_rtl.smt2                                                               |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|int_check_bvsle_bvshl0_rtl.smt2                                                             |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|int_check_bvsle_bvshl1_rtl.smt2                                                             |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|int_check_bvsle_bvudiv0_ltr_inv_g.smt2                                                      |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|int_check_bvsle_bvudiv1_rtl.smt2                                                            |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|int_check_bvsle_bvurem0_ltr_inv_g.smt2                                                      |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|int_check_bvsle_bvurem0_rtl.smt2                                                            |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|int_check_bvsle_bvurem1_ltr_inv_r.smt2                                                      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|int_check_bvsle_bvurem1_rtl.smt2                                                            |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|int_check_bvslt_bvadd_ltr_inv_g.smt2                                                        |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|int_check_bvslt_bvadd_ltr_inv_r.smt2                                                        |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|int_check_bvslt_bvadd_rtl.smt2                                                              |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|int_check_bvslt_bvand_ltr_inv_g.smt2                                                        |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|int_check_bvslt_bvand_rtl.smt2                                                              |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|int_check_bvslt_bvashr1_ltr_inv_g.smt2                                                      |   0.496s  |   0.496s  |   0.000s  | 0.0%|
|int_check_bvslt_bvlshr1_ltr_inv_g.smt2                                                      |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|int_check_bvslt_bvlshr1_rtl.smt2                                                            |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|int_check_bvslt_bvmul_rtl.smt2                                                              |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|int_check_bvslt_bvneg_ltr_inv_g.smt2                                                        |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|int_check_bvslt_bvneg_rtl.smt2                                                              |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|int_check_bvslt_bvnot_ltr_inv_g.smt2                                                        |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|int_check_bvslt_bvnot_rtl.smt2                                                              |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|int_check_bvslt_bvor_ltr_inv_g.smt2                                                         |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|int_check_bvslt_bvor_rtl.smt2                                                               |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|int_check_bvslt_bvshl0_rtl.smt2                                                             |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|int_check_bvslt_bvshl1_rtl.smt2                                                             |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|int_check_bvslt_bvudiv0_rtl.smt2                                                            |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|int_check_bvslt_bvudiv1_rtl.smt2                                                            |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|int_check_bvslt_bvurem0_ltr_inv_r.smt2                                                      |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|int_check_bvslt_bvurem0_rtl.smt2                                                            |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|int_check_bvslt_bvurem1_ltr_inv_g.smt2                                                      |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|int_check_bvslt_bvurem1_rtl.smt2                                                            |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|int_check_bvuge_bvand_ltr_inv_g.smt2                                                        |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|int_check_bvuge_bvand_rtl.smt2                                                              |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|int_check_bvuge_bvashr0_ltr_inv_g.smt2                                                      |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|int_check_bvuge_bvlshr0_ltr_inv_g.smt2                                                      |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|int_check_bvuge_bvlshr0_rtl.smt2                                                            |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|int_check_bvuge_bvlshr1_rtl.smt2                                                            |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|int_check_bvuge_bvmul_rtl.smt2                                                              |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|int_check_bvuge_bvor_ltr_inv_g.smt2                                                         |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|int_check_bvuge_bvudiv0_rtl.smt2                                                            |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|int_check_bvuge_bvurem1_ltr_inv_g.smt2                                                      |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|int_check_bvuge_bvurem1_rtl.smt2                                                            |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|int_check_bvugt_bvand_ltr_inv_g.smt2                                                        |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|int_check_bvugt_bvand_rtl.smt2                                                              |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|int_check_bvugt_bvlshr0_rtl.smt2                                                            |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|int_check_bvugt_bvlshr1_rtl.smt2                                                            |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|int_check_bvugt_bvmul_rtl.smt2                                                              |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|int_check_bvugt_bvor_ltr_inv_g.smt2                                                         |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|int_check_bvugt_bvor_rtl.smt2                                                               |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|int_check_bvugt_bvshl0_rtl.smt2                                                             |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|int_check_bvule_bvand_ltr_inv_g.smt2                                                        |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|int_check_bvule_bvashr0_ltr_inv_g.smt2                                                      |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|int_check_bvule_bvashr1_ltr_inv_g.smt2                                                      |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|int_check_bvule_bvashr1_rtl.smt2                                                            |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|int_check_bvule_bvlshr0_ltr_inv_g.smt2                                                      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|int_check_bvule_bvlshr1_ltr_inv_g.smt2                                                      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|int_check_bvule_bvor_ltr_inv_g.smt2                                                         |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|int_check_bvule_bvor_rtl.smt2                                                               |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|int_check_bvule_bvshl1_ltr_inv_g.smt2                                                       |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|int_check_bvule_bvudiv0_ltr_inv_g.smt2                                                      |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|int_check_bvule_bvudiv0_rtl.smt2                                                            |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|int_check_bvule_bvudiv1_rtl.smt2                                                            |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|int_check_bvult_bvand_ltr_inv_g.smt2                                                        |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|int_check_bvult_bvand_rtl.smt2                                                              |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|int_check_bvult_bvashr0_ltr_inv_g.smt2                                                      |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|int_check_bvult_bvashr1_ltr_inv_g.smt2                                                      |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|int_check_bvult_bvlshr0_ltr_inv_g.smt2                                                      |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|int_check_bvult_bvlshr1_ltr_inv_g.smt2                                                      |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|int_check_bvult_bvor_ltr_inv_g.smt2                                                         |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|int_check_bvult_bvor_rtl.smt2                                                               |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|int_check_bvult_bvshl1_ltr_inv_g.smt2                                                       |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|int_check_bvult_bvudiv1_ltr_inv_g.smt2                                                      |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|int_check_bvult_bvudiv1_rtl.smt2                                                            |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|int_check_eq_bvand_rtl.smt2                                                                 |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|int_check_eq_bvmul_rtl.smt2                                                                 |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|int_check_eq_bvor_rtl.smt2                                                                  |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|int_check_eq_bvshl0_rtl.smt2                                                                |   0.404s  |   0.404s  |   0.000s  | 0.0%|
|int_check_eq_bvurem1_ltr_inv_g.smt2                                                         |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|int_check_eq_bvurem1_rtl.smt2                                                               |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|int_check_ne_bvadd_ltr_inv_g.smt2                                                           |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|int_check_ne_bvadd_ltr_inv_r.smt2                                                           |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|int_check_ne_bvand_ltr_inv_g.smt2                                                           |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|int_check_ne_bvand_rtl.smt2                                                                 |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|int_check_ne_bvashr1_ltr_inv_r.smt2                                                         |   0.577s  |   0.577s  |   0.000s  | 0.0%|
|int_check_ne_bvashr1_rtl.smt2                                                               |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|int_check_ne_bvlshr0_ltr_inv_g.smt2                                                         |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|int_check_ne_bvlshr0_rtl.smt2                                                               |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|int_check_ne_bvlshr1_ltr_inv_g.smt2                                                         |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|int_check_ne_bvlshr1_rtl.smt2                                                               |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|int_check_ne_bvneg_ltr_inv_g.smt2                                                           |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|int_check_ne_bvnot_ltr_inv_g.smt2                                                           |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|int_check_ne_bvor_ltr_inv_g.smt2                                                            |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|int_check_ne_bvor_rtl.smt2                                                                  |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|int_check_ne_bvshl0_rtl.smt2                                                                |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|int_check_ne_bvshl1_ltr_inv_g.smt2                                                          |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|int_check_ne_bvudiv0_ltr_inv_g.smt2                                                         |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|int_check_ne_bvurem0_ltr_inv_g.smt2                                                         |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|n0-00001.smt2                                                                               |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|qf_AddSub_1040_values_0.smt2                                                                |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|qf_AddSub_1043_values_0.smt2                                                                |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|qf_AddSub_1202_values_0.smt2                                                                |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|qf_AddSub_1295_values_0.smt2                                                                |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|qf_AddSub_1560_values_0.smt2                                                                |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|qf_AddSub_1564_values_0.smt2                                                                |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|qf_AddSub_1599_values_0.smt2                                                                |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|qf_AddSub_1604_values_0.smt2                                                                |   0.511s  |   0.511s  |   0.000s  | 0.0%|
|qf_AddSub_1624_values_0.smt2                                                                |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|qf_AndOrXor_1012_values_0.smt2                                                              |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|qf_AndOrXor_1230_values_0.smt2                                                              |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|qf_AndOrXor_1241_values_0.smt2                                                              |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|qf_AndOrXor_1247_values_0.smt2                                                              |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|qf_AndOrXor_1253_values_0.smt2                                                              |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_AndOrXor_1280_values_0.smt2                                                              |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|qf_AndOrXor_1288_values_0.smt2                                                              |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|qf_AndOrXor_1294_values_0.smt2                                                              |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|qf_AndOrXor_135_values_0.smt2                                                               |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_AndOrXor_144_values_0.smt2                                                               |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|qf_AndOrXor_151_values_0.smt2                                                               |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|qf_AndOrXor_1733_values_0.smt2                                                              |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|qf_AndOrXor_1795_values_0.smt2                                                              |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_AndOrXor_1864_values_0.smt2                                                              |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|qf_AndOrXor_1979_values_0.smt2                                                              |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|qf_AndOrXor_2008_values_0.smt2                                                              |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|qf_AndOrXor_2052_values_0.smt2                                                              |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|qf_AndOrXor_2063_values_0.smt2                                                              |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|qf_AndOrXor_2113_values_0.smt2                                                              |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|qf_AndOrXor_2118_values_0.smt2                                                              |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|qf_AndOrXor_2123_values_0.smt2                                                              |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|qf_AndOrXor_2160_values_0.smt2                                                              |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|qf_AndOrXor_2188_values_0.smt2                                                              |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|qf_AndOrXor_2231_values_0.smt2                                                              |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_AndOrXor_2243_values_0.smt2                                                              |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|qf_AndOrXor_2247_values_0.smt2                                                              |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|qf_AndOrXor_2263_values_0.smt2                                                              |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|qf_AndOrXor_2264_values_0.smt2                                                              |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|qf_AndOrXor_2265_values_0.smt2                                                              |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|qf_AndOrXor_2284_values_0.smt2                                                              |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|qf_AndOrXor_2285_values_0.smt2                                                              |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|qf_AndOrXor_2297_values_0.smt2                                                              |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|qf_AndOrXor_2367_values_0.smt2                                                              |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|qf_AndOrXor_2416_values_0.smt2                                                              |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|qf_AndOrXor_2417_values_0.smt2                                                              |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|qf_AndOrXor_2429_values_0.smt2                                                              |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|qf_AndOrXor_2430_values_0.smt2                                                              |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|qf_AndOrXor_2475_values_0.smt2                                                              |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|qf_AndOrXor_2486_values_0.smt2                                                              |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|qf_AndOrXor_2515_values_0.smt2                                                              |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|qf_AndOrXor_2581_values_0.smt2                                                              |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|qf_AndOrXor_2587_values_0.smt2                                                              |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|qf_AndOrXor_2595_values_0.smt2                                                              |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|qf_AndOrXor_2607_values_0.smt2                                                              |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|qf_AndOrXor_2617_values_0.smt2                                                              |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|qf_AndOrXor_2627_values_0.smt2                                                              |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|qf_AndOrXor_2647_values_0.smt2                                                              |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|qf_AndOrXor_2658_values_0.smt2                                                              |   0.016s  |   0.016s  |   0.000s  | 0.0%|
|qf_AndOrXor_273_values_7.smt2                                                               |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|qf_AndOrXor_280_values_3.smt2                                                               |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|qf_AndOrXor_298_values_0.smt2                                                               |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|qf_AndOrXor_363_values_0.smt2                                                               |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|qf_AndOrXor_364_values_0.smt2                                                               |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|qf_AndOrXor_516_values_0.smt2                                                               |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|qf_AndOrXor_523_values_0.smt2                                                               |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|qf_AndOrXor_530_values_0.smt2                                                               |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|qf_AndOrXor_537_values_0.smt2                                                               |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|qf_AndOrXor_698_values_0.smt2                                                               |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|qf_AndOrXor_709_values_0.smt2                                                               |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|qf_AndOrXor_716_values_0.smt2                                                               |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|qf_AndOrXor_732-1_values_0.smt2                                                             |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|qf_AndOrXor_732-2_values_0.smt2                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|qf_AndOrXor_745_values_0.smt2                                                               |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|qf_AndOrXor_757_values_0.smt2                                                               |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|qf_AndOrXor_819_values_0.smt2                                                               |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|qf_AndOrXor_827_values_0.smt2                                                               |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|qf_AndOrXor_937_values_0.smt2                                                               |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|qf_InstCombineShift239_values_0.smt2                                                        |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|qf_InstCombineShift279_values_0.smt2                                                        |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|qf_InstCombineShift440_values_0.smt2                                                        |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|qf_InstCombineShift476_values_0.smt2                                                        |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|qf_Select_420_values_0.smt2                                                                 |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|qf_Select_423_values_57.smt2                                                                |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|qf_Select_427_values_0.smt2                                                                 |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|qf_Select_430_values_60.smt2                                                                |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|qf_Select_433_values_0.smt2                                                                 |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|qf_Select_576a_values_0.smt2                                                                |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|qf_Select_576b_values_0.smt2                                                                |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|qf_Select_704_values_0.smt2                                                                 |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|qf_Select_740_values_0.smt2                                                                 |   0.364s  |   0.364s  |   0.000s  | 0.0%|
|qf_Select_741_values_0.smt2                                                                 |   0.352s  |   0.352s  |   0.000s  | 0.0%|
|qf_Select_746_values_0.smt2                                                                 |   0.268s  |   0.268s  |   0.000s  | 0.0%|
|qf_Select_747_values_0.smt2                                                                 |   0.246s  |   0.246s  |   0.000s  | 0.0%|
</details>
