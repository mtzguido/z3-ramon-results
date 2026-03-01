# .

* SAT 146
* UNSAT 40
* TIMEOUT 122
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: quotient_pairs=true inputs/certora
Job tag: qp_true_certora
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 9b30560b617f35b45d3704d99dce09c021636fca
Z3 branch: modgb
Z3 options: "-T:200 smt.arith.nl.grobner_quotient_pairs=true"
Z3 inputs: inputs/certora
Z3 commit message: nla: add quotient reasoning for equation combinations

Extend grobner quotient propagation to combine pairs and triples
of equations sharing a nonlinear variable. When equations of the
form v*lc_i + r_i = 0 share variable v, their linear combinations
produce v*lc_comb + r_comb = 0. If |v| > |r_comb| > 0 and v does
not divide r_comb, generate a conflict lemma.

This handles mod arithmetic patterns like:
  (mod (- x y) m) = 0 AND (mod x m) != (mod y m)
where the three mod expansions produce equations sharing m as
nonlinear factor, and combining them yields m*(q2-q1+q3) = r2-r3
with |r2-r3| < m, forcing r2 = r3 (contradiction).

Co-authored-by: Copilot <223556219+Copilot@users.noreply.github.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|65782_cd31513fdcd15701933b_6_QF_UFDTLIA.smt2                 |    0.106s | 21.492MiB| sat | 0 |  |  |
|63058_aa742630eef64f949de269382c1f9035_25_UFNIA.smt2         |    0.116s | 22.792MiB| unsat | 0 |  |  |
|65782_cd31513fdcd15701933b_6_QF_UFLIA.smt2                   |    0.136s | 21.536MiB| sat | 0 |  |  |
|65782_cd31513fdcd15701933b_6_QF_UFNIA.smt2                   |    0.151s | 21.108MiB| sat | 0 |  |  |
|65782_cd31513fdcd15701933b_6_QF_UFDTNIA.smt2                 |    0.167s | 21.02MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_40_QF_UFDTLIA.smt2                 |    0.175s | 23.456MiB| sat | 0 |  |  |
|63058_aa742630eef64f949de269382c1f9035_25_UFLIA.smt2         |    0.181s | 23.808MiB| unsat | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_34_QF_UFDTLIA.smt2                |    0.197s | 23.48MiB| sat | 0 |  |  |
|63058_aa742630eef64f949de269382c1f9035_25_UFDTNIA.smt2       |    0.207s | 23.968MiB| unsat | 0 |  |  |
|63058_aa742630eef64f949de269382c1f9035_25_UFDTLIA.smt2       |    0.220s | 24.584MiB| unsat | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_34_QF_UFLIA.smt2                  |    0.221s | 25.84MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_40_QF_UFLIA.smt2                   |    0.226s | 24.08MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_40_QF_UFDTNIA.smt2                 |    0.274s | 23.036MiB| sat | 0 |  |  |
|39657_2866defdd1f2434b69ab_48_QF_UFDTNIA.smt2                |    0.306s | 26.728MiB| sat | 0 |  |  |
|65782_cd31513fdcd15701933b_7_QF_UFLIA.smt2                   |    0.383s | 25.732MiB| sat | 0 |  |  |
|38347_092cc73601c78e45f4f9_58_QF_UFDTNIA.smt2                |    0.476s | 27.716MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_40_QF_UFNIA.smt2                   |    0.478s | 24.048MiB| sat | 0 |  |  |
|72771_f9d228efc97cf1458e38_64_QF_UFDTNIA.smt2                |    0.485s | 27.048MiB| sat | 0 |  |  |
|41958_45c688a4814eb926c254_59_QF_UFDTNIA.smt2                |    0.486s | 30.544MiB| sat | 0 |  |  |
|65782_cd31513fdcd15701933b_7_QF_UFDTLIA.smt2                 |    0.518s | 25.372MiB| sat | 0 |  |  |
|38347_092cc73601c78e45f4f9_58_QF_UFDTLIA.smt2                |    0.541s | 28.036MiB| sat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFDTLIA.smt2    |    0.559s | 33.668MiB| sat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFDTNIA.smt2    |    0.573s | 28.172MiB| sat | 0 |  |  |
|65782_cd31513fdcd15701933b_8_QF_UFDTLIA.smt2                 |    0.574s | 26.464MiB| sat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFDTLIA.smt2    |    0.690s | 30.828MiB| sat | 0 |  |  |
|41958_45c688a4814eb926c254_60_QF_UFDTNIA.smt2                |    0.733s | 29.732MiB| sat | 0 |  |  |
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                |    0.735s | 29.236MiB| sat | 0 |  |  |
|65782_cd31513fdcd15701933b_8_QF_UFLIA.smt2                   |    0.797s | 26.568MiB| sat | 0 |  |  |
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                  |    0.873s | 27.668MiB| unsat | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_35_QF_UFDTLIA.smt2                |    0.921s | 26.884MiB| unsat | 0 |  |  |
|83314_a702bf8b823398c9e37a_0_UFDTNIA.smt2                    |    0.961s | 27.568MiB| sat | 0 |  |  |
|65782_cd31513fdcd15701933b_8_QF_UFNIA.smt2                   |    0.970s | 24.54MiB| sat | 0 |  |  |
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                |    1.181s | 34.612MiB| sat | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_35_QF_UFLIA.smt2                  |    1.207s | 36.336MiB| unsat | 0 |  |  |
|65782_cd31513fdcd15701933b_8_QF_UFDTNIA.smt2                 |    1.248s | 25.088MiB| sat | 0 |  |  |
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                  |    1.413s | 34.396MiB| sat | 0 |  |  |
|83314_a702bf8b823398c9e37a_0_UFNIA.smt2                      |    1.426s | 26.188MiB| sat | 0 |  |  |
|41958_45c688a4814eb926c254_60_QF_UFDTLIA.smt2                |    1.461s | 35.688MiB| sat | 0 |  |  |
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                |    1.475s | 28.344MiB| unsat | 0 |  |  |
|41958_45c688a4814eb926c254_59_QF_UFDTLIA.smt2                |    1.536s | 38.056MiB| sat | 0 |  |  |
|72658_63104dadde9c6026353f_70_QF_UFDTLIA.smt2                |    1.645s | 55.656MiB| sat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                |    1.769s | 23.252MiB| unsat | 0 |  |  |
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                |    1.863s | 36.528MiB| sat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFDTNIA.smt2    |    2.000s | 30.228MiB| sat | 0 |  |  |
|38347_092cc73601c78e45f4f9_58_QF_UFNIA.smt2                  |    2.027s | 32.124MiB| sat | 0 |  |  |
|44289_4066055e0f64d96da11a_14_QF_UFDTNIA.smt2                |    2.039s | 43.46MiB| sat | 0 |  |  |
|38347_092cc73601c78e45f4f9_58_QF_UFLIA.smt2                  |    2.097s | 31.212MiB| sat | 0 |  |  |
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                  |    2.271s | 40.108MiB| sat | 0 |  |  |
|44289_4066055e0f64d96da11a_14_QF_UFDTLIA.smt2                |    2.396s | 43.616MiB| sat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                  |    2.472s | 23.428MiB| unsat | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTNIA.smt2    |    2.756s | 39.328MiB| sat | 0 |  |  |
|39657_2866defdd1f2434b69ab_47_QF_UFDTNIA.smt2                |    2.823s | 27.54MiB| sat | 0 |  |  |
|44289_e5a2e5c780236919ee6a_18_QF_UFDTLIA.smt2                |    2.863s | 60.456MiB| sat | 0 |  |  |
|39657_1c7158801cd59dc13f05_46_QF_UFDTLIA.smt2                |    2.879s | 55.396MiB| sat | 0 |  |  |
|44289_e5a2e5c780236919ee6a_17_QF_UFDTNIA.smt2                |    2.909s | 59.912MiB| sat | 0 |  |  |
|44289_e5a2e5c780236919ee6a_17_QF_UFDTLIA.smt2                |    3.012s | 60.448MiB| sat | 0 |  |  |
|39657_1c7158801cd59dc13f05_44_QF_UFDTLIA.smt2                |    3.036s | 55.264MiB| sat | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFDTNIA.smt2    |    3.144s | 58.652MiB| sat | 0 |  |  |
|44289_e5a2e5c780236919ee6a_18_QF_UFDTNIA.smt2                |    3.348s | 61.092MiB| sat | 0 |  |  |
|63058_55d6bef5390186355f11_26_QF_UFDTLIA.smt2                |    3.368s | 49.232MiB| sat | 0 |  |  |
|39657_2866defdd1f2434b69ab_47_QF_UFNIA.smt2                  |    3.374s | 35.016MiB| sat | 0 |  |  |
|41958_32933c5a1384696720a2_61_QF_UFNIA.smt2                  |    3.423s | 28.34MiB| sat | 0 |  |  |
|65782_cd31513fdcd15701933b_7_QF_UFNIA.smt2                   |    3.498s | 26.336MiB| unsat | 0 |  |  |
|38347_092cc73601c78e45f4f9_56_QF_UFDTNIA.smt2                |    3.672s | 48.56MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_41_QF_UFDTLIA.smt2                 |    3.782s | 39.624MiB| sat | 0 |  |  |
|41958_32933c5a1384696720a2_63_QF_UFDTLIA.smt2                |    3.841s | 33.052MiB| sat | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFNIA.smt2      |    4.187s | 43.788MiB| sat | 0 |  |  |
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                  |    4.602s | 31.948MiB| sat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_22_QF_UFDTLIA.smt2                |    4.792s | 45.588MiB| sat | 0 |  |  |
|65782_cd31513fdcd15701933b_7_QF_UFDTNIA.smt2                 |    5.188s | 26.04MiB| unsat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_23_QF_UFDTLIA.smt2                |    5.278s | 66.348MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_41_QF_UFLIA.smt2                   |    5.427s | 51.772MiB| sat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_24_QF_UFDTNIA.smt2                |    5.450s | 63.384MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_41_QF_UFDTNIA.smt2                 |    5.489s | 37.364MiB| sat | 0 |  |  |
|39657_1c7158801cd59dc13f05_45_QF_UFDTLIA.smt2                |    5.534s | 53.164MiB| sat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                  |    5.616s | 31.596MiB| unsat | 0 |  |  |
|41958_45c688a4814eb926c254_60_QF_UFLIA.smt2                  |    5.621s | 57.448MiB| sat | 0 |  |  |
|39657_2866defdd1f2434b69ab_48_QF_UFDTLIA.smt2                |    6.039s | 30.564MiB| sat | 0 |  |  |
|66603_accdadf23a1cf70ae043_72_QF_UFDTNIA.smt2                |    6.184s | 103.0MiB| unsat | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTNIA.smt2    |    6.340s | 47.272MiB| sat | 0 |  |  |
|41958_45c688a4814eb926c254_60_QF_UFNIA.smt2                  |    6.417s | 49.304MiB| sat | 0 |  |  |
|41958_32933c5a1384696720a2_63_QF_UFLIA.smt2                  |    6.466s | 34.628MiB| sat | 0 |  |  |
|66603_accdadf23a1cf70ae043_72_QF_UFDTLIA.smt2                |    6.543s | 105.0MiB| unsat | 0 |  |  |
|72771_f9d228efc97cf1458e38_64_QF_UFDTLIA.smt2                |    6.597s | 31.484MiB| sat | 0 |  |  |
|44289_4066055e0f64d96da11a_15_QF_UFDTNIA.smt2                |    7.083s | 82.668MiB| sat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_24_QF_UFDTLIA.smt2                |    7.300s | 63.932MiB| sat | 0 |  |  |
|44289_e5a2e5c780236919ee6a_18_QF_UFLIA.smt2                  |    7.613s | 88.708MiB| sat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_22_QF_UFDTNIA.smt2                |    7.910s | 46.048MiB| sat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                |    8.505s | 67.008MiB| unsat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                |    8.663s | 66.844MiB| unsat | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFNIA.smt2      |    9.262s | 44.912MiB| sat | 0 |  |  |
|940_590f27b1c3c800d3243e_31_QF_UFNIA.smt2                    |    9.598s | 65.788MiB| sat | 0 |  |  |
|41958_45c688a4814eb926c254_59_QF_UFLIA.smt2                  |    9.875s | 101.0MiB| sat | 0 |  |  |
|39657_2866defdd1f2434b69ab_47_QF_UFDTLIA.smt2                |   10.133s | 31.684MiB| sat | 0 |  |  |
|44289_4066055e0f64d96da11a_15_QF_UFDTLIA.smt2                |   11.026s | 83.072MiB| sat | 0 |  |  |
|39657_1c7158801cd59dc13f05_45_QF_UFLIA.smt2                  |   11.645s | 68.516MiB| sat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                  |   11.997s | 72.988MiB| unsat | 0 |  |  |
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFDTLIA.smt2    |   12.436s | 129.0MiB| sat | 0 |  |  |
|39657_1c7158801cd59dc13f05_44_QF_UFLIA.smt2                  |   12.863s | 66.312MiB| sat | 0 |  |  |
|41958_45c688a4814eb926c254_59_QF_UFNIA.smt2                  |   13.192s | 73.152MiB| sat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_23_QF_UFDTNIA.smt2                |   13.723s | 51.968MiB| sat | 0 |  |  |
|66603_accdadf23a1cf70ae043_76_QF_UFDTNIA.smt2                |   14.329s | 144.0MiB| unsat | 0 |  |  |
|41958_32933c5a1384696720a2_62_QF_UFLIA.smt2                  |   15.479s | 43.996MiB| sat | 0 |  |  |
|38347_092cc73601c78e45f4f9_56_QF_UFNIA.smt2                  |   15.569s | 66.168MiB| sat | 0 |  |  |
|39657_2866defdd1f2434b69ab_48_QF_UFNIA.smt2                  |   16.362s | 41.292MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_39_QF_UFDTLIA.smt2                 |   16.418s | 79.936MiB| sat | 0 |  |  |
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFDTNIA.smt2     |   16.848s | 82.88MiB| sat | 0 |  |  |
|83314_a702bf8b823398c9e37a_1_UFNIA.smt2                      |   17.844s | 44.208MiB| sat | 0 |  |  |
|44289_e5a2e5c780236919ee6a_17_QF_UFLIA.smt2                  |   18.386s | 90.988MiB| sat | 0 |  |  |
|66603_accdadf23a1cf70ae043_74_QF_UFDTLIA.smt2                |   18.442s | 129.0MiB| sat | 0 |  |  |
|66603_accdadf23a1cf70ae043_73_QF_UFDTNIA.smt2                |   18.555s | 102.0MiB| sat | 0 |  |  |
|44289_e5a2e5c780236919ee6a_18_QF_UFNIA.smt2                  |   18.639s | 100.0MiB| sat | 0 |  |  |
|44289_4066055e0f64d96da11a_14_QF_UFNIA.smt2                  |   18.781s | 105.0MiB| sat | 0 |  |  |
|39657_1c7158801cd59dc13f05_44_QF_UFDTNIA.smt2                |   19.010s | 64.616MiB| sat | 0 |  |  |
|940_590f27b1c3c800d3243e_31_QF_UFDTNIA.smt2                  |   19.049s | 65.008MiB| sat | 0 |  |  |
|63058_55d6bef5390186355f11_26_QF_UFDTNIA.smt2                |   19.303s | 64.868MiB| sat | 0 |  |  |
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFDTLIA.smt2     |   19.311s | 81.168MiB| sat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                |   20.864s | 34.744MiB| unsat | 0 |  |  |
|39657_1c7158801cd59dc13f05_45_QF_UFDTNIA.smt2                |   20.917s | 60.74MiB| sat | 0 |  |  |
|41958_32933c5a1384696720a2_62_QF_UFDTLIA.smt2                |   21.058s | 53.064MiB| sat | 0 |  |  |
|66603_accdadf23a1cf70ae043_75_QF_UFDTLIA.smt2                |   21.875s | 130.0MiB| sat | 0 |  |  |
|72658_63104dadde9c6026353f_70_QF_UFLIA.smt2                  |   21.912s | 74.0MiB| sat | 0 |  |  |
|66603_accdadf23a1cf70ae043_72_QF_UFLIA.smt2                  |   24.462s | 540.0MiB| unsat | 0 |  |  |
|38347_092cc73601c78e45f4f9_55_QF_UFDTLIA.smt2                |   26.689s | 24.02MiB| unsat | 0 |  |  |
|30078_f817a923328f75af7e60_27_QF_UFDTNIA.smt2                |   30.605s | 131.0MiB| unsat | 0 |  |  |
|3106_1c933134166dbad31f79_41_QF_UFNIA.smt2                   |   30.694s | 52.2MiB| sat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFLIA.smt2      |   31.510s | 118.0MiB| sat | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFDTLIA.smt2    |   34.467s | 93.424MiB| sat | 0 |  |  |
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFLIA.smt2      |   34.541s | 125.0MiB| sat | 0 |  |  |
|66603_accdadf23a1cf70ae043_76_QF_UFDTLIA.smt2                |   35.325s | 234.0MiB| unsat | 0 |  |  |
|39657_1c7158801cd59dc13f05_46_QF_UFLIA.smt2                  |   36.162s | 68.712MiB| sat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_22_QF_UFLIA.smt2                  |   37.228s | 167.0MiB| sat | 0 |  |  |
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFDTLIA.smt2    |   37.245s | 82.148MiB| sat | 0 |  |  |
|30078_f817a923328f75af7e60_27_QF_UFDTLIA.smt2                |   38.078s | 150.0MiB| unsat | 0 |  |  |
|39657_2866defdd1f2434b69ab_48_QF_UFLIA.smt2                  |   38.794s | 44.26MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_39_QF_UFDTNIA.smt2                 |   39.536s | 94.604MiB| sat | 0 |  |  |
|940_590f27b1c3c800d3243e_29_QF_UFDTNIA.smt2                  |   40.604s | 222.0MiB| sat | 0 |  |  |
|940_590f27b1c3c800d3243e_32_QF_UFNIA.smt2                    |   43.959s | 206.0MiB| sat | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_36_QF_UFLIA.smt2                  |   45.620s | 287.0MiB| unsat | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTNIA.smt2    |   46.643s | 63.756MiB| sat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                  |   50.221s | 37.62MiB| unsat | 0 |  |  |
|940_590f27b1c3c800d3243e_31_QF_UFDTLIA.smt2                  |   52.719s | 152.0MiB| sat | 0 |  |  |
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFDTNIA.smt2    |   53.591s | 76.168MiB| sat | 0 |  |  |
|72771_f9d228efc97cf1458e38_64_QF_UFLIA.smt2                  |   55.035s | 54.756MiB| sat | 0 |  |  |
|39657_1c7158801cd59dc13f05_46_QF_UFDTNIA.smt2                |   55.594s | 63.352MiB| sat | 0 |  |  |
|83314_a702bf8b823398c9e37a_1_UFDTNIA.smt2                    |   56.083s | 49.776MiB| sat | 0 |  |  |
|44289_4066055e0f64d96da11a_14_QF_UFLIA.smt2                  |   56.449s | 114.0MiB| sat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFLIA.smt2      |   61.301s | 150.0MiB| sat | 0 |  |  |
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFDTNIA.smt2    |   64.972s | 178.0MiB| sat | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFLIA.smt2      |   67.739s | 275.0MiB| sat | 0 |  |  |
|39657_2866defdd1f2434b69ab_47_QF_UFLIA.smt2                  |   68.261s | 49.664MiB| sat | 0 |  |  |
|72771_f9d228efc97cf1458e38_64_QF_UFNIA.smt2                  |   70.200s | 45.588MiB| sat | 0 |  |  |
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFNIA.smt2       |   71.485s | 129.0MiB| sat | 0 |  |  |
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFNIA.smt2      |   73.391s | 143.0MiB| sat | 0 |  |  |
|30078_f817a923328f75af7e60_28_QF_UFDTNIA.smt2                |   80.371s | 138.0MiB| unsat | 0 |  |  |
|940_590f27b1c3c800d3243e_33_QF_UFNIA.smt2                    |   80.398s | 488.0MiB| sat | 0 |  |  |
|39657_1c7158801cd59dc13f05_45_QF_UFNIA.smt2                  |   81.587s | 94.236MiB| sat | 0 |  |  |
|83314_a702bf8b823398c9e37a_0_UFDTLIA.smt2                    |   83.709s | 145.0MiB| sat | 0 |  |  |
|30078_f817a923328f75af7e60_28_QF_UFDTLIA.smt2                |   83.919s | 161.0MiB| unsat | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFDTNIA.smt2    |   84.612s | 96.688MiB| unsat | 0 |  |  |
|63058_55d6bef5390186355f11_26_QF_UFNIA.smt2                  |   85.726s | 219.0MiB| sat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFNIA.smt2      |   85.794s | 208.0MiB| sat | 0 |  |  |
|3106_1c933134166dbad31f79_39_QF_UFLIA.smt2                   |   87.036s | 135.0MiB| sat | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                |   91.709s | 37.504MiB| unsat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_24_QF_UFLIA.smt2                  |   93.853s | 232.0MiB| sat | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_23_QF_UFLIA.smt2                  |   98.526s | 190.0MiB| sat | 0 |  |  |
|66603_accdadf23a1cf70ae043_76_QF_UFLIA.smt2                  |   99.594s | 1737.0MiB| unsat | 0 |  |  |
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFNIA.smt2      |  100.374s | 232.0MiB| sat | 0 |  |  |
|41958_32933c5a1384696720a2_63_QF_UFDTNIA.smt2                |  100.402s | 34.016MiB| unsat | 0 |  |  |
|940_590f27b1c3c800d3243e_29_QF_UFNIA.smt2                    |  106.471s | 250.0MiB| sat | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFDTLIA.smt2    |  108.824s | 196.0MiB| unsat | 0 |  |  |
|30078_f817a923328f75af7e60_27_QF_UFNIA.smt2                  |  118.069s | 422.0MiB| unsat | 0 |  |  |
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFNIA.smt2      |  121.274s | 177.0MiB| sat | 0 |  |  |
|63058_55d6bef5390186355f11_26_QF_UFLIA.smt2                  |  130.527s | 216.0MiB| sat | 0 |  |  |
|940_590f27b1c3c800d3243e_30_QF_UFNIA.smt2                    |  136.135s | 325.0MiB| sat | 0 |  |  |
|940_590f27b1c3c800d3243e_32_QF_UFDTNIA.smt2                  |  137.774s | 265.0MiB| sat | 0 |  |  |
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFDTNIA.smt2    |  142.198s | 120.0MiB| sat | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_36_QF_UFDTLIA.smt2                |  153.679s | 423.0MiB| unsat | 0 |  |  |
|41958_32933c5a1384696720a2_61_QF_UFDTLIA.smt2                |  159.006s | 118.0MiB| sat | 0 |  |  |
|30078_f817a923328f75af7e60_27_QF_UFLIA.smt2                  |  163.777s | 462.0MiB| unsat | 0 |  |  |
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFDTLIA.smt2    |  170.121s | 135.0MiB| sat | 0 |  |  |
|30078_f817a923328f75af7e60_28_QF_UFNIA.smt2                  |  175.726s | 426.0MiB| unsat | 0 |  |  |
|93493_5990a6bf5f2740164f77_50_QF_UFDTLIA.smt2                |  179.110s | 236.0MiB| sat | 0 |  |  |
|30078_f817a923328f75af7e60_28_QF_UFLIA.smt2                  |  193.218s | 482.0MiB| unsat | 0 |  |  |
|44289_e5a2e5c780236919ee6a_17_QF_UFNIA.smt2                  |  193.798s | 126.0MiB| sat | 0 |  |  |
|83314_a702bf8b823398c9e37a_3_UFDTLIA.smt2                    |  195.405s | 857.0MiB| unsat | 0 |  |  |
|38347_092cc73601c78e45f4f9_55_QF_UFLIA.smt2                  |  200.014s | 36.052MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_57_QF_UFLIA.smt2                  |  200.014s | 37.832MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_57_QF_UFNIA.smt2                  |  200.016s | 41.168MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_57_QF_UFDTLIA.smt2                |  200.018s | 30.604MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTNIA.smt2    |  200.020s | 95.736MiB| timeout | 0 |  |  |
|65782_cd31513fdcd15701933b_5_QF_UFNIA.smt2                   |  200.022s | 66.952MiB| timeout | 0 |  |  |
|72658_63104dadde9c6026353f_71_QF_UFDTNIA.smt2                |  200.023s | 44.144MiB| timeout | 0 |  |  |
|41958_32933c5a1384696720a2_63_QF_UFNIA.smt2                  |  200.023s | 38.168MiB| timeout | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_35_QF_UFDTNIA.smt2                |  200.025s | 58.392MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_3_UFNIA.smt2                      |  200.028s | 60.632MiB| timeout | 0 |  |  |
|52759_b3ecd2335fd16ec2eee2_9_UFNIA.smt2                      |  200.029s | 67.22MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_31_QF_UFLIA.smt2                    |  200.029s | 168.0MiB| timeout | 0 |  |  |
|65782_cd31513fdcd15701933b_5_QF_UFDTNIA.smt2                 |  200.030s | 59.312MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_55_QF_UFDTNIA.smt2                |  200.031s | 24.544MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_55_QF_UFNIA.smt2                  |  200.033s | 25.572MiB| timeout | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_34_QF_UFDTNIA.smt2                |  200.033s | 58.048MiB| timeout | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_36_QF_UFDTNIA.smt2                |  200.034s | 58.72MiB| timeout | 0 |  |  |
|93493_798593962ee29ad45ac8_52_QF_UFDTNIA.smt2                |  200.034s | 151.0MiB| timeout | 0 |  |  |
|39657_1c7158801cd59dc13f05_44_QF_UFNIA.smt2                  |  200.035s | 125.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2      |  200.035s | 117.0MiB| timeout | 0 |  |  |
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFLIA.smt2      |  200.037s | 163.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_2_UFLIA.smt2                      |  200.037s | 218.0MiB| timeout | 0 |  |  |
|72658_63104dadde9c6026353f_70_QF_UFNIA.smt2                  |  200.039s | 67.432MiB| timeout | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_35_QF_UFNIA.smt2                  |  200.039s | 67.952MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_57_QF_UFDTNIA.smt2                |  200.039s | 28.672MiB| timeout | 0 |  |  |
|72658_63104dadde9c6026353f_70_QF_UFDTNIA.smt2                |  200.040s | 86.128MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTNIA.smt2    |  200.041s | 68.472MiB| timeout | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_24_QF_UFNIA.smt2                  |  200.041s | 228.0MiB| timeout | 0 |  |  |
|39657_1c7158801cd59dc13f05_46_QF_UFNIA.smt2                  |  200.042s | 102.0MiB| timeout | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_22_QF_UFNIA.smt2                  |  200.042s | 206.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_4_UFDTNIA.smt2                    |  200.043s | 170.0MiB| timeout | 0 |  |  |
|52759_b3ecd2335fd16ec2eee2_9_UFDTNIA.smt2                    |  200.043s | 46.42MiB| timeout | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_36_QF_UFNIA.smt2                  |  200.043s | 53.876MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_3_UFDTNIA.smt2                    |  200.043s | 53.588MiB| timeout | 0 |  |  |
|44788_1965f0d6d94d5d8054ba_34_QF_UFNIA.smt2                  |  200.044s | 56.228MiB| timeout | 0 |  |  |
|72658_63104dadde9c6026353f_71_QF_UFNIA.smt2                  |  200.045s | 42.008MiB| timeout | 0 |  |  |
|41958_32933c5a1384696720a2_61_QF_UFLIA.smt2                  |  200.045s | 90.64MiB| timeout | 0 |  |  |
|41958_32933c5a1384696720a2_62_QF_UFDTNIA.smt2                |  200.045s | 53.96MiB| timeout | 0 |  |  |
|93493_798593962ee29ad45ac8_52_QF_UFNIA.smt2                  |  200.046s | 195.0MiB| timeout | 0 |  |  |
|52759_b3ecd2335fd16ec2eee2_9_UFDTLIA.smt2                    |  200.046s | 65.724MiB| timeout | 0 |  |  |
|63058_64ab9a7ef7b6c3492507_23_QF_UFNIA.smt2                  |  200.047s | 187.0MiB| timeout | 0 |  |  |
|65782_cd31513fdcd15701933b_5_QF_UFLIA.smt2                   |  200.049s | 196.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_2_UFDTLIA.smt2                    |  200.050s | 202.0MiB| timeout | 0 |  |  |
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFLIA.smt2       |  200.050s | 114.0MiB| timeout | 0 |  |  |
|72658_63104dadde9c6026353f_71_QF_UFDTLIA.smt2                |  200.050s | 244.0MiB| timeout | 0 |  |  |
|41958_32933c5a1384696720a2_62_QF_UFNIA.smt2                  |  200.051s | 39.176MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFNIA.smt2      |  200.052s | 99.376MiB| timeout | 0 |  |  |
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFLIA.smt2      |  200.052s | 118.0MiB| timeout | 0 |  |  |
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFDTLIA.smt2    |  200.052s | 217.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_2_UFNIA.smt2                      |  200.052s | 189.0MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_56_QF_UFLIA.smt2                  |  200.054s | 199.0MiB| timeout | 0 |  |  |
|93493_5990a6bf5f2740164f77_50_QF_UFLIA.smt2                  |  200.055s | 294.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_2_UFDTNIA.smt2                    |  200.056s | 180.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFNIA.smt2      |  200.057s | 81.696MiB| timeout | 0 |  |  |
|65782_cd31513fdcd15701933b_5_QF_UFDTLIA.smt2                 |  200.058s | 195.0MiB| timeout | 0 |  |  |
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFNIA.smt2      |  200.059s | 182.0MiB| timeout | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                  |  200.059s | 154.0MiB| timeout | 0 |  |  |
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFLIA.smt2      |  200.060s | 262.0MiB| timeout | 0 |  |  |
|93493_5990a6bf5f2740164f77_50_QF_UFNIA.smt2                  |  200.060s | 339.0MiB| timeout | 0 |  |  |
|52759_b3ecd2335fd16ec2eee2_9_UFLIA.smt2                      |  200.061s | 64.136MiB| timeout | 0 |  |  |
|93493_798593962ee29ad45ac8_52_QF_UFDTLIA.smt2                |  200.061s | 175.0MiB| timeout | 0 |  |  |
|38347_092cc73601c78e45f4f9_56_QF_UFDTLIA.smt2                |  200.061s | 192.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_4_UFNIA.smt2                      |  200.061s | 228.0MiB| timeout | 0 |  |  |
|41958_32933c5a1384696720a2_61_QF_UFDTNIA.smt2                |  200.061s | 41.592MiB| timeout | 0 |  |  |
|93493_798593962ee29ad45ac8_52_QF_UFLIA.smt2                  |  200.062s | 240.0MiB| timeout | 0 |  |  |
|38347_525a1ca0331f2bcbf520_54_QF_UFDTNIA.smt2                |  200.062s | 190.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_0_UFLIA.smt2                      |  200.062s | 142.0MiB| timeout | 0 |  |  |
|3106_1c933134166dbad31f79_39_QF_UFNIA.smt2                   |  200.063s | 150.0MiB| timeout | 0 |  |  |
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFDTNIA.smt2    |  200.063s | 218.0MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_75_QF_UFDTNIA.smt2                |  200.063s | 184.0MiB| timeout | 0 |  |  |
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFNIA.smt2      |  200.063s | 258.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_33_QF_UFDTNIA.smt2                  |  200.063s | 280.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_29_QF_UFLIA.smt2                    |  200.064s | 464.0MiB| timeout | 0 |  |  |
|3106_1c933134166dbad31f79_38_QF_UFDTLIA.smt2                 |  200.065s | 283.0MiB| timeout | 0 |  |  |
|72658_63104dadde9c6026353f_71_QF_UFLIA.smt2                  |  200.065s | 209.0MiB| timeout | 0 |  |  |
|38347_525a1ca0331f2bcbf520_54_QF_UFNIA.smt2                  |  200.066s | 366.0MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_74_QF_UFDTNIA.smt2                |  200.067s | 179.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_30_QF_UFLIA.smt2                    |  200.068s | 349.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_1_UFLIA.smt2                      |  200.069s | 259.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_33_QF_UFDTLIA.smt2                  |  200.070s | 439.0MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_73_QF_UFDTLIA.smt2                |  200.071s | 288.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_32_QF_UFLIA.smt2                    |  200.072s | 349.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_33_QF_UFLIA.smt2                    |  200.072s | 398.0MiB| timeout | 0 |  |  |
|93493_5990a6bf5f2740164f77_50_QF_UFDTNIA.smt2                |  200.073s | 226.0MiB| timeout | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFNIA.smt2      |  200.075s | 224.0MiB| timeout | 0 |  |  |
|3106_1c933134166dbad31f79_38_QF_UFDTNIA.smt2                 |  200.076s | 400.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_3_UFLIA.smt2                      |  200.079s | 439.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFLIA.smt2      |  200.079s | 537.0MiB| timeout | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFNIA.smt2      |  200.079s | 269.0MiB| timeout | 0 |  |  |
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFLIA.smt2      |  200.081s | 395.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_30_QF_UFDTNIA.smt2                  |  200.083s | 203.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_30_QF_UFDTLIA.smt2                  |  200.085s | 412.0MiB| timeout | 0 |  |  |
|44289_4066055e0f64d96da11a_15_QF_UFLIA.smt2                  |  200.087s | 436.0MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_73_QF_UFNIA.smt2                  |  200.092s | 439.0MiB| timeout | 0 |  |  |
|44289_4066055e0f64d96da11a_15_QF_UFNIA.smt2                  |  200.092s | 431.0MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                  |  200.094s | 578.0MiB| timeout | 0 |  |  |
|3106_1c933134166dbad31f79_38_QF_UFLIA.smt2                   |  200.096s | 602.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTLIA.smt2    |  200.096s | 692.0MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_73_QF_UFLIA.smt2                  |  200.098s | 630.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_29_QF_UFDTLIA.smt2                  |  200.098s | 372.0MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_74_QF_UFLIA.smt2                  |  200.098s | 587.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_1_UFDTLIA.smt2                    |  200.099s | 550.0MiB| timeout | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                |  200.100s | 614.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTLIA.smt2    |  200.102s | 690.0MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_75_QF_UFNIA.smt2                  |  200.105s | 639.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTLIA.smt2    |  200.105s | 752.0MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_74_QF_UFNIA.smt2                  |  200.111s | 646.0MiB| timeout | 0 |  |  |
|940_590f27b1c3c800d3243e_32_QF_UFDTLIA.smt2                  |  200.115s | 526.0MiB| timeout | 0 |  |  |
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                  |  200.116s | 516.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_4_UFLIA.smt2                      |  200.129s | 649.0MiB| timeout | 0 |  |  |
|83314_a702bf8b823398c9e37a_4_UFDTLIA.smt2                    |  200.133s | 696.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFLIA.smt2      |  200.137s | 833.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFLIA.smt2      |  200.140s | 1355.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTLIA.smt2    |  200.146s | 1180.0MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_75_QF_UFLIA.smt2                  |  200.155s | 1226.0MiB| timeout | 0 |  |  |
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                   |  200.164s | 1154.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFLIA.smt2      |  200.166s | 694.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTLIA.smt2    |  200.176s | 1430.0MiB| timeout | 0 |  |  |
|66603_accdadf23a1cf70ae043_76_QF_UFNIA.smt2                  |  200.185s | 1565.0MiB| timeout | 0 |  |  |
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFLIA.smt2      |  200.211s | 1920.0MiB| timeout | 0 |  |  |
|38347_525a1ca0331f2bcbf520_54_QF_UFDTLIA.smt2                |  200.222s | 1976.0MiB| timeout | 0 |  |  |
|38347_525a1ca0331f2bcbf520_54_QF_UFLIA.smt2                  |  200.258s | 2177.0MiB| timeout | 0 |  |  |
