# data

* SAT 104
* UNSAT 40
* TIMEOUT 153
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-clausal-lookahead-60-qfufnia-unknown
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
|int_check_bvule_bvurem1_ltr_inv_g.smt2                       |    0.014s | 52.604MiB| unsat | 0 |  |  |
|int_check_bvult_bvurem1_ltr_inv_g.smt2                       |    0.014s | 52.56MiB| unsat | 0 |  |  |
|int_check_bvule_bvneg_ltr_inv_g.smt2                         |    0.015s | 52.728MiB| unsat | 0 |  |  |
|qf_Select_705_values_0.smt2                                  |    0.015s | 53.048MiB| unsat | 0 |  |  |
|qf_AndOrXor_210_values_0.smt2                                |    0.015s | 52.812MiB| sat | 0 |  |  |
|int_check_bvult_bvneg_ltr_inv_g.smt2                         |    0.015s | 52.772MiB| unsat | 0 |  |  |
|int_check_bvsgt_bvadd_rtl.smt2                               |    0.015s | 53.324MiB| sat | 0 |  |  |
|qf_Select_700_values_123.smt2                                |    0.015s | 52.812MiB| unsat | 0 |  |  |
|int_check_bvult_bvurem0_ltr_inv_g.smt2                       |    0.015s | 52.56MiB| unsat | 0 |  |  |
|int_check_bvsgt_bvshl0_ltr_inv_g.smt2                        |    0.017s | 53.396MiB| sat | 0 |  |  |
|int_check_bvsgt_bvshl0_rtl.smt2                              |    0.017s | 53.332MiB| sat | 0 |  |  |
|qf_Select_727_values_0.smt2                                  |    0.017s | 53.324MiB| unsat | 0 |  |  |
|qf_AndOrXor_1894_values_0.smt2                               |    0.017s | 52.796MiB| unsat | 0 |  |  |
|int_check_bvuge_bvashr1_ltr_inv_g.smt2                       |    0.018s | 53.556MiB| sat | 0 |  |  |
|int_check_bvsgt_bvashr1_ltr_inv_g.smt2                       |    0.018s | 53.584MiB| sat | 0 |  |  |
|int_check_bvule_bvudiv1_ltr_inv_g.smt2                       |    0.018s | 53.3MiB| sat | 0 |  |  |
|qf_AndOrXor_1869_values_0.smt2                               |    0.018s | 52.816MiB| unsat | 0 |  |  |
|int_check_bvsgt_bvurem0_rtl.smt2                             |    0.019s | 53.344MiB| sat | 0 |  |  |
|qf_Select_575b_values_0.smt2                                 |    0.019s | 53.324MiB| sat | 0 |  |  |
|qf_AndOrXor_794_values_121.smt2                              |    0.019s | 52.82MiB| unsat | 0 |  |  |
|qf_AndOrXor_230_values_0.smt2                                |    0.020s | 53.1MiB| sat | 0 |  |  |
|qf_AndOrXor_2443_values_0.smt2                               |    0.020s | 53.536MiB| sat | 0 |  |  |
|qf_InstCombineShift497a_values_0.smt2                        |    0.021s | 53.328MiB| sat | 0 |  |  |
|int_check_bvsge_bvurem1_ltr_inv_g.smt2                       |    0.021s | 53.34MiB| sat | 0 |  |  |
|qf_InstCombineShift497b_values_0.smt2                        |    0.022s | 54.348MiB| sat | 0 |  |  |
|int_check_bvule_bvurem0_ltr_inv_g.smt2                       |    0.023s | 52.536MiB| unsat | 0 |  |  |
|int_check_bvsle_bvashr0_rtl.smt2                             |    0.027s | 53.584MiB| sat | 0 |  |  |
|int_check_bvsle_bvurem1_ltr_inv_g.smt2                       |    0.030s | 53.344MiB| sat | 0 |  |  |
|qf_InstCombineShift497c_values_0.smt2                        |    0.030s | 54.468MiB| sat | 0 |  |  |
|int_check_bvugt_bvurem0_rtl.smt2                             |    0.035s | 53.344MiB| unsat | 0 |  |  |
|int_check_eq_bvurem0_rtl.smt2                                |    0.041s | 53.36MiB| unsat | 0 |  |  |
|int_check_bvuge_bvurem0_rtl.smt2                             |    0.042s | 53.368MiB| unsat | 0 |  |  |
|int_check_bvugt_bvudiv1_rtl.smt2                             |    0.044s | 53.068MiB| unsat | 0 |  |  |
|int_check_bvsge_bvudiv1_rtl.smt2                             |    0.045s | 53.636MiB| sat | 0 |  |  |
|int_check_bvslt_bvudiv0_ltr_inv_g.smt2                       |    0.048s | 53.728MiB| sat | 0 |  |  |
|int_check_eq_bvurem0_ltr_inv_g.smt2                          |    0.050s | 53.02MiB| unsat | 0 |  |  |
|int_check_bvsgt_bvlshr0_rtl.smt2                             |    0.055s | 53.6MiB| sat | 0 |  |  |
|int_check_bvsle_bvshl0_ltr_inv_g.smt2                        |    0.055s | 53.504MiB| sat | 0 |  |  |
|qf_Select_575a_values_0.smt2                                 |    0.057s | 53.976MiB| sat | 0 |  |  |
|int_check_bvuge_bvashr1_rtl.smt2                             |    0.061s | 53.324MiB| sat | 0 |  |  |
|int_check_bvsle_bvudiv0_rtl.smt2                             |    0.062s | 53.868MiB| sat | 0 |  |  |
|qf_AndOrXor_290_values_7.smt2                                |    0.071s | 53.788MiB| sat | 0 |  |  |
|int_check_eq_bvudiv0_rtl.smt2                                |    0.078s | 53.696MiB| unsat | 0 |  |  |
|int_check_bvslt_bvlshr0_ltr_inv_g.smt2                       |    0.084s | 53.856MiB| sat | 0 |  |  |
|int_check_eq_bvashr0_rtl.smt2                                |    0.088s | 53.784MiB| sat | 0 |  |  |
|int_check_bvsge_bvneg_ltr_inv_g.smt2                         |    0.095s | 53.688MiB| unsat | 0 |  |  |
|int_check_bvugt_bvashr0_ltr_inv_g.smt2                       |    0.099s | 53.704MiB| sat | 0 |  |  |
|int_check_bvsge_bvashr1_rtl.smt2                             |    0.103s | 53.684MiB| sat | 0 |  |  |
|int_check_bvsle_bvashr1_rtl.smt2                             |    0.112s | 53.504MiB| sat | 0 |  |  |
|int_check_eq_bvudiv1_rtl.smt2                                |    0.114s | 53.836MiB| unsat | 0 |  |  |
|int_check_bvsgt_bvashr0_rtl.smt2                             |    0.120s | 53.968MiB| sat | 0 |  |  |
|int_check_bvugt_bvudiv0_rtl.smt2                             |    0.124s | 53.156MiB| unsat | 0 |  |  |
|int_check_bvsgt_bvurem1_rtl.smt2                             |    0.145s | 54.02MiB| sat | 0 |  |  |
|qf_Select_510_values_0.smt2                                  |    0.147s | 54.572MiB| sat | 0 |  |  |
|int_check_bvugt_bvashr1_ltr_inv_g.smt2                       |    0.184s | 54.1MiB| sat | 0 |  |  |
|int_check_bvslt_bvashr0_rtl.smt2                             |    0.186s | 54.868MiB| sat | 0 |  |  |
|qf_AddSub_1619_values_0.smt2                                 |    0.189s | 53.576MiB| unsat | 0 |  |  |
|int_check_bvsle_bvashr0_ltr_inv_g.smt2                       |    0.204s | 54.096MiB| sat | 0 |  |  |
|int_check_bvuge_bvshl0_rtl.smt2                              |    0.209s | 54.404MiB| sat | 0 |  |  |
|int_check_bvsge_bvlshr0_rtl.smt2                             |    0.214s | 54.124MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_40_QF_UFNIA.smt2                   |    0.223s | 58.572MiB| sat | 0 |  |  |
|int_check_bvult_bvashr1_rtl.smt2                             |    0.231s | 53.72MiB| sat | 0 |  |  |
|int_check_bvsgt_bvlshr1_rtl.smt2                             |    0.289s | 54.172MiB| sat | 0 |  |  |
|int_check_bvslt_bvashr1_rtl.smt2                             |    0.293s | 54.424MiB| sat | 0 |  |  |
|int_check_bvslt_bvlshr0_rtl.smt2                             |    0.328s | 54.452MiB| sat | 0 |  |  |
|n99-0002.smt2                                                |    0.336s | 58.632MiB| sat | 0 |  |  |
|qf_AddSub_1165_values_0.smt2                                 |    0.409s | 54.208MiB| unsat | 0 |  |  |
|41958_45c688a4814eb926c254_60_QF_UFNIA.smt2                  |    0.449s | 86.348MiB| sat | 0 |  |  |
|int_check_bvsle_bvadd_ltr_inv_g.smt2                         |    0.499s | 54.572MiB| unsat | 0 |  |  |
|qf_AddSub_1574_values_0.smt2                                 |    0.591s | 54.54MiB| unsat | 0 |  |  |
|int_check_bvugt_bvashr1_rtl.smt2                             |    0.663s | 55.788MiB| sat | 0 |  |  |
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                  |    0.932s | 73.38MiB| sat | 0 |  |  |
|63058_aa742630eef64f949de269382c1f9035_25_UFNIA.smt2         |    1.164s | 60.916MiB| unsat | 0 |  |  |
|83314_a702bf8b823398c9e37a_0_UFNIA.smt2                      |    1.205s | 64.904MiB| sat | 0 |  |  |
|n92-0047.smt2                                                |    1.233s | 127.0MiB| sat | 0 |  |  |
|39657_2866defdd1f2434b69ab_48_QF_UFNIA.smt2                  |    1.513s | 76.888MiB| sat | 0 |  |  |
|n124-0028.smt2                                               |    1.648s | 70.808MiB| sat | 0 |  |  |
|41958_45c688a4814eb926c254_59_QF_UFNIA.smt2                  |    1.673s | 110.0MiB| sat | 0 |  |  |
|65782_cd31513fdcd15701933b_6_QF_UFNIA.smt2                   |    1.689s | 55.204MiB| sat | 0 |  |  |
|n125-0029.smt2                                               |    1.718s | 65.812MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_41_QF_UFNIA.smt2                   |    1.743s | 86.948MiB| sat | 0 |  |  |
|n128-0032.smt2                                               |    1.848s | 120.0MiB| sat | 0 |  |  |
|n86-0040.smt2                                                |    2.015s | 81.312MiB| sat | 0 |  |  |
|n104-0007.smt2                                               |    2.170s | 145.0MiB| unsat | 0 |  |  |
|65782_cd31513fdcd15701933b_8_QF_UFNIA.smt2                   |    2.197s | 60.968MiB| sat | 0 |  |  |
|n108-0012.smt2                                               |    2.275s | 126.0MiB| unsat | 0 |  |  |
|n100-0003.smt2                                               |    2.356s | 81.304MiB| sat | 0 |  |  |
|38347_092cc73601c78e45f4f9_58_QF_UFNIA.smt2                  |    2.424s | 67.488MiB| sat | 0 |  |  |
|n17-0021.smt2                                                |    2.472s | 151.0MiB| unsat | 0 |  |  |
|72658_63104dadde9c6026353f_70_QF_UFNIA.smt2                  |    3.097s | 56.024MiB| sat | 0 |  |  |
|n134-0038.smt2                                               |    3.266s | 61.26MiB| sat | 0 |  |  |
|n27-0034.smt2                                                |    4.292s | 322.0MiB| unsat | 0 |  |  |
|n110-0014.smt2                                               |    4.310s | 73.748MiB| sat | 0 |  |  |
|44289_e5a2e5c780236919ee6a_17_QF_UFNIA.smt2                  |    4.321s | 152.0MiB| sat | 0 |  |  |
|n12-0013.smt2                                                |    4.466s | 125.0MiB| sat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFNIA.smt2      |    4.668s | 168.0MiB| sat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFNIA.smt2      |    5.294s | 203.0MiB| sat | 0 |  |  |
|72771_f9d228efc97cf1458e38_64_QF_UFNIA.smt2                  |    5.386s | 79.648MiB| sat | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFNIA.smt2      |    5.549s | 90.608MiB| sat | 0 |  |  |
|n26-0033.smt2                                                |    5.972s | 362.0MiB| unsat | 0 |  |  |
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                  |    5.977s | 67.228MiB| unsat | 0 |  |  |
|n47-0000.smt2                                                |    5.980s | 77.984MiB| sat | 0 |  |  |
|n102-0005.smt2                                               |    6.156s | 61.756MiB| sat | 0 |  |  |
|n90-0045.smt2                                                |    6.196s | 91.984MiB| sat | 0 |  |  |
|n41-0048.smt2                                                |    6.561s | 110.0MiB| unsat | 0 |  |  |
|n73-0027.smt2                                                |    7.256s | 88.684MiB| unsat | 0 |  |  |
|n57-0010.smt2                                                |    7.434s | 121.0MiB| sat | 0 |  |  |
|44289_e5a2e5c780236919ee6a_18_QF_UFNIA.smt2                  |    7.960s | 161.0MiB| sat | 0 |  |  |
|n119-0023.smt2                                               |    8.030s | 108.0MiB| sat | 0 |  |  |
|n107-0011.smt2                                               |    8.360s | 116.0MiB| sat | 0 |  |  |
|n9-0009.smt2                                                 |    9.276s | 109.0MiB| sat | 0 |  |  |
|940_590f27b1c3c800d3243e_32_QF_UFNIA.smt2                    |    9.574s | 277.0MiB| sat | 0 |  |  |
|39657_1c7158801cd59dc13f05_46_QF_UFNIA.smt2                  |    9.828s | 120.0MiB| sat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_22_QF_UFNIA.smt2                  |   10.452s | 208.0MiB| sat | 0 |  |  |
|n5-0005.smt2                                                 |   10.560s | 99.0MiB| sat | 0 |  |  |
|44289_4066055e0f64d96da11a_14_QF_UFNIA.smt2                  |   10.580s | 184.0MiB| sat | 0 |  |  |
|63058_55d6bef5390186355f11_26_QF_UFNIA.smt2                  |   10.784s | 272.0MiB| sat | 0 |  |  |
|n61-0015.smt2                                                |   10.901s | 195.0MiB| sat | 0 |  |  |
|n132-0036.smt2                                               |   11.228s | 60.052MiB| sat | 0 |  |  |
|n34-0041.smt2                                                |   11.377s | 136.0MiB| sat | 0 |  |  |
|n1-0001.smt2                                                 |   11.494s | 1129.0MiB| unsat | 0 |  |  |
|qf_muldivrem_152_values_0.smt2                               |   11.895s | 73.004MiB| unsat | 0 |  |  |
|n87-0041.smt2                                                |   12.912s | 111.0MiB| sat | 0 |  |  |
|39657_2866defdd1f2434b69ab_47_QF_UFNIA.smt2                  |   15.131s | 73.348MiB| sat | 0 |  |  |
|n18-0022.smt2                                                |   16.173s | 135.0MiB| sat | 0 |  |  |
|n38-0045.smt2                                                |   16.388s | 177.0MiB| sat | 0 |  |  |
|n131-0035.smt2                                               |   18.168s | 64.412MiB| sat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                  |   20.427s | 80.56MiB| unsat | 0 |  |  |
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                  |   23.017s | 843.0MiB| unsat | 0 |  |  |
|93493_798593962ee29ad45ac8_52_QF_UFNIA.smt2                  |   23.139s | 278.0MiB| sat | 0 |  |  |
|n25-0032.smt2                                                |   23.756s | 311.0MiB| sat | 0 |  |  |
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFNIA.smt2       |   24.677s | 183.0MiB| sat | 0 |  |  |
|940_590f27b1c3c800d3243e_30_QF_UFNIA.smt2                    |   25.820s | 408.0MiB| sat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                  |   29.742s | 74.124MiB| unsat | 0 |  |  |
|n106-0009.smt2                                               |   33.267s | 64.68MiB| sat | 0 |  |  |
|n31-0038.smt2                                                |   33.700s | 84.868MiB| sat | 0 |  |  |
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFNIA.smt2      |   36.644s | 192.0MiB| sat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_23_QF_UFNIA.smt2                  |   40.722s | 299.0MiB| sat | 0 |  |  |
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFNIA.smt2      |   41.444s | 214.0MiB| sat | 0 |  |  |
|n65-0019.smt2                                                |   44.051s | 101.0MiB| sat | 0 |  |  |
|n11-0012.smt2                                                |   52.300s | 120.0MiB| sat | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFNIA.smt2      |   54.149s | 391.0MiB| sat | 0 |  |  |
|n89-0044.smt2                                                |   55.065s | 142.0MiB| unsat | 0 |  |  |
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFNIA.smt2      |   56.961s | 237.0MiB| sat | 0 |  |  |
|n93-0048.smt2                                                |   58.707s | 154.0MiB| timeout | 0 |  |  |
|n97-0000.smt2                                                |   59.425s | 110.0MiB| timeout | 0 |  |  |
|n105-0008.smt2                                               |   59.641s | 137.0MiB| timeout | 0 |  |  |
|n122-0026.smt2                                               |   59.759s | 154.0MiB| timeout | 0 |  |  |
|n137-0041.smt2                                               |   59.787s | 148.0MiB| timeout | 0 |  |  |
|n91-0046.smt2                                                |   59.825s | 226.0MiB| timeout | 0 |  |  |
|n63-0017.smt2                                                |   59.849s | 227.0MiB| timeout | 0 |  |  |
|n0-0000.smt2                                                 |   59.853s | 236.0MiB| timeout | 0 |  |  |
|n123-0027.smt2                                               |   59.856s | 157.0MiB| timeout | 0 |  |  |
|n127-0031.smt2                                               |   59.856s | 102.0MiB| timeout | 0 |  |  |
|n78-0032.smt2                                                |   59.865s | 521.0MiB| timeout | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_36_QF_UFNIA.smt2                  |   59.872s | 108.0MiB| timeout | 0 |  |  |
|n7-0007.smt2                                                 |   59.877s | 348.0MiB| timeout | 0 |  |  |
|n3-0003.smt2                                                 |   59.878s | 164.0MiB| timeout | 0 |  |  |
|0066.smt2                                                    |   59.880s | 2941.0MiB| timeout | 0 |  |  |
|41958_32933c5a1384696720a2_61_QF_UFNIA.smt2                  |   59.881s | 77.228MiB| timeout | 0 |  |  |
|n40-0047.smt2                                                |   59.883s | 382.0MiB| timeout | 0 |  |  |
|n77-0031.smt2                                                |   59.884s | 633.0MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_57_QF_UFNIA.smt2                  |   59.888s | 69.112MiB| timeout | 0 |  |  |
|n68-0022.smt2                                                |   59.890s | 335.0MiB| timeout | 0 |  |  |
|int_check_ne_bvashr0_ltr_inv_g.smt2                          |   59.902s | 53.456MiB| timeout | 0 |  |  |
|n10-0010.smt2                                                |   59.905s | 211.0MiB| timeout | 0 |  |  |
|n76-0030.smt2                                                |   59.912s | 1047.0MiB| timeout | 0 |  |  |
|n75-0029.smt2                                                |   59.926s | 85.888MiB| timeout | 0 |  |  |
|n114-0018.smt2                                               |   59.926s | 198.0MiB| timeout | 0 |  |  |
|n28-0035.smt2                                                |   59.926s | 302.0MiB| timeout | 0 |  |  |
|qf_muldivrem_239_values_0.smt2                               |   59.926s | 129.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFNIA.smt2      |   59.927s | 112.0MiB| timeout | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_34_QF_UFNIA.smt2                  |   59.932s | 67.972MiB| timeout | 0 |  |  |
|n67-0021.smt2                                                |   59.933s | 585.0MiB| timeout | 0 |  |  |
|n46-0053.smt2                                                |   59.936s | 221.0MiB| timeout | 0 |  |  |
|38347_525a1ca0331f2bcbf520_54_QF_UFNIA.smt2                  |   59.936s | 356.0MiB| timeout | 0 |  |  |
|n121-0025.smt2                                               |   59.937s | 447.0MiB| timeout | 0 |  |  |
|n80-0034.smt2                                                |   59.937s | 80.664MiB| timeout | 0 |  |  |
|n19-0024.smt2                                                |   59.940s | 194.0MiB| timeout | 0 |  |  |
|n94-0049.smt2                                                |   59.940s | 273.0MiB| timeout | 0 |  |  |
|qf_muldivrem_229_values_0.smt2                               |   59.943s | 114.0MiB| timeout | 0 |  |  |
|0054.smt2                                                    |   59.944s | 1405.0MiB| timeout | 0 |  |  |
|n23-0030.smt2                                                |   59.945s | 356.0MiB| timeout | 0 |  |  |
|qf_InstCombineShift497d_values_0.smt2                        |   59.945s | 110.0MiB| timeout | 0 |  |  |
|int_check_eq_bvlshr0_rtl.smt2                                |   59.945s | 118.0MiB| timeout | 0 |  |  |
|72658_63104dadde9c6026353f_71_QF_UFNIA.smt2                  |   59.945s | 67.18MiB| timeout | 0 |  |  |
|n6-0006.smt2                                                 |   59.946s | 75.672MiB| timeout | 0 |  |  |
|n111-0015.smt2                                               |   59.947s | 915.0MiB| timeout | 0 |  |  |
|n55-0008.smt2                                                |   59.947s | 101.0MiB| timeout | 0 |  |  |
|n52-0005.smt2                                                |   59.948s | 87.748MiB| timeout | 0 |  |  |
|n39-0046.smt2                                                |   59.950s | 1710.0MiB| timeout | 0 |  |  |
|n126-0030.smt2                                               |   59.951s | 135.0MiB| timeout | 0 |  |  |
|41958_32933c5a1384696720a2_63_QF_UFNIA.smt2                  |   59.951s | 78.26MiB| timeout | 0 |  |  |
|n30-0037.smt2                                                |   59.951s | 233.0MiB| timeout | 0 |  |  |
|n56-0009.smt2                                                |   59.954s | 104.0MiB| timeout | 0 |  |  |
|n116-0020.smt2                                               |   59.955s | 772.0MiB| timeout | 0 |  |  |
|n24-0031.smt2                                                |   59.956s | 343.0MiB| timeout | 0 |  |  |
|qf_muldivrem_290_292_values_0.smt2                           |   59.958s | 125.0MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_55_QF_UFNIA.smt2                  |   59.959s | 58.664MiB| timeout | 0 |  |  |
|3106_1c933134166dbad31f79_39_QF_UFNIA.smt2                   |   59.959s | 164.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_1_UFNIA.smt2                      |   59.960s | 107.0MiB| timeout | 0 |  |  |
|n51-0004.smt2                                                |   59.961s | 85.204MiB| timeout | 0 |  |  |
|n136-0040.smt2                                               |   59.962s | 462.0MiB| timeout | 0 |  |  |
|n82-0036.smt2                                                |   59.962s | 176.0MiB| timeout | 0 |  |  |
|0065.smt2                                                    |   59.964s | 226.0MiB| timeout | 0 |  |  |
|n85-0039.smt2                                                |   59.964s | 728.0MiB| timeout | 0 |  |  |
|0057.smt2                                                    |   59.964s | 192.0MiB| timeout | 0 |  |  |
|n84-0038.smt2                                                |   59.966s | 516.0MiB| timeout | 0 |  |  |
|n113-0017.smt2                                               |   59.966s | 189.0MiB| timeout | 0 |  |  |
|0060.smt2                                                    |   59.968s | 194.0MiB| timeout | 0 |  |  |
|n95-0050.smt2                                                |   59.968s | 828.0MiB| timeout | 0 |  |  |
|int_check_bvsge_bvlshr0_ltr_inv_g.smt2                       |   59.970s | 54.168MiB| timeout | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                  |   59.970s | 56.808MiB| timeout | 0 |  |  |
|n44-0051.smt2                                                |   59.970s | 502.0MiB| timeout | 0 |  |  |
|n21-0027.smt2                                                |   59.971s | 228.0MiB| timeout | 0 |  |  |
|n50-0003.smt2                                                |   59.972s | 89.816MiB| timeout | 0 |  |  |
|n42-0049.smt2                                                |   59.973s | 348.0MiB| timeout | 0 |  |  |
|n35-0042.smt2                                                |   59.974s | 329.0MiB| timeout | 0 |  |  |
|n135-0039.smt2                                               |   59.975s | 107.0MiB| timeout | 0 |  |  |
|n115-0019.smt2                                               |   59.975s | 120.0MiB| timeout | 0 |  |  |
|n49-0002.smt2                                                |   59.976s | 90.348MiB| timeout | 0 |  |  |
|n4-0004.smt2                                                 |   59.977s | 108.0MiB| timeout | 0 |  |  |
|n81-0035.smt2                                                |   59.977s | 366.0MiB| timeout | 0 |  |  |
|n29-0036.smt2                                                |   59.979s | 1720.0MiB| timeout | 0 |  |  |
|n2-0002.smt2                                                 |   59.979s | 487.0MiB| timeout | 0 |  |  |
|0058.smt2                                                    |   59.981s | 798.0MiB| timeout | 0 |  |  |
|n58-0011.smt2                                                |   59.981s | 69.648MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_3_UFNIA.smt2                      |   59.981s | 102.0MiB| timeout | 0 |  |  |
|39657_1c7158801cd59dc13f05_45_QF_UFNIA.smt2                  |   59.983s | 116.0MiB| timeout | 0 |  |  |
|41958_32933c5a1384696720a2_62_QF_UFNIA.smt2                  |   59.985s | 73.78MiB| timeout | 0 |  |  |
|n13-0015.smt2                                                |   59.985s | 347.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_4_UFNIA.smt2                      |   59.985s | 316.0MiB| timeout | 0 |  |  |
|65782_cd31513fdcd15701933b_7_QF_UFNIA.smt2                   |   59.986s | 74.248MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFNIA.smt2      |   59.986s | 129.0MiB| timeout | 0 |  |  |
|n130-0034.smt2                                               |   59.987s | 277.0MiB| timeout | 0 |  |  |
|n120-0024.smt2                                               |   59.987s | 157.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2      |   59.987s | 145.0MiB| timeout | 0 |  |  |
|0055.smt2                                                    |   59.987s | 1409.0MiB| timeout | 0 |  |  |
|n62-0016.smt2                                                |   59.988s | 317.0MiB| timeout | 0 |  |  |
|n37-0044.smt2                                                |   59.988s | 187.0MiB| timeout | 0 |  |  |
|n101-0004.smt2                                               |   59.988s | 101.0MiB| timeout | 0 |  |  |
|44289_4066055e0f64d96da11a_15_QF_UFNIA.smt2                  |   59.988s | 655.0MiB| timeout | 0 |  |  |
|n66-0020.smt2                                                |   59.989s | 281.0MiB| timeout | 0 |  |  |
|n60-0014.smt2                                                |   59.990s | 348.0MiB| timeout | 0 |  |  |
|n88-0042.smt2                                                |   59.991s | 127.0MiB| timeout | 0 |  |  |
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFNIA.smt2      |   59.991s | 459.0MiB| timeout | 0 |  |  |
|n36-0043.smt2                                                |   59.992s | 515.0MiB| timeout | 0 |  |  |
|65782_cd31513fdcd15701933b_5_QF_UFNIA.smt2                   |   59.993s | 98.0MiB| timeout | 0 |  |  |
|n133-0037.smt2                                               |   59.993s | 60.04MiB| timeout | 0 |  |  |
|n48-0001.smt2                                                |   59.993s | 116.0MiB| timeout | 0 |  |  |
|n16-0019.smt2                                                |   59.994s | 234.0MiB| timeout | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_35_QF_UFNIA.smt2                  |   59.994s | 86.156MiB| timeout | 0 |  |  |
|0056.smt2                                                    |   59.994s | 324.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_31_QF_UFNIA.smt2                    |   59.995s | 113.0MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_56_QF_UFNIA.smt2                  |   59.995s | 130.0MiB| timeout | 0 |  |  |
|n54-0007.smt2                                                |   59.996s | 238.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_29_QF_UFNIA.smt2                    |   59.996s | 286.0MiB| timeout | 0 |  |  |
|n129-0033.smt2                                               |   59.997s | 117.0MiB| timeout | 0 |  |  |
|0061.smt2                                                    |   59.998s | 191.0MiB| timeout | 0 |  |  |
|n22-0029.smt2                                                |   59.998s | 310.0MiB| timeout | 0 |  |  |
|n98-0001.smt2                                                |   59.998s | 122.0MiB| timeout | 0 |  |  |
|int_check_ne_bvashr1_ltr_inv_g.smt2                          |   59.999s | 53.796MiB| timeout | 0 |  |  |
|n59-0012.smt2                                                |   59.999s | 148.0MiB| timeout | 0 |  |  |
|n118-0022.smt2                                               |   60.000s | 483.0MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_73_QF_UFNIA.smt2                  |   60.000s | 779.0MiB| timeout | 0 |  |  |
|39657_1c7158801cd59dc13f05_44_QF_UFNIA.smt2                  |   60.001s | 125.0MiB| timeout | 0 |  |  |
|n64-0018.smt2                                                |   60.001s | 205.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFNIA.smt2      |   60.002s | 114.0MiB| timeout | 0 |  |  |
|n69-0023.smt2                                                |   60.002s | 147.0MiB| timeout | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_24_QF_UFNIA.smt2                  |   60.003s | 371.0MiB| timeout | 0 |  |  |
|0067.smt2                                                    |   60.003s | 461.0MiB| timeout | 0 |  |  |
|n8-0008.smt2                                                 |   60.004s | 294.0MiB| timeout | 0 |  |  |
|n109-0013.smt2                                               |   60.004s | 260.0MiB| timeout | 0 |  |  |
|n103-0006.smt2                                               |   60.006s | 70.324MiB| timeout | 0 |  |  |
|n96-0051.smt2                                                |   60.007s | 234.0MiB| timeout | 0 |  |  |
|n83-0037.smt2                                                |   60.007s | 549.0MiB| timeout | 0 |  |  |
|n71-0025.smt2                                                |   60.008s | 1030.0MiB| timeout | 0 |  |  |
|n72-0026.smt2                                                |   60.014s | 528.0MiB| timeout | 0 |  |  |
|n53-0006.smt2                                                |   60.015s | 59.988MiB| timeout | 0 |  |  |
|0064.smt2                                                    |   60.017s | 573.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_2_UFNIA.smt2                      |   60.018s | 211.0MiB| timeout | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFNIA.smt2      |   60.022s | 397.0MiB| timeout | 0 |  |  |
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                   |   60.023s | 1002.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_33_QF_UFNIA.smt2                    |   60.023s | 309.0MiB| timeout | 0 |  |  |
|0059.smt2                                                    |   60.025s | 808.0MiB| timeout | 0 |  |  |
|n20-0026.smt2                                                |   60.028s | 822.0MiB| timeout | 0 |  |  |
|n70-0024.smt2                                                |   60.028s | 1045.0MiB| timeout | 0 |  |  |
|n45-0052.smt2                                                |   60.030s | 1308.0MiB| timeout | 0 |  |  |
|n79-0033.smt2                                                |   60.030s | 343.0MiB| timeout | 0 |  |  |
|n117-0021.smt2                                               |   60.031s | 645.0MiB| timeout | 0 |  |  |
|n33-0040.smt2                                                |   60.031s | 598.0MiB| timeout | 0 |  |  |
|0062.smt2                                                    |   60.035s | 2697.0MiB| timeout | 0 |  |  |
|n32-0039.smt2                                                |   60.036s | 427.0MiB| timeout | 0 |  |  |
|n112-0016.smt2                                               |   60.039s | 814.0MiB| timeout | 0 |  |  |
|n74-0028.smt2                                                |   60.040s | 156.0MiB| timeout | 0 |  |  |
|n43-0050.smt2                                                |   60.051s | 1112.0MiB| timeout | 0 |  |  |
|0063.smt2                                                    |   60.065s | 2090.0MiB| timeout | 0 |  |  |
