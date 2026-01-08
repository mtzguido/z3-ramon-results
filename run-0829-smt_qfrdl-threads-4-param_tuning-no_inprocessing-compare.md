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
Job tag: smt_qfrdl-threads-4-param_tuning-no_inprocessing
Runner: lev-ripper
Z3 repo: ilanashapiro/z3
Z3 commit: e742d8ba0b05eaff1ccca5ff1116975780d26bb0
Z3 branch: param-tuning
Z3 options: "-T:30 smt.threads=4 tactic.default_tactic=smt smt.auto_config.false smt_parallel.inprocessing=false"
Z3 inputs: inputs/QF_RDL
Z3 commit message: change some scoring strategies, add LIA and NIA param tuning

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt_qfrdl-threads-4-param_tuning-no_inprocessing
Runner: lev-ripper
Z3 repo: ilanashapiro/z3
Z3 commit: e742d8ba0b05eaff1ccca5ff1116975780d26bb0
Z3 branch: param-tuning
Z3 options: "-T:30 smt.threads=4 tactic.default_tactic=smt smt.auto_config.false smt_parallel.inprocessing=false"
Z3 inputs: inputs/QF_RDL
Z3 commit message: change some scoring strategies, add LIA and NIA param tuning

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.227s  |   0.227s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.227s  |   0.227s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.227s  |   0.227s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.227s  |   0.227s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scheduling/swv14_2885.smt2                                                                 |  30.178s |644.0MiB|
|scheduling/swv13_3200.smt2                                                                 |  30.157s |714.0MiB|
|scheduling/yn1_950.smt2                                                                    |  30.151s |317.0MiB|
|scheduling/swv11_2988.smt2                                                                 |  30.150s |629.0MiB|
|scheduling/swv11_2900.smt2                                                                 |  30.148s |613.0MiB|
|scheduling/swv11_3050.smt2                                                                 |  30.147s |613.0MiB|
|scheduling/swv14_2800.smt2                                                                 |  30.141s |634.0MiB|
|skdmxa2/skdmxa-3x3-18.base.cvc.smt2                                                        |  30.141s |642.0MiB|
|scheduling/swv12_2972.smt2                                                                 |  30.139s |700.0MiB|
|scheduling/swv14_3000.smt2                                                                 |  30.132s |666.0MiB|
|scheduling/swv13_3000.smt2                                                                 |  30.132s |700.0MiB|
|scheduling/swv13_3104.smt2                                                                 |  30.131s |705.0MiB|
|scheduling/swv11_2983.smt2                                                                 |  30.130s |657.0MiB|
|scheduling/swv14_2895.smt2                                                                 |  30.130s |663.0MiB|
|scheduling/swv12_3004.smt2                                                                 |  30.127s |685.0MiB|
|scheduling/swv14_2905.smt2                                                                 |  30.127s |633.0MiB|
|scheduling/swv12_3050.smt2                                                                 |  30.126s |734.0MiB|
|skdmxa2/skdmxa-3x3-15.base.cvc.smt2                                                        |  30.126s |511.0MiB|
|scheduling/swv12_2990.smt2                                                                 |  30.124s |668.0MiB|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                        |  30.124s |735.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scheduling/swv14_2885.smt2                                                                 |  30.178s |644.0MiB|
|scheduling/swv13_3200.smt2                                                                 |  30.157s |714.0MiB|
|scheduling/yn1_950.smt2                                                                    |  30.151s |317.0MiB|
|scheduling/swv11_2988.smt2                                                                 |  30.150s |629.0MiB|
|scheduling/swv11_2900.smt2                                                                 |  30.148s |613.0MiB|
|scheduling/swv11_3050.smt2                                                                 |  30.147s |613.0MiB|
|scheduling/swv14_2800.smt2                                                                 |  30.141s |634.0MiB|
|skdmxa2/skdmxa-3x3-18.base.cvc.smt2                                                        |  30.141s |642.0MiB|
|scheduling/swv12_2972.smt2                                                                 |  30.139s |700.0MiB|
|scheduling/swv14_3000.smt2                                                                 |  30.132s |666.0MiB|
|scheduling/swv13_3000.smt2                                                                 |  30.132s |700.0MiB|
|scheduling/swv13_3104.smt2                                                                 |  30.131s |705.0MiB|
|scheduling/swv11_2983.smt2                                                                 |  30.130s |657.0MiB|
|scheduling/swv14_2895.smt2                                                                 |  30.130s |663.0MiB|
|scheduling/swv12_3004.smt2                                                                 |  30.127s |685.0MiB|
|scheduling/swv14_2905.smt2                                                                 |  30.127s |633.0MiB|
|scheduling/swv12_3050.smt2                                                                 |  30.126s |734.0MiB|
|skdmxa2/skdmxa-3x3-15.base.cvc.smt2                                                        |  30.126s |511.0MiB|
|scheduling/swv12_2990.smt2                                                                 |  30.124s |668.0MiB|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                        |  30.124s |735.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |90.648MiB|90.648MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |90.796MiB|90.796MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |91.16MiB|91.16MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |91.856MiB|91.856MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |92.44MiB|92.44MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |92.844MiB|92.844MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |93.408MiB|93.408MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |94.072MiB|94.072MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |95.008MiB|95.008MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |95.636MiB|95.636MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |95.864MiB|95.864MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |96.264MiB|96.264MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |96.664MiB|96.664MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |97.184MiB|97.184MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |97.704MiB|97.704MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |98.74MiB|98.74MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |99.392MiB|99.392MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |99.288MiB|99.288MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |99.912MiB|99.912MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |98.0MiB|98.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |90.648MiB|90.648MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |90.796MiB|90.796MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |91.16MiB|91.16MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |91.856MiB|91.856MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |92.44MiB|92.44MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |92.844MiB|92.844MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |93.408MiB|93.408MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |94.072MiB|94.072MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |95.008MiB|95.008MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |95.636MiB|95.636MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |95.864MiB|95.864MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |96.264MiB|96.264MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |96.664MiB|96.664MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |97.184MiB|97.184MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |97.704MiB|97.704MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |98.74MiB|98.74MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |99.392MiB|99.392MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |99.288MiB|99.288MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |99.912MiB|99.912MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |98.0MiB|98.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |90.648MiB|90.648MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |90.796MiB|90.796MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |91.16MiB|91.16MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |91.856MiB|91.856MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |92.44MiB|92.44MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |92.844MiB|92.844MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |93.408MiB|93.408MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |94.072MiB|94.072MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |95.008MiB|95.008MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |95.636MiB|95.636MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |95.864MiB|95.864MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |96.264MiB|96.264MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |96.664MiB|96.664MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |97.184MiB|97.184MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |97.704MiB|97.704MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |98.74MiB|98.74MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |99.392MiB|99.392MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |99.288MiB|99.288MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |99.912MiB|99.912MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |98.0MiB|98.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |90.648MiB|90.648MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |90.796MiB|90.796MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |91.16MiB|91.16MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |91.856MiB|91.856MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |92.44MiB|92.44MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |92.844MiB|92.844MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |93.408MiB|93.408MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |94.072MiB|94.072MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |95.008MiB|95.008MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |95.636MiB|95.636MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |95.864MiB|95.864MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |96.264MiB|96.264MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |96.664MiB|96.664MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |97.184MiB|97.184MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |97.704MiB|97.704MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |98.74MiB|98.74MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |99.392MiB|99.392MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |99.288MiB|99.288MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |99.912MiB|99.912MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |98.0MiB|98.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|skdmxa2/skdmxa-3x3-20.induction.cvc.smt2                                                   |  23.345s |926.0MiB|
|skdmxa2/skdmxa-3x3-17.induction.cvc.smt2                                                   |  12.511s |861.0MiB|
|skdmxa2/skdmxa-3x3-18.induction.cvc.smt2                                                   |  12.215s |808.0MiB|
|skdmxa2/skdmxa-3x3-19.induction.cvc.smt2                                                   |  11.120s |796.0MiB|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                        |  30.124s |735.0MiB|
|scheduling/swv12_3050.smt2                                                                 |  30.126s |734.0MiB|
|skdmxa2/skdmxa-3x3-15.induction.cvc.smt2                                                   |  12.946s |732.0MiB|
|skdmxa2/skdmxa-3x3-16.induction.cvc.smt2                                                   |   8.205s |720.0MiB|
|scheduling/swv13_3150.smt2                                                                 |  30.113s |719.0MiB|
|scheduling/swv13_3200.smt2                                                                 |  30.157s |714.0MiB|
|scheduling/swv13_3104.smt2                                                                 |  30.131s |705.0MiB|
|scheduling/swv12_2972.smt2                                                                 |  30.139s |700.0MiB|
|scheduling/swv13_3000.smt2                                                                 |  30.132s |700.0MiB|
|skdmxa2/skdmxa-3x3-14.induction.cvc.smt2                                                   |   6.326s |691.0MiB|
|scheduling/swv12_3004.smt2                                                                 |  30.127s |685.0MiB|
|skdmxa2/skdmxa-3x3-19.base.cvc.smt2                                                        |  30.109s |675.0MiB|
|scheduling/swv12_2990.smt2                                                                 |  30.124s |668.0MiB|
|scheduling/swv14_3000.smt2                                                                 |  30.132s |666.0MiB|
|scheduling/swv12_2900.smt2                                                                 |  30.118s |665.0MiB|
|scheduling/swv14_2895.smt2                                                                 |  30.130s |663.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|skdmxa2/skdmxa-3x3-20.induction.cvc.smt2                                                   |  23.345s |926.0MiB|
|skdmxa2/skdmxa-3x3-17.induction.cvc.smt2                                                   |  12.511s |861.0MiB|
|skdmxa2/skdmxa-3x3-18.induction.cvc.smt2                                                   |  12.215s |808.0MiB|
|skdmxa2/skdmxa-3x3-19.induction.cvc.smt2                                                   |  11.120s |796.0MiB|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                        |  30.124s |735.0MiB|
|scheduling/swv12_3050.smt2                                                                 |  30.126s |734.0MiB|
|skdmxa2/skdmxa-3x3-15.induction.cvc.smt2                                                   |  12.946s |732.0MiB|
|skdmxa2/skdmxa-3x3-16.induction.cvc.smt2                                                   |   8.205s |720.0MiB|
|scheduling/swv13_3150.smt2                                                                 |  30.113s |719.0MiB|
|scheduling/swv13_3200.smt2                                                                 |  30.157s |714.0MiB|
|scheduling/swv13_3104.smt2                                                                 |  30.131s |705.0MiB|
|scheduling/swv12_2972.smt2                                                                 |  30.139s |700.0MiB|
|scheduling/swv13_3000.smt2                                                                 |  30.132s |700.0MiB|
|skdmxa2/skdmxa-3x3-14.induction.cvc.smt2                                                   |   6.326s |691.0MiB|
|scheduling/swv12_3004.smt2                                                                 |  30.127s |685.0MiB|
|skdmxa2/skdmxa-3x3-19.base.cvc.smt2                                                        |  30.109s |675.0MiB|
|scheduling/swv12_2990.smt2                                                                 |  30.124s |668.0MiB|
|scheduling/swv14_3000.smt2                                                                 |  30.132s |666.0MiB|
|scheduling/swv12_2900.smt2                                                                 |  30.118s |665.0MiB|
|scheduling/swv14_2895.smt2                                                                 |  30.130s |663.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking21.smt2                                             |   0.241s  |   0.241s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking22.smt2                                             |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-2.smt2                                         |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-3.smt2                                         |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-4.smt2                                         |   1.348s  |   1.348s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-5.smt2                                         |  13.411s  |  13.411s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-6.smt2                                         |  30.026s  |  30.026s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-7.smt2                                         |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-matrix1x1.pddl.smt2                                  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-matrix2x2.pddl.smt2                                  |  30.072s  |  30.072s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-1.smt2                                         |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-2.smt2                                         |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-3.smt2                                         |   0.551s  |   0.551s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-4.smt2                                         |  22.070s  |  22.070s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-5.smt2                                         |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-6.smt2                                         |  30.077s  |  30.077s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-03.smt2                                      |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-04.smt2                                      |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-05.smt2                                      |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-06.smt2                                      |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-07.smt2                                      |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-08.smt2                                      |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-09.smt2                                      |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-10.smt2                                      |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-20.smt2                                      |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-30.smt2                                      |   0.456s  |   0.456s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-40.smt2                                      |   0.717s  |   0.717s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-60.smt2                                      |   1.909s  |   1.909s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-70.smt2                                      |   3.613s  |   3.613s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-80.smt2                                      |   3.280s  |   3.280s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-90.smt2                                      |   5.456s  |   5.456s  |   0.000s  | 0.0%|
|check/bignum_rdl1.smt2                                                                      |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|check/bignum_rdl2.smt2                                                                      |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-1.smt2                                                                   |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-10.smt2                                                                  |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-11.smt2                                                                  |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-12.smt2                                                                  |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-13.smt2                                                                  |   0.296s  |   0.296s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-14.smt2                                                                  |   0.376s  |   0.376s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-15.smt2                                                                  |   0.438s  |   0.438s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-16.smt2                                                                  |   0.396s  |   0.396s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-17.smt2                                                                  |   0.552s  |   0.552s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-18.smt2                                                                  |   1.148s  |   1.148s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-19.smt2                                                                  |   1.008s  |   1.008s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-2.smt2                                                                   |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-20.smt2                                                                  |   1.318s  |   1.318s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-3.smt2                                                                   |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-4.smt2                                                                   |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-5.smt2                                                                   |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-6.smt2                                                                   |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-7.smt2                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-8.smt2                                                                   |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-9.smt2                                                                   |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-1.smt2                                                                   |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-10.smt2                                                                  |   0.785s  |   0.785s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-11.smt2                                                                  |   1.452s  |   1.452s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-12.smt2                                                                  |   1.712s  |   1.712s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-13.smt2                                                                  |   2.792s  |   2.792s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-14.smt2                                                                  |   3.239s  |   3.239s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-15.smt2                                                                  |   5.020s  |   5.020s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-16.smt2                                                                  |   7.301s  |   7.301s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-17.smt2                                                                  |  10.252s  |  10.252s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-18.smt2                                                                  |  17.161s  |  17.161s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-19.smt2                                                                  |  23.891s  |  23.891s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-2.smt2                                                                   |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-20.smt2                                                                  |  27.151s  |  27.151s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-3.smt2                                                                   |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-4.smt2                                                                   |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-5.smt2                                                                   |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-6.smt2                                                                   |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-7.smt2                                                                   |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-8.smt2                                                                   |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-9.smt2                                                                   |   0.349s  |   0.349s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-1.smt2                                                                   |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-10.smt2                                                                  |   1.809s  |   1.809s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-11.smt2                                                                  |   3.541s  |   3.541s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-12.smt2                                                                  |   8.141s  |   8.141s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-13.smt2                                                                  |  10.241s  |  10.241s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-14.smt2                                                                  |  22.488s  |  22.488s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-15.smt2                                                                  |  27.054s  |  27.054s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-16.smt2                                                                  |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-17.smt2                                                                  |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-18.smt2                                                                  |  30.025s  |  30.025s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-19.smt2                                                                  |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-2.smt2                                                                   |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-20.smt2                                                                  |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-3.smt2                                                                   |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-4.smt2                                                                   |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-5.smt2                                                                   |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-6.smt2                                                                   |   0.325s  |   0.325s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-7.smt2                                                                   |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-8.smt2                                                                   |   0.374s  |   0.374s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-9.smt2                                                                   |   1.168s  |   1.168s  |   0.000s  | 0.0%|
|scheduling/abz5_1000.smt2                                                                   |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|scheduling/abz5_1200.smt2                                                                   |   3.484s  |   3.484s  |   0.000s  | 0.0%|
|scheduling/abz5_1234.smt2                                                                   |   3.407s  |   3.407s  |   0.000s  | 0.0%|
|scheduling/abz5_1300.smt2                                                                   |   0.689s  |   0.689s  |   0.000s  | 0.0%|
|scheduling/abz5_1400.smt2                                                                   |   0.370s  |   0.370s  |   0.000s  | 0.0%|
|scheduling/abz6_1000.smt2                                                                   |   0.414s  |   0.414s  |   0.000s  | 0.0%|
|scheduling/abz6_1100.smt2                                                                   |   0.314s  |   0.314s  |   0.000s  | 0.0%|
|scheduling/abz6_800.smt2                                                                    |   0.316s  |   0.316s  |   0.000s  | 0.0%|
|scheduling/abz6_900.smt2                                                                    |   0.537s  |   0.537s  |   0.000s  | 0.0%|
|scheduling/abz6_943.smt2                                                                    |   0.883s  |   0.883s  |   0.000s  | 0.0%|
|scheduling/abz7_500.smt2                                                                    |   2.252s  |   2.252s  |   0.000s  | 0.0%|
|scheduling/abz7_600.smt2                                                                    |  30.057s  |  30.057s  |   0.000s  | 0.0%|
|scheduling/abz7_667.smt2                                                                    |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|scheduling/abz7_670.smt2                                                                    |  30.067s  |  30.067s  |   0.000s  | 0.0%|
|scheduling/abz7_691.smt2                                                                    |  30.075s  |  30.075s  |   0.000s  | 0.0%|
|scheduling/abz7_700.smt2                                                                    |  30.070s  |  30.070s  |   0.000s  | 0.0%|
|scheduling/abz7_800.smt2                                                                    |  30.075s  |  30.075s  |   0.000s  | 0.0%|
|scheduling/orb01_1000.smt2                                                                  |  30.040s  |  30.040s  |   0.000s  | 0.0%|
|scheduling/orb01_1059.smt2                                                                  |  30.078s  |  30.078s  |   0.000s  | 0.0%|
|scheduling/orb01_1100.smt2                                                                  |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|scheduling/orb01_1200.smt2                                                                  |   1.986s  |   1.986s  |   0.000s  | 0.0%|
|scheduling/orb01_900.smt2                                                                   |   0.728s  |   0.728s  |   0.000s  | 0.0%|
|scheduling/orb02_1000.smt2                                                                  |   0.384s  |   0.384s  |   0.000s  | 0.0%|
|scheduling/orb02_700.smt2                                                                   |   0.323s  |   0.323s  |   0.000s  | 0.0%|
|scheduling/orb02_800.smt2                                                                   |   0.351s  |   0.351s  |   0.000s  | 0.0%|
|scheduling/orb02_888.smt2                                                                   |   2.692s  |   2.692s  |   0.000s  | 0.0%|
|scheduling/orb02_900.smt2                                                                   |   1.278s  |   1.278s  |   0.000s  | 0.0%|
|scheduling/orb03_1005.smt2                                                                  |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|scheduling/orb03_1100.smt2                                                                  |   0.829s  |   0.829s  |   0.000s  | 0.0%|
|scheduling/orb03_1200.smt2                                                                  |   0.601s  |   0.601s  |   0.000s  | 0.0%|
|scheduling/orb03_850.smt2                                                                   |   0.413s  |   0.413s  |   0.000s  | 0.0%|
|scheduling/orb03_950.smt2                                                                   |  21.376s  |  21.376s  |   0.000s  | 0.0%|
|scheduling/orb04_1005.smt2                                                                  |  10.224s  |  10.224s  |   0.000s  | 0.0%|
|scheduling/orb04_1100.smt2                                                                  |   0.741s  |   0.741s  |   0.000s  | 0.0%|
|scheduling/orb04_1200.smt2                                                                  |   0.390s  |   0.390s  |   0.000s  | 0.0%|
|scheduling/orb04_850.smt2                                                                   |   0.350s  |   0.350s  |   0.000s  | 0.0%|
|scheduling/orb04_950.smt2                                                                   |   0.633s  |   0.633s  |   0.000s  | 0.0%|
|scheduling/orb05_1000.smt2                                                                  |   0.631s  |   0.631s  |   0.000s  | 0.0%|
|scheduling/orb05_700.smt2                                                                   |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|scheduling/orb05_800.smt2                                                                   |   0.508s  |   0.508s  |   0.000s  | 0.0%|
|scheduling/orb05_887.smt2                                                                   |   8.685s  |   8.685s  |   0.000s  | 0.0%|
|scheduling/orb05_900.smt2                                                                   |   2.044s  |   2.044s  |   0.000s  | 0.0%|
|scheduling/orb06_1000.smt2                                                                  |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|scheduling/orb06_1010.smt2                                                                  |  30.063s  |  30.063s  |   0.000s  | 0.0%|
|scheduling/orb06_1100.smt2                                                                  |   2.348s  |   2.348s  |   0.000s  | 0.0%|
|scheduling/orb06_1200.smt2                                                                  |   0.362s  |   0.362s  |   0.000s  | 0.0%|
|scheduling/orb06_900.smt2                                                                   |   0.597s  |   0.597s  |   0.000s  | 0.0%|
|scheduling/orb07_250.smt2                                                                   |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|scheduling/orb07_330.smt2                                                                   |   0.336s  |   0.336s  |   0.000s  | 0.0%|
|scheduling/orb07_397.smt2                                                                   |   4.555s  |   4.555s  |   0.000s  | 0.0%|
|scheduling/orb07_430.smt2                                                                   |   0.842s  |   0.842s  |   0.000s  | 0.0%|
|scheduling/orb07_550.smt2                                                                   |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|scheduling/orb08_1000.smt2                                                                  |   0.639s  |   0.639s  |   0.000s  | 0.0%|
|scheduling/orb08_700.smt2                                                                   |   0.302s  |   0.302s  |   0.000s  | 0.0%|
|scheduling/orb08_830.smt2                                                                   |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|scheduling/orb08_888.smt2                                                                   |  14.024s  |  14.024s  |   0.000s  | 0.0%|
|scheduling/orb08_930.smt2                                                                   |   9.643s  |   9.643s  |   0.000s  | 0.0%|
|scheduling/orb09_1000.smt2                                                                  |   0.481s  |   0.481s  |   0.000s  | 0.0%|
|scheduling/orb09_1100.smt2                                                                  |   0.271s  |   0.271s  |   0.000s  | 0.0%|
|scheduling/orb09_800.smt2                                                                   |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|scheduling/orb09_900.smt2                                                                   |   2.309s  |   2.309s  |   0.000s  | 0.0%|
|scheduling/orb09_934.smt2                                                                   |   9.880s  |   9.880s  |   0.000s  | 0.0%|
|scheduling/orb10_1000.smt2                                                                  |   4.319s  |   4.319s  |   0.000s  | 0.0%|
|scheduling/orb10_1100.smt2                                                                  |   0.468s  |   0.468s  |   0.000s  | 0.0%|
|scheduling/orb10_800.smt2                                                                   |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|scheduling/orb10_900.smt2                                                                   |   1.090s  |   1.090s  |   0.000s  | 0.0%|
|scheduling/orb10_944.smt2                                                                   |   4.528s  |   4.528s  |   0.000s  | 0.0%|
|scheduling/swv11_2900.smt2                                                                  |  30.148s  |  30.148s  |   0.000s  | 0.0%|
|scheduling/swv11_2983.smt2                                                                  |  30.130s  |  30.130s  |   0.000s  | 0.0%|
|scheduling/swv11_2988.smt2                                                                  |  30.150s  |  30.150s  |   0.000s  | 0.0%|
|scheduling/swv11_2992.smt2                                                                  |  30.122s  |  30.122s  |   0.000s  | 0.0%|
|scheduling/swv11_3050.smt2                                                                  |  30.147s  |  30.147s  |   0.000s  | 0.0%|
|scheduling/swv12_2900.smt2                                                                  |  30.118s  |  30.118s  |   0.000s  | 0.0%|
|scheduling/swv12_2972.smt2                                                                  |  30.139s  |  30.139s  |   0.000s  | 0.0%|
|scheduling/swv12_2990.smt2                                                                  |  30.124s  |  30.124s  |   0.000s  | 0.0%|
|scheduling/swv12_3004.smt2                                                                  |  30.127s  |  30.127s  |   0.000s  | 0.0%|
|scheduling/swv12_3050.smt2                                                                  |  30.126s  |  30.126s  |   0.000s  | 0.0%|
|scheduling/swv13_3000.smt2                                                                  |  30.132s  |  30.132s  |   0.000s  | 0.0%|
|scheduling/swv13_3104.smt2                                                                  |  30.131s  |  30.131s  |   0.000s  | 0.0%|
|scheduling/swv13_3150.smt2                                                                  |  30.113s  |  30.113s  |   0.000s  | 0.0%|
|scheduling/swv13_3200.smt2                                                                  |  30.157s  |  30.157s  |   0.000s  | 0.0%|
|scheduling/swv14_2800.smt2                                                                  |  30.141s  |  30.141s  |   0.000s  | 0.0%|
|scheduling/swv14_2885.smt2                                                                  |  30.178s  |  30.178s  |   0.000s  | 0.0%|
|scheduling/swv14_2895.smt2                                                                  |  30.130s  |  30.130s  |   0.000s  | 0.0%|
|scheduling/swv14_2905.smt2                                                                  |  30.127s  |  30.127s  |   0.000s  | 0.0%|
|scheduling/swv14_3000.smt2                                                                  |  30.132s  |  30.132s  |   0.000s  | 0.0%|
|scheduling/yn1_750.smt2                                                                     |   1.824s  |   1.824s  |   0.000s  | 0.0%|
|scheduling/yn1_827.smt2                                                                     |  30.087s  |  30.087s  |   0.000s  | 0.0%|
|scheduling/yn1_850.smt2                                                                     |  30.096s  |  30.096s  |   0.000s  | 0.0%|
|scheduling/yn1_887.smt2                                                                     |  30.101s  |  30.101s  |   0.000s  | 0.0%|
|scheduling/yn1_950.smt2                                                                     |  30.151s  |  30.151s  |   0.000s  | 0.0%|
|scheduling/yn2_750.smt2                                                                     |   5.727s  |   5.727s  |   0.000s  | 0.0%|
|scheduling/yn2_862.smt2                                                                     |  30.085s  |  30.085s  |   0.000s  | 0.0%|
|scheduling/yn2_890.smt2                                                                     |  30.102s  |  30.102s  |   0.000s  | 0.0%|
|scheduling/yn2_910.smt2                                                                     |  30.106s  |  30.106s  |   0.000s  | 0.0%|
|scheduling/yn2_950.smt2                                                                     |  30.075s  |  30.075s  |   0.000s  | 0.0%|
|scheduling/yn3_750.smt2                                                                     |   5.611s  |   5.611s  |   0.000s  | 0.0%|
|scheduling/yn3_828.smt2                                                                     |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|scheduling/yn3_860.smt2                                                                     |  30.098s  |  30.098s  |   0.000s  | 0.0%|
|scheduling/yn3_894.smt2                                                                     |  30.104s  |  30.104s  |   0.000s  | 0.0%|
|scheduling/yn3_950.smt2                                                                     |  30.070s  |  30.070s  |   0.000s  | 0.0%|
|scheduling/yn4_1000.smt2                                                                    |  30.076s  |  30.076s  |   0.000s  | 0.0%|
|scheduling/yn4_850.smt2                                                                     |  30.083s  |  30.083s  |   0.000s  | 0.0%|
|scheduling/yn4_919.smt2                                                                     |  30.095s  |  30.095s  |   0.000s  | 0.0%|
|scheduling/yn4_950.smt2                                                                     |  30.094s  |  30.094s  |   0.000s  | 0.0%|
|scheduling/yn4_969.smt2                                                                     |  30.080s  |  30.080s  |   0.000s  | 0.0%|
|skdmxa/skdmxa-3x3-10.smt2                                                                   |   2.812s  |   2.812s  |   0.000s  | 0.0%|
|skdmxa/skdmxa-3x3-15.smt2                                                                   |  28.471s  |  28.471s  |   0.000s  | 0.0%|
|skdmxa/skdmxa-3x3-20.smt2                                                                   |  30.094s  |  30.094s  |   0.000s  | 0.0%|
|skdmxa/skdmxa-3x3-5.smt2                                                                    |   0.811s  |   0.811s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-10.base.cvc.smt2                                                         |   2.402s  |   2.402s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-10.induction.cvc.smt2                                                    |   3.030s  |   3.030s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-11.base.cvc.smt2                                                         |   6.212s  |   6.212s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-11.induction.cvc.smt2                                                    |   3.919s  |   3.919s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-12.base.cvc.smt2                                                         |  20.697s  |  20.697s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-12.induction.cvc.smt2                                                    |   3.785s  |   3.785s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-13.base.cvc.smt2                                                         |  30.113s  |  30.113s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-13.induction.cvc.smt2                                                    |   7.371s  |   7.371s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-14.base.cvc.smt2                                                         |  30.096s  |  30.096s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-14.induction.cvc.smt2                                                    |   6.326s  |   6.326s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-15.base.cvc.smt2                                                         |  30.126s  |  30.126s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-15.induction.cvc.smt2                                                    |  12.946s  |  12.946s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-16.base.cvc.smt2                                                         |  30.092s  |  30.092s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-16.induction.cvc.smt2                                                    |   8.205s  |   8.205s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-17.base.cvc.smt2                                                         |  30.101s  |  30.101s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-17.induction.cvc.smt2                                                    |  12.511s  |  12.511s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-18.base.cvc.smt2                                                         |  30.141s  |  30.141s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-18.induction.cvc.smt2                                                    |  12.215s  |  12.215s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-19.base.cvc.smt2                                                         |  30.109s  |  30.109s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-19.induction.cvc.smt2                                                    |  11.120s  |  11.120s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                         |  30.124s  |  30.124s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-20.induction.cvc.smt2                                                    |  23.345s  |  23.345s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-5.base.cvc.smt2                                                          |   1.073s  |   1.073s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-5.induction.cvc.smt2                                                     |   0.903s  |   0.903s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-6.base.cvc.smt2                                                          |   0.833s  |   0.833s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-6.induction.cvc.smt2                                                     |   1.142s  |   1.142s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-7.base.cvc.smt2                                                          |   1.114s  |   1.114s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-7.induction.cvc.smt2                                                     |   1.627s  |   1.627s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-8.base.cvc.smt2                                                          |   1.362s  |   1.362s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-8.induction.cvc.smt2                                                     |   1.875s  |   1.875s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-9.base.cvc.smt2                                                          |   1.572s  |   1.572s  |   0.000s  | 0.0%|
</details>
