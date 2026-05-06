Comparing data and data


# SUMMARY
- LHS tests = 38
- RHS tests = 38
- LHS success = 38  (100.0%)
- RHS success = 38  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_LRA-timeout20min-auto_config}
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bb9a55789061a7e3da7e3868f9e388c750e72ad9
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=1 tactic.default_tactic=smt smt.auto_config=true"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LRA
Z3 commit message: clean up code

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: Z3-threads-1-sequential-smtcomp2025-QF_LRA-timeout20min-auto_config}
Runner: rise-runner-2
Z3 repo: ilanashapiro/z3
Z3 commit: bb9a55789061a7e3da7e3868f9e388c750e72ad9
Z3 branch: core_min
Z3 options: "-T:1200 -v:0 smt.threads=1 tactic.default_tactic=smt smt.auto_config=true"
Z3 inputs: inputs/smt_comp_2025_parallel/QF_LRA
Z3 commit message: clean up code

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.174s  |1200.174s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.157s  |1200.157s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 624.775s  | 624.775s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.014s  |1200.014s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1087.008s  |1087.008s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.214s  |1200.214s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.025s  |1200.025s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 805.834s  | 805.834s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.076s  |1200.076s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.134s  |1200.134s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.300s  |1200.300s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.222s  |1200.222s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.137s  |1200.137s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.174s  |1200.174s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.157s  |1200.157s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 624.775s  | 624.775s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.014s  |1200.014s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1087.008s  |1087.008s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.214s  |1200.214s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.025s  |1200.025s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 805.834s  | 805.834s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.076s  |1200.076s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.134s  |1200.134s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.300s  |1200.300s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.222s  |1200.222s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.137s  |1200.137s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.174s  |1200.174s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.157s  |1200.157s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 624.775s  | 624.775s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.014s  |1200.014s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1087.008s  |1087.008s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.214s  |1200.214s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.025s  |1200.025s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 805.834s  | 805.834s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.076s  |1200.076s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.134s  |1200.134s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.300s  |1200.300s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.222s  |1200.222s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.137s  |1200.137s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.174s  |1200.174s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.157s  |1200.157s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 624.775s  | 624.775s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.014s  |1200.014s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1087.008s  |1087.008s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.214s  |1200.214s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.025s  |1200.025s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 805.834s  | 805.834s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.076s  |1200.076s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.134s  |1200.134s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.300s  |1200.300s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.222s  |1200.222s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.137s  |1200.137s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1200.300s |2552.0MiB|
|scrambled25695.smt2                                                                        |1200.222s |1723.0MiB|
|scrambled111949.smt2                                                                       |1200.214s |2015.0MiB|
|scrambled55850.smt2                                                                        |1200.181s |1348.0MiB|
|scrambled101728.smt2                                                                       |1200.174s |1264.0MiB|
|scrambled102621.smt2                                                                       |1200.157s |1514.0MiB|
|scrambled98986.smt2                                                                        |1200.153s |1328.0MiB|
|scrambled8163.smt2                                                                         |1200.145s |1265.0MiB|
|scrambled77008.smt2                                                                        |1200.145s |1001.0MiB|
|scrambled37260.smt2                                                                        |1200.137s |1008.0MiB|
|scrambled13169.smt2                                                                        |1200.134s |1276.0MiB|
|scrambled44527.smt2                                                                        |1200.120s |1130.0MiB|
|scrambled95284.smt2                                                                        |1200.101s |533.0MiB|
|scrambled124455.smt2                                                                       |1200.076s |476.0MiB|
|scrambled117897.smt2                                                                       |1200.064s |394.0MiB|
|scrambled47581.smt2                                                                        |1200.054s |314.0MiB|
|scrambled59368.smt2                                                                        |1200.054s |281.0MiB|
|scrambled55845.smt2                                                                        |1200.054s |160.0MiB|
|scrambled76525.smt2                                                                        |1200.046s |299.0MiB|
|scrambled49820.smt2                                                                        |1200.041s |67.476MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1200.300s |2552.0MiB|
|scrambled25695.smt2                                                                        |1200.222s |1723.0MiB|
|scrambled111949.smt2                                                                       |1200.214s |2015.0MiB|
|scrambled55850.smt2                                                                        |1200.181s |1348.0MiB|
|scrambled101728.smt2                                                                       |1200.174s |1264.0MiB|
|scrambled102621.smt2                                                                       |1200.157s |1514.0MiB|
|scrambled98986.smt2                                                                        |1200.153s |1328.0MiB|
|scrambled8163.smt2                                                                         |1200.145s |1265.0MiB|
|scrambled77008.smt2                                                                        |1200.145s |1001.0MiB|
|scrambled37260.smt2                                                                        |1200.137s |1008.0MiB|
|scrambled13169.smt2                                                                        |1200.134s |1276.0MiB|
|scrambled44527.smt2                                                                        |1200.120s |1130.0MiB|
|scrambled95284.smt2                                                                        |1200.101s |533.0MiB|
|scrambled124455.smt2                                                                       |1200.076s |476.0MiB|
|scrambled117897.smt2                                                                       |1200.064s |394.0MiB|
|scrambled47581.smt2                                                                        |1200.054s |314.0MiB|
|scrambled59368.smt2                                                                        |1200.054s |281.0MiB|
|scrambled55845.smt2                                                                        |1200.054s |160.0MiB|
|scrambled76525.smt2                                                                        |1200.046s |299.0MiB|
|scrambled49820.smt2                                                                        |1200.041s |67.476MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |58.972MiB|58.972MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |1264.0MiB|1264.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |1514.0MiB|1514.0MiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |1584.0MiB|1584.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |34.836MiB|34.836MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |47.352MiB|47.352MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |828.0MiB|828.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |2015.0MiB|2015.0MiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |49.484MiB|49.484MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |394.0MiB|394.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |54.136MiB|54.136MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |476.0MiB|476.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |29.8MiB|29.8MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |1276.0MiB|1276.0MiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |2552.0MiB|2552.0MiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |331.0MiB|331.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |1723.0MiB|1723.0MiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |46.28MiB|46.28MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |59.072MiB|59.072MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |1008.0MiB|1008.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |58.972MiB|58.972MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |1264.0MiB|1264.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |1514.0MiB|1514.0MiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |1584.0MiB|1584.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |34.836MiB|34.836MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |47.352MiB|47.352MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |828.0MiB|828.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |2015.0MiB|2015.0MiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |49.484MiB|49.484MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |394.0MiB|394.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |54.136MiB|54.136MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |476.0MiB|476.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |29.8MiB|29.8MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |1276.0MiB|1276.0MiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |2552.0MiB|2552.0MiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |331.0MiB|331.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |1723.0MiB|1723.0MiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |46.28MiB|46.28MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |59.072MiB|59.072MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |1008.0MiB|1008.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |58.972MiB|58.972MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |1264.0MiB|1264.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |1514.0MiB|1514.0MiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |1584.0MiB|1584.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |34.836MiB|34.836MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |47.352MiB|47.352MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |828.0MiB|828.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |2015.0MiB|2015.0MiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |49.484MiB|49.484MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |394.0MiB|394.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |54.136MiB|54.136MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |476.0MiB|476.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |29.8MiB|29.8MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |1276.0MiB|1276.0MiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |2552.0MiB|2552.0MiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |331.0MiB|331.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |1723.0MiB|1723.0MiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |46.28MiB|46.28MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |59.072MiB|59.072MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |1008.0MiB|1008.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |58.972MiB|58.972MiB|0B| 0.0%|
|scrambled101728.smt2                                                                        |1264.0MiB|1264.0MiB|0B| 0.0%|
|scrambled102621.smt2                                                                        |1514.0MiB|1514.0MiB|0B| 0.0%|
|scrambled102680.smt2                                                                        |1584.0MiB|1584.0MiB|0B| 0.0%|
|scrambled103576.smt2                                                                        |34.836MiB|34.836MiB|0B| 0.0%|
|scrambled104811.smt2                                                                        |47.352MiB|47.352MiB|0B| 0.0%|
|scrambled109307.smt2                                                                        |828.0MiB|828.0MiB|0B| 0.0%|
|scrambled111949.smt2                                                                        |2015.0MiB|2015.0MiB|0B| 0.0%|
|scrambled115671.smt2                                                                        |49.484MiB|49.484MiB|0B| 0.0%|
|scrambled117897.smt2                                                                        |394.0MiB|394.0MiB|0B| 0.0%|
|scrambled122587.smt2                                                                        |54.136MiB|54.136MiB|0B| 0.0%|
|scrambled124455.smt2                                                                        |476.0MiB|476.0MiB|0B| 0.0%|
|scrambled124681.smt2                                                                        |29.8MiB|29.8MiB|0B| 0.0%|
|scrambled13169.smt2                                                                         |1276.0MiB|1276.0MiB|0B| 0.0%|
|scrambled13209.smt2                                                                         |2552.0MiB|2552.0MiB|0B| 0.0%|
|scrambled17583.smt2                                                                         |331.0MiB|331.0MiB|0B| 0.0%|
|scrambled25695.smt2                                                                         |1723.0MiB|1723.0MiB|0B| 0.0%|
|scrambled31085.smt2                                                                         |46.28MiB|46.28MiB|0B| 0.0%|
|scrambled35077.smt2                                                                         |59.072MiB|59.072MiB|0B| 0.0%|
|scrambled37260.smt2                                                                         |1008.0MiB|1008.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1200.300s |2552.0MiB|
|scrambled111949.smt2                                                                       |1200.214s |2015.0MiB|
|scrambled25695.smt2                                                                        |1200.222s |1723.0MiB|
|scrambled102680.smt2                                                                       | 624.775s |1584.0MiB|
|scrambled102621.smt2                                                                       |1200.157s |1514.0MiB|
|scrambled55850.smt2                                                                        |1200.181s |1348.0MiB|
|scrambled98986.smt2                                                                        |1200.153s |1328.0MiB|
|scrambled13169.smt2                                                                        |1200.134s |1276.0MiB|
|scrambled8163.smt2                                                                         |1200.145s |1265.0MiB|
|scrambled101728.smt2                                                                       |1200.174s |1264.0MiB|
|scrambled44527.smt2                                                                        |1200.120s |1130.0MiB|
|scrambled37260.smt2                                                                        |1200.137s |1008.0MiB|
|scrambled77008.smt2                                                                        |1200.145s |1001.0MiB|
|scrambled109307.smt2                                                                       |1087.008s |828.0MiB|
|scrambled95284.smt2                                                                        |1200.101s |533.0MiB|
|scrambled124455.smt2                                                                       |1200.076s |476.0MiB|
|scrambled117897.smt2                                                                       |1200.064s |394.0MiB|
|scrambled17583.smt2                                                                        |1200.038s |331.0MiB|
|scrambled47581.smt2                                                                        |1200.054s |314.0MiB|
|scrambled76525.smt2                                                                        |1200.046s |299.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|scrambled13209.smt2                                                                        |1200.300s |2552.0MiB|
|scrambled111949.smt2                                                                       |1200.214s |2015.0MiB|
|scrambled25695.smt2                                                                        |1200.222s |1723.0MiB|
|scrambled102680.smt2                                                                       | 624.775s |1584.0MiB|
|scrambled102621.smt2                                                                       |1200.157s |1514.0MiB|
|scrambled55850.smt2                                                                        |1200.181s |1348.0MiB|
|scrambled98986.smt2                                                                        |1200.153s |1328.0MiB|
|scrambled13169.smt2                                                                        |1200.134s |1276.0MiB|
|scrambled8163.smt2                                                                         |1200.145s |1265.0MiB|
|scrambled101728.smt2                                                                       |1200.174s |1264.0MiB|
|scrambled44527.smt2                                                                        |1200.120s |1130.0MiB|
|scrambled37260.smt2                                                                        |1200.137s |1008.0MiB|
|scrambled77008.smt2                                                                        |1200.145s |1001.0MiB|
|scrambled109307.smt2                                                                       |1087.008s |828.0MiB|
|scrambled95284.smt2                                                                        |1200.101s |533.0MiB|
|scrambled124455.smt2                                                                       |1200.076s |476.0MiB|
|scrambled117897.smt2                                                                       |1200.064s |394.0MiB|
|scrambled17583.smt2                                                                        |1200.038s |331.0MiB|
|scrambled47581.smt2                                                                        |1200.054s |314.0MiB|
|scrambled76525.smt2                                                                        |1200.046s |299.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|scrambled101086.smt2                                                                        |1200.039s  |1200.039s  |   0.000s  | 0.0%|
|scrambled101728.smt2                                                                        |1200.174s  |1200.174s  |   0.000s  | 0.0%|
|scrambled102621.smt2                                                                        |1200.157s  |1200.157s  |   0.000s  | 0.0%|
|scrambled102680.smt2                                                                        | 624.775s  | 624.775s  |   0.000s  | 0.0%|
|scrambled103576.smt2                                                                        |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled104811.smt2                                                                        |1200.014s  |1200.014s  |   0.000s  | 0.0%|
|scrambled109307.smt2                                                                        |1087.008s  |1087.008s  |   0.000s  | 0.0%|
|scrambled111949.smt2                                                                        |1200.214s  |1200.214s  |   0.000s  | 0.0%|
|scrambled115671.smt2                                                                        |1200.025s  |1200.025s  |   0.000s  | 0.0%|
|scrambled117897.smt2                                                                        |1200.064s  |1200.064s  |   0.000s  | 0.0%|
|scrambled122587.smt2                                                                        | 805.834s  | 805.834s  |   0.000s  | 0.0%|
|scrambled124455.smt2                                                                        |1200.076s  |1200.076s  |   0.000s  | 0.0%|
|scrambled124681.smt2                                                                        |1200.035s  |1200.035s  |   0.000s  | 0.0%|
|scrambled13169.smt2                                                                         |1200.134s  |1200.134s  |   0.000s  | 0.0%|
|scrambled13209.smt2                                                                         |1200.300s  |1200.300s  |   0.000s  | 0.0%|
|scrambled17583.smt2                                                                         |1200.038s  |1200.038s  |   0.000s  | 0.0%|
|scrambled25695.smt2                                                                         |1200.222s  |1200.222s  |   0.000s  | 0.0%|
|scrambled31085.smt2                                                                         |1200.017s  |1200.017s  |   0.000s  | 0.0%|
|scrambled35077.smt2                                                                         |1200.028s  |1200.028s  |   0.000s  | 0.0%|
|scrambled37260.smt2                                                                         |1200.137s  |1200.137s  |   0.000s  | 0.0%|
|scrambled44527.smt2                                                                         |1200.120s  |1200.120s  |   0.000s  | 0.0%|
|scrambled46192.smt2                                                                         |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled47581.smt2                                                                         |1200.054s  |1200.054s  |   0.000s  | 0.0%|
|scrambled49820.smt2                                                                         |1200.041s  |1200.041s  |   0.000s  | 0.0%|
|scrambled55845.smt2                                                                         |1200.054s  |1200.054s  |   0.000s  | 0.0%|
|scrambled55850.smt2                                                                         |1200.181s  |1200.181s  |   0.000s  | 0.0%|
|scrambled59368.smt2                                                                         |1200.054s  |1200.054s  |   0.000s  | 0.0%|
|scrambled65517.smt2                                                                         |1200.037s  |1200.037s  |   0.000s  | 0.0%|
|scrambled71015.smt2                                                                         |1200.033s  |1200.033s  |   0.000s  | 0.0%|
|scrambled76525.smt2                                                                         |1200.046s  |1200.046s  |   0.000s  | 0.0%|
|scrambled76532.smt2                                                                         |1200.014s  |1200.014s  |   0.000s  | 0.0%|
|scrambled77008.smt2                                                                         |1200.145s  |1200.145s  |   0.000s  | 0.0%|
|scrambled77308.smt2                                                                         |1200.015s  |1200.015s  |   0.000s  | 0.0%|
|scrambled8163.smt2                                                                          |1200.145s  |1200.145s  |   0.000s  | 0.0%|
|scrambled88927.smt2                                                                         |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled92964.smt2                                                                         |1200.032s  |1200.032s  |   0.000s  | 0.0%|
|scrambled95284.smt2                                                                         |1200.101s  |1200.101s  |   0.000s  | 0.0%|
</details>
