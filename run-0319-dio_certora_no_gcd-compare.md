Comparing data and data


# SUMMARY
- LHS tests = 308
- RHS tests = 308
- LHS success = 308  (100.0%)
- RHS success = 308  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: dio_certora_no_gcd
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 7ee34151501242638597e0af7e4c3e1cd5934046
Z3 branch: 
Z3 options: "-T:600 -st lp.dio=true lp.dio_run_gcd=false"
Z3 inputs: inputs/certora
Z3 commit message: make gcd call in dio optional

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: dio_certora_no_gcd
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 7ee34151501242638597e0af7e4c3e1cd5934046
Z3 branch: 
Z3 options: "-T:600 -st lp.dio=true lp.dio_run_gcd=false"
Z3 inputs: inputs/certora
Z3 commit message: make gcd call in dio optional

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |   1.608s  |   1.608s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |   0.948s  |   0.948s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |   2.402s  |   2.402s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   1.708s  |   1.708s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |   0.875s  |   0.875s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |   1.598s  |   1.598s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |   1.112s  |   1.112s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   1.031s  |   1.031s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |  15.216s  |  15.216s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |   1.589s  |   1.589s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 | 599.493s  | 599.493s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   4.109s  |   4.109s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               | 599.336s  | 599.336s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |  60.892s  |  60.892s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 | 599.601s  | 599.601s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  34.687s  |  34.687s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |   5.486s  |   5.486s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |  39.489s  |  39.489s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |  12.027s  |  12.027s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  18.041s  |  18.041s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |   1.608s  |   1.608s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |   0.948s  |   0.948s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |   2.402s  |   2.402s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   1.708s  |   1.708s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |   0.875s  |   0.875s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |   1.598s  |   1.598s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |   1.112s  |   1.112s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   1.031s  |   1.031s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |  15.216s  |  15.216s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |   1.589s  |   1.589s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 | 599.493s  | 599.493s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   4.109s  |   4.109s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               | 599.336s  | 599.336s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |  60.892s  |  60.892s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 | 599.601s  | 599.601s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  34.687s  |  34.687s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |   5.486s  |   5.486s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |  39.489s  |  39.489s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |  12.027s  |  12.027s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  18.041s  |  18.041s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |   1.608s  |   1.608s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |   0.948s  |   0.948s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |   2.402s  |   2.402s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   1.708s  |   1.708s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |   0.875s  |   0.875s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |   1.598s  |   1.598s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |   1.112s  |   1.112s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   1.031s  |   1.031s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |  15.216s  |  15.216s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |   1.589s  |   1.589s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 | 599.493s  | 599.493s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   4.109s  |   4.109s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               | 599.336s  | 599.336s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |  60.892s  |  60.892s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 | 599.601s  | 599.601s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  34.687s  |  34.687s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |   5.486s  |   5.486s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |  39.489s  |  39.489s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |  12.027s  |  12.027s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  18.041s  |  18.041s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |   1.608s  |   1.608s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |   0.948s  |   0.948s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |   2.402s  |   2.402s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   1.708s  |   1.708s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |   0.875s  |   0.875s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |   1.598s  |   1.598s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |   1.112s  |   1.112s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   1.031s  |   1.031s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |  15.216s  |  15.216s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |   1.589s  |   1.589s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 | 599.493s  | 599.493s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   4.109s  |   4.109s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               | 599.336s  | 599.336s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |  60.892s  |  60.892s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 | 599.601s  | 599.601s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  34.687s  |  34.687s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |   5.486s  |   5.486s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |  39.489s  |  39.489s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |  12.027s  |  12.027s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  18.041s  |  18.041s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFLIA.smt2                                    | 600.010s |2249.0MiB|
|38347_525a1ca0331f2bcbf520_54_QF_UFLIA.smt2                                                | 599.897s |2217.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFLIA.smt2                                    | 599.890s |1343.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 | 599.886s |967.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTLIA.smt2                                  | 599.848s |2056.0MiB|
|38347_092cc73601c78e45f4f9_57_QF_UFDTLIA.smt2                                              | 599.839s |32.324MiB|
|66603_accdadf23a1cf70ae043_76_QF_UFNIA.smt2                                                | 599.830s |1545.0MiB|
|66603_accdadf23a1cf70ae043_74_QF_UFNIA.smt2                                                | 599.823s |640.0MiB|
|66603_accdadf23a1cf70ae043_73_QF_UFLIA.smt2                                                | 599.802s |802.0MiB|
|83314_a702bf8b823398c9e37a_1_UFDTLIA.smt2                                                  | 599.787s |678.0MiB|
|72658_63104dadde9c6026353f_71_QF_UFLIA.smt2                                                | 599.785s |329.0MiB|
|940_590f27b1c3c800d3243e_33_QF_UFLIA.smt2                                                  | 599.775s |439.0MiB|
|65782_cd31513fdcd15701933b_5_QF_UFNIA.smt2                                                 | 599.773s |82.392MiB|
|940_590f27b1c3c800d3243e_29_QF_UFLIA.smt2                                                  | 599.767s |543.0MiB|
|66603_accdadf23a1cf70ae043_75_QF_UFLIA.smt2                                                | 599.763s |1229.0MiB|
|66603_accdadf23a1cf70ae043_73_QF_UFDTLIA.smt2                                              | 599.762s |354.0MiB|
|44788_1965f0d6d94d5d8054ba_36_QF_UFDTNIA.smt2                                              | 599.760s |77.46MiB|
|41958_32933c5a1384696720a2_62_QF_UFNIA.smt2                                                | 599.757s |58.004MiB|
|83314_a702bf8b823398c9e37a_2_UFLIA.smt2                                                    | 599.753s |291.0MiB|
|940_590f27b1c3c800d3243e_32_QF_UFDTLIA.smt2                                                | 599.747s |622.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFLIA.smt2                                    | 600.010s |2249.0MiB|
|38347_525a1ca0331f2bcbf520_54_QF_UFLIA.smt2                                                | 599.897s |2217.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFLIA.smt2                                    | 599.890s |1343.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 | 599.886s |967.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTLIA.smt2                                  | 599.848s |2056.0MiB|
|38347_092cc73601c78e45f4f9_57_QF_UFDTLIA.smt2                                              | 599.839s |32.324MiB|
|66603_accdadf23a1cf70ae043_76_QF_UFNIA.smt2                                                | 599.830s |1545.0MiB|
|66603_accdadf23a1cf70ae043_74_QF_UFNIA.smt2                                                | 599.823s |640.0MiB|
|66603_accdadf23a1cf70ae043_73_QF_UFLIA.smt2                                                | 599.802s |802.0MiB|
|83314_a702bf8b823398c9e37a_1_UFDTLIA.smt2                                                  | 599.787s |678.0MiB|
|72658_63104dadde9c6026353f_71_QF_UFLIA.smt2                                                | 599.785s |329.0MiB|
|940_590f27b1c3c800d3243e_33_QF_UFLIA.smt2                                                  | 599.775s |439.0MiB|
|65782_cd31513fdcd15701933b_5_QF_UFNIA.smt2                                                 | 599.773s |82.392MiB|
|940_590f27b1c3c800d3243e_29_QF_UFLIA.smt2                                                  | 599.767s |543.0MiB|
|66603_accdadf23a1cf70ae043_75_QF_UFLIA.smt2                                                | 599.763s |1229.0MiB|
|66603_accdadf23a1cf70ae043_73_QF_UFDTLIA.smt2                                              | 599.762s |354.0MiB|
|44788_1965f0d6d94d5d8054ba_36_QF_UFDTNIA.smt2                                              | 599.760s |77.46MiB|
|41958_32933c5a1384696720a2_62_QF_UFNIA.smt2                                                | 599.757s |58.004MiB|
|83314_a702bf8b823398c9e37a_2_UFLIA.smt2                                                    | 599.753s |291.0MiB|
|940_590f27b1c3c800d3243e_32_QF_UFDTLIA.smt2                                                | 599.747s |622.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |35.92MiB|35.92MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |28.532MiB|28.532MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |39.736MiB|39.736MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |30.752MiB|30.752MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |34.024MiB|34.024MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |27.32MiB|27.32MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |33.908MiB|33.908MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |27.376MiB|27.376MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |66.676MiB|66.676MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |22.888MiB|22.888MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 |183.0MiB|183.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |23.924MiB|23.924MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               |714.0MiB|714.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |37.544MiB|37.544MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 |601.0MiB|601.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |34.624MiB|34.624MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |65.98MiB|65.98MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |36.752MiB|36.752MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |72.244MiB|72.244MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |33.884MiB|33.884MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |35.92MiB|35.92MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |28.532MiB|28.532MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |39.736MiB|39.736MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |30.752MiB|30.752MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |34.024MiB|34.024MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |27.32MiB|27.32MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |33.908MiB|33.908MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |27.376MiB|27.376MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |66.676MiB|66.676MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |22.888MiB|22.888MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 |183.0MiB|183.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |23.924MiB|23.924MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               |714.0MiB|714.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |37.544MiB|37.544MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 |601.0MiB|601.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |34.624MiB|34.624MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |65.98MiB|65.98MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |36.752MiB|36.752MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |72.244MiB|72.244MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |33.884MiB|33.884MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |35.92MiB|35.92MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |28.532MiB|28.532MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |39.736MiB|39.736MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |30.752MiB|30.752MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |34.024MiB|34.024MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |27.32MiB|27.32MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |33.908MiB|33.908MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |27.376MiB|27.376MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |66.676MiB|66.676MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |22.888MiB|22.888MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 |183.0MiB|183.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |23.924MiB|23.924MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               |714.0MiB|714.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |37.544MiB|37.544MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 |601.0MiB|601.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |34.624MiB|34.624MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |65.98MiB|65.98MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |36.752MiB|36.752MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |72.244MiB|72.244MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |33.884MiB|33.884MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |35.92MiB|35.92MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |28.532MiB|28.532MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |39.736MiB|39.736MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |30.752MiB|30.752MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |34.024MiB|34.024MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |27.32MiB|27.32MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |33.908MiB|33.908MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |27.376MiB|27.376MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |66.676MiB|66.676MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |22.888MiB|22.888MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 |183.0MiB|183.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |23.924MiB|23.924MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               |714.0MiB|714.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |37.544MiB|37.544MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 |601.0MiB|601.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |34.624MiB|34.624MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |65.98MiB|65.98MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |36.752MiB|36.752MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |72.244MiB|72.244MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |33.884MiB|33.884MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFLIA.smt2                                    | 600.010s |2249.0MiB|
|38347_525a1ca0331f2bcbf520_54_QF_UFLIA.smt2                                                | 599.897s |2217.0MiB|
|38347_525a1ca0331f2bcbf520_54_QF_UFDTLIA.smt2                                              | 599.525s |2112.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTLIA.smt2                                  | 599.848s |2056.0MiB|
|66603_accdadf23a1cf70ae043_76_QF_UFLIA.smt2                                                | 106.709s |1714.0MiB|
|66603_accdadf23a1cf70ae043_76_QF_UFNIA.smt2                                                | 599.830s |1545.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTLIA.smt2                                  | 599.716s |1418.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFLIA.smt2                                    | 599.890s |1343.0MiB|
|66603_accdadf23a1cf70ae043_75_QF_UFLIA.smt2                                                | 599.763s |1229.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTLIA.smt2                                  | 599.441s |1216.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFLIA.smt2                                    | 599.738s |1155.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 | 599.886s |967.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFLIA.smt2                                    | 599.469s |928.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTLIA.smt2                                  | 599.732s |919.0MiB|
|83314_a702bf8b823398c9e37a_3_UFDTLIA.smt2                                                  | 511.982s |851.0MiB|
|66603_accdadf23a1cf70ae043_73_QF_UFLIA.smt2                                                | 599.802s |802.0MiB|
|83314_a702bf8b823398c9e37a_4_UFDTLIA.smt2                                                  | 599.245s |795.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFLIA.smt2                                    | 599.217s |792.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTLIA.smt2                                  | 599.391s |744.0MiB|
|83314_a702bf8b823398c9e37a_4_UFLIA.smt2                                                    | 599.616s |732.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFLIA.smt2                                    | 600.010s |2249.0MiB|
|38347_525a1ca0331f2bcbf520_54_QF_UFLIA.smt2                                                | 599.897s |2217.0MiB|
|38347_525a1ca0331f2bcbf520_54_QF_UFDTLIA.smt2                                              | 599.525s |2112.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTLIA.smt2                                  | 599.848s |2056.0MiB|
|66603_accdadf23a1cf70ae043_76_QF_UFLIA.smt2                                                | 106.709s |1714.0MiB|
|66603_accdadf23a1cf70ae043_76_QF_UFNIA.smt2                                                | 599.830s |1545.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTLIA.smt2                                  | 599.716s |1418.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFLIA.smt2                                    | 599.890s |1343.0MiB|
|66603_accdadf23a1cf70ae043_75_QF_UFLIA.smt2                                                | 599.763s |1229.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTLIA.smt2                                  | 599.441s |1216.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFLIA.smt2                                    | 599.738s |1155.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 | 599.886s |967.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFLIA.smt2                                    | 599.469s |928.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTLIA.smt2                                  | 599.732s |919.0MiB|
|83314_a702bf8b823398c9e37a_3_UFDTLIA.smt2                                                  | 511.982s |851.0MiB|
|66603_accdadf23a1cf70ae043_73_QF_UFLIA.smt2                                                | 599.802s |802.0MiB|
|83314_a702bf8b823398c9e37a_4_UFDTLIA.smt2                                                  | 599.245s |795.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFLIA.smt2                                    | 599.217s |792.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTLIA.smt2                                  | 599.391s |744.0MiB|
|83314_a702bf8b823398c9e37a_4_UFLIA.smt2                                                    | 599.616s |732.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |   1.608s  |   1.608s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |   0.948s  |   0.948s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |   2.402s  |   2.402s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   1.708s  |   1.708s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |   0.875s  |   0.875s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |   1.598s  |   1.598s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |   1.112s  |   1.112s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   1.031s  |   1.031s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |  15.216s  |  15.216s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |   1.589s  |   1.589s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 | 599.493s  | 599.493s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   4.109s  |   4.109s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               | 599.336s  | 599.336s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |  60.892s  |  60.892s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 | 599.601s  | 599.601s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  34.687s  |  34.687s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |   5.486s  |   5.486s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |  39.489s  |  39.489s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |  12.027s  |  12.027s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  18.041s  |  18.041s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTLIA.smt2                                   | 599.716s  | 599.716s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTNIA.smt2                                   | 599.627s  | 599.627s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFLIA.smt2                                     | 599.890s  | 599.890s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     | 599.464s  | 599.464s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTLIA.smt2                                   | 599.441s  | 599.441s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTNIA.smt2                                   | 111.893s  | 111.893s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFLIA.smt2                                     | 599.738s  | 599.738s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFNIA.smt2                                     |   6.828s  |   6.828s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTLIA.smt2                                   | 599.848s  | 599.848s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTNIA.smt2                                   | 599.425s  | 599.425s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFLIA.smt2                                     | 600.010s  | 600.010s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFNIA.smt2                                     | 599.512s  | 599.512s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTLIA.smt2                                   | 599.732s  | 599.732s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTNIA.smt2                                   | 596.903s  | 596.903s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFLIA.smt2                                     | 599.469s  | 599.469s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFNIA.smt2                                     | 117.184s  | 117.184s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTLIA.smt2                                   | 599.391s  | 599.391s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTNIA.smt2                                   |   3.559s  |   3.559s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFLIA.smt2                                     | 599.217s  | 599.217s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFNIA.smt2                                     |  11.588s  |  11.588s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_27_QF_UFDTLIA.smt2                                               |  61.690s  |  61.690s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_27_QF_UFDTNIA.smt2                                               |  57.607s  |  57.607s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_27_QF_UFLIA.smt2                                                 | 171.786s  | 171.786s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_27_QF_UFNIA.smt2                                                 | 138.500s  | 138.500s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_28_QF_UFDTLIA.smt2                                               | 114.082s  | 114.082s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_28_QF_UFDTNIA.smt2                                               |  90.140s  |  90.140s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_28_QF_UFLIA.smt2                                                 | 309.522s  | 309.522s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_28_QF_UFNIA.smt2                                                 | 243.478s  | 243.478s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_38_QF_UFDTLIA.smt2                                                | 599.443s  | 599.443s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_38_QF_UFDTNIA.smt2                                                | 599.708s  | 599.708s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_38_QF_UFLIA.smt2                                                  | 599.639s  | 599.639s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                  | 599.886s  | 599.886s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_39_QF_UFDTLIA.smt2                                                |  20.913s  |  20.913s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_39_QF_UFDTNIA.smt2                                                | 241.489s  | 241.489s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_39_QF_UFLIA.smt2                                                  | 116.866s  | 116.866s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_39_QF_UFNIA.smt2                                                  | 168.948s  | 168.948s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_40_QF_UFDTLIA.smt2                                                |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_40_QF_UFDTNIA.smt2                                                |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_40_QF_UFLIA.smt2                                                  |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_40_QF_UFNIA.smt2                                                  |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_41_QF_UFDTLIA.smt2                                                |   4.046s  |   4.046s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_41_QF_UFDTNIA.smt2                                                |   4.565s  |   4.565s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_41_QF_UFLIA.smt2                                                  |   9.041s  |   9.041s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_41_QF_UFNIA.smt2                                                  |  38.937s  |  38.937s  |   0.000s  | 0.0%|
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFDTLIA.smt2                                    |  37.069s  |  37.069s  |   0.000s  | 0.0%|
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFDTNIA.smt2                                    |  67.385s  |  67.385s  |   0.000s  | 0.0%|
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFLIA.smt2                                      | 599.602s  | 599.602s  |   0.000s  | 0.0%|
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFNIA.smt2                                      |  68.659s  |  68.659s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_55_QF_UFDTLIA.smt2                                               | 187.485s  | 187.485s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_55_QF_UFDTNIA.smt2                                               | 599.747s  | 599.747s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_55_QF_UFLIA.smt2                                                 | 599.499s  | 599.499s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_55_QF_UFNIA.smt2                                                 | 599.587s  | 599.587s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_56_QF_UFDTLIA.smt2                                               | 599.495s  | 599.495s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_56_QF_UFDTNIA.smt2                                               |   3.869s  |   3.869s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_56_QF_UFLIA.smt2                                                 | 599.604s  | 599.604s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_56_QF_UFNIA.smt2                                                 |  47.039s  |  47.039s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_57_QF_UFDTLIA.smt2                                               | 599.839s  | 599.839s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_57_QF_UFDTNIA.smt2                                               | 599.714s  | 599.714s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_57_QF_UFLIA.smt2                                                 | 599.608s  | 599.608s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_57_QF_UFNIA.smt2                                                 | 599.691s  | 599.691s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_58_QF_UFDTLIA.smt2                                               |   0.658s  |   0.658s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_58_QF_UFDTNIA.smt2                                               |   3.848s  |   3.848s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_58_QF_UFLIA.smt2                                                 |   2.560s  |   2.560s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_58_QF_UFNIA.smt2                                                 |   3.933s  |   3.933s  |   0.000s  | 0.0%|
|38347_525a1ca0331f2bcbf520_54_QF_UFDTLIA.smt2                                               | 599.525s  | 599.525s  |   0.000s  | 0.0%|
|38347_525a1ca0331f2bcbf520_54_QF_UFDTNIA.smt2                                               | 599.567s  | 599.567s  |   0.000s  | 0.0%|
|38347_525a1ca0331f2bcbf520_54_QF_UFLIA.smt2                                                 | 599.897s  | 599.897s  |   0.000s  | 0.0%|
|38347_525a1ca0331f2bcbf520_54_QF_UFNIA.smt2                                                 | 599.614s  | 599.614s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_44_QF_UFDTLIA.smt2                                               |   4.136s  |   4.136s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_44_QF_UFDTNIA.smt2                                               |  12.164s  |  12.164s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_44_QF_UFLIA.smt2                                                 |  21.845s  |  21.845s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_44_QF_UFNIA.smt2                                                 | 250.729s  | 250.729s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_45_QF_UFDTLIA.smt2                                               |   4.635s  |   4.635s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_45_QF_UFDTNIA.smt2                                               |  40.085s  |  40.085s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_45_QF_UFLIA.smt2                                                 |   8.353s  |   8.353s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_45_QF_UFNIA.smt2                                                 | 272.326s  | 272.326s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_46_QF_UFDTLIA.smt2                                               |   2.641s  |   2.641s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_46_QF_UFDTNIA.smt2                                               |  24.500s  |  24.500s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_46_QF_UFLIA.smt2                                                 |  27.791s  |  27.791s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_46_QF_UFNIA.smt2                                                 | 486.088s  | 486.088s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_47_QF_UFDTLIA.smt2                                               |   7.211s  |   7.211s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_47_QF_UFDTNIA.smt2                                               |   0.820s  |   0.820s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_47_QF_UFLIA.smt2                                                 |  75.278s  |  75.278s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_47_QF_UFNIA.smt2                                                 |   6.206s  |   6.206s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_48_QF_UFDTLIA.smt2                                               |   4.142s  |   4.142s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_48_QF_UFDTNIA.smt2                                               |   0.257s  |   0.257s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_48_QF_UFLIA.smt2                                                 |   8.850s  |   8.850s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_48_QF_UFNIA.smt2                                                 |  33.480s  |  33.480s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_61_QF_UFDTLIA.smt2                                               | 175.801s  | 175.801s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_61_QF_UFDTNIA.smt2                                               |   5.729s  |   5.729s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_61_QF_UFLIA.smt2                                                 | 599.708s  | 599.708s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_61_QF_UFNIA.smt2                                                 |   8.282s  |   8.282s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_62_QF_UFDTLIA.smt2                                               |  22.846s  |  22.846s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_62_QF_UFDTNIA.smt2                                               | 599.131s  | 599.131s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_62_QF_UFLIA.smt2                                                 |  27.937s  |  27.937s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_62_QF_UFNIA.smt2                                                 | 599.757s  | 599.757s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_63_QF_UFDTLIA.smt2                                               |   7.525s  |   7.525s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_63_QF_UFDTNIA.smt2                                               |  34.133s  |  34.133s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_63_QF_UFLIA.smt2                                                 |   6.792s  |   6.792s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_63_QF_UFNIA.smt2                                                 | 599.543s  | 599.543s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_59_QF_UFDTLIA.smt2                                               |   1.460s  |   1.460s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_59_QF_UFDTNIA.smt2                                               |   0.805s  |   0.805s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_59_QF_UFLIA.smt2                                                 |  17.868s  |  17.868s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_59_QF_UFNIA.smt2                                                 |   5.931s  |   5.931s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_60_QF_UFDTLIA.smt2                                               |   1.029s  |   1.029s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_60_QF_UFDTNIA.smt2                                               |   0.395s  |   0.395s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_60_QF_UFLIA.smt2                                                 |   4.948s  |   4.948s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_60_QF_UFNIA.smt2                                                 |   3.571s  |   3.571s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_14_QF_UFDTLIA.smt2                                               |   3.363s  |   3.363s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_14_QF_UFDTNIA.smt2                                               |   2.136s  |   2.136s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_14_QF_UFLIA.smt2                                                 |  29.575s  |  29.575s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_14_QF_UFNIA.smt2                                                 |  21.253s  |  21.253s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_15_QF_UFDTLIA.smt2                                               |  10.065s  |  10.065s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_15_QF_UFDTNIA.smt2                                               |   6.465s  |   6.465s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_15_QF_UFLIA.smt2                                                 | 599.426s  | 599.426s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_15_QF_UFNIA.smt2                                                 | 351.355s  | 351.355s  |   0.000s  | 0.0%|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFDTLIA.smt2                                   |  16.243s  |  16.243s  |   0.000s  | 0.0%|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFDTNIA.smt2                                   | 253.635s  | 253.635s  |   0.000s  | 0.0%|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFLIA.smt2                                     | 599.163s  | 599.163s  |   0.000s  | 0.0%|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFNIA.smt2                                     | 599.640s  | 599.640s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_17_QF_UFDTLIA.smt2                                               |   3.425s  |   3.425s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_17_QF_UFDTNIA.smt2                                               |   3.326s  |   3.326s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_17_QF_UFLIA.smt2                                                 |  26.448s  |  26.448s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_17_QF_UFNIA.smt2                                                 | 146.736s  | 146.736s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_18_QF_UFDTLIA.smt2                                               |   2.846s  |   2.846s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_18_QF_UFDTNIA.smt2                                               |   4.080s  |   4.080s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_18_QF_UFLIA.smt2                                                 |  14.990s  |  14.990s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_18_QF_UFNIA.smt2                                                 |  13.962s  |  13.962s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_34_QF_UFDTLIA.smt2                                               |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_34_QF_UFDTNIA.smt2                                               |   8.868s  |   8.868s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_34_QF_UFLIA.smt2                                                 |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_34_QF_UFNIA.smt2                                                 |  10.097s  |  10.097s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_35_QF_UFDTLIA.smt2                                               |   0.830s  |   0.830s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_35_QF_UFDTNIA.smt2                                               | 599.464s  | 599.464s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_35_QF_UFLIA.smt2                                                 |   1.694s  |   1.694s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_35_QF_UFNIA.smt2                                                 | 599.256s  | 599.256s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_36_QF_UFDTLIA.smt2                                               | 259.491s  | 259.491s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_36_QF_UFDTNIA.smt2                                               | 599.760s  | 599.760s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_36_QF_UFLIA.smt2                                                 |  40.074s  |  40.074s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_36_QF_UFNIA.smt2                                                 | 599.632s  | 599.632s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFDTLIA.smt2                                   |   0.523s  |   0.523s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFDTNIA.smt2                                   |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFLIA.smt2                                     |  56.017s  |  56.017s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFNIA.smt2                                     |  51.901s  |  51.901s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFDTLIA.smt2                                   |   0.718s  |   0.718s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFDTNIA.smt2                                   |   0.722s  |   0.722s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFLIA.smt2                                     |  47.093s  |  47.093s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFNIA.smt2                                     |  55.233s  |  55.233s  |   0.000s  | 0.0%|
|52759_b3ecd2335fd16ec2eee2_9_UFDTLIA.smt2                                                   |  81.530s  |  81.530s  |   0.000s  | 0.0%|
|52759_b3ecd2335fd16ec2eee2_9_UFDTNIA.smt2                                                   | 476.967s  | 476.967s  |   0.000s  | 0.0%|
|52759_b3ecd2335fd16ec2eee2_9_UFLIA.smt2                                                     |  93.669s  |  93.669s  |   0.000s  | 0.0%|
|52759_b3ecd2335fd16ec2eee2_9_UFNIA.smt2                                                     | 439.753s  | 439.753s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFDTLIA.smt2                                   |  87.767s  |  87.767s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFDTNIA.smt2                                   | 109.209s  | 109.209s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFLIA.smt2                                     | 599.696s  | 599.696s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFNIA.smt2                                     | 599.719s  | 599.719s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFDTLIA.smt2                                   |  27.352s  |  27.352s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFDTNIA.smt2                                   |   2.476s  |   2.476s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFLIA.smt2                                     | 599.568s  | 599.568s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFNIA.smt2                                     |  65.023s  |  65.023s  |   0.000s  | 0.0%|
|63058_55d6bef5390186355f11_26_QF_UFDTLIA.smt2                                               |   3.121s  |   3.121s  |   0.000s  | 0.0%|
|63058_55d6bef5390186355f11_26_QF_UFDTNIA.smt2                                               |   8.183s  |   8.183s  |   0.000s  | 0.0%|
|63058_55d6bef5390186355f11_26_QF_UFLIA.smt2                                                 |  91.293s  |  91.293s  |   0.000s  | 0.0%|
|63058_55d6bef5390186355f11_26_QF_UFNIA.smt2                                                 | 121.503s  | 121.503s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_22_QF_UFDTLIA.smt2                                               |   4.195s  |   4.195s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_22_QF_UFDTNIA.smt2                                               |   9.502s  |   9.502s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_22_QF_UFLIA.smt2                                                 |  50.031s  |  50.031s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_22_QF_UFNIA.smt2                                                 | 109.989s  | 109.989s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_23_QF_UFDTLIA.smt2                                               |   5.005s  |   5.005s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_23_QF_UFDTNIA.smt2                                               |   8.313s  |   8.313s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_23_QF_UFLIA.smt2                                                 |  52.155s  |  52.155s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_23_QF_UFNIA.smt2                                                 | 226.418s  | 226.418s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_24_QF_UFDTLIA.smt2                                               |  10.428s  |  10.428s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_24_QF_UFDTNIA.smt2                                               |   3.982s  |   3.982s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_24_QF_UFLIA.smt2                                                 |  82.119s  |  82.119s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_24_QF_UFNIA.smt2                                                 | 599.611s  | 599.611s  |   0.000s  | 0.0%|
|63058_aa742630eef64f949de269382c1f9035_25_UFDTLIA.smt2                                      |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|63058_aa742630eef64f949de269382c1f9035_25_UFDTNIA.smt2                                      |   0.271s  |   0.271s  |   0.000s  | 0.0%|
|63058_aa742630eef64f949de269382c1f9035_25_UFLIA.smt2                                        |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|63058_aa742630eef64f949de269382c1f9035_25_UFNIA.smt2                                        |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_5_QF_UFDTLIA.smt2                                                | 599.493s  | 599.493s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_5_QF_UFDTNIA.smt2                                                | 599.724s  | 599.724s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_5_QF_UFLIA.smt2                                                  | 599.345s  | 599.345s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_5_QF_UFNIA.smt2                                                  | 599.773s  | 599.773s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_6_QF_UFDTLIA.smt2                                                |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_6_QF_UFDTNIA.smt2                                                |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_6_QF_UFLIA.smt2                                                  |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_6_QF_UFNIA.smt2                                                  |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_7_QF_UFDTLIA.smt2                                                |   0.543s  |   0.543s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_7_QF_UFDTNIA.smt2                                                |  12.502s  |  12.502s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_7_QF_UFLIA.smt2                                                  |   0.369s  |   0.369s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_7_QF_UFNIA.smt2                                                  |   5.616s  |   5.616s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_8_QF_UFDTLIA.smt2                                                |   0.505s  |   0.505s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_8_QF_UFDTNIA.smt2                                                |   1.669s  |   1.669s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_8_QF_UFLIA.smt2                                                  |   0.591s  |   0.591s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_8_QF_UFNIA.smt2                                                  |   0.744s  |   0.744s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_72_QF_UFDTLIA.smt2                                               |   7.018s  |   7.018s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_72_QF_UFDTNIA.smt2                                               |   5.283s  |   5.283s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_72_QF_UFLIA.smt2                                                 |  49.925s  |  49.925s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                                                 | 573.796s  | 573.796s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_73_QF_UFDTLIA.smt2                                               | 599.762s  | 599.762s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_73_QF_UFDTNIA.smt2                                               |   8.042s  |   8.042s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_73_QF_UFLIA.smt2                                                 | 599.802s  | 599.802s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_73_QF_UFNIA.smt2                                                 | 599.604s  | 599.604s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_74_QF_UFDTLIA.smt2                                               |  28.002s  |  28.002s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_74_QF_UFDTNIA.smt2                                               | 599.741s  | 599.741s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_74_QF_UFLIA.smt2                                                 | 599.686s  | 599.686s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_74_QF_UFNIA.smt2                                                 | 599.823s  | 599.823s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_75_QF_UFDTLIA.smt2                                               |  21.811s  |  21.811s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_75_QF_UFDTNIA.smt2                                               |  30.474s  |  30.474s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_75_QF_UFLIA.smt2                                                 | 599.763s  | 599.763s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_75_QF_UFNIA.smt2                                                 | 599.556s  | 599.556s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_76_QF_UFDTLIA.smt2                                               |  25.280s  |  25.280s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_76_QF_UFDTNIA.smt2                                               |  24.508s  |  24.508s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_76_QF_UFLIA.smt2                                                 | 106.709s  | 106.709s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_76_QF_UFNIA.smt2                                                 | 599.830s  | 599.830s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_70_QF_UFDTLIA.smt2                                               |   2.034s  |   2.034s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_70_QF_UFDTNIA.smt2                                               | 233.994s  | 233.994s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_70_QF_UFLIA.smt2                                                 |  16.845s  |  16.845s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_70_QF_UFNIA.smt2                                                 |   1.224s  |   1.224s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_71_QF_UFDTLIA.smt2                                               | 599.289s  | 599.289s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_71_QF_UFDTNIA.smt2                                               | 599.497s  | 599.497s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_71_QF_UFLIA.smt2                                                 | 599.785s  | 599.785s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_71_QF_UFNIA.smt2                                                 | 599.675s  | 599.675s  |   0.000s  | 0.0%|
|72771_f9d228efc97cf1458e38_64_QF_UFDTLIA.smt2                                               |   6.052s  |   6.052s  |   0.000s  | 0.0%|
|72771_f9d228efc97cf1458e38_64_QF_UFDTNIA.smt2                                               |   0.669s  |   0.669s  |   0.000s  | 0.0%|
|72771_f9d228efc97cf1458e38_64_QF_UFLIA.smt2                                                 |  29.793s  |  29.793s  |   0.000s  | 0.0%|
|72771_f9d228efc97cf1458e38_64_QF_UFNIA.smt2                                                 |   1.469s  |   1.469s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_0_UFDTLIA.smt2                                                   |   9.790s  |   9.790s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_0_UFDTNIA.smt2                                                   |   1.353s  |   1.353s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_0_UFLIA.smt2                                                     | 400.053s  | 400.053s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_0_UFNIA.smt2                                                     |   0.568s  |   0.568s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_1_UFDTLIA.smt2                                                   | 599.787s  | 599.787s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_1_UFDTNIA.smt2                                                   |  30.189s  |  30.189s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_1_UFLIA.smt2                                                     | 599.635s  | 599.635s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_1_UFNIA.smt2                                                     | 151.574s  | 151.574s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_2_UFDTLIA.smt2                                                   | 599.515s  | 599.515s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_2_UFDTNIA.smt2                                                   | 599.578s  | 599.578s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_2_UFLIA.smt2                                                     | 599.753s  | 599.753s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_2_UFNIA.smt2                                                     | 599.611s  | 599.611s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_3_UFDTLIA.smt2                                                   | 511.982s  | 511.982s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_3_UFDTNIA.smt2                                                   | 599.438s  | 599.438s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_3_UFLIA.smt2                                                     | 599.580s  | 599.580s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_3_UFNIA.smt2                                                     | 100.488s  | 100.488s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_4_UFDTLIA.smt2                                                   | 599.245s  | 599.245s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_4_UFDTNIA.smt2                                                   | 599.610s  | 599.610s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_4_UFLIA.smt2                                                     | 599.616s  | 599.616s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_4_UFNIA.smt2                                                     | 599.714s  | 599.714s  |   0.000s  | 0.0%|
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFDTLIA.smt2                                   |  40.529s  |  40.529s  |   0.000s  | 0.0%|
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFDTNIA.smt2                                   | 158.497s  | 158.497s  |   0.000s  | 0.0%|
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFLIA.smt2                                     | 599.705s  | 599.705s  |   0.000s  | 0.0%|
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFNIA.smt2                                     | 149.010s  | 149.010s  |   0.000s  | 0.0%|
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFDTLIA.smt2                                   | 131.241s  | 131.241s  |   0.000s  | 0.0%|
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFDTNIA.smt2                                   |  12.416s  |  12.416s  |   0.000s  | 0.0%|
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFLIA.smt2                                     | 599.634s  | 599.634s  |   0.000s  | 0.0%|
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFNIA.smt2                                     |  84.686s  |  84.686s  |   0.000s  | 0.0%|
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFDTLIA.smt2                                   | 599.359s  | 599.359s  |   0.000s  | 0.0%|
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFDTNIA.smt2                                   | 599.499s  | 599.499s  |   0.000s  | 0.0%|
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFLIA.smt2                                     | 599.685s  | 599.685s  |   0.000s  | 0.0%|
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFNIA.smt2                                     | 599.445s  | 599.445s  |   0.000s  | 0.0%|
|93493_5990a6bf5f2740164f77_50_QF_UFDTLIA.smt2                                               | 378.138s  | 378.138s  |   0.000s  | 0.0%|
|93493_5990a6bf5f2740164f77_50_QF_UFDTNIA.smt2                                               | 599.553s  | 599.553s  |   0.000s  | 0.0%|
|93493_5990a6bf5f2740164f77_50_QF_UFLIA.smt2                                                 | 599.097s  | 599.097s  |   0.000s  | 0.0%|
|93493_5990a6bf5f2740164f77_50_QF_UFNIA.smt2                                                 | 445.475s  | 445.475s  |   0.000s  | 0.0%|
|93493_798593962ee29ad45ac8_52_QF_UFDTLIA.smt2                                               | 599.519s  | 599.519s  |   0.000s  | 0.0%|
|93493_798593962ee29ad45ac8_52_QF_UFDTNIA.smt2                                               | 599.598s  | 599.598s  |   0.000s  | 0.0%|
|93493_798593962ee29ad45ac8_52_QF_UFLIA.smt2                                                 | 599.454s  | 599.454s  |   0.000s  | 0.0%|
|93493_798593962ee29ad45ac8_52_QF_UFNIA.smt2                                                 | 599.721s  | 599.721s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_29_QF_UFDTLIA.smt2                                                 | 599.468s  | 599.468s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_29_QF_UFDTNIA.smt2                                                 | 277.004s  | 277.004s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_29_QF_UFLIA.smt2                                                   | 599.767s  | 599.767s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_29_QF_UFNIA.smt2                                                   |  55.714s  |  55.714s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_30_QF_UFDTLIA.smt2                                                 | 599.262s  | 599.262s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_30_QF_UFDTNIA.smt2                                                 |  89.296s  |  89.296s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_30_QF_UFLIA.smt2                                                   | 599.676s  | 599.676s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_30_QF_UFNIA.smt2                                                   | 599.542s  | 599.542s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_31_QF_UFDTLIA.smt2                                                 | 599.389s  | 599.389s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_31_QF_UFDTNIA.smt2                                                 |  15.411s  |  15.411s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_31_QF_UFLIA.smt2                                                   | 599.587s  | 599.587s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_31_QF_UFNIA.smt2                                                   |   9.781s  |   9.781s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_32_QF_UFDTLIA.smt2                                                 | 599.747s  | 599.747s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_32_QF_UFDTNIA.smt2                                                 |  78.359s  |  78.359s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_32_QF_UFLIA.smt2                                                   | 599.372s  | 599.372s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_32_QF_UFNIA.smt2                                                   |  45.513s  |  45.513s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_33_QF_UFDTLIA.smt2                                                 | 599.617s  | 599.617s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_33_QF_UFDTNIA.smt2                                                 |  81.842s  |  81.842s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_33_QF_UFLIA.smt2                                                   | 599.775s  | 599.775s  |   0.000s  | 0.0%|
</details>
