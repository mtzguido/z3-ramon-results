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
Job tag: smt_qflia-threads-4-update_bb_hyperparams
Runner: lev-ripper
Z3 repo: ilanashapiro/z3
Z3 commit: 318e4a10580d65c819338e7eb0c1410b0200f613
Z3 branch: backbones
Z3 options: "-T:30 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_bb_threads=1"
Z3 inputs: inputs/QF_LIA
Z3 commit message: update bb hyperparams after copilot (hopefully??) ran tuning experiments

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt_qflia-threads-4-update_bb_hyperparams
Runner: lev-ripper
Z3 repo: ilanashapiro/z3
Z3 commit: 318e4a10580d65c819338e7eb0c1410b0200f613
Z3 branch: backbones
Z3 options: "-T:30 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.num_bb_threads=1"
Z3 inputs: inputs/QF_LIA
Z3 commit message: update bb hyperparams after copilot (hopefully??) ran tuning experiments

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
|n4408-RF-03.smt2                                                                           |   0.034s |1780.0KiB|
|v30_problem_2__019.smt2.slack.smt2                                                         |   0.034s |1788.0KiB|
|n7761-prp-7-46.smt2                                                                        |   0.032s |1560.0KiB|
|n3131-RF-08.smt2                                                                           |   0.032s |1564.0KiB|
|n8303-ring_2exp14_7vars_4ite_unsat.smt2                                                    |   0.032s |1788.0KiB|
|n2151-RC-11.smt2                                                                           |   0.031s |1788.0KiB|
|n3948-RF-09.smt2                                                                           |   0.031s |1560.0KiB|
|n5346-RC-02.smt2                                                                           |   0.031s |1788.0KiB|
|ex3180_2400_100.smt2                                                                       |   0.031s |1788.0KiB|
|n2475-RF-08.smt2                                                                           |   0.031s |1564.0KiB|
|n4343-RC-10.smt2                                                                           |   0.031s |1560.0KiB|
|n912-RC-01.smt2                                                                            |   0.030s |1560.0KiB|
|n3146-RC-07.smt2                                                                           |   0.030s |1560.0KiB|
|n5249-RF-01.smt2                                                                           |   0.030s |1560.0KiB|
|n3649-RC-10.smt2                                                                           |   0.030s |1560.0KiB|
|n5521-RC-00.smt2                                                                           |   0.030s |1560.0KiB|
|n3221-RF-02.smt2                                                                           |   0.030s |1560.0KiB|
|n3345-RF-05.smt2                                                                           |   0.030s |1560.0KiB|
|n5592-RC-15.smt2                                                                           |   0.029s |1568.0KiB|
|n5297-RC-07.smt2                                                                           |   0.029s |1560.0KiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|n4408-RF-03.smt2                                                                           |   0.034s |1780.0KiB|
|v30_problem_2__019.smt2.slack.smt2                                                         |   0.034s |1788.0KiB|
|n7761-prp-7-46.smt2                                                                        |   0.032s |1560.0KiB|
|n3131-RF-08.smt2                                                                           |   0.032s |1564.0KiB|
|n8303-ring_2exp14_7vars_4ite_unsat.smt2                                                    |   0.032s |1788.0KiB|
|n2151-RC-11.smt2                                                                           |   0.031s |1788.0KiB|
|n3948-RF-09.smt2                                                                           |   0.031s |1560.0KiB|
|n5346-RC-02.smt2                                                                           |   0.031s |1788.0KiB|
|ex3180_2400_100.smt2                                                                       |   0.031s |1788.0KiB|
|n2475-RF-08.smt2                                                                           |   0.031s |1564.0KiB|
|n4343-RC-10.smt2                                                                           |   0.031s |1560.0KiB|
|n912-RC-01.smt2                                                                            |   0.030s |1560.0KiB|
|n3146-RC-07.smt2                                                                           |   0.030s |1560.0KiB|
|n5249-RF-01.smt2                                                                           |   0.030s |1560.0KiB|
|n3649-RC-10.smt2                                                                           |   0.030s |1560.0KiB|
|n5521-RC-00.smt2                                                                           |   0.030s |1560.0KiB|
|n3221-RF-02.smt2                                                                           |   0.030s |1560.0KiB|
|n3345-RF-05.smt2                                                                           |   0.030s |1560.0KiB|
|n5592-RC-15.smt2                                                                           |   0.029s |1568.0KiB|
|n5297-RC-07.smt2                                                                           |   0.029s |1560.0KiB|
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
|n5763-RC-10.smt2                                                                           |   0.025s |2056.0KiB|
|n4565-RF-09.smt2                                                                           |   0.003s |1836.0KiB|
|v30_problem_2__018.smt2.slack.smt2                                                         |   0.019s |1832.0KiB|
|n8142-prp-25-36.smt2                                                                       |   0.023s |1820.0KiB|
|n5628-RF-05.smt2                                                                           |   0.025s |1808.0KiB|
|d60.2.smt2                                                                                 |   0.004s |1800.0KiB|
|n2222-RF-05.smt2                                                                           |   0.028s |1792.0KiB|
|n7087-prp-18-46.smt2                                                                       |   0.026s |1792.0KiB|
|n3430-RC-11.smt2                                                                           |   0.026s |1792.0KiB|
|n25-cut_lemma_02_006.smt2.slack.smt2                                                       |   0.026s |1792.0KiB|
|n3386-RF-15.smt2                                                                           |   0.025s |1792.0KiB|
|v35_problem_2__011.smt2.slack.smt2                                                         |   0.025s |1792.0KiB|
|n4198-RF-05.smt2                                                                           |   0.025s |1792.0KiB|
|n1594-RC-11.smt2                                                                           |   0.025s |1792.0KiB|
|n4497-RF-04.smt2                                                                           |   0.024s |1792.0KiB|
|n1810-RC-08.smt2                                                                           |   0.024s |1792.0KiB|
|n8294-ring_2exp14_6vars_1ite_unsat.smt2                                                    |   0.024s |1792.0KiB|
|n6475-problem__006.smt2                                                                    |   0.024s |1792.0KiB|
|n1966-RC-11.smt2                                                                           |   0.022s |1792.0KiB|
|35-14.slack.smt2                                                                           |   0.022s |1792.0KiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|n5763-RC-10.smt2                                                                           |   0.025s |2056.0KiB|
|n4565-RF-09.smt2                                                                           |   0.003s |1836.0KiB|
|v30_problem_2__018.smt2.slack.smt2                                                         |   0.019s |1832.0KiB|
|n8142-prp-25-36.smt2                                                                       |   0.023s |1820.0KiB|
|n5628-RF-05.smt2                                                                           |   0.025s |1808.0KiB|
|d60.2.smt2                                                                                 |   0.004s |1800.0KiB|
|n2222-RF-05.smt2                                                                           |   0.028s |1792.0KiB|
|n7087-prp-18-46.smt2                                                                       |   0.026s |1792.0KiB|
|n3430-RC-11.smt2                                                                           |   0.026s |1792.0KiB|
|n25-cut_lemma_02_006.smt2.slack.smt2                                                       |   0.026s |1792.0KiB|
|n3386-RF-15.smt2                                                                           |   0.025s |1792.0KiB|
|v35_problem_2__011.smt2.slack.smt2                                                         |   0.025s |1792.0KiB|
|n4198-RF-05.smt2                                                                           |   0.025s |1792.0KiB|
|n1594-RC-11.smt2                                                                           |   0.025s |1792.0KiB|
|n4497-RF-04.smt2                                                                           |   0.024s |1792.0KiB|
|n1810-RC-08.smt2                                                                           |   0.024s |1792.0KiB|
|n8294-ring_2exp14_6vars_1ite_unsat.smt2                                                    |   0.024s |1792.0KiB|
|n6475-problem__006.smt2                                                                    |   0.024s |1792.0KiB|
|n1966-RC-11.smt2                                                                           |   0.022s |1792.0KiB|
|35-14.slack.smt2                                                                           |   0.022s |1792.0KiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>
