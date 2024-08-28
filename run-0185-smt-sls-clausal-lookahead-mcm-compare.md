Comparing data and data


# SUMMARY
- LHS tests = 186
- RHS tests = 186
- LHS success = 186  (100.0%)
- RHS success = 186  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: MCM
Job tag: smt-sls-clausal-lookahead-mcm
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 22e4054674a291d83f59019273ff0b24f24295bf
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true  sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_NIA_MCM
Z3 commit message: add clausal lookahead to arithmetic solver as part of portfolio

have legacy qfbv-sls solver use nnf pre-processing. It relies on it for correctness of the score updates.

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: MCM
Job tag: smt-sls-clausal-lookahead-mcm
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 22e4054674a291d83f59019273ff0b24f24295bf
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true  sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_NIA_MCM
Z3 commit message: add clausal lookahead to arithmetic solver as part of portfolio

have legacy qfbv-sls solver use nnf pre-processing. It relies on it for correctness of the score updates.

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  16.816s  |  16.816s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |   4.732s  |   4.732s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  59.900s  |  59.900s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |   0.792s  |   0.792s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |   0.993s  |   0.993s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  59.969s  |  59.969s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |   1.046s  |   1.046s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  59.959s  |  59.959s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  59.917s  |  59.917s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  59.860s  |  59.860s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   0.124s  |   0.124s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  16.816s  |  16.816s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |   4.732s  |   4.732s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  59.900s  |  59.900s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |   0.792s  |   0.792s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |   0.993s  |   0.993s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  59.969s  |  59.969s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |   1.046s  |   1.046s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  59.959s  |  59.959s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  59.917s  |  59.917s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  59.860s  |  59.860s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   0.124s  |   0.124s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  16.816s  |  16.816s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |   4.732s  |   4.732s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  59.900s  |  59.900s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |   0.792s  |   0.792s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |   0.993s  |   0.993s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  59.969s  |  59.969s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |   1.046s  |   1.046s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  59.959s  |  59.959s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  59.917s  |  59.917s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  59.860s  |  59.860s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   0.124s  |   0.124s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  16.816s  |  16.816s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |   4.732s  |   4.732s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  59.900s  |  59.900s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |   0.792s  |   0.792s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |   0.993s  |   0.993s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  59.969s  |  59.969s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |   1.046s  |   1.046s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  59.959s  |  59.959s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  59.917s  |  59.917s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  59.860s  |  59.860s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   0.124s  |   0.124s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|185.smt2                                                                                   |  60.701s |11.954GiB|
|186.smt2                                                                                   |  60.524s |9662.0MiB|
|184.smt2                                                                                   |  60.515s |7895.0MiB|
|182.smt2                                                                                   |  60.435s |7047.0MiB|
|183.smt2                                                                                   |  60.363s |7048.0MiB|
|11.smt2                                                                                    |  60.292s |23.252MiB|
|181.smt2                                                                                   |  60.166s |3033.0MiB|
|174.smt2                                                                                   |  60.152s |2093.0MiB|
|176.smt2                                                                                   |  60.150s |2403.0MiB|
|180.smt2                                                                                   |  60.147s |2257.0MiB|
|175.smt2                                                                                   |  60.146s |1851.0MiB|
|90.smt2                                                                                    |  60.127s |37.068MiB|
|178.smt2                                                                                   |  60.117s |2444.0MiB|
|173.smt2                                                                                   |  60.103s |1899.0MiB|
|179.smt2                                                                                   |  60.085s |2257.0MiB|
|163.smt2                                                                                   |  60.053s |750.0MiB|
|23.smt2                                                                                    |  60.044s |27.392MiB|
|165.smt2                                                                                   |  60.042s |757.0MiB|
|169.smt2                                                                                   |  60.025s |881.0MiB|
|149.smt2                                                                                   |  60.024s |152.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|185.smt2                                                                                   |  60.701s |11.954GiB|
|186.smt2                                                                                   |  60.524s |9662.0MiB|
|184.smt2                                                                                   |  60.515s |7895.0MiB|
|182.smt2                                                                                   |  60.435s |7047.0MiB|
|183.smt2                                                                                   |  60.363s |7048.0MiB|
|11.smt2                                                                                    |  60.292s |23.252MiB|
|181.smt2                                                                                   |  60.166s |3033.0MiB|
|174.smt2                                                                                   |  60.152s |2093.0MiB|
|176.smt2                                                                                   |  60.150s |2403.0MiB|
|180.smt2                                                                                   |  60.147s |2257.0MiB|
|175.smt2                                                                                   |  60.146s |1851.0MiB|
|90.smt2                                                                                    |  60.127s |37.068MiB|
|178.smt2                                                                                   |  60.117s |2444.0MiB|
|173.smt2                                                                                   |  60.103s |1899.0MiB|
|179.smt2                                                                                   |  60.085s |2257.0MiB|
|163.smt2                                                                                   |  60.053s |750.0MiB|
|23.smt2                                                                                    |  60.044s |27.392MiB|
|165.smt2                                                                                   |  60.042s |757.0MiB|
|169.smt2                                                                                   |  60.025s |881.0MiB|
|149.smt2                                                                                   |  60.024s |152.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |28.02MiB|28.02MiB|0B| 0.0%|
|02.smt2                                                                                     |25.336MiB|25.336MiB|0B| 0.0%|
|03.smt2                                                                                     |26.224MiB|26.224MiB|0B| 0.0%|
|04.smt2                                                                                     |24.012MiB|24.012MiB|0B| 0.0%|
|05.smt2                                                                                     |27.432MiB|27.432MiB|0B| 0.0%|
|06.smt2                                                                                     |20.144MiB|20.144MiB|0B| 0.0%|
|07.smt2                                                                                     |24.052MiB|24.052MiB|0B| 0.0%|
|08.smt2                                                                                     |22.064MiB|22.064MiB|0B| 0.0%|
|09.smt2                                                                                     |23.292MiB|23.292MiB|0B| 0.0%|
|10.smt2                                                                                     |25.164MiB|25.164MiB|0B| 0.0%|
|100.smt2                                                                                    |30.996MiB|30.996MiB|0B| 0.0%|
|101.smt2                                                                                    |27.624MiB|27.624MiB|0B| 0.0%|
|102.smt2                                                                                    |35.32MiB|35.32MiB|0B| 0.0%|
|103.smt2                                                                                    |30.98MiB|30.98MiB|0B| 0.0%|
|104.smt2                                                                                    |33.912MiB|33.912MiB|0B| 0.0%|
|105.smt2                                                                                    |98.0MiB|98.0MiB|0B| 0.0%|
|106.smt2                                                                                    |119.0MiB|119.0MiB|0B| 0.0%|
|107.smt2                                                                                    |25.852MiB|25.852MiB|0B| 0.0%|
|108.smt2                                                                                    |100.0MiB|100.0MiB|0B| 0.0%|
|109.smt2                                                                                    |27.016MiB|27.016MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |28.02MiB|28.02MiB|0B| 0.0%|
|02.smt2                                                                                     |25.336MiB|25.336MiB|0B| 0.0%|
|03.smt2                                                                                     |26.224MiB|26.224MiB|0B| 0.0%|
|04.smt2                                                                                     |24.012MiB|24.012MiB|0B| 0.0%|
|05.smt2                                                                                     |27.432MiB|27.432MiB|0B| 0.0%|
|06.smt2                                                                                     |20.144MiB|20.144MiB|0B| 0.0%|
|07.smt2                                                                                     |24.052MiB|24.052MiB|0B| 0.0%|
|08.smt2                                                                                     |22.064MiB|22.064MiB|0B| 0.0%|
|09.smt2                                                                                     |23.292MiB|23.292MiB|0B| 0.0%|
|10.smt2                                                                                     |25.164MiB|25.164MiB|0B| 0.0%|
|100.smt2                                                                                    |30.996MiB|30.996MiB|0B| 0.0%|
|101.smt2                                                                                    |27.624MiB|27.624MiB|0B| 0.0%|
|102.smt2                                                                                    |35.32MiB|35.32MiB|0B| 0.0%|
|103.smt2                                                                                    |30.98MiB|30.98MiB|0B| 0.0%|
|104.smt2                                                                                    |33.912MiB|33.912MiB|0B| 0.0%|
|105.smt2                                                                                    |98.0MiB|98.0MiB|0B| 0.0%|
|106.smt2                                                                                    |119.0MiB|119.0MiB|0B| 0.0%|
|107.smt2                                                                                    |25.852MiB|25.852MiB|0B| 0.0%|
|108.smt2                                                                                    |100.0MiB|100.0MiB|0B| 0.0%|
|109.smt2                                                                                    |27.016MiB|27.016MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |28.02MiB|28.02MiB|0B| 0.0%|
|02.smt2                                                                                     |25.336MiB|25.336MiB|0B| 0.0%|
|03.smt2                                                                                     |26.224MiB|26.224MiB|0B| 0.0%|
|04.smt2                                                                                     |24.012MiB|24.012MiB|0B| 0.0%|
|05.smt2                                                                                     |27.432MiB|27.432MiB|0B| 0.0%|
|06.smt2                                                                                     |20.144MiB|20.144MiB|0B| 0.0%|
|07.smt2                                                                                     |24.052MiB|24.052MiB|0B| 0.0%|
|08.smt2                                                                                     |22.064MiB|22.064MiB|0B| 0.0%|
|09.smt2                                                                                     |23.292MiB|23.292MiB|0B| 0.0%|
|10.smt2                                                                                     |25.164MiB|25.164MiB|0B| 0.0%|
|100.smt2                                                                                    |30.996MiB|30.996MiB|0B| 0.0%|
|101.smt2                                                                                    |27.624MiB|27.624MiB|0B| 0.0%|
|102.smt2                                                                                    |35.32MiB|35.32MiB|0B| 0.0%|
|103.smt2                                                                                    |30.98MiB|30.98MiB|0B| 0.0%|
|104.smt2                                                                                    |33.912MiB|33.912MiB|0B| 0.0%|
|105.smt2                                                                                    |98.0MiB|98.0MiB|0B| 0.0%|
|106.smt2                                                                                    |119.0MiB|119.0MiB|0B| 0.0%|
|107.smt2                                                                                    |25.852MiB|25.852MiB|0B| 0.0%|
|108.smt2                                                                                    |100.0MiB|100.0MiB|0B| 0.0%|
|109.smt2                                                                                    |27.016MiB|27.016MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |28.02MiB|28.02MiB|0B| 0.0%|
|02.smt2                                                                                     |25.336MiB|25.336MiB|0B| 0.0%|
|03.smt2                                                                                     |26.224MiB|26.224MiB|0B| 0.0%|
|04.smt2                                                                                     |24.012MiB|24.012MiB|0B| 0.0%|
|05.smt2                                                                                     |27.432MiB|27.432MiB|0B| 0.0%|
|06.smt2                                                                                     |20.144MiB|20.144MiB|0B| 0.0%|
|07.smt2                                                                                     |24.052MiB|24.052MiB|0B| 0.0%|
|08.smt2                                                                                     |22.064MiB|22.064MiB|0B| 0.0%|
|09.smt2                                                                                     |23.292MiB|23.292MiB|0B| 0.0%|
|10.smt2                                                                                     |25.164MiB|25.164MiB|0B| 0.0%|
|100.smt2                                                                                    |30.996MiB|30.996MiB|0B| 0.0%|
|101.smt2                                                                                    |27.624MiB|27.624MiB|0B| 0.0%|
|102.smt2                                                                                    |35.32MiB|35.32MiB|0B| 0.0%|
|103.smt2                                                                                    |30.98MiB|30.98MiB|0B| 0.0%|
|104.smt2                                                                                    |33.912MiB|33.912MiB|0B| 0.0%|
|105.smt2                                                                                    |98.0MiB|98.0MiB|0B| 0.0%|
|106.smt2                                                                                    |119.0MiB|119.0MiB|0B| 0.0%|
|107.smt2                                                                                    |25.852MiB|25.852MiB|0B| 0.0%|
|108.smt2                                                                                    |100.0MiB|100.0MiB|0B| 0.0%|
|109.smt2                                                                                    |27.016MiB|27.016MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|185.smt2                                                                                   |  60.701s |11.954GiB|
|186.smt2                                                                                   |  60.524s |9662.0MiB|
|184.smt2                                                                                   |  60.515s |7895.0MiB|
|183.smt2                                                                                   |  60.363s |7048.0MiB|
|182.smt2                                                                                   |  60.435s |7047.0MiB|
|181.smt2                                                                                   |  60.166s |3033.0MiB|
|178.smt2                                                                                   |  60.117s |2444.0MiB|
|176.smt2                                                                                   |  60.150s |2403.0MiB|
|180.smt2                                                                                   |  60.147s |2257.0MiB|
|179.smt2                                                                                   |  60.085s |2257.0MiB|
|174.smt2                                                                                   |  60.152s |2093.0MiB|
|172.smt2                                                                                   |  60.020s |2036.0MiB|
|173.smt2                                                                                   |  60.103s |1899.0MiB|
|175.smt2                                                                                   |  60.146s |1851.0MiB|
|169.smt2                                                                                   |  60.025s |881.0MiB|
|165.smt2                                                                                   |  60.042s |757.0MiB|
|163.smt2                                                                                   |  60.053s |750.0MiB|
|161.smt2                                                                                   |  60.015s |723.0MiB|
|171.smt2                                                                                   |  59.991s |625.0MiB|
|160.smt2                                                                                   |  59.896s |622.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|185.smt2                                                                                   |  60.701s |11.954GiB|
|186.smt2                                                                                   |  60.524s |9662.0MiB|
|184.smt2                                                                                   |  60.515s |7895.0MiB|
|183.smt2                                                                                   |  60.363s |7048.0MiB|
|182.smt2                                                                                   |  60.435s |7047.0MiB|
|181.smt2                                                                                   |  60.166s |3033.0MiB|
|178.smt2                                                                                   |  60.117s |2444.0MiB|
|176.smt2                                                                                   |  60.150s |2403.0MiB|
|180.smt2                                                                                   |  60.147s |2257.0MiB|
|179.smt2                                                                                   |  60.085s |2257.0MiB|
|174.smt2                                                                                   |  60.152s |2093.0MiB|
|172.smt2                                                                                   |  60.020s |2036.0MiB|
|173.smt2                                                                                   |  60.103s |1899.0MiB|
|175.smt2                                                                                   |  60.146s |1851.0MiB|
|169.smt2                                                                                   |  60.025s |881.0MiB|
|165.smt2                                                                                   |  60.042s |757.0MiB|
|163.smt2                                                                                   |  60.053s |750.0MiB|
|161.smt2                                                                                   |  60.015s |723.0MiB|
|171.smt2                                                                                   |  59.991s |625.0MiB|
|160.smt2                                                                                   |  59.896s |622.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  16.816s  |  16.816s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |   4.732s  |   4.732s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  59.900s  |  59.900s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |   0.792s  |   0.792s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |   0.993s  |   0.993s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  59.969s  |  59.969s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |   1.046s  |   1.046s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  59.959s  |  59.959s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  59.917s  |  59.917s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  59.860s  |  59.860s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  60.292s  |  60.292s  |   0.000s  | 0.0%|
|110.smt2                                                                                    |  60.010s  |  60.010s  |   0.000s  | 0.0%|
|111.smt2                                                                                    |  59.839s  |  59.839s  |   0.000s  | 0.0%|
|112.smt2                                                                                    |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|113.smt2                                                                                    |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|114.smt2                                                                                    |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|115.smt2                                                                                    |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|116.smt2                                                                                    |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|117.smt2                                                                                    |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|118.smt2                                                                                    |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|119.smt2                                                                                    |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|12.smt2                                                                                     |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|120.smt2                                                                                    |  59.686s  |  59.686s  |   0.000s  | 0.0%|
|121.smt2                                                                                    |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|122.smt2                                                                                    |  59.953s  |  59.953s  |   0.000s  | 0.0%|
|123.smt2                                                                                    |  16.076s  |  16.076s  |   0.000s  | 0.0%|
|124.smt2                                                                                    |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|125.smt2                                                                                    |  60.018s  |  60.018s  |   0.000s  | 0.0%|
|126.smt2                                                                                    |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|127.smt2                                                                                    |  60.014s  |  60.014s  |   0.000s  | 0.0%|
|128.smt2                                                                                    |  60.011s  |  60.011s  |   0.000s  | 0.0%|
|129.smt2                                                                                    |  60.009s  |  60.009s  |   0.000s  | 0.0%|
|13.smt2                                                                                     |   2.117s  |   2.117s  |   0.000s  | 0.0%|
|130.smt2                                                                                    |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|131.smt2                                                                                    |  59.961s  |  59.961s  |   0.000s  | 0.0%|
|132.smt2                                                                                    |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|133.smt2                                                                                    |  60.022s  |  60.022s  |   0.000s  | 0.0%|
|134.smt2                                                                                    |  59.960s  |  59.960s  |   0.000s  | 0.0%|
|135.smt2                                                                                    |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|136.smt2                                                                                    |  60.004s  |  60.004s  |   0.000s  | 0.0%|
|137.smt2                                                                                    |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|138.smt2                                                                                    |  59.936s  |  59.936s  |   0.000s  | 0.0%|
|139.smt2                                                                                    |  59.939s  |  59.939s  |   0.000s  | 0.0%|
|14.smt2                                                                                     |   1.296s  |   1.296s  |   0.000s  | 0.0%|
|140.smt2                                                                                    |  59.935s  |  59.935s  |   0.000s  | 0.0%|
|141.smt2                                                                                    |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|142.smt2                                                                                    |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|143.smt2                                                                                    |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|144.smt2                                                                                    |  60.011s  |  60.011s  |   0.000s  | 0.0%|
|145.smt2                                                                                    |  59.937s  |  59.937s  |   0.000s  | 0.0%|
|146.smt2                                                                                    |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|147.smt2                                                                                    |  59.905s  |  59.905s  |   0.000s  | 0.0%|
|148.smt2                                                                                    |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|149.smt2                                                                                    |  60.024s  |  60.024s  |   0.000s  | 0.0%|
|15.smt2                                                                                     |   5.295s  |   5.295s  |   0.000s  | 0.0%|
|150.smt2                                                                                    |  59.963s  |  59.963s  |   0.000s  | 0.0%|
|151.smt2                                                                                    |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|152.smt2                                                                                    |   8.854s  |   8.854s  |   0.000s  | 0.0%|
|153.smt2                                                                                    |  60.009s  |  60.009s  |   0.000s  | 0.0%|
|154.smt2                                                                                    |  60.011s  |  60.011s  |   0.000s  | 0.0%|
|155.smt2                                                                                    |  60.004s  |  60.004s  |   0.000s  | 0.0%|
|156.smt2                                                                                    |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|157.smt2                                                                                    |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|158.smt2                                                                                    |  59.829s  |  59.829s  |   0.000s  | 0.0%|
|159.smt2                                                                                    |  59.928s  |  59.928s  |   0.000s  | 0.0%|
|16.smt2                                                                                     |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|160.smt2                                                                                    |  59.896s  |  59.896s  |   0.000s  | 0.0%|
|161.smt2                                                                                    |  60.015s  |  60.015s  |   0.000s  | 0.0%|
|162.smt2                                                                                    |   0.499s  |   0.499s  |   0.000s  | 0.0%|
|163.smt2                                                                                    |  60.053s  |  60.053s  |   0.000s  | 0.0%|
|164.smt2                                                                                    |   0.324s  |   0.324s  |   0.000s  | 0.0%|
|165.smt2                                                                                    |  60.042s  |  60.042s  |   0.000s  | 0.0%|
|166.smt2                                                                                    |   0.357s  |   0.357s  |   0.000s  | 0.0%|
|167.smt2                                                                                    |  60.023s  |  60.023s  |   0.000s  | 0.0%|
|168.smt2                                                                                    |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|169.smt2                                                                                    |  60.025s  |  60.025s  |   0.000s  | 0.0%|
|17.smt2                                                                                     |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|170.smt2                                                                                    |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|171.smt2                                                                                    |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|172.smt2                                                                                    |  60.020s  |  60.020s  |   0.000s  | 0.0%|
|173.smt2                                                                                    |  60.103s  |  60.103s  |   0.000s  | 0.0%|
|174.smt2                                                                                    |  60.152s  |  60.152s  |   0.000s  | 0.0%|
|175.smt2                                                                                    |  60.146s  |  60.146s  |   0.000s  | 0.0%|
|176.smt2                                                                                    |  60.150s  |  60.150s  |   0.000s  | 0.0%|
|177.smt2                                                                                    |   1.939s  |   1.939s  |   0.000s  | 0.0%|
|178.smt2                                                                                    |  60.117s  |  60.117s  |   0.000s  | 0.0%|
|179.smt2                                                                                    |  60.085s  |  60.085s  |   0.000s  | 0.0%|
|18.smt2                                                                                     |  59.948s  |  59.948s  |   0.000s  | 0.0%|
|180.smt2                                                                                    |  60.147s  |  60.147s  |   0.000s  | 0.0%|
|181.smt2                                                                                    |  60.166s  |  60.166s  |   0.000s  | 0.0%|
|182.smt2                                                                                    |  60.435s  |  60.435s  |   0.000s  | 0.0%|
|183.smt2                                                                                    |  60.363s  |  60.363s  |   0.000s  | 0.0%|
|184.smt2                                                                                    |  60.515s  |  60.515s  |   0.000s  | 0.0%|
|185.smt2                                                                                    |  60.701s  |  60.701s  |   0.000s  | 0.0%|
|186.smt2                                                                                    |  60.524s  |  60.524s  |   0.000s  | 0.0%|
|19.smt2                                                                                     |  59.963s  |  59.963s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|21.smt2                                                                                     |  59.963s  |  59.963s  |   0.000s  | 0.0%|
|22.smt2                                                                                     |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|23.smt2                                                                                     |  60.044s  |  60.044s  |   0.000s  | 0.0%|
|24.smt2                                                                                     |  59.942s  |  59.942s  |   0.000s  | 0.0%|
|25.smt2                                                                                     |  59.939s  |  59.939s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  58.471s  |  58.471s  |   0.000s  | 0.0%|
|27.smt2                                                                                     |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|28.smt2                                                                                     |  59.911s  |  59.911s  |   0.000s  | 0.0%|
|29.smt2                                                                                     |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|30.smt2                                                                                     |  59.996s  |  59.996s  |   0.000s  | 0.0%|
|31.smt2                                                                                     |  59.754s  |  59.754s  |   0.000s  | 0.0%|
|32.smt2                                                                                     |  59.937s  |  59.937s  |   0.000s  | 0.0%|
|33.smt2                                                                                     |   8.136s  |   8.136s  |   0.000s  | 0.0%|
|34.smt2                                                                                     |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|35.smt2                                                                                     |  52.309s  |  52.309s  |   0.000s  | 0.0%|
|36.smt2                                                                                     |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|37.smt2                                                                                     |  60.013s  |  60.013s  |   0.000s  | 0.0%|
|38.smt2                                                                                     |  59.853s  |  59.853s  |   0.000s  | 0.0%|
|39.smt2                                                                                     |  60.016s  |  60.016s  |   0.000s  | 0.0%|
|40.smt2                                                                                     |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  43.158s  |  43.158s  |   0.000s  | 0.0%|
|42.smt2                                                                                     |  59.816s  |  59.816s  |   0.000s  | 0.0%|
|43.smt2                                                                                     |   1.958s  |   1.958s  |   0.000s  | 0.0%|
|44.smt2                                                                                     |  59.980s  |  59.980s  |   0.000s  | 0.0%|
|45.smt2                                                                                     |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|46.smt2                                                                                     |  59.839s  |  59.839s  |   0.000s  | 0.0%|
|47.smt2                                                                                     |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|48.smt2                                                                                     |  45.156s  |  45.156s  |   0.000s  | 0.0%|
|49.smt2                                                                                     |  59.954s  |  59.954s  |   0.000s  | 0.0%|
|50.smt2                                                                                     |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|51.smt2                                                                                     |  59.903s  |  59.903s  |   0.000s  | 0.0%|
|52.smt2                                                                                     |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|53.smt2                                                                                     |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|54.smt2                                                                                     |  59.719s  |  59.719s  |   0.000s  | 0.0%|
|55.smt2                                                                                     |  59.776s  |  59.776s  |   0.000s  | 0.0%|
|56.smt2                                                                                     |  59.928s  |  59.928s  |   0.000s  | 0.0%|
|57.smt2                                                                                     |  59.971s  |  59.971s  |   0.000s  | 0.0%|
|58.smt2                                                                                     |  59.980s  |  59.980s  |   0.000s  | 0.0%|
|59.smt2                                                                                     |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|60.smt2                                                                                     |  59.978s  |  59.978s  |   0.000s  | 0.0%|
|61.smt2                                                                                     |  60.006s  |  60.006s  |   0.000s  | 0.0%|
|62.smt2                                                                                     |  59.986s  |  59.986s  |   0.000s  | 0.0%|
|63.smt2                                                                                     |  59.997s  |  59.997s  |   0.000s  | 0.0%|
|64.smt2                                                                                     |  59.758s  |  59.758s  |   0.000s  | 0.0%|
|65.smt2                                                                                     |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|66.smt2                                                                                     |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|67.smt2                                                                                     |  59.951s  |  59.951s  |   0.000s  | 0.0%|
|68.smt2                                                                                     |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|69.smt2                                                                                     |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|70.smt2                                                                                     |  59.958s  |  59.958s  |   0.000s  | 0.0%|
|71.smt2                                                                                     |  60.004s  |  60.004s  |   0.000s  | 0.0%|
|72.smt2                                                                                     |  59.965s  |  59.965s  |   0.000s  | 0.0%|
|73.smt2                                                                                     |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|74.smt2                                                                                     |  59.930s  |  59.930s  |   0.000s  | 0.0%|
|75.smt2                                                                                     |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|76.smt2                                                                                     |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|77.smt2                                                                                     |  59.961s  |  59.961s  |   0.000s  | 0.0%|
|78.smt2                                                                                     |  59.972s  |  59.972s  |   0.000s  | 0.0%|
|79.smt2                                                                                     |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|80.smt2                                                                                     |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|81.smt2                                                                                     |  59.948s  |  59.948s  |   0.000s  | 0.0%|
|82.smt2                                                                                     |  60.007s  |  60.007s  |   0.000s  | 0.0%|
|83.smt2                                                                                     |  59.971s  |  59.971s  |   0.000s  | 0.0%|
|84.smt2                                                                                     |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|85.smt2                                                                                     |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|86.smt2                                                                                     |  60.005s  |  60.005s  |   0.000s  | 0.0%|
|87.smt2                                                                                     |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|88.smt2                                                                                     |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|89.smt2                                                                                     |  59.959s  |  59.959s  |   0.000s  | 0.0%|
|90.smt2                                                                                     |  60.127s  |  60.127s  |   0.000s  | 0.0%|
|91.smt2                                                                                     |  59.869s  |  59.869s  |   0.000s  | 0.0%|
|92.smt2                                                                                     |  59.903s  |  59.903s  |   0.000s  | 0.0%|
|93.smt2                                                                                     |  59.950s  |  59.950s  |   0.000s  | 0.0%|
|94.smt2                                                                                     |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|95.smt2                                                                                     |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|96.smt2                                                                                     |  59.977s  |  59.977s  |   0.000s  | 0.0%|
|97.smt2                                                                                     |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|98.smt2                                                                                     |  59.991s  |  59.991s  |   0.000s  | 0.0%|
</details>
