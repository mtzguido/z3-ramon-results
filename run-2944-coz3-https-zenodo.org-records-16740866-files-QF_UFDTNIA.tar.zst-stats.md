# .

* SAT 35
* UNSAT 9
* TIMEOUT 36
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_UFDTNIA.tar.zst?download=1 | Source list: benchmarks-qf.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_UFDTNIA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 2081918cea27e604b9077a6c36acb2ac28aa5b78
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_UFDTNIA.tar.zst?download=1
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
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/63058_aa742630eef64f949de269382c1f9035_25_UFDTNIA.smt2 |    0.078s | 24.056MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_6_QF_UFDTNIA.smt2 |    0.082s | 21.78MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_40_QF_UFDTNIA.smt2 |    0.102s | 24.044MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/41958_45c688a4814eb926c254_60_QF_UFDTNIA.smt2 |    0.211s | 29.864MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/39657_2866defdd1f2434b69ab_47_QF_UFDTNIA.smt2 |    0.240s | 27.32MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/41958_45c688a4814eb926c254_59_QF_UFDTNIA.smt2 |    0.274s | 31.78MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFDTNIA.smt2 |    0.274s | 29.104MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFDTNIA.smt2 |    0.308s | 29.68MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_58_QF_UFDTNIA.smt2 |    0.358s | 28.572MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2 |    0.757s | 30.644MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_8_QF_UFDTNIA.smt2 |    0.912s | 25.932MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/39657_2866defdd1f2434b69ab_48_QF_UFDTNIA.smt2 |    0.973s | 29.648MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/44289_4066055e0f64d96da11a_14_QF_UFDTNIA.smt2 |    0.974s | 43.892MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2 |    1.009s | 28.592MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_0_UFDTNIA.smt2 |    1.129s | 28.736MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_7_QF_UFDTNIA.smt2 |    1.199s | 26.168MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/44289_e5a2e5c780236919ee6a_18_QF_UFDTNIA.smt2 |    1.393s | 51.96MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/44289_e5a2e5c780236919ee6a_17_QF_UFDTNIA.smt2 |    1.421s | 51.064MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/72771_f9d228efc97cf1458e38_64_QF_UFDTNIA.smt2 |    1.584s | 30.228MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/63058_64ab9a7ef7b6c3492507_22_QF_UFDTNIA.smt2 |    1.666s | 46.86MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/63058_55d6bef5390186355f11_26_QF_UFDTNIA.smt2 |    2.070s | 53.024MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/44289_4066055e0f64d96da11a_15_QF_UFDTNIA.smt2 |    2.578s | 78.168MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_72_QF_UFDTNIA.smt2 |    2.647s | 85.084MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/63058_64ab9a7ef7b6c3492507_24_QF_UFDTNIA.smt2 |    2.671s | 74.992MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2 |    3.581s | 25.468MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_2_UFDTNIA.smt2 |    3.740s | 91.136MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_31_QF_UFDTNIA.smt2 |    4.193s | 60.284MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_39_QF_UFDTNIA.smt2 |    4.198s | 69.768MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFDTNIA.smt2 |    4.720s | 67.196MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_41_QF_UFDTNIA.smt2 |    5.081s | 39.288MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/63058_64ab9a7ef7b6c3492507_23_QF_UFDTNIA.smt2 |    5.319s | 53.496MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/39657_1c7158801cd59dc13f05_44_QF_UFDTNIA.smt2 |    5.499s | 67.708MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_1_UFDTNIA.smt2 |    5.671s | 41.784MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTNIA.smt2 |    5.963s | 43.196MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_76_QF_UFDTNIA.smt2 |    6.953s | 140.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2 |    7.361s | 32.216MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/39657_1c7158801cd59dc13f05_45_QF_UFDTNIA.smt2 |    7.409s | 59.768MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFDTNIA.smt2 |    7.604s | 85.38MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFDTNIA.smt2 |    8.771s | 70.204MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/30078_f817a923328f75af7e60_27_QF_UFDTNIA.smt2 |    8.809s | 124.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/39657_1c7158801cd59dc13f05_46_QF_UFDTNIA.smt2 |    9.264s | 62.86MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/30078_f817a923328f75af7e60_28_QF_UFDTNIA.smt2 |   14.819s | 134.0MiB| unsat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_74_QF_UFDTNIA.smt2 |   18.271s | 170.0MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTNIA.smt2 |   19.874s | 58.284MiB| sat | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/41958_32933c5a1384696720a2_63_QF_UFDTNIA.smt2 |   20.012s | 28.984MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_57_QF_UFDTNIA.smt2 |   20.012s | 27.052MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2 |   20.013s | 38.4MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/72658_63104dadde9c6026353f_70_QF_UFDTNIA.smt2 |   20.016s | 41.64MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/72658_63104dadde9c6026353f_71_QF_UFDTNIA.smt2 |   20.017s | 29.46MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_56_QF_UFDTNIA.smt2 |   20.018s | 58.544MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/44788_1965f0d6d94d5d8054ba_34_QF_UFDTNIA.smt2 |   20.019s | 33.016MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_3_UFDTNIA.smt2 |   20.019s | 44.744MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_73_QF_UFDTNIA.smt2 |   20.021s | 114.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20240410-certora/nia-splits/0010.smt2 |   20.023s | 115.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/44788_1965f0d6d94d5d8054ba_36_QF_UFDTNIA.smt2 |   20.023s | 34.588MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/65782_cd31513fdcd15701933b_5_QF_UFDTNIA.smt2 |   20.025s | 40.524MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_30_QF_UFDTNIA.smt2 |   20.026s | 181.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/41958_32933c5a1384696720a2_62_QF_UFDTNIA.smt2 |   20.026s | 28.524MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/44788_1965f0d6d94d5d8054ba_35_QF_UFDTNIA.smt2 |   20.026s | 33.92MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/38347_092cc73601c78e45f4f9_55_QF_UFDTNIA.smt2 |   20.028s | 23.624MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/38347_525a1ca0331f2bcbf520_54_QF_UFDTNIA.smt2 |   20.028s | 121.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_29_QF_UFDTNIA.smt2 |   20.031s | 189.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTNIA.smt2 |   20.031s | 51.168MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFDTNIA.smt2 |   20.032s | 72.98MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_32_QF_UFDTNIA.smt2 |   20.033s | 197.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTNIA.smt2 |   20.033s | 61.624MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/66603_accdadf23a1cf70ae043_75_QF_UFDTNIA.smt2 |   20.034s | 127.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTNIA.smt2 |   20.035s | 44.436MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20240410-certora/lia/0014.smt2    |   20.036s | 237.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/41958_32933c5a1384696720a2_61_QF_UFDTNIA.smt2 |   20.036s | 35.656MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20240410-certora/lia-splits/0011.smt2 |   20.037s | 152.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/93493_798593962ee29ad45ac8_52_QF_UFDTNIA.smt2 |   20.037s | 71.736MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFDTNIA.smt2 |   20.039s | 89.596MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFDTNIA.smt2 |   20.040s | 87.78MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/83314_a702bf8b823398c9e37a_4_UFDTNIA.smt2 |   20.044s | 136.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/93493_5990a6bf5f2740164f77_50_QF_UFDTNIA.smt2 |   20.049s | 202.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/93493_4ea6163ed03941199c785278ccc42812_49_QF_UFDTNIA.smt2 |   20.049s | 190.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/940_590f27b1c3c800d3243e_33_QF_UFDTNIA.smt2 |   20.052s | 181.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20240410-certora/nia/0013.smt2    |   20.054s | 140.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDTNIA/20230314-Jaroslav-Bendik-Certora/3106_1c933134166dbad31f79_38_QF_UFDTNIA.smt2 |   20.057s | 229.0MiB| timeout | 0 |  |  |
