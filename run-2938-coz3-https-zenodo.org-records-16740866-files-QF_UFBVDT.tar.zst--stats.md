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
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_UFBVDT.tar.zst?download=1 | Source list: benchmarks-qf.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_UFBVDT.tar.zst-
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 2081918cea27e604b9077a6c36acb2ac28aa5b78
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_UFBVDT.tar.zst?download=1
Z3 commit message: cmake: skip std::atomic link check for Emscripten and single-threaded builds (#9932)

The "Python bindings (Pyodide)" CI job fails at CMake configure time
because Emscripten's cross-compiler cannot pass the `std::atomic` link
tests in `check_link_atomic.cmake`, resulting in a fatal error even
though Pyodide builds are single-threaded and never need `libatomic`.

## Change

- **`cmake/check_link_atomic.cmake`**: guard the entire atomic check
behind `if (NOT (EMSCRIPTEN OR Z3_SINGLE_THREADED))`. Emscripten sets
`EMSCRIPTEN` automatically via `emcmake`; Pyodide builds also pass
`-DZ3_SINGLE_THREADED=TRUE`, so either condition is sufficient to bypass
the check safely.

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/44788_1965f0d6d94d5d8054ba_34_QF_UFDTBV.smt2 |    0.078s | 20.576MiB| unsat | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_6_QF_UFDTBV.smt2 |    0.097s | 34.312MiB| sat | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_55_QF_UFDTBV.smt2 |    0.225s | 31.708MiB| unsat | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_40_QF_UFDTBV.smt2 |    0.301s | 60.908MiB| sat | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/39657_2866defdd1f2434b69ab_47_QF_UFDTBV.smt2 |    0.649s | 85.336MiB| sat | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_57_QF_UFDTBV.smt2 |    0.784s | 42.404MiB| unsat | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_58_QF_UFDTBV.smt2 |    0.933s | 136.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/72771_f9d228efc97cf1458e38_64_QF_UFDTBV.smt2 |    0.945s | 89.364MiB| sat | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/39657_2866defdd1f2434b69ab_48_QF_UFDTBV.smt2 |    1.140s | 139.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/41958_45c688a4814eb926c254_60_QF_UFDTBV.smt2 |    1.890s | 221.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/44289_4066055e0f64d96da11a_14_QF_UFDTBV.smt2 |   20.139s | 479.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_41_QF_UFDTBV.smt2 |   20.154s | 304.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/63058_64ab9a7ef7b6c3492507_22_QF_UFDTBV.smt2 |   20.167s | 396.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/41958_45c688a4814eb926c254_59_QF_UFDTBV.smt2 |   20.195s | 335.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/63058_64ab9a7ef7b6c3492507_23_QF_UFDTBV.smt2 |   20.224s | 450.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_39_QF_UFDTBV.smt2 |   20.231s | 608.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/44289_4066055e0f64d96da11a_15_QF_UFDTBV.smt2 |   20.246s | 651.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/44289_e5a2e5c780236919ee6a_17_QF_UFDTBV.smt2 |   20.252s | 536.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/44289_e5a2e5c780236919ee6a_18_QF_UFDTBV.smt2 |   20.257s | 535.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/63058_64ab9a7ef7b6c3492507_24_QF_UFDTBV.smt2 |   20.263s | 514.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/39657_1c7158801cd59dc13f05_46_QF_UFDTBV.smt2 |   20.271s | 762.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/39657_1c7158801cd59dc13f05_44_QF_UFDTBV.smt2 |   20.280s | 770.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/39657_1c7158801cd59dc13f05_45_QF_UFDTBV.smt2 |   20.284s | 762.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/63058_55d6bef5390186355f11_26_QF_UFDTBV.smt2 |   20.378s | 960.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/17512_5c1021b0faa6b6e1791b_20_QF_UFDTBV.smt2 |   20.514s | 1124.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/41958_32933c5a1384696720a2_62_QF_UFDTBV.smt2 |   20.525s | 1996.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFDTBV.smt2 |   20.623s | 1923.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/41958_32933c5a1384696720a2_63_QF_UFDTBV.smt2 |   20.703s | 3664.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_7_QF_UFDTBV.smt2 |   20.795s | 3676.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/17512_5c1021b0faa6b6e1791b_21_QF_UFDTBV.smt2 |   20.820s | 3824.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFDTBV.smt2 |   20.859s | 3830.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_8_QF_UFDTBV.smt2 |   21.091s | 3609.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/41958_32933c5a1384696720a2_61_QF_UFDTBV.smt2 |   21.097s | 7301.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFDTBV.smt2 |   21.118s | 3728.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/30078_f817a923328f75af7e60_27_QF_UFDTBV.smt2 |   21.124s | 7517.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/63058_aa742630eef64f949de269382c1f9035_25_UFDTBV.smt2 |   21.140s | 7723.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/38347_525a1ca0331f2bcbf520_54_QF_UFDTBV.smt2 |   21.145s | 7270.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTBV.smt2 |   21.162s | 7473.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/11775_ad46e5b8db4748c51973_42_QF_UFDTBV.smt2 |   21.171s | 7278.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFDTBV.smt2 |   21.177s | 7398.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_38_QF_UFDTBV.smt2 |   21.178s | 3870.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/17512_5c1021b0faa6b6e1791b_19_QF_UFDTBV.smt2 |   21.193s | 3883.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFDTBV.smt2 |   21.201s | 7471.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/44788_1965f0d6d94d5d8054ba_35_QF_UFDTBV.smt2 |   21.219s | 7367.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_1_UFDTBV.smt2 |   21.225s | 7707.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFDTBV.smt2 |   21.233s | 7561.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_0_UFDTBV.smt2 |   21.240s | 7342.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_29_QF_UFDTBV.smt2 |   21.244s | 7701.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTBV.smt2 |   21.253s | 7448.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/44788_1965f0d6d94d5d8054ba_36_QF_UFDTBV.smt2 |   21.258s | 4193.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_3_UFDTBV.smt2 |   21.279s | 7412.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_76_QF_UFDTBV.smt2 |   21.325s | 6902.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/72658_63104dadde9c6026353f_71_QF_UFDTBV.smt2 |   21.512s | 5736.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/72658_63104dadde9c6026353f_70_QF_UFDTBV.smt2 |   21.583s | 5156.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_73_QF_UFDTBV.smt2 |   21.588s | 5276.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_72_QF_UFDTBV.smt2 |   21.634s | 7534.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_75_QF_UFDTBV.smt2 |   21.656s | 7677.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTBV.smt2 |   21.659s | 7447.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFDTBV.smt2 |   21.677s | 7511.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/30078_f817a923328f75af7e60_28_QF_UFDTBV.smt2 |   21.695s | 7526.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/11775_ad46e5b8db4748c51973_43_QF_UFDTBV.smt2 |   21.697s | 7355.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTBV.smt2 |   21.699s | 7519.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_32_QF_UFDTBV.smt2 |   21.699s | 7867.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_74_QF_UFDTBV.smt2 |   21.700s | 7812.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_2_UFDTBV.smt2 |   21.738s | 7728.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_4_UFDTBV.smt2 |   21.745s | 7804.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_33_QF_UFDTBV.smt2 |   21.762s | 7554.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_56_QF_UFDTBV.smt2 |   21.764s | 7252.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/93493_5990a6bf5f2740164f77_50_QF_UFDTBV.smt2 |   21.770s | 7342.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_30_QF_UFDTBV.smt2 |   21.779s | 7804.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/93493_4ea6163ed03941199c785278ccc42812_49_QF_UFDTBV.smt2 |   21.791s | 7310.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_31_QF_UFDTBV.smt2 |   21.792s | 7524.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTBV.smt2 |   21.807s | 7779.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/93493_798593962ee29ad45ac8_52_QF_UFDTBV.smt2 |   21.822s | 8458.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFDTBV.smt2 |   21.935s | 7936.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFBVDT/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_5_QF_UFDTBV.smt2 |   21.951s | 8514.0MiB| timeout | 0 |  |  |
