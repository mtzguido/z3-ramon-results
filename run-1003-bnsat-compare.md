Comparing data and data


# SUMMARY
- LHS tests = 1147
- RHS tests = 1147
- LHS success = 1147  (100.0%)
- RHS success = 1147  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: use has_real_monomial as the gate to bounded nlsat
Job tag: bnsat
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: e62d4e9d50ad91d0ba940dd95d2fb4c377b8c954
Z3 branch: bnsat
Z3 options: "-T:200 "
Z3 inputs: inputs/QF_NRA_small
Z3 commit message: Gate early bounded_nlsat on real monomials, remove parameter

Only call bounded_nlsat before the lemma return when the to-refine
set contains real (non-integer) monomials. Integer NLA problems are
better served by the lemma pipeline; calling nlsat drains the rlimit
budget without benefit. For real NLA (QF_NRA, QF_UFNRA, QF_NIRA with
reals), nlsat via CAD is the right approach when bounds propagation
is not converging.

Remove the arith.nl.nra_before_lemma_return parameter since the
has_real_monomial() gate is precise enough.

Co-authored-by: Copilot <223556219+Copilot@users.noreply.github.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: use has_real_monomial as the gate to bounded nlsat
Job tag: bnsat
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: e62d4e9d50ad91d0ba940dd95d2fb4c377b8c954
Z3 branch: bnsat
Z3 options: "-T:200 "
Z3 inputs: inputs/QF_NRA_small
Z3 commit message: Gate early bounded_nlsat on real monomials, remove parameter

Only call bounded_nlsat before the lemma return when the to-refine
set contains real (non-integer) monomials. Integer NLA problems are
better served by the lemma pipeline; calling nlsat drains the rlimit
budget without benefit. For real NLA (QF_NRA, QF_UFNRA, QF_NIRA with
reals), nlsat via CAD is the right approach when bounds propagation
is not converging.

Remove the arith.nl.nra_before_lemma_return parameter since the
has_real_monomial() gate is precise enough.

