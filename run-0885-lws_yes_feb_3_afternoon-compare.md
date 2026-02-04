Comparing data and data


# SUMMARY
- LHS tests = 2313
- RHS tests = 2313
- LHS success = 2298  (99.3514915693904%)
- RHS success = 2298  (99.3514915693904%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: yes lws
Job tag: lws_yes_feb_3_afternoon
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: beacd4358794404e164ab5be34d0302542e0f70d
Z3 branch: lws
Z3 options: "-T:600 nlsat.lws=true smt.random_seed=6"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: fix issue 8397

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: yes lws
Job tag: lws_yes_feb_3_afternoon
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: beacd4358794404e164ab5be34d0302542e0f70d
Z3 branch: lws
Z3 options: "-T:600 nlsat.lws=true smt.random_seed=6"
Z3 inputs: inputs/QF_NIA_small
Z3 commit message: fix issue 8397

Signed-off-by: Lev Nachmanson <levnach@hotmail.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 600.061s  | 600.061s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 600.090s  | 600.090s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.479s  |   1.479s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.315s  |   0.315s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.345s  |   0.345s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.069s  |   1.069s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 600.096s  | 600.096s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.349s  |   0.349s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.132s  |   0.132s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 600.061s  | 600.061s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 600.090s  | 600.090s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.479s  |   1.479s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.315s  |   0.315s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.345s  |   0.345s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.069s  |   1.069s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 600.096s  | 600.096s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.349s  |   0.349s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.132s  |   0.132s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 600.061s  | 600.061s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 600.090s  | 600.090s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.479s  |   1.479s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.315s  |   0.315s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.345s  |   0.345s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.069s  |   1.069s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 600.096s  | 600.096s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.349s  |   0.349s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.132s  |   0.132s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 600.061s  | 600.061s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 600.090s  | 600.090s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.479s  |   1.479s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.315s  |   0.315s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.345s  |   0.345s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.069s  |   1.069s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 600.096s  | 600.096s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.349s  |   0.349s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.132s  |   0.132s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|177.smt2                                                                                   | 659.907s |152.0MiB|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13504_terminationG_0.smt2                  | 654.238s |191.0MiB|
|From_T2__destroy_seg_leak.t2__p18873_terminationG_0.smt2                                   | 646.822s |203.0MiB|
|From_T2__small35.t2__p24016_terminationG_0.smt2                                            | 646.631s |123.0MiB|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1619_terminationG_0.smt2                       | 644.235s |611.0MiB|
|From_T2__streamserver-succeed.t2__p24621_terminationG_0.smt2                               | 633.250s |1423.0MiB|
|From_T2__s1-striped.t2_fixed__p9772_safety_0.smt2                                          | 631.763s |112.0MiB|
|From_T2__n-46.t2__p4403_terminationG_0.smt2                                                | 628.945s |193.0MiB|
|From_T2__n-5.t2_fixed__p4590_terminationG_0.smt2                                           | 618.474s |360.0MiB|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2674_safety_0.smt2                   | 615.283s |98.0MiB|
|Stroeder_15__svcomp_ex2.c__p25903_terminationG_0.smt2                                      | 613.489s |246.0MiB|
|From_T2__slayer-3-new.t2__p21954_terminationG_0.smt2                                       | 608.143s |820.0MiB|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31977_safety_0.smt2            | 608.092s |160.0MiB|
|From_T2__fun1.t2_fixed__p754_terminationG_0.smt2                                           | 607.823s |840.0MiB|
|From_T2__small35.t2__p24066_terminationG_0.smt2                                            | 607.627s |197.0MiB|
|From_T2__s1.t2__p20857_safety_0.smt2                                                       | 607.580s |74.472MiB|
|Stroeder_15__Et1.c__p22595_terminationG_0.smt2                                             | 607.574s |168.0MiB|
|Stroeder_15__Choose.c__p22179_terminationG_0.smt2                                          | 607.307s |547.0MiB|
|From_T2__ex36.t2__p31189_safety_0.smt2                                                     | 607.255s |152.0MiB|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5002_safety_0.smt2                          | 607.217s |589.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|177.smt2                                                                                   | 659.907s |152.0MiB|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13504_terminationG_0.smt2                  | 654.238s |191.0MiB|
|From_T2__destroy_seg_leak.t2__p18873_terminationG_0.smt2                                   | 646.822s |203.0MiB|
|From_T2__small35.t2__p24016_terminationG_0.smt2                                            | 646.631s |123.0MiB|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1619_terminationG_0.smt2                       | 644.235s |611.0MiB|
|From_T2__streamserver-succeed.t2__p24621_terminationG_0.smt2                               | 633.250s |1423.0MiB|
|From_T2__s1-striped.t2_fixed__p9772_safety_0.smt2                                          | 631.763s |112.0MiB|
|From_T2__n-46.t2__p4403_terminationG_0.smt2                                                | 628.945s |193.0MiB|
|From_T2__n-5.t2_fixed__p4590_terminationG_0.smt2                                           | 618.474s |360.0MiB|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2674_safety_0.smt2                   | 615.283s |98.0MiB|
|Stroeder_15__svcomp_ex2.c__p25903_terminationG_0.smt2                                      | 613.489s |246.0MiB|
|From_T2__slayer-3-new.t2__p21954_terminationG_0.smt2                                       | 608.143s |820.0MiB|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31977_safety_0.smt2            | 608.092s |160.0MiB|
|From_T2__fun1.t2_fixed__p754_terminationG_0.smt2                                           | 607.823s |840.0MiB|
|From_T2__small35.t2__p24066_terminationG_0.smt2                                            | 607.627s |197.0MiB|
|From_T2__s1.t2__p20857_safety_0.smt2                                                       | 607.580s |74.472MiB|
|Stroeder_15__Et1.c__p22595_terminationG_0.smt2                                             | 607.574s |168.0MiB|
|Stroeder_15__Choose.c__p22179_terminationG_0.smt2                                          | 607.307s |547.0MiB|
|From_T2__ex36.t2__p31189_safety_0.smt2                                                     | 607.255s |152.0MiB|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5002_safety_0.smt2                          | 607.217s |589.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |94.844MiB|94.844MiB|0B| 0.0%|
|04.smt2                                                                                     |77.26MiB|77.26MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |27.124MiB|27.124MiB|0B| 0.0%|
|1010.smt2                                                                                   |27.436MiB|27.436MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.524MiB|23.524MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.028MiB|24.028MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.92MiB|24.92MiB|0B| 0.0%|
|1063.smt2                                                                                   |26.372MiB|26.372MiB|0B| 0.0%|
|107.smt2                                                                                    |22.272MiB|22.272MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.476MiB|27.476MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.12MiB|80.12MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.104MiB|23.104MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.276MiB|23.276MiB|0B| 0.0%|
|1092.smt2                                                                                   |25.24MiB|25.24MiB|0B| 0.0%|
|11.smt2                                                                                     |81.884MiB|81.884MiB|0B| 0.0%|
|1104.smt2                                                                                   |23.608MiB|23.608MiB|0B| 0.0%|
|1112.smt2                                                                                   |25.62MiB|25.62MiB|0B| 0.0%|
|1113.smt2                                                                                   |23.46MiB|23.46MiB|0B| 0.0%|
|1126.smt2                                                                                   |24.128MiB|24.128MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |94.844MiB|94.844MiB|0B| 0.0%|
|04.smt2                                                                                     |77.26MiB|77.26MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |27.124MiB|27.124MiB|0B| 0.0%|
|1010.smt2                                                                                   |27.436MiB|27.436MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.524MiB|23.524MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.028MiB|24.028MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.92MiB|24.92MiB|0B| 0.0%|
|1063.smt2                                                                                   |26.372MiB|26.372MiB|0B| 0.0%|
|107.smt2                                                                                    |22.272MiB|22.272MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.476MiB|27.476MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.12MiB|80.12MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.104MiB|23.104MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.276MiB|23.276MiB|0B| 0.0%|
|1092.smt2                                                                                   |25.24MiB|25.24MiB|0B| 0.0%|
|11.smt2                                                                                     |81.884MiB|81.884MiB|0B| 0.0%|
|1104.smt2                                                                                   |23.608MiB|23.608MiB|0B| 0.0%|
|1112.smt2                                                                                   |25.62MiB|25.62MiB|0B| 0.0%|
|1113.smt2                                                                                   |23.46MiB|23.46MiB|0B| 0.0%|
|1126.smt2                                                                                   |24.128MiB|24.128MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |94.844MiB|94.844MiB|0B| 0.0%|
|04.smt2                                                                                     |77.26MiB|77.26MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |27.124MiB|27.124MiB|0B| 0.0%|
|1010.smt2                                                                                   |27.436MiB|27.436MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.524MiB|23.524MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.028MiB|24.028MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.92MiB|24.92MiB|0B| 0.0%|
|1063.smt2                                                                                   |26.372MiB|26.372MiB|0B| 0.0%|
|107.smt2                                                                                    |22.272MiB|22.272MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.476MiB|27.476MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.12MiB|80.12MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.104MiB|23.104MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.276MiB|23.276MiB|0B| 0.0%|
|1092.smt2                                                                                   |25.24MiB|25.24MiB|0B| 0.0%|
|11.smt2                                                                                     |81.884MiB|81.884MiB|0B| 0.0%|
|1104.smt2                                                                                   |23.608MiB|23.608MiB|0B| 0.0%|
|1112.smt2                                                                                   |25.62MiB|25.62MiB|0B| 0.0%|
|1113.smt2                                                                                   |23.46MiB|23.46MiB|0B| 0.0%|
|1126.smt2                                                                                   |24.128MiB|24.128MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     |94.844MiB|94.844MiB|0B| 0.0%|
|04.smt2                                                                                     |77.26MiB|77.26MiB|0B| 0.0%|
|1.smt2                                                                                      |117.0MiB|117.0MiB|0B| 0.0%|
|1008.smt2                                                                                   |27.124MiB|27.124MiB|0B| 0.0%|
|1010.smt2                                                                                   |27.436MiB|27.436MiB|0B| 0.0%|
|1018.smt2                                                                                   |23.524MiB|23.524MiB|0B| 0.0%|
|1021.smt2                                                                                   |24.028MiB|24.028MiB|0B| 0.0%|
|1034.smt2                                                                                   |24.92MiB|24.92MiB|0B| 0.0%|
|1063.smt2                                                                                   |26.372MiB|26.372MiB|0B| 0.0%|
|107.smt2                                                                                    |22.272MiB|22.272MiB|0B| 0.0%|
|1082.smt2                                                                                   |27.476MiB|27.476MiB|0B| 0.0%|
|1085.smt2                                                                                   |80.12MiB|80.12MiB|0B| 0.0%|
|1089.smt2                                                                                   |23.104MiB|23.104MiB|0B| 0.0%|
|1090.smt2                                                                                   |23.276MiB|23.276MiB|0B| 0.0%|
|1092.smt2                                                                                   |25.24MiB|25.24MiB|0B| 0.0%|
|11.smt2                                                                                     |81.884MiB|81.884MiB|0B| 0.0%|
|1104.smt2                                                                                   |23.608MiB|23.608MiB|0B| 0.0%|
|1112.smt2                                                                                   |25.62MiB|25.62MiB|0B| 0.0%|
|1113.smt2                                                                                   |23.46MiB|23.46MiB|0B| 0.0%|
|1126.smt2                                                                                   |24.128MiB|24.128MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13800_terminationG_0.smt2               | 600.558s |13.518GiB|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   | 600.946s |6795.0MiB|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6638_safety_0.smt2                    | 527.610s |5407.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          | 600.653s |4856.0MiB|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4635_safety_0.smt2                          | 345.746s |4413.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                         | 600.558s |4143.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2              | 600.479s |2996.0MiB|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                             | 600.486s |2706.0MiB|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                              | 600.370s |2657.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         | 121.521s |2611.0MiB|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3037_safety_0.smt2         | 347.608s |2510.0MiB|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31433_safety_0.smt2              | 600.373s |2466.0MiB|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                       | 534.494s |2460.0MiB|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                   | 570.892s |2442.0MiB|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                               | 600.672s |2296.0MiB|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                               | 382.909s |2296.0MiB|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                       | 600.657s |2287.0MiB|
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2                                       | 572.931s |2206.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2                         | 566.723s |2182.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              | 600.454s |2072.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13800_terminationG_0.smt2               | 600.558s |13.518GiB|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                   | 600.946s |6795.0MiB|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6638_safety_0.smt2                    | 527.610s |5407.0MiB|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                          | 600.653s |4856.0MiB|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4635_safety_0.smt2                          | 345.746s |4413.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                         | 600.558s |4143.0MiB|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2              | 600.479s |2996.0MiB|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                             | 600.486s |2706.0MiB|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                              | 600.370s |2657.0MiB|
|From_T2__statemate.t2__term_unfeasibility_0_0.smt2                                         | 121.521s |2611.0MiB|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3037_safety_0.smt2         | 347.608s |2510.0MiB|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31433_safety_0.smt2              | 600.373s |2466.0MiB|
|From_T2__florian_sas2.t2__p32394_terminationG_0.smt2                                       | 534.494s |2460.0MiB|
|From_T2__apchild-accepted.t2__p16354_terminationG_0.smt2                                   | 570.892s |2442.0MiB|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                               | 600.672s |2296.0MiB|
|From_T2__rlft3.t2__p9077_terminationG_0.smt2                                               | 382.909s |2296.0MiB|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                       | 600.657s |2287.0MiB|
|From_T2__select.t2_fixed__p21326_terminationG_0.smt2                                       | 572.931s |2206.0MiB|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8786_terminationG_0.smt2                         | 566.723s |2182.0MiB|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                              | 600.454s |2072.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|02.smt2                                                                                     | 600.061s  | 600.061s  |   0.000s  | 0.0%|
|04.smt2                                                                                     | 600.090s  | 600.090s  |   0.000s  | 0.0%|
|1.smt2                                                                                      |   1.479s  |   1.479s  |   0.000s  | 0.0%|
|1008.smt2                                                                                   |   0.315s  |   0.315s  |   0.000s  | 0.0%|
|1010.smt2                                                                                   |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|1018.smt2                                                                                   |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|1021.smt2                                                                                   |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|1034.smt2                                                                                   |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|1063.smt2                                                                                   |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|107.smt2                                                                                    |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|1082.smt2                                                                                   |   0.345s  |   0.345s  |   0.000s  | 0.0%|
|1085.smt2                                                                                   |   1.069s  |   1.069s  |   0.000s  | 0.0%|
|1089.smt2                                                                                   |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|1090.smt2                                                                                   |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|1092.smt2                                                                                   |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|11.smt2                                                                                     | 600.096s  | 600.096s  |   0.000s  | 0.0%|
|1104.smt2                                                                                   |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|1112.smt2                                                                                   |   0.349s  |   0.349s  |   0.000s  | 0.0%|
|1113.smt2                                                                                   |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|1126.smt2                                                                                   |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|1132.smt2                                                                                   |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|1148.smt2                                                                                   |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|1152.smt2                                                                                   |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|1176.smt2                                                                                   |   0.518s  |   0.518s  |   0.000s  | 0.0%|
|1188.smt2                                                                                   |   0.289s  |   0.289s  |   0.000s  | 0.0%|
|1190.smt2                                                                                   |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|1192.smt2                                                                                   |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|1198.smt2                                                                                   |   0.493s  |   0.493s  |   0.000s  | 0.0%|
|1199.smt2                                                                                   |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|1221.smt2                                                                                   |   0.867s  |   0.867s  |   0.000s  | 0.0%|
|124.smt2                                                                                    | 600.110s  | 600.110s  |   0.000s  | 0.0%|
|1244.smt2                                                                                   |   0.720s  |   0.720s  |   0.000s  | 0.0%|
|1258.smt2                                                                                   |   0.338s  |   0.338s  |   0.000s  | 0.0%|
|1260.smt2                                                                                   |   0.728s  |   0.728s  |   0.000s  | 0.0%|
|1268.smt2                                                                                   |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|127.smt2                                                                                    |   1.392s  |   1.392s  |   0.000s  | 0.0%|
|1270.smt2                                                                                   |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|1283.smt2                                                                                   |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|1287.smt2                                                                                   |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|1296.smt2                                                                                   |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|1303.smt2                                                                                   |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|1304.smt2                                                                                   |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|1308.smt2                                                                                   |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|1324.smt2                                                                                   |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|1344.smt2                                                                                   |   0.329s  |   0.329s  |   0.000s  | 0.0%|
|1349.smt2                                                                                   |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|1354.smt2                                                                                   |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|1361.smt2                                                                                   |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|1367.smt2                                                                                   |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|1371.smt2                                                                                   |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|140.smt2                                                                                    | 600.084s  | 600.084s  |   0.000s  | 0.0%|
|1410.smt2                                                                                   |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|1422.smt2                                                                                   |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|1425.smt2                                                                                   |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|1430.smt2                                                                                   |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|1448.smt2                                                                                   |   0.479s  |   0.479s  |   0.000s  | 0.0%|
|1458.smt2                                                                                   |   0.525s  |   0.525s  |   0.000s  | 0.0%|
|1460.smt2                                                                                   |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|1468.smt2                                                                                   |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|1484.smt2                                                                                   |   1.349s  |   1.349s  |   0.000s  | 0.0%|
|1488.smt2                                                                                   |   1.875s  |   1.875s  |   0.000s  | 0.0%|
|149.smt2                                                                                    |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|1500.smt2                                                                                   |   0.325s  |   0.325s  |   0.000s  | 0.0%|
|1511.smt2                                                                                   |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|1514.smt2                                                                                   |   0.370s  |   0.370s  |   0.000s  | 0.0%|
|1516.smt2                                                                                   |   0.571s  |   0.571s  |   0.000s  | 0.0%|
|1520.smt2                                                                                   |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|1521.smt2                                                                                   |   0.268s  |   0.268s  |   0.000s  | 0.0%|
|1536.smt2                                                                                   |   0.509s  |   0.509s  |   0.000s  | 0.0%|
|1541.smt2                                                                                   |   0.453s  |   0.453s  |   0.000s  | 0.0%|
|1547.smt2                                                                                   |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|1555.smt2                                                                                   |   0.507s  |   0.507s  |   0.000s  | 0.0%|
|1557.smt2                                                                                   |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|1567.smt2                                                                                   |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|1574.smt2                                                                                   |   2.020s  |   2.020s  |   0.000s  | 0.0%|
|1582.smt2                                                                                   |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|1586.smt2                                                                                   |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|1594.smt2                                                                                   |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|1607.smt2                                                                                   |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|1631.smt2                                                                                   |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|1640.smt2                                                                                   |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|1644.smt2                                                                                   |   0.280s  |   0.280s  |   0.000s  | 0.0%|
|1648.smt2                                                                                   |   5.710s  |   5.710s  |   0.000s  | 0.0%|
|1649.smt2                                                                                   |   4.247s  |   4.247s  |   0.000s  | 0.0%|
|1662.smt2                                                                                   |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|1668.smt2                                                                                   |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|167.smt2                                                                                    |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|1677.smt2                                                                                   |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|1689.smt2                                                                                   |   1.608s  |   1.608s  |   0.000s  | 0.0%|
|1693.smt2                                                                                   |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|1728.smt2                                                                                   |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|1734.smt2                                                                                   |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|1741.smt2                                                                                   |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|1757.smt2                                                                                   |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|1767.smt2                                                                                   |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|1768.smt2                                                                                   |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|177.smt2                                                                                    | 659.907s  | 659.907s  |   0.000s  | 0.0%|
|1775.smt2                                                                                   |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|1776.smt2                                                                                   |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|1785.smt2                                                                                   |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|179.smt2                                                                                    |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|1794.smt2                                                                                   |   0.241s  |   0.241s  |   0.000s  | 0.0%|
|1805.smt2                                                                                   |   0.699s  |   0.699s  |   0.000s  | 0.0%|
|1809.smt2                                                                                   |   3.503s  |   3.503s  |   0.000s  | 0.0%|
|181.smt2                                                                                    | 600.185s  | 600.185s  |   0.000s  | 0.0%|
|182.smt2                                                                                    | 600.350s  | 600.350s  |   0.000s  | 0.0%|
|183.smt2                                                                                    | 600.258s  | 600.258s  |   0.000s  | 0.0%|
|185.smt2                                                                                    | 600.408s  | 600.408s  |   0.000s  | 0.0%|
|1850.smt2                                                                                   |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|1852.smt2                                                                                   |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|1858.smt2                                                                                   |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|187.smt2                                                                                    |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|1884.smt2                                                                                   |   0.639s  |   0.639s  |   0.000s  | 0.0%|
|1895.smt2                                                                                   |   2.033s  |   2.033s  |   0.000s  | 0.0%|
|1898.smt2                                                                                   |   2.441s  |   2.441s  |   0.000s  | 0.0%|
|1901.smt2                                                                                   |   1.536s  |   1.536s  |   0.000s  | 0.0%|
|1917.smt2                                                                                   |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|192.smt2                                                                                    |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|1924.smt2                                                                                   |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|1933.smt2                                                                                   |   2.425s  |   2.425s  |   0.000s  | 0.0%|
|1934.smt2                                                                                   |   3.184s  |   3.184s  |   0.000s  | 0.0%|
|199.smt2                                                                                    |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|20.smt2                                                                                     |   5.398s  |   5.398s  |   0.000s  | 0.0%|
|203.smt2                                                                                    |   6.290s  |   6.290s  |   0.000s  | 0.0%|
|211.smt2                                                                                    |   2.198s  |   2.198s  |   0.000s  | 0.0%|
|23.smt2                                                                                     |   2.661s  |   2.661s  |   0.000s  | 0.0%|
|250.smt2                                                                                    |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|257.smt2                                                                                    |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|264.smt2                                                                                    |   0.356s  |   0.356s  |   0.000s  | 0.0%|
|269.smt2                                                                                    |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|281.smt2                                                                                    |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|307.smt2                                                                                    |   2.231s  |   2.231s  |   0.000s  | 0.0%|
|310.smt2                                                                                    |   1.797s  |   1.797s  |   0.000s  | 0.0%|
|322.smt2                                                                                    |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|34.smt2                                                                                     |   1.218s  |   1.218s  |   0.000s  | 0.0%|
|35.smt2                                                                                     | 600.093s  | 600.093s  |   0.000s  | 0.0%|
|359.smt2                                                                                    |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|364.smt2                                                                                    |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|367.smt2                                                                                    |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|370.smt2                                                                                    |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|377.smt2                                                                                    |   0.232s  |   0.232s  |   0.000s  | 0.0%|
|40.smt2                                                                                     | 600.135s  | 600.135s  |   0.000s  | 0.0%|
|400.smt2                                                                                    |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|424.smt2                                                                                    |   3.393s  |   3.393s  |   0.000s  | 0.0%|
|443.smt2                                                                                    |   0.281s  |   0.281s  |   0.000s  | 0.0%|
|449.smt2                                                                                    |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|455.smt2                                                                                    |   0.451s  |   0.451s  |   0.000s  | 0.0%|
|460.smt2                                                                                    |   0.500s  |   0.500s  |   0.000s  | 0.0%|
|466.smt2                                                                                    |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|485.smt2                                                                                    |   0.951s  |   0.951s  |   0.000s  | 0.0%|
|496.smt2                                                                                    |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|498.smt2                                                                                    |   0.265s  |   0.265s  |   0.000s  | 0.0%|
|500.smt2                                                                                    |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|507.smt2                                                                                    |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|514.smt2                                                                                    |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|520.smt2                                                                                    |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|527.smt2                                                                                    |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|535.smt2                                                                                    |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|54.smt2                                                                                     | 600.110s  | 600.110s  |   0.000s  | 0.0%|
|544.smt2                                                                                    |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|551.smt2                                                                                    |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|572.smt2                                                                                    |   1.733s  |   1.733s  |   0.000s  | 0.0%|
|573.smt2                                                                                    |   2.466s  |   2.466s  |   0.000s  | 0.0%|
|574.smt2                                                                                    |   1.379s  |   1.379s  |   0.000s  | 0.0%|
|58.smt2                                                                                     | 600.135s  | 600.135s  |   0.000s  | 0.0%|
|583.smt2                                                                                    |   2.045s  |   2.045s  |   0.000s  | 0.0%|
|586.smt2                                                                                    |   2.098s  |   2.098s  |   0.000s  | 0.0%|
|599.smt2                                                                                    |   0.386s  |   0.386s  |   0.000s  | 0.0%|
|604.smt2                                                                                    |   4.535s  |   4.535s  |   0.000s  | 0.0%|
|624.smt2                                                                                    |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|625.smt2                                                                                    |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|65.smt2                                                                                     | 602.232s  | 602.232s  |   0.000s  | 0.0%|
|652.smt2                                                                                    |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|673.smt2                                                                                    |   1.248s  |   1.248s  |   0.000s  | 0.0%|
|677.smt2                                                                                    |   0.447s  |   0.447s  |   0.000s  | 0.0%|
|701.smt2                                                                                    |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|706.smt2                                                                                    |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|707.smt2                                                                                    |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|709.smt2                                                                                    |   0.323s  |   0.323s  |   0.000s  | 0.0%|
|711.smt2                                                                                    |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|722.smt2                                                                                    |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|73.smt2                                                                                     | 600.086s  | 600.086s  |   0.000s  | 0.0%|
|732.smt2                                                                                    |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|74.smt2                                                                                     |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|75.smt2                                                                                     |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|750.smt2                                                                                    |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|781.smt2                                                                                    |   0.400s  |   0.400s  |   0.000s  | 0.0%|
|788.smt2                                                                                    |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|798.smt2                                                                                    |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|808.smt2                                                                                    |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|821.smt2                                                                                    |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|824.smt2                                                                                    |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|828.smt2                                                                                    |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|83.smt2                                                                                     |   3.499s  |   3.499s  |   0.000s  | 0.0%|
|841.smt2                                                                                    |   0.285s  |   0.285s  |   0.000s  | 0.0%|
|843.smt2                                                                                    |   0.398s  |   0.398s  |   0.000s  | 0.0%|
|849.smt2                                                                                    |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|866.smt2                                                                                    |   1.123s  |   1.123s  |   0.000s  | 0.0%|
|888.smt2                                                                                    |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|891.smt2                                                                                    |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|909.smt2                                                                                    |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|93.smt2                                                                                     |   4.393s  |   4.393s  |   0.000s  | 0.0%|
|940.smt2                                                                                    |   0.288s  |   0.288s  |   0.000s  | 0.0%|
|946.smt2                                                                                    |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|947.smt2                                                                                    |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|966.smt2                                                                                    | 600.239s  | 600.239s  |   0.000s  | 0.0%|
|98.smt2                                                                                     | 600.056s  | 600.056s  |   0.000s  | 0.0%|
|989.smt2                                                                                    |   0.431s  |   0.431s  |   0.000s  | 0.0%|
|99.smt2                                                                                     | 600.068s  | 600.068s  |   0.000s  | 0.0%|
|995.smt2                                                                                    |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex2.06_false-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  | 144.401s  | 144.401s  |   0.000s  | 0.0%|
|ChenFlurMukhopadhyay-SAS2012-Ex3.10_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2  |   0.471s  |   0.471s  |   0.000s  | 0.0%|
|From_AProVE_2014__AProVE12-cyclic-Visit.jar-obl-9__p27675_terminationG_0.smt2               |   8.869s  |   8.869s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__p27480_terminationG_0.smt2                          | 600.288s  | 600.288s  |   0.000s  | 0.0%|
|From_AProVE_2014__Alternate.jar-obl-10__terminationS_8_0.smt2                               |   6.013s  |   6.013s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduce2.jar-obl-9__terminationS_1_0.smt2                   |   0.979s  |   0.979s  |   0.000s  | 0.0%|
|From_AProVE_2014__AlternatingGrowReduceRec2.jar-obl-9__term_unfeasibility_1_0.smt2          |   0.452s  |   0.452s  |   0.000s  | 0.0%|
|From_AProVE_2014__BMOG_CAV_12_MarkingGraphVisitor.jar-obl-11__p27764_terminationG_0.smt2    | 600.082s  | 600.082s  |   0.000s  | 0.0%|
|From_AProVE_2014__Choose.jar-obl-8__p27802_terminationG_0.smt2                              |   0.638s  |   0.638s  |   0.000s  | 0.0%|
|From_AProVE_2014__ChooseLife.jar-obl-8__p27825_terminationG_0.smt2                          |  25.734s  |  25.734s  |   0.000s  | 0.0%|
|From_AProVE_2014__Convert.jar-obl-9__p27975_edge_closing_0.smt2                             |   3.208s  |   3.208s  |   0.000s  | 0.0%|
|From_AProVE_2014__ConvertRec.jar-obl-9__p28041_edge_closing_0.smt2                          |   2.289s  |   2.289s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__p28122_terminationG_0.smt2                            | 600.403s  | 600.403s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10-2__terminationS_9_0.smt2                                 |   5.397s  |   5.397s  |   0.000s  | 0.0%|
|From_AProVE_2014__Count.jar-obl-10__p28177_edge_closing_0.smt2                              |   2.808s  |   2.808s  |   0.000s  | 0.0%|
|From_AProVE_2014__CountMetaList.jar-obl-9__p28209_edge_closing_0.smt2                       |  17.881s  |  17.881s  |   0.000s  | 0.0%|
|From_AProVE_2014__CyclicalListDuplicate.jar-obl-9__p28410_terminationG_0.smt2               |   4.964s  |   4.964s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__p28453_terminationG_0.smt2                          |  59.213s  |  59.213s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_12_0.smt2                              |   3.700s  |   3.700s  |   0.000s  | 0.0%|
|From_AProVE_2014__Distances.jar-obl-19__terminationS_4_0.smt2                               |   9.217s  |   9.217s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28485_terminationG_0.smt2                           |   9.217s  |   9.217s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28519_terminationG_0.smt2                           |   1.678s  |   1.678s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28547_terminationG_0.smt2                           | 600.188s  | 600.188s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivMinus.jar-obl-11__p28566_edge_closing_0.smt2                           |  72.542s  |  72.542s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__p28667_terminationG_0.smt2                         | 207.472s  | 207.472s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_14_0.smt2                             |   4.048s  |   4.048s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary.jar-obl-10__terminationS_23_0.smt2                             |  17.528s  |  17.528s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28622_terminationG_0.smt2                         |   3.464s  |   3.464s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28634_edge_closing_0.smt2                         |  10.158s  |  10.158s  |   0.000s  | 0.0%|
|From_AProVE_2014__DivTernary2.jar-obl-9__p28644_edge_closing_0.smt2                         |  31.765s  |  31.765s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__p28689_terminationG_0.smt2                             | 600.298s  | 600.298s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_10_0.smt2                                 |   9.613s  |   9.613s  |   0.000s  | 0.0%|
|From_AProVE_2014__Domino.jar-obl-27__terminationS_4_0.smt2                                  |  10.574s  |  10.574s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et1-rec.jar-obl-8__p28758_terminationG_0.smt2                             | 600.087s  | 600.087s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3-rec.jar-obl-8__p28848_terminationG_0.smt2                             |   0.468s  |   0.468s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et3.jar-obl-9__p28807_terminationG_0.smt2                                 | 600.146s  | 600.146s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4-rec.jar-obl-8__p28955_terminationG_0.smt2                             |   2.697s  |   2.697s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28888_terminationG_0.smt2                                 |   2.372s  |   2.372s  |   0.000s  | 0.0%|
|From_AProVE_2014__Et4.jar-obl-8__p28936_terminationG_0.smt2                                 |   7.978s  |   7.978s  |   0.000s  | 0.0%|
|From_AProVE_2014__EvenOdd.jar-obl-8__p29030_terminationG_0.smt2                             |   0.325s  |   0.325s  |   0.000s  | 0.0%|
|From_AProVE_2014__Exc2.jar-obl-8__p29261_edge_closing_0.smt2                                |   1.079s  |   1.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__FibSLR.jar-obl-8__p29342_terminationG_0.smt2                              | 600.088s  | 600.088s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29372_safety_0.smt2                                  |   4.856s  |   4.856s  |   0.000s  | 0.0%|
|From_AProVE_2014__Flatten.jar-obl-10__p29393_safety_0.smt2                                  |   0.886s  |   0.886s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29425_safety_0.smt2                               |   6.875s  |   6.875s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29448_safety_0.smt2                               | 600.172s  | 600.172s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenRTA.jar-obl-10__p29475_terminationG_0.smt2                         | 600.158s  | 600.158s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTree.jar-obl-9__p29513_terminationG_0.smt2                         |   8.586s  |   8.586s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29555_safety_0.smt2                       |  40.251s  |  40.251s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29573_safety_0.smt2                       |  14.493s  |  14.493s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeListRec.jar-obl-10__p29595_terminationG_0.smt2                 | 600.115s  | 600.115s  |   0.000s  | 0.0%|
|From_AProVE_2014__FlattenTreeRec.jar-obl-9__p29631_edge_closing_0.smt2                      |   6.611s  |   6.611s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29751_terminationG_0.smt2                              |   1.706s  |   1.706s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29767_edge_closing_0.smt2                              |   3.246s  |   3.246s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__p29778_edge_closing_0.smt2                              | 600.229s  | 600.229s  |   0.000s  | 0.0%|
|From_AProVE_2014__Graph.jar-obl-17__terminationQ_2_0.smt2                                   |   2.698s  |   2.698s  |   0.000s  | 0.0%|
|From_AProVE_2014__Kernel93.jar-obl-9__p9885_terminationG_0.smt2                             |  13.911s  |  13.911s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9911_terminationG_0.smt2                          | 600.176s  | 600.176s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9927_safety_0.smt2                                |   1.321s  |   1.321s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__p9942_edge_closing_0.smt2                          |  26.239s  |  26.239s  |   0.000s  | 0.0%|
|From_AProVE_2014__KnapsackDP.jar-obl-11__terminationQ_4_0.smt2                              |  56.662s  |  56.662s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p10012_edge_closing_0.smt2                         |  95.892s  |  95.892s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeaves.jar-obl-10__p9986_terminationG_0.smt2                          |   2.774s  |   2.774s  |   0.000s  | 0.0%|
|From_AProVE_2014__LessLeavesRec.jar-obl-10__p10045_terminationG_0.smt2                      | 600.348s  | 600.348s  |   0.000s  | 0.0%|
|From_AProVE_2014__LinkedList.jar-obl-10__p10080_terminationG_0.smt2                         |  11.905s  |  11.905s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10189_terminationG_0.smt2                               |  10.778s  |  10.778s  |   0.000s  | 0.0%|
|From_AProVE_2014__List.jar-obl-12__p10211_edge_closing_0.smt2                               |   4.039s  |   4.039s  |   0.000s  | 0.0%|
|From_AProVE_2014__ListContent.jar-obl-9__p10107_terminationG_0.smt2                         | 600.102s  | 600.102s  |   0.000s  | 0.0%|
|From_AProVE_2014__LoopingNonterm.jar-obl-8__p10312_terminationG_0.smt2                      | 600.065s  | 600.065s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__p10718_edge_closing_0.smt2                               | 600.155s  | 600.155s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_13_0.smt2                                   |   7.708s  |   7.708s  |   0.000s  | 0.0%|
|From_AProVE_2014__Main.jar-obl-11__terminationS_27_0.smt2                                   |  14.814s  |  14.814s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10342_terminationG_0.smt2                           |  11.757s  |  11.757s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainCopy.jar-obl-10__p10364_edge_closing_0.smt2                           | 600.116s  | 600.116s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10430_safety_0.smt2                               | 600.071s  | 600.071s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10459_terminationG_0.smt2                         |   2.634s  |   2.634s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10491_safety_0.smt2                               |  17.063s  |  17.063s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainDelete.jar-obl-10__p10518_edge_closing_0.smt2                         |   4.308s  |   4.308s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10595_terminationG_0.smt2                           |   5.728s  |   5.728s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainFind.jar-obl-10__p10620_edge_closing_0.smt2                           |  13.518s  |  13.518s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainGet.jar-obl-10__p10683_edge_closing_0.smt2                            | 600.256s  | 600.256s  |   0.000s  | 0.0%|
|From_AProVE_2014__MainMove.jar-obl-11__p10751_edge_closing_0.smt2                           |  11.018s  |  11.018s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10783_safety_0.smt2                                   |   6.685s  |   6.685s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10797_safety_0.smt2                                   | 600.105s  | 600.105s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10817_safety_0.smt2                                   | 600.224s  | 600.224s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10831_terminationG_0.smt2                             | 600.348s  | 600.348s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__p10847_edge_closing_0.smt2                             |  16.595s  |  16.595s  |   0.000s  | 0.0%|
|From_AProVE_2014__Matrix.jar-obl-16__term_unfeasibility_4_0.smt2                            |   1.111s  |   1.111s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__p10900_terminationG_0.smt2                    | 600.264s  | 600.264s  |   0.000s  | 0.0%|
|From_AProVE_2014__MirrorBinTreeRec.jar-obl-9__terminationS_8_0.smt2                         |  12.301s  |  12.301s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__p11042_safety_0.smt2                        |   3.295s  |   3.295s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_12_0.smt2                      |  26.899s  |  26.899s  |   0.000s  | 0.0%|
|From_AProVE_2014__MysteriousProgram.jar-obl-12__terminationS_6_0.smt2                       |  31.164s  |  31.164s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11209_safety_0.smt2                                     | 600.117s  | 600.117s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_05.jar-obl-9__p11244_edge_closing_0.smt2                               | 603.674s  | 603.674s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11278_terminationG_0.smt2                               | 600.096s  | 600.096s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_10.jar-obl-8__p11301_terminationG_0.smt2                               |   5.557s  |   5.557s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11329_terminationG_0.smt2                               |   8.999s  |   8.999s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_11.jar-obl-8__p11345_terminationG_0.smt2                               |   2.922s  |   2.922s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11367_terminationG_0.smt2                               |   5.940s  |   5.940s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_12.jar-obl-8__p11383_terminationG_0.smt2                               | 600.216s  | 600.216s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11407_edge_closing_0.smt2                               |   0.992s  |   0.992s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__p11445_edge_closing_0.smt2                               |   3.488s  |   3.488s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_13.jar-obl-8__terminationQ_1_0.smt2                                    |   3.627s  |   3.627s  |   0.000s  | 0.0%|
|From_AProVE_2014__NO_23.jar-obl-8__p11498_terminationG_0.smt2                               |   4.153s  |   4.153s  |   0.000s  | 0.0%|
|From_AProVE_2014__NestedLoop.jar-obl-10__p11151_terminationG_0.smt2                         |   1.738s  |   1.738s  |   0.000s  | 0.0%|
|From_AProVE_2014__NonPeriodicNonterm2.jar-obl-8__terminationS_0_0.smt2                      |   7.332s  |   7.332s  |   0.000s  | 0.0%|
|From_AProVE_2014__Norm.jar-obl-9__p11588_terminationG_0.smt2                                | 600.387s  | 600.387s  |   0.000s  | 0.0%|
|From_AProVE_2014__PastaB11.jar-obl-8__terminationS_0_0.smt2                                 |   1.982s  |   1.982s  |   0.000s  | 0.0%|
|From_AProVE_2014__Power.jar-obl-10__p11792_terminationG_0.smt2                              | 128.272s  | 128.272s  |   0.000s  | 0.0%|
|From_AProVE_2014__Queen.jar-obl-10__p11807_terminationG_0.smt2                              |  20.201s  |  20.201s  |   0.000s  | 0.0%|
|From_AProVE_2014__RSA.jar-obl-17__p11920_terminationG_0.smt2                                |   1.723s  |   1.723s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11832_safety_0.smt2                               |   8.756s  |   8.756s  |   0.000s  | 0.0%|
|From_AProVE_2014__RandomHard.jar-obl-10__p11849_terminationG_0.smt2                         |  11.026s  |  11.026s  |   0.000s  | 0.0%|
|From_AProVE_2014__Round3.jar-obl-8__p11893_terminationG_0.smt2                              |  90.349s  |  90.349s  |   0.000s  | 0.0%|
|From_AProVE_2014__Samefringe.jar-obl-10__p11956_terminationG_0.smt2                         |   4.644s  |   4.644s  |   0.000s  | 0.0%|
|From_AProVE_2014__SharingPair.jar-obl-8__p12030_edge_closing_0.smt2                         |  18.956s  |  18.956s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12086_terminationG_0.smt2                          | 600.138s  | 600.138s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12110_terminationG_0.smt2                          | 600.179s  | 600.179s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12138_terminationG_0.smt2                          | 236.351s  | 236.351s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12162_terminationG_0.smt2                          |   7.297s  |   7.297s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12188_terminationG_0.smt2                          | 600.229s  | 600.229s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12217_terminationG_0.smt2                          | 600.179s  | 600.179s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__p12246_terminationG_0.smt2                          |  35.788s  |  35.788s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationQ_3_0.smt2                               |   2.220s  |   2.220s  |   0.000s  | 0.0%|
|From_AProVE_2014__SortCount.jar-obl-10__terminationS_4_0.smt2                               |   8.654s  |   8.654s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12467_terminationG_0.smt2                    |   3.971s  |   3.971s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__p12483_terminationG_0.smt2                    | 600.669s  | 600.669s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesIte.jar-obl-13__terminationS_12_0.smt2                        |   3.781s  |   3.781s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12559_terminationG_0.smt2                    |   3.248s  |   3.248s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__p12576_terminationG_0.smt2                    | 600.211s  | 600.211s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_11_0.smt2                        |   1.915s  |   1.915s  |   0.000s  | 0.0%|
|From_AProVE_2014__TaylorSeriesRec.jar-obl-13__terminationS_9_0.smt2                         |   2.309s  |   2.309s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test1.jar-obl-8__p12793_terminationG_0.smt2                               |  22.101s  |  22.101s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12672_terminationG_0.smt2                        |  13.223s  |  13.223s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12688_terminationG_0.smt2                        | 600.107s  | 600.107s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12705_edge_closing_0.smt2                        |  28.114s  |  28.114s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12728_edge_closing_0.smt2                        |  16.705s  |  16.705s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12748_edge_closing_0.smt2                        |   8.277s  |   8.277s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test13Loops.jar-obl-10__p12774_edge_closing_0.smt2                        |  90.384s  |  90.384s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test2.jar-obl-8__term_unfeasibility_0_0.smt2                              |   1.480s  |   1.480s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_10_0.smt2                                  |  65.817s  |  65.817s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_1_0.smt2                                   |  32.326s  |  32.326s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_29_0.smt2                                  |  66.316s  |  66.316s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_38_0.smt2                                  |  55.287s  |  55.287s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test4.jar-obl-10__terminationS_6_0.smt2                                   |  34.842s  |  34.842s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__p12864_terminationG_0.smt2                              |  14.083s  |  14.083s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__term_unfeasibility_4_0.smt2                             |  86.520s  |  86.520s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_16_0.smt2                                  | 171.210s  | 171.210s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_25_0.smt2                                  | 172.758s  | 172.758s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_34_0.smt2                                  |   6.138s  |   6.138s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test6.jar-obl-13__terminationS_43_0.smt2                                  |  49.598s  |  49.598s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12888_terminationG_0.smt2                              |   2.078s  |   2.078s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12919_safety_0.smt2                                    |   0.743s  |   0.743s  |   0.000s  | 0.0%|
|From_AProVE_2014__Test7.jar-obl-11__p12938_edge_closing_0.smt2                              | 600.087s  | 600.087s  |   0.000s  | 0.0%|
|From_AProVE_2014__TestJulia7.jar-obl-8__p12986_terminationG_0.smt2                          |   5.432s  |   5.432s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13025_terminationG_0.smt2                             |  67.118s  |  67.118s  |   0.000s  | 0.0%|
|From_AProVE_2014__TriTas.jar-obl-12__p13043_edge_closing_0.smt2                             |   7.935s  |   7.935s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDiv.jar-obl-8__p13204_edge_closing_0.smt2                |   2.633s  |   2.633s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13246_terminationG_0.smt2        |  11.416s  |  11.416s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternDivWidening.jar-obl-8__p13266_edge_closing_0.smt2        | 438.806s  | 438.806s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-alternatingIncr.jar-obl-8__p13182_terminationG_0.smt2          |   0.637s  |   0.637s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv.jar-obl-8__p13409_terminationG_0.smt2              |   2.386s  |   2.386s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complInterv3.jar-obl-8__p13363_terminationG_0.smt2             |   3.234s  |   3.234s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-complxStruc.jar-obl-8__terminationQ_0_0.smt2                   |   4.290s  |   4.290s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-convLower.jar-obl-8__p13465_terminationG_0.smt2                |   0.584s  |   0.584s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13488_terminationG_0.smt2                   | 601.864s  | 601.864s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-cousot.jar-obl-8__p13504_terminationG_0.smt2                   | 654.238s  | 654.238s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-even.jar-obl-9__p13541_terminationG_0.smt2                     |  29.396s  |  29.396s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex02.jar-obl-8__p13595_terminationG_0.smt2                     |   3.709s  |   3.709s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex04.jar-obl-8__p13648_terminationG_0.smt2                     |   4.028s  |   4.028s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex06.jar-obl-8__p13693_terminationG_0.smt2                     |   1.462s  |   1.462s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex08.jar-obl-8__p13746_terminationG_0.smt2                     | 600.207s  | 600.207s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-ex09half.jar-obl-8__p13773_terminationG_0.smt2                 | 600.073s  | 600.073s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13800_terminationG_0.smt2                | 600.558s  | 600.558s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13819_terminationG_0.smt2                |   1.498s  |   1.498s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-factorial.jar-obl-8__p13835_terminationG_0.smt2                |  33.587s  |  33.587s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13857_terminationG_0.smt2                      | 600.160s  | 600.160s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13879_terminationG_0.smt2                      |   2.408s  |   2.408s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13895_terminationG_0.smt2                      | 600.081s  | 600.081s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13911_terminationG_0.smt2                      | 600.119s  | 600.119s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13925_edge_closing_0.smt2                      |   7.300s  |   7.300s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-fib.jar-obl-8__p13936_edge_closing_0.smt2                      | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-flip2.jar-obl-8__p13963_edge_closing_0.smt2                    |   2.084s  |   2.084s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-gauss.jar-obl-8__p14028_terminationG_0.smt2                    |   0.769s  |   0.769s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14098_terminationG_0.smt2                     |   2.580s  |   2.580s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-lcm.jar-obl-10__p14129_edge_closing_0.smt2                     |   4.844s  |   4.844s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-marbie2.jar-obl-8__p14171_terminationG_0.smt2                  |   4.293s  |   4.293s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14201_terminationG_0.smt2                   |   6.752s  |   6.752s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14221_terminationG_0.smt2                   |   3.927s  |   3.927s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-middle.jar-obl-8__p14237_terminationG_0.smt2                   |   3.581s  |   3.581s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14264_terminationG_0.smt2             |   3.492s  |   3.492s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14280_terminationG_0.smt2             |   8.976s  |   8.976s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorInterv.jar-obl-8__p14299_edge_closing_0.smt2             |   5.890s  |   5.890s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-mirrorIntervSim.jar-obl-8__p14328_terminationG_0.smt2          | 600.107s  | 600.107s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowKonv.jar-obl-8__p14411_terminationG_0.smt2               | 600.215s  | 600.215s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-narrowing.jar-obl-8__p14385_terminationG_0.smt2                | 114.066s  | 114.066s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-plait.jar-obl-8__p14480_terminationG_0.smt2                    |   4.719s  |   4.719s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-sunset.jar-obl-8__p14515_edge_closing_0.smt2                   |   2.356s  |   2.356s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__p14597_terminationG_0.smt2                |   1.858s  |   1.858s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDown.jar-obl-8__terminationS_1_0.smt2                     |   1.813s  |   1.813s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-upAndDownIneq.jar-obl-8__terminationS_1_0.smt2                 |   1.225s  |   1.225s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileBreak.jar-obl-8__p14672_terminationG_0.smt2               |   4.796s  |   4.796s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileIncrPart.jar-obl-8__p14730_terminationG_0.smt2            |   0.591s  |   0.591s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNested.jar-obl-8__p14763_terminationG_0.smt2              | 600.100s  | 600.100s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileNestedOffset.jar-obl-8__p14810_edge_closing_0.smt2        |   2.982s  |   2.982s  |   0.000s  | 0.0%|
|From_AProVE_2014__Velroyen08-whileSum.jar-obl-8__p14857_terminationG_0.smt2                 |   5.613s  |   5.613s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternDivWidening_rec.jar-obl-8__p27568_terminationG_0.smt2               |   7.673s  |   7.673s  |   0.000s  | 0.0%|
|From_AProVE_2014__alternKonv_rec.jar-obl-8__p27639_edge_closing_0.smt2                      |   2.338s  |   2.338s  |   0.000s  | 0.0%|
|From_AProVE_2014__complxStruc_rec.jar-obl-8__terminationS_0_0.smt2                          |  17.951s  |  17.951s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28249_terminationG_0.smt2                          | 600.678s  | 600.678s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28267_terminationG_0.smt2                          |   4.708s  |   4.708s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28283_terminationG_0.smt2                          | 600.305s  | 600.305s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28299_terminationG_0.smt2                          | 600.398s  | 600.398s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28317_terminationG_0.smt2                          |  11.686s  |  11.686s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28333_terminationG_0.smt2                          | 600.213s  | 600.213s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28349_terminationG_0.smt2                          | 600.306s  | 600.306s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28367_terminationG_0.smt2                          |  12.833s  |  12.833s  |   0.000s  | 0.0%|
|From_AProVE_2014__cousot_rec.jar-obl-8__p28383_terminationG_0.smt2                          | 600.168s  | 600.168s  |   0.000s  | 0.0%|
|From_AProVE_2014__even_rec.jar-obl-8__p29058_terminationG_0.smt2                            |   0.667s  |   0.667s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex01_rec.jar-obl-8__p29091_terminationG_0.smt2                            |   5.871s  |   5.871s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29168_terminationG_0.smt2                            | 600.142s  | 600.142s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex04_rec.jar-obl-8__p29187_terminationG_0.smt2                            |   5.351s  |   5.351s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__p29227_terminationG_0.smt2                            |   8.901s  |   8.901s  |   0.000s  | 0.0%|
|From_AProVE_2014__ex08_rec.jar-obl-8__terminationS_4_0.smt2                                 |   3.821s  |   3.821s  |   0.000s  | 0.0%|
|From_AProVE_2014__flip_rec.jar-obl-8__p29677_terminationG_0.smt2                            | 600.086s  | 600.086s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4408_safety_0.smt2                           |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4423_safety_0.smt2                           |  53.806s  |  53.806s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4452_safety_0.smt2                           |   5.572s  |   5.572s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4467_safety_0.smt2                           |   0.387s  |   0.387s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4490_safety_0.smt2                           |   2.951s  |   2.951s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4509_safety_0.smt2                           |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4524_safety_0.smt2                           |   7.174s  |   7.174s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4544_terminationG_0.smt2                     |  33.769s  |  33.769s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4576_safety_0.smt2                           |   0.708s  |   0.708s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4595_safety_0.smt2                           |   2.894s  |   2.894s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4616_safety_0.smt2                           |   9.901s  |   9.901s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4657_safety_0.smt2                           | 600.253s  | 600.253s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4675_safety_0.smt2                           |  12.430s  |  12.430s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4694_safety_0.smt2                           |   2.492s  |   2.492s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4727_safety_0.smt2                           |  10.351s  |  10.351s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4746_safety_0.smt2                           | 606.850s  | 606.850s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4770_safety_0.smt2                           |   2.832s  |   2.832s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4783_safety_0.smt2                           |   0.889s  |   0.889s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4800_safety_0.smt2                           | 600.031s  | 600.031s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4816_safety_0.smt2                           |  11.532s  |  11.532s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4834_safety_0.smt2                           |   0.246s  |   0.246s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4855_safety_0.smt2                           | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4889_safety_0.smt2                           |   1.999s  |   1.999s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4901_safety_0.smt2                           |  21.432s  |  21.432s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4929_safety_0.smt2                           | 600.036s  | 600.036s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4946_safety_0.smt2                           | 123.372s  | 123.372s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4962_safety_0.smt2                           |   7.765s  |   7.765s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p4979_safety_0.smt2                           |   3.789s  |   3.789s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5002_safety_0.smt2                           | 607.217s  | 607.217s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5023_safety_0.smt2                           | 600.087s  | 600.087s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5045_safety_0.smt2                           |  21.665s  |  21.665s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5068_safety_0.smt2                           |   2.514s  |   2.514s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5085_safety_0.smt2                           |  11.076s  |  11.076s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5099_safety_0.smt2                           |   1.602s  |   1.602s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5117_safety_0.smt2                           |  84.999s  |  84.999s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5140_safety_0.smt2                           |   0.539s  |   0.539s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5160_safety_0.smt2                           |   5.480s  |   5.480s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5177_safety_0.smt2                           |   1.590s  |   1.590s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5200_safety_0.smt2                           |  14.724s  |  14.724s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5220_safety_0.smt2                           |   8.792s  |   8.792s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5245_safety_0.smt2                           |   2.243s  |   2.243s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5263_safety_0.smt2                           |  12.987s  |  12.987s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5284_safety_0.smt2                           |   0.321s  |   0.321s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5299_safety_0.smt2                           | 600.071s  | 600.071s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5318_safety_0.smt2                           |  16.721s  |  16.721s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5336_safety_0.smt2                           |   2.140s  |   2.140s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5362_safety_0.smt2                           |   2.313s  |   2.313s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5380_safety_0.smt2                           | 600.043s  | 600.043s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreate.jar-obl-10__p5394_edge_closing_0.smt2                     | 606.797s  | 606.797s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29854_safety_0.smt2                     |   0.347s  |   0.347s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29877_safety_0.smt2                     |   1.080s  |   1.080s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29899_safety_0.smt2                     |  27.040s  |  27.040s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29923_safety_0.smt2                     |   0.561s  |   0.561s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29941_safety_0.smt2                     | 600.073s  | 600.073s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29960_safety_0.smt2                     | 600.081s  | 600.081s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p29982_safety_0.smt2                     |   2.052s  |   2.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30020_safety_0.smt2                     | 600.106s  | 600.106s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30040_safety_0.smt2                     | 600.073s  | 600.073s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30071_safety_0.smt2                     |   5.934s  |   5.934s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30088_safety_0.smt2                     |   0.344s  |   0.344s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30114_safety_0.smt2                     |  10.044s  |  10.044s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30132_safety_0.smt2                     | 100.425s  | 100.425s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30154_safety_0.smt2                     | 600.122s  | 600.122s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30178_terminationG_0.smt2               |   6.884s  |   6.884s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30215_safety_0.smt2                     |   0.721s  |   0.721s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30234_safety_0.smt2                     |  19.472s  |  19.472s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30251_safety_0.smt2                     |   1.113s  |   1.113s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30268_safety_0.smt2                     |   1.383s  |   1.383s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30285_safety_0.smt2                     |   0.655s  |   0.655s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30308_safety_0.smt2                     |   1.116s  |   1.116s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30328_safety_0.smt2                     |   0.642s  |   0.642s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30359_safety_0.smt2                     |  16.704s  |  16.704s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30379_safety_0.smt2                     | 600.044s  | 600.044s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30401_safety_0.smt2                     |  45.736s  |  45.736s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30418_safety_0.smt2                     |   0.937s  |   0.937s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30433_safety_0.smt2                     |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30454_safety_0.smt2                     |   0.774s  |   0.774s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30477_safety_0.smt2                     |   0.345s  |   0.345s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30491_terminationG_0.smt2               | 600.347s  | 600.347s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30522_safety_0.smt2                     |  69.570s  |  69.570s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30536_safety_0.smt2                     |   3.305s  |   3.305s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30565_safety_0.smt2                     |   2.219s  |   2.219s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30588_safety_0.smt2                     | 600.075s  | 600.075s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30611_safety_0.smt2                     |   7.918s  |   7.918s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30625_safety_0.smt2                     |   2.190s  |   2.190s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30649_safety_0.smt2                     |   6.620s  |   6.620s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30674_safety_0.smt2                     |   0.595s  |   0.595s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30699_safety_0.smt2                     |   1.488s  |   1.488s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30713_safety_0.smt2                     |  11.199s  |  11.199s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30742_safety_0.smt2                     |  11.886s  |  11.886s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30762_safety_0.smt2                     |   0.310s  |   0.310s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30786_safety_0.smt2                     | 600.057s  | 600.057s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30804_safety_0.smt2                     |   6.840s  |   6.840s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__p30820_safety_0.smt2                     | 600.075s  | 600.075s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateClear.jar-obl-11__terminationQ_0_0.smt2                    |  11.683s  |  11.683s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30861_safety_0.smt2               | 600.056s  | 600.056s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30879_safety_0.smt2               | 600.106s  | 600.106s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30895_safety_0.smt2               |   1.824s  |   1.824s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30915_safety_0.smt2               |   1.416s  |   1.416s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30935_safety_0.smt2               |   1.958s  |   1.958s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30951_safety_0.smt2               | 600.052s  | 600.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30967_safety_0.smt2               |   2.233s  |   2.233s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p30993_safety_0.smt2               | 600.073s  | 600.073s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31023_safety_0.smt2               |   4.093s  |   4.093s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31041_safety_0.smt2               |   2.098s  |   2.098s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31062_safety_0.smt2               |   0.556s  |   0.556s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31079_safety_0.smt2               |   9.109s  |   9.109s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31103_safety_0.smt2               | 600.088s  | 600.088s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31120_safety_0.smt2               | 602.338s  | 602.338s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31139_safety_0.smt2               | 600.270s  | 600.270s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31162_safety_0.smt2               | 600.248s  | 600.248s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31198_safety_0.smt2               |   7.075s  |   7.075s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31214_safety_0.smt2               |   2.192s  |   2.192s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31238_safety_0.smt2               |   1.743s  |   1.743s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31260_safety_0.smt2               |   2.385s  |   2.385s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31280_safety_0.smt2               |  27.965s  |  27.965s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31302_safety_0.smt2               |   6.764s  |   6.764s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31318_safety_0.smt2               |   1.636s  |   1.636s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31339_safety_0.smt2               | 606.179s  | 606.179s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31371_safety_0.smt2               |   6.420s  |   6.420s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31389_safety_0.smt2               |   1.029s  |   1.029s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31417_safety_0.smt2               |   6.320s  |   6.320s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31433_safety_0.smt2               | 600.373s  | 600.373s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31458_safety_0.smt2               |   5.195s  |   5.195s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31475_safety_0.smt2               |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31502_safety_0.smt2               |   1.610s  |   1.610s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31530_safety_0.smt2               |   5.789s  |   5.789s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31555_safety_0.smt2               |   0.840s  |   0.840s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31568_safety_0.smt2               |   2.392s  |   2.392s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31599_safety_0.smt2               | 600.163s  | 600.163s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31615_safety_0.smt2               |   0.409s  |   0.409s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31631_safety_0.smt2               |   1.462s  |   1.462s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31649_safety_0.smt2               |   4.101s  |   4.101s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31678_safety_0.smt2               | 600.052s  | 600.052s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31705_safety_0.smt2               |   8.699s  |   8.699s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31726_safety_0.smt2               | 600.190s  | 600.190s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31747_safety_0.smt2               | 600.269s  | 600.269s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31764_safety_0.smt2               |   2.914s  |   2.914s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31792_safety_0.smt2               |   4.186s  |   4.186s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31816_safety_0.smt2               |   1.590s  |   1.590s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__p31837_safety_0.smt2               |  38.481s  |  38.481s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsKey.jar-obl-11__terminationS_2_0.smt2              |   4.429s  |   4.429s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31858_terminationG_0.smt2       |  45.938s  |  45.938s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31890_safety_0.smt2             |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31906_safety_0.smt2             |   0.387s  |   0.387s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31933_safety_0.smt2             |  16.019s  |  16.019s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31946_safety_0.smt2             |   1.017s  |   1.017s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31977_safety_0.smt2             | 608.092s  | 608.092s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p31987_safety_0.smt2             | 121.215s  | 121.215s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32011_safety_0.smt2             |   1.290s  |   1.290s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32037_safety_0.smt2             |   0.994s  |   0.994s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32061_safety_0.smt2             |   1.294s  |   1.294s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32079_safety_0.smt2             |   2.253s  |   2.253s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32102_safety_0.smt2             |   1.938s  |   1.938s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32114_safety_0.smt2             |   0.776s  |   0.776s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32139_safety_0.smt2             | 600.037s  | 600.037s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32157_safety_0.smt2             |   7.200s  |   7.200s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32174_safety_0.smt2             |   0.818s  |   0.818s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32196_safety_0.smt2             | 600.099s  | 600.099s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32231_safety_0.smt2             |   2.184s  |   2.184s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32246_safety_0.smt2             | 600.093s  | 600.093s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32268_safety_0.smt2             |   0.474s  |   0.474s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32285_safety_0.smt2             |   0.401s  |   0.401s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32305_safety_0.smt2             |   2.326s  |   2.326s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32319_safety_0.smt2             | 600.131s  | 600.131s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32340_safety_0.smt2             |   2.301s  |   2.301s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32365_safety_0.smt2             | 600.247s  | 600.247s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32397_safety_0.smt2             | 600.135s  | 600.135s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32413_safety_0.smt2             |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32438_safety_0.smt2             |   2.715s  |   2.715s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32455_safety_0.smt2             |   2.239s  |   2.239s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32475_safety_0.smt2             | 102.284s  | 102.284s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32488_safety_0.smt2             |   0.437s  |   0.437s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32511_safety_0.smt2             |  13.764s  |  13.764s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32526_safety_0.smt2             |   1.212s  |   1.212s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32548_safety_0.smt2             | 600.142s  | 600.142s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32579_safety_0.smt2             |   0.727s  |   0.727s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32596_safety_0.smt2             |   0.285s  |   0.285s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32619_safety_0.smt2             |   2.622s  |   2.622s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32635_safety_0.smt2             | 600.240s  | 600.240s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32658_safety_0.smt2             |   8.614s  |   8.614s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32674_safety_0.smt2             | 601.474s  | 601.474s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32695_safety_0.smt2             |   1.668s  |   1.668s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32715_safety_0.smt2             | 600.146s  | 600.146s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32746_safety_0.smt2             |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p32763_safety_0.smt2             | 600.103s  | 600.103s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p334_safety_0.smt2               |   4.270s  |   4.270s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p359_safety_0.smt2               |  55.599s  |  55.599s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p374_safety_0.smt2               |   6.718s  |   6.718s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p396_safety_0.smt2               |   1.028s  |   1.028s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p423_safety_0.smt2               |   0.801s  |   0.801s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateContainsValue.jar-obl-11__p440_terminationG_0.smt2         | 178.493s  | 178.493s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateGet.jar-obl-11__p1105_safety_0.smt2                        |   0.650s  |   0.650s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1543_terminationG_0.smt2              |   2.344s  |   2.344s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1578_safety_0.smt2                    |   1.301s  |   1.301s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1596_safety_0.smt2                    |   2.315s  |   2.315s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1624_safety_0.smt2                    |   5.673s  |   5.673s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1650_safety_0.smt2                    |   0.631s  |   0.631s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1666_safety_0.smt2                    | 600.048s  | 600.048s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1696_safety_0.smt2                    |  59.697s  |  59.697s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1718_terminationG_0.smt2              |  16.749s  |  16.749s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1749_safety_0.smt2                    |   0.779s  |   0.779s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1762_safety_0.smt2                    |  27.427s  |  27.427s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1794_safety_0.smt2                    |   1.115s  |   1.115s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1808_safety_0.smt2                    |  15.145s  |  15.145s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1881_safety_0.smt2                    | 600.053s  | 600.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1904_safety_0.smt2                    |   2.350s  |   2.350s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1939_safety_0.smt2                    |   2.171s  |   2.171s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p1989_safety_0.smt2                    |   1.493s  |   1.493s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2019_safety_0.smt2                    |   1.074s  |   1.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2047_safety_0.smt2                    |   2.173s  |   2.173s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2106_safety_0.smt2                    | 600.073s  | 600.073s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2138_safety_0.smt2                    | 600.074s  | 600.074s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2164_safety_0.smt2                    |   2.115s  |   2.115s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2200_safety_0.smt2                    |   1.823s  |   1.823s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2229_safety_0.smt2                    |   1.648s  |   1.648s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2274_safety_0.smt2                    |   5.319s  |   5.319s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2292_safety_0.smt2                    |   6.185s  |   6.185s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2318_safety_0.smt2                    | 600.091s  | 600.091s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2336_safety_0.smt2                    |   1.983s  |   1.983s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2398_safety_0.smt2                    | 600.103s  | 600.103s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2424_safety_0.smt2                    |   1.351s  |   1.351s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2442_safety_0.smt2                    |  22.339s  |  22.339s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2469_terminationG_0.smt2              | 104.794s  | 104.794s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2501_safety_0.smt2                    | 600.072s  | 600.072s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2529_safety_0.smt2                    |   0.682s  |   0.682s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2547_safety_0.smt2                    |   2.070s  |   2.070s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2565_safety_0.smt2                    | 600.335s  | 600.335s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2587_safety_0.smt2                    |  23.323s  |  23.323s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2610_safety_0.smt2                    |   2.428s  |   2.428s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2624_safety_0.smt2                    |   2.169s  |   2.169s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2650_safety_0.smt2                    |   1.330s  |   1.330s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2674_safety_0.smt2                    | 615.283s  | 615.283s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2694_safety_0.smt2                    |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2710_safety_0.smt2                    | 236.034s  | 236.034s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2744_safety_0.smt2                    |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2769_safety_0.smt2                    |   0.809s  |   0.809s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2794_safety_0.smt2                    |   1.287s  |   1.287s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2813_safety_0.smt2                    | 600.115s  | 600.115s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2836_safety_0.smt2                    |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__p2859_safety_0.smt2                    |   1.054s  |   1.054s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIsEmpty.jar-obl-10__terminationS_1_0.smt2                  |  20.896s  |  20.896s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2903_safety_0.smt2          |   0.639s  |   0.639s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2923_safety_0.smt2          | 600.205s  | 600.205s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2952_safety_0.smt2          |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2974_safety_0.smt2          |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p2999_safety_0.smt2          | 600.088s  | 600.088s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3015_safety_0.smt2          |   2.614s  |   2.614s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3067_safety_0.smt2          |   5.967s  |   5.967s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3088_safety_0.smt2          | 600.327s  | 600.327s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3111_safety_0.smt2          |   0.754s  |   0.754s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3125_safety_0.smt2          | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3144_safety_0.smt2          |   2.076s  |   2.076s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3156_safety_0.smt2          | 600.218s  | 600.218s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3177_safety_0.smt2          |   0.584s  |   0.584s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3204_safety_0.smt2          |  17.941s  |  17.941s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3228_safety_0.smt2          |   1.705s  |   1.705s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3247_safety_0.smt2          |   1.488s  |   1.488s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3276_safety_0.smt2          | 600.067s  | 600.067s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3295_safety_0.smt2          | 600.091s  | 600.091s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3316_safety_0.smt2          |   0.382s  |   0.382s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3339_safety_0.smt2          |   0.817s  |   0.817s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__p3355_safety_0.smt2          | 600.075s  | 600.075s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorEntryLoop.jar-obl-12__terminationS_1_0.smt2        |   6.715s  |   6.715s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateIteratorKeyLoop.jar-obl-12__p3705_safety_0.smt2            |   1.585s  |   1.585s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5427_safety_0.smt2                        |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5452_safety_0.smt2                        | 600.120s  | 600.120s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5483_safety_0.smt2                        |   8.230s  |   8.230s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5509_safety_0.smt2                        |   2.161s  |   2.161s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5528_safety_0.smt2                        | 600.051s  | 600.051s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5552_safety_0.smt2                        |  30.924s  |  30.924s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5566_safety_0.smt2                        |   2.193s  |   2.193s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5586_terminationG_0.smt2                  |   2.342s  |   2.342s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5625_safety_0.smt2                        |   9.947s  |   9.947s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5640_safety_0.smt2                        |   2.251s  |   2.251s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5665_safety_0.smt2                        |   0.854s  |   0.854s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5675_safety_0.smt2                        |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5710_safety_0.smt2                        |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5725_safety_0.smt2                        |   0.423s  |   0.423s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5754_safety_0.smt2                        |  10.107s  |  10.107s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5790_safety_0.smt2                        |  27.203s  |  27.203s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5807_safety_0.smt2                        |   0.303s  |   0.303s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5840_safety_0.smt2                        |   6.119s  |   6.119s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5857_safety_0.smt2                        |   1.012s  |   1.012s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5884_safety_0.smt2                        |   0.976s  |   0.976s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5896_safety_0.smt2                        |   8.708s  |   8.708s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5922_safety_0.smt2                        |   1.104s  |   1.104s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5945_safety_0.smt2                        |  15.347s  |  15.347s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p5984_safety_0.smt2                        |   0.551s  |   0.551s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6000_safety_0.smt2                        |   9.493s  |   9.493s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6028_safety_0.smt2                        |   2.756s  |   2.756s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6048_safety_0.smt2                        | 600.182s  | 600.182s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6071_safety_0.smt2                        |   2.340s  |   2.340s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6085_safety_0.smt2                        |   1.114s  |   1.114s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6102_safety_0.smt2                        |   1.994s  |   1.994s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6125_safety_0.smt2                        |  25.377s  |  25.377s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6161_safety_0.smt2                        |   0.711s  |   0.711s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6179_safety_0.smt2                        |   9.857s  |   9.857s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6207_safety_0.smt2                        |   2.682s  |   2.682s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6223_safety_0.smt2                        |   2.241s  |   2.241s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6247_safety_0.smt2                        | 600.063s  | 600.063s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6269_safety_0.smt2                        | 600.114s  | 600.114s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6290_safety_0.smt2                        |  15.730s  |  15.730s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6313_safety_0.smt2                        |   1.356s  |   1.356s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6345_safety_0.smt2                        |   7.472s  |   7.472s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6363_safety_0.smt2                        |  20.464s  |  20.464s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6393_safety_0.smt2                        | 600.115s  | 600.115s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6414_safety_0.smt2                        | 600.068s  | 600.068s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6433_safety_0.smt2                        |   0.554s  |   0.554s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6451_safety_0.smt2                        |   2.185s  |   2.185s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6477_safety_0.smt2                        |  14.728s  |  14.728s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreatePut.jar-obl-10__p6498_terminationG_0.smt2                  | 600.550s  | 600.550s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6519_terminationG_0.smt2               |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6579_safety_0.smt2                     |   2.317s  |   2.317s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6603_safety_0.smt2                     |   2.187s  |   2.187s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6620_safety_0.smt2                     |   5.944s  |   5.944s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6656_safety_0.smt2                     | 600.086s  | 600.086s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6722_safety_0.smt2                     |   0.945s  |   0.945s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6750_safety_0.smt2                     |   8.842s  |   8.842s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6767_safety_0.smt2                     |   0.423s  |   0.423s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6792_safety_0.smt2                     |  14.508s  |  14.508s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6811_safety_0.smt2                     |  86.120s  |  86.120s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6833_safety_0.smt2                     |   2.243s  |   2.243s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6858_terminationG_0.smt2               |  10.876s  |  10.876s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6918_safety_0.smt2                     |   1.158s  |   1.158s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6933_safety_0.smt2                     |   1.526s  |   1.526s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6950_safety_0.smt2                     |   2.278s  |   2.278s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6967_safety_0.smt2                     | 600.308s  | 600.308s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p6990_safety_0.smt2                     |   2.163s  |   2.163s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__p7011_safety_0.smt2                     |   1.628s  |   1.628s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateRemove.jar-obl-11__terminationS_0_0.smt2                   |   3.022s  |   3.022s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7055_safety_0.smt2                       |   0.759s  |   0.759s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7074_safety_0.smt2                       | 600.060s  | 600.060s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7104_safety_0.smt2                       |   1.855s  |   1.855s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7124_safety_0.smt2                       |  40.933s  |  40.933s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7143_safety_0.smt2                       |   1.329s  |   1.329s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7163_safety_0.smt2                       |  51.984s  |  51.984s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7184_safety_0.smt2                       | 600.053s  | 600.053s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7205_safety_0.smt2                       | 600.207s  | 600.207s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7234_safety_0.smt2                       |   1.283s  |   1.283s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7255_safety_0.smt2                       |  13.544s  |  13.544s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7280_safety_0.smt2                       | 600.092s  | 600.092s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7295_safety_0.smt2                       |   2.369s  |   2.369s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7312_safety_0.smt2                       |   1.244s  |   1.244s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7334_safety_0.smt2                       |   2.225s  |   2.225s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7359_safety_0.smt2                       |   5.266s  |   5.266s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7378_safety_0.smt2                       | 600.121s  | 600.121s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7407_safety_0.smt2                       |   8.018s  |   8.018s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7426_safety_0.smt2                       | 600.078s  | 600.078s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7445_terminationG_0.smt2                 |  21.664s  |  21.664s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7477_safety_0.smt2                       |   0.706s  |   0.706s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7493_safety_0.smt2                       |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7512_safety_0.smt2                       |   0.461s  |   0.461s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7535_safety_0.smt2                       |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7555_safety_0.smt2                       | 600.121s  | 600.121s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7576_safety_0.smt2                       | 600.105s  | 600.105s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7593_safety_0.smt2                       |  26.552s  |  26.552s  |   0.000s  | 0.0%|
|From_AProVE_2014__juHashMapCreateSize.jar-obl-10__p7615_edge_closing_0.smt2                 | 600.412s  | 600.412s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9355_terminationG_0.smt2            |  81.293s  |  81.293s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9373_terminationG_0.smt2            |   3.761s  |   3.761s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9392_safety_0.smt2                  |  27.031s  |  27.031s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9409_safety_0.smt2                  |   2.656s  |   2.656s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9426_safety_0.smt2                  |  13.462s  |  13.462s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9447_safety_0.smt2                  |  16.974s  |  16.974s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9464_safety_0.smt2                  |   1.835s  |   1.835s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9478_terminationG_0.smt2            |  39.641s  |  39.641s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9495_safety_0.smt2                  |  63.058s  |  63.058s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9514_safety_0.smt2                  |   1.447s  |   1.447s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9536_terminationG_0.smt2            |  24.475s  |  24.475s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9553_safety_0.smt2                  |  22.988s  |  22.988s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9579_terminationG_0.smt2            |   1.694s  |   1.694s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9599_safety_0.smt2                  | 131.838s  | 131.838s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__p9619_terminationG_0.smt2            | 137.287s  | 137.287s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAll.jar-obl-11__terminationS_0_0.smt2                |   2.159s  |   2.159s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7661_safety_0.smt2                |  36.448s  |  36.448s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7676_safety_0.smt2                |   4.265s  |   4.265s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7691_safety_0.smt2                |   4.443s  |   4.443s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7706_safety_0.smt2                |   3.038s  |   3.038s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7719_safety_0.smt2                |   4.302s  |   4.302s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7733_safety_0.smt2                |   3.611s  |   3.611s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7744_safety_0.smt2                |  54.789s  |  54.789s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7758_safety_0.smt2                |  16.522s  |  16.522s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7772_safety_0.smt2                |   5.952s  |   5.952s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7784_safety_0.smt2                |   3.613s  |   3.613s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7794_safety_0.smt2                |   2.035s  |   2.035s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7804_safety_0.smt2                |   3.949s  |   3.949s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7814_safety_0.smt2                |   2.353s  |   2.353s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7826_safety_0.smt2                |   6.311s  |   6.311s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7836_safety_0.smt2                |   5.671s  |   5.671s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7846_safety_0.smt2                |   3.439s  |   3.439s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7858_safety_0.smt2                |   3.560s  |   3.560s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7870_safety_0.smt2                |   3.426s  |   3.426s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7885_safety_0.smt2                | 212.133s  | 212.133s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7898_safety_0.smt2                |   9.838s  |   9.838s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7913_safety_0.smt2                |  16.747s  |  16.747s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7928_safety_0.smt2                |   4.412s  |   4.412s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7947_safety_0.smt2                |   7.920s  |   7.920s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7961_safety_0.smt2                |   6.660s  |   6.660s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7974_safety_0.smt2                |  64.296s  |  64.296s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p7995_safety_0.smt2                |   9.727s  |   9.727s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8012_safety_0.smt2                |  12.079s  |  12.079s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8024_safety_0.smt2                |   4.238s  |   4.238s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8043_safety_0.smt2                |   3.696s  |   3.696s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8053_safety_0.smt2                |   1.504s  |   1.504s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8067_safety_0.smt2                |  24.502s  |  24.502s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8104_safety_0.smt2                |   4.149s  |   4.149s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8124_safety_0.smt2                |   3.106s  |   3.106s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8136_safety_0.smt2                |   4.729s  |   4.729s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8152_safety_0.smt2                |  28.923s  |  28.923s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8174_safety_0.smt2                |   3.733s  |   3.733s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8186_safety_0.smt2                |   2.381s  |   2.381s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8197_safety_0.smt2                |   2.168s  |   2.168s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8209_safety_0.smt2                |   4.947s  |   4.947s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8219_safety_0.smt2                |   3.083s  |   3.083s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8231_safety_0.smt2                |   3.570s  |   3.570s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8241_safety_0.smt2                |   2.587s  |   2.587s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8256_safety_0.smt2                |   9.614s  |   9.614s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8266_safety_0.smt2                |   9.505s  |   9.505s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8278_safety_0.smt2                |   3.000s  |   3.000s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8294_safety_0.smt2                |   3.122s  |   3.122s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8312_safety_0.smt2                |   3.097s  |   3.097s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8326_safety_0.smt2                |   5.359s  |   5.359s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8339_safety_0.smt2                |   4.934s  |   4.934s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8353_safety_0.smt2                |   3.437s  |   3.437s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8365_safety_0.smt2                |   2.454s  |   2.454s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8376_safety_0.smt2                |   1.582s  |   1.582s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8386_safety_0.smt2                |  22.003s  |  22.003s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8406_safety_0.smt2                |   3.190s  |   3.190s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8419_safety_0.smt2                |   1.720s  |   1.720s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8432_safety_0.smt2                |  86.327s  |  86.327s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8446_safety_0.smt2                |   1.314s  |   1.314s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8465_safety_0.smt2                |  13.482s  |  13.482s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8478_safety_0.smt2                |   2.088s  |   2.088s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8489_safety_0.smt2                |  12.731s  |  12.731s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8513_safety_0.smt2                |  11.766s  |  11.766s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8531_safety_0.smt2                |  32.727s  |  32.727s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8544_safety_0.smt2                |   8.868s  |   8.868s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8561_safety_0.smt2                | 600.083s  | 600.083s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8574_safety_0.smt2                |   6.792s  |   6.792s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8584_safety_0.smt2                |  23.827s  |  23.827s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8623_safety_0.smt2                |   3.477s  |   3.477s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8641_safety_0.smt2                |   2.154s  |   2.154s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8652_safety_0.smt2                |   6.593s  |   6.593s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8666_safety_0.smt2                |   2.550s  |   2.550s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8680_safety_0.smt2                | 418.569s  | 418.569s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8694_safety_0.smt2                |   3.812s  |   3.812s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8705_safety_0.smt2                |   3.949s  |   3.949s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8717_safety_0.smt2                |  74.985s  |  74.985s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8731_safety_0.smt2                |  47.341s  |  47.341s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8741_safety_0.smt2                |   1.973s  |   1.973s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8753_safety_0.smt2                |  10.819s  |  10.819s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8765_safety_0.smt2                |   3.901s  |   3.901s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8778_safety_0.smt2                |  15.513s  |  15.513s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8791_safety_0.smt2                |   7.566s  |   7.566s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8803_safety_0.smt2                |   1.525s  |   1.525s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8814_safety_0.smt2                |   2.232s  |   2.232s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8840_safety_0.smt2                |   7.946s  |   7.946s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8855_safety_0.smt2                |  18.503s  |  18.503s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8867_safety_0.smt2                |   2.121s  |   2.121s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8880_safety_0.smt2                |  50.565s  |  50.565s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8903_safety_0.smt2                |  64.685s  |  64.685s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8917_safety_0.smt2                |   3.217s  |   3.217s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8929_safety_0.smt2                |   6.625s  |   6.625s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8945_safety_0.smt2                |   2.291s  |   2.291s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8959_safety_0.smt2                |  15.883s  |  15.883s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8977_safety_0.smt2                |   4.377s  |   4.377s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8988_safety_0.smt2                |   1.650s  |   1.650s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p8999_safety_0.smt2                |  19.575s  |  19.575s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9017_safety_0.smt2                |   5.141s  |   5.141s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9028_safety_0.smt2                |   9.309s  |   9.309s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9067_safety_0.smt2                |   7.229s  |   7.229s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9081_safety_0.smt2                |  10.454s  |  10.454s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9099_safety_0.smt2                |   2.608s  |   2.608s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9110_safety_0.smt2                |   3.170s  |   3.170s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9121_safety_0.smt2                |   2.693s  |   2.693s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9137_safety_0.smt2                |   1.899s  |   1.899s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9149_safety_0.smt2                | 600.076s  | 600.076s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9165_safety_0.smt2                |   1.304s  |   1.304s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9177_safety_0.smt2                |   3.323s  |   3.323s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9188_safety_0.smt2                |   7.623s  |   7.623s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9199_safety_0.smt2                |   2.289s  |   2.289s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9214_safety_0.smt2                |   2.805s  |   2.805s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9227_safety_0.smt2                |   3.592s  |   3.592s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9241_safety_0.smt2                |   2.151s  |   2.151s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9255_safety_0.smt2                |  13.045s  |  13.045s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9267_safety_0.smt2                |  13.490s  |  13.490s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9281_safety_0.smt2                |   1.592s  |   1.592s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9294_safety_0.smt2                |   7.586s  |   7.586s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9306_safety_0.smt2                |  40.777s  |  40.777s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__p9322_safety_0.smt2                |   1.543s  |   1.543s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateAddAllAt.jar-obl-17__terminationS_2_0.smt2              |   3.019s  |   3.019s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContains.jar-obl-16__term_unfeasibility_9_0.smt2        |   6.027s  |   6.027s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_12_0.smt2          |  79.650s  |  79.650s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_21_0.smt2          |  93.585s  |  93.585s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateContainsAll.jar-obl-11__terminationS_30_0.smt2          |  50.050s  |  50.050s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateEquals.jar-obl-13__term_unfeasibility_5_0.smt2          |   3.494s  |   3.494s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateLastIndexOf.jar-obl-16__term_unfeasibility_4_0.smt2     |   5.801s  |   5.801s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_0_0.smt2             | 600.186s  | 600.186s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_19_0.smt2            | 177.311s  | 177.311s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAll.jar-obl-11__terminationS_28_0.smt2            | 231.525s  | 231.525s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveAt.jar-obl-10__term_unfeasibility_3_0.smt2        |   2.110s  |   2.110s  |   0.000s  | 0.0%|
|From_AProVE_2014__juLinkedListCreateRemoveLastOccurrence.jar-obl-16__term_unfeasibility_9_0.smt2  |   2.064s  |   2.064s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10912_terminationG_0.smt2                    |   2.681s  |   2.681s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10930_terminationG_0.smt2                    |   2.520s  |   2.520s  |   0.000s  | 0.0%|
|From_AProVE_2014__mirrorInterv_rec.jar-obl-8__p10946_edge_closing_0.smt2                    | 600.198s  | 600.198s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11055_terminationG_0.smt2                       |   2.486s  |   2.486s  |   0.000s  | 0.0%|
|From_AProVE_2014__narrowing_rec.jar-obl-8__p11071_edge_closing_0.smt2                       |  10.449s  |  10.449s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric2_rec.jar-obl-8__p12293_terminationG_0.smt2                     |   4.924s  |   4.924s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12326_terminationG_0.smt2                      | 600.065s  | 600.065s  |   0.000s  | 0.0%|
|From_AProVE_2014__sumGeneric_rec.jar-obl-8__p12350_terminationG_0.smt2                      |   5.670s  |   5.670s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__p12391_terminationG_0.smt2                          |   7.494s  |   7.494s  |   0.000s  | 0.0%|
|From_AProVE_2014__sunset_rec.jar-obl-8__term_unfeasibility_0_0.smt2                         |   0.840s  |   0.840s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__p13122_edge_closing_0.smt2                   |   5.398s  |   5.398s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDownIneq_rec.jar-obl-8__terminationS_4_0.smt2                        |   3.085s  |   3.085s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__p13155_edge_closing_0.smt2                       | 600.118s  | 600.118s  |   0.000s  | 0.0%|
|From_AProVE_2014__upAndDown_rec.jar-obl-8__terminationS_3_0.smt2                            |   3.050s  |   3.050s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNestedOffset_rec.jar-obl-9__p14936_terminationG_0.smt2               |   0.707s  |   0.707s  |   0.000s  | 0.0%|
|From_AProVE_2014__whileNested_rec.jar-obl-9__p14975_terminationG_0.smt2                     |   1.118s  |   1.118s  |   0.000s  | 0.0%|
|From_T2__1.t2__p15279_safety_0.smt2                                                         |   7.203s  |   7.203s  |   0.000s  | 0.0%|
|From_T2__1394complete-fail.t2__p15161_safety_0.smt2                                         |   3.856s  |   3.856s  |   0.000s  | 0.0%|
|From_T2__2.t2__p15344_terminationG_0.smt2                                                   | 600.132s  | 600.132s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7940_terminationG_0.smt2                                               |  30.553s  |  30.553s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7965_terminationG_0.smt2                                               |  17.201s  |  17.201s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p7990_terminationG_0.smt2                                               |  10.327s  |  10.327s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8014_terminationG_0.smt2                                               |   0.811s  |   0.811s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8036_terminationG_0.smt2                                               | 156.739s  | 156.739s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8056_terminationG_0.smt2                                               | 197.042s  | 197.042s  |   0.000s  | 0.0%|
|From_T2__Prim_4.t2__p8088_edge_closing_0.smt2                                               |   3.151s  |   3.151s  |   0.000s  | 0.0%|
|From_T2__acqrel-fail.t2__p15388_terminationG_0.smt2                                         |   0.289s  |   0.289s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15470_terminationG_0.smt2                                          |   4.960s  |   4.960s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15486_terminationG_0.smt2                                          | 600.314s  | 600.314s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__p15502_terminationG_0.smt2                                          |   3.891s  |   3.891s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2__terminationQ_9_0.smt2                                               |   1.720s  |   1.720s  |   0.000s  | 0.0%|
|From_T2__afagp-fail.t2_fixed__p15428_terminationG_0.smt2                                    |   1.296s  |   1.296s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15582_terminationG_0.smt2                                               | 600.136s  | 600.136s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15598_terminationG_0.smt2                                               | 600.217s  | 600.217s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15616_terminationG_0.smt2                                               |  20.084s  |  20.084s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15632_terminationG_0.smt2                                               | 600.122s  | 600.122s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__p15648_terminationG_0.smt2                                               | 600.119s  | 600.119s  |   0.000s  | 0.0%|
|From_T2__agafp.t2__terminationQ_12_0.smt2                                                   |   2.330s  |   2.330s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15538_terminationG_0.smt2                                         | 600.130s  | 600.130s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15554_terminationG_0.smt2                                         | 600.167s  | 600.167s  |   0.000s  | 0.0%|
|From_T2__agafp.t2_fixed__p15572_edge_closing_0.smt2                                         | 600.087s  | 600.087s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p15972_terminationG_0.smt2                               | 600.545s  | 600.545s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__p16010_terminationG_0.smt2                               |  72.142s  |  72.142s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2__term_unfeasibility_2_0.smt2                              |  10.012s  |  10.012s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15778_terminationG_0.smt2                         |   6.433s  |   6.433s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15806_terminationG_0.smt2                         | 600.388s  | 600.388s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15852_terminationG_0.smt2                         |  10.978s  |  10.978s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15876_safety_0.smt2                               |   0.537s  |   0.537s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__p15906_edge_closing_0.smt2                         | 600.293s  | 600.293s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_11_0.smt2                             |  41.253s  |  41.253s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted-fail.t2_fixed__terminationS_5_0.smt2                              |  30.287s  |  30.287s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16279_terminationG_0.smt2                                    | 600.946s  | 600.946s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__p16319_terminationG_0.smt2                                    |  32.215s  |  32.215s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2__terminationQ_9_0.smt2                                         |  19.691s  |  19.691s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16109_terminationG_0.smt2                              |  32.525s  |  32.525s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16142_safety_0.smt2                                    |   2.276s  |   2.276s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__p16184_edge_closing_0.smt2                              | 600.286s  | 600.286s  |   0.000s  | 0.0%|
|From_T2__apchild-accepted.t2_fixed__terminationS_4_0.smt2                                   |  90.637s  |  90.637s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16624_terminationG_0.smt2                                        |   5.040s  |   5.040s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16640_terminationG_0.smt2                                        |   5.875s  |   5.875s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16660_terminationG_0.smt2                                        |  12.534s  |  12.534s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__p16675_safety_0.smt2                                              |   0.602s  |   0.602s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_1_0.smt2                                             |  11.667s  |  11.667s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2__terminationS_4_0.smt2                                             |  10.249s  |  10.249s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16480_terminationG_0.smt2                                  |   7.070s  |   7.070s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16501_safety_0.smt2                                        |   0.417s  |   0.417s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16518_safety_0.smt2                                        |   1.296s  |   1.296s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16538_terminationG_0.smt2                                  |   4.534s  |   4.534s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16558_terminationG_0.smt2                                  |   6.590s  |   6.590s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16582_safety_0.smt2                                        |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__p16596_terminationG_0.smt2                                  | 542.715s  | 542.715s  |   0.000s  | 0.0%|
|From_T2__apchild-live.t2_fixed__term_unfeasibility_2_0.smt2                                 |   2.950s  |   2.950s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16429_terminationG_0.smt2                                 |  15.385s  |  15.385s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16446_terminationG_0.smt2                                 |   7.057s  |   7.057s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__p16461_edge_closing_0.smt2                                 | 538.063s  | 538.063s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2__terminationS_33_0.smt2                                     |  16.320s  |  16.320s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__p16388_terminationG_0.smt2                           | 606.746s  | 606.746s  |   0.000s  | 0.0%|
|From_T2__apchildlive-succeed.t2_fixed__term_unfeasibility_1_0.smt2                          |   4.301s  |   4.301s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17029_terminationG_0.smt2                                              |   4.218s  |   4.218s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17049_terminationG_0.smt2                                              | 600.074s  | 600.074s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17068_terminationG_0.smt2                                              |  10.861s  |  10.861s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17084_terminationG_0.smt2                                              | 600.154s  | 600.154s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17100_terminationG_0.smt2                                              | 600.201s  | 600.201s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17118_terminationG_0.smt2                                              |  13.857s  |  13.857s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17134_terminationG_0.smt2                                              | 600.186s  | 600.186s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17150_terminationG_0.smt2                                              | 600.083s  | 600.083s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17168_terminationG_0.smt2                                              |   2.158s  |   2.158s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17184_terminationG_0.smt2                                              | 600.088s  | 600.088s  |   0.000s  | 0.0%|
|From_T2__bakery.t2__p17200_terminationG_0.smt2                                              | 600.104s  | 600.104s  |   0.000s  | 0.0%|
|From_T2__brockschmidt_1.t2__p17389_terminationG_0.smt2                                      |   3.333s  |   3.333s  |   0.000s  | 0.0%|
|From_T2__broydn.c.i.broydn.pl.t2.fixed.t2_fixed__term_unfeasibility_10_0.smt2               |   3.081s  |   3.081s  |   0.000s  | 0.0%|
|From_T2__broydn.t2__term_unfeasibility_11_0.smt2                                            |  35.889s  |  35.889s  |   0.000s  | 0.0%|
|From_T2__broydn.t2_fixed__term_unfeasibility_3_0.smt2                                       |  10.604s  |  10.604s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__p17426_terminationG_0.smt2                                      |  29.664s  |  29.664s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__term_unfeasibility_1_0.smt2                                     |  42.549s  |  42.549s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_17_0.smt2                                          |  52.271s  |  52.271s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_26_0.smt2                                          |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|From_T2__brp_withassume.t2__terminationS_5_0.smt2                                           |  62.783s  |  62.783s  |   0.000s  | 0.0%|
|From_T2__bs.t2_fixed__p17456_terminationG_0.smt2                                            | 582.254s  | 582.254s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17543_terminationG_0.smt2                                             | 219.808s  | 219.808s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17559_terminationG_0.smt2                                             | 600.099s  | 600.099s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17578_terminationG_0.smt2                                             |   2.850s  |   2.850s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17594_terminationG_0.smt2                                             | 600.110s  | 600.110s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17610_terminationG_0.smt2                                             | 600.136s  | 600.136s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17628_terminationG_0.smt2                                             |   2.597s  |   2.597s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17644_terminationG_0.smt2                                             | 600.136s  | 600.136s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17661_terminationG_0.smt2                                             | 600.174s  | 600.174s  |   0.000s  | 0.0%|
|From_T2__byron-4.t2__p17679_terminationG_0.smt2                                             |   1.948s  |   1.948s  |   0.000s  | 0.0%|
|From_T2__cfg.t2__p17716_terminationG_0.smt2                                                 | 600.204s  | 600.204s  |   0.000s  | 0.0%|
|From_T2__collatz.t2_fixed__terminationS_2_0.smt2                                            |   0.449s  |   0.449s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17837_safety_0.smt2                                                  | 600.224s  | 600.224s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17860_terminationG_0.smt2                                            |   0.324s  |   0.324s  |   0.000s  | 0.0%|
|From_T2__compress.t2__p17884_terminationG_0.smt2                                            |  15.146s  |  15.146s  |   0.000s  | 0.0%|
|From_T2__compress.t2_fixed__p17801_edge_closing_0.smt2                                      |   4.749s  |   4.749s  |   0.000s  | 0.0%|
|From_T2__consts1.t2__p17980_terminationG_0.smt2                                             | 600.144s  | 600.144s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2__p17940_terminationG_0.smt2                                           |   2.414s  |   2.414s  |   0.000s  | 0.0%|
|From_T2__consts1nt.t2_fixed__p17918_terminationG_0.smt2                                     |   6.864s  |   6.864s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2__p18050_terminationG_0.smt2                                           |   1.549s  |   1.549s  |   0.000s  | 0.0%|
|From_T2__consts2nt.t2_fixed__p18017_terminationG_0.smt2                                     |   3.545s  |   3.545s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2__p18179_terminationG_0.smt2                                           |   4.437s  |   4.437s  |   0.000s  | 0.0%|
|From_T2__consts3nt.t2_fixed__p18120_terminationG_0.smt2                                     |   3.800s  |   3.800s  |   0.000s  | 0.0%|
|From_T2__consts4.t2__p18338_terminationG_0.smt2                                             | 600.085s  | 600.085s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18220_terminationG_0.smt2                                     |   4.330s  |   4.330s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18242_terminationG_0.smt2                                     |   8.107s  |   8.107s  |   0.000s  | 0.0%|
|From_T2__consts4nt.t2_fixed__p18266_terminationG_0.smt2                                     |   4.696s  |   4.696s  |   0.000s  | 0.0%|
|From_T2__consts5.t2__p18494_terminationG_0.smt2                                             |   1.161s  |   1.161s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18414_terminationG_0.smt2                                           |   2.090s  |   2.090s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2__p18444_edge_closing_0.smt2                                           |  36.275s  |  36.275s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18371_terminationG_0.smt2                                     |   1.911s  |   1.911s  |   0.000s  | 0.0%|
|From_T2__consts5nt.t2_fixed__p18393_terminationG_0.smt2                                     |   4.697s  |   4.697s  |   0.000s  | 0.0%|
|From_T2__cover.t2__p18610_edge_closing_0.smt2                                               | 600.454s  | 600.454s  |   0.000s  | 0.0%|
|From_T2__curious.t2__p18703_terminationG_0.smt2                                             |   1.415s  |   1.415s  |   0.000s  | 0.0%|
|From_T2__curious4.t2__p18665_edge_closing_0.smt2                                            | 600.206s  | 600.206s  |   0.000s  | 0.0%|
|From_T2__d.t2__p19043_terminationG_0.smt2                                                   |   1.094s  |   1.094s  |   0.000s  | 0.0%|
|From_T2__db2.t2__p18746_edge_closing_0.smt2                                                 | 600.337s  | 600.337s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_20_0.smt2                                                     |   9.211s  |   9.211s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_33_0.smt2                                                     |  20.227s  |  20.227s  |   0.000s  | 0.0%|
|From_T2__db2.t2__terminationS_6_0.smt2                                                      |   9.614s  |   9.614s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__p18729_edge_closing_0.smt2                                           | 600.123s  | 600.123s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_18_0.smt2                                               |  11.243s  |  11.243s  |   0.000s  | 0.0%|
|From_T2__db2.t2_fixed__terminationS_28_0.smt2                                               |  10.372s  |  10.372s  |   0.000s  | 0.0%|
|From_T2__db3.t2__p18773_terminationG_0.smt2                                                 | 600.251s  | 600.251s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationQ_0_0.smt2                                                      | 287.540s  | 287.540s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_26_0.smt2                                                     |  11.747s  |  11.747s  |   0.000s  | 0.0%|
|From_T2__db3.t2__terminationS_40_0.smt2                                                     |  13.364s  |  13.364s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__p18755_terminationG_0.smt2                                           | 600.088s  | 600.088s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_0_0.smt2                                                |  23.503s  |  23.503s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_21_0.smt2                                               |  11.213s  |  11.213s  |   0.000s  | 0.0%|
|From_T2__db3.t2_fixed__terminationS_3_0.smt2                                                |  22.687s  |  22.687s  |   0.000s  | 0.0%|
|From_T2__dead.neg-st88b-succeed.t2__p18802_terminationG_0.smt2                              | 600.077s  | 600.077s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2__p18873_terminationG_0.smt2                                    | 646.822s  | 646.822s  |   0.000s  | 0.0%|
|From_T2__destroy_seg_leak.t2_fixed__p18843_safety_0.smt2                                    |   2.024s  |   2.024s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18920_terminationG_0.smt2                                      |   3.685s  |   3.685s  |   0.000s  | 0.0%|
|From_T2__disj_nightmare.t2__p18946_edge_closing_0.smt2                                      | 600.255s  | 600.255s  |   0.000s  | 0.0%|
|From_T2__dummy.t2__p19098_terminationG_0.smt2                                               | 600.113s  | 600.113s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__p19133_terminationG_0.smt2                                              | 600.133s  | 600.133s  |   0.000s  | 0.0%|
|From_T2__dumper.t2__terminationS_1_0.smt2                                                   |   3.242s  |   3.242s  |   0.000s  | 0.0%|
|From_T2__e-acqrel-succeed.t2__p19620_safety_0.smt2                                          |   0.585s  |   0.585s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19669_safety_0.smt2                                                       | 600.113s  | 600.113s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19793_safety_0.smt2                                                       |   5.238s  |   5.238s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19844_safety_0.smt2                                                       |   1.141s  |   1.141s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19879_safety_0.smt2                                                       | 600.101s  | 600.101s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19908_safety_0.smt2                                                       |   0.970s  |   0.970s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19956_safety_0.smt2                                                       |   0.490s  |   0.490s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p19978_safety_0.smt2                                                       | 600.064s  | 600.064s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20050_safety_0.smt2                                                       | 600.081s  | 600.081s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20154_safety_0.smt2                                                       |   0.676s  |   0.676s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20182_safety_0.smt2                                                       | 600.111s  | 600.111s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20225_safety_0.smt2                                                       |   1.192s  |   1.192s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20262_safety_0.smt2                                                       |   4.577s  |   4.577s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20296_safety_0.smt2                                                       |   5.473s  |   5.473s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20322_safety_0.smt2                                                       |  10.343s  |  10.343s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20360_safety_0.smt2                                                       |   0.693s  |   0.693s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20405_safety_0.smt2                                                       | 600.182s  | 600.182s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20458_safety_0.smt2                                                       |   0.602s  |   0.602s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20506_safety_0.smt2                                                       |   3.330s  |   3.330s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20573_safety_0.smt2                                                       | 600.143s  | 600.143s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20628_safety_0.smt2                                                       |   2.211s  |   2.211s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20672_safety_0.smt2                                                       |   6.776s  |   6.776s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20696_safety_0.smt2                                                       | 600.101s  | 600.101s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20738_safety_0.smt2                                                       |   2.316s  |   2.316s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20765_safety_0.smt2                                                       |   1.337s  |   1.337s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20799_safety_0.smt2                                                       |   6.038s  |   6.038s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20828_safety_0.smt2                                                       | 600.123s  | 600.123s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20879_safety_0.smt2                                                       | 600.165s  | 600.165s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p20924_safety_0.smt2                                                       |   7.989s  |   7.989s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21066_safety_0.smt2                                                       |   8.025s  |   8.025s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21132_safety_0.smt2                                                       | 600.305s  | 600.305s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21367_safety_0.smt2                                                       | 600.069s  | 600.069s  |   0.000s  | 0.0%|
|From_T2__edn.t2__p21455_safety_0.smt2                                                       |   0.988s  |   0.988s  |   0.000s  | 0.0%|
|From_T2__edn.t2__terminationS_2_0.smt2                                                      |   0.497s  |   0.497s  |   0.000s  | 0.0%|
|From_T2__efegp.t2__p21964_edge_closing_0.smt2                                               | 577.266s  | 577.266s  |   0.000s  | 0.0%|
|From_T2__efegp.t2_fixed__p21941_edge_closing_0.smt2                                         | 600.184s  | 600.184s  |   0.000s  | 0.0%|
|From_T2__eric.t2__p22069_terminationG_0.smt2                                                |   2.810s  |   2.810s  |   0.000s  | 0.0%|
|From_T2__eric1.t2__p22014_edge_closing_0.smt2                                               |   1.063s  |   1.063s  |   0.000s  | 0.0%|
|From_T2__eric2.t2__terminationQ_0_0.smt2                                                    |   2.950s  |   2.950s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22351_terminationG_0.smt2                                                 |   0.932s  |   0.932s  |   0.000s  | 0.0%|
|From_T2__ex1.t2__p22367_terminationG_0.smt2                                                 | 600.090s  | 600.090s  |   0.000s  | 0.0%|
|From_T2__ex10.t2__p22103_terminationG_0.smt2                                                |   0.849s  |   0.849s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22228_terminationG_0.smt2                                                |  10.631s  |  10.631s  |   0.000s  | 0.0%|
|From_T2__ex16.t2__p22253_terminationG_0.smt2                                                |   8.369s  |   8.369s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22165_terminationG_0.smt2                                          |   4.112s  |   4.112s  |   0.000s  | 0.0%|
|From_T2__ex16.t2_fixed__p22190_terminationG_0.smt2                                          |   7.516s  |   7.516s  |   0.000s  | 0.0%|
|From_T2__ex17.t2__p22290_terminationG_0.smt2                                                |   6.119s  |   6.119s  |   0.000s  | 0.0%|
|From_T2__ex19.t2__p22325_terminationG_0.smt2                                                | 600.115s  | 600.115s  |   0.000s  | 0.0%|
|From_T2__ex2.t2__p22462_terminationG_0.smt2                                                 |   1.371s  |   1.371s  |   0.000s  | 0.0%|
|From_T2__ex2.t2_fixed__p22449_terminationG_0.smt2                                           |   5.019s  |   5.019s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p24638_terminationG_0.smt2                                                | 602.604s  | 602.604s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25279_safety_0.smt2                                                      |   1.704s  |   1.704s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25402_safety_0.smt2                                                      |   1.608s  |   1.608s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25532_safety_0.smt2                                                      |   2.887s  |   2.887s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25650_safety_0.smt2                                                      | 600.067s  | 600.067s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p25811_safety_0.smt2                                                      |   2.827s  |   2.827s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26154_safety_0.smt2                                                      |   4.873s  |   4.873s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26310_safety_0.smt2                                                      |  20.609s  |  20.609s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26688_safety_0.smt2                                                      |   1.942s  |   1.942s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p26896_safety_0.smt2                                                      |   0.766s  |   0.766s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27260_safety_0.smt2                                                      |   1.858s  |   1.858s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27736_safety_0.smt2                                                      |   1.958s  |   1.958s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27854_safety_0.smt2                                                      |   2.725s  |   2.725s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p27937_safety_0.smt2                                                      |   1.401s  |   1.401s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28143_safety_0.smt2                                                      |   1.439s  |   1.439s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28282_safety_0.smt2                                                      |   5.442s  |   5.442s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28396_safety_0.smt2                                                      |   2.385s  |   2.385s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28445_safety_0.smt2                                                      |   0.878s  |   0.878s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28528_safety_0.smt2                                                      |   8.450s  |   8.450s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28593_safety_0.smt2                                                      |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28669_safety_0.smt2                                                      |   3.102s  |   3.102s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28710_safety_0.smt2                                                      | 600.170s  | 600.170s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28763_safety_0.smt2                                                      |   1.242s  |   1.242s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28843_safety_0.smt2                                                      | 600.065s  | 600.065s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p28953_safety_0.smt2                                                      |   1.787s  |   1.787s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29075_safety_0.smt2                                                      |   2.666s  |   2.666s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29189_safety_0.smt2                                                      |   2.183s  |   2.183s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29291_safety_0.smt2                                                      |   1.179s  |   1.179s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29339_safety_0.smt2                                                      |   7.121s  |   7.121s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29417_safety_0.smt2                                                      |  17.101s  |  17.101s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29508_safety_0.smt2                                                      |   2.611s  |   2.611s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29585_safety_0.smt2                                                      |   7.108s  |   7.108s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29667_safety_0.smt2                                                      |   4.344s  |   4.344s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29769_safety_0.smt2                                                      |   3.170s  |   3.170s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29903_safety_0.smt2                                                      |  64.824s  |  64.824s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p29995_safety_0.smt2                                                      |   5.164s  |   5.164s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30140_safety_0.smt2                                                      | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30283_safety_0.smt2                                                      | 600.226s  | 600.226s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30341_safety_0.smt2                                                      |   4.066s  |   4.066s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30378_safety_0.smt2                                                      |   4.124s  |   4.124s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30450_safety_0.smt2                                                      | 605.118s  | 605.118s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30487_safety_0.smt2                                                      |   7.899s  |   7.899s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30570_safety_0.smt2                                                      |   7.172s  |   7.172s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30669_safety_0.smt2                                                      |  10.464s  |  10.464s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30759_safety_0.smt2                                                      |   3.049s  |   3.049s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30852_safety_0.smt2                                                      |   2.342s  |   2.342s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p30909_safety_0.smt2                                                      |   2.386s  |   2.386s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31057_safety_0.smt2                                                      |   1.069s  |   1.069s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31189_safety_0.smt2                                                      | 607.255s  | 607.255s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31283_safety_0.smt2                                                      |   0.910s  |   0.910s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31375_safety_0.smt2                                                      | 600.155s  | 600.155s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31417_safety_0.smt2                                                      |   3.098s  |   3.098s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31483_safety_0.smt2                                                      |   4.173s  |   4.173s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31535_safety_0.smt2                                                      | 600.043s  | 600.043s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31596_safety_0.smt2                                                      |   1.140s  |   1.140s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31649_safety_0.smt2                                                      | 600.178s  | 600.178s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31717_safety_0.smt2                                                      |   2.913s  |   2.913s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31769_safety_0.smt2                                                      |   8.267s  |   8.267s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31824_safety_0.smt2                                                      | 305.918s  | 305.918s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31869_safety_0.smt2                                                      |   2.834s  |   2.834s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31932_safety_0.smt2                                                      |   1.460s  |   1.460s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p31964_safety_0.smt2                                                      |   0.838s  |   0.838s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32037_safety_0.smt2                                                      |   1.084s  |   1.084s  |   0.000s  | 0.0%|
|From_T2__ex36.t2__p32131_safety_0.smt2                                                      |   4.394s  |   4.394s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22547_terminationG_0.smt2                                          |   2.013s  |   2.013s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22611_safety_0.smt2                                                |   3.958s  |   3.958s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22718_safety_0.smt2                                                |   1.980s  |   1.980s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p22848_safety_0.smt2                                                |   2.955s  |   2.955s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23071_safety_0.smt2                                                |   6.605s  |   6.605s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23187_safety_0.smt2                                                |   6.019s  |   6.019s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23260_safety_0.smt2                                                |   2.641s  |   2.641s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23302_safety_0.smt2                                                |   2.142s  |   2.142s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23504_safety_0.smt2                                                |   1.906s  |   1.906s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23573_safety_0.smt2                                                |   3.183s  |   3.183s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23612_safety_0.smt2                                                |   2.538s  |   2.538s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23679_safety_0.smt2                                                |  12.670s  |  12.670s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23746_safety_0.smt2                                                |   2.585s  |   2.585s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p23881_safety_0.smt2                                                |   4.585s  |   4.585s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24107_safety_0.smt2                                                |   2.047s  |   2.047s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24259_safety_0.smt2                                                |   4.418s  |   4.418s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24469_safety_0.smt2                                                |   6.675s  |   6.675s  |   0.000s  | 0.0%|
|From_T2__ex36.t2_fixed__p24595_safety_0.smt2                                                |   8.200s  |   8.200s  |   0.000s  | 0.0%|
|From_T2__ex40.t2__p32196_terminationG_0.smt2                                                |   6.620s  |   6.620s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32277_terminationG_0.smt2                                            |  11.511s  |  11.511s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__p32294_terminationG_0.smt2                                            | 600.351s  | 600.351s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationQ_1_0.smt2                                                 |  78.431s  |  78.431s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_18_0.smt2                                                |  37.513s  |  37.513s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_27_0.smt2                                                |  16.231s  |  16.231s  |   0.000s  | 0.0%|
|From_T2__firewire.t2__terminationS_9_0.smt2                                                 |  19.276s  |  19.276s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32378_terminationG_0.smt2                                        |   3.086s  |   3.086s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__p32410_terminationG_0.smt2                                        | 286.277s  | 286.277s  |   0.000s  | 0.0%|
|From_T2__florian_sas2.t2__terminationS_2_0.smt2                                             |  16.401s  |  16.401s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32424_terminationG_0.smt2                                       | 600.143s  | 600.143s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__p32442_edge_closing_0.smt2                                       |  13.138s  |  13.138s  |   0.000s  | 0.0%|
|From_T2__florian_sumit.t2__terminationQ_0_0.smt2                                            |   5.464s  |   5.464s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_12_0.smt2                                                     | 600.223s  | 600.223s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_21_0.smt2                                                     | 600.238s  | 600.238s  |   0.000s  | 0.0%|
|From_T2__foo.t2__terminationS_30_0.smt2                                                     | 600.181s  | 600.181s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32585_terminationG_0.smt2                         |  14.431s  |  14.431s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32621_safety_0.smt2                               | 600.073s  | 600.073s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.fixed.t2__p32640_edge_closing_0.smt2                         | 600.479s  | 600.479s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32660_terminationG_0.smt2               | 600.479s  | 600.479s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__p32684_safety_0.smt2                     |   1.584s  |   1.584s  |   0.000s  | 0.0%|
|From_T2__fourn.c.i.fourn.pl.t2.nor.t2.rlgfixed.t2__terminationQ_1_0.smt2                    |   3.477s  |   3.477s  |   0.000s  | 0.0%|
|From_T2__fourn.t2__p32736_edge_closing_0.smt2                                               | 600.801s  | 600.801s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p806_terminationG_0.smt2                                                  | 600.317s  | 600.317s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__p831_terminationG_0.smt2                                                  |  46.823s  |  46.823s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationQ_0_0.smt2                                                     | 113.982s  | 113.982s  |   0.000s  | 0.0%|
|From_T2__fun1.t2__terminationS_3_0.smt2                                                     |  25.518s  |  25.518s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p703_terminationG_0.smt2                                            |  38.390s  |  38.390s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p728_terminationG_0.smt2                                            |   3.585s  |   3.585s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__p754_terminationG_0.smt2                                            | 607.823s  | 607.823s  |   0.000s  | 0.0%|
|From_T2__fun1.t2_fixed__term_unfeasibility_0_0.smt2                                         |   2.951s  |   2.951s  |   0.000s  | 0.0%|
|From_T2__fun10.t2__p405_terminationG_0.smt2                                                 |   1.323s  |   1.323s  |   0.000s  | 0.0%|
|From_T2__fun10b.t2__p340_terminationG_0.smt2                                                | 600.148s  | 600.148s  |   0.000s  | 0.0%|
|From_T2__fun11.t2__p467_terminationG_0.smt2                                                 |   3.610s  |   3.610s  |   0.000s  | 0.0%|
|From_T2__fun11.t2_fixed__p437_terminationG_0.smt2                                           |   0.537s  |   0.537s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p596_terminationG_0.smt2                                                 | 122.657s  | 122.657s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p616_terminationG_0.smt2                                                 |  84.076s  |  84.076s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p639_terminationG_0.smt2                                                 | 600.325s  | 600.325s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p666_terminationG_0.smt2                                                 |  40.825s  |  40.825s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__p685_terminationG_0.smt2                                                 | 121.182s  | 121.182s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2__terminationS_15_0.smt2                                                   |  19.300s  |  19.300s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p494_terminationG_0.smt2                                           |   2.037s  |   2.037s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p519_terminationG_0.smt2                                           | 160.959s  | 160.959s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p544_terminationG_0.smt2                                           | 276.366s  | 276.366s  |   0.000s  | 0.0%|
|From_T2__fun1b.t2_fixed__p577_terminationG_0.smt2                                           | 166.238s  | 166.238s  |   0.000s  | 0.0%|
|From_T2__fun4-alt.t2__p884_terminationG_0.smt2                                              |  10.769s  |  10.769s  |   0.000s  | 0.0%|
|From_T2__fun4.t2__p994_terminationG_0.smt2                                                  |  25.045s  |  25.045s  |   0.000s  | 0.0%|
|From_T2__fun5.t2__p1026_terminationG_0.smt2                                                 |  19.522s  |  19.522s  |   0.000s  | 0.0%|
|From_T2__fun5.t2_fixed__p1011_edge_closing_0.smt2                                           |   3.719s  |   3.719s  |   0.000s  | 0.0%|
|From_T2__fun6.t2__p1084_terminationG_0.smt2                                                 |   3.864s  |   3.864s  |   0.000s  | 0.0%|
|From_T2__fun6.t2_fixed__p1064_edge_closing_0.smt2                                           |  14.875s  |  14.875s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__p1142_terminationG_0.smt2                                                 |  15.183s  |  15.183s  |   0.000s  | 0.0%|
|From_T2__fun7.t2__terminationQ_0_0.smt2                                                     |   5.342s  |   5.342s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1196_terminationG_0.smt2                                                 |   3.650s  |   3.650s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1232_edge_closing_0.smt2                                                 | 601.733s  | 601.733s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1248_edge_closing_0.smt2                                                 |  16.711s  |  16.711s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1258_edge_closing_0.smt2                                                 |  91.363s  |  91.363s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1270_edge_closing_0.smt2                                                 |   3.911s  |   3.911s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1280_edge_closing_0.smt2                                                 |   4.563s  |   4.563s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1292_edge_closing_0.smt2                                                 | 600.163s  | 600.163s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1302_edge_closing_0.smt2                                                 |   8.348s  |   8.348s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1314_edge_closing_0.smt2                                                 |  56.608s  |  56.608s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1324_edge_closing_0.smt2                                                 |   3.229s  |   3.229s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1334_edge_closing_0.smt2                                                 |   4.810s  |   4.810s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1346_edge_closing_0.smt2                                                 |   6.815s  |   6.815s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1356_edge_closing_0.smt2                                                 | 600.270s  | 600.270s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1366_edge_closing_0.smt2                                                 |  94.498s  |  94.498s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1376_edge_closing_0.smt2                                                 |   4.803s  |   4.803s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1386_edge_closing_0.smt2                                                 |  38.130s  |  38.130s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1397_edge_closing_0.smt2                                                 |  61.812s  |  61.812s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1407_edge_closing_0.smt2                                                 |   4.410s  |   4.410s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1420_edge_closing_0.smt2                                                 |  14.472s  |  14.472s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1430_edge_closing_0.smt2                                                 | 207.017s  | 207.017s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1442_edge_closing_0.smt2                                                 |   3.282s  |   3.282s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1452_edge_closing_0.smt2                                                 |   3.089s  |   3.089s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1462_edge_closing_0.smt2                                                 |   8.864s  |   8.864s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1472_edge_closing_0.smt2                                                 | 230.847s  | 230.847s  |   0.000s  | 0.0%|
|From_T2__fun9.t2__p1483_edge_closing_0.smt2                                                 |   9.684s  |   9.684s  |   0.000s  | 0.0%|
|From_T2__hand7.t2__p1503_terminationG_0.smt2                                                |  12.975s  |  12.975s  |   0.000s  | 0.0%|
|From_T2__heidy1.t2__p1531_terminationG_0.smt2                                               |   3.481s  |   3.481s  |   0.000s  | 0.0%|
|From_T2__heidy6.t2__terminationQ_1_0.smt2                                                   |  69.171s  |  69.171s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__p1650_edge_closing_0.smt2                              | 600.170s  | 600.170s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_14_0.smt2                                 |  16.962s  |  16.962s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_24_0.smt2                                 | 216.177s  | 216.177s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_33_0.smt2                                 |  79.931s  |  79.931s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_42_0.smt2                                 | 138.781s  | 138.781s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2__terminationS_5_0.smt2                                  |  62.663s  |  62.663s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__p1619_terminationG_0.smt2                        | 644.235s  | 644.235s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_18_0.smt2                           |  49.141s  |  49.141s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_28_0.smt2                           |  30.959s  |  30.959s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_43_0.smt2                           |  30.489s  |  30.489s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.fixed.t2_fixed__terminationS_53_0.smt2                           |  94.216s  |  94.216s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1697_terminationG_0.smt2                    | 600.233s  | 600.233s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__p1718_edge_closing_0.smt2                    | 600.176s  | 600.176s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_18_0.smt2                       |  57.418s  |  57.418s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_27_0.smt2                       |  95.825s  |  95.825s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_36_0.smt2                       |  96.104s  |  96.104s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_46_0.smt2                       |  37.562s  |  37.562s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2__terminationS_7_0.smt2                        |  13.678s  |  13.678s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__p1682_edge_closing_0.smt2              | 275.318s  | 275.318s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_21_0.smt2                 |  44.431s  |  44.431s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_32_0.smt2                 |  23.754s  |  23.754s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_44_0.smt2                 |  53.323s  |  53.323s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_54_0.smt2                 |  26.770s  |  26.770s  |   0.000s  | 0.0%|
|From_T2__hqr.c.i.hqr.pl.t2.nor.t2.rlgfixed.t2_fixed__terminationS_64_0.smt2                 |  25.813s  |  25.813s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__p1776_terminationG_0.smt2                                                  |  41.470s  |  41.470s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_18_0.smt2                                                     |  60.735s  |  60.735s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_28_0.smt2                                                     |  24.702s  |  24.702s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_38_0.smt2                                                     |   5.487s  |   5.487s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_48_0.smt2                                                     |  59.006s  |  59.006s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_58_0.smt2                                                     |  41.987s  |  41.987s  |   0.000s  | 0.0%|
|From_T2__hqr.t2__terminationS_68_0.smt2                                                     |  26.109s  |  26.109s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__p1737_terminationG_0.smt2                                            | 600.162s  | 600.162s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__term_unfeasibility_1_0.smt2                                          | 172.218s  | 172.218s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_27_0.smt2                                               |  36.197s  |  36.197s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_38_0.smt2                                               |  41.052s  |  41.052s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_48_0.smt2                                               |  43.154s  |  43.154s  |   0.000s  | 0.0%|
|From_T2__hqr.t2_fixed__terminationS_57_0.smt2                                               |  31.022s  |  31.022s  |   0.000s  | 0.0%|
|From_T2__insertsort.t2_fixed__p1846_terminationG_0.smt2                                     |   3.302s  |   3.302s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2024_terminationG_0.smt2                                        |  15.415s  |  15.415s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2040_terminationG_0.smt2                                        | 195.898s  | 195.898s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2099_terminationG_0.smt2                                        | 294.598s  | 294.598s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2132_terminationG_0.smt2                                        |  37.630s  |  37.630s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2157_terminationG_0.smt2                                        |  53.348s  |  53.348s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2182_terminationG_0.smt2                                        | 293.296s  | 293.296s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2214_terminationG_0.smt2                                        |   3.289s  |   3.289s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2230_terminationG_0.smt2                                        | 600.169s  | 600.169s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2254_terminationG_0.smt2                                        | 223.300s  | 223.300s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2__p2276_terminationG_0.smt2                                        |  40.975s  |  40.975s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__p1996_terminationG_0.smt2                                  | 600.166s  | 600.166s  |   0.000s  | 0.0%|
|From_T2__janne_complex.t2_fixed__terminationS_1_0.smt2                                      |   1.793s  |   1.793s  |   0.000s  | 0.0%|
|From_T2__java_DivMinus2.c.t2__p2415_terminationG_0.smt2                                     |  31.576s  |  31.576s  |   0.000s  | 0.0%|
|From_T2__java_Recursions.c.t2__p2534_terminationG_0.smt2                                    |   0.864s  |   0.864s  |   0.000s  | 0.0%|
|From_T2__loop3.t2__term_unfeasibility_39_0.smt2                                             |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|From_T2__matmult.t2__p2669_terminationG_0.smt2                                              |   2.259s  |   2.259s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2711_terminationG_0.smt2                                                 |  27.966s  |  27.966s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2764_terminationG_0.smt2                                                 |   4.030s  |   4.030s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2790_terminationG_0.smt2                                                 | 600.147s  | 600.147s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2810_terminationG_0.smt2                                                 |   1.857s  |   1.857s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2826_terminationG_0.smt2                                                 | 600.132s  | 600.132s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2842_terminationG_0.smt2                                                 |   3.465s  |   3.465s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2861_terminationG_0.smt2                                                 |   2.880s  |   2.880s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2877_terminationG_0.smt2                                                 |   3.589s  |   3.589s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2893_terminationG_0.smt2                                                 | 600.144s  | 600.144s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2911_terminationG_0.smt2                                                 |   3.501s  |   3.501s  |   0.000s  | 0.0%|
|From_T2__mc91.t2__p2932_edge_closing_0.smt2                                                 |   7.105s  |   7.105s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p2968_terminationG_0.smt2                                             |   3.519s  |   3.519s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3001_terminationG_0.smt2                                             |   5.175s  |   5.175s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3031_terminationG_0.smt2                                             |   2.919s  |   2.919s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3059_terminationG_0.smt2                                             | 411.865s  | 411.865s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3075_terminationG_0.smt2                                             | 600.511s  | 600.511s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3099_terminationG_0.smt2                                             |   4.501s  |   4.501s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3121_terminationG_0.smt2                                             |  48.024s  |  48.024s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3143_terminationG_0.smt2                                             | 600.283s  | 600.283s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3167_terminationG_0.smt2                                             |  17.732s  |  17.732s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3189_terminationG_0.smt2                                             |  70.720s  |  70.720s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3205_terminationG_0.smt2                                             | 600.335s  | 600.335s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3229_terminationG_0.smt2                                             |   2.643s  |   2.643s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3256_terminationG_0.smt2                                             |   4.262s  |   4.262s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3279_terminationG_0.smt2                                             | 600.445s  | 600.445s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3304_terminationG_0.smt2                                             |   3.113s  |   3.113s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3327_terminationG_0.smt2                                             |  55.534s  |  55.534s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3343_terminationG_0.smt2                                             |   3.925s  |   3.925s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3367_terminationG_0.smt2                                             |   5.620s  |   5.620s  |   0.000s  | 0.0%|
|From_T2__mc91test.t2__p3388_edge_closing_0.smt2                                             |   4.677s  |   4.677s  |   0.000s  | 0.0%|
|From_T2__n-1.t2__p3816_terminationG_0.smt2                                                  | 600.109s  | 600.109s  |   0.000s  | 0.0%|
|From_T2__n-12.t2__p3470_edge_closing_0.smt2                                                 |   0.925s  |   0.925s  |   0.000s  | 0.0%|
|From_T2__n-13.t2__p3488_terminationG_0.smt2                                                 |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|From_T2__n-15.t2__p3596_terminationG_0.smt2                                                 |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|From_T2__n-15a.t2__p3581_terminationG_0.smt2                                                |   4.951s  |   4.951s  |   0.000s  | 0.0%|
|From_T2__n-16a.t2__p3627_terminationG_0.smt2                                                | 600.099s  | 600.099s  |   0.000s  | 0.0%|
|From_T2__n-18.t2__p3712_terminationG_0.smt2                                                 |   0.757s  |   0.757s  |   0.000s  | 0.0%|
|From_T2__n-1c.t2__p3754_edge_closing_0.smt2                                                 |  35.360s  |  35.360s  |   0.000s  | 0.0%|
|From_T2__n-1d.t2_fixed__p3770_edge_closing_0.smt2                                           | 600.148s  | 600.148s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3885_terminationG_0.smt2                                                 | 600.144s  | 600.144s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3904_terminationG_0.smt2                                                 |   3.421s  |   3.421s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3920_terminationG_0.smt2                                                 |   3.716s  |   3.716s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3936_terminationG_0.smt2                                                 | 600.111s  | 600.111s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3954_terminationG_0.smt2                                                 |   1.652s  |   1.652s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3970_terminationG_0.smt2                                                 | 600.284s  | 600.284s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p3986_terminationG_0.smt2                                                 | 600.114s  | 600.114s  |   0.000s  | 0.0%|
|From_T2__n-21.t2__p4004_terminationG_0.smt2                                                 |   3.375s  |   3.375s  |   0.000s  | 0.0%|
|From_T2__n-21.t2_fixed__p3838_terminationG_0.smt2                                           | 600.135s  | 600.135s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4196_terminationG_0.smt2                                                  |   0.246s  |   0.246s  |   0.000s  | 0.0%|
|From_T2__n-3.t2__p4212_terminationG_0.smt2                                                  |   6.312s  |   6.312s  |   0.000s  | 0.0%|
|From_T2__n-33.t2__p4083_terminationG_0.smt2                                                 |   7.881s  |   7.881s  |   0.000s  | 0.0%|
|From_T2__n-37.t2__p4149_terminationG_0.smt2                                                 | 600.069s  | 600.069s  |   0.000s  | 0.0%|
|From_T2__n-3a.t2_fixed__p4168_edge_closing_0.smt2                                           | 600.107s  | 600.107s  |   0.000s  | 0.0%|
|From_T2__n-4.t2__p4556_edge_closing_0.smt2                                                  | 137.640s  | 137.640s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4267_terminationG_0.smt2                                                 |   2.424s  |   2.424s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4288_terminationG_0.smt2                                                 |   3.979s  |   3.979s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4304_terminationG_0.smt2                                                 | 600.214s  | 600.214s  |   0.000s  | 0.0%|
|From_T2__n-40.t2__p4322_edge_closing_0.smt2                                                 |   1.657s  |   1.657s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4233_terminationG_0.smt2                                           |   1.291s  |   1.291s  |   0.000s  | 0.0%|
|From_T2__n-40.t2_fixed__p4249_terminationG_0.smt2                                           |  22.476s  |  22.476s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4352_terminationG_0.smt2                                                 | 600.116s  | 600.116s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4370_terminationG_0.smt2                                                 |   3.102s  |   3.102s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4386_terminationG_0.smt2                                                 | 600.098s  | 600.098s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4403_terminationG_0.smt2                                                 | 628.945s  | 628.945s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4421_terminationG_0.smt2                                                 |   2.109s  |   2.109s  |   0.000s  | 0.0%|
|From_T2__n-46.t2__p4437_terminationG_0.smt2                                                 | 292.059s  | 292.059s  |   0.000s  | 0.0%|
|From_T2__n-48.t2__p4500_terminationG_0.smt2                                                 |   4.261s  |   4.261s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4656_terminationG_0.smt2                                                  |  59.730s  |  59.730s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4677_terminationG_0.smt2                                                  | 600.136s  | 600.136s  |   0.000s  | 0.0%|
|From_T2__n-5.t2__p4701_edge_closing_0.smt2                                                  |   1.758s  |   1.758s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4569_terminationG_0.smt2                                            |  16.733s  |  16.733s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4590_terminationG_0.smt2                                            | 618.474s  | 618.474s  |   0.000s  | 0.0%|
|From_T2__n-5.t2_fixed__p4609_edge_closing_0.smt2                                            |  18.051s  |  18.051s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4803_terminationG_0.smt2                                                  |   2.415s  |   2.415s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4819_terminationG_0.smt2                                                  | 600.070s  | 600.070s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4838_terminationG_0.smt2                                                  |   2.037s  |   2.037s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4854_terminationG_0.smt2                                                  |   3.932s  |   3.932s  |   0.000s  | 0.0%|
|From_T2__n-6.t2__p4866_edge_closing_0.smt2                                                  | 600.109s  | 600.109s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4771_terminationG_0.smt2                                            | 600.145s  | 600.145s  |   0.000s  | 0.0%|
|From_T2__n-6.t2_fixed__p4794_edge_closing_0.smt2                                            |   2.244s  |   2.244s  |   0.000s  | 0.0%|
|From_T2__n-6a.t2_fixed__p4722_safety_0.smt2                                                 | 602.824s  | 602.824s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p4999_terminationG_0.smt2                                                  | 264.370s  | 264.370s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5015_terminationG_0.smt2                                                  | 600.219s  | 600.219s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5034_terminationG_0.smt2                                                  |   3.825s  |   3.825s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5050_terminationG_0.smt2                                                  | 229.717s  | 229.717s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5066_terminationG_0.smt2                                                  | 600.154s  | 600.154s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5084_terminationG_0.smt2                                                  |   4.087s  |   4.087s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5100_terminationG_0.smt2                                                  | 600.143s  | 600.143s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5116_terminationG_0.smt2                                                  | 600.077s  | 600.077s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5134_terminationG_0.smt2                                                  |   1.401s  |   1.401s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5150_terminationG_0.smt2                                                  |   2.187s  |   2.187s  |   0.000s  | 0.0%|
|From_T2__n-7.t2__p5166_terminationG_0.smt2                                                  | 600.066s  | 600.066s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4887_terminationG_0.smt2                                            |   0.750s  |   0.750s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4903_terminationG_0.smt2                                            |   3.898s  |   3.898s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4919_terminationG_0.smt2                                            | 600.114s  | 600.114s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4938_terminationG_0.smt2                                            |   2.837s  |   2.837s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__p4954_terminationG_0.smt2                                            |   8.638s  |   8.638s  |   0.000s  | 0.0%|
|From_T2__n-7.t2_fixed__terminationQ_15_0.smt2                                               |   1.448s  |   1.448s  |   0.000s  | 0.0%|
|From_T2__n-9.t2__p5277_terminationG_0.smt2                                                  |   4.488s  |   4.488s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6187_terminationG_0.smt2                           | 600.391s  | 600.391s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6203_terminationG_0.smt2                           | 600.273s  | 600.273s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__p6221_edge_closing_0.smt2                           | 286.135s  | 286.135s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationQ_3_0.smt2                               |  13.112s  |  13.112s  |   0.000s  | 0.0%|
|From_T2__n_firewire_instrumented-PP.t2__terminationS_6_0.smt2                               |  26.974s  |  26.974s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5306_terminationG_0.smt2                                               | 600.291s  | 600.291s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5324_terminationG_0.smt2                                               | 258.823s  | 258.823s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5341_terminationG_0.smt2                                               | 600.411s  | 600.411s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__p5353_edge_closing_0.smt2                                               | 606.418s  | 606.418s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationQ_6_0.smt2                                                   |   2.734s  |   2.734s  |   0.000s  | 0.0%|
|From_T2__nakata.t2__terminationS_3_0.smt2                                                   |  24.228s  |  24.228s  |   0.000s  | 0.0%|
|From_T2__ndes.t2__p5373_terminationG_0.smt2                                                 |  23.789s  |  23.789s  |   0.000s  | 0.0%|
|From_T2__ndes.t2_fixed__term_unfeasibility_2_0.smt2                                         |   7.460s  |   7.460s  |   0.000s  | 0.0%|
|From_T2__neg-acqrel-fail.t2__p5620_terminationG_0.smt2                                      |   3.098s  |   3.098s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6235_terminationG_0.smt2                                             |   0.990s  |   0.990s  |   0.000s  | 0.0%|
|From_T2__non_term.t2__p6251_terminationG_0.smt2                                             | 600.105s  | 600.105s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6291_terminationG_0.smt2                                       |   6.394s  |   6.394s  |   0.000s  | 0.0%|
|From_T2__oct_vs_subpoly.t2__p6309_terminationG_0.smt2                                       |   3.600s  |   3.600s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__p6338_terminationG_0.smt2                                           |  11.479s  |  11.479s  |   0.000s  | 0.0%|
|From_T2__opt-tree.c.t2__terminationS_1_0.smt2                                               |   2.561s  |   2.561s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2__p6637_terminationG_0.smt2                                       |   3.562s  |   3.562s  |   0.000s  | 0.0%|
|From_T2__p-43-terminate.t2_fixed__p6628_terminationG_0.smt2                                 |   5.117s  |   5.117s  |   0.000s  | 0.0%|
|From_T2__p-46.t2__p6685_terminationG_0.smt2                                                 |  19.333s  |  19.333s  |   0.000s  | 0.0%|
|From_T2__p-5.t2__p6860_edge_closing_0.smt2                                                  |   3.381s  |   3.381s  |   0.000s  | 0.0%|
|From_T2__p-5.t2_fixed__p6778_terminationG_0.smt2                                            | 600.076s  | 600.076s  |   0.000s  | 0.0%|
|From_T2__p.t2__p8315_terminationG_0.smt2                                                    | 556.051s  | 556.051s  |   0.000s  | 0.0%|
|From_T2__p.t2__terminationS_3_0.smt2                                                        |   7.131s  |   7.131s  |   0.000s  | 0.0%|
|From_T2__p_armc.t2__p6954_edge_closing_0.smt2                                               | 600.274s  | 600.274s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p6980_terminationG_0.smt2                                             | 600.181s  | 600.181s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7002_edge_closing_0.smt2                                             | 600.196s  | 600.196s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7021_edge_closing_0.smt2                                             | 600.096s  | 600.096s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7043_edge_closing_0.smt2                                             |   5.184s  |   5.184s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7069_edge_closing_0.smt2                                             | 600.207s  | 600.207s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7100_edge_closing_0.smt2                                             | 600.171s  | 600.171s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7126_edge_closing_0.smt2                                             |   5.382s  |   5.382s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7145_edge_closing_0.smt2                                             | 600.145s  | 600.145s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7164_edge_closing_0.smt2                                             | 601.327s  | 601.327s  |   0.000s  | 0.0%|
|From_T2__pentagon.t2__p7186_edge_closing_0.smt2                                             |  15.985s  |  15.985s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7265_terminationG_0.smt2                                               |   2.306s  |   2.306s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2__p7297_terminationG_0.smt2                                               | 600.370s  | 600.370s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__p7218_edge_closing_0.smt2                                         | 600.588s  | 600.588s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_16_0.smt2                                            |  16.279s  |  16.279s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_25_0.smt2                                            |  15.203s  |  15.203s  |   0.000s  | 0.0%|
|From_T2__pgarch.t2_fixed__terminationS_3_0.smt2                                             |  13.111s  |  13.111s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2__term_unfeasibility_0_0.smt2                                        |  12.497s  |  12.497s  |   0.000s  | 0.0%|
|From_T2__polling.bug.t2_fixed__term_unfeasibility_1_0.smt2                                  |  18.036s  |  18.036s  |   0.000s  | 0.0%|
|From_T2__polling.t2_fixed__p7336_terminationG_0.smt2                                        | 600.657s  | 600.657s  |   0.000s  | 0.0%|
|From_T2__polyrank2.t2__p7393_terminationG_0.smt2                                            |   0.702s  |   0.702s  |   0.000s  | 0.0%|
|From_T2__polyrank3.t2__p7436_terminationG_0.smt2                                            |   4.223s  |   4.223s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7472_terminationG_0.smt2                                            |  61.717s  |  61.717s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7499_terminationG_0.smt2                                            |   3.117s  |   3.117s  |   0.000s  | 0.0%|
|From_T2__polyrank4.t2__p7519_terminationG_0.smt2                                            |   3.045s  |   3.045s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7550_terminationG_0.smt2                                            |   2.113s  |   2.113s  |   0.000s  | 0.0%|
|From_T2__polyrank5.t2__p7566_terminationG_0.smt2                                            | 600.159s  | 600.159s  |   0.000s  | 0.0%|
|From_T2__polyrank6.t2__p7590_terminationG_0.smt2                                            |   2.196s  |   2.196s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7691_terminationG_0.smt2                                              |   0.482s  |   0.482s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7707_terminationG_0.smt2                                              |  12.233s  |  12.233s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7723_terminationG_0.smt2                                              | 600.164s  | 600.164s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7742_edge_closing_0.smt2                                              | 167.765s  | 167.765s  |   0.000s  | 0.0%|
|From_T2__ppblock.t2__p7759_edge_closing_0.smt2                                              | 600.059s  | 600.059s  |   0.000s  | 0.0%|
|From_T2__ppblockbug.t2__p7669_terminationG_0.smt2                                           |   1.056s  |   1.056s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7856_terminationG_0.smt2                                          |  17.308s  |  17.308s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7872_terminationG_0.smt2                                          | 600.135s  | 600.135s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7890_terminationG_0.smt2                                          |   2.571s  |   2.571s  |   0.000s  | 0.0%|
|From_T2__ppblockterm.t2__p7907_edge_closing_0.smt2                                          |   7.833s  |   7.833s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7777_terminationG_0.smt2                                       |  13.531s  |  13.531s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7793_terminationG_0.smt2                                       | 600.056s  | 600.056s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7811_terminationG_0.smt2                                       |   4.008s  |   4.008s  |   0.000s  | 0.0%|
|From_T2__ppblocktermbug.t2__p7828_edge_closing_0.smt2                                       |  13.135s  |  13.135s  |   0.000s  | 0.0%|
|From_T2__prime.t2__p8294_terminationG_0.smt2                                                |   4.225s  |   4.225s  |   0.000s  | 0.0%|
|From_T2__qrdcmp.c.i.qrdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |   2.853s  |   2.853s  |   0.000s  | 0.0%|
|From_T2__queens.t2__p8372_terminationG_0.smt2                                               |   2.625s  |   2.625s  |   0.000s  | 0.0%|
|From_T2__queens.t2_fixed__p8358_terminationG_0.smt2                                         | 531.480s  | 531.480s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8420_terminationG_0.smt2                                           |   6.148s  |   6.148s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8440_terminationG_0.smt2                                           | 600.081s  | 600.081s  |   0.000s  | 0.0%|
|From_T2__randomwalk.t2__p8459_edge_closing_0.smt2                                           |   1.382s  |   1.382s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2__p8550_terminationG_0.smt2                                  |   4.702s  |   4.702s  |   0.000s  | 0.0%|
|From_T2__refine_disj_problem.t2_fixed__p8508_terminationG_0.smt2                            |   3.248s  |   3.248s  |   0.000s  | 0.0%|
|From_T2__rev_nt2.t2_fixed__p8634_safety_0.smt2                                              | 600.120s  | 600.120s  |   0.000s  | 0.0%|
|From_T2__reverse_div4.t2__p8604_safety_0.smt2                                               |   3.851s  |   3.851s  |   0.000s  | 0.0%|
|From_T2__reverse_seg_cyclic.t2_fixed__term_unfeasibility_2_0.smt2                           |   3.000s  |   3.000s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8744_terminationG_0.smt2                          |   2.034s  |   2.034s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8764_terminationG_0.smt2                          | 600.464s  | 600.464s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8813_terminationG_0.smt2                          |  10.574s  |  10.574s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8833_terminationG_0.smt2                          | 600.368s  | 600.368s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8853_terminationG_0.smt2                          | 600.540s  | 600.540s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8875_terminationG_0.smt2                          |   8.304s  |   8.304s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8895_terminationG_0.smt2                          | 600.254s  | 600.254s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8915_terminationG_0.smt2                          | 600.558s  | 600.558s  |   0.000s  | 0.0%|
|From_T2__rlft3.c.i.rlft3.pl.t2.fixed.t2__p8941_terminationG_0.smt2                          |   1.664s  |   1.664s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9006_terminationG_0.smt2                                                | 600.281s  | 600.281s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9044_terminationG_0.smt2                                                |   8.570s  |   8.570s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9061_terminationG_0.smt2                                                | 600.324s  | 600.324s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9095_terminationG_0.smt2                                                |  10.695s  |  10.695s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9111_terminationG_0.smt2                                                | 600.473s  | 600.473s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9127_terminationG_0.smt2                                                | 600.419s  | 600.419s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9145_terminationG_0.smt2                                                |   8.726s  |   8.726s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9161_terminationG_0.smt2                                                | 600.333s  | 600.333s  |   0.000s  | 0.0%|
|From_T2__rlft3.t2__p9177_terminationG_0.smt2                                                | 600.434s  | 600.434s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9200_terminationG_0.smt2                          | 600.232s  | 600.232s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9218_terminationG_0.smt2                          |  10.880s  |  10.880s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9234_terminationG_0.smt2                          | 600.183s  | 600.183s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9252_edge_closing_0.smt2                          |  10.876s  |  10.876s  |   0.000s  | 0.0%|
|From_T2__ruslan-benchmarks_misc_n-38.t2__p9264_edge_closing_0.smt2                          |   5.400s  |   5.400s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12025_terminationG_0.smt2                                          | 223.084s  | 223.084s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12349_safety_0.smt2                                                | 600.093s  | 600.093s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12568_safety_0.smt2                                                | 600.136s  | 600.136s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12752_safety_0.smt2                                                |   4.332s  |   4.332s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12812_safety_0.smt2                                                |   3.526s  |   3.526s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12904_safety_0.smt2                                                |  43.702s  |  43.702s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12942_safety_0.smt2                                                |   5.009s  |   5.009s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p12976_safety_0.smt2                                                |   5.327s  |   5.327s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13058_safety_0.smt2                                                | 600.134s  | 600.134s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13097_safety_0.smt2                                                |   3.529s  |   3.529s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13135_safety_0.smt2                                                |   0.538s  |   0.538s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13195_safety_0.smt2                                                | 600.148s  | 600.148s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13216_safety_0.smt2                                                |   0.562s  |   0.562s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13288_safety_0.smt2                                                | 600.097s  | 600.097s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13336_safety_0.smt2                                                | 600.059s  | 600.059s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13467_safety_0.smt2                                                | 131.923s  | 131.923s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13547_safety_0.smt2                                                |   4.378s  |   4.378s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13600_safety_0.smt2                                                |  35.512s  |  35.512s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13677_safety_0.smt2                                                |   4.595s  |   4.595s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13711_safety_0.smt2                                                | 600.069s  | 600.069s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13759_safety_0.smt2                                                |   5.346s  |   5.346s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13813_safety_0.smt2                                                |   6.198s  |   6.198s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13843_safety_0.smt2                                                |   0.856s  |   0.856s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13884_safety_0.smt2                                                | 600.052s  | 600.052s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p13960_safety_0.smt2                                                |   6.716s  |   6.716s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14001_safety_0.smt2                                                |  31.408s  |  31.408s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14138_safety_0.smt2                                                |   8.276s  |   8.276s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14171_safety_0.smt2                                                |   9.550s  |   9.550s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14256_safety_0.smt2                                                |   4.245s  |   4.245s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14281_safety_0.smt2                                                | 489.185s  | 489.185s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14353_safety_0.smt2                                                |   4.458s  |   4.458s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14371_safety_0.smt2                                                | 600.138s  | 600.138s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14418_safety_0.smt2                                                |   0.970s  |   0.970s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14431_safety_0.smt2                                                |   0.739s  |   0.739s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14737_safety_0.smt2                                                |  10.882s  |  10.882s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14919_safety_0.smt2                                                | 600.101s  | 600.101s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p14996_safety_0.smt2                                                | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__p15078_safety_0.smt2                                                |   2.632s  |   2.632s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2__term_unfeasibility_1_0.smt2                                         |   7.959s  |   7.959s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10066_safety_0.smt2                                          |   3.859s  |   3.859s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10133_safety_0.smt2                                          |   0.338s  |   0.338s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10168_safety_0.smt2                                          | 600.118s  | 600.118s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10216_safety_0.smt2                                          | 600.159s  | 600.159s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10273_safety_0.smt2                                          |   2.934s  |   2.934s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10316_safety_0.smt2                                          |   2.650s  |   2.650s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10430_safety_0.smt2                                          |   8.337s  |   8.337s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10512_safety_0.smt2                                          |   3.069s  |   3.069s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10555_safety_0.smt2                                          |   3.819s  |   3.819s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10604_safety_0.smt2                                          |  16.740s  |  16.740s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10632_safety_0.smt2                                          |  29.611s  |  29.611s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10685_safety_0.smt2                                          |   0.977s  |   0.977s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10708_safety_0.smt2                                          |   0.913s  |   0.913s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10737_safety_0.smt2                                          |   2.439s  |   2.439s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10777_safety_0.smt2                                          | 600.178s  | 600.178s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10804_safety_0.smt2                                          | 600.064s  | 600.064s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10907_safety_0.smt2                                          |   6.594s  |   6.594s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p10987_safety_0.smt2                                          |   1.079s  |   1.079s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11010_safety_0.smt2                                          |   4.965s  |   4.965s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11070_safety_0.smt2                                          |   0.892s  |   0.892s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11092_safety_0.smt2                                          |   1.144s  |   1.144s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11134_safety_0.smt2                                          | 600.160s  | 600.160s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11206_safety_0.smt2                                          |   7.423s  |   7.423s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11249_safety_0.smt2                                          |   6.596s  |   6.596s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11279_safety_0.smt2                                          | 600.056s  | 600.056s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11293_safety_0.smt2                                          | 600.129s  | 600.129s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11660_safety_0.smt2                                          | 600.083s  | 600.083s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11700_safety_0.smt2                                          | 600.106s  | 600.106s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11816_safety_0.smt2                                          |   3.739s  |   3.739s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11854_safety_0.smt2                                          |   0.741s  |   0.741s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p11971_safety_0.smt2                                          | 188.015s  | 188.015s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9297_terminationG_0.smt2                                     |  16.218s  |  16.218s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9315_terminationG_0.smt2                                     |  84.941s  |  84.941s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9567_safety_0.smt2                                           |   4.910s  |   4.910s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9728_safety_0.smt2                                           | 600.089s  | 600.089s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9772_safety_0.smt2                                           | 631.763s  | 631.763s  |   0.000s  | 0.0%|
|From_T2__s1-striped.t2_fixed__p9943_safety_0.smt2                                           |   4.363s  |   4.363s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p17926_terminationG_0.smt2                                                  | 510.971s  | 510.971s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18239_safety_0.smt2                                                        |   3.729s  |   3.729s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18399_safety_0.smt2                                                        |   0.541s  |   0.541s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18422_safety_0.smt2                                                        | 600.071s  | 600.071s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18691_safety_0.smt2                                                        |   9.220s  |   9.220s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18716_safety_0.smt2                                                        |  13.360s  |  13.360s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18741_safety_0.smt2                                                        | 600.102s  | 600.102s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18830_safety_0.smt2                                                        |   4.331s  |   4.331s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18864_safety_0.smt2                                                        | 600.192s  | 600.192s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18901_safety_0.smt2                                                        |   0.515s  |   0.515s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p18964_safety_0.smt2                                                        |  16.263s  |  16.263s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19014_safety_0.smt2                                                        | 600.103s  | 600.103s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19051_safety_0.smt2                                                        |   0.620s  |   0.620s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19123_safety_0.smt2                                                        | 264.421s  | 264.421s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19160_safety_0.smt2                                                        | 600.171s  | 600.171s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19287_safety_0.smt2                                                        |   9.446s  |   9.446s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19317_safety_0.smt2                                                        |  10.087s  |  10.087s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19424_safety_0.smt2                                                        |   5.913s  |   5.913s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19467_safety_0.smt2                                                        |   1.462s  |   1.462s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19523_safety_0.smt2                                                        |   3.224s  |   3.224s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19576_safety_0.smt2                                                        |   4.442s  |   4.442s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19619_safety_0.smt2                                                        |   4.664s  |   4.664s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19670_safety_0.smt2                                                        |   0.794s  |   0.794s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19702_safety_0.smt2                                                        | 600.084s  | 600.084s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19772_safety_0.smt2                                                        |   4.192s  |   4.192s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19829_safety_0.smt2                                                        |   4.490s  |   4.490s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19894_safety_0.smt2                                                        |   0.817s  |   0.817s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p19953_safety_0.smt2                                                        |   3.918s  |   3.918s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20015_safety_0.smt2                                                        | 600.071s  | 600.071s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20088_safety_0.smt2                                                        | 600.109s  | 600.109s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20147_safety_0.smt2                                                        |   4.329s  |   4.329s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20179_safety_0.smt2                                                        | 600.070s  | 600.070s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20227_safety_0.smt2                                                        |  16.950s  |  16.950s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20268_safety_0.smt2                                                        |   1.252s  |   1.252s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20287_safety_0.smt2                                                        |   0.442s  |   0.442s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20628_safety_0.smt2                                                        |   3.409s  |   3.409s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20781_safety_0.smt2                                                        | 600.077s  | 600.077s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p20857_safety_0.smt2                                                        | 607.580s  | 607.580s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21013_safety_0.smt2                                                        |   4.227s  |   4.227s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21118_safety_0.smt2                                                        | 600.098s  | 600.098s  |   0.000s  | 0.0%|
|From_T2__s1.t2__p21153_safety_0.smt2                                                        | 600.078s  | 600.078s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15164_terminationG_0.smt2                                            | 269.676s  | 269.676s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15180_terminationG_0.smt2                                            |  27.626s  |  27.626s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15597_safety_0.smt2                                                  | 600.112s  | 600.112s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15640_safety_0.smt2                                                  | 600.074s  | 600.074s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p15883_safety_0.smt2                                                  |  63.180s  |  63.180s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16042_safety_0.smt2                                                  | 600.058s  | 600.058s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16093_safety_0.smt2                                                  | 600.107s  | 600.107s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16158_safety_0.smt2                                                  |   2.940s  |   2.940s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16485_safety_0.smt2                                                  |   0.702s  |   0.702s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16526_safety_0.smt2                                                  |   4.751s  |   4.751s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16586_safety_0.smt2                                                  |   1.318s  |   1.318s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16626_safety_0.smt2                                                  |   6.097s  |   6.097s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16656_safety_0.smt2                                                  |   1.001s  |   1.001s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16834_safety_0.smt2                                                  | 600.070s  | 600.070s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16901_safety_0.smt2                                                  |   0.677s  |   0.677s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p16947_safety_0.smt2                                                  |   2.705s  |   2.705s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17067_safety_0.smt2                                                  |   4.162s  |   4.162s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17133_safety_0.smt2                                                  |   4.408s  |   4.408s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17167_safety_0.smt2                                                  | 600.132s  | 600.132s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17181_safety_0.smt2                                                  | 600.073s  | 600.073s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17590_safety_0.smt2                                                  |   0.523s  |   0.523s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17686_safety_0.smt2                                                  |   8.123s  |   8.123s  |   0.000s  | 0.0%|
|From_T2__s1.t2_fixed__p17765_safety_0.smt2                                                  |   2.744s  |   2.744s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21288_terminationG_0.smt2                                                | 600.672s  | 600.672s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__p21305_terminationG_0.smt2                                                |  64.878s  |  64.878s  |   0.000s  | 0.0%|
|From_T2__sas2.t2__terminationQ_1_0.smt2                                                     |   7.150s  |   7.150s  |   0.000s  | 0.0%|
|From_T2__select.t2__p21345_terminationG_0.smt2                                              | 168.149s  | 168.149s  |   0.000s  | 0.0%|
|From_T2__simple.t2__p21460_terminationG_0.smt2                                              |   0.320s  |   0.320s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21513_terminationG_0.smt2                                   | 600.168s  | 600.168s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21529_terminationG_0.smt2                                   | 600.252s  | 600.252s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21547_terminationG_0.smt2                                   |   1.422s  |   1.422s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21563_terminationG_0.smt2                                   |   4.116s  |   4.116s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21579_terminationG_0.smt2                                   | 600.308s  | 600.308s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21597_terminationG_0.smt2                                   |   1.761s  |   1.761s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21613_terminationG_0.smt2                                   | 600.181s  | 600.181s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21629_terminationG_0.smt2                                   | 600.243s  | 600.243s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21647_terminationG_0.smt2                                   |   2.411s  |   2.411s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21663_terminationG_0.smt2                                   | 600.141s  | 600.141s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21681_safety_0.smt2                                         | 600.114s  | 600.114s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21714_safety_0.smt2                                         |   8.035s  |   8.035s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21738_safety_0.smt2                                         |   5.826s  |   5.826s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21762_safety_0.smt2                                         |   5.072s  |   5.072s  |   0.000s  | 0.0%|
|From_T2__slayer-3-filtered.t2__p21786_safety_0.smt2                                         | 600.245s  | 600.245s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21887_terminationG_0.smt2                                        |   1.259s  |   1.259s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21904_terminationG_0.smt2                                        | 600.299s  | 600.299s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21920_terminationG_0.smt2                                        |   2.559s  |   2.559s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21938_terminationG_0.smt2                                        |   7.934s  |   7.934s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21954_terminationG_0.smt2                                        | 608.143s  | 608.143s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21970_terminationG_0.smt2                                        | 600.322s  | 600.322s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p21988_terminationG_0.smt2                                        |   1.827s  |   1.827s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22004_terminationG_0.smt2                                        | 600.269s  | 600.269s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22040_safety_0.smt2                                              |   4.217s  |   4.217s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22063_safety_0.smt2                                              |   3.457s  |   3.457s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2__p22104_safety_0.smt2                                              |   1.852s  |   1.852s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21801_terminationG_0.smt2                                  |  23.862s  |  23.862s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21832_safety_0.smt2                                        |   8.713s  |   8.713s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__p21855_safety_0.smt2                                        |   3.880s  |   3.880s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_1_0.smt2                                       |  10.518s  |  10.518s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_29_0.smt2                                      |  38.581s  |  38.581s  |   0.000s  | 0.0%|
|From_T2__slayer-3-new.t2_fixed__terminationS_39_0.smt2                                      |  15.775s  |  15.775s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22188_terminationG_0.smt2                                            |   8.341s  |   8.341s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22206_terminationG_0.smt2                                            | 600.096s  | 600.096s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22223_terminationG_0.smt2                                            | 600.289s  | 600.289s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22243_terminationG_0.smt2                                            |   2.205s  |   2.205s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22262_terminationG_0.smt2                                            | 600.216s  | 600.216s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22280_terminationG_0.smt2                                            | 600.307s  | 600.307s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22301_terminationG_0.smt2                                            |   2.045s  |   2.045s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22317_terminationG_0.smt2                                            | 600.292s  | 600.292s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22348_safety_0.smt2                                                  | 600.090s  | 600.090s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22367_safety_0.smt2                                                  |   6.479s  |   6.479s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2__p22398_safety_0.smt2                                                  | 600.093s  | 600.093s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22141_safety_0.smt2                                            |   2.480s  |   2.480s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__p22165_safety_0.smt2                                            | 600.092s  | 600.092s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_13_0.smt2                                          |  19.172s  |  19.172s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_22_0.smt2                                          |  15.548s  |  15.548s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_32_0.smt2                                          |  15.541s  |  15.541s  |   0.000s  | 0.0%|
|From_T2__slayer-3.t2_fixed__terminationS_6_0.smt2                                           |  15.402s  |  15.402s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22442_terminationG_0.smt2                                   |   6.616s  |   6.616s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22466_safety_0.smt2                                         | 600.074s  | 600.074s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22485_terminationG_0.smt2                                   | 600.209s  | 600.209s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22506_safety_0.smt2                                         |  13.711s  |  13.711s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22534_terminationG_0.smt2                                   |   2.158s  |   2.158s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22554_safety_0.smt2                                         | 190.053s  | 190.053s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22580_terminationG_0.smt2                                   |   7.120s  |   7.120s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22597_safety_0.smt2                                         |   4.541s  |   4.541s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22618_safety_0.smt2                                         |   4.025s  |   4.025s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22647_safety_0.smt2                                         |  10.027s  |  10.027s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22668_safety_0.smt2                                         | 467.130s  | 467.130s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22693_safety_0.smt2                                         |   6.646s  |   6.646s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__p22710_safety_0.smt2                                         |   5.172s  |   5.172s  |   0.000s  | 0.0%|
|From_T2__slayer-4-filtered.t2__terminationS_3_0.smt2                                        |   7.152s  |   7.152s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22746_terminationG_0.smt2                                   |   3.849s  |   3.849s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22780_safety_0.smt2                                         | 600.131s  | 600.131s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22796_safety_0.smt2                                         |   4.883s  |   4.883s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22827_terminationG_0.smt2                                   |   7.123s  |   7.123s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22860_terminationG_0.smt2                                   |   6.647s  |   6.647s  |   0.000s  | 0.0%|
|From_T2__slayer-5-filtered.t2__p22891_terminationG_0.smt2                                   | 600.104s  | 600.104s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2__p23156_terminationG_0.smt2                                           | 600.114s  | 600.114s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22950_safety_0.smt2                                           | 600.112s  | 600.112s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22972_safety_0.smt2                                           | 600.291s  | 600.291s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p22991_safety_0.smt2                                           |   1.853s  |   1.853s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23010_safety_0.smt2                                           | 600.088s  | 600.088s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23057_safety_0.smt2                                           | 600.107s  | 600.107s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23091_safety_0.smt2                                           |   5.968s  |   5.968s  |   0.000s  | 0.0%|
|From_T2__slayer-n1.t2_fixed__p23107_safety_0.smt2                                           | 600.164s  | 600.164s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23173_terminationG_0.smt2                                  |   0.838s  |   0.838s  |   0.000s  | 0.0%|
|From_T2__slayer-n2-filtered.t2__p23194_terminationG_0.smt2                                  |   3.725s  |   3.725s  |   0.000s  | 0.0%|
|From_T2__slayer-n2.t2__p23222_terminationG_0.smt2                                           |   2.819s  |   2.819s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23267_safety_0.smt2                                        |   1.408s  |   1.408s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23305_safety_0.smt2                                        |   2.472s  |   2.472s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23340_safety_0.smt2                                        |   2.717s  |   2.717s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23379_safety_0.smt2                                        |   6.622s  |   6.622s  |   0.000s  | 0.0%|
|From_T2__slayer-n5-filtered.t2__p23413_safety_0.smt2                                        |   3.321s  |   3.321s  |   0.000s  | 0.0%|
|From_T2__small01.t2__p23469_terminationG_0.smt2                                             | 600.107s  | 600.107s  |   0.000s  | 0.0%|
|From_T2__small01.t2__terminationQ_3_0.smt2                                                  |   6.722s  |   6.722s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23517_terminationG_0.smt2                                             |   1.732s  |   1.732s  |   0.000s  | 0.0%|
|From_T2__small03.t2__p23533_terminationG_0.smt2                                             |   3.061s  |   3.061s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23554_terminationG_0.smt2                                             |   4.321s  |   4.321s  |   0.000s  | 0.0%|
|From_T2__small04.t2__p23571_terminationG_0.smt2                                             |  59.283s  |  59.283s  |   0.000s  | 0.0%|
|From_T2__small05.t2__p23592_terminationG_0.smt2                                             | 600.084s  | 600.084s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23679_terminationG_0.smt2                                             |   0.854s  |   0.854s  |   0.000s  | 0.0%|
|From_T2__small14.t2__p23695_terminationG_0.smt2                                             | 600.157s  | 600.157s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23750_terminationG_0.smt2                                             |   4.157s  |   4.157s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23766_terminationG_0.smt2                                             |  18.291s  |  18.291s  |   0.000s  | 0.0%|
|From_T2__small15.t2__p23788_edge_closing_0.smt2                                             | 600.093s  | 600.093s  |   0.000s  | 0.0%|
|From_T2__small16.t2__p23821_edge_closing_0.smt2                                             |   7.384s  |   7.384s  |   0.000s  | 0.0%|
|From_T2__small18.t2__p23872_edge_closing_0.smt2                                             |   0.794s  |   0.794s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p23984_terminationG_0.smt2                                             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24000_terminationG_0.smt2                                             |   6.900s  |   6.900s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24016_terminationG_0.smt2                                             | 646.631s  | 646.631s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24034_terminationG_0.smt2                                             |   3.769s  |   3.769s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24050_terminationG_0.smt2                                             |  15.145s  |  15.145s  |   0.000s  | 0.0%|
|From_T2__small35.t2__p24066_terminationG_0.smt2                                             | 607.627s  | 607.627s  |   0.000s  | 0.0%|
|From_T2__spctrm.c.i.spctrm.pl.t2.fixed.t2__term_unfeasibility_10_0.smt2                     |   3.469s  |   3.469s  |   0.000s  | 0.0%|
|From_T2__spctrm.t2__term_unfeasibility_5_0.smt2                                             |   9.471s  |   9.471s  |   0.000s  | 0.0%|
|From_T2__spiral.t2__p24127_edge_closing_0.smt2                                              | 600.182s  | 600.182s  |   0.000s  | 0.0%|
|From_T2__st88.bug.t2_fixed__p24181_terminationG_0.smt2                                      | 600.131s  | 600.131s  |   0.000s  | 0.0%|
|From_T2__st88b-fail.t2__p24138_terminationG_0.smt2                                          |   2.350s  |   2.350s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24621_terminationG_0.smt2                                | 633.250s  | 633.250s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24667_terminationG_0.smt2                                | 600.268s  | 600.268s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24703_terminationG_0.smt2                                |   3.570s  |   3.570s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24720_terminationG_0.smt2                                | 600.291s  | 600.291s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24737_terminationG_0.smt2                                | 600.460s  | 600.460s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24755_terminationG_0.smt2                                |  22.125s  |  22.125s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24771_terminationG_0.smt2                                | 600.188s  | 600.188s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24787_terminationG_0.smt2                                | 600.547s  | 600.547s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24810_terminationG_0.smt2                                |   3.796s  |   3.796s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2__p24825_edge_closing_0.smt2                                |  18.819s  |  18.819s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__p24587_edge_closing_0.smt2                          | 600.134s  | 600.134s  |   0.000s  | 0.0%|
|From_T2__streamserver-succeed.t2_fixed__terminationS_25_0.smt2                              |   8.465s  |   8.465s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2__terminationS_0_0.smt2                                         |   4.420s  |   4.420s  |   0.000s  | 0.0%|
|From_T2__streamserver.bug.t2_fixed__terminationS_2_0.smt2                                   |   2.617s  |   2.617s  |   0.000s  | 0.0%|
|From_T2__sudoku.t2__p24872_terminationG_0.smt2                                              | 600.486s  | 600.486s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__p24898_edge_closing_0.smt2                       | 600.210s  | 600.210s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__term_unfeasibility_1_0.smt2                      |  11.048s  |  11.048s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_0_0.smt2                            |  16.618s  |  16.618s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_19_0.smt2                           |  21.220s  |  21.220s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_28_0.smt2                           |  32.391s  |  32.391s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_37_0.smt2                           |  82.675s  |  82.675s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_47_0.smt2                           |  27.521s  |  27.521s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.fixed.t2__terminationS_56_0.smt2                           |  18.158s  |  18.158s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__fixed_safety_0_0.smt2                  |   5.753s  |   5.753s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__p24940_edge_closing_0.smt2             | 600.259s  | 600.259s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_11_0.smt2                 |  43.721s  |  43.721s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_20_0.smt2                 |   3.489s  |   3.489s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                  |  19.414s  |  19.414s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_39_0.smt2                 |  22.051s  |  22.051s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_48_0.smt2                 |  33.007s  |  33.007s  |   0.000s  | 0.0%|
|From_T2__svdcmp.c.i.svdcmp.pl.t2.nor.t2.rlgfixed.t2__terminationS_57_0.smt2                 |  23.847s  |  23.847s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2__term_unfeasibility_10_0.smt2                                            |  42.628s  |  42.628s  |   0.000s  | 0.0%|
|From_T2__svdcmp.t2_fixed__term_unfeasibility_10_0.smt2                                      |  10.521s  |  10.521s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25005_terminationG_0.smt2                           | 601.875s  | 601.875s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25030_terminationG_0.smt2                           | 600.653s  | 600.653s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__p25050_edge_closing_0.smt2                           |  84.773s  |  84.773s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.fixed.t2__term_unfeasibility_2_0.smt2                          |  13.370s  |  13.370s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25078_terminationG_0.smt2                 | 600.484s  | 600.484s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__p25099_edge_closing_0.smt2                 | 600.237s  | 600.237s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__term_unfeasibility_1_0.smt2                |  11.995s  |  11.995s  |   0.000s  | 0.0%|
|From_T2__tqli.c.i.tqli.pl.t2.nor.t2.rlgfixed.t2__terminationS_2_0.smt2                      |   9.799s  |   9.799s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25231_terminationG_0.smt2                                                | 600.276s  | 600.276s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__p25267_edge_closing_0.smt2                                                | 276.631s  | 276.631s  |   0.000s  | 0.0%|
|From_T2__tqli.t2__terminationQ_2_0.smt2                                                     |  11.941s  |  11.941s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25131_terminationG_0.smt2                                          |  22.487s  |  22.487s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25153_terminationG_0.smt2                                          | 600.945s  | 600.945s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25176_terminationG_0.smt2                                          | 600.718s  | 600.718s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__p25199_edge_closing_0.smt2                                          | 600.194s  | 600.194s  |   0.000s  | 0.0%|
|From_T2__tqli.t2_fixed__terminationQ_2_0.smt2                                               |  10.691s  |  10.691s  |   0.000s  | 0.0%|
|From_T2__ud.t2__p25362_terminationG_0.smt2                                                  |  15.721s  |  15.721s  |   0.000s  | 0.0%|
|From_T2__w2_nt.t2__p25384_safety_0.smt2                                                     | 600.077s  | 600.077s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25539_terminationG_0.smt2                                                |   1.608s  |   1.608s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25562_terminationG_0.smt2                                                | 225.123s  | 225.123s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25580_terminationG_0.smt2                                                | 600.187s  | 600.187s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25598_terminationG_0.smt2                                                |   1.494s  |   1.494s  |   0.000s  | 0.0%|
|From_T2__walk.t2__p25613_edge_closing_0.smt2                                                |   4.922s  |   4.922s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25648_terminationG_0.smt2                                            |  10.848s  |  10.848s  |   0.000s  | 0.0%|
|From_T2__weakness.t2__p25671_terminationG_0.smt2                                            | 101.776s  | 101.776s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2__p25728_terminationG_0.smt2                                          |   4.426s  |   4.426s  |   0.000s  | 0.0%|
|From_T2__wrong_loop.t2_fixed__p25712_edge_closing_0.smt2                                    |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__p25773_terminationG_0.smt2                                            |  28.967s  |  28.967s  |   0.000s  | 0.0%|
|From_T2__zeroconf.t2__terminationS_2_0.smt2                                                 |   3.454s  |   3.454s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25903_terminationG_0.smt2                                      |   3.092s  |   3.092s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p25952_safety_0.smt2                                            |   1.430s  |   1.430s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26007_safety_0.smt2                                            |   2.160s  |   2.160s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26045_safety_0.smt2                                            |   8.507s  |   8.507s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26088_safety_0.smt2                                            |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26143_safety_0.smt2                                            | 600.076s  | 600.076s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26165_terminationG_0.smt2                                      | 600.176s  | 600.176s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26214_safety_0.smt2                                            |   5.120s  |   5.120s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26281_safety_0.smt2                                            |   1.907s  |   1.907s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26305_terminationG_0.smt2                                      | 600.070s  | 600.070s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2__p26355_safety_0.smt2                                            |   0.769s  |   0.769s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25815_safety_0.smt2                                      |   3.348s  |   3.348s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__p25859_safety_0.smt2                                      |   0.436s  |   0.436s  |   0.000s  | 0.0%|
|From_T2__zlib-adler32.c.t2_fixed__terminationS_0_0.smt2                                     |   1.534s  |   1.534s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26457_safety_0.smt2                                       | 136.336s  | 136.336s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26484_terminationG_0.smt2                                 | 600.119s  | 600.119s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26531_safety_0.smt2                                       |   2.652s  |   2.652s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2__p26555_edge_closing_0.smt2                                 |  47.400s  |  47.400s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32-BYFOUR.c.t2_fixed__p26393_terminationG_0.smt2                           |   4.596s  |   4.596s  |   0.000s  | 0.0%|
|From_T2__zlib-crc32.c.t2__p26616_edge_closing_0.smt2                                        | 251.278s  | 251.278s  |   0.000s  | 0.0%|
|Hanoi_plus_false-termination.c_Iteration1_Lasso+nonterminationTemplate_0.smt2               |   2.577s  |   2.577s  |   0.000s  | 0.0%|
|PastaA6_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|PastaC7_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                    |   1.810s  |   1.810s  |   0.000s  | 0.0%|
|Pure3Phase_true-termination.c_Iteration5_Loop+nonterminationTemplate_0.smt2                 |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20212_terminationG_0.smt2           | 600.228s  | 600.228s  |   0.000s  | 0.0%|
|Stroeder_15__4NestedWith3Variables_true-termination.c__p20216_terminationG_0.smt2           | 600.120s  | 600.120s  |   0.000s  | 0.0%|
|Stroeder_15__AlternKonv.c__p20685_terminationG_0.smt2                                       |  14.277s  |  14.277s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex2.02_false-termination.c__p21028_terminationG_0.smt2  | 600.075s  | 600.075s  |   0.000s  | 0.0%|
|Stroeder_15__ChenFlurMukhopadhyay-SAS2012-Ex3.02_false-termination.c__p21749_edge_closing_0.smt2  |  11.241s  |  11.241s  |   0.000s  | 0.0%|
|Stroeder_15__Choose.c__p22179_terminationG_0.smt2                                           | 607.307s  | 607.307s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22342_terminationG_0.smt2                                      | 600.073s  | 600.073s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22350_terminationG_0.smt2                                      |   4.376s  |   4.376s  |   0.000s  | 0.0%|
|Stroeder_15__ComplxStruc.c__p22352_terminationG_0.smt2                                      | 600.180s  | 600.180s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22437_terminationG_0.smt2                                           | 600.065s  | 600.065s  |   0.000s  | 0.0%|
|Stroeder_15__Cousot.c__p22441_terminationG_0.smt2                                           | 132.217s  | 132.217s  |   0.000s  | 0.0%|
|Stroeder_15__DoubleNeg.c__p22532_terminationG_0.smt2                                        | 600.102s  | 600.102s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22590_terminationG_0.smt2                                              |   2.825s  |   2.825s  |   0.000s  | 0.0%|
|Stroeder_15__Et1.c__p22595_terminationG_0.smt2                                              | 607.574s  | 607.574s  |   0.000s  | 0.0%|
|Stroeder_15__Et4.c__p22639_terminationG_0.smt2                                              |   1.368s  |   1.368s  |   0.000s  | 0.0%|
|Stroeder_15__Even.c__p22673_terminationG_0.smt2                                             |  35.757s  |  35.757s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22751_terminationG_0.smt2                                             |   0.633s  |   0.633s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22755_terminationG_0.smt2                                             |   2.300s  |   2.300s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22756_terminationG_0.smt2                                             |   8.669s  |   8.669s  |   0.000s  | 0.0%|
|Stroeder_15__Ex04.c__p22757_terminationG_0.smt2                                             |   9.877s  |   9.877s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22819_terminationG_0.smt2                                             |  11.887s  |  11.887s  |   0.000s  | 0.0%|
|Stroeder_15__Ex08.c__p22824_edge_closing_0.smt2                                             |   5.936s  |   5.936s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22852_terminationG_0.smt2                                        |   1.547s  |   1.547s  |   0.000s  | 0.0%|
|Stroeder_15__Factorial.c__p22854_terminationG_0.smt2                                        | 600.250s  | 600.250s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22867_terminationG_0.smt2                                        |   1.783s  |   1.783s  |   0.000s  | 0.0%|
|Stroeder_15__Fibonacci.c__p22871_terminationG_0.smt2                                        |   0.982s  |   0.982s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__p23173_terminationG_0.smt2                                              |   7.591s  |   7.591s  |   0.000s  | 0.0%|
|Stroeder_15__GCD.c__terminationS_5_0.smt2                                                   |   2.946s  |   2.946s  |   0.000s  | 0.0%|
|Stroeder_15__GulwaniJainKoskinen-PLDI2009-Fig1_true-termination.c__p23481_edge_closing_0.smt2  | 600.102s  | 600.102s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex5_false-termination.c__p24056_edge_closing_0.smt2      |   5.747s  |   5.747s  |   0.000s  | 0.0%|
|Stroeder_15__LeikeHeizmann-WST2014-Ex6_false-termination.c__p24089_terminationG_0.smt2      |   3.774s  |   3.774s  |   0.000s  | 0.0%|
|Stroeder_15__Lobnya-Boolean-Reordered_true-termination.c__p24120_terminationG_0.smt2        |   3.055s  |   3.055s  |   0.000s  | 0.0%|
|Stroeder_15__LogMult.c__p24141_terminationG_0.smt2                                          |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|Stroeder_15__Marbie1.c__p24189_terminationG_0.smt2                                          |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24243_terminationG_0.smt2           |   2.203s  |   2.203s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24246_terminationG_0.smt2           |   1.388s  |   1.388s  |   0.000s  | 0.0%|
|Stroeder_15__Masse-VMCAI2014-Fig1b_true-termination.c__p24251_edge_closing_0.smt2           |  13.463s  |  13.463s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorInterv.c__p24423_edge_closing_0.smt2                                     |  77.365s  |  77.365s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__p24483_terminationG_0.smt2                                  |   2.004s  |   2.004s  |   0.000s  | 0.0%|
|Stroeder_15__MirrorIntervSim.c__terminationS_0_0.smt2                                       |   0.644s  |   0.644s  |   0.000s  | 0.0%|
|Stroeder_15__NO_10.c__p24670_terminationG_0.smt2                                            |   3.524s  |   3.524s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24712_terminationG_0.smt2                                            |   6.980s  |   6.980s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__p24727_terminationG_0.smt2                                            |   4.661s  |   4.661s  |   0.000s  | 0.0%|
|Stroeder_15__NO_12.c__terminationS_0_0.smt2                                                 |   3.013s  |   3.013s  |   0.000s  | 0.0%|
|Stroeder_15__NO_13.c__p24749_terminationG_0.smt2                                            |  54.661s  |  54.661s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24836_terminationG_0.smt2                |   0.451s  |   0.451s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination1_false-termination.c__p24842_terminationG_0.smt2                |   7.884s  |   7.884s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24928_edge_closing_0.smt2                |  57.455s  |  57.455s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination2_false-termination.c__p24940_edge_closing_0.smt2                | 600.086s  | 600.086s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24955_terminationG_0.smt2                | 600.139s  | 600.139s  |   0.000s  | 0.0%|
|Stroeder_15__NonTermination4_false-termination.c__p24980_edge_closing_0.smt2                |   0.460s  |   0.460s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple6_false-termination.c__p25121_terminationG_0.smt2          | 600.116s  | 600.116s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple8_false-termination.c__p25188_edge_closing_0.smt2          |   4.218s  |   4.218s  |   0.000s  | 0.0%|
|Stroeder_15__NonTerminationSimple9_false-termination.c__p25203_terminationG_0.smt2          |   1.198s  |   1.198s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC1.c__p25352_terminationG_0.smt2                                          |   2.963s  |   2.963s  |   0.000s  | 0.0%|
|Stroeder_15__PastaC10.c__p25335_terminationG_0.smt2                                         |   0.843s  |   0.843s  |   0.000s  | 0.0%|
|Stroeder_15__Pure3Phase_true-termination.c__p25518_terminationG_0.smt2                      |   6.940s  |   6.940s  |   0.000s  | 0.0%|
|Stroeder_15__Sunset.c__p25623_terminationG_0.smt2                                           |  13.934s  |  13.934s  |   0.000s  | 0.0%|
|Stroeder_15__UpAndDown.c__p26202_terminationG_0.smt2                                        |  39.369s  |  39.369s  |   0.000s  | 0.0%|
|Stroeder_15__Velroyen_false-termination.c__p26334_terminationG_0.smt2                       |   0.578s  |   0.578s  |   0.000s  | 0.0%|
|Stroeder_15__WhileIncr.c__p26382_terminationG_0.smt2                                        |   3.355s  |   3.355s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26451_terminationG_0.smt2                                |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|Stroeder_15__WhileNestedOffset.c__p26458_terminationG_0.smt2                                | 600.275s  | 600.275s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20349_terminationG_0.smt2                          |   6.554s  |   6.554s  |   0.000s  | 0.0%|
|Stroeder_15__aaron3_true-termination.c__p20354_terminationG_0.smt2                          |   5.716s  |   5.716s  |   0.000s  | 0.0%|
|Stroeder_15__collatz.c__p22222_edge_closing_0.smt2                                          |   2.737s  |   2.737s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_c.01-no-inv.c__p25768_terminationG_0.smt2                               |   2.535s  |   2.535s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25816_terminationG_0.smt2                                       |   3.750s  |   3.750s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25822_terminationG_0.smt2                                       | 600.202s  | 600.202s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25831_terminationG_0.smt2                                       |  74.779s  |  74.779s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25837_terminationG_0.smt2                                       | 129.217s  | 129.217s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25846_terminationG_0.smt2                                       |   7.994s  |   7.994s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25847_terminationG_0.smt2                                       |   9.106s  |   9.106s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25853_terminationG_0.smt2                                       |  80.479s  |  80.479s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25863_terminationG_0.smt2                                       | 600.640s  | 600.640s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25867_terminationG_0.smt2                                       |   3.532s  |   3.532s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25886_terminationG_0.smt2                                       |   7.926s  |   7.926s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25903_terminationG_0.smt2                                       | 613.489s  | 613.489s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25913_terminationG_0.smt2                                       | 600.190s  | 600.190s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25929_terminationG_0.smt2                                       | 600.178s  | 600.178s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25963_terminationG_0.smt2                                       | 600.164s  | 600.164s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__p25983_terminationG_0.smt2                                       |   9.134s  |   9.134s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex2.c__terminationS_0_0.smt2                                            |   0.692s  |   0.692s  |   0.000s  | 0.0%|
|Stroeder_15__svcomp_ex3b.c__p26046_terminationG_0.smt2                                      |   4.200s  |   4.200s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26547_terminationG_0.smt2                       | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26555_terminationG_0.smt2                       |   5.333s  |   5.333s  |   0.000s  | 0.0%|
|Ton_Chanh_15__2Nested_false-termination.c__p26557_terminationG_0.smt2                       | 600.071s  | 600.071s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Bangalore_false-termination.c__p26582_terminationG_0.smt2                     | 600.071s  | 600.071s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Benghazi_nondet_true-termination.c__p26678_terminationG_0.smt2                |   1.495s  |   1.495s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Copenhagen_disj_true-termination.c__p26854_edge_closing_0.smt2                |  10.155s  |  10.155s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Gothenburg_v2_true-termination.c__p26878_terminationG_0.smt2                  |   1.104s  |   1.104s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26899_terminationG_0.smt2                   |   4.129s  |   4.129s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_2vars_false-termination.c__p26907_terminationG_0.smt2                   |   3.017s  |   3.017s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26981_terminationG_0.smt2                   |  12.833s  |  12.833s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p26990_terminationG_0.smt2                   |   7.701s  |   7.701s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_3vars_false-termination.c__p27021_terminationG_0.smt2                   |  25.495s  |  25.495s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27052_terminationG_0.smt2                    |   1.435s  |   1.435s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27220_terminationG_0.smt2                    |   3.790s  |   3.790s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Hanoi_plus_false-termination.c__p27226_terminationG_0.smt2                    |  76.490s  |  76.490s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27264_terminationG_0.smt2                        |   3.344s  |   3.344s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27269_terminationG_0.smt2                        | 600.066s  | 600.066s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Mysore_false-termination.c__p27288_edge_closing_0.smt2                        |   3.305s  |   3.305s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27381_terminationG_0.smt2                  |  26.207s  |  26.207s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v1_false-termination.c__p27382_terminationG_0.smt2                  | 600.094s  | 600.094s  |   0.000s  | 0.0%|
|Ton_Chanh_15__Singapore_v2_false-termination.c__p27439_terminationG_0.smt2                  | 600.068s  | 600.068s  |   0.000s  | 0.0%|
|aaron3_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                     |   0.404s  |   0.404s  |   0.000s  | 0.0%|
|aproveSMT1008289700543544835.smt2                                                           |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|aproveSMT1022543817592849705.smt2                                                           |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|aproveSMT1045293394610378205.smt2                                                           |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|aproveSMT1059628807158111792.smt2                                                           |   2.217s  |   2.217s  |   0.000s  | 0.0%|
|aproveSMT1067631316961394932.smt2                                                           |  93.764s  |  93.764s  |   0.000s  | 0.0%|
|aproveSMT1076852626867582761.smt2                                                           |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|aproveSMT1105246329636558105.smt2                                                           |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|aproveSMT1133405555645861684.smt2                                                           |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|aproveSMT1154766035975480809.smt2                                                           |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|aproveSMT1166681508436419880.smt2                                                           |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|aproveSMT1207857789260966146.smt2                                                           |   0.717s  |   0.717s  |   0.000s  | 0.0%|
|aproveSMT1222406278700673783.smt2                                                           |   2.908s  |   2.908s  |   0.000s  | 0.0%|
|aproveSMT1256079449125527892.smt2                                                           |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|aproveSMT1261041288686639410.smt2                                                           |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|aproveSMT1296180034830538453.smt2                                                           |   0.803s  |   0.803s  |   0.000s  | 0.0%|
|aproveSMT1329540615731828670.smt2                                                           | 600.311s  | 600.311s  |   0.000s  | 0.0%|
|aproveSMT1437438160177275586.smt2                                                           | 286.563s  | 286.563s  |   0.000s  | 0.0%|
|aproveSMT144364303553946193.smt2                                                            |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|aproveSMT1444998859697836742.smt2                                                           |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|aproveSMT1510730073127582778.smt2                                                           |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|aproveSMT1524169612101880749.smt2                                                           |   1.279s  |   1.279s  |   0.000s  | 0.0%|
|aproveSMT1530191844080893274.smt2                                                           |   4.126s  |   4.126s  |   0.000s  | 0.0%|
|aproveSMT1575921927310304758.smt2                                                           |   3.492s  |   3.492s  |   0.000s  | 0.0%|
|aproveSMT1619938986991890573.smt2                                                           |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|aproveSMT1656844573245055412.smt2                                                           |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|aproveSMT1697563446985587562.smt2                                                           |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|aproveSMT1705398915961754594.smt2                                                           |   3.901s  |   3.901s  |   0.000s  | 0.0%|
|aproveSMT1709482801492808359.smt2                                                           |   0.283s  |   0.283s  |   0.000s  | 0.0%|
|aproveSMT1747479424109945297.smt2                                                           |   3.854s  |   3.854s  |   0.000s  | 0.0%|
|aproveSMT1750284694627347091.smt2                                                           |   1.202s  |   1.202s  |   0.000s  | 0.0%|
|aproveSMT1802082844053698751.smt2                                                           | 600.276s  | 600.276s  |   0.000s  | 0.0%|
|aproveSMT1832939841447591359.smt2                                                           |   3.720s  |   3.720s  |   0.000s  | 0.0%|
|aproveSMT1909899370567820557.smt2                                                           |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|aproveSMT2059890911796961568.smt2                                                           |   0.791s  |   0.791s  |   0.000s  | 0.0%|
|aproveSMT2080970443407093756.smt2                                                           |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|aproveSMT2121292005079447352.smt2                                                           | 600.062s  | 600.062s  |   0.000s  | 0.0%|
|aproveSMT2123657877861531207.smt2                                                           |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|aproveSMT2142784755099170345.smt2                                                           |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|aproveSMT2158114964317463984.smt2                                                           |   0.300s  |   0.300s  |   0.000s  | 0.0%|
|aproveSMT2180393309678538513.smt2                                                           |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|aproveSMT2180870078806303650.smt2                                                           |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|aproveSMT2200431342265122737.smt2                                                           |   0.563s  |   0.563s  |   0.000s  | 0.0%|
|aproveSMT2217993778086906389.smt2                                                           |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|aproveSMT2256159023721325971.smt2                                                           |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|aproveSMT2271093326661303672.smt2                                                           |   0.984s  |   0.984s  |   0.000s  | 0.0%|
|aproveSMT2279546529930018049.smt2                                                           | 600.370s  | 600.370s  |   0.000s  | 0.0%|
|aproveSMT2313612983845754801.smt2                                                           |   1.793s  |   1.793s  |   0.000s  | 0.0%|
|aproveSMT2315623815142209104.smt2                                                           |   0.643s  |   0.643s  |   0.000s  | 0.0%|
|aproveSMT2316535250821506157.smt2                                                           |   4.761s  |   4.761s  |   0.000s  | 0.0%|
|aproveSMT2322179511678559502.smt2                                                           |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|aproveSMT233295163504864559.smt2                                                            |   2.112s  |   2.112s  |   0.000s  | 0.0%|
|aproveSMT2355004445894478329.smt2                                                           |   2.571s  |   2.571s  |   0.000s  | 0.0%|
|aproveSMT2409578890815829527.smt2                                                           |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|aproveSMT2423766902024488209.smt2                                                           |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|aproveSMT2477805317391230600.smt2                                                           |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|aproveSMT2493881658895874595.smt2                                                           |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|aproveSMT2598777028614012130.smt2                                                           |   3.543s  |   3.543s  |   0.000s  | 0.0%|
|aproveSMT2631357328519238424.smt2                                                           |   0.360s  |   0.360s  |   0.000s  | 0.0%|
|aproveSMT2632098249079857042.smt2                                                           |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|aproveSMT2807471946702649636.smt2                                                           |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|aproveSMT2844713893974801294.smt2                                                           |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|aproveSMT2846862246352958329.smt2                                                           |   0.626s  |   0.626s  |   0.000s  | 0.0%|
|aproveSMT2880696731965229413.smt2                                                           |   3.770s  |   3.770s  |   0.000s  | 0.0%|
|aproveSMT2881315380892242955.smt2                                                           |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|aproveSMT2912633883485370336.smt2                                                           |   6.082s  |   6.082s  |   0.000s  | 0.0%|
|aproveSMT2926330432023427683.smt2                                                           |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|aproveSMT2934397244559601587.smt2                                                           |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|aproveSMT2958125353683346121.smt2                                                           |   0.869s  |   0.869s  |   0.000s  | 0.0%|
|aproveSMT2992043958700127833.smt2                                                           |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|aproveSMT3033966919233248917.smt2                                                           |   6.064s  |   6.064s  |   0.000s  | 0.0%|
|aproveSMT3039391242675517681.smt2                                                           |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|aproveSMT3057256999514663885.smt2                                                           |   3.865s  |   3.865s  |   0.000s  | 0.0%|
|aproveSMT3060102017506592639.smt2                                                           |   3.558s  |   3.558s  |   0.000s  | 0.0%|
|aproveSMT3082703823983150903.smt2                                                           |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|aproveSMT3090147554356497231.smt2                                                           |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|aproveSMT3101880129747917873.smt2                                                           |  25.032s  |  25.032s  |   0.000s  | 0.0%|
|aproveSMT325795488857285297.smt2                                                            |   2.808s  |   2.808s  |   0.000s  | 0.0%|
|aproveSMT3264265901512371238.smt2                                                           |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|aproveSMT3305912493296657311.smt2                                                           |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|aproveSMT3306677380446705919.smt2                                                           |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|aproveSMT3320813910319868151.smt2                                                           |   3.960s  |   3.960s  |   0.000s  | 0.0%|
|aproveSMT3334656614075774306.smt2                                                           |   1.234s  |   1.234s  |   0.000s  | 0.0%|
|aproveSMT334180970798087384.smt2                                                            |   6.643s  |   6.643s  |   0.000s  | 0.0%|
|aproveSMT3342367565143444747.smt2                                                           |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|aproveSMT3400215009548742987.smt2                                                           |   0.832s  |   0.832s  |   0.000s  | 0.0%|
|aproveSMT3417012265546351137.smt2                                                           |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|aproveSMT342988194676879281.smt2                                                            |   1.292s  |   1.292s  |   0.000s  | 0.0%|
|aproveSMT3496695621216907819.smt2                                                           |   1.025s  |   1.025s  |   0.000s  | 0.0%|
|aproveSMT3571876635740058861.smt2                                                           |   6.036s  |   6.036s  |   0.000s  | 0.0%|
|aproveSMT3611058756933534688.smt2                                                           |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|aproveSMT3612851711724526218.smt2                                                           |   2.511s  |   2.511s  |   0.000s  | 0.0%|
|aproveSMT3778692042252886508.smt2                                                           |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|aproveSMT3807494294977005803.smt2                                                           |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|aproveSMT3839584170547805483.smt2                                                           | 216.329s  | 216.329s  |   0.000s  | 0.0%|
|aproveSMT3935457195847984314.smt2                                                           |   0.924s  |   0.924s  |   0.000s  | 0.0%|
|aproveSMT3970517148307051183.smt2                                                           |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|aproveSMT3981927164583947462.smt2                                                           |   1.405s  |   1.405s  |   0.000s  | 0.0%|
|aproveSMT4004559194265078508.smt2                                                           |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|aproveSMT4005477226838207398.smt2                                                           |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|aproveSMT4015411381612320072.smt2                                                           |   7.513s  |   7.513s  |   0.000s  | 0.0%|
|aproveSMT405002793410787217.smt2                                                            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|aproveSMT4068876412031045354.smt2                                                           |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|aproveSMT4159349101604568985.smt2                                                           |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|aproveSMT4163246385735196737.smt2                                                           |   0.361s  |   0.361s  |   0.000s  | 0.0%|
|aproveSMT4177797293206130085.smt2                                                           |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|aproveSMT4293993713008672806.smt2                                                           |   3.663s  |   3.663s  |   0.000s  | 0.0%|
|aproveSMT4380061691498964684.smt2                                                           |   3.250s  |   3.250s  |   0.000s  | 0.0%|
|aproveSMT4408268044216253595.smt2                                                           |   4.206s  |   4.206s  |   0.000s  | 0.0%|
|aproveSMT4439607947222714793.smt2                                                           |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|aproveSMT4504963179470263546.smt2                                                           |   0.534s  |   0.534s  |   0.000s  | 0.0%|
|aproveSMT4525776783561378911.smt2                                                           |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|aproveSMT4553505495713257009.smt2                                                           |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|aproveSMT4589478066325636629.smt2                                                           |   0.719s  |   0.719s  |   0.000s  | 0.0%|
|aproveSMT4606013414596055049.smt2                                                           |   0.286s  |   0.286s  |   0.000s  | 0.0%|
|aproveSMT4610599926347927445.smt2                                                           |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|aproveSMT4626738710431749334.smt2                                                           |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|aproveSMT4726660327701427.smt2                                                              |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|aproveSMT4764278413219307912.smt2                                                           |   0.487s  |   0.487s  |   0.000s  | 0.0%|
|aproveSMT4776473963623431246.smt2                                                           |   7.985s  |   7.985s  |   0.000s  | 0.0%|
|aproveSMT4786517774271864296.smt2                                                           |   6.041s  |   6.041s  |   0.000s  | 0.0%|
|aproveSMT4790304217385820014.smt2                                                           |   2.734s  |   2.734s  |   0.000s  | 0.0%|
|aproveSMT4812740542900327077.smt2                                                           |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|aproveSMT4817399800518468578.smt2                                                           |   2.552s  |   2.552s  |   0.000s  | 0.0%|
|aproveSMT4830702979511545177.smt2                                                           |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|aproveSMT4843513687534854491.smt2                                                           |   1.530s  |   1.530s  |   0.000s  | 0.0%|
|aproveSMT4894552965501289252.smt2                                                           |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|aproveSMT4940364873027923219.smt2                                                           |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|aproveSMT5038173880269306850.smt2                                                           |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|aproveSMT5046440760903487310.smt2                                                           |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|aproveSMT5056627952338669338.smt2                                                           |   2.677s  |   2.677s  |   0.000s  | 0.0%|
|aproveSMT5205173846890464046.smt2                                                           |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|aproveSMT5210438168892578988.smt2                                                           |   0.256s  |   0.256s  |   0.000s  | 0.0%|
|aproveSMT5219933089216354552.smt2                                                           |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|aproveSMT522772885303483707.smt2                                                            |   1.654s  |   1.654s  |   0.000s  | 0.0%|
|aproveSMT5236930360453082734.smt2                                                           |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|aproveSMT525791599825112152.smt2                                                            |   0.246s  |   0.246s  |   0.000s  | 0.0%|
|aproveSMT5335778151184305698.smt2                                                           |   2.449s  |   2.449s  |   0.000s  | 0.0%|
|aproveSMT5348320449423401087.smt2                                                           |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|aproveSMT5476436532372645500.smt2                                                           |   0.740s  |   0.740s  |   0.000s  | 0.0%|
|aproveSMT5493191018463992513.smt2                                                           |   0.283s  |   0.283s  |   0.000s  | 0.0%|
|aproveSMT5521985939949569030.smt2                                                           |  75.234s  |  75.234s  |   0.000s  | 0.0%|
|aproveSMT5541044923638316164.smt2                                                           |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|aproveSMT5555859573725551605.smt2                                                           |   3.312s  |   3.312s  |   0.000s  | 0.0%|
|aproveSMT5598217329789101375.smt2                                                           |   3.727s  |   3.727s  |   0.000s  | 0.0%|
|aproveSMT5606410117877393489.smt2                                                           |   0.446s  |   0.446s  |   0.000s  | 0.0%|
|aproveSMT5625725354797588883.smt2                                                           |   0.680s  |   0.680s  |   0.000s  | 0.0%|
|aproveSMT5697460246608014240.smt2                                                           |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|aproveSMT5775190440758349853.smt2                                                           |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|aproveSMT578728211229400351.smt2                                                            | 600.201s  | 600.201s  |   0.000s  | 0.0%|
|aproveSMT5829491630698138486.smt2                                                           |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|aproveSMT5858552346124402853.smt2                                                           |   1.401s  |   1.401s  |   0.000s  | 0.0%|
|aproveSMT5913022081957613825.smt2                                                           |   3.732s  |   3.732s  |   0.000s  | 0.0%|
|aproveSMT5989587704234446991.smt2                                                           |   6.890s  |   6.890s  |   0.000s  | 0.0%|
|aproveSMT5992389869070970435.smt2                                                           |   3.241s  |   3.241s  |   0.000s  | 0.0%|
|aproveSMT6007639960281434719.smt2                                                           |   1.853s  |   1.853s  |   0.000s  | 0.0%|
|aproveSMT6023062156836720896.smt2                                                           |  78.445s  |  78.445s  |   0.000s  | 0.0%|
|aproveSMT6030602863271290399.smt2                                                           | 600.107s  | 600.107s  |   0.000s  | 0.0%|
|aproveSMT6033388866962201290.smt2                                                           |   4.094s  |   4.094s  |   0.000s  | 0.0%|
|aproveSMT6054561478528727566.smt2                                                           |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|aproveSMT6071606564644554507.smt2                                                           |   6.005s  |   6.005s  |   0.000s  | 0.0%|
|aproveSMT6116422603960968616.smt2                                                           |  11.039s  |  11.039s  |   0.000s  | 0.0%|
|aproveSMT6155317075733447430.smt2                                                           |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|aproveSMT6201299735749963496.smt2                                                           |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|aproveSMT6242888656932764676.smt2                                                           |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|aproveSMT6285895805497343865.smt2                                                           |   0.859s  |   0.859s  |   0.000s  | 0.0%|
|aproveSMT629665582926508878.smt2                                                            |   0.852s  |   0.852s  |   0.000s  | 0.0%|
|aproveSMT6301725928280158574.smt2                                                           |   3.164s  |   3.164s  |   0.000s  | 0.0%|
|aproveSMT6405258831427788557.smt2                                                           |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|aproveSMT6456513912671766647.smt2                                                           |   1.504s  |   1.504s  |   0.000s  | 0.0%|
|aproveSMT6461796824751951221.smt2                                                           |   2.535s  |   2.535s  |   0.000s  | 0.0%|
|aproveSMT6500048596873196244.smt2                                                           |   3.574s  |   3.574s  |   0.000s  | 0.0%|
|aproveSMT6549179037310304786.smt2                                                           |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|aproveSMT655469581631834278.smt2                                                            |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|aproveSMT6658278851923446624.smt2                                                           |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|aproveSMT6674842082078899004.smt2                                                           |   4.365s  |   4.365s  |   0.000s  | 0.0%|
|aproveSMT6744625072979146355.smt2                                                           |   4.341s  |   4.341s  |   0.000s  | 0.0%|
|aproveSMT6753330551938377858.smt2                                                           |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|aproveSMT6771738228131904044.smt2                                                           |   2.520s  |   2.520s  |   0.000s  | 0.0%|
|aproveSMT6871796204961549893.smt2                                                           |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|aproveSMT691472806777450769.smt2                                                            |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|aproveSMT7048666801337573956.smt2                                                           |   5.971s  |   5.971s  |   0.000s  | 0.0%|
|aproveSMT7070426067875134896.smt2                                                           |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|aproveSMT7081278616493440418.smt2                                                           |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|aproveSMT7141115503836990123.smt2                                                           |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|aproveSMT7144269790757830415.smt2                                                           |   8.451s  |   8.451s  |   0.000s  | 0.0%|
|aproveSMT7145338241152838632.smt2                                                           |   5.667s  |   5.667s  |   0.000s  | 0.0%|
|aproveSMT7201733644041072759.smt2                                                           | 600.356s  | 600.356s  |   0.000s  | 0.0%|
|aproveSMT7278800282732675654.smt2                                                           |   3.147s  |   3.147s  |   0.000s  | 0.0%|
|aproveSMT7315824316795347455.smt2                                                           |   1.477s  |   1.477s  |   0.000s  | 0.0%|
|aproveSMT7334875128895402176.smt2                                                           |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|aproveSMT7377887083439038055.smt2                                                           |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|aproveSMT7425096829426664326.smt2                                                           |   8.262s  |   8.262s  |   0.000s  | 0.0%|
|aproveSMT743198230882528455.smt2                                                            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|aproveSMT7440630011441673394.smt2                                                           |  60.153s  |  60.153s  |   0.000s  | 0.0%|
|aproveSMT7608975121595496463.smt2                                                           |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|aproveSMT7610852511450248253.smt2                                                           |   0.470s  |   0.470s  |   0.000s  | 0.0%|
|aproveSMT778144120697107907.smt2                                                            |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|aproveSMT7823144654332746343.smt2                                                           |   1.562s  |   1.562s  |   0.000s  | 0.0%|
|aproveSMT7861215804091976133.smt2                                                           |   1.360s  |   1.360s  |   0.000s  | 0.0%|
|aproveSMT7917963829768768087.smt2                                                           |   4.974s  |   4.974s  |   0.000s  | 0.0%|
|aproveSMT8012602079643276968.smt2                                                           |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|aproveSMT8038578912200818680.smt2                                                           |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|aproveSMT8056030040600901039.smt2                                                           | 373.793s  | 373.793s  |   0.000s  | 0.0%|
|aproveSMT8120783453179243473.smt2                                                           |   0.524s  |   0.524s  |   0.000s  | 0.0%|
|aproveSMT8137047330849691949.smt2                                                           |   2.773s  |   2.773s  |   0.000s  | 0.0%|
|aproveSMT8204649684904954337.smt2                                                           |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|aproveSMT8205772230016192248.smt2                                                           |  10.491s  |  10.491s  |   0.000s  | 0.0%|
|aproveSMT8213728202959413718.smt2                                                           |   2.905s  |   2.905s  |   0.000s  | 0.0%|
|aproveSMT8264792885821091201.smt2                                                           |   7.008s  |   7.008s  |   0.000s  | 0.0%|
|aproveSMT8282187318664889653.smt2                                                           |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|aproveSMT82980353335522103.smt2                                                             |   3.603s  |   3.603s  |   0.000s  | 0.0%|
|aproveSMT8328864454385468275.smt2                                                           |   5.642s  |   5.642s  |   0.000s  | 0.0%|
|aproveSMT8349063162874178644.smt2                                                           |   2.375s  |   2.375s  |   0.000s  | 0.0%|
|aproveSMT8366476055690990863.smt2                                                           |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|aproveSMT8377786446909921993.smt2                                                           |   0.338s  |   0.338s  |   0.000s  | 0.0%|
|aproveSMT8384181922198476260.smt2                                                           | 600.141s  | 600.141s  |   0.000s  | 0.0%|
|aproveSMT8423039779088334472.smt2                                                           |   0.294s  |   0.294s  |   0.000s  | 0.0%|
|aproveSMT8524404391338204488.smt2                                                           |   0.341s  |   0.341s  |   0.000s  | 0.0%|
|aproveSMT8573084889555001775.smt2                                                           |  31.772s  |  31.772s  |   0.000s  | 0.0%|
|aproveSMT8666199152065483741.smt2                                                           |   0.288s  |   0.288s  |   0.000s  | 0.0%|
|aproveSMT8677323562739420602.smt2                                                           |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|aproveSMT8739079467798956217.smt2                                                           |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|aproveSMT8739447481320129819.smt2                                                           |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|aproveSMT8797788573757816721.smt2                                                           |   0.431s  |   0.431s  |   0.000s  | 0.0%|
|aproveSMT8801446599485295192.smt2                                                           |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|aproveSMT880649614033826505.smt2                                                            |   2.105s  |   2.105s  |   0.000s  | 0.0%|
|aproveSMT8813034472200507181.smt2                                                           |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|aproveSMT8866413736567330792.smt2                                                           |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|aproveSMT8878736820157791946.smt2                                                           |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|aproveSMT901847787721299507.smt2                                                            |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|aproveSMT902782301342505505.smt2                                                            |   1.710s  |   1.710s  |   0.000s  | 0.0%|
|aproveSMT9030607454323718032.smt2                                                           |   4.003s  |   4.003s  |   0.000s  | 0.0%|
|aproveSMT9054136929086877877.smt2                                                           |   4.166s  |   4.166s  |   0.000s  | 0.0%|
|aproveSMT9073350781778038452.smt2                                                           |   2.403s  |   2.403s  |   0.000s  | 0.0%|
|aproveSMT9118077011737449494.smt2                                                           |   7.743s  |   7.743s  |   0.000s  | 0.0%|
|aproveSMT9169917326916030775.smt2                                                           |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|aproveSMT9190658207098859112.smt2                                                           |   3.913s  |   3.913s  |   0.000s  | 0.0%|
|aproveSMT9210831631031619938.smt2                                                           |  33.671s  |  33.671s  |   0.000s  | 0.0%|
|aproveSMT944940066259205664.smt2                                                            |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|aproveSMT955385929993658388.smt2                                                            |   0.471s  |   0.471s  |   0.000s  | 0.0%|
|aproveSMT993796237976442048.smt2                                                            |  22.285s  |  22.285s  |   0.000s  | 0.0%|
|b.04_true-termination.c_Iteration1_Loop+nonterminationTemplate_0.smt2                       |   0.657s  |   0.657s  |   0.000s  | 0.0%|
|b.07-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2               |   0.931s  |   0.931s  |   0.000s  | 0.0%|
|flag-alloca_true-termination.c.i_Iteration1_Lasso+nonterminationTemplate.smt2               |   2.119s  |   2.119s  |   0.000s  | 0.0%|
|java_AG313-alloca_true-termination.c.i_Iteration2_Lasso+nonterminationTemplate.smt2         |   0.492s  |   0.492s  |   0.000s  | 0.0%|
|problem-000008.cvc.1.smt2                                                                   |   1.512s  |   1.512s  |   0.000s  | 0.0%|
|problem-000019.cvc.1.smt2                                                                   |   1.021s  |   1.021s  |   0.000s  | 0.0%|
|problem-000019.cvc.2.smt2                                                                   |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|problem-000025.cvc.2.smt2                                                                   |  10.040s  |  10.040s  |   0.000s  | 0.0%|
|problem-000080.cvc.1.smt2                                                                   |   0.871s  |   0.871s  |   0.000s  | 0.0%|
|problem-000124.cvc.1.smt2                                                                   |   9.766s  |   9.766s  |   0.000s  | 0.0%|
|problem-000131.cvc.1.smt2                                                                   |   0.435s  |   0.435s  |   0.000s  | 0.0%|
|problem-000441.cvc.1.smt2                                                                   |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|problem-001265.cvc.1.smt2                                                                   |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|problem-001268.cvc.1.smt2                                                                   |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|problem-002452.cvc.1.smt2                                                                   |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|problem-002563.cvc.1.smt2                                                                   |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|problem-002617.cvc.1.smt2                                                                   |   0.713s  |   0.713s  |   0.000s  | 0.0%|
|problem-002619.cvc.1.smt2                                                                   |   1.209s  |   1.209s  |   0.000s  | 0.0%|
|problem-002871.cvc.1.smt2                                                                   |   0.469s  |   0.469s  |   0.000s  | 0.0%|
|problem-002949.cvc.1.smt2                                                                   |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|problem-005140.cvc.1.smt2                                                                   |   0.246s  |   0.246s  |   0.000s  | 0.0%|
|problem-005897.cvc.1.smt2                                                                   |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|problem-005952.cvc.1.smt2                                                                   |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|problem-006501.cvc.1.smt2                                                                   |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|problem-006526.cvc.1.smt2                                                                   |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|problem-006535.cvc.1.smt2                                                                   |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|problem-006538.cvc.1.smt2                                                                   |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|problem-006542.cvc.1.smt2                                                                   |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|problem-006547.cvc.1.smt2                                                                   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|term-0BB4ks.smt2                                                                            | 600.136s  | 600.136s  |   0.000s  | 0.0%|
|term-0Hb4yp.smt2                                                                            |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|term-AwuLMZ.smt2                                                                            |   2.296s  |   2.296s  |   0.000s  | 0.0%|
|term-BjWYcv.smt2                                                                            |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|term-K5O3aH.smt2                                                                            | 600.091s  | 600.091s  |   0.000s  | 0.0%|
|term-Kkefdl.smt2                                                                            |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|term-WG086A.smt2                                                                            | 600.147s  | 600.147s  |   0.000s  | 0.0%|
|term-XoKPE3.smt2                                                                            |   0.333s  |   0.333s  |   0.000s  | 0.0%|
|term-cTfKvw.smt2                                                                            | 169.197s  | 169.197s  |   0.000s  | 0.0%|
|term-e0uxKl.smt2                                                                            |   0.265s  |   0.265s  |   0.000s  | 0.0%|
|term-fu8ErM.smt2                                                                            | 600.065s  | 600.065s  |   0.000s  | 0.0%|
|term-iQK4Ty.smt2                                                                            | 600.095s  | 600.095s  |   0.000s  | 0.0%|
|term-nKoz7d.smt2                                                                            |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|term-rGohwx.smt2                                                                            |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|term-tEmpby.smt2                                                                            |   0.105s  |   0.105s  |   0.000s  | 0.0%|
</details>
