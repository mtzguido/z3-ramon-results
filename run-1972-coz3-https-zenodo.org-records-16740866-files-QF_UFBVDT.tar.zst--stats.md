# .

* SAT 0
* UNSAT 1
* TIMEOUT 63
* UNKNOWN 0

* ERRORS 12 (segfault:12)

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_UFBVDT.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_UFBVDT.tar.zst-
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 459629c662eb7abf25a010b7383431a9f729d234
Z3 branch: master
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_UFBVDT.tar.zst?download=1
Z3 commit message: bugfixes to ho_matcher

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/44788_1965f0d6d94d5d8054ba_34_QF_UFDTBV.smt2 |    0.062s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_6_QF_UFDTBV.smt2 |    0.450s | 21.604MiB| segfault | 139 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/44788_1965f0d6d94d5d8054ba_35_QF_UFDTBV.smt2 |    0.700s | 25.544MiB| segfault | 139 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/17512_5c1021b0faa6b6e1791b_19_QF_UFDTBV.smt2 |    0.739s | 22.688MiB| segfault | 139 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_55_QF_UFDTBV.smt2 |    3.333s | 26.388MiB| segfault | 139 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/39657_2866defdd1f2434b69ab_48_QF_UFDTBV.smt2 |    3.437s | 27.264MiB| segfault | 139 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/39657_2866defdd1f2434b69ab_47_QF_UFDTBV.smt2 |    3.473s | 24.972MiB| segfault | 139 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFDTBV.smt2 |    5.540s | 29.592MiB| segfault | 139 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_58_QF_UFDTBV.smt2 |    8.555s | 34.052MiB| segfault | 139 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/72771_f9d228efc97cf1458e38_64_QF_UFDTBV.smt2 |   10.434s | 33.876MiB| segfault | 139 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_40_QF_UFDTBV.smt2 |   11.538s | 29.508MiB| segfault | 139 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/44788_1965f0d6d94d5d8054ba_36_QF_UFDTBV.smt2 |   15.624s | 24.844MiB| segfault | 139 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/63058_aa742630eef64f949de269382c1f9035_25_UFDTBV.smt2 |   17.619s | 41.592MiB| segfault | 139 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_8_QF_UFDTBV.smt2 |   20.011s | 22.416MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_1_UFDTBV.smt2 |   20.011s | 27.964MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/41958_32933c5a1384696720a2_61_QF_UFDTBV.smt2 |   20.012s | 22.324MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/41958_32933c5a1384696720a2_62_QF_UFDTBV.smt2 |   20.012s | 21.38MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTBV.smt2 |   20.013s | 36.356MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_31_QF_UFDTBV.smt2 |   20.013s | 34.876MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/39657_1c7158801cd59dc13f05_44_QF_UFDTBV.smt2 |   20.014s | 38.54MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/30078_f817a923328f75af7e60_28_QF_UFDTBV.smt2 |   20.014s | 57.332MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTBV.smt2 |   20.015s | 31.92MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFDTBV.smt2 |   20.015s | 27.424MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_41_QF_UFDTBV.smt2 |   20.016s | 36.98MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_30_QF_UFDTBV.smt2 |   20.017s | 73.216MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_2_UFDTBV.smt2 |   20.017s | 44.68MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_29_QF_UFDTBV.smt2 |   20.017s | 73.956MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/38347_525a1ca0331f2bcbf520_54_QF_UFDTBV.smt2 |   20.018s | 44.396MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTBV.smt2 |   20.018s | 29.82MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/63058_64ab9a7ef7b6c3492507_23_QF_UFDTBV.smt2 |   20.020s | 119.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFDTBV.smt2 |   20.022s | 65.524MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_32_QF_UFDTBV.smt2 |   20.023s | 73.288MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/11775_ad46e5b8db4748c51973_42_QF_UFDTBV.smt2 |   20.024s | 26.14MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/72658_63104dadde9c6026353f_71_QF_UFDTBV.smt2 |   20.025s | 65.712MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_5_QF_UFDTBV.smt2 |   20.025s | 25.668MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/44289_e5a2e5c780236919ee6a_18_QF_UFDTBV.smt2 |   20.026s | 46.424MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/44289_e5a2e5c780236919ee6a_17_QF_UFDTBV.smt2 |   20.026s | 45.696MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_57_QF_UFDTBV.smt2 |   20.029s | 60.82MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/72658_63104dadde9c6026353f_70_QF_UFDTBV.smt2 |   20.029s | 100.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFDTBV.smt2 |   20.030s | 60.776MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFDTBV.smt2 |   20.031s | 98.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/63058_64ab9a7ef7b6c3492507_24_QF_UFDTBV.smt2 |   20.031s | 190.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/63058_64ab9a7ef7b6c3492507_22_QF_UFDTBV.smt2 |   20.034s | 112.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_76_QF_UFDTBV.smt2 |   20.034s | 87.188MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/44289_4066055e0f64d96da11a_14_QF_UFDTBV.smt2 |   20.036s | 39.592MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_7_QF_UFDTBV.smt2 |   20.037s | 22.256MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_0_UFDTBV.smt2 |   20.038s | 25.024MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/39657_1c7158801cd59dc13f05_45_QF_UFDTBV.smt2 |   20.039s | 37.568MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/17512_5c1021b0faa6b6e1791b_21_QF_UFDTBV.smt2 |   20.040s | 25.24MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/41958_32933c5a1384696720a2_63_QF_UFDTBV.smt2 |   20.040s | 21.456MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_72_QF_UFDTBV.smt2 |   20.042s | 54.092MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_3_UFDTBV.smt2 |   20.042s | 27.576MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/11775_ad46e5b8db4748c51973_43_QF_UFDTBV.smt2 |   20.042s | 24.848MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTBV.smt2 |   20.042s | 27.988MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_56_QF_UFDTBV.smt2 |   20.042s | 58.112MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/93493_798593962ee29ad45ac8_52_QF_UFDTBV.smt2 |   20.043s | 39.36MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/39657_1c7158801cd59dc13f05_46_QF_UFDTBV.smt2 |   20.043s | 38.916MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTBV.smt2 |   20.044s | 27.568MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/41958_45c688a4814eb926c254_59_QF_UFDTBV.smt2 |   20.045s | 33.396MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/17512_5c1021b0faa6b6e1791b_20_QF_UFDTBV.smt2 |   20.045s | 24.744MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFDTBV.smt2 |   20.046s | 42.728MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/41958_45c688a4814eb926c254_60_QF_UFDTBV.smt2 |   20.046s | 29.868MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_75_QF_UFDTBV.smt2 |   20.047s | 52.464MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_4_UFDTBV.smt2 |   20.048s | 52.66MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_33_QF_UFDTBV.smt2 |   20.049s | 66.88MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/44289_4066055e0f64d96da11a_15_QF_UFDTBV.smt2 |   20.049s | 71.596MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_73_QF_UFDTBV.smt2 |   20.050s | 38.012MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFDTBV.smt2 |   20.050s | 39.02MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_74_QF_UFDTBV.smt2 |   20.050s | 52.576MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/30078_f817a923328f75af7e60_27_QF_UFDTBV.smt2 |   20.050s | 56.928MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFDTBV.smt2 |   20.051s | 64.48MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_39_QF_UFDTBV.smt2 |   20.052s | 102.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/93493_4ea6163ed03941199c785278ccc42812_49_QF_UFDTBV.smt2 |   20.055s | 131.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/63058_55d6bef5390186355f11_26_QF_UFDTBV.smt2 |   20.055s | 112.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/93493_5990a6bf5f2740164f77_50_QF_UFDTBV.smt2 |   20.056s | 233.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_38_QF_UFDTBV.smt2 |   20.056s | 169.0MiB| timeout | 0 |  |  |
