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
Job tag: smt_qfrdl-threads-4-param_tuning-no_inprocessing-scaled_replay_conflicts
Runner: lev-ripper
Z3 repo: ilanashapiro/z3
Z3 commit: d631679e101d8a410ed7a9e2f9b793a0b158a243
Z3 branch: param-tuning
Z3 options: "-T:30 smt.threads=4 tactic.default_tactic=smt smt.auto_config.false smt_parallel.inprocessing=false"
Z3 inputs: inputs/QF_RDL
Z3 commit message: scaling m_max_prefix_conflicts

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt_qfrdl-threads-4-param_tuning-no_inprocessing-scaled_replay_conflicts
Runner: lev-ripper
Z3 repo: ilanashapiro/z3
Z3 commit: d631679e101d8a410ed7a9e2f9b793a0b158a243
Z3 branch: param-tuning
Z3 options: "-T:30 smt.threads=4 tactic.default_tactic=smt smt.auto_config.false smt_parallel.inprocessing=false"
Z3 inputs: inputs/QF_RDL
Z3 commit message: scaling m_max_prefix_conflicts

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.240s  |   0.240s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.240s  |   0.240s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.240s  |   0.240s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.240s  |   0.240s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scheduling/swv14_2800.smt2                                                                 |  30.223s |648.0MiB|
|scheduling/swv14_3000.smt2                                                                 |  30.195s |684.0MiB|
|scheduling/swv11_2900.smt2                                                                 |  30.193s |613.0MiB|
|scheduling/swv13_3150.smt2                                                                 |  30.193s |689.0MiB|
|scheduling/swv11_2992.smt2                                                                 |  30.192s |627.0MiB|
|scheduling/swv11_3050.smt2                                                                 |  30.159s |679.0MiB|
|scheduling/swv11_2983.smt2                                                                 |  30.151s |646.0MiB|
|scheduling/swv13_3000.smt2                                                                 |  30.151s |659.0MiB|
|scheduling/swv12_2900.smt2                                                                 |  30.132s |661.0MiB|
|scheduling/swv13_3200.smt2                                                                 |  30.131s |696.0MiB|
|scheduling/swv12_3004.smt2                                                                 |  30.130s |681.0MiB|
|scheduling/swv11_2988.smt2                                                                 |  30.130s |621.0MiB|
|scheduling/swv12_2972.smt2                                                                 |  30.128s |697.0MiB|
|scheduling/swv14_2885.smt2                                                                 |  30.126s |659.0MiB|
|scheduling/swv13_3104.smt2                                                                 |  30.126s |696.0MiB|
|scheduling/swv12_3050.smt2                                                                 |  30.125s |731.0MiB|
|scheduling/swv14_2895.smt2                                                                 |  30.125s |648.0MiB|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                        |  30.125s |739.0MiB|
|scheduling/swv14_2905.smt2                                                                 |  30.119s |653.0MiB|
|scheduling/swv12_2990.smt2                                                                 |  30.116s |664.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scheduling/swv14_2800.smt2                                                                 |  30.223s |648.0MiB|
|scheduling/swv14_3000.smt2                                                                 |  30.195s |684.0MiB|
|scheduling/swv11_2900.smt2                                                                 |  30.193s |613.0MiB|
|scheduling/swv13_3150.smt2                                                                 |  30.193s |689.0MiB|
|scheduling/swv11_2992.smt2                                                                 |  30.192s |627.0MiB|
|scheduling/swv11_3050.smt2                                                                 |  30.159s |679.0MiB|
|scheduling/swv11_2983.smt2                                                                 |  30.151s |646.0MiB|
|scheduling/swv13_3000.smt2                                                                 |  30.151s |659.0MiB|
|scheduling/swv12_2900.smt2                                                                 |  30.132s |661.0MiB|
|scheduling/swv13_3200.smt2                                                                 |  30.131s |696.0MiB|
|scheduling/swv12_3004.smt2                                                                 |  30.130s |681.0MiB|
|scheduling/swv11_2988.smt2                                                                 |  30.130s |621.0MiB|
|scheduling/swv12_2972.smt2                                                                 |  30.128s |697.0MiB|
|scheduling/swv14_2885.smt2                                                                 |  30.126s |659.0MiB|
|scheduling/swv13_3104.smt2                                                                 |  30.126s |696.0MiB|
|scheduling/swv12_3050.smt2                                                                 |  30.125s |731.0MiB|
|scheduling/swv14_2895.smt2                                                                 |  30.125s |648.0MiB|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                        |  30.125s |739.0MiB|
|scheduling/swv14_2905.smt2                                                                 |  30.119s |653.0MiB|
|scheduling/swv12_2990.smt2                                                                 |  30.116s |664.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |90.392MiB|90.392MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |90.972MiB|90.972MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |91.16MiB|91.16MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |91.928MiB|91.928MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |92.696MiB|92.696MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |92.952MiB|92.952MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |93.932MiB|93.932MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |94.072MiB|94.072MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |94.912MiB|94.912MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |95.7MiB|95.7MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |95.76MiB|95.76MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |96.084MiB|96.084MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |96.408MiB|96.408MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |97.696MiB|97.696MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |97.448MiB|97.448MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |98.776MiB|98.776MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |98.9MiB|98.9MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |99.364MiB|99.364MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |99.736MiB|99.736MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |98.0MiB|98.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |90.392MiB|90.392MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |90.972MiB|90.972MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |91.16MiB|91.16MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |91.928MiB|91.928MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |92.696MiB|92.696MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |92.952MiB|92.952MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |93.932MiB|93.932MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |94.072MiB|94.072MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |94.912MiB|94.912MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |95.7MiB|95.7MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |95.76MiB|95.76MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |96.084MiB|96.084MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |96.408MiB|96.408MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |97.696MiB|97.696MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |97.448MiB|97.448MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |98.776MiB|98.776MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |98.9MiB|98.9MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |99.364MiB|99.364MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |99.736MiB|99.736MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |98.0MiB|98.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |90.392MiB|90.392MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |90.972MiB|90.972MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |91.16MiB|91.16MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |91.928MiB|91.928MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |92.696MiB|92.696MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |92.952MiB|92.952MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |93.932MiB|93.932MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |94.072MiB|94.072MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |94.912MiB|94.912MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |95.7MiB|95.7MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |95.76MiB|95.76MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |96.084MiB|96.084MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |96.408MiB|96.408MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |97.696MiB|97.696MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |97.448MiB|97.448MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |98.776MiB|98.776MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |98.9MiB|98.9MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |99.364MiB|99.364MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |99.736MiB|99.736MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |98.0MiB|98.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |90.392MiB|90.392MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |90.972MiB|90.972MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |91.16MiB|91.16MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |91.928MiB|91.928MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |92.696MiB|92.696MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |92.952MiB|92.952MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |93.932MiB|93.932MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |94.072MiB|94.072MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |94.912MiB|94.912MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |95.7MiB|95.7MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |95.76MiB|95.76MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |96.084MiB|96.084MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |96.408MiB|96.408MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |97.696MiB|97.696MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |97.448MiB|97.448MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |98.776MiB|98.776MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |98.9MiB|98.9MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |99.364MiB|99.364MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |99.736MiB|99.736MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |98.0MiB|98.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|skdmxa2/skdmxa-3x3-18.induction.cvc.smt2                                                   |  14.829s |904.0MiB|
|skdmxa2/skdmxa-3x3-20.induction.cvc.smt2                                                   |  24.153s |901.0MiB|
|skdmxa2/skdmxa-3x3-19.induction.cvc.smt2                                                   |  12.450s |843.0MiB|
|skdmxa2/skdmxa-3x3-17.induction.cvc.smt2                                                   |  10.765s |798.0MiB|
|skdmxa2/skdmxa-3x3-15.induction.cvc.smt2                                                   |  11.718s |742.0MiB|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                        |  30.125s |739.0MiB|
|scheduling/swv12_3050.smt2                                                                 |  30.125s |731.0MiB|
|skdmxa2/skdmxa-3x3-16.induction.cvc.smt2                                                   |   8.611s |721.0MiB|
|skdmxa2/skdmxa-3x3-14.induction.cvc.smt2                                                   |   6.580s |698.0MiB|
|scheduling/swv12_2972.smt2                                                                 |  30.128s |697.0MiB|
|scheduling/swv13_3200.smt2                                                                 |  30.131s |696.0MiB|
|scheduling/swv13_3104.smt2                                                                 |  30.126s |696.0MiB|
|scheduling/swv13_3150.smt2                                                                 |  30.193s |689.0MiB|
|scheduling/swv14_3000.smt2                                                                 |  30.195s |684.0MiB|
|scheduling/swv12_3004.smt2                                                                 |  30.130s |681.0MiB|
|scheduling/swv11_3050.smt2                                                                 |  30.159s |679.0MiB|
|skdmxa2/skdmxa-3x3-19.base.cvc.smt2                                                        |  30.103s |673.0MiB|
|scheduling/swv12_2990.smt2                                                                 |  30.116s |664.0MiB|
|scheduling/swv12_2900.smt2                                                                 |  30.132s |661.0MiB|
|scheduling/swv13_3000.smt2                                                                 |  30.151s |659.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|skdmxa2/skdmxa-3x3-18.induction.cvc.smt2                                                   |  14.829s |904.0MiB|
|skdmxa2/skdmxa-3x3-20.induction.cvc.smt2                                                   |  24.153s |901.0MiB|
|skdmxa2/skdmxa-3x3-19.induction.cvc.smt2                                                   |  12.450s |843.0MiB|
|skdmxa2/skdmxa-3x3-17.induction.cvc.smt2                                                   |  10.765s |798.0MiB|
|skdmxa2/skdmxa-3x3-15.induction.cvc.smt2                                                   |  11.718s |742.0MiB|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                        |  30.125s |739.0MiB|
|scheduling/swv12_3050.smt2                                                                 |  30.125s |731.0MiB|
|skdmxa2/skdmxa-3x3-16.induction.cvc.smt2                                                   |   8.611s |721.0MiB|
|skdmxa2/skdmxa-3x3-14.induction.cvc.smt2                                                   |   6.580s |698.0MiB|
|scheduling/swv12_2972.smt2                                                                 |  30.128s |697.0MiB|
|scheduling/swv13_3200.smt2                                                                 |  30.131s |696.0MiB|
|scheduling/swv13_3104.smt2                                                                 |  30.126s |696.0MiB|
|scheduling/swv13_3150.smt2                                                                 |  30.193s |689.0MiB|
|scheduling/swv14_3000.smt2                                                                 |  30.195s |684.0MiB|
|scheduling/swv12_3004.smt2                                                                 |  30.130s |681.0MiB|
|scheduling/swv11_3050.smt2                                                                 |  30.159s |679.0MiB|
|skdmxa2/skdmxa-3x3-19.base.cvc.smt2                                                        |  30.103s |673.0MiB|
|scheduling/swv12_2990.smt2                                                                 |  30.116s |664.0MiB|
|scheduling/swv12_2900.smt2                                                                 |  30.132s |661.0MiB|
|scheduling/swv13_3000.smt2                                                                 |  30.151s |659.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking21.smt2                                             |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking22.smt2                                             |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-2.smt2                                         |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-3.smt2                                         |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-4.smt2                                         |   1.405s  |   1.405s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-5.smt2                                         |  13.034s  |  13.034s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-6.smt2                                         |  30.051s  |  30.051s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-7.smt2                                         |  30.051s  |  30.051s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-matrix1x1.pddl.smt2                                  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-matrix2x2.pddl.smt2                                  |  30.063s  |  30.063s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-1.smt2                                         |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-2.smt2                                         |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-3.smt2                                         |   0.571s  |   0.571s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-4.smt2                                         |  20.141s  |  20.141s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-5.smt2                                         |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-6.smt2                                         |  30.075s  |  30.075s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-03.smt2                                      |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-04.smt2                                      |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-05.smt2                                      |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-06.smt2                                      |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-07.smt2                                      |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-08.smt2                                      |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-09.smt2                                      |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-10.smt2                                      |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-20.smt2                                      |   0.271s  |   0.271s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-30.smt2                                      |   0.471s  |   0.471s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-40.smt2                                      |   0.753s  |   0.753s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-60.smt2                                      |   1.978s  |   1.978s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-70.smt2                                      |   3.527s  |   3.527s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-80.smt2                                      |   3.711s  |   3.711s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-90.smt2                                      |   5.350s  |   5.350s  |   0.000s  | 0.0%|
|check/bignum_rdl1.smt2                                                                      |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|check/bignum_rdl2.smt2                                                                      |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-1.smt2                                                                   |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-10.smt2                                                                  |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-11.smt2                                                                  |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-12.smt2                                                                  |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-13.smt2                                                                  |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-14.smt2                                                                  |   0.406s  |   0.406s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-15.smt2                                                                  |   0.473s  |   0.473s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-16.smt2                                                                  |   0.360s  |   0.360s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-17.smt2                                                                  |   0.551s  |   0.551s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-18.smt2                                                                  |   0.972s  |   0.972s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-19.smt2                                                                  |   1.152s  |   1.152s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-2.smt2                                                                   |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-20.smt2                                                                  |   1.142s  |   1.142s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-3.smt2                                                                   |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-4.smt2                                                                   |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-5.smt2                                                                   |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-6.smt2                                                                   |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-7.smt2                                                                   |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-8.smt2                                                                   |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-9.smt2                                                                   |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-1.smt2                                                                   |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-10.smt2                                                                  |   0.701s  |   0.701s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-11.smt2                                                                  |   1.457s  |   1.457s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-12.smt2                                                                  |   1.419s  |   1.419s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-13.smt2                                                                  |   2.327s  |   2.327s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-14.smt2                                                                  |   4.134s  |   4.134s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-15.smt2                                                                  |   4.837s  |   4.837s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-16.smt2                                                                  |   8.701s  |   8.701s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-17.smt2                                                                  |  10.577s  |  10.577s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-18.smt2                                                                  |  10.719s  |  10.719s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-19.smt2                                                                  |  20.282s  |  20.282s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-2.smt2                                                                   |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-20.smt2                                                                  |  30.021s  |  30.021s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-3.smt2                                                                   |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-4.smt2                                                                   |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-5.smt2                                                                   |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-6.smt2                                                                   |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-7.smt2                                                                   |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-8.smt2                                                                   |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-9.smt2                                                                   |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-1.smt2                                                                   |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-10.smt2                                                                  |   2.555s  |   2.555s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-11.smt2                                                                  |   3.355s  |   3.355s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-12.smt2                                                                  |   5.445s  |   5.445s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-13.smt2                                                                  |   8.706s  |   8.706s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-14.smt2                                                                  |  20.482s  |  20.482s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-15.smt2                                                                  |  25.051s  |  25.051s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-16.smt2                                                                  |  27.512s  |  27.512s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-17.smt2                                                                  |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-18.smt2                                                                  |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-19.smt2                                                                  |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-2.smt2                                                                   |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-20.smt2                                                                  |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-3.smt2                                                                   |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-4.smt2                                                                   |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-5.smt2                                                                   |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-6.smt2                                                                   |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-7.smt2                                                                   |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-8.smt2                                                                   |   0.368s  |   0.368s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-9.smt2                                                                   |   1.143s  |   1.143s  |   0.000s  | 0.0%|
|scheduling/abz5_1000.smt2                                                                   |   0.281s  |   0.281s  |   0.000s  | 0.0%|
|scheduling/abz5_1200.smt2                                                                   |   3.269s  |   3.269s  |   0.000s  | 0.0%|
|scheduling/abz5_1234.smt2                                                                   |   3.576s  |   3.576s  |   0.000s  | 0.0%|
|scheduling/abz5_1300.smt2                                                                   |   0.654s  |   0.654s  |   0.000s  | 0.0%|
|scheduling/abz5_1400.smt2                                                                   |   0.364s  |   0.364s  |   0.000s  | 0.0%|
|scheduling/abz6_1000.smt2                                                                   |   0.481s  |   0.481s  |   0.000s  | 0.0%|
|scheduling/abz6_1100.smt2                                                                   |   0.441s  |   0.441s  |   0.000s  | 0.0%|
|scheduling/abz6_800.smt2                                                                    |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|scheduling/abz6_900.smt2                                                                    |   0.446s  |   0.446s  |   0.000s  | 0.0%|
|scheduling/abz6_943.smt2                                                                    |   1.048s  |   1.048s  |   0.000s  | 0.0%|
|scheduling/abz7_500.smt2                                                                    |   2.609s  |   2.609s  |   0.000s  | 0.0%|
|scheduling/abz7_600.smt2                                                                    |  30.076s  |  30.076s  |   0.000s  | 0.0%|
|scheduling/abz7_667.smt2                                                                    |  30.080s  |  30.080s  |   0.000s  | 0.0%|
|scheduling/abz7_670.smt2                                                                    |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|scheduling/abz7_691.smt2                                                                    |  30.076s  |  30.076s  |   0.000s  | 0.0%|
|scheduling/abz7_700.smt2                                                                    |  30.066s  |  30.066s  |   0.000s  | 0.0%|
|scheduling/abz7_800.smt2                                                                    |  30.076s  |  30.076s  |   0.000s  | 0.0%|
|scheduling/orb01_1000.smt2                                                                  |  28.622s  |  28.622s  |   0.000s  | 0.0%|
|scheduling/orb01_1059.smt2                                                                  |  30.069s  |  30.069s  |   0.000s  | 0.0%|
|scheduling/orb01_1100.smt2                                                                  |  17.519s  |  17.519s  |   0.000s  | 0.0%|
|scheduling/orb01_1200.smt2                                                                  |   1.953s  |   1.953s  |   0.000s  | 0.0%|
|scheduling/orb01_900.smt2                                                                   |   0.721s  |   0.721s  |   0.000s  | 0.0%|
|scheduling/orb02_1000.smt2                                                                  |   0.396s  |   0.396s  |   0.000s  | 0.0%|
|scheduling/orb02_700.smt2                                                                   |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|scheduling/orb02_800.smt2                                                                   |   0.382s  |   0.382s  |   0.000s  | 0.0%|
|scheduling/orb02_888.smt2                                                                   |   2.079s  |   2.079s  |   0.000s  | 0.0%|
|scheduling/orb02_900.smt2                                                                   |   1.270s  |   1.270s  |   0.000s  | 0.0%|
|scheduling/orb03_1005.smt2                                                                  |  30.051s  |  30.051s  |   0.000s  | 0.0%|
|scheduling/orb03_1100.smt2                                                                  |   0.944s  |   0.944s  |   0.000s  | 0.0%|
|scheduling/orb03_1200.smt2                                                                  |   0.586s  |   0.586s  |   0.000s  | 0.0%|
|scheduling/orb03_850.smt2                                                                   |   0.406s  |   0.406s  |   0.000s  | 0.0%|
|scheduling/orb03_950.smt2                                                                   |  18.088s  |  18.088s  |   0.000s  | 0.0%|
|scheduling/orb04_1005.smt2                                                                  |  10.748s  |  10.748s  |   0.000s  | 0.0%|
|scheduling/orb04_1100.smt2                                                                  |   0.747s  |   0.747s  |   0.000s  | 0.0%|
|scheduling/orb04_1200.smt2                                                                  |   0.453s  |   0.453s  |   0.000s  | 0.0%|
|scheduling/orb04_850.smt2                                                                   |   0.311s  |   0.311s  |   0.000s  | 0.0%|
|scheduling/orb04_950.smt2                                                                   |   0.707s  |   0.707s  |   0.000s  | 0.0%|
|scheduling/orb05_1000.smt2                                                                  |   0.597s  |   0.597s  |   0.000s  | 0.0%|
|scheduling/orb05_700.smt2                                                                   |   0.334s  |   0.334s  |   0.000s  | 0.0%|
|scheduling/orb05_800.smt2                                                                   |   0.497s  |   0.497s  |   0.000s  | 0.0%|
|scheduling/orb05_887.smt2                                                                   |   6.987s  |   6.987s  |   0.000s  | 0.0%|
|scheduling/orb05_900.smt2                                                                   |   1.637s  |   1.637s  |   0.000s  | 0.0%|
|scheduling/orb06_1000.smt2                                                                  |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|scheduling/orb06_1010.smt2                                                                  |  30.070s  |  30.070s  |   0.000s  | 0.0%|
|scheduling/orb06_1100.smt2                                                                  |   2.339s  |   2.339s  |   0.000s  | 0.0%|
|scheduling/orb06_1200.smt2                                                                  |   0.358s  |   0.358s  |   0.000s  | 0.0%|
|scheduling/orb06_900.smt2                                                                   |   0.605s  |   0.605s  |   0.000s  | 0.0%|
|scheduling/orb07_250.smt2                                                                   |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|scheduling/orb07_330.smt2                                                                   |   0.325s  |   0.325s  |   0.000s  | 0.0%|
|scheduling/orb07_397.smt2                                                                   |   2.693s  |   2.693s  |   0.000s  | 0.0%|
|scheduling/orb07_430.smt2                                                                   |   0.921s  |   0.921s  |   0.000s  | 0.0%|
|scheduling/orb07_550.smt2                                                                   |   0.352s  |   0.352s  |   0.000s  | 0.0%|
|scheduling/orb08_1000.smt2                                                                  |   0.798s  |   0.798s  |   0.000s  | 0.0%|
|scheduling/orb08_700.smt2                                                                   |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|scheduling/orb08_830.smt2                                                                   |   0.308s  |   0.308s  |   0.000s  | 0.0%|
|scheduling/orb08_888.smt2                                                                   |  14.400s  |  14.400s  |   0.000s  | 0.0%|
|scheduling/orb08_930.smt2                                                                   |   4.695s  |   4.695s  |   0.000s  | 0.0%|
|scheduling/orb09_1000.smt2                                                                  |   0.434s  |   0.434s  |   0.000s  | 0.0%|
|scheduling/orb09_1100.smt2                                                                  |   0.368s  |   0.368s  |   0.000s  | 0.0%|
|scheduling/orb09_800.smt2                                                                   |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|scheduling/orb09_900.smt2                                                                   |   2.160s  |   2.160s  |   0.000s  | 0.0%|
|scheduling/orb09_934.smt2                                                                   |   2.043s  |   2.043s  |   0.000s  | 0.0%|
|scheduling/orb10_1000.smt2                                                                  |   3.538s  |   3.538s  |   0.000s  | 0.0%|
|scheduling/orb10_1100.smt2                                                                  |   0.422s  |   0.422s  |   0.000s  | 0.0%|
|scheduling/orb10_800.smt2                                                                   |   0.262s  |   0.262s  |   0.000s  | 0.0%|
|scheduling/orb10_900.smt2                                                                   |   1.159s  |   1.159s  |   0.000s  | 0.0%|
|scheduling/orb10_944.smt2                                                                   |   4.428s  |   4.428s  |   0.000s  | 0.0%|
|scheduling/swv11_2900.smt2                                                                  |  30.193s  |  30.193s  |   0.000s  | 0.0%|
|scheduling/swv11_2983.smt2                                                                  |  30.151s  |  30.151s  |   0.000s  | 0.0%|
|scheduling/swv11_2988.smt2                                                                  |  30.130s  |  30.130s  |   0.000s  | 0.0%|
|scheduling/swv11_2992.smt2                                                                  |  30.192s  |  30.192s  |   0.000s  | 0.0%|
|scheduling/swv11_3050.smt2                                                                  |  30.159s  |  30.159s  |   0.000s  | 0.0%|
|scheduling/swv12_2900.smt2                                                                  |  30.132s  |  30.132s  |   0.000s  | 0.0%|
|scheduling/swv12_2972.smt2                                                                  |  30.128s  |  30.128s  |   0.000s  | 0.0%|
|scheduling/swv12_2990.smt2                                                                  |  30.116s  |  30.116s  |   0.000s  | 0.0%|
|scheduling/swv12_3004.smt2                                                                  |  30.130s  |  30.130s  |   0.000s  | 0.0%|
|scheduling/swv12_3050.smt2                                                                  |  30.125s  |  30.125s  |   0.000s  | 0.0%|
|scheduling/swv13_3000.smt2                                                                  |  30.151s  |  30.151s  |   0.000s  | 0.0%|
|scheduling/swv13_3104.smt2                                                                  |  30.126s  |  30.126s  |   0.000s  | 0.0%|
|scheduling/swv13_3150.smt2                                                                  |  30.193s  |  30.193s  |   0.000s  | 0.0%|
|scheduling/swv13_3200.smt2                                                                  |  30.131s  |  30.131s  |   0.000s  | 0.0%|
|scheduling/swv14_2800.smt2                                                                  |  30.223s  |  30.223s  |   0.000s  | 0.0%|
|scheduling/swv14_2885.smt2                                                                  |  30.126s  |  30.126s  |   0.000s  | 0.0%|
|scheduling/swv14_2895.smt2                                                                  |  30.125s  |  30.125s  |   0.000s  | 0.0%|
|scheduling/swv14_2905.smt2                                                                  |  30.119s  |  30.119s  |   0.000s  | 0.0%|
|scheduling/swv14_3000.smt2                                                                  |  30.195s  |  30.195s  |   0.000s  | 0.0%|
|scheduling/yn1_750.smt2                                                                     |   1.995s  |   1.995s  |   0.000s  | 0.0%|
|scheduling/yn1_827.smt2                                                                     |  30.084s  |  30.084s  |   0.000s  | 0.0%|
|scheduling/yn1_850.smt2                                                                     |  30.075s  |  30.075s  |   0.000s  | 0.0%|
|scheduling/yn1_887.smt2                                                                     |  30.099s  |  30.099s  |   0.000s  | 0.0%|
|scheduling/yn1_950.smt2                                                                     |  30.063s  |  30.063s  |   0.000s  | 0.0%|
|scheduling/yn2_750.smt2                                                                     |   5.001s  |   5.001s  |   0.000s  | 0.0%|
|scheduling/yn2_862.smt2                                                                     |  30.087s  |  30.087s  |   0.000s  | 0.0%|
|scheduling/yn2_890.smt2                                                                     |  30.113s  |  30.113s  |   0.000s  | 0.0%|
|scheduling/yn2_910.smt2                                                                     |  30.103s  |  30.103s  |   0.000s  | 0.0%|
|scheduling/yn2_950.smt2                                                                     |  30.062s  |  30.062s  |   0.000s  | 0.0%|
|scheduling/yn3_750.smt2                                                                     |   5.477s  |   5.477s  |   0.000s  | 0.0%|
|scheduling/yn3_828.smt2                                                                     |  30.064s  |  30.064s  |   0.000s  | 0.0%|
|scheduling/yn3_860.smt2                                                                     |  30.079s  |  30.079s  |   0.000s  | 0.0%|
|scheduling/yn3_894.smt2                                                                     |  30.101s  |  30.101s  |   0.000s  | 0.0%|
|scheduling/yn3_950.smt2                                                                     |  30.070s  |  30.070s  |   0.000s  | 0.0%|
|scheduling/yn4_1000.smt2                                                                    |  30.076s  |  30.076s  |   0.000s  | 0.0%|
|scheduling/yn4_850.smt2                                                                     |  30.082s  |  30.082s  |   0.000s  | 0.0%|
|scheduling/yn4_919.smt2                                                                     |  30.086s  |  30.086s  |   0.000s  | 0.0%|
|scheduling/yn4_950.smt2                                                                     |  30.078s  |  30.078s  |   0.000s  | 0.0%|
|scheduling/yn4_969.smt2                                                                     |  30.075s  |  30.075s  |   0.000s  | 0.0%|
|skdmxa/skdmxa-3x3-10.smt2                                                                   |   2.351s  |   2.351s  |   0.000s  | 0.0%|
|skdmxa/skdmxa-3x3-15.smt2                                                                   |  30.095s  |  30.095s  |   0.000s  | 0.0%|
|skdmxa/skdmxa-3x3-20.smt2                                                                   |  30.091s  |  30.091s  |   0.000s  | 0.0%|
|skdmxa/skdmxa-3x3-5.smt2                                                                    |   0.689s  |   0.689s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-10.base.cvc.smt2                                                         |   2.367s  |   2.367s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-10.induction.cvc.smt2                                                    |   3.242s  |   3.242s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-11.base.cvc.smt2                                                         |   6.456s  |   6.456s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-11.induction.cvc.smt2                                                    |   4.084s  |   4.084s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-12.base.cvc.smt2                                                         |  26.437s  |  26.437s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-12.induction.cvc.smt2                                                    |   4.045s  |   4.045s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-13.base.cvc.smt2                                                         |  30.107s  |  30.107s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-13.induction.cvc.smt2                                                    |   9.662s  |   9.662s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-14.base.cvc.smt2                                                         |  30.102s  |  30.102s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-14.induction.cvc.smt2                                                    |   6.580s  |   6.580s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-15.base.cvc.smt2                                                         |  30.086s  |  30.086s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-15.induction.cvc.smt2                                                    |  11.718s  |  11.718s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-16.base.cvc.smt2                                                         |  30.101s  |  30.101s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-16.induction.cvc.smt2                                                    |   8.611s  |   8.611s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-17.base.cvc.smt2                                                         |  30.103s  |  30.103s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-17.induction.cvc.smt2                                                    |  10.765s  |  10.765s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-18.base.cvc.smt2                                                         |  30.097s  |  30.097s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-18.induction.cvc.smt2                                                    |  14.829s  |  14.829s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-19.base.cvc.smt2                                                         |  30.103s  |  30.103s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-19.induction.cvc.smt2                                                    |  12.450s  |  12.450s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                         |  30.125s  |  30.125s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-20.induction.cvc.smt2                                                    |  24.153s  |  24.153s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-5.base.cvc.smt2                                                          |   1.070s  |   1.070s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-5.induction.cvc.smt2                                                     |   0.898s  |   0.898s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-6.base.cvc.smt2                                                          |   0.834s  |   0.834s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-6.induction.cvc.smt2                                                     |   1.172s  |   1.172s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-7.base.cvc.smt2                                                          |   1.121s  |   1.121s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-7.induction.cvc.smt2                                                     |   1.647s  |   1.647s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-8.base.cvc.smt2                                                          |   1.365s  |   1.365s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-8.induction.cvc.smt2                                                     |   1.983s  |   1.983s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-9.base.cvc.smt2                                                          |   1.633s  |   1.633s  |   0.000s  | 0.0%|
</details>
