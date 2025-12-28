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
Job tag: smt_qfrdl-threads-4-no_inprocessing-reducedparams
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
Job tag: smt_qfrdl-threads-4-no_inprocessing-reducedparams
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
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.204s  |   0.204s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.204s  |   0.204s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.204s  |   0.204s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.204s  |   0.204s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scheduling/swv14_2800.smt2                                                                 |  30.189s |628.0MiB|
|skdmxa2/skdmxa-3x3-20.induction.cvc.smt2                                                   |  30.176s |953.0MiB|
|skdmxa/skdmxa-3x3-20.smt2                                                                  |  30.154s |406.0MiB|
|scheduling/swv11_2900.smt2                                                                 |  30.154s |633.0MiB|
|scheduling/swv12_2972.smt2                                                                 |  30.154s |693.0MiB|
|scheduling/swv13_3200.smt2                                                                 |  30.150s |722.0MiB|
|scheduling/swv13_3000.smt2                                                                 |  30.149s |697.0MiB|
|scheduling/swv11_2988.smt2                                                                 |  30.145s |639.0MiB|
|scheduling/swv13_3104.smt2                                                                 |  30.144s |676.0MiB|
|scheduling/swv14_2895.smt2                                                                 |  30.143s |626.0MiB|
|scheduling/swv11_3050.smt2                                                                 |  30.138s |641.0MiB|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                        |  30.137s |730.0MiB|
|scheduling/swv12_3004.smt2                                                                 |  30.136s |690.0MiB|
|skdmxa2/skdmxa-3x3-18.base.cvc.smt2                                                        |  30.136s |640.0MiB|
|scheduling/swv14_3000.smt2                                                                 |  30.133s |677.0MiB|
|scheduling/swv14_2885.smt2                                                                 |  30.131s |605.0MiB|
|scheduling/swv13_3150.smt2                                                                 |  30.131s |684.0MiB|
|skdmxa2/skdmxa-3x3-17.base.cvc.smt2                                                        |  30.131s |597.0MiB|
|scheduling/swv12_2900.smt2                                                                 |  30.129s |687.0MiB|
|scheduling/swv12_3050.smt2                                                                 |  30.125s |732.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scheduling/swv14_2800.smt2                                                                 |  30.189s |628.0MiB|
|skdmxa2/skdmxa-3x3-20.induction.cvc.smt2                                                   |  30.176s |953.0MiB|
|skdmxa/skdmxa-3x3-20.smt2                                                                  |  30.154s |406.0MiB|
|scheduling/swv11_2900.smt2                                                                 |  30.154s |633.0MiB|
|scheduling/swv12_2972.smt2                                                                 |  30.154s |693.0MiB|
|scheduling/swv13_3200.smt2                                                                 |  30.150s |722.0MiB|
|scheduling/swv13_3000.smt2                                                                 |  30.149s |697.0MiB|
|scheduling/swv11_2988.smt2                                                                 |  30.145s |639.0MiB|
|scheduling/swv13_3104.smt2                                                                 |  30.144s |676.0MiB|
|scheduling/swv14_2895.smt2                                                                 |  30.143s |626.0MiB|
|scheduling/swv11_3050.smt2                                                                 |  30.138s |641.0MiB|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                        |  30.137s |730.0MiB|
|scheduling/swv12_3004.smt2                                                                 |  30.136s |690.0MiB|
|skdmxa2/skdmxa-3x3-18.base.cvc.smt2                                                        |  30.136s |640.0MiB|
|scheduling/swv14_3000.smt2                                                                 |  30.133s |677.0MiB|
|scheduling/swv14_2885.smt2                                                                 |  30.131s |605.0MiB|
|scheduling/swv13_3150.smt2                                                                 |  30.131s |684.0MiB|
|skdmxa2/skdmxa-3x3-17.base.cvc.smt2                                                        |  30.131s |597.0MiB|
|scheduling/swv12_2900.smt2                                                                 |  30.129s |687.0MiB|
|scheduling/swv12_3050.smt2                                                                 |  30.125s |732.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |90.392MiB|90.392MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |90.904MiB|90.904MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |91.164MiB|91.164MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |91.932MiB|91.932MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |92.184MiB|92.184MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |92.956MiB|92.956MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |93.404MiB|93.404MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |93.964MiB|93.964MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |94.64MiB|94.64MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |95.636MiB|95.636MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |95.98MiB|95.98MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |96.52MiB|96.52MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |96.932MiB|96.932MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |96.952MiB|96.952MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |97.5MiB|97.5MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |98.176MiB|98.176MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |99.52MiB|99.52MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |99.152MiB|99.152MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |97.0MiB|97.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |98.0MiB|98.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |90.392MiB|90.392MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |90.904MiB|90.904MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |91.164MiB|91.164MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |91.932MiB|91.932MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |92.184MiB|92.184MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |92.956MiB|92.956MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |93.404MiB|93.404MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |93.964MiB|93.964MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |94.64MiB|94.64MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |95.636MiB|95.636MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |95.98MiB|95.98MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |96.52MiB|96.52MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |96.932MiB|96.932MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |96.952MiB|96.952MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |97.5MiB|97.5MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |98.176MiB|98.176MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |99.52MiB|99.52MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |99.152MiB|99.152MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |97.0MiB|97.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |98.0MiB|98.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |90.392MiB|90.392MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |90.904MiB|90.904MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |91.164MiB|91.164MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |91.932MiB|91.932MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |92.184MiB|92.184MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |92.956MiB|92.956MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |93.404MiB|93.404MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |93.964MiB|93.964MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |94.64MiB|94.64MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |95.636MiB|95.636MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |95.98MiB|95.98MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |96.52MiB|96.52MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |96.932MiB|96.932MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |96.952MiB|96.952MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |97.5MiB|97.5MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |98.176MiB|98.176MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |99.52MiB|99.52MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |99.152MiB|99.152MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |97.0MiB|97.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |98.0MiB|98.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |90.392MiB|90.392MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |90.904MiB|90.904MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |91.164MiB|91.164MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |91.932MiB|91.932MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |92.184MiB|92.184MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |92.956MiB|92.956MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |93.404MiB|93.404MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |93.964MiB|93.964MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |94.64MiB|94.64MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |95.636MiB|95.636MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |95.98MiB|95.98MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |96.52MiB|96.52MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |96.932MiB|96.932MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |96.952MiB|96.952MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |97.5MiB|97.5MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |98.176MiB|98.176MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |99.52MiB|99.52MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |99.152MiB|99.152MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |97.0MiB|97.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |98.0MiB|98.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|skdmxa2/skdmxa-3x3-20.induction.cvc.smt2                                                   |  30.176s |953.0MiB|
|skdmxa2/skdmxa-3x3-18.induction.cvc.smt2                                                   |  13.659s |880.0MiB|
|skdmxa2/skdmxa-3x3-17.induction.cvc.smt2                                                   |  12.060s |823.0MiB|
|skdmxa2/skdmxa-3x3-19.induction.cvc.smt2                                                   |  10.007s |822.0MiB|
|skdmxa2/skdmxa-3x3-15.induction.cvc.smt2                                                   |  20.429s |761.0MiB|
|scheduling/swv12_3050.smt2                                                                 |  30.125s |732.0MiB|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                        |  30.137s |730.0MiB|
|scheduling/swv13_3200.smt2                                                                 |  30.150s |722.0MiB|
|skdmxa2/skdmxa-3x3-16.induction.cvc.smt2                                                   |   8.466s |717.0MiB|
|scheduling/swv13_3000.smt2                                                                 |  30.149s |697.0MiB|
|scheduling/swv12_2972.smt2                                                                 |  30.154s |693.0MiB|
|scheduling/swv12_3004.smt2                                                                 |  30.136s |690.0MiB|
|scheduling/swv12_2900.smt2                                                                 |  30.129s |687.0MiB|
|scheduling/swv13_3150.smt2                                                                 |  30.131s |684.0MiB|
|scheduling/swv14_3000.smt2                                                                 |  30.133s |677.0MiB|
|scheduling/swv12_2990.smt2                                                                 |  30.115s |677.0MiB|
|scheduling/swv13_3104.smt2                                                                 |  30.144s |676.0MiB|
|skdmxa2/skdmxa-3x3-14.induction.cvc.smt2                                                   |   5.695s |667.0MiB|
|skdmxa2/skdmxa-3x3-19.base.cvc.smt2                                                        |  30.098s |665.0MiB|
|scheduling/swv11_3050.smt2                                                                 |  30.138s |641.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|skdmxa2/skdmxa-3x3-20.induction.cvc.smt2                                                   |  30.176s |953.0MiB|
|skdmxa2/skdmxa-3x3-18.induction.cvc.smt2                                                   |  13.659s |880.0MiB|
|skdmxa2/skdmxa-3x3-17.induction.cvc.smt2                                                   |  12.060s |823.0MiB|
|skdmxa2/skdmxa-3x3-19.induction.cvc.smt2                                                   |  10.007s |822.0MiB|
|skdmxa2/skdmxa-3x3-15.induction.cvc.smt2                                                   |  20.429s |761.0MiB|
|scheduling/swv12_3050.smt2                                                                 |  30.125s |732.0MiB|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                        |  30.137s |730.0MiB|
|scheduling/swv13_3200.smt2                                                                 |  30.150s |722.0MiB|
|skdmxa2/skdmxa-3x3-16.induction.cvc.smt2                                                   |   8.466s |717.0MiB|
|scheduling/swv13_3000.smt2                                                                 |  30.149s |697.0MiB|
|scheduling/swv12_2972.smt2                                                                 |  30.154s |693.0MiB|
|scheduling/swv12_3004.smt2                                                                 |  30.136s |690.0MiB|
|scheduling/swv12_2900.smt2                                                                 |  30.129s |687.0MiB|
|scheduling/swv13_3150.smt2                                                                 |  30.131s |684.0MiB|
|scheduling/swv14_3000.smt2                                                                 |  30.133s |677.0MiB|
|scheduling/swv12_2990.smt2                                                                 |  30.115s |677.0MiB|
|scheduling/swv13_3104.smt2                                                                 |  30.144s |676.0MiB|
|skdmxa2/skdmxa-3x3-14.induction.cvc.smt2                                                   |   5.695s |667.0MiB|
|skdmxa2/skdmxa-3x3-19.base.cvc.smt2                                                        |  30.098s |665.0MiB|
|scheduling/swv11_3050.smt2                                                                 |  30.138s |641.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking21.smt2                                             |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking22.smt2                                             |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-2.smt2                                         |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-3.smt2                                         |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-4.smt2                                         |   0.904s  |   0.904s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-5.smt2                                         |  10.616s  |  10.616s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-6.smt2                                         |  30.051s  |  30.051s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-7.smt2                                         |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-matrix1x1.pddl.smt2                                  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-matrix2x2.pddl.smt2                                  |  30.067s  |  30.067s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-1.smt2                                         |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-2.smt2                                         |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-3.smt2                                         |   0.429s  |   0.429s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-4.smt2                                         |  16.892s  |  16.892s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-5.smt2                                         |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-6.smt2                                         |  30.079s  |  30.079s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-03.smt2                                      |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-04.smt2                                      |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-05.smt2                                      |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-06.smt2                                      |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-07.smt2                                      |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-08.smt2                                      |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-09.smt2                                      |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-10.smt2                                      |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-20.smt2                                      |   0.268s  |   0.268s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-30.smt2                                      |   0.472s  |   0.472s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-40.smt2                                      |   0.857s  |   0.857s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-60.smt2                                      |   1.266s  |   1.266s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-70.smt2                                      |   1.475s  |   1.475s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-80.smt2                                      |   2.686s  |   2.686s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-90.smt2                                      |   3.082s  |   3.082s  |   0.000s  | 0.0%|
|check/bignum_rdl1.smt2                                                                      |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|check/bignum_rdl2.smt2                                                                      |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-1.smt2                                                                   |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-10.smt2                                                                  |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-11.smt2                                                                  |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-12.smt2                                                                  |   0.279s  |   0.279s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-13.smt2                                                                  |   0.316s  |   0.316s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-14.smt2                                                                  |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-15.smt2                                                                  |   0.496s  |   0.496s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-16.smt2                                                                  |   0.530s  |   0.530s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-17.smt2                                                                  |   0.715s  |   0.715s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-18.smt2                                                                  |   0.741s  |   0.741s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-19.smt2                                                                  |   1.097s  |   1.097s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-2.smt2                                                                   |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-20.smt2                                                                  |   1.334s  |   1.334s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-3.smt2                                                                   |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-4.smt2                                                                   |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-5.smt2                                                                   |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-6.smt2                                                                   |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-7.smt2                                                                   |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-8.smt2                                                                   |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-9.smt2                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-1.smt2                                                                   |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-10.smt2                                                                  |   0.659s  |   0.659s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-11.smt2                                                                  |   0.995s  |   0.995s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-12.smt2                                                                  |   2.233s  |   2.233s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-13.smt2                                                                  |   2.129s  |   2.129s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-14.smt2                                                                  |   3.461s  |   3.461s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-15.smt2                                                                  |   4.537s  |   4.537s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-16.smt2                                                                  |   7.748s  |   7.748s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-17.smt2                                                                  |  20.263s  |  20.263s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-18.smt2                                                                  |  25.740s  |  25.740s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-19.smt2                                                                  |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-2.smt2                                                                   |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-20.smt2                                                                  |  30.033s  |  30.033s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-3.smt2                                                                   |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-4.smt2                                                                   |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-5.smt2                                                                   |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-6.smt2                                                                   |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-7.smt2                                                                   |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-8.smt2                                                                   |   0.301s  |   0.301s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-9.smt2                                                                   |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-1.smt2                                                                   |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-10.smt2                                                                  |   2.160s  |   2.160s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-11.smt2                                                                  |   3.054s  |   3.054s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-12.smt2                                                                  |   7.004s  |   7.004s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-13.smt2                                                                  |  11.851s  |  11.851s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-14.smt2                                                                  |  21.630s  |  21.630s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-15.smt2                                                                  |  27.475s  |  27.475s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-16.smt2                                                                  |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-17.smt2                                                                  |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-18.smt2                                                                  |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-19.smt2                                                                  |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-2.smt2                                                                   |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-20.smt2                                                                  |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-3.smt2                                                                   |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-4.smt2                                                                   |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-5.smt2                                                                   |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-6.smt2                                                                   |   0.388s  |   0.388s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-7.smt2                                                                   |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-8.smt2                                                                   |   0.325s  |   0.325s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-9.smt2                                                                   |   0.904s  |   0.904s  |   0.000s  | 0.0%|
|scheduling/abz5_1000.smt2                                                                   |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|scheduling/abz5_1200.smt2                                                                   |   2.037s  |   2.037s  |   0.000s  | 0.0%|
|scheduling/abz5_1234.smt2                                                                   |   4.147s  |   4.147s  |   0.000s  | 0.0%|
|scheduling/abz5_1300.smt2                                                                   |   0.590s  |   0.590s  |   0.000s  | 0.0%|
|scheduling/abz5_1400.smt2                                                                   |   0.466s  |   0.466s  |   0.000s  | 0.0%|
|scheduling/abz6_1000.smt2                                                                   |   0.414s  |   0.414s  |   0.000s  | 0.0%|
|scheduling/abz6_1100.smt2                                                                   |   0.393s  |   0.393s  |   0.000s  | 0.0%|
|scheduling/abz6_800.smt2                                                                    |   0.302s  |   0.302s  |   0.000s  | 0.0%|
|scheduling/abz6_900.smt2                                                                    |   0.509s  |   0.509s  |   0.000s  | 0.0%|
|scheduling/abz6_943.smt2                                                                    |   0.883s  |   0.883s  |   0.000s  | 0.0%|
|scheduling/abz7_500.smt2                                                                    |   3.312s  |   3.312s  |   0.000s  | 0.0%|
|scheduling/abz7_600.smt2                                                                    |  30.075s  |  30.075s  |   0.000s  | 0.0%|
|scheduling/abz7_667.smt2                                                                    |  30.071s  |  30.071s  |   0.000s  | 0.0%|
|scheduling/abz7_670.smt2                                                                    |  30.093s  |  30.093s  |   0.000s  | 0.0%|
|scheduling/abz7_691.smt2                                                                    |  30.094s  |  30.094s  |   0.000s  | 0.0%|
|scheduling/abz7_700.smt2                                                                    |  30.070s  |  30.070s  |   0.000s  | 0.0%|
|scheduling/abz7_800.smt2                                                                    |  30.095s  |  30.095s  |   0.000s  | 0.0%|
|scheduling/orb01_1000.smt2                                                                  |  30.065s  |  30.065s  |   0.000s  | 0.0%|
|scheduling/orb01_1059.smt2                                                                  |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|scheduling/orb01_1100.smt2                                                                  |  13.531s  |  13.531s  |   0.000s  | 0.0%|
|scheduling/orb01_1200.smt2                                                                  |   1.552s  |   1.552s  |   0.000s  | 0.0%|
|scheduling/orb01_900.smt2                                                                   |   0.741s  |   0.741s  |   0.000s  | 0.0%|
|scheduling/orb02_1000.smt2                                                                  |   0.346s  |   0.346s  |   0.000s  | 0.0%|
|scheduling/orb02_700.smt2                                                                   |   0.297s  |   0.297s  |   0.000s  | 0.0%|
|scheduling/orb02_800.smt2                                                                   |   0.377s  |   0.377s  |   0.000s  | 0.0%|
|scheduling/orb02_888.smt2                                                                   |   1.932s  |   1.932s  |   0.000s  | 0.0%|
|scheduling/orb02_900.smt2                                                                   |   0.746s  |   0.746s  |   0.000s  | 0.0%|
|scheduling/orb03_1005.smt2                                                                  |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|scheduling/orb03_1100.smt2                                                                  |   4.911s  |   4.911s  |   0.000s  | 0.0%|
|scheduling/orb03_1200.smt2                                                                  |   0.649s  |   0.649s  |   0.000s  | 0.0%|
|scheduling/orb03_850.smt2                                                                   |   0.448s  |   0.448s  |   0.000s  | 0.0%|
|scheduling/orb03_950.smt2                                                                   |  14.780s  |  14.780s  |   0.000s  | 0.0%|
|scheduling/orb04_1005.smt2                                                                  |   7.907s  |   7.907s  |   0.000s  | 0.0%|
|scheduling/orb04_1100.smt2                                                                  |   0.851s  |   0.851s  |   0.000s  | 0.0%|
|scheduling/orb04_1200.smt2                                                                  |   0.392s  |   0.392s  |   0.000s  | 0.0%|
|scheduling/orb04_850.smt2                                                                   |   0.342s  |   0.342s  |   0.000s  | 0.0%|
|scheduling/orb04_950.smt2                                                                   |   0.587s  |   0.587s  |   0.000s  | 0.0%|
|scheduling/orb05_1000.smt2                                                                  |   0.661s  |   0.661s  |   0.000s  | 0.0%|
|scheduling/orb05_700.smt2                                                                   |   0.311s  |   0.311s  |   0.000s  | 0.0%|
|scheduling/orb05_800.smt2                                                                   |   0.398s  |   0.398s  |   0.000s  | 0.0%|
|scheduling/orb05_887.smt2                                                                   |   6.625s  |   6.625s  |   0.000s  | 0.0%|
|scheduling/orb05_900.smt2                                                                   |   1.948s  |   1.948s  |   0.000s  | 0.0%|
|scheduling/orb06_1000.smt2                                                                  |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|scheduling/orb06_1010.smt2                                                                  |  30.061s  |  30.061s  |   0.000s  | 0.0%|
|scheduling/orb06_1100.smt2                                                                  |   0.829s  |   0.829s  |   0.000s  | 0.0%|
|scheduling/orb06_1200.smt2                                                                  |   0.398s  |   0.398s  |   0.000s  | 0.0%|
|scheduling/orb06_900.smt2                                                                   |   0.570s  |   0.570s  |   0.000s  | 0.0%|
|scheduling/orb07_250.smt2                                                                   |   0.280s  |   0.280s  |   0.000s  | 0.0%|
|scheduling/orb07_330.smt2                                                                   |   0.321s  |   0.321s  |   0.000s  | 0.0%|
|scheduling/orb07_397.smt2                                                                   |   3.721s  |   3.721s  |   0.000s  | 0.0%|
|scheduling/orb07_430.smt2                                                                   |   0.914s  |   0.914s  |   0.000s  | 0.0%|
|scheduling/orb07_550.smt2                                                                   |   0.271s  |   0.271s  |   0.000s  | 0.0%|
|scheduling/orb08_1000.smt2                                                                  |   0.627s  |   0.627s  |   0.000s  | 0.0%|
|scheduling/orb08_700.smt2                                                                   |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|scheduling/orb08_830.smt2                                                                   |   0.399s  |   0.399s  |   0.000s  | 0.0%|
|scheduling/orb08_888.smt2                                                                   |   8.512s  |   8.512s  |   0.000s  | 0.0%|
|scheduling/orb08_930.smt2                                                                   |   2.768s  |   2.768s  |   0.000s  | 0.0%|
|scheduling/orb09_1000.smt2                                                                  |   0.402s  |   0.402s  |   0.000s  | 0.0%|
|scheduling/orb09_1100.smt2                                                                  |   0.370s  |   0.370s  |   0.000s  | 0.0%|
|scheduling/orb09_800.smt2                                                                   |   0.341s  |   0.341s  |   0.000s  | 0.0%|
|scheduling/orb09_900.smt2                                                                   |   2.095s  |   2.095s  |   0.000s  | 0.0%|
|scheduling/orb09_934.smt2                                                                   |   2.482s  |   2.482s  |   0.000s  | 0.0%|
|scheduling/orb10_1000.smt2                                                                  |   1.145s  |   1.145s  |   0.000s  | 0.0%|
|scheduling/orb10_1100.smt2                                                                  |   0.381s  |   0.381s  |   0.000s  | 0.0%|
|scheduling/orb10_800.smt2                                                                   |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|scheduling/orb10_900.smt2                                                                   |   0.935s  |   0.935s  |   0.000s  | 0.0%|
|scheduling/orb10_944.smt2                                                                   |   3.926s  |   3.926s  |   0.000s  | 0.0%|
|scheduling/swv11_2900.smt2                                                                  |  30.154s  |  30.154s  |   0.000s  | 0.0%|
|scheduling/swv11_2983.smt2                                                                  |  30.122s  |  30.122s  |   0.000s  | 0.0%|
|scheduling/swv11_2988.smt2                                                                  |  30.145s  |  30.145s  |   0.000s  | 0.0%|
|scheduling/swv11_2992.smt2                                                                  |  30.120s  |  30.120s  |   0.000s  | 0.0%|
|scheduling/swv11_3050.smt2                                                                  |  30.138s  |  30.138s  |   0.000s  | 0.0%|
|scheduling/swv12_2900.smt2                                                                  |  30.129s  |  30.129s  |   0.000s  | 0.0%|
|scheduling/swv12_2972.smt2                                                                  |  30.154s  |  30.154s  |   0.000s  | 0.0%|
|scheduling/swv12_2990.smt2                                                                  |  30.115s  |  30.115s  |   0.000s  | 0.0%|
|scheduling/swv12_3004.smt2                                                                  |  30.136s  |  30.136s  |   0.000s  | 0.0%|
|scheduling/swv12_3050.smt2                                                                  |  30.125s  |  30.125s  |   0.000s  | 0.0%|
|scheduling/swv13_3000.smt2                                                                  |  30.149s  |  30.149s  |   0.000s  | 0.0%|
|scheduling/swv13_3104.smt2                                                                  |  30.144s  |  30.144s  |   0.000s  | 0.0%|
|scheduling/swv13_3150.smt2                                                                  |  30.131s  |  30.131s  |   0.000s  | 0.0%|
|scheduling/swv13_3200.smt2                                                                  |  30.150s  |  30.150s  |   0.000s  | 0.0%|
|scheduling/swv14_2800.smt2                                                                  |  30.189s  |  30.189s  |   0.000s  | 0.0%|
|scheduling/swv14_2885.smt2                                                                  |  30.131s  |  30.131s  |   0.000s  | 0.0%|
|scheduling/swv14_2895.smt2                                                                  |  30.143s  |  30.143s  |   0.000s  | 0.0%|
|scheduling/swv14_2905.smt2                                                                  |  30.111s  |  30.111s  |   0.000s  | 0.0%|
|scheduling/swv14_3000.smt2                                                                  |  30.133s  |  30.133s  |   0.000s  | 0.0%|
|scheduling/yn1_750.smt2                                                                     |   1.894s  |   1.894s  |   0.000s  | 0.0%|
|scheduling/yn1_827.smt2                                                                     |  30.077s  |  30.077s  |   0.000s  | 0.0%|
|scheduling/yn1_850.smt2                                                                     |  30.100s  |  30.100s  |   0.000s  | 0.0%|
|scheduling/yn1_887.smt2                                                                     |  30.094s  |  30.094s  |   0.000s  | 0.0%|
|scheduling/yn1_950.smt2                                                                     |  30.088s  |  30.088s  |   0.000s  | 0.0%|
|scheduling/yn2_750.smt2                                                                     |   6.832s  |   6.832s  |   0.000s  | 0.0%|
|scheduling/yn2_862.smt2                                                                     |  30.082s  |  30.082s  |   0.000s  | 0.0%|
|scheduling/yn2_890.smt2                                                                     |  30.094s  |  30.094s  |   0.000s  | 0.0%|
|scheduling/yn2_910.smt2                                                                     |  30.096s  |  30.096s  |   0.000s  | 0.0%|
|scheduling/yn2_950.smt2                                                                     |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|scheduling/yn3_750.smt2                                                                     |   5.975s  |   5.975s  |   0.000s  | 0.0%|
|scheduling/yn3_828.smt2                                                                     |  30.077s  |  30.077s  |   0.000s  | 0.0%|
|scheduling/yn3_860.smt2                                                                     |  30.097s  |  30.097s  |   0.000s  | 0.0%|
|scheduling/yn3_894.smt2                                                                     |  30.090s  |  30.090s  |   0.000s  | 0.0%|
|scheduling/yn3_950.smt2                                                                     |  30.073s  |  30.073s  |   0.000s  | 0.0%|
|scheduling/yn4_1000.smt2                                                                    |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|scheduling/yn4_850.smt2                                                                     |  30.088s  |  30.088s  |   0.000s  | 0.0%|
|scheduling/yn4_919.smt2                                                                     |  30.099s  |  30.099s  |   0.000s  | 0.0%|
|scheduling/yn4_950.smt2                                                                     |  30.082s  |  30.082s  |   0.000s  | 0.0%|
|scheduling/yn4_969.smt2                                                                     |  30.094s  |  30.094s  |   0.000s  | 0.0%|
|skdmxa/skdmxa-3x3-10.smt2                                                                   |   2.262s  |   2.262s  |   0.000s  | 0.0%|
|skdmxa/skdmxa-3x3-15.smt2                                                                   |  30.114s  |  30.114s  |   0.000s  | 0.0%|
|skdmxa/skdmxa-3x3-20.smt2                                                                   |  30.154s  |  30.154s  |   0.000s  | 0.0%|
|skdmxa/skdmxa-3x3-5.smt2                                                                    |   0.740s  |   0.740s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-10.base.cvc.smt2                                                         |   2.348s  |   2.348s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-10.induction.cvc.smt2                                                    |   3.023s  |   3.023s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-11.base.cvc.smt2                                                         |   5.287s  |   5.287s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-11.induction.cvc.smt2                                                    |   3.658s  |   3.658s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-12.base.cvc.smt2                                                         |  13.368s  |  13.368s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-12.induction.cvc.smt2                                                    |   3.618s  |   3.618s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-13.base.cvc.smt2                                                         |  30.097s  |  30.097s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-13.induction.cvc.smt2                                                    |   7.559s  |   7.559s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-14.base.cvc.smt2                                                         |  30.079s  |  30.079s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-14.induction.cvc.smt2                                                    |   5.695s  |   5.695s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-15.base.cvc.smt2                                                         |  30.076s  |  30.076s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-15.induction.cvc.smt2                                                    |  20.429s  |  20.429s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-16.base.cvc.smt2                                                         |  30.090s  |  30.090s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-16.induction.cvc.smt2                                                    |   8.466s  |   8.466s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-17.base.cvc.smt2                                                         |  30.131s  |  30.131s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-17.induction.cvc.smt2                                                    |  12.060s  |  12.060s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-18.base.cvc.smt2                                                         |  30.136s  |  30.136s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-18.induction.cvc.smt2                                                    |  13.659s  |  13.659s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-19.base.cvc.smt2                                                         |  30.098s  |  30.098s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-19.induction.cvc.smt2                                                    |  10.007s  |  10.007s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                         |  30.137s  |  30.137s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-20.induction.cvc.smt2                                                    |  30.176s  |  30.176s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-5.base.cvc.smt2                                                          |   1.143s  |   1.143s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-5.induction.cvc.smt2                                                     |   0.893s  |   0.893s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-6.base.cvc.smt2                                                          |   0.821s  |   0.821s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-6.induction.cvc.smt2                                                     |   1.139s  |   1.139s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-7.base.cvc.smt2                                                          |   1.116s  |   1.116s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-7.induction.cvc.smt2                                                     |   1.640s  |   1.640s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-8.base.cvc.smt2                                                          |   1.372s  |   1.372s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-8.induction.cvc.smt2                                                     |   1.917s  |   1.917s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-9.base.cvc.smt2                                                          |   1.640s  |   1.640s  |   0.000s  | 0.0%|
</details>
