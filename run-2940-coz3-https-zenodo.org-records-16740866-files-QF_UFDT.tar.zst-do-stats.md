# .

* SAT 3
* UNSAT 0
* TIMEOUT 200
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_UFDT.tar.zst?download=1 | Source list: benchmarks-qf.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_UFDT.tar.zst-do
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 2081918cea27e604b9077a6c36acb2ac28aa5b78
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_UFDT.tar.zst?download=1
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
|non-incremental/QF_UFDT/20170428-Barrett/cdt-cade2015/data/distro/stream_processor/x2015_09_10_16_45_47_401_987519.smt_in.smt2 |    0.045s | 19.852MiB| sat | 0 |  |  |
|non-incremental/QF_UFDT/20170428-Barrett/cdt-cade2015/data/afp/coinductive_list/x2015_09_10_17_01_00_473_1716450.smt_in.smt2 |    0.047s | 19.864MiB| sat | 0 |  |  |
|non-incremental/QF_UFDT/20170428-Barrett/cdt-cade2015/data/distro/stream_processor/x2015_09_10_16_45_54_875_1000989.smt_in.smt2 |    0.048s | 19.844MiB| sat | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e29.smt2     |   20.014s | 33.896MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e94.smt2     |   20.016s | 32.756MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e77.smt2     |   20.017s | 35.756MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k79.smt2     |   20.018s | 33.58MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e82.smt2     |   20.019s | 36.928MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k92.smt2     |   20.020s | 72.784MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e27.smt2     |   20.020s | 37.784MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e54.smt2     |   20.020s | 32.656MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e88.smt2     |   20.021s | 30.724MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e41.smt2     |   20.021s | 32.312MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e03.smt2     |   20.023s | 32.86MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k11.smt2     |   20.023s | 40.072MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k91.smt2     |   20.032s | 178.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k94.smt2     |   20.034s | 35.628MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k86.smt2     |   20.034s | 178.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e81.smt2     |   20.035s | 30.036MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e14.smt2     |   20.035s | 39.088MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e21.smt2     |   20.036s | 31.912MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e57.smt2     |   20.036s | 39.404MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k32.smt2     |   20.036s | 31.58MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e04.smt2     |   20.036s | 37.308MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e74.smt2     |   20.038s | 42.488MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e36.smt2     |   20.040s | 30.544MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k12.smt2     |   20.040s | 37.72MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e34.smt2     |   20.040s | 32.312MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k59.smt2     |   20.041s | 31.196MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e52.smt2     |   20.042s | 36.636MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e73.smt2     |   20.043s | 38.316MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e80.smt2     |   20.044s | 37.16MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e75.smt2     |   20.048s | 29.568MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e83.smt2     |   20.049s | 31.38MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e99.smt2     |   20.049s | 38.124MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k05.smt2     |   20.049s | 43.812MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e67.smt2     |   20.050s | 29.772MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e12.smt2     |   20.050s | 33.364MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e43.smt2     |   20.051s | 32.656MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k19.smt2     |   20.051s | 31.348MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e71.smt2     |   20.051s | 34.1MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k74.smt2     |   20.051s | 35.176MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e24.smt2     |   20.051s | 35.124MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e66.smt2     |   20.053s | 36.372MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k50.smt2     |   20.053s | 38.892MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e78.smt2     |   20.053s | 33.04MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k10.smt2     |   20.054s | 49.736MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e37.smt2     |   20.055s | 38.296MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k75.smt2     |   20.057s | 37.356MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k41.smt2     |   20.058s | 35.184MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k33.smt2     |   20.059s | 38.56MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e50.smt2     |   20.059s | 31.452MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e33.smt2     |   20.059s | 35.2MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k38.smt2     |   20.061s | 35.344MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e56.smt2     |   20.063s | 33.784MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e02.smt2     |   20.064s | 30.896MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e31.smt2     |   20.064s | 33.248MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k24.smt2     |   20.064s | 31.38MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e16.smt2     |   20.066s | 34.596MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e51.smt2     |   20.067s | 33.936MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k27.smt2     |   20.067s | 38.324MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k28.smt2     |   20.067s | 31.996MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e35.smt2     |   20.067s | 37.644MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k70.smt2     |   20.068s | 37.416MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k51.smt2     |   20.069s | 35.132MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k20.smt2     |   20.069s | 31.636MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k16.smt2     |   20.070s | 32.828MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k80.smt2     |   20.070s | 62.7MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k64.smt2     |   20.070s | 33.34MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k23.smt2     |   20.070s | 32.908MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e08.smt2     |   20.070s | 29.96MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e42.smt2     |   20.071s | 31.7MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e20.smt2     |   20.071s | 33.956MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e97.smt2     |   20.071s | 182.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k36.smt2     |   20.071s | 32.644MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k13.smt2     |   20.071s | 29.28MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e11.smt2     |   20.073s | 35.272MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k43.smt2     |   20.073s | 72.476MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e59.smt2     |   20.073s | 34.704MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k04.smt2     |   20.073s | 43.788MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e47.smt2     |   20.074s | 32.536MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k90.smt2     |   20.074s | 34.056MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k35.smt2     |   20.074s | 41.836MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k21.smt2     |   20.074s | 37.512MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e38.smt2     |   20.075s | 31.34MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e22.smt2     |   20.076s | 33.716MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e06.smt2     |   20.076s | 33.14MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k42.smt2     |   20.076s | 39.932MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k25.smt2     |   20.076s | 34.004MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e32.smt2     |   20.077s | 35.744MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k34.smt2     |   20.077s | 34.364MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k98.smt2     |   20.077s | 178.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k26.smt2     |   20.077s | 34.828MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k00.smt2     |   20.078s | 37.104MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e49.smt2     |   20.078s | 32.632MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k08.smt2     |   20.078s | 45.348MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e91.smt2     |   20.079s | 35.376MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e25.smt2     |   20.079s | 33.808MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e58.smt2     |   20.079s | 33.828MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e19.smt2     |   20.080s | 31.796MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k73.smt2     |   20.081s | 31.148MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e92.smt2     |   20.081s | 32.964MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e55.smt2     |   20.081s | 31.972MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e62.smt2     |   20.082s | 36.056MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e17.smt2     |   20.083s | 38.4MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e79.smt2     |   20.084s | 39.9MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k09.smt2     |   20.084s | 38.14MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e44.smt2     |   20.084s | 29.196MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k31.smt2     |   20.085s | 30.736MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k02.smt2     |   20.085s | 34.86MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e00.smt2     |   20.085s | 31.64MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e98.smt2     |   20.086s | 33.48MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e65.smt2     |   20.086s | 37.272MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k56.smt2     |   20.086s | 34.4MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e95.smt2     |   20.086s | 39.66MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k17.smt2     |   20.087s | 45.064MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k68.smt2     |   20.087s | 37.684MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e68.smt2     |   20.088s | 35.64MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k15.smt2     |   20.088s | 34.144MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e15.smt2     |   20.089s | 32.064MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k62.smt2     |   20.089s | 38.776MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k22.smt2     |   20.089s | 29.444MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k60.smt2     |   20.089s | 34.784MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k77.smt2     |   20.091s | 37.624MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e30.smt2     |   20.091s | 29.28MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k03.smt2     |   20.091s | 38.912MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e13.smt2     |   20.091s | 30.644MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k39.smt2     |   20.091s | 72.296MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e23.smt2     |   20.092s | 32.928MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k29.smt2     |   20.092s | 38.448MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e48.smt2     |   20.092s | 31.036MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k99.smt2     |   20.092s | 179.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e60.smt2     |   20.092s | 35.192MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e45.smt2     |   20.093s | 33.376MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e86.smt2     |   20.093s | 39.928MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e63.smt2     |   20.094s | 35.884MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k07.smt2     |   20.094s | 45.448MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k47.smt2     |   20.094s | 77.804MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k37.smt2     |   20.094s | 69.992MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e61.smt2     |   20.095s | 34.684MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k01.smt2     |   20.095s | 34.792MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k65.smt2     |   20.095s | 37.808MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e18.smt2     |   20.095s | 32.108MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e40.smt2     |   20.096s | 33.568MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k93.smt2     |   20.097s | 179.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k06.smt2     |   20.097s | 45.292MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e53.smt2     |   20.098s | 33.08MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k58.smt2     |   20.098s | 32.46MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k40.smt2     |   20.098s | 34.1MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e85.smt2     |   20.098s | 37.592MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e84.smt2     |   20.098s | 32.58MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k84.smt2     |   20.099s | 178.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e09.smt2     |   20.099s | 36.572MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e28.smt2     |   20.099s | 38.712MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e93.smt2     |   20.099s | 30.132MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k30.smt2     |   20.099s | 30.692MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e07.smt2     |   20.100s | 32.98MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e90.smt2     |   20.100s | 38.068MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k57.smt2     |   20.101s | 87.096MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k69.smt2     |   20.102s | 53.484MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k66.smt2     |   20.102s | 29.672MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e89.smt2     |   20.102s | 37.796MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e87.smt2     |   20.102s | 35.572MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e39.smt2     |   20.102s | 32.504MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e05.smt2     |   20.103s | 36.552MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e72.smt2     |   20.103s | 38.408MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k14.smt2     |   20.104s | 30.372MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k95.smt2     |   20.105s | 100.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k76.smt2     |   20.105s | 37.476MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k18.smt2     |   20.106s | 30.492MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e01.smt2     |   20.106s | 31.248MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e76.smt2     |   20.107s | 35.672MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k78.smt2     |   20.107s | 143.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e26.smt2     |   20.107s | 32.484MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k44.smt2     |   20.107s | 184.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k61.smt2     |   20.108s | 37.636MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k52.smt2     |   20.109s | 37.46MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k54.smt2     |   20.109s | 185.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k71.smt2     |   20.110s | 86.328MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k88.smt2     |   20.110s | 118.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e10.smt2     |   20.110s | 34.28MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e69.smt2     |   20.111s | 39.744MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e70.smt2     |   20.111s | 34.708MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k55.smt2     |   20.111s | 188.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e64.smt2     |   20.111s | 37.028MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k83.smt2     |   20.112s | 178.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k48.smt2     |   20.112s | 76.52MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k49.smt2     |   20.113s | 33.312MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k53.smt2     |   20.114s | 172.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e46.smt2     |   20.114s | 34.936MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k72.smt2     |   20.114s | 97.548MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k67.smt2     |   20.114s | 32.12MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k46.smt2     |   20.114s | 76.256MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k89.smt2     |   20.117s | 99.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k87.smt2     |   20.117s | 178.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k63.smt2     |   20.120s | 87.464MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k81.smt2     |   20.120s | 178.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k85.smt2     |   20.121s | 178.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k45.smt2     |   20.122s | 186.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k97.smt2     |   20.122s | 180.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k82.smt2     |   20.126s | 177.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_e96.smt2     |   20.135s | 177.0MiB| timeout | 0 |  |  |
|non-incremental/QF_UFDT/20210312-Bouvier/vlsat3_k96.smt2     |   20.137s | 180.0MiB| timeout | 0 |  |  |
