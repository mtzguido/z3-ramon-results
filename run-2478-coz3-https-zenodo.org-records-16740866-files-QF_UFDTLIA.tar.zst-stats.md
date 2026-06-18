# .

* SAT 38
* UNSAT 8
* TIMEOUT 30
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_UFDTLIA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_UFDTLIA.tar.zst
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: 9091df56cbb91c668c6ef3e26899d2839d38e8a5
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_UFDTLIA.tar.zst?download=1
Z3 commit message: Fix instance of "flexible array member". (#9883)

This is another PR towards the goal of getting a clean build with clang,
using the compiler options used in building clang-tidy.

In https://github.com/Z3Prover/z3/pull/9800, we changed the build flags
to eliminate a warning for zero-length arrays. In that PR, I missed this
one: there was one instance of m_arr[] instead of m_arr[0]. In the
clang-tidy build, that gives warnings like:
```
/Users/daviddetlefs/llvm-project/build_dbg/_deps/z3-src/src/model/func_interp.h:43:12: warning: flexible array members are a C99 feature [-Wc99-extensions]
```

The PR fixes this, making it a zero-length array, the idiom used in all
the other similar cases. I also added the compiler flag that produced
this warning, so we can notice such changes in the future.

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_6_QF_UFDTLIA.smt2 |    0.061s | 21.728MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_40_QF_UFDTLIA.smt2 |    0.122s | 23.576MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/44788_1965f0d6d94d5d8054ba_34_QF_UFDTLIA.smt2 |    0.129s | 23.6MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/63058_aa742630eef64f949de269382c1f9035_25_UFDTLIA.smt2 |    0.139s | 24.884MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_7_QF_UFDTLIA.smt2 |    0.375s | 25.504MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2 |    0.379s | 34.032MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_58_QF_UFDTLIA.smt2 |    0.418s | 29.22MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFDTLIA.smt2 |    0.439s | 33.648MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_8_QF_UFDTLIA.smt2 |    0.459s | 25.836MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/41958_45c688a4814eb926c254_60_QF_UFDTLIA.smt2 |    0.479s | 33.856MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFDTLIA.smt2 |    0.544s | 30.656MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/44788_1965f0d6d94d5d8054ba_35_QF_UFDTLIA.smt2 |    0.712s | 27.212MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2 |    0.716s | 36.056MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/41958_45c688a4814eb926c254_59_QF_UFDTLIA.smt2 |    0.948s | 38.332MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/72658_63104dadde9c6026353f_70_QF_UFDTLIA.smt2 |    1.114s | 55.792MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_41_QF_UFDTLIA.smt2 |    1.257s | 38.964MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/44289_4066055e0f64d96da11a_14_QF_UFDTLIA.smt2 |    1.458s | 42.932MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/44289_e5a2e5c780236919ee6a_17_QF_UFDTLIA.smt2 |    1.570s | 50.092MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/44289_e5a2e5c780236919ee6a_18_QF_UFDTLIA.smt2 |    1.614s | 48.964MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/39657_1c7158801cd59dc13f05_46_QF_UFDTLIA.smt2 |    1.693s | 56.112MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/39657_1c7158801cd59dc13f05_45_QF_UFDTLIA.smt2 |    1.772s | 55.5MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/39657_2866defdd1f2434b69ab_48_QF_UFDTLIA.smt2 |    1.866s | 30.096MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/39657_1c7158801cd59dc13f05_44_QF_UFDTLIA.smt2 |    1.908s | 52.936MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/63058_55d6bef5390186355f11_26_QF_UFDTLIA.smt2 |    1.932s | 49.168MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/41958_32933c5a1384696720a2_63_QF_UFDTLIA.smt2 |    2.220s | 33.172MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/63058_64ab9a7ef7b6c3492507_23_QF_UFDTLIA.smt2 |    2.318s | 66.788MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/63058_64ab9a7ef7b6c3492507_22_QF_UFDTLIA.smt2 |    2.617s | 45.96MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/44289_4066055e0f64d96da11a_15_QF_UFDTLIA.smt2 |    3.212s | 76.996MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_72_QF_UFDTLIA.smt2 |    3.854s | 104.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/63058_64ab9a7ef7b6c3492507_24_QF_UFDTLIA.smt2 |    3.985s | 66.24MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2 |    4.011s | 69.532MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/72771_f9d228efc97cf1458e38_64_QF_UFDTLIA.smt2 |    4.033s | 33.564MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2 |    6.258s | 74.236MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_75_QF_UFDTLIA.smt2 |    8.231s | 126.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/41958_32933c5a1384696720a2_62_QF_UFDTLIA.smt2 |    8.267s | 53.536MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFDTLIA.smt2 |    8.459s | 80.992MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFDTLIA.smt2 |    9.743s | 79.728MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFDTLIA.smt2 |   10.050s | 87.624MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_55_QF_UFDTLIA.smt2 |   10.080s | 23.664MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFDTLIA.smt2 |   10.258s | 83.22MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_39_QF_UFDTLIA.smt2 |   10.334s | 82.844MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_76_QF_UFDTLIA.smt2 |   11.354s | 232.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/30078_f817a923328f75af7e60_27_QF_UFDTLIA.smt2 |   11.597s | 139.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/39657_2866defdd1f2434b69ab_47_QF_UFDTLIA.smt2 |   17.254s | 38.332MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFDTLIA.smt2 |   19.187s | 143.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_74_QF_UFDTLIA.smt2 |   19.724s | 139.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_56_QF_UFDTLIA.smt2 |   20.017s | 151.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/93493_5990a6bf5f2740164f77_50_QF_UFDTLIA.smt2 |   20.017s | 181.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/41958_32933c5a1384696720a2_61_QF_UFDTLIA.smt2 |   20.020s | 83.332MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_29_QF_UFDTLIA.smt2 |   20.022s | 291.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/72658_63104dadde9c6026353f_71_QF_UFDTLIA.smt2 |   20.033s | 200.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFDTLIA.smt2 |   20.035s | 171.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_57_QF_UFDTLIA.smt2 |   20.035s | 28.444MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/30078_f817a923328f75af7e60_28_QF_UFDTLIA.smt2 |   20.036s | 143.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_1_UFDTLIA.smt2 |   20.037s | 316.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_32_QF_UFDTLIA.smt2 |   20.038s | 284.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/93493_4ea6163ed03941199c785278ccc42812_49_QF_UFDTLIA.smt2 |   20.039s | 187.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/93493_798593962ee29ad45ac8_52_QF_UFDTLIA.smt2 |   20.046s | 136.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_5_QF_UFDTLIA.smt2 |   20.049s | 126.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_2_UFDTLIA.smt2 |   20.051s | 187.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_3_UFDTLIA.smt2 |   20.057s | 222.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_73_QF_UFDTLIA.smt2 |   20.060s | 237.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_0_UFDTLIA.smt2 |   20.065s | 146.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_31_QF_UFDTLIA.smt2 |   20.066s | 148.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_33_QF_UFDTLIA.smt2 |   20.066s | 279.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_38_QF_UFDTLIA.smt2 |   20.068s | 258.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/44788_1965f0d6d94d5d8054ba_36_QF_UFDTLIA.smt2 |   20.075s | 354.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_30_QF_UFDTLIA.smt2 |   20.088s | 287.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2 |   20.088s | 366.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTLIA.smt2 |   20.090s | 491.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTLIA.smt2 |   20.110s | 522.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTLIA.smt2 |   20.114s | 624.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_4_UFDTLIA.smt2 |   20.118s | 613.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTLIA.smt2 |   20.124s | 917.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTLIA.smt2 |   20.133s | 1178.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/38347_525a1ca0331f2bcbf520_54_QF_UFDTLIA.smt2 |   20.140s | 1280.0MiB| timeout | 0 |  |  |
