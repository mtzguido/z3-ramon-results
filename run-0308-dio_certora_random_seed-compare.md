Comparing data and data


# SUMMARY
- LHS tests = 308
- RHS tests = 308
- LHS success = 0  (0.0%)
- RHS success = 0  (0.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: dio on certora random seed
Job tag: dio_certora_random_seed
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 14e2aadad0b55b8b6c52e52ea534f9470c8f88dd
Z3 branch: 
Z3 options: "-T:600 lp.dio_eqs=true -st smt.random_seed=159"
Z3 inputs: inputs/certora
Z3 commit message: include LICENSE.txt in wheels (#7614)

Update setup.py so that we copy LICENSE.TXT to src/api/python before
creating the sdist.  Any wheels built from this sdist will now
contain the LICENSE.txt file.

Fixes #7604

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: dio on certora random seed
Job tag: dio_certora_random_seed
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 14e2aadad0b55b8b6c52e52ea534f9470c8f88dd
Z3 branch: 
Z3 options: "-T:600 lp.dio_eqs=true -st smt.random_seed=159"
Z3 inputs: inputs/certora
Z3 commit message: include LICENSE.txt in wheels (#7614)

Update setup.py so that we copy LICENSE.TXT to src/api/python before
creating the sdist.  Any wheels built from this sdist will now
contain the LICENSE.txt file.

Fixes #7604

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
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTNIA.smt2                                  |   0.010s |1484.0KiB|
|72658_63104dadde9c6026353f_71_QF_UFDTNIA.smt2                                              |   0.009s |1560.0KiB|
|30078_f817a923328f75af7e60_27_QF_UFDTNIA.smt2                                              |   0.009s |1560.0KiB|
|940_590f27b1c3c800d3243e_31_QF_UFLIA.smt2                                                  |   0.008s |1564.0KiB|
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFLIA.smt2                                     |   0.008s |1564.0KiB|
|39657_1c7158801cd59dc13f05_44_QF_UFLIA.smt2                                                |   0.008s |1556.0KiB|
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFDTLIA.smt2                                   |   0.008s |1560.0KiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTNIA.smt2                                  |   0.008s |1788.0KiB|
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFDTNIA.smt2                                  |   0.007s |1560.0KiB|
|44289_e5a2e5c780236919ee6a_18_QF_UFDTLIA.smt2                                              |   0.007s |1560.0KiB|
|44289_4066055e0f64d96da11a_15_QF_UFDTLIA.smt2                                              |   0.007s |1560.0KiB|
|63058_aa742630eef64f949de269382c1f9035_25_UFDTLIA.smt2                                     |   0.007s |1552.0KiB|
|44289_e5a2e5c780236919ee6a_18_QF_UFDTNIA.smt2                                              |   0.007s |1412.0KiB|
|41958_32933c5a1384696720a2_63_QF_UFLIA.smt2                                                |   0.007s |1560.0KiB|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                |   0.007s |1556.0KiB|
|44289_e5a2e5c780236919ee6a_17_QF_UFDTLIA.smt2                                              |   0.007s |1552.0KiB|
|44289_4066055e0f64d96da11a_14_QF_UFDTLIA.smt2                                              |   0.007s |1596.0KiB|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                |   0.007s |1328.0KiB|
|30078_f817a923328f75af7e60_28_QF_UFDTNIA.smt2                                              |   0.007s |1788.0KiB|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFNIA.smt2                                    |   0.007s |1560.0KiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTNIA.smt2                                  |   0.010s |1484.0KiB|
|72658_63104dadde9c6026353f_71_QF_UFDTNIA.smt2                                              |   0.009s |1560.0KiB|
|30078_f817a923328f75af7e60_27_QF_UFDTNIA.smt2                                              |   0.009s |1560.0KiB|
|940_590f27b1c3c800d3243e_31_QF_UFLIA.smt2                                                  |   0.008s |1564.0KiB|
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFLIA.smt2                                     |   0.008s |1564.0KiB|
|39657_1c7158801cd59dc13f05_44_QF_UFLIA.smt2                                                |   0.008s |1556.0KiB|
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFDTLIA.smt2                                   |   0.008s |1560.0KiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTNIA.smt2                                  |   0.008s |1788.0KiB|
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFDTNIA.smt2                                  |   0.007s |1560.0KiB|
|44289_e5a2e5c780236919ee6a_18_QF_UFDTLIA.smt2                                              |   0.007s |1560.0KiB|
|44289_4066055e0f64d96da11a_15_QF_UFDTLIA.smt2                                              |   0.007s |1560.0KiB|
|63058_aa742630eef64f949de269382c1f9035_25_UFDTLIA.smt2                                     |   0.007s |1552.0KiB|
|44289_e5a2e5c780236919ee6a_18_QF_UFDTNIA.smt2                                              |   0.007s |1412.0KiB|
|41958_32933c5a1384696720a2_63_QF_UFLIA.smt2                                                |   0.007s |1560.0KiB|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                |   0.007s |1556.0KiB|
|44289_e5a2e5c780236919ee6a_17_QF_UFDTLIA.smt2                                              |   0.007s |1552.0KiB|
|44289_4066055e0f64d96da11a_14_QF_UFDTLIA.smt2                                              |   0.007s |1596.0KiB|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                |   0.007s |1328.0KiB|
|30078_f817a923328f75af7e60_28_QF_UFDTNIA.smt2                                              |   0.007s |1788.0KiB|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFNIA.smt2                                    |   0.007s |1560.0KiB|
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
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTNIA.smt2                                  |   0.008s |1788.0KiB|
|30078_f817a923328f75af7e60_28_QF_UFDTNIA.smt2                                              |   0.007s |1788.0KiB|
|41958_45c688a4814eb926c254_60_QF_UFDTLIA.smt2                                              |   0.006s |1788.0KiB|
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFNIA.smt2                                    |   0.005s |1788.0KiB|
|3106_1c933134166dbad31f79_40_QF_UFNIA.smt2                                                 |   0.005s |1788.0KiB|
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFDTLIA.smt2                                  |   0.005s |1788.0KiB|
|41958_45c688a4814eb926c254_59_QF_UFLIA.smt2                                                |   0.004s |1788.0KiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTLIA.smt2                                  |   0.004s |1788.0KiB|
|63058_64ab9a7ef7b6c3492507_24_QF_UFNIA.smt2                                                |   0.004s |1788.0KiB|
|63058_64ab9a7ef7b6c3492507_24_QF_UFLIA.smt2                                                |   0.003s |1788.0KiB|
|63058_64ab9a7ef7b6c3492507_23_QF_UFLIA.smt2                                                |   0.003s |1788.0KiB|
|3106_1c933134166dbad31f79_38_QF_UFDTLIA.smt2                                               |   0.003s |1788.0KiB|
|83314_a702bf8b823398c9e37a_4_UFLIA.smt2                                                    |   0.003s |1788.0KiB|
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFDTLIA.smt2                                  |   0.005s |1784.0KiB|
|83314_a702bf8b823398c9e37a_1_UFDTLIA.smt2                                                  |   0.003s |1784.0KiB|
|3106_1c933134166dbad31f79_39_QF_UFLIA.smt2                                                 |   0.003s |1784.0KiB|
|65782_cd31513fdcd15701933b_5_QF_UFNIA.smt2                                                 |   0.006s |1780.0KiB|
|940_590f27b1c3c800d3243e_29_QF_UFLIA.smt2                                                  |   0.004s |1780.0KiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFNIA.smt2                                    |   0.005s |1740.0KiB|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFDTNIA.smt2                                  |   0.005s |1732.0KiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTNIA.smt2                                  |   0.008s |1788.0KiB|
|30078_f817a923328f75af7e60_28_QF_UFDTNIA.smt2                                              |   0.007s |1788.0KiB|
|41958_45c688a4814eb926c254_60_QF_UFDTLIA.smt2                                              |   0.006s |1788.0KiB|
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFNIA.smt2                                    |   0.005s |1788.0KiB|
|3106_1c933134166dbad31f79_40_QF_UFNIA.smt2                                                 |   0.005s |1788.0KiB|
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFDTLIA.smt2                                  |   0.005s |1788.0KiB|
|41958_45c688a4814eb926c254_59_QF_UFLIA.smt2                                                |   0.004s |1788.0KiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTLIA.smt2                                  |   0.004s |1788.0KiB|
|63058_64ab9a7ef7b6c3492507_24_QF_UFNIA.smt2                                                |   0.004s |1788.0KiB|
|63058_64ab9a7ef7b6c3492507_24_QF_UFLIA.smt2                                                |   0.003s |1788.0KiB|
|63058_64ab9a7ef7b6c3492507_23_QF_UFLIA.smt2                                                |   0.003s |1788.0KiB|
|3106_1c933134166dbad31f79_38_QF_UFDTLIA.smt2                                               |   0.003s |1788.0KiB|
|83314_a702bf8b823398c9e37a_4_UFLIA.smt2                                                    |   0.003s |1788.0KiB|
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFDTLIA.smt2                                  |   0.005s |1784.0KiB|
|83314_a702bf8b823398c9e37a_1_UFDTLIA.smt2                                                  |   0.003s |1784.0KiB|
|3106_1c933134166dbad31f79_39_QF_UFLIA.smt2                                                 |   0.003s |1784.0KiB|
|65782_cd31513fdcd15701933b_5_QF_UFNIA.smt2                                                 |   0.006s |1780.0KiB|
|940_590f27b1c3c800d3243e_29_QF_UFLIA.smt2                                                  |   0.004s |1780.0KiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFNIA.smt2                                    |   0.005s |1740.0KiB|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFDTNIA.smt2                                  |   0.005s |1732.0KiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>
