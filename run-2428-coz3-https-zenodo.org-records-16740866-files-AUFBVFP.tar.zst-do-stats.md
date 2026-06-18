# .

* SAT 3
* UNSAT 6
* TIMEOUT 48
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/AUFBVFP.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-AUFBVFP.tar.zst-do
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: 9091df56cbb91c668c6ef3e26899d2839d38e8a5
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/AUFBVFP.tar.zst?download=1
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
|non-incremental/AUFBVFP/20210301-Alive2-partial-undef/ph7/583_ph7.smt2 |    0.358s | 114.0MiB| unsat | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/340_oggenc.smt2 |    0.458s | 35.656MiB| sat | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/392_oggenc.smt2 |    1.652s | 44.372MiB| sat | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/ph7/611_ph7.smt2     |    1.747s | 41.688MiB| unsat | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/290_oggenc.smt2 |    2.802s | 338.0MiB| unsat | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/344_oggenc.smt2 |    3.364s | 46.644MiB| sat | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/455_oggenc.smt2 |    4.033s | 328.0MiB| unsat | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/397_oggenc.smt2 |    7.560s | 60.144MiB| unsat | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2-partial-undef/sqlite3/816_sqlite3.smt2 |    9.115s | 66.676MiB| unsat | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/434_oggenc.smt2 |   20.022s | 220.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2-partial-undef/oggenc/351_oggenc.smt2 |   20.032s | 35.472MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/ph7/568_ph7.smt2     |   20.040s | 88.264MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2-partial-undef/oggenc/374_oggenc.smt2 |   20.040s | 105.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/411_oggenc.smt2 |   20.042s | 46.916MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/ph7/757_ph7.smt2     |   20.056s | 98.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/bzip2/001_bzip2.smt2 |   20.058s | 127.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2-partial-undef/ph7/744_ph7.smt2 |   20.061s | 93.392MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2-partial-undef/oggenc/384_oggenc.smt2 |   20.061s | 101.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/sqlite3/892_sqlite3.smt2 |   20.064s | 101.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/445_oggenc.smt2 |   20.067s | 194.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2-partial-undef/oggenc/357_oggenc.smt2 |   20.073s | 101.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2-partial-undef/oggenc/392_oggenc.smt2 |   20.077s | 117.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/322_oggenc.smt2 |   20.080s | 129.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/354_oggenc.smt2 |   20.109s | 136.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/426_oggenc.smt2 |   20.110s | 254.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/422_oggenc.smt2 |   20.112s | 166.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/324_oggenc.smt2 |   20.113s | 268.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/277_oggenc.smt2 |   20.120s | 243.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/356_oggenc.smt2 |   20.120s | 258.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2-partial-undef/oggenc/352_oggenc.smt2 |   20.131s | 252.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/410_oggenc.smt2 |   20.132s | 221.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/295_oggenc.smt2 |   20.147s | 267.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/342_oggenc.smt2 |   20.152s | 269.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/449_oggenc.smt2 |   20.153s | 274.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/305_oggenc.smt2 |   20.155s | 422.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/288_oggenc.smt2 |   20.158s | 352.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/368_oggenc.smt2 |   20.169s | 447.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/sqlite3/917_sqlite3.smt2 |   20.173s | 408.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/293_oggenc.smt2 |   20.177s | 450.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/300_oggenc.smt2 |   20.195s | 476.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/343_oggenc.smt2 |   20.197s | 559.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/409_oggenc.smt2 |   20.200s | 679.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/369_oggenc.smt2 |   20.204s | 555.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/459_oggenc.smt2 |   20.215s | 549.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2-partial-undef/oggenc/386_oggenc.smt2 |   20.216s | 663.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/358_oggenc.smt2 |   20.218s | 791.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/303_oggenc.smt2 |   20.223s | 666.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/446_oggenc.smt2 |   20.313s | 1369.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/430_oggenc.smt2 |   20.331s | 1798.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2-partial-undef/sqlite3/870_sqlite3.smt2 |   20.466s | 3148.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/453_oggenc.smt2 |   20.494s | 3568.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/461_oggenc.smt2 |   20.602s | 5084.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/385_oggenc.smt2 |   20.628s | 5165.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2-partial-undef/oggenc/346_oggenc.smt2 |   20.702s | 6299.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2-partial-undef/oggenc/344_oggenc.smt2 |   20.716s | 6502.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2/oggenc/457_oggenc.smt2 |   20.773s | 7312.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVFP/20210301-Alive2-partial-undef/ph7/489_ph7.smt2 |   20.775s | 7764.0MiB| timeout | 0 |  |  |
