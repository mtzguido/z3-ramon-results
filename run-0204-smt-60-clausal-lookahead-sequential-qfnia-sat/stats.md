# data

* SAT 263
* UNSAT 0
* TIMEOUT 4
* UNKNOWN 0

* UNSET 0

* ERROR 1

# Meta data

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


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|00294.smt2                                                   |    0.014s | 52.468MiB| sat | 0 |  |  |
|qf_AndOrXor_2285_values_0.smt2                               |    0.015s | 52.564MiB| sat | 0 |  |  |
|qf_AndOrXor_1247_values_0.smt2                               |    0.015s | 52.592MiB| sat | 0 |  |  |
|int_check_ne_bvand_ltr_inv_g.smt2                            |    0.015s | 52.544MiB| sat | 0 |  |  |
|qf_AndOrXor_2284_values_0.smt2                               |    0.015s | 52.48MiB| sat | 0 |  |  |
|qf_AndOrXor_1294_values_0.smt2                               |    0.015s | 52.544MiB| sat | 0 |  |  |
|int_check_bvuge_bvor_ltr_inv_g.smt2                          |    0.016s | 52.556MiB| sat | 0 |  |  |
|01052.smt2                                                   |    0.016s | 52.5MiB| sat | 0 |  |  |
|qf_AndOrXor_2063_values_0.smt2                               |    0.016s | 52.5MiB| sat | 0 |  |  |
|qf_AndOrXor_2417_values_0.smt2                               |    0.016s | 52.564MiB| sat | 0 |  |  |
|qf_AndOrXor_2581_values_0.smt2                               |    0.016s | 52.448MiB| sat | 0 |  |  |
|qf_AndOrXor_716_values_0.smt2                                |    0.016s | 52.596MiB| sat | 0 |  |  |
|00251.smt2                                                   |    0.016s | 52.48MiB| sat | 0 |  |  |
|00105.smt2                                                   |    0.016s | 52.592MiB| sat | 0 |  |  |
|int_check_bvuge_bvand_ltr_inv_g.smt2                         |    0.016s | 52.56MiB| sat | 0 |  |  |
|int_check_bvult_bvor_rtl.smt2                                |    0.016s | 52.392MiB| sat | 0 |  |  |
|int_check_bvuge_bvand_rtl.smt2                               |    0.017s | 52.428MiB| sat | 0 |  |  |
|00035.smt2                                                   |    0.017s | 52.564MiB| sat | 0 |  |  |
|qf_AndOrXor_1012_values_0.smt2                               |    0.017s | 53.148MiB| sat | 0 |  |  |
|int_check_bvuge_bvmul_rtl.smt2                               |    0.017s | 52.852MiB| sat | 0 |  |  |
|qf_AndOrXor_151_values_0.smt2                                |    0.017s | 52.476MiB| sat | 0 |  |  |
|qf_AndOrXor_2475_values_0.smt2                               |    0.017s | 53.236MiB| sat | 0 |  |  |
|qf_AndOrXor_1280_values_0.smt2                               |    0.017s | 52.496MiB| sat | 0 |  |  |
|int_check_ne_bvadd_ltr_inv_r.smt2                            |    0.017s | 52.828MiB| sat | 0 |  |  |
|00005.smt2                                                   |    0.018s | 52.244MiB| sat | 0 |  |  |
|int_check_bvugt_bvor_rtl.smt2                                |    0.018s | 52.532MiB| sat | 0 |  |  |
|qf_AndOrXor_745_values_0.smt2                                |    0.018s | 52.52MiB| sat | 0 |  |  |
|int_check_eq_bvand_rtl.smt2                                  |    0.018s | 52.56MiB| sat | 0 |  |  |
|qf_AndOrXor_1230_values_0.smt2                               |    0.018s | 52.556MiB| sat | 0 |  |  |
|int_check_bvult_bvand_ltr_inv_g.smt2                         |    0.018s | 52.472MiB| sat | 0 |  |  |
|qf_AndOrXor_2658_values_0.smt2                               |    0.018s | 52.472MiB| sat | 0 |  |  |
|qf_AndOrXor_2367_values_0.smt2                               |    0.018s | 52.416MiB| sat | 0 |  |  |
|qf_AndOrXor_1733_values_0.smt2                               |    0.018s | 52.448MiB| sat | 0 |  |  |
|qf_InstCombineShift440_values_0.smt2                         |    0.018s | 53.072MiB| sat | 0 |  |  |
|int_check_bvugt_bvand_ltr_inv_g.smt2                         |    0.018s | 52.56MiB| sat | 0 |  |  |
|qf_AndOrXor_2247_values_0.smt2                               |    0.019s | 52.456MiB| sat | 0 |  |  |
|int_check_ne_bvnot_ltr_inv_g.smt2                            |    0.019s | 52.628MiB| sat | 0 |  |  |
|qf_AndOrXor_144_values_0.smt2                                |    0.019s | 52.548MiB| sat | 0 |  |  |
|int_check_ne_bvand_rtl.smt2                                  |    0.019s | 52.548MiB| sat | 0 |  |  |
|int_check_bvsge_bvor_rtl.smt2                                |    0.019s | 53.036MiB| sat | 0 |  |  |
|qf_AndOrXor_827_values_0.smt2                                |    0.019s | 52.576MiB| sat | 0 |  |  |
|qf_AndOrXor_1795_values_0.smt2                               |    0.019s | 52.896MiB| sat | 0 |  |  |
|00149.smt2                                                   |    0.019s | 52.524MiB| sat | 0 |  |  |
|qf_AndOrXor_1979_values_0.smt2                               |    0.019s | 52.444MiB| sat | 0 |  |  |
|qf_AndOrXor_2052_values_0.smt2                               |    0.019s | 52.468MiB| sat | 0 |  |  |
|qf_AndOrXor_2008_values_0.smt2                               |    0.019s | 52.58MiB| sat | 0 |  |  |
|int_check_bvsge_bvand_ltr_inv_g.smt2                         |    0.019s | 53.092MiB| sat | 0 |  |  |
|int_check_bvsgt_bvneg_rtl.smt2                               |    0.019s | 53.328MiB| sat | 0 |  |  |
|qf_AndOrXor_2118_values_0.smt2                               |    0.019s | 52.452MiB| sat | 0 |  |  |
|qf_AndOrXor_1253_values_0.smt2                               |    0.019s | 52.6MiB| sat | 0 |  |  |
|int_check_bvsge_bvshl0_rtl.smt2                              |    0.019s | 53.216MiB| sat | 0 |  |  |
|int_check_bvult_bvand_rtl.smt2                               |    0.019s | 52.44MiB| sat | 0 |  |  |
|qf_AndOrXor_2297_values_0.smt2                               |    0.020s | 52.56MiB| sat | 0 |  |  |
|qf_AndOrXor_2627_values_0.smt2                               |    0.020s | 52.556MiB| sat | 0 |  |  |
|qf_AndOrXor_2231_values_0.smt2                               |    0.020s | 52.552MiB| sat | 0 |  |  |
|int_check_ne_bvor_rtl.smt2                                   |    0.020s | 52.572MiB| sat | 0 |  |  |
|qf_AndOrXor_2607_values_0.smt2                               |    0.020s | 52.556MiB| sat | 0 |  |  |
|qf_AddSub_1624_values_0.smt2                                 |    0.020s | 52.932MiB| sat | 0 |  |  |
|int_check_bvsle_bvand_rtl.smt2                               |    0.020s | 52.816MiB| sat | 0 |  |  |
|qf_AddSub_1043_values_0.smt2                                 |    0.020s | 53.184MiB| sat | 0 |  |  |
|00102.smt2                                                   |    0.020s | 52.556MiB| sat | 0 |  |  |
|int_check_bvuge_bvurem1_rtl.smt2                             |    0.020s | 53.068MiB| sat | 0 |  |  |
|int_check_bvsgt_bvlshr0_ltr_inv_r.smt2                       |    0.020s | 53.404MiB| sat | 0 |  |  |
|qf_AndOrXor_709_values_0.smt2                                |    0.020s | 52.464MiB| sat | 0 |  |  |
|qf_AndOrXor_2188_values_0.smt2                               |    0.020s | 52.592MiB| sat | 0 |  |  |
|qf_AndOrXor_2123_values_0.smt2                               |    0.020s | 52.384MiB| sat | 0 |  |  |
|qf_AndOrXor_819_values_0.smt2                                |    0.020s | 53.064MiB| sat | 0 |  |  |
|int_check_bvsge_bvnot_ltr_inv_g.smt2                         |    0.020s | 52.972MiB| sat | 0 |  |  |
|qf_Select_420_values_0.smt2                                  |    0.020s | 52.78MiB| sat | 0 |  |  |
|int_check_eq_bvor_rtl.smt2                                   |    0.020s | 52.484MiB| sat | 0 |  |  |
|qf_AndOrXor_1241_values_0.smt2                               |    0.020s | 52.716MiB| sat | 0 |  |  |
|int_check_bvsgt_bvadd_ltr_inv_r.smt2                         |    0.020s | 53.096MiB| sat | 0 |  |  |
|qf_AndOrXor_280_values_3.smt2                                |    0.020s | 53.44MiB| sat | 0 |  |  |
|int_check_bvsle_bvurem0_ltr_inv_g.smt2                       |    0.020s | 53.332MiB| sat | 0 |  |  |
|qf_AddSub_1295_values_0.smt2                                 |    0.020s | 52.94MiB| sat | 0 |  |  |
|n0-00001.smt2                                                |    0.021s | 52.528MiB| sat | 0 |  |  |
|00003.smt2                                                   |    0.021s | 52.304MiB| sat | 0 |  |  |
|qf_AndOrXor_732-2_values_0.smt2                              |    0.021s | 52.624MiB| sat | 0 |  |  |
|qf_AndOrXor_2113_values_0.smt2                               |    0.021s | 52.512MiB| sat | 0 |  |  |
|int_check_bvult_bvudiv1_rtl.smt2                             |    0.021s | 52.824MiB| sat | 0 |  |  |
|qf_AndOrXor_1288_values_0.smt2                               |    0.021s | 52.488MiB| sat | 0 |  |  |
|int_check_bvsle_bvshl0_rtl.smt2                              |    0.021s | 53.472MiB| sat | 0 |  |  |
|qf_InstCombineShift279_values_0.smt2                         |    0.021s | 53.228MiB| sat | 0 |  |  |
|qf_AndOrXor_2430_values_0.smt2                               |    0.021s | 52.516MiB| sat | 0 |  |  |
|00967.smt2                                                   |    0.021s | 52.444MiB| sat | 0 |  |  |
|qf_InstCombineShift239_values_0.smt2                         |    0.021s | 53.104MiB| sat | 0 |  |  |
|qf_AndOrXor_537_values_0.smt2                                |    0.021s | 53.084MiB| sat | 0 |  |  |
|00085.smt2                                                   |    0.021s | 52.292MiB| sat | 0 |  |  |
|int_check_bvslt_bvand_rtl.smt2                               |    0.021s | 53.244MiB| sat | 0 |  |  |
|qf_AndOrXor_2515_values_0.smt2                               |    0.021s | 53.128MiB| sat | 0 |  |  |
|int_check_bvsle_bvadd_ltr_inv_r.smt2                         |    0.021s | 53.0MiB| sat | 0 |  |  |
|00324.smt2                                                   |    0.021s | 52.528MiB| sat | 0 |  |  |
|qf_AndOrXor_698_values_0.smt2                                |    0.021s | 52.424MiB| sat | 0 |  |  |
|int_check_bvsge_bvmul_rtl.smt2                               |    0.021s | 53.364MiB| sat | 0 |  |  |
|qf_AndOrXor_2263_values_0.smt2                               |    0.022s | 52.352MiB| sat | 0 |  |  |
|int_check_bvugt_bvor_ltr_inv_g.smt2                          |    0.022s | 52.508MiB| sat | 0 |  |  |
|qf_AndOrXor_2243_values_0.smt2                               |    0.022s | 52.472MiB| sat | 0 |  |  |
|qf_Select_576b_values_0.smt2                                 |    0.022s | 53.532MiB| sat | 0 |  |  |
|int_check_bvslt_bvadd_ltr_inv_r.smt2                         |    0.022s | 53.048MiB| sat | 0 |  |  |
|qf_AndOrXor_523_values_0.smt2                                |    0.022s | 53.38MiB| sat | 0 |  |  |
|int_check_eq_bvurem1_ltr_inv_g.smt2                          |    0.022s | 53.352MiB| sat | 0 |  |  |
|00002.smt2                                                   |    0.022s | 52.544MiB| sat | 0 |  |  |
|int_check_bvsle_bvneg_ltr_inv_g.smt2                         |    0.022s | 53.256MiB| sat | 0 |  |  |
|int_check_bvuge_bvurem1_ltr_inv_g.smt2                       |    0.022s | 53.068MiB| sat | 0 |  |  |
|00428.smt2                                                   |    0.022s | 52.776MiB| sat | 0 |  |  |
|int_check_bvule_bvand_ltr_inv_g.smt2                         |    0.022s | 52.44MiB| sat | 0 |  |  |
|qf_AndOrXor_2647_values_0.smt2                               |    0.022s | 52.576MiB| sat | 0 |  |  |
|int_check_bvsle_bvor_ltr_inv_g.smt2                          |    0.022s | 52.956MiB| sat | 0 |  |  |
|int_check_bvsle_bvnot_ltr_inv_g.smt2                         |    0.023s | 52.916MiB| sat | 0 |  |  |
|int_check_bvugt_bvand_rtl.smt2                               |    0.023s | 52.636MiB| sat | 0 |  |  |
|int_check_bvsgt_bvand_rtl.smt2                               |    0.023s | 53.004MiB| sat | 0 |  |  |
|int_check_bvslt_bvnot_ltr_inv_g.smt2                         |    0.023s | 52.96MiB| sat | 0 |  |  |
|int_check_bvsgt_bvneg_ltr_inv_g.smt2                         |    0.023s | 53.088MiB| sat | 0 |  |  |
|int_check_bvule_bvudiv0_rtl.smt2                             |    0.023s | 53.048MiB| sat | 0 |  |  |
|qf_AndOrXor_2595_values_0.smt2                               |    0.023s | 52.38MiB| sat | 0 |  |  |
|qf_Select_433_values_0.smt2                                  |    0.023s | 53.004MiB| sat | 0 |  |  |
|qf_Select_423_values_57.smt2                                 |    0.023s | 53.088MiB| sat | 0 |  |  |
|int_check_bvsle_bvand_ltr_inv_g.smt2                         |    0.023s | 52.984MiB| sat | 0 |  |  |
|qf_AndOrXor_135_values_0.smt2                                |    0.023s | 52.464MiB| sat | 0 |  |  |
|00415.smt2                                                   |    0.023s | 52.816MiB| sat | 0 |  |  |
|00402.smt2                                                   |    0.024s | 52.796MiB| sat | 0 |  |  |
|qf_AndOrXor_757_values_0.smt2                                |    0.024s | 52.468MiB| sat | 0 |  |  |
|int_check_bvsgt_bvnot_rtl.smt2                               |    0.024s | 52.968MiB| sat | 0 |  |  |
|00413.smt2                                                   |    0.024s | 53.372MiB| sat | 0 |  |  |
|int_check_bvsgt_bvand_ltr_inv_g.smt2                         |    0.024s | 52.916MiB| sat | 0 |  |  |
|int_check_bvsgt_bvadd_ltr_inv_g.smt2                         |    0.024s | 53.476MiB| sat | 0 |  |  |
|int_check_ne_bvor_ltr_inv_g.smt2                             |    0.025s | 52.432MiB| sat | 0 |  |  |
|int_check_bvsgt_bvor_rtl.smt2                                |    0.025s | 53.044MiB| sat | 0 |  |  |
|00194.smt2                                                   |    0.025s | 52.58MiB| sat | 0 |  |  |
|int_check_bvslt_bvneg_ltr_inv_g.smt2                         |    0.025s | 53.304MiB| sat | 0 |  |  |
|00104.smt2                                                   |    0.025s | 52.756MiB| sat | 0 |  |  |
|int_check_bvsge_bvor_ltr_inv_g.smt2                          |    0.025s | 52.952MiB| sat | 0 |  |  |
|qf_AndOrXor_516_values_0.smt2                                |    0.025s | 53.208MiB| sat | 0 |  |  |
|int_check_bvsle_bvshl1_rtl.smt2                              |    0.025s | 53.26MiB| sat | 0 |  |  |
|int_check_bvsge_bvand_rtl.smt2                               |    0.025s | 53.24MiB| sat | 0 |  |  |
|qf_AndOrXor_2486_values_0.smt2                               |    0.026s | 53.252MiB| sat | 0 |  |  |
|qf_Select_430_values_60.smt2                                 |    0.026s | 53.0MiB| sat | 0 |  |  |
|qf_AddSub_1560_values_0.smt2                                 |    0.026s | 52.904MiB| sat | 0 |  |  |
|int_check_eq_bvmul_rtl.smt2                                  |    0.026s | 52.912MiB| sat | 0 |  |  |
|int_check_bvule_bvudiv1_rtl.smt2                             |    0.026s | 52.832MiB| sat | 0 |  |  |
|int_check_bvslt_bvudiv1_rtl.smt2                             |    0.026s | 53.388MiB| sat | 0 |  |  |
|int_check_bvsgt_bvor_ltr_inv_g.smt2                          |    0.026s | 52.964MiB| sat | 0 |  |  |
|int_check_bvslt_bvor_rtl.smt2                                |    0.026s | 53.216MiB| sat | 0 |  |  |
|00314.smt2                                                   |    0.026s | 53.692MiB| sat | 0 |  |  |
|00020.smt2                                                   |    0.027s | 52.304MiB| sat | 0 |  |  |
|int_check_bvsle_bvor_rtl.smt2                                |    0.027s | 53.064MiB| sat | 0 |  |  |
|qf_AddSub_1040_values_0.smt2                                 |    0.027s | 53.044MiB| sat | 0 |  |  |
|qf_AndOrXor_2265_values_0.smt2                               |    0.028s | 52.48MiB| sat | 0 |  |  |
|int_check_bvsle_bvurem0_rtl.smt2                             |    0.028s | 53.128MiB| sat | 0 |  |  |
|int_check_bvslt_bvnot_rtl.smt2                               |    0.028s | 53.036MiB| sat | 0 |  |  |
|00235.smt2                                                   |    0.028s | 52.3MiB| sat | 0 |  |  |
|int_check_bvule_bvudiv0_ltr_inv_g.smt2                       |    0.029s | 52.844MiB| sat | 0 |  |  |
|qf_AndOrXor_732-1_values_0.smt2                              |    0.029s | 52.612MiB| sat | 0 |  |  |
|int_check_bvslt_bvor_ltr_inv_g.smt2                          |    0.029s | 53.088MiB| sat | 0 |  |  |
|qf_AndOrXor_2617_values_0.smt2                               |    0.029s | 52.572MiB| sat | 0 |  |  |
|qf_AndOrXor_937_values_0.smt2                                |    0.031s | 53.312MiB| sat | 0 |  |  |
|00247.smt2                                                   |    0.031s | 52.384MiB| sat | 0 |  |  |
|int_check_bvsgt_bvurem0_ltr_inv_g.smt2                       |    0.031s | 53.6MiB| sat | 0 |  |  |
|00243.smt2                                                   |    0.031s | 52.488MiB| sat | 0 |  |  |
|00304.smt2                                                   |    0.031s | 54.684MiB| sat | 0 |  |  |
|int_check_bvsgt_bvnot_ltr_inv_g.smt2                         |    0.031s | 52.888MiB| sat | 0 |  |  |
|00249.smt2                                                   |    0.032s | 52.56MiB| sat | 0 |  |  |
|int_check_ne_bvlshr0_rtl.smt2                                |    0.032s | 52.992MiB| sat | 0 |  |  |
|int_check_ne_bvshl0_rtl.smt2                                 |    0.032s | 53.16MiB| sat | 0 |  |  |
|qf_AndOrXor_2160_values_0.smt2                               |    0.032s | 52.652MiB| sat | 0 |  |  |
|int_check_bvsgt_bvudiv0_rtl.smt2                             |    0.033s | 53.348MiB| sat | 0 |  |  |
|int_check_bvslt_bvurem1_ltr_inv_g.smt2                       |    0.034s | 53.26MiB| sat | 0 |  |  |
|qf_Select_704_values_0.smt2                                  |    0.034s | 53.16MiB| sat | 0 |  |  |
|int_check_bvule_bvor_ltr_inv_g.smt2                          |    0.034s | 52.488MiB| sat | 0 |  |  |
|int_check_eq_bvurem1_rtl.smt2                                |    0.034s | 53.264MiB| sat | 0 |  |  |
|int_check_bvsgt_bvashr1_rtl.smt2                             |    0.034s | 53.604MiB| sat | 0 |  |  |
|int_check_bvugt_bvmul_rtl.smt2                               |    0.037s | 53.236MiB| sat | 0 |  |  |
|int_check_bvslt_bvneg_rtl.smt2                               |    0.037s | 53.092MiB| sat | 0 |  |  |
|int_check_bvsle_bvudiv1_rtl.smt2                             |    0.040s | 53.556MiB| sat | 0 |  |  |
|int_check_ne_bvneg_ltr_inv_g.smt2                            |    0.040s | 52.936MiB| sat | 0 |  |  |
|int_check_bvslt_bvand_ltr_inv_g.smt2                         |    0.040s | 53.396MiB| sat | 0 |  |  |
|qf_AndOrXor_2264_values_0.smt2                               |    0.041s | 52.496MiB| sat | 0 |  |  |
|int_check_bvslt_bvurem1_rtl.smt2                             |    0.041s | 53.412MiB| sat | 0 |  |  |
|int_check_bvsle_bvurem1_rtl.smt2                             |    0.042s | 53.452MiB| sat | 0 |  |  |
|qf_AndOrXor_1864_values_0.smt2                               |    0.042s | 53.304MiB| sat | 0 |  |  |
|int_check_bvule_bvor_rtl.smt2                                |    0.042s | 52.576MiB| sat | 0 |  |  |
|int_check_ne_bvlshr1_rtl.smt2                                |    0.042s | 53.076MiB| sat | 0 |  |  |
|00018.smt2                                                   |    0.043s | 54.456MiB| sat | 0 |  |  |
|int_check_ne_bvashr1_rtl.smt2                                |    0.044s | 53.4MiB| sat | 0 |  |  |
|int_check_bvult_bvudiv1_ltr_inv_g.smt2                       |    0.044s | 53.404MiB| sat | 0 |  |  |
|qf_Select_427_values_0.smt2                                  |    0.045s | 52.816MiB| sat | 0 |  |  |
|qf_AndOrXor_2429_values_0.smt2                               |    0.045s | 52.596MiB| sat | 0 |  |  |
|int_check_bvslt_bvshl1_rtl.smt2                              |    0.046s | 53.616MiB| sat | 0 |  |  |
|int_check_bvslt_bvudiv0_rtl.smt2                             |    0.046s | 53.36MiB| sat | 0 |  |  |
|int_check_bvslt_bvadd_ltr_inv_g.smt2                         |    0.047s | 53.188MiB| sat | 0 |  |  |
|int_check_bvuge_bvudiv0_rtl.smt2                             |    0.048s | 53.068MiB| sat | 0 |  |  |
|qf_InstCombineShift476_values_0.smt2                         |    0.049s | 53.056MiB| sat | 0 |  |  |
|int_check_bvsgt_bvurem1_ltr_inv_g.smt2                       |    0.049s | 53.84MiB| sat | 0 |  |  |
|qf_AndOrXor_363_values_0.smt2                                |    0.049s | 53.324MiB| sat | 0 |  |  |
|int_check_bvsle_bvurem1_ltr_inv_r.smt2                       |    0.049s | 53.556MiB| sat | 0 |  |  |
|int_check_bvule_bvlshr0_ltr_inv_g.smt2                       |    0.050s | 53.08MiB| sat | 0 |  |  |
|int_check_bvslt_bvurem0_ltr_inv_r.smt2                       |    0.050s | 53.288MiB| sat | 0 |  |  |
|qf_AndOrXor_364_values_0.smt2                                |    0.050s | 53.192MiB| sat | 0 |  |  |
|qf_Select_576a_values_0.smt2                                 |    0.051s | 53.684MiB| sat | 0 |  |  |
|int_check_bvslt_bvadd_rtl.smt2                               |    0.051s | 53.356MiB| sat | 0 |  |  |
|int_check_ne_bvlshr0_ltr_inv_g.smt2                          |    0.053s | 53.08MiB| sat | 0 |  |  |
|int_check_bvule_bvlshr1_ltr_inv_g.smt2                       |    0.053s | 53.264MiB| sat | 0 |  |  |
|qf_AndOrXor_530_values_0.smt2                                |    0.053s | 53.004MiB| sat | 0 |  |  |
|int_check_bvsle_bvlshr1_ltr_inv_g.smt2                       |    0.053s | 53.52MiB| sat | 0 |  |  |
|qf_AndOrXor_2416_values_0.smt2                               |    0.054s | 52.36MiB| sat | 0 |  |  |
|int_check_bvult_bvor_ltr_inv_g.smt2                          |    0.055s | 52.52MiB| sat | 0 |  |  |
|qf_AndOrXor_298_values_0.smt2                                |    0.055s | 53.392MiB| sat | 0 |  |  |
|qf_AndOrXor_2587_values_0.smt2                               |    0.055s | 52.588MiB| sat | 0 |  |  |
|int_check_bvsge_bvudiv0_rtl.smt2                             |    0.056s | 53.804MiB| sat | 0 |  |  |
|qf_AndOrXor_273_values_7.smt2                                |    0.057s | 53.38MiB| sat | 0 |  |  |
|int_check_bvult_bvshl1_ltr_inv_g.smt2                        |    0.057s | 53.064MiB| sat | 0 |  |  |
|int_check_bvsge_bvadd_ltr_inv_r.smt2                         |    0.057s | 53.476MiB| sat | 0 |  |  |
|int_check_bvult_bvlshr0_ltr_inv_g.smt2                       |    0.059s | 53.28MiB| sat | 0 |  |  |
|int_check_bvult_bvlshr1_ltr_inv_g.smt2                       |    0.060s | 53.052MiB| sat | 0 |  |  |
|int_check_bvslt_bvurem0_rtl.smt2                             |    0.061s | 53.68MiB| sat | 0 |  |  |
|int_check_ne_bvurem0_ltr_inv_g.smt2                          |    0.062s | 53.276MiB| sat | 0 |  |  |
|int_check_bvsgt_bvudiv1_rtl.smt2                             |    0.063s | 53.748MiB| sat | 0 |  |  |
|qf_AddSub_1564_values_0.smt2                                 |    0.063s | 53.468MiB| sat | 0 |  |  |
|int_check_bvule_bvshl1_ltr_inv_g.smt2                        |    0.064s | 52.936MiB| sat | 0 |  |  |
|int_check_bvsge_bvurem0_rtl.smt2                             |    0.065s | 53.736MiB| sat | 0 |  |  |
|int_check_bvsgt_bvmul_rtl.smt2                               |    0.065s | 53.42MiB| sat | 0 |  |  |
|int_check_bvsge_bvlshr0_ltr_inv_r.smt2                       |    0.065s | 53.492MiB| sat | 0 |  |  |
|int_check_bvugt_bvlshr1_rtl.smt2                             |    0.067s | 53.412MiB| sat | 0 |  |  |
|int_check_bvugt_bvlshr0_rtl.smt2                             |    0.067s | 53.436MiB| sat | 0 |  |  |
|int_check_bvsge_bvlshr1_rtl.smt2                             |    0.068s | 53.86MiB| sat | 0 |  |  |
|00379.smt2                                                   |    0.070s | 54.936MiB| sat | 1 |  |  |
|00793.smt2                                                   |    0.071s | 58.32MiB| sat | 0 |  |  |
|int_check_bvsge_bvurem0_ltr_inv_g.smt2                       |    0.076s | 53.28MiB| sat | 0 |  |  |
|int_check_bvslt_bvlshr1_rtl.smt2                             |    0.077s | 53.388MiB| sat | 0 |  |  |
|int_check_bvsle_bvlshr1_rtl.smt2                             |    0.078s | 53.844MiB| sat | 0 |  |  |
|int_check_bvslt_bvlshr1_ltr_inv_g.smt2                       |    0.079s | 53.48MiB| sat | 0 |  |  |
|int_check_ne_bvadd_ltr_inv_g.smt2                            |    0.083s | 53.344MiB| sat | 0 |  |  |
|int_check_bvuge_bvashr0_ltr_inv_g.smt2                       |    0.084s | 53.548MiB| sat | 0 |  |  |
|int_check_bvule_bvashr1_ltr_inv_g.smt2                       |    0.090s | 53.616MiB| sat | 0 |  |  |
|int_check_bvuge_bvlshr1_rtl.smt2                             |    0.102s | 53.652MiB| sat | 0 |  |  |
|qf_AddSub_1202_values_0.smt2                                 |    0.105s | 53.292MiB| sat | 0 |  |  |
|int_check_bvsle_bvlshr0_rtl.smt2                             |    0.106s | 53.572MiB| sat | 0 |  |  |
|int_check_bvule_bvashr1_rtl.smt2                             |    0.109s | 53.7MiB| sat | 0 |  |  |
|int_check_bvuge_bvlshr0_ltr_inv_g.smt2                       |    0.114s | 54.08MiB| sat | 0 |  |  |
|qf_muldivrem_876_values_0.smt2                               |    0.116s | 53.576MiB| sat | 0 |  |  |
|int_check_bvsge_bvshl0_ltr_inv_g.smt2                        |    0.117s | 54.056MiB| sat | 0 |  |  |
|int_check_bvult_bvashr1_ltr_inv_g.smt2                       |    0.119s | 53.648MiB| sat | 0 |  |  |
|int_check_bvsge_bvashr0_ltr_inv_g.smt2                       |    0.122s | 54.42MiB| sat | 0 |  |  |
|int_check_bvslt_bvshl0_rtl.smt2                              |    0.122s | 53.848MiB| sat | 0 |  |  |
|int_check_bvsge_bvashr1_ltr_inv_g.smt2                       |    0.124s | 53.724MiB| sat | 0 |  |  |
|int_check_bvult_bvashr0_ltr_inv_g.smt2                       |    0.149s | 53.544MiB| sat | 0 |  |  |
|qf_AddSub_1599_values_0.smt2                                 |    0.162s | 53.888MiB| sat | 0 |  |  |
|int_check_bvsle_bvudiv0_ltr_inv_g.smt2                       |    0.173s | 53.964MiB| sat | 0 |  |  |
|int_check_bvule_bvashr0_ltr_inv_g.smt2                       |    0.184s | 54.032MiB| sat | 0 |  |  |
|int_check_bvugt_bvshl0_rtl.smt2                              |    0.186s | 53.892MiB| sat | 0 |  |  |
|int_check_bvsgt_bvashr0_ltr_inv_g.smt2                       |    0.206s | 54.252MiB| sat | 0 |  |  |
|qf_Select_747_values_0.smt2                                  |    0.233s | 54.288MiB| sat | 0 |  |  |
|int_check_bvslt_bvmul_rtl.smt2                               |    0.272s | 54.792MiB| sat | 0 |  |  |
|qf_Select_746_values_0.smt2                                  |    0.296s | 53.684MiB| sat | 0 |  |  |
|int_check_bvsle_bvashr1_ltr_inv_g.smt2                       |    0.326s | 53.944MiB| sat | 0 |  |  |
|qf_Select_740_values_0.smt2                                  |    0.352s | 54.064MiB| sat | 0 |  |  |
|qf_Select_741_values_0.smt2                                  |    0.353s | 54.164MiB| sat | 0 |  |  |
|int_check_eq_bvshl0_rtl.smt2                                 |    0.387s | 54.088MiB| sat | 0 |  |  |
|int_check_bvsge_bvashr0_rtl.smt2                             |    0.496s | 55.448MiB| sat | 0 |  |  |
|int_check_bvslt_bvashr1_ltr_inv_g.smt2                       |    0.500s | 54.428MiB| sat | 0 |  |  |
|qf_AddSub_1604_values_0.smt2                                 |    0.521s | 55.116MiB| sat | 0 |  |  |
|int_check_ne_bvashr1_ltr_inv_r.smt2                          |    0.526s | 54.268MiB| sat | 0 |  |  |
|int_check_bvsge_bvurem1_rtl.smt2                             |    0.919s | 55.084MiB| sat | 0 |  |  |
|int_check_ne_bvshl1_ltr_inv_g.smt2                           |   59.996s | 53.024MiB| timeout | 0 |  |  |
|int_check_ne_bvudiv0_ltr_inv_g.smt2                          |   59.996s | 53.444MiB| timeout | 0 |  |  |
|int_check_ne_bvlshr1_ltr_inv_g.smt2                          |   59.998s | 53.152MiB| timeout | 0 |  |  |
|int_check_bvuge_bvlshr0_rtl.smt2                             |   59.999s | 53.324MiB| timeout | 0 |  |  |
