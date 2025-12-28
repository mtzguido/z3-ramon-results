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
Job tag: smt_qfrdl-threads-4-inprocessing
Runner: lev-ripper
Z3 repo: ilanashapiro/z3
Z3 commit: 82e9cc4a848d2c0a9d85241a0ea1f13168231009
Z3 branch: parallel-lockdebug1
Z3 options: "-T:30 smt.threads=4 tactic.default_tactic=smt smt.auto_config.false smt_parallel.inprocessing=true"
Z3 inputs: inputs/QF_RDL
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into parallel-lockdebug1

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt_qfrdl-threads-4-inprocessing
Runner: lev-ripper
Z3 repo: ilanashapiro/z3
Z3 commit: 82e9cc4a848d2c0a9d85241a0ea1f13168231009
Z3 branch: parallel-lockdebug1
Z3 options: "-T:30 smt.threads=4 tactic.default_tactic=smt smt.auto_config.false smt_parallel.inprocessing=true"
Z3 inputs: inputs/QF_RDL
Z3 commit message: Merge branch 'master' of github.com:Z3Prover/z3 into parallel-lockdebug1

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.229s  |   0.229s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.229s  |   0.229s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.229s  |   0.229s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.229s  |   0.229s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|skdmxa2/skdmxa-3x3-15.base.cvc.smt2                                                        |  30.272s |1469.0MiB|
|skdmxa2/skdmxa-3x3-16.base.cvc.smt2                                                        |  30.253s |1399.0MiB|
|skdmxa2/skdmxa-3x3-18.base.cvc.smt2                                                        |  30.204s |1638.0MiB|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                        |  30.198s |1390.0MiB|
|scheduling/swv13_3200.smt2                                                                 |  30.193s |703.0MiB|
|skdmxa2/skdmxa-3x3-14.base.cvc.smt2                                                        |  30.185s |1281.0MiB|
|skdmxa2/skdmxa-3x3-17.base.cvc.smt2                                                        |  30.180s |1441.0MiB|
|scheduling/swv13_3104.smt2                                                                 |  30.177s |724.0MiB|
|skdmxa2/skdmxa-3x3-19.base.cvc.smt2                                                        |  30.177s |1304.0MiB|
|skdmxa2/skdmxa-3x3-12.base.cvc.smt2                                                        |  30.169s |1112.0MiB|
|skdmxa2/skdmxa-3x3-20.induction.cvc.smt2                                                   |  30.166s |985.0MiB|
|skdmxa2/skdmxa-3x3-13.base.cvc.smt2                                                        |  30.161s |1190.0MiB|
|scheduling/swv11_2900.smt2                                                                 |  30.154s |635.0MiB|
|scheduling/swv14_3000.smt2                                                                 |  30.147s |673.0MiB|
|scheduling/swv11_2988.smt2                                                                 |  30.146s |595.0MiB|
|scheduling/swv11_3050.smt2                                                                 |  30.143s |632.0MiB|
|scheduling/swv14_2800.smt2                                                                 |  30.142s |630.0MiB|
|scheduling/swv11_2983.smt2                                                                 |  30.141s |640.0MiB|
|scheduling/swv14_2905.smt2                                                                 |  30.141s |637.0MiB|
|scheduling/swv12_2990.smt2                                                                 |  30.140s |684.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|skdmxa2/skdmxa-3x3-15.base.cvc.smt2                                                        |  30.272s |1469.0MiB|
|skdmxa2/skdmxa-3x3-16.base.cvc.smt2                                                        |  30.253s |1399.0MiB|
|skdmxa2/skdmxa-3x3-18.base.cvc.smt2                                                        |  30.204s |1638.0MiB|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                        |  30.198s |1390.0MiB|
|scheduling/swv13_3200.smt2                                                                 |  30.193s |703.0MiB|
|skdmxa2/skdmxa-3x3-14.base.cvc.smt2                                                        |  30.185s |1281.0MiB|
|skdmxa2/skdmxa-3x3-17.base.cvc.smt2                                                        |  30.180s |1441.0MiB|
|scheduling/swv13_3104.smt2                                                                 |  30.177s |724.0MiB|
|skdmxa2/skdmxa-3x3-19.base.cvc.smt2                                                        |  30.177s |1304.0MiB|
|skdmxa2/skdmxa-3x3-12.base.cvc.smt2                                                        |  30.169s |1112.0MiB|
|skdmxa2/skdmxa-3x3-20.induction.cvc.smt2                                                   |  30.166s |985.0MiB|
|skdmxa2/skdmxa-3x3-13.base.cvc.smt2                                                        |  30.161s |1190.0MiB|
|scheduling/swv11_2900.smt2                                                                 |  30.154s |635.0MiB|
|scheduling/swv14_3000.smt2                                                                 |  30.147s |673.0MiB|
|scheduling/swv11_2988.smt2                                                                 |  30.146s |595.0MiB|
|scheduling/swv11_3050.smt2                                                                 |  30.143s |632.0MiB|
|scheduling/swv14_2800.smt2                                                                 |  30.142s |630.0MiB|
|scheduling/swv11_2983.smt2                                                                 |  30.141s |640.0MiB|
|scheduling/swv14_2905.smt2                                                                 |  30.141s |637.0MiB|
|scheduling/swv12_2990.smt2                                                                 |  30.140s |684.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |90.34MiB|90.34MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |90.904MiB|90.904MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |91.164MiB|91.164MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |91.928MiB|91.928MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |92.536MiB|92.536MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |92.908MiB|92.908MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |93.412MiB|93.412MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |94.02MiB|94.02MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |94.76MiB|94.76MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |95.636MiB|95.636MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |95.724MiB|95.724MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |96.012MiB|96.012MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |96.664MiB|96.664MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |96.932MiB|96.932MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |97.568MiB|97.568MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |98.436MiB|98.436MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |99.308MiB|99.308MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |99.256MiB|99.256MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |97.0MiB|97.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |98.0MiB|98.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |90.34MiB|90.34MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |90.904MiB|90.904MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |91.164MiB|91.164MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |91.928MiB|91.928MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |92.536MiB|92.536MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |92.908MiB|92.908MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |93.412MiB|93.412MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |94.02MiB|94.02MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |94.76MiB|94.76MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |95.636MiB|95.636MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |95.724MiB|95.724MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |96.012MiB|96.012MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |96.664MiB|96.664MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |96.932MiB|96.932MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |97.568MiB|97.568MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |98.436MiB|98.436MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |99.308MiB|99.308MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |99.256MiB|99.256MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |97.0MiB|97.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |98.0MiB|98.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |90.34MiB|90.34MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |90.904MiB|90.904MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |91.164MiB|91.164MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |91.928MiB|91.928MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |92.536MiB|92.536MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |92.908MiB|92.908MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |93.412MiB|93.412MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |94.02MiB|94.02MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |94.76MiB|94.76MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |95.636MiB|95.636MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |95.724MiB|95.724MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |96.012MiB|96.012MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |96.664MiB|96.664MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |96.932MiB|96.932MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |97.568MiB|97.568MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |98.436MiB|98.436MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |99.308MiB|99.308MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |99.256MiB|99.256MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |97.0MiB|97.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |98.0MiB|98.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |90.34MiB|90.34MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |90.904MiB|90.904MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |91.164MiB|91.164MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |91.928MiB|91.928MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |92.536MiB|92.536MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |92.908MiB|92.908MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |93.412MiB|93.412MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |94.02MiB|94.02MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |94.76MiB|94.76MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |95.636MiB|95.636MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |95.724MiB|95.724MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |96.012MiB|96.012MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |96.664MiB|96.664MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |96.932MiB|96.932MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |97.568MiB|97.568MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |98.436MiB|98.436MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |99.308MiB|99.308MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |99.256MiB|99.256MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |97.0MiB|97.0MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |98.0MiB|98.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|skdmxa2/skdmxa-3x3-18.base.cvc.smt2                                                        |  30.204s |1638.0MiB|
|skdmxa2/skdmxa-3x3-15.base.cvc.smt2                                                        |  30.272s |1469.0MiB|
|skdmxa2/skdmxa-3x3-17.base.cvc.smt2                                                        |  30.180s |1441.0MiB|
|skdmxa2/skdmxa-3x3-16.base.cvc.smt2                                                        |  30.253s |1399.0MiB|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                        |  30.198s |1390.0MiB|
|skdmxa2/skdmxa-3x3-19.base.cvc.smt2                                                        |  30.177s |1304.0MiB|
|skdmxa2/skdmxa-3x3-14.base.cvc.smt2                                                        |  30.185s |1281.0MiB|
|skdmxa2/skdmxa-3x3-13.base.cvc.smt2                                                        |  30.161s |1190.0MiB|
|skdmxa2/skdmxa-3x3-12.base.cvc.smt2                                                        |  30.169s |1112.0MiB|
|skdmxa2/skdmxa-3x3-20.induction.cvc.smt2                                                   |  30.166s |985.0MiB|
|skdmxa2/skdmxa-3x3-18.induction.cvc.smt2                                                   |  13.920s |875.0MiB|
|skdmxa2/skdmxa-3x3-19.induction.cvc.smt2                                                   |  12.639s |852.0MiB|
|skdmxa/skdmxa-3x3-20.smt2                                                                  |  30.132s |850.0MiB|
|skdmxa2/skdmxa-3x3-17.induction.cvc.smt2                                                   |  12.496s |838.0MiB|
|SMT-Temporal-Planning-Benchmarks/tempo-width-6.smt2                                        |  11.834s |832.0MiB|
|skdmxa2/skdmxa-3x3-11.base.cvc.smt2                                                        |   9.118s |778.0MiB|
|scheduling/swv12_3050.smt2                                                                 |  30.129s |764.0MiB|
|skdmxa2/skdmxa-3x3-15.induction.cvc.smt2                                                   |  12.522s |746.0MiB|
|scheduling/swv13_3104.smt2                                                                 |  30.177s |724.0MiB|
|scheduling/swv13_3150.smt2                                                                 |  30.132s |724.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|skdmxa2/skdmxa-3x3-18.base.cvc.smt2                                                        |  30.204s |1638.0MiB|
|skdmxa2/skdmxa-3x3-15.base.cvc.smt2                                                        |  30.272s |1469.0MiB|
|skdmxa2/skdmxa-3x3-17.base.cvc.smt2                                                        |  30.180s |1441.0MiB|
|skdmxa2/skdmxa-3x3-16.base.cvc.smt2                                                        |  30.253s |1399.0MiB|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                        |  30.198s |1390.0MiB|
|skdmxa2/skdmxa-3x3-19.base.cvc.smt2                                                        |  30.177s |1304.0MiB|
|skdmxa2/skdmxa-3x3-14.base.cvc.smt2                                                        |  30.185s |1281.0MiB|
|skdmxa2/skdmxa-3x3-13.base.cvc.smt2                                                        |  30.161s |1190.0MiB|
|skdmxa2/skdmxa-3x3-12.base.cvc.smt2                                                        |  30.169s |1112.0MiB|
|skdmxa2/skdmxa-3x3-20.induction.cvc.smt2                                                   |  30.166s |985.0MiB|
|skdmxa2/skdmxa-3x3-18.induction.cvc.smt2                                                   |  13.920s |875.0MiB|
|skdmxa2/skdmxa-3x3-19.induction.cvc.smt2                                                   |  12.639s |852.0MiB|
|skdmxa/skdmxa-3x3-20.smt2                                                                  |  30.132s |850.0MiB|
|skdmxa2/skdmxa-3x3-17.induction.cvc.smt2                                                   |  12.496s |838.0MiB|
|SMT-Temporal-Planning-Benchmarks/tempo-width-6.smt2                                        |  11.834s |832.0MiB|
|skdmxa2/skdmxa-3x3-11.base.cvc.smt2                                                        |   9.118s |778.0MiB|
|scheduling/swv12_3050.smt2                                                                 |  30.129s |764.0MiB|
|skdmxa2/skdmxa-3x3-15.induction.cvc.smt2                                                   |  12.522s |746.0MiB|
|scheduling/swv13_3104.smt2                                                                 |  30.177s |724.0MiB|
|scheduling/swv13_3150.smt2                                                                 |  30.132s |724.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking21.smt2                                             |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking22.smt2                                             |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-2.smt2                                         |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-3.smt2                                         |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-4.smt2                                         |   0.859s  |   0.859s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-5.smt2                                         |   1.490s  |   1.490s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-6.smt2                                         |   2.783s  |   2.783s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-7.smt2                                         |   4.600s  |   4.600s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-matrix1x1.pddl.smt2                                  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-matrix2x2.pddl.smt2                                  |   6.988s  |   6.988s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-1.smt2                                         |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-2.smt2                                         |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-3.smt2                                         |   0.461s  |   0.461s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-4.smt2                                         |   1.508s  |   1.508s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-5.smt2                                         |   5.421s  |   5.421s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-6.smt2                                         |  11.834s  |  11.834s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-03.smt2                                      |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-04.smt2                                      |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-05.smt2                                      |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-06.smt2                                      |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-07.smt2                                      |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-08.smt2                                      |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-09.smt2                                      |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-10.smt2                                      |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-20.smt2                                      |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-30.smt2                                      |   0.469s  |   0.469s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-40.smt2                                      |   1.043s  |   1.043s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-60.smt2                                      |   1.422s  |   1.422s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-70.smt2                                      |   1.546s  |   1.546s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-80.smt2                                      |   1.790s  |   1.790s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-90.smt2                                      |   1.901s  |   1.901s  |   0.000s  | 0.0%|
|check/bignum_rdl1.smt2                                                                      |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|check/bignum_rdl2.smt2                                                                      |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-1.smt2                                                                   |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-10.smt2                                                                  |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-11.smt2                                                                  |   0.391s  |   0.391s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-12.smt2                                                                  |   0.534s  |   0.534s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-13.smt2                                                                  |   0.859s  |   0.859s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-14.smt2                                                                  |   0.877s  |   0.877s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-15.smt2                                                                  |   0.972s  |   0.972s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-16.smt2                                                                  |   1.436s  |   1.436s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-17.smt2                                                                  |   1.883s  |   1.883s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-18.smt2                                                                  |   1.919s  |   1.919s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-19.smt2                                                                  |   3.339s  |   3.339s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-2.smt2                                                                   |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-20.smt2                                                                  |   4.276s  |   4.276s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-3.smt2                                                                   |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-4.smt2                                                                   |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-5.smt2                                                                   |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-6.smt2                                                                   |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-7.smt2                                                                   |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-8.smt2                                                                   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-9.smt2                                                                   |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-1.smt2                                                                   |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-10.smt2                                                                  |   1.837s  |   1.837s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-11.smt2                                                                  |   3.344s  |   3.344s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-12.smt2                                                                  |   5.326s  |   5.326s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-13.smt2                                                                  |   9.466s  |   9.466s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-14.smt2                                                                  |  14.570s  |  14.570s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-15.smt2                                                                  |  29.088s  |  29.088s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-16.smt2                                                                  |  30.023s  |  30.023s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-17.smt2                                                                  |  30.025s  |  30.025s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-18.smt2                                                                  |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-19.smt2                                                                  |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-2.smt2                                                                   |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-20.smt2                                                                  |  30.051s  |  30.051s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-3.smt2                                                                   |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-4.smt2                                                                   |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-5.smt2                                                                   |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-6.smt2                                                                   |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-7.smt2                                                                   |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-8.smt2                                                                   |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-9.smt2                                                                   |   0.857s  |   0.857s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-1.smt2                                                                   |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-10.smt2                                                                  |   9.616s  |   9.616s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-11.smt2                                                                  |  11.086s  |  11.086s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-12.smt2                                                                  |  22.550s  |  22.550s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-13.smt2                                                                  |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-14.smt2                                                                  |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-15.smt2                                                                  |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-16.smt2                                                                  |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-17.smt2                                                                  |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-18.smt2                                                                  |  30.057s  |  30.057s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-19.smt2                                                                  |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-2.smt2                                                                   |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-20.smt2                                                                  |  30.062s  |  30.062s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-3.smt2                                                                   |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-4.smt2                                                                   |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-5.smt2                                                                   |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-6.smt2                                                                   |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-7.smt2                                                                   |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-8.smt2                                                                   |   0.606s  |   0.606s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-9.smt2                                                                   |   2.387s  |   2.387s  |   0.000s  | 0.0%|
|scheduling/abz5_1000.smt2                                                                   |   0.284s  |   0.284s  |   0.000s  | 0.0%|
|scheduling/abz5_1200.smt2                                                                   |   3.519s  |   3.519s  |   0.000s  | 0.0%|
|scheduling/abz5_1234.smt2                                                                   |   1.789s  |   1.789s  |   0.000s  | 0.0%|
|scheduling/abz5_1300.smt2                                                                   |   0.690s  |   0.690s  |   0.000s  | 0.0%|
|scheduling/abz5_1400.smt2                                                                   |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|scheduling/abz6_1000.smt2                                                                   |   0.411s  |   0.411s  |   0.000s  | 0.0%|
|scheduling/abz6_1100.smt2                                                                   |   0.314s  |   0.314s  |   0.000s  | 0.0%|
|scheduling/abz6_800.smt2                                                                    |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|scheduling/abz6_900.smt2                                                                    |   0.442s  |   0.442s  |   0.000s  | 0.0%|
|scheduling/abz6_943.smt2                                                                    |   0.877s  |   0.877s  |   0.000s  | 0.0%|
|scheduling/abz7_500.smt2                                                                    |   3.176s  |   3.176s  |   0.000s  | 0.0%|
|scheduling/abz7_600.smt2                                                                    |  30.073s  |  30.073s  |   0.000s  | 0.0%|
|scheduling/abz7_667.smt2                                                                    |  30.087s  |  30.087s  |   0.000s  | 0.0%|
|scheduling/abz7_670.smt2                                                                    |  30.089s  |  30.089s  |   0.000s  | 0.0%|
|scheduling/abz7_691.smt2                                                                    |  30.093s  |  30.093s  |   0.000s  | 0.0%|
|scheduling/abz7_700.smt2                                                                    |  30.098s  |  30.098s  |   0.000s  | 0.0%|
|scheduling/abz7_800.smt2                                                                    |  30.133s  |  30.133s  |   0.000s  | 0.0%|
|scheduling/orb01_1000.smt2                                                                  |  24.886s  |  24.886s  |   0.000s  | 0.0%|
|scheduling/orb01_1059.smt2                                                                  |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|scheduling/orb01_1100.smt2                                                                  |  23.036s  |  23.036s  |   0.000s  | 0.0%|
|scheduling/orb01_1200.smt2                                                                  |   0.972s  |   0.972s  |   0.000s  | 0.0%|
|scheduling/orb01_900.smt2                                                                   |   0.632s  |   0.632s  |   0.000s  | 0.0%|
|scheduling/orb02_1000.smt2                                                                  |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|scheduling/orb02_700.smt2                                                                   |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|scheduling/orb02_800.smt2                                                                   |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|scheduling/orb02_888.smt2                                                                   |   2.697s  |   2.697s  |   0.000s  | 0.0%|
|scheduling/orb02_900.smt2                                                                   |   0.819s  |   0.819s  |   0.000s  | 0.0%|
|scheduling/orb03_1005.smt2                                                                  |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|scheduling/orb03_1100.smt2                                                                  |   2.926s  |   2.926s  |   0.000s  | 0.0%|
|scheduling/orb03_1200.smt2                                                                  |   0.572s  |   0.572s  |   0.000s  | 0.0%|
|scheduling/orb03_850.smt2                                                                   |   0.467s  |   0.467s  |   0.000s  | 0.0%|
|scheduling/orb03_950.smt2                                                                   |   7.024s  |   7.024s  |   0.000s  | 0.0%|
|scheduling/orb04_1005.smt2                                                                  |   9.852s  |   9.852s  |   0.000s  | 0.0%|
|scheduling/orb04_1100.smt2                                                                  |   0.631s  |   0.631s  |   0.000s  | 0.0%|
|scheduling/orb04_1200.smt2                                                                  |   0.368s  |   0.368s  |   0.000s  | 0.0%|
|scheduling/orb04_850.smt2                                                                   |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|scheduling/orb04_950.smt2                                                                   |   0.636s  |   0.636s  |   0.000s  | 0.0%|
|scheduling/orb05_1000.smt2                                                                  |   0.551s  |   0.551s  |   0.000s  | 0.0%|
|scheduling/orb05_700.smt2                                                                   |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|scheduling/orb05_800.smt2                                                                   |   0.417s  |   0.417s  |   0.000s  | 0.0%|
|scheduling/orb05_887.smt2                                                                   |   9.226s  |   9.226s  |   0.000s  | 0.0%|
|scheduling/orb05_900.smt2                                                                   |   4.251s  |   4.251s  |   0.000s  | 0.0%|
|scheduling/orb06_1000.smt2                                                                  |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|scheduling/orb06_1010.smt2                                                                  |  30.061s  |  30.061s  |   0.000s  | 0.0%|
|scheduling/orb06_1100.smt2                                                                  |   1.245s  |   1.245s  |   0.000s  | 0.0%|
|scheduling/orb06_1200.smt2                                                                  |   0.426s  |   0.426s  |   0.000s  | 0.0%|
|scheduling/orb06_900.smt2                                                                   |   0.539s  |   0.539s  |   0.000s  | 0.0%|
|scheduling/orb07_250.smt2                                                                   |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|scheduling/orb07_330.smt2                                                                   |   0.322s  |   0.322s  |   0.000s  | 0.0%|
|scheduling/orb07_397.smt2                                                                   |   6.127s  |   6.127s  |   0.000s  | 0.0%|
|scheduling/orb07_430.smt2                                                                   |   0.924s  |   0.924s  |   0.000s  | 0.0%|
|scheduling/orb07_550.smt2                                                                   |   0.257s  |   0.257s  |   0.000s  | 0.0%|
|scheduling/orb08_1000.smt2                                                                  |   0.624s  |   0.624s  |   0.000s  | 0.0%|
|scheduling/orb08_700.smt2                                                                   |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|scheduling/orb08_830.smt2                                                                   |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|scheduling/orb08_888.smt2                                                                   |  12.479s  |  12.479s  |   0.000s  | 0.0%|
|scheduling/orb08_930.smt2                                                                   |   5.491s  |   5.491s  |   0.000s  | 0.0%|
|scheduling/orb09_1000.smt2                                                                  |   0.471s  |   0.471s  |   0.000s  | 0.0%|
|scheduling/orb09_1100.smt2                                                                  |   0.279s  |   0.279s  |   0.000s  | 0.0%|
|scheduling/orb09_800.smt2                                                                   |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|scheduling/orb09_900.smt2                                                                   |   4.108s  |   4.108s  |   0.000s  | 0.0%|
|scheduling/orb09_934.smt2                                                                   |   8.407s  |   8.407s  |   0.000s  | 0.0%|
|scheduling/orb10_1000.smt2                                                                  |   3.480s  |   3.480s  |   0.000s  | 0.0%|
|scheduling/orb10_1100.smt2                                                                  |   0.423s  |   0.423s  |   0.000s  | 0.0%|
|scheduling/orb10_800.smt2                                                                   |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|scheduling/orb10_900.smt2                                                                   |   0.905s  |   0.905s  |   0.000s  | 0.0%|
|scheduling/orb10_944.smt2                                                                   |   6.026s  |   6.026s  |   0.000s  | 0.0%|
|scheduling/swv11_2900.smt2                                                                  |  30.154s  |  30.154s  |   0.000s  | 0.0%|
|scheduling/swv11_2983.smt2                                                                  |  30.141s  |  30.141s  |   0.000s  | 0.0%|
|scheduling/swv11_2988.smt2                                                                  |  30.146s  |  30.146s  |   0.000s  | 0.0%|
|scheduling/swv11_2992.smt2                                                                  |  30.131s  |  30.131s  |   0.000s  | 0.0%|
|scheduling/swv11_3050.smt2                                                                  |  30.143s  |  30.143s  |   0.000s  | 0.0%|
|scheduling/swv12_2900.smt2                                                                  |  30.098s  |  30.098s  |   0.000s  | 0.0%|
|scheduling/swv12_2972.smt2                                                                  |  30.136s  |  30.136s  |   0.000s  | 0.0%|
|scheduling/swv12_2990.smt2                                                                  |  30.140s  |  30.140s  |   0.000s  | 0.0%|
|scheduling/swv12_3004.smt2                                                                  |  30.133s  |  30.133s  |   0.000s  | 0.0%|
|scheduling/swv12_3050.smt2                                                                  |  30.129s  |  30.129s  |   0.000s  | 0.0%|
|scheduling/swv13_3000.smt2                                                                  |  30.126s  |  30.126s  |   0.000s  | 0.0%|
|scheduling/swv13_3104.smt2                                                                  |  30.177s  |  30.177s  |   0.000s  | 0.0%|
|scheduling/swv13_3150.smt2                                                                  |  30.132s  |  30.132s  |   0.000s  | 0.0%|
|scheduling/swv13_3200.smt2                                                                  |  30.193s  |  30.193s  |   0.000s  | 0.0%|
|scheduling/swv14_2800.smt2                                                                  |  30.142s  |  30.142s  |   0.000s  | 0.0%|
|scheduling/swv14_2885.smt2                                                                  |  30.137s  |  30.137s  |   0.000s  | 0.0%|
|scheduling/swv14_2895.smt2                                                                  |  30.126s  |  30.126s  |   0.000s  | 0.0%|
|scheduling/swv14_2905.smt2                                                                  |  30.141s  |  30.141s  |   0.000s  | 0.0%|
|scheduling/swv14_3000.smt2                                                                  |  30.147s  |  30.147s  |   0.000s  | 0.0%|
|scheduling/yn1_750.smt2                                                                     |   2.044s  |   2.044s  |   0.000s  | 0.0%|
|scheduling/yn1_827.smt2                                                                     |  30.101s  |  30.101s  |   0.000s  | 0.0%|
|scheduling/yn1_850.smt2                                                                     |  30.104s  |  30.104s  |   0.000s  | 0.0%|
|scheduling/yn1_887.smt2                                                                     |  30.092s  |  30.092s  |   0.000s  | 0.0%|
|scheduling/yn1_950.smt2                                                                     |  30.089s  |  30.089s  |   0.000s  | 0.0%|
|scheduling/yn2_750.smt2                                                                     |   3.908s  |   3.908s  |   0.000s  | 0.0%|
|scheduling/yn2_862.smt2                                                                     |  30.091s  |  30.091s  |   0.000s  | 0.0%|
|scheduling/yn2_890.smt2                                                                     |  30.090s  |  30.090s  |   0.000s  | 0.0%|
|scheduling/yn2_910.smt2                                                                     |  30.099s  |  30.099s  |   0.000s  | 0.0%|
|scheduling/yn2_950.smt2                                                                     |  30.086s  |  30.086s  |   0.000s  | 0.0%|
|scheduling/yn3_750.smt2                                                                     |   3.956s  |   3.956s  |   0.000s  | 0.0%|
|scheduling/yn3_828.smt2                                                                     |  30.082s  |  30.082s  |   0.000s  | 0.0%|
|scheduling/yn3_860.smt2                                                                     |  30.099s  |  30.099s  |   0.000s  | 0.0%|
|scheduling/yn3_894.smt2                                                                     |  30.103s  |  30.103s  |   0.000s  | 0.0%|
|scheduling/yn3_950.smt2                                                                     |  30.086s  |  30.086s  |   0.000s  | 0.0%|
|scheduling/yn4_1000.smt2                                                                    |  30.087s  |  30.087s  |   0.000s  | 0.0%|
|scheduling/yn4_850.smt2                                                                     |  30.078s  |  30.078s  |   0.000s  | 0.0%|
|scheduling/yn4_919.smt2                                                                     |  30.090s  |  30.090s  |   0.000s  | 0.0%|
|scheduling/yn4_950.smt2                                                                     |  30.091s  |  30.091s  |   0.000s  | 0.0%|
|scheduling/yn4_969.smt2                                                                     |  30.085s  |  30.085s  |   0.000s  | 0.0%|
|skdmxa/skdmxa-3x3-10.smt2                                                                   |   2.244s  |   2.244s  |   0.000s  | 0.0%|
|skdmxa/skdmxa-3x3-15.smt2                                                                   |  30.127s  |  30.127s  |   0.000s  | 0.0%|
|skdmxa/skdmxa-3x3-20.smt2                                                                   |  30.132s  |  30.132s  |   0.000s  | 0.0%|
|skdmxa/skdmxa-3x3-5.smt2                                                                    |   0.853s  |   0.853s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-10.base.cvc.smt2                                                         |   2.410s  |   2.410s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-10.induction.cvc.smt2                                                    |   3.027s  |   3.027s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-11.base.cvc.smt2                                                         |   9.118s  |   9.118s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-11.induction.cvc.smt2                                                    |   3.693s  |   3.693s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-12.base.cvc.smt2                                                         |  30.169s  |  30.169s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-12.induction.cvc.smt2                                                    |   3.812s  |   3.812s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-13.base.cvc.smt2                                                         |  30.161s  |  30.161s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-13.induction.cvc.smt2                                                    |   7.737s  |   7.737s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-14.base.cvc.smt2                                                         |  30.185s  |  30.185s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-14.induction.cvc.smt2                                                    |   6.572s  |   6.572s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-15.base.cvc.smt2                                                         |  30.272s  |  30.272s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-15.induction.cvc.smt2                                                    |  12.522s  |  12.522s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-16.base.cvc.smt2                                                         |  30.253s  |  30.253s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-16.induction.cvc.smt2                                                    |   8.527s  |   8.527s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-17.base.cvc.smt2                                                         |  30.180s  |  30.180s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-17.induction.cvc.smt2                                                    |  12.496s  |  12.496s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-18.base.cvc.smt2                                                         |  30.204s  |  30.204s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-18.induction.cvc.smt2                                                    |  13.920s  |  13.920s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-19.base.cvc.smt2                                                         |  30.177s  |  30.177s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-19.induction.cvc.smt2                                                    |  12.639s  |  12.639s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                         |  30.198s  |  30.198s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-20.induction.cvc.smt2                                                    |  30.166s  |  30.166s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-5.base.cvc.smt2                                                          |   1.161s  |   1.161s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-5.induction.cvc.smt2                                                     |   0.968s  |   0.968s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-6.base.cvc.smt2                                                          |   0.832s  |   0.832s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-6.induction.cvc.smt2                                                     |   1.147s  |   1.147s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-7.base.cvc.smt2                                                          |   1.147s  |   1.147s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-7.induction.cvc.smt2                                                     |   1.659s  |   1.659s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-8.base.cvc.smt2                                                          |   1.348s  |   1.348s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-8.induction.cvc.smt2                                                     |   1.922s  |   1.922s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-9.base.cvc.smt2                                                          |   1.599s  |   1.599s  |   0.000s  | 0.0%|
</details>
