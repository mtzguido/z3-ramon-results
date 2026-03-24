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
Job description: test multivariate factorization on certora
Job tag: mfact_cert
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: fbbdf6a06ac53ffe6f741b906508f6736583651f
Z3 branch: mfact
Z3 options: "-T:200 smt.random_seed=111"
Z3 inputs: inputs/certora
Z3 commit message: refactor try_bivar_hensel_lift and outline the algorithm

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: test multivariate factorization on certora
Job tag: mfact_cert
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: fbbdf6a06ac53ffe6f741b906508f6736583651f
Z3 branch: mfact
Z3 options: "-T:200 smt.random_seed=111"
Z3 inputs: inputs/certora
Z3 commit message: refactor try_bivar_hensel_lift and outline the algorithm

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |   0.909s  |   0.909s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |   1.206s  |   1.206s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |   2.574s  |   2.574s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   0.966s  |   0.966s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |   0.469s  |   0.469s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |   2.240s  |   2.240s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |   1.341s  |   1.341s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   0.942s  |   0.942s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |  21.768s  |  21.768s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |   3.516s  |   3.516s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 | 200.026s  | 200.026s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   2.098s  |   2.098s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               | 200.060s  | 200.060s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |  46.163s  |  46.163s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 | 200.071s  | 200.071s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  53.273s  |  53.273s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |   5.043s  |   5.043s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |   9.722s  |   9.722s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |   9.353s  |   9.353s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |   5.295s  |   5.295s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |   0.909s  |   0.909s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |   1.206s  |   1.206s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |   2.574s  |   2.574s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   0.966s  |   0.966s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |   0.469s  |   0.469s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |   2.240s  |   2.240s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |   1.341s  |   1.341s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   0.942s  |   0.942s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |  21.768s  |  21.768s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |   3.516s  |   3.516s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 | 200.026s  | 200.026s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   2.098s  |   2.098s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               | 200.060s  | 200.060s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |  46.163s  |  46.163s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 | 200.071s  | 200.071s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  53.273s  |  53.273s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |   5.043s  |   5.043s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |   9.722s  |   9.722s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |   9.353s  |   9.353s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |   5.295s  |   5.295s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |   0.909s  |   0.909s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |   1.206s  |   1.206s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |   2.574s  |   2.574s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   0.966s  |   0.966s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |   0.469s  |   0.469s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |   2.240s  |   2.240s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |   1.341s  |   1.341s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   0.942s  |   0.942s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |  21.768s  |  21.768s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |   3.516s  |   3.516s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 | 200.026s  | 200.026s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   2.098s  |   2.098s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               | 200.060s  | 200.060s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |  46.163s  |  46.163s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 | 200.071s  | 200.071s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  53.273s  |  53.273s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |   5.043s  |   5.043s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |   9.722s  |   9.722s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |   9.353s  |   9.353s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |   5.295s  |   5.295s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |   0.909s  |   0.909s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |   1.206s  |   1.206s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |   2.574s  |   2.574s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   0.966s  |   0.966s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |   0.469s  |   0.469s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |   2.240s  |   2.240s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |   1.341s  |   1.341s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   0.942s  |   0.942s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |  21.768s  |  21.768s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |   3.516s  |   3.516s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 | 200.026s  | 200.026s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   2.098s  |   2.098s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               | 200.060s  | 200.060s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |  46.163s  |  46.163s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 | 200.071s  | 200.071s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  53.273s  |  53.273s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |   5.043s  |   5.043s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |   9.722s  |   9.722s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |   9.353s  |   9.353s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |   5.295s  |   5.295s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFLIA.smt2                                    | 200.309s |3026.0MiB|
|38347_525a1ca0331f2bcbf520_54_QF_UFDTLIA.smt2                                              | 200.302s |2495.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTLIA.smt2                                  | 200.295s |2945.0MiB|
|38347_525a1ca0331f2bcbf520_54_QF_UFLIA.smt2                                                | 200.277s |2246.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTLIA.smt2                                  | 200.252s |2234.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFLIA.smt2                                    | 200.247s |2377.0MiB|
|66603_accdadf23a1cf70ae043_76_QF_UFNIA.smt2                                                | 200.200s |1565.0MiB|
|66603_accdadf23a1cf70ae043_75_QF_UFLIA.smt2                                                | 200.190s |1723.0MiB|
|66603_accdadf23a1cf70ae043_74_QF_UFLIA.smt2                                                | 200.183s |1384.0MiB|
|66603_accdadf23a1cf70ae043_74_QF_UFNIA.smt2                                                | 200.157s |1308.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 | 200.146s |889.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFLIA.smt2                                                 | 200.137s |876.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTLIA.smt2                                  | 200.130s |1070.0MiB|
|66603_accdadf23a1cf70ae043_75_QF_UFNIA.smt2                                                | 200.126s |1208.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFLIA.smt2                                    | 200.113s |1146.0MiB|
|83314_a702bf8b823398c9e37a_4_UFLIA.smt2                                                    | 200.105s |792.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTLIA.smt2                                  | 200.103s |655.0MiB|
|940_590f27b1c3c800d3243e_29_QF_UFLIA.smt2                                                  | 200.102s |747.0MiB|
|93493_5990a6bf5f2740164f77_50_QF_UFLIA.smt2                                                | 200.101s |420.0MiB|
|66603_accdadf23a1cf70ae043_73_QF_UFLIA.smt2                                                | 200.099s |911.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFLIA.smt2                                    | 200.309s |3026.0MiB|
|38347_525a1ca0331f2bcbf520_54_QF_UFDTLIA.smt2                                              | 200.302s |2495.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTLIA.smt2                                  | 200.295s |2945.0MiB|
|38347_525a1ca0331f2bcbf520_54_QF_UFLIA.smt2                                                | 200.277s |2246.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTLIA.smt2                                  | 200.252s |2234.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFLIA.smt2                                    | 200.247s |2377.0MiB|
|66603_accdadf23a1cf70ae043_76_QF_UFNIA.smt2                                                | 200.200s |1565.0MiB|
|66603_accdadf23a1cf70ae043_75_QF_UFLIA.smt2                                                | 200.190s |1723.0MiB|
|66603_accdadf23a1cf70ae043_74_QF_UFLIA.smt2                                                | 200.183s |1384.0MiB|
|66603_accdadf23a1cf70ae043_74_QF_UFNIA.smt2                                                | 200.157s |1308.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 | 200.146s |889.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFLIA.smt2                                                 | 200.137s |876.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTLIA.smt2                                  | 200.130s |1070.0MiB|
|66603_accdadf23a1cf70ae043_75_QF_UFNIA.smt2                                                | 200.126s |1208.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFLIA.smt2                                    | 200.113s |1146.0MiB|
|83314_a702bf8b823398c9e37a_4_UFLIA.smt2                                                    | 200.105s |792.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTLIA.smt2                                  | 200.103s |655.0MiB|
|940_590f27b1c3c800d3243e_29_QF_UFLIA.smt2                                                  | 200.102s |747.0MiB|
|93493_5990a6bf5f2740164f77_50_QF_UFLIA.smt2                                                | 200.101s |420.0MiB|
|66603_accdadf23a1cf70ae043_73_QF_UFLIA.smt2                                                | 200.099s |911.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |36.548MiB|36.548MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |30.076MiB|30.076MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |40.472MiB|40.472MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |31.976MiB|31.976MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |34.86MiB|34.86MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |28.616MiB|28.616MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |35.756MiB|35.756MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |28.332MiB|28.332MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |85.772MiB|85.772MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |23.912MiB|23.912MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 |177.0MiB|177.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |23.716MiB|23.716MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               |478.0MiB|478.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |40.364MiB|40.364MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 |506.0MiB|506.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |37.724MiB|37.724MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |68.532MiB|68.532MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |34.128MiB|34.128MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |86.892MiB|86.892MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |31.784MiB|31.784MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |36.548MiB|36.548MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |30.076MiB|30.076MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |40.472MiB|40.472MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |31.976MiB|31.976MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |34.86MiB|34.86MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |28.616MiB|28.616MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |35.756MiB|35.756MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |28.332MiB|28.332MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |85.772MiB|85.772MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |23.912MiB|23.912MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 |177.0MiB|177.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |23.716MiB|23.716MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               |478.0MiB|478.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |40.364MiB|40.364MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 |506.0MiB|506.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |37.724MiB|37.724MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |68.532MiB|68.532MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |34.128MiB|34.128MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |86.892MiB|86.892MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |31.784MiB|31.784MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |36.548MiB|36.548MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |30.076MiB|30.076MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |40.472MiB|40.472MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |31.976MiB|31.976MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |34.86MiB|34.86MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |28.616MiB|28.616MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |35.756MiB|35.756MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |28.332MiB|28.332MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |85.772MiB|85.772MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |23.912MiB|23.912MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 |177.0MiB|177.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |23.716MiB|23.716MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               |478.0MiB|478.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |40.364MiB|40.364MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 |506.0MiB|506.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |37.724MiB|37.724MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |68.532MiB|68.532MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |34.128MiB|34.128MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |86.892MiB|86.892MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |31.784MiB|31.784MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |36.548MiB|36.548MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |30.076MiB|30.076MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |40.472MiB|40.472MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |31.976MiB|31.976MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |34.86MiB|34.86MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |28.616MiB|28.616MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |35.756MiB|35.756MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |28.332MiB|28.332MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |85.772MiB|85.772MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |23.912MiB|23.912MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 |177.0MiB|177.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |23.716MiB|23.716MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               |478.0MiB|478.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |40.364MiB|40.364MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 |506.0MiB|506.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |37.724MiB|37.724MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |68.532MiB|68.532MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |34.128MiB|34.128MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |86.892MiB|86.892MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |31.784MiB|31.784MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFLIA.smt2                                    | 200.309s |3026.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTLIA.smt2                                  | 200.295s |2945.0MiB|
|38347_525a1ca0331f2bcbf520_54_QF_UFDTLIA.smt2                                              | 200.302s |2495.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFLIA.smt2                                    | 200.247s |2377.0MiB|
|38347_525a1ca0331f2bcbf520_54_QF_UFLIA.smt2                                                | 200.277s |2246.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTLIA.smt2                                  | 200.252s |2234.0MiB|
|66603_accdadf23a1cf70ae043_76_QF_UFLIA.smt2                                                |  36.382s |1741.0MiB|
|66603_accdadf23a1cf70ae043_75_QF_UFLIA.smt2                                                | 200.190s |1723.0MiB|
|66603_accdadf23a1cf70ae043_76_QF_UFNIA.smt2                                                | 200.200s |1565.0MiB|
|66603_accdadf23a1cf70ae043_74_QF_UFLIA.smt2                                                | 200.183s |1384.0MiB|
|66603_accdadf23a1cf70ae043_74_QF_UFNIA.smt2                                                | 200.157s |1308.0MiB|
|66603_accdadf23a1cf70ae043_75_QF_UFNIA.smt2                                                | 200.126s |1208.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFLIA.smt2                                    | 200.113s |1146.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTLIA.smt2                                  | 200.130s |1070.0MiB|
|66603_accdadf23a1cf70ae043_73_QF_UFLIA.smt2                                                | 200.099s |911.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFLIA.smt2                                    | 200.096s |909.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 | 200.146s |889.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFLIA.smt2                                                 | 200.137s |876.0MiB|
|44788_1965f0d6d94d5d8054ba_36_QF_UFDTLIA.smt2                                              | 200.093s |870.0MiB|
|66603_accdadf23a1cf70ae043_73_QF_UFNIA.smt2                                                | 200.094s |823.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFLIA.smt2                                    | 200.309s |3026.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTLIA.smt2                                  | 200.295s |2945.0MiB|
|38347_525a1ca0331f2bcbf520_54_QF_UFDTLIA.smt2                                              | 200.302s |2495.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFLIA.smt2                                    | 200.247s |2377.0MiB|
|38347_525a1ca0331f2bcbf520_54_QF_UFLIA.smt2                                                | 200.277s |2246.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTLIA.smt2                                  | 200.252s |2234.0MiB|
|66603_accdadf23a1cf70ae043_76_QF_UFLIA.smt2                                                |  36.382s |1741.0MiB|
|66603_accdadf23a1cf70ae043_75_QF_UFLIA.smt2                                                | 200.190s |1723.0MiB|
|66603_accdadf23a1cf70ae043_76_QF_UFNIA.smt2                                                | 200.200s |1565.0MiB|
|66603_accdadf23a1cf70ae043_74_QF_UFLIA.smt2                                                | 200.183s |1384.0MiB|
|66603_accdadf23a1cf70ae043_74_QF_UFNIA.smt2                                                | 200.157s |1308.0MiB|
|66603_accdadf23a1cf70ae043_75_QF_UFNIA.smt2                                                | 200.126s |1208.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFLIA.smt2                                    | 200.113s |1146.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTLIA.smt2                                  | 200.130s |1070.0MiB|
|66603_accdadf23a1cf70ae043_73_QF_UFLIA.smt2                                                | 200.099s |911.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFLIA.smt2                                    | 200.096s |909.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 | 200.146s |889.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFLIA.smt2                                                 | 200.137s |876.0MiB|
|44788_1965f0d6d94d5d8054ba_36_QF_UFDTLIA.smt2                                              | 200.093s |870.0MiB|
|66603_accdadf23a1cf70ae043_73_QF_UFNIA.smt2                                                | 200.094s |823.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |   0.909s  |   0.909s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |   1.206s  |   1.206s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |   2.574s  |   2.574s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   0.966s  |   0.966s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |   0.469s  |   0.469s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |   2.240s  |   2.240s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |   1.341s  |   1.341s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   0.942s  |   0.942s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |  21.768s  |  21.768s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |   3.516s  |   3.516s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 | 200.026s  | 200.026s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   2.098s  |   2.098s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               | 200.060s  | 200.060s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |  46.163s  |  46.163s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 | 200.071s  | 200.071s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  53.273s  |  53.273s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |   5.043s  |   5.043s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |   9.722s  |   9.722s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |   9.353s  |   9.353s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |   5.295s  |   5.295s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTLIA.smt2                                   | 200.295s  | 200.295s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTNIA.smt2                                   | 200.038s  | 200.038s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFLIA.smt2                                     | 200.309s  | 200.309s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     | 200.020s  | 200.020s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTLIA.smt2                                   | 200.130s  | 200.130s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTNIA.smt2                                   | 200.032s  | 200.032s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFLIA.smt2                                     | 200.096s  | 200.096s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFNIA.smt2                                     |   3.212s  |   3.212s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTLIA.smt2                                   | 200.252s  | 200.252s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTNIA.smt2                                   | 200.027s  | 200.027s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFLIA.smt2                                     | 200.247s  | 200.247s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFNIA.smt2                                     | 200.027s  | 200.027s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTLIA.smt2                                   | 200.089s  | 200.089s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTNIA.smt2                                   | 124.640s  | 124.640s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFLIA.smt2                                     | 200.113s  | 200.113s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFNIA.smt2                                     | 200.032s  | 200.032s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTLIA.smt2                                   | 200.103s  | 200.103s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTNIA.smt2                                   |   3.600s  |   3.600s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFLIA.smt2                                     | 200.097s  | 200.097s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFNIA.smt2                                     |   9.508s  |   9.508s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_27_QF_UFDTLIA.smt2                                               |  23.576s  |  23.576s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_27_QF_UFDTNIA.smt2                                               |  19.213s  |  19.213s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_27_QF_UFLIA.smt2                                                 |  57.638s  |  57.638s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_27_QF_UFNIA.smt2                                                 |  36.906s  |  36.906s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_28_QF_UFDTLIA.smt2                                               |  40.720s  |  40.720s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_28_QF_UFDTNIA.smt2                                               |  23.551s  |  23.551s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_28_QF_UFLIA.smt2                                                 | 104.522s  | 104.522s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_28_QF_UFNIA.smt2                                                 |  45.019s  |  45.019s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_38_QF_UFDTLIA.smt2                                                | 200.059s  | 200.059s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_38_QF_UFDTNIA.smt2                                                | 200.088s  | 200.088s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_38_QF_UFLIA.smt2                                                  | 200.137s  | 200.137s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                  | 200.146s  | 200.146s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_39_QF_UFDTLIA.smt2                                                |   8.597s  |   8.597s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_39_QF_UFDTNIA.smt2                                                |  27.238s  |  27.238s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_39_QF_UFLIA.smt2                                                  |  36.260s  |  36.260s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_39_QF_UFNIA.smt2                                                  | 173.069s  | 173.069s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_40_QF_UFDTLIA.smt2                                                |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_40_QF_UFDTNIA.smt2                                                |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_40_QF_UFLIA.smt2                                                  |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_40_QF_UFNIA.smt2                                                  |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_41_QF_UFDTLIA.smt2                                                |   2.224s  |   2.224s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_41_QF_UFDTNIA.smt2                                                |  10.587s  |  10.587s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_41_QF_UFLIA.smt2                                                  |   9.265s  |   9.265s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_41_QF_UFNIA.smt2                                                  |  12.188s  |  12.188s  |   0.000s  | 0.0%|
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFDTLIA.smt2                                    |  12.657s  |  12.657s  |   0.000s  | 0.0%|
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFDTNIA.smt2                                    |  17.978s  |  17.978s  |   0.000s  | 0.0%|
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFLIA.smt2                                      | 200.044s  | 200.044s  |   0.000s  | 0.0%|
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFNIA.smt2                                      |  64.483s  |  64.483s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_55_QF_UFDTLIA.smt2                                               |  14.685s  |  14.685s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_55_QF_UFDTNIA.smt2                                               | 175.134s  | 175.134s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_55_QF_UFLIA.smt2                                                 | 200.014s  | 200.014s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_55_QF_UFNIA.smt2                                                 | 200.022s  | 200.022s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_56_QF_UFDTLIA.smt2                                               |  28.907s  |  28.907s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_56_QF_UFDTNIA.smt2                                               |   1.959s  |   1.959s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_56_QF_UFLIA.smt2                                                 | 200.050s  | 200.050s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_56_QF_UFNIA.smt2                                                 |  17.251s  |  17.251s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_57_QF_UFDTLIA.smt2                                               | 200.030s  | 200.030s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_57_QF_UFDTNIA.smt2                                               | 200.014s  | 200.014s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_57_QF_UFLIA.smt2                                                 | 200.016s  | 200.016s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_57_QF_UFNIA.smt2                                                 | 200.026s  | 200.026s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_58_QF_UFDTLIA.smt2                                               |   0.345s  |   0.345s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_58_QF_UFDTNIA.smt2                                               |   0.456s  |   0.456s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_58_QF_UFLIA.smt2                                                 |   0.922s  |   0.922s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_58_QF_UFNIA.smt2                                                 |   1.841s  |   1.841s  |   0.000s  | 0.0%|
|38347_525a1ca0331f2bcbf520_54_QF_UFDTLIA.smt2                                               | 200.302s  | 200.302s  |   0.000s  | 0.0%|
|38347_525a1ca0331f2bcbf520_54_QF_UFDTNIA.smt2                                               | 200.030s  | 200.030s  |   0.000s  | 0.0%|
|38347_525a1ca0331f2bcbf520_54_QF_UFLIA.smt2                                                 | 200.277s  | 200.277s  |   0.000s  | 0.0%|
|38347_525a1ca0331f2bcbf520_54_QF_UFNIA.smt2                                                 | 200.043s  | 200.043s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_44_QF_UFDTLIA.smt2                                               |   2.837s  |   2.837s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_44_QF_UFDTNIA.smt2                                               |  18.395s  |  18.395s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_44_QF_UFLIA.smt2                                                 |  88.315s  |  88.315s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_44_QF_UFNIA.smt2                                                 |  99.574s  |  99.574s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_45_QF_UFDTLIA.smt2                                               |   4.132s  |   4.132s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_45_QF_UFDTNIA.smt2                                               |   7.477s  |   7.477s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_45_QF_UFLIA.smt2                                                 |  36.069s  |  36.069s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_45_QF_UFNIA.smt2                                                 | 107.581s  | 107.581s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_46_QF_UFDTLIA.smt2                                               |   2.933s  |   2.933s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_46_QF_UFDTNIA.smt2                                               |  28.688s  |  28.688s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_46_QF_UFLIA.smt2                                                 |   4.301s  |   4.301s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_46_QF_UFNIA.smt2                                                 |  95.498s  |  95.498s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_47_QF_UFDTLIA.smt2                                               |  16.493s  |  16.493s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_47_QF_UFDTNIA.smt2                                               |   0.434s  |   0.434s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_47_QF_UFLIA.smt2                                                 |  38.607s  |  38.607s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_47_QF_UFNIA.smt2                                                 |   5.657s  |   5.657s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_48_QF_UFDTLIA.smt2                                               |   9.444s  |   9.444s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_48_QF_UFDTNIA.smt2                                               |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_48_QF_UFLIA.smt2                                                 |  10.226s  |  10.226s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_48_QF_UFNIA.smt2                                                 |   1.338s  |   1.338s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_61_QF_UFDTLIA.smt2                                               | 200.043s  | 200.043s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_61_QF_UFDTNIA.smt2                                               | 200.021s  | 200.021s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_61_QF_UFLIA.smt2                                                 | 200.055s  | 200.055s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_61_QF_UFNIA.smt2                                                 |   6.166s  |   6.166s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_62_QF_UFDTLIA.smt2                                               |  21.620s  |  21.620s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_62_QF_UFDTNIA.smt2                                               | 200.025s  | 200.025s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_62_QF_UFLIA.smt2                                                 |  28.528s  |  28.528s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_62_QF_UFNIA.smt2                                                 |  37.698s  |  37.698s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_63_QF_UFDTLIA.smt2                                               |   1.597s  |   1.597s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_63_QF_UFDTNIA.smt2                                               |  81.289s  |  81.289s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_63_QF_UFLIA.smt2                                                 |   5.061s  |   5.061s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_63_QF_UFNIA.smt2                                                 | 200.028s  | 200.028s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_59_QF_UFDTLIA.smt2                                               |   0.878s  |   0.878s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_59_QF_UFDTNIA.smt2                                               |   0.450s  |   0.450s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_59_QF_UFLIA.smt2                                                 |  47.561s  |  47.561s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_59_QF_UFNIA.smt2                                                 |   3.412s  |   3.412s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_60_QF_UFDTLIA.smt2                                               |   0.602s  |   0.602s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_60_QF_UFDTNIA.smt2                                               |   0.349s  |   0.349s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_60_QF_UFLIA.smt2                                                 |   3.683s  |   3.683s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_60_QF_UFNIA.smt2                                                 |   8.885s  |   8.885s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_14_QF_UFDTLIA.smt2                                               |   2.118s  |   2.118s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_14_QF_UFDTNIA.smt2                                               |   2.005s  |   2.005s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_14_QF_UFLIA.smt2                                                 |   8.889s  |   8.889s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_14_QF_UFNIA.smt2                                                 |  86.192s  |  86.192s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_15_QF_UFDTLIA.smt2                                               |   6.555s  |   6.555s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_15_QF_UFDTNIA.smt2                                               |   5.162s  |   5.162s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_15_QF_UFLIA.smt2                                                 | 200.081s  | 200.081s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_15_QF_UFNIA.smt2                                                 | 129.420s  | 129.420s  |   0.000s  | 0.0%|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFDTLIA.smt2                                   |   6.836s  |   6.836s  |   0.000s  | 0.0%|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFDTNIA.smt2                                   |   6.512s  |   6.512s  |   0.000s  | 0.0%|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFLIA.smt2                                     |  84.002s  |  84.002s  |   0.000s  | 0.0%|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFNIA.smt2                                     |  21.456s  |  21.456s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_17_QF_UFDTLIA.smt2                                               |   2.348s  |   2.348s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_17_QF_UFDTNIA.smt2                                               |   2.600s  |   2.600s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_17_QF_UFLIA.smt2                                                 |  10.670s  |  10.670s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_17_QF_UFNIA.smt2                                                 |  13.045s  |  13.045s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_18_QF_UFDTLIA.smt2                                               |   2.495s  |   2.495s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_18_QF_UFDTNIA.smt2                                               |   3.301s  |   3.301s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_18_QF_UFLIA.smt2                                                 |   7.940s  |   7.940s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_18_QF_UFNIA.smt2                                                 |  13.893s  |  13.893s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_34_QF_UFDTLIA.smt2                                               |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_34_QF_UFDTNIA.smt2                                               | 200.017s  | 200.017s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_34_QF_UFLIA.smt2                                                 |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_34_QF_UFNIA.smt2                                                 | 200.018s  | 200.018s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_35_QF_UFDTLIA.smt2                                               |   0.970s  |   0.970s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_35_QF_UFDTNIA.smt2                                               | 200.024s  | 200.024s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_35_QF_UFLIA.smt2                                                 |   0.781s  |   0.781s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_35_QF_UFNIA.smt2                                                 | 200.050s  | 200.050s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_36_QF_UFDTLIA.smt2                                               | 200.093s  | 200.093s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_36_QF_UFDTNIA.smt2                                               | 200.042s  | 200.042s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_36_QF_UFLIA.smt2                                                 | 149.041s  | 149.041s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_36_QF_UFNIA.smt2                                                 | 200.027s  | 200.027s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFDTLIA.smt2                                   |   0.509s  |   0.509s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFDTNIA.smt2                                   |   0.635s  |   0.635s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFLIA.smt2                                     |  29.125s  |  29.125s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFNIA.smt2                                     | 200.047s  | 200.047s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFDTLIA.smt2                                   |   0.535s  |   0.535s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFDTNIA.smt2                                   |   0.726s  |   0.726s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFLIA.smt2                                     |  15.451s  |  15.451s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFNIA.smt2                                     | 200.033s  | 200.033s  |   0.000s  | 0.0%|
|52759_b3ecd2335fd16ec2eee2_9_UFDTLIA.smt2                                                   | 200.019s  | 200.019s  |   0.000s  | 0.0%|
|52759_b3ecd2335fd16ec2eee2_9_UFDTNIA.smt2                                                   | 200.014s  | 200.014s  |   0.000s  | 0.0%|
|52759_b3ecd2335fd16ec2eee2_9_UFLIA.smt2                                                     | 200.032s  | 200.032s  |   0.000s  | 0.0%|
|52759_b3ecd2335fd16ec2eee2_9_UFNIA.smt2                                                     | 200.021s  | 200.021s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFDTLIA.smt2                                   |  29.719s  |  29.719s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFDTNIA.smt2                                   |  39.859s  |  39.859s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFLIA.smt2                                     |  40.124s  |  40.124s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFNIA.smt2                                     | 200.061s  | 200.061s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFDTLIA.smt2                                   |   4.957s  |   4.957s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFDTNIA.smt2                                   |   3.709s  |   3.709s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFLIA.smt2                                     |  16.782s  |  16.782s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFNIA.smt2                                     |  14.456s  |  14.456s  |   0.000s  | 0.0%|
|63058_55d6bef5390186355f11_26_QF_UFDTLIA.smt2                                               |   2.767s  |   2.767s  |   0.000s  | 0.0%|
|63058_55d6bef5390186355f11_26_QF_UFDTNIA.smt2                                               |   5.017s  |   5.017s  |   0.000s  | 0.0%|
|63058_55d6bef5390186355f11_26_QF_UFLIA.smt2                                                 |  29.645s  |  29.645s  |   0.000s  | 0.0%|
|63058_55d6bef5390186355f11_26_QF_UFNIA.smt2                                                 |  26.426s  |  26.426s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_22_QF_UFDTLIA.smt2                                               |   3.666s  |   3.666s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_22_QF_UFDTNIA.smt2                                               |   5.999s  |   5.999s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_22_QF_UFLIA.smt2                                                 |  16.907s  |  16.907s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_22_QF_UFNIA.smt2                                                 |  36.612s  |  36.612s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_23_QF_UFDTLIA.smt2                                               |   2.908s  |   2.908s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_23_QF_UFDTNIA.smt2                                               |   6.917s  |   6.917s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_23_QF_UFLIA.smt2                                                 |  34.180s  |  34.180s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_23_QF_UFNIA.smt2                                                 | 200.032s  | 200.032s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_24_QF_UFDTLIA.smt2                                               |   3.112s  |   3.112s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_24_QF_UFDTNIA.smt2                                               |   3.804s  |   3.804s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_24_QF_UFLIA.smt2                                                 |  39.809s  |  39.809s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_24_QF_UFNIA.smt2                                                 | 200.052s  | 200.052s  |   0.000s  | 0.0%|
|63058_aa742630eef64f949de269382c1f9035_25_UFDTLIA.smt2                                      |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|63058_aa742630eef64f949de269382c1f9035_25_UFDTNIA.smt2                                      |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|63058_aa742630eef64f949de269382c1f9035_25_UFLIA.smt2                                        |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|63058_aa742630eef64f949de269382c1f9035_25_UFNIA.smt2                                        |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_5_QF_UFDTLIA.smt2                                                | 200.067s  | 200.067s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_5_QF_UFDTNIA.smt2                                                | 200.035s  | 200.035s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_5_QF_UFLIA.smt2                                                  | 200.042s  | 200.042s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_5_QF_UFNIA.smt2                                                  | 200.017s  | 200.017s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_6_QF_UFDTLIA.smt2                                                |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_6_QF_UFDTNIA.smt2                                                |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_6_QF_UFLIA.smt2                                                  |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_6_QF_UFNIA.smt2                                                  |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_7_QF_UFDTLIA.smt2                                                |   0.583s  |   0.583s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_7_QF_UFDTNIA.smt2                                                |  10.235s  |  10.235s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_7_QF_UFLIA.smt2                                                  |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_7_QF_UFNIA.smt2                                                  |   2.148s  |   2.148s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_8_QF_UFDTLIA.smt2                                                |   0.642s  |   0.642s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_8_QF_UFDTNIA.smt2                                                |   2.489s  |   2.489s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_8_QF_UFLIA.smt2                                                  |   0.424s  |   0.424s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_8_QF_UFNIA.smt2                                                  |   1.934s  |   1.934s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_72_QF_UFDTLIA.smt2                                               |   5.554s  |   5.554s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_72_QF_UFDTNIA.smt2                                               |   5.310s  |   5.310s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_72_QF_UFLIA.smt2                                                 |  13.981s  |  13.981s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                                                 |  23.056s  |  23.056s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_73_QF_UFDTLIA.smt2                                               | 200.049s  | 200.049s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_73_QF_UFDTNIA.smt2                                               |   7.001s  |   7.001s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_73_QF_UFLIA.smt2                                                 | 200.099s  | 200.099s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_73_QF_UFNIA.smt2                                                 | 200.094s  | 200.094s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_74_QF_UFDTLIA.smt2                                               |  13.748s  |  13.748s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_74_QF_UFDTNIA.smt2                                               | 200.036s  | 200.036s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_74_QF_UFLIA.smt2                                                 | 200.183s  | 200.183s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_74_QF_UFNIA.smt2                                                 | 200.157s  | 200.157s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_75_QF_UFDTLIA.smt2                                               |  18.531s  |  18.531s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_75_QF_UFDTNIA.smt2                                               | 200.030s  | 200.030s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_75_QF_UFLIA.smt2                                                 | 200.190s  | 200.190s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_75_QF_UFNIA.smt2                                                 | 200.126s  | 200.126s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_76_QF_UFDTLIA.smt2                                               |  15.561s  |  15.561s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_76_QF_UFDTNIA.smt2                                               |  12.455s  |  12.455s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_76_QF_UFLIA.smt2                                                 |  36.382s  |  36.382s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_76_QF_UFNIA.smt2                                                 | 200.200s  | 200.200s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_70_QF_UFDTLIA.smt2                                               |   1.582s  |   1.582s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_70_QF_UFDTNIA.smt2                                               | 200.014s  | 200.014s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_70_QF_UFLIA.smt2                                                 |   9.581s  |   9.581s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_70_QF_UFNIA.smt2                                                 |   2.976s  |   2.976s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_71_QF_UFDTLIA.smt2                                               | 200.085s  | 200.085s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_71_QF_UFDTNIA.smt2                                               | 200.019s  | 200.019s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_71_QF_UFLIA.smt2                                                 | 200.059s  | 200.059s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_71_QF_UFNIA.smt2                                                 | 200.031s  | 200.031s  |   0.000s  | 0.0%|
|72771_f9d228efc97cf1458e38_64_QF_UFDTLIA.smt2                                               |   2.797s  |   2.797s  |   0.000s  | 0.0%|
|72771_f9d228efc97cf1458e38_64_QF_UFDTNIA.smt2                                               |   0.532s  |   0.532s  |   0.000s  | 0.0%|
|72771_f9d228efc97cf1458e38_64_QF_UFLIA.smt2                                                 |  22.011s  |  22.011s  |   0.000s  | 0.0%|
|72771_f9d228efc97cf1458e38_64_QF_UFNIA.smt2                                                 |   1.728s  |   1.728s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_0_UFDTLIA.smt2                                                   |   7.294s  |   7.294s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_0_UFDTNIA.smt2                                                   |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_0_UFLIA.smt2                                                     |  35.576s  |  35.576s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_0_UFNIA.smt2                                                     |   0.872s  |   0.872s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_1_UFDTLIA.smt2                                                   | 200.072s  | 200.072s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_1_UFDTNIA.smt2                                                   |  47.841s  |  47.841s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_1_UFLIA.smt2                                                     | 200.071s  | 200.071s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_1_UFNIA.smt2                                                     |   1.676s  |   1.676s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_2_UFDTLIA.smt2                                                   | 200.075s  | 200.075s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_2_UFDTNIA.smt2                                                   |  55.687s  |  55.687s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_2_UFLIA.smt2                                                     | 200.040s  | 200.040s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_2_UFNIA.smt2                                                     | 200.034s  | 200.034s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_3_UFDTLIA.smt2                                                   | 111.388s  | 111.388s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_3_UFDTNIA.smt2                                                   | 200.039s  | 200.039s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_3_UFLIA.smt2                                                     | 200.084s  | 200.084s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_3_UFNIA.smt2                                                     | 200.033s  | 200.033s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_4_UFDTLIA.smt2                                                   | 200.086s  | 200.086s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_4_UFDTNIA.smt2                                                   |  55.058s  |  55.058s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_4_UFLIA.smt2                                                     | 200.105s  | 200.105s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_4_UFNIA.smt2                                                     | 200.050s  | 200.050s  |   0.000s  | 0.0%|
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFDTLIA.smt2                                   |  19.755s  |  19.755s  |   0.000s  | 0.0%|
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFDTNIA.smt2                                   | 122.822s  | 122.822s  |   0.000s  | 0.0%|
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFLIA.smt2                                     | 200.033s  | 200.033s  |   0.000s  | 0.0%|
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFNIA.smt2                                     |  89.936s  |  89.936s  |   0.000s  | 0.0%|
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFDTLIA.smt2                                   |  30.344s  |  30.344s  |   0.000s  | 0.0%|
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFDTNIA.smt2                                   |  19.852s  |  19.852s  |   0.000s  | 0.0%|
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFLIA.smt2                                     | 200.032s  | 200.032s  |   0.000s  | 0.0%|
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFNIA.smt2                                     |  14.643s  |  14.643s  |   0.000s  | 0.0%|
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFDTLIA.smt2                                   | 200.047s  | 200.047s  |   0.000s  | 0.0%|
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFDTNIA.smt2                                   | 200.048s  | 200.048s  |   0.000s  | 0.0%|
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFLIA.smt2                                     | 200.068s  | 200.068s  |   0.000s  | 0.0%|
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFNIA.smt2                                     | 200.066s  | 200.066s  |   0.000s  | 0.0%|
|93493_5990a6bf5f2740164f77_50_QF_UFDTLIA.smt2                                               |  65.425s  |  65.425s  |   0.000s  | 0.0%|
|93493_5990a6bf5f2740164f77_50_QF_UFDTNIA.smt2                                               | 142.850s  | 142.850s  |   0.000s  | 0.0%|
|93493_5990a6bf5f2740164f77_50_QF_UFLIA.smt2                                                 | 200.101s  | 200.101s  |   0.000s  | 0.0%|
|93493_5990a6bf5f2740164f77_50_QF_UFNIA.smt2                                                 | 200.085s  | 200.085s  |   0.000s  | 0.0%|
|93493_798593962ee29ad45ac8_52_QF_UFDTLIA.smt2                                               | 200.039s  | 200.039s  |   0.000s  | 0.0%|
|93493_798593962ee29ad45ac8_52_QF_UFDTNIA.smt2                                               | 200.026s  | 200.026s  |   0.000s  | 0.0%|
|93493_798593962ee29ad45ac8_52_QF_UFLIA.smt2                                                 | 200.037s  | 200.037s  |   0.000s  | 0.0%|
|93493_798593962ee29ad45ac8_52_QF_UFNIA.smt2                                                 | 200.030s  | 200.030s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_29_QF_UFDTLIA.smt2                                                 | 200.068s  | 200.068s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_29_QF_UFDTNIA.smt2                                                 |  26.765s  |  26.765s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_29_QF_UFLIA.smt2                                                   | 200.102s  | 200.102s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_29_QF_UFNIA.smt2                                                   | 200.072s  | 200.072s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_30_QF_UFDTLIA.smt2                                                 | 200.063s  | 200.063s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_30_QF_UFDTNIA.smt2                                                 |  25.690s  |  25.690s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_30_QF_UFLIA.smt2                                                   | 200.065s  | 200.065s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_30_QF_UFNIA.smt2                                                   |  34.778s  |  34.778s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_31_QF_UFDTLIA.smt2                                                 | 200.073s  | 200.073s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_31_QF_UFDTNIA.smt2                                                 |  12.453s  |  12.453s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_31_QF_UFLIA.smt2                                                   |  49.093s  |  49.093s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_31_QF_UFNIA.smt2                                                   |   7.413s  |   7.413s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_32_QF_UFDTLIA.smt2                                                 | 200.082s  | 200.082s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_32_QF_UFDTNIA.smt2                                                 |  43.959s  |  43.959s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_32_QF_UFLIA.smt2                                                   | 200.076s  | 200.076s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_32_QF_UFNIA.smt2                                                   | 118.778s  | 118.778s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_33_QF_UFDTLIA.smt2                                                 | 200.054s  | 200.054s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_33_QF_UFDTNIA.smt2                                                 |  33.257s  |  33.257s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_33_QF_UFLIA.smt2                                                   | 200.051s  | 200.051s  |   0.000s  | 0.0%|
</details>
