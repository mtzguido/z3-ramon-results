Comparing data and data


# SUMMARY
- LHS tests = 5000
- RHS tests = 5000
- LHS success = 360  (7.2%)
- RHS success = 360  (7.2%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt_qflia-threads-4
Runner: lev-ripper
Z3 repo: ilanashapiro/z3
Z3 commit: 9ebd9343485603e28d1d08382c26ee3738aa382a
Z3 branch: sls-tactic
Z3 options: "-T:30 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.sls=false"
Z3 inputs: inputs/QF_LIA
Z3 commit message: clean up code

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt_qflia-threads-4
Runner: lev-ripper
Z3 repo: ilanashapiro/z3
Z3 commit: 9ebd9343485603e28d1d08382c26ee3738aa382a
Z3 branch: sls-tactic
Z3 options: "-T:30 smt.threads=4 tactic.default_tactic=smt smt.auto_config=false smt_parallel.sls=false"
Z3 inputs: inputs/QF_LIA
Z3 commit message: clean up code

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|20-14.smt2                                                                                  |  30.018s  |  30.018s  |   0.000s  | 0.0%|
|25-27.smt2                                                                                  |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|25-33.smt2                                                                                  |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|25-35.slack.smt2                                                                            |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|30-16.slack.smt2                                                                            |  30.037s  |  30.037s  |   0.000s  | 0.0%|
|30-27.smt2                                                                                  |  30.033s  |  30.033s  |   0.000s  | 0.0%|
|30-31.slack.smt2                                                                            |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|40-8.slack.smt2                                                                             |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|Example_7.txt.smt2                                                                          |  30.040s  |  30.040s  |   0.000s  | 0.0%|
|Example_9.txt.smt2                                                                          |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|MULTIPLIER_11.msat.smt2                                                                     |  30.037s  |  30.037s  |   0.000s  | 0.0%|
|MULTIPLIER_32.msat.smt2                                                                     |  30.025s  |  30.025s  |   0.000s  | 0.0%|
|MULTIPLIER_9.msat.smt2                                                                      |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|SIMPLEBITADDER_COMPOSE_10.msat.smt2                                                         |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|SIMPLEBITADDER_COMPOSE_13.msat.smt2                                                         |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|SIMPLEBITADDER_COMPOSE_14.msat.smt2                                                         |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|Sz256_6616.smt2                                                                             |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|c10_problem__003.smt2.slack.smt2                                                            |  30.021s  |  30.021s  |   0.000s  | 0.0%|
|constraint-221609.smt2                                                                      |  30.069s  |  30.069s  |   0.000s  | 0.0%|
|constraint-285271.smt2                                                                      |  30.083s  |  30.083s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|20-14.smt2                                                                                  |  30.018s  |  30.018s  |   0.000s  | 0.0%|
|25-27.smt2                                                                                  |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|25-33.smt2                                                                                  |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|25-35.slack.smt2                                                                            |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|30-16.slack.smt2                                                                            |  30.037s  |  30.037s  |   0.000s  | 0.0%|
|30-27.smt2                                                                                  |  30.033s  |  30.033s  |   0.000s  | 0.0%|
|30-31.slack.smt2                                                                            |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|40-8.slack.smt2                                                                             |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|Example_7.txt.smt2                                                                          |  30.040s  |  30.040s  |   0.000s  | 0.0%|
|Example_9.txt.smt2                                                                          |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|MULTIPLIER_11.msat.smt2                                                                     |  30.037s  |  30.037s  |   0.000s  | 0.0%|
|MULTIPLIER_32.msat.smt2                                                                     |  30.025s  |  30.025s  |   0.000s  | 0.0%|
|MULTIPLIER_9.msat.smt2                                                                      |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|SIMPLEBITADDER_COMPOSE_10.msat.smt2                                                         |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|SIMPLEBITADDER_COMPOSE_13.msat.smt2                                                         |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|SIMPLEBITADDER_COMPOSE_14.msat.smt2                                                         |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|Sz256_6616.smt2                                                                             |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|c10_problem__003.smt2.slack.smt2                                                            |  30.021s  |  30.021s  |   0.000s  | 0.0%|
|constraint-221609.smt2                                                                      |  30.069s  |  30.069s  |   0.000s  | 0.0%|
|constraint-285271.smt2                                                                      |  30.083s  |  30.083s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|20-14.smt2                                                                                  |  30.018s  |  30.018s  |   0.000s  | 0.0%|
|25-27.smt2                                                                                  |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|25-33.smt2                                                                                  |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|25-35.slack.smt2                                                                            |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|30-16.slack.smt2                                                                            |  30.037s  |  30.037s  |   0.000s  | 0.0%|
|30-27.smt2                                                                                  |  30.033s  |  30.033s  |   0.000s  | 0.0%|
|30-31.slack.smt2                                                                            |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|40-8.slack.smt2                                                                             |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|Example_7.txt.smt2                                                                          |  30.040s  |  30.040s  |   0.000s  | 0.0%|
|Example_9.txt.smt2                                                                          |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|MULTIPLIER_11.msat.smt2                                                                     |  30.037s  |  30.037s  |   0.000s  | 0.0%|
|MULTIPLIER_32.msat.smt2                                                                     |  30.025s  |  30.025s  |   0.000s  | 0.0%|
|MULTIPLIER_9.msat.smt2                                                                      |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|SIMPLEBITADDER_COMPOSE_10.msat.smt2                                                         |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|SIMPLEBITADDER_COMPOSE_13.msat.smt2                                                         |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|SIMPLEBITADDER_COMPOSE_14.msat.smt2                                                         |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|Sz256_6616.smt2                                                                             |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|c10_problem__003.smt2.slack.smt2                                                            |  30.021s  |  30.021s  |   0.000s  | 0.0%|
|constraint-221609.smt2                                                                      |  30.069s  |  30.069s  |   0.000s  | 0.0%|
|constraint-285271.smt2                                                                      |  30.083s  |  30.083s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|20-14.smt2                                                                                  |  30.018s  |  30.018s  |   0.000s  | 0.0%|
|25-27.smt2                                                                                  |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|25-33.smt2                                                                                  |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|25-35.slack.smt2                                                                            |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|30-16.slack.smt2                                                                            |  30.037s  |  30.037s  |   0.000s  | 0.0%|
|30-27.smt2                                                                                  |  30.033s  |  30.033s  |   0.000s  | 0.0%|
|30-31.slack.smt2                                                                            |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|40-8.slack.smt2                                                                             |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|Example_7.txt.smt2                                                                          |  30.040s  |  30.040s  |   0.000s  | 0.0%|
|Example_9.txt.smt2                                                                          |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|MULTIPLIER_11.msat.smt2                                                                     |  30.037s  |  30.037s  |   0.000s  | 0.0%|
|MULTIPLIER_32.msat.smt2                                                                     |  30.025s  |  30.025s  |   0.000s  | 0.0%|
|MULTIPLIER_9.msat.smt2                                                                      |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|SIMPLEBITADDER_COMPOSE_10.msat.smt2                                                         |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|SIMPLEBITADDER_COMPOSE_13.msat.smt2                                                         |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|SIMPLEBITADDER_COMPOSE_14.msat.smt2                                                         |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|Sz256_6616.smt2                                                                             |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|c10_problem__003.smt2.slack.smt2                                                            |  30.021s  |  30.021s  |   0.000s  | 0.0%|
|constraint-221609.smt2                                                                      |  30.069s  |  30.069s  |   0.000s  | 0.0%|
|constraint-285271.smt2                                                                      |  30.083s  |  30.083s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|constraint-579281.smt2                                                                     |  30.138s |776.0MiB|
|constraint-551279.smt2                                                                     |  30.125s |817.0MiB|
|constraint-603294.smt2                                                                     |  30.122s |751.0MiB|
|constraint-495717.smt2                                                                     |  30.122s |687.0MiB|
|constraint-506600.smt2                                                                     |  30.109s |663.0MiB|
|constraint-478122.smt2                                                                     |  30.106s |743.0MiB|
|constraint-479884.smt2                                                                     |  30.103s |640.0MiB|
|n7618-prp-50-47.smt2                                                                       |  30.098s |440.0MiB|
|n7549-prp-38-48.smt2                                                                       |  30.094s |452.0MiB|
|constraint-357303.smt2                                                                     |  30.093s |571.0MiB|
|n7453-prp-20-47.smt2                                                                       |  30.093s |505.0MiB|
|constraint-394532.smt2                                                                     |  30.092s |559.0MiB|
|n7555-prp-39-49.smt2                                                                       |  30.091s |476.0MiB|
|n7402-prp-11-46.smt2                                                                       |  30.091s |442.0MiB|
|n7444-prp-19-48.smt2                                                                       |  30.090s |535.0MiB|
|n7405-prp-11-49.smt2                                                                       |  30.089s |470.0MiB|
|n7514-prp-31-48.smt2                                                                       |  30.088s |449.0MiB|
|n7464-prp-22-48.smt2                                                                       |  30.088s |523.0MiB|
|n7510-prp-30-49.smt2                                                                       |  30.088s |471.0MiB|
|n7499-prp-29-48.smt2                                                                       |  30.087s |523.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|constraint-579281.smt2                                                                     |  30.138s |776.0MiB|
|constraint-551279.smt2                                                                     |  30.125s |817.0MiB|
|constraint-603294.smt2                                                                     |  30.122s |751.0MiB|
|constraint-495717.smt2                                                                     |  30.122s |687.0MiB|
|constraint-506600.smt2                                                                     |  30.109s |663.0MiB|
|constraint-478122.smt2                                                                     |  30.106s |743.0MiB|
|constraint-479884.smt2                                                                     |  30.103s |640.0MiB|
|n7618-prp-50-47.smt2                                                                       |  30.098s |440.0MiB|
|n7549-prp-38-48.smt2                                                                       |  30.094s |452.0MiB|
|constraint-357303.smt2                                                                     |  30.093s |571.0MiB|
|n7453-prp-20-47.smt2                                                                       |  30.093s |505.0MiB|
|constraint-394532.smt2                                                                     |  30.092s |559.0MiB|
|n7555-prp-39-49.smt2                                                                       |  30.091s |476.0MiB|
|n7402-prp-11-46.smt2                                                                       |  30.091s |442.0MiB|
|n7444-prp-19-48.smt2                                                                       |  30.090s |535.0MiB|
|n7405-prp-11-49.smt2                                                                       |  30.089s |470.0MiB|
|n7514-prp-31-48.smt2                                                                       |  30.088s |449.0MiB|
|n7464-prp-22-48.smt2                                                                       |  30.088s |523.0MiB|
|n7510-prp-30-49.smt2                                                                       |  30.088s |471.0MiB|
|n7499-prp-29-48.smt2                                                                       |  30.087s |523.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|20-14.smt2                                                                                  |94.04MiB|94.04MiB|0B| 0.0%|
|25-27.smt2                                                                                  |93.688MiB|93.688MiB|0B| 0.0%|
|25-33.smt2                                                                                  |93.392MiB|93.392MiB|0B| 0.0%|
|25-35.slack.smt2                                                                            |96.324MiB|96.324MiB|0B| 0.0%|
|30-16.slack.smt2                                                                            |96.08MiB|96.08MiB|0B| 0.0%|
|30-27.smt2                                                                                  |94.78MiB|94.78MiB|0B| 0.0%|
|30-31.slack.smt2                                                                            |96.78MiB|96.78MiB|0B| 0.0%|
|40-8.slack.smt2                                                                             |97.592MiB|97.592MiB|0B| 0.0%|
|Example_7.txt.smt2                                                                          |133.0MiB|133.0MiB|0B| 0.0%|
|Example_9.txt.smt2                                                                          |152.0MiB|152.0MiB|0B| 0.0%|
|MULTIPLIER_11.msat.smt2                                                                     |112.0MiB|112.0MiB|0B| 0.0%|
|MULTIPLIER_32.msat.smt2                                                                     |116.0MiB|116.0MiB|0B| 0.0%|
|MULTIPLIER_9.msat.smt2                                                                      |105.0MiB|105.0MiB|0B| 0.0%|
|SIMPLEBITADDER_COMPOSE_10.msat.smt2                                                         |102.0MiB|102.0MiB|0B| 0.0%|
|SIMPLEBITADDER_COMPOSE_13.msat.smt2                                                         |107.0MiB|107.0MiB|0B| 0.0%|
|SIMPLEBITADDER_COMPOSE_14.msat.smt2                                                         |108.0MiB|108.0MiB|0B| 0.0%|
|Sz256_6616.smt2                                                                             |118.0MiB|118.0MiB|0B| 0.0%|
|c10_problem__003.smt2.slack.smt2                                                            |98.836MiB|98.836MiB|0B| 0.0%|
|constraint-221609.smt2                                                                      |309.0MiB|309.0MiB|0B| 0.0%|
|constraint-285271.smt2                                                                      |375.0MiB|375.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|20-14.smt2                                                                                  |94.04MiB|94.04MiB|0B| 0.0%|
|25-27.smt2                                                                                  |93.688MiB|93.688MiB|0B| 0.0%|
|25-33.smt2                                                                                  |93.392MiB|93.392MiB|0B| 0.0%|
|25-35.slack.smt2                                                                            |96.324MiB|96.324MiB|0B| 0.0%|
|30-16.slack.smt2                                                                            |96.08MiB|96.08MiB|0B| 0.0%|
|30-27.smt2                                                                                  |94.78MiB|94.78MiB|0B| 0.0%|
|30-31.slack.smt2                                                                            |96.78MiB|96.78MiB|0B| 0.0%|
|40-8.slack.smt2                                                                             |97.592MiB|97.592MiB|0B| 0.0%|
|Example_7.txt.smt2                                                                          |133.0MiB|133.0MiB|0B| 0.0%|
|Example_9.txt.smt2                                                                          |152.0MiB|152.0MiB|0B| 0.0%|
|MULTIPLIER_11.msat.smt2                                                                     |112.0MiB|112.0MiB|0B| 0.0%|
|MULTIPLIER_32.msat.smt2                                                                     |116.0MiB|116.0MiB|0B| 0.0%|
|MULTIPLIER_9.msat.smt2                                                                      |105.0MiB|105.0MiB|0B| 0.0%|
|SIMPLEBITADDER_COMPOSE_10.msat.smt2                                                         |102.0MiB|102.0MiB|0B| 0.0%|
|SIMPLEBITADDER_COMPOSE_13.msat.smt2                                                         |107.0MiB|107.0MiB|0B| 0.0%|
|SIMPLEBITADDER_COMPOSE_14.msat.smt2                                                         |108.0MiB|108.0MiB|0B| 0.0%|
|Sz256_6616.smt2                                                                             |118.0MiB|118.0MiB|0B| 0.0%|
|c10_problem__003.smt2.slack.smt2                                                            |98.836MiB|98.836MiB|0B| 0.0%|
|constraint-221609.smt2                                                                      |309.0MiB|309.0MiB|0B| 0.0%|
|constraint-285271.smt2                                                                      |375.0MiB|375.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|20-14.smt2                                                                                  |94.04MiB|94.04MiB|0B| 0.0%|
|25-27.smt2                                                                                  |93.688MiB|93.688MiB|0B| 0.0%|
|25-33.smt2                                                                                  |93.392MiB|93.392MiB|0B| 0.0%|
|25-35.slack.smt2                                                                            |96.324MiB|96.324MiB|0B| 0.0%|
|30-16.slack.smt2                                                                            |96.08MiB|96.08MiB|0B| 0.0%|
|30-27.smt2                                                                                  |94.78MiB|94.78MiB|0B| 0.0%|
|30-31.slack.smt2                                                                            |96.78MiB|96.78MiB|0B| 0.0%|
|40-8.slack.smt2                                                                             |97.592MiB|97.592MiB|0B| 0.0%|
|Example_7.txt.smt2                                                                          |133.0MiB|133.0MiB|0B| 0.0%|
|Example_9.txt.smt2                                                                          |152.0MiB|152.0MiB|0B| 0.0%|
|MULTIPLIER_11.msat.smt2                                                                     |112.0MiB|112.0MiB|0B| 0.0%|
|MULTIPLIER_32.msat.smt2                                                                     |116.0MiB|116.0MiB|0B| 0.0%|
|MULTIPLIER_9.msat.smt2                                                                      |105.0MiB|105.0MiB|0B| 0.0%|
|SIMPLEBITADDER_COMPOSE_10.msat.smt2                                                         |102.0MiB|102.0MiB|0B| 0.0%|
|SIMPLEBITADDER_COMPOSE_13.msat.smt2                                                         |107.0MiB|107.0MiB|0B| 0.0%|
|SIMPLEBITADDER_COMPOSE_14.msat.smt2                                                         |108.0MiB|108.0MiB|0B| 0.0%|
|Sz256_6616.smt2                                                                             |118.0MiB|118.0MiB|0B| 0.0%|
|c10_problem__003.smt2.slack.smt2                                                            |98.836MiB|98.836MiB|0B| 0.0%|
|constraint-221609.smt2                                                                      |309.0MiB|309.0MiB|0B| 0.0%|
|constraint-285271.smt2                                                                      |375.0MiB|375.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|20-14.smt2                                                                                  |94.04MiB|94.04MiB|0B| 0.0%|
|25-27.smt2                                                                                  |93.688MiB|93.688MiB|0B| 0.0%|
|25-33.smt2                                                                                  |93.392MiB|93.392MiB|0B| 0.0%|
|25-35.slack.smt2                                                                            |96.324MiB|96.324MiB|0B| 0.0%|
|30-16.slack.smt2                                                                            |96.08MiB|96.08MiB|0B| 0.0%|
|30-27.smt2                                                                                  |94.78MiB|94.78MiB|0B| 0.0%|
|30-31.slack.smt2                                                                            |96.78MiB|96.78MiB|0B| 0.0%|
|40-8.slack.smt2                                                                             |97.592MiB|97.592MiB|0B| 0.0%|
|Example_7.txt.smt2                                                                          |133.0MiB|133.0MiB|0B| 0.0%|
|Example_9.txt.smt2                                                                          |152.0MiB|152.0MiB|0B| 0.0%|
|MULTIPLIER_11.msat.smt2                                                                     |112.0MiB|112.0MiB|0B| 0.0%|
|MULTIPLIER_32.msat.smt2                                                                     |116.0MiB|116.0MiB|0B| 0.0%|
|MULTIPLIER_9.msat.smt2                                                                      |105.0MiB|105.0MiB|0B| 0.0%|
|SIMPLEBITADDER_COMPOSE_10.msat.smt2                                                         |102.0MiB|102.0MiB|0B| 0.0%|
|SIMPLEBITADDER_COMPOSE_13.msat.smt2                                                         |107.0MiB|107.0MiB|0B| 0.0%|
|SIMPLEBITADDER_COMPOSE_14.msat.smt2                                                         |108.0MiB|108.0MiB|0B| 0.0%|
|Sz256_6616.smt2                                                                             |118.0MiB|118.0MiB|0B| 0.0%|
|c10_problem__003.smt2.slack.smt2                                                            |98.836MiB|98.836MiB|0B| 0.0%|
|constraint-221609.smt2                                                                      |309.0MiB|309.0MiB|0B| 0.0%|
|constraint-285271.smt2                                                                      |375.0MiB|375.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|n4085-RC-02.smt2                                                                           |   3.062s |1921.0MiB|
|n4083-RC-00.smt2                                                                           |   1.630s |1041.0MiB|
|constraint-551279.smt2                                                                     |  30.125s |817.0MiB|
|n4086-RC-03.smt2                                                                           |   1.553s |797.0MiB|
|constraint-605010.smt2                                                                     |  17.462s |790.0MiB|
|constraint-579281.smt2                                                                     |  30.138s |776.0MiB|
|constraint-651478.smt2                                                                     |  14.395s |763.0MiB|
|constraint-603294.smt2                                                                     |  30.122s |751.0MiB|
|constraint-478122.smt2                                                                     |  30.106s |743.0MiB|
|constraint-645054.smt2                                                                     |   4.543s |726.0MiB|
|constraint-642278.smt2                                                                     |  14.709s |723.0MiB|
|constraint-495717.smt2                                                                     |  30.122s |687.0MiB|
|constraint-506600.smt2                                                                     |  30.109s |663.0MiB|
|constraint-644686.smt2                                                                     |   5.908s |653.0MiB|
|constraint-479884.smt2                                                                     |  30.103s |640.0MiB|
|constraint-496324.smt2                                                                     |  10.994s |602.0MiB|
|constraint-357303.smt2                                                                     |  30.093s |571.0MiB|
|n4056-RC-05.smt2                                                                           |   0.707s |566.0MiB|
|n4058-RC-07.smt2                                                                           |   0.785s |564.0MiB|
|constraint-394532.smt2                                                                     |  30.092s |559.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|n4085-RC-02.smt2                                                                           |   3.062s |1921.0MiB|
|n4083-RC-00.smt2                                                                           |   1.630s |1041.0MiB|
|constraint-551279.smt2                                                                     |  30.125s |817.0MiB|
|n4086-RC-03.smt2                                                                           |   1.553s |797.0MiB|
|constraint-605010.smt2                                                                     |  17.462s |790.0MiB|
|constraint-579281.smt2                                                                     |  30.138s |776.0MiB|
|constraint-651478.smt2                                                                     |  14.395s |763.0MiB|
|constraint-603294.smt2                                                                     |  30.122s |751.0MiB|
|constraint-478122.smt2                                                                     |  30.106s |743.0MiB|
|constraint-645054.smt2                                                                     |   4.543s |726.0MiB|
|constraint-642278.smt2                                                                     |  14.709s |723.0MiB|
|constraint-495717.smt2                                                                     |  30.122s |687.0MiB|
|constraint-506600.smt2                                                                     |  30.109s |663.0MiB|
|constraint-644686.smt2                                                                     |   5.908s |653.0MiB|
|constraint-479884.smt2                                                                     |  30.103s |640.0MiB|
|constraint-496324.smt2                                                                     |  10.994s |602.0MiB|
|constraint-357303.smt2                                                                     |  30.093s |571.0MiB|
|n4056-RC-05.smt2                                                                           |   0.707s |566.0MiB|
|n4058-RC-07.smt2                                                                           |   0.785s |564.0MiB|
|constraint-394532.smt2                                                                     |  30.092s |559.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|20-14.smt2                                                                                  |  30.018s  |  30.018s  |   0.000s  | 0.0%|
|25-27.smt2                                                                                  |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|25-33.smt2                                                                                  |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|25-35.slack.smt2                                                                            |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|30-16.slack.smt2                                                                            |  30.037s  |  30.037s  |   0.000s  | 0.0%|
|30-27.smt2                                                                                  |  30.033s  |  30.033s  |   0.000s  | 0.0%|
|30-31.slack.smt2                                                                            |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|40-8.slack.smt2                                                                             |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|Example_7.txt.smt2                                                                          |  30.040s  |  30.040s  |   0.000s  | 0.0%|
|Example_9.txt.smt2                                                                          |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|MULTIPLIER_11.msat.smt2                                                                     |  30.037s  |  30.037s  |   0.000s  | 0.0%|
|MULTIPLIER_32.msat.smt2                                                                     |  30.025s  |  30.025s  |   0.000s  | 0.0%|
|MULTIPLIER_9.msat.smt2                                                                      |  30.047s  |  30.047s  |   0.000s  | 0.0%|
|SIMPLEBITADDER_COMPOSE_10.msat.smt2                                                         |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|SIMPLEBITADDER_COMPOSE_13.msat.smt2                                                         |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|SIMPLEBITADDER_COMPOSE_14.msat.smt2                                                         |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|Sz256_6616.smt2                                                                             |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|c10_problem__003.smt2.slack.smt2                                                            |  30.021s  |  30.021s  |   0.000s  | 0.0%|
|constraint-221609.smt2                                                                      |  30.069s  |  30.069s  |   0.000s  | 0.0%|
|constraint-285271.smt2                                                                      |  30.083s  |  30.083s  |   0.000s  | 0.0%|
|constraint-319990.smt2                                                                      |  30.076s  |  30.076s  |   0.000s  | 0.0%|
|constraint-321761.smt2                                                                      |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|constraint-357303.smt2                                                                      |  30.093s  |  30.093s  |   0.000s  | 0.0%|
|constraint-373262.smt2                                                                      |  30.083s  |  30.083s  |   0.000s  | 0.0%|
|constraint-394532.smt2                                                                      |  30.092s  |  30.092s  |   0.000s  | 0.0%|
|constraint-478122.smt2                                                                      |  30.106s  |  30.106s  |   0.000s  | 0.0%|
|constraint-479884.smt2                                                                      |  30.103s  |  30.103s  |   0.000s  | 0.0%|
|constraint-495717.smt2                                                                      |  30.122s  |  30.122s  |   0.000s  | 0.0%|
|constraint-506600.smt2                                                                      |  30.109s  |  30.109s  |   0.000s  | 0.0%|
|constraint-551279.smt2                                                                      |  30.125s  |  30.125s  |   0.000s  | 0.0%|
|constraint-579281.smt2                                                                      |  30.138s  |  30.138s  |   0.000s  | 0.0%|
|constraint-603294.smt2                                                                      |  30.122s  |  30.122s  |   0.000s  | 0.0%|
|ex5000_2400_100.smt2                                                                        |  30.021s  |  30.021s  |   0.000s  | 0.0%|
|ex5020_2400_100.smt2                                                                        |  30.022s  |  30.022s  |   0.000s  | 0.0%|
|ex5040_2400_100.smt2                                                                        |  30.022s  |  30.022s  |   0.000s  | 0.0%|
|ex5060_2400_100.smt2                                                                        |  30.051s  |  30.051s  |   0.000s  | 0.0%|
|ex5080_2400_100.smt2                                                                        |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|ex5120_2400_100.smt2                                                                        |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|ex5180_2400_100.smt2                                                                        |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|ex5200_2400_100.smt2                                                                        |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|ex5240_2400_100.smt2                                                                        |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|ex5360_2400_100.smt2                                                                        |  30.024s  |  30.024s  |   0.000s  | 0.0%|
|n100-unbd-sage16.smt2                                                                       |  30.033s  |  30.033s  |   0.000s  | 0.0%|
|n103-unbd-sage19.smt2                                                                       |  30.018s  |  30.018s  |   0.000s  | 0.0%|
|n104-unbd-sage2.smt2                                                                        |  30.037s  |  30.037s  |   0.000s  | 0.0%|
|n106-unbd-sage21.smt2                                                                       |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|n107-unbd-sage22.smt2                                                                       |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|n108-unbd-sage23.smt2                                                                       |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|n111-unbd-sage4.smt2                                                                        |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|n113-unbd-sage6.smt2                                                                        |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|n115-unbd-sage8.smt2                                                                        |  30.037s  |  30.037s  |   0.000s  | 0.0%|
|n116-unbd-sage9.smt2                                                                        |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|n118-unbd-sage1.smt2                                                                        |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|n123-unbd-sage14.smt2                                                                       |  30.040s  |  30.040s  |   0.000s  | 0.0%|
|n125-unbd-sage16.smt2                                                                       |  30.040s  |  30.040s  |   0.000s  | 0.0%|
|n128-unbd-sage19.smt2                                                                       |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|n129-unbd-sage2.smt2                                                                        |  30.031s  |  30.031s  |   0.000s  | 0.0%|
|n133-unbd-sage23.smt2                                                                       |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|n135-unbd-sage3.smt2                                                                        |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|n136-unbd-sage4.smt2                                                                        |  30.040s  |  30.040s  |   0.000s  | 0.0%|
|n138-unbd-sage6.smt2                                                                        |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|n49-unbd-sage15.smt2                                                                        |  30.033s  |  30.033s  |   0.000s  | 0.0%|
|n53-unbd-sage19.smt2                                                                        |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|n54-unbd-sage2.smt2                                                                         |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|n6133-problem__014.smt2                                                                     |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|n6258-problem_2__034.smt2                                                                   |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|n6290-problem__031.smt2                                                                     |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|n6329-problem_2__035.smt2                                                                   |  30.040s  |  30.040s  |   0.000s  | 0.0%|
|n6516-cut_lemma_01_006.smt2                                                                 |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|n67-unbd-sage0.smt2                                                                         |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|n6754-prp-14-47.smt2                                                                        |  30.063s  |  30.063s  |   0.000s  | 0.0%|
|n6771-prp-18-49.smt2                                                                        |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|n6772-prp-18-50.smt2                                                                        |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|n6773-prp-19-46.smt2                                                                        |  30.061s  |  30.061s  |   0.000s  | 0.0%|
|n6782-prp-20-50.smt2                                                                        |  30.058s  |  30.058s  |   0.000s  | 0.0%|
|n6806-prp-28-46.smt2                                                                        |  30.058s  |  30.058s  |   0.000s  | 0.0%|
|n6810-prp-28-50.smt2                                                                        |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|n6814-prp-29-49.smt2                                                                        |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|n6825-prp-32-50.smt2                                                                        |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|n6834-prp-34-48.smt2                                                                        |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|n6835-prp-34-49.smt2                                                                        |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|n6836-prp-34-50.smt2                                                                        |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|n6839-prp-36-45.smt2                                                                        |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|n6842-prp-36-48.smt2                                                                        |  30.067s  |  30.067s  |   0.000s  | 0.0%|
|n6844-prp-36-50.smt2                                                                        |  30.067s  |  30.067s  |   0.000s  | 0.0%|
|n6849-prp-38-42.smt2                                                                        |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|n6857-prp-39-41.smt2                                                                        |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|n6870-prp-40-46.smt2                                                                        |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|n6873-prp-40-49.smt2                                                                        |  30.071s  |  30.071s  |   0.000s  | 0.0%|
|n6874-prp-40-50.smt2                                                                        |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|n6875-prp-41-42.smt2                                                                        |  30.057s  |  30.057s  |   0.000s  | 0.0%|
|n6878-prp-41-45.smt2                                                                        |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|n6879-prp-41-46.smt2                                                                        |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|n6886-prp-42-48.smt2                                                                        |  30.032s  |  30.032s  |   0.000s  | 0.0%|
|n6891-prp-43-46.smt2                                                                        |  30.051s  |  30.051s  |   0.000s  | 0.0%|
|n6893-prp-43-48.smt2                                                                        |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|n6894-prp-43-49.smt2                                                                        |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|n6895-prp-43-50.smt2                                                                        |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|n6897-prp-44-47.smt2                                                                        |  30.061s  |  30.061s  |   0.000s  | 0.0%|
|n6898-prp-44-48.smt2                                                                        |  30.066s  |  30.066s  |   0.000s  | 0.0%|
|n69-unbd-sage10.smt2                                                                        |  30.031s  |  30.031s  |   0.000s  | 0.0%|
|n6902-prp-45-45.smt2                                                                        |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|n6904-prp-45-47.smt2                                                                        |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|n6906-prp-45-49.smt2                                                                        |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|n6908-prp-46-46.smt2                                                                        |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|n6909-prp-46-48.smt2                                                                        |  30.040s  |  30.040s  |   0.000s  | 0.0%|
|n6910-prp-46-49.smt2                                                                        |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|n6911-prp-46-50.smt2                                                                        |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|n6912-prp-47-46.smt2                                                                        |  30.062s  |  30.062s  |   0.000s  | 0.0%|
|n6917-prp-48-46.smt2                                                                        |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|n6918-prp-48-47.smt2                                                                        |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|n6919-prp-48-48.smt2                                                                        |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|n6923-prp-49-47.smt2                                                                        |  30.063s  |  30.063s  |   0.000s  | 0.0%|
|n6931-prp-5-50.smt2                                                                         |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|n6933-prp-50-47.smt2                                                                        |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|n6934-prp-50-48.smt2                                                                        |  30.062s  |  30.062s  |   0.000s  | 0.0%|
|n6936-prp-50-50.smt2                                                                        |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|n6938-prp-51-47.smt2                                                                        |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|n6939-prp-51-48.smt2                                                                        |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|n6940-prp-51-49.smt2                                                                        |  30.057s  |  30.057s  |   0.000s  | 0.0%|
|n6941-prp-51-50.smt2                                                                        |  30.058s  |  30.058s  |   0.000s  | 0.0%|
|n6945-prp-52-50.smt2                                                                        |  30.065s  |  30.065s  |   0.000s  | 0.0%|
|n6947-prp-53-47.smt2                                                                        |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|n6949-prp-53-49.smt2                                                                        |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|n6952-prp-54-47.smt2                                                                        |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|n6953-prp-54-48.smt2                                                                        |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|n6956-prp-55-46.smt2                                                                        |  30.051s  |  30.051s  |   0.000s  | 0.0%|
|n6957-prp-55-47.smt2                                                                        |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|n6965-prp-57-48.smt2                                                                        |  30.063s  |  30.063s  |   0.000s  | 0.0%|
|n6968-prp-58-47.smt2                                                                        |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|n6970-prp-58-49.smt2                                                                        |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|n6971-prp-58-50.smt2                                                                        |  30.056s  |  30.056s  |   0.000s  | 0.0%|
|n6972-prp-59-48.smt2                                                                        |  30.064s  |  30.064s  |   0.000s  | 0.0%|
|n6975-prp-60-48.smt2                                                                        |  30.058s  |  30.058s  |   0.000s  | 0.0%|
|n6981-prp-62-50.smt2                                                                        |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|n6982-prp-63-50.smt2                                                                        |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|n6983-prp-7-46.smt2                                                                         |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|n6984-prp-7-47.smt2                                                                         |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|n6985-prp-7-48.smt2                                                                         |  30.034s  |  30.034s  |   0.000s  | 0.0%|
|n6987-prp-7-50.smt2                                                                         |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|n6991-prp-8-49.smt2                                                                         |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|n6995-prp-10-48.smt2                                                                        |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|n6996-prp-10-49.smt2                                                                        |  30.065s  |  30.065s  |   0.000s  | 0.0%|
|n6999-prp-11-47.smt2                                                                        |  30.076s  |  30.076s  |   0.000s  | 0.0%|
|n70-unbd-sage11.smt2                                                                        |  30.016s  |  30.016s  |   0.000s  | 0.0%|
|n7000-prp-11-48.smt2                                                                        |  30.071s  |  30.071s  |   0.000s  | 0.0%|
|n7001-prp-11-49.smt2                                                                        |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|n7003-prp-12-46.smt2                                                                        |  30.061s  |  30.061s  |   0.000s  | 0.0%|
|n7006-prp-12-49.smt2                                                                        |  30.083s  |  30.083s  |   0.000s  | 0.0%|
|n7011-prp-13-49.smt2                                                                        |  30.069s  |  30.069s  |   0.000s  | 0.0%|
|n7012-prp-13-50.smt2                                                                        |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|n7014-prp-5-47.smt2                                                                         |  30.064s  |  30.064s  |   0.000s  | 0.0%|
|n7016-prp-5-49.smt2                                                                         |  30.067s  |  30.067s  |   0.000s  | 0.0%|
|n7018-prp-6-46.smt2                                                                         |  30.065s  |  30.065s  |   0.000s  | 0.0%|
|n7020-prp-6-48.smt2                                                                         |  30.065s  |  30.065s  |   0.000s  | 0.0%|
|n7025-prp-7-48.smt2                                                                         |  30.067s  |  30.067s  |   0.000s  | 0.0%|
|n7026-prp-7-49.smt2                                                                         |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|n7083-prp-17-47.smt2                                                                        |  30.066s  |  30.066s  |   0.000s  | 0.0%|
|n7128-prp-25-48.smt2                                                                        |  30.067s  |  30.067s  |   0.000s  | 0.0%|
|n7129-prp-25-49.smt2                                                                        |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|n7130-prp-25-50.smt2                                                                        |  30.070s  |  30.070s  |   0.000s  | 0.0%|
|n7134-prp-26-50.smt2                                                                        |  30.076s  |  30.076s  |   0.000s  | 0.0%|
|n7138-prp-27-49.smt2                                                                        |  30.067s  |  30.067s  |   0.000s  | 0.0%|
|n7139-prp-27-50.smt2                                                                        |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|n7142-prp-28-48.smt2                                                                        |  30.066s  |  30.066s  |   0.000s  | 0.0%|
|n7148-prp-29-49.smt2                                                                        |  30.061s  |  30.061s  |   0.000s  | 0.0%|
|n7204-prp-39-50.smt2                                                                        |  30.077s  |  30.077s  |   0.000s  | 0.0%|
|n7219-prp-41-50.smt2                                                                        |  30.070s  |  30.070s  |   0.000s  | 0.0%|
|n7228-prp-43-49.smt2                                                                        |  30.076s  |  30.076s  |   0.000s  | 0.0%|
|n7269-prp-50-50.smt2                                                                        |  30.085s  |  30.085s  |   0.000s  | 0.0%|
|n7274-prp-51-50.smt2                                                                        |  30.083s  |  30.083s  |   0.000s  | 0.0%|
|n7279-prp-52-50.smt2                                                                        |  30.070s  |  30.070s  |   0.000s  | 0.0%|
|n7389-prp-0-48.smt2                                                                         |  30.078s  |  30.078s  |   0.000s  | 0.0%|
|n7393-prp-1-47.smt2                                                                         |  30.081s  |  30.081s  |   0.000s  | 0.0%|
|n7399-prp-10-48.smt2                                                                        |  30.062s  |  30.062s  |   0.000s  | 0.0%|
|n74-unbd-sage15.smt2                                                                        |  30.040s  |  30.040s  |   0.000s  | 0.0%|
|n7402-prp-11-46.smt2                                                                        |  30.091s  |  30.091s  |   0.000s  | 0.0%|
|n7403-prp-11-47.smt2                                                                        |  30.079s  |  30.079s  |   0.000s  | 0.0%|
|n7405-prp-11-49.smt2                                                                        |  30.089s  |  30.089s  |   0.000s  | 0.0%|
|n7410-prp-12-49.smt2                                                                        |  30.086s  |  30.086s  |   0.000s  | 0.0%|
|n7412-prp-13-46.smt2                                                                        |  30.082s  |  30.082s  |   0.000s  | 0.0%|
|n7427-prp-16-46.smt2                                                                        |  30.084s  |  30.084s  |   0.000s  | 0.0%|
|n7429-prp-16-48.smt2                                                                        |  30.079s  |  30.079s  |   0.000s  | 0.0%|
|n7430-prp-16-49.smt2                                                                        |  30.079s  |  30.079s  |   0.000s  | 0.0%|
|n7443-prp-19-47.smt2                                                                        |  30.084s  |  30.084s  |   0.000s  | 0.0%|
|n7444-prp-19-48.smt2                                                                        |  30.090s  |  30.090s  |   0.000s  | 0.0%|
|n7448-prp-2-47.smt2                                                                         |  30.084s  |  30.084s  |   0.000s  | 0.0%|
|n7450-prp-2-49.smt2                                                                         |  30.063s  |  30.063s  |   0.000s  | 0.0%|
|n7452-prp-20-46.smt2                                                                        |  30.070s  |  30.070s  |   0.000s  | 0.0%|
|n7453-prp-20-47.smt2                                                                        |  30.093s  |  30.093s  |   0.000s  | 0.0%|
|n7459-prp-21-48.smt2                                                                        |  30.082s  |  30.082s  |   0.000s  | 0.0%|
|n7463-prp-22-47.smt2                                                                        |  30.081s  |  30.081s  |   0.000s  | 0.0%|
|n7464-prp-22-48.smt2                                                                        |  30.088s  |  30.088s  |   0.000s  | 0.0%|
|n7472-prp-24-46.smt2                                                                        |  30.083s  |  30.083s  |   0.000s  | 0.0%|
|n7487-prp-27-46.smt2                                                                        |  30.073s  |  30.073s  |   0.000s  | 0.0%|
|n7489-prp-27-48.smt2                                                                        |  30.083s  |  30.083s  |   0.000s  | 0.0%|
|n7492-prp-28-46.smt2                                                                        |  30.078s  |  30.078s  |   0.000s  | 0.0%|
|n7498-prp-29-47.smt2                                                                        |  30.086s  |  30.086s  |   0.000s  | 0.0%|
|n7499-prp-29-48.smt2                                                                        |  30.087s  |  30.087s  |   0.000s  | 0.0%|
|n75-unbd-sage16.smt2                                                                        |  30.022s  |  30.022s  |   0.000s  | 0.0%|
|n7502-prp-3-46.smt2                                                                         |  30.085s  |  30.085s  |   0.000s  | 0.0%|
|n7503-prp-3-47.smt2                                                                         |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|n7507-prp-30-46.smt2                                                                        |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|n7508-prp-30-47.smt2                                                                        |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|n7510-prp-30-49.smt2                                                                        |  30.088s  |  30.088s  |   0.000s  | 0.0%|
|n7514-prp-31-48.smt2                                                                        |  30.088s  |  30.088s  |   0.000s  | 0.0%|
|n7517-prp-32-46.smt2                                                                        |  30.066s  |  30.066s  |   0.000s  | 0.0%|
|n7522-prp-33-46.smt2                                                                        |  30.071s  |  30.071s  |   0.000s  | 0.0%|
|n7523-prp-33-47.smt2                                                                        |  30.071s  |  30.071s  |   0.000s  | 0.0%|
|n7525-prp-33-49.smt2                                                                        |  30.061s  |  30.061s  |   0.000s  | 0.0%|
|n7527-prp-34-46.smt2                                                                        |  30.057s  |  30.057s  |   0.000s  | 0.0%|
|n7528-prp-34-47.smt2                                                                        |  30.076s  |  30.076s  |   0.000s  | 0.0%|
|n7529-prp-34-48.smt2                                                                        |  30.080s  |  30.080s  |   0.000s  | 0.0%|
|n7533-prp-35-47.smt2                                                                        |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|n7534-prp-35-48.smt2                                                                        |  30.086s  |  30.086s  |   0.000s  | 0.0%|
|n7540-prp-36-49.smt2                                                                        |  30.083s  |  30.083s  |   0.000s  | 0.0%|
|n7544-prp-37-48.smt2                                                                        |  30.071s  |  30.071s  |   0.000s  | 0.0%|
|n7545-prp-37-49.smt2                                                                        |  30.062s  |  30.062s  |   0.000s  | 0.0%|
|n7549-prp-38-48.smt2                                                                        |  30.094s  |  30.094s  |   0.000s  | 0.0%|
|n7550-prp-38-49.smt2                                                                        |  30.083s  |  30.083s  |   0.000s  | 0.0%|
|n7555-prp-39-49.smt2                                                                        |  30.091s  |  30.091s  |   0.000s  | 0.0%|
|n7562-prp-40-46.smt2                                                                        |  30.073s  |  30.073s  |   0.000s  | 0.0%|
|n7563-prp-40-47.smt2                                                                        |  30.081s  |  30.081s  |   0.000s  | 0.0%|
|n7579-prp-43-48.smt2                                                                        |  30.076s  |  30.076s  |   0.000s  | 0.0%|
|n7580-prp-43-49.smt2                                                                        |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|n7583-prp-44-47.smt2                                                                        |  30.068s  |  30.068s  |   0.000s  | 0.0%|
|n7584-prp-44-48.smt2                                                                        |  30.083s  |  30.083s  |   0.000s  | 0.0%|
|n7585-prp-44-49.smt2                                                                        |  30.085s  |  30.085s  |   0.000s  | 0.0%|
|n7587-prp-45-46.smt2                                                                        |  30.080s  |  30.080s  |   0.000s  | 0.0%|
|n7588-prp-45-47.smt2                                                                        |  30.078s  |  30.078s  |   0.000s  | 0.0%|
|n7592-prp-46-46.smt2                                                                        |  30.078s  |  30.078s  |   0.000s  | 0.0%|
|n7594-prp-46-48.smt2                                                                        |  30.079s  |  30.079s  |   0.000s  | 0.0%|
|n76-unbd-sage17.smt2                                                                        |  30.034s  |  30.034s  |   0.000s  | 0.0%|
|n7603-prp-48-47.smt2                                                                        |  30.073s  |  30.073s  |   0.000s  | 0.0%|
|n7605-prp-48-49.smt2                                                                        |  30.076s  |  30.076s  |   0.000s  | 0.0%|
|n7609-prp-49-48.smt2                                                                        |  30.082s  |  30.082s  |   0.000s  | 0.0%|
|n7618-prp-50-47.smt2                                                                        |  30.098s  |  30.098s  |   0.000s  | 0.0%|
|n7619-prp-50-48.smt2                                                                        |  30.084s  |  30.084s  |   0.000s  | 0.0%|
|n7637-prp-8-47.smt2                                                                         |  30.073s  |  30.073s  |   0.000s  | 0.0%|
|n7641-prp-9-46.smt2                                                                         |  30.077s  |  30.077s  |   0.000s  | 0.0%|
|n7642-prp-9-47.smt2                                                                         |  30.073s  |  30.073s  |   0.000s  | 0.0%|
|n7643-prp-9-48.smt2                                                                         |  30.085s  |  30.085s  |   0.000s  | 0.0%|
|n77-unbd-sage18.smt2                                                                        |  30.040s  |  30.040s  |   0.000s  | 0.0%|
|n7778-prp-0-48.smt2                                                                         |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|n78-unbd-sage19.smt2                                                                        |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|n7822-prp-37-47.smt2                                                                        |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|n79-unbd-sage2.smt2                                                                         |  30.033s  |  30.033s  |   0.000s  | 0.0%|
|n7958-prp-0-48.smt2                                                                         |  30.063s  |  30.063s  |   0.000s  | 0.0%|
|n7959-prp-0-49.smt2                                                                         |  30.065s  |  30.065s  |   0.000s  | 0.0%|
|n7961-prp-1-46.smt2                                                                         |  30.058s  |  30.058s  |   0.000s  | 0.0%|
|n7970-prp-10-50.smt2                                                                        |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|n7971-prp-11-46.smt2                                                                        |  30.052s  |  30.052s  |   0.000s  | 0.0%|
|n7977-prp-12-47.smt2                                                                        |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|n7979-prp-12-49.smt2                                                                        |  30.068s  |  30.068s  |   0.000s  | 0.0%|
|n7982-prp-13-47.smt2                                                                        |  30.075s  |  30.075s  |   0.000s  | 0.0%|
|n7983-prp-13-48.smt2                                                                        |  30.070s  |  30.070s  |   0.000s  | 0.0%|
|n7984-prp-13-49.smt2                                                                        |  30.072s  |  30.072s  |   0.000s  | 0.0%|
|n7987-prp-14-47.smt2                                                                        |  30.065s  |  30.065s  |   0.000s  | 0.0%|
|n7990-prp-14-50.smt2                                                                        |  30.068s  |  30.068s  |   0.000s  | 0.0%|
|n7993-prp-15-48.smt2                                                                        |  30.069s  |  30.069s  |   0.000s  | 0.0%|
|n7994-prp-15-49.smt2                                                                        |  30.075s  |  30.075s  |   0.000s  | 0.0%|
|n8000-prp-16-50.smt2                                                                        |  30.073s  |  30.073s  |   0.000s  | 0.0%|
|n8001-prp-17-46.smt2                                                                        |  30.064s  |  30.064s  |   0.000s  | 0.0%|
|n8003-prp-17-48.smt2                                                                        |  30.062s  |  30.062s  |   0.000s  | 0.0%|
|n8005-prp-17-50.smt2                                                                        |  30.077s  |  30.077s  |   0.000s  | 0.0%|
|n8010-prp-18-50.smt2                                                                        |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|n8015-prp-19-50.smt2                                                                        |  30.081s  |  30.081s  |   0.000s  | 0.0%|
|n8019-prp-2-49.smt2                                                                         |  30.057s  |  30.057s  |   0.000s  | 0.0%|
|n8023-prp-20-48.smt2                                                                        |  30.063s  |  30.063s  |   0.000s  | 0.0%|
|n8025-prp-20-50.smt2                                                                        |  30.075s  |  30.075s  |   0.000s  | 0.0%|
|n8026-prp-21-46.smt2                                                                        |  30.060s  |  30.060s  |   0.000s  | 0.0%|
|n8028-prp-21-48.smt2                                                                        |  30.078s  |  30.078s  |   0.000s  | 0.0%|
|n8029-prp-21-49.smt2                                                                        |  30.065s  |  30.065s  |   0.000s  | 0.0%|
|n8030-prp-21-50.smt2                                                                        |  30.072s  |  30.072s  |   0.000s  | 0.0%|
|n8033-prp-22-48.smt2                                                                        |  30.065s  |  30.065s  |   0.000s  | 0.0%|
|n8037-prp-23-47.smt2                                                                        |  30.061s  |  30.061s  |   0.000s  | 0.0%|
|n8040-prp-23-50.smt2                                                                        |  30.078s  |  30.078s  |   0.000s  | 0.0%|
|n8041-prp-24-46.smt2                                                                        |  30.068s  |  30.068s  |   0.000s  | 0.0%|
|n8042-prp-24-47.smt2                                                                        |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|n8047-prp-3-47.smt2                                                                         |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|n8049-prp-3-49.smt2                                                                         |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|n8050-prp-3-50.smt2                                                                         |  30.069s  |  30.069s  |   0.000s  | 0.0%|
|n8054-prp-4-49.smt2                                                                         |  30.051s  |  30.051s  |   0.000s  | 0.0%|
|n8055-prp-4-50.smt2                                                                         |  30.074s  |  30.074s  |   0.000s  | 0.0%|
|n8056-prp-5-46.smt2                                                                         |  30.049s  |  30.049s  |   0.000s  | 0.0%|
|n8059-prp-5-49.smt2                                                                         |  30.067s  |  30.067s  |   0.000s  | 0.0%|
|n8064-prp-6-49.smt2                                                                         |  30.062s  |  30.062s  |   0.000s  | 0.0%|
|n8070-prp-7-50.smt2                                                                         |  30.067s  |  30.067s  |   0.000s  | 0.0%|
|n8072-prp-8-47.smt2                                                                         |  30.067s  |  30.067s  |   0.000s  | 0.0%|
|n8077-prp-9-47.smt2                                                                         |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|n8079-prp-9-49.smt2                                                                         |  30.058s  |  30.058s  |   0.000s  | 0.0%|
|n8080-prp-9-50.smt2                                                                         |  30.068s  |  30.068s  |   0.000s  | 0.0%|
|n82-unbd-sage22.smt2                                                                        |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|n8214-ring_2exp10_6vars_5ite_unsat.smt2                                                     |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|n8220-ring_2exp10_7vars_5ite_unsat.smt2                                                     |  30.040s  |  30.040s  |   0.000s  | 0.0%|
|n8226-ring_2exp10_8vars_4ite_unsat.smt2                                                     |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|n8227-ring_2exp10_8vars_5ite_unsat.smt2                                                     |  30.031s  |  30.031s  |   0.000s  | 0.0%|
|n8228-ring_2exp10_8vars_6ite_unsat.smt2                                                     |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|n8234-ring_2exp10_9vars_4ite_unsat.smt2                                                     |  30.019s  |  30.019s  |   0.000s  | 0.0%|
|n8235-ring_2exp10_9vars_5ite_unsat.smt2                                                     |  30.019s  |  30.019s  |   0.000s  | 0.0%|
|n8237-ring_2exp10_9vars_7ite_unsat.smt2                                                     |  30.046s  |  30.046s  |   0.000s  | 0.0%|
|n8262-ring_2exp12_7vars_5ite_unsat.smt2                                                     |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|n8270-ring_2exp12_8vars_6ite_unsat.smt2                                                     |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|n8271-ring_2exp12_8vars_7ite_unsat.smt2                                                     |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|n8310-ring_2exp14_8vars_4ite_unsat.smt2                                                     |  30.035s  |  30.035s  |   0.000s  | 0.0%|
|n8311-ring_2exp14_8vars_5ite_unsat.smt2                                                     |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|n8312-ring_2exp14_8vars_6ite_unsat.smt2                                                     |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|n8318-ring_2exp14_9vars_4ite_unsat.smt2                                                     |  30.044s  |  30.044s  |   0.000s  | 0.0%|
|n8319-ring_2exp14_9vars_5ite_unsat.smt2                                                     |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|n8322-ring_2exp14_9vars_8ite_unsat.smt2                                                     |  30.034s  |  30.034s  |   0.000s  | 0.0%|
|n8340-ring_2exp16_6vars_5ite_unsat.smt2                                                     |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|n8352-ring_2exp16_8vars_4ite_unsat.smt2                                                     |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|n8354-ring_2exp16_8vars_6ite_unsat.smt2                                                     |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|n8355-ring_2exp16_8vars_7ite_unsat.smt2                                                     |  30.019s  |  30.019s  |   0.000s  | 0.0%|
|n8360-ring_2exp16_9vars_4ite_unsat.smt2                                                     |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|n8361-ring_2exp16_9vars_5ite_unsat.smt2                                                     |  30.022s  |  30.022s  |   0.000s  | 0.0%|
|n8364-ring_2exp16_9vars_8ite_unsat.smt2                                                     |  30.016s  |  30.016s  |   0.000s  | 0.0%|
|n8424-ring_2exp6_6vars_5ite_unsat.smt2                                                      |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|n8431-ring_2exp6_7vars_6ite_unsat.smt2                                                      |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|n8438-ring_2exp6_8vars_6ite_unsat.smt2                                                      |  30.034s  |  30.034s  |   0.000s  | 0.0%|
|n8439-ring_2exp6_8vars_7ite_unsat.smt2                                                      |  30.029s  |  30.029s  |   0.000s  | 0.0%|
|n8446-ring_2exp6_9vars_6ite_unsat.smt2                                                      |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|n8447-ring_2exp6_9vars_7ite_unsat.smt2                                                      |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|n8472-ring_2exp8_7vars_5ite_unsat.smt2                                                      |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|n8473-ring_2exp8_7vars_6ite_unsat.smt2                                                      |  30.037s  |  30.037s  |   0.000s  | 0.0%|
|n8486-ring_2exp8_9vars_4ite_unsat.smt2                                                      |  30.040s  |  30.040s  |   0.000s  | 0.0%|
|n8488-ring_2exp8_9vars_6ite_unsat.smt2                                                      |  30.019s  |  30.019s  |   0.000s  | 0.0%|
|n8489-ring_2exp8_9vars_7ite_unsat.smt2                                                      |  30.043s  |  30.043s  |   0.000s  | 0.0%|
|n89-unbd-sage7.smt2                                                                         |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|n90-unbd-sage8.smt2                                                                         |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|n92-unbd-sage0.smt2                                                                         |  30.039s  |  30.039s  |   0.000s  | 0.0%|
|n93-unbd-sage1.smt2                                                                         |  30.042s  |  30.042s  |   0.000s  | 0.0%|
|n95-unbd-sage11.smt2                                                                        |  30.033s  |  30.033s  |   0.000s  | 0.0%|
|prp-0-197.smt2                                                                              |  30.075s  |  30.075s  |   0.000s  | 0.0%|
|prp-22-41.smt2                                                                              |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|prp-23-39.smt2                                                                              |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|prp-23-41.smt2                                                                              |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|prp-39-44.smt2                                                                              |  30.038s  |  30.038s  |   0.000s  | 0.0%|
|prp-39-45.smt2                                                                              |  30.071s  |  30.071s  |   0.000s  | 0.0%|
|prp-40-40.smt2                                                                              |  30.055s  |  30.055s  |   0.000s  | 0.0%|
|prp-40-42.smt2                                                                              |  30.048s  |  30.048s  |   0.000s  | 0.0%|
|prp-40-43.smt2                                                                              |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|prp-42-44.smt2                                                                              |  30.059s  |  30.059s  |   0.000s  | 0.0%|
|prp-45-41.smt2                                                                              |  30.062s  |  30.062s  |   0.000s  | 0.0%|
|prp-46-45.smt2                                                                              |  30.050s  |  30.050s  |   0.000s  | 0.0%|
|prp-47-42.smt2                                                                              |  30.034s  |  30.034s  |   0.000s  | 0.0%|
|prp-47-44.smt2                                                                              |  30.051s  |  30.051s  |   0.000s  | 0.0%|
|prp-49-43.smt2                                                                              |  30.054s  |  30.054s  |   0.000s  | 0.0%|
|prp-49-44.smt2                                                                              |  30.045s  |  30.045s  |   0.000s  | 0.0%|
|prp-50-43.smt2                                                                              |  30.053s  |  30.053s  |   0.000s  | 0.0%|
|prp-50-44.smt2                                                                              |  30.064s  |  30.064s  |   0.000s  | 0.0%|
|v20_problem__014.smt2.slack.smt2                                                            |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|v25_problem_2__028.smt2.slack.smt2                                                          |  30.037s  |  30.037s  |   0.000s  | 0.0%|
|v25_problem__033.smt2.slack.smt2                                                            |  30.034s  |  30.034s  |   0.000s  | 0.0%|
|v30_problem_2__029.smt2.slack.smt2                                                          |  30.034s  |  30.034s  |   0.000s  | 0.0%|
|v30_problem__033.smt2.slack.smt2                                                            |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|v40_problem_2__018.smt2.slack.smt2                                                          |  30.041s  |  30.041s  |   0.000s  | 0.0%|
|v40_problem_2__031.smt2.slack.smt2                                                          |  30.036s  |  30.036s  |   0.000s  | 0.0%|
|v45_problem_2__014.smt2.slack.smt2                                                          |  30.034s  |  30.034s  |   0.000s  | 0.0%|
</details>
