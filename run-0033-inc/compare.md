Comparing data and data


# SUMMARY
- LHS tests = 2000
- RHS tests = 2000
- LHS success = 334  (16.7%)
- RHS success = 334  (16.7%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: inc
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 766b9df4e2514fc2cd72bccba134d3c35c1feb7f
Z3 branch: sls
Z3 options: "-T:20 -v:2 -st sls.euf_incremental=true tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)""
Z3 inputs: inputs/QF_UF_SAT
Z3 commit message: fixup handling of disequality propagation

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: inc
Z3 repo: https://github.com/Z3Prover/z3
Z3 commit: 766b9df4e2514fc2cd72bccba134d3c35c1feb7f
Z3 branch: sls
Z3 options: "-T:20 -v:2 -st sls.euf_incremental=true tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)""
Z3 inputs: inputs/QF_UF_SAT
Z3 commit message: fixup handling of disequality propagation

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00001.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00002.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00011.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|00019.smt2                                                                                  |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00060.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00081.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00152.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00001.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00002.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00011.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|00019.smt2                                                                                  |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00060.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00081.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00152.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00001.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00002.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00011.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|00019.smt2                                                                                  |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00060.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00081.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00152.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00001.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00002.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00011.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|00019.smt2                                                                                  |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00060.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00081.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00152.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|SEQ020_size4.smt2                                                                          |   6.365s |21.768MiB|
|QF_UF_needham.4.prop4_ab_cti_max.smt2                                                      |   0.230s |25.144MiB|
|QF_UF_telephony.5.prop1_ab_cti_max.smt2                                                    |   0.203s |24.292MiB|
|QF_UF_lifts.2.prop1_ab_cti_max.smt2                                                        |   0.201s |24.96MiB|
|iso_brn_repgen_sk041.smt2                                                                  |   0.193s |21.02MiB|
|QF_UF_needham.4.prop2_ab_cti_max.smt2                                                      |   0.179s |25.264MiB|
|iso_brn_repgen_sk023.smt2                                                                  |   0.177s |21.048MiB|
|QF_UF_lifts.1.prop1_ab_cti_max.smt2                                                        |   0.175s |24.972MiB|
|QF_UF_telephony.8.prop1_ab_cti_max.smt2                                                    |   0.175s |24.34MiB|
|QF_UF_telephony.7.prop1_ab_cti_max.smt2                                                    |   0.170s |23.916MiB|
|QF_UF_telephony.6.prop1_ab_cti_max.smt2                                                    |   0.166s |23.988MiB|
|QF_UF_telephony.4.prop1_ab_cti_max.smt2                                                    |   0.152s |23.52MiB|
|QF_UF_extinction.4.prop1_ab_cti_max.smt2                                                   |   0.148s |24.024MiB|
|QF_UF_synapse.1.prop1_ab_cti_max.smt2                                                      |   0.147s |24.356MiB|
|QF_UF_lamport_nonatomic.1.prop1_ab_cti_max.smt2                                            |   0.146s |23.908MiB|
|iso_brn_repgen_sk027.smt2                                                                  |   0.145s |21.02MiB|
|QF_UF_needham.3.prop3_ab_cti_max.smt2                                                      |   0.140s |23.716MiB|
|iso_brn_repgen012.smt2                                                                     |   0.140s |21.62MiB|
|QF_UF_lamport_nonatomic.2.prop1_ab_cti_max.smt2                                            |   0.140s |23.976MiB|
|QF_UF_lamport_nonatomic.3.prop1_ab_cti_max.smt2                                            |   0.139s |23.908MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|SEQ020_size4.smt2                                                                          |   6.365s |21.768MiB|
|QF_UF_needham.4.prop4_ab_cti_max.smt2                                                      |   0.230s |25.144MiB|
|QF_UF_telephony.5.prop1_ab_cti_max.smt2                                                    |   0.203s |24.292MiB|
|QF_UF_lifts.2.prop1_ab_cti_max.smt2                                                        |   0.201s |24.96MiB|
|iso_brn_repgen_sk041.smt2                                                                  |   0.193s |21.02MiB|
|QF_UF_needham.4.prop2_ab_cti_max.smt2                                                      |   0.179s |25.264MiB|
|iso_brn_repgen_sk023.smt2                                                                  |   0.177s |21.048MiB|
|QF_UF_lifts.1.prop1_ab_cti_max.smt2                                                        |   0.175s |24.972MiB|
|QF_UF_telephony.8.prop1_ab_cti_max.smt2                                                    |   0.175s |24.34MiB|
|QF_UF_telephony.7.prop1_ab_cti_max.smt2                                                    |   0.170s |23.916MiB|
|QF_UF_telephony.6.prop1_ab_cti_max.smt2                                                    |   0.166s |23.988MiB|
|QF_UF_telephony.4.prop1_ab_cti_max.smt2                                                    |   0.152s |23.52MiB|
|QF_UF_extinction.4.prop1_ab_cti_max.smt2                                                   |   0.148s |24.024MiB|
|QF_UF_synapse.1.prop1_ab_cti_max.smt2                                                      |   0.147s |24.356MiB|
|QF_UF_lamport_nonatomic.1.prop1_ab_cti_max.smt2                                            |   0.146s |23.908MiB|
|iso_brn_repgen_sk027.smt2                                                                  |   0.145s |21.02MiB|
|QF_UF_needham.3.prop3_ab_cti_max.smt2                                                      |   0.140s |23.716MiB|
|iso_brn_repgen012.smt2                                                                     |   0.140s |21.62MiB|
|QF_UF_lamport_nonatomic.2.prop1_ab_cti_max.smt2                                            |   0.140s |23.976MiB|
|QF_UF_lamport_nonatomic.3.prop1_ab_cti_max.smt2                                            |   0.139s |23.908MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00001.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00002.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00003.smt2                                                                                  |18.284MiB|18.284MiB|0B| 0.0%|
|00011.smt2                                                                                  |18.776MiB|18.776MiB|0B| 0.0%|
|00019.smt2                                                                                  |19.836MiB|19.836MiB|0B| 0.0%|
|00020.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00060.smt2                                                                                  |18.892MiB|18.892MiB|0B| 0.0%|
|00081.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00085.smt2                                                                                  |18.28MiB|18.28MiB|0B| 0.0%|
|00102.smt2                                                                                  |18.54MiB|18.54MiB|0B| 0.0%|
|00104.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00105.smt2                                                                                  |18.8MiB|18.8MiB|0B| 0.0%|
|00152.smt2                                                                                  |18.256MiB|18.256MiB|0B| 0.0%|
|00194.smt2                                                                                  |18.508MiB|18.508MiB|0B| 0.0%|
|00235.smt2                                                                                  |18.476MiB|18.476MiB|0B| 0.0%|
|00243.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00247.smt2                                                                                  |18.532MiB|18.532MiB|0B| 0.0%|
|00249.smt2                                                                                  |18.608MiB|18.608MiB|0B| 0.0%|
|00251.smt2                                                                                  |18.564MiB|18.564MiB|0B| 0.0%|
|00294.smt2                                                                                  |18.508MiB|18.508MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00001.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00002.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00003.smt2                                                                                  |18.284MiB|18.284MiB|0B| 0.0%|
|00011.smt2                                                                                  |18.776MiB|18.776MiB|0B| 0.0%|
|00019.smt2                                                                                  |19.836MiB|19.836MiB|0B| 0.0%|
|00020.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00060.smt2                                                                                  |18.892MiB|18.892MiB|0B| 0.0%|
|00081.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00085.smt2                                                                                  |18.28MiB|18.28MiB|0B| 0.0%|
|00102.smt2                                                                                  |18.54MiB|18.54MiB|0B| 0.0%|
|00104.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00105.smt2                                                                                  |18.8MiB|18.8MiB|0B| 0.0%|
|00152.smt2                                                                                  |18.256MiB|18.256MiB|0B| 0.0%|
|00194.smt2                                                                                  |18.508MiB|18.508MiB|0B| 0.0%|
|00235.smt2                                                                                  |18.476MiB|18.476MiB|0B| 0.0%|
|00243.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00247.smt2                                                                                  |18.532MiB|18.532MiB|0B| 0.0%|
|00249.smt2                                                                                  |18.608MiB|18.608MiB|0B| 0.0%|
|00251.smt2                                                                                  |18.564MiB|18.564MiB|0B| 0.0%|
|00294.smt2                                                                                  |18.508MiB|18.508MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00001.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00002.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00003.smt2                                                                                  |18.284MiB|18.284MiB|0B| 0.0%|
|00011.smt2                                                                                  |18.776MiB|18.776MiB|0B| 0.0%|
|00019.smt2                                                                                  |19.836MiB|19.836MiB|0B| 0.0%|
|00020.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00060.smt2                                                                                  |18.892MiB|18.892MiB|0B| 0.0%|
|00081.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00085.smt2                                                                                  |18.28MiB|18.28MiB|0B| 0.0%|
|00102.smt2                                                                                  |18.54MiB|18.54MiB|0B| 0.0%|
|00104.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00105.smt2                                                                                  |18.8MiB|18.8MiB|0B| 0.0%|
|00152.smt2                                                                                  |18.256MiB|18.256MiB|0B| 0.0%|
|00194.smt2                                                                                  |18.508MiB|18.508MiB|0B| 0.0%|
|00235.smt2                                                                                  |18.476MiB|18.476MiB|0B| 0.0%|
|00243.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00247.smt2                                                                                  |18.532MiB|18.532MiB|0B| 0.0%|
|00249.smt2                                                                                  |18.608MiB|18.608MiB|0B| 0.0%|
|00251.smt2                                                                                  |18.564MiB|18.564MiB|0B| 0.0%|
|00294.smt2                                                                                  |18.508MiB|18.508MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00001.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00002.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00003.smt2                                                                                  |18.284MiB|18.284MiB|0B| 0.0%|
|00011.smt2                                                                                  |18.776MiB|18.776MiB|0B| 0.0%|
|00019.smt2                                                                                  |19.836MiB|19.836MiB|0B| 0.0%|
|00020.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00060.smt2                                                                                  |18.892MiB|18.892MiB|0B| 0.0%|
|00081.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00085.smt2                                                                                  |18.28MiB|18.28MiB|0B| 0.0%|
|00102.smt2                                                                                  |18.54MiB|18.54MiB|0B| 0.0%|
|00104.smt2                                                                                  |18.504MiB|18.504MiB|0B| 0.0%|
|00105.smt2                                                                                  |18.8MiB|18.8MiB|0B| 0.0%|
|00152.smt2                                                                                  |18.256MiB|18.256MiB|0B| 0.0%|
|00194.smt2                                                                                  |18.508MiB|18.508MiB|0B| 0.0%|
|00235.smt2                                                                                  |18.476MiB|18.476MiB|0B| 0.0%|
|00243.smt2                                                                                  |18.512MiB|18.512MiB|0B| 0.0%|
|00247.smt2                                                                                  |18.532MiB|18.532MiB|0B| 0.0%|
|00249.smt2                                                                                  |18.608MiB|18.608MiB|0B| 0.0%|
|00251.smt2                                                                                  |18.564MiB|18.564MiB|0B| 0.0%|
|00294.smt2                                                                                  |18.508MiB|18.508MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|QF_UF_needham.4.prop2_ab_cti_max.smt2                                                      |   0.179s |25.264MiB|
|QF_UF_needham.4.prop3_ab_cti_max.smt2                                                      |   0.099s |25.224MiB|
|QF_UF_needham.4.prop4_ab_cti_max.smt2                                                      |   0.230s |25.144MiB|
|QF_UF_synapse.2.prop1_ab_cti_max.smt2                                                      |   0.109s |25.064MiB|
|QF_UF_lifts.1.prop1_ab_cti_max.smt2                                                        |   0.175s |24.972MiB|
|QF_UF_lifts.2.prop1_ab_cti_max.smt2                                                        |   0.201s |24.96MiB|
|QF_UF_synapse.1.prop1_ab_cti_max.smt2                                                      |   0.147s |24.356MiB|
|QF_UF_telephony.8.prop1_ab_cti_max.smt2                                                    |   0.175s |24.34MiB|
|QF_UF_telephony.5.prop1_ab_cti_max.smt2                                                    |   0.203s |24.292MiB|
|QF_UF_leader_election.2.prop1_ab_cti_max.smt2                                              |   0.061s |24.056MiB|
|QF_UF_leader_election.1.prop1_ab_cti_max.smt2                                              |   0.129s |24.052MiB|
|QF_UF_extinction.4.prop1_ab_cti_max.smt2                                                   |   0.148s |24.024MiB|
|QF_UF_telephony.6.prop1_ab_cti_max.smt2                                                    |   0.166s |23.988MiB|
|QF_UF_lamport_nonatomic.2.prop1_ab_cti_max.smt2                                            |   0.140s |23.976MiB|
|QF_UF_telephony.7.prop1_ab_cti_max.smt2                                                    |   0.170s |23.916MiB|
|QF_UF_lamport_nonatomic.1.prop1_ab_cti_max.smt2                                            |   0.146s |23.908MiB|
|QF_UF_lamport_nonatomic.3.prop1_ab_cti_max.smt2                                            |   0.139s |23.908MiB|
|QF_UF_rether.3.prop1_ab_cti_max.smt2                                                       |   0.125s |23.812MiB|
|QF_UF_extinction.3.prop1_ab_cti_max.smt2                                                   |   0.121s |23.744MiB|
|QF_UF_needham.3.prop3_ab_cti_max.smt2                                                      |   0.140s |23.716MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|QF_UF_needham.4.prop2_ab_cti_max.smt2                                                      |   0.179s |25.264MiB|
|QF_UF_needham.4.prop3_ab_cti_max.smt2                                                      |   0.099s |25.224MiB|
|QF_UF_needham.4.prop4_ab_cti_max.smt2                                                      |   0.230s |25.144MiB|
|QF_UF_synapse.2.prop1_ab_cti_max.smt2                                                      |   0.109s |25.064MiB|
|QF_UF_lifts.1.prop1_ab_cti_max.smt2                                                        |   0.175s |24.972MiB|
|QF_UF_lifts.2.prop1_ab_cti_max.smt2                                                        |   0.201s |24.96MiB|
|QF_UF_synapse.1.prop1_ab_cti_max.smt2                                                      |   0.147s |24.356MiB|
|QF_UF_telephony.8.prop1_ab_cti_max.smt2                                                    |   0.175s |24.34MiB|
|QF_UF_telephony.5.prop1_ab_cti_max.smt2                                                    |   0.203s |24.292MiB|
|QF_UF_leader_election.2.prop1_ab_cti_max.smt2                                              |   0.061s |24.056MiB|
|QF_UF_leader_election.1.prop1_ab_cti_max.smt2                                              |   0.129s |24.052MiB|
|QF_UF_extinction.4.prop1_ab_cti_max.smt2                                                   |   0.148s |24.024MiB|
|QF_UF_telephony.6.prop1_ab_cti_max.smt2                                                    |   0.166s |23.988MiB|
|QF_UF_lamport_nonatomic.2.prop1_ab_cti_max.smt2                                            |   0.140s |23.976MiB|
|QF_UF_telephony.7.prop1_ab_cti_max.smt2                                                    |   0.170s |23.916MiB|
|QF_UF_lamport_nonatomic.1.prop1_ab_cti_max.smt2                                            |   0.146s |23.908MiB|
|QF_UF_lamport_nonatomic.3.prop1_ab_cti_max.smt2                                            |   0.139s |23.908MiB|
|QF_UF_rether.3.prop1_ab_cti_max.smt2                                                       |   0.125s |23.812MiB|
|QF_UF_extinction.3.prop1_ab_cti_max.smt2                                                   |   0.121s |23.744MiB|
|QF_UF_needham.3.prop3_ab_cti_max.smt2                                                      |   0.140s |23.716MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|00001.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00002.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00003.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00011.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|00019.smt2                                                                                  |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|00020.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00060.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00081.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00085.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00102.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00104.smt2                                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|00105.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00152.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00194.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00235.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00243.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00247.smt2                                                                                  |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|00249.smt2                                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|00251.smt2                                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|00294.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00314.smt2                                                                                  |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|00324.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00379.smt2                                                                                  |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|00402.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|00415.smt2                                                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|00428.smt2                                                                                  |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|00793.smt2                                                                                  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|01052.smt2                                                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_AR_ab_cti_max.smt2                                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_AR_ab_fp_max.smt2                                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_Huffman_enc_ab_reg_max.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_adding.1.prop1_ab_cti_max.smt2                                                        |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|QF_UF_adding.1.prop1_ab_reg_max.smt2                                                        |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_adding.2.prop1_ab_cti_max.smt2                                                        |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|QF_UF_adding.2.prop1_ab_reg_max.smt2                                                        |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|QF_UF_adding.3.prop1_ab_reg_max.smt2                                                        |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|QF_UF_adding.4.prop1_ab_reg_max.smt2                                                        |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|QF_UF_adding.5.prop1_ab_cti_max.smt2                                                        |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|QF_UF_adding.5.prop1_ab_reg_max.smt2                                                        |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|QF_UF_adding.6.prop1_ab_cti_max.smt2                                                        |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_adding.6.prop1_ab_reg_max.smt2                                                        |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|QF_UF_anderson.1.prop1_ab_reg_max.smt2                                                      |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_anderson.2.prop1_ab_cti_max.smt2                                                      |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|QF_UF_anderson.2.prop1_ab_reg_max.smt2                                                      |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_anderson.3.prop1_ab_cti_max.smt2                                                      |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|QF_UF_anderson.3.prop1_ab_reg_max.smt2                                                      |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_anderson.5.prop1_ab_reg_max.smt2                                                      |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_anderson.6.prop1_ab_cti_max.smt2                                                      |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|QF_UF_anderson.6.prop1_ab_reg_max.smt2                                                      |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_anderson.7.prop1_ab_cti_max.smt2                                                      |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|QF_UF_anderson.7.prop1_ab_reg_max.smt2                                                      |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_at.1.prop1_ab_cti_max.smt2                                                            |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|QF_UF_at.1.prop1_ab_reg_max.smt2                                                            |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_at.2.prop1_ab_reg_max.smt2                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_at.3.prop1_ab_reg_max.smt2                                                            |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_at.4.prop1_ab_reg_max.smt2                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_at.6.prop1_ab_reg_max.smt2                                                            |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_at.7.prop1_ab_reg_max.smt2                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_bakery.2.prop1_ab_reg_max.smt2                                                        |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|QF_UF_bakery.3.prop1_ab_reg_max.smt2                                                        |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_bakery.4.prop1_ab_cti_max.smt2                                                        |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|QF_UF_bakery.6.prop1_ab_cti_max.smt2                                                        |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|QF_UF_bakery.6.prop1_ab_reg_max.smt2                                                        |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_bakery.7.prop1_ab_reg_max.smt2                                                        |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_bakery.8.prop1_ab_reg_max.smt2                                                        |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_bit-vector_ab_br_max.smt2                                                             |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_bit-vector_ab_cti_max.smt2                                                            |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_blocks.2.prop1_ab_cti_max.smt2                                                        |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|QF_UF_blocks.4.prop1_ab_cti_max.smt2                                                        |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|QF_UF_bridge.2.prop1_ab_cti_max.smt2                                                        |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|QF_UF_bridge.3.prop1_ab_cti_max.smt2                                                        |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|QF_UF_brp.1.prop1_ab_cti_max.smt2                                                           |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|QF_UF_brp.2.prop1_ab_cti_max.smt2                                                           |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|QF_UF_brp.4.prop1_ab_cti_max.smt2                                                           |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|QF_UF_brp.5.prop1_ab_cti_max.smt2                                                           |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|QF_UF_brp2.1.prop1_ab_cti_max.smt2                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|QF_UF_brp2.1.prop2_ab_cti_max.smt2                                                          |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|QF_UF_brp2.1.prop3_ab_cti_max.smt2                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|QF_UF_brp2.2.prop1_ab_cti_max.smt2                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|QF_UF_brp2.2.prop2_ab_cti_max.smt2                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|QF_UF_brp2.2.prop3_ab_cti_max.smt2                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|QF_UF_brp2.3.prop1_ab_cti_max.smt2                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|QF_UF_brp2.3.prop2_ab_cti_max.smt2                                                          |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|QF_UF_brp2.4.prop3_ab_cti_max.smt2                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|QF_UF_brp2.5.prop1_ab_cti_max.smt2                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|QF_UF_brp2.5.prop2_ab_cti_max.smt2                                                          |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|QF_UF_brp2.5.prop3_ab_cti_max.smt2                                                          |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|QF_UF_brp2.6.prop1_ab_cti_max.smt2                                                          |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|QF_UF_brp2.6.prop2_ab_cti_max.smt2                                                          |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|QF_UF_brp2.6.prop3_ab_cti_max.smt2                                                          |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|QF_UF_bug-1_ab_reg_max.smt2                                                                 |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|QF_UF_cambridge.1.prop1_ab_cti_max.smt2                                                     |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|QF_UF_cambridge.2.prop1_ab_cti_max.smt2                                                     |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|QF_UF_cambridge.2.prop2_ab_cti_max.smt2                                                     |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|QF_UF_cambridge.3.prop1_ab_cti_max.smt2                                                     |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|QF_UF_cambridge.3.prop2_ab_cti_max.smt2                                                     |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|QF_UF_cambridge.4.prop1_ab_cti_max.smt2                                                     |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|QF_UF_cambridge.4.prop2_ab_cti_max.smt2                                                     |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|QF_UF_cambridge.5.prop1_ab_cti_max.smt2                                                     |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|QF_UF_cambridge.6.prop1_ab_cti_max.smt2                                                     |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|QF_UF_cambridge.6.prop2_ab_cti_max.smt2                                                     |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|QF_UF_cambridge.7.prop1_ab_cti_max.smt2                                                     |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|QF_UF_cambridge.7.prop2_ab_cti_max.smt2                                                     |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|QF_UF_cav14_example_v_ab_cti_max.smt2                                                       |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_collision.2.prop1_ab_cti_max.smt2                                                     |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|QF_UF_collision.3.prop1_ab_cti_max.smt2                                                     |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|QF_UF_collision.4.prop1_ab_cti_max.smt2                                                     |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|QF_UF_collision.6.prop1_ab_cti_max.smt2                                                     |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|QF_UF_counter_ab_cti_max.smt2                                                               |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_counter_ab_reg_max.smt2                                                               |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_counter_v_ab_cti_max.smt2                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_counter_v_ab_fp_max.smt2                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_cyclic_scheduler.2.prop1_ab_cti_max.smt2                                              |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|QF_UF_cyclic_scheduler.3.prop1_ab_cti_max.smt2                                              |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|QF_UF_cyclic_scheduler.4.prop1_ab_cti_max.smt2                                              |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|QF_UF_diagonal_ab_cti_max.smt2                                                              |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_diagonal_ab_reg_max.smt2                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_diagonal_v_ab_cti_max.smt2                                                            |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_diagonal_v_ab_reg_max.smt2                                                            |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_driving_phils.1.prop1_ab_reg_max.smt2                                                 |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_driving_phils.2.prop1_ab_reg_max.smt2                                                 |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_driving_phils.3.prop1_ab_reg_max.smt2                                                 |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_driving_phils.5.prop1_ab_reg_max.smt2                                                 |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_dyn_partition_ab_reg_max.smt2                                                         |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_elevator.2.prop1_ab_cti_max.smt2                                                      |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|QF_UF_elevator.3.prop1_ab_cti_max.smt2                                                      |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|QF_UF_elevator.4.prop1_ab_cti_max.smt2                                                      |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|QF_UF_elevator.5.prop1_ab_cti_max.smt2                                                      |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|QF_UF_elevator_planning.2.prop1_ab_cti_max.smt2                                             |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|QF_UF_elevator_planning.3.prop1_ab_reg_max.smt2                                             |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|QF_UF_eq_sdp_v1_ab_cti_max.smt2                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_eq_sdp_v2_ab_cti_max.smt2                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_eq_sdp_v2_ab_reg_max.smt2                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_eq_sdp_v3_ab_cti_max.smt2                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_eq_sdp_v4_ab_cti_max.smt2                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_eq_sdp_v6_ab_cti_max.smt2                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_exit.1.prop1_ab_cti_max.smt2                                                          |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|QF_UF_exit.3.prop1_ab_cti_max.smt2                                                          |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|QF_UF_extinction.1.prop1_ab_reg_max.smt2                                                    |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_extinction.3.prop1_ab_cti_max.smt2                                                    |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|QF_UF_extinction.3.prop1_ab_reg_max.smt2                                                    |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_extinction.4.prop1_ab_cti_max.smt2                                                    |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|QF_UF_extinction.4.prop1_ab_reg_max.smt2                                                    |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_fischer.1.prop1_ab_cti_max.smt2                                                       |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|QF_UF_fischer.4.prop1_ab_reg_max.smt2                                                       |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_fischer.5.prop1_ab_reg_max.smt2                                                       |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_fischer.6.prop1_ab_reg_max.smt2                                                       |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_fischer.7.prop1_ab_reg_max.smt2                                                       |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_gear.1.prop1_ab_reg_max.smt2                                                          |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_gear.1.prop2_ab_cti_max.smt2                                                          |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|QF_UF_gear.1.prop3_ab_cti_max.smt2                                                          |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|QF_UF_gear.1.prop4_ab_cti_max.smt2                                                          |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|QF_UF_gear.2.prop1_ab_reg_max.smt2                                                          |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_gear.2.prop2_ab_cti_max.smt2                                                          |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|QF_UF_gear.2.prop3_ab_cti_max.smt2                                                          |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|QF_UF_h_FIFO_ab_reg_max.smt2                                                                |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|QF_UF_h_TreeArb_ab_cti_max.smt2                                                             |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|QF_UF_h_Vending_ab_cti_max.smt2                                                             |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|QF_UF_h_b02_ab_br_max.smt2                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_h_b07_ab_reg_max.smt2                                                                 |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_hanoi.2.prop1_ab_reg_max.smt2                                                         |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|QF_UF_hanoi.3.prop1_ab_reg_max.smt2                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|QF_UF_hanoi.4.prop1_ab_reg_max.smt2                                                         |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|QF_UF_iprotocol.2.prop1_ab_cti_max.smt2                                                     |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|QF_UF_itc99_b13_ab_reg_max.smt2                                                             |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_krebs.1.prop1_ab_cti_max.smt2                                                         |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|QF_UF_krebs.2.prop1_ab_cti_max.smt2                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|QF_UF_krebs.2.prop1_ab_reg_max.smt2                                                         |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|QF_UF_krebs.3.prop1_ab_cti_max.smt2                                                         |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|QF_UF_krebs.3.prop1_ab_reg_max.smt2                                                         |   0.014s  |   0.014s  |   0.000s  | 0.0%|
|QF_UF_krebs.4.prop1_ab_cti_max.smt2                                                         |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|QF_UF_krebs.4.prop1_ab_reg_max.smt2                                                         |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|QF_UF_lamport.1.prop1_ab_reg_max.smt2                                                       |   0.013s  |   0.013s  |   0.000s  | 0.0%|
|QF_UF_lamport.2.prop1_ab_cti_max.smt2                                                       |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|QF_UF_lamport.2.prop1_ab_reg_max.smt2                                                       |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_lamport.5.prop1_ab_cti_max.smt2                                                       |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|QF_UF_lamport.6.prop1_ab_reg_max.smt2                                                       |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_lamport.7.prop1_ab_cti_max.smt2                                                       |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|QF_UF_lamport.8.prop1_ab_cti_max.smt2                                                       |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|QF_UF_lamport_nonatomic.1.prop1_ab_cti_max.smt2                                             |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|QF_UF_lamport_nonatomic.1.prop1_ab_reg_max.smt2                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|QF_UF_lamport_nonatomic.2.prop1_ab_cti_max.smt2                                             |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|QF_UF_lamport_nonatomic.2.prop1_ab_reg_max.smt2                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_lamport_nonatomic.3.prop1_ab_cti_max.smt2                                             |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|QF_UF_lamport_nonatomic.4.prop1_ab_reg_max.smt2                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_lann.1.prop1_ab_cti_max.smt2                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|QF_UF_lann.1.prop1_ab_reg_max.smt2                                                          |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|QF_UF_lann.2.prop1_ab_cti_max.smt2                                                          |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|QF_UF_lann.2.prop1_ab_reg_max.smt2                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|QF_UF_lann.3.prop1_ab_cti_max.smt2                                                          |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|QF_UF_lann.5.prop1_ab_reg_max.smt2                                                          |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|QF_UF_lann.6.prop1_ab_reg_max.smt2                                                          |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|QF_UF_lann.7.prop1_ab_reg_max.smt2                                                          |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|QF_UF_leader_election.1.prop1_ab_cti_max.smt2                                               |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|QF_UF_leader_election.2.prop1_ab_reg_max.smt2                                               |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_leader_election.5.prop1_ab_reg_max.smt2                                               |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|QF_UF_leader_election.6.prop1_ab_reg_max.smt2                                               |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|QF_UF_leader_filters.1.prop1_ab_cti_max.smt2                                                |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|QF_UF_leader_filters.1.prop1_ab_reg_max.smt2                                                |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_leader_filters.2.prop1_ab_reg_max.smt2                                                |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_leader_filters.3.prop1_ab_reg_max.smt2                                                |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_leader_filters.4.prop1_ab_reg_max.smt2                                                |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_leader_filters.5.prop1_ab_reg_max.smt2                                                |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_lifts.1.prop1_ab_cti_max.smt2                                                         |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|QF_UF_lifts.2.prop1_ab_cti_max.smt2                                                         |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|QF_UF_loyd.3.prop1_ab_cti_max.smt2                                                          |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|QF_UF_lup.1.prop1_ab_cti_max.smt2                                                           |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|QF_UF_lup.2.prop1_ab_cti_max.smt2                                                           |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|QF_UF_lup.3.prop1_ab_cti_max.smt2                                                           |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|QF_UF_lup.4.prop1_ab_cti_max.smt2                                                           |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|QF_UF_mcs.1.prop1_ab_cti_max.smt2                                                           |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|QF_UF_mcs.3.prop1_ab_cti_max.smt2                                                           |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|QF_UF_mcs.3.prop1_ab_reg_max.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_mcs.4.prop1_ab_reg_max.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_mcs.5.prop1_ab_reg_max.smt2                                                           |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|QF_UF_mcs.6.prop1_ab_reg_max.smt2                                                           |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_miim_ab_reg_max.smt2                                                                  |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|QF_UF_mpeg_ab_reg_max.smt2                                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_msmie.1.prop1_ab_cti_max.smt2                                                         |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|QF_UF_needham.1.prop1_ab_cti_max.smt2                                                       |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|QF_UF_needham.1.prop2_ab_cti_max.smt2                                                       |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|QF_UF_needham.1.prop3_ab_cti_max.smt2                                                       |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|QF_UF_needham.2.prop1_ab_cti_max.smt2                                                       |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|QF_UF_needham.2.prop3_ab_cti_max.smt2                                                       |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|QF_UF_needham.3.prop1_ab_cti_max.smt2                                                       |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|QF_UF_needham.3.prop2_ab_cti_max.smt2                                                       |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|QF_UF_needham.3.prop3_ab_cti_max.smt2                                                       |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|QF_UF_needham.3.prop4_ab_cti_max.smt2                                                       |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|QF_UF_needham.4.prop2_ab_cti_max.smt2                                                       |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|QF_UF_needham.4.prop3_ab_cti_max.smt2                                                       |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|QF_UF_needham.4.prop4_ab_cti_max.smt2                                                       |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|QF_UF_paper_v3_ab_cti_max.smt2                                                              |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|QF_UF_peg_solitaire.1.prop1_ab_reg_max.smt2                                                 |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|QF_UF_peg_solitaire.4.prop1_ab_reg_max.smt2                                                 |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|QF_UF_peg_solitaire.5.prop1_ab_reg_max.smt2                                                 |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|QF_UF_peg_solitaire.6.prop1_ab_cti_max.smt2                                                 |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|QF_UF_peg_solitaire.6.prop1_ab_reg_max.smt2                                                 |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|QF_UF_peterson.1.prop1_ab_cti_max.smt2                                                      |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|QF_UF_peterson.2.prop1_ab_reg_max.smt2                                                      |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_peterson.3.prop1_ab_cti_max.smt2                                                      |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|QF_UF_peterson.3.prop1_ab_reg_max.smt2                                                      |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_peterson.4.prop1_ab_cti_max.smt2                                                      |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|QF_UF_peterson.4.prop1_ab_reg_max.smt2                                                      |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_peterson.5.prop1_ab_reg_max.smt2                                                      |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|QF_UF_peterson.6.prop1_ab_cti_max.smt2                                                      |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|QF_UF_peterson.6.prop1_ab_reg_max.smt2                                                      |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_peterson.7.prop1_ab_reg_max.smt2                                                      |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|QF_UF_pgm_protocol.1.prop5_ab_reg_max.smt2                                                  |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_pgm_protocol.3.prop5_ab_reg_max.smt2                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_pgm_protocol.5.prop5_ab_reg_max.smt2                                                  |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|QF_UF_pgm_protocol.8.prop5_ab_reg_max.smt2                                                  |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_pipeline_ab_reg_max.smt2                                                              |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_pj_icu_ab_fp_max.smt2                                                                 |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|QF_UF_plc.2.prop2_ab_reg_max.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|QF_UF_plc.3.prop2_ab_reg_max.smt2                                                           |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|QF_UF_plc.4.prop2_ab_reg_max.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_production_cell.2.prop1_ab_cti_max.smt2                                               |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|QF_UF_production_cell.3.prop1_ab_reg_max.smt2                                               |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_production_cell.6.prop1_ab_reg_max.smt2                                               |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|QF_UF_protocols.1.prop1_ab_cti_max.smt2                                                     |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|QF_UF_protocols.2.prop1_ab_cti_max.smt2                                                     |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|QF_UF_protocols.3.prop1_ab_cti_max.smt2                                                     |   0.020s  |   0.020s  |   0.000s  | 0.0%|
|QF_UF_protocols.4.prop1_ab_cti_max.smt2                                                     |   0.019s  |   0.019s  |   0.000s  | 0.0%|
|QF_UF_reader_writer.1.prop1_ab_cti_max.smt2                                                 |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|QF_UF_reader_writer.2.prop1_ab_cti_max.smt2                                                 |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|QF_UF_resistance.2.prop1_ab_cti_max.smt2                                                    |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|QF_UF_resistance.2.prop3_ab_reg_max.smt2                                                    |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|QF_UF_rether.1.prop1_ab_cti_max.smt2                                                        |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|QF_UF_rether.2.prop1_ab_cti_max.smt2                                                        |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|QF_UF_rether.3.prop1_ab_cti_max.smt2                                                        |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|QF_UF_schedule_world.1.prop1_ab_cti_max.smt2                                                |   0.015s  |   0.015s  |   0.000s  | 0.0%|
|QF_UF_schedule_world.2.prop1_ab_cti_max.smt2                                                |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|QF_UF_schedule_world.3.prop1_ab_reg_max.smt2                                                |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|QF_UF_seq_ab_cti_max.smt2                                                                   |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_sw_ball2001_ab_cti_max.smt2                                                           |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_sw_ball2004_1_ab_cti_max.smt2                                                         |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_sw_ball2004_2_ab_cti_max.smt2                                                         |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_sw_loop_ab_cti_max.smt2                                                               |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_sw_loop_ab_fp_max.smt2                                                                |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_sw_loop_v_ab_cti_max.smt2                                                             |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_sw_state_machine_ab_cti_max.smt2                                                      |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_sw_sym_ex_ab_cti_max.smt2                                                             |   0.011s  |   0.011s  |   0.000s  | 0.0%|
|QF_UF_sw_sym_ex_v_ab_cti_max.smt2                                                           |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_swap_three_ab_br_max.smt2                                                             |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|QF_UF_swap_three_ab_cti_max.smt2                                                            |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_swap_two_ab_br_max.smt2                                                               |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_swap_two_ab_cti_max.smt2                                                              |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_synabs2_ab_cti_max.smt2                                                               |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_synabs2_ab_reg_max.smt2                                                               |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_synapse.1.prop1_ab_cti_max.smt2                                                       |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|QF_UF_synapse.2.prop1_ab_cti_max.smt2                                                       |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|QF_UF_szymanski.1.prop1_ab_cti_max.smt2                                                     |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|QF_UF_szymanski.1.prop1_ab_reg_max.smt2                                                     |   0.009s  |   0.009s  |   0.000s  | 0.0%|
|QF_UF_szymanski.2.prop1_ab_reg_max.smt2                                                     |   0.010s  |   0.010s  |   0.000s  | 0.0%|
|QF_UF_szymanski.3.prop1_ab_cti_max.smt2                                                     |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|QF_UF_szymanski.3.prop1_ab_reg_max.smt2                                                     |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|QF_UF_szymanski.4.prop1_ab_reg_max.smt2                                                     |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|QF_UF_szymanski.5.prop1_ab_reg_max.smt2                                                     |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|QF_UF_telephony.1.prop1_ab_cti_max.smt2                                                     |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|QF_UF_telephony.4.prop1_ab_cti_max.smt2                                                     |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|QF_UF_telephony.5.prop1_ab_cti_max.smt2                                                     |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|QF_UF_telephony.7.prop1_ab_cti_max.smt2                                                     |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|QF_UF_telephony.8.prop1_ab_cti_max.smt2                                                     |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|QF_UF_train-gate.2.prop1_ab_cti_max.smt2                                                    |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|QF_UF_train-gate.3.prop1_ab_cti_max.smt2                                                    |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|QF_UF_train-gate.4.prop1_ab_cti_max.smt2                                                    |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|QF_UF_train-gate.7.prop1_ab_cti_max.smt2                                                    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|QF_UF_v_DAIO_ab_br_max.smt2                                                                 |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|QF_UF_v_DAIO_ab_reg_max.smt2                                                                |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|iso_brn068.smt2                                                                             |   0.012s  |   0.012s  |   0.000s  | 0.0%|
|iso_brn069.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|iso_brn071.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|iso_brn096.smt2                                                                             |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|iso_brn1088.smt2                                                                            |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|iso_brn1240.smt2                                                                            |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|iso_brn1242.smt2                                                                            |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|iso_brn1283.smt2                                                                            |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|iso_brn175.smt2                                                                             |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|iso_brn176.smt2                                                                             |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|iso_brn222.smt2                                                                             |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|iso_brn509.smt2                                                                             |   0.017s  |   0.017s  |   0.000s  | 0.0%|
|iso_brn510.smt2                                                                             |   0.018s  |   0.018s  |   0.000s  | 0.0%|
|smt2831655880469397696.smt2                                                                 |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|smt3232867547761696161.smt2                                                                 |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|smt3248576982810563470.smt2                                                                 |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|smt3508124013603727984.smt2                                                                 |   0.008s  |   0.008s  |   0.000s  | 0.0%|
|smt3910673230463462036.smt2                                                                 |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|smt4027072204816894856.smt2                                                                 |   0.006s  |   0.006s  |   0.000s  | 0.0%|
|smt4480564921249140261.smt2                                                                 |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|smt6109211130895037835.smt2                                                                 |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|smt6377531776677660648.smt2                                                                 |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|smt834303034702425531.smt2                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
|smt862177804180920815.smt2                                                                  |   0.007s  |   0.007s  |   0.000s  | 0.0%|
</details>
