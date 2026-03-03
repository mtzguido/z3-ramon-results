# .

* SAT 148
* UNSAT 40
* TIMEOUT 119
* UNKNOWN 0

* UNSET 1

* ERROR 1

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: quotient_pairs=true inputs/certora
Job tag: fix_in_qp_true_certora
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 186ef6a0cd3f0fc8821795515994089cfc4e65db
Z3 branch: modgb
Z3 options: "-T:200 smt.arith.nl.grobner_quotient_pairs=true"
Z3 inputs: inputs/certora
Z3 commit message: fix unsound grobner-quotient-pair lemma: skip lc with non-integral coefficients

pdd::reduce() can introduce non-integral coefficients via leading-term
division. The quotient lemma reasoning assumed lc_comb = lc_i - lc_j
was always integer-valued, which failed when lc had non-integral coefficients.
Filter out such entries when building var_to_facts.

Co-authored-by: Copilot <223556219+Copilot@users.noreply.github.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|63058_aa742630eef64f949de269382c1f9035_25_UFNIA.smt2         |    0.133s | 22.692MiB| unsat | 0 |  |  |
|65782_cd31513fdcd15701933b_6_QF_UFDTNIA.smt2                 |    0.141s | 21.02MiB| sat | 0 |  |  |
|65782_cd31513fdcd15701933b_6_QF_UFDTLIA.smt2                 |    0.149s | 21.48MiB| sat | 0 |  |  |
|65782_cd31513fdcd15701933b_6_QF_UFNIA.smt2                   |    0.173s | 20.968MiB| sat | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_34_QF_UFDTLIA.smt2                |    0.179s | 23.492MiB| sat | 0 |  |  |
|63058_aa742630eef64f949de269382c1f9035_25_UFDTLIA.smt2       |    0.184s | 24.536MiB| unsat | 0 |  |  |
|63058_aa742630eef64f949de269382c1f9035_25_UFLIA.smt2         |    0.188s | 23.812MiB| unsat | 0 |  |  |
|3106_1c933134166dbad31f79_40_QF_UFDTNIA.smt2                 |    0.202s | 23.14MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_40_QF_UFDTLIA.smt2                 |    0.218s | 23.512MiB| sat | 0 |  |  |
|63058_aa742630eef64f949de269382c1f9035_25_UFDTNIA.smt2       |    0.232s | 23.948MiB| unsat | 0 |  |  |
|65782_cd31513fdcd15701933b_6_QF_UFLIA.smt2                   |    0.236s | 21.532MiB| sat | 0 |  |  |
|39657_2866defdd1f2434b69ab_48_QF_UFDTNIA.smt2                |    0.265s | 26.632MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_40_QF_UFLIA.smt2                   |    0.267s | 24.084MiB| sat | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_34_QF_UFLIA.smt2                  |    0.350s | 25.568MiB| sat | 0 |  |  |
|65782_cd31513fdcd15701933b_7_QF_UFLIA.smt2                   |    0.448s | 25.704MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_40_QF_UFNIA.smt2                   |    0.478s | 24.06MiB| sat | 0 |  |  |
|65782_cd31513fdcd15701933b_7_QF_UFDTLIA.smt2                 |    0.494s | 25.28MiB| sat | 0 |  |  |
|65782_cd31513fdcd15701933b_8_QF_UFLIA.smt2                   |    0.532s | 26.588MiB| sat | 0 |  |  |
|65782_cd31513fdcd15701933b_8_QF_UFDTLIA.smt2                 |    0.540s | 26.664MiB| sat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFDTLIA.smt2    |    0.549s | 33.596MiB| sat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFDTNIA.smt2    |    0.554s | 28.184MiB| sat | 0 |  |  |
|38347_092cc73601c78e45f4f9_58_QF_UFDTNIA.smt2                |    0.570s | 27.788MiB| sat | 0 |  |  |
|41958_45c688a4814eb926c254_60_QF_UFDTNIA.smt2                |    0.579s | 29.748MiB| sat | 0 |  |  |
|72771_f9d228efc97cf1458e38_64_QF_UFDTNIA.smt2                |    0.658s | 27.136MiB| sat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFDTLIA.smt2    |    0.678s | 30.812MiB| sat | 0 |  |  |
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                |    0.700s | 29.084MiB| sat | 0 |  |  |
|41958_45c688a4814eb926c254_59_QF_UFDTNIA.smt2                |    0.720s | 30.496MiB| sat | 0 |  |  |
|65782_cd31513fdcd15701933b_8_QF_UFNIA.smt2                   |    0.779s | 24.624MiB| sat | 0 |  |  |
|38347_092cc73601c78e45f4f9_58_QF_UFDTLIA.smt2                |    0.801s | 28.036MiB| sat | 0 |  |  |
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                |    0.808s | 34.452MiB| sat | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_35_QF_UFDTLIA.smt2                |    0.866s | 26.68MiB| unsat | 0 |  |  |
|83314_a702bf8b823398c9e37a_0_UFDTNIA.smt2                    |    0.885s | 27.516MiB| sat | 0 |  |  |
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                  |    0.921s | 27.58MiB| unsat | 0 |  |  |
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                  |    1.287s | 34.412MiB| sat | 0 |  |  |
|65782_cd31513fdcd15701933b_8_QF_UFDTNIA.smt2                 |    1.320s | 24.98MiB| sat | 0 |  |  |
|83314_a702bf8b823398c9e37a_0_UFNIA.smt2                      |    1.405s | 26.156MiB| sat | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_35_QF_UFLIA.smt2                  |    1.422s | 36.1MiB| unsat | 0 |  |  |
|41958_45c688a4814eb926c254_60_QF_UFDTLIA.smt2                |    1.447s | 35.448MiB| sat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                |    1.482s | 23.292MiB| unsat | 0 |  |  |
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                |    1.493s | 28.164MiB| unsat | 0 |  |  |
|41958_45c688a4814eb926c254_59_QF_UFDTLIA.smt2                |    1.535s | 37.944MiB| sat | 0 |  |  |
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                |    1.709s | 36.384MiB| sat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFDTNIA.smt2    |    1.712s | 30.104MiB| sat | 0 |  |  |
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                  |    1.782s | 31.916MiB| sat | 0 |  |  |
|39657_2866defdd1f2434b69ab_47_QF_UFDTNIA.smt2                |    1.878s | 27.532MiB| sat | 0 |  |  |
|38347_092cc73601c78e45f4f9_58_QF_UFNIA.smt2                  |    1.957s | 32.02MiB| sat | 0 |  |  |
|44289_4066055e0f64d96da11a_14_QF_UFDTNIA.smt2                |    2.014s | 43.556MiB| sat | 0 |  |  |
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                  |    2.193s | 40.108MiB| sat | 0 |  |  |
|38347_092cc73601c78e45f4f9_58_QF_UFLIA.smt2                  |    2.382s | 31.212MiB| sat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                  |    2.439s | 23.42MiB| unsat | 0 |  |  |
|44289_4066055e0f64d96da11a_14_QF_UFDTLIA.smt2                |    2.617s | 43.648MiB| sat | 0 |  |  |
|44289_e5a2e5c780236919ee6a_18_QF_UFDTLIA.smt2                |    2.790s | 60.276MiB| sat | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFDTNIA.smt2    |    2.822s | 58.664MiB| sat | 0 |  |  |
|39657_1c7158801cd59dc13f05_46_QF_UFDTLIA.smt2                |    2.851s | 55.224MiB| sat | 0 |  |  |
|72658_63104dadde9c6026353f_70_QF_UFDTLIA.smt2                |    2.863s | 55.544MiB| sat | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTNIA.smt2    |    2.954s | 39.44MiB| sat | 0 |  |  |
|63058_55d6bef5390186355f11_26_QF_UFDTLIA.smt2                |    3.121s | 49.388MiB| sat | 0 |  |  |
|39657_2866defdd1f2434b69ab_47_QF_UFNIA.smt2                  |    3.125s | 34.956MiB| sat | 0 |  |  |
|41958_32933c5a1384696720a2_61_QF_UFNIA.smt2                  |    3.196s | 28.316MiB| sat | 0 |  |  |
|44289_e5a2e5c780236919ee6a_18_QF_UFDTNIA.smt2                |    3.257s | 61.208MiB| sat | 0 |  |  |
|44289_e5a2e5c780236919ee6a_17_QF_UFDTNIA.smt2                |    3.389s | 60.104MiB| sat | 0 |  |  |
|65782_cd31513fdcd15701933b_7_QF_UFNIA.smt2                   |    3.516s | 26.368MiB| unsat | 0 |  |  |
|38347_092cc73601c78e45f4f9_56_QF_UFDTNIA.smt2                |    3.540s | 48.52MiB| sat | 0 |  |  |
|41958_32933c5a1384696720a2_63_QF_UFDTLIA.smt2                |    3.838s | 33.072MiB| sat | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFNIA.smt2      |    3.935s | 43.588MiB| sat | 0 |  |  |
|44289_e5a2e5c780236919ee6a_17_QF_UFDTLIA.smt2                |    4.099s | 60.56MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_41_QF_UFDTLIA.smt2                 |    4.126s | 39.644MiB| sat | 0 |  |  |
|39657_1c7158801cd59dc13f05_44_QF_UFDTLIA.smt2                |    4.251s | 55.28MiB| sat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_22_QF_UFDTLIA.smt2                |    4.333s | 45.572MiB| sat | 0 |  |  |
|65782_cd31513fdcd15701933b_7_QF_UFDTNIA.smt2                 |    5.093s | 26.068MiB| unsat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_23_QF_UFDTLIA.smt2                |    5.096s | 66.472MiB| sat | 0 |  |  |
|66603_accdadf23a1cf70ae043_72_QF_UFDTNIA.smt2                |    5.151s | 103.0MiB| unsat | 0 |  |  |
|3106_1c933134166dbad31f79_41_QF_UFDTNIA.smt2                 |    5.173s | 37.364MiB| sat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_24_QF_UFDTNIA.smt2                |    5.203s | 63.412MiB| sat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                |    5.293s | 66.908MiB| unsat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                  |    5.387s | 31.724MiB| unsat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_24_QF_UFDTLIA.smt2                |    5.389s | 64.12MiB| sat | 0 |  |  |
|39657_1c7158801cd59dc13f05_45_QF_UFDTLIA.smt2                |    5.405s | 52.972MiB| sat | 0 |  |  |
|39657_2866defdd1f2434b69ab_48_QF_UFDTLIA.smt2                |    6.033s | 30.56MiB| sat | 0 |  |  |
|41958_45c688a4814eb926c254_60_QF_UFNIA.smt2                  |    6.055s | 49.26MiB| sat | 0 |  |  |
|66603_accdadf23a1cf70ae043_72_QF_UFDTLIA.smt2                |    6.126s | 105.0MiB| unsat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_22_QF_UFDTNIA.smt2                |    6.190s | 45.84MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_41_QF_UFLIA.smt2                   |    6.196s | 51.784MiB| sat | 0 |  |  |
|41958_32933c5a1384696720a2_63_QF_UFLIA.smt2                  |    6.365s | 34.584MiB| sat | 0 |  |  |
|41958_45c688a4814eb926c254_60_QF_UFLIA.smt2                  |    6.708s | 57.452MiB| sat | 0 |  |  |
|44289_4066055e0f64d96da11a_15_QF_UFDTNIA.smt2                |    6.954s | 82.544MiB| sat | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTNIA.smt2    |    6.974s | 47.276MiB| sat | 0 |  |  |
|72771_f9d228efc97cf1458e38_64_QF_UFDTLIA.smt2                |    7.697s | 31.488MiB| sat | 0 |  |  |
|41958_45c688a4814eb926c254_59_QF_UFLIA.smt2                  |    8.588s | 101.0MiB| sat | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFNIA.smt2      |    8.608s | 44.804MiB| sat | 0 |  |  |
|44289_4066055e0f64d96da11a_15_QF_UFDTLIA.smt2                |    9.307s | 83.28MiB| sat | 0 |  |  |
|940_590f27b1c3c800d3243e_31_QF_UFNIA.smt2                    |    9.822s | 66.012MiB| sat | 0 |  |  |
|39657_2866defdd1f2434b69ab_47_QF_UFDTLIA.smt2                |   10.098s | 31.664MiB| sat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                |   10.912s | 66.732MiB| unsat | 0 |  |  |
|39657_1c7158801cd59dc13f05_45_QF_UFLIA.smt2                  |   11.155s | 68.84MiB| sat | 0 |  |  |
|44289_e5a2e5c780236919ee6a_18_QF_UFLIA.smt2                  |   11.756s | 88.656MiB| sat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                  |   11.846s | 73.068MiB| unsat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_23_QF_UFDTNIA.smt2                |   13.233s | 52.04MiB| sat | 0 |  |  |
|41958_45c688a4814eb926c254_59_QF_UFNIA.smt2                  |   14.083s | 73.1MiB| sat | 0 |  |  |
|41958_32933c5a1384696720a2_62_QF_UFLIA.smt2                  |   14.773s | 43.848MiB| sat | 0 |  |  |
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFDTLIA.smt2    |   15.045s | 129.0MiB| sat | 0 |  |  |
|66603_accdadf23a1cf70ae043_73_QF_UFDTNIA.smt2                |   15.194s | 102.0MiB| sat | 0 |  |  |
|66603_accdadf23a1cf70ae043_76_QF_UFDTNIA.smt2                |   15.448s | 144.0MiB| unsat | 0 |  |  |
|38347_092cc73601c78e45f4f9_56_QF_UFNIA.smt2                  |   15.663s | 66.396MiB| sat | 0 |  |  |
|83314_a702bf8b823398c9e37a_1_UFNIA.smt2                      |   16.022s | 44.288MiB| sat | 0 |  |  |
|39657_2866defdd1f2434b69ab_48_QF_UFNIA.smt2                  |   16.471s | 41.3MiB| sat | 0 |  |  |
|41958_32933c5a1384696720a2_62_QF_UFDTLIA.smt2                |   17.065s | 52.912MiB| sat | 0 |  |  |
|44289_e5a2e5c780236919ee6a_17_QF_UFLIA.smt2                  |   17.492s | 90.996MiB| sat | 0 |  |  |
|44289_e5a2e5c780236919ee6a_18_QF_UFNIA.smt2                  |   17.814s | 99.0MiB| sat | 0 |  |  |
|940_590f27b1c3c800d3243e_31_QF_UFDTNIA.smt2                  |   17.870s | 64.832MiB| sat | 0 |  |  |
|39657_1c7158801cd59dc13f05_44_QF_UFLIA.smt2                  |   18.262s | 66.076MiB| sat | 0 |  |  |
|44289_4066055e0f64d96da11a_14_QF_UFNIA.smt2                  |   19.056s | 105.0MiB| sat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                |   19.429s | 34.744MiB| unsat | 0 |  |  |
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFDTLIA.smt2     |   20.405s | 81.216MiB| sat | 0 |  |  |
|39657_1c7158801cd59dc13f05_45_QF_UFDTNIA.smt2                |   20.682s | 60.872MiB| sat | 0 |  |  |
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFDTNIA.smt2     |   20.755s | 82.96MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_39_QF_UFDTLIA.smt2                 |   21.805s | 79.872MiB| sat | 0 |  |  |
|72658_63104dadde9c6026353f_70_QF_UFLIA.smt2                  |   22.243s | 73.952MiB| sat | 0 |  |  |
|39657_1c7158801cd59dc13f05_44_QF_UFDTNIA.smt2                |   22.477s | 64.548MiB| sat | 0 |  |  |
|66603_accdadf23a1cf70ae043_72_QF_UFLIA.smt2                  |   23.093s | 540.0MiB| unsat | 0 |  |  |
|38347_092cc73601c78e45f4f9_55_QF_UFDTLIA.smt2                |   23.323s | 24.016MiB| unsat | 0 |  |  |
|66603_accdadf23a1cf70ae043_74_QF_UFDTLIA.smt2                |   25.039s | 129.0MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_41_QF_UFNIA.smt2                   |   25.406s | 52.22MiB| sat | 0 |  |  |
|66603_accdadf23a1cf70ae043_75_QF_UFDTLIA.smt2                |   27.392s | 130.0MiB| sat | 0 |  |  |
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFDTLIA.smt2    |   28.119s | 81.944MiB| sat | 0 |  |  |
|63058_55d6bef5390186355f11_26_QF_UFDTNIA.smt2                |   30.796s | 64.936MiB| sat | 0 |  |  |
|39657_1c7158801cd59dc13f05_46_QF_UFLIA.smt2                  |   33.905s | 68.64MiB| sat | 0 |  |  |
|72658_63104dadde9c6026353f_70_QF_UFDTNIA.smt2                |   34.388s | 38.072MiB| sat | 0 |  |  |
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFLIA.smt2      |   35.263s | 125.0MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_39_QF_UFDTNIA.smt2                 |   36.977s | 94.676MiB| sat | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTNIA.smt2    |   37.028s | 63.788MiB| sat | 0 |  |  |
|39657_2866defdd1f2434b69ab_48_QF_UFLIA.smt2                  |   39.426s | 44.288MiB| sat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFLIA.smt2      |   40.903s | 150.0MiB| sat | 0 |  |  |
|66603_accdadf23a1cf70ae043_76_QF_UFDTLIA.smt2                |   42.420s | 234.0MiB| unsat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_22_QF_UFLIA.smt2                  |   43.101s | 166.0MiB| sat | 0 |  |  |
|72771_f9d228efc97cf1458e38_64_QF_UFNIA.smt2                  |   43.405s | 45.468MiB| sat | 0 |  |  |
|83314_a702bf8b823398c9e37a_1_UFDTNIA.smt2                    |   43.461s | 49.8MiB| sat | 0 |  |  |
|940_590f27b1c3c800d3243e_29_QF_UFDTNIA.smt2                  |   43.618s | 222.0MiB| sat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFLIA.smt2      |   43.744s | 118.0MiB| sat | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_36_QF_UFLIA.smt2                  |   45.511s | 287.0MiB| unsat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_23_QF_UFLIA.smt2                  |   47.064s | 190.0MiB| sat | 0 |  |  |
|30078_f817a923328f75af7e60_27_QF_UFDTNIA.smt2                |   47.098s | 131.0MiB| unsat | 0 |  |  |
|41958_32933c5a1384696720a2_63_QF_UFNIA.smt2                  |   49.019s | 32.144MiB| unset | 139 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFDTLIA.smt2    |   50.085s | 93.328MiB| sat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                  |   52.173s | 37.708MiB| unsat | 0 |  |  |
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFNIA.smt2      |   52.351s | 143.0MiB| sat | 0 |  |  |
|44289_4066055e0f64d96da11a_14_QF_UFLIA.smt2                  |   52.727s | 114.0MiB| sat | 0 |  |  |
|83314_a702bf8b823398c9e37a_0_UFDTLIA.smt2                    |   53.714s | 144.0MiB| sat | 0 |  |  |
|72771_f9d228efc97cf1458e38_64_QF_UFLIA.smt2                  |   56.047s | 54.72MiB| sat | 0 |  |  |
|39657_1c7158801cd59dc13f05_46_QF_UFDTNIA.smt2                |   57.589s | 63.62MiB| sat | 0 |  |  |
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFDTNIA.smt2    |   57.956s | 76.34MiB| sat | 0 |  |  |
|940_590f27b1c3c800d3243e_31_QF_UFDTLIA.smt2                  |   59.016s | 152.0MiB| sat | 0 |  |  |
|63058_55d6bef5390186355f11_26_QF_UFNIA.smt2                  |   60.399s | 219.0MiB| sat | 0 |  |  |
|39657_2866defdd1f2434b69ab_47_QF_UFLIA.smt2                  |   62.508s | 49.652MiB| sat | 0 |  |  |
|940_590f27b1c3c800d3243e_32_QF_UFNIA.smt2                    |   66.473s | 206.0MiB| sat | 0 |  |  |
|39657_1c7158801cd59dc13f05_45_QF_UFNIA.smt2                  |   69.603s | 94.156MiB| sat | 0 |  |  |
|30078_f817a923328f75af7e60_28_QF_UFDTNIA.smt2                |   75.131s | 139.0MiB| unsat | 0 |  |  |
|30078_f817a923328f75af7e60_27_QF_UFNIA.smt2                  |   75.753s | 422.0MiB| unsat | 0 |  |  |
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFNIA.smt2       |   76.104s | 129.0MiB| sat | 0 |  |  |
|940_590f27b1c3c800d3243e_33_QF_UFNIA.smt2                    |   76.872s | 488.0MiB| sat | 0 |  |  |
|30078_f817a923328f75af7e60_27_QF_UFDTLIA.smt2                |   77.007s | 150.0MiB| unsat | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFLIA.smt2      |   80.082s | 275.0MiB| sat | 0 |  |  |
|63058_55d6bef5390186355f11_26_QF_UFLIA.smt2                  |   84.253s | 216.0MiB| sat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                |   85.394s | 37.492MiB| unsat | 0 |  |  |
|3106_1c933134166dbad31f79_39_QF_UFLIA.smt2                   |   85.612s | 135.0MiB| sat | 0 |  |  |
|940_590f27b1c3c800d3243e_32_QF_UFDTNIA.smt2                  |   89.874s | 265.0MiB| sat | 0 |  |  |
|940_590f27b1c3c800d3243e_30_QF_UFNIA.smt2                    |   91.030s | 325.0MiB| sat | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFDTNIA.smt2    |   91.402s | 96.868MiB| unsat | 0 |  |  |
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFDTNIA.smt2    |   91.484s | 178.0MiB| sat | 0 |  |  |
|66603_accdadf23a1cf70ae043_76_QF_UFLIA.smt2                  |   95.080s | 1737.0MiB| unsat | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFDTLIA.smt2    |  105.813s | 196.0MiB| unsat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFNIA.smt2      |  114.490s | 231.0MiB| sat | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFNIA.smt2      |  116.818s | 287.0MiB| sat | 0 |  |  |
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFNIA.smt2      |  122.803s | 177.0MiB| sat | 0 |  |  |
|30078_f817a923328f75af7e60_28_QF_UFDTLIA.smt2                |  127.601s | 161.0MiB| unsat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFNIA.smt2      |  128.015s | 208.0MiB| sat | 0 |  |  |
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFDTLIA.smt2    |  130.248s | 135.0MiB| sat | 0 |  |  |
|41958_32933c5a1384696720a2_63_QF_UFDTNIA.smt2                |  131.520s | 34.0MiB| unsat | 0 |  |  |
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFDTNIA.smt2    |  138.120s | 120.0MiB| sat | 0 |  |  |
|940_590f27b1c3c800d3243e_29_QF_UFNIA.smt2                    |  144.077s | 250.0MiB| sat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_24_QF_UFLIA.smt2                  |  144.599s | 232.0MiB| sat | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_36_QF_UFDTLIA.smt2                |  162.547s | 423.0MiB| unsat | 0 |  |  |
|30078_f817a923328f75af7e60_28_QF_UFNIA.smt2                  |  168.485s | 426.0MiB| unsat | 0 |  |  |
|41958_32933c5a1384696720a2_62_QF_UFNIA.smt2                  |  170.029s | 37.792MiB| unsat | 0 |  |  |
|93493_5990a6bf5f2740164f77_50_QF_UFDTLIA.smt2                |  171.960s | 236.0MiB| sat | 0 |  |  |
|30078_f817a923328f75af7e60_28_QF_UFLIA.smt2                  |  183.805s | 481.0MiB| unsat | 0 |  |  |
|44289_e5a2e5c780236919ee6a_17_QF_UFNIA.smt2                  |  189.420s | 126.0MiB| sat | 0 |  |  |
|41958_32933c5a1384696720a2_61_QF_UFDTLIA.smt2                |  194.105s | 119.0MiB| sat | 0 |  |  |
|83314_a702bf8b823398c9e37a_3_UFDTLIA.smt2                    |  195.917s | 857.0MiB| unsat | 0 |  |  |
|38347_092cc73601c78e45f4f9_57_QF_UFLIA.smt2                  |  200.015s | 37.564MiB| timeout | 0 |  |  |
|72658_63104dadde9c6026353f_71_QF_UFDTNIA.smt2                |  200.021s | 47.904MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_55_QF_UFDTNIA.smt2                |  200.021s | 24.604MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_57_QF_UFDTLIA.smt2                |  200.021s | 30.092MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_55_QF_UFNIA.smt2                  |  200.022s | 26.092MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFNIA.smt2      |  200.023s | 95.256MiB| timeout | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_36_QF_UFDTNIA.smt2                |  200.029s | 63.232MiB| timeout | 0 |  |  |
|65782_cd31513fdcd15701933b_5_QF_UFNIA.smt2                   |  200.029s | 66.816MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_3_UFNIA.smt2                      |  200.029s | 59.26MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTNIA.smt2    |  200.031s | 72.12MiB| timeout | 0 |  |  |
|52759_b3ecd2335fd16ec2eee2_9_UFDTNIA.smt2                    |  200.031s | 46.7MiB| timeout | 0 |  |  |
|65782_cd31513fdcd15701933b_5_QF_UFDTNIA.smt2                 |  200.031s | 57.036MiB| timeout | 0 |  |  |
|52759_b3ecd2335fd16ec2eee2_9_UFNIA.smt2                      |  200.033s | 64.148MiB| timeout | 0 |  |  |
|41958_32933c5a1384696720a2_61_QF_UFDTNIA.smt2                |  200.033s | 43.036MiB| timeout | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_34_QF_UFDTNIA.smt2                |  200.034s | 57.912MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_55_QF_UFLIA.smt2                  |  200.035s | 35.976MiB| timeout | 0 |  |  |
|3106_1c933134166dbad31f79_39_QF_UFNIA.smt2                   |  200.036s | 178.0MiB| timeout | 0 |  |  |
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFLIA.smt2       |  200.036s | 133.0MiB| timeout | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_24_QF_UFNIA.smt2                  |  200.037s | 230.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_4_UFDTNIA.smt2                    |  200.039s | 183.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFNIA.smt2      |  200.039s | 96.36MiB| timeout | 0 |  |  |
|93493_5990a6bf5f2740164f77_50_QF_UFLIA.smt2                  |  200.040s | 291.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_3_UFDTNIA.smt2                    |  200.041s | 58.152MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_75_QF_UFDTNIA.smt2                |  200.042s | 184.0MiB| timeout | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_35_QF_UFNIA.smt2                  |  200.043s | 68.012MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_57_QF_UFDTNIA.smt2                |  200.043s | 28.532MiB| timeout | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_34_QF_UFNIA.smt2                  |  200.045s | 56.284MiB| timeout | 0 |  |  |
|39657_1c7158801cd59dc13f05_46_QF_UFNIA.smt2                  |  200.045s | 101.0MiB| timeout | 0 |  |  |
|72658_63104dadde9c6026353f_71_QF_UFNIA.smt2                  |  200.045s | 48.928MiB| timeout | 0 |  |  |
|72658_63104dadde9c6026353f_71_QF_UFDTLIA.smt2                |  200.045s | 232.0MiB| timeout | 0 |  |  |
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFDTLIA.smt2    |  200.046s | 234.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2      |  200.047s | 110.0MiB| timeout | 0 |  |  |
|41958_32933c5a1384696720a2_61_QF_UFLIA.smt2                  |  200.047s | 86.284MiB| timeout | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_23_QF_UFNIA.smt2                  |  200.048s | 185.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_2_UFNIA.smt2                      |  200.048s | 192.0MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_56_QF_UFLIA.smt2                  |  200.049s | 181.0MiB| timeout | 0 |  |  |
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFLIA.smt2      |  200.049s | 162.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTNIA.smt2    |  200.049s | 92.82MiB| timeout | 0 |  |  |
|41958_32933c5a1384696720a2_62_QF_UFDTNIA.smt2                |  200.049s | 49.164MiB| timeout | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_35_QF_UFDTNIA.smt2                |  200.049s | 54.68MiB| timeout | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_36_QF_UFNIA.smt2                  |  200.050s | 67.864MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_56_QF_UFDTLIA.smt2                |  200.050s | 190.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_0_UFLIA.smt2                      |  200.050s | 157.0MiB| timeout | 0 |  |  |
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFLIA.smt2      |  200.051s | 119.0MiB| timeout | 0 |  |  |
|52759_b3ecd2335fd16ec2eee2_9_UFLIA.smt2                      |  200.051s | 64.024MiB| timeout | 0 |  |  |
|65782_cd31513fdcd15701933b_5_QF_UFLIA.smt2                   |  200.051s | 176.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_2_UFDTNIA.smt2                    |  200.052s | 180.0MiB| timeout | 0 |  |  |
|39657_1c7158801cd59dc13f05_44_QF_UFNIA.smt2                  |  200.052s | 117.0MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_73_QF_UFDTLIA.smt2                |  200.052s | 293.0MiB| timeout | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_22_QF_UFNIA.smt2                  |  200.052s | 206.0MiB| timeout | 0 |  |  |
|65782_cd31513fdcd15701933b_5_QF_UFDTLIA.smt2                 |  200.055s | 144.0MiB| timeout | 0 |  |  |
|93493_798593962ee29ad45ac8_52_QF_UFNIA.smt2                  |  200.055s | 195.0MiB| timeout | 0 |  |  |
|52759_b3ecd2335fd16ec2eee2_9_UFDTLIA.smt2                    |  200.055s | 65.792MiB| timeout | 0 |  |  |
|93493_798593962ee29ad45ac8_52_QF_UFLIA.smt2                  |  200.055s | 256.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_2_UFDTLIA.smt2                    |  200.056s | 202.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_31_QF_UFLIA.smt2                    |  200.057s | 163.0MiB| timeout | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                  |  200.057s | 154.0MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_57_QF_UFNIA.smt2                  |  200.057s | 41.512MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_2_UFLIA.smt2                      |  200.058s | 201.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_33_QF_UFDTNIA.smt2                  |  200.059s | 265.0MiB| timeout | 0 |  |  |
|93493_798593962ee29ad45ac8_52_QF_UFDTLIA.smt2                |  200.060s | 205.0MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_74_QF_UFDTNIA.smt2                |  200.060s | 186.0MiB| timeout | 0 |  |  |
|93493_5990a6bf5f2740164f77_50_QF_UFDTNIA.smt2                |  200.062s | 226.0MiB| timeout | 0 |  |  |
|93493_798593962ee29ad45ac8_52_QF_UFDTNIA.smt2                |  200.062s | 149.0MiB| timeout | 0 |  |  |
|72658_63104dadde9c6026353f_70_QF_UFNIA.smt2                  |  200.063s | 64.12MiB| timeout | 0 |  |  |
|3106_1c933134166dbad31f79_38_QF_UFDTNIA.smt2                 |  200.066s | 394.0MiB| timeout | 0 |  |  |
|3106_1c933134166dbad31f79_38_QF_UFDTLIA.smt2                 |  200.066s | 286.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_3_UFLIA.smt2                      |  200.067s | 432.0MiB| timeout | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFNIA.smt2      |  200.067s | 236.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_1_UFLIA.smt2                      |  200.068s | 275.0MiB| timeout | 0 |  |  |
|72658_63104dadde9c6026353f_71_QF_UFLIA.smt2                  |  200.069s | 193.0MiB| timeout | 0 |  |  |
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFNIA.smt2      |  200.070s | 255.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_30_QF_UFLIA.smt2                    |  200.071s | 351.0MiB| timeout | 0 |  |  |
|38347_525a1ca0331f2bcbf520_54_QF_UFNIA.smt2                  |  200.071s | 360.0MiB| timeout | 0 |  |  |
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFNIA.smt2      |  200.072s | 156.0MiB| timeout | 0 |  |  |
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFLIA.smt2      |  200.073s | 265.0MiB| timeout | 0 |  |  |
|93493_5990a6bf5f2740164f77_50_QF_UFNIA.smt2                  |  200.073s | 329.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_29_QF_UFLIA.smt2                    |  200.074s | 475.0MiB| timeout | 0 |  |  |
|38347_525a1ca0331f2bcbf520_54_QF_UFDTNIA.smt2                |  200.074s | 195.0MiB| timeout | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFLIA.smt2      |  200.076s | 407.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_29_QF_UFDTLIA.smt2                  |  200.078s | 371.0MiB| timeout | 0 |  |  |
|30078_f817a923328f75af7e60_27_QF_UFLIA.smt2                  |  200.078s | 461.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_4_UFNIA.smt2                      |  200.078s | 205.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFLIA.smt2      |  200.080s | 518.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_33_QF_UFLIA.smt2                    |  200.081s | 395.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_33_QF_UFDTLIA.smt2                  |  200.081s | 440.0MiB| timeout | 0 |  |  |
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFDTNIA.smt2    |  200.081s | 218.0MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_74_QF_UFNIA.smt2                  |  200.084s | 646.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_32_QF_UFLIA.smt2                    |  200.086s | 355.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_30_QF_UFDTNIA.smt2                  |  200.086s | 212.0MiB| timeout | 0 |  |  |
|44289_4066055e0f64d96da11a_15_QF_UFNIA.smt2                  |  200.086s | 498.0MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                  |  200.093s | 578.0MiB| timeout | 0 |  |  |
|44289_4066055e0f64d96da11a_15_QF_UFLIA.smt2                  |  200.095s | 408.0MiB| timeout | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                |  200.095s | 612.0MiB| timeout | 0 |  |  |
|3106_1c933134166dbad31f79_38_QF_UFLIA.smt2                   |  200.096s | 573.0MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_73_QF_UFLIA.smt2                  |  200.097s | 598.0MiB| timeout | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                  |  200.098s | 516.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_4_UFLIA.smt2                      |  200.101s | 655.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_30_QF_UFDTLIA.smt2                  |  200.101s | 411.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTLIA.smt2    |  200.101s | 715.0MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_75_QF_UFNIA.smt2                  |  200.103s | 638.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTLIA.smt2    |  200.103s | 763.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_4_UFDTLIA.smt2                    |  200.108s | 698.0MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_73_QF_UFNIA.smt2                  |  200.109s | 482.0MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_74_QF_UFLIA.smt2                  |  200.109s | 588.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTLIA.smt2    |  200.118s | 686.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_1_UFDTLIA.smt2                    |  200.118s | 519.0MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_75_QF_UFLIA.smt2                  |  200.120s | 1060.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_32_QF_UFDTLIA.smt2                  |  200.125s | 526.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFLIA.smt2      |  200.135s | 763.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTLIA.smt2    |  200.137s | 1179.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFLIA.smt2      |  200.148s | 821.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFLIA.smt2      |  200.150s | 1355.0MiB| timeout | 0 |  |  |
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                   |  200.157s | 1155.0MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_76_QF_UFNIA.smt2                  |  200.162s | 1565.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTLIA.smt2    |  200.186s | 1430.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFLIA.smt2      |  200.201s | 1925.0MiB| timeout | 0 |  |  |
|38347_525a1ca0331f2bcbf520_54_QF_UFDTLIA.smt2                |  200.224s | 1949.0MiB| timeout | 0 |  |  |
|38347_525a1ca0331f2bcbf520_54_QF_UFLIA.smt2                  |  200.247s | 2147.0MiB| timeout | 0 |  |  |
