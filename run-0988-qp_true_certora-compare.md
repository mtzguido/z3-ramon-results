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
Job description: quotient_pairs=true inputs/certora
Job tag: qp_true_certora
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 9b30560b617f35b45d3704d99dce09c021636fca
Z3 branch: modgb
Z3 options: "-T:200 smt.arith.nl.grobner_quotient_pairs=true"
Z3 inputs: inputs/certora
Z3 commit message: nla: add quotient reasoning for equation combinations

Extend grobner quotient propagation to combine pairs and triples
of equations sharing a nonlinear variable. When equations of the
form v*lc_i + r_i = 0 share variable v, their linear combinations
produce v*lc_comb + r_comb = 0. If |v| > |r_comb| > 0 and v does
not divide r_comb, generate a conflict lemma.

This handles mod arithmetic patterns like:
  (mod (- x y) m) = 0 AND (mod x m) != (mod y m)
where the three mod expansions produce equations sharing m as
nonlinear factor, and combining them yields m*(q2-q1+q3) = r2-r3
with |r2-r3| < m, forcing r2 = r3 (contradiction).

Co-authored-by: Copilot <223556219+Copilot@users.noreply.github.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: quotient_pairs=true inputs/certora
Job tag: qp_true_certora
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 9b30560b617f35b45d3704d99dce09c021636fca
Z3 branch: modgb
Z3 options: "-T:200 smt.arith.nl.grobner_quotient_pairs=true"
Z3 inputs: inputs/certora
Z3 commit message: nla: add quotient reasoning for equation combinations

Extend grobner quotient propagation to combine pairs and triples
of equations sharing a nonlinear variable. When equations of the
form v*lc_i + r_i = 0 share variable v, their linear combinations
produce v*lc_comb + r_comb = 0. If |v| > |r_comb| > 0 and v does
not divide r_comb, generate a conflict lemma.

This handles mod arithmetic patterns like:
  (mod (- x y) m) = 0 AND (mod x m) != (mod y m)
where the three mod expansions produce equations sharing m as
nonlinear factor, and combining them yields m*(q2-q1+q3) = r2-r3
with |r2-r3| < m, forcing r2 = r3 (contradiction).

