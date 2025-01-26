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
|int_check_bvule_bvneg_ltr_inv_g.smt2                         |    0.013s | 52.576MiB| unsat | 0 |  |  |
|int_check_bvult_bvneg_ltr_inv_g.smt2                         |    0.014s | 52.48MiB| unsat | 0 |  |  |
|int_check_bvule_bvurem1_ltr_inv_g.smt2                       |    0.015s | 52.56MiB| unsat | 0 |  |  |
|qf_AndOrXor_1869_values_0.smt2                               |    0.015s | 52.812MiB| unsat | 0 |  |  |
|int_check_bvult_bvurem1_ltr_inv_g.smt2                       |    0.015s | 52.812MiB| unsat | 0 |  |  |
|qf_Select_700_values_123.smt2                                |    0.015s | 52.812MiB| unsat | 0 |  |  |
|int_check_bvult_bvurem0_ltr_inv_g.smt2                       |    0.015s | 52.56MiB| unsat | 0 |  |  |
|int_check_bvsgt_bvshl0_rtl.smt2                              |    0.016s | 53.124MiB| sat | 0 |  |  |
|qf_Select_705_values_0.smt2                                  |    0.016s | 53.072MiB| unsat | 0 |  |  |
|qf_AndOrXor_1894_values_0.smt2                               |    0.016s | 52.836MiB| unsat | 0 |  |  |
|qf_AndOrXor_210_values_0.smt2                                |    0.016s | 52.82MiB| sat | 0 |  |  |
|int_check_bvsgt_bvadd_rtl.smt2                               |    0.016s | 53.072MiB| sat | 0 |  |  |
|qf_AndOrXor_230_values_0.smt2                                |    0.017s | 53.204MiB| sat | 0 |  |  |
|qf_Select_575b_values_0.smt2                                 |    0.017s | 53.324MiB| sat | 0 |  |  |
|int_check_bvugt_bvudiv1_rtl.smt2                             |    0.017s | 53.068MiB| unsat | 0 |  |  |
|int_check_bvuge_bvashr1_ltr_inv_g.smt2                       |    0.018s | 53.58MiB| sat | 0 |  |  |
|qf_Select_727_values_0.smt2                                  |    0.018s | 53.088MiB| unsat | 0 |  |  |
|int_check_bvule_bvudiv1_ltr_inv_g.smt2                       |    0.018s | 53.072MiB| sat | 0 |  |  |
|qf_AndOrXor_794_values_121.smt2                              |    0.018s | 52.752MiB| unsat | 0 |  |  |
|int_check_bvsgt_bvurem0_rtl.smt2                             |    0.019s | 53.556MiB| sat | 0 |  |  |
|int_check_bvsgt_bvashr1_ltr_inv_g.smt2                       |    0.019s | 53.584MiB| sat | 0 |  |  |
|qf_InstCombineShift497a_values_0.smt2                        |    0.020s | 53.324MiB| sat | 0 |  |  |
|qf_AndOrXor_2443_values_0.smt2                               |    0.020s | 53.648MiB| sat | 0 |  |  |
|qf_InstCombineShift497b_values_0.smt2                        |    0.023s | 54.368MiB| sat | 0 |  |  |
|int_check_bvugt_bvudiv0_rtl.smt2                             |    0.025s | 53.132MiB| unsat | 0 |  |  |
|qf_InstCombineShift497c_values_0.smt2                        |    0.025s | 54.292MiB| sat | 0 |  |  |
|int_check_bvsge_bvurem1_ltr_inv_g.smt2                       |    0.026s | 53.34MiB| sat | 0 |  |  |
|int_check_bvsle_bvurem1_ltr_inv_g.smt2                       |    0.028s | 53.556MiB| sat | 0 |  |  |
|int_check_bvsle_bvashr0_rtl.smt2                             |    0.028s | 53.588MiB| sat | 0 |  |  |
|int_check_bvule_bvurem0_ltr_inv_g.smt2                       |    0.032s | 52.548MiB| unsat | 0 |  |  |
|int_check_bvuge_bvurem0_rtl.smt2                             |    0.037s | 53.328MiB| unsat | 0 |  |  |
|int_check_bvugt_bvurem0_rtl.smt2                             |    0.037s | 53.324MiB| unsat | 0 |  |  |
|int_check_eq_bvurem0_rtl.smt2                                |    0.038s | 53.256MiB| unsat | 0 |  |  |
|int_check_bvsge_bvudiv1_rtl.smt2                             |    0.043s | 53.58MiB| sat | 0 |  |  |
|int_check_bvslt_bvudiv0_ltr_inv_g.smt2                       |    0.050s | 53.808MiB| sat | 0 |  |  |
|qf_Select_575a_values_0.smt2                                 |    0.050s | 54.46MiB| sat | 0 |  |  |
|int_check_bvsle_bvshl0_ltr_inv_g.smt2                        |    0.052s | 53.58MiB| sat | 0 |  |  |
|int_check_eq_bvurem0_ltr_inv_g.smt2                          |    0.053s | 53.16MiB| unsat | 0 |  |  |
|int_check_bvsgt_bvlshr0_rtl.smt2                             |    0.059s | 53.816MiB| sat | 0 |  |  |
|int_check_bvsgt_bvshl0_ltr_inv_g.smt2                        |    0.060s | 53.232MiB| sat | 0 |  |  |
|int_check_bvuge_bvashr1_rtl.smt2                             |    0.063s | 53.324MiB| sat | 0 |  |  |
|int_check_bvsle_bvudiv0_rtl.smt2                             |    0.067s | 53.868MiB| sat | 0 |  |  |
|int_check_eq_bvudiv0_rtl.smt2                                |    0.074s | 53.348MiB| unsat | 0 |  |  |
|qf_AndOrXor_290_values_7.smt2                                |    0.076s | 53.74MiB| sat | 0 |  |  |
|int_check_bvslt_bvlshr0_ltr_inv_g.smt2                       |    0.082s | 53.76MiB| sat | 0 |  |  |
|int_check_bvsge_bvneg_ltr_inv_g.smt2                         |    0.093s | 53.584MiB| unsat | 0 |  |  |
|int_check_bvsle_bvashr1_rtl.smt2                             |    0.095s | 53.592MiB| sat | 0 |  |  |
|int_check_eq_bvashr0_rtl.smt2                                |    0.097s | 53.784MiB| sat | 0 |  |  |
|int_check_bvugt_bvashr0_ltr_inv_g.smt2                       |    0.100s | 53.712MiB| sat | 0 |  |  |
|int_check_bvsge_bvashr1_rtl.smt2                             |    0.104s | 53.56MiB| sat | 0 |  |  |
|int_check_bvsgt_bvashr0_rtl.smt2                             |    0.121s | 54.096MiB| sat | 0 |  |  |
|int_check_eq_bvudiv1_rtl.smt2                                |    0.123s | 53.836MiB| unsat | 0 |  |  |
|int_check_bvsgt_bvurem1_rtl.smt2                             |    0.146s | 53.916MiB| sat | 0 |  |  |
|qf_Select_510_values_0.smt2                                  |    0.150s | 54.352MiB| sat | 0 |  |  |
|int_check_bvsle_bvashr0_ltr_inv_g.smt2                       |    0.175s | 54.092MiB| sat | 0 |  |  |
|int_check_bvslt_bvashr0_rtl.smt2                             |    0.183s | 54.608MiB| sat | 0 |  |  |
|qf_AddSub_1619_values_0.smt2                                 |    0.192s | 53.576MiB| unsat | 0 |  |  |
|int_check_bvsge_bvlshr0_rtl.smt2                             |    0.202s | 54.096MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_40_QF_UFNIA.smt2                   |    0.205s | 58.556MiB| sat | 0 |  |  |
|int_check_bvugt_bvashr1_ltr_inv_g.smt2                       |    0.222s | 54.084MiB| sat | 0 |  |  |
|int_check_bvuge_bvshl0_rtl.smt2                              |    0.223s | 54.276MiB| sat | 0 |  |  |
|int_check_bvult_bvashr1_rtl.smt2                             |    0.228s | 53.944MiB| sat | 0 |  |  |
|int_check_bvsgt_bvlshr1_rtl.smt2                             |    0.293s | 54.092MiB| sat | 0 |  |  |
|int_check_bvslt_bvashr1_rtl.smt2                             |    0.295s | 54.444MiB| sat | 0 |  |  |
|int_check_bvslt_bvlshr0_rtl.smt2                             |    0.301s | 54.488MiB| sat | 0 |  |  |
|n99-0002.smt2                                                |    0.344s | 58.708MiB| sat | 0 |  |  |
|int_check_bvsle_bvadd_ltr_inv_g.smt2                         |    0.452s | 55.0MiB| unsat | 0 |  |  |
|qf_AddSub_1165_values_0.smt2                                 |    0.469s | 54.128MiB| unsat | 0 |  |  |
|41958_45c688a4814eb926c254_60_QF_UFNIA.smt2                  |    0.510s | 86.38MiB| sat | 0 |  |  |
|int_check_bvugt_bvashr1_rtl.smt2                             |    0.631s | 55.84MiB| sat | 0 |  |  |
|qf_AddSub_1574_values_0.smt2                                 |    0.637s | 54.528MiB| unsat | 0 |  |  |
|63058_aa742630eef64f949de269382c1f9035_25_UFNIA.smt2         |    1.036s | 60.788MiB| unsat | 0 |  |  |
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                  |    1.056s | 73.168MiB| sat | 0 |  |  |
|83314_a702bf8b823398c9e37a_0_UFNIA.smt2                      |    1.196s | 64.936MiB| sat | 0 |  |  |
|n92-0047.smt2                                                |    1.265s | 127.0MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_41_QF_UFNIA.smt2                   |    1.523s | 86.88MiB| sat | 0 |  |  |
|41958_45c688a4814eb926c254_59_QF_UFNIA.smt2                  |    1.570s | 110.0MiB| sat | 0 |  |  |
|39657_2866defdd1f2434b69ab_48_QF_UFNIA.smt2                  |    1.571s | 76.68MiB| sat | 0 |  |  |
|65782_cd31513fdcd15701933b_6_QF_UFNIA.smt2                   |    1.656s | 55.212MiB| sat | 0 |  |  |
|n125-0029.smt2                                               |    1.757s | 65.868MiB| sat | 0 |  |  |
|n124-0028.smt2                                               |    1.833s | 70.856MiB| sat | 0 |  |  |
|n86-0040.smt2                                                |    1.885s | 81.312MiB| sat | 0 |  |  |
|n128-0032.smt2                                               |    1.940s | 120.0MiB| sat | 0 |  |  |
|65782_cd31513fdcd15701933b_8_QF_UFNIA.smt2                   |    2.164s | 61.16MiB| sat | 0 |  |  |
|n104-0007.smt2                                               |    2.223s | 144.0MiB| unsat | 0 |  |  |
|n100-0003.smt2                                               |    2.289s | 81.324MiB| sat | 0 |  |  |
|n108-0012.smt2                                               |    2.304s | 126.0MiB| unsat | 0 |  |  |
|n17-0021.smt2                                                |    2.346s | 151.0MiB| unsat | 0 |  |  |
|38347_092cc73601c78e45f4f9_58_QF_UFNIA.smt2                  |    2.510s | 67.484MiB| sat | 0 |  |  |
|72658_63104dadde9c6026353f_70_QF_UFNIA.smt2                  |    2.880s | 55.904MiB| sat | 0 |  |  |
|n134-0038.smt2                                               |    3.010s | 61.256MiB| sat | 0 |  |  |
|44289_e5a2e5c780236919ee6a_17_QF_UFNIA.smt2                  |    3.905s | 152.0MiB| sat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFNIA.smt2      |    4.320s | 168.0MiB| sat | 0 |  |  |
|n110-0014.smt2                                               |    4.322s | 73.988MiB| sat | 0 |  |  |
|n27-0034.smt2                                                |    4.436s | 323.0MiB| unsat | 0 |  |  |
|n12-0013.smt2                                                |    4.500s | 125.0MiB| sat | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFNIA.smt2      |    4.645s | 90.576MiB| sat | 0 |  |  |
|72771_f9d228efc97cf1458e38_64_QF_UFNIA.smt2                  |    5.019s | 79.692MiB| sat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFNIA.smt2      |    5.158s | 203.0MiB| sat | 0 |  |  |
|n47-0000.smt2                                                |    5.291s | 78.152MiB| sat | 0 |  |  |
|n90-0045.smt2                                                |    6.003s | 92.06MiB| sat | 0 |  |  |
|n26-0033.smt2                                                |    6.228s | 362.0MiB| unsat | 0 |  |  |
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                  |    6.264s | 67.372MiB| unsat | 0 |  |  |
|n102-0005.smt2                                               |    6.331s | 61.708MiB| sat | 0 |  |  |
|n41-0048.smt2                                                |    6.921s | 110.0MiB| unsat | 0 |  |  |
|n73-0027.smt2                                                |    7.114s | 88.808MiB| unsat | 0 |  |  |
|n57-0010.smt2                                                |    7.157s | 121.0MiB| sat | 0 |  |  |
|44289_e5a2e5c780236919ee6a_18_QF_UFNIA.smt2                  |    7.244s | 161.0MiB| sat | 0 |  |  |
|n107-0011.smt2                                               |    7.908s | 116.0MiB| sat | 0 |  |  |
|n119-0023.smt2                                               |    8.246s | 108.0MiB| sat | 0 |  |  |
|n9-0009.smt2                                                 |    9.076s | 109.0MiB| sat | 0 |  |  |
|n5-0005.smt2                                                 |    9.445s | 99.0MiB| sat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_22_QF_UFNIA.smt2                  |    9.620s | 208.0MiB| sat | 0 |  |  |
|39657_1c7158801cd59dc13f05_46_QF_UFNIA.smt2                  |    9.640s | 120.0MiB| sat | 0 |  |  |
|940_590f27b1c3c800d3243e_32_QF_UFNIA.smt2                    |    9.664s | 277.0MiB| sat | 0 |  |  |
|44289_4066055e0f64d96da11a_14_QF_UFNIA.smt2                  |   10.086s | 185.0MiB| sat | 0 |  |  |
|n34-0041.smt2                                                |   10.489s | 137.0MiB| sat | 0 |  |  |
|n132-0036.smt2                                               |   10.689s | 59.988MiB| sat | 0 |  |  |
|n61-0015.smt2                                                |   10.706s | 195.0MiB| sat | 0 |  |  |
|63058_55d6bef5390186355f11_26_QF_UFNIA.smt2                  |   11.199s | 272.0MiB| sat | 0 |  |  |
|qf_muldivrem_152_values_0.smt2                               |   11.530s | 73.364MiB| unsat | 0 |  |  |
|n1-0001.smt2                                                 |   12.541s | 1127.0MiB| unsat | 0 |  |  |
|n87-0041.smt2                                                |   13.105s | 111.0MiB| sat | 0 |  |  |
|39657_2866defdd1f2434b69ab_47_QF_UFNIA.smt2                  |   14.951s | 73.144MiB| sat | 0 |  |  |
|n38-0045.smt2                                                |   16.871s | 177.0MiB| sat | 0 |  |  |
|n131-0035.smt2                                               |   17.287s | 64.364MiB| sat | 0 |  |  |
|n18-0022.smt2                                                |   17.932s | 135.0MiB| sat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                  |   19.538s | 80.544MiB| unsat | 0 |  |  |
|93493_798593962ee29ad45ac8_52_QF_UFNIA.smt2                  |   21.058s | 278.0MiB| sat | 0 |  |  |
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFNIA.smt2       |   24.069s | 183.0MiB| sat | 0 |  |  |
|n25-0032.smt2                                                |   24.939s | 310.0MiB| sat | 0 |  |  |
|940_590f27b1c3c800d3243e_30_QF_UFNIA.smt2                    |   25.582s | 407.0MiB| sat | 0 |  |  |
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                  |   27.803s | 843.0MiB| unsat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                  |   28.353s | 74.116MiB| unsat | 0 |  |  |
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFNIA.smt2      |   32.220s | 192.0MiB| sat | 0 |  |  |
|n106-0009.smt2                                               |   34.345s | 64.584MiB| sat | 0 |  |  |
|n31-0038.smt2                                                |   34.370s | 85.012MiB| sat | 0 |  |  |
|n65-0019.smt2                                                |   41.048s | 101.0MiB| sat | 0 |  |  |
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFNIA.smt2      |   41.370s | 215.0MiB| sat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_23_QF_UFNIA.smt2                  |   42.636s | 299.0MiB| sat | 0 |  |  |
|n11-0012.smt2                                                |   52.874s | 119.0MiB| sat | 0 |  |  |
|n48-0001.smt2                                                |   56.776s | 113.0MiB| timeout | 0 |  |  |
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFNIA.smt2      |   56.828s | 237.0MiB| sat | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFNIA.smt2      |   57.148s | 391.0MiB| sat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_24_QF_UFNIA.smt2                  |   58.163s | 371.0MiB| sat | 0 |  |  |
|n89-0044.smt2                                                |   58.835s | 141.0MiB| unsat | 0 |  |  |
|n95-0050.smt2                                                |   59.285s | 813.0MiB| timeout | 0 |  |  |
|n93-0048.smt2                                                |   59.286s | 154.0MiB| timeout | 0 |  |  |
|n30-0037.smt2                                                |   59.574s | 232.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_31_QF_UFNIA.smt2                    |   59.611s | 113.0MiB| timeout | 0 |  |  |
|n71-0025.smt2                                                |   59.618s | 1028.0MiB| timeout | 0 |  |  |
|0067.smt2                                                    |   59.734s | 460.0MiB| timeout | 0 |  |  |
|qf_muldivrem_239_values_0.smt2                               |   59.778s | 128.0MiB| timeout | 0 |  |  |
|0059.smt2                                                    |   59.811s | 808.0MiB| timeout | 0 |  |  |
|qf_muldivrem_290_292_values_0.smt2                           |   59.820s | 123.0MiB| timeout | 0 |  |  |
|n114-0018.smt2                                               |   59.829s | 198.0MiB| timeout | 0 |  |  |
|n126-0030.smt2                                               |   59.840s | 136.0MiB| timeout | 0 |  |  |
|65782_cd31513fdcd15701933b_5_QF_UFNIA.smt2                   |   59.844s | 98.0MiB| timeout | 0 |  |  |
|n101-0004.smt2                                               |   59.853s | 101.0MiB| timeout | 0 |  |  |
|n109-0013.smt2                                               |   59.858s | 261.0MiB| timeout | 0 |  |  |
|n105-0008.smt2                                               |   59.873s | 137.0MiB| timeout | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_35_QF_UFNIA.smt2                  |   59.878s | 86.104MiB| timeout | 0 |  |  |
|41958_32933c5a1384696720a2_63_QF_UFNIA.smt2                  |   59.880s | 76.628MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_1_UFNIA.smt2                      |   59.895s | 108.0MiB| timeout | 0 |  |  |
|n58-0011.smt2                                                |   59.895s | 69.5MiB| timeout | 0 |  |  |
|0060.smt2                                                    |   59.896s | 188.0MiB| timeout | 0 |  |  |
|n91-0046.smt2                                                |   59.899s | 226.0MiB| timeout | 0 |  |  |
|n69-0023.smt2                                                |   59.906s | 147.0MiB| timeout | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFNIA.smt2      |   59.908s | 400.0MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_55_QF_UFNIA.smt2                  |   59.909s | 58.632MiB| timeout | 0 |  |  |
|n137-0041.smt2                                               |   59.913s | 148.0MiB| timeout | 0 |  |  |
|39657_1c7158801cd59dc13f05_44_QF_UFNIA.smt2                  |   59.914s | 125.0MiB| timeout | 0 |  |  |
|n130-0034.smt2                                               |   59.920s | 276.0MiB| timeout | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_36_QF_UFNIA.smt2                  |   59.922s | 108.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_4_UFNIA.smt2                      |   59.924s | 332.0MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_57_QF_UFNIA.smt2                  |   59.929s | 69.176MiB| timeout | 0 |  |  |
|n113-0017.smt2                                               |   59.929s | 189.0MiB| timeout | 0 |  |  |
|n54-0007.smt2                                                |   59.930s | 234.0MiB| timeout | 0 |  |  |
|72658_63104dadde9c6026353f_71_QF_UFNIA.smt2                  |   59.931s | 66.94MiB| timeout | 0 |  |  |
|n120-0024.smt2                                               |   59.932s | 160.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2      |   59.934s | 145.0MiB| timeout | 0 |  |  |
|n121-0025.smt2                                               |   59.935s | 447.0MiB| timeout | 0 |  |  |
|n4-0004.smt2                                                 |   59.937s | 108.0MiB| timeout | 0 |  |  |
|n50-0003.smt2                                                |   59.938s | 89.788MiB| timeout | 0 |  |  |
|41958_32933c5a1384696720a2_62_QF_UFNIA.smt2                  |   59.939s | 72.756MiB| timeout | 0 |  |  |
|n98-0001.smt2                                                |   59.939s | 122.0MiB| timeout | 0 |  |  |
|n129-0033.smt2                                               |   59.941s | 117.0MiB| timeout | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                  |   59.943s | 56.808MiB| timeout | 0 |  |  |
|qf_InstCombineShift497d_values_0.smt2                        |   59.944s | 103.0MiB| timeout | 0 |  |  |
|n7-0007.smt2                                                 |   59.944s | 349.0MiB| timeout | 0 |  |  |
|n37-0044.smt2                                                |   59.946s | 187.0MiB| timeout | 0 |  |  |
|n49-0002.smt2                                                |   59.947s | 90.832MiB| timeout | 0 |  |  |
|n75-0029.smt2                                                |   59.948s | 86.02MiB| timeout | 0 |  |  |
|n66-0020.smt2                                                |   59.950s | 281.0MiB| timeout | 0 |  |  |
|n36-0043.smt2                                                |   59.951s | 516.0MiB| timeout | 0 |  |  |
|n123-0027.smt2                                               |   59.952s | 151.0MiB| timeout | 0 |  |  |
|n10-0010.smt2                                                |   59.952s | 212.0MiB| timeout | 0 |  |  |
|n81-0035.smt2                                                |   59.953s | 367.0MiB| timeout | 0 |  |  |
|n72-0026.smt2                                                |   59.953s | 523.0MiB| timeout | 0 |  |  |
|n56-0009.smt2                                                |   59.953s | 104.0MiB| timeout | 0 |  |  |
|n64-0018.smt2                                                |   59.957s | 204.0MiB| timeout | 0 |  |  |
|n40-0047.smt2                                                |   59.957s | 380.0MiB| timeout | 0 |  |  |
|n63-0017.smt2                                                |   59.957s | 231.0MiB| timeout | 0 |  |  |
|n55-0008.smt2                                                |   59.957s | 102.0MiB| timeout | 0 |  |  |
|n8-0008.smt2                                                 |   59.959s | 296.0MiB| timeout | 0 |  |  |
|n118-0022.smt2                                               |   59.960s | 490.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFNIA.smt2      |   59.961s | 114.0MiB| timeout | 0 |  |  |
|n133-0037.smt2                                               |   59.961s | 60.272MiB| timeout | 0 |  |  |
|int_check_ne_bvashr1_ltr_inv_g.smt2                          |   59.961s | 53.796MiB| timeout | 0 |  |  |
|n62-0016.smt2                                                |   59.962s | 312.0MiB| timeout | 0 |  |  |
|n122-0026.smt2                                               |   59.962s | 154.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_2_UFNIA.smt2                      |   59.964s | 211.0MiB| timeout | 0 |  |  |
|0056.smt2                                                    |   59.964s | 326.0MiB| timeout | 0 |  |  |
|n97-0000.smt2                                                |   59.965s | 110.0MiB| timeout | 0 |  |  |
|n103-0006.smt2                                               |   59.966s | 70.136MiB| timeout | 0 |  |  |
|0065.smt2                                                    |   59.968s | 226.0MiB| timeout | 0 |  |  |
|int_check_ne_bvashr0_ltr_inv_g.smt2                          |   59.968s | 53.452MiB| timeout | 0 |  |  |
|0064.smt2                                                    |   59.968s | 571.0MiB| timeout | 0 |  |  |
|39657_1c7158801cd59dc13f05_45_QF_UFNIA.smt2                  |   59.968s | 116.0MiB| timeout | 0 |  |  |
|int_check_eq_bvlshr0_rtl.smt2                                |   59.969s | 118.0MiB| timeout | 0 |  |  |
|n51-0004.smt2                                                |   59.969s | 86.868MiB| timeout | 0 |  |  |
|n16-0019.smt2                                                |   59.970s | 239.0MiB| timeout | 0 |  |  |
|n88-0042.smt2                                                |   59.973s | 127.0MiB| timeout | 0 |  |  |
|n32-0039.smt2                                                |   59.974s | 424.0MiB| timeout | 0 |  |  |
|n135-0039.smt2                                               |   59.975s | 107.0MiB| timeout | 0 |  |  |
|n94-0049.smt2                                                |   59.977s | 273.0MiB| timeout | 0 |  |  |
|n45-0052.smt2                                                |   59.977s | 1306.0MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_56_QF_UFNIA.smt2                  |   59.978s | 130.0MiB| timeout | 0 |  |  |
|44289_4066055e0f64d96da11a_15_QF_UFNIA.smt2                  |   59.978s | 646.0MiB| timeout | 0 |  |  |
|n2-0002.smt2                                                 |   59.979s | 488.0MiB| timeout | 0 |  |  |
|41958_32933c5a1384696720a2_61_QF_UFNIA.smt2                  |   59.980s | 77.524MiB| timeout | 0 |  |  |
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                   |   59.980s | 1001.0MiB| timeout | 0 |  |  |
|n127-0031.smt2                                               |   59.980s | 102.0MiB| timeout | 0 |  |  |
|65782_cd31513fdcd15701933b_7_QF_UFNIA.smt2                   |   59.981s | 74.028MiB| timeout | 0 |  |  |
|n112-0016.smt2                                               |   59.981s | 814.0MiB| timeout | 0 |  |  |
|3106_1c933134166dbad31f79_39_QF_UFNIA.smt2                   |   59.981s | 165.0MiB| timeout | 0 |  |  |
|n22-0029.smt2                                                |   59.981s | 309.0MiB| timeout | 0 |  |  |
|0062.smt2                                                    |   59.981s | 2695.0MiB| timeout | 0 |  |  |
|0055.smt2                                                    |   59.982s | 1410.0MiB| timeout | 0 |  |  |
|n52-0005.smt2                                                |   59.983s | 90.768MiB| timeout | 0 |  |  |
|int_check_bvsge_bvlshr0_ltr_inv_g.smt2                       |   59.984s | 54.124MiB| timeout | 0 |  |  |
|n23-0030.smt2                                                |   59.984s | 364.0MiB| timeout | 0 |  |  |
|n0-0000.smt2                                                 |   59.984s | 235.0MiB| timeout | 0 |  |  |
|n19-0024.smt2                                                |   59.985s | 194.0MiB| timeout | 0 |  |  |
|n60-0014.smt2                                                |   59.985s | 346.0MiB| timeout | 0 |  |  |
|n84-0038.smt2                                                |   59.985s | 528.0MiB| timeout | 0 |  |  |
|n53-0006.smt2                                                |   59.985s | 59.984MiB| timeout | 0 |  |  |
|n115-0019.smt2                                               |   59.985s | 120.0MiB| timeout | 0 |  |  |
|38347_525a1ca0331f2bcbf520_54_QF_UFNIA.smt2                  |   59.985s | 358.0MiB| timeout | 0 |  |  |
|n46-0053.smt2                                                |   59.987s | 220.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_29_QF_UFNIA.smt2                    |   59.988s | 286.0MiB| timeout | 0 |  |  |
|qf_muldivrem_229_values_0.smt2                               |   59.988s | 120.0MiB| timeout | 0 |  |  |
|0061.smt2                                                    |   59.989s | 189.0MiB| timeout | 0 |  |  |
|0058.smt2                                                    |   59.990s | 805.0MiB| timeout | 0 |  |  |
|n74-0028.smt2                                                |   59.990s | 158.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_3_UFNIA.smt2                      |   59.990s | 99.0MiB| timeout | 0 |  |  |
|n59-0012.smt2                                                |   59.990s | 151.0MiB| timeout | 0 |  |  |
|n82-0036.smt2                                                |   59.991s | 176.0MiB| timeout | 0 |  |  |
|0054.smt2                                                    |   59.992s | 1406.0MiB| timeout | 0 |  |  |
|n21-0027.smt2                                                |   59.992s | 228.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFNIA.smt2      |   59.992s | 113.0MiB| timeout | 0 |  |  |
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFNIA.smt2      |   59.992s | 457.0MiB| timeout | 0 |  |  |
|n117-0021.smt2                                               |   59.993s | 642.0MiB| timeout | 0 |  |  |
|n116-0020.smt2                                               |   59.995s | 772.0MiB| timeout | 0 |  |  |
|n111-0015.smt2                                               |   59.995s | 905.0MiB| timeout | 0 |  |  |
|n96-0051.smt2                                                |   59.996s | 231.0MiB| timeout | 0 |  |  |
|n13-0015.smt2                                                |   59.996s | 440.0MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_73_QF_UFNIA.smt2                  |   59.996s | 783.0MiB| timeout | 0 |  |  |
|n44-0051.smt2                                                |   59.998s | 502.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFNIA.smt2      |   59.998s | 128.0MiB| timeout | 0 |  |  |
|n24-0031.smt2                                                |   60.000s | 343.0MiB| timeout | 0 |  |  |
|n79-0033.smt2                                                |   60.000s | 334.0MiB| timeout | 0 |  |  |
|n28-0035.smt2                                                |   60.001s | 303.0MiB| timeout | 0 |  |  |
|n77-0031.smt2                                                |   60.002s | 639.0MiB| timeout | 0 |  |  |
|n35-0042.smt2                                                |   60.003s | 331.0MiB| timeout | 0 |  |  |
|n83-0037.smt2                                                |   60.006s | 548.0MiB| timeout | 0 |  |  |
|0057.smt2                                                    |   60.006s | 192.0MiB| timeout | 0 |  |  |
|n42-0049.smt2                                                |   60.007s | 364.0MiB| timeout | 0 |  |  |
|n3-0003.smt2                                                 |   60.009s | 164.0MiB| timeout | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_34_QF_UFNIA.smt2                  |   60.010s | 67.768MiB| timeout | 0 |  |  |
|n68-0022.smt2                                                |   60.013s | 340.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_33_QF_UFNIA.smt2                    |   60.014s | 309.0MiB| timeout | 0 |  |  |
|n6-0006.smt2                                                 |   60.015s | 75.86MiB| timeout | 0 |  |  |
|n136-0040.smt2                                               |   60.016s | 464.0MiB| timeout | 0 |  |  |
|n78-0032.smt2                                                |   60.016s | 525.0MiB| timeout | 0 |  |  |
|n20-0026.smt2                                                |   60.016s | 825.0MiB| timeout | 0 |  |  |
|n70-0024.smt2                                                |   60.017s | 1048.0MiB| timeout | 0 |  |  |
|n29-0036.smt2                                                |   60.018s | 1715.0MiB| timeout | 0 |  |  |
|n33-0040.smt2                                                |   60.024s | 608.0MiB| timeout | 0 |  |  |
|n67-0021.smt2                                                |   60.024s | 579.0MiB| timeout | 0 |  |  |
|n39-0046.smt2                                                |   60.024s | 1713.0MiB| timeout | 0 |  |  |
|n76-0030.smt2                                                |   60.031s | 1042.0MiB| timeout | 0 |  |  |
|n85-0039.smt2                                                |   60.046s | 738.0MiB| timeout | 0 |  |  |
|0066.smt2                                                    |   60.050s | 2929.0MiB| timeout | 0 |  |  |
|0063.smt2                                                    |   60.065s | 2076.0MiB| timeout | 0 |  |  |
|n80-0034.smt2                                                |   60.109s | 80.66MiB| timeout | 0 |  |  |
|n43-0050.smt2                                                |   60.125s | 1122.0MiB| timeout | 0 |  |  |
