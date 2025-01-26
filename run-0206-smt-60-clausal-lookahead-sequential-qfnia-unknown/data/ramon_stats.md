# data

* SAT 105
* UNSAT 40
* TIMEOUT 152
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-60-clausal-lookahead-sequential-qfnia-unknown
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 04d0e9492b0066675c75fc5fb1df6b23b79607e5
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" smt.sls.enable=true smt.sls.parallel=false model_validate=true sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_UFNIA_UNKNOWN
Z3 commit message: set log level of revert repair down to 3

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|int_check_bvule_bvneg_ltr_inv_g.smt2                         |    0.014s | 52.576MiB| unsat | 0 |  |  |
|int_check_bvult_bvurem1_ltr_inv_g.smt2                       |    0.014s | 52.548MiB| unsat | 0 |  |  |
|int_check_bvule_bvurem1_ltr_inv_g.smt2                       |    0.015s | 52.392MiB| unsat | 0 |  |  |
|qf_Select_705_values_0.smt2                                  |    0.015s | 52.832MiB| unsat | 0 |  |  |
|qf_AndOrXor_1894_values_0.smt2                               |    0.015s | 52.812MiB| unsat | 0 |  |  |
|qf_AndOrXor_210_values_0.smt2                                |    0.015s | 52.82MiB| sat | 0 |  |  |
|int_check_bvult_bvneg_ltr_inv_g.smt2                         |    0.015s | 52.556MiB| unsat | 0 |  |  |
|qf_AndOrXor_794_values_121.smt2                              |    0.015s | 52.816MiB| unsat | 0 |  |  |
|int_check_bvult_bvurem0_ltr_inv_g.smt2                       |    0.015s | 52.816MiB| unsat | 0 |  |  |
|qf_AndOrXor_1869_values_0.smt2                               |    0.016s | 52.812MiB| unsat | 0 |  |  |
|int_check_bvugt_bvudiv1_rtl.smt2                             |    0.016s | 53.068MiB| unsat | 0 |  |  |
|qf_Select_700_values_123.smt2                                |    0.016s | 52.836MiB| unsat | 0 |  |  |
|int_check_bvsgt_bvshl0_ltr_inv_g.smt2                        |    0.017s | 53.3MiB| sat | 0 |  |  |
|int_check_bvsgt_bvshl0_rtl.smt2                              |    0.017s | 53.328MiB| sat | 0 |  |  |
|qf_Select_727_values_0.smt2                                  |    0.017s | 53.068MiB| unsat | 0 |  |  |
|int_check_bvsgt_bvashr1_ltr_inv_g.smt2                       |    0.017s | 53.58MiB| sat | 0 |  |  |
|int_check_bvule_bvudiv1_ltr_inv_g.smt2                       |    0.017s | 53.068MiB| sat | 0 |  |  |
|int_check_bvsgt_bvadd_rtl.smt2                               |    0.017s | 53.068MiB| sat | 0 |  |  |
|qf_AndOrXor_230_values_0.smt2                                |    0.018s | 53.264MiB| sat | 0 |  |  |
|qf_InstCombineShift497a_values_0.smt2                        |    0.018s | 53.328MiB| sat | 0 |  |  |
|qf_Select_575b_values_0.smt2                                 |    0.018s | 53.324MiB| sat | 0 |  |  |
|qf_AndOrXor_2443_values_0.smt2                               |    0.018s | 53.632MiB| sat | 0 |  |  |
|int_check_bvuge_bvashr1_ltr_inv_g.smt2                       |    0.019s | 53.344MiB| sat | 0 |  |  |
|int_check_bvsgt_bvurem0_rtl.smt2                             |    0.020s | 53.584MiB| sat | 0 |  |  |
|int_check_bvsge_bvurem1_ltr_inv_g.smt2                       |    0.020s | 53.58MiB| sat | 0 |  |  |
|qf_InstCombineShift497b_values_0.smt2                        |    0.023s | 54.368MiB| sat | 0 |  |  |
|int_check_bvsle_bvashr0_rtl.smt2                             |    0.026s | 53.624MiB| sat | 0 |  |  |
|int_check_bvule_bvurem0_ltr_inv_g.smt2                       |    0.027s | 52.552MiB| unsat | 0 |  |  |
|qf_InstCombineShift497c_values_0.smt2                        |    0.027s | 54.58MiB| sat | 0 |  |  |
|int_check_bvsle_bvurem1_ltr_inv_g.smt2                       |    0.028s | 53.416MiB| sat | 0 |  |  |
|int_check_bvugt_bvudiv0_rtl.smt2                             |    0.029s | 53.172MiB| unsat | 0 |  |  |
|int_check_bvugt_bvurem0_rtl.smt2                             |    0.036s | 53.344MiB| unsat | 0 |  |  |
|int_check_eq_bvurem0_rtl.smt2                                |    0.038s | 53.352MiB| unsat | 0 |  |  |
|int_check_bvuge_bvurem0_rtl.smt2                             |    0.042s | 53.068MiB| unsat | 0 |  |  |
|int_check_bvsge_bvudiv1_rtl.smt2                             |    0.044s | 53.58MiB| sat | 0 |  |  |
|int_check_bvslt_bvudiv0_ltr_inv_g.smt2                       |    0.046s | 53.736MiB| sat | 0 |  |  |
|qf_Select_575a_values_0.smt2                                 |    0.047s | 53.916MiB| sat | 0 |  |  |
|int_check_bvuge_bvashr1_rtl.smt2                             |    0.053s | 53.356MiB| sat | 0 |  |  |
|int_check_eq_bvurem0_ltr_inv_g.smt2                          |    0.054s | 53.276MiB| unsat | 0 |  |  |
|int_check_bvsgt_bvlshr0_rtl.smt2                             |    0.054s | 53.612MiB| sat | 0 |  |  |
|int_check_bvsle_bvshl0_ltr_inv_g.smt2                        |    0.055s | 53.676MiB| sat | 0 |  |  |
|int_check_bvsle_bvudiv0_rtl.smt2                             |    0.063s | 53.872MiB| sat | 0 |  |  |
|qf_AndOrXor_290_values_7.smt2                                |    0.076s | 53.856MiB| sat | 0 |  |  |
|int_check_eq_bvudiv0_rtl.smt2                                |    0.078s | 53.344MiB| unsat | 0 |  |  |
|int_check_bvslt_bvlshr0_ltr_inv_g.smt2                       |    0.081s | 53.836MiB| sat | 0 |  |  |
|int_check_eq_bvashr0_rtl.smt2                                |    0.090s | 53.78MiB| sat | 0 |  |  |
|int_check_bvsge_bvneg_ltr_inv_g.smt2                         |    0.095s | 53.584MiB| unsat | 0 |  |  |
|int_check_bvugt_bvashr0_ltr_inv_g.smt2                       |    0.097s | 53.664MiB| sat | 0 |  |  |
|int_check_bvsle_bvashr1_rtl.smt2                             |    0.101s | 53.584MiB| sat | 0 |  |  |
|int_check_bvsge_bvashr1_rtl.smt2                             |    0.110s | 53.712MiB| sat | 0 |  |  |
|int_check_eq_bvudiv1_rtl.smt2                                |    0.121s | 53.856MiB| unsat | 0 |  |  |
|int_check_bvsgt_bvashr0_rtl.smt2                             |    0.122s | 54.096MiB| sat | 0 |  |  |
|int_check_bvsgt_bvurem1_rtl.smt2                             |    0.158s | 53.92MiB| sat | 0 |  |  |
|qf_Select_510_values_0.smt2                                  |    0.172s | 54.352MiB| sat | 0 |  |  |
|int_check_bvsle_bvashr0_ltr_inv_g.smt2                       |    0.177s | 54.072MiB| sat | 0 |  |  |
|int_check_bvslt_bvashr0_rtl.smt2                             |    0.181s | 54.636MiB| sat | 0 |  |  |
|int_check_bvugt_bvashr1_ltr_inv_g.smt2                       |    0.194s | 54.024MiB| sat | 0 |  |  |
|qf_AddSub_1619_values_0.smt2                                 |    0.196s | 53.616MiB| unsat | 0 |  |  |
|3106_1c933134166dbad31f79_40_QF_UFNIA.smt2                   |    0.207s | 58.56MiB| sat | 0 |  |  |
|int_check_bvsge_bvlshr0_rtl.smt2                             |    0.209s | 54.112MiB| sat | 0 |  |  |
|int_check_bvuge_bvshl0_rtl.smt2                              |    0.221s | 54.4MiB| sat | 0 |  |  |
|int_check_bvult_bvashr1_rtl.smt2                             |    0.226s | 53.856MiB| sat | 0 |  |  |
|int_check_bvsgt_bvlshr1_rtl.smt2                             |    0.282s | 54.052MiB| sat | 0 |  |  |
|int_check_bvslt_bvashr1_rtl.smt2                             |    0.288s | 54.42MiB| sat | 0 |  |  |
|int_check_bvslt_bvlshr0_rtl.smt2                             |    0.322s | 54.552MiB| sat | 0 |  |  |
|n99-0002.smt2                                                |    0.347s | 58.784MiB| sat | 0 |  |  |
|qf_AddSub_1165_values_0.smt2                                 |    0.449s | 54.036MiB| unsat | 0 |  |  |
|int_check_bvsle_bvadd_ltr_inv_g.smt2                         |    0.459s | 54.7MiB| unsat | 0 |  |  |
|41958_45c688a4814eb926c254_60_QF_UFNIA.smt2                  |    0.493s | 86.34MiB| sat | 0 |  |  |
|qf_AddSub_1574_values_0.smt2                                 |    0.597s | 54.452MiB| unsat | 0 |  |  |
|int_check_bvugt_bvashr1_rtl.smt2                             |    0.616s | 55.6MiB| sat | 0 |  |  |
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                  |    0.984s | 73.584MiB| sat | 0 |  |  |
|63058_aa742630eef64f949de269382c1f9035_25_UFNIA.smt2         |    1.058s | 60.856MiB| unsat | 0 |  |  |
|83314_a702bf8b823398c9e37a_0_UFNIA.smt2                      |    1.159s | 64.932MiB| sat | 0 |  |  |
|n92-0047.smt2                                                |    1.301s | 127.0MiB| sat | 0 |  |  |
|39657_2866defdd1f2434b69ab_48_QF_UFNIA.smt2                  |    1.535s | 76.892MiB| sat | 0 |  |  |
|n124-0028.smt2                                               |    1.541s | 70.804MiB| sat | 0 |  |  |
|n125-0029.smt2                                               |    1.621s | 65.884MiB| sat | 0 |  |  |
|41958_45c688a4814eb926c254_59_QF_UFNIA.smt2                  |    1.696s | 110.0MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_41_QF_UFNIA.smt2                   |    1.731s | 87.096MiB| sat | 0 |  |  |
|65782_cd31513fdcd15701933b_6_QF_UFNIA.smt2                   |    1.777s | 55.216MiB| sat | 0 |  |  |
|n128-0032.smt2                                               |    1.874s | 120.0MiB| sat | 0 |  |  |
|n86-0040.smt2                                                |    1.914s | 81.368MiB| sat | 0 |  |  |
|n104-0007.smt2                                               |    2.217s | 144.0MiB| unsat | 0 |  |  |
|65782_cd31513fdcd15701933b_8_QF_UFNIA.smt2                   |    2.280s | 61.16MiB| sat | 0 |  |  |
|n108-0012.smt2                                               |    2.322s | 126.0MiB| unsat | 0 |  |  |
|n100-0003.smt2                                               |    2.340s | 81.292MiB| sat | 0 |  |  |
|38347_092cc73601c78e45f4f9_58_QF_UFNIA.smt2                  |    2.369s | 67.484MiB| sat | 0 |  |  |
|n17-0021.smt2                                                |    2.392s | 151.0MiB| unsat | 0 |  |  |
|72658_63104dadde9c6026353f_70_QF_UFNIA.smt2                  |    3.077s | 56.024MiB| sat | 0 |  |  |
|n134-0038.smt2                                               |    3.260s | 61.248MiB| sat | 0 |  |  |
|n110-0014.smt2                                               |    3.967s | 73.804MiB| sat | 0 |  |  |
|n27-0034.smt2                                                |    4.075s | 323.0MiB| unsat | 0 |  |  |
|44289_e5a2e5c780236919ee6a_17_QF_UFNIA.smt2                  |    4.090s | 152.0MiB| sat | 0 |  |  |
|n12-0013.smt2                                                |    4.391s | 125.0MiB| sat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFNIA.smt2      |    4.393s | 168.0MiB| sat | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFNIA.smt2      |    4.592s | 90.596MiB| sat | 0 |  |  |
|72771_f9d228efc97cf1458e38_64_QF_UFNIA.smt2                  |    5.050s | 79.668MiB| sat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFNIA.smt2      |    5.452s | 203.0MiB| sat | 0 |  |  |
|n47-0000.smt2                                                |    5.770s | 78.212MiB| sat | 0 |  |  |
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                  |    6.210s | 67.368MiB| unsat | 0 |  |  |
|n26-0033.smt2                                                |    6.263s | 363.0MiB| unsat | 0 |  |  |
|n90-0045.smt2                                                |    6.288s | 92.016MiB| sat | 0 |  |  |
|n102-0005.smt2                                               |    6.328s | 61.752MiB| sat | 0 |  |  |
|n41-0048.smt2                                                |    6.812s | 110.0MiB| unsat | 0 |  |  |
|n73-0027.smt2                                                |    7.000s | 88.764MiB| unsat | 0 |  |  |
|44289_e5a2e5c780236919ee6a_18_QF_UFNIA.smt2                  |    7.267s | 161.0MiB| sat | 0 |  |  |
|n57-0010.smt2                                                |    7.289s | 121.0MiB| sat | 0 |  |  |
|n5-0005.smt2                                                 |    7.869s | 99.0MiB| sat | 0 |  |  |
|n119-0023.smt2                                               |    8.195s | 108.0MiB| sat | 0 |  |  |
|n107-0011.smt2                                               |    8.375s | 116.0MiB| sat | 0 |  |  |
|n9-0009.smt2                                                 |    8.738s | 109.0MiB| sat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_22_QF_UFNIA.smt2                  |    9.574s | 207.0MiB| sat | 0 |  |  |
|940_590f27b1c3c800d3243e_32_QF_UFNIA.smt2                    |    9.671s | 277.0MiB| sat | 0 |  |  |
|39657_1c7158801cd59dc13f05_46_QF_UFNIA.smt2                  |    9.723s | 120.0MiB| sat | 0 |  |  |
|44289_4066055e0f64d96da11a_14_QF_UFNIA.smt2                  |   10.063s | 185.0MiB| sat | 0 |  |  |
|n61-0015.smt2                                                |   10.810s | 195.0MiB| sat | 0 |  |  |
|63058_55d6bef5390186355f11_26_QF_UFNIA.smt2                  |   10.853s | 272.0MiB| sat | 0 |  |  |
|n34-0041.smt2                                                |   10.929s | 137.0MiB| sat | 0 |  |  |
|qf_muldivrem_152_values_0.smt2                               |   11.463s | 72.928MiB| unsat | 0 |  |  |
|n1-0001.smt2                                                 |   11.513s | 1128.0MiB| unsat | 0 |  |  |
|n132-0036.smt2                                               |   11.920s | 60.032MiB| sat | 0 |  |  |
|n87-0041.smt2                                                |   12.803s | 111.0MiB| sat | 0 |  |  |
|39657_2866defdd1f2434b69ab_47_QF_UFNIA.smt2                  |   15.547s | 73.348MiB| sat | 0 |  |  |
|n38-0045.smt2                                                |   16.659s | 177.0MiB| sat | 0 |  |  |
|n131-0035.smt2                                               |   17.289s | 64.392MiB| sat | 0 |  |  |
|n18-0022.smt2                                                |   17.525s | 135.0MiB| sat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                  |   20.046s | 80.328MiB| unsat | 0 |  |  |
|93493_798593962ee29ad45ac8_52_QF_UFNIA.smt2                  |   21.687s | 279.0MiB| sat | 0 |  |  |
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFNIA.smt2       |   24.317s | 183.0MiB| sat | 0 |  |  |
|940_590f27b1c3c800d3243e_30_QF_UFNIA.smt2                    |   25.360s | 407.0MiB| sat | 0 |  |  |
|n25-0032.smt2                                                |   25.439s | 310.0MiB| sat | 0 |  |  |
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                  |   27.915s | 845.0MiB| unsat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                  |   30.236s | 74.116MiB| unsat | 0 |  |  |
|n106-0009.smt2                                               |   33.975s | 64.616MiB| sat | 0 |  |  |
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFNIA.smt2      |   34.448s | 191.0MiB| sat | 0 |  |  |
|n31-0038.smt2                                                |   34.896s | 85.044MiB| sat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_23_QF_UFNIA.smt2                  |   41.450s | 298.0MiB| sat | 0 |  |  |
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFNIA.smt2      |   41.897s | 215.0MiB| sat | 0 |  |  |
|n65-0019.smt2                                                |   42.361s | 101.0MiB| sat | 0 |  |  |
|n11-0012.smt2                                                |   52.873s | 120.0MiB| sat | 0 |  |  |
|n89-0044.smt2                                                |   56.465s | 142.0MiB| unsat | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFNIA.smt2      |   57.339s | 390.0MiB| sat | 0 |  |  |
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFNIA.smt2      |   57.346s | 237.0MiB| sat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_24_QF_UFNIA.smt2                  |   58.824s | 369.0MiB| sat | 0 |  |  |
|n78-0032.smt2                                                |   59.619s | 524.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_33_QF_UFNIA.smt2                    |   59.647s | 309.0MiB| timeout | 0 |  |  |
|n36-0043.smt2                                                |   59.652s | 515.0MiB| timeout | 0 |  |  |
|qf_muldivrem_239_values_0.smt2                               |   59.728s | 129.0MiB| timeout | 0 |  |  |
|0065.smt2                                                    |   59.778s | 225.0MiB| timeout | 0 |  |  |
|0062.smt2                                                    |   59.784s | 2698.0MiB| timeout | 0 |  |  |
|n103-0006.smt2                                               |   59.794s | 70.608MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2      |   59.801s | 145.0MiB| timeout | 0 |  |  |
|n49-0002.smt2                                                |   59.808s | 90.348MiB| timeout | 0 |  |  |
|n58-0011.smt2                                                |   59.834s | 69.704MiB| timeout | 0 |  |  |
|n75-0029.smt2                                                |   59.836s | 85.628MiB| timeout | 0 |  |  |
|65782_cd31513fdcd15701933b_5_QF_UFNIA.smt2                   |   59.841s | 98.0MiB| timeout | 0 |  |  |
|n44-0051.smt2                                                |   59.851s | 503.0MiB| timeout | 0 |  |  |
|n22-0029.smt2                                                |   59.851s | 310.0MiB| timeout | 0 |  |  |
|n13-0015.smt2                                                |   59.879s | 353.0MiB| timeout | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_34_QF_UFNIA.smt2                  |   59.880s | 67.528MiB| timeout | 0 |  |  |
|n130-0034.smt2                                               |   59.882s | 277.0MiB| timeout | 0 |  |  |
|n123-0027.smt2                                               |   59.882s | 152.0MiB| timeout | 0 |  |  |
|n7-0007.smt2                                                 |   59.884s | 349.0MiB| timeout | 0 |  |  |
|n129-0033.smt2                                               |   59.885s | 117.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_1_UFNIA.smt2                      |   59.887s | 108.0MiB| timeout | 0 |  |  |
|n97-0000.smt2                                                |   59.888s | 109.0MiB| timeout | 0 |  |  |
|n137-0041.smt2                                               |   59.889s | 148.0MiB| timeout | 0 |  |  |
|n46-0053.smt2                                                |   59.892s | 224.0MiB| timeout | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_36_QF_UFNIA.smt2                  |   59.893s | 109.0MiB| timeout | 0 |  |  |
|n3-0003.smt2                                                 |   59.893s | 166.0MiB| timeout | 0 |  |  |
|n83-0037.smt2                                                |   59.898s | 551.0MiB| timeout | 0 |  |  |
|0057.smt2                                                    |   59.902s | 197.0MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_55_QF_UFNIA.smt2                  |   59.903s | 58.668MiB| timeout | 0 |  |  |
|int_check_eq_bvlshr0_rtl.smt2                                |   59.904s | 119.0MiB| timeout | 0 |  |  |
|n126-0030.smt2                                               |   59.905s | 135.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_2_UFNIA.smt2                      |   59.907s | 211.0MiB| timeout | 0 |  |  |
|n98-0001.smt2                                                |   59.907s | 122.0MiB| timeout | 0 |  |  |
|n16-0019.smt2                                                |   59.910s | 234.0MiB| timeout | 0 |  |  |
|n118-0022.smt2                                               |   59.912s | 479.0MiB| timeout | 0 |  |  |
|n64-0018.smt2                                                |   59.913s | 203.0MiB| timeout | 0 |  |  |
|n0-0000.smt2                                                 |   59.915s | 239.0MiB| timeout | 0 |  |  |
|72658_63104dadde9c6026353f_71_QF_UFNIA.smt2                  |   59.917s | 66.944MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFNIA.smt2      |   59.922s | 114.0MiB| timeout | 0 |  |  |
|n80-0034.smt2                                                |   59.925s | 80.74MiB| timeout | 0 |  |  |
|n120-0024.smt2                                               |   59.927s | 157.0MiB| timeout | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                  |   59.935s | 56.8MiB| timeout | 0 |  |  |
|n81-0035.smt2                                                |   59.935s | 366.0MiB| timeout | 0 |  |  |
|44289_4066055e0f64d96da11a_15_QF_UFNIA.smt2                  |   59.935s | 657.0MiB| timeout | 0 |  |  |
|n60-0014.smt2                                                |   59.938s | 347.0MiB| timeout | 0 |  |  |
|n42-0049.smt2                                                |   59.940s | 358.0MiB| timeout | 0 |  |  |
|39657_1c7158801cd59dc13f05_45_QF_UFNIA.smt2                  |   59.940s | 116.0MiB| timeout | 0 |  |  |
|n62-0016.smt2                                                |   59.943s | 316.0MiB| timeout | 0 |  |  |
|n82-0036.smt2                                                |   59.944s | 178.0MiB| timeout | 0 |  |  |
|n115-0019.smt2                                               |   59.944s | 124.0MiB| timeout | 0 |  |  |
|n72-0026.smt2                                                |   59.945s | 530.0MiB| timeout | 0 |  |  |
|n35-0042.smt2                                                |   59.946s | 331.0MiB| timeout | 0 |  |  |
|0058.smt2                                                    |   59.949s | 797.0MiB| timeout | 0 |  |  |
|n136-0040.smt2                                               |   59.950s | 464.0MiB| timeout | 0 |  |  |
|n127-0031.smt2                                               |   59.950s | 102.0MiB| timeout | 0 |  |  |
|n37-0044.smt2                                                |   59.951s | 180.0MiB| timeout | 0 |  |  |
|n55-0008.smt2                                                |   59.951s | 100.0MiB| timeout | 0 |  |  |
|41958_32933c5a1384696720a2_62_QF_UFNIA.smt2                  |   59.953s | 73.26MiB| timeout | 0 |  |  |
|n45-0052.smt2                                                |   59.955s | 1307.0MiB| timeout | 0 |  |  |
|65782_cd31513fdcd15701933b_7_QF_UFNIA.smt2                   |   59.956s | 73.648MiB| timeout | 0 |  |  |
|n66-0020.smt2                                                |   59.957s | 281.0MiB| timeout | 0 |  |  |
|n114-0018.smt2                                               |   59.959s | 198.0MiB| timeout | 0 |  |  |
|qf_muldivrem_290_292_values_0.smt2                           |   59.960s | 125.0MiB| timeout | 0 |  |  |
|n63-0017.smt2                                                |   59.961s | 229.0MiB| timeout | 0 |  |  |
|n2-0002.smt2                                                 |   59.962s | 488.0MiB| timeout | 0 |  |  |
|n30-0037.smt2                                                |   59.962s | 231.0MiB| timeout | 0 |  |  |
|n77-0031.smt2                                                |   59.963s | 634.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_4_UFNIA.smt2                      |   59.963s | 331.0MiB| timeout | 0 |  |  |
|n122-0026.smt2                                               |   59.963s | 155.0MiB| timeout | 0 |  |  |
|n50-0003.smt2                                                |   59.965s | 90.104MiB| timeout | 0 |  |  |
|n51-0004.smt2                                                |   59.965s | 84.984MiB| timeout | 0 |  |  |
|n21-0027.smt2                                                |   59.966s | 228.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_29_QF_UFNIA.smt2                    |   59.967s | 286.0MiB| timeout | 0 |  |  |
|qf_InstCombineShift497d_values_0.smt2                        |   59.967s | 101.0MiB| timeout | 0 |  |  |
|n133-0037.smt2                                               |   59.967s | 60.048MiB| timeout | 0 |  |  |
|41958_32933c5a1384696720a2_61_QF_UFNIA.smt2                  |   59.968s | 77.192MiB| timeout | 0 |  |  |
|n96-0051.smt2                                                |   59.971s | 231.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFNIA.smt2      |   59.971s | 114.0MiB| timeout | 0 |  |  |
|n109-0013.smt2                                               |   59.972s | 262.0MiB| timeout | 0 |  |  |
|n88-0042.smt2                                                |   59.972s | 127.0MiB| timeout | 0 |  |  |
|n20-0026.smt2                                                |   59.975s | 820.0MiB| timeout | 0 |  |  |
|n69-0023.smt2                                                |   59.975s | 149.0MiB| timeout | 0 |  |  |
|n84-0038.smt2                                                |   59.976s | 513.0MiB| timeout | 0 |  |  |
|n74-0028.smt2                                                |   59.976s | 159.0MiB| timeout | 0 |  |  |
|n19-0024.smt2                                                |   59.977s | 194.0MiB| timeout | 0 |  |  |
|n111-0015.smt2                                               |   59.977s | 917.0MiB| timeout | 0 |  |  |
|n6-0006.smt2                                                 |   59.977s | 75.648MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_57_QF_UFNIA.smt2                  |   59.977s | 69.336MiB| timeout | 0 |  |  |
|n68-0022.smt2                                                |   59.977s | 338.0MiB| timeout | 0 |  |  |
|0060.smt2                                                    |   59.978s | 202.0MiB| timeout | 0 |  |  |
|int_check_bvsge_bvlshr0_ltr_inv_g.smt2                       |   59.979s | 54.128MiB| timeout | 0 |  |  |
|n135-0039.smt2                                               |   59.979s | 105.0MiB| timeout | 0 |  |  |
|n43-0050.smt2                                                |   59.979s | 1115.0MiB| timeout | 0 |  |  |
|n105-0008.smt2                                               |   59.980s | 135.0MiB| timeout | 0 |  |  |
|n56-0009.smt2                                                |   59.980s | 105.0MiB| timeout | 0 |  |  |
|n121-0025.smt2                                               |   59.981s | 446.0MiB| timeout | 0 |  |  |
|int_check_ne_bvashr1_ltr_inv_g.smt2                          |   59.982s | 53.788MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_31_QF_UFNIA.smt2                    |   59.983s | 112.0MiB| timeout | 0 |  |  |
|n71-0025.smt2                                                |   59.984s | 1030.0MiB| timeout | 0 |  |  |
|n70-0024.smt2                                                |   59.984s | 1047.0MiB| timeout | 0 |  |  |
|n33-0040.smt2                                                |   59.986s | 609.0MiB| timeout | 0 |  |  |
|0056.smt2                                                    |   59.987s | 326.0MiB| timeout | 0 |  |  |
|n48-0001.smt2                                                |   59.987s | 115.0MiB| timeout | 0 |  |  |
|n54-0007.smt2                                                |   59.988s | 233.0MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_56_QF_UFNIA.smt2                  |   59.988s | 131.0MiB| timeout | 0 |  |  |
|n93-0048.smt2                                                |   59.988s | 153.0MiB| timeout | 0 |  |  |
|n23-0030.smt2                                                |   59.989s | 364.0MiB| timeout | 0 |  |  |
|qf_muldivrem_229_values_0.smt2                               |   59.989s | 120.0MiB| timeout | 0 |  |  |
|n53-0006.smt2                                                |   59.989s | 59.98MiB| timeout | 0 |  |  |
|41958_32933c5a1384696720a2_63_QF_UFNIA.smt2                  |   59.989s | 77.004MiB| timeout | 0 |  |  |
|n28-0035.smt2                                                |   59.991s | 304.0MiB| timeout | 0 |  |  |
|3106_1c933134166dbad31f79_39_QF_UFNIA.smt2                   |   59.994s | 164.0MiB| timeout | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_35_QF_UFNIA.smt2                  |   59.997s | 86.336MiB| timeout | 0 |  |  |
|n101-0004.smt2                                               |   59.997s | 101.0MiB| timeout | 0 |  |  |
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFNIA.smt2      |   59.997s | 457.0MiB| timeout | 0 |  |  |
|0061.smt2                                                    |   59.998s | 199.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFNIA.smt2      |   59.998s | 128.0MiB| timeout | 0 |  |  |
|n10-0010.smt2                                                |   59.998s | 212.0MiB| timeout | 0 |  |  |
|n95-0050.smt2                                                |   59.999s | 843.0MiB| timeout | 0 |  |  |
|n40-0047.smt2                                                |   60.001s | 382.0MiB| timeout | 0 |  |  |
|n91-0046.smt2                                                |   60.001s | 234.0MiB| timeout | 0 |  |  |
|n113-0017.smt2                                               |   60.001s | 189.0MiB| timeout | 0 |  |  |
|int_check_ne_bvashr0_ltr_inv_g.smt2                          |   60.002s | 53.456MiB| timeout | 0 |  |  |
|n85-0039.smt2                                                |   60.002s | 733.0MiB| timeout | 0 |  |  |
|n59-0012.smt2                                                |   60.003s | 150.0MiB| timeout | 0 |  |  |
|n4-0004.smt2                                                 |   60.005s | 108.0MiB| timeout | 0 |  |  |
|n117-0021.smt2                                               |   60.005s | 646.0MiB| timeout | 0 |  |  |
|0064.smt2                                                    |   60.005s | 574.0MiB| timeout | 0 |  |  |
|n32-0039.smt2                                                |   60.005s | 425.0MiB| timeout | 0 |  |  |
|39657_1c7158801cd59dc13f05_44_QF_UFNIA.smt2                  |   60.006s | 125.0MiB| timeout | 0 |  |  |
|0054.smt2                                                    |   60.007s | 1407.0MiB| timeout | 0 |  |  |
|n8-0008.smt2                                                 |   60.010s | 294.0MiB| timeout | 0 |  |  |
|n67-0021.smt2                                                |   60.010s | 582.0MiB| timeout | 0 |  |  |
|38347_525a1ca0331f2bcbf520_54_QF_UFNIA.smt2                  |   60.010s | 356.0MiB| timeout | 0 |  |  |
|n79-0033.smt2                                                |   60.012s | 350.0MiB| timeout | 0 |  |  |
|0067.smt2                                                    |   60.012s | 460.0MiB| timeout | 0 |  |  |
|n24-0031.smt2                                                |   60.018s | 343.0MiB| timeout | 0 |  |  |
|n112-0016.smt2                                               |   60.018s | 804.0MiB| timeout | 0 |  |  |
|n116-0020.smt2                                               |   60.018s | 774.0MiB| timeout | 0 |  |  |
|n94-0049.smt2                                                |   60.019s | 273.0MiB| timeout | 0 |  |  |
|n29-0036.smt2                                                |   60.021s | 1719.0MiB| timeout | 0 |  |  |
|0055.smt2                                                    |   60.022s | 1406.0MiB| timeout | 0 |  |  |
|n52-0005.smt2                                                |   60.025s | 87.308MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_73_QF_UFNIA.smt2                  |   60.030s | 779.0MiB| timeout | 0 |  |  |
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                   |   60.034s | 999.0MiB| timeout | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFNIA.smt2      |   60.034s | 397.0MiB| timeout | 0 |  |  |
|0059.smt2                                                    |   60.040s | 808.0MiB| timeout | 0 |  |  |
|n39-0046.smt2                                                |   60.052s | 1694.0MiB| timeout | 0 |  |  |
|0063.smt2                                                    |   60.054s | 2095.0MiB| timeout | 0 |  |  |
|0066.smt2                                                    |   60.084s | 2943.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_3_UFNIA.smt2                      |   60.347s | 102.0MiB| timeout | 0 |  |  |
|n76-0030.smt2                                                |   62.054s | 1040.0MiB| timeout | 0 |  |  |
