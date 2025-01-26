# data

* SAT 123
* UNSAT 43
* TIMEOUT 131
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-60-qfufnia-unknown
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 04d0e9492b0066675c75fc5fb1df6b23b79607e5
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" model_validate=true"
Z3 inputs: inputs/QF_UFNIA_UNKNOWN
Z3 commit message: set log level of revert repair down to 3

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|int_check_bvule_bvurem1_ltr_inv_g.smt2                       |    0.007s | 18.768MiB| unsat | 0 |  |  |
|int_check_bvule_bvneg_ltr_inv_g.smt2                         |    0.008s | 18.764MiB| unsat | 0 |  |  |
|qf_AndOrXor_1894_values_0.smt2                               |    0.008s | 19.276MiB| unsat | 0 |  |  |
|int_check_bvult_bvurem1_ltr_inv_g.smt2                       |    0.008s | 19.0MiB| unsat | 0 |  |  |
|qf_AndOrXor_794_values_121.smt2                              |    0.008s | 19.02MiB| unsat | 0 |  |  |
|int_check_bvult_bvurem0_ltr_inv_g.smt2                       |    0.008s | 18.996MiB| unsat | 0 |  |  |
|qf_Select_727_values_0.smt2                                  |    0.009s | 19.28MiB| unsat | 0 |  |  |
|qf_Select_705_values_0.smt2                                  |    0.009s | 19.276MiB| unsat | 0 |  |  |
|qf_AndOrXor_1869_values_0.smt2                               |    0.009s | 19.296MiB| unsat | 0 |  |  |
|int_check_bvult_bvneg_ltr_inv_g.smt2                         |    0.009s | 19.02MiB| unsat | 0 |  |  |
|qf_Select_700_values_123.smt2                                |    0.009s | 19.532MiB| unsat | 0 |  |  |
|int_check_bvule_bvudiv1_ltr_inv_g.smt2                       |    0.010s | 19.508MiB| sat | 0 |  |  |
|int_check_eq_bvurem0_rtl.smt2                                |    0.011s | 19.536MiB| unsat | 0 |  |  |
|int_check_bvuge_bvurem0_rtl.smt2                             |    0.011s | 19.288MiB| unsat | 0 |  |  |
|int_check_bvugt_bvudiv1_rtl.smt2                             |    0.011s | 19.508MiB| unsat | 0 |  |  |
|int_check_bvuge_bvashr1_ltr_inv_g.smt2                       |    0.012s | 19.764MiB| sat | 0 |  |  |
|int_check_bvsgt_bvshl0_ltr_inv_g.smt2                        |    0.013s | 20.044MiB| sat | 0 |  |  |
|int_check_bvuge_bvashr1_rtl.smt2                             |    0.013s | 20.02MiB| sat | 0 |  |  |
|int_check_bvugt_bvurem0_rtl.smt2                             |    0.013s | 19.536MiB| unsat | 0 |  |  |
|int_check_bvsge_bvashr1_rtl.smt2                             |    0.013s | 19.788MiB| sat | 0 |  |  |
|int_check_bvsle_bvashr1_rtl.smt2                             |    0.014s | 20.02MiB| sat | 0 |  |  |
|int_check_bvsle_bvudiv0_rtl.smt2                             |    0.015s | 20.208MiB| sat | 0 |  |  |
|int_check_eq_bvudiv0_rtl.smt2                                |    0.015s | 19.436MiB| unsat | 0 |  |  |
|int_check_bvsgt_bvadd_rtl.smt2                               |    0.015s | 19.644MiB| sat | 0 |  |  |
|int_check_bvule_bvurem0_ltr_inv_g.smt2                       |    0.016s | 18.896MiB| unsat | 0 |  |  |
|int_check_eq_bvurem0_ltr_inv_g.smt2                          |    0.016s | 19.484MiB| unsat | 0 |  |  |
|int_check_bvsgt_bvashr0_rtl.smt2                             |    0.017s | 20.3MiB| sat | 0 |  |  |
|int_check_bvsgt_bvlshr1_rtl.smt2                             |    0.023s | 20.064MiB| sat | 0 |  |  |
|int_check_bvsge_bvneg_ltr_inv_g.smt2                         |    0.026s | 19.788MiB| unsat | 0 |  |  |
|int_check_bvsle_bvashr0_ltr_inv_g.smt2                       |    0.028s | 20.304MiB| sat | 0 |  |  |
|int_check_bvsgt_bvashr1_ltr_inv_g.smt2                       |    0.035s | 20.336MiB| sat | 0 |  |  |
|int_check_bvslt_bvudiv0_ltr_inv_g.smt2                       |    0.036s | 20.3MiB| sat | 0 |  |  |
|63058_aa742630eef64f949de269382c1f9035_25_UFNIA.smt2         |    0.038s | 22.072MiB| unsat | 0 |  |  |
|65782_cd31513fdcd15701933b_6_QF_UFNIA.smt2                   |    0.039s | 20.532MiB| sat | 0 |  |  |
|qf_AddSub_1619_values_0.smt2                                 |    0.040s | 19.952MiB| unsat | 0 |  |  |
|int_check_bvult_bvashr1_rtl.smt2                             |    0.047s | 20.048MiB| sat | 0 |  |  |
|int_check_bvugt_bvashr0_ltr_inv_g.smt2                       |    0.055s | 19.956MiB| sat | 0 |  |  |
|qf_AndOrXor_290_values_7.smt2                                |    0.059s | 20.528MiB| sat | 0 |  |  |
|int_check_eq_bvudiv1_rtl.smt2                                |    0.064s | 20.064MiB| unsat | 0 |  |  |
|qf_AndOrXor_210_values_0.smt2                                |    0.067s | 19.788MiB| sat | 0 |  |  |
|qf_Select_510_values_0.smt2                                  |    0.076s | 20.56MiB| sat | 0 |  |  |
|qf_AndOrXor_230_values_0.smt2                                |    0.076s | 20.176MiB| sat | 0 |  |  |
|int_check_bvsle_bvshl0_ltr_inv_g.smt2                        |    0.077s | 20.256MiB| sat | 0 |  |  |
|int_check_bvsge_bvudiv1_rtl.smt2                             |    0.079s | 20.368MiB| sat | 0 |  |  |
|qf_InstCombineShift497a_values_0.smt2                        |    0.080s | 20.048MiB| sat | 0 |  |  |
|int_check_bvsle_bvurem1_ltr_inv_g.smt2                       |    0.084s | 20.556MiB| sat | 0 |  |  |
|int_check_bvugt_bvudiv0_rtl.smt2                             |    0.090s | 19.276MiB| unsat | 0 |  |  |
|int_check_bvslt_bvlshr0_ltr_inv_g.smt2                       |    0.091s | 20.516MiB| sat | 0 |  |  |
|qf_Select_575b_values_0.smt2                                 |    0.092s | 20.52MiB| sat | 0 |  |  |
|int_check_ne_bvashr0_ltr_inv_g.smt2                          |    0.105s | 20.536MiB| sat | 0 |  |  |
|int_check_bvsgt_bvshl0_rtl.smt2                              |    0.106s | 20.02MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_40_QF_UFNIA.smt2                   |    0.107s | 23.052MiB| sat | 0 |  |  |
|int_check_bvsge_bvurem1_ltr_inv_g.smt2                       |    0.130s | 21.272MiB| sat | 0 |  |  |
|qf_InstCombineShift497c_values_0.smt2                        |    0.132s | 22.624MiB| sat | 0 |  |  |
|int_check_bvsge_bvlshr0_rtl.smt2                             |    0.133s | 20.312MiB| sat | 0 |  |  |
|int_check_bvsgt_bvurem1_rtl.smt2                             |    0.139s | 21.028MiB| sat | 0 |  |  |
|int_check_bvsgt_bvlshr0_rtl.smt2                             |    0.142s | 21.056MiB| sat | 0 |  |  |
|int_check_bvslt_bvashr1_rtl.smt2                             |    0.147s | 20.632MiB| sat | 0 |  |  |
|n101-0004.smt2                                               |    0.149s | 26.86MiB| sat | 0 |  |  |
|int_check_bvsgt_bvurem0_rtl.smt2                             |    0.150s | 20.872MiB| sat | 0 |  |  |
|int_check_bvugt_bvashr1_ltr_inv_g.smt2                       |    0.167s | 20.948MiB| sat | 0 |  |  |
|int_check_bvuge_bvshl0_rtl.smt2                              |    0.168s | 20.664MiB| sat | 0 |  |  |
|int_check_bvslt_bvlshr0_rtl.smt2                             |    0.189s | 20.564MiB| sat | 0 |  |  |
|qf_AddSub_1165_values_0.smt2                                 |    0.202s | 20.364MiB| unsat | 0 |  |  |
|int_check_bvslt_bvashr0_rtl.smt2                             |    0.252s | 21.62MiB| sat | 0 |  |  |
|int_check_bvsle_bvadd_ltr_inv_g.smt2                         |    0.260s | 20.964MiB| unsat | 0 |  |  |
|qf_InstCombineShift497b_values_0.smt2                        |    0.268s | 22.708MiB| sat | 0 |  |  |
|int_check_ne_bvashr1_ltr_inv_g.smt2                          |    0.274s | 20.996MiB| sat | 0 |  |  |
|n99-0002.smt2                                                |    0.293s | 25.584MiB| sat | 0 |  |  |
|int_check_bvsle_bvashr0_rtl.smt2                             |    0.304s | 21.2MiB| sat | 0 |  |  |
|qf_Select_575a_values_0.smt2                                 |    0.319s | 21.548MiB| sat | 0 |  |  |
|qf_AddSub_1574_values_0.smt2                                 |    0.337s | 20.732MiB| unsat | 0 |  |  |
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                  |    0.355s | 26.38MiB| unsat | 0 |  |  |
|83314_a702bf8b823398c9e37a_0_UFNIA.smt2                      |    0.367s | 25.364MiB| sat | 0 |  |  |
|65782_cd31513fdcd15701933b_8_QF_UFNIA.smt2                   |    0.368s | 24.104MiB| sat | 0 |  |  |
|qf_AndOrXor_2443_values_0.smt2                               |    0.375s | 21.496MiB| sat | 0 |  |  |
|41958_45c688a4814eb926c254_60_QF_UFNIA.smt2                  |    0.411s | 39.808MiB| sat | 0 |  |  |
|int_check_bvugt_bvashr1_rtl.smt2                             |    0.455s | 21.904MiB| sat | 0 |  |  |
|38347_092cc73601c78e45f4f9_58_QF_UFNIA.smt2                  |    0.504s | 29.356MiB| sat | 0 |  |  |
|int_check_bvsge_bvlshr0_ltr_inv_g.smt2                       |    0.510s | 22.308MiB| sat | 0 |  |  |
|n86-0040.smt2                                                |    0.545s | 34.968MiB| sat | 0 |  |  |
|n131-0035.smt2                                               |    0.806s | 24.804MiB| sat | 0 |  |  |
|n110-0014.smt2                                               |    0.840s | 27.988MiB| sat | 0 |  |  |
|n106-0009.smt2                                               |    0.922s | 28.772MiB| sat | 0 |  |  |
|n92-0047.smt2                                                |    1.168s | 73.964MiB| sat | 0 |  |  |
|n102-0005.smt2                                               |    1.269s | 26.656MiB| sat | 0 |  |  |
|n132-0036.smt2                                               |    1.323s | 25.648MiB| sat | 0 |  |  |
|n65-0019.smt2                                                |    1.345s | 34.76MiB| sat | 0 |  |  |
|41958_45c688a4814eb926c254_59_QF_UFNIA.smt2                  |    1.432s | 61.096MiB| sat | 0 |  |  |
|n128-0032.smt2                                               |    1.515s | 62.124MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_41_QF_UFNIA.smt2                   |    1.523s | 44.028MiB| sat | 0 |  |  |
|39657_2866defdd1f2434b69ab_47_QF_UFNIA.smt2                  |    1.615s | 31.136MiB| sat | 0 |  |  |
|n129-0033.smt2                                               |    1.667s | 42.656MiB| sat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                  |    1.805s | 23.06MiB| unsat | 0 |  |  |
|n137-0041.smt2                                               |    1.919s | 61.808MiB| sat | 0 |  |  |
|n104-0007.smt2                                               |    2.015s | 82.604MiB| unsat | 0 |  |  |
|n108-0012.smt2                                               |    2.169s | 71.588MiB| unsat | 0 |  |  |
|int_check_eq_bvashr0_rtl.smt2                                |    2.178s | 23.456MiB| sat | 0 |  |  |
|n127-0031.smt2                                               |    2.350s | 41.824MiB| sat | 0 |  |  |
|n17-0021.smt2                                                |    2.375s | 87.832MiB| unsat | 0 |  |  |
|940_590f27b1c3c800d3243e_31_QF_UFNIA.smt2                    |    2.659s | 60.88MiB| sat | 0 |  |  |
|n90-0045.smt2                                                |    2.739s | 44.172MiB| sat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                  |    3.006s | 31.532MiB| unsat | 0 |  |  |
|n18-0022.smt2                                                |    3.231s | 50.248MiB| sat | 0 |  |  |
|38347_092cc73601c78e45f4f9_56_QF_UFNIA.smt2                  |    3.323s | 63.544MiB| sat | 0 |  |  |
|39657_2866defdd1f2434b69ab_48_QF_UFNIA.smt2                  |    3.385s | 36.504MiB| sat | 0 |  |  |
|44289_e5a2e5c780236919ee6a_17_QF_UFNIA.smt2                  |    3.870s | 86.652MiB| sat | 0 |  |  |
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                  |    3.872s | 32.48MiB| sat | 0 |  |  |
|n30-0037.smt2                                                |    4.086s | 65.44MiB| sat | 0 |  |  |
|n12-0013.smt2                                                |    4.250s | 68.264MiB| sat | 0 |  |  |
|83314_a702bf8b823398c9e37a_1_UFNIA.smt2                      |    4.285s | 45.088MiB| sat | 0 |  |  |
|n27-0034.smt2                                                |    4.717s | 197.0MiB| unsat | 0 |  |  |
|44289_4066055e0f64d96da11a_14_QF_UFNIA.smt2                  |    4.924s | 97.756MiB| sat | 0 |  |  |
|n26-0033.smt2                                                |    5.532s | 238.0MiB| unsat | 0 |  |  |
|n134-0038.smt2                                               |    5.550s | 34.76MiB| sat | 0 |  |  |
|n53-0006.smt2                                                |    5.833s | 25.516MiB| sat | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFNIA.smt2      |    5.978s | 45.38MiB| sat | 0 |  |  |
|44289_e5a2e5c780236919ee6a_18_QF_UFNIA.smt2                  |    6.458s | 94.38MiB| sat | 0 |  |  |
|n41-0048.smt2                                                |    6.495s | 64.412MiB| unsat | 0 |  |  |
|n37-0044.smt2                                                |    6.551s | 83.88MiB| sat | 0 |  |  |
|n5-0005.smt2                                                 |    6.963s | 42.644MiB| sat | 0 |  |  |
|38347_092cc73601c78e45f4f9_55_QF_UFNIA.smt2                  |    7.030s | 23.976MiB| unsat | 0 |  |  |
|n57-0010.smt2                                                |    7.255s | 72.528MiB| sat | 0 |  |  |
|n96-0051.smt2                                                |    8.267s | 105.0MiB| sat | 0 |  |  |
|n125-0029.smt2                                               |    8.357s | 38.844MiB| sat | 0 |  |  |
|n119-0023.smt2                                               |    8.634s | 59.932MiB| sat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_22_QF_UFNIA.smt2                  |    8.702s | 140.0MiB| sat | 0 |  |  |
|n56-0009.smt2                                                |    9.234s | 89.848MiB| sat | 0 |  |  |
|n9-0009.smt2                                                 |    9.277s | 69.752MiB| sat | 0 |  |  |
|n61-0015.smt2                                                |    9.282s | 126.0MiB| sat | 0 |  |  |
|39657_1c7158801cd59dc13f05_46_QF_UFNIA.smt2                  |    9.295s | 72.56MiB| sat | 0 |  |  |
|940_590f27b1c3c800d3243e_32_QF_UFNIA.smt2                    |    9.312s | 198.0MiB| sat | 0 |  |  |
|n1-0001.smt2                                                 |    9.834s | 774.0MiB| unsat | 0 |  |  |
|qf_muldivrem_152_values_0.smt2                               |    9.853s | 38.984MiB| unsat | 0 |  |  |
|n73-0027.smt2                                                |   10.340s | 46.212MiB| unsat | 0 |  |  |
|n11-0012.smt2                                                |   10.509s | 47.456MiB| sat | 0 |  |  |
|63058_55d6bef5390186355f11_26_QF_UFNIA.smt2                  |   10.620s | 194.0MiB| sat | 0 |  |  |
|n31-0038.smt2                                                |   10.765s | 36.624MiB| sat | 0 |  |  |
|n100-0003.smt2                                               |   10.922s | 47.056MiB| sat | 0 |  |  |
|n133-0037.smt2                                               |   11.029s | 36.328MiB| sat | 0 |  |  |
|n58-0011.smt2                                                |   11.315s | 42.724MiB| sat | 0 |  |  |
|n34-0041.smt2                                                |   11.699s | 73.096MiB| sat | 0 |  |  |
|n38-0045.smt2                                                |   12.065s | 99.0MiB| sat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                  |   12.164s | 40.108MiB| unsat | 0 |  |  |
|n91-0046.smt2                                                |   12.253s | 103.0MiB| sat | 0 |  |  |
|n135-0039.smt2                                               |   12.310s | 50.664MiB| sat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFNIA.smt2      |   12.853s | 153.0MiB| sat | 0 |  |  |
|n35-0042.smt2                                                |   13.130s | 121.0MiB| sat | 0 |  |  |
|72771_f9d228efc97cf1458e38_64_QF_UFNIA.smt2                  |   13.708s | 42.976MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_39_QF_UFNIA.smt2                   |   13.987s | 119.0MiB| sat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFNIA.smt2      |   14.138s | 154.0MiB| sat | 0 |  |  |
|n107-0011.smt2                                               |   15.462s | 97.028MiB| sat | 0 |  |  |
|n46-0053.smt2                                                |   19.315s | 124.0MiB| sat | 0 |  |  |
|n25-0032.smt2                                                |   22.115s | 220.0MiB| sat | 0 |  |  |
|0057.smt2                                                    |   23.040s | 115.0MiB| sat | 0 |  |  |
|940_590f27b1c3c800d3243e_33_QF_UFNIA.smt2                    |   25.211s | 401.0MiB| sat | 0 |  |  |
|n126-0030.smt2                                               |   26.260s | 53.6MiB| unsat | 0 |  |  |
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFNIA.smt2       |   26.391s | 119.0MiB| sat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_23_QF_UFNIA.smt2                  |   26.702s | 183.0MiB| sat | 0 |  |  |
|940_590f27b1c3c800d3243e_30_QF_UFNIA.smt2                    |   28.760s | 328.0MiB| sat | 0 |  |  |
|n124-0028.smt2                                               |   29.900s | 52.316MiB| sat | 0 |  |  |
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                  |   30.643s | 588.0MiB| unsat | 0 |  |  |
|n89-0044.smt2                                                |   37.317s | 85.52MiB| unsat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_24_QF_UFNIA.smt2                  |   43.061s | 226.0MiB| sat | 0 |  |  |
|0065.smt2                                                    |   48.400s | 202.0MiB| sat | 0 |  |  |
|n19-0024.smt2                                                |   50.117s | 109.0MiB| sat | 0 |  |  |
|66603_accdadf23a1cf70ae043_73_QF_UFNIA.smt2                  |   58.966s | 572.0MiB| timeout | 0 |  |  |
|65782_cd31513fdcd15701933b_7_QF_UFNIA.smt2                   |   59.156s | 62.068MiB| timeout | 0 |  |  |
|n3-0003.smt2                                                 |   59.425s | 110.0MiB| timeout | 0 |  |  |
|n98-0001.smt2                                                |   59.660s | 78.708MiB| timeout | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFNIA.smt2      |   59.700s | 278.0MiB| timeout | 0 |  |  |
|n121-0025.smt2                                               |   59.777s | 286.0MiB| timeout | 0 |  |  |
|n63-0017.smt2                                                |   59.783s | 121.0MiB| timeout | 0 |  |  |
|int_check_eq_bvlshr0_rtl.smt2                                |   59.788s | 88.704MiB| timeout | 0 |  |  |
|n23-0030.smt2                                                |   59.798s | 273.0MiB| timeout | 0 |  |  |
|n67-0021.smt2                                                |   59.828s | 378.0MiB| timeout | 0 |  |  |
|n123-0027.smt2                                               |   59.840s | 283.0MiB| timeout | 0 |  |  |
|n81-0035.smt2                                                |   59.841s | 294.0MiB| timeout | 0 |  |  |
|n16-0019.smt2                                                |   59.842s | 144.0MiB| timeout | 0 |  |  |
|n20-0026.smt2                                                |   59.854s | 572.0MiB| timeout | 0 |  |  |
|93493_798593962ee29ad45ac8_52_QF_UFNIA.smt2                  |   59.871s | 248.0MiB| timeout | 0 |  |  |
|n75-0029.smt2                                                |   59.873s | 49.216MiB| timeout | 0 |  |  |
|n77-0031.smt2                                                |   59.875s | 468.0MiB| timeout | 0 |  |  |
|n32-0039.smt2                                                |   59.877s | 269.0MiB| timeout | 0 |  |  |
|0055.smt2                                                    |   59.877s | 1407.0MiB| timeout | 0 |  |  |
|n130-0034.smt2                                               |   59.879s | 176.0MiB| timeout | 0 |  |  |
|n103-0006.smt2                                               |   59.880s | 30.896MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFNIA.smt2      |   59.890s | 123.0MiB| timeout | 0 |  |  |
|n122-0026.smt2                                               |   59.890s | 109.0MiB| timeout | 0 |  |  |
|n84-0038.smt2                                                |   59.894s | 317.0MiB| timeout | 0 |  |  |
|n115-0019.smt2                                               |   59.894s | 68.336MiB| timeout | 0 |  |  |
|n55-0008.smt2                                                |   59.903s | 64.932MiB| timeout | 0 |  |  |
|n62-0016.smt2                                                |   59.908s | 185.0MiB| timeout | 0 |  |  |
|0067.smt2                                                    |   59.914s | 295.0MiB| timeout | 0 |  |  |
|n87-0041.smt2                                                |   59.921s | 87.292MiB| timeout | 0 |  |  |
|n69-0023.smt2                                                |   59.927s | 75.368MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_2_UFNIA.smt2                      |   59.928s | 159.0MiB| timeout | 0 |  |  |
|0061.smt2                                                    |   59.929s | 163.0MiB| timeout | 0 |  |  |
|0060.smt2                                                    |   59.929s | 144.0MiB| timeout | 0 |  |  |
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFNIA.smt2      |   59.930s | 150.0MiB| timeout | 0 |  |  |
|qf_muldivrem_290_292_values_0.smt2                           |   59.931s | 93.464MiB| timeout | 0 |  |  |
|n116-0020.smt2                                               |   59.932s | 536.0MiB| timeout | 0 |  |  |
|n83-0037.smt2                                                |   59.932s | 361.0MiB| timeout | 0 |  |  |
|n10-0010.smt2                                                |   59.935s | 135.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2      |   59.937s | 103.0MiB| timeout | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_36_QF_UFNIA.smt2                  |   59.938s | 56.696MiB| timeout | 0 |  |  |
|qf_muldivrem_229_values_0.smt2                               |   59.938s | 88.96MiB| timeout | 0 |  |  |
|0064.smt2                                                    |   59.941s | 377.0MiB| timeout | 0 |  |  |
|0058.smt2                                                    |   59.943s | 520.0MiB| timeout | 0 |  |  |
|n71-0025.smt2                                                |   59.943s | 1028.0MiB| timeout | 0 |  |  |
|n44-0051.smt2                                                |   59.944s | 332.0MiB| timeout | 0 |  |  |
|qf_InstCombineShift497d_values_0.smt2                        |   59.945s | 79.2MiB| timeout | 0 |  |  |
|39657_1c7158801cd59dc13f05_45_QF_UFNIA.smt2                  |   59.945s | 118.0MiB| timeout | 0 |  |  |
|n97-0000.smt2                                                |   59.948s | 59.72MiB| timeout | 0 |  |  |
|n94-0049.smt2                                                |   59.952s | 82.06MiB| timeout | 0 |  |  |
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFNIA.smt2      |   59.953s | 257.0MiB| timeout | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_35_QF_UFNIA.smt2                  |   59.954s | 56.192MiB| timeout | 0 |  |  |
|41958_32933c5a1384696720a2_61_QF_UFNIA.smt2                  |   59.955s | 41.772MiB| timeout | 0 |  |  |
|n13-0015.smt2                                                |   59.955s | 188.0MiB| timeout | 0 |  |  |
|n117-0021.smt2                                               |   59.955s | 253.0MiB| timeout | 0 |  |  |
|n47-0000.smt2                                                |   59.956s | 72.396MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_57_QF_UFNIA.smt2                  |   59.958s | 37.836MiB| timeout | 0 |  |  |
|n78-0032.smt2                                                |   59.959s | 341.0MiB| timeout | 0 |  |  |
|n66-0020.smt2                                                |   59.961s | 143.0MiB| timeout | 0 |  |  |
|n105-0008.smt2                                               |   59.961s | 107.0MiB| timeout | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_34_QF_UFNIA.smt2                  |   59.962s | 70.256MiB| timeout | 0 |  |  |
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                   |   59.962s | 686.0MiB| timeout | 0 |  |  |
|72658_63104dadde9c6026353f_70_QF_UFNIA.smt2                  |   59.962s | 51.336MiB| timeout | 0 |  |  |
|n49-0002.smt2                                                |   59.962s | 98.448MiB| timeout | 0 |  |  |
|qf_muldivrem_239_values_0.smt2                               |   59.962s | 126.0MiB| timeout | 0 |  |  |
|n40-0047.smt2                                                |   59.964s | 347.0MiB| timeout | 0 |  |  |
|n80-0034.smt2                                                |   59.964s | 58.996MiB| timeout | 0 |  |  |
|n88-0042.smt2                                                |   59.965s | 81.112MiB| timeout | 0 |  |  |
|n82-0036.smt2                                                |   59.967s | 121.0MiB| timeout | 0 |  |  |
|72658_63104dadde9c6026353f_71_QF_UFNIA.smt2                  |   59.967s | 30.444MiB| timeout | 0 |  |  |
|n109-0013.smt2                                               |   59.968s | 150.0MiB| timeout | 0 |  |  |
|n0-0000.smt2                                                 |   59.968s | 127.0MiB| timeout | 0 |  |  |
|n24-0031.smt2                                                |   59.970s | 277.0MiB| timeout | 0 |  |  |
|n112-0016.smt2                                               |   59.970s | 563.0MiB| timeout | 0 |  |  |
|n120-0024.smt2                                               |   59.970s | 78.916MiB| timeout | 0 |  |  |
|n7-0007.smt2                                                 |   59.970s | 174.0MiB| timeout | 0 |  |  |
|41958_32933c5a1384696720a2_63_QF_UFNIA.smt2                  |   59.972s | 37.704MiB| timeout | 0 |  |  |
|n50-0003.smt2                                                |   59.973s | 51.132MiB| timeout | 0 |  |  |
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFNIA.smt2      |   59.973s | 151.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFNIA.smt2      |   59.974s | 85.12MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_29_QF_UFNIA.smt2                    |   59.974s | 257.0MiB| timeout | 0 |  |  |
|n64-0018.smt2                                                |   59.974s | 117.0MiB| timeout | 0 |  |  |
|n51-0004.smt2                                                |   59.974s | 66.512MiB| timeout | 0 |  |  |
|n28-0035.smt2                                                |   59.975s | 255.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_3_UFNIA.smt2                      |   59.978s | 60.44MiB| timeout | 0 |  |  |
|n76-0030.smt2                                                |   59.980s | 1041.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFNIA.smt2      |   59.980s | 86.208MiB| timeout | 0 |  |  |
|n111-0015.smt2                                               |   59.981s | 589.0MiB| timeout | 0 |  |  |
|39657_1c7158801cd59dc13f05_44_QF_UFNIA.smt2                  |   59.982s | 99.328MiB| timeout | 0 |  |  |
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFNIA.smt2      |   59.982s | 155.0MiB| timeout | 0 |  |  |
|n60-0014.smt2                                                |   59.983s | 182.0MiB| timeout | 0 |  |  |
|n22-0029.smt2                                                |   59.983s | 162.0MiB| timeout | 0 |  |  |
|n93-0048.smt2                                                |   59.983s | 122.0MiB| timeout | 0 |  |  |
|n72-0026.smt2                                                |   59.985s | 351.0MiB| timeout | 0 |  |  |
|n79-0033.smt2                                                |   59.988s | 261.0MiB| timeout | 0 |  |  |
|n48-0001.smt2                                                |   59.988s | 91.936MiB| timeout | 0 |  |  |
|n118-0022.smt2                                               |   59.990s | 344.0MiB| timeout | 0 |  |  |
|38347_525a1ca0331f2bcbf520_54_QF_UFNIA.smt2                  |   59.990s | 259.0MiB| timeout | 0 |  |  |
|n6-0006.smt2                                                 |   59.991s | 31.748MiB| timeout | 0 |  |  |
|n33-0040.smt2                                                |   59.991s | 452.0MiB| timeout | 0 |  |  |
|n59-0012.smt2                                                |   59.991s | 87.304MiB| timeout | 0 |  |  |
|n54-0007.smt2                                                |   59.992s | 154.0MiB| timeout | 0 |  |  |
|n52-0005.smt2                                                |   59.992s | 78.896MiB| timeout | 0 |  |  |
|0056.smt2                                                    |   59.992s | 180.0MiB| timeout | 0 |  |  |
|n113-0017.smt2                                               |   59.992s | 150.0MiB| timeout | 0 |  |  |
|n74-0028.smt2                                                |   59.993s | 76.852MiB| timeout | 0 |  |  |
|65782_cd31513fdcd15701933b_5_QF_UFNIA.smt2                   |   59.997s | 68.532MiB| timeout | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFNIA.smt2      |   59.998s | 260.0MiB| timeout | 0 |  |  |
|n2-0002.smt2                                                 |   59.999s | 312.0MiB| timeout | 0 |  |  |
|n36-0043.smt2                                                |   60.002s | 356.0MiB| timeout | 0 |  |  |
|0062.smt2                                                    |   60.003s | 2700.0MiB| timeout | 0 |  |  |
|n4-0004.smt2                                                 |   60.005s | 134.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_4_UFNIA.smt2                      |   60.005s | 221.0MiB| timeout | 0 |  |  |
|41958_32933c5a1384696720a2_62_QF_UFNIA.smt2                  |   60.007s | 51.14MiB| timeout | 0 |  |  |
|n68-0022.smt2                                                |   60.007s | 170.0MiB| timeout | 0 |  |  |
|n8-0008.smt2                                                 |   60.008s | 198.0MiB| timeout | 0 |  |  |
|n136-0040.smt2                                               |   60.009s | 353.0MiB| timeout | 0 |  |  |
|n42-0049.smt2                                                |   60.010s | 169.0MiB| timeout | 0 |  |  |
|n95-0050.smt2                                                |   60.011s | 642.0MiB| timeout | 0 |  |  |
|44289_4066055e0f64d96da11a_15_QF_UFNIA.smt2                  |   60.011s | 497.0MiB| timeout | 0 |  |  |
|0054.smt2                                                    |   60.013s | 1406.0MiB| timeout | 0 |  |  |
|n39-0046.smt2                                                |   60.015s | 1299.0MiB| timeout | 0 |  |  |
|n21-0027.smt2                                                |   60.020s | 150.0MiB| timeout | 0 |  |  |
|n70-0024.smt2                                                |   60.020s | 1046.0MiB| timeout | 0 |  |  |
|n85-0039.smt2                                                |   60.021s | 456.0MiB| timeout | 0 |  |  |
|n45-0052.smt2                                                |   60.027s | 936.0MiB| timeout | 0 |  |  |
|0059.smt2                                                    |   60.028s | 563.0MiB| timeout | 0 |  |  |
|n29-0036.smt2                                                |   60.039s | 1718.0MiB| timeout | 0 |  |  |
|n43-0050.smt2                                                |   60.048s | 852.0MiB| timeout | 0 |  |  |
|0066.smt2                                                    |   60.064s | 1921.0MiB| timeout | 0 |  |  |
|0063.smt2                                                    |   60.067s | 1485.0MiB| timeout | 0 |  |  |
|n114-0018.smt2                                               |   60.514s | 106.0MiB| timeout | 0 |  |  |
