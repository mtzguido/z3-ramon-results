Comparing data and data


# SUMMARY
- LHS tests = 255
- RHS tests = 255
- LHS success = 255  (100.0%)
- RHS success = 255  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt_qfrdl-threads-4-no_inprocessing
Runner: lev-ripper
Z3 repo: ilanashapiro/z3
Z3 commit: 82e9cc4a848d2c0a9d85241a0ea1f13168231009
Z3 branch: parallel-lockdebug1
Z3 options: "-T:30 smt.threads=4 tactic.default_tactic=smt smt.auto_config.false smt_parallel.inprocessing=false"
Z3 inputs: inputs/QF_RDL
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into parallel-lockdebug1

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt_qfrdl-threads-4-no_inprocessing
Runner: lev-ripper
Z3 repo: ilanashapiro/z3
Z3 commit: 82e9cc4a848d2c0a9d85241a0ea1f13168231009
Z3 branch: parallel-lockdebug1
Z3 options: "-T:30 smt.threads=4 tactic.default_tactic=smt smt.auto_config.false smt_parallel.inprocessing=false"
Z3 inputs: inputs/QF_RDL
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into parallel-lockdebug1

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.227s  |   0.227s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.227s  |   0.227s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.227s  |   0.227s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.227s  |   0.227s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scheduling/swv11_3050.smt2                                                                 |  30.179s |629.0MiB|
|scheduling/yn3_894.smt2                                                                    |  30.147s |310.0MiB|
|scheduling/swv14_2800.smt2                                                                 |  30.143s |645.0MiB|
|scheduling/swv13_3200.smt2                                                                 |  30.141s |701.0MiB|
|scheduling/yn1_827.smt2                                                                    |  30.139s |297.0MiB|
|scheduling/swv14_2885.smt2                                                                 |  30.137s |619.0MiB|
|scheduling/swv12_2972.smt2                                                                 |  30.137s |674.0MiB|
|scheduling/swv11_2900.smt2                                                                 |  30.136s |620.0MiB|
|scheduling/swv14_2905.smt2                                                                 |  30.131s |625.0MiB|
|scheduling/swv12_2900.smt2                                                                 |  30.130s |662.0MiB|
|scheduling/swv14_2895.smt2                                                                 |  30.129s |648.0MiB|
|scheduling/swv12_3004.smt2                                                                 |  30.127s |686.0MiB|
|scheduling/swv12_3050.smt2                                                                 |  30.126s |735.0MiB|
|scheduling/swv13_3150.smt2                                                                 |  30.125s |687.0MiB|
|scheduling/swv11_2983.smt2                                                                 |  30.124s |645.0MiB|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                        |  30.121s |732.0MiB|
|skdmxa2/skdmxa-3x3-14.base.cvc.smt2                                                        |  30.120s |490.0MiB|
|scheduling/swv14_3000.smt2                                                                 |  30.119s |676.0MiB|
|skdmxa2/skdmxa-3x3-16.base.cvc.smt2                                                        |  30.119s |534.0MiB|
|scheduling/swv13_3104.smt2                                                                 |  30.118s |671.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scheduling/swv11_3050.smt2                                                                 |  30.179s |629.0MiB|
|scheduling/yn3_894.smt2                                                                    |  30.147s |310.0MiB|
|scheduling/swv14_2800.smt2                                                                 |  30.143s |645.0MiB|
|scheduling/swv13_3200.smt2                                                                 |  30.141s |701.0MiB|
|scheduling/yn1_827.smt2                                                                    |  30.139s |297.0MiB|
|scheduling/swv14_2885.smt2                                                                 |  30.137s |619.0MiB|
|scheduling/swv12_2972.smt2                                                                 |  30.137s |674.0MiB|
|scheduling/swv11_2900.smt2                                                                 |  30.136s |620.0MiB|
|scheduling/swv14_2905.smt2                                                                 |  30.131s |625.0MiB|
|scheduling/swv12_2900.smt2                                                                 |  30.130s |662.0MiB|
|scheduling/swv14_2895.smt2                                                                 |  30.129s |648.0MiB|
|scheduling/swv12_3004.smt2                                                                 |  30.127s |686.0MiB|
|scheduling/swv12_3050.smt2                                                                 |  30.126s |735.0MiB|
|scheduling/swv13_3150.smt2                                                                 |  30.125s |687.0MiB|
|scheduling/swv11_2983.smt2                                                                 |  30.124s |645.0MiB|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                        |  30.121s |732.0MiB|
|skdmxa2/skdmxa-3x3-14.base.cvc.smt2                                                        |  30.120s |490.0MiB|
|scheduling/swv14_3000.smt2                                                                 |  30.119s |676.0MiB|
|skdmxa2/skdmxa-3x3-16.base.cvc.smt2                                                        |  30.119s |534.0MiB|
|scheduling/swv13_3104.smt2                                                                 |  30.118s |671.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |90.4MiB|90.4MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |91.144MiB|91.144MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |91.16MiB|91.16MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |91.928MiB|91.928MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |92.44MiB|92.44MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |92.952MiB|92.952MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |93.408MiB|93.408MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |94.224MiB|94.224MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |95.0MiB|95.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |95.9MiB|95.9MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |95.72MiB|95.72MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |96.268MiB|96.268MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |96.652MiB|96.652MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |97.188MiB|97.188MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |97.684MiB|97.684MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |98.168MiB|98.168MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |99.004MiB|99.004MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |99.244MiB|99.244MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |97.0MiB|97.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |98.0MiB|98.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |90.4MiB|90.4MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |91.144MiB|91.144MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |91.16MiB|91.16MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |91.928MiB|91.928MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |92.44MiB|92.44MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |92.952MiB|92.952MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |93.408MiB|93.408MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |94.224MiB|94.224MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |95.0MiB|95.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |95.9MiB|95.9MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |95.72MiB|95.72MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |96.268MiB|96.268MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |96.652MiB|96.652MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |97.188MiB|97.188MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |97.684MiB|97.684MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |98.168MiB|98.168MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |99.004MiB|99.004MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |99.244MiB|99.244MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |97.0MiB|97.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |98.0MiB|98.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |90.4MiB|90.4MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |91.144MiB|91.144MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |91.16MiB|91.16MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |91.928MiB|91.928MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |92.44MiB|92.44MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |92.952MiB|92.952MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |93.408MiB|93.408MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |94.224MiB|94.224MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |95.0MiB|95.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |95.9MiB|95.9MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |95.72MiB|95.72MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |96.268MiB|96.268MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |96.652MiB|96.652MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |97.188MiB|97.188MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |97.684MiB|97.684MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |98.168MiB|98.168MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |99.004MiB|99.004MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |99.244MiB|99.244MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |97.0MiB|97.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |98.0MiB|98.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |90.4MiB|90.4MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |91.144MiB|91.144MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |91.16MiB|91.16MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |91.928MiB|91.928MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |92.44MiB|92.44MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |92.952MiB|92.952MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |93.408MiB|93.408MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |94.224MiB|94.224MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |95.0MiB|95.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |95.9MiB|95.9MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |95.72MiB|95.72MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |96.268MiB|96.268MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |96.652MiB|96.652MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |97.188MiB|97.188MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |97.684MiB|97.684MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |98.168MiB|98.168MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |99.004MiB|99.004MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |99.244MiB|99.244MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |97.0MiB|97.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |98.0MiB|98.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|skdmxa2/skdmxa-3x3-20.induction.cvc.smt2                                                   |  25.707s |929.0MiB|
|skdmxa2/skdmxa-3x3-18.induction.cvc.smt2                                                   |  13.624s |863.0MiB|
|skdmxa2/skdmxa-3x3-17.induction.cvc.smt2                                                   |  13.417s |828.0MiB|
|skdmxa2/skdmxa-3x3-19.induction.cvc.smt2                                                   |   9.766s |822.0MiB|
|scheduling/swv12_3050.smt2                                                                 |  30.126s |735.0MiB|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                        |  30.121s |732.0MiB|
|skdmxa2/skdmxa-3x3-15.induction.cvc.smt2                                                   |  13.406s |729.0MiB|
|skdmxa2/skdmxa-3x3-16.induction.cvc.smt2                                                   |   8.746s |715.0MiB|
|scheduling/swv13_3200.smt2                                                                 |  30.141s |701.0MiB|
|skdmxa2/skdmxa-3x3-14.induction.cvc.smt2                                                   |   6.297s |698.0MiB|
|scheduling/swv13_3000.smt2                                                                 |  30.118s |688.0MiB|
|scheduling/swv13_3150.smt2                                                                 |  30.125s |687.0MiB|
|scheduling/swv12_3004.smt2                                                                 |  30.127s |686.0MiB|
|scheduling/swv14_3000.smt2                                                                 |  30.119s |676.0MiB|
|scheduling/swv12_2972.smt2                                                                 |  30.137s |674.0MiB|
|scheduling/swv13_3104.smt2                                                                 |  30.118s |671.0MiB|
|skdmxa2/skdmxa-3x3-19.base.cvc.smt2                                                        |  30.106s |668.0MiB|
|scheduling/swv12_2900.smt2                                                                 |  30.130s |662.0MiB|
|scheduling/swv12_2990.smt2                                                                 |  30.094s |661.0MiB|
|scheduling/swv14_2895.smt2                                                                 |  30.129s |648.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|skdmxa2/skdmxa-3x3-20.induction.cvc.smt2                                                   |  25.707s |929.0MiB|
|skdmxa2/skdmxa-3x3-18.induction.cvc.smt2                                                   |  13.624s |863.0MiB|
|skdmxa2/skdmxa-3x3-17.induction.cvc.smt2                                                   |  13.417s |828.0MiB|
|skdmxa2/skdmxa-3x3-19.induction.cvc.smt2                                                   |   9.766s |822.0MiB|
|scheduling/swv12_3050.smt2                                                                 |  30.126s |735.0MiB|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                        |  30.121s |732.0MiB|
|skdmxa2/skdmxa-3x3-15.induction.cvc.smt2                                                   |  13.406s |729.0MiB|
|skdmxa2/skdmxa-3x3-16.induction.cvc.smt2                                                   |   8.746s |715.0MiB|
|scheduling/swv13_3200.smt2                                                                 |  30.141s |701.0MiB|
|skdmxa2/skdmxa-3x3-14.induction.cvc.smt2                                                   |   6.297s |698.0MiB|
|scheduling/swv13_3000.smt2                                                                 |  30.118s |688.0MiB|
|scheduling/swv13_3150.smt2                                                                 |  30.125s |687.0MiB|
|scheduling/swv12_3004.smt2                                                                 |  30.127s |686.0MiB|
|scheduling/swv14_3000.smt2                                                                 |  30.119s |676.0MiB|
|scheduling/swv12_2972.smt2                                                                 |  30.137s |674.0MiB|
|scheduling/swv13_3104.smt2                                                                 |  30.118s |671.0MiB|
|skdmxa2/skdmxa-3x3-19.base.cvc.smt2                                                        |  30.106s |668.0MiB|
|scheduling/swv12_2900.smt2                                                                 |  30.130s |662.0MiB|
|scheduling/swv12_2990.smt2                                                                 |  30.094s |661.0MiB|
|scheduling/swv14_2895.smt2                                                                 |  30.129s |648.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking21.smt2                                             |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking22.smt2                                             |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-2.smt2                                         |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-3.smt2                                         |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-4.smt2                                         |   0.928s  |   0.928s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-5.smt2                                         |  11.559s  |  11.559s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-6.smt2                                         |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-7.smt2                                         |  30.066s  |  30.066s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-matrix1x1.pddl.smt2                                  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-matrix2x2.pddl.smt2                                  |  30.075s  |  30.075s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-1.smt2                                         |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-2.smt2                                         |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-3.smt2                                         |   0.458s  |   0.458s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-4.smt2                                         |  14.394s  |  14.394s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-5.smt2                                         |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-6.smt2                                         |  30.073s  |  30.073s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-03.smt2                                      |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-04.smt2                                      |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-05.smt2                                      |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-06.smt2                                      |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-07.smt2                                      |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-08.smt2                                      |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-09.smt2                                      |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-10.smt2                                      |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-20.smt2                                      |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-30.smt2                                      |   0.469s  |   0.469s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-40.smt2                                      |   0.914s  |   0.914s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-60.smt2                                      |   1.270s  |   1.270s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-70.smt2                                      |   2.563s  |   2.563s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-80.smt2                                      |   2.856s  |   2.856s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-90.smt2                                      |   3.048s  |   3.048s  |   0.000s  | 0.0%|
|check/bignum_rdl1.smt2                                                                      |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|check/bignum_rdl2.smt2                                                                      |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-1.smt2                                                                   |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-10.smt2                                                                  |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-11.smt2                                                                  |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-12.smt2                                                                  |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-13.smt2                                                                  |   0.342s  |   0.342s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-14.smt2                                                                  |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-15.smt2                                                                  |   0.556s  |   0.556s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-16.smt2                                                                  |   0.553s  |   0.553s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-17.smt2                                                                  |   0.688s  |   0.688s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-18.smt2                                                                  |   0.771s  |   0.771s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-19.smt2                                                                  |   0.868s  |   0.868s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-2.smt2                                                                   |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-20.smt2                                                                  |   1.199s  |   1.199s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-3.smt2                                                                   |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-4.smt2                                                                   |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-5.smt2                                                                   |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-6.smt2                                                                   |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-7.smt2                                                                   |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-8.smt2                                                                   |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-9.smt2                                                                   |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-1.smt2                                                                   |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-10.smt2                                                                  |   0.592s  |   0.592s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-11.smt2                                                                  |   0.937s  |   0.937s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-12.smt2                                                                  |   2.265s  |   2.265s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-13.smt2                                                                  |   1.716s  |   1.716s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-14.smt2                                                                  |   5.022s  |   5.022s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-15.smt2                                                                  |   5.956s  |   5.956s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-16.smt2                                                                  |   6.969s  |   6.969s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-17.smt2                                                                  |  13.208s  |  13.208s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-18.smt2                                                                  |  20.916s  |  20.916s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-19.smt2                                                                  |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-2.smt2                                                                   |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-20.smt2                                                                  |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-3.smt2                                                                   |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-4.smt2                                                                   |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-5.smt2                                                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-6.smt2                                                                   |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-7.smt2                                                                   |   0.285s  |   0.285s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-8.smt2                                                                   |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-9.smt2                                                                   |   0.381s  |   0.381s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-1.smt2                                                                   |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-10.smt2                                                                  |   1.768s  |   1.768s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-11.smt2                                                                  |   2.179s  |   2.179s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-12.smt2                                                                  |   6.241s  |   6.241s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-13.smt2                                                                  |  10.364s  |  10.364s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-14.smt2                                                                  |  21.595s  |  21.595s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-15.smt2                                                                  |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-16.smt2                                                                  |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-17.smt2                                                                  |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-18.smt2                                                                  |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-19.smt2                                                                  |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-2.smt2                                                                   |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-20.smt2                                                                  |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-3.smt2                                                                   |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-4.smt2                                                                   |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-5.smt2                                                                   |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-6.smt2                                                                   |   0.300s  |   0.300s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-7.smt2                                                                   |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-8.smt2                                                                   |   0.324s  |   0.324s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-9.smt2                                                                   |   0.929s  |   0.929s  |   0.000s  | 0.0%|
|scheduling/abz5_1000.smt2                                                                   |   0.308s  |   0.308s  |   0.000s  | 0.0%|
|scheduling/abz5_1200.smt2                                                                   |   2.115s  |   2.115s  |   0.000s  | 0.0%|
|scheduling/abz5_1234.smt2                                                                   |   2.405s  |   2.405s  |   0.000s  | 0.0%|
|scheduling/abz5_1300.smt2                                                                   |   0.694s  |   0.694s  |   0.000s  | 0.0%|
|scheduling/abz5_1400.smt2                                                                   |   0.353s  |   0.353s  |   0.000s  | 0.0%|
|scheduling/abz6_1000.smt2                                                                   |   0.458s  |   0.458s  |   0.000s  | 0.0%|
|scheduling/abz6_1100.smt2                                                                   |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|scheduling/abz6_800.smt2                                                                    |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|scheduling/abz6_900.smt2                                                                    |   0.480s  |   0.480s  |   0.000s  | 0.0%|
|scheduling/abz6_943.smt2                                                                    |   1.371s  |   1.371s  |   0.000s  | 0.0%|
|scheduling/abz7_500.smt2                                                                    |   3.212s  |   3.212s  |   0.000s  | 0.0%|
|scheduling/abz7_600.smt2                                                                    |  30.061s  |  30.061s  |   0.000s  | 0.0%|
|scheduling/abz7_667.smt2                                                                    |  30.058s  |  30.058s  |   0.000s  | 0.0%|
|scheduling/abz7_670.smt2                                                                    |  30.106s  |  30.106s  |   0.000s  | 0.0%|
|scheduling/abz7_691.smt2                                                                    |  30.076s  |  30.076s  |   0.000s  | 0.0%|
|scheduling/abz7_700.smt2                                                                    |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|scheduling/abz7_800.smt2                                                                    |  30.086s  |  30.086s  |   0.000s  | 0.0%|
|scheduling/orb01_1000.smt2                                                                  |  16.496s  |  16.496s  |   0.000s  | 0.0%|
|scheduling/orb01_1059.smt2                                                                  |  30.062s  |  30.062s  |   0.000s  | 0.0%|
|scheduling/orb01_1100.smt2                                                                  |   5.441s  |   5.441s  |   0.000s  | 0.0%|
|scheduling/orb01_1200.smt2                                                                  |   1.024s  |   1.024s  |   0.000s  | 0.0%|
|scheduling/orb01_900.smt2                                                                   |   0.588s  |   0.588s  |   0.000s  | 0.0%|
|scheduling/orb02_1000.smt2                                                                  |   0.344s  |   0.344s  |   0.000s  | 0.0%|
|scheduling/orb02_700.smt2                                                                   |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|scheduling/orb02_800.smt2                                                                   |   0.455s  |   0.455s  |   0.000s  | 0.0%|
|scheduling/orb02_888.smt2                                                                   |   1.865s  |   1.865s  |   0.000s  | 0.0%|
|scheduling/orb02_900.smt2                                                                   |   0.740s  |   0.740s  |   0.000s  | 0.0%|
|scheduling/orb03_1005.smt2                                                                  |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|scheduling/orb03_1100.smt2                                                                  |   5.084s  |   5.084s  |   0.000s  | 0.0%|
|scheduling/orb03_1200.smt2                                                                  |   0.659s  |   0.659s  |   0.000s  | 0.0%|
|scheduling/orb03_850.smt2                                                                   |   0.468s  |   0.468s  |   0.000s  | 0.0%|
|scheduling/orb03_950.smt2                                                                   |  11.352s  |  11.352s  |   0.000s  | 0.0%|
|scheduling/orb04_1005.smt2                                                                  |   8.408s  |   8.408s  |   0.000s  | 0.0%|
|scheduling/orb04_1100.smt2                                                                  |   0.762s  |   0.762s  |   0.000s  | 0.0%|
|scheduling/orb04_1200.smt2                                                                  |   0.422s  |   0.422s  |   0.000s  | 0.0%|
|scheduling/orb04_850.smt2                                                                   |   0.332s  |   0.332s  |   0.000s  | 0.0%|
|scheduling/orb04_950.smt2                                                                   |   0.635s  |   0.635s  |   0.000s  | 0.0%|
|scheduling/orb05_1000.smt2                                                                  |   0.571s  |   0.571s  |   0.000s  | 0.0%|
|scheduling/orb05_700.smt2                                                                   |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|scheduling/orb05_800.smt2                                                                   |   0.386s  |   0.386s  |   0.000s  | 0.0%|
|scheduling/orb05_887.smt2                                                                   |   7.141s  |   7.141s  |   0.000s  | 0.0%|
|scheduling/orb05_900.smt2                                                                   |   3.136s  |   3.136s  |   0.000s  | 0.0%|
|scheduling/orb06_1000.smt2                                                                  |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|scheduling/orb06_1010.smt2                                                                  |  30.078s  |  30.078s  |   0.000s  | 0.0%|
|scheduling/orb06_1100.smt2                                                                  |   1.309s  |   1.309s  |   0.000s  | 0.0%|
|scheduling/orb06_1200.smt2                                                                  |   0.389s  |   0.389s  |   0.000s  | 0.0%|
|scheduling/orb06_900.smt2                                                                   |   0.619s  |   0.619s  |   0.000s  | 0.0%|
|scheduling/orb07_250.smt2                                                                   |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|scheduling/orb07_330.smt2                                                                   |   0.287s  |   0.287s  |   0.000s  | 0.0%|
|scheduling/orb07_397.smt2                                                                   |   3.715s  |   3.715s  |   0.000s  | 0.0%|
|scheduling/orb07_430.smt2                                                                   |   0.823s  |   0.823s  |   0.000s  | 0.0%|
|scheduling/orb07_550.smt2                                                                   |   0.397s  |   0.397s  |   0.000s  | 0.0%|
|scheduling/orb08_1000.smt2                                                                  |   0.615s  |   0.615s  |   0.000s  | 0.0%|
|scheduling/orb08_700.smt2                                                                   |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|scheduling/orb08_830.smt2                                                                   |   0.424s  |   0.424s  |   0.000s  | 0.0%|
|scheduling/orb08_888.smt2                                                                   |   7.830s  |   7.830s  |   0.000s  | 0.0%|
|scheduling/orb08_930.smt2                                                                   |   3.028s  |   3.028s  |   0.000s  | 0.0%|
|scheduling/orb09_1000.smt2                                                                  |   0.426s  |   0.426s  |   0.000s  | 0.0%|
|scheduling/orb09_1100.smt2                                                                  |   0.281s  |   0.281s  |   0.000s  | 0.0%|
|scheduling/orb09_800.smt2                                                                   |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|scheduling/orb09_900.smt2                                                                   |   2.309s  |   2.309s  |   0.000s  | 0.0%|
|scheduling/orb09_934.smt2                                                                   |   2.769s  |   2.769s  |   0.000s  | 0.0%|
|scheduling/orb10_1000.smt2                                                                  |   1.371s  |   1.371s  |   0.000s  | 0.0%|
|scheduling/orb10_1100.smt2                                                                  |   0.387s  |   0.387s  |   0.000s  | 0.0%|
|scheduling/orb10_800.smt2                                                                   |   0.262s  |   0.262s  |   0.000s  | 0.0%|
|scheduling/orb10_900.smt2                                                                   |   0.861s  |   0.861s  |   0.000s  | 0.0%|
|scheduling/orb10_944.smt2                                                                   |   6.014s  |   6.014s  |   0.000s  | 0.0%|
|scheduling/swv11_2900.smt2                                                                  |  30.136s  |  30.136s  |   0.000s  | 0.0%|
|scheduling/swv11_2983.smt2                                                                  |  30.124s  |  30.124s  |   0.000s  | 0.0%|
|scheduling/swv11_2988.smt2                                                                  |  30.118s  |  30.118s  |   0.000s  | 0.0%|
|scheduling/swv11_2992.smt2                                                                  |  30.103s  |  30.103s  |   0.000s  | 0.0%|
|scheduling/swv11_3050.smt2                                                                  |  30.179s  |  30.179s  |   0.000s  | 0.0%|
|scheduling/swv12_2900.smt2                                                                  |  30.130s  |  30.130s  |   0.000s  | 0.0%|
|scheduling/swv12_2972.smt2                                                                  |  30.137s  |  30.137s  |   0.000s  | 0.0%|
|scheduling/swv12_2990.smt2                                                                  |  30.094s  |  30.094s  |   0.000s  | 0.0%|
|scheduling/swv12_3004.smt2                                                                  |  30.127s  |  30.127s  |   0.000s  | 0.0%|
|scheduling/swv12_3050.smt2                                                                  |  30.126s  |  30.126s  |   0.000s  | 0.0%|
|scheduling/swv13_3000.smt2                                                                  |  30.118s  |  30.118s  |   0.000s  | 0.0%|
|scheduling/swv13_3104.smt2                                                                  |  30.118s  |  30.118s  |   0.000s  | 0.0%|
|scheduling/swv13_3150.smt2                                                                  |  30.125s  |  30.125s  |   0.000s  | 0.0%|
|scheduling/swv13_3200.smt2                                                                  |  30.141s  |  30.141s  |   0.000s  | 0.0%|
|scheduling/swv14_2800.smt2                                                                  |  30.143s  |  30.143s  |   0.000s  | 0.0%|
|scheduling/swv14_2885.smt2                                                                  |  30.137s  |  30.137s  |   0.000s  | 0.0%|
|scheduling/swv14_2895.smt2                                                                  |  30.129s  |  30.129s  |   0.000s  | 0.0%|
|scheduling/swv14_2905.smt2                                                                  |  30.131s  |  30.131s  |   0.000s  | 0.0%|
|scheduling/swv14_3000.smt2                                                                  |  30.119s  |  30.119s  |   0.000s  | 0.0%|
|scheduling/yn1_750.smt2                                                                     |   2.114s  |   2.114s  |   0.000s  | 0.0%|
|scheduling/yn1_827.smt2                                                                     |  30.139s  |  30.139s  |   0.000s  | 0.0%|
|scheduling/yn1_850.smt2                                                                     |  30.099s  |  30.099s  |   0.000s  | 0.0%|
|scheduling/yn1_887.smt2                                                                     |  30.088s  |  30.088s  |   0.000s  | 0.0%|
|scheduling/yn1_950.smt2                                                                     |  30.098s  |  30.098s  |   0.000s  | 0.0%|
|scheduling/yn2_750.smt2                                                                     |   7.151s  |   7.151s  |   0.000s  | 0.0%|
|scheduling/yn2_862.smt2                                                                     |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|scheduling/yn2_890.smt2                                                                     |  30.073s  |  30.073s  |   0.000s  | 0.0%|
|scheduling/yn2_910.smt2                                                                     |  30.100s  |  30.100s  |   0.000s  | 0.0%|
|scheduling/yn2_950.smt2                                                                     |  30.075s  |  30.075s  |   0.000s  | 0.0%|
|scheduling/yn3_750.smt2                                                                     |   5.633s  |   5.633s  |   0.000s  | 0.0%|
|scheduling/yn3_828.smt2                                                                     |  30.082s  |  30.082s  |   0.000s  | 0.0%|
|scheduling/yn3_860.smt2                                                                     |  30.091s  |  30.091s  |   0.000s  | 0.0%|
|scheduling/yn3_894.smt2                                                                     |  30.147s  |  30.147s  |   0.000s  | 0.0%|
|scheduling/yn3_950.smt2                                                                     |  30.078s  |  30.078s  |   0.000s  | 0.0%|
|scheduling/yn4_1000.smt2                                                                    |  30.088s  |  30.088s  |   0.000s  | 0.0%|
|scheduling/yn4_850.smt2                                                                     |  30.088s  |  30.088s  |   0.000s  | 0.0%|
|scheduling/yn4_919.smt2                                                                     |  30.077s  |  30.077s  |   0.000s  | 0.0%|
|scheduling/yn4_950.smt2                                                                     |  30.089s  |  30.089s  |   0.000s  | 0.0%|
|scheduling/yn4_969.smt2                                                                     |  30.100s  |  30.100s  |   0.000s  | 0.0%|
|skdmxa/skdmxa-3x3-10.smt2                                                                   |   2.245s  |   2.245s  |   0.000s  | 0.0%|
|skdmxa/skdmxa-3x3-15.smt2                                                                   |  28.552s  |  28.552s  |   0.000s  | 0.0%|
|skdmxa/skdmxa-3x3-20.smt2                                                                   |  30.116s  |  30.116s  |   0.000s  | 0.0%|
|skdmxa/skdmxa-3x3-5.smt2                                                                    |   1.039s  |   1.039s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-10.base.cvc.smt2                                                         |   2.404s  |   2.404s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-10.induction.cvc.smt2                                                    |   3.039s  |   3.039s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-11.base.cvc.smt2                                                         |   5.620s  |   5.620s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-11.induction.cvc.smt2                                                    |   3.944s  |   3.944s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-12.base.cvc.smt2                                                         |  13.467s  |  13.467s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-12.induction.cvc.smt2                                                    |   3.934s  |   3.934s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-13.base.cvc.smt2                                                         |  30.091s  |  30.091s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-13.induction.cvc.smt2                                                    |   7.781s  |   7.781s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-14.base.cvc.smt2                                                         |  30.120s  |  30.120s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-14.induction.cvc.smt2                                                    |   6.297s  |   6.297s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-15.base.cvc.smt2                                                         |  30.090s  |  30.090s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-15.induction.cvc.smt2                                                    |  13.406s  |  13.406s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-16.base.cvc.smt2                                                         |  30.119s  |  30.119s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-16.induction.cvc.smt2                                                    |   8.746s  |   8.746s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-17.base.cvc.smt2                                                         |  30.102s  |  30.102s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-17.induction.cvc.smt2                                                    |  13.417s  |  13.417s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-18.base.cvc.smt2                                                         |  30.107s  |  30.107s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-18.induction.cvc.smt2                                                    |  13.624s  |  13.624s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-19.base.cvc.smt2                                                         |  30.106s  |  30.106s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-19.induction.cvc.smt2                                                    |   9.766s  |   9.766s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                         |  30.121s  |  30.121s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-20.induction.cvc.smt2                                                    |  25.707s  |  25.707s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-5.base.cvc.smt2                                                          |   1.060s  |   1.060s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-5.induction.cvc.smt2                                                     |   0.902s  |   0.902s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-6.base.cvc.smt2                                                          |   0.828s  |   0.828s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-6.induction.cvc.smt2                                                     |   1.163s  |   1.163s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-7.base.cvc.smt2                                                          |   1.113s  |   1.113s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-7.induction.cvc.smt2                                                     |   1.659s  |   1.659s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-8.base.cvc.smt2                                                          |   1.379s  |   1.379s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-8.induction.cvc.smt2                                                     |   1.851s  |   1.851s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-9.base.cvc.smt2                                                          |   1.658s  |   1.658s  |   0.000s  | 0.0%|
</details>
