Comparing data and data


# SUMMARY
- LHS tests = 5000
- RHS tests = 5000
- LHS success = 0  (0.0%)
- RHS success = 0  (0.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt_qflia-threads-4-shareunits-no_inprocessing-shareconflicts1
Runner: lev-ripper
Z3 repo: ilanashapiro/z3
Z3 commit: 26119a88154a77e05984d35baabd0a52992c356f
Z3 branch: parallel-lockdebug1
Z3 options: "-T:30 smt.threads=4 tactic.default_tactic=smt smt_parallel.share_units=true smt_parallel.inprocessing=false smt_parallel.share_conflicts=true"
Z3 inputs: inputs/QF_LIA
Z3 commit message: clean up code

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt_qflia-threads-4-shareunits-no_inprocessing-shareconflicts1
Runner: lev-ripper
Z3 repo: ilanashapiro/z3
Z3 commit: 26119a88154a77e05984d35baabd0a52992c356f
Z3 branch: parallel-lockdebug1
Z3 options: "-T:30 smt.threads=4 tactic.default_tactic=smt smt_parallel.share_units=true smt_parallel.inprocessing=false smt_parallel.share_conflicts=true"
Z3 inputs: inputs/QF_LIA
Z3 commit message: clean up code

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|n3175-RC-04.smt2                                                                           |   0.033s |1560.0KiB|
|n6177-problem_2__023.smt2                                                                  |   0.032s |1788.0KiB|
|ex4060_2400_100.smt2                                                                       |   0.031s |1784.0KiB|
|n4141-RF-10.smt2                                                                           |   0.031s |1560.0KiB|
|n2198-RF-13.smt2                                                                           |   0.031s |1572.0KiB|
|n3534-RF-04.smt2                                                                           |   0.030s |1792.0KiB|
|n6112-problem_2__028.smt2                                                                  |   0.030s |1560.0KiB|
|n5670-RC-07.smt2                                                                           |   0.030s |1560.0KiB|
|n3058-RC-13.smt2                                                                           |   0.030s |1560.0KiB|
|n8341-ring_2exp16_7vars_0ite_unsat.smt2                                                    |   0.030s |1576.0KiB|
|n8096-prp-4-47.smt2                                                                        |   0.030s |1788.0KiB|
|n788-RC-03.smt2                                                                            |   0.030s |1560.0KiB|
|n2622-RF-06.smt2                                                                           |   0.030s |1560.0KiB|
|n6393-problem_2__029.smt2                                                                  |   0.030s |1560.0KiB|
|n8473-ring_2exp8_7vars_6ite_unsat.smt2                                                     |   0.030s |1548.0KiB|
|n1852-RF-03.smt2                                                                           |   0.030s |1560.0KiB|
|prp-24-33.smt2                                                                             |   0.030s |1788.0KiB|
|n2291-RF-11.smt2                                                                           |   0.030s |1564.0KiB|
|n5603-RF-12.smt2                                                                           |   0.030s |1564.0KiB|
|n5932-RC-09.smt2                                                                           |   0.029s |1564.0KiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|n3175-RC-04.smt2                                                                           |   0.033s |1560.0KiB|
|n6177-problem_2__023.smt2                                                                  |   0.032s |1788.0KiB|
|ex4060_2400_100.smt2                                                                       |   0.031s |1784.0KiB|
|n4141-RF-10.smt2                                                                           |   0.031s |1560.0KiB|
|n2198-RF-13.smt2                                                                           |   0.031s |1572.0KiB|
|n3534-RF-04.smt2                                                                           |   0.030s |1792.0KiB|
|n6112-problem_2__028.smt2                                                                  |   0.030s |1560.0KiB|
|n5670-RC-07.smt2                                                                           |   0.030s |1560.0KiB|
|n3058-RC-13.smt2                                                                           |   0.030s |1560.0KiB|
|n8341-ring_2exp16_7vars_0ite_unsat.smt2                                                    |   0.030s |1576.0KiB|
|n8096-prp-4-47.smt2                                                                        |   0.030s |1788.0KiB|
|n788-RC-03.smt2                                                                            |   0.030s |1560.0KiB|
|n2622-RF-06.smt2                                                                           |   0.030s |1560.0KiB|
|n6393-problem_2__029.smt2                                                                  |   0.030s |1560.0KiB|
|n8473-ring_2exp8_7vars_6ite_unsat.smt2                                                     |   0.030s |1548.0KiB|
|n1852-RF-03.smt2                                                                           |   0.030s |1560.0KiB|
|prp-24-33.smt2                                                                             |   0.030s |1788.0KiB|
|n2291-RF-11.smt2                                                                           |   0.030s |1564.0KiB|
|n5603-RF-12.smt2                                                                           |   0.030s |1564.0KiB|
|n5932-RC-09.smt2                                                                           |   0.029s |1564.0KiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|n7528-prp-34-47.smt2                                                                       |   0.025s |1844.0KiB|
|n7277-prp-52-48.smt2                                                                       |   0.005s |1816.0KiB|
|n7327-prp-61-49.smt2                                                                       |   0.004s |1816.0KiB|
|n4564-RF-08.smt2                                                                           |   0.003s |1816.0KiB|
|n5222-RF-00.smt2                                                                           |   0.003s |1816.0KiB|
|n7258-prp-49-49.smt2                                                                       |   0.004s |1812.0KiB|
|n4931-RC-10.smt2                                                                           |   0.003s |1812.0KiB|
|n7033-prp-9-46.smt2                                                                        |   0.025s |1796.0KiB|
|v20_problem__032.smt2.slack.smt2                                                           |   0.003s |1796.0KiB|
|n3534-RF-04.smt2                                                                           |   0.030s |1792.0KiB|
|ex8020_2400_100.smt2                                                                       |   0.026s |1792.0KiB|
|20-9.slack.smt2                                                                            |   0.026s |1792.0KiB|
|n718-RF-03.smt2                                                                            |   0.026s |1792.0KiB|
|n2465-RC-12.smt2                                                                           |   0.025s |1792.0KiB|
|n2239-RC-06.smt2                                                                           |   0.024s |1792.0KiB|
|FISCHER1-1-fair.smt2                                                                       |   0.023s |1792.0KiB|
|n2165-RF-10.smt2                                                                           |   0.023s |1792.0KiB|
|n534-RF-05.smt2                                                                            |   0.022s |1792.0KiB|
|n4226-RF-01.smt2                                                                           |   0.022s |1792.0KiB|
|n6029-problem__001.smt2                                                                    |   0.021s |1792.0KiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|n7528-prp-34-47.smt2                                                                       |   0.025s |1844.0KiB|
|n7277-prp-52-48.smt2                                                                       |   0.005s |1816.0KiB|
|n7327-prp-61-49.smt2                                                                       |   0.004s |1816.0KiB|
|n4564-RF-08.smt2                                                                           |   0.003s |1816.0KiB|
|n5222-RF-00.smt2                                                                           |   0.003s |1816.0KiB|
|n7258-prp-49-49.smt2                                                                       |   0.004s |1812.0KiB|
|n4931-RC-10.smt2                                                                           |   0.003s |1812.0KiB|
|n7033-prp-9-46.smt2                                                                        |   0.025s |1796.0KiB|
|v20_problem__032.smt2.slack.smt2                                                           |   0.003s |1796.0KiB|
|n3534-RF-04.smt2                                                                           |   0.030s |1792.0KiB|
|ex8020_2400_100.smt2                                                                       |   0.026s |1792.0KiB|
|20-9.slack.smt2                                                                            |   0.026s |1792.0KiB|
|n718-RF-03.smt2                                                                            |   0.026s |1792.0KiB|
|n2465-RC-12.smt2                                                                           |   0.025s |1792.0KiB|
|n2239-RC-06.smt2                                                                           |   0.024s |1792.0KiB|
|FISCHER1-1-fair.smt2                                                                       |   0.023s |1792.0KiB|
|n2165-RF-10.smt2                                                                           |   0.023s |1792.0KiB|
|n534-RF-05.smt2                                                                            |   0.022s |1792.0KiB|
|n4226-RF-01.smt2                                                                           |   0.022s |1792.0KiB|
|n6029-problem__001.smt2                                                                    |   0.021s |1792.0KiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>
