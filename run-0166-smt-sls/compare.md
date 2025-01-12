Comparing data and data


# SUMMARY
- LHS tests = 186
- RHS tests = 186
- LHS success = 2  (1.075268817204301%)
- RHS success = 2  (1.075268817204301%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: fa22b646aa5965a8e4d79eef54e26707fe9931fc
Z3 branch: master
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: inputs/QF_NIA_MCM
Z3 commit message: address some build warnings.

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: smt-sls
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: fa22b646aa5965a8e4d79eef54e26707fe9931fc
Z3 branch: master
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: inputs/QF_NIA_MCM
Z3 commit message: address some build warnings.

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|185.smt2                                                                                    |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|186.smt2                                                                                    |  20.006s  |  20.006s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|185.smt2                                                                                    |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|186.smt2                                                                                    |  20.006s  |  20.006s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|185.smt2                                                                                    |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|186.smt2                                                                                    |  20.006s  |  20.006s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|185.smt2                                                                                    |  20.004s  |  20.004s  |   0.000s  | 0.0%|
|186.smt2                                                                                    |  20.006s  |  20.006s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|186.smt2                                                                                   |  20.006s |245.0MiB|
|185.smt2                                                                                   |  20.004s |245.0MiB|
|184.smt2                                                                                   |  13.012s |408.0MiB|
|182.smt2                                                                                   |   5.678s |271.0MiB|
|183.smt2                                                                                   |   5.456s |271.0MiB|
|178.smt2                                                                                   |   2.839s |150.0MiB|
|181.smt2                                                                                   |   2.609s |153.0MiB|
|176.smt2                                                                                   |   2.485s |142.0MiB|
|172.smt2                                                                                   |   2.440s |143.0MiB|
|180.smt2                                                                                   |   2.276s |146.0MiB|
|179.smt2                                                                                   |   2.074s |146.0MiB|
|173.smt2                                                                                   |   2.032s |137.0MiB|
|175.smt2                                                                                   |   1.930s |131.0MiB|
|174.smt2                                                                                   |   1.816s |131.0MiB|
|169.smt2                                                                                   |   0.975s |77.932MiB|
|163.smt2                                                                                   |   0.942s |73.648MiB|
|168.smt2                                                                                   |   0.934s |67.068MiB|
|167.smt2                                                                                   |   0.865s |57.948MiB|
|161.smt2                                                                                   |   0.828s |72.86MiB|
|165.smt2                                                                                   |   0.807s |75.944MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|186.smt2                                                                                   |  20.006s |245.0MiB|
|185.smt2                                                                                   |  20.004s |245.0MiB|
|184.smt2                                                                                   |  13.012s |408.0MiB|
|182.smt2                                                                                   |   5.678s |271.0MiB|
|183.smt2                                                                                   |   5.456s |271.0MiB|
|178.smt2                                                                                   |   2.839s |150.0MiB|
|181.smt2                                                                                   |   2.609s |153.0MiB|
|176.smt2                                                                                   |   2.485s |142.0MiB|
|172.smt2                                                                                   |   2.440s |143.0MiB|
|180.smt2                                                                                   |   2.276s |146.0MiB|
|179.smt2                                                                                   |   2.074s |146.0MiB|
|173.smt2                                                                                   |   2.032s |137.0MiB|
|175.smt2                                                                                   |   1.930s |131.0MiB|
|174.smt2                                                                                   |   1.816s |131.0MiB|
|169.smt2                                                                                   |   0.975s |77.932MiB|
|163.smt2                                                                                   |   0.942s |73.648MiB|
|168.smt2                                                                                   |   0.934s |67.068MiB|
|167.smt2                                                                                   |   0.865s |57.948MiB|
|161.smt2                                                                                   |   0.828s |72.86MiB|
|165.smt2                                                                                   |   0.807s |75.944MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|185.smt2                                                                                    |245.0MiB|245.0MiB|0B| 0.0%|
|186.smt2                                                                                    |245.0MiB|245.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|185.smt2                                                                                    |245.0MiB|245.0MiB|0B| 0.0%|
|186.smt2                                                                                    |245.0MiB|245.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|185.smt2                                                                                    |245.0MiB|245.0MiB|0B| 0.0%|
|186.smt2                                                                                    |245.0MiB|245.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|185.smt2                                                                                    |245.0MiB|245.0MiB|0B| 0.0%|
|186.smt2                                                                                    |245.0MiB|245.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|184.smt2                                                                                   |  13.012s |408.0MiB|
|182.smt2                                                                                   |   5.678s |271.0MiB|
|183.smt2                                                                                   |   5.456s |271.0MiB|
|186.smt2                                                                                   |  20.006s |245.0MiB|
|185.smt2                                                                                   |  20.004s |245.0MiB|
|181.smt2                                                                                   |   2.609s |153.0MiB|
|178.smt2                                                                                   |   2.839s |150.0MiB|
|180.smt2                                                                                   |   2.276s |146.0MiB|
|179.smt2                                                                                   |   2.074s |146.0MiB|
|172.smt2                                                                                   |   2.440s |143.0MiB|
|176.smt2                                                                                   |   2.485s |142.0MiB|
|173.smt2                                                                                   |   2.032s |137.0MiB|
|175.smt2                                                                                   |   1.930s |131.0MiB|
|174.smt2                                                                                   |   1.816s |131.0MiB|
|169.smt2                                                                                   |   0.975s |77.932MiB|
|165.smt2                                                                                   |   0.807s |75.944MiB|
|163.smt2                                                                                   |   0.942s |73.648MiB|
|161.smt2                                                                                   |   0.828s |72.86MiB|
|168.smt2                                                                                   |   0.934s |67.068MiB|
|160.smt2                                                                                   |   0.696s |60.492MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|184.smt2                                                                                   |  13.012s |408.0MiB|
|182.smt2                                                                                   |   5.678s |271.0MiB|
|183.smt2                                                                                   |   5.456s |271.0MiB|
|186.smt2                                                                                   |  20.006s |245.0MiB|
|185.smt2                                                                                   |  20.004s |245.0MiB|
|181.smt2                                                                                   |   2.609s |153.0MiB|
|178.smt2                                                                                   |   2.839s |150.0MiB|
|180.smt2                                                                                   |   2.276s |146.0MiB|
|179.smt2                                                                                   |   2.074s |146.0MiB|
|172.smt2                                                                                   |   2.440s |143.0MiB|
|176.smt2                                                                                   |   2.485s |142.0MiB|
|173.smt2                                                                                   |   2.032s |137.0MiB|
|175.smt2                                                                                   |   1.930s |131.0MiB|
|174.smt2                                                                                   |   1.816s |131.0MiB|
|169.smt2                                                                                   |   0.975s |77.932MiB|
|165.smt2                                                                                   |   0.807s |75.944MiB|
|163.smt2                                                                                   |   0.942s |73.648MiB|
|161.smt2                                                                                   |   0.828s |72.86MiB|
|168.smt2                                                                                   |   0.934s |67.068MiB|
|160.smt2                                                                                   |   0.696s |60.492MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|185.smt2                                                                                    |  20.004s  |  20.004s  |   0.000s  | 0.0%|
</details>
