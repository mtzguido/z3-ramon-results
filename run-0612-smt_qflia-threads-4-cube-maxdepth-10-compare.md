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
Job tag: smt_qflia-threads-4-cube-maxdepth-10
Runner: lev-ripper
Z3 repo: ilanashapiro/z3
Z3 commit: 0fdf5bcb3f7b1a50215d74a4d5f836dfe620ccb5
Z3 branch: 
Z3 options: "-T:30 smt.threads=4 tactic.default_tactic=smt smt_parallel.share_conflicts=false smt_parallel.share_units=false smt_parallel.max_cube_depth=10"
Z3 inputs: inputs/QF_LIA
Z3 commit message: Fix configuration for depth splitting in notes

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt_qflia-threads-4-cube-maxdepth-10
Runner: lev-ripper
Z3 repo: ilanashapiro/z3
Z3 commit: 0fdf5bcb3f7b1a50215d74a4d5f836dfe620ccb5
Z3 branch: 
Z3 options: "-T:30 smt.threads=4 tactic.default_tactic=smt smt_parallel.share_conflicts=false smt_parallel.share_units=false smt_parallel.max_cube_depth=10"
Z3 inputs: inputs/QF_LIA
Z3 commit message: Fix configuration for depth splitting in notes

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
|n1216-RF-01.smt2                                                                           |   0.032s |1560.0KiB|
|n3684-RC-15.smt2                                                                           |   0.031s |1788.0KiB|
|c100_problem__006.smt2.slack.smt2                                                          |   0.030s |1560.0KiB|
|ex28000_2600_100.smt2                                                                      |   0.030s |1560.0KiB|
|n2811-RF-06.smt2                                                                           |   0.030s |1560.0KiB|
|n2757-RC-00.smt2                                                                           |   0.030s |1560.0KiB|
|n5603-RF-12.smt2                                                                           |   0.030s |1560.0KiB|
|n2311-RF-00.smt2                                                                           |   0.029s |1560.0KiB|
|n3457-RC-06.smt2                                                                           |   0.029s |1560.0KiB|
|35-3.slack.smt2                                                                            |   0.029s |1560.0KiB|
|v40_problem_2__007.smt2.slack.smt2                                                         |   0.029s |1560.0KiB|
|n4485-RC-07.smt2                                                                           |   0.029s |1560.0KiB|
|v35_problem_2__011.smt2.slack.smt2                                                         |   0.029s |1788.0KiB|
|n6417-problem__018.smt2                                                                    |   0.029s |1788.0KiB|
|10-15.smt2                                                                                 |   0.029s |1560.0KiB|
|v10_problem__019.smt2.slack.smt2                                                           |   0.029s |1564.0KiB|
|n6898-prp-44-48.smt2                                                                       |   0.029s |1564.0KiB|
|n6304-problem_2__010.smt2                                                                  |   0.029s |1788.0KiB|
|n2874-RF-05.smt2                                                                           |   0.028s |1560.0KiB|
|n5617-RC-10.smt2                                                                           |   0.028s |1564.0KiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|n1216-RF-01.smt2                                                                           |   0.032s |1560.0KiB|
|n3684-RC-15.smt2                                                                           |   0.031s |1788.0KiB|
|c100_problem__006.smt2.slack.smt2                                                          |   0.030s |1560.0KiB|
|ex28000_2600_100.smt2                                                                      |   0.030s |1560.0KiB|
|n2811-RF-06.smt2                                                                           |   0.030s |1560.0KiB|
|n2757-RC-00.smt2                                                                           |   0.030s |1560.0KiB|
|n5603-RF-12.smt2                                                                           |   0.030s |1560.0KiB|
|n2311-RF-00.smt2                                                                           |   0.029s |1560.0KiB|
|n3457-RC-06.smt2                                                                           |   0.029s |1560.0KiB|
|35-3.slack.smt2                                                                            |   0.029s |1560.0KiB|
|v40_problem_2__007.smt2.slack.smt2                                                         |   0.029s |1560.0KiB|
|n4485-RC-07.smt2                                                                           |   0.029s |1560.0KiB|
|v35_problem_2__011.smt2.slack.smt2                                                         |   0.029s |1788.0KiB|
|n6417-problem__018.smt2                                                                    |   0.029s |1788.0KiB|
|10-15.smt2                                                                                 |   0.029s |1560.0KiB|
|v10_problem__019.smt2.slack.smt2                                                           |   0.029s |1564.0KiB|
|n6898-prp-44-48.smt2                                                                       |   0.029s |1564.0KiB|
|n6304-problem_2__010.smt2                                                                  |   0.029s |1788.0KiB|
|n2874-RF-05.smt2                                                                           |   0.028s |1560.0KiB|
|n5617-RC-10.smt2                                                                           |   0.028s |1564.0KiB|
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
|convert-jpg2gif-query-1239.smt2                                                            |   0.004s |2044.0KiB|
|n7050-prp-10-49.smt2                                                                       |   0.017s |1816.0KiB|
|n7350-prp-68-49.smt2                                                                       |   0.004s |1816.0KiB|
|n7277-prp-52-48.smt2                                                                       |   0.025s |1804.0KiB|
|n6260-problem__001.smt2                                                                    |   0.020s |1804.0KiB|
|n7618-prp-50-47.smt2                                                                       |   0.018s |1804.0KiB|
|n2836-RC-15.smt2                                                                           |   0.026s |1792.0KiB|
|n5481-RF-04.smt2                                                                           |   0.025s |1792.0KiB|
|n6060-problem__001.smt2                                                                    |   0.025s |1792.0KiB|
|MULTIPLIER_PRIME_11.msat.smt2                                                              |   0.025s |1792.0KiB|
|n4003-RF-00.smt2                                                                           |   0.024s |1792.0KiB|
|ex27900_2600_100.smt2                                                                      |   0.024s |1792.0KiB|
|n3463-RC-12.smt2                                                                           |   0.021s |1792.0KiB|
|n477-RF-11.smt2                                                                            |   0.019s |1792.0KiB|
|n4495-RF-02.smt2                                                                           |   0.019s |1792.0KiB|
|45-11.smt2                                                                                 |   0.019s |1792.0KiB|
|n3283-RF-06.smt2                                                                           |   0.012s |1792.0KiB|
|n3067-RF-06.smt2                                                                           |   0.011s |1792.0KiB|
|FISCHER7-9-fair.smt2                                                                       |   0.004s |1792.0KiB|
|n40-sat-b5.lp.smt2                                                                         |   0.004s |1792.0KiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|convert-jpg2gif-query-1239.smt2                                                            |   0.004s |2044.0KiB|
|n7050-prp-10-49.smt2                                                                       |   0.017s |1816.0KiB|
|n7350-prp-68-49.smt2                                                                       |   0.004s |1816.0KiB|
|n7277-prp-52-48.smt2                                                                       |   0.025s |1804.0KiB|
|n6260-problem__001.smt2                                                                    |   0.020s |1804.0KiB|
|n7618-prp-50-47.smt2                                                                       |   0.018s |1804.0KiB|
|n2836-RC-15.smt2                                                                           |   0.026s |1792.0KiB|
|n5481-RF-04.smt2                                                                           |   0.025s |1792.0KiB|
|n6060-problem__001.smt2                                                                    |   0.025s |1792.0KiB|
|MULTIPLIER_PRIME_11.msat.smt2                                                              |   0.025s |1792.0KiB|
|n4003-RF-00.smt2                                                                           |   0.024s |1792.0KiB|
|ex27900_2600_100.smt2                                                                      |   0.024s |1792.0KiB|
|n3463-RC-12.smt2                                                                           |   0.021s |1792.0KiB|
|n477-RF-11.smt2                                                                            |   0.019s |1792.0KiB|
|n4495-RF-02.smt2                                                                           |   0.019s |1792.0KiB|
|45-11.smt2                                                                                 |   0.019s |1792.0KiB|
|n3283-RF-06.smt2                                                                           |   0.012s |1792.0KiB|
|n3067-RF-06.smt2                                                                           |   0.011s |1792.0KiB|
|FISCHER7-9-fair.smt2                                                                       |   0.004s |1792.0KiB|
|n40-sat-b5.lp.smt2                                                                         |   0.004s |1792.0KiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>
