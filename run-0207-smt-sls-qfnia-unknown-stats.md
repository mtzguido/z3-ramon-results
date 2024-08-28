# data

* SAT 36
* UNSAT 0
* TIMEOUT 261
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls-qfnia-unknown
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 04d0e9492b0066675c75fc5fb1df6b23b79607e5
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_UFNIA_UNKNOWN
Z3 commit message: set log level of revert repair down to 3

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|qf_InstCombineShift497a_values_0.smt2                        |    0.007s | 18.764MiB| sat | 0 |  |  |
|int_check_bvule_bvudiv1_ltr_inv_g.smt2                       |    0.007s | 18.592MiB| sat | 0 |  |  |
|int_check_bvsgt_bvadd_rtl.smt2                               |    0.007s | 18.768MiB| sat | 0 |  |  |
|int_check_bvsgt_bvshl0_ltr_inv_g.smt2                        |    0.008s | 18.764MiB| sat | 0 |  |  |
|qf_AndOrXor_230_values_0.smt2                                |    0.008s | 18.768MiB| sat | 0 |  |  |
|qf_AndOrXor_210_values_0.smt2                                |    0.008s | 18.68MiB| sat | 0 |  |  |
|qf_AndOrXor_2443_values_0.smt2                               |    0.008s | 19.008MiB| sat | 0 |  |  |
|int_check_bvsgt_bvurem0_rtl.smt2                             |    0.009s | 18.64MiB| sat | 0 |  |  |
|int_check_bvsle_bvurem1_ltr_inv_g.smt2                       |    0.009s | 18.764MiB| sat | 0 |  |  |
|qf_InstCombineShift497c_values_0.smt2                        |    0.009s | 19.02MiB| sat | 0 |  |  |
|int_check_bvsgt_bvashr1_ltr_inv_g.smt2                       |    0.013s | 18.72MiB| sat | 0 |  |  |
|int_check_bvsle_bvashr1_rtl.smt2                             |    0.013s | 18.848MiB| sat | 0 |  |  |
|int_check_bvsgt_bvshl0_rtl.smt2                              |    0.014s | 18.744MiB| sat | 0 |  |  |
|qf_AndOrXor_290_values_7.smt2                                |    0.015s | 19.0MiB| sat | 0 |  |  |
|int_check_ne_bvashr0_ltr_inv_g.smt2                          |    0.015s | 18.768MiB| sat | 0 |  |  |
|int_check_bvslt_bvudiv0_ltr_inv_g.smt2                       |    0.016s | 18.764MiB| sat | 0 |  |  |
|qf_Select_575a_values_0.smt2                                 |    0.019s | 18.768MiB| sat | 0 |  |  |
|int_check_bvsle_bvashr0_rtl.smt2                             |    0.021s | 18.684MiB| sat | 0 |  |  |
|int_check_bvsle_bvudiv0_rtl.smt2                             |    0.073s | 18.848MiB| sat | 0 |  |  |
|qf_Select_575b_values_0.smt2                                 |    0.152s | 18.828MiB| sat | 0 |  |  |
|n86-0040.smt2                                                |    0.371s | 27.856MiB| sat | 0 |  |  |
|n125-0029.smt2                                               |    0.476s | 24.064MiB| sat | 0 |  |  |
|72658_63104dadde9c6026353f_70_QF_UFNIA.smt2                  |    0.707s | 19.76MiB| sat | 0 |  |  |
|n123-0027.smt2                                               |    0.796s | 26.772MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_40_QF_UFNIA.smt2                   |    1.107s | 21.708MiB| sat | 0 |  |  |
|n65-0019.smt2                                                |    1.234s | 25.204MiB| sat | 0 |  |  |
|n134-0038.smt2                                               |    1.289s | 21.852MiB| sat | 0 |  |  |
|n99-0002.smt2                                                |    1.488s | 21.692MiB| sat | 0 |  |  |
|72771_f9d228efc97cf1458e38_64_QF_UFNIA.smt2                  |    1.519s | 29.824MiB| sat | 0 |  |  |
|41958_45c688a4814eb926c254_59_QF_UFNIA.smt2                  |    4.603s | 38.864MiB| sat | 0 |  |  |
|n88-0042.smt2                                                |    5.170s | 36.32MiB| sat | 0 |  |  |
|int_check_bvsge_bvashr1_rtl.smt2                             |    5.194s | 18.844MiB| sat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFNIA.smt2      |    8.736s | 52.428MiB| sat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFNIA.smt2      |   10.297s | 61.784MiB| sat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_22_QF_UFNIA.smt2                  |   13.698s | 89.384MiB| sat | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFNIA.smt2      |   34.395s | 196.0MiB| sat | 0 |  |  |
|n75-0029.smt2                                                |   58.885s | 28.104MiB| timeout | 0 |  |  |
|0057.smt2                                                    |   59.490s | 58.556MiB| timeout | 0 |  |  |
|n119-0023.smt2                                               |   59.660s | 42.16MiB| timeout | 0 |  |  |
|0063.smt2                                                    |   59.805s | 935.0MiB| timeout | 0 |  |  |
|int_check_eq_bvurem0_ltr_inv_g.smt2                          |   59.811s | 18.788MiB| timeout | 0 |  |  |
|n71-0025.smt2                                                |   59.813s | 495.0MiB| timeout | 0 |  |  |
|n101-0004.smt2                                               |   59.823s | 23.328MiB| timeout | 0 |  |  |
|int_check_ne_bvashr1_ltr_inv_g.smt2                          |   59.831s | 19.02MiB| timeout | 0 |  |  |
|int_check_bvsle_bvshl0_ltr_inv_g.smt2                        |   59.831s | 18.832MiB| timeout | 0 |  |  |
|n13-0015.smt2                                                |   59.863s | 99.42MiB| timeout | 0 |  |  |
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                  |   59.864s | 30.744MiB| timeout | 0 |  |  |
|qf_AddSub_1619_values_0.smt2                                 |   59.885s | 18.8MiB| timeout | 0 |  |  |
|n124-0028.smt2                                               |   59.885s | 27.484MiB| timeout | 0 |  |  |
|n128-0032.smt2                                               |   59.888s | 51.492MiB| timeout | 0 |  |  |
|int_check_bvuge_bvurem0_rtl.smt2                             |   59.890s | 18.78MiB| timeout | 0 |  |  |
|n116-0020.smt2                                               |   59.894s | 374.0MiB| timeout | 0 |  |  |
|n48-0001.smt2                                                |   59.895s | 24.74MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_73_QF_UFNIA.smt2                  |   59.899s | 183.0MiB| timeout | 0 |  |  |
|n67-0021.smt2                                                |   59.901s | 301.0MiB| timeout | 0 |  |  |
|n106-0009.smt2                                               |   59.903s | 23.592MiB| timeout | 0 |  |  |
|n82-0036.smt2                                                |   59.911s | 38.292MiB| timeout | 0 |  |  |
|n111-0015.smt2                                               |   59.915s | 517.0MiB| timeout | 0 |  |  |
|41958_32933c5a1384696720a2_62_QF_UFNIA.smt2                  |   59.916s | 20.984MiB| timeout | 0 |  |  |
|n103-0006.smt2                                               |   59.916s | 24.94MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_3_UFNIA.smt2                      |   59.917s | 26.484MiB| timeout | 0 |  |  |
|qf_AndOrXor_794_values_121.smt2                              |   59.918s | 19.04MiB| timeout | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_23_QF_UFNIA.smt2                  |   59.919s | 93.312MiB| timeout | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_34_QF_UFNIA.smt2                  |   59.924s | 22.928MiB| timeout | 0 |  |  |
|n85-0039.smt2                                                |   59.926s | 237.0MiB| timeout | 0 |  |  |
|int_check_eq_bvurem0_rtl.smt2                                |   59.928s | 19.052MiB| timeout | 0 |  |  |
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                  |   59.928s | 25.548MiB| timeout | 0 |  |  |
|39657_2866defdd1f2434b69ab_48_QF_UFNIA.smt2                  |   59.929s | 29.34MiB| timeout | 0 |  |  |
|n6-0006.smt2                                                 |   59.929s | 26.7MiB| timeout | 0 |  |  |
|n92-0047.smt2                                                |   59.929s | 64.396MiB| timeout | 0 |  |  |
|n135-0039.smt2                                               |   59.931s | 28.992MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_56_QF_UFNIA.smt2                  |   59.931s | 36.328MiB| timeout | 0 |  |  |
|int_check_eq_bvudiv1_rtl.smt2                                |   59.932s | 18.808MiB| timeout | 0 |  |  |
|n109-0013.smt2                                               |   59.934s | 93.332MiB| timeout | 0 |  |  |
|n87-0041.smt2                                                |   59.936s | 36.12MiB| timeout | 0 |  |  |
|qf_muldivrem_229_values_0.smt2                               |   59.936s | 18.8MiB| timeout | 0 |  |  |
|0060.smt2                                                    |   59.937s | 60.86MiB| timeout | 0 |  |  |
|n77-0031.smt2                                                |   59.941s | 215.0MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_55_QF_UFNIA.smt2                  |   59.945s | 21.176MiB| timeout | 0 |  |  |
|int_check_bvslt_bvlshr0_ltr_inv_g.smt2                       |   59.948s | 18.888MiB| timeout | 0 |  |  |
|int_check_bvslt_bvlshr0_rtl.smt2                             |   59.948s | 18.856MiB| timeout | 0 |  |  |
|n127-0031.smt2                                               |   59.949s | 27.748MiB| timeout | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_36_QF_UFNIA.smt2                  |   59.951s | 26.14MiB| timeout | 0 |  |  |
|n59-0012.smt2                                                |   59.953s | 32.22MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_0_UFNIA.smt2                      |   59.954s | 22.808MiB| timeout | 0 |  |  |
|n64-0018.smt2                                                |   59.954s | 90.376MiB| timeout | 0 |  |  |
|n53-0006.smt2                                                |   59.954s | 22.164MiB| timeout | 0 |  |  |
|n33-0040.smt2                                                |   59.955s | 177.0MiB| timeout | 0 |  |  |
|n63-0017.smt2                                                |   59.956s | 87.38MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_58_QF_UFNIA.smt2                  |   59.956s | 25.392MiB| timeout | 0 |  |  |
|qf_muldivrem_239_values_0.smt2                               |   59.957s | 18.824MiB| timeout | 0 |  |  |
|qf_AndOrXor_1894_values_0.smt2                               |   59.957s | 18.828MiB| timeout | 0 |  |  |
|int_check_bvult_bvurem0_ltr_inv_g.smt2                       |   59.958s | 18.748MiB| timeout | 0 |  |  |
|n24-0031.smt2                                                |   59.959s | 128.0MiB| timeout | 0 |  |  |
|39657_1c7158801cd59dc13f05_46_QF_UFNIA.smt2                  |   59.959s | 44.112MiB| timeout | 0 |  |  |
|n120-0024.smt2                                               |   59.959s | 37.384MiB| timeout | 0 |  |  |
|n104-0007.smt2                                               |   59.959s | 70.912MiB| timeout | 0 |  |  |
|n73-0027.smt2                                                |   59.960s | 29.128MiB| timeout | 0 |  |  |
|n60-0014.smt2                                                |   59.960s | 100.0MiB| timeout | 0 |  |  |
|n97-0000.smt2                                                |   59.960s | 28.832MiB| timeout | 0 |  |  |
|n21-0027.smt2                                                |   59.961s | 78.856MiB| timeout | 0 |  |  |
|n136-0040.smt2                                               |   59.962s | 163.0MiB| timeout | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                  |   59.962s | 21.072MiB| timeout | 0 |  |  |
|n38-0045.smt2                                                |   59.962s | 81.428MiB| timeout | 0 |  |  |
|n40-0047.smt2                                                |   59.962s | 251.0MiB| timeout | 0 |  |  |
|n90-0045.smt2                                                |   59.962s | 28.24MiB| timeout | 0 |  |  |
|n28-0035.smt2                                                |   59.963s | 151.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_30_QF_UFNIA.smt2                    |   59.965s | 92.58MiB| timeout | 0 |  |  |
|qf_muldivrem_152_values_0.smt2                               |   59.966s | 19.04MiB| timeout | 0 |  |  |
|n129-0033.smt2                                               |   59.967s | 31.536MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_57_QF_UFNIA.smt2                  |   59.967s | 23.804MiB| timeout | 0 |  |  |
|int_check_bvugt_bvashr0_ltr_inv_g.smt2                       |   59.968s | 18.82MiB| timeout | 0 |  |  |
|n126-0030.smt2                                               |   59.968s | 22.512MiB| timeout | 0 |  |  |
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFNIA.smt2      |   59.969s | 60.252MiB| timeout | 0 |  |  |
|n133-0037.smt2                                               |   59.969s | 20.936MiB| timeout | 0 |  |  |
|n70-0024.smt2                                                |   59.969s | 496.0MiB| timeout | 0 |  |  |
|n83-0037.smt2                                                |   59.970s | 194.0MiB| timeout | 0 |  |  |
|0064.smt2                                                    |   59.970s | 260.0MiB| timeout | 0 |  |  |
|72658_63104dadde9c6026353f_71_QF_UFNIA.smt2                  |   59.970s | 19.948MiB| timeout | 0 |  |  |
|int_check_bvule_bvurem1_ltr_inv_g.smt2                       |   59.971s | 18.736MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_31_QF_UFNIA.smt2                    |   59.971s | 41.56MiB| timeout | 0 |  |  |
|n54-0007.smt2                                                |   59.973s | 90.764MiB| timeout | 0 |  |  |
|n130-0034.smt2                                               |   59.973s | 78.68MiB| timeout | 0 |  |  |
|int_check_bvsle_bvadd_ltr_inv_g.smt2                         |   59.973s | 18.816MiB| timeout | 0 |  |  |
|44289_e5a2e5c780236919ee6a_17_QF_UFNIA.smt2                  |   59.973s | 73.688MiB| timeout | 0 |  |  |
|int_check_bvsge_bvudiv1_rtl.smt2                             |   59.974s | 18.856MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_29_QF_UFNIA.smt2                    |   59.974s | 95.3MiB| timeout | 0 |  |  |
|int_check_bvugt_bvudiv0_rtl.smt2                             |   59.975s | 18.776MiB| timeout | 0 |  |  |
|n58-0011.smt2                                                |   59.975s | 23.912MiB| timeout | 0 |  |  |
|qf_AddSub_1165_values_0.smt2                                 |   59.975s | 18.84MiB| timeout | 0 |  |  |
|n74-0028.smt2                                                |   59.976s | 37.512MiB| timeout | 0 |  |  |
|n49-0002.smt2                                                |   59.977s | 25.1MiB| timeout | 0 |  |  |
|n105-0008.smt2                                               |   59.978s | 32.108MiB| timeout | 0 |  |  |
|n46-0053.smt2                                                |   59.979s | 77.936MiB| timeout | 0 |  |  |
|3106_1c933134166dbad31f79_39_QF_UFNIA.smt2                   |   59.979s | 62.776MiB| timeout | 0 |  |  |
|n137-0041.smt2                                               |   59.979s | 53.708MiB| timeout | 0 |  |  |
|65782_cd31513fdcd15701933b_6_QF_UFNIA.smt2                   |   59.979s | 20.092MiB| timeout | 0 |  |  |
|0061.smt2                                                    |   59.980s | 70.468MiB| timeout | 0 |  |  |
|n3-0003.smt2                                                 |   59.980s | 36.588MiB| timeout | 0 |  |  |
|qf_InstCombineShift497d_values_0.smt2                        |   59.980s | 18.836MiB| timeout | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                  |   59.980s | 26.412MiB| timeout | 0 |  |  |
|n26-0033.smt2                                                |   59.980s | 137.0MiB| timeout | 0 |  |  |
|n19-0024.smt2                                                |   59.982s | 98.244MiB| timeout | 0 |  |  |
|n114-0018.smt2                                               |   59.982s | 56.856MiB| timeout | 0 |  |  |
|0059.smt2                                                    |   59.982s | 470.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFNIA.smt2      |   59.983s | 33.076MiB| timeout | 0 |  |  |
|int_check_eq_bvudiv0_rtl.smt2                                |   59.983s | 19.08MiB| timeout | 0 |  |  |
|int_check_bvslt_bvashr1_rtl.smt2                             |   59.983s | 18.856MiB| timeout | 0 |  |  |
|n44-0051.smt2                                                |   59.983s | 249.0MiB| timeout | 0 |  |  |
|65782_cd31513fdcd15701933b_8_QF_UFNIA.smt2                   |   59.983s | 22.528MiB| timeout | 0 |  |  |
|63058_aa742630eef64f949de269382c1f9035_25_UFNIA.smt2         |   59.983s | 21.208MiB| timeout | 0 |  |  |
|n35-0042.smt2                                                |   59.984s | 51.156MiB| timeout | 0 |  |  |
|n4-0004.smt2                                                 |   59.984s | 47.812MiB| timeout | 0 |  |  |
|44289_e5a2e5c780236919ee6a_18_QF_UFNIA.smt2                  |   59.984s | 78.268MiB| timeout | 0 |  |  |
|n69-0023.smt2                                                |   59.984s | 35.784MiB| timeout | 0 |  |  |
|int_check_bvult_bvneg_ltr_inv_g.smt2                         |   59.985s | 18.76MiB| timeout | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                  |   59.986s | 25.828MiB| timeout | 0 |  |  |
|n102-0005.smt2                                               |   59.986s | 21.632MiB| timeout | 0 |  |  |
|n47-0000.smt2                                                |   59.986s | 25.056MiB| timeout | 0 |  |  |
|0067.smt2                                                    |   59.986s | 235.0MiB| timeout | 0 |  |  |
|n76-0030.smt2                                                |   59.987s | 496.0MiB| timeout | 0 |  |  |
|n132-0036.smt2                                               |   59.987s | 21.044MiB| timeout | 0 |  |  |
|int_check_bvuge_bvshl0_rtl.smt2                              |   59.987s | 18.812MiB| timeout | 0 |  |  |
|int_check_bvugt_bvurem0_rtl.smt2                             |   59.987s | 18.792MiB| timeout | 0 |  |  |
|int_check_bvsge_bvlshr0_rtl.smt2                             |   59.987s | 18.868MiB| timeout | 0 |  |  |
|n42-0049.smt2                                                |   59.988s | 84.844MiB| timeout | 0 |  |  |
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFNIA.smt2      |   59.988s | 65.484MiB| timeout | 0 |  |  |
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFNIA.smt2      |   59.988s | 64.936MiB| timeout | 0 |  |  |
|n66-0020.smt2                                                |   59.988s | 130.0MiB| timeout | 0 |  |  |
|n52-0005.smt2                                                |   59.989s | 21.256MiB| timeout | 0 |  |  |
|n117-0021.smt2                                               |   59.989s | 104.0MiB| timeout | 0 |  |  |
|39657_2866defdd1f2434b69ab_47_QF_UFNIA.smt2                  |   59.989s | 24.668MiB| timeout | 0 |  |  |
|41958_32933c5a1384696720a2_61_QF_UFNIA.smt2                  |   59.990s | 21.844MiB| timeout | 0 |  |  |
|n12-0013.smt2                                                |   59.990s | 52.308MiB| timeout | 0 |  |  |
|int_check_bvuge_bvashr1_rtl.smt2                             |   59.990s | 19.02MiB| timeout | 0 |  |  |
|n22-0029.smt2                                                |   59.990s | 93.32MiB| timeout | 0 |  |  |
|n118-0022.smt2                                               |   59.991s | 211.0MiB| timeout | 0 |  |  |
|n131-0035.smt2                                               |   59.991s | 22.396MiB| timeout | 0 |  |  |
|n80-0034.smt2                                                |   59.991s | 26.412MiB| timeout | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_35_QF_UFNIA.smt2                  |   59.991s | 35.336MiB| timeout | 0 |  |  |
|int_check_bvule_bvneg_ltr_inv_g.smt2                         |   59.991s | 19.0MiB| timeout | 0 |  |  |
|n91-0046.smt2                                                |   59.991s | 66.324MiB| timeout | 0 |  |  |
|int_check_bvult_bvurem1_ltr_inv_g.smt2                       |   59.991s | 18.74MiB| timeout | 0 |  |  |
|qf_Select_700_values_123.smt2                                |   59.991s | 18.796MiB| timeout | 0 |  |  |
|n0-0000.smt2                                                 |   59.992s | 79.848MiB| timeout | 0 |  |  |
|n107-0011.smt2                                               |   59.992s | 47.788MiB| timeout | 0 |  |  |
|44289_4066055e0f64d96da11a_14_QF_UFNIA.smt2                  |   59.992s | 69.82MiB| timeout | 0 |  |  |
|n100-0003.smt2                                               |   59.992s | 26.896MiB| timeout | 0 |  |  |
|n41-0048.smt2                                                |   59.992s | 47.308MiB| timeout | 0 |  |  |
|n9-0009.smt2                                                 |   59.992s | 46.796MiB| timeout | 0 |  |  |
|n51-0004.smt2                                                |   59.992s | 23.816MiB| timeout | 0 |  |  |
|n72-0026.smt2                                                |   59.993s | 190.0MiB| timeout | 0 |  |  |
|n113-0017.smt2                                               |   59.993s | 75.472MiB| timeout | 0 |  |  |
|qf_Select_510_values_0.smt2                                  |   59.994s | 18.856MiB| timeout | 0 |  |  |
|n112-0016.smt2                                               |   59.994s | 379.0MiB| timeout | 0 |  |  |
|39657_1c7158801cd59dc13f05_44_QF_UFNIA.smt2                  |   59.994s | 43.808MiB| timeout | 0 |  |  |
|n94-0049.smt2                                                |   59.994s | 39.52MiB| timeout | 0 |  |  |
|n78-0032.smt2                                                |   59.994s | 216.0MiB| timeout | 0 |  |  |
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFNIA.smt2       |   59.994s | 69.576MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFNIA.smt2      |   59.994s | 37.028MiB| timeout | 0 |  |  |
|n34-0041.smt2                                                |   59.995s | 64.796MiB| timeout | 0 |  |  |
|qf_Select_727_values_0.smt2                                  |   59.995s | 18.836MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                  |   59.995s | 245.0MiB| timeout | 0 |  |  |
|n81-0035.smt2                                                |   59.995s | 128.0MiB| timeout | 0 |  |  |
|65782_cd31513fdcd15701933b_5_QF_UFNIA.smt2                   |   59.995s | 30.188MiB| timeout | 0 |  |  |
|n108-0012.smt2                                               |   59.995s | 83.412MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFNIA.smt2      |   59.995s | 30.84MiB| timeout | 0 |  |  |
|int_check_bvsgt_bvurem1_rtl.smt2                             |   59.995s | 19.12MiB| timeout | 0 |  |  |
|n56-0009.smt2                                                |   59.995s | 45.696MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_32_QF_UFNIA.smt2                    |   59.996s | 92.852MiB| timeout | 0 |  |  |
|int_check_bvsle_bvashr0_ltr_inv_g.smt2                       |   59.996s | 18.856MiB| timeout | 0 |  |  |
|int_check_bvsge_bvneg_ltr_inv_g.smt2                         |   59.996s | 18.792MiB| timeout | 0 |  |  |
|44289_4066055e0f64d96da11a_15_QF_UFNIA.smt2                  |   59.996s | 118.0MiB| timeout | 0 |  |  |
|qf_Select_705_values_0.smt2                                  |   59.996s | 18.832MiB| timeout | 0 |  |  |
|0058.smt2                                                    |   59.997s | 504.0MiB| timeout | 0 |  |  |
|qf_InstCombineShift497b_values_0.smt2                        |   59.997s | 19.028MiB| timeout | 0 |  |  |
|n98-0001.smt2                                                |   59.997s | 27.236MiB| timeout | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_24_QF_UFNIA.smt2                  |   59.997s | 119.0MiB| timeout | 0 |  |  |
|3106_1c933134166dbad31f79_41_QF_UFNIA.smt2                   |   59.997s | 34.94MiB| timeout | 0 |  |  |
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFNIA.smt2      |   59.997s | 161.0MiB| timeout | 0 |  |  |
|n36-0043.smt2                                                |   59.998s | 280.0MiB| timeout | 0 |  |  |
|int_check_bvule_bvurem0_ltr_inv_g.smt2                       |   59.998s | 18.744MiB| timeout | 0 |  |  |
|n95-0050.smt2                                                |   59.998s | 252.0MiB| timeout | 0 |  |  |
|int_check_bvugt_bvashr1_rtl.smt2                             |   59.998s | 19.02MiB| timeout | 0 |  |  |
|38347_525a1ca0331f2bcbf520_54_QF_UFNIA.smt2                  |   59.998s | 90.764MiB| timeout | 0 |  |  |
|n18-0022.smt2                                                |   59.998s | 38.92MiB| timeout | 0 |  |  |
|41958_45c688a4814eb926c254_60_QF_UFNIA.smt2                  |   59.998s | 33.176MiB| timeout | 0 |  |  |
|int_check_eq_bvashr0_rtl.smt2                                |   59.999s | 19.152MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_33_QF_UFNIA.smt2                    |   59.999s | 93.508MiB| timeout | 0 |  |  |
|n84-0038.smt2                                                |   59.999s | 197.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_2_UFNIA.smt2                      |   59.999s | 78.968MiB| timeout | 0 |  |  |
|int_check_eq_bvlshr0_rtl.smt2                                |   59.999s | 18.816MiB| timeout | 0 |  |  |
|n10-0010.smt2                                                |   59.999s | 96.144MiB| timeout | 0 |  |  |
|int_check_bvult_bvashr1_rtl.smt2                             |   59.999s | 18.996MiB| timeout | 0 |  |  |
|int_check_bvuge_bvashr1_ltr_inv_g.smt2                       |   60.000s | 18.852MiB| timeout | 0 |  |  |
|n8-0008.smt2                                                 |   60.000s | 97.284MiB| timeout | 0 |  |  |
|n110-0014.smt2                                               |   60.000s | 22.94MiB| timeout | 0 |  |  |
|n62-0016.smt2                                                |   60.000s | 100.0MiB| timeout | 0 |  |  |
|qf_muldivrem_290_292_values_0.smt2                           |   60.000s | 18.784MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2      |   60.000s | 44.596MiB| timeout | 0 |  |  |
|n20-0026.smt2                                                |   60.000s | 376.0MiB| timeout | 0 |  |  |
|qf_AndOrXor_1869_values_0.smt2                               |   60.000s | 18.8MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_4_UFNIA.smt2                      |   60.000s | 92.028MiB| timeout | 0 |  |  |
|int_check_bvugt_bvudiv1_rtl.smt2                             |   60.000s | 19.084MiB| timeout | 0 |  |  |
|n11-0012.smt2                                                |   60.001s | 33.376MiB| timeout | 0 |  |  |
|n96-0051.smt2                                                |   60.001s | 91.096MiB| timeout | 0 |  |  |
|int_check_bvslt_bvashr0_rtl.smt2                             |   60.001s | 19.156MiB| timeout | 0 |  |  |
|int_check_bvsge_bvurem1_ltr_inv_g.smt2                       |   60.001s | 19.0MiB| timeout | 0 |  |  |
|n55-0008.smt2                                                |   60.001s | 23.64MiB| timeout | 0 |  |  |
|65782_cd31513fdcd15701933b_7_QF_UFNIA.smt2                   |   60.002s | 22.36MiB| timeout | 0 |  |  |
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                   |   60.002s | 221.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_1_UFNIA.smt2                      |   60.002s | 28.436MiB| timeout | 0 |  |  |
|39657_1c7158801cd59dc13f05_45_QF_UFNIA.smt2                  |   60.002s | 43.496MiB| timeout | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFNIA.smt2      |   60.002s | 94.244MiB| timeout | 0 |  |  |
|n32-0039.smt2                                                |   60.002s | 154.0MiB| timeout | 0 |  |  |
|n50-0003.smt2                                                |   60.003s | 23.72MiB| timeout | 0 |  |  |
|n37-0044.smt2                                                |   60.003s | 57.812MiB| timeout | 0 |  |  |
|int_check_bvsgt_bvashr0_rtl.smt2                             |   60.003s | 18.852MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFNIA.smt2      |   60.003s | 28.616MiB| timeout | 0 |  |  |
|93493_798593962ee29ad45ac8_52_QF_UFNIA.smt2                  |   60.004s | 78.884MiB| timeout | 0 |  |  |
|n68-0022.smt2                                                |   60.004s | 124.0MiB| timeout | 0 |  |  |
|0065.smt2                                                    |   60.005s | 97.788MiB| timeout | 0 |  |  |
|n17-0021.smt2                                                |   60.005s | 79.288MiB| timeout | 0 |  |  |
|n30-0037.smt2                                                |   60.005s | 46.592MiB| timeout | 0 |  |  |
|n93-0048.smt2                                                |   60.005s | 29.04MiB| timeout | 0 |  |  |
|n57-0010.smt2                                                |   60.005s | 47.572MiB| timeout | 0 |  |  |
|n16-0019.smt2                                                |   60.006s | 103.0MiB| timeout | 0 |  |  |
|n79-0033.smt2                                                |   60.006s | 109.0MiB| timeout | 0 |  |  |
|0056.smt2                                                    |   60.006s | 75.5MiB| timeout | 0 |  |  |
|n2-0002.smt2                                                 |   60.007s | 213.0MiB| timeout | 0 |  |  |
|n27-0034.smt2                                                |   60.007s | 138.0MiB| timeout | 0 |  |  |
|n5-0005.smt2                                                 |   60.008s | 35.48MiB| timeout | 0 |  |  |
|n61-0015.smt2                                                |   60.008s | 91.788MiB| timeout | 0 |  |  |
|n7-0007.smt2                                                 |   60.008s | 131.0MiB| timeout | 0 |  |  |
|n115-0019.smt2                                               |   60.009s | 32.688MiB| timeout | 0 |  |  |
|n1-0001.smt2                                                 |   60.010s | 706.0MiB| timeout | 0 |  |  |
|n25-0032.smt2                                                |   60.010s | 120.0MiB| timeout | 0 |  |  |
|0055.smt2                                                    |   60.010s | 1429.0MiB| timeout | 0 |  |  |
|n121-0025.smt2                                               |   60.011s | 178.0MiB| timeout | 0 |  |  |
|n31-0038.smt2                                                |   60.012s | 26.184MiB| timeout | 0 |  |  |
|n43-0050.smt2                                                |   60.013s | 469.0MiB| timeout | 0 |  |  |
|63058_55d6bef5390186355f11_26_QF_UFNIA.smt2                  |   60.015s | 89.392MiB| timeout | 0 |  |  |
|n39-0046.smt2                                                |   60.019s | 732.0MiB| timeout | 0 |  |  |
|n45-0052.smt2                                                |   60.024s | 718.0MiB| timeout | 0 |  |  |
|n29-0036.smt2                                                |   60.029s | 1741.0MiB| timeout | 0 |  |  |
|int_check_bvugt_bvashr1_ltr_inv_g.smt2                       |   60.031s | 18.884MiB| timeout | 0 |  |  |
|n122-0026.smt2                                               |   60.035s | 31.348MiB| timeout | 0 |  |  |
|0054.smt2                                                    |   60.037s | 1429.0MiB| timeout | 0 |  |  |
|0066.smt2                                                    |   60.037s | 1315.0MiB| timeout | 0 |  |  |
|int_check_bvsge_bvlshr0_ltr_inv_g.smt2                       |   60.048s | 19.072MiB| timeout | 0 |  |  |
|0062.smt2                                                    |   60.051s | 2681.0MiB| timeout | 0 |  |  |
|int_check_bvsgt_bvlshr0_rtl.smt2                             |   60.053s | 19.08MiB| timeout | 0 |  |  |
|qf_AddSub_1574_values_0.smt2                                 |   60.066s | 19.02MiB| timeout | 0 |  |  |
|41958_32933c5a1384696720a2_63_QF_UFNIA.smt2                  |   60.075s | 21.024MiB| timeout | 0 |  |  |
|n23-0030.smt2                                                |   60.106s | 105.0MiB| timeout | 0 |  |  |
|int_check_bvsgt_bvlshr1_rtl.smt2                             |   60.115s | 18.86MiB| timeout | 0 |  |  |
|n89-0044.smt2                                                |   60.126s | 35.476MiB| timeout | 0 |  |  |
