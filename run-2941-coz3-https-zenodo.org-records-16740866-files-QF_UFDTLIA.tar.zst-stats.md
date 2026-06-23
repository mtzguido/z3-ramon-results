# .

* SAT 39
* UNSAT 9
* TIMEOUT 28
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_UFDTLIA.tar.zst?download=1 | Source list: benchmarks-qf.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_UFDTLIA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 2081918cea27e604b9077a6c36acb2ac28aa5b78
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_UFDTLIA.tar.zst?download=1
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
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_6_QF_UFDTLIA.smt2 |    0.054s | 22.364MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/63058_aa742630eef64f949de269382c1f9035_25_UFDTLIA.smt2 |    0.099s | 25.528MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/44788_1965f0d6d94d5d8054ba_34_QF_UFDTLIA.smt2 |    0.100s | 23.944MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_40_QF_UFDTLIA.smt2 |    0.100s | 24.208MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_7_QF_UFDTLIA.smt2 |    0.294s | 26.092MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2 |    0.317s | 34.724MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_58_QF_UFDTLIA.smt2 |    0.322s | 29.756MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFDTLIA.smt2 |    0.331s | 34.364MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_8_QF_UFDTLIA.smt2 |    0.356s | 26.876MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/41958_45c688a4814eb926c254_60_QF_UFDTLIA.smt2 |    0.363s | 34.376MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFDTLIA.smt2 |    0.423s | 31.328MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/44788_1965f0d6d94d5d8054ba_35_QF_UFDTLIA.smt2 |    0.516s | 27.716MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2 |    0.557s | 36.628MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/41958_45c688a4814eb926c254_59_QF_UFDTLIA.smt2 |    0.685s | 39.208MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/72658_63104dadde9c6026353f_70_QF_UFDTLIA.smt2 |    0.794s | 56.428MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_41_QF_UFDTLIA.smt2 |    0.872s | 39.492MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/44289_4066055e0f64d96da11a_14_QF_UFDTLIA.smt2 |    1.035s | 43.628MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/44289_e5a2e5c780236919ee6a_17_QF_UFDTLIA.smt2 |    1.087s | 50.632MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/44289_e5a2e5c780236919ee6a_18_QF_UFDTLIA.smt2 |    1.105s | 49.624MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/39657_1c7158801cd59dc13f05_46_QF_UFDTLIA.smt2 |    1.188s | 56.788MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/39657_1c7158801cd59dc13f05_45_QF_UFDTLIA.smt2 |    1.226s | 56.044MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/63058_55d6bef5390186355f11_26_QF_UFDTLIA.smt2 |    1.297s | 49.74MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/39657_2866defdd1f2434b69ab_48_QF_UFDTLIA.smt2 |    1.342s | 30.776MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/39657_1c7158801cd59dc13f05_44_QF_UFDTLIA.smt2 |    1.383s | 53.568MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/41958_32933c5a1384696720a2_63_QF_UFDTLIA.smt2 |    1.568s | 33.576MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/63058_64ab9a7ef7b6c3492507_23_QF_UFDTLIA.smt2 |    1.618s | 67.52MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/63058_64ab9a7ef7b6c3492507_22_QF_UFDTLIA.smt2 |    1.734s | 46.392MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/44289_4066055e0f64d96da11a_15_QF_UFDTLIA.smt2 |    2.412s | 77.656MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/63058_64ab9a7ef7b6c3492507_24_QF_UFDTLIA.smt2 |    2.830s | 66.98MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_72_QF_UFDTLIA.smt2 |    2.845s | 104.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/72771_f9d228efc97cf1458e38_64_QF_UFDTLIA.smt2 |    2.870s | 33.976MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2 |    2.914s | 70.144MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2 |    4.506s | 75.128MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/41958_32933c5a1384696720a2_62_QF_UFDTLIA.smt2 |    6.100s | 54.32MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_75_QF_UFDTLIA.smt2 |    6.329s | 127.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFDTLIA.smt2 |    6.770s | 81.512MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_55_QF_UFDTLIA.smt2 |    7.201s | 24.26MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFDTLIA.smt2 |    7.495s | 88.3MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFDTLIA.smt2 |    7.519s | 80.568MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFDTLIA.smt2 |    7.782s | 83.92MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_39_QF_UFDTLIA.smt2 |    8.419s | 83.38MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/30078_f817a923328f75af7e60_27_QF_UFDTLIA.smt2 |    8.622s | 140.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_76_QF_UFDTLIA.smt2 |    8.649s | 233.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/39657_2866defdd1f2434b69ab_47_QF_UFDTLIA.smt2 |   13.987s | 38.972MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_74_QF_UFDTLIA.smt2 |   15.606s | 140.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_56_QF_UFDTLIA.smt2 |   16.796s | 151.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFDTLIA.smt2 |   18.703s | 144.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/30078_f817a923328f75af7e60_28_QF_UFDTLIA.smt2 |   19.270s | 147.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/41958_32933c5a1384696720a2_61_QF_UFDTLIA.smt2 |   20.021s | 90.736MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_57_QF_UFDTLIA.smt2 |   20.023s | 29.004MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/93493_5990a6bf5f2740164f77_50_QF_UFDTLIA.smt2 |   20.026s | 185.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_31_QF_UFDTLIA.smt2 |   20.029s | 165.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/93493_798593962ee29ad45ac8_52_QF_UFDTLIA.smt2 |   20.029s | 142.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_0_UFDTLIA.smt2 |   20.033s | 149.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_2_UFDTLIA.smt2 |   20.033s | 200.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/93493_4ea6163ed03941199c785278ccc42812_49_QF_UFDTLIA.smt2 |   20.035s | 200.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_5_QF_UFDTLIA.smt2 |   20.040s | 140.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/44788_1965f0d6d94d5d8054ba_36_QF_UFDTLIA.smt2 |   20.049s | 382.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_73_QF_UFDTLIA.smt2 |   20.051s | 239.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/72658_63104dadde9c6026353f_71_QF_UFDTLIA.smt2 |   20.052s | 214.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2 |   20.054s | 389.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_38_QF_UFDTLIA.smt2 |   20.058s | 259.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_3_UFDTLIA.smt2 |   20.059s | 231.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_29_QF_UFDTLIA.smt2 |   20.059s | 304.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_32_QF_UFDTLIA.smt2 |   20.060s | 291.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFDTLIA.smt2 |   20.062s | 192.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_33_QF_UFDTLIA.smt2 |   20.069s | 285.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTLIA.smt2 |   20.070s | 553.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_30_QF_UFDTLIA.smt2 |   20.071s | 292.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_1_UFDTLIA.smt2 |   20.071s | 328.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTLIA.smt2 |   20.079s | 495.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTLIA.smt2 |   20.107s | 640.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_4_UFDTLIA.smt2 |   20.109s | 653.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTLIA.smt2 |   20.113s | 918.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/38347_525a1ca0331f2bcbf520_54_QF_UFDTLIA.smt2 |   20.133s | 1280.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTLIA/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTLIA.smt2 |   20.150s | 1179.0MiB| timeout | 0 |  |  |
