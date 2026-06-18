# .

* SAT 7
* UNSAT 3
* TIMEOUT 66
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_UFBVDT.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_UFBVDT.tar.zst-
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: 9091df56cbb91c668c6ef3e26899d2839d38e8a5
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_UFBVDT.tar.zst?download=1
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
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/44788_1965f0d6d94d5d8054ba_34_QF_UFDTBV.smt2 |    0.036s | 19.788MiB| unsat | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_6_QF_UFDTBV.smt2 |    0.101s | 33.704MiB| sat | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_55_QF_UFDTBV.smt2 |    0.208s | 31.076MiB| unsat | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_40_QF_UFDTBV.smt2 |    0.591s | 60.336MiB| sat | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/39657_2866defdd1f2434b69ab_47_QF_UFDTBV.smt2 |    0.744s | 84.928MiB| sat | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_57_QF_UFDTBV.smt2 |    0.981s | 41.528MiB| unsat | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_58_QF_UFDTBV.smt2 |    1.181s | 136.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/72771_f9d228efc97cf1458e38_64_QF_UFDTBV.smt2 |    1.246s | 89.028MiB| sat | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/39657_2866defdd1f2434b69ab_48_QF_UFDTBV.smt2 |    1.541s | 138.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/41958_45c688a4814eb926c254_60_QF_UFDTBV.smt2 |    2.507s | 220.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/63058_64ab9a7ef7b6c3492507_23_QF_UFDTBV.smt2 |   20.049s | 447.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/63058_64ab9a7ef7b6c3492507_22_QF_UFDTBV.smt2 |   20.210s | 394.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFDTBV.smt2 |   20.270s | 3830.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_41_QF_UFDTBV.smt2 |   20.282s | 304.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/41958_45c688a4814eb926c254_59_QF_UFDTBV.smt2 |   20.288s | 301.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/44289_e5a2e5c780236919ee6a_18_QF_UFDTBV.smt2 |   20.289s | 534.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/44289_4066055e0f64d96da11a_15_QF_UFDTBV.smt2 |   20.300s | 649.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/44289_4066055e0f64d96da11a_14_QF_UFDTBV.smt2 |   20.342s | 335.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/63058_64ab9a7ef7b6c3492507_24_QF_UFDTBV.smt2 |   20.414s | 506.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTBV.smt2 |   20.456s | 7519.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/44289_e5a2e5c780236919ee6a_17_QF_UFDTBV.smt2 |   20.456s | 535.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_39_QF_UFDTBV.smt2 |   20.498s | 607.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/63058_55d6bef5390186355f11_26_QF_UFDTBV.smt2 |   20.580s | 956.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/39657_1c7158801cd59dc13f05_44_QF_UFDTBV.smt2 |   20.591s | 761.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/39657_1c7158801cd59dc13f05_45_QF_UFDTBV.smt2 |   20.618s | 759.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/39657_1c7158801cd59dc13f05_46_QF_UFDTBV.smt2 |   20.652s | 759.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_1_UFDTBV.smt2 |   20.735s | 3918.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/17512_5c1021b0faa6b6e1791b_20_QF_UFDTBV.smt2 |   20.891s | 1120.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFDTBV.smt2 |   21.055s | 3801.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFDTBV.smt2 |   21.175s | 1922.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/41958_32933c5a1384696720a2_62_QF_UFDTBV.smt2 |   21.223s | 1995.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/11775_ad46e5b8db4748c51973_42_QF_UFDTBV.smt2 |   21.679s | 6584.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/41958_32933c5a1384696720a2_63_QF_UFDTBV.smt2 |   21.719s | 3663.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/30078_f817a923328f75af7e60_27_QF_UFDTBV.smt2 |   21.808s | 3677.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/11775_ad46e5b8db4748c51973_43_QF_UFDTBV.smt2 |   21.811s | 3681.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/30078_f817a923328f75af7e60_28_QF_UFDTBV.smt2 |   21.812s | 3690.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_7_QF_UFDTBV.smt2 |   21.819s | 3676.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_0_UFDTBV.smt2 |   21.825s | 3865.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_76_QF_UFDTBV.smt2 |   21.841s | 4093.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/38347_525a1ca0331f2bcbf520_54_QF_UFDTBV.smt2 |   21.845s | 3784.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFDTBV.smt2 |   21.847s | 3817.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/44788_1965f0d6d94d5d8054ba_35_QF_UFDTBV.smt2 |   21.850s | 3794.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_72_QF_UFDTBV.smt2 |   21.853s | 3686.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_8_QF_UFDTBV.smt2 |   21.854s | 3609.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/72658_63104dadde9c6026353f_70_QF_UFDTBV.smt2 |   21.858s | 3656.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_29_QF_UFDTBV.smt2 |   21.860s | 3870.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFDTBV.smt2 |   21.860s | 3728.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_33_QF_UFDTBV.smt2 |   21.871s | 3867.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_73_QF_UFDTBV.smt2 |   21.890s | 4364.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_75_QF_UFDTBV.smt2 |   21.895s | 3757.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_74_QF_UFDTBV.smt2 |   21.898s | 3667.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTBV.smt2 |   21.899s | 3842.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_4_UFDTBV.smt2 |   21.906s | 4156.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_2_UFDTBV.smt2 |   21.917s | 3921.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/17512_5c1021b0faa6b6e1791b_21_QF_UFDTBV.smt2 |   21.929s | 3823.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_30_QF_UFDTBV.smt2 |   21.932s | 3983.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFDTBV.smt2 |   21.933s | 3708.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_32_QF_UFDTBV.smt2 |   21.938s | 4147.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/17512_5c1021b0faa6b6e1791b_19_QF_UFDTBV.smt2 |   21.950s | 3883.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFDTBV.smt2 |   21.984s | 4449.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/44788_1965f0d6d94d5d8054ba_36_QF_UFDTBV.smt2 |   21.988s | 4192.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_38_QF_UFDTBV.smt2 |   21.999s | 3869.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/72658_63104dadde9c6026353f_71_QF_UFDTBV.smt2 |   22.034s | 4083.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/93493_798593962ee29ad45ac8_52_QF_UFDTBV.smt2 |   22.062s | 4764.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/63058_aa742630eef64f949de269382c1f9035_25_UFDTBV.smt2 |   22.082s | 4299.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTBV.smt2 |   22.253s | 5319.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_5_QF_UFDTBV.smt2 |   22.260s | 7082.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_56_QF_UFDTBV.smt2 |   22.293s | 7251.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/93493_5990a6bf5f2740164f77_50_QF_UFDTBV.smt2 |   22.320s | 7341.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/41958_32933c5a1384696720a2_61_QF_UFDTBV.smt2 |   22.325s | 7300.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTBV.smt2 |   22.342s | 7472.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFDTBV.smt2 |   22.372s | 6232.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/93493_4ea6163ed03941199c785278ccc42812_49_QF_UFDTBV.smt2 |   22.378s | 6440.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_31_QF_UFDTBV.smt2 |   22.384s | 6623.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_3_UFDTBV.smt2 |   22.399s | 6903.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTBV.smt2 |   22.429s | 7448.0MiB| timeout | 0 |  |  |
