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
Job description: 
Job tag: smt-60-clausal-lookahead-sequential-mcm
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: ce615ee116aefdd08e12c5dc7e63ba7c69b2315e
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" smt.sls.enable=true smt.sls.parallel=false model_validate=true sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_NIA_MCM
Z3 commit message: avoid repeated clauses during scoring function

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-60-clausal-lookahead-sequential-mcm
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: ce615ee116aefdd08e12c5dc7e63ba7c69b2315e
Z3 branch: master
Z3 options: "-T:60 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify smt)" smt.sls.enable=true smt.sls.parallel=false model_validate=true sls.arith_use_clausal_lookahead=true"
Z3 inputs: inputs/QF_NIA_MCM
Z3 commit message: avoid repeated clauses during scoring function

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  60.084s  |  60.084s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  59.916s  |  59.916s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |   2.828s  |   2.828s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  60.045s  |  60.045s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   0.320s  |   0.320s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |   0.716s  |   0.716s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |   5.073s  |   5.073s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  60.007s  |  60.007s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  60.031s  |  60.031s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |   2.236s  |   2.236s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  60.068s  |  60.068s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  60.006s  |  60.006s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   1.990s  |   1.990s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  59.949s  |  59.949s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   0.598s  |   0.598s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  60.084s  |  60.084s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  59.916s  |  59.916s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |   2.828s  |   2.828s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  60.045s  |  60.045s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   0.320s  |   0.320s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |   0.716s  |   0.716s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |   5.073s  |   5.073s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  60.007s  |  60.007s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  60.031s  |  60.031s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |   2.236s  |   2.236s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  60.068s  |  60.068s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  60.006s  |  60.006s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   1.990s  |   1.990s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  59.949s  |  59.949s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   0.598s  |   0.598s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  60.084s  |  60.084s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  59.916s  |  59.916s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |   2.828s  |   2.828s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  60.045s  |  60.045s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   0.320s  |   0.320s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |   0.716s  |   0.716s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |   5.073s  |   5.073s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  60.007s  |  60.007s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  60.031s  |  60.031s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |   2.236s  |   2.236s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  60.068s  |  60.068s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  60.006s  |  60.006s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   1.990s  |   1.990s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  59.949s  |  59.949s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   0.598s  |   0.598s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  60.084s  |  60.084s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  59.916s  |  59.916s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |   2.828s  |   2.828s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  60.045s  |  60.045s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   0.320s  |   0.320s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |   0.716s  |   0.716s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |   5.073s  |   5.073s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  60.007s  |  60.007s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  60.031s  |  60.031s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |   2.236s  |   2.236s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  60.068s  |  60.068s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  60.006s  |  60.006s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   1.990s  |   1.990s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  59.949s  |  59.949s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   0.598s  |   0.598s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|61.smt2                                                                                    |  60.296s |177.0MiB|
|67.smt2                                                                                    |  60.120s |183.0MiB|
|39.smt2                                                                                    |  60.105s |182.0MiB|
|01.smt2                                                                                    |  60.084s |152.0MiB|
|97.smt2                                                                                    |  60.081s |179.0MiB|
|105.smt2                                                                                   |  60.068s |218.0MiB|
|159.smt2                                                                                   |  60.048s |219.0MiB|
|85.smt2                                                                                    |  60.047s |148.0MiB|
|122.smt2                                                                                   |  60.047s |231.0MiB|
|51.smt2                                                                                    |  60.047s |219.0MiB|
|153.smt2                                                                                   |  60.046s |235.0MiB|
|05.smt2                                                                                    |  60.045s |199.0MiB|
|114.smt2                                                                                   |  60.045s |202.0MiB|
|167.smt2                                                                                   |  60.045s |235.0MiB|
|144.smt2                                                                                   |  60.044s |218.0MiB|
|94.smt2                                                                                    |  60.043s |184.0MiB|
|126.smt2                                                                                   |  60.040s |217.0MiB|
|135.smt2                                                                                   |  60.039s |219.0MiB|
|158.smt2                                                                                   |  60.037s |245.0MiB|
|142.smt2                                                                                   |  60.037s |224.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|61.smt2                                                                                    |  60.296s |177.0MiB|
|67.smt2                                                                                    |  60.120s |183.0MiB|
|39.smt2                                                                                    |  60.105s |182.0MiB|
|01.smt2                                                                                    |  60.084s |152.0MiB|
|97.smt2                                                                                    |  60.081s |179.0MiB|
|105.smt2                                                                                   |  60.068s |218.0MiB|
|159.smt2                                                                                   |  60.048s |219.0MiB|
|85.smt2                                                                                    |  60.047s |148.0MiB|
|122.smt2                                                                                   |  60.047s |231.0MiB|
|51.smt2                                                                                    |  60.047s |219.0MiB|
|153.smt2                                                                                   |  60.046s |235.0MiB|
|05.smt2                                                                                    |  60.045s |199.0MiB|
|114.smt2                                                                                   |  60.045s |202.0MiB|
|167.smt2                                                                                   |  60.045s |235.0MiB|
|144.smt2                                                                                   |  60.044s |218.0MiB|
|94.smt2                                                                                    |  60.043s |184.0MiB|
|126.smt2                                                                                   |  60.040s |217.0MiB|
|135.smt2                                                                                   |  60.039s |219.0MiB|
|158.smt2                                                                                   |  60.037s |245.0MiB|
|142.smt2                                                                                   |  60.037s |224.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |152.0MiB|152.0MiB|0B| 0.0%|
|02.smt2                                                                                     |158.0MiB|158.0MiB|0B| 0.0%|
|03.smt2                                                                                     |68.848MiB|68.848MiB|0B| 0.0%|
|04.smt2                                                                                     |131.0MiB|131.0MiB|0B| 0.0%|
|05.smt2                                                                                     |199.0MiB|199.0MiB|0B| 0.0%|
|06.smt2                                                                                     |58.368MiB|58.368MiB|0B| 0.0%|
|07.smt2                                                                                     |64.74MiB|64.74MiB|0B| 0.0%|
|08.smt2                                                                                     |106.0MiB|106.0MiB|0B| 0.0%|
|09.smt2                                                                                     |139.0MiB|139.0MiB|0B| 0.0%|
|10.smt2                                                                                     |70.792MiB|70.792MiB|0B| 0.0%|
|100.smt2                                                                                    |195.0MiB|195.0MiB|0B| 0.0%|
|101.smt2                                                                                    |205.0MiB|205.0MiB|0B| 0.0%|
|102.smt2                                                                                    |188.0MiB|188.0MiB|0B| 0.0%|
|103.smt2                                                                                    |182.0MiB|182.0MiB|0B| 0.0%|
|104.smt2                                                                                    |76.068MiB|76.068MiB|0B| 0.0%|
|105.smt2                                                                                    |218.0MiB|218.0MiB|0B| 0.0%|
|106.smt2                                                                                    |213.0MiB|213.0MiB|0B| 0.0%|
|107.smt2                                                                                    |75.236MiB|75.236MiB|0B| 0.0%|
|108.smt2                                                                                    |226.0MiB|226.0MiB|0B| 0.0%|
|109.smt2                                                                                    |67.1MiB|67.1MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |152.0MiB|152.0MiB|0B| 0.0%|
|02.smt2                                                                                     |158.0MiB|158.0MiB|0B| 0.0%|
|03.smt2                                                                                     |68.848MiB|68.848MiB|0B| 0.0%|
|04.smt2                                                                                     |131.0MiB|131.0MiB|0B| 0.0%|
|05.smt2                                                                                     |199.0MiB|199.0MiB|0B| 0.0%|
|06.smt2                                                                                     |58.368MiB|58.368MiB|0B| 0.0%|
|07.smt2                                                                                     |64.74MiB|64.74MiB|0B| 0.0%|
|08.smt2                                                                                     |106.0MiB|106.0MiB|0B| 0.0%|
|09.smt2                                                                                     |139.0MiB|139.0MiB|0B| 0.0%|
|10.smt2                                                                                     |70.792MiB|70.792MiB|0B| 0.0%|
|100.smt2                                                                                    |195.0MiB|195.0MiB|0B| 0.0%|
|101.smt2                                                                                    |205.0MiB|205.0MiB|0B| 0.0%|
|102.smt2                                                                                    |188.0MiB|188.0MiB|0B| 0.0%|
|103.smt2                                                                                    |182.0MiB|182.0MiB|0B| 0.0%|
|104.smt2                                                                                    |76.068MiB|76.068MiB|0B| 0.0%|
|105.smt2                                                                                    |218.0MiB|218.0MiB|0B| 0.0%|
|106.smt2                                                                                    |213.0MiB|213.0MiB|0B| 0.0%|
|107.smt2                                                                                    |75.236MiB|75.236MiB|0B| 0.0%|
|108.smt2                                                                                    |226.0MiB|226.0MiB|0B| 0.0%|
|109.smt2                                                                                    |67.1MiB|67.1MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |152.0MiB|152.0MiB|0B| 0.0%|
|02.smt2                                                                                     |158.0MiB|158.0MiB|0B| 0.0%|
|03.smt2                                                                                     |68.848MiB|68.848MiB|0B| 0.0%|
|04.smt2                                                                                     |131.0MiB|131.0MiB|0B| 0.0%|
|05.smt2                                                                                     |199.0MiB|199.0MiB|0B| 0.0%|
|06.smt2                                                                                     |58.368MiB|58.368MiB|0B| 0.0%|
|07.smt2                                                                                     |64.74MiB|64.74MiB|0B| 0.0%|
|08.smt2                                                                                     |106.0MiB|106.0MiB|0B| 0.0%|
|09.smt2                                                                                     |139.0MiB|139.0MiB|0B| 0.0%|
|10.smt2                                                                                     |70.792MiB|70.792MiB|0B| 0.0%|
|100.smt2                                                                                    |195.0MiB|195.0MiB|0B| 0.0%|
|101.smt2                                                                                    |205.0MiB|205.0MiB|0B| 0.0%|
|102.smt2                                                                                    |188.0MiB|188.0MiB|0B| 0.0%|
|103.smt2                                                                                    |182.0MiB|182.0MiB|0B| 0.0%|
|104.smt2                                                                                    |76.068MiB|76.068MiB|0B| 0.0%|
|105.smt2                                                                                    |218.0MiB|218.0MiB|0B| 0.0%|
|106.smt2                                                                                    |213.0MiB|213.0MiB|0B| 0.0%|
|107.smt2                                                                                    |75.236MiB|75.236MiB|0B| 0.0%|
|108.smt2                                                                                    |226.0MiB|226.0MiB|0B| 0.0%|
|109.smt2                                                                                    |67.1MiB|67.1MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |152.0MiB|152.0MiB|0B| 0.0%|
|02.smt2                                                                                     |158.0MiB|158.0MiB|0B| 0.0%|
|03.smt2                                                                                     |68.848MiB|68.848MiB|0B| 0.0%|
|04.smt2                                                                                     |131.0MiB|131.0MiB|0B| 0.0%|
|05.smt2                                                                                     |199.0MiB|199.0MiB|0B| 0.0%|
|06.smt2                                                                                     |58.368MiB|58.368MiB|0B| 0.0%|
|07.smt2                                                                                     |64.74MiB|64.74MiB|0B| 0.0%|
|08.smt2                                                                                     |106.0MiB|106.0MiB|0B| 0.0%|
|09.smt2                                                                                     |139.0MiB|139.0MiB|0B| 0.0%|
|10.smt2                                                                                     |70.792MiB|70.792MiB|0B| 0.0%|
|100.smt2                                                                                    |195.0MiB|195.0MiB|0B| 0.0%|
|101.smt2                                                                                    |205.0MiB|205.0MiB|0B| 0.0%|
|102.smt2                                                                                    |188.0MiB|188.0MiB|0B| 0.0%|
|103.smt2                                                                                    |182.0MiB|182.0MiB|0B| 0.0%|
|104.smt2                                                                                    |76.068MiB|76.068MiB|0B| 0.0%|
|105.smt2                                                                                    |218.0MiB|218.0MiB|0B| 0.0%|
|106.smt2                                                                                    |213.0MiB|213.0MiB|0B| 0.0%|
|107.smt2                                                                                    |75.236MiB|75.236MiB|0B| 0.0%|
|108.smt2                                                                                    |226.0MiB|226.0MiB|0B| 0.0%|
|109.smt2                                                                                    |67.1MiB|67.1MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|185.smt2                                                                                   |  60.032s |1126.0MiB|
|186.smt2                                                                                   |  59.770s |1078.0MiB|
|182.smt2                                                                                   |  59.993s |730.0MiB|
|184.smt2                                                                                   |  60.016s |702.0MiB|
|183.smt2                                                                                   |  60.024s |670.0MiB|
|178.smt2                                                                                   |  59.966s |471.0MiB|
|181.smt2                                                                                   |  60.019s |444.0MiB|
|179.smt2                                                                                   |  60.018s |388.0MiB|
|173.smt2                                                                                   |  59.995s |372.0MiB|
|180.smt2                                                                                   |  60.007s |365.0MiB|
|172.smt2                                                                                   |  60.012s |361.0MiB|
|176.smt2                                                                                   |  59.999s |359.0MiB|
|174.smt2                                                                                   |  59.985s |332.0MiB|
|175.smt2                                                                                   |  60.009s |329.0MiB|
|165.smt2                                                                                   |  59.968s |309.0MiB|
|168.smt2                                                                                   |  60.014s |278.0MiB|
|163.smt2                                                                                   |  60.005s |273.0MiB|
|169.smt2                                                                                   |  59.981s |270.0MiB|
|160.smt2                                                                                   |  60.034s |265.0MiB|
|171.smt2                                                                                   |  60.015s |250.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|185.smt2                                                                                   |  60.032s |1126.0MiB|
|186.smt2                                                                                   |  59.770s |1078.0MiB|
|182.smt2                                                                                   |  59.993s |730.0MiB|
|184.smt2                                                                                   |  60.016s |702.0MiB|
|183.smt2                                                                                   |  60.024s |670.0MiB|
|178.smt2                                                                                   |  59.966s |471.0MiB|
|181.smt2                                                                                   |  60.019s |444.0MiB|
|179.smt2                                                                                   |  60.018s |388.0MiB|
|173.smt2                                                                                   |  59.995s |372.0MiB|
|180.smt2                                                                                   |  60.007s |365.0MiB|
|172.smt2                                                                                   |  60.012s |361.0MiB|
|176.smt2                                                                                   |  59.999s |359.0MiB|
|174.smt2                                                                                   |  59.985s |332.0MiB|
|175.smt2                                                                                   |  60.009s |329.0MiB|
|165.smt2                                                                                   |  59.968s |309.0MiB|
|168.smt2                                                                                   |  60.014s |278.0MiB|
|163.smt2                                                                                   |  60.005s |273.0MiB|
|169.smt2                                                                                   |  59.981s |270.0MiB|
|160.smt2                                                                                   |  60.034s |265.0MiB|
|171.smt2                                                                                   |  60.015s |250.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|01.smt2                                                                                     |  60.084s  |  60.084s  |   0.000s  | 0.0%|
|02.smt2                                                                                     |  59.916s  |  59.916s  |   0.000s  | 0.0%|
|03.smt2                                                                                     |   2.828s  |   2.828s  |   0.000s  | 0.0%|
|04.smt2                                                                                     |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|05.smt2                                                                                     |  60.045s  |  60.045s  |   0.000s  | 0.0%|
|06.smt2                                                                                     |   0.320s  |   0.320s  |   0.000s  | 0.0%|
|07.smt2                                                                                     |   0.716s  |   0.716s  |   0.000s  | 0.0%|
|08.smt2                                                                                     |  59.991s  |  59.991s  |   0.000s  | 0.0%|
|09.smt2                                                                                     |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|10.smt2                                                                                     |   5.073s  |   5.073s  |   0.000s  | 0.0%|
|100.smt2                                                                                    |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|101.smt2                                                                                    |  60.007s  |  60.007s  |   0.000s  | 0.0%|
|102.smt2                                                                                    |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|103.smt2                                                                                    |  60.031s  |  60.031s  |   0.000s  | 0.0%|
|104.smt2                                                                                    |   2.236s  |   2.236s  |   0.000s  | 0.0%|
|105.smt2                                                                                    |  60.068s  |  60.068s  |   0.000s  | 0.0%|
|106.smt2                                                                                    |  60.006s  |  60.006s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   1.990s  |   1.990s  |   0.000s  | 0.0%|
|108.smt2                                                                                    |  59.949s  |  59.949s  |   0.000s  | 0.0%|
|109.smt2                                                                                    |   0.598s  |   0.598s  |   0.000s  | 0.0%|
|11.smt2                                                                                     |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|110.smt2                                                                                    |  60.010s  |  60.010s  |   0.000s  | 0.0%|
|111.smt2                                                                                    |  59.645s  |  59.645s  |   0.000s  | 0.0%|
|112.smt2                                                                                    |   8.260s  |   8.260s  |   0.000s  | 0.0%|
|113.smt2                                                                                    |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|114.smt2                                                                                    |  60.045s  |  60.045s  |   0.000s  | 0.0%|
|115.smt2                                                                                    |   1.397s  |   1.397s  |   0.000s  | 0.0%|
|116.smt2                                                                                    |  60.001s  |  60.001s  |   0.000s  | 0.0%|
|117.smt2                                                                                    |   0.538s  |   0.538s  |   0.000s  | 0.0%|
|118.smt2                                                                                    |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|119.smt2                                                                                    |  59.817s  |  59.817s  |   0.000s  | 0.0%|
|12.smt2                                                                                     |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|120.smt2                                                                                    |  59.844s  |  59.844s  |   0.000s  | 0.0%|
|121.smt2                                                                                    |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|122.smt2                                                                                    |  60.047s  |  60.047s  |   0.000s  | 0.0%|
|123.smt2                                                                                    |   8.306s  |   8.306s  |   0.000s  | 0.0%|
|124.smt2                                                                                    |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|125.smt2                                                                                    |  59.980s  |  59.980s  |   0.000s  | 0.0%|
|126.smt2                                                                                    |  60.040s  |  60.040s  |   0.000s  | 0.0%|
|127.smt2                                                                                    |  60.025s  |  60.025s  |   0.000s  | 0.0%|
|128.smt2                                                                                    |  60.022s  |  60.022s  |   0.000s  | 0.0%|
|129.smt2                                                                                    |  59.952s  |  59.952s  |   0.000s  | 0.0%|
|13.smt2                                                                                     |   0.856s  |   0.856s  |   0.000s  | 0.0%|
|130.smt2                                                                                    |  60.011s  |  60.011s  |   0.000s  | 0.0%|
|131.smt2                                                                                    |  59.897s  |  59.897s  |   0.000s  | 0.0%|
|132.smt2                                                                                    |  60.004s  |  60.004s  |   0.000s  | 0.0%|
|133.smt2                                                                                    |  59.852s  |  59.852s  |   0.000s  | 0.0%|
|134.smt2                                                                                    |  59.948s  |  59.948s  |   0.000s  | 0.0%|
|135.smt2                                                                                    |  60.039s  |  60.039s  |   0.000s  | 0.0%|
|136.smt2                                                                                    |  59.983s  |  59.983s  |   0.000s  | 0.0%|
|137.smt2                                                                                    |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|138.smt2                                                                                    |  59.949s  |  59.949s  |   0.000s  | 0.0%|
|139.smt2                                                                                    |  60.015s  |  60.015s  |   0.000s  | 0.0%|
|14.smt2                                                                                     |   0.521s  |   0.521s  |   0.000s  | 0.0%|
|140.smt2                                                                                    |  59.840s  |  59.840s  |   0.000s  | 0.0%|
|141.smt2                                                                                    |  60.034s  |  60.034s  |   0.000s  | 0.0%|
|142.smt2                                                                                    |  60.037s  |  60.037s  |   0.000s  | 0.0%|
|143.smt2                                                                                    |  60.000s  |  60.000s  |   0.000s  | 0.0%|
|144.smt2                                                                                    |  60.044s  |  60.044s  |   0.000s  | 0.0%|
|145.smt2                                                                                    |  60.012s  |  60.012s  |   0.000s  | 0.0%|
|146.smt2                                                                                    |  59.982s  |  59.982s  |   0.000s  | 0.0%|
|147.smt2                                                                                    |  59.989s  |  59.989s  |   0.000s  | 0.0%|
|148.smt2                                                                                    |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|149.smt2                                                                                    |  59.899s  |  59.899s  |   0.000s  | 0.0%|
|15.smt2                                                                                     |   0.604s  |   0.604s  |   0.000s  | 0.0%|
|150.smt2                                                                                    |  59.966s  |  59.966s  |   0.000s  | 0.0%|
|151.smt2                                                                                    |  59.994s  |  59.994s  |   0.000s  | 0.0%|
|152.smt2                                                                                    |   5.912s  |   5.912s  |   0.000s  | 0.0%|
|153.smt2                                                                                    |  60.046s  |  60.046s  |   0.000s  | 0.0%|
|154.smt2                                                                                    |  60.014s  |  60.014s  |   0.000s  | 0.0%|
|155.smt2                                                                                    |  60.009s  |  60.009s  |   0.000s  | 0.0%|
|156.smt2                                                                                    |  59.939s  |  59.939s  |   0.000s  | 0.0%|
|157.smt2                                                                                    |  59.966s  |  59.966s  |   0.000s  | 0.0%|
|158.smt2                                                                                    |  60.037s  |  60.037s  |   0.000s  | 0.0%|
|159.smt2                                                                                    |  60.048s  |  60.048s  |   0.000s  | 0.0%|
|16.smt2                                                                                     |  60.004s  |  60.004s  |   0.000s  | 0.0%|
|160.smt2                                                                                    |  60.034s  |  60.034s  |   0.000s  | 0.0%|
|161.smt2                                                                                    |  60.015s  |  60.015s  |   0.000s  | 0.0%|
|162.smt2                                                                                    |   2.772s  |   2.772s  |   0.000s  | 0.0%|
|163.smt2                                                                                    |  60.005s  |  60.005s  |   0.000s  | 0.0%|
|164.smt2                                                                                    |   3.206s  |   3.206s  |   0.000s  | 0.0%|
|165.smt2                                                                                    |  59.968s  |  59.968s  |   0.000s  | 0.0%|
|166.smt2                                                                                    |   0.594s  |   0.594s  |   0.000s  | 0.0%|
|167.smt2                                                                                    |  60.045s  |  60.045s  |   0.000s  | 0.0%|
|168.smt2                                                                                    |  60.014s  |  60.014s  |   0.000s  | 0.0%|
|169.smt2                                                                                    |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|17.smt2                                                                                     |  60.037s  |  60.037s  |   0.000s  | 0.0%|
|170.smt2                                                                                    |   0.444s  |   0.444s  |   0.000s  | 0.0%|
|171.smt2                                                                                    |  60.015s  |  60.015s  |   0.000s  | 0.0%|
|172.smt2                                                                                    |  60.012s  |  60.012s  |   0.000s  | 0.0%|
|173.smt2                                                                                    |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|174.smt2                                                                                    |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|175.smt2                                                                                    |  60.009s  |  60.009s  |   0.000s  | 0.0%|
|176.smt2                                                                                    |  59.999s  |  59.999s  |   0.000s  | 0.0%|
|177.smt2                                                                                    |   9.756s  |   9.756s  |   0.000s  | 0.0%|
|178.smt2                                                                                    |  59.966s  |  59.966s  |   0.000s  | 0.0%|
|179.smt2                                                                                    |  60.018s  |  60.018s  |   0.000s  | 0.0%|
|18.smt2                                                                                     |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|180.smt2                                                                                    |  60.007s  |  60.007s  |   0.000s  | 0.0%|
|181.smt2                                                                                    |  60.019s  |  60.019s  |   0.000s  | 0.0%|
|182.smt2                                                                                    |  59.993s  |  59.993s  |   0.000s  | 0.0%|
|183.smt2                                                                                    |  60.024s  |  60.024s  |   0.000s  | 0.0%|
|184.smt2                                                                                    |  60.016s  |  60.016s  |   0.000s  | 0.0%|
|185.smt2                                                                                    |  60.032s  |  60.032s  |   0.000s  | 0.0%|
|186.smt2                                                                                    |  59.770s  |  59.770s  |   0.000s  | 0.0%|
|19.smt2                                                                                     |  59.998s  |  59.998s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |  60.033s  |  60.033s  |   0.000s  | 0.0%|
|21.smt2                                                                                     |  59.990s  |  59.990s  |   0.000s  | 0.0%|
|22.smt2                                                                                     |  60.015s  |  60.015s  |   0.000s  | 0.0%|
|23.smt2                                                                                     |  60.026s  |  60.026s  |   0.000s  | 0.0%|
|24.smt2                                                                                     |  59.980s  |  59.980s  |   0.000s  | 0.0%|
|25.smt2                                                                                     |  60.036s  |  60.036s  |   0.000s  | 0.0%|
|26.smt2                                                                                     |  59.971s  |  59.971s  |   0.000s  | 0.0%|
|27.smt2                                                                                     |  59.960s  |  59.960s  |   0.000s  | 0.0%|
|28.smt2                                                                                     |  59.862s  |  59.862s  |   0.000s  | 0.0%|
|29.smt2                                                                                     |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|30.smt2                                                                                     |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|31.smt2                                                                                     |  60.023s  |  60.023s  |   0.000s  | 0.0%|
|32.smt2                                                                                     |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|33.smt2                                                                                     |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|34.smt2                                                                                     |  60.023s  |  60.023s  |   0.000s  | 0.0%|
|35.smt2                                                                                     |  60.016s  |  60.016s  |   0.000s  | 0.0%|
|36.smt2                                                                                     |  59.963s  |  59.963s  |   0.000s  | 0.0%|
|37.smt2                                                                                     |  60.025s  |  60.025s  |   0.000s  | 0.0%|
|38.smt2                                                                                     |  59.790s  |  59.790s  |   0.000s  | 0.0%|
|39.smt2                                                                                     |  60.105s  |  60.105s  |   0.000s  | 0.0%|
|40.smt2                                                                                     |  59.851s  |  59.851s  |   0.000s  | 0.0%|
|41.smt2                                                                                     |  60.015s  |  60.015s  |   0.000s  | 0.0%|
|42.smt2                                                                                     |  59.781s  |  59.781s  |   0.000s  | 0.0%|
|43.smt2                                                                                     |   1.634s  |   1.634s  |   0.000s  | 0.0%|
|44.smt2                                                                                     |  59.413s  |  59.413s  |   0.000s  | 0.0%|
|45.smt2                                                                                     |   0.319s  |   0.319s  |   0.000s  | 0.0%|
|46.smt2                                                                                     |  59.632s  |  59.632s  |   0.000s  | 0.0%|
|47.smt2                                                                                     |  60.012s  |  60.012s  |   0.000s  | 0.0%|
|48.smt2                                                                                     |  60.006s  |  60.006s  |   0.000s  | 0.0%|
|49.smt2                                                                                     |  60.022s  |  60.022s  |   0.000s  | 0.0%|
|50.smt2                                                                                     |  59.972s  |  59.972s  |   0.000s  | 0.0%|
|51.smt2                                                                                     |  60.047s  |  60.047s  |   0.000s  | 0.0%|
|52.smt2                                                                                     |  59.927s  |  59.927s  |   0.000s  | 0.0%|
|53.smt2                                                                                     |  60.012s  |  60.012s  |   0.000s  | 0.0%|
|54.smt2                                                                                     |  59.875s  |  59.875s  |   0.000s  | 0.0%|
|55.smt2                                                                                     |  59.972s  |  59.972s  |   0.000s  | 0.0%|
|56.smt2                                                                                     |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|57.smt2                                                                                     |  59.984s  |  59.984s  |   0.000s  | 0.0%|
|58.smt2                                                                                     |  59.882s  |  59.882s  |   0.000s  | 0.0%|
|59.smt2                                                                                     |  60.004s  |  60.004s  |   0.000s  | 0.0%|
|60.smt2                                                                                     |  60.024s  |  60.024s  |   0.000s  | 0.0%|
|61.smt2                                                                                     |  60.296s  |  60.296s  |   0.000s  | 0.0%|
|62.smt2                                                                                     |  59.967s  |  59.967s  |   0.000s  | 0.0%|
|63.smt2                                                                                     |  59.892s  |  59.892s  |   0.000s  | 0.0%|
|64.smt2                                                                                     |  59.976s  |  59.976s  |   0.000s  | 0.0%|
|65.smt2                                                                                     |  59.988s  |  59.988s  |   0.000s  | 0.0%|
|66.smt2                                                                                     |  60.002s  |  60.002s  |   0.000s  | 0.0%|
|67.smt2                                                                                     |  60.120s  |  60.120s  |   0.000s  | 0.0%|
|68.smt2                                                                                     |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|69.smt2                                                                                     |  59.796s  |  59.796s  |   0.000s  | 0.0%|
|70.smt2                                                                                     |  59.979s  |  59.979s  |   0.000s  | 0.0%|
|71.smt2                                                                                     |  59.939s  |  59.939s  |   0.000s  | 0.0%|
|72.smt2                                                                                     |  59.975s  |  59.975s  |   0.000s  | 0.0%|
|73.smt2                                                                                     |  60.013s  |  60.013s  |   0.000s  | 0.0%|
|74.smt2                                                                                     |  60.034s  |  60.034s  |   0.000s  | 0.0%|
|75.smt2                                                                                     |  59.962s  |  59.962s  |   0.000s  | 0.0%|
|76.smt2                                                                                     |  59.943s  |  59.943s  |   0.000s  | 0.0%|
|77.smt2                                                                                     |  59.946s  |  59.946s  |   0.000s  | 0.0%|
|78.smt2                                                                                     |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|79.smt2                                                                                     |  59.992s  |  59.992s  |   0.000s  | 0.0%|
|80.smt2                                                                                     |  59.872s  |  59.872s  |   0.000s  | 0.0%|
|81.smt2                                                                                     |  59.930s  |  59.930s  |   0.000s  | 0.0%|
|82.smt2                                                                                     |  60.005s  |  60.005s  |   0.000s  | 0.0%|
|83.smt2                                                                                     |  59.913s  |  59.913s  |   0.000s  | 0.0%|
|84.smt2                                                                                     |  60.028s  |  60.028s  |   0.000s  | 0.0%|
|85.smt2                                                                                     |  60.047s  |  60.047s  |   0.000s  | 0.0%|
|86.smt2                                                                                     |  59.974s  |  59.974s  |   0.000s  | 0.0%|
|87.smt2                                                                                     |  59.985s  |  59.985s  |   0.000s  | 0.0%|
|88.smt2                                                                                     |  60.010s  |  60.010s  |   0.000s  | 0.0%|
|89.smt2                                                                                     |  59.995s  |  59.995s  |   0.000s  | 0.0%|
|90.smt2                                                                                     |  59.867s  |  59.867s  |   0.000s  | 0.0%|
|91.smt2                                                                                     |  59.981s  |  59.981s  |   0.000s  | 0.0%|
|92.smt2                                                                                     |  59.688s  |  59.688s  |   0.000s  | 0.0%|
|93.smt2                                                                                     |  60.009s  |  60.009s  |   0.000s  | 0.0%|
|94.smt2                                                                                     |  60.043s  |  60.043s  |   0.000s  | 0.0%|
|95.smt2                                                                                     |  60.023s  |  60.023s  |   0.000s  | 0.0%|
|96.smt2                                                                                     |  60.013s  |  60.013s  |   0.000s  | 0.0%|
|97.smt2                                                                                     |  60.081s  |  60.081s  |   0.000s  | 0.0%|
|98.smt2                                                                                     |  60.032s  |  60.032s  |   0.000s  | 0.0%|
</details>
