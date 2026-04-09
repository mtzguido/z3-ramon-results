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
Job tag: smt_qfrdl-sequential
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 477a1d817da44f7615fa53a10b4bd03d2cc84e48
Z3 branch: master
Z3 options: "-T:60 smt.threads=1 tactic.default_tactic=smt smt.auto_config=false"
Z3 inputs: inputs/QF_RDL
Z3 commit message: Add mod-factor-propagation lemma to NLA divisions solver (#9235)

When a monic x*y has a factor x with mod(x, p) = 0 (fixed), propagate
mod(x*y, p) = 0. This enables Z3 to prove divisibility properties like
x mod p = 0 => (x*y) mod p = 0, which previously timed out even for
p = 2. The lemma fires in the NLA divisions check and allows Gröbner
basis and LIA to subsequently derive distributivity of div over addition.

Extends division tuples from (q, x, y) to (q, x, y, r) to track the
mod lpvar. Also registers bounded divisions from the mod internalization
path in theory_lra, not just the idiv path.

Co-authored-by: Claude Opus 4.6 (1M context) <noreply@anthropic.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt_qfrdl-sequential
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 477a1d817da44f7615fa53a10b4bd03d2cc84e48
Z3 branch: master
Z3 options: "-T:60 smt.threads=1 tactic.default_tactic=smt smt.auto_config=false"
Z3 inputs: inputs/QF_RDL
Z3 commit message: Add mod-factor-propagation lemma to NLA divisions solver (#9235)

When a monic x*y has a factor x with mod(x, p) = 0 (fixed), propagate
mod(x*y, p) = 0. This enables Z3 to prove divisibility properties like
x mod p = 0 => (x*y) mod p = 0, which previously timed out even for
p = 2. The lemma fires in the NLA divisions check and allows Gröbner
basis and LIA to subsequently derive distributivity of div over addition.

Extends division tuples from (q, x, y) to (q, x, y, r) to track the
mod lpvar. Also registers bounded divisions from the mod internalization
path in theory_lra, not just the idiv path.

Co-authored-by: Claude Opus 4.6 (1M context) <noreply@anthropic.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.097s  |   0.097s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.097s  |   0.097s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.097s  |   0.097s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.097s  |   0.097s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scheduling/swv13_3200.smt2                                                                 |  60.127s |284.0MiB|
|scheduling/swv13_3000.smt2                                                                 |  60.124s |279.0MiB|
|skdmxa2/skdmxa-3x3-19.base.cvc.smt2                                                        |  60.119s |717.0MiB|
|scheduling/yn4_950.smt2                                                                    |  60.116s |102.0MiB|
|scheduling/abz7_700.smt2                                                                   |  60.115s |89.424MiB|
|scheduling/swv12_3050.smt2                                                                 |  60.114s |281.0MiB|
|scheduling/swv14_2895.smt2                                                                 |  60.112s |272.0MiB|
|scheduling/swv11_2988.smt2                                                                 |  60.110s |291.0MiB|
|scheduling/yn1_950.smt2                                                                    |  60.104s |108.0MiB|
|scheduling/yn1_887.smt2                                                                    |  60.101s |102.0MiB|
|scheduling/orb01_1059.smt2                                                                 |  60.100s |31.624MiB|
|scheduling/yn3_950.smt2                                                                    |  60.099s |103.0MiB|
|scheduling/orb06_1000.smt2                                                                 |  60.098s |32.908MiB|
|scheduling/swv12_2900.smt2                                                                 |  60.097s |283.0MiB|
|scheduling/yn3_860.smt2                                                                    |  60.097s |97.0MiB|
|scheduling/swv14_2885.smt2                                                                 |  60.096s |278.0MiB|
|scheduling/yn4_919.smt2                                                                    |  60.095s |102.0MiB|
|scheduling/yn2_890.smt2                                                                    |  60.095s |102.0MiB|
|scheduling/abz7_600.smt2                                                                   |  60.093s |78.108MiB|
|scheduling/yn1_850.smt2                                                                    |  60.092s |97.992MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scheduling/swv13_3200.smt2                                                                 |  60.127s |284.0MiB|
|scheduling/swv13_3000.smt2                                                                 |  60.124s |279.0MiB|
|skdmxa2/skdmxa-3x3-19.base.cvc.smt2                                                        |  60.119s |717.0MiB|
|scheduling/yn4_950.smt2                                                                    |  60.116s |102.0MiB|
|scheduling/abz7_700.smt2                                                                   |  60.115s |89.424MiB|
|scheduling/swv12_3050.smt2                                                                 |  60.114s |281.0MiB|
|scheduling/swv14_2895.smt2                                                                 |  60.112s |272.0MiB|
|scheduling/swv11_2988.smt2                                                                 |  60.110s |291.0MiB|
|scheduling/yn1_950.smt2                                                                    |  60.104s |108.0MiB|
|scheduling/yn1_887.smt2                                                                    |  60.101s |102.0MiB|
|scheduling/orb01_1059.smt2                                                                 |  60.100s |31.624MiB|
|scheduling/yn3_950.smt2                                                                    |  60.099s |103.0MiB|
|scheduling/orb06_1000.smt2                                                                 |  60.098s |32.908MiB|
|scheduling/swv12_2900.smt2                                                                 |  60.097s |283.0MiB|
|scheduling/yn3_860.smt2                                                                    |  60.097s |97.0MiB|
|scheduling/swv14_2885.smt2                                                                 |  60.096s |278.0MiB|
|scheduling/yn4_919.smt2                                                                    |  60.095s |102.0MiB|
|scheduling/yn2_890.smt2                                                                    |  60.095s |102.0MiB|
|scheduling/abz7_600.smt2                                                                   |  60.093s |78.108MiB|
|scheduling/yn1_850.smt2                                                                    |  60.092s |97.992MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |20.816MiB|20.816MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |20.952MiB|20.952MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |21.224MiB|21.224MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |21.732MiB|21.732MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |22.388MiB|22.388MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |22.444MiB|22.444MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |22.696MiB|22.696MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |22.744MiB|22.744MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |23.252MiB|23.252MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |23.588MiB|23.588MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |23.828MiB|23.828MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |24.112MiB|24.112MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |24.62MiB|24.62MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |24.748MiB|24.748MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |25.22MiB|25.22MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |25.564MiB|25.564MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |25.692MiB|25.692MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |26.072MiB|26.072MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |26.796MiB|26.796MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |26.832MiB|26.832MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |20.816MiB|20.816MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |20.952MiB|20.952MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |21.224MiB|21.224MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |21.732MiB|21.732MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |22.388MiB|22.388MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |22.444MiB|22.444MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |22.696MiB|22.696MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |22.744MiB|22.744MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |23.252MiB|23.252MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |23.588MiB|23.588MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |23.828MiB|23.828MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |24.112MiB|24.112MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |24.62MiB|24.62MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |24.748MiB|24.748MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |25.22MiB|25.22MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |25.564MiB|25.564MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |25.692MiB|25.692MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |26.072MiB|26.072MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |26.796MiB|26.796MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |26.832MiB|26.832MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |20.816MiB|20.816MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |20.952MiB|20.952MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |21.224MiB|21.224MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |21.732MiB|21.732MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |22.388MiB|22.388MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |22.444MiB|22.444MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |22.696MiB|22.696MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |22.744MiB|22.744MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |23.252MiB|23.252MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |23.588MiB|23.588MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |23.828MiB|23.828MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |24.112MiB|24.112MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |24.62MiB|24.62MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |24.748MiB|24.748MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |25.22MiB|25.22MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |25.564MiB|25.564MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |25.692MiB|25.692MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |26.072MiB|26.072MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |26.796MiB|26.796MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |26.832MiB|26.832MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |20.816MiB|20.816MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |20.952MiB|20.952MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |21.224MiB|21.224MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |21.732MiB|21.732MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |22.388MiB|22.388MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |22.444MiB|22.444MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |22.696MiB|22.696MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |22.744MiB|22.744MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |23.252MiB|23.252MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |23.588MiB|23.588MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |23.828MiB|23.828MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |24.112MiB|24.112MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |24.62MiB|24.62MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |24.748MiB|24.748MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |25.22MiB|25.22MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |25.564MiB|25.564MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |25.692MiB|25.692MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |26.072MiB|26.072MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |26.796MiB|26.796MiB|0B| 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |26.832MiB|26.832MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|skdmxa2/skdmxa-3x3-19.base.cvc.smt2                                                        |  60.119s |717.0MiB|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                        |  60.087s |628.0MiB|
|skdmxa2/skdmxa-3x3-18.base.cvc.smt2                                                        |  60.063s |506.0MiB|
|skdmxa2/skdmxa-3x3-17.base.cvc.smt2                                                        |  60.081s |480.0MiB|
|skdmxa2/skdmxa-3x3-20.induction.cvc.smt2                                                   |  60.061s |419.0MiB|
|skdmxa2/skdmxa-3x3-15.base.cvc.smt2                                                        |  60.057s |413.0MiB|
|skdmxa2/skdmxa-3x3-19.induction.cvc.smt2                                                   |  60.070s |409.0MiB|
|skdmxa2/skdmxa-3x3-16.induction.cvc.smt2                                                   |  51.768s |394.0MiB|
|skdmxa2/skdmxa-3x3-17.induction.cvc.smt2                                                   |  45.723s |375.0MiB|
|skdmxa2/skdmxa-3x3-16.base.cvc.smt2                                                        |  60.049s |347.0MiB|
|skdmxa2/skdmxa-3x3-14.base.cvc.smt2                                                        |  60.071s |345.0MiB|
|skdmxa2/skdmxa-3x3-14.induction.cvc.smt2                                                   |  43.763s |334.0MiB|
|skdmxa2/skdmxa-3x3-18.induction.cvc.smt2                                                   |  60.052s |326.0MiB|
|skdmxa2/skdmxa-3x3-13.base.cvc.smt2                                                        |  60.047s |302.0MiB|
|scheduling/swv11_2988.smt2                                                                 |  60.110s |291.0MiB|
|scheduling/swv12_2990.smt2                                                                 |  60.085s |286.0MiB|
|scheduling/swv13_3200.smt2                                                                 |  60.127s |284.0MiB|
|scheduling/swv12_2900.smt2                                                                 |  60.097s |283.0MiB|
|scheduling/swv14_2905.smt2                                                                 |  60.069s |282.0MiB|
|scheduling/swv12_3050.smt2                                                                 |  60.114s |281.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|skdmxa2/skdmxa-3x3-19.base.cvc.smt2                                                        |  60.119s |717.0MiB|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                        |  60.087s |628.0MiB|
|skdmxa2/skdmxa-3x3-18.base.cvc.smt2                                                        |  60.063s |506.0MiB|
|skdmxa2/skdmxa-3x3-17.base.cvc.smt2                                                        |  60.081s |480.0MiB|
|skdmxa2/skdmxa-3x3-20.induction.cvc.smt2                                                   |  60.061s |419.0MiB|
|skdmxa2/skdmxa-3x3-15.base.cvc.smt2                                                        |  60.057s |413.0MiB|
|skdmxa2/skdmxa-3x3-19.induction.cvc.smt2                                                   |  60.070s |409.0MiB|
|skdmxa2/skdmxa-3x3-16.induction.cvc.smt2                                                   |  51.768s |394.0MiB|
|skdmxa2/skdmxa-3x3-17.induction.cvc.smt2                                                   |  45.723s |375.0MiB|
|skdmxa2/skdmxa-3x3-16.base.cvc.smt2                                                        |  60.049s |347.0MiB|
|skdmxa2/skdmxa-3x3-14.base.cvc.smt2                                                        |  60.071s |345.0MiB|
|skdmxa2/skdmxa-3x3-14.induction.cvc.smt2                                                   |  43.763s |334.0MiB|
|skdmxa2/skdmxa-3x3-18.induction.cvc.smt2                                                   |  60.052s |326.0MiB|
|skdmxa2/skdmxa-3x3-13.base.cvc.smt2                                                        |  60.047s |302.0MiB|
|scheduling/swv11_2988.smt2                                                                 |  60.110s |291.0MiB|
|scheduling/swv12_2990.smt2                                                                 |  60.085s |286.0MiB|
|scheduling/swv13_3200.smt2                                                                 |  60.127s |284.0MiB|
|scheduling/swv12_2900.smt2                                                                 |  60.097s |283.0MiB|
|scheduling/swv14_2905.smt2                                                                 |  60.069s |282.0MiB|
|scheduling/swv12_3050.smt2                                                                 |  60.114s |281.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|SMT-Temporal-Planning-Benchmarks/cooking01.smt2                                             |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking02.smt2                                             |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking03.smt2                                             |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking04.smt2                                             |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking05.smt2                                             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking06.smt2                                             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking07.smt2                                             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking08.smt2                                             |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking09.smt2                                             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking10.smt2                                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking11.smt2                                             |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking12.smt2                                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking13.smt2                                             |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking14.smt2                                             |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking15.smt2                                             |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking16.smt2                                             |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking17.smt2                                             |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking18.smt2                                             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking19.smt2                                             |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking20.smt2                                             |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking21.smt2                                             |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/cooking22.smt2                                             |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-2.smt2                                         |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-3.smt2                                         |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-4.smt2                                         |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-5.smt2                                         |   0.293s  |   0.293s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-6.smt2                                         |   0.663s  |   0.663s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-depth-7.smt2                                         |   1.113s  |   1.113s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-matrix1x1.pddl.smt2                                  |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-matrix2x2.pddl.smt2                                  |   1.510s  |   1.510s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-1.smt2                                         |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-2.smt2                                         |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-3.smt2                                         |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-4.smt2                                         |   0.371s  |   0.371s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-5.smt2                                         |   0.900s  |   0.900s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tempo-width-6.smt2                                         |   2.564s  |   2.564s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-03.smt2                                      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-04.smt2                                      |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-05.smt2                                      |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-06.smt2                                      |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-07.smt2                                      |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-08.smt2                                      |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-09.smt2                                      |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-10.smt2                                      |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-20.smt2                                      |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-30.smt2                                      |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-40.smt2                                      |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-60.smt2                                      |   0.324s  |   0.324s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-70.smt2                                      |   0.358s  |   0.358s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-80.smt2                                      |   0.423s  |   0.423s  |   0.000s  | 0.0%|
|SMT-Temporal-Planning-Benchmarks/tms-2-3-light-90.smt2                                      |   0.477s  |   0.477s  |   0.000s  | 0.0%|
|check/bignum_rdl1.smt2                                                                      |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|check/bignum_rdl2.smt2                                                                      |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-1.smt2                                                                   |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-10.smt2                                                                  |   0.548s  |   0.548s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-11.smt2                                                                  |   1.345s  |   1.345s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-12.smt2                                                                  |   2.264s  |   2.264s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-13.smt2                                                                  |   2.965s  |   2.965s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-14.smt2                                                                  |   3.110s  |   3.110s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-15.smt2                                                                  |   3.442s  |   3.442s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-16.smt2                                                                  |   3.896s  |   3.896s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-17.smt2                                                                  |   8.507s  |   8.507s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-18.smt2                                                                  |   8.029s  |   8.029s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-19.smt2                                                                  |  15.595s  |  15.595s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-2.smt2                                                                   |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-20.smt2                                                                  |  27.549s  |  27.549s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-3.smt2                                                                   |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-4.smt2                                                                   |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-5.smt2                                                                   |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-6.smt2                                                                   |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-7.smt2                                                                   |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-8.smt2                                                                   |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|sal/fischer3-mutex-9.smt2                                                                   |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-1.smt2                                                                   |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-10.smt2                                                                  |   8.741s  |   8.741s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-11.smt2                                                                  |  16.009s  |  16.009s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-12.smt2                                                                  |  59.848s  |  59.848s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-13.smt2                                                                  |  60.041s  |  60.041s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-14.smt2                                                                  |  60.034s  |  60.034s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-15.smt2                                                                  |  60.040s  |  60.040s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-16.smt2                                                                  |  60.037s  |  60.037s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-17.smt2                                                                  |  60.011s  |  60.011s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-18.smt2                                                                  |  60.014s  |  60.014s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-19.smt2                                                                  |  60.012s  |  60.012s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-2.smt2                                                                   |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-20.smt2                                                                  |  60.042s  |  60.042s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-3.smt2                                                                   |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-4.smt2                                                                   |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-5.smt2                                                                   |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-6.smt2                                                                   |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-7.smt2                                                                   |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-8.smt2                                                                   |   0.414s  |   0.414s  |   0.000s  | 0.0%|
|sal/fischer6-mutex-9.smt2                                                                   |   2.508s  |   2.508s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-1.smt2                                                                   |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-10.smt2                                                                  |  52.238s  |  52.238s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-11.smt2                                                                  |  60.016s  |  60.016s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-12.smt2                                                                  |  60.013s  |  60.013s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-13.smt2                                                                  |  60.018s  |  60.018s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-14.smt2                                                                  |  60.032s  |  60.032s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-15.smt2                                                                  |  60.016s  |  60.016s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-16.smt2                                                                  |  60.038s  |  60.038s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-17.smt2                                                                  |  60.016s  |  60.016s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-18.smt2                                                                  |  60.016s  |  60.016s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-19.smt2                                                                  |  60.034s  |  60.034s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-2.smt2                                                                   |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-20.smt2                                                                  |  60.034s  |  60.034s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-3.smt2                                                                   |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-4.smt2                                                                   |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-5.smt2                                                                   |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-6.smt2                                                                   |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-7.smt2                                                                   |   0.316s  |   0.316s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-8.smt2                                                                   |   1.018s  |   1.018s  |   0.000s  | 0.0%|
|sal/fischer9-mutex-9.smt2                                                                   |   8.805s  |   8.805s  |   0.000s  | 0.0%|
|scheduling/abz5_1000.smt2                                                                   |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|scheduling/abz5_1200.smt2                                                                   |   5.049s  |   5.049s  |   0.000s  | 0.0%|
|scheduling/abz5_1234.smt2                                                                   |   8.355s  |   8.355s  |   0.000s  | 0.0%|
|scheduling/abz5_1300.smt2                                                                   |   0.770s  |   0.770s  |   0.000s  | 0.0%|
|scheduling/abz5_1400.smt2                                                                   |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|scheduling/abz6_1000.smt2                                                                   |   0.472s  |   0.472s  |   0.000s  | 0.0%|
|scheduling/abz6_1100.smt2                                                                   |   0.308s  |   0.308s  |   0.000s  | 0.0%|
|scheduling/abz6_800.smt2                                                                    |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|scheduling/abz6_900.smt2                                                                    |   0.450s  |   0.450s  |   0.000s  | 0.0%|
|scheduling/abz6_943.smt2                                                                    |   2.416s  |   2.416s  |   0.000s  | 0.0%|
|scheduling/abz7_500.smt2                                                                    |   2.689s  |   2.689s  |   0.000s  | 0.0%|
|scheduling/abz7_600.smt2                                                                    |  60.093s  |  60.093s  |   0.000s  | 0.0%|
|scheduling/abz7_667.smt2                                                                    |  60.084s  |  60.084s  |   0.000s  | 0.0%|
|scheduling/abz7_670.smt2                                                                    |  60.073s  |  60.073s  |   0.000s  | 0.0%|
|scheduling/abz7_691.smt2                                                                    |  60.049s  |  60.049s  |   0.000s  | 0.0%|
|scheduling/abz7_700.smt2                                                                    |  60.115s  |  60.115s  |   0.000s  | 0.0%|
|scheduling/abz7_800.smt2                                                                    |  60.018s  |  60.018s  |   0.000s  | 0.0%|
|scheduling/orb01_1000.smt2                                                                  |  45.794s  |  45.794s  |   0.000s  | 0.0%|
|scheduling/orb01_1059.smt2                                                                  |  60.100s  |  60.100s  |   0.000s  | 0.0%|
|scheduling/orb01_1100.smt2                                                                  |  47.294s  |  47.294s  |   0.000s  | 0.0%|
|scheduling/orb01_1200.smt2                                                                  |   2.709s  |   2.709s  |   0.000s  | 0.0%|
|scheduling/orb01_900.smt2                                                                   |   0.686s  |   0.686s  |   0.000s  | 0.0%|
|scheduling/orb02_1000.smt2                                                                  |   0.333s  |   0.333s  |   0.000s  | 0.0%|
|scheduling/orb02_700.smt2                                                                   |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|scheduling/orb02_800.smt2                                                                   |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|scheduling/orb02_888.smt2                                                                   |   4.797s  |   4.797s  |   0.000s  | 0.0%|
|scheduling/orb02_900.smt2                                                                   |   1.207s  |   1.207s  |   0.000s  | 0.0%|
|scheduling/orb03_1005.smt2                                                                  |  60.082s  |  60.082s  |   0.000s  | 0.0%|
|scheduling/orb03_1100.smt2                                                                  |   7.358s  |   7.358s  |   0.000s  | 0.0%|
|scheduling/orb03_1200.smt2                                                                  |   1.864s  |   1.864s  |   0.000s  | 0.0%|
|scheduling/orb03_850.smt2                                                                   |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|scheduling/orb03_950.smt2                                                                   |  10.448s  |  10.448s  |   0.000s  | 0.0%|
|scheduling/orb04_1005.smt2                                                                  |  20.917s  |  20.917s  |   0.000s  | 0.0%|
|scheduling/orb04_1100.smt2                                                                  |   3.514s  |   3.514s  |   0.000s  | 0.0%|
|scheduling/orb04_1200.smt2                                                                  |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|scheduling/orb04_850.smt2                                                                   |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|scheduling/orb04_950.smt2                                                                   |   0.705s  |   0.705s  |   0.000s  | 0.0%|
|scheduling/orb05_1000.smt2                                                                  |   0.338s  |   0.338s  |   0.000s  | 0.0%|
|scheduling/orb05_700.smt2                                                                   |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|scheduling/orb05_800.smt2                                                                   |   0.535s  |   0.535s  |   0.000s  | 0.0%|
|scheduling/orb05_887.smt2                                                                   |  19.633s  |  19.633s  |   0.000s  | 0.0%|
|scheduling/orb05_900.smt2                                                                   |  11.001s  |  11.001s  |   0.000s  | 0.0%|
|scheduling/orb06_1000.smt2                                                                  |  60.098s  |  60.098s  |   0.000s  | 0.0%|
|scheduling/orb06_1010.smt2                                                                  |  60.012s  |  60.012s  |   0.000s  | 0.0%|
|scheduling/orb06_1100.smt2                                                                  |  13.655s  |  13.655s  |   0.000s  | 0.0%|
|scheduling/orb06_1200.smt2                                                                  |   1.411s  |   1.411s  |   0.000s  | 0.0%|
|scheduling/orb06_900.smt2                                                                   |   0.651s  |   0.651s  |   0.000s  | 0.0%|
|scheduling/orb07_250.smt2                                                                   |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|scheduling/orb07_330.smt2                                                                   |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|scheduling/orb07_397.smt2                                                                   |   6.834s  |   6.834s  |   0.000s  | 0.0%|
|scheduling/orb07_430.smt2                                                                   |   0.808s  |   0.808s  |   0.000s  | 0.0%|
|scheduling/orb07_550.smt2                                                                   |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|scheduling/orb08_1000.smt2                                                                  |   5.002s  |   5.002s  |   0.000s  | 0.0%|
|scheduling/orb08_700.smt2                                                                   |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|scheduling/orb08_830.smt2                                                                   |   2.051s  |   2.051s  |   0.000s  | 0.0%|
|scheduling/orb08_888.smt2                                                                   |  18.491s  |  18.491s  |   0.000s  | 0.0%|
|scheduling/orb08_930.smt2                                                                   |  13.004s  |  13.004s  |   0.000s  | 0.0%|
|scheduling/orb09_1000.smt2                                                                  |   1.534s  |   1.534s  |   0.000s  | 0.0%|
|scheduling/orb09_1100.smt2                                                                  |   0.636s  |   0.636s  |   0.000s  | 0.0%|
|scheduling/orb09_800.smt2                                                                   |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|scheduling/orb09_900.smt2                                                                   |   4.194s  |   4.194s  |   0.000s  | 0.0%|
|scheduling/orb09_934.smt2                                                                   |  18.996s  |  18.996s  |   0.000s  | 0.0%|
|scheduling/orb10_1000.smt2                                                                  |   4.184s  |   4.184s  |   0.000s  | 0.0%|
|scheduling/orb10_1100.smt2                                                                  |   0.538s  |   0.538s  |   0.000s  | 0.0%|
|scheduling/orb10_800.smt2                                                                   |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|scheduling/orb10_900.smt2                                                                   |   1.391s  |   1.391s  |   0.000s  | 0.0%|
|scheduling/orb10_944.smt2                                                                   |  14.095s  |  14.095s  |   0.000s  | 0.0%|
|scheduling/swv11_2900.smt2                                                                  |  60.046s  |  60.046s  |   0.000s  | 0.0%|
|scheduling/swv11_2983.smt2                                                                  |  60.048s  |  60.048s  |   0.000s  | 0.0%|
|scheduling/swv11_2988.smt2                                                                  |  60.110s  |  60.110s  |   0.000s  | 0.0%|
|scheduling/swv11_2992.smt2                                                                  |  60.058s  |  60.058s  |   0.000s  | 0.0%|
|scheduling/swv11_3050.smt2                                                                  |  60.071s  |  60.071s  |   0.000s  | 0.0%|
|scheduling/swv12_2900.smt2                                                                  |  60.097s  |  60.097s  |   0.000s  | 0.0%|
|scheduling/swv12_2972.smt2                                                                  |  60.047s  |  60.047s  |   0.000s  | 0.0%|
|scheduling/swv12_2990.smt2                                                                  |  60.085s  |  60.085s  |   0.000s  | 0.0%|
|scheduling/swv12_3004.smt2                                                                  |  60.058s  |  60.058s  |   0.000s  | 0.0%|
|scheduling/swv12_3050.smt2                                                                  |  60.114s  |  60.114s  |   0.000s  | 0.0%|
|scheduling/swv13_3000.smt2                                                                  |  60.124s  |  60.124s  |   0.000s  | 0.0%|
|scheduling/swv13_3104.smt2                                                                  |  60.041s  |  60.041s  |   0.000s  | 0.0%|
|scheduling/swv13_3150.smt2                                                                  |  60.050s  |  60.050s  |   0.000s  | 0.0%|
|scheduling/swv13_3200.smt2                                                                  |  60.127s  |  60.127s  |   0.000s  | 0.0%|
|scheduling/swv14_2800.smt2                                                                  |  60.074s  |  60.074s  |   0.000s  | 0.0%|
|scheduling/swv14_2885.smt2                                                                  |  60.096s  |  60.096s  |   0.000s  | 0.0%|
|scheduling/swv14_2895.smt2                                                                  |  60.112s  |  60.112s  |   0.000s  | 0.0%|
|scheduling/swv14_2905.smt2                                                                  |  60.069s  |  60.069s  |   0.000s  | 0.0%|
|scheduling/swv14_3000.smt2                                                                  |  60.071s  |  60.071s  |   0.000s  | 0.0%|
|scheduling/yn1_750.smt2                                                                     |   1.364s  |   1.364s  |   0.000s  | 0.0%|
|scheduling/yn1_827.smt2                                                                     |  60.042s  |  60.042s  |   0.000s  | 0.0%|
|scheduling/yn1_850.smt2                                                                     |  60.092s  |  60.092s  |   0.000s  | 0.0%|
|scheduling/yn1_887.smt2                                                                     |  60.101s  |  60.101s  |   0.000s  | 0.0%|
|scheduling/yn1_950.smt2                                                                     |  60.104s  |  60.104s  |   0.000s  | 0.0%|
|scheduling/yn2_750.smt2                                                                     |   1.716s  |   1.716s  |   0.000s  | 0.0%|
|scheduling/yn2_862.smt2                                                                     |  60.087s  |  60.087s  |   0.000s  | 0.0%|
|scheduling/yn2_890.smt2                                                                     |  60.095s  |  60.095s  |   0.000s  | 0.0%|
|scheduling/yn2_910.smt2                                                                     |  60.087s  |  60.087s  |   0.000s  | 0.0%|
|scheduling/yn2_950.smt2                                                                     |  60.079s  |  60.079s  |   0.000s  | 0.0%|
|scheduling/yn3_750.smt2                                                                     |   1.321s  |   1.321s  |   0.000s  | 0.0%|
|scheduling/yn3_828.smt2                                                                     |  60.069s  |  60.069s  |   0.000s  | 0.0%|
|scheduling/yn3_860.smt2                                                                     |  60.097s  |  60.097s  |   0.000s  | 0.0%|
|scheduling/yn3_894.smt2                                                                     |  60.038s  |  60.038s  |   0.000s  | 0.0%|
|scheduling/yn3_950.smt2                                                                     |  60.099s  |  60.099s  |   0.000s  | 0.0%|
|scheduling/yn4_1000.smt2                                                                    |  60.055s  |  60.055s  |   0.000s  | 0.0%|
|scheduling/yn4_850.smt2                                                                     |  60.031s  |  60.031s  |   0.000s  | 0.0%|
|scheduling/yn4_919.smt2                                                                     |  60.095s  |  60.095s  |   0.000s  | 0.0%|
|scheduling/yn4_950.smt2                                                                     |  60.116s  |  60.116s  |   0.000s  | 0.0%|
|scheduling/yn4_969.smt2                                                                     |  60.086s  |  60.086s  |   0.000s  | 0.0%|
|skdmxa/skdmxa-3x3-10.smt2                                                                   |  14.622s  |  14.622s  |   0.000s  | 0.0%|
|skdmxa/skdmxa-3x3-15.smt2                                                                   |  60.033s  |  60.033s  |   0.000s  | 0.0%|
|skdmxa/skdmxa-3x3-20.smt2                                                                   |  60.039s  |  60.039s  |   0.000s  | 0.0%|
|skdmxa/skdmxa-3x3-5.smt2                                                                    |   1.610s  |   1.610s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-10.base.cvc.smt2                                                         |  16.433s  |  16.433s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-10.induction.cvc.smt2                                                    |   5.460s  |   5.460s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-11.base.cvc.smt2                                                         |  38.967s  |  38.967s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-11.induction.cvc.smt2                                                    |   8.977s  |   8.977s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-12.base.cvc.smt2                                                         |  60.033s  |  60.033s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-12.induction.cvc.smt2                                                    |  17.314s  |  17.314s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-13.base.cvc.smt2                                                         |  60.047s  |  60.047s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-13.induction.cvc.smt2                                                    |  20.795s  |  20.795s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-14.base.cvc.smt2                                                         |  60.071s  |  60.071s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-14.induction.cvc.smt2                                                    |  43.763s  |  43.763s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-15.base.cvc.smt2                                                         |  60.057s  |  60.057s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-15.induction.cvc.smt2                                                    |  15.867s  |  15.867s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-16.base.cvc.smt2                                                         |  60.049s  |  60.049s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-16.induction.cvc.smt2                                                    |  51.768s  |  51.768s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-17.base.cvc.smt2                                                         |  60.081s  |  60.081s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-17.induction.cvc.smt2                                                    |  45.723s  |  45.723s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-18.base.cvc.smt2                                                         |  60.063s  |  60.063s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-18.induction.cvc.smt2                                                    |  60.052s  |  60.052s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-19.base.cvc.smt2                                                         |  60.119s  |  60.119s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-19.induction.cvc.smt2                                                    |  60.070s  |  60.070s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-20.base.cvc.smt2                                                         |  60.087s  |  60.087s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-20.induction.cvc.smt2                                                    |  60.061s  |  60.061s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-5.base.cvc.smt2                                                          |   0.939s  |   0.939s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-5.induction.cvc.smt2                                                     |   1.238s  |   1.238s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-6.base.cvc.smt2                                                          |   2.355s  |   2.355s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-6.induction.cvc.smt2                                                     |   2.569s  |   2.569s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-7.base.cvc.smt2                                                          |   7.439s  |   7.439s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-7.induction.cvc.smt2                                                     |   5.773s  |   5.773s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-8.base.cvc.smt2                                                          |   6.370s  |   6.370s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-8.induction.cvc.smt2                                                     |   7.629s  |   7.629s  |   0.000s  | 0.0%|
|skdmxa2/skdmxa-3x3-9.base.cvc.smt2                                                          |  13.618s  |  13.618s  |   0.000s  | 0.0%|
</details>
