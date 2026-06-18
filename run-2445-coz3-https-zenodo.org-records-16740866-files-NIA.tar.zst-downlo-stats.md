# .

* SAT 71
* UNSAT 150
* TIMEOUT 36
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/NIA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-NIA.tar.zst-downlo
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: 9091df56cbb91c668c6ef3e26899d2839d38e8a5
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/NIA.tar.zst?download=1
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
|non-incremental/NIA/tptp/NUM879=1.smt2                       |    0.015s | 19.54MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_11.smt2 |    0.016s | 19.864MiB| unsat | 0 |  |  |
|non-incremental/NIA/tptp/NUM882=1.smt2                       |    0.016s | 19.148MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_1.smt2 |    0.017s | 19.92MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_0.smt2 |    0.017s | 20.048MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_0.smt2 |    0.018s | 19.92MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_11.smt2 |    0.018s | 20.124MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_7.smt2 |    0.018s | 20.232MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_0.smt2 |    0.018s | 20.24MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/sum02_false-unreach-call_true-no-overflow.c_0.smt2 |    0.018s | 19.796MiB| unsat | 0 |  |  |
|non-incremental/NIA/tptp/ARI118=1.smt2                       |    0.018s | 20.252MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_65.smt2 |    0.019s | 20.248MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_93.smt2 |    0.019s | 20.28MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_63.smt2 |    0.019s | 20.44MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_64.smt2 |    0.019s | 20.452MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_9.smt2 |    0.019s | 20.452MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_11.smt2 |    0.019s | 20.4MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_89.smt2 |    0.019s | 20.316MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_19.smt2 |    0.020s | 20.3MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_11.smt2 |    0.020s | 20.592MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/gcd_3_true-unreach-call_true-no-overflow.i_2.smt2 |    0.020s | 20.336MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_19.smt2 |    0.020s | 20.556MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_0.smt2 |    0.020s | 20.54MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_3.smt2 |    0.020s | 20.256MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_8.smt2 |    0.020s | 20.348MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_25.smt2 |    0.020s | 20.496MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_84.smt2 |    0.020s | 20.304MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_80.smt2 |    0.020s | 20.468MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_48.smt2 |    0.020s | 20.532MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_5.smt2 |    0.020s | 20.596MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_8.smt2 |    0.020s | 20.484MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_13.smt2 |    0.020s | 20.352MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/sum02_false-unreach-call_true-no-overflow.c_1.smt2 |    0.020s | 19.972MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_1.smt2 |    0.020s | 20.316MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_2.smt2 |    0.020s | 20.416MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_8.smt2 |    0.020s | 20.452MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_34.smt2 |    0.020s | 20.32MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_33.smt2 |    0.020s | 20.456MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_17.smt2 |    0.020s | 20.336MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_12.smt2 |    0.020s | 20.524MiB| sat | 0 |  |  |
|non-incremental/NIA/tptp/NUM878=1.smt2                       |    0.020s | 20.04MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_94.smt2 |    0.021s | 20.568MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_68.smt2 |    0.021s | 20.284MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_20.smt2 |    0.021s | 20.468MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_4.smt2 |    0.021s | 20.512MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_46.smt2 |    0.021s | 20.372MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_58.smt2 |    0.021s | 20.404MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_9.smt2 |    0.021s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_9.smt2 |    0.021s | 20.352MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_7.smt2 |    0.021s | 20.316MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_12.smt2 |    0.021s | 20.568MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_29.smt2 |    0.021s | 20.368MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_0.smt2 |    0.021s | 20.732MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_69.smt2 |    0.021s | 20.396MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_88.smt2 |    0.021s | 20.264MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_18.smt2 |    0.021s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_37.smt2 |    0.021s | 20.44MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_1.smt2 |    0.021s | 20.516MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/byte_add_1_true-unreach-call_true-no-overflow_true-termination.i_1.smt2 |    0.021s | 20.184MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_24.smt2 |    0.021s | 20.096MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_3.smt2 |    0.022s | 20.348MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_55.smt2 |    0.022s | 20.524MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_5.smt2 |    0.022s | 20.616MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_67.smt2 |    0.022s | 20.516MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_13.smt2 |    0.022s | 20.508MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_2.smt2 |    0.022s | 20.664MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_21.smt2 |    0.022s | 20.372MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_44.smt2 |    0.022s | 20.452MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_40.smt2 |    0.022s | 20.536MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_2.smt2 |    0.022s | 20.404MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/byte_add_1_true-unreach-call_true-no-overflow_true-termination.i_2.smt2 |    0.022s | 20.168MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_9.smt2 |    0.022s | 20.42MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_86.smt2 |    0.022s | 20.48MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_13.smt2 |    0.022s | 20.652MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_35.smt2 |    0.022s | 20.492MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_28.smt2 |    0.022s | 20.488MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_36.smt2 |    0.022s | 20.496MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_10.smt2 |    0.022s | 20.796MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_42.smt2 |    0.022s | 20.552MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_43.smt2 |    0.022s | 20.472MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_24.smt2 |    0.023s | 20.592MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_15.smt2 |    0.023s | 20.388MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_6.smt2 |    0.023s | 20.788MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_23.smt2 |    0.023s | 20.52MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_6.smt2 |    0.023s | 20.524MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_10.smt2 |    0.023s | 20.408MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_18.smt2 |    0.024s | 20.524MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_26.smt2 |    0.024s | 20.388MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_85.smt2 |    0.024s | 20.368MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_9.smt2 |    0.024s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_7.smt2 |    0.024s | 20.608MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_60.smt2 |    0.024s | 20.728MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_30.smt2 |    0.024s | 20.54MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_32.smt2 |    0.024s | 20.472MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_10.smt2 |    0.024s | 20.348MiB| sat | 0 |  |  |
|non-incremental/NIA/psyco/060.smt2                           |    0.024s | 20.472MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_7.smt2 |    0.025s | 20.42MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_91.smt2 |    0.025s | 20.512MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_66.smt2 |    0.025s | 20.444MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_39.smt2 |    0.025s | 20.42MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_76.smt2 |    0.025s | 21.004MiB| unsat | 0 |  |  |
|non-incremental/NIA/psyco/059.smt2                           |    0.025s | 20.46MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_62.smt2 |    0.026s | 20.868MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_22.smt2 |    0.026s | 20.708MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_92.smt2 |    0.026s | 20.652MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/pals_lcr-var-start-time.6_true-unreach-call.ufo.UNBOUNDED.pals.c_1.smt2 |    0.026s | 20.46MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_5.smt2 |    0.026s | 20.38MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_87.smt2 |    0.026s | 20.38MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/byte_add_1_true-unreach-call_true-no-overflow_true-termination.i_0.smt2 |    0.027s | 20.444MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_45.smt2 |    0.027s | 20.48MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_74.smt2 |    0.027s | 20.564MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_5.smt2 |    0.028s | 20.348MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_12.smt2 |    0.028s | 20.496MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_11.smt2 |    0.028s | 20.344MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_59.smt2 |    0.028s | 20.74MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_7.smt2 |    0.029s | 20.992MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_4.smt2 |    0.029s | 20.816MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_21.smt2 |    0.029s | 20.676MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/byte_add_1_true-unreach-call_true-no-overflow_true-termination.i_3.smt2 |    0.030s | 20.048MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_3.smt2 |    0.030s | 20.632MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_25.smt2 |    0.030s | 20.62MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_16.smt2 |    0.030s | 20.172MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_3.smt2 |    0.030s | 20.468MiB| unsat | 0 |  |  |
|non-incremental/NIA/psyco/182.smt2                           |    0.030s | 20.244MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_41.smt2 |    0.031s | 20.4MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_4.smt2 |    0.031s | 20.508MiB| sat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/ps4-ll.c_1.smt2 |    0.031s | 20.58MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_79.smt2 |    0.032s | 20.368MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_72.smt2 |    0.032s | 21.624MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_13.smt2 |    0.032s | 20.472MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_71.smt2 |    0.032s | 21.52MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_27.smt2 |    0.033s | 20.564MiB| unsat | 0 |  |  |
|non-incremental/NIA/tptp/NUM880=1.smt2                       |    0.033s | 19.492MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_23.smt2 |    0.034s | 20.672MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_70.smt2 |    0.034s | 21.588MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_75.smt2 |    0.034s | 20.648MiB| sat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/gauss_sum.i_0.smt2 |    0.034s | 20.568MiB| sat | 0 |  |  |
|non-incremental/NIA/tptp/NUM881=1.smt2                       |    0.034s | 18.992MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_31.smt2 |    0.035s | 20.328MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_61.smt2 |    0.035s | 20.844MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_6.smt2 |    0.035s | 20.444MiB| sat | 0 |  |  |
|non-incremental/NIA/tptp/ARI123=1.smt2                       |    0.035s | 20.532MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_82.smt2 |    0.036s | 21.156MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_14.smt2 |    0.036s | 20.292MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_38.smt2 |    0.037s | 20.296MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_6.smt2 |    0.037s | 20.636MiB| sat | 0 |  |  |
|non-incremental/NIA/tptp/NUM886=1.smt2                       |    0.037s | 19.42MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_49.smt2 |    0.038s | 20.536MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_18.smt2 |    0.038s | 20.8MiB| sat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/egcd2-ll.c_2.smt2 |    0.038s | 20.284MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_1.smt2 |    0.040s | 20.608MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_77.smt2 |    0.040s | 20.424MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_10.smt2 |    0.040s | 20.54MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_16.smt2 |    0.041s | 20.452MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/gcd_3_true-unreach-call_true-no-overflow.i_1.smt2 |    0.041s | 20.38MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_81.smt2 |    0.044s | 20.504MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/implicitunsignedconversion_true-unreach-call_true-termination.c_0.smt2 |    0.044s | 20.052MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_73.smt2 |    0.044s | 20.496MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_78.smt2 |    0.046s | 20.424MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_90.smt2 |    0.046s | 21.384MiB| unsat | 0 |  |  |
|non-incremental/NIA/psyco/183.smt2                           |    0.046s | 20.964MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_2.smt2 |    0.048s | 20.376MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_83.smt2 |    0.050s | 21.08MiB| unsat | 0 |  |  |
|non-incremental/NIA/20240413-AutomizerLoopAcceleration/in-de62.c_AllErrorsAtOnce_Iteration8_0.smt2 |    0.055s | 20.52MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/gcd_2_true-unreach-call_true-no-overflow.i_0.smt2 |    0.056s | 21.176MiB| unsat | 0 |  |  |
|non-incremental/NIA/tptp/NUM885=1.smt2                       |    0.058s | 19.576MiB| sat | 0 |  |  |
|non-incremental/NIA/psyco/184.smt2                           |    0.059s | 21.08MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_4.smt2 |    0.061s | 21.176MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_95.smt2 |    0.066s | 21.036MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_15.smt2 |    0.075s | 21.676MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_4.smt2 |    0.080s | 20.864MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_22.smt2 |    0.081s | 21.228MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_97.smt2 |    0.081s | 21.248MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/dijkstra.c_7.smt2 |    0.082s | 20.492MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_2.smt2 |    0.087s | 20.732MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_17.smt2 |    0.096s | 21.704MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_0.smt2 |    0.096s | 21.124MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/gcd_3_true-unreach-call_true-no-overflow.i_0.smt2 |    0.131s | 21.364MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_18.smt2 |    0.155s | 21.84MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_12.smt2 |    0.156s | 22.344MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_8.smt2 |    0.188s | 21.192MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_13.smt2 |    0.205s | 22.328MiB| sat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/jain_6-1.c_0.smt2 |    0.252s | 21.368MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_3.smt2 |    0.307s | 21.584MiB| sat | 0 |  |  |
|non-incremental/NIA/20240413-AutomizerLoopAcceleration/in-de51.c_AllErrorsAtOnce_Iteration8_0.smt2 |    0.320s | 21.588MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_18.smt2 |    0.378s | 21.596MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/jain_6-1.c_2.smt2 |    0.404s | 21.588MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_1.smt2 |    0.406s | 21.16MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_14.smt2 |    0.415s | 22.776MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/jain_4-2.c_0.smt2 |    0.534s | 21.908MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_98.smt2 |    0.590s | 22.384MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_16.smt2 |    0.607s | 21.772MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_6.smt2 |    0.809s | 21.708MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_16.smt2 |    0.812s | 22.428MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_20.smt2 |    0.917s | 22.424MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_96.smt2 |    1.464s | 22.752MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_8.smt2 |    2.021s | 23.128MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_2.smt2 |    2.232s | 22.568MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_10.smt2 |    2.724s | 22.812MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_15.smt2 |    3.422s | 24.924MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_1.smt2 |    3.448s | 29.764MiB| sat | 0 |  |  |
|non-incremental/NIA/20240413-AutomizerLoopAcceleration/gsv2008.c.i.v+lhb-reducer.c_AllErrorsAtOnce_Iteration2_0.smt2 |    4.181s | 78.38MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_7.smt2 |    7.512s | 51.98MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_14.smt2 |    7.551s | 51.788MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_15.smt2 |    7.647s | 52.004MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_11.smt2 |    7.878s | 51.984MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_9.smt2 |    7.888s | 52.012MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_8.smt2 |    7.893s | 51.904MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_16.smt2 |    7.937s | 51.884MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_17.smt2 |    8.038s | 52.008MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_10.smt2 |    8.068s | 51.796MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_12.smt2 |    8.376s | 52.3MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_13.smt2 |    8.379s | 52.236MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_11.smt2 |    8.441s | 27.8MiB| sat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_2.smt2 |    8.798s | 53.676MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_3.smt2 |    8.835s | 53.648MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_5.smt2 |    9.020s | 53.656MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_6.smt2 |    9.692s | 53.22MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_1.smt2 |    9.990s | 32.424MiB| unsat | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_4.smt2 |   10.504s | 54.172MiB| unsat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_0.smt2 |   18.751s | 37.94MiB| sat | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_3.smt2 |   20.007s | 29.052MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/egcd2-ll.c_0.smt2 |   20.007s | 37.892MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/egcd2-ll.c_1.smt2 |   20.007s | 40.848MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_5.smt2 |   20.008s | 62.712MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/jain_7-2.c_0.smt2 |   20.008s | 62.388MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_12.smt2 |   20.009s | 84.668MiB| timeout | 0 |  |  |
|non-incremental/NIA/20240413-AutomizerLoopAcceleration/in-de61.c_AllErrorsAtOnce_Iteration6_0.smt2 |   20.009s | 38.904MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_4.smt2 |   20.010s | 34.968MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_13.smt2 |   20.011s | 30.024MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_9.smt2 |   20.011s | 113.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_17.smt2 |   20.011s | 29.588MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/dijkstra.c_1.smt2 |   20.011s | 50.492MiB| timeout | 0 |  |  |
|non-incremental/NIA/20240413-AutomizerLoopAcceleration/in-de41.c_AllErrorsAtOnce_Iteration5_0.smt2 |   20.011s | 25.656MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_14.smt2 |   20.012s | 90.94MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_7.smt2 |   20.012s | 32.34MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_0.smt2 |   20.012s | 51.856MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_10.smt2 |   20.013s | 112.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/dijkstra.c_3.smt2 |   20.013s | 24.372MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/jain_7-2.c_2.smt2 |   20.014s | 50.052MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_17.smt2 |   20.015s | 103.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_8.smt2 |   20.016s | 106.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/dijkstra.c_6.smt2 |   20.017s | 48.468MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_5.smt2 |   20.018s | 30.948MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_11.smt2 |   20.020s | 117.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20240413-AutomizerLoopAcceleration/gsv2008.c.i.p+cfa-reducer.c_AllErrorsAtOnce_Iteration2_0.smt2 |   20.020s | 97.544MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/jain_7-2.c_1.smt2 |   20.021s | 36.156MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/dijkstra.c_0.smt2 |   20.021s | 21.716MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_16.smt2 |   20.022s | 37.16MiB| timeout | 0 |  |  |
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_6.smt2 |   20.028s | 40.688MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/modulus-1.c_3.smt2 |   20.203s | 1754.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/modulus-1.c_0.smt2 |   20.236s | 2240.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/modulus-1.c_1.smt2 |   20.245s | 2272.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/modulus-1.c_8.smt2 |   20.248s | 2443.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/gcd_2.c_0.smt2 |   20.388s | 4834.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/gcd_2.c_1.smt2 |   20.389s | 4960.0MiB| timeout | 0 |  |  |
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/gcd_2.c_2.smt2 |   20.482s | 6587.0MiB| timeout | 0 |  |  |