Co-authored-by: Copilot <223556219+Copilot@users.noreply.github.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |   1.863s  |   1.863s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |   0.735s  |   0.735s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |   2.271s  |   2.271s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   4.602s  |   4.602s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |   1.181s  |   1.181s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |   1.475s  |   1.475s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |   1.413s  |   1.413s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   0.873s  |   0.873s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |   8.663s  |   8.663s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |   1.769s  |   1.769s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 | 200.059s  | 200.059s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   2.472s  |   2.472s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               | 200.100s  | 200.100s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |  91.709s  |  91.709s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 | 200.116s  | 200.116s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  50.221s  |  50.221s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |   8.505s  |   8.505s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |  20.864s  |  20.864s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |  11.997s  |  11.997s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |   5.616s  |   5.616s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |   1.863s  |   1.863s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |   0.735s  |   0.735s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |   2.271s  |   2.271s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   4.602s  |   4.602s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |   1.181s  |   1.181s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |   1.475s  |   1.475s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |   1.413s  |   1.413s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   0.873s  |   0.873s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |   8.663s  |   8.663s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |   1.769s  |   1.769s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 | 200.059s  | 200.059s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   2.472s  |   2.472s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               | 200.100s  | 200.100s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |  91.709s  |  91.709s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 | 200.116s  | 200.116s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  50.221s  |  50.221s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |   8.505s  |   8.505s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |  20.864s  |  20.864s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |  11.997s  |  11.997s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |   5.616s  |   5.616s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |   1.863s  |   1.863s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |   0.735s  |   0.735s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |   2.271s  |   2.271s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   4.602s  |   4.602s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |   1.181s  |   1.181s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |   1.475s  |   1.475s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |   1.413s  |   1.413s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   0.873s  |   0.873s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |   8.663s  |   8.663s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |   1.769s  |   1.769s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 | 200.059s  | 200.059s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   2.472s  |   2.472s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               | 200.100s  | 200.100s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |  91.709s  |  91.709s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 | 200.116s  | 200.116s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  50.221s  |  50.221s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |   8.505s  |   8.505s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |  20.864s  |  20.864s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |  11.997s  |  11.997s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |   5.616s  |   5.616s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |   1.863s  |   1.863s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |   0.735s  |   0.735s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |   2.271s  |   2.271s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   4.602s  |   4.602s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |   1.181s  |   1.181s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |   1.475s  |   1.475s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |   1.413s  |   1.413s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   0.873s  |   0.873s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |   8.663s  |   8.663s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |   1.769s  |   1.769s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 | 200.059s  | 200.059s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   2.472s  |   2.472s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               | 200.100s  | 200.100s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |  91.709s  |  91.709s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 | 200.116s  | 200.116s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  50.221s  |  50.221s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |   8.505s  |   8.505s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |  20.864s  |  20.864s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |  11.997s  |  11.997s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |   5.616s  |   5.616s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|38347_525a1ca0331f2bcbf520_54_QF_UFLIA.smt2                                                | 200.258s |2177.0MiB|
|38347_525a1ca0331f2bcbf520_54_QF_UFDTLIA.smt2                                              | 200.222s |1976.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFLIA.smt2                                    | 200.211s |1920.0MiB|
|66603_accdadf23a1cf70ae043_76_QF_UFNIA.smt2                                                | 200.185s |1565.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTLIA.smt2                                  | 200.176s |1430.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFLIA.smt2                                    | 200.166s |694.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 | 200.164s |1154.0MiB|
|66603_accdadf23a1cf70ae043_75_QF_UFLIA.smt2                                                | 200.155s |1226.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTLIA.smt2                                  | 200.146s |1180.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFLIA.smt2                                    | 200.140s |1355.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFLIA.smt2                                    | 200.137s |833.0MiB|
|83314_a702bf8b823398c9e37a_4_UFDTLIA.smt2                                                  | 200.133s |696.0MiB|
|83314_a702bf8b823398c9e37a_4_UFLIA.smt2                                                    | 200.129s |649.0MiB|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                | 200.116s |516.0MiB|
|940_590f27b1c3c800d3243e_32_QF_UFDTLIA.smt2                                                | 200.115s |526.0MiB|
|66603_accdadf23a1cf70ae043_74_QF_UFNIA.smt2                                                | 200.111s |646.0MiB|
|66603_accdadf23a1cf70ae043_75_QF_UFNIA.smt2                                                | 200.105s |639.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTLIA.smt2                                  | 200.105s |752.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTLIA.smt2                                  | 200.102s |690.0MiB|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                              | 200.100s |614.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|38347_525a1ca0331f2bcbf520_54_QF_UFLIA.smt2                                                | 200.258s |2177.0MiB|
|38347_525a1ca0331f2bcbf520_54_QF_UFDTLIA.smt2                                              | 200.222s |1976.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFLIA.smt2                                    | 200.211s |1920.0MiB|
|66603_accdadf23a1cf70ae043_76_QF_UFNIA.smt2                                                | 200.185s |1565.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTLIA.smt2                                  | 200.176s |1430.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFLIA.smt2                                    | 200.166s |694.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 | 200.164s |1154.0MiB|
|66603_accdadf23a1cf70ae043_75_QF_UFLIA.smt2                                                | 200.155s |1226.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTLIA.smt2                                  | 200.146s |1180.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFLIA.smt2                                    | 200.140s |1355.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFLIA.smt2                                    | 200.137s |833.0MiB|
|83314_a702bf8b823398c9e37a_4_UFDTLIA.smt2                                                  | 200.133s |696.0MiB|
|83314_a702bf8b823398c9e37a_4_UFLIA.smt2                                                    | 200.129s |649.0MiB|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                | 200.116s |516.0MiB|
|940_590f27b1c3c800d3243e_32_QF_UFDTLIA.smt2                                                | 200.115s |526.0MiB|
|66603_accdadf23a1cf70ae043_74_QF_UFNIA.smt2                                                | 200.111s |646.0MiB|
|66603_accdadf23a1cf70ae043_75_QF_UFNIA.smt2                                                | 200.105s |639.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTLIA.smt2                                  | 200.105s |752.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTLIA.smt2                                  | 200.102s |690.0MiB|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                              | 200.100s |614.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |36.528MiB|36.528MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |29.236MiB|29.236MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |40.108MiB|40.108MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |31.948MiB|31.948MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |34.612MiB|34.612MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |28.344MiB|28.344MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |34.396MiB|34.396MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |27.668MiB|27.668MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |66.844MiB|66.844MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |23.252MiB|23.252MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 |154.0MiB|154.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |23.428MiB|23.428MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               |614.0MiB|614.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |37.504MiB|37.504MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 |516.0MiB|516.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |37.62MiB|37.62MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |67.008MiB|67.008MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |34.744MiB|34.744MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |72.988MiB|72.988MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |31.596MiB|31.596MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |36.528MiB|36.528MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |29.236MiB|29.236MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |40.108MiB|40.108MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |31.948MiB|31.948MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |34.612MiB|34.612MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |28.344MiB|28.344MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |34.396MiB|34.396MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |27.668MiB|27.668MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |66.844MiB|66.844MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |23.252MiB|23.252MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 |154.0MiB|154.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |23.428MiB|23.428MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               |614.0MiB|614.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |37.504MiB|37.504MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 |516.0MiB|516.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |37.62MiB|37.62MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |67.008MiB|67.008MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |34.744MiB|34.744MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |72.988MiB|72.988MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |31.596MiB|31.596MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |36.528MiB|36.528MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |29.236MiB|29.236MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |40.108MiB|40.108MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |31.948MiB|31.948MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |34.612MiB|34.612MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |28.344MiB|28.344MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |34.396MiB|34.396MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |27.668MiB|27.668MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |66.844MiB|66.844MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |23.252MiB|23.252MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 |154.0MiB|154.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |23.428MiB|23.428MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               |614.0MiB|614.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |37.504MiB|37.504MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 |516.0MiB|516.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |37.62MiB|37.62MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |67.008MiB|67.008MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |34.744MiB|34.744MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |72.988MiB|72.988MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |31.596MiB|31.596MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |36.528MiB|36.528MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |29.236MiB|29.236MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |40.108MiB|40.108MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |31.948MiB|31.948MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |34.612MiB|34.612MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |28.344MiB|28.344MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |34.396MiB|34.396MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |27.668MiB|27.668MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |66.844MiB|66.844MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |23.252MiB|23.252MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 |154.0MiB|154.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |23.428MiB|23.428MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               |614.0MiB|614.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |37.504MiB|37.504MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 |516.0MiB|516.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |37.62MiB|37.62MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |67.008MiB|67.008MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |34.744MiB|34.744MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |72.988MiB|72.988MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |31.596MiB|31.596MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|38347_525a1ca0331f2bcbf520_54_QF_UFLIA.smt2                                                | 200.258s |2177.0MiB|
|38347_525a1ca0331f2bcbf520_54_QF_UFDTLIA.smt2                                              | 200.222s |1976.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFLIA.smt2                                    | 200.211s |1920.0MiB|
|66603_accdadf23a1cf70ae043_76_QF_UFLIA.smt2                                                |  99.594s |1737.0MiB|
|66603_accdadf23a1cf70ae043_76_QF_UFNIA.smt2                                                | 200.185s |1565.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTLIA.smt2                                  | 200.176s |1430.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFLIA.smt2                                    | 200.140s |1355.0MiB|
|66603_accdadf23a1cf70ae043_75_QF_UFLIA.smt2                                                | 200.155s |1226.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTLIA.smt2                                  | 200.146s |1180.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 | 200.164s |1154.0MiB|
|83314_a702bf8b823398c9e37a_3_UFDTLIA.smt2                                                  | 195.405s |857.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFLIA.smt2                                    | 200.137s |833.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTLIA.smt2                                  | 200.105s |752.0MiB|
|83314_a702bf8b823398c9e37a_4_UFDTLIA.smt2                                                  | 200.133s |696.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFLIA.smt2                                    | 200.166s |694.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTLIA.smt2                                  | 200.096s |692.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTLIA.smt2                                  | 200.102s |690.0MiB|
|83314_a702bf8b823398c9e37a_4_UFLIA.smt2                                                    | 200.129s |649.0MiB|
|66603_accdadf23a1cf70ae043_74_QF_UFNIA.smt2                                                | 200.111s |646.0MiB|
|66603_accdadf23a1cf70ae043_75_QF_UFNIA.smt2                                                | 200.105s |639.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|38347_525a1ca0331f2bcbf520_54_QF_UFLIA.smt2                                                | 200.258s |2177.0MiB|
|38347_525a1ca0331f2bcbf520_54_QF_UFDTLIA.smt2                                              | 200.222s |1976.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFLIA.smt2                                    | 200.211s |1920.0MiB|
|66603_accdadf23a1cf70ae043_76_QF_UFLIA.smt2                                                |  99.594s |1737.0MiB|
|66603_accdadf23a1cf70ae043_76_QF_UFNIA.smt2                                                | 200.185s |1565.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTLIA.smt2                                  | 200.176s |1430.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFLIA.smt2                                    | 200.140s |1355.0MiB|
|66603_accdadf23a1cf70ae043_75_QF_UFLIA.smt2                                                | 200.155s |1226.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTLIA.smt2                                  | 200.146s |1180.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 | 200.164s |1154.0MiB|
|83314_a702bf8b823398c9e37a_3_UFDTLIA.smt2                                                  | 195.405s |857.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFLIA.smt2                                    | 200.137s |833.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTLIA.smt2                                  | 200.105s |752.0MiB|
|83314_a702bf8b823398c9e37a_4_UFDTLIA.smt2                                                  | 200.133s |696.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFLIA.smt2                                    | 200.166s |694.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTLIA.smt2                                  | 200.096s |692.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTLIA.smt2                                  | 200.102s |690.0MiB|
|83314_a702bf8b823398c9e37a_4_UFLIA.smt2                                                    | 200.129s |649.0MiB|
|66603_accdadf23a1cf70ae043_74_QF_UFNIA.smt2                                                | 200.111s |646.0MiB|
|66603_accdadf23a1cf70ae043_75_QF_UFNIA.smt2                                                | 200.105s |639.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |   1.863s  |   1.863s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |   0.735s  |   0.735s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |   2.271s  |   2.271s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   4.602s  |   4.602s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |   1.181s  |   1.181s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |   1.475s  |   1.475s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |   1.413s  |   1.413s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   0.873s  |   0.873s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |   8.663s  |   8.663s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |   1.769s  |   1.769s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 | 200.059s  | 200.059s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   2.472s  |   2.472s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               | 200.100s  | 200.100s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |  91.709s  |  91.709s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 | 200.116s  | 200.116s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  50.221s  |  50.221s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |   8.505s  |   8.505s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |  20.864s  |  20.864s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |  11.997s  |  11.997s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |   5.616s  |   5.616s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTLIA.smt2                                   | 200.176s  | 200.176s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTNIA.smt2                                   |  46.643s  |  46.643s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFLIA.smt2                                     | 200.140s  | 200.140s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     | 200.035s  | 200.035s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTLIA.smt2                                   | 200.102s  | 200.102s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTNIA.smt2                                   |   2.756s  |   2.756s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFLIA.smt2                                     | 200.137s  | 200.137s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFNIA.smt2                                     |   9.262s  |   9.262s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTLIA.smt2                                   | 200.146s  | 200.146s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTNIA.smt2                                   | 200.020s  | 200.020s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFLIA.smt2                                     | 200.211s  | 200.211s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFNIA.smt2                                     | 200.057s  | 200.057s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTLIA.smt2                                   | 200.105s  | 200.105s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTNIA.smt2                                   |   6.340s  |   6.340s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFLIA.smt2                                     | 200.166s  | 200.166s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFNIA.smt2                                     | 200.052s  | 200.052s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTLIA.smt2                                   | 200.096s  | 200.096s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTNIA.smt2                                   | 200.041s  | 200.041s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFLIA.smt2                                     | 200.079s  | 200.079s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFNIA.smt2                                     |   4.187s  |   4.187s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_27_QF_UFDTLIA.smt2                                               |  38.078s  |  38.078s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_27_QF_UFDTNIA.smt2                                               |  30.605s  |  30.605s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_27_QF_UFLIA.smt2                                                 | 163.777s  | 163.777s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_27_QF_UFNIA.smt2                                                 | 118.069s  | 118.069s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_28_QF_UFDTLIA.smt2                                               |  83.919s  |  83.919s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_28_QF_UFDTNIA.smt2                                               |  80.371s  |  80.371s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_28_QF_UFLIA.smt2                                                 | 193.218s  | 193.218s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_28_QF_UFNIA.smt2                                                 | 175.726s  | 175.726s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_38_QF_UFDTLIA.smt2                                                | 200.065s  | 200.065s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_38_QF_UFDTNIA.smt2                                                | 200.076s  | 200.076s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_38_QF_UFLIA.smt2                                                  | 200.096s  | 200.096s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                  | 200.164s  | 200.164s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_39_QF_UFDTLIA.smt2                                                |  16.418s  |  16.418s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_39_QF_UFDTNIA.smt2                                                |  39.536s  |  39.536s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_39_QF_UFLIA.smt2                                                  |  87.036s  |  87.036s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_39_QF_UFNIA.smt2                                                  | 200.063s  | 200.063s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_40_QF_UFDTLIA.smt2                                                |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_40_QF_UFDTNIA.smt2                                                |   0.274s  |   0.274s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_40_QF_UFLIA.smt2                                                  |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_40_QF_UFNIA.smt2                                                  |   0.478s  |   0.478s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_41_QF_UFDTLIA.smt2                                                |   3.782s  |   3.782s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_41_QF_UFDTNIA.smt2                                                |   5.489s  |   5.489s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_41_QF_UFLIA.smt2                                                  |   5.427s  |   5.427s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_41_QF_UFNIA.smt2                                                  |  30.694s  |  30.694s  |   0.000s  | 0.0%|
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFDTLIA.smt2                                    |  19.311s  |  19.311s  |   0.000s  | 0.0%|
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFDTNIA.smt2                                    |  16.848s  |  16.848s  |   0.000s  | 0.0%|
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFLIA.smt2                                      | 200.050s  | 200.050s  |   0.000s  | 0.0%|
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFNIA.smt2                                      |  71.485s  |  71.485s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_55_QF_UFDTLIA.smt2                                               |  26.689s  |  26.689s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_55_QF_UFDTNIA.smt2                                               | 200.031s  | 200.031s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_55_QF_UFLIA.smt2                                                 | 200.014s  | 200.014s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_55_QF_UFNIA.smt2                                                 | 200.033s  | 200.033s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_56_QF_UFDTLIA.smt2                                               | 200.061s  | 200.061s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_56_QF_UFDTNIA.smt2                                               |   3.672s  |   3.672s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_56_QF_UFLIA.smt2                                                 | 200.054s  | 200.054s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_56_QF_UFNIA.smt2                                                 |  15.569s  |  15.569s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_57_QF_UFDTLIA.smt2                                               | 200.018s  | 200.018s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_57_QF_UFDTNIA.smt2                                               | 200.039s  | 200.039s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_57_QF_UFLIA.smt2                                                 | 200.014s  | 200.014s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_57_QF_UFNIA.smt2                                                 | 200.016s  | 200.016s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_58_QF_UFDTLIA.smt2                                               |   0.541s  |   0.541s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_58_QF_UFDTNIA.smt2                                               |   0.476s  |   0.476s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_58_QF_UFLIA.smt2                                                 |   2.097s  |   2.097s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_58_QF_UFNIA.smt2                                                 |   2.027s  |   2.027s  |   0.000s  | 0.0%|
|38347_525a1ca0331f2bcbf520_54_QF_UFDTLIA.smt2                                               | 200.222s  | 200.222s  |   0.000s  | 0.0%|
|38347_525a1ca0331f2bcbf520_54_QF_UFDTNIA.smt2                                               | 200.062s  | 200.062s  |   0.000s  | 0.0%|
|38347_525a1ca0331f2bcbf520_54_QF_UFLIA.smt2                                                 | 200.258s  | 200.258s  |   0.000s  | 0.0%|
|38347_525a1ca0331f2bcbf520_54_QF_UFNIA.smt2                                                 | 200.066s  | 200.066s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_44_QF_UFDTLIA.smt2                                               |   3.036s  |   3.036s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_44_QF_UFDTNIA.smt2                                               |  19.010s  |  19.010s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_44_QF_UFLIA.smt2                                                 |  12.863s  |  12.863s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_44_QF_UFNIA.smt2                                                 | 200.035s  | 200.035s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_45_QF_UFDTLIA.smt2                                               |   5.534s  |   5.534s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_45_QF_UFDTNIA.smt2                                               |  20.917s  |  20.917s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_45_QF_UFLIA.smt2                                                 |  11.645s  |  11.645s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_45_QF_UFNIA.smt2                                                 |  81.587s  |  81.587s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_46_QF_UFDTLIA.smt2                                               |   2.879s  |   2.879s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_46_QF_UFDTNIA.smt2                                               |  55.594s  |  55.594s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_46_QF_UFLIA.smt2                                                 |  36.162s  |  36.162s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_46_QF_UFNIA.smt2                                                 | 200.042s  | 200.042s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_47_QF_UFDTLIA.smt2                                               |  10.133s  |  10.133s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_47_QF_UFDTNIA.smt2                                               |   2.823s  |   2.823s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_47_QF_UFLIA.smt2                                                 |  68.261s  |  68.261s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_47_QF_UFNIA.smt2                                                 |   3.374s  |   3.374s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_48_QF_UFDTLIA.smt2                                               |   6.039s  |   6.039s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_48_QF_UFDTNIA.smt2                                               |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_48_QF_UFLIA.smt2                                                 |  38.794s  |  38.794s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_48_QF_UFNIA.smt2                                                 |  16.362s  |  16.362s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_61_QF_UFDTLIA.smt2                                               | 159.006s  | 159.006s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_61_QF_UFDTNIA.smt2                                               | 200.061s  | 200.061s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_61_QF_UFLIA.smt2                                                 | 200.045s  | 200.045s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_61_QF_UFNIA.smt2                                                 |   3.423s  |   3.423s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_62_QF_UFDTLIA.smt2                                               |  21.058s  |  21.058s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_62_QF_UFDTNIA.smt2                                               | 200.045s  | 200.045s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_62_QF_UFLIA.smt2                                                 |  15.479s  |  15.479s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_62_QF_UFNIA.smt2                                                 | 200.051s  | 200.051s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_63_QF_UFDTLIA.smt2                                               |   3.841s  |   3.841s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_63_QF_UFDTNIA.smt2                                               | 100.402s  | 100.402s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_63_QF_UFLIA.smt2                                                 |   6.466s  |   6.466s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_63_QF_UFNIA.smt2                                                 | 200.023s  | 200.023s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_59_QF_UFDTLIA.smt2                                               |   1.536s  |   1.536s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_59_QF_UFDTNIA.smt2                                               |   0.486s  |   0.486s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_59_QF_UFLIA.smt2                                                 |   9.875s  |   9.875s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_59_QF_UFNIA.smt2                                                 |  13.192s  |  13.192s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_60_QF_UFDTLIA.smt2                                               |   1.461s  |   1.461s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_60_QF_UFDTNIA.smt2                                               |   0.733s  |   0.733s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_60_QF_UFLIA.smt2                                                 |   5.621s  |   5.621s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_60_QF_UFNIA.smt2                                                 |   6.417s  |   6.417s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_14_QF_UFDTLIA.smt2                                               |   2.396s  |   2.396s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_14_QF_UFDTNIA.smt2                                               |   2.039s  |   2.039s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_14_QF_UFLIA.smt2                                                 |  56.449s  |  56.449s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_14_QF_UFNIA.smt2                                                 |  18.781s  |  18.781s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_15_QF_UFDTLIA.smt2                                               |  11.026s  |  11.026s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_15_QF_UFDTNIA.smt2                                               |   7.083s  |   7.083s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_15_QF_UFLIA.smt2                                                 | 200.087s  | 200.087s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_15_QF_UFNIA.smt2                                                 | 200.092s  | 200.092s  |   0.000s  | 0.0%|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFDTLIA.smt2                                   |  12.436s  |  12.436s  |   0.000s  | 0.0%|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFDTNIA.smt2                                   |  53.591s  |  53.591s  |   0.000s  | 0.0%|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFLIA.smt2                                     | 200.037s  | 200.037s  |   0.000s  | 0.0%|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFNIA.smt2                                     | 121.274s  | 121.274s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_17_QF_UFDTLIA.smt2                                               |   3.012s  |   3.012s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_17_QF_UFDTNIA.smt2                                               |   2.909s  |   2.909s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_17_QF_UFLIA.smt2                                                 |  18.386s  |  18.386s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_17_QF_UFNIA.smt2                                                 | 193.798s  | 193.798s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_18_QF_UFDTLIA.smt2                                               |   2.863s  |   2.863s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_18_QF_UFDTNIA.smt2                                               |   3.348s  |   3.348s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_18_QF_UFLIA.smt2                                                 |   7.613s  |   7.613s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_18_QF_UFNIA.smt2                                                 |  18.639s  |  18.639s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_34_QF_UFDTLIA.smt2                                               |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_34_QF_UFDTNIA.smt2                                               | 200.033s  | 200.033s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_34_QF_UFLIA.smt2                                                 |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_34_QF_UFNIA.smt2                                                 | 200.044s  | 200.044s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_35_QF_UFDTLIA.smt2                                               |   0.921s  |   0.921s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_35_QF_UFDTNIA.smt2                                               | 200.025s  | 200.025s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_35_QF_UFLIA.smt2                                                 |   1.207s  |   1.207s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_35_QF_UFNIA.smt2                                                 | 200.039s  | 200.039s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_36_QF_UFDTLIA.smt2                                               | 153.679s  | 153.679s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_36_QF_UFDTNIA.smt2                                               | 200.034s  | 200.034s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_36_QF_UFLIA.smt2                                                 |  45.620s  |  45.620s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_36_QF_UFNIA.smt2                                                 | 200.043s  | 200.043s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFDTLIA.smt2                                   |   0.559s  |   0.559s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFDTNIA.smt2                                   |   0.573s  |   0.573s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFLIA.smt2                                     |  61.301s  |  61.301s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFNIA.smt2                                     | 100.374s  | 100.374s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFDTLIA.smt2                                   |   0.690s  |   0.690s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFDTNIA.smt2                                   |   2.000s  |   2.000s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFLIA.smt2                                     |  31.510s  |  31.510s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFNIA.smt2                                     |  85.794s  |  85.794s  |   0.000s  | 0.0%|
|52759_b3ecd2335fd16ec2eee2_9_UFDTLIA.smt2                                                   | 200.046s  | 200.046s  |   0.000s  | 0.0%|
|52759_b3ecd2335fd16ec2eee2_9_UFDTNIA.smt2                                                   | 200.043s  | 200.043s  |   0.000s  | 0.0%|
|52759_b3ecd2335fd16ec2eee2_9_UFLIA.smt2                                                     | 200.061s  | 200.061s  |   0.000s  | 0.0%|
|52759_b3ecd2335fd16ec2eee2_9_UFNIA.smt2                                                     | 200.029s  | 200.029s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFDTLIA.smt2                                   | 108.824s  | 108.824s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFDTNIA.smt2                                   |  84.612s  |  84.612s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFLIA.smt2                                     | 200.081s  | 200.081s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFNIA.smt2                                     | 200.075s  | 200.075s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFDTLIA.smt2                                   |  34.467s  |  34.467s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFDTNIA.smt2                                   |   3.144s  |   3.144s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFLIA.smt2                                     |  67.739s  |  67.739s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFNIA.smt2                                     | 200.079s  | 200.079s  |   0.000s  | 0.0%|
|63058_55d6bef5390186355f11_26_QF_UFDTLIA.smt2                                               |   3.368s  |   3.368s  |   0.000s  | 0.0%|
|63058_55d6bef5390186355f11_26_QF_UFDTNIA.smt2                                               |  19.303s  |  19.303s  |   0.000s  | 0.0%|
|63058_55d6bef5390186355f11_26_QF_UFLIA.smt2                                                 | 130.527s  | 130.527s  |   0.000s  | 0.0%|
|63058_55d6bef5390186355f11_26_QF_UFNIA.smt2                                                 |  85.726s  |  85.726s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_22_QF_UFDTLIA.smt2                                               |   4.792s  |   4.792s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_22_QF_UFDTNIA.smt2                                               |   7.910s  |   7.910s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_22_QF_UFLIA.smt2                                                 |  37.228s  |  37.228s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_22_QF_UFNIA.smt2                                                 | 200.042s  | 200.042s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_23_QF_UFDTLIA.smt2                                               |   5.278s  |   5.278s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_23_QF_UFDTNIA.smt2                                               |  13.723s  |  13.723s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_23_QF_UFLIA.smt2                                                 |  98.526s  |  98.526s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_23_QF_UFNIA.smt2                                                 | 200.047s  | 200.047s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_24_QF_UFDTLIA.smt2                                               |   7.300s  |   7.300s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_24_QF_UFDTNIA.smt2                                               |   5.450s  |   5.450s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_24_QF_UFLIA.smt2                                                 |  93.853s  |  93.853s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_24_QF_UFNIA.smt2                                                 | 200.041s  | 200.041s  |   0.000s  | 0.0%|
|63058_aa742630eef64f949de269382c1f9035_25_UFDTLIA.smt2                                      |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|63058_aa742630eef64f949de269382c1f9035_25_UFDTNIA.smt2                                      |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|63058_aa742630eef64f949de269382c1f9035_25_UFLIA.smt2                                        |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|63058_aa742630eef64f949de269382c1f9035_25_UFNIA.smt2                                        |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_5_QF_UFDTLIA.smt2                                                | 200.058s  | 200.058s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_5_QF_UFDTNIA.smt2                                                | 200.030s  | 200.030s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_5_QF_UFLIA.smt2                                                  | 200.049s  | 200.049s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_5_QF_UFNIA.smt2                                                  | 200.022s  | 200.022s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_6_QF_UFDTLIA.smt2                                                |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_6_QF_UFDTNIA.smt2                                                |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_6_QF_UFLIA.smt2                                                  |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_6_QF_UFNIA.smt2                                                  |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_7_QF_UFDTLIA.smt2                                                |   0.518s  |   0.518s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_7_QF_UFDTNIA.smt2                                                |   5.188s  |   5.188s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_7_QF_UFLIA.smt2                                                  |   0.383s  |   0.383s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_7_QF_UFNIA.smt2                                                  |   3.498s  |   3.498s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_8_QF_UFDTLIA.smt2                                                |   0.574s  |   0.574s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_8_QF_UFDTNIA.smt2                                                |   1.248s  |   1.248s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_8_QF_UFLIA.smt2                                                  |   0.797s  |   0.797s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_8_QF_UFNIA.smt2                                                  |   0.970s  |   0.970s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_72_QF_UFDTLIA.smt2                                               |   6.543s  |   6.543s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_72_QF_UFDTNIA.smt2                                               |   6.184s  |   6.184s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_72_QF_UFLIA.smt2                                                 |  24.462s  |  24.462s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                                                 | 200.094s  | 200.094s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_73_QF_UFDTLIA.smt2                                               | 200.071s  | 200.071s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_73_QF_UFDTNIA.smt2                                               |  18.555s  |  18.555s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_73_QF_UFLIA.smt2                                                 | 200.098s  | 200.098s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_73_QF_UFNIA.smt2                                                 | 200.092s  | 200.092s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_74_QF_UFDTLIA.smt2                                               |  18.442s  |  18.442s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_74_QF_UFDTNIA.smt2                                               | 200.067s  | 200.067s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_74_QF_UFLIA.smt2                                                 | 200.098s  | 200.098s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_74_QF_UFNIA.smt2                                                 | 200.111s  | 200.111s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_75_QF_UFDTLIA.smt2                                               |  21.875s  |  21.875s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_75_QF_UFDTNIA.smt2                                               | 200.063s  | 200.063s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_75_QF_UFLIA.smt2                                                 | 200.155s  | 200.155s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_75_QF_UFNIA.smt2                                                 | 200.105s  | 200.105s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_76_QF_UFDTLIA.smt2                                               |  35.325s  |  35.325s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_76_QF_UFDTNIA.smt2                                               |  14.329s  |  14.329s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_76_QF_UFLIA.smt2                                                 |  99.594s  |  99.594s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_76_QF_UFNIA.smt2                                                 | 200.185s  | 200.185s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_70_QF_UFDTLIA.smt2                                               |   1.645s  |   1.645s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_70_QF_UFDTNIA.smt2                                               | 200.040s  | 200.040s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_70_QF_UFLIA.smt2                                                 |  21.912s  |  21.912s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_70_QF_UFNIA.smt2                                                 | 200.039s  | 200.039s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_71_QF_UFDTLIA.smt2                                               | 200.050s  | 200.050s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_71_QF_UFDTNIA.smt2                                               | 200.023s  | 200.023s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_71_QF_UFLIA.smt2                                                 | 200.065s  | 200.065s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_71_QF_UFNIA.smt2                                                 | 200.045s  | 200.045s  |   0.000s  | 0.0%|
|72771_f9d228efc97cf1458e38_64_QF_UFDTLIA.smt2                                               |   6.597s  |   6.597s  |   0.000s  | 0.0%|
|72771_f9d228efc97cf1458e38_64_QF_UFDTNIA.smt2                                               |   0.485s  |   0.485s  |   0.000s  | 0.0%|
|72771_f9d228efc97cf1458e38_64_QF_UFLIA.smt2                                                 |  55.035s  |  55.035s  |   0.000s  | 0.0%|
|72771_f9d228efc97cf1458e38_64_QF_UFNIA.smt2                                                 |  70.200s  |  70.200s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_0_UFDTLIA.smt2                                                   |  83.709s  |  83.709s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_0_UFDTNIA.smt2                                                   |   0.961s  |   0.961s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_0_UFLIA.smt2                                                     | 200.062s  | 200.062s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_0_UFNIA.smt2                                                     |   1.426s  |   1.426s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_1_UFDTLIA.smt2                                                   | 200.099s  | 200.099s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_1_UFDTNIA.smt2                                                   |  56.083s  |  56.083s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_1_UFLIA.smt2                                                     | 200.069s  | 200.069s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_1_UFNIA.smt2                                                     |  17.844s  |  17.844s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_2_UFDTLIA.smt2                                                   | 200.050s  | 200.050s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_2_UFDTNIA.smt2                                                   | 200.056s  | 200.056s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_2_UFLIA.smt2                                                     | 200.037s  | 200.037s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_2_UFNIA.smt2                                                     | 200.052s  | 200.052s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_3_UFDTLIA.smt2                                                   | 195.405s  | 195.405s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_3_UFDTNIA.smt2                                                   | 200.043s  | 200.043s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_3_UFLIA.smt2                                                     | 200.079s  | 200.079s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_3_UFNIA.smt2                                                     | 200.028s  | 200.028s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_4_UFDTLIA.smt2                                                   | 200.133s  | 200.133s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_4_UFDTNIA.smt2                                                   | 200.043s  | 200.043s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_4_UFLIA.smt2                                                     | 200.129s  | 200.129s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_4_UFNIA.smt2                                                     | 200.061s  | 200.061s  |   0.000s  | 0.0%|
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFDTLIA.smt2                                   |  37.245s  |  37.245s  |   0.000s  | 0.0%|
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFDTNIA.smt2                                   | 142.198s  | 142.198s  |   0.000s  | 0.0%|
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFLIA.smt2                                     | 200.052s  | 200.052s  |   0.000s  | 0.0%|
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFNIA.smt2                                     | 200.059s  | 200.059s  |   0.000s  | 0.0%|
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFDTLIA.smt2                                   | 170.121s  | 170.121s  |   0.000s  | 0.0%|
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFDTNIA.smt2                                   |  64.972s  |  64.972s  |   0.000s  | 0.0%|
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFLIA.smt2                                     |  34.541s  |  34.541s  |   0.000s  | 0.0%|
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFNIA.smt2                                     |  73.391s  |  73.391s  |   0.000s  | 0.0%|
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFDTLIA.smt2                                   | 200.052s  | 200.052s  |   0.000s  | 0.0%|
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFDTNIA.smt2                                   | 200.063s  | 200.063s  |   0.000s  | 0.0%|
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFLIA.smt2                                     | 200.060s  | 200.060s  |   0.000s  | 0.0%|
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFNIA.smt2                                     | 200.063s  | 200.063s  |   0.000s  | 0.0%|
|93493_5990a6bf5f2740164f77_50_QF_UFDTLIA.smt2                                               | 179.110s  | 179.110s  |   0.000s  | 0.0%|
|93493_5990a6bf5f2740164f77_50_QF_UFDTNIA.smt2                                               | 200.073s  | 200.073s  |   0.000s  | 0.0%|
|93493_5990a6bf5f2740164f77_50_QF_UFLIA.smt2                                                 | 200.055s  | 200.055s  |   0.000s  | 0.0%|
|93493_5990a6bf5f2740164f77_50_QF_UFNIA.smt2                                                 | 200.060s  | 200.060s  |   0.000s  | 0.0%|
|93493_798593962ee29ad45ac8_52_QF_UFDTLIA.smt2                                               | 200.061s  | 200.061s  |   0.000s  | 0.0%|
|93493_798593962ee29ad45ac8_52_QF_UFDTNIA.smt2                                               | 200.034s  | 200.034s  |   0.000s  | 0.0%|
|93493_798593962ee29ad45ac8_52_QF_UFLIA.smt2                                                 | 200.062s  | 200.062s  |   0.000s  | 0.0%|
|93493_798593962ee29ad45ac8_52_QF_UFNIA.smt2                                                 | 200.046s  | 200.046s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_29_QF_UFDTLIA.smt2                                                 | 200.098s  | 200.098s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_29_QF_UFDTNIA.smt2                                                 |  40.604s  |  40.604s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_29_QF_UFLIA.smt2                                                   | 200.064s  | 200.064s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_29_QF_UFNIA.smt2                                                   | 106.471s  | 106.471s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_30_QF_UFDTLIA.smt2                                                 | 200.085s  | 200.085s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_30_QF_UFDTNIA.smt2                                                 | 200.083s  | 200.083s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_30_QF_UFLIA.smt2                                                   | 200.068s  | 200.068s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_30_QF_UFNIA.smt2                                                   | 136.135s  | 136.135s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_31_QF_UFDTLIA.smt2                                                 |  52.719s  |  52.719s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_31_QF_UFDTNIA.smt2                                                 |  19.049s  |  19.049s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_31_QF_UFLIA.smt2                                                   | 200.029s  | 200.029s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_31_QF_UFNIA.smt2                                                   |   9.598s  |   9.598s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_32_QF_UFDTLIA.smt2                                                 | 200.115s  | 200.115s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_32_QF_UFDTNIA.smt2                                                 | 137.774s  | 137.774s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_32_QF_UFLIA.smt2                                                   | 200.072s  | 200.072s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_32_QF_UFNIA.smt2                                                   |  43.959s  |  43.959s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_33_QF_UFDTLIA.smt2                                                 | 200.070s  | 200.070s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_33_QF_UFDTNIA.smt2                                                 | 200.063s  | 200.063s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_33_QF_UFLIA.smt2                                                   | 200.072s  | 200.072s  |   0.000s  | 0.0%|
</details>
