# .

* SAT 160
* UNSAT 44
* TIMEOUT 104
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: masterd on certora
Job tag: master_on_certora
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 8d81a2dcaf4de007ce587f396f1b48fbc29646dd
Z3 branch: 
Z3 options: "-T:600 -st smt.arith.lp.dio_eqs=false"
Z3 inputs: inputs/certora
Z3 commit message: Note that Z3_get_numeral_small is essentially redundant (#7599)

* Check that Z3_get_numeral_small is given non-null out params

Analogous to other Z3_get_numeral_* functions with out params.

* Note that Z3_get_numeral_small is essentially redundant

The error behavior of Z3_get_numeral_small does not follow the pattern of
the other functions. The functions that have out params and return a bool
indicating success (such as Z3_get_numeral_rational_int64) return false
rather than signaling an error when given an unsupported expression
argument (such as a rounding mode value). The functions that do not have out
params signal an error in such cases. Z3_get_numeral_small is the odd one
out in that it signals errors and returns a status bool.

This error handling is the only difference between Z3_get_numeral_small and
Z3_get_numeral_rational_int64, so this patch adds a comment to the
documentation.

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|65782_cd31513fdcd15701933b_6_QF_UFNIA.smt2                   |    0.090s | 21.1MiB| sat | 0 |  |  |
|65782_cd31513fdcd15701933b_6_QF_UFDTNIA.smt2                 |    0.099s | 21.024MiB| sat | 0 |  |  |
|65782_cd31513fdcd15701933b_6_QF_UFDTLIA.smt2                 |    0.110s | 21.516MiB| sat | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_34_QF_UFDTLIA.smt2                |    0.138s | 23.304MiB| sat | 0 |  |  |
|63058_aa742630eef64f949de269382c1f9035_25_UFLIA.smt2         |    0.138s | 23.812MiB| unsat | 0 |  |  |
|65782_cd31513fdcd15701933b_6_QF_UFLIA.smt2                   |    0.149s | 21.528MiB| sat | 0 |  |  |
|63058_aa742630eef64f949de269382c1f9035_25_UFDTLIA.smt2       |    0.182s | 24.392MiB| unsat | 0 |  |  |
|63058_aa742630eef64f949de269382c1f9035_25_UFDTNIA.smt2       |    0.191s | 23.704MiB| unsat | 0 |  |  |
|63058_aa742630eef64f949de269382c1f9035_25_UFNIA.smt2         |    0.201s | 23.248MiB| unsat | 0 |  |  |
|3106_1c933134166dbad31f79_40_QF_UFDTLIA.smt2                 |    0.219s | 23.324MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_40_QF_UFLIA.smt2                   |    0.228s | 23.86MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_40_QF_UFDTNIA.smt2                 |    0.245s | 22.768MiB| sat | 0 |  |  |
|39657_2866defdd1f2434b69ab_48_QF_UFDTNIA.smt2                |    0.270s | 26.168MiB| sat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFDTNIA.smt2    |    0.271s | 27.26MiB| sat | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_34_QF_UFLIA.smt2                  |    0.340s | 25.268MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_40_QF_UFNIA.smt2                   |    0.350s | 23.528MiB| sat | 0 |  |  |
|65782_cd31513fdcd15701933b_7_QF_UFDTLIA.smt2                 |    0.429s | 25.344MiB| sat | 0 |  |  |
|65782_cd31513fdcd15701933b_7_QF_UFLIA.smt2                   |    0.441s | 25.6MiB| sat | 0 |  |  |
|41958_45c688a4814eb926c254_60_QF_UFDTNIA.smt2                |    0.455s | 28.328MiB| sat | 0 |  |  |
|41958_45c688a4814eb926c254_59_QF_UFDTNIA.smt2                |    0.500s | 30.076MiB| sat | 0 |  |  |
|65782_cd31513fdcd15701933b_8_QF_UFDTLIA.smt2                 |    0.550s | 25.576MiB| sat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFDTLIA.smt2    |    0.564s | 33.288MiB| sat | 0 |  |  |
|72771_f9d228efc97cf1458e38_64_QF_UFDTNIA.smt2                |    0.586s | 26.42MiB| sat | 0 |  |  |
|83314_a702bf8b823398c9e37a_0_UFNIA.smt2                      |    0.596s | 25.228MiB| sat | 0 |  |  |
|65782_cd31513fdcd15701933b_8_QF_UFLIA.smt2                   |    0.645s | 26.464MiB| sat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFDTNIA.smt2    |    0.662s | 29.024MiB| sat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFDTLIA.smt2    |    0.745s | 30.304MiB| sat | 0 |  |  |
|65782_cd31513fdcd15701933b_8_QF_UFNIA.smt2                   |    0.882s | 24.98MiB| sat | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_35_QF_UFDTLIA.smt2                |    0.918s | 26.408MiB| unsat | 0 |  |  |
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                  |    0.943s | 27.016MiB| unsat | 0 |  |  |
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                |    0.988s | 28.468MiB| sat | 0 |  |  |
|41958_45c688a4814eb926c254_60_QF_UFDTLIA.smt2                |    1.031s | 33.132MiB| sat | 0 |  |  |
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                |    1.040s | 34.284MiB| sat | 0 |  |  |
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                  |    1.167s | 33.956MiB| sat | 0 |  |  |
|72771_f9d228efc97cf1458e38_64_QF_UFNIA.smt2                  |    1.280s | 37.488MiB| sat | 0 |  |  |
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                |    1.319s | 36.044MiB| sat | 0 |  |  |
|39657_2866defdd1f2434b69ab_47_QF_UFDTNIA.smt2                |    1.363s | 26.568MiB| sat | 0 |  |  |
|83314_a702bf8b823398c9e37a_0_UFDTNIA.smt2                    |    1.373s | 27.008MiB| sat | 0 |  |  |
|41958_45c688a4814eb926c254_59_QF_UFDTLIA.smt2                |    1.424s | 36.196MiB| sat | 0 |  |  |
|38347_092cc73601c78e45f4f9_58_QF_UFDTNIA.smt2                |    1.528s | 26.728MiB| sat | 0 |  |  |
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                  |    1.617s | 30.788MiB| sat | 0 |  |  |
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                |    1.660s | 27.372MiB| unsat | 0 |  |  |
|65782_cd31513fdcd15701933b_8_QF_UFDTNIA.smt2                 |    1.761s | 25.04MiB| sat | 0 |  |  |
|72658_63104dadde9c6026353f_70_QF_UFDTLIA.smt2                |    1.805s | 55.08MiB| sat | 0 |  |  |
|38347_092cc73601c78e45f4f9_58_QF_UFDTLIA.smt2                |    1.835s | 27.604MiB| sat | 0 |  |  |
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                  |    1.974s | 39.684MiB| sat | 0 |  |  |
|44289_4066055e0f64d96da11a_14_QF_UFDTNIA.smt2                |    1.999s | 41.48MiB| sat | 0 |  |  |
|41958_32933c5a1384696720a2_61_QF_UFNIA.smt2                  |    2.048s | 27.096MiB| sat | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_35_QF_UFLIA.smt2                  |    2.190s | 35.78MiB| unsat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                |    2.227s | 23.316MiB| unsat | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFDTNIA.smt2    |    2.337s | 55.72MiB| sat | 0 |  |  |
|38347_092cc73601c78e45f4f9_58_QF_UFLIA.smt2                  |    2.479s | 31.008MiB| sat | 0 |  |  |
|44289_4066055e0f64d96da11a_14_QF_UFDTLIA.smt2                |    2.610s | 42.832MiB| sat | 0 |  |  |
|39657_1c7158801cd59dc13f05_46_QF_UFDTLIA.smt2                |    2.677s | 50.732MiB| sat | 0 |  |  |
|44289_e5a2e5c780236919ee6a_18_QF_UFDTLIA.smt2                |    2.678s | 57.748MiB| sat | 0 |  |  |
|38347_092cc73601c78e45f4f9_58_QF_UFNIA.smt2                  |    2.696s | 30.048MiB| sat | 0 |  |  |
|44289_e5a2e5c780236919ee6a_17_QF_UFDTLIA.smt2                |    2.896s | 57.592MiB| sat | 0 |  |  |
|63058_55d6bef5390186355f11_26_QF_UFDTLIA.smt2                |    3.092s | 47.956MiB| sat | 0 |  |  |
|39657_2866defdd1f2434b69ab_48_QF_UFDTLIA.smt2                |    3.261s | 28.7MiB| sat | 0 |  |  |
|41958_32933c5a1384696720a2_63_QF_UFDTLIA.smt2                |    3.396s | 31.564MiB| sat | 0 |  |  |
|41958_45c688a4814eb926c254_60_QF_UFNIA.smt2                  |    3.408s | 45.512MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_41_QF_UFDTLIA.smt2                 |    3.512s | 37.828MiB| sat | 0 |  |  |
|44289_e5a2e5c780236919ee6a_18_QF_UFDTNIA.smt2                |    3.594s | 58.48MiB| sat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                  |    3.851s | 23.396MiB| unsat | 0 |  |  |
|39657_1c7158801cd59dc13f05_45_QF_UFDTLIA.smt2                |    3.906s | 52.064MiB| sat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_24_QF_UFDTNIA.smt2                |    4.054s | 62.228MiB| sat | 0 |  |  |
|72658_63104dadde9c6026353f_70_QF_UFDTNIA.smt2                |    4.107s | 23.268MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_41_QF_UFDTNIA.smt2                 |    4.298s | 35.276MiB| sat | 0 |  |  |
|39657_1c7158801cd59dc13f05_44_QF_UFDTLIA.smt2                |    4.312s | 50.624MiB| sat | 0 |  |  |
|41958_45c688a4814eb926c254_60_QF_UFLIA.smt2                  |    4.324s | 49.532MiB| sat | 0 |  |  |
|38347_092cc73601c78e45f4f9_56_QF_UFDTNIA.smt2                |    4.362s | 46.464MiB| sat | 0 |  |  |
|65782_cd31513fdcd15701933b_7_QF_UFNIA.smt2                   |    4.599s | 26.724MiB| unsat | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTNIA.smt2    |    4.654s | 43.6MiB| sat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_23_QF_UFDTLIA.smt2                |    4.759s | 65.624MiB| sat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_22_QF_UFDTLIA.smt2                |    4.900s | 45.336MiB| sat | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFNIA.smt2      |    5.406s | 41.776MiB| sat | 0 |  |  |
|39657_2866defdd1f2434b69ab_47_QF_UFDTLIA.smt2                |    5.551s | 30.0MiB| sat | 0 |  |  |
|66603_accdadf23a1cf70ae043_72_QF_UFDTLIA.smt2                |    5.622s | 104.0MiB| unsat | 0 |  |  |
|66603_accdadf23a1cf70ae043_72_QF_UFDTNIA.smt2                |    5.961s | 103.0MiB| unsat | 0 |  |  |
|72771_f9d228efc97cf1458e38_64_QF_UFDTLIA.smt2                |    6.143s | 29.856MiB| sat | 0 |  |  |
|66603_accdadf23a1cf70ae043_73_QF_UFDTNIA.smt2                |    6.360s | 95.716MiB| sat | 0 |  |  |
|41958_32933c5a1384696720a2_63_QF_UFLIA.smt2                  |    6.616s | 32.712MiB| sat | 0 |  |  |
|41958_45c688a4814eb926c254_59_QF_UFNIA.smt2                  |    6.663s | 62.64MiB| sat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_23_QF_UFDTNIA.smt2                |    6.984s | 48.452MiB| sat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                |    7.419s | 66.3MiB| unsat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                  |    7.559s | 31.728MiB| unsat | 0 |  |  |
|44289_4066055e0f64d96da11a_15_QF_UFDTNIA.smt2                |    7.897s | 78.68MiB| sat | 0 |  |  |
|44289_e5a2e5c780236919ee6a_17_QF_UFDTNIA.smt2                |    8.321s | 57.508MiB| sat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_22_QF_UFDTNIA.smt2                |    8.684s | 44.36MiB| sat | 0 |  |  |
|39657_1c7158801cd59dc13f05_45_QF_UFLIA.smt2                  |    8.891s | 59.004MiB| sat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                  |    9.288s | 72.588MiB| unsat | 0 |  |  |
|65782_cd31513fdcd15701933b_7_QF_UFDTNIA.smt2                 |    9.451s | 26.524MiB| unsat | 0 |  |  |
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFDTNIA.smt2    |    9.491s | 72.5MiB| sat | 0 |  |  |
|44289_4066055e0f64d96da11a_15_QF_UFDTLIA.smt2                |    9.584s | 81.672MiB| sat | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_34_QF_UFNIA.smt2                  |   10.475s | 28.576MiB| unsat | 0 |  |  |
|39657_2866defdd1f2434b69ab_48_QF_UFLIA.smt2                  |   11.207s | 37.772MiB| sat | 0 |  |  |
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFDTLIA.smt2    |   11.505s | 122.0MiB| sat | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_34_QF_UFDTNIA.smt2                |   11.752s | 26.768MiB| unsat | 0 |  |  |
|3106_1c933134166dbad31f79_41_QF_UFLIA.smt2                   |   12.298s | 45.848MiB| sat | 0 |  |  |
|72658_63104dadde9c6026353f_70_QF_UFNIA.smt2                  |   12.932s | 25.812MiB| sat | 0 |  |  |
|83314_a702bf8b823398c9e37a_0_UFDTLIA.smt2                    |   13.010s | 84.748MiB| sat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_24_QF_UFDTLIA.smt2                |   13.057s | 68.204MiB| sat | 0 |  |  |
|39657_1c7158801cd59dc13f05_44_QF_UFDTNIA.smt2                |   13.364s | 53.444MiB| sat | 0 |  |  |
|83314_a702bf8b823398c9e37a_1_UFNIA.smt2                      |   13.503s | 44.14MiB| sat | 0 |  |  |
|44289_e5a2e5c780236919ee6a_18_QF_UFLIA.smt2                  |   14.272s | 87.572MiB| sat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                  |   14.297s | 32.288MiB| unsat | 0 |  |  |
|940_590f27b1c3c800d3243e_31_QF_UFNIA.smt2                    |   14.355s | 65.4MiB| sat | 0 |  |  |
|39657_2866defdd1f2434b69ab_48_QF_UFNIA.smt2                  |   15.034s | 38.676MiB| sat | 0 |  |  |
|39657_1c7158801cd59dc13f05_44_QF_UFLIA.smt2                  |   15.088s | 84.48MiB| sat | 0 |  |  |
|66603_accdadf23a1cf70ae043_76_QF_UFDTNIA.smt2                |   15.846s | 142.0MiB| unsat | 0 |  |  |
|72658_63104dadde9c6026353f_70_QF_UFLIA.smt2                  |   16.429s | 73.24MiB| sat | 0 |  |  |
|63058_55d6bef5390186355f11_26_QF_UFDTNIA.smt2                |   16.570s | 51.252MiB| sat | 0 |  |  |
|940_590f27b1c3c800d3243e_31_QF_UFDTNIA.smt2                  |   16.902s | 74.96MiB| sat | 0 |  |  |
|44289_4066055e0f64d96da11a_14_QF_UFNIA.smt2                  |   17.266s | 92.008MiB| sat | 0 |  |  |
|41958_45c688a4814eb926c254_59_QF_UFLIA.smt2                  |   17.757s | 85.416MiB| sat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                |   18.494s | 63.816MiB| unsat | 0 |  |  |
|44289_e5a2e5c780236919ee6a_17_QF_UFLIA.smt2                  |   18.816s | 90.188MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_39_QF_UFDTLIA.smt2                 |   20.406s | 83.42MiB| sat | 0 |  |  |
|66603_accdadf23a1cf70ae043_75_QF_UFDTLIA.smt2                |   20.584s | 123.0MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_41_QF_UFNIA.smt2                   |   21.333s | 50.564MiB| sat | 0 |  |  |
|44289_e5a2e5c780236919ee6a_18_QF_UFNIA.smt2                  |   21.685s | 90.216MiB| sat | 0 |  |  |
|39657_1c7158801cd59dc13f05_46_QF_UFDTNIA.smt2                |   22.093s | 54.472MiB| sat | 0 |  |  |
|38347_092cc73601c78e45f4f9_56_QF_UFNIA.smt2                  |   24.090s | 71.316MiB| sat | 0 |  |  |
|41958_32933c5a1384696720a2_62_QF_UFDTLIA.smt2                |   25.373s | 51.348MiB| sat | 0 |  |  |
|66603_accdadf23a1cf70ae043_76_QF_UFDTLIA.smt2                |   26.362s | 229.0MiB| unsat | 0 |  |  |
|44289_4066055e0f64d96da11a_14_QF_UFLIA.smt2                  |   27.267s | 98.0MiB| sat | 0 |  |  |
|39657_1c7158801cd59dc13f05_46_QF_UFLIA.smt2                  |   28.292s | 60.956MiB| sat | 0 |  |  |
|41958_32933c5a1384696720a2_62_QF_UFLIA.smt2                  |   30.986s | 46.452MiB| sat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFLIA.smt2      |   31.442s | 117.0MiB| sat | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTNIA.smt2    |   31.805s | 52.284MiB| sat | 0 |  |  |
|39657_1c7158801cd59dc13f05_45_QF_UFDTNIA.smt2                |   32.470s | 57.148MiB| sat | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFDTLIA.smt2    |   32.612s | 80.272MiB| sat | 0 |  |  |
|72771_f9d228efc97cf1458e38_64_QF_UFLIA.smt2                  |   32.956s | 47.116MiB| sat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                |   32.976s | 36.62MiB| unsat | 0 |  |  |
|66603_accdadf23a1cf70ae043_74_QF_UFDTLIA.smt2                |   34.461s | 126.0MiB| sat | 0 |  |  |
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFDTLIA.smt2     |   35.063s | 80.4MiB| sat | 0 |  |  |
|83314_a702bf8b823398c9e37a_1_UFDTNIA.smt2                    |   35.674s | 46.34MiB| sat | 0 |  |  |
|83314_a702bf8b823398c9e37a_2_UFDTNIA.smt2                    |   37.696s | 101.0MiB| sat | 0 |  |  |
|30078_f817a923328f75af7e60_27_QF_UFDTLIA.smt2                |   37.894s | 147.0MiB| unsat | 0 |  |  |
|940_590f27b1c3c800d3243e_32_QF_UFNIA.smt2                    |   39.821s | 254.0MiB| sat | 0 |  |  |
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFDTLIA.smt2    |   39.830s | 76.144MiB| sat | 0 |  |  |
|66603_accdadf23a1cf70ae043_72_QF_UFLIA.smt2                  |   41.590s | 533.0MiB| unsat | 0 |  |  |
|66603_accdadf23a1cf70ae043_75_QF_UFDTNIA.smt2                |   41.606s | 133.0MiB| sat | 0 |  |  |
|44289_e5a2e5c780236919ee6a_17_QF_UFNIA.smt2                  |   42.058s | 108.0MiB| sat | 0 |  |  |
|30078_f817a923328f75af7e60_27_QF_UFDTNIA.smt2                |   43.087s | 131.0MiB| unsat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFLIA.smt2      |   43.548s | 148.0MiB| sat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_23_QF_UFLIA.smt2                  |   45.295s | 162.0MiB| sat | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFNIA.smt2      |   48.624s | 244.0MiB| sat | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTNIA.smt2    |   49.286s | 54.3MiB| sat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFNIA.smt2      |   50.173s | 156.0MiB| sat | 0 |  |  |
|52759_b3ecd2335fd16ec2eee2_9_UFDTLIA.smt2                    |   54.072s | 50.428MiB| sat | 0 |  |  |
|39657_2866defdd1f2434b69ab_47_QF_UFNIA.smt2                  |   56.347s | 50.836MiB| sat | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_36_QF_UFLIA.smt2                  |   63.265s | 284.0MiB| unsat | 0 |  |  |
|940_590f27b1c3c800d3243e_29_QF_UFDTNIA.smt2                  |   63.679s | 195.0MiB| sat | 0 |  |  |
|940_590f27b1c3c800d3243e_29_QF_UFNIA.smt2                    |   65.423s | 237.0MiB| sat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_22_QF_UFLIA.smt2                  |   65.827s | 149.0MiB| sat | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFDTNIA.smt2    |   66.391s | 93.208MiB| unsat | 0 |  |  |
|39657_2866defdd1f2434b69ab_47_QF_UFLIA.smt2                  |   68.890s | 46.584MiB| sat | 0 |  |  |
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFNIA.smt2      |   75.134s | 157.0MiB| sat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                |   75.830s | 37.28MiB| unsat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_24_QF_UFLIA.smt2                  |   80.652s | 192.0MiB| sat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFNIA.smt2      |   83.584s | 147.0MiB| sat | 0 |  |  |
|30078_f817a923328f75af7e60_28_QF_UFDTLIA.smt2                |   86.063s | 159.0MiB| unsat | 0 |  |  |
|940_590f27b1c3c800d3243e_33_QF_UFDTNIA.smt2                  |   93.497s | 164.0MiB| sat | 0 |  |  |
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFNIA.smt2      |   93.932s | 131.0MiB| sat | 0 |  |  |
|83314_a702bf8b823398c9e37a_3_UFDTNIA.smt2                    |   94.906s | 51.444MiB| unsat | 0 |  |  |
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFNIA.smt2      |   97.946s | 143.0MiB| sat | 0 |  |  |
|52759_b3ecd2335fd16ec2eee2_9_UFLIA.smt2                      |   99.047s | 79.624MiB| sat | 0 |  |  |
|30078_f817a923328f75af7e60_28_QF_UFDTNIA.smt2                |  106.333s | 139.0MiB| unsat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_22_QF_UFNIA.smt2                  |  117.869s | 186.0MiB| sat | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFDTLIA.smt2    |  119.557s | 194.0MiB| unsat | 0 |  |  |
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFNIA.smt2       |  121.671s | 114.0MiB| sat | 0 |  |  |
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFDTNIA.smt2    |  121.923s | 123.0MiB| sat | 0 |  |  |
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFDTNIA.smt2     |  127.319s | 99.0MiB| sat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_23_QF_UFNIA.smt2                  |  127.467s | 189.0MiB| sat | 0 |  |  |
|63058_55d6bef5390186355f11_26_QF_UFNIA.smt2                  |  128.378s | 216.0MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_39_QF_UFLIA.smt2                   |  135.274s | 122.0MiB| sat | 0 |  |  |
|30078_f817a923328f75af7e60_27_QF_UFNIA.smt2                  |  138.542s | 417.0MiB| unsat | 0 |  |  |
|940_590f27b1c3c800d3243e_30_QF_UFNIA.smt2                    |  152.661s | 445.0MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_39_QF_UFNIA.smt2                   |  153.397s | 155.0MiB| sat | 0 |  |  |
|63058_55d6bef5390186355f11_26_QF_UFLIA.smt2                  |  172.432s | 194.0MiB| sat | 0 |  |  |
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFDTNIA.smt2    |  176.724s | 99.824MiB| sat | 0 |  |  |
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFDTLIA.smt2    |  179.903s | 143.0MiB| sat | 0 |  |  |
|66603_accdadf23a1cf70ae043_76_QF_UFLIA.smt2                  |  194.593s | 1714.0MiB| unsat | 0 |  |  |
|41958_32933c5a1384696720a2_61_QF_UFDTLIA.smt2                |  206.832s | 117.0MiB| sat | 0 |  |  |
|30078_f817a923328f75af7e60_28_QF_UFLIA.smt2                  |  207.360s | 478.0MiB| unsat | 0 |  |  |
|41958_32933c5a1384696720a2_63_QF_UFDTNIA.smt2                |  208.596s | 34.364MiB| unsat | 0 |  |  |
|38347_092cc73601c78e45f4f9_55_QF_UFDTLIA.smt2                |  221.407s | 25.828MiB| unsat | 0 |  |  |
|39657_1c7158801cd59dc13f05_46_QF_UFNIA.smt2                  |  222.877s | 114.0MiB| sat | 0 |  |  |
|30078_f817a923328f75af7e60_28_QF_UFNIA.smt2                  |  243.476s | 432.0MiB| unsat | 0 |  |  |
|30078_f817a923328f75af7e60_27_QF_UFLIA.smt2                  |  245.688s | 457.0MiB| unsat | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_36_QF_UFDTLIA.smt2                |  248.867s | 419.0MiB| unsat | 0 |  |  |
|39657_1c7158801cd59dc13f05_44_QF_UFNIA.smt2                  |  274.395s | 134.0MiB| sat | 0 |  |  |
|83314_a702bf8b823398c9e37a_0_UFLIA.smt2                      |  285.960s | 189.0MiB| sat | 0 |  |  |
|39657_1c7158801cd59dc13f05_45_QF_UFNIA.smt2                  |  292.750s | 120.0MiB| sat | 0 |  |  |
|93493_5990a6bf5f2740164f77_50_QF_UFDTNIA.smt2                |  345.089s | 235.0MiB| sat | 0 |  |  |
|93493_5990a6bf5f2740164f77_50_QF_UFDTLIA.smt2                |  349.377s | 247.0MiB| sat | 0 |  |  |
|44289_4066055e0f64d96da11a_15_QF_UFNIA.smt2                  |  358.834s | 597.0MiB| sat | 0 |  |  |
|93493_5990a6bf5f2740164f77_50_QF_UFNIA.smt2                  |  359.483s | 319.0MiB| sat | 0 |  |  |
|52759_b3ecd2335fd16ec2eee2_9_UFDTNIA.smt2                    |  363.368s | 110.0MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_39_QF_UFDTNIA.smt2                 |  424.924s | 182.0MiB| sat | 0 |  |  |
|940_590f27b1c3c800d3243e_33_QF_UFNIA.smt2                    |  433.188s | 352.0MiB| sat | 0 |  |  |
|83314_a702bf8b823398c9e37a_3_UFDTLIA.smt2                    |  511.111s | 851.0MiB| unsat | 0 |  |  |
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                  |  534.201s | 589.0MiB| unsat | 0 |  |  |
|41958_32933c5a1384696720a2_61_QF_UFLIA.smt2                  |  596.785s | 155.0MiB| timeout | 0 |  |  |
|38347_525a1ca0331f2bcbf520_54_QF_UFDTNIA.smt2                |  597.614s | 233.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_4_UFDTLIA.smt2                    |  598.545s | 787.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_30_QF_UFDTNIA.smt2                  |  599.014s | 277.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_30_QF_UFDTLIA.smt2                  |  599.118s | 489.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_33_QF_UFDTLIA.smt2                  |  599.123s | 462.0MiB| timeout | 0 |  |  |
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFLIA.smt2      |  599.151s | 206.0MiB| timeout | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                  |  599.161s | 182.0MiB| timeout | 0 |  |  |
|65782_cd31513fdcd15701933b_5_QF_UFLIA.smt2                   |  599.185s | 249.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_31_QF_UFLIA.smt2                    |  599.279s | 204.0MiB| timeout | 0 |  |  |
|72658_63104dadde9c6026353f_71_QF_UFDTNIA.smt2                |  599.286s | 99.0MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_55_QF_UFDTNIA.smt2                |  599.326s | 25.284MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_73_QF_UFDTLIA.smt2                |  599.333s | 339.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFNIA.smt2      |  599.345s | 113.0MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_55_QF_UFLIA.smt2                  |  599.370s | 57.292MiB| timeout | 0 |  |  |
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFDTNIA.smt2    |  599.380s | 248.0MiB| timeout | 0 |  |  |
|41958_32933c5a1384696720a2_63_QF_UFNIA.smt2                  |  599.408s | 45.916MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTNIA.smt2    |  599.426s | 90.216MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_74_QF_UFNIA.smt2                  |  599.438s | 640.0MiB| timeout | 0 |  |  |
|93493_5990a6bf5f2740164f77_50_QF_UFLIA.smt2                  |  599.442s | 359.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFLIA.smt2      |  599.448s | 1150.0MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_57_QF_UFDTNIA.smt2                |  599.450s | 33.176MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_33_QF_UFLIA.smt2                    |  599.458s | 435.0MiB| timeout | 0 |  |  |
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFNIA.smt2      |  599.459s | 330.0MiB| timeout | 0 |  |  |
|44289_4066055e0f64d96da11a_15_QF_UFLIA.smt2                  |  599.477s | 641.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_3_UFNIA.smt2                      |  599.479s | 111.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFLIA.smt2      |  599.494s | 1345.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_1_UFLIA.smt2                      |  599.500s | 379.0MiB| timeout | 0 |  |  |
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFLIA.smt2       |  599.502s | 165.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_30_QF_UFLIA.smt2                    |  599.512s | 392.0MiB| timeout | 0 |  |  |
|3106_1c933134166dbad31f79_38_QF_UFDTLIA.smt2                 |  599.512s | 366.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_31_QF_UFDTLIA.smt2                  |  599.515s | 198.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTLIA.smt2    |  599.520s | 1931.0MiB| timeout | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFLIA.smt2      |  599.520s | 388.0MiB| timeout | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_24_QF_UFNIA.smt2                  |  599.522s | 300.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_2_UFNIA.smt2                      |  599.523s | 240.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_32_QF_UFDTNIA.smt2                  |  599.524s | 269.0MiB| timeout | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_35_QF_UFDTNIA.smt2                |  599.525s | 56.776MiB| timeout | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFNIA.smt2      |  599.528s | 286.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFLIA.smt2      |  599.531s | 850.0MiB| timeout | 0 |  |  |
|41958_32933c5a1384696720a2_61_QF_UFDTNIA.smt2                |  599.535s | 55.996MiB| timeout | 0 |  |  |
|41958_32933c5a1384696720a2_62_QF_UFDTNIA.smt2                |  599.540s | 64.392MiB| timeout | 0 |  |  |
|52759_b3ecd2335fd16ec2eee2_9_UFNIA.smt2                      |  599.541s | 120.0MiB| timeout | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_36_QF_UFNIA.smt2                  |  599.541s | 83.8MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2      |  599.547s | 120.0MiB| timeout | 0 |  |  |
|3106_1c933134166dbad31f79_38_QF_UFLIA.smt2                   |  599.559s | 684.0MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_55_QF_UFNIA.smt2                  |  599.576s | 32.684MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_2_UFDTLIA.smt2                    |  599.576s | 330.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_29_QF_UFDTLIA.smt2                  |  599.579s | 421.0MiB| timeout | 0 |  |  |
|72658_63104dadde9c6026353f_71_QF_UFLIA.smt2                  |  599.585s | 284.0MiB| timeout | 0 |  |  |
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFLIA.smt2      |  599.586s | 161.0MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_56_QF_UFLIA.smt2                  |  599.586s | 248.0MiB| timeout | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_36_QF_UFDTNIA.smt2                |  599.591s | 103.0MiB| timeout | 0 |  |  |
|93493_798593962ee29ad45ac8_52_QF_UFDTNIA.smt2                |  599.594s | 142.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_4_UFLIA.smt2                      |  599.598s | 720.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_4_UFDTNIA.smt2                    |  599.604s | 182.0MiB| timeout | 0 |  |  |
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                   |  599.616s | 958.0MiB| timeout | 0 |  |  |
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFDTLIA.smt2    |  599.618s | 231.0MiB| timeout | 0 |  |  |
|41958_32933c5a1384696720a2_62_QF_UFNIA.smt2                  |  599.619s | 51.792MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_4_UFNIA.smt2                      |  599.622s | 246.0MiB| timeout | 0 |  |  |
|65782_cd31513fdcd15701933b_5_QF_UFDTNIA.smt2                 |  599.623s | 93.728MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_56_QF_UFDTLIA.smt2                |  599.623s | 238.0MiB| timeout | 0 |  |  |
|3106_1c933134166dbad31f79_38_QF_UFDTNIA.smt2                 |  599.629s | 478.0MiB| timeout | 0 |  |  |
|93493_798593962ee29ad45ac8_52_QF_UFDTLIA.smt2                |  599.634s | 225.0MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_57_QF_UFLIA.smt2                  |  599.636s | 149.0MiB| timeout | 0 |  |  |
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFLIA.smt2      |  599.643s | 268.0MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_57_QF_UFNIA.smt2                  |  599.648s | 110.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTLIA.smt2    |  599.649s | 746.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFLIA.smt2      |  599.653s | 970.0MiB| timeout | 0 |  |  |
|93493_798593962ee29ad45ac8_52_QF_UFNIA.smt2                  |  599.654s | 340.0MiB| timeout | 0 |  |  |
|93493_798593962ee29ad45ac8_52_QF_UFLIA.smt2                  |  599.656s | 309.0MiB| timeout | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                  |  599.674s | 621.0MiB| timeout | 0 |  |  |
|65782_cd31513fdcd15701933b_5_QF_UFDTLIA.smt2                 |  599.688s | 273.0MiB| timeout | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                |  599.692s | 706.0MiB| timeout | 0 |  |  |
|38347_525a1ca0331f2bcbf520_54_QF_UFDTLIA.smt2                |  599.697s | 2127.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_2_UFLIA.smt2                      |  599.699s | 300.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_3_UFLIA.smt2                      |  599.708s | 687.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFNIA.smt2      |  599.726s | 87.024MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_75_QF_UFLIA.smt2                  |  599.727s | 1241.0MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_74_QF_UFDTNIA.smt2                |  599.729s | 192.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFLIA.smt2      |  599.733s | 2059.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_32_QF_UFLIA.smt2                    |  599.738s | 396.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTLIA.smt2    |  599.745s | 969.0MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_76_QF_UFNIA.smt2                  |  599.757s | 1545.0MiB| timeout | 0 |  |  |
|38347_525a1ca0331f2bcbf520_54_QF_UFNIA.smt2                  |  599.770s | 357.0MiB| timeout | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_35_QF_UFNIA.smt2                  |  599.776s | 76.696MiB| timeout | 0 |  |  |
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFLIA.smt2      |  599.778s | 269.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_29_QF_UFLIA.smt2                    |  599.784s | 552.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_32_QF_UFDTLIA.smt2                  |  599.786s | 621.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTLIA.smt2    |  599.789s | 1420.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFNIA.smt2      |  599.797s | 99.384MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_75_QF_UFNIA.smt2                  |  599.803s | 632.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_1_UFDTLIA.smt2                    |  599.807s | 701.0MiB| timeout | 0 |  |  |
|65782_cd31513fdcd15701933b_5_QF_UFNIA.smt2                   |  599.809s | 98.86MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTNIA.smt2    |  599.810s | 114.0MiB| timeout | 0 |  |  |
|72658_63104dadde9c6026353f_71_QF_UFNIA.smt2                  |  599.815s | 48.34MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_74_QF_UFLIA.smt2                  |  599.816s | 580.0MiB| timeout | 0 |  |  |
|38347_525a1ca0331f2bcbf520_54_QF_UFLIA.smt2                  |  599.823s | 2235.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTLIA.smt2    |  599.831s | 1217.0MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_73_QF_UFNIA.smt2                  |  599.849s | 786.0MiB| timeout | 0 |  |  |
|72658_63104dadde9c6026353f_71_QF_UFDTLIA.smt2                |  599.851s | 404.0MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_57_QF_UFDTLIA.smt2                |  599.872s | 33.16MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_73_QF_UFLIA.smt2                  |  599.874s | 792.0MiB| timeout | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFLIA.smt2      |  599.903s | 441.0MiB| timeout | 0 |  |  |