Co-authored-by: Copilot <223556219+Copilot@users.noreply.github.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|2013POPL-BenAmGen-Ex4.2.bpl_Iteration1_Loop_2-pieceTemplate.smt2                            |  14.178s  |  14.178s  |   0.000s  | 0.0%|
|Arthan1A-chunk-0020.smt2                                                                    |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|ArthanKM2-chunk-0002.smt2                                                                   |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|ArthanM2-chunk-0012.smt2                                                                    |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|Ben-Amram-2010LMCS-Ex2.3_true-termination.c_Iteration1_Lasso_7-phaseTemplate.smt2           |   1.233s  |   1.233s  |   0.000s  | 0.0%|
|BenAmram-2010LMCS-Ex2.3.bpl_Iteration1_Lasso_2-pieceTemplate.smt2                           |  52.910s  |  52.910s  |   0.000s  | 0.0%|
|Boulder.bpl_Iteration1_Loop_4-pieceTemplate.smt2                                            |  54.325s  |  54.325s  |   0.000s  | 0.0%|
|BradleyMannaSipma-2005CAV-Fig1_true-termination.c_Iteration1_Lasso_4-pieceTemplate.smt2     | 200.103s  | 200.103s  |   0.000s  | 0.0%|
|BradleyMannaSipma-2005ICALP-Fig1-deterministic.bpl_Iteration1_Lasso_7-phaseTemplate.smt2    |  14.204s  |  14.204s  |   0.000s  | 0.0%|
|BradleyMannaSipma-2005ICALP-Fig1_true-termination.c_Iteration1_Lasso_7-phaseTemplate.smt2   |  82.090s  |  82.090s  |   0.000s  | 0.0%|
|Braverman-2006CAV-Ex1-int.bpl_Iteration1_Loop_4-phaseTemplate.smt2                          |  16.378s  |  16.378s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0025.smt2                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0047.smt2                                                                  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0062.smt2                                                                  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0074.smt2                                                                  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0086.smt2                                                                  |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0096.smt2                                                                  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0108.smt2                                                                  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0122.smt2                                                                  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0137.smt2                                                                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|2013POPL-BenAmGen-Ex4.2.bpl_Iteration1_Loop_2-pieceTemplate.smt2                            |  14.178s  |  14.178s  |   0.000s  | 0.0%|
|Arthan1A-chunk-0020.smt2                                                                    |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|ArthanKM2-chunk-0002.smt2                                                                   |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|ArthanM2-chunk-0012.smt2                                                                    |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|Ben-Amram-2010LMCS-Ex2.3_true-termination.c_Iteration1_Lasso_7-phaseTemplate.smt2           |   1.233s  |   1.233s  |   0.000s  | 0.0%|
|BenAmram-2010LMCS-Ex2.3.bpl_Iteration1_Lasso_2-pieceTemplate.smt2                           |  52.910s  |  52.910s  |   0.000s  | 0.0%|
|Boulder.bpl_Iteration1_Loop_4-pieceTemplate.smt2                                            |  54.325s  |  54.325s  |   0.000s  | 0.0%|
|BradleyMannaSipma-2005CAV-Fig1_true-termination.c_Iteration1_Lasso_4-pieceTemplate.smt2     | 200.103s  | 200.103s  |   0.000s  | 0.0%|
|BradleyMannaSipma-2005ICALP-Fig1-deterministic.bpl_Iteration1_Lasso_7-phaseTemplate.smt2    |  14.204s  |  14.204s  |   0.000s  | 0.0%|
|BradleyMannaSipma-2005ICALP-Fig1_true-termination.c_Iteration1_Lasso_7-phaseTemplate.smt2   |  82.090s  |  82.090s  |   0.000s  | 0.0%|
|Braverman-2006CAV-Ex1-int.bpl_Iteration1_Loop_4-phaseTemplate.smt2                          |  16.378s  |  16.378s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0025.smt2                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0047.smt2                                                                  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0062.smt2                                                                  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0074.smt2                                                                  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0086.smt2                                                                  |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0096.smt2                                                                  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0108.smt2                                                                  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0122.smt2                                                                  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0137.smt2                                                                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|2013POPL-BenAmGen-Ex4.2.bpl_Iteration1_Loop_2-pieceTemplate.smt2                            |  14.178s  |  14.178s  |   0.000s  | 0.0%|
|Arthan1A-chunk-0020.smt2                                                                    |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|ArthanKM2-chunk-0002.smt2                                                                   |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|ArthanM2-chunk-0012.smt2                                                                    |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|Ben-Amram-2010LMCS-Ex2.3_true-termination.c_Iteration1_Lasso_7-phaseTemplate.smt2           |   1.233s  |   1.233s  |   0.000s  | 0.0%|
|BenAmram-2010LMCS-Ex2.3.bpl_Iteration1_Lasso_2-pieceTemplate.smt2                           |  52.910s  |  52.910s  |   0.000s  | 0.0%|
|Boulder.bpl_Iteration1_Loop_4-pieceTemplate.smt2                                            |  54.325s  |  54.325s  |   0.000s  | 0.0%|
|BradleyMannaSipma-2005CAV-Fig1_true-termination.c_Iteration1_Lasso_4-pieceTemplate.smt2     | 200.103s  | 200.103s  |   0.000s  | 0.0%|
|BradleyMannaSipma-2005ICALP-Fig1-deterministic.bpl_Iteration1_Lasso_7-phaseTemplate.smt2    |  14.204s  |  14.204s  |   0.000s  | 0.0%|
|BradleyMannaSipma-2005ICALP-Fig1_true-termination.c_Iteration1_Lasso_7-phaseTemplate.smt2   |  82.090s  |  82.090s  |   0.000s  | 0.0%|
|Braverman-2006CAV-Ex1-int.bpl_Iteration1_Loop_4-phaseTemplate.smt2                          |  16.378s  |  16.378s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0025.smt2                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0047.smt2                                                                  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0062.smt2                                                                  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0074.smt2                                                                  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0086.smt2                                                                  |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0096.smt2                                                                  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0108.smt2                                                                  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0122.smt2                                                                  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0137.smt2                                                                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|2013POPL-BenAmGen-Ex4.2.bpl_Iteration1_Loop_2-pieceTemplate.smt2                            |  14.178s  |  14.178s  |   0.000s  | 0.0%|
|Arthan1A-chunk-0020.smt2                                                                    |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|ArthanKM2-chunk-0002.smt2                                                                   |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|ArthanM2-chunk-0012.smt2                                                                    |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|Ben-Amram-2010LMCS-Ex2.3_true-termination.c_Iteration1_Lasso_7-phaseTemplate.smt2           |   1.233s  |   1.233s  |   0.000s  | 0.0%|
|BenAmram-2010LMCS-Ex2.3.bpl_Iteration1_Lasso_2-pieceTemplate.smt2                           |  52.910s  |  52.910s  |   0.000s  | 0.0%|
|Boulder.bpl_Iteration1_Loop_4-pieceTemplate.smt2                                            |  54.325s  |  54.325s  |   0.000s  | 0.0%|
|BradleyMannaSipma-2005CAV-Fig1_true-termination.c_Iteration1_Lasso_4-pieceTemplate.smt2     | 200.103s  | 200.103s  |   0.000s  | 0.0%|
|BradleyMannaSipma-2005ICALP-Fig1-deterministic.bpl_Iteration1_Lasso_7-phaseTemplate.smt2    |  14.204s  |  14.204s  |   0.000s  | 0.0%|
|BradleyMannaSipma-2005ICALP-Fig1_true-termination.c_Iteration1_Lasso_7-phaseTemplate.smt2   |  82.090s  |  82.090s  |   0.000s  | 0.0%|
|Braverman-2006CAV-Ex1-int.bpl_Iteration1_Loop_4-phaseTemplate.smt2                          |  16.378s  |  16.378s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0025.smt2                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0047.smt2                                                                  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0062.smt2                                                                  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0074.smt2                                                                  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0086.smt2                                                                  |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0096.smt2                                                                  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0108.smt2                                                                  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0122.smt2                                                                  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0137.smt2                                                                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|Gulwani.bpl_Iteration1_Lasso_4-pieceTemplate.smt2                                          | 200.136s |1181.0MiB|
|brp_withassume.t2.c_Iteration1_Loop_4-pieceTemplate.smt2                                   | 200.134s |1239.0MiB|
|aviad_true-termination.c_Iteration1_Loop_3-lexTemplate.smt2                                | 200.112s |1055.0MiB|
|aviad_true-termination.c_Iteration1_Loop_6-phaseTemplate.smt2                              | 200.108s |944.0MiB|
|BradleyMannaSipma-2005CAV-Fig1_true-termination.c_Iteration1_Lasso_4-pieceTemplate.smt2    | 200.103s |725.0MiB|
|etcs_braking_2.01.seq_lazy_linear_enc_global_13.smt2                                       | 200.097s |691.0MiB|
|afagp-fail.t2.c_Iteration1_Lasso_3-pieceTemplate.smt2                                      | 200.084s |639.0MiB|
|min_rf_true-termination.c_Iteration1_Loop_4-pieceTemplate.smt2                             | 200.082s |528.0MiB|
|yPositive-SIscaled50.bpl_Iteration1_Loop_4-pieceTemplate.smt2                              | 200.078s |699.0MiB|
|p-46.t2.c_Iteration2_Lasso_7-phaseTemplate.smt2                                            | 200.077s |426.0MiB|
|mbo_E19E22.smt2                                                                            | 200.072s |482.0MiB|
|efegp.t2.c_Iteration1_Lasso_3-pieceTemplate.smt2                                           | 200.069s |563.0MiB|
|LeeJonesBen-Amram-2001POPL-Ex5_true-termination.c_Iteration2_Lasso_3-pieceTemplate.smt2    | 200.063s |457.0MiB|
|mbo_E10E28.smt2                                                                            | 200.062s |512.0MiB|
|heidy7-simple.t2.c_Iteration2_Lasso_4-pieceTemplate.smt2                                   | 200.058s |436.0MiB|
|simple_ballistics_reach.01.seq_lazy_global_7.smt2                                          | 200.054s |43.556MiB|
|LeeJonesBen-Amram-2001POPL-Ex5_true-termination.c_Iteration2_Lasso_7-phaseTemplate.smt2    | 200.051s |400.0MiB|
|mbo_E3E23.smt2                                                                             | 200.046s |594.0MiB|
|kissing_3_11.smt2                                                                          | 200.041s |117.0MiB|
|matrix-4-all-13.smt2                                                                       | 200.041s |35.676MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|Gulwani.bpl_Iteration1_Lasso_4-pieceTemplate.smt2                                          | 200.136s |1181.0MiB|
|brp_withassume.t2.c_Iteration1_Loop_4-pieceTemplate.smt2                                   | 200.134s |1239.0MiB|
|aviad_true-termination.c_Iteration1_Loop_3-lexTemplate.smt2                                | 200.112s |1055.0MiB|
|aviad_true-termination.c_Iteration1_Loop_6-phaseTemplate.smt2                              | 200.108s |944.0MiB|
|BradleyMannaSipma-2005CAV-Fig1_true-termination.c_Iteration1_Lasso_4-pieceTemplate.smt2    | 200.103s |725.0MiB|
|etcs_braking_2.01.seq_lazy_linear_enc_global_13.smt2                                       | 200.097s |691.0MiB|
|afagp-fail.t2.c_Iteration1_Lasso_3-pieceTemplate.smt2                                      | 200.084s |639.0MiB|
|min_rf_true-termination.c_Iteration1_Loop_4-pieceTemplate.smt2                             | 200.082s |528.0MiB|
|yPositive-SIscaled50.bpl_Iteration1_Loop_4-pieceTemplate.smt2                              | 200.078s |699.0MiB|
|p-46.t2.c_Iteration2_Lasso_7-phaseTemplate.smt2                                            | 200.077s |426.0MiB|
|mbo_E19E22.smt2                                                                            | 200.072s |482.0MiB|
|efegp.t2.c_Iteration1_Lasso_3-pieceTemplate.smt2                                           | 200.069s |563.0MiB|
|LeeJonesBen-Amram-2001POPL-Ex5_true-termination.c_Iteration2_Lasso_3-pieceTemplate.smt2    | 200.063s |457.0MiB|
|mbo_E10E28.smt2                                                                            | 200.062s |512.0MiB|
|heidy7-simple.t2.c_Iteration2_Lasso_4-pieceTemplate.smt2                                   | 200.058s |436.0MiB|
|simple_ballistics_reach.01.seq_lazy_global_7.smt2                                          | 200.054s |43.556MiB|
|LeeJonesBen-Amram-2001POPL-Ex5_true-termination.c_Iteration2_Lasso_7-phaseTemplate.smt2    | 200.051s |400.0MiB|
|mbo_E3E23.smt2                                                                             | 200.046s |594.0MiB|
|kissing_3_11.smt2                                                                          | 200.041s |117.0MiB|
|matrix-4-all-13.smt2                                                                       | 200.041s |35.676MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|2013POPL-BenAmGen-Ex4.2.bpl_Iteration1_Loop_2-pieceTemplate.smt2                            |25.072MiB|25.072MiB|0B| 0.0%|
|Arthan1A-chunk-0020.smt2                                                                    |20.7MiB|20.7MiB|0B| 0.0%|
|ArthanKM2-chunk-0002.smt2                                                                   |20.928MiB|20.928MiB|0B| 0.0%|
|ArthanM2-chunk-0012.smt2                                                                    |18.712MiB|18.712MiB|0B| 0.0%|
|Ben-Amram-2010LMCS-Ex2.3_true-termination.c_Iteration1_Lasso_7-phaseTemplate.smt2           |43.136MiB|43.136MiB|0B| 0.0%|
|BenAmram-2010LMCS-Ex2.3.bpl_Iteration1_Lasso_2-pieceTemplate.smt2                           |56.276MiB|56.276MiB|0B| 0.0%|
|Boulder.bpl_Iteration1_Loop_4-pieceTemplate.smt2                                            |54.088MiB|54.088MiB|0B| 0.0%|
|BradleyMannaSipma-2005CAV-Fig1_true-termination.c_Iteration1_Lasso_4-pieceTemplate.smt2     |725.0MiB|725.0MiB|0B| 0.0%|
|BradleyMannaSipma-2005ICALP-Fig1-deterministic.bpl_Iteration1_Lasso_7-phaseTemplate.smt2    |31.268MiB|31.268MiB|0B| 0.0%|
|BradleyMannaSipma-2005ICALP-Fig1_true-termination.c_Iteration1_Lasso_7-phaseTemplate.smt2   |206.0MiB|206.0MiB|0B| 0.0%|
|Braverman-2006CAV-Ex1-int.bpl_Iteration1_Loop_4-phaseTemplate.smt2                          |26.98MiB|26.98MiB|0B| 0.0%|
|CMOS-opamp-chunk-0025.smt2                                                                  |20.636MiB|20.636MiB|0B| 0.0%|
|CMOS-opamp-chunk-0047.smt2                                                                  |20.588MiB|20.588MiB|0B| 0.0%|
|CMOS-opamp-chunk-0062.smt2                                                                  |20.796MiB|20.796MiB|0B| 0.0%|
|CMOS-opamp-chunk-0074.smt2                                                                  |20.676MiB|20.676MiB|0B| 0.0%|
|CMOS-opamp-chunk-0086.smt2                                                                  |20.816MiB|20.816MiB|0B| 0.0%|
|CMOS-opamp-chunk-0096.smt2                                                                  |20.82MiB|20.82MiB|0B| 0.0%|
|CMOS-opamp-chunk-0108.smt2                                                                  |20.98MiB|20.98MiB|0B| 0.0%|
|CMOS-opamp-chunk-0122.smt2                                                                  |21.0MiB|21.0MiB|0B| 0.0%|
|CMOS-opamp-chunk-0137.smt2                                                                  |20.708MiB|20.708MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|2013POPL-BenAmGen-Ex4.2.bpl_Iteration1_Loop_2-pieceTemplate.smt2                            |25.072MiB|25.072MiB|0B| 0.0%|
|Arthan1A-chunk-0020.smt2                                                                    |20.7MiB|20.7MiB|0B| 0.0%|
|ArthanKM2-chunk-0002.smt2                                                                   |20.928MiB|20.928MiB|0B| 0.0%|
|ArthanM2-chunk-0012.smt2                                                                    |18.712MiB|18.712MiB|0B| 0.0%|
|Ben-Amram-2010LMCS-Ex2.3_true-termination.c_Iteration1_Lasso_7-phaseTemplate.smt2           |43.136MiB|43.136MiB|0B| 0.0%|
|BenAmram-2010LMCS-Ex2.3.bpl_Iteration1_Lasso_2-pieceTemplate.smt2                           |56.276MiB|56.276MiB|0B| 0.0%|
|Boulder.bpl_Iteration1_Loop_4-pieceTemplate.smt2                                            |54.088MiB|54.088MiB|0B| 0.0%|
|BradleyMannaSipma-2005CAV-Fig1_true-termination.c_Iteration1_Lasso_4-pieceTemplate.smt2     |725.0MiB|725.0MiB|0B| 0.0%|
|BradleyMannaSipma-2005ICALP-Fig1-deterministic.bpl_Iteration1_Lasso_7-phaseTemplate.smt2    |31.268MiB|31.268MiB|0B| 0.0%|
|BradleyMannaSipma-2005ICALP-Fig1_true-termination.c_Iteration1_Lasso_7-phaseTemplate.smt2   |206.0MiB|206.0MiB|0B| 0.0%|
|Braverman-2006CAV-Ex1-int.bpl_Iteration1_Loop_4-phaseTemplate.smt2                          |26.98MiB|26.98MiB|0B| 0.0%|
|CMOS-opamp-chunk-0025.smt2                                                                  |20.636MiB|20.636MiB|0B| 0.0%|
|CMOS-opamp-chunk-0047.smt2                                                                  |20.588MiB|20.588MiB|0B| 0.0%|
|CMOS-opamp-chunk-0062.smt2                                                                  |20.796MiB|20.796MiB|0B| 0.0%|
|CMOS-opamp-chunk-0074.smt2                                                                  |20.676MiB|20.676MiB|0B| 0.0%|
|CMOS-opamp-chunk-0086.smt2                                                                  |20.816MiB|20.816MiB|0B| 0.0%|
|CMOS-opamp-chunk-0096.smt2                                                                  |20.82MiB|20.82MiB|0B| 0.0%|
|CMOS-opamp-chunk-0108.smt2                                                                  |20.98MiB|20.98MiB|0B| 0.0%|
|CMOS-opamp-chunk-0122.smt2                                                                  |21.0MiB|21.0MiB|0B| 0.0%|
|CMOS-opamp-chunk-0137.smt2                                                                  |20.708MiB|20.708MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|2013POPL-BenAmGen-Ex4.2.bpl_Iteration1_Loop_2-pieceTemplate.smt2                            |25.072MiB|25.072MiB|0B| 0.0%|
|Arthan1A-chunk-0020.smt2                                                                    |20.7MiB|20.7MiB|0B| 0.0%|
|ArthanKM2-chunk-0002.smt2                                                                   |20.928MiB|20.928MiB|0B| 0.0%|
|ArthanM2-chunk-0012.smt2                                                                    |18.712MiB|18.712MiB|0B| 0.0%|
|Ben-Amram-2010LMCS-Ex2.3_true-termination.c_Iteration1_Lasso_7-phaseTemplate.smt2           |43.136MiB|43.136MiB|0B| 0.0%|
|BenAmram-2010LMCS-Ex2.3.bpl_Iteration1_Lasso_2-pieceTemplate.smt2                           |56.276MiB|56.276MiB|0B| 0.0%|
|Boulder.bpl_Iteration1_Loop_4-pieceTemplate.smt2                                            |54.088MiB|54.088MiB|0B| 0.0%|
|BradleyMannaSipma-2005CAV-Fig1_true-termination.c_Iteration1_Lasso_4-pieceTemplate.smt2     |725.0MiB|725.0MiB|0B| 0.0%|
|BradleyMannaSipma-2005ICALP-Fig1-deterministic.bpl_Iteration1_Lasso_7-phaseTemplate.smt2    |31.268MiB|31.268MiB|0B| 0.0%|
|BradleyMannaSipma-2005ICALP-Fig1_true-termination.c_Iteration1_Lasso_7-phaseTemplate.smt2   |206.0MiB|206.0MiB|0B| 0.0%|
|Braverman-2006CAV-Ex1-int.bpl_Iteration1_Loop_4-phaseTemplate.smt2                          |26.98MiB|26.98MiB|0B| 0.0%|
|CMOS-opamp-chunk-0025.smt2                                                                  |20.636MiB|20.636MiB|0B| 0.0%|
|CMOS-opamp-chunk-0047.smt2                                                                  |20.588MiB|20.588MiB|0B| 0.0%|
|CMOS-opamp-chunk-0062.smt2                                                                  |20.796MiB|20.796MiB|0B| 0.0%|
|CMOS-opamp-chunk-0074.smt2                                                                  |20.676MiB|20.676MiB|0B| 0.0%|
|CMOS-opamp-chunk-0086.smt2                                                                  |20.816MiB|20.816MiB|0B| 0.0%|
|CMOS-opamp-chunk-0096.smt2                                                                  |20.82MiB|20.82MiB|0B| 0.0%|
|CMOS-opamp-chunk-0108.smt2                                                                  |20.98MiB|20.98MiB|0B| 0.0%|
|CMOS-opamp-chunk-0122.smt2                                                                  |21.0MiB|21.0MiB|0B| 0.0%|
|CMOS-opamp-chunk-0137.smt2                                                                  |20.708MiB|20.708MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|2013POPL-BenAmGen-Ex4.2.bpl_Iteration1_Loop_2-pieceTemplate.smt2                            |25.072MiB|25.072MiB|0B| 0.0%|
|Arthan1A-chunk-0020.smt2                                                                    |20.7MiB|20.7MiB|0B| 0.0%|
|ArthanKM2-chunk-0002.smt2                                                                   |20.928MiB|20.928MiB|0B| 0.0%|
|ArthanM2-chunk-0012.smt2                                                                    |18.712MiB|18.712MiB|0B| 0.0%|
|Ben-Amram-2010LMCS-Ex2.3_true-termination.c_Iteration1_Lasso_7-phaseTemplate.smt2           |43.136MiB|43.136MiB|0B| 0.0%|
|BenAmram-2010LMCS-Ex2.3.bpl_Iteration1_Lasso_2-pieceTemplate.smt2                           |56.276MiB|56.276MiB|0B| 0.0%|
|Boulder.bpl_Iteration1_Loop_4-pieceTemplate.smt2                                            |54.088MiB|54.088MiB|0B| 0.0%|
|BradleyMannaSipma-2005CAV-Fig1_true-termination.c_Iteration1_Lasso_4-pieceTemplate.smt2     |725.0MiB|725.0MiB|0B| 0.0%|
|BradleyMannaSipma-2005ICALP-Fig1-deterministic.bpl_Iteration1_Lasso_7-phaseTemplate.smt2    |31.268MiB|31.268MiB|0B| 0.0%|
|BradleyMannaSipma-2005ICALP-Fig1_true-termination.c_Iteration1_Lasso_7-phaseTemplate.smt2   |206.0MiB|206.0MiB|0B| 0.0%|
|Braverman-2006CAV-Ex1-int.bpl_Iteration1_Loop_4-phaseTemplate.smt2                          |26.98MiB|26.98MiB|0B| 0.0%|
|CMOS-opamp-chunk-0025.smt2                                                                  |20.636MiB|20.636MiB|0B| 0.0%|
|CMOS-opamp-chunk-0047.smt2                                                                  |20.588MiB|20.588MiB|0B| 0.0%|
|CMOS-opamp-chunk-0062.smt2                                                                  |20.796MiB|20.796MiB|0B| 0.0%|
|CMOS-opamp-chunk-0074.smt2                                                                  |20.676MiB|20.676MiB|0B| 0.0%|
|CMOS-opamp-chunk-0086.smt2                                                                  |20.816MiB|20.816MiB|0B| 0.0%|
|CMOS-opamp-chunk-0096.smt2                                                                  |20.82MiB|20.82MiB|0B| 0.0%|
|CMOS-opamp-chunk-0108.smt2                                                                  |20.98MiB|20.98MiB|0B| 0.0%|
|CMOS-opamp-chunk-0122.smt2                                                                  |21.0MiB|21.0MiB|0B| 0.0%|
|CMOS-opamp-chunk-0137.smt2                                                                  |20.708MiB|20.708MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|brp_withassume.t2.c_Iteration1_Loop_4-pieceTemplate.smt2                                   | 200.134s |1239.0MiB|
|Gulwani.bpl_Iteration1_Lasso_4-pieceTemplate.smt2                                          | 200.136s |1181.0MiB|
|aviad_true-termination.c_Iteration1_Loop_3-lexTemplate.smt2                                | 200.112s |1055.0MiB|
|mbo_E8E14.smt2                                                                             |  99.595s |948.0MiB|
|mbo_E6E19.smt2                                                                             |  62.150s |946.0MiB|
|aviad_true-termination.c_Iteration1_Loop_6-phaseTemplate.smt2                              | 200.108s |944.0MiB|
|mbo_E3E8.smt2                                                                              |  59.918s |909.0MiB|
|mbo_E1E13.smt2                                                                             |  61.313s |886.0MiB|
|mbo_E2E4.smt2                                                                              |  60.427s |880.0MiB|
|GulwaniJainKoskinen-2009PLDI-Fig1_true-termination.c_Iteration1_Lasso_3-lexTemplate.smt2   | 137.580s |867.0MiB|
|mbo_E3E13.smt2                                                                             |  62.101s |843.0MiB|
|mbo_E2E10.smt2                                                                             |  58.679s |770.0MiB|
|mbo_E12E13.smt2                                                                            |  58.753s |748.0MiB|
|BradleyMannaSipma-2005CAV-Fig1_true-termination.c_Iteration1_Lasso_4-pieceTemplate.smt2    | 200.103s |725.0MiB|
|yPositive-SIscaled50.bpl_Iteration1_Loop_4-pieceTemplate.smt2                              | 200.078s |699.0MiB|
|etcs_braking_2.01.seq_lazy_linear_enc_global_13.smt2                                       | 200.097s |691.0MiB|
|NoriSharma-2013FSE-Fig8_true-termination.c_Iteration1_Loop_7-phaseTemplate.smt2            | 155.929s |678.0MiB|
|afagp-fail.t2.c_Iteration1_Lasso_3-pieceTemplate.smt2                                      | 200.084s |639.0MiB|
|mbo_E10E18.smt2                                                                            |  58.247s |614.0MiB|
|mbo_E8E24.smt2                                                                             |  56.986s |610.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|brp_withassume.t2.c_Iteration1_Loop_4-pieceTemplate.smt2                                   | 200.134s |1239.0MiB|
|Gulwani.bpl_Iteration1_Lasso_4-pieceTemplate.smt2                                          | 200.136s |1181.0MiB|
|aviad_true-termination.c_Iteration1_Loop_3-lexTemplate.smt2                                | 200.112s |1055.0MiB|
|mbo_E8E14.smt2                                                                             |  99.595s |948.0MiB|
|mbo_E6E19.smt2                                                                             |  62.150s |946.0MiB|
|aviad_true-termination.c_Iteration1_Loop_6-phaseTemplate.smt2                              | 200.108s |944.0MiB|
|mbo_E3E8.smt2                                                                              |  59.918s |909.0MiB|
|mbo_E1E13.smt2                                                                             |  61.313s |886.0MiB|
|mbo_E2E4.smt2                                                                              |  60.427s |880.0MiB|
|GulwaniJainKoskinen-2009PLDI-Fig1_true-termination.c_Iteration1_Lasso_3-lexTemplate.smt2   | 137.580s |867.0MiB|
|mbo_E3E13.smt2                                                                             |  62.101s |843.0MiB|
|mbo_E2E10.smt2                                                                             |  58.679s |770.0MiB|
|mbo_E12E13.smt2                                                                            |  58.753s |748.0MiB|
|BradleyMannaSipma-2005CAV-Fig1_true-termination.c_Iteration1_Lasso_4-pieceTemplate.smt2    | 200.103s |725.0MiB|
|yPositive-SIscaled50.bpl_Iteration1_Loop_4-pieceTemplate.smt2                              | 200.078s |699.0MiB|
|etcs_braking_2.01.seq_lazy_linear_enc_global_13.smt2                                       | 200.097s |691.0MiB|
|NoriSharma-2013FSE-Fig8_true-termination.c_Iteration1_Loop_7-phaseTemplate.smt2            | 155.929s |678.0MiB|
|afagp-fail.t2.c_Iteration1_Lasso_3-pieceTemplate.smt2                                      | 200.084s |639.0MiB|
|mbo_E10E18.smt2                                                                            |  58.247s |614.0MiB|
|mbo_E8E24.smt2                                                                             |  56.986s |610.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|2013POPL-BenAmGen-Ex4.2.bpl_Iteration1_Loop_2-pieceTemplate.smt2                            |  14.178s  |  14.178s  |   0.000s  | 0.0%|
|Arthan1A-chunk-0020.smt2                                                                    |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|ArthanKM2-chunk-0002.smt2                                                                   |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|ArthanM2-chunk-0012.smt2                                                                    |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|Ben-Amram-2010LMCS-Ex2.3_true-termination.c_Iteration1_Lasso_7-phaseTemplate.smt2           |   1.233s  |   1.233s  |   0.000s  | 0.0%|
|BenAmram-2010LMCS-Ex2.3.bpl_Iteration1_Lasso_2-pieceTemplate.smt2                           |  52.910s  |  52.910s  |   0.000s  | 0.0%|
|Boulder.bpl_Iteration1_Loop_4-pieceTemplate.smt2                                            |  54.325s  |  54.325s  |   0.000s  | 0.0%|
|BradleyMannaSipma-2005CAV-Fig1_true-termination.c_Iteration1_Lasso_4-pieceTemplate.smt2     | 200.103s  | 200.103s  |   0.000s  | 0.0%|
|BradleyMannaSipma-2005ICALP-Fig1-deterministic.bpl_Iteration1_Lasso_7-phaseTemplate.smt2    |  14.204s  |  14.204s  |   0.000s  | 0.0%|
|BradleyMannaSipma-2005ICALP-Fig1_true-termination.c_Iteration1_Lasso_7-phaseTemplate.smt2   |  82.090s  |  82.090s  |   0.000s  | 0.0%|
|Braverman-2006CAV-Ex1-int.bpl_Iteration1_Loop_4-phaseTemplate.smt2                          |  16.378s  |  16.378s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0025.smt2                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0047.smt2                                                                  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0062.smt2                                                                  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0074.smt2                                                                  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0086.smt2                                                                  |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0096.smt2                                                                  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0108.smt2                                                                  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0122.smt2                                                                  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0137.smt2                                                                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0148.smt2                                                                  |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0158.smt2                                                                  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0169.smt2                                                                  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0180.smt2                                                                  |   0.265s  |   0.265s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0190.smt2                                                                  |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0200.smt2                                                                  |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0213.smt2                                                                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0231.smt2                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0246.smt2                                                                  |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0260.smt2                                                                  |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0275.smt2                                                                  |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0286.smt2                                                                  |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0298.smt2                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0310.smt2                                                                  |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0320.smt2                                                                  |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0332.smt2                                                                  |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|CMOS-opamp-chunk-0342.smt2                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|CONVOI2-chunk-0018.smt2                                                                     |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|CONVOI2-chunk-0031.smt2                                                                     |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|CONVOI2-chunk-0041.smt2                                                                     |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|Canberra.bpl_Iteration1_Loop_2-pieceTemplate.smt2                                           |   0.590s  |   0.590s  |   0.000s  | 0.0%|
|Chua-1-IL-L-chunk-0016.smt2                                                                 |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|Chua-1-IL-L-chunk-0030.smt2                                                                 |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|Chua-1-IL-L-chunk-0042.smt2                                                                 |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|Chua-1-IL-L-chunk-0054.smt2                                                                 |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|Chua-1-IL-L-chunk-0066.smt2                                                                 |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|Chua-1-IL-L-chunk-0078.smt2                                                                 |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|Chua-1-IL-L-chunk-0090.smt2                                                                 |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|Chua-1-IL-L-chunk-0104.smt2                                                                 |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|Chua-1-IL-L-chunk-0117.smt2                                                                 |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|Chua-1-IL-L-chunk-0129.smt2                                                                 |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|Chua-1-IL-L-chunk-0143.smt2                                                                 |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|Chua-1-IL-L-chunk-0154.smt2                                                                 |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|Chua-1-IL-U-chunk-0025.smt2                                                                 |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|Chua-1-IL-U-chunk-0038.smt2                                                                 |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|Chua-1-IL-U-chunk-0049.smt2                                                                 |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|Chua-1-IL-U-chunk-0063.smt2                                                                 |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|Chua-1-IL-U-chunk-0076.smt2                                                                 |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|Chua-1-VC1-L-chunk-0019.smt2                                                                |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|Chua-1-VC1-L-chunk-0035.smt2                                                                |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|Chua-1-VC1-L-chunk-0046.smt2                                                                |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|Chua-1-VC1-L-chunk-0057.smt2                                                                |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|Chua-1-VC1-L-chunk-0070.smt2                                                                |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|Chua-1-VC1-L-chunk-0081.smt2                                                                |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|Chua-1-VC1-L-chunk-0093.smt2                                                                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|Chua-1-VC1-L-chunk-0107.smt2                                                                |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|Chua-1-VC1-L-chunk-0120.smt2                                                                |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|Chua-1-VC1-L-chunk-0132.smt2                                                                |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|Chua-1-VC1-L-chunk-0146.smt2                                                                |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|Chua-1-VC1-L-chunk-0160.smt2                                                                |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|Chua-1-VC1-U-chunk-0032.smt2                                                                |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|Chua-1-VC1-U-chunk-0044.smt2                                                                |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|Chua-1-VC1-U-chunk-0056.smt2                                                                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|Chua-1-VC1-U-chunk-0072.smt2                                                                |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|Chua-1-VC1-U-chunk-0083.smt2                                                                |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|Chua-1-VC2-L-chunk-0027.smt2                                                                |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|Chua-1-VC2-L-chunk-0039.smt2                                                                |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|Chua-1-VC2-L-chunk-0050.smt2                                                                |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|Chua-1-VC2-L-chunk-0064.smt2                                                                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|Chua-1-VC2-L-chunk-0077.smt2                                                                |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|Chua-1-VC2-U-chunk-0024.smt2                                                                |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|Chua-1-VC2-U-chunk-0038.smt2                                                                |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|Chua-1-VC2-U-chunk-0050.smt2                                                                |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|Chua-1-VC2-U-chunk-0061.smt2                                                                |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|Chua-1-VC2-U-chunk-0073.smt2                                                                |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|Chua-1-VC2-U-chunk-0086.smt2                                                                |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|Chua-1-VC2-U-chunk-0097.smt2                                                                |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|Chua-1-VC2-U-chunk-0113.smt2                                                                |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|Chua-1-VC2-U-chunk-0123.smt2                                                                |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|Chua-1-VC2-U-chunk-0135.smt2                                                                |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|Chua-1-VC2-U-chunk-0149.smt2                                                                |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|Chua-2-IL-L-chunk-0005.smt2                                                                 |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|Chua-2-IL-L-chunk-0021.smt2                                                                 |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|Chua-2-IL-L-chunk-0037.smt2                                                                 |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|Chua-2-IL-L-chunk-0047.smt2                                                                 |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|Chua-2-IL-L-chunk-0058.smt2                                                                 |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|Chua-2-IL-L-chunk-0072.smt2                                                                 |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|Chua-2-IL-L-chunk-0082.smt2                                                                 |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|Chua-2-IL-L-chunk-0093.smt2                                                                 |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|Chua-2-IL-L-chunk-0104.smt2                                                                 |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|Chua-2-IL-U-chunk-0009.smt2                                                                 |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|Chua-2-IL-U-chunk-0021.smt2                                                                 |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|Chua-2-IL-U-chunk-0032.smt2                                                                 |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|Chua-2-IL-U-chunk-0042.smt2                                                                 |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|Chua-2-IL-U-chunk-0053.smt2                                                                 |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|Chua-2-IL-U-chunk-0067.smt2                                                                 |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|Chua-2-IL-U-chunk-0083.smt2                                                                 |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|Chua-2-IL-U-chunk-0094.smt2                                                                 |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|Chua-2-IL-U-chunk-0107.smt2                                                                 |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|Chua-2-IL-U-chunk-0123.smt2                                                                 |   1.616s  |   1.616s  |   0.000s  | 0.0%|
|Chua-2-VC1-L-chunk-0036.smt2                                                                |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|Chua-2-VC1-L-chunk-0052.smt2                                                                |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|Chua-2-VC1-L-chunk-0062.smt2                                                                |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|Chua-2-VC1-L-chunk-0073.smt2                                                                |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|Chua-2-VC1-L-chunk-0086.smt2                                                                |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|Chua-2-VC1-L-chunk-0097.smt2                                                                |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|Chua-2-VC1-L-chunk-0108.smt2                                                                |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|Chua-2-VC1-L-chunk-0119.smt2                                                                |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|Chua-2-VC1-U-chunk-0013.smt2                                                                |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|Chua-2-VC1-U-chunk-0024.smt2                                                                |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|Chua-2-VC1-U-chunk-0035.smt2                                                                |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|Chua-2-VC1-U-chunk-0045.smt2                                                                |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|Chua-2-VC1-U-chunk-0058.smt2                                                                |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|Chua-2-VC1-U-chunk-0071.smt2                                                                |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|Chua-2-VC1-U-chunk-0087.smt2                                                                |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|Chua-2-VC1-U-chunk-0098.smt2                                                                |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|Chua-2-VC1-U-chunk-0117.smt2                                                                |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|Chua-2-VC2-L-chunk-0013.smt2                                                                |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|Chua-2-VC2-L-chunk-0029.smt2                                                                |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|Chua-2-VC2-L-chunk-0040.smt2                                                                |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|Chua-2-VC2-L-chunk-0052.smt2                                                                |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|Chua-2-VC2-L-chunk-0062.smt2                                                                |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|Chua-2-VC2-U-chunk-0018.smt2                                                                |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|Chua-2-VC2-U-chunk-0029.smt2                                                                |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|Chua-2-VC2-U-chunk-0039.smt2                                                                |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|Chua-2-VC2-U-chunk-0051.smt2                                                                |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|Chua-2-VC2-U-chunk-0066.smt2                                                                |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|Chua-2-VC2-U-chunk-0086.smt2                                                                |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|Chua-2-VC2-U-chunk-0097.smt2                                                                |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|Chua-2-VC2-U-chunk-0111.smt2                                                                |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|Chua-2-VC2-U-chunk-0127.smt2                                                                |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|Collatz.bpl_Iteration1_Lasso_2-pieceTemplate.smt2                                           |  64.858s  |  64.858s  |   0.000s  | 0.0%|
|Collatz.bpl_Iteration1_Lasso_6-nestedTemplate.smt2                                          |  49.648s  |  49.648s  |   0.000s  | 0.0%|
|Collatz.bpl_Iteration1_Loop_3-nestedTemplate.smt2                                           |  44.797s  |  44.797s  |   0.000s  | 0.0%|
|Collatz.bpl_Iteration1_Loop_6-phaseTemplate.smt2                                            |  48.737s  |  48.737s  |   0.000s  | 0.0%|
|CookSeeZuleger-2013TACAS-Fig3_true-termination.c_Iteration1_Loop_5-phaseTemplate.smt2       |   0.639s  |   0.639s  |   0.000s  | 0.0%|
|CookSeeZuleger-2013TACAS-Fig7a_true-termination.c_Iteration1_Loop_5-phaseTemplate.smt2      |   0.951s  |   0.951s  |   0.000s  | 0.0%|
|CookSeeZuleger-2013TACAS-Fig7b.bpl_Iteration1_Loop_3-pieceTemplate.smt2                     |  54.380s  |  54.380s  |   0.000s  | 0.0%|
|Garmisch.bpl_Iteration1_Loop_4-pieceTemplate.smt2                                           |  20.556s  |  20.556s  |   0.000s  | 0.0%|
|Gulwani.bpl_Iteration1_Lasso_4-pieceTemplate.smt2                                           | 200.136s  | 200.136s  |   0.000s  | 0.0%|
|GulwaniJainKoskinen-2009PLDI-Fig1_true-termination.c_Iteration1_Lasso_3-lexTemplate.smt2    | 137.580s  | 137.580s  |   0.000s  | 0.0%|
|GulwaniJainKoskinen-2009PLDI-Fig1_true-termination.c_Iteration1_Lasso_6-nestedTemplate.smt2  | 113.241s  | 113.241s  |   0.000s  | 0.0%|
|InVarSynth_BugHoareAnnotationWithMinimiation.bpl_Iteration1_0.smt2                          | 200.015s  | 200.015s  |   0.000s  | 0.0%|
|InVarSynth_LabelEncodingWithUnrolling.bpl_Iteration2_0.smt2                                 |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|InVarSynth_PostfixIncrementDecrement.c_Iteration3_0.smt2                                    |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|InVarSynth_ShortCircuit-SideEffect-SwitchStatement-Safe.c_Iteration1_0.smt2                 |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|InVarSynth_doubleLoopUniformIterations.bpl_Iteration2_0.smt2                                |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|InVarSynth_threadpooling_out2.mover.bpl_Iteration2_0.smt2                                   | 200.020s  | 200.020s  |   0.000s  | 0.0%|
|KroeningSharyginaTsitovichWintersteiger-2010CAV-Fig1_true-termination.c_Iteration1_Lasso_4-lexTemplate.smt2  |  71.341s  |  71.341s  |   0.000s  | 0.0%|
|KroeningSharyginaTsitovichWintersteiger-2010CAV-Fig1_true-termination.c_Iteration1_Lasso_affineTemplate.smt2  |   4.987s  |   4.987s  |   0.000s  | 0.0%|
|LeeJonesBen-Amram-2001POPL-Ex1_true-termination.c_Iteration1_Loop_7-phaseTemplate.smt2      |  70.907s  |  70.907s  |   0.000s  | 0.0%|
|LeeJonesBen-Amram-2001POPL-Ex4_true-termination.c_Iteration2_Loop_3-pieceTemplate.smt2      |  58.440s  |  58.440s  |   0.000s  | 0.0%|
|LeeJonesBen-Amram-2001POPL-Ex5_true-termination.c_Iteration2_Lasso_3-pieceTemplate.smt2     | 200.063s  | 200.063s  |   0.000s  | 0.0%|
|LeeJonesBen-Amram-2001POPL-Ex5_true-termination.c_Iteration2_Lasso_7-phaseTemplate.smt2     | 200.051s  | 200.051s  |   0.000s  | 0.0%|
|Lobnya-Boolean-Reordered.bpl_Iteration1_Loop_4-pieceTemplate.smt2                           |  37.824s  |  37.824s  |   0.000s  | 0.0%|
|Lyapunov1a-chunk-0011.smt2                                                                  |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|Lyapunov1a-chunk-0021.smt2                                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|Lyapunov1a-chunk-0032.smt2                                                                  |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|Lyapunov1a-chunk-0042.smt2                                                                  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|Masse_true-termination.c_Iteration1_Loop_2-pieceTemplate.smt2                               |  58.091s  |  58.091s  |   0.000s  | 0.0%|
|MulliganEconomicsModel0006a.smt2                                                            |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|MulliganEconomicsModel0013c.smt2                                                            |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|MulliganEconomicsModel0018e.smt2                                                            |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|MulliganEconomicsModel0024a.smt2                                                            |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|MulliganEconomicsModel0027c.smt2                                                            |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|MulliganEconomicsModel0030e.smt2                                                            |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|MulliganEconomicsModel0054a.smt2                                                            |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|MulliganEconomicsModel0057c.smt2                                                            |  18.625s  |  18.625s  |   0.000s  | 0.0%|
|MulliganEconomicsModel0063e.smt2                                                            |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|MulliganEconomicsModel0067a.smt2                                                            |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|MulliganEconomicsModel0077c.smt2                                                            |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|MulliganEconomicsModel0080e.smt2                                                            |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|MulliganEconomicsModel0085a.smt2                                                            |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|Mysore2.bpl_Iteration1_Loop_3-pieceTemplate.smt2                                            |  32.926s  |  32.926s  |   0.000s  | 0.0%|
|Nichols-Plot-Inverted-Pendulum-Fails-1-6-chunk-0024.smt2                                    |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|Nichols-Plot-Inverted-Pendulum-Fails-1-6-chunk-0036.smt2                                    |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|Nichols-Plot-Inverted-Pendulum-Fails-1-6-chunk-0054.smt2                                    |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|Nichols-Plot-Inverted-Pendulum-Fails-1-6-chunk-0078.smt2                                    |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|Nichols-Plot-Inverted-Pendulum-Fails-1-6-chunk-0098.smt2                                    |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|Nichols-Plot-Inverted-Pendulum-Fails-1-6-chunk-0117.smt2                                    |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|Nichols-Plot-Inverted-Pendulum-Fails-1-6-chunk-0137.smt2                                    |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|Nichols-Plot-Inverted-Pendulum-Fails-1-6-chunk-0156.smt2                                    |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|Nichols-Plot-Inverted-Pendulum-Fails-1-6-chunk-0173.smt2                                    |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|Nichols-Plot-Inverted-Pendulum-Fails-1-6-chunk-0190.smt2                                    |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|Nichols-Plot-Inverted-Pendulum-Fails-1-6-chunk-0205.smt2                                    |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|Nichols-Plot-Inverted-Pendulum-Fails-1-6-chunk-0224.smt2                                    |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|Nichols-Plot-Inverted-Pendulum-Fails-1-6-chunk-0241.smt2                                    |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|NoriSharma-2013FSE-Fig8_true-termination.c_Iteration1_Lasso_4-pieceTemplate.smt2            | 142.591s  | 142.591s  |   0.000s  | 0.0%|
|NoriSharma-2013FSE-Fig8_true-termination.c_Iteration1_Loop_7-phaseTemplate.smt2             | 155.929s  | 155.929s  |   0.000s  | 0.0%|
|Nyala-TwoLex.bpl_Iteration1_Lasso_4-pieceTemplate.smt2                                      |  66.149s  |  66.149s  |   0.000s  | 0.0%|
|OpposedDisjuncts.bpl_Iteration1_Loop_4-pieceTemplate.smt2                                   | 110.526s  | 110.526s  |   0.000s  | 0.0%|
|RL-high-pass-circuit-gain-chunk-0010.smt2                                                   |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|SantaBarbara01.bpl_Iteration1_Lasso_4-pieceTemplate.smt2                                    |  52.024s  |  52.024s  |   0.000s  | 0.0%|
|SyntaxSupportDisjunction1.bpl_Iteration1_Loop_4-pieceTemplate.smt2                          |   0.725s  |   0.725s  |   0.000s  | 0.0%|
|SyntaxSupportDivision1.bpl_Iteration1_Lasso_7-nestedTemplate.smt2                           |  39.202s  |  39.202s  |   0.000s  | 0.0%|
|TelAviv-Amir-Minimum_true-termination.c_Iteration1_Lasso_7-phaseTemplate.smt2               |   4.849s  |   4.849s  |   0.000s  | 0.0%|
|afagp-fail.t2.c_Iteration1_Lasso_3-pieceTemplate.smt2                                       | 200.084s  | 200.084s  |   0.000s  | 0.0%|
|asin-8-chunk-0024.smt2                                                                      |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|asin-8-chunk-0039.smt2                                                                      |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|asin-8-chunk-0053.smt2                                                                      |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|asin-8-vars4-chunk-0019.smt2                                                                |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|asin-8-vars4-chunk-0034.smt2                                                                |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|asin-8-vars4-chunk-0046.smt2                                                                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|atan-problem-1-chunk-0006.smt2                                                              |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|atan-problem-1-chunk-0022.smt2                                                              |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|atan-problem-1-chunk-0035.smt2                                                              |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|atan-problem-1-chunk-0047.smt2                                                              |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|atan-problem-1-chunk-0058.smt2                                                              |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|atan-problem-1-chunk-0071.smt2                                                              |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|atan-problem-1-chunk-0081.smt2                                                              |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|atan-problem-1-chunk-0091.smt2                                                              |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|atan-problem-1-chunk-0102.smt2                                                              |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|atan-problem-1-weak-chunk-0020.smt2                                                         |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|atan-problem-1-weak-chunk-0035.smt2                                                         |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|atan-problem-2-chunk-0011.smt2                                                              |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|atan-problem-2-chunk-0024.smt2                                                              |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|atan-problem-2-chunk-0037.smt2                                                              |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|atan-problem-2-chunk-0047.smt2                                                              |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|atan-problem-2-chunk-0059.smt2                                                              |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|atan-problem-2-chunk-0070.smt2                                                              |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|atan-problem-2-chunk-0080.smt2                                                              |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|atan-problem-2-chunk-0092.smt2                                                              |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|atan-problem-2-chunk-0107.smt2                                                              |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|atan-problem-2-chunk-0117.smt2                                                              |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|atan-problem-2-sqrt-chunk-0019.smt2                                                         |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|atan-problem-2-sqrt-chunk-0039.smt2                                                         |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|atan-problem-2-sqrt-weak-chunk-0009.smt2                                                    |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|atan-problem-2-sqrt-weak-chunk-0032.smt2                                                    |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|atan-problem-2-sqrt-weak-chunk-0050.smt2                                                    |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|atan-problem-2-sqrt-weak-chunk-0065.smt2                                                    |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|atan-problem-2-sqrt-weak-chunk-0075.smt2                                                    |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|atan-problem-2-sqrt-weak-chunk-0086.smt2                                                    |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|atan-problem-2-weak-chunk-0014.smt2                                                         |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|atan-problem-2-weak-chunk-0028.smt2                                                         |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|atan-problem-2-weak-chunk-0041.smt2                                                         |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|atan-problem-2-weak-chunk-0053.smt2                                                         |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|atan-problem-2-weak-chunk-0064.smt2                                                         |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|atan-problem-2-weak-chunk-0076.smt2                                                         |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|atan-problem-2-weak-chunk-0087.smt2                                                         |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|atan-problem-2-weak-chunk-0098.smt2                                                         |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|atan-problem-2-weak-chunk-0109.smt2                                                         |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|atan-problem-2-weak-chunk-0124.smt2                                                         |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|atan-problem-2-weak-chunk-0134.smt2                                                         |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|atan-problem-2-weak-chunk-0146.smt2                                                         |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|atan-problem-2-weak-chunk-0157.smt2                                                         |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|atan-problem-2-weak-chunk-0168.smt2                                                         |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|atan-problem-2-weak-chunk-0179.smt2                                                         |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|atan-problem-2-weak-chunk-0189.smt2                                                         |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|atan-problem-2-weak-chunk-0201.smt2                                                         |   0.322s  |   0.322s  |   0.000s  | 0.0%|
|atan-problem-2-weak-chunk-0212.smt2                                                         |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|atan-problem-2-weak-chunk-0222.smt2                                                         |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|atan-problem-2-weak2-chunk-0008.smt2                                                        |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|atan-problem-2-weak2-chunk-0022.smt2                                                        |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|atan-problem-2-weak2-chunk-0043.smt2                                                        |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|atan-problem-2-weak2-chunk-0056.smt2                                                        |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|atan-problem-2-weak2-chunk-0070.smt2                                                        |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|atan-problem-2-weak2-chunk-0082.smt2                                                        |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|atan-problem-2-weak2-chunk-0093.smt2                                                        |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|atan-problem-2-weak2-chunk-0103.smt2                                                        |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|atan-problem-2-weak2-chunk-0120.smt2                                                        |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|atan-problem-2-weak2-chunk-0136.smt2                                                        |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|atan-problem-2-weakT-chunk-0019.smt2                                                        |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|atan-problem-2-weakT-chunk-0030.smt2                                                        |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|atan-problem-2-weakT-chunk-0041.smt2                                                        |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|atan-problem-2-weakT-chunk-0054.smt2                                                        |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0011.smt2                                                                 |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0027.smt2                                                                 |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0045.smt2                                                                 |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0057.smt2                                                                 |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0067.smt2                                                                 |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0077.smt2                                                                 |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0089.smt2                                                                 |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0099.smt2                                                                 |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0109.smt2                                                                 |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0119.smt2                                                                 |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0129.smt2                                                                 |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0139.smt2                                                                 |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0149.smt2                                                                 |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0159.smt2                                                                 |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0169.smt2                                                                 |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0179.smt2                                                                 |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0189.smt2                                                                 |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0199.smt2                                                                 |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0210.smt2                                                                 |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0220.smt2                                                                 |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0230.smt2                                                                 |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0240.smt2                                                                 |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0250.smt2                                                                 |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0260.smt2                                                                 |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0270.smt2                                                                 |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0280.smt2                                                                 |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0290.smt2                                                                 |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0300.smt2                                                                 |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0310.smt2                                                                 |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0320.smt2                                                                 |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0330.smt2                                                                 |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0340.smt2                                                                 |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0350.smt2                                                                 |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0360.smt2                                                                 |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0370.smt2                                                                 |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0380.smt2                                                                 |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0390.smt2                                                                 |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0400.smt2                                                                 |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0413.smt2                                                                 |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0423.smt2                                                                 |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0433.smt2                                                                 |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0443.smt2                                                                 |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0453.smt2                                                                 |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0463.smt2                                                                 |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0473.smt2                                                                 |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0483.smt2                                                                 |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0493.smt2                                                                 |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0503.smt2                                                                 |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0513.smt2                                                                 |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0523.smt2                                                                 |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0533.smt2                                                                 |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0543.smt2                                                                 |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0553.smt2                                                                 |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0563.smt2                                                                 |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0573.smt2                                                                 |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0583.smt2                                                                 |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0593.smt2                                                                 |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0603.smt2                                                                 |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0613.smt2                                                                 |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0623.smt2                                                                 |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|atan-vega-3-chunk-0633.smt2                                                                 |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0019.smt2                                                            |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0074.smt2                                                            |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0102.smt2                                                            |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0113.smt2                                                            |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0126.smt2                                                            |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0136.smt2                                                            |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0147.smt2                                                            |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0159.smt2                                                            |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0170.smt2                                                            |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0183.smt2                                                            |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0193.smt2                                                            |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0204.smt2                                                            |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0218.smt2                                                            |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0231.smt2                                                            |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0241.smt2                                                            |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0255.smt2                                                            |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0267.smt2                                                            |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0277.smt2                                                            |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0290.smt2                                                            |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0301.smt2                                                            |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0312.smt2                                                            |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0323.smt2                                                            |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0334.smt2                                                            |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0344.smt2                                                            |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0363.smt2                                                            |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0374.smt2                                                            |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0385.smt2                                                            | 200.015s  | 200.015s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0398.smt2                                                            |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0409.smt2                                                            |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0421.smt2                                                            |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0433.smt2                                                            |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0444.smt2                                                            |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0457.smt2                                                            |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0469.smt2                                                            |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0480.smt2                                                            |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0490.smt2                                                            |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0500.smt2                                                            |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0510.smt2                                                            |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0522.smt2                                                            |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0534.smt2                                                            |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0545.smt2                                                            |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0555.smt2                                                            |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0566.smt2                                                            |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0576.smt2                                                            |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0586.smt2                                                            |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0596.smt2                                                            |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0606.smt2                                                            |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0619.smt2                                                            |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0629.smt2                                                            |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0639.smt2                                                            |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0651.smt2                                                            |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0661.smt2                                                            |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0671.smt2                                                            |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0681.smt2                                                            |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0691.smt2                                                            |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0701.smt2                                                            |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0711.smt2                                                            |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|atan-vega-3-weak-chunk-0721.smt2                                                            |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|avg60.i_5_5_4.bpl_3.smt2                                                                    | 200.019s  | 200.019s  |   0.000s  | 0.0%|
|aviad_true-termination.c_Iteration1_Loop_3-lexTemplate.smt2                                 | 200.112s  | 200.112s  |   0.000s  | 0.0%|
|aviad_true-termination.c_Iteration1_Loop_6-phaseTemplate.smt2                               | 200.108s  | 200.108s  |   0.000s  | 0.0%|
|ball_count_1d_plain.01.qfree_global_1.smt2                                                  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|ball_count_1d_plain.01.qfree_global_5.smt2                                                  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|ball_count_1d_plain.01.redlog_global_13.smt2                                                |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|ball_count_1d_plain.01.redlog_global_9.smt2                                                 |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|ball_count_1d_plain.01.seq_lazy_global_3.smt2                                               |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|ball_count_1d_plain.01.seq_lazy_lemmas_global_11.smt2                                       |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|ball_count_1d_plain.01.seq_lazy_lemmas_global_7.smt2                                        |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|ball_count_1d_plain.01.seq_lazy_linear_enc_global_15.smt2                                   |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|ball_count_1d_plain.01.seq_lazy_linear_enc_lemmas_global_1.smt2                             |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|ball_count_1d_plain.01.seq_lazy_linear_enc_lemmas_global_5.smt2                             |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|ball_count_1d_plain.02.qfree_global_13.smt2                                                 |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|ball_count_1d_plain.02.qfree_global_9.smt2                                                  |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|ball_count_1d_plain.02.redlog_global_3.smt2                                                 |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|ball_count_1d_plain.02.seq_lazy_global_11.smt2                                              |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|ball_count_1d_plain.02.seq_lazy_global_7.smt2                                               |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|ball_count_1d_plain.02.seq_lazy_lemmas_global_15.smt2                                       |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|ball_count_1d_plain.02.seq_lazy_linear_enc_global_1.smt2                                    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|ball_count_1d_plain.02.seq_lazy_linear_enc_global_5.smt2                                    |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|ball_count_1d_plain.02.seq_lazy_linear_enc_lemmas_global_13.smt2                            |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|ball_count_1d_plain.02.seq_lazy_linear_enc_lemmas_global_9.smt2                             |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|ball_count_1d_plain.03.qfree_global_3.smt2                                                  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|ball_count_1d_plain.03.redlog_global_11.smt2                                                |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|ball_count_1d_plain.03.redlog_global_7.smt2                                                 |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|ball_count_1d_plain.03.seq_lazy_global_15.smt2                                              |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|ball_count_1d_plain.03.seq_lazy_lemmas_global_1.smt2                                        |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|ball_count_1d_plain.03.seq_lazy_lemmas_global_5.smt2                                        |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|ball_count_1d_plain.03.seq_lazy_linear_enc_global_13.smt2                                   |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|ball_count_1d_plain.03.seq_lazy_linear_enc_global_9.smt2                                    |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|ball_count_1d_plain.03.seq_lazy_linear_enc_lemmas_global_3.smt2                             |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|ball_count_1d_plain.04.qfree_global_11.smt2                                                 |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|ball_count_1d_plain.04.qfree_global_7.smt2                                                  |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|ball_count_1d_plain.04.redlog_global_15.smt2                                                |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|ball_count_1d_plain.04.seq_lazy_global_1.smt2                                               |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|ball_count_1d_plain.04.seq_lazy_global_5.smt2                                               |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|ball_count_1d_plain.04.seq_lazy_lemmas_global_13.smt2                                       |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|ball_count_1d_plain.04.seq_lazy_lemmas_global_9.smt2                                        |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|ball_count_1d_plain.04.seq_lazy_linear_enc_global_3.smt2                                    |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|ball_count_1d_plain.04.seq_lazy_linear_enc_lemmas_global_11.smt2                            |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|ball_count_1d_plain.04.seq_lazy_linear_enc_lemmas_global_7.smt2                             |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|ball_count_1d_plain.05.qfree_global_15.smt2                                                 |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|ball_count_1d_plain.05.redlog_global_1.smt2                                                 |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|ball_count_1d_plain.05.redlog_global_5.smt2                                                 |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|ball_count_1d_plain.05.seq_lazy_global_13.smt2                                              |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|ball_count_1d_plain.05.seq_lazy_global_9.smt2                                               |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|ball_count_1d_plain.05.seq_lazy_lemmas_global_3.smt2                                        |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|ball_count_1d_plain.05.seq_lazy_linear_enc_global_11.smt2                                   |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|ball_count_1d_plain.05.seq_lazy_linear_enc_global_7.smt2                                    |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|ball_count_1d_plain.05.seq_lazy_linear_enc_lemmas_global_15.smt2                            |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|ball_count_1d_plain.10.qfree_global_1.smt2                                                  |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|ball_count_1d_plain.10.qfree_global_5.smt2                                                  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|ball_count_1d_plain.10.redlog_global_13.smt2                                                |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|ball_count_1d_plain.10.redlog_global_9.smt2                                                 |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|ball_count_1d_plain.10.seq_lazy_global_3.smt2                                               |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|ball_count_1d_plain.10.seq_lazy_lemmas_global_11.smt2                                       |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|ball_count_1d_plain.10.seq_lazy_lemmas_global_7.smt2                                        |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|ball_count_1d_plain.10.seq_lazy_linear_enc_global_15.smt2                                   |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|ball_count_1d_plain.10.seq_lazy_linear_enc_lemmas_global_1.smt2                             |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|ball_count_1d_plain.10.seq_lazy_linear_enc_lemmas_global_5.smt2                             |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|ball_count_2d_hill.01.redlog_global_13.smt2                                                 |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|ball_count_2d_hill.01.redlog_global_9.smt2                                                  |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|ball_count_2d_hill.01.seq_lazy_global_3.smt2                                                |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|ball_count_2d_hill.01.seq_lazy_lemmas_global_11.smt2                                        |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|ball_count_2d_hill.01.seq_lazy_lemmas_global_7.smt2                                         |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|ball_count_2d_hill.01.seq_lazy_linear_enc_global_15.smt2                                    |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|ball_count_2d_hill.01.seq_lazy_linear_enc_lemmas_global_1.smt2                              |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|ball_count_2d_hill.01.seq_lazy_linear_enc_lemmas_global_5.smt2                              |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|ball_count_2d_hill.02.redlog_global_13.smt2                                                 |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|ball_count_2d_hill.02.redlog_global_9.smt2                                                  |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|ball_count_2d_hill.02.seq_lazy_global_3.smt2                                                |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|ball_count_2d_hill.02.seq_lazy_lemmas_global_11.smt2                                        |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|ball_count_2d_hill.02.seq_lazy_lemmas_global_7.smt2                                         |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|ball_count_2d_hill.02.seq_lazy_linear_enc_global_15.smt2                                    |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|ball_count_2d_hill.02.seq_lazy_linear_enc_lemmas_global_1.smt2                              |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|ball_count_2d_hill.02.seq_lazy_linear_enc_lemmas_global_5.smt2                              |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|ball_count_2d_hill.03.redlog_global_13.smt2                                                 |   7.274s  |   7.274s  |   0.000s  | 0.0%|
|ball_count_2d_hill.03.redlog_global_9.smt2                                                  |   0.861s  |   0.861s  |   0.000s  | 0.0%|
|ball_count_2d_hill.03.seq_lazy_global_3.smt2                                                |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|ball_count_2d_hill.03.seq_lazy_lemmas_global_11.smt2                                        |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|ball_count_2d_hill.03.seq_lazy_lemmas_global_7.smt2                                         |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|ball_count_2d_hill.03.seq_lazy_linear_enc_global_15.smt2                                    |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|ball_count_2d_hill.03.seq_lazy_linear_enc_lemmas_global_1.smt2                              |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|ball_count_2d_hill.03.seq_lazy_linear_enc_lemmas_global_5.smt2                              |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|ball_count_2d_hill.04.redlog_global_13.smt2                                                 |   8.065s  |   8.065s  |   0.000s  | 0.0%|
|ball_count_2d_hill.04.redlog_global_9.smt2                                                  |   0.878s  |   0.878s  |   0.000s  | 0.0%|
|ball_count_2d_hill.04.seq_lazy_global_3.smt2                                                |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|ball_count_2d_hill.04.seq_lazy_lemmas_global_11.smt2                                        |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|ball_count_2d_hill.04.seq_lazy_lemmas_global_7.smt2                                         |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|ball_count_2d_hill.04.seq_lazy_linear_enc_global_15.smt2                                    |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|ball_count_2d_hill.04.seq_lazy_linear_enc_lemmas_global_1.smt2                              |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|ball_count_2d_hill.04.seq_lazy_linear_enc_lemmas_global_5.smt2                              |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|ball_count_2d_hill.05.redlog_global_13.smt2                                                 |   7.249s  |   7.249s  |   0.000s  | 0.0%|
|ball_count_2d_hill.05.redlog_global_9.smt2                                                  |   0.820s  |   0.820s  |   0.000s  | 0.0%|
|ball_count_2d_hill.05.seq_lazy_global_3.smt2                                                |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|ball_count_2d_hill.05.seq_lazy_lemmas_global_11.smt2                                        |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|ball_count_2d_hill.05.seq_lazy_lemmas_global_7.smt2                                         |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|ball_count_2d_hill.05.seq_lazy_linear_enc_global_15.smt2                                    |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|ball_count_2d_hill.05.seq_lazy_linear_enc_lemmas_global_1.smt2                              |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|ball_count_2d_hill.05.seq_lazy_linear_enc_lemmas_global_5.smt2                              |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|ball_count_2d_hill.10.redlog_global_13.smt2                                                 |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|ball_count_2d_hill.10.redlog_global_9.smt2                                                  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|ball_count_2d_hill.10.seq_lazy_global_3.smt2                                                |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|ball_count_2d_hill.10.seq_lazy_lemmas_global_11.smt2                                        |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|ball_count_2d_hill.10.seq_lazy_lemmas_global_7.smt2                                         |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|ball_count_2d_hill.10.seq_lazy_linear_enc_global_15.smt2                                    |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|ball_count_2d_hill.10.seq_lazy_linear_enc_lemmas_global_1.smt2                              |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|ball_count_2d_hill.10.seq_lazy_linear_enc_lemmas_global_5.smt2                              |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.01.qfree_global_13.smt2                                           |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.01.qfree_global_9.smt2                                            |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.01.redlog_global_3.smt2                                           |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.01.seq_lazy_global_11.smt2                                        |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.01.seq_lazy_global_7.smt2                                         |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.01.seq_lazy_lemmas_global_15.smt2                                 |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.01.seq_lazy_linear_enc_global_1.smt2                              |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.01.seq_lazy_linear_enc_global_5.smt2                              |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.01.seq_lazy_linear_enc_lemmas_global_13.smt2                      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.01.seq_lazy_linear_enc_lemmas_global_9.smt2                       |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.02.qfree_global_3.smt2                                            |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.02.redlog_global_11.smt2                                          |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.02.redlog_global_7.smt2                                           |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.02.seq_lazy_global_15.smt2                                        |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.02.seq_lazy_lemmas_global_1.smt2                                  |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.02.seq_lazy_lemmas_global_5.smt2                                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.02.seq_lazy_linear_enc_global_13.smt2                             |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.02.seq_lazy_linear_enc_global_9.smt2                              |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.02.seq_lazy_linear_enc_lemmas_global_3.smt2                       |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.03.qfree_global_11.smt2                                           |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.03.qfree_global_7.smt2                                            |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.03.redlog_global_15.smt2                                          |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.03.seq_lazy_global_1.smt2                                         |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.03.seq_lazy_global_5.smt2                                         |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.03.seq_lazy_lemmas_global_13.smt2                                 |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.03.seq_lazy_lemmas_global_9.smt2                                  |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.03.seq_lazy_linear_enc_global_3.smt2                              |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.03.seq_lazy_linear_enc_lemmas_global_11.smt2                      |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.03.seq_lazy_linear_enc_lemmas_global_7.smt2                       |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.04.qfree_global_15.smt2                                           |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.04.redlog_global_1.smt2                                           |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.04.redlog_global_5.smt2                                           |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.04.seq_lazy_global_13.smt2                                        |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.04.seq_lazy_global_9.smt2                                         |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.04.seq_lazy_lemmas_global_3.smt2                                  |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.04.seq_lazy_linear_enc_global_11.smt2                             |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.04.seq_lazy_linear_enc_global_7.smt2                              |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.04.seq_lazy_linear_enc_lemmas_global_15.smt2                      |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.05.qfree_global_1.smt2                                            |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.05.qfree_global_5.smt2                                            |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.05.redlog_global_13.smt2                                          |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.05.redlog_global_9.smt2                                           |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.05.seq_lazy_global_3.smt2                                         |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.05.seq_lazy_lemmas_global_11.smt2                                 |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.05.seq_lazy_lemmas_global_7.smt2                                  |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.05.seq_lazy_linear_enc_global_15.smt2                             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.05.seq_lazy_linear_enc_lemmas_global_1.smt2                       |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.05.seq_lazy_linear_enc_lemmas_global_5.smt2                       |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.10.qfree_global_13.smt2                                           |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.10.qfree_global_9.smt2                                            |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.10.redlog_global_3.smt2                                           |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.10.seq_lazy_global_11.smt2                                        |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.10.seq_lazy_global_7.smt2                                         |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.10.seq_lazy_lemmas_global_15.smt2                                 |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.10.seq_lazy_linear_enc_global_1.smt2                              |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.10.seq_lazy_linear_enc_global_5.smt2                              |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.10.seq_lazy_linear_enc_lemmas_global_13.smt2                      |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|ball_count_2d_hill_simple.10.seq_lazy_linear_enc_lemmas_global_9.smt2                       |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|ball_count_2d_plain.01.qfree_global_3.smt2                                                  |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|ball_count_2d_plain.01.redlog_global_11.smt2                                                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|ball_count_2d_plain.01.redlog_global_7.smt2                                                 |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|ball_count_2d_plain.01.seq_lazy_global_15.smt2                                              |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|ball_count_2d_plain.01.seq_lazy_lemmas_global_1.smt2                                        |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|ball_count_2d_plain.01.seq_lazy_lemmas_global_5.smt2                                        |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|ball_count_2d_plain.01.seq_lazy_linear_enc_global_13.smt2                                   |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|ball_count_2d_plain.01.seq_lazy_linear_enc_global_9.smt2                                    |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|ball_count_2d_plain.01.seq_lazy_linear_enc_lemmas_global_3.smt2                             |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|ball_count_2d_plain.02.qfree_global_11.smt2                                                 |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|ball_count_2d_plain.02.qfree_global_7.smt2                                                  |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|ball_count_2d_plain.02.redlog_global_15.smt2                                                |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|ball_count_2d_plain.02.seq_lazy_global_1.smt2                                               |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|ball_count_2d_plain.02.seq_lazy_global_5.smt2                                               |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|ball_count_2d_plain.02.seq_lazy_lemmas_global_13.smt2                                       |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|ball_count_2d_plain.02.seq_lazy_lemmas_global_9.smt2                                        |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|ball_count_2d_plain.02.seq_lazy_linear_enc_global_3.smt2                                    |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|ball_count_2d_plain.02.seq_lazy_linear_enc_lemmas_global_11.smt2                            |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|ball_count_2d_plain.02.seq_lazy_linear_enc_lemmas_global_7.smt2                             |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|ball_count_2d_plain.03.qfree_global_15.smt2                                                 |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|ball_count_2d_plain.03.redlog_global_1.smt2                                                 |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|ball_count_2d_plain.03.redlog_global_5.smt2                                                 |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|ball_count_2d_plain.03.seq_lazy_global_13.smt2                                              |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|ball_count_2d_plain.03.seq_lazy_global_9.smt2                                               |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|ball_count_2d_plain.03.seq_lazy_lemmas_global_3.smt2                                        |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|ball_count_2d_plain.03.seq_lazy_linear_enc_global_11.smt2                                   |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|ball_count_2d_plain.03.seq_lazy_linear_enc_global_7.smt2                                    |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|ball_count_2d_plain.03.seq_lazy_linear_enc_lemmas_global_15.smt2                            |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|ball_count_2d_plain.04.qfree_global_1.smt2                                                  |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|ball_count_2d_plain.04.qfree_global_5.smt2                                                  |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|ball_count_2d_plain.04.redlog_global_13.smt2                                                |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|ball_count_2d_plain.04.redlog_global_9.smt2                                                 |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|ball_count_2d_plain.04.seq_lazy_global_3.smt2                                               |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|ball_count_2d_plain.04.seq_lazy_lemmas_global_11.smt2                                       |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|ball_count_2d_plain.04.seq_lazy_lemmas_global_7.smt2                                        |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|ball_count_2d_plain.04.seq_lazy_linear_enc_global_15.smt2                                   |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|ball_count_2d_plain.04.seq_lazy_linear_enc_lemmas_global_1.smt2                             |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|ball_count_2d_plain.04.seq_lazy_linear_enc_lemmas_global_5.smt2                             |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|ball_count_2d_plain.05.qfree_global_13.smt2                                                 |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|ball_count_2d_plain.05.qfree_global_9.smt2                                                  |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|ball_count_2d_plain.05.redlog_global_3.smt2                                                 |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|ball_count_2d_plain.05.seq_lazy_global_11.smt2                                              |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|ball_count_2d_plain.05.seq_lazy_global_7.smt2                                               |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|ball_count_2d_plain.05.seq_lazy_lemmas_global_15.smt2                                       |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|ball_count_2d_plain.05.seq_lazy_linear_enc_global_1.smt2                                    |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|ball_count_2d_plain.05.seq_lazy_linear_enc_global_5.smt2                                    |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|ball_count_2d_plain.05.seq_lazy_linear_enc_lemmas_global_13.smt2                            |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|ball_count_2d_plain.05.seq_lazy_linear_enc_lemmas_global_9.smt2                             |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|ball_count_2d_plain.10.qfree_global_3.smt2                                                  |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|ball_count_2d_plain.10.redlog_global_11.smt2                                                |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|ball_count_2d_plain.10.redlog_global_7.smt2                                                 |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|ball_count_2d_plain.10.seq_lazy_global_15.smt2                                              |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|ball_count_2d_plain.10.seq_lazy_lemmas_global_1.smt2                                        |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|ball_count_2d_plain.10.seq_lazy_lemmas_global_5.smt2                                        |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|ball_count_2d_plain.10.seq_lazy_linear_enc_global_13.smt2                                   |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|ball_count_2d_plain.10.seq_lazy_linear_enc_global_9.smt2                                    |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|ball_count_2d_plain.10.seq_lazy_linear_enc_lemmas_global_3.smt2                             |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|ball_count_2d_slope.01.seq_lazy_global_11.smt2                                              |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|ball_count_2d_slope.01.seq_lazy_global_7.smt2                                               |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|ball_count_2d_slope.01.seq_lazy_lemmas_global_15.smt2                                       |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|ball_count_2d_slope.01.seq_lazy_linear_enc_global_1.smt2                                    |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|ball_count_2d_slope.01.seq_lazy_linear_enc_global_5.smt2                                    |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|ball_count_2d_slope.01.seq_lazy_linear_enc_lemmas_global_13.smt2                            |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|ball_count_2d_slope.01.seq_lazy_linear_enc_lemmas_global_9.smt2                             |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|ball_count_2d_slope.02.seq_lazy_global_3.smt2                                               |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|ball_count_2d_slope.02.seq_lazy_lemmas_global_11.smt2                                       |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|ball_count_2d_slope.02.seq_lazy_lemmas_global_7.smt2                                        |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|ball_count_2d_slope.02.seq_lazy_linear_enc_global_15.smt2                                   |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|ball_count_2d_slope.02.seq_lazy_linear_enc_lemmas_global_1.smt2                             |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|ball_count_2d_slope.02.seq_lazy_linear_enc_lemmas_global_5.smt2                             |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|ball_count_2d_slope.03.seq_lazy_global_13.smt2                                              |  14.067s  |  14.067s  |   0.000s  | 0.0%|
|ball_count_2d_slope.03.seq_lazy_global_9.smt2                                               |   0.901s  |   0.901s  |   0.000s  | 0.0%|
|ball_count_2d_slope.03.seq_lazy_lemmas_global_3.smt2                                        |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|ball_count_2d_slope.03.seq_lazy_linear_enc_global_11.smt2                                   |   2.548s  |   2.548s  |   0.000s  | 0.0%|
|ball_count_2d_slope.03.seq_lazy_linear_enc_global_7.smt2                                    |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|ball_count_2d_slope.03.seq_lazy_linear_enc_lemmas_global_15.smt2                            |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|ball_count_2d_slope.04.seq_lazy_global_1.smt2                                               |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|ball_count_2d_slope.04.seq_lazy_global_5.smt2                                               |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|ball_count_2d_slope.04.seq_lazy_lemmas_global_13.smt2                                       |  14.070s  |  14.070s  |   0.000s  | 0.0%|
|ball_count_2d_slope.04.seq_lazy_lemmas_global_9.smt2                                        |   2.672s  |   2.672s  |   0.000s  | 0.0%|
|ball_count_2d_slope.04.seq_lazy_linear_enc_global_3.smt2                                    |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|ball_count_2d_slope.04.seq_lazy_linear_enc_lemmas_global_11.smt2                            |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|ball_count_2d_slope.04.seq_lazy_linear_enc_lemmas_global_7.smt2                             |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|ball_count_2d_slope.05.seq_lazy_global_15.smt2                                              |  10.086s  |  10.086s  |   0.000s  | 0.0%|
|ball_count_2d_slope.05.seq_lazy_lemmas_global_1.smt2                                        |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|ball_count_2d_slope.05.seq_lazy_lemmas_global_5.smt2                                        |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|ball_count_2d_slope.05.seq_lazy_linear_enc_global_13.smt2                                   |  14.093s  |  14.093s  |   0.000s  | 0.0%|
|ball_count_2d_slope.05.seq_lazy_linear_enc_global_9.smt2                                    |   0.717s  |   0.717s  |   0.000s  | 0.0%|
|ball_count_2d_slope.05.seq_lazy_linear_enc_lemmas_global_3.smt2                             |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|ball_count_2d_slope.10.seq_lazy_global_11.smt2                                              |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|ball_count_2d_slope.10.seq_lazy_global_7.smt2                                               |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|ball_count_2d_slope.10.seq_lazy_lemmas_global_15.smt2                                       |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|ball_count_2d_slope.10.seq_lazy_linear_enc_global_1.smt2                                    |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|ball_count_2d_slope.10.seq_lazy_linear_enc_global_5.smt2                                    |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|ball_count_2d_slope.10.seq_lazy_linear_enc_lemmas_global_13.smt2                            |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|ball_count_2d_slope.10.seq_lazy_linear_enc_lemmas_global_9.smt2                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|bf10.t2.c_Iteration1_Loop_4-pieceTemplate.smt2                                              |   0.600s  |   0.600s  |   0.000s  | 0.0%|
|bottom-plate-mixer-chunk-0039.smt2                                                          |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|bottom-plate-mixer-chunk-0050.smt2                                                          |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|brp_withassume.t2.c_Iteration1_Loop_4-pieceTemplate.smt2                                    | 200.134s  | 200.134s  |   0.000s  | 0.0%|
|byron-1.t2.c_Iteration1_Loop_3-pieceTemplate.smt2                                           |  32.902s  |  32.902s  |   0.000s  | 0.0%|
|cbrt-problem-3-chunk-0028.smt2                                                              |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|cbrt-problem-3-chunk-0055.smt2                                                              |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|cbrt-problem-3-chunk-0070.smt2                                                              |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|cbrt-problem-3-weak-chunk-0023.smt2                                                         |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|cbrt-problem-3-weak-chunk-0040.smt2                                                         |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|cbrt-problem-3-weak-chunk-0069.smt2                                                         |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|cbrt-problem-3-weak-chunk-0084.smt2                                                         |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|cbrt-problem-3-weak-chunk-0094.smt2                                                         |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|cbrt-problem-3-weak-chunk-0108.smt2                                                         |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|collatz.t2.c_Iteration3_Lasso_6-phaseTemplate.smt2                                          |  66.646s  |  66.646s  |   0.000s  | 0.0%|
|cos-3410-b-chunk-0015.smt2                                                                  |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|cos-3410-b-chunk-0027.smt2                                                                  |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|cos-problem-5-chunk-0023.smt2                                                               |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|cos-problem-5-chunk-0039.smt2                                                               |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|db3.t2.c_Iteration2_Loop_4-pieceTemplate.smt2                                               |  15.407s  |  15.407s  |   0.000s  | 0.0%|
|efegp.t2.c_Iteration1_Lasso_3-pieceTemplate.smt2                                            | 200.069s  | 200.069s  |   0.000s  | 0.0%|
|eric.t2.c_Iteration1_Lasso_5-phaseTemplate.smt2                                             |   1.759s  |   1.759s  |   0.000s  | 0.0%|
|eric2.t2.c_Iteration1_Loop_4-pieceTemplate.smt2                                             |  59.970s  |  59.970s  |   0.000s  | 0.0%|
|eric2.t2.c_Iteration7_Loop_4-pieceTemplate.smt2                                             |  94.515s  |  94.515s  |   0.000s  | 0.0%|
|etcs_braking_2.01.qfree_global_3.smt2                                                       |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|etcs_braking_2.01.redlog_global_11.smt2                                                     |  50.255s  |  50.255s  |   0.000s  | 0.0%|
|etcs_braking_2.01.redlog_global_7.smt2                                                      |  50.371s  |  50.371s  |   0.000s  | 0.0%|
|etcs_braking_2.01.seq_lazy_global_15.smt2                                                   |  14.334s  |  14.334s  |   0.000s  | 0.0%|
|etcs_braking_2.01.seq_lazy_lemmas_global_1.smt2                                             |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|etcs_braking_2.01.seq_lazy_lemmas_global_5.smt2                                             |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|etcs_braking_2.01.seq_lazy_linear_enc_global_13.smt2                                        | 200.097s  | 200.097s  |   0.000s  | 0.0%|
|etcs_braking_2.01.seq_lazy_linear_enc_global_9.smt2                                         |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|etcs_braking_2.01.seq_lazy_linear_enc_lemmas_global_3.smt2                                  |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|ex11.t2.c_Iteration1_Lasso_5-phaseTemplate.smt2                                             |   1.155s  |   1.155s  |   0.000s  | 0.0%|
|ex4.t2.c_Iteration2_Loop_3-pieceTemplate.smt2                                               |  14.270s  |  14.270s  |   0.000s  | 0.0%|
|exp-361-neg-6-e-chunk-0216.smt2                                                             |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0016.smt2                                                            |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0028.smt2                                                            |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0038.smt2                                                            |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0048.smt2                                                            |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0059.smt2                                                            |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0069.smt2                                                            |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0079.smt2                                                            |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0090.smt2                                                            |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0102.smt2                                                            |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0112.smt2                                                            |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0124.smt2                                                            |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0134.smt2                                                            |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0144.smt2                                                            |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0154.smt2                                                            |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0164.smt2                                                            |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0174.smt2                                                            |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0184.smt2                                                            |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0194.smt2                                                            |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0204.smt2                                                            |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0214.smt2                                                            |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0224.smt2                                                            |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0234.smt2                                                            |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0245.smt2                                                            |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0255.smt2                                                            |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0265.smt2                                                            |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0275.smt2                                                            |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0285.smt2                                                            |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0295.smt2                                                            |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0305.smt2                                                            |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0315.smt2                                                            |   1.339s  |   1.339s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0325.smt2                                                            |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0335.smt2                                                            |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0346.smt2                                                            |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0358.smt2                                                            |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0375.smt2                                                            |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|exp-problem-10-2-chunk-0385.smt2                                                            |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|exp-problem-10-3-chunk-0010.smt2                                                            |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|exp-problem-10-3-chunk-0021.smt2                                                            |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|exp-problem-10-3-chunk-0032.smt2                                                            |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|exp-problem-10-3-chunk-0042.smt2                                                            |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|exp-problem-10-3-chunk-0052.smt2                                                            |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|exp-problem-10-3-chunk-0063.smt2                                                            |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|exp-problem-10-3-chunk-0073.smt2                                                            |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|exp-problem-10-3-chunk-0084.smt2                                                            |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|exp-problem-10-3-chunk-0096.smt2                                                            |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|exp-problem-10-3-chunk-0106.smt2                                                            |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|exp-problem-10-3-chunk-0118.smt2                                                            |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|exp-problem-10-3-chunk-0128.smt2                                                            |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|exp-problem-10-3-chunk-0138.smt2                                                            |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|exp-problem-10-3-chunk-0148.smt2                                                            |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|exp-problem-10-3-chunk-0158.smt2                                                            |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|exp-problem-10-3-chunk-0168.smt2                                                            |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|exp-problem-10-3-chunk-0178.smt2                                                            |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|exp-problem-10-3-chunk-0188.smt2                                                            |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|exp-problem-10-3-weak-chunk-0015.smt2                                                       |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|exp-problem-10-3-weak-chunk-0025.smt2                                                       |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|exp-problem-10-3-weak-chunk-0035.smt2                                                       |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|exp-problem-10-3-weak-chunk-0048.smt2                                                       |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|exp-problem-10-3-weak-chunk-0059.smt2                                                       |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|exp-problem-10-3-weak-chunk-0070.smt2                                                       |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|exp-problem-10-3-weak-chunk-0080.smt2                                                       |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|exp-problem-10-3-weak-chunk-0091.smt2                                                       |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|exp-problem-10-3-weak-chunk-0101.smt2                                                       |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|exp-problem-10-3-weak-chunk-0111.smt2                                                       |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|exp-problem-10-3-weak-chunk-0121.smt2                                                       |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|exp-problem-10-3-weak-chunk-0131.smt2                                                       |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|exp-problem-10-3-weak-chunk-0141.smt2                                                       |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|exp-problem-10-3-weak-chunk-0151.smt2                                                       |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|exp-problem-10-3-weak-chunk-0161.smt2                                                       |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|exp-problem-10-3-weak-chunk-0171.smt2                                                       |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|exp-problem-10-3-weak-chunk-0181.smt2                                                       |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|exp-problem-10-3-weak-chunk-0191.smt2                                                       |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|exp-problem-10-3-weak-chunk-0202.smt2                                                       |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|exp-problem-10-3-weak-chunk-0218.smt2                                                       |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|exp-problem-10-3-weak-chunk-0230.smt2                                                       |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|firewire.t2.c_Iteration1_Lasso_7-nestedTemplate.smt2                                        | 124.536s  | 124.536s  |   0.000s  | 0.0%|
|fragtest_simple.i_4_5_4.bpl_3.smt2                                                          | 200.030s  | 200.030s  |   0.000s  | 0.0%|
|fuhs-inflasso.t2.c_Iteration2_Loop_4-pieceTemplate.smt2                                     |  26.250s  |  26.250s  |   0.000s  | 0.0%|
|fun9.t2.c_Iteration1_Loop_4-pieceTemplate.smt2                                              |  19.252s  |  19.252s  |   0.000s  | 0.0%|
|gen-09.smt2                                                                                 |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|heidy7-simple.t2.c_Iteration2_Lasso_4-pieceTemplate.smt2                                    | 200.058s  | 200.058s  |   0.000s  | 0.0%|
|hong_10.smt2                                                                                |  39.768s  |  39.768s  |   0.000s  | 0.0%|
|hong_2.smt2                                                                                 |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|iecs.t2.c_Iteration1_Loop_4-pieceTemplate.smt2                                              |  56.521s  |  56.521s  |   0.000s  | 0.0%|
|joey_false-termination.c_Iteration2_Loop_6-phaseTemplate.smt2                               |   3.545s  |   3.545s  |   0.000s  | 0.0%|
|kissing_3_11.smt2                                                                           | 200.041s  | 200.041s  |   0.000s  | 0.0%|
|kissing_3_9.smt2                                                                            | 200.032s  | 200.032s  |   0.000s  | 0.0%|
|kissing_4_18.smt2                                                                           | 200.013s  | 200.013s  |   0.000s  | 0.0%|
|kissing_4_4.smt2                                                                            |  50.665s  |  50.665s  |   0.000s  | 0.0%|
|linear_search.i_7_19_3.bpl_3.smt2                                                           | 200.017s  | 200.017s  |   0.000s  | 0.0%|
|log-fun-ineq-g-chunk-0036.smt2                                                              |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|loop_on_input.t2.c_Iteration1_Loop_4-pieceTemplate.smt2                                     |  15.758s  |  15.758s  |   0.000s  | 0.0%|
|matrix-1-all-10.smt2                                                                        |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|matrix-1-all-2.smt2                                                                         |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|matrix-1-all-29.smt2                                                                        |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|matrix-1-all-38.smt2                                                                        |   0.646s  |   0.646s  |   0.000s  | 0.0%|
|matrix-1-all-47.smt2                                                                        |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|matrix-1-all-8.smt2                                                                         |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|matrix-2-all-17.smt2                                                                        | 200.032s  | 200.032s  |   0.000s  | 0.0%|
|matrix-2-all-4.smt2                                                                         |  14.436s  |  14.436s  |   0.000s  | 0.0%|
|matrix-3-all-13.smt2                                                                        | 200.033s  | 200.033s  |   0.000s  | 0.0%|
|matrix-3-all-4.smt2                                                                         |  32.738s  |  32.738s  |   0.000s  | 0.0%|
|matrix-4-all-13.smt2                                                                        | 200.041s  | 200.041s  |   0.000s  | 0.0%|
|matrix-4-all-22.smt2                                                                        | 200.016s  | 200.016s  |   0.000s  | 0.0%|
|matrix-4-all-4.smt2                                                                         | 200.039s  | 200.039s  |   0.000s  | 0.0%|
|matrix-5-all-13.smt2                                                                        |  92.956s  |  92.956s  |   0.000s  | 0.0%|
|matrix-5-all-23.smt2                                                                        |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|mbo_E10E18.smt2                                                                             |  58.247s  |  58.247s  |   0.000s  | 0.0%|
|mbo_E10E28.smt2                                                                             | 200.062s  | 200.062s  |   0.000s  | 0.0%|
|mbo_E11E20.smt2                                                                             | 200.013s  | 200.013s  |   0.000s  | 0.0%|
|mbo_E12E13.smt2                                                                             |  58.753s  |  58.753s  |   0.000s  | 0.0%|
|mbo_E12E23.smt2                                                                             | 200.021s  | 200.021s  |   0.000s  | 0.0%|
|mbo_E13E17.smt2                                                                             |  14.293s  |  14.293s  |   0.000s  | 0.0%|
|mbo_E13E27.smt2                                                                             |  99.786s  |  99.786s  |   0.000s  | 0.0%|
|mbo_E14E22.smt2                                                                             |  45.676s  |  45.676s  |   0.000s  | 0.0%|
|mbo_E15E18.smt2                                                                             |  14.637s  |  14.637s  |   0.000s  | 0.0%|
|mbo_E15E28.smt2                                                                             | 200.018s  | 200.018s  |   0.000s  | 0.0%|
|mbo_E16E25.smt2                                                                             | 200.039s  | 200.039s  |   0.000s  | 0.0%|
|mbo_E17E23.smt2                                                                             |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|mbo_E18E22.smt2                                                                             | 200.027s  | 200.027s  |   0.000s  | 0.0%|
|mbo_E19E22.smt2                                                                             | 200.072s  | 200.072s  |   0.000s  | 0.0%|
|mbo_E1E13.smt2                                                                              |  61.313s  |  61.313s  |   0.000s  | 0.0%|
|mbo_E1E22.smt2                                                                              |  14.245s  |  14.245s  |   0.000s  | 0.0%|
|mbo_E1E6.smt2                                                                               |  15.729s  |  15.729s  |   0.000s  | 0.0%|
|mbo_E20E25.smt2                                                                             |  72.091s  |  72.091s  |   0.000s  | 0.0%|
|mbo_E21E27.smt2                                                                             |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|mbo_E23E24.smt2                                                                             |  84.652s  |  84.652s  |   0.000s  | 0.0%|
|mbo_E25.smt2                                                                                |  50.270s  |  50.270s  |   0.000s  | 0.0%|
|mbo_E2E10.smt2                                                                              |  58.679s  |  58.679s  |   0.000s  | 0.0%|
|mbo_E2E20.smt2                                                                              | 200.017s  | 200.017s  |   0.000s  | 0.0%|
|mbo_E2E4.smt2                                                                               |  60.427s  |  60.427s  |   0.000s  | 0.0%|
|mbo_E3E13.smt2                                                                              |  62.101s  |  62.101s  |   0.000s  | 0.0%|
|mbo_E3E23.smt2                                                                              | 200.046s  | 200.046s  |   0.000s  | 0.0%|
|mbo_E3E8.smt2                                                                               |  59.918s  |  59.918s  |   0.000s  | 0.0%|
|mbo_E4E17.smt2                                                                              |  15.363s  |  15.363s  |   0.000s  | 0.0%|
|mbo_E4E27.smt2                                                                              | 114.586s  | 114.586s  |   0.000s  | 0.0%|
|mbo_E5E12.smt2                                                                              |  16.761s  |  16.761s  |   0.000s  | 0.0%|
|mbo_E5E23.smt2                                                                              |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|mbo_E6.smt2                                                                                 |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|mbo_E6E19.smt2                                                                              |  62.150s  |  62.150s  |   0.000s  | 0.0%|
|mbo_E6E7.smt2                                                                               |  14.135s  |  14.135s  |   0.000s  | 0.0%|
|mbo_E7E16.smt2                                                                              | 113.037s  | 113.037s  |   0.000s  | 0.0%|
|mbo_E7E26.smt2                                                                              |  25.611s  |  25.611s  |   0.000s  | 0.0%|
|mbo_E8E14.smt2                                                                              |  99.595s  |  99.595s  |   0.000s  | 0.0%|
|mbo_E8E24.smt2                                                                              |  56.986s  |  56.986s  |   0.000s  | 0.0%|
|mbo_E9E13.smt2                                                                              |  14.369s  |  14.369s  |   0.000s  | 0.0%|
|mbo_E9E23.smt2                                                                              |  97.584s  |  97.584s  |   0.000s  | 0.0%|
|mc91test.t2.c_Iteration5_Loop_3-pieceTemplate.smt2                                          |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|mgc_06.smt2                                                                                 |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|min_rf_true-termination.c_Iteration1_Loop_4-pieceTemplate.smt2                              | 200.082s  | 200.082s  |   0.000s  | 0.0%|
|nested.t2.c_Iteration3_Loop_3-pieceTemplate.smt2                                            |  32.195s  |  32.195s  |   0.000s  | 0.0%|
|p-42.t2.c_Iteration2_Loop_4-pieceTemplate.smt2                                              |   0.366s  |   0.366s  |   0.000s  | 0.0%|
|p-46.t2.c_Iteration2_Lasso_7-phaseTemplate.smt2                                             | 200.077s  | 200.077s  |   0.000s  | 0.0%|
|p-55.t2.c_Iteration3_Loop_4-pieceTemplate.smt2                                              |   4.674s  |   4.674s  |   0.000s  | 0.0%|
|pentagon.t2.c_Iteration9_Loop_3-pieceTemplate.smt2                                          |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|polypaver-bench-exp-3d-chunk-0028.smt2                                                      |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|polypaver-bench-exp-3d-chunk-0072.smt2                                                      |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|polypaver-bench-exp-3d-chunk-0085.smt2                                                      |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|polypaver-bench-exp-3d-chunk-0109.smt2                                                      |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|polypaver-bench-exp-3d-chunk-0126.smt2                                                      |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|polypaver-bench-exp-3d-chunk-0138.smt2                                                      |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0020.smt2                                                     |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0069.smt2                                                     |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0087.smt2                                                     |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0100.smt2                                                     |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0144.smt2                                                     |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0162.smt2                                                     |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0183.smt2                                                     |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0196.smt2                                                     |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0206.smt2                                                     |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0217.smt2                                                     |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0227.smt2                                                     |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0237.smt2                                                     |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0250.smt2                                                     |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0265.smt2                                                     |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0278.smt2                                                     |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0288.smt2                                                     |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0299.smt2                                                     |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0310.smt2                                                     |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0320.smt2                                                     |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0330.smt2                                                     |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0342.smt2                                                     |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0352.smt2                                                     |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0369.smt2                                                     |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0379.smt2                                                     |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0390.smt2                                                     |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0405.smt2                                                     |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0415.smt2                                                     |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0425.smt2                                                     |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0435.smt2                                                     |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0446.smt2                                                     |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0456.smt2                                                     |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0469.smt2                                                     |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0481.smt2                                                     |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0493.smt2                                                     |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0504.smt2                                                     |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|polypaver-bench-sqrt-3d-chunk-0515.smt2                                                     |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|polypaver-sqrt-circles-1a-chunk-0011.smt2                                                   |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|polypaver-sqrt43-int-3vars-chunk-0029.smt2                                                  |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|polypaver-sqrt43-int-3vars-chunk-0043.smt2                                                  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|polypaver-sqrt43-int-3vars-chunk-0075.smt2                                                  |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|polypaver-sqrt43-int-3vars-chunk-0086.smt2                                                  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|polypaver-sqrt43-int-3vars-chunk-0103.smt2                                                  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|polypaver-sqrt43-int-3vars-chunk-0121.smt2                                                  |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|polypaver-sqrt43-int-4vars-chunk-0026.smt2                                                  |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|polypaver-sqrt43-int-chunk-0053.smt2                                                        |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|polyrank3.t2.c_Iteration2_Loop_3-pieceTemplate.smt2                                         |  28.375s  |  28.375s  |   0.000s  | 0.0%|
|polyrank3.t2.c_Iteration8_Loop_4-pieceTemplate.smt2                                         |  66.426s  |  66.426s  |   0.000s  | 0.0%|
|polyrank4.t2.c_Iteration3_Loop_3-pieceTemplate.smt2                                         |  54.532s  |  54.532s  |   0.000s  | 0.0%|
|polyrank4.t2.c_Iteration8_Loop_2-pieceTemplate.smt2                                         |  52.194s  |  52.194s  |   0.000s  | 0.0%|
|polyrank5.t2.c_Iteration1_Loop_7-phaseTemplate.smt2                                         |  51.104s  |  51.104s  |   0.000s  | 0.0%|
|qrdcmp.t2.c_Iteration6_Loop_3-pieceTemplate.smt2                                            |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|sas2.t2.c_Iteration1_Lasso_4-pieceTemplate.smt2                                             | 123.257s  | 123.257s  |   0.000s  | 0.0%|
|sas2.t2.c_Iteration6_Lasso_7-nestedTemplate.smt2                                            |  56.827s  |  56.827s  |   0.000s  | 0.0%|
|selectSort.t2.c_Iteration3_Loop_4-pieceTemplate.smt2                                        |  14.610s  |  14.610s  |   0.000s  | 0.0%|
|seq.i_5_5_5.bpl_3.smt2                                                                      | 200.021s  | 200.021s  |   0.000s  | 0.0%|
|simple-scaled200.bpl_Iteration1_Lasso_7-phaseTemplate.smt2                                  |  46.259s  |  46.259s  |   0.000s  | 0.0%|
|simple_ballistics_reach.01.seq_lazy_global_11.smt2                                          | 200.016s  | 200.016s  |   0.000s  | 0.0%|
|simple_ballistics_reach.01.seq_lazy_global_7.smt2                                           | 200.054s  | 200.054s  |   0.000s  | 0.0%|
|simple_ballistics_reach.01.seq_lazy_lemmas_global_15.smt2                                   | 200.038s  | 200.038s  |   0.000s  | 0.0%|
|simple_ballistics_reach.01.seq_lazy_linear_enc_global_1.smt2                                |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|simple_ballistics_reach.01.seq_lazy_linear_enc_global_5.smt2                                | 200.032s  | 200.032s  |   0.000s  | 0.0%|
|simple_ballistics_reach.01.seq_lazy_linear_enc_lemmas_global_13.smt2                        | 200.037s  | 200.037s  |   0.000s  | 0.0%|
|simple_ballistics_reach.01.seq_lazy_linear_enc_lemmas_global_9.smt2                         | 200.037s  | 200.037s  |   0.000s  | 0.0%|
|sin-344-3-chunk-0029.smt2                                                                   |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|sin-344-3-chunk-0046.smt2                                                                   |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|sin-344-3-chunk-0058.smt2                                                                   |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|sin-344-3-weak-chunk-0017.smt2                                                              |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|sin-344-3-weak-chunk-0044.smt2                                                              |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|sin-344-4-chunk-0032.smt2                                                                   |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|sin-344-4-chunk-0050.smt2                                                                   |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0018.smt2                                                               |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0030.smt2                                                               |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0044.smt2                                                               |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0054.smt2                                                               |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0068.smt2                                                               |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0078.smt2                                                               |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0092.smt2                                                               |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0102.smt2                                                               |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0114.smt2                                                               |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0126.smt2                                                               |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0139.smt2                                                               |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0158.smt2                                                               |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0168.smt2                                                               |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0186.smt2                                                               |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0198.smt2                                                               |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0209.smt2                                                               |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0221.smt2                                                               |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0232.smt2                                                               |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0242.smt2                                                               |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0252.smt2                                                               |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0262.smt2                                                               |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0272.smt2                                                               |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0285.smt2                                                               |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0296.smt2                                                               |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0306.smt2                                                               |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0316.smt2                                                               |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0326.smt2                                                               |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0338.smt2                                                               |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0348.smt2                                                               |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0358.smt2                                                               |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0368.smt2                                                               |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0378.smt2                                                               |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0391.smt2                                                               |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0401.smt2                                                               |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0414.smt2                                                               |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0424.smt2                                                               |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0434.smt2                                                               |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0444.smt2                                                               |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0454.smt2                                                               |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0464.smt2                                                               |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0474.smt2                                                               |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0484.smt2                                                               |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0494.smt2                                                               |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0504.smt2                                                               |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0514.smt2                                                               |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0524.smt2                                                               |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0536.smt2                                                               |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0549.smt2                                                               |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0560.smt2                                                               |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0572.smt2                                                               |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0584.smt2                                                               |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0597.smt2                                                               |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0607.smt2                                                               |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0620.smt2                                                               |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|sin-cos-346-b-chunk-0631.smt2                                                               |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|sin-problem-10-2-chunk-0010.smt2                                                            |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|sin-problem-10-2-chunk-0024.smt2                                                            |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|sin-problem-10-2-chunk-0034.smt2                                                            |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|sin-problem-10-3-chunk-0023.smt2                                                            |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|sin-problem-10-3-chunk-0033.smt2                                                            |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|sin-problem-7-chunk-0054.smt2                                                               |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|sin-problem-7-chunk-0079.smt2                                                               |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|sin-problem-7-chunk-0091.smt2                                                               |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|sin-problem-7-chunk-0105.smt2                                                               |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|sin-problem-7-chunk-0117.smt2                                                               |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|sin-problem-7-chunk-0129.smt2                                                               |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|sin-problem-7-chunk-0143.smt2                                                               |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|sin-problem-7-chunk-0156.smt2                                                               |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|sin-problem-7-chunk-0172.smt2                                                               |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|sin-problem-7-chunk-0182.smt2                                                               |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|sin-problem-7-chunk-0192.smt2                                                               |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|sin-problem-7-chunk-0208.smt2                                                               |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|sin-problem-7-chunk-0221.smt2                                                               |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|sin-problem-7-chunk-0233.smt2                                                               |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|sin-problem-7-chunk-0247.smt2                                                               |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|sin-problem-7-chunk-0257.smt2                                                               |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|sin-problem-7-chunk-0273.smt2                                                               |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|sin-problem-7-chunk-0283.smt2                                                               |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|sin-problem-7-chunk-0297.smt2                                                               | 200.021s  | 200.021s  |   0.000s  | 0.0%|
|sin-problem-7-chunk-0311.smt2                                                               |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|sin-problem-7-chunk-0322.smt2                                                               |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|sin-problem-7-chunk-0335.smt2                                                               |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|sin-problem-7-chunk-0348.smt2                                                               |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|sin-problem-7-chunk-0361.smt2                                                               |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|sin-problem-7-weak-chunk-0073.smt2                                                          |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|sin-problem-7-weak-chunk-0085.smt2                                                          |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|sin-problem-7-weak-chunk-0101.smt2                                                          |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|sin-problem-7-weak-chunk-0115.smt2                                                          |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|sin-problem-7-weak-chunk-0126.smt2                                                          |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|sin-problem-7-weak-chunk-0138.smt2                                                          |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|sin-problem-7-weak-chunk-0149.smt2                                                          |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|sin-problem-7-weak-chunk-0160.smt2                                                          |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|sin-problem-7-weak-chunk-0171.smt2                                                          |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|sin-problem-7-weak-chunk-0181.smt2                                                          |   3.050s  |   3.050s  |   0.000s  | 0.0%|
|sin-problem-7-weak2-chunk-0044.smt2                                                         |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|sin-problem-7-weak2-chunk-0057.smt2                                                         |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|sin-problem-7-weak2-chunk-0075.smt2                                                         |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|sin-problem-7-weak2-chunk-0088.smt2                                                         |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|sin-problem-7-weak2-chunk-0100.smt2                                                         |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|sin-problem-7-weak2-chunk-0113.smt2                                                         |   2.628s  |   2.628s  |   0.000s  | 0.0%|
|sin-problem-7-weak2-chunk-0123.smt2                                                         |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|sin-problem-8-chunk-0026.smt2                                                               |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|sin-problem-8-chunk-0043.smt2                                                               |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|sin-problem-8-chunk-0054.smt2                                                               |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|sin-problem-8-chunk-0067.smt2                                                               |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|sin-problem-8-weak-chunk-0027.smt2                                                          |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|sin-problem-8-weak-chunk-0044.smt2                                                          |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|sin-problem-8-weak-chunk-0056.smt2                                                          |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|sin-problem-8-weak-chunk-0068.smt2                                                          |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|sin-problem-8-weak-chunk-0079.smt2                                                          |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|sort.t2.c_Iteration5_Loop_3-pieceTemplate.smt2                                              |   0.460s  |   0.460s  |   0.000s  | 0.0%|
|spiral.t2.c_Iteration8_Loop_4-pieceTemplate.smt2                                            |   0.402s  |   0.402s  |   0.000s  | 0.0%|
|sqrt-1mcosq-7-chunk-0027.smt2                                                               |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|sqrt-1mcosq-7-chunk-0039.smt2                                                               |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|sqrt-1mcosq-7-chunk-0053.smt2                                                               |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|sqrt-1mcosq-7-chunk-0077.smt2                                                               |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|sqrt-1mcosq-7-chunk-0093.smt2                                                               |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|sqrt-1mcosq-7-chunk-0116.smt2                                                               |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|sqrt-1mcosq-7-chunk-0130.smt2                                                               |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|sqrt-1mcosq-7-chunk-0143.smt2                                                               |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|sqrt-1mcosq-7-chunk-0155.smt2                                                               |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|sqrt-1mcosq-7-chunk-0167.smt2                                                               |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|sqrt-1mcosq-7-chunk-0177.smt2                                                               |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|sqrt-1mcosq-7-chunk-0191.smt2                                                               |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|sqrt-1mcosq-7-chunk-0206.smt2                                                               |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|sqrt-1mcosq-7-chunk-0216.smt2                                                               |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|sqrt-1mcosq-7-chunk-0230.smt2                                                               |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0026.smt2                                                               |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0043.smt2                                                               |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0054.smt2                                                               |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0064.smt2                                                               |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0075.smt2                                                               |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0085.smt2                                                               |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0100.smt2                                                               |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0110.smt2                                                               |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0121.smt2                                                               |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0132.smt2                                                               |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0142.smt2                                                               |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0155.smt2                                                               |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0166.smt2                                                               |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0176.smt2                                                               |  84.190s  |  84.190s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0189.smt2                                                               |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0199.smt2                                                               |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0209.smt2                                                               |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0223.smt2                                                               |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0233.smt2                                                               | 200.028s  | 200.028s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0243.smt2                                                               |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0254.smt2                                                               |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0265.smt2                                                               |  90.649s  |  90.649s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0276.smt2                                                               |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0286.smt2                                                               |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0296.smt2                                                               |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0307.smt2                                                               |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0318.smt2                                                               |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0328.smt2                                                               |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0339.smt2                                                               |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0349.smt2                                                               |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0359.smt2                                                               |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0370.smt2                                                               |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0380.smt2                                                               |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0391.smt2                                                               |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0402.smt2                                                               |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0412.smt2                                                               |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0426.smt2                                                               |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0436.smt2                                                               |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0446.smt2                                                               |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0457.smt2                                                               |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0467.smt2                                                               |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0479.smt2                                                               |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0496.smt2                                                               |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0508.smt2                                                               |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0519.smt2                                                               |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0530.smt2                                                               |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0541.smt2                                                               |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0556.smt2                                                               |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0567.smt2                                                               |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0577.smt2                                                               |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0589.smt2                                                               |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0600.smt2                                                               |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0610.smt2                                                               |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0621.smt2                                                               |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0633.smt2                                                               |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0643.smt2                                                               |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0657.smt2                                                               |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0668.smt2                                                               |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0679.smt2                                                               |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0690.smt2                                                               |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0700.smt2                                                               |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0714.smt2                                                               |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|sqrt-1mcosq-8-chunk-0728.smt2                                                               |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|sqrt-circles-2-chunk-0002.smt2                                                              |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|sqrt-circles-2-chunk-0015.smt2                                                              |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|sqrt-circles-3-chunk-0016.smt2                                                              |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|sqrt-problem-12vars3-chunk-0010.smt2                                                        |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|sqrt-problem-12vars3-chunk-0025.smt2                                                        |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|sqrt-problem-12vars3-chunk-0039.smt2                                                        |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|sqrt-problem-12vars3-chunk-0055.smt2                                                        |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|sqrt-problem-12vars3-chunk-0068.smt2                                                        |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|sqrt-problem-12vars3-chunk-0081.smt2                                                        |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|sqrt-problem-12vars3-chunk-0097.smt2                                                        |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|sqrt-problem-13-chunk-0019.smt2                                                             |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|sqrt-problem-13-sqrt1-chunk-0015.smt2                                                       |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|sqrt-problem-13-sqrt1-chunk-0034.smt2                                                       |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|sqrt-problem-13-sqrt1-chunk-0049.smt2                                                       |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|sqrt-problem-13-sqrt1-chunk-0062.smt2                                                       |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|sqrt-problem-13-sqrt1-chunk-0080.smt2                                                       |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|sqrt-problem-13-vars5-chunk-0026.smt2                                                       |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|sqrt-problem-Melquiond2-chunk-0010.smt2                                                     |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|sqrt-problem-Melquiond2-chunk-0023.smt2                                                     |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|sqrt-problem-Melquiond2-chunk-0034.smt2                                                     |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|sqrt-problem-Melquiond2-chunk-0045.smt2                                                     |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|sqrt-problem-Melquiond2-chunk-0059.smt2                                                     |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|sqrt-problem-Melquiond2-chunk-0071.smt2                                                     |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|sqrt-problem-Melquiond2-chunk-0081.smt2                                                     |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|sqrt-problem-Melquiond2-chunk-0091.smt2                                                     |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|sqrt-problem-Melquiond3-chunk-0018.smt2                                                     |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|standard_copy5_ground.i_3_2_2.bpl_3.smt2                                                    |  32.232s  |  32.232s  |   0.000s  | 0.0%|
|standard_init9_ground.i_3_2_2.bpl_1.smt2                                                    |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|standard_two_index_05.i_3_2_2.bpl_5.smt2                                                    | 200.032s  | 200.032s  |   0.000s  | 0.0%|
|toeplz.c.i.toeplz.pl.t2.fixed.t2.c_Iteration10_Loop_3-pieceTemplate.smt2                    |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|toeplz.t2.c_Iteration7_Loop_4-pieceTemplate.smt2                                            |   0.654s  |   0.654s  |   0.000s  | 0.0%|
|yPositive-MixedIntReal.bpl_Iteration1_Loop_3-pieceTemplate.smt2                             |  56.342s  |  56.342s  |   0.000s  | 0.0%|
</details>
