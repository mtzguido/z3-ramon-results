# .

* SAT 30
* UNSAT 5
* TIMEOUT 141
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/QF_ALIA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-QF_ALIA.tar.zst-do
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 459629c662eb7abf25a010b7383431a9f729d234
Z3 branch: master
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/QF_ALIA.tar.zst?download=1
Z3 commit message: bugfixes to ho_matcher

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/QF_ALIA/piVC/piVC_ffa5fa.smt2                |    0.024s | 19.72MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_stateful-1.i_2.smt2 |    0.054s | 24.728MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_sync.i_1.smt2 |    0.061s | 24.836MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_stateful-1.i_4.smt2 |    0.065s | 24.868MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_lazy.i_6.smt2 |    0.066s | 25.136MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_read_write_lock-1.i_0.smt2 |    0.089s | 28.736MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/misc/stack-th1-6.smt2 |    0.100s | 19.856MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_szymanski.i_6.smt2 |    0.118s | 33.276MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_sync.i_0.smt2 |    0.122s | 25.116MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/misc/queue-th2-6.smt2 |    0.126s | 19.828MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/misc/queue-th1-6.smt2 |    0.129s | 19.608MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/misc/stack-th2-6.smt2 |    0.130s | 19.592MiB| unsat | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/misc/stack-invalid-6.smt2 |    0.131s | 19.652MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_peterson.i_0.smt2 |    0.133s | 35.472MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_lamport.i_0.smt2 |    0.134s | 37.356MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_time_var_mutex.i_0.smt2 |    0.144s | 37.22MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_sync.i_3.smt2 |    0.148s | 24.636MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_stateful-1.i_3.smt2 |    0.152s | 24.808MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_lazy.i_7.smt2 |    0.153s | 25.132MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_lazy.i_3.smt2 |    0.154s | 25.628MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_sync.i_6.smt2 |    0.155s | 24.672MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_stateful-1.i_1.smt2 |    0.157s | 24.792MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_sync.i_4.smt2 |    0.158s | 24.624MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_sync.i_2.smt2 |    0.162s | 24.624MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_szymanski.i_7.smt2 |    0.199s | 33.392MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_szymanski.i_1.smt2 |    0.206s | 33.336MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_szymanski.i_5.smt2 |    0.216s | 33.676MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_szymanski.i_2.smt2 |    0.216s | 33.68MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_szymanski.i_0.smt2 |    0.217s | 33.324MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_dekker.i_0.smt2 |    0.221s | 35.416MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_fib-1.i_0.smt2 |    0.781s | 79.576MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_fib-2.i_0.smt2 |    0.872s | 79.936MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_queue-1.i_0.smt2 |    0.939s | 79.168MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_fib_longer-2.i_0.smt2 |    1.432s | 101.0MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_fib_longer-1.i_0.smt2 |    1.450s | 101.0MiB| sat | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.29.smt2       |   20.011s | 23.616MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.9.smt2        |   20.011s | 21.336MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.10.smt2            |   20.011s | 21.248MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_np_sf_ai_00006_001.cvc.smt2 |   20.012s | 20.04MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.22.smt2            |   20.013s | 22.556MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/piVC/piVC_3031c9.smt2                |   20.014s | 24.104MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/piVC/piVC_5b181b.smt2                |   20.014s | 20.052MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.17.smt2       |   20.016s | 22.304MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/AllInterval-015.c_AllErrorsAtOnce_Iteration2_0.smt2 |   20.019s | 21.716MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/tree-3.i_7.smt2 |   20.019s | 24.952MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_np_sf_ai_00010_001.cvc.smt2 |   20.024s | 20.4MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_read_write_lock-2.i_0.smt2 |   20.027s | 20.672MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/tree-4.i_11.smt2 |   20.028s | 68.004MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/tree-4.i_4.smt2 |   20.033s | 69.364MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/cvc/pp-dmem2.smt2                    |   20.033s | 21.66MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/cvc/pp-bloaddata.smt2                |   20.035s | 21.92MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/cvc/read2.smt2                       |   20.036s | 20.208MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/cvc/pp-dmem-a.smt2                   |   20.036s | 21.572MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/cvc/pp-bloaddata-a.smt2              |   20.039s | 21.832MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_bia_np_sf_ai_00008_001.cvc.smt2 |   20.045s | 20.368MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_np_sf_ai_00011_001.cvc.smt2 |   20.046s | 20.46MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/qlock/qlock-mutex-15.smt2 |   20.047s | 21.648MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/qlock/qlock-mutex-5.smt2 |   20.049s | 20.764MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_np_sf_ai_00008_001.cvc.smt2 |   20.049s | 20.332MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/piVC/piVC_ed9849.smt2                |   20.051s | 20.828MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_bia_np_sf_ai_00012_001.cvc.smt2 |   20.051s | 20.416MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.14.smt2            |   20.051s | 21.552MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.30.smt2       |   20.052s | 23.764MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.26.smt2       |   20.053s | 23.288MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/qlock/qlock-bug-20.smt2 |   20.055s | 22.124MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.10.smt2       |   20.055s | 21.516MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.28.smt2            |   20.055s | 23.22MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.8.smt2             |   20.056s | 20.852MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.12.smt2       |   20.056s | 21.472MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/piVC/piVC_fdec13.smt2                |   20.057s | 20.872MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/piVC/piVC_13f61c.smt2                |   20.059s | 20.864MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.11.smt2       |   20.059s | 21.572MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.24.smt2       |   20.059s | 23.208MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_np_sf_ai_00007_001.cvc.smt2 |   20.061s | 20.116MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/piVC/piVC_cb19c7.smt2                |   20.062s | 19.876MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.28.smt2       |   20.062s | 23.408MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.24.smt2            |   20.062s | 22.772MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/qlock/qlock-bug2-15.smt2 |   20.063s | 21.916MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.11.smt2            |   20.066s | 21.376MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/qlock/qlock-bug2-10.smt2 |   20.068s | 21.132MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_bia_np_sf_ai_00004_001.cvc.smt2 |   20.069s | 20.228MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.20.smt2       |   20.071s | 22.688MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_bia_np_sf_ai_00005_001.cvc.smt2 |   20.072s | 20.328MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.6.smt2        |   20.072s | 21.008MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/piVC/piVC_509c40.smt2                |   20.073s | 23.268MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_bia_np_sf_ai_00006_001.cvc.smt2 |   20.073s | 20.108MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.19.smt2            |   20.073s | 22.232MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/qlock/qlock-bug2-20.smt2 |   20.074s | 22.152MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/pointer/pointer-invalid-5.smt2 |   20.074s | 20.676MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_np_sf_ai_00004_001.cvc.smt2 |   20.074s | 20.196MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_bia_np_sf_ai_00003_001.cvc.smt2 |   20.074s | 19.936MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_bia_np_sf_ai_00013_001.cvc.smt2 |   20.074s | 20.708MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/piVC/piVC_f5059f.smt2                |   20.075s | 23.22MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.6.smt2             |   20.075s | 20.94MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/qlock/qlock-bug-5.smt2 |   20.077s | 20.692MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/piVC/piVC_408ff0.smt2                |   20.077s | 21.844MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/piVC/piVC_174f4d.smt2                |   20.077s | 19.928MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/piVC/piVC_22b1f2.smt2                |   20.078s | 23.26MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.27.smt2            |   20.078s | 23.064MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/qlock/qlock-bug-10.smt2 |   20.079s | 21.464MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_bia_np_sf_ai_00011_001.cvc.smt2 |   20.079s | 20.584MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.18.smt2       |   20.079s | 22.488MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.25.smt2       |   20.079s | 23.256MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.23.smt2            |   20.079s | 22.732MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/qlock/qlock-bug-15.smt2 |   20.080s | 21.784MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.29.smt2            |   20.080s | 23.384MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.20.smt2            |   20.080s | 22.132MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.12.smt2            |   20.080s | 21.536MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_np_sf_ai_00014_001.cvc.smt2 |   20.081s | 20.36MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/piVC/piVC_d421cb.smt2                |   20.082s | 20.912MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_np_sf_ai_00002_001.cvc.smt2 |   20.082s | 20.108MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_bia_np_sf_ai_00015_001.cvc.smt2 |   20.082s | 20.644MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.5.smt2             |   20.082s | 20.772MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.30.smt2            |   20.082s | 23.484MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/qlock/qlock-mutex-10.smt2 |   20.083s | 21.432MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/pointer/pointer-safe-15.smt2 |   20.083s | 22.076MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_bia_np_sf_ai_00007_001.cvc.smt2 |   20.083s | 20.316MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.13.smt2            |   20.083s | 21.636MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.21.smt2            |   20.083s | 22.568MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/qlock/qlock-mutex-20.smt2 |   20.084s | 22.348MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_bia_np_sf_ai_00001_001.cvc.smt2 |   20.084s | 19.84MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_np_sf_ai_00009_001.cvc.smt2 |   20.092s | 20.336MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.14.smt2       |   20.093s | 22.004MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/tree-4.i_2.smt2 |   20.094s | 67.476MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_np_sf_ai_00012_001.cvc.smt2 |   20.096s | 20.5MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/AllInterval-011.c_AllErrorsAtOnce_Iteration2_0.smt2 |   20.102s | 20.988MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/tree-4.i_1.smt2 |   20.103s | 67.712MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.9.smt2             |   20.110s | 21.148MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_np_sf_ai_00001_001.cvc.smt2 |   20.111s | 20.104MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/pointer/pointer-safe-20.smt2 |   20.113s | 22.812MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_bia_np_sf_ai_00014_001.cvc.smt2 |   20.113s | 20.352MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.27.smt2       |   20.113s | 23.316MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/CostasArray-15.c_AllErrorsAtOnce_Iteration2_0.smt2 |   20.114s | 26.8MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/pointer/pointer-invalid-20.smt2 |   20.114s | 22.72MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/pointer/pointer-safe-10.smt2 |   20.114s | 21.532MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.8.smt2        |   20.114s | 21.232MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.18.smt2            |   20.115s | 22.028MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/AllInterval-016.c_AllErrorsAtOnce_Iteration2_0.smt2 |   20.116s | 21.868MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.7.smt2        |   20.116s | 21.144MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/AllInterval-019.c_AllErrorsAtOnce_Iteration2_0.smt2 |   20.117s | 22.804MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_bia_np_sf_ai_00010_001.cvc.smt2 |   20.117s | 20.356MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.17.smt2            |   20.117s | 21.856MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/piVC/piVC_7fd2c4.smt2                |   20.118s | 19.892MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_bia_np_sf_ai_00009_001.cvc.smt2 |   20.118s | 20.4MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_bia_np_sf_ai_00002_001.cvc.smt2 |   20.118s | 19.896MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.23.smt2       |   20.118s | 22.884MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.13.smt2       |   20.118s | 21.896MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.19.smt2       |   20.118s | 22.596MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.26.smt2            |   20.118s | 22.9MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.15.smt2            |   20.119s | 21.9MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.16.smt2            |   20.119s | 22.008MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_np_sf_ai_00003_001.cvc.smt2 |   20.120s | 20.132MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.25.smt2            |   20.120s | 22.852MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/tree-3.i_6.smt2 |   20.121s | 25.904MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/pointer/pointer-invalid-10.smt2 |   20.121s | 21.484MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_np_sf_ai_00005_001.cvc.smt2 |   20.122s | 19.992MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.base.7.smt2             |   20.122s | 20.812MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/cs_queue-2.i_0.smt2 |   20.123s | 21.616MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_np_sf_ai_00013_001.cvc.smt2 |   20.123s | 20.408MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/ios/ios_t1_ios_np_sf_ai_00015_001.cvc.smt2 |   20.123s | 20.612MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.21.smt2       |   20.123s | 22.72MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/pointer/pointer-invalid-15.smt2 |   20.124s | 22.016MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/array_benchmarks/pointer/pointer-safe-5.smt2 |   20.124s | 20.904MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.22.smt2       |   20.124s | 22.668MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.5.smt2        |   20.125s | 20.872MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.15.smt2       |   20.125s | 22.088MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/tree-4.i_3.smt2 |   20.126s | 68.484MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/tree-4.i_5.smt2 |   20.126s | 68.5MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/piVC/piVC_46582a.smt2                |   20.126s | 23.16MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/qlock2/qlock.induction.16.smt2       |   20.126s | 22.124MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/tree-4.i_6.smt2 |   20.127s | 67.972MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/tree-4.i_8.smt2 |   20.129s | 68.316MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/tree-4.i_9.smt2 |   20.129s | 67.768MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/tree-4.i_0.smt2 |   20.129s | 67.74MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/tree-4.i_10.smt2 |   20.131s | 67.068MiB| timeout | 0 |  |  |
|non-incremental/QF_ALIA/20230321-UltimateAutomizerSvcomp2023/tree-4.i_7.smt2 |   20.131s | 67.996MiB| timeout | 0 |  |  |
