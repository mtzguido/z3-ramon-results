Comparing data and data


# SUMMARY
- LHS tests = 2313
- RHS tests = 2313
- LHS success = 0  (0.0%)
- RHS success = 0  (0.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: dio no dio on qf_nia small
Job tag: dio_no_dio_qf_nia_small
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 14e2aadad0b55b8b6c52e52ea534f9470c8f88dd
Z3 branch: 
Z3 options: "-T:600 lp.dio_eqs=false -st"
Z3 inputs: inputs/QF_NIA_small
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
Job description: dio no dio on qf_nia small
Job tag: dio_no_dio_qf_nia_small
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 14e2aadad0b55b8b6c52e52ea534f9470c8f88dd
Z3 branch: 
Z3 options: "-T:600 lp.dio_eqs=false -st"
Z3 inputs: inputs/QF_NIA_small
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
|From_T2__florian_sas2.t2__p32378_terminationG_0.smt2                                       |   0.012s |1564.0KiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9322_safety_0.smt2               |   0.011s |1560.0KiB|
|problem-006501.cvc.1.smt2                                                                  |   0.011s |1504.0KiB|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6071_safety_0.smt2                       |   0.010s |1780.0KiB|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5299_safety_0.smt2                          |   0.010s |1560.0KiB|
|From_T2__zlib-adler32.c.t2__p26088_safety_0.smt2                                           |   0.007s |1556.0KiB|
|From_T2__s1.t2_fixed__p17686_safety_0.smt2                                                 |   0.007s |1564.0KiB|
|1933.smt2                                                                                  |   0.007s |1560.0KiB|
|From_T2__s1-striped.t2_fixed__p10066_safety_0.smt2                                         |   0.007s |1560.0KiB|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31599_safety_0.smt2              |   0.006s |1560.0KiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8294_safety_0.smt2               |   0.006s |1564.0KiB|
|From_T2__s1.t2__p18239_safety_0.smt2                                                       |   0.006s |1520.0KiB|
|From_T2__compress.t2__p17860_terminationG_0.smt2                                           |   0.006s |1496.0KiB|
|aproveSMT2477805317391230600.smt2                                                          |   0.006s |1364.0KiB|
|From_T2__slayer-n5-filtered.t2__p23413_safety_0.smt2                                       |   0.006s |1560.0KiB|
|824.smt2                                                                                   |   0.006s |1560.0KiB|
|From_T2__s1.t2__p19894_safety_0.smt2                                                       |   0.006s |1424.0KiB|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32746_safety_0.smt2            |   0.006s |1548.0KiB|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__terminationQ_0_0.smt2                   |   0.006s |1772.0KiB|
|From_T2__svdcmp.t2__term_unfeasibility_10_0.smt2                                           |   0.006s |1560.0KiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_T2__florian_sas2.t2__p32378_terminationG_0.smt2                                       |   0.012s |1564.0KiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9322_safety_0.smt2               |   0.011s |1560.0KiB|
|problem-006501.cvc.1.smt2                                                                  |   0.011s |1504.0KiB|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6071_safety_0.smt2                       |   0.010s |1780.0KiB|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5299_safety_0.smt2                          |   0.010s |1560.0KiB|
|From_T2__zlib-adler32.c.t2__p26088_safety_0.smt2                                           |   0.007s |1556.0KiB|
|From_T2__s1.t2_fixed__p17686_safety_0.smt2                                                 |   0.007s |1564.0KiB|
|1933.smt2                                                                                  |   0.007s |1560.0KiB|
|From_T2__s1-striped.t2_fixed__p10066_safety_0.smt2                                         |   0.007s |1560.0KiB|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31599_safety_0.smt2              |   0.006s |1560.0KiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8294_safety_0.smt2               |   0.006s |1564.0KiB|
|From_T2__s1.t2__p18239_safety_0.smt2                                                       |   0.006s |1520.0KiB|
|From_T2__compress.t2__p17860_terminationG_0.smt2                                           |   0.006s |1496.0KiB|
|aproveSMT2477805317391230600.smt2                                                          |   0.006s |1364.0KiB|
|From_T2__slayer-n5-filtered.t2__p23413_safety_0.smt2                                       |   0.006s |1560.0KiB|
|824.smt2                                                                                   |   0.006s |1560.0KiB|
|From_T2__s1.t2__p19894_safety_0.smt2                                                       |   0.006s |1424.0KiB|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32746_safety_0.smt2            |   0.006s |1548.0KiB|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__terminationQ_0_0.smt2                   |   0.006s |1772.0KiB|
|From_T2__svdcmp.t2__term_unfeasibility_10_0.smt2                                           |   0.006s |1560.0KiB|
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
|aproveSMT3839584170547805483.smt2                                                          |   0.004s |1812.0KiB|
|From_T2__ex36.t2__p28282_safety_0.smt2                                                     |   0.005s |1804.0KiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9165_safety_0.smt2               |   0.004s |1800.0KiB|
|From_T2__s1-striped.t2_fixed__p10316_safety_0.smt2                                         |   0.004s |1800.0KiB|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_9_0.smt2                        |   0.005s |1792.0KiB|
|From_T2__s1.t2__p21013_safety_0.smt2                                                       |   0.005s |1792.0KiB|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_43_0.smt2                          |   0.004s |1792.0KiB|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3037_safety_0.smt2         |   0.004s |1792.0KiB|
|From_T2__s1-striped.t2__p13058_safety_0.smt2                                               |   0.004s |1792.0KiB|
|From_T2__slayer-3-filtered.t2__p21547_terminationG_0.smt2                                  |   0.004s |1792.0KiB|
|From_T2__ex36.t2__p29075_safety_0.smt2                                                     |   0.004s |1792.0KiB|
|From_T2__slayer-3-new.t2__p21988_terminationG_0.smt2                                       |   0.004s |1792.0KiB|
|From_T2__ex36.t2__p28763_safety_0.smt2                                                     |   0.004s |1792.0KiB|
|From_T2__ex36.t2__p29769_safety_0.smt2                                                     |   0.004s |1792.0KiB|
|From_T2__ppblockterm.t2__p7872_terminationG_0.smt2                                         |   0.003s |1792.0KiB|
|From_T2__slayer-3-filtered.t2__p21597_terminationG_0.smt2                                  |   0.003s |1792.0KiB|
|From_T2__ex36.t2__p31964_safety_0.smt2                                                     |   0.003s |1792.0KiB|
|From_AProVE_2014__MainCopy.jar-obl-10__p10342_terminationG_0.smt2                          |   0.003s |1792.0KiB|
|From_AProVE_2014__Velroyen08-even.jar-obl-9__p13541_terminationG_0.smt2                    |   0.003s |1792.0KiB|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29475_terminationG_0.smt2                        |   0.003s |1792.0KiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|aproveSMT3839584170547805483.smt2                                                          |   0.004s |1812.0KiB|
|From_T2__ex36.t2__p28282_safety_0.smt2                                                     |   0.005s |1804.0KiB|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9165_safety_0.smt2               |   0.004s |1800.0KiB|
|From_T2__s1-striped.t2_fixed__p10316_safety_0.smt2                                         |   0.004s |1800.0KiB|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_9_0.smt2                        |   0.005s |1792.0KiB|
|From_T2__s1.t2__p21013_safety_0.smt2                                                       |   0.005s |1792.0KiB|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_43_0.smt2                          |   0.004s |1792.0KiB|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3037_safety_0.smt2         |   0.004s |1792.0KiB|
|From_T2__s1-striped.t2__p13058_safety_0.smt2                                               |   0.004s |1792.0KiB|
|From_T2__slayer-3-filtered.t2__p21547_terminationG_0.smt2                                  |   0.004s |1792.0KiB|
|From_T2__ex36.t2__p29075_safety_0.smt2                                                     |   0.004s |1792.0KiB|
|From_T2__slayer-3-new.t2__p21988_terminationG_0.smt2                                       |   0.004s |1792.0KiB|
|From_T2__ex36.t2__p28763_safety_0.smt2                                                     |   0.004s |1792.0KiB|
|From_T2__ex36.t2__p29769_safety_0.smt2                                                     |   0.004s |1792.0KiB|
|From_T2__ppblockterm.t2__p7872_terminationG_0.smt2                                         |   0.003s |1792.0KiB|
|From_T2__slayer-3-filtered.t2__p21597_terminationG_0.smt2                                  |   0.003s |1792.0KiB|
|From_T2__ex36.t2__p31964_safety_0.smt2                                                     |   0.003s |1792.0KiB|
|From_AProVE_2014__MainCopy.jar-obl-10__p10342_terminationG_0.smt2                          |   0.003s |1792.0KiB|
|From_AProVE_2014__Velroyen08-even.jar-obl-9__p13541_terminationG_0.smt2                    |   0.003s |1792.0KiB|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29475_terminationG_0.smt2                        |   0.003s |1792.0KiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
</details>
