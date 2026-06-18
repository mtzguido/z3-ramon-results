# .

* SAT 33
* UNSAT 9
* TIMEOUT 38
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_UFDTNIA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_UFDTNIA.tar.zst
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: 9091df56cbb91c668c6ef3e26899d2839d38e8a5
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_UFDTNIA.tar.zst?download=1
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
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/63058_aa742630eef64f949de269382c1f9035_25_UFDTNIA.smt2 |    0.091s | 23.492MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_6_QF_UFDTNIA.smt2 |    0.120s | 21.328MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_40_QF_UFDTNIA.smt2 |    0.125s | 23.468MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/41958_45c688a4814eb926c254_60_QF_UFDTNIA.smt2 |    0.226s | 29.136MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/39657_2866defdd1f2434b69ab_47_QF_UFDTNIA.smt2 |    0.271s | 26.868MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFDTNIA.smt2 |    0.312s | 28.408MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/41958_45c688a4814eb926c254_59_QF_UFDTNIA.smt2 |    0.320s | 31.248MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFDTNIA.smt2 |    0.392s | 29.276MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_58_QF_UFDTNIA.smt2 |    0.419s | 28.104MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2 |    1.025s | 30.264MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/39657_2866defdd1f2434b69ab_48_QF_UFDTNIA.smt2 |    1.231s | 29.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_8_QF_UFDTNIA.smt2 |    1.261s | 25.348MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2 |    1.311s | 27.964MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/44289_4066055e0f64d96da11a_14_QF_UFDTNIA.smt2 |    1.369s | 43.344MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_0_UFDTNIA.smt2 |    1.561s | 28.02MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_7_QF_UFDTNIA.smt2 |    1.685s | 25.592MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/44289_e5a2e5c780236919ee6a_18_QF_UFDTNIA.smt2 |    1.920s | 51.172MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/44289_e5a2e5c780236919ee6a_17_QF_UFDTNIA.smt2 |    1.974s | 50.516MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/72771_f9d228efc97cf1458e38_64_QF_UFDTNIA.smt2 |    2.082s | 29.664MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/63058_64ab9a7ef7b6c3492507_22_QF_UFDTNIA.smt2 |    2.432s | 46.34MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/63058_55d6bef5390186355f11_26_QF_UFDTNIA.smt2 |    2.913s | 52.424MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_72_QF_UFDTNIA.smt2 |    3.629s | 84.608MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/44289_4066055e0f64d96da11a_15_QF_UFDTNIA.smt2 |    3.686s | 77.376MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/63058_64ab9a7ef7b6c3492507_24_QF_UFDTNIA.smt2 |    3.787s | 74.384MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_2_UFDTNIA.smt2 |    4.957s | 90.588MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2 |    5.054s | 24.664MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_39_QF_UFDTNIA.smt2 |    5.661s | 69.004MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_31_QF_UFDTNIA.smt2 |    6.177s | 59.752MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFDTNIA.smt2 |    6.348s | 66.716MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_41_QF_UFDTNIA.smt2 |    6.729s | 38.648MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/63058_64ab9a7ef7b6c3492507_23_QF_UFDTNIA.smt2 |    6.815s | 53.04MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/39657_1c7158801cd59dc13f05_44_QF_UFDTNIA.smt2 |    7.460s | 67.112MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTNIA.smt2 |    8.067s | 42.556MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_1_UFDTNIA.smt2 |    8.162s | 41.092MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_76_QF_UFDTNIA.smt2 |    9.025s | 140.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFDTNIA.smt2 |    9.517s | 84.796MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2 |   10.100s | 31.816MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/39657_1c7158801cd59dc13f05_45_QF_UFDTNIA.smt2 |   10.535s | 59.152MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFDTNIA.smt2 |   11.824s | 69.496MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/30078_f817a923328f75af7e60_27_QF_UFDTNIA.smt2 |   12.783s | 124.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/39657_1c7158801cd59dc13f05_46_QF_UFDTNIA.smt2 |   13.024s | 62.14MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/30078_f817a923328f75af7e60_28_QF_UFDTNIA.smt2 |   20.001s | 133.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/44788_1965f0d6d94d5d8054ba_34_QF_UFDTNIA.smt2 |   20.006s | 28.072MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_55_QF_UFDTNIA.smt2 |   20.006s | 22.996MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_57_QF_UFDTNIA.smt2 |   20.006s | 26.216MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_5_QF_UFDTNIA.smt2 |   20.007s | 39.192MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2 |   20.007s | 36.472MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/44788_1965f0d6d94d5d8054ba_35_QF_UFDTNIA.smt2 |   20.007s | 33.2MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_3_UFDTNIA.smt2 |   20.008s | 43.348MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/41958_32933c5a1384696720a2_62_QF_UFDTNIA.smt2 |   20.008s | 27.764MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/44788_1965f0d6d94d5d8054ba_36_QF_UFDTNIA.smt2 |   20.009s | 33.012MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFDTNIA.smt2 |   20.010s | 82.948MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFDTNIA.smt2 |   20.010s | 82.208MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/41958_32933c5a1384696720a2_61_QF_UFDTNIA.smt2 |   20.010s | 34.848MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_56_QF_UFDTNIA.smt2 |   20.010s | 54.636MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/72658_63104dadde9c6026353f_71_QF_UFDTNIA.smt2 |   20.011s | 28.396MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTNIA.smt2 |   20.011s | 48.02MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/41958_32933c5a1384696720a2_63_QF_UFDTNIA.smt2 |   20.013s | 27.936MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_73_QF_UFDTNIA.smt2 |   20.014s | 107.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/72658_63104dadde9c6026353f_70_QF_UFDTNIA.smt2 |   20.016s | 41.124MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTNIA.smt2 |   20.020s | 43.108MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/93493_5990a6bf5f2740164f77_50_QF_UFDTNIA.smt2 |   20.020s | 198.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/38347_525a1ca0331f2bcbf520_54_QF_UFDTNIA.smt2 |   20.021s | 115.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_30_QF_UFDTNIA.smt2 |   20.024s | 172.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/93493_4ea6163ed03941199c785278ccc42812_49_QF_UFDTNIA.smt2 |   20.025s | 185.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTNIA.smt2 |   20.029s | 53.792MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/93493_798593962ee29ad45ac8_52_QF_UFDTNIA.smt2 |   20.029s | 70.896MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTNIA.smt2 |   20.029s | 60.996MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20240410-certora/nia-splits/0010.smt2 |   20.031s | 114.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_74_QF_UFDTNIA.smt2 |   20.031s | 131.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_38_QF_UFDTNIA.smt2 |   20.031s | 218.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFDTNIA.smt2 |   20.032s | 70.256MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_75_QF_UFDTNIA.smt2 |   20.032s | 122.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20240410-certora/nia/0013.smt2    |   20.033s | 136.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_29_QF_UFDTNIA.smt2 |   20.033s | 167.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_4_UFDTNIA.smt2 |   20.034s | 124.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_33_QF_UFDTNIA.smt2 |   20.034s | 171.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20240410-certora/lia-splits/0011.smt2 |   20.035s | 148.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_32_QF_UFDTNIA.smt2 |   20.035s | 196.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20240410-certora/lia/0014.smt2    |   20.036s | 229.0MiB| timeout | 0 |  |  |
