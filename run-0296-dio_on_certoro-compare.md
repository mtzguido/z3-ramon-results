Comparing data and data


# SUMMARY
- LHS tests = 308
- RHS tests = 308
- LHS success = 307  (99.67532467532467%)
- RHS success = 307  (99.67532467532467%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: dio on certora
Job tag: dio_on_certoro
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 8d81a2dcaf4de007ce587f396f1b48fbc29646dd
Z3 branch: 
Z3 options: "-T:600 -st smt.arith.lp.dio_eqs=true"
Z3 inputs: inputs/certora
Z3 commit message: Note that Z3_get_numeral_small is essentially redundant (#7599)

* Check that Z3_get_numeral_small is given non-null out params

Analogous to other Z3_get_numeral_* functions with out params.

* Note that Z3_get_numeral_small is essentially redundant

The error behavior of Z3_get_numeral_small does not follow the pattern of
the other functions. The functions that have out params and return a bool
indicating success (such as Z3_get_numeral_rational_int64) return false
rather than signaling an error when given an unsupported expression
argument (such as a rounding mode value). The functions that do not have out
params signal an error in such cases. Z3_get_numeral_small is the odd one
out in that it signals errors and returns a status bool.

This error handling is the only difference between Z3_get_numeral_small and
Z3_get_numeral_rational_int64, so this patch adds a comment to the
documentation.

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: dio on certora
Job tag: dio_on_certoro
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 8d81a2dcaf4de007ce587f396f1b48fbc29646dd
Z3 branch: 
Z3 options: "-T:600 -st smt.arith.lp.dio_eqs=true"
Z3 inputs: inputs/certora
Z3 commit message: Note that Z3_get_numeral_small is essentially redundant (#7599)

* Check that Z3_get_numeral_small is given non-null out params

Analogous to other Z3_get_numeral_* functions with out params.

* Note that Z3_get_numeral_small is essentially redundant

The error behavior of Z3_get_numeral_small does not follow the pattern of
the other functions. The functions that have out params and return a bool
indicating success (such as Z3_get_numeral_rational_int64) return false
rather than signaling an error when given an unsupported expression
argument (such as a rounding mode value). The functions that do not have out
params signal an error in such cases. Z3_get_numeral_small is the odd one
out in that it signals errors and returns a status bool.

This error handling is the only difference between Z3_get_numeral_small and
Z3_get_numeral_rational_int64, so this patch adds a comment to the
documentation.

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |   1.342s  |   1.342s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |   1.515s  |   1.515s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |   2.097s  |   2.097s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   1.313s  |   1.313s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |   0.660s  |   0.660s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |   1.873s  |   1.873s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |   1.172s  |   1.172s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   1.440s  |   1.440s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |   9.076s  |   9.076s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |   0.937s  |   0.937s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 |  44.362s  |  44.362s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   6.145s  |   6.145s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               | 599.575s  | 599.575s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               | 599.776s  | 599.776s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 | 599.715s  | 599.715s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |   8.268s  |   8.268s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |   5.554s  |   5.554s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |  24.055s  |  24.055s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |   9.548s  |   9.548s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  19.482s  |  19.482s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |   1.342s  |   1.342s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |   1.515s  |   1.515s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |   2.097s  |   2.097s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   1.313s  |   1.313s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |   0.660s  |   0.660s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |   1.873s  |   1.873s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |   1.172s  |   1.172s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   1.440s  |   1.440s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |   9.076s  |   9.076s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |   0.937s  |   0.937s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 |  44.362s  |  44.362s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   6.145s  |   6.145s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               | 599.575s  | 599.575s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               | 599.776s  | 599.776s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 | 599.715s  | 599.715s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |   8.268s  |   8.268s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |   5.554s  |   5.554s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |  24.055s  |  24.055s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |   9.548s  |   9.548s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  19.482s  |  19.482s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |   1.342s  |   1.342s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |   1.515s  |   1.515s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |   2.097s  |   2.097s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   1.313s  |   1.313s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |   0.660s  |   0.660s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |   1.873s  |   1.873s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |   1.172s  |   1.172s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   1.440s  |   1.440s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |   9.076s  |   9.076s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |   0.937s  |   0.937s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 |  44.362s  |  44.362s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   6.145s  |   6.145s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               | 599.575s  | 599.575s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               | 599.776s  | 599.776s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 | 599.715s  | 599.715s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |   8.268s  |   8.268s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |   5.554s  |   5.554s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |  24.055s  |  24.055s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |   9.548s  |   9.548s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  19.482s  |  19.482s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |   1.342s  |   1.342s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |   1.515s  |   1.515s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |   2.097s  |   2.097s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   1.313s  |   1.313s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |   0.660s  |   0.660s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |   1.873s  |   1.873s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |   1.172s  |   1.172s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   1.440s  |   1.440s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |   9.076s  |   9.076s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |   0.937s  |   0.937s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 |  44.362s  |  44.362s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   6.145s  |   6.145s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               | 599.575s  | 599.575s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               | 599.776s  | 599.776s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 | 599.715s  | 599.715s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |   8.268s  |   8.268s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |   5.554s  |   5.554s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |  24.055s  |  24.055s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |   9.548s  |   9.548s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  19.482s  |  19.482s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFLIA.smt2                                    | 600.002s |535.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFNIA.smt2                                    | 599.984s |606.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTNIA.smt2                                  | 599.979s |75.672MiB|
|72658_63104dadde9c6026353f_70_QF_UFDTNIA.smt2                                              | 599.888s |173.0MiB|
|940_590f27b1c3c800d3243e_32_QF_UFDTNIA.smt2                                                | 599.880s |176.0MiB|
|66603_accdadf23a1cf70ae043_76_QF_UFNIA.smt2                                                | 599.871s |1545.0MiB|
|44788_1965f0d6d94d5d8054ba_36_QF_UFNIA.smt2                                                | 599.839s |78.4MiB|
|83314_a702bf8b823398c9e37a_0_UFLIA.smt2                                                    | 599.836s |319.0MiB|
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFNIA.smt2                                    | 599.817s |135.0MiB|
|44289_e5a2e5c780236919ee6a_18_QF_UFNIA.smt2                                                | 599.809s |95.376MiB|
|41958_32933c5a1384696720a2_61_QF_UFDTNIA.smt2                                              | 599.808s |46.912MiB|
|83314_a702bf8b823398c9e37a_4_UFNIA.smt2                                                    | 599.789s |154.0MiB|
|44788_1965f0d6d94d5d8054ba_35_QF_UFDTNIA.smt2                                              | 599.781s |41.988MiB|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFNIA.smt2                                    | 599.780s |100.0MiB|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                              | 599.776s |38.528MiB|
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFLIA.smt2                                    | 599.768s |463.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFDTLIA.smt2                                               | 599.746s |381.0MiB|
|93493_798593962ee29ad45ac8_52_QF_UFDTNIA.smt2                                              | 599.721s |182.0MiB|
|940_590f27b1c3c800d3243e_31_QF_UFDTNIA.smt2                                                | 599.720s |98.632MiB|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                | 599.715s |652.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFLIA.smt2                                    | 600.002s |535.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFNIA.smt2                                    | 599.984s |606.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTNIA.smt2                                  | 599.979s |75.672MiB|
|72658_63104dadde9c6026353f_70_QF_UFDTNIA.smt2                                              | 599.888s |173.0MiB|
|940_590f27b1c3c800d3243e_32_QF_UFDTNIA.smt2                                                | 599.880s |176.0MiB|
|66603_accdadf23a1cf70ae043_76_QF_UFNIA.smt2                                                | 599.871s |1545.0MiB|
|44788_1965f0d6d94d5d8054ba_36_QF_UFNIA.smt2                                                | 599.839s |78.4MiB|
|83314_a702bf8b823398c9e37a_0_UFLIA.smt2                                                    | 599.836s |319.0MiB|
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFNIA.smt2                                    | 599.817s |135.0MiB|
|44289_e5a2e5c780236919ee6a_18_QF_UFNIA.smt2                                                | 599.809s |95.376MiB|
|41958_32933c5a1384696720a2_61_QF_UFDTNIA.smt2                                              | 599.808s |46.912MiB|
|83314_a702bf8b823398c9e37a_4_UFNIA.smt2                                                    | 599.789s |154.0MiB|
|44788_1965f0d6d94d5d8054ba_35_QF_UFDTNIA.smt2                                              | 599.781s |41.988MiB|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFNIA.smt2                                    | 599.780s |100.0MiB|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                              | 599.776s |38.528MiB|
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFLIA.smt2                                    | 599.768s |463.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFDTLIA.smt2                                               | 599.746s |381.0MiB|
|93493_798593962ee29ad45ac8_52_QF_UFDTNIA.smt2                                              | 599.721s |182.0MiB|
|940_590f27b1c3c800d3243e_31_QF_UFDTNIA.smt2                                                | 599.720s |98.632MiB|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                | 599.715s |652.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |35.812MiB|35.812MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |29.22MiB|29.22MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |39.936MiB|39.936MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |31.068MiB|31.068MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |34.28MiB|34.28MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |28.356MiB|28.356MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |33.944MiB|33.944MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |27.58MiB|27.58MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |67.232MiB|67.232MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |23.204MiB|23.204MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 |88.884MiB|88.884MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |23.904MiB|23.904MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               |762.0MiB|762.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |38.528MiB|38.528MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 |652.0MiB|652.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |35.252MiB|35.252MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |66.204MiB|66.204MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |34.308MiB|34.308MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |72.62MiB|72.62MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |34.488MiB|34.488MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |35.812MiB|35.812MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |29.22MiB|29.22MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |39.936MiB|39.936MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |31.068MiB|31.068MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |34.28MiB|34.28MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |28.356MiB|28.356MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |33.944MiB|33.944MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |27.58MiB|27.58MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |67.232MiB|67.232MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |23.204MiB|23.204MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 |88.884MiB|88.884MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |23.904MiB|23.904MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               |762.0MiB|762.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |38.528MiB|38.528MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 |652.0MiB|652.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |35.252MiB|35.252MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |66.204MiB|66.204MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |34.308MiB|34.308MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |72.62MiB|72.62MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |34.488MiB|34.488MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |35.812MiB|35.812MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |29.22MiB|29.22MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |39.936MiB|39.936MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |31.068MiB|31.068MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |34.28MiB|34.28MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |28.356MiB|28.356MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |33.944MiB|33.944MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |27.58MiB|27.58MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |67.232MiB|67.232MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |23.204MiB|23.204MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 |88.884MiB|88.884MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |23.904MiB|23.904MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               |762.0MiB|762.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |38.528MiB|38.528MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 |652.0MiB|652.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |35.252MiB|35.252MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |66.204MiB|66.204MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |34.308MiB|34.308MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |72.62MiB|72.62MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |34.488MiB|34.488MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |35.812MiB|35.812MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |29.22MiB|29.22MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |39.936MiB|39.936MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |31.068MiB|31.068MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |34.28MiB|34.28MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |28.356MiB|28.356MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |33.944MiB|33.944MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |27.58MiB|27.58MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |67.232MiB|67.232MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |23.204MiB|23.204MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 |88.884MiB|88.884MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |23.904MiB|23.904MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               |762.0MiB|762.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |38.528MiB|38.528MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 |652.0MiB|652.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |35.252MiB|35.252MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |66.204MiB|66.204MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |34.308MiB|34.308MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |72.62MiB|72.62MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |34.488MiB|34.488MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTLIA.smt2                                  | 599.524s |2579.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFLIA.smt2                                    | 598.082s |2566.0MiB|
|38347_525a1ca0331f2bcbf520_54_QF_UFLIA.smt2                                                | 598.774s |2408.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFLIA.smt2                                    | 599.227s |2315.0MiB|
|38347_525a1ca0331f2bcbf520_54_QF_UFDTLIA.smt2                                              | 599.387s |2221.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTLIA.smt2                                  | 599.248s |2159.0MiB|
|66603_accdadf23a1cf70ae043_76_QF_UFLIA.smt2                                                |  88.426s |1714.0MiB|
|66603_accdadf23a1cf70ae043_76_QF_UFNIA.smt2                                                | 599.871s |1545.0MiB|
|66603_accdadf23a1cf70ae043_75_QF_UFLIA.smt2                                                | 599.080s |1534.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTLIA.smt2                                  | 599.339s |1217.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFLIA.smt2                                    | 599.335s |1193.0MiB|
|66603_accdadf23a1cf70ae043_74_QF_UFNIA.smt2                                                | 599.445s |1107.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTLIA.smt2                                  | 599.448s |1063.0MiB|
|66603_accdadf23a1cf70ae043_75_QF_UFNIA.smt2                                                | 598.774s |1030.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 | 599.576s |1029.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFLIA.smt2                                    | 599.667s |1020.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTLIA.smt2                                  | 598.616s |993.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFLIA.smt2                                    | 599.585s |988.0MiB|
|66603_accdadf23a1cf70ae043_74_QF_UFLIA.smt2                                                | 599.389s |968.0MiB|
|83314_a702bf8b823398c9e37a_1_UFDTLIA.smt2                                                  | 599.631s |925.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTLIA.smt2                                  | 599.524s |2579.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFLIA.smt2                                    | 598.082s |2566.0MiB|
|38347_525a1ca0331f2bcbf520_54_QF_UFLIA.smt2                                                | 598.774s |2408.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFLIA.smt2                                    | 599.227s |2315.0MiB|
|38347_525a1ca0331f2bcbf520_54_QF_UFDTLIA.smt2                                              | 599.387s |2221.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTLIA.smt2                                  | 599.248s |2159.0MiB|
|66603_accdadf23a1cf70ae043_76_QF_UFLIA.smt2                                                |  88.426s |1714.0MiB|
|66603_accdadf23a1cf70ae043_76_QF_UFNIA.smt2                                                | 599.871s |1545.0MiB|
|66603_accdadf23a1cf70ae043_75_QF_UFLIA.smt2                                                | 599.080s |1534.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTLIA.smt2                                  | 599.339s |1217.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFLIA.smt2                                    | 599.335s |1193.0MiB|
|66603_accdadf23a1cf70ae043_74_QF_UFNIA.smt2                                                | 599.445s |1107.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTLIA.smt2                                  | 599.448s |1063.0MiB|
|66603_accdadf23a1cf70ae043_75_QF_UFNIA.smt2                                                | 598.774s |1030.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 | 599.576s |1029.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFLIA.smt2                                    | 599.667s |1020.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTLIA.smt2                                  | 598.616s |993.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFLIA.smt2                                    | 599.585s |988.0MiB|
|66603_accdadf23a1cf70ae043_74_QF_UFLIA.smt2                                                | 599.389s |968.0MiB|
|83314_a702bf8b823398c9e37a_1_UFDTLIA.smt2                                                  | 599.631s |925.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |   1.342s  |   1.342s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |   1.515s  |   1.515s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |   2.097s  |   2.097s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   1.313s  |   1.313s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |   0.660s  |   0.660s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |   1.873s  |   1.873s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |   1.172s  |   1.172s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   1.440s  |   1.440s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |   9.076s  |   9.076s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |   0.937s  |   0.937s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 |  44.362s  |  44.362s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   6.145s  |   6.145s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               | 599.575s  | 599.575s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               | 599.776s  | 599.776s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 | 599.715s  | 599.715s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |   8.268s  |   8.268s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |   5.554s  |   5.554s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |  24.055s  |  24.055s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |   9.548s  |   9.548s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |  19.482s  |  19.482s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTLIA.smt2                                   | 599.524s  | 599.524s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTNIA.smt2                                   | 597.898s  | 597.898s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFLIA.smt2                                     | 598.082s  | 598.082s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     | 599.621s  | 599.621s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTLIA.smt2                                   | 599.339s  | 599.339s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTNIA.smt2                                   | 599.397s  | 599.397s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFLIA.smt2                                     | 599.335s  | 599.335s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFNIA.smt2                                     |   3.651s  |   3.651s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTLIA.smt2                                   | 599.248s  | 599.248s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTNIA.smt2                                   | 599.979s  | 599.979s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFLIA.smt2                                     | 599.227s  | 599.227s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFNIA.smt2                                     | 599.202s  | 599.202s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTLIA.smt2                                   | 599.448s  | 599.448s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTNIA.smt2                                   |  14.947s  |  14.947s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFLIA.smt2                                     | 599.585s  | 599.585s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFNIA.smt2                                     | 599.984s  | 599.984s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTLIA.smt2                                   | 598.616s  | 598.616s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTNIA.smt2                                   |   3.362s  |   3.362s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFLIA.smt2                                     | 599.667s  | 599.667s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFNIA.smt2                                     |  11.451s  |  11.451s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_27_QF_UFDTLIA.smt2                                               |  39.365s  |  39.365s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_27_QF_UFDTNIA.smt2                                               |  42.035s  |  42.035s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_27_QF_UFLIA.smt2                                                 | 139.980s  | 139.980s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_27_QF_UFNIA.smt2                                                 |  94.505s  |  94.505s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_28_QF_UFDTLIA.smt2                                               |  99.962s  |  99.962s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_28_QF_UFDTNIA.smt2                                               |  93.341s  |  93.341s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_28_QF_UFLIA.smt2                                                 | 201.747s  | 201.747s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_28_QF_UFNIA.smt2                                                 | 150.462s  | 150.462s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_38_QF_UFDTLIA.smt2                                                | 599.746s  | 599.746s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_38_QF_UFDTNIA.smt2                                                | 599.563s  | 599.563s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_38_QF_UFLIA.smt2                                                  | 599.493s  | 599.493s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                  | 599.576s  | 599.576s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_39_QF_UFDTLIA.smt2                                                |  63.055s  |  63.055s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_39_QF_UFDTNIA.smt2                                                |  29.983s  |  29.983s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_39_QF_UFLIA.smt2                                                  | 599.285s  | 599.285s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_39_QF_UFNIA.smt2                                                  | 599.561s  | 599.561s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_40_QF_UFDTLIA.smt2                                                |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_40_QF_UFDTNIA.smt2                                                |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_40_QF_UFLIA.smt2                                                  |   0.260s  |   0.260s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_40_QF_UFNIA.smt2                                                  |  23.437s  |  23.437s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_41_QF_UFDTLIA.smt2                                                |   4.942s  |   4.942s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_41_QF_UFDTNIA.smt2                                                | 599.541s  | 599.541s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_41_QF_UFLIA.smt2                                                  |  26.376s  |  26.376s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_41_QF_UFNIA.smt2                                                  | 162.875s  | 162.875s  |   0.000s  | 0.0%|
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFDTLIA.smt2                                    |  20.439s  |  20.439s  |   0.000s  | 0.0%|
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFDTNIA.smt2                                    |  39.293s  |  39.293s  |   0.000s  | 0.0%|
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFLIA.smt2                                      | 599.108s  | 599.108s  |   0.000s  | 0.0%|
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFNIA.smt2                                      | 599.314s  | 599.314s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_55_QF_UFDTLIA.smt2                                               |  72.332s  |  72.332s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_55_QF_UFDTNIA.smt2                                               | 598.922s  | 598.922s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_55_QF_UFLIA.smt2                                                 | 599.516s  | 599.516s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_55_QF_UFNIA.smt2                                                 | 598.986s  | 598.986s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_56_QF_UFDTLIA.smt2                                               |  90.695s  |  90.695s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_56_QF_UFDTNIA.smt2                                               |  24.626s  |  24.626s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_56_QF_UFLIA.smt2                                                 | 599.592s  | 599.592s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_56_QF_UFNIA.smt2                                                 |  63.529s  |  63.529s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_57_QF_UFDTLIA.smt2                                               | 599.413s  | 599.413s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_57_QF_UFDTNIA.smt2                                               | 598.930s  | 598.930s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_57_QF_UFLIA.smt2                                                 | 599.418s  | 599.418s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_57_QF_UFNIA.smt2                                                 | 599.572s  | 599.572s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_58_QF_UFDTLIA.smt2                                               |   0.556s  |   0.556s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_58_QF_UFDTNIA.smt2                                               |   0.425s  |   0.425s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_58_QF_UFLIA.smt2                                                 |   1.897s  |   1.897s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_58_QF_UFNIA.smt2                                                 |   2.037s  |   2.037s  |   0.000s  | 0.0%|
|38347_525a1ca0331f2bcbf520_54_QF_UFDTLIA.smt2                                               | 599.387s  | 599.387s  |   0.000s  | 0.0%|
|38347_525a1ca0331f2bcbf520_54_QF_UFDTNIA.smt2                                               | 599.563s  | 599.563s  |   0.000s  | 0.0%|
|38347_525a1ca0331f2bcbf520_54_QF_UFLIA.smt2                                                 | 598.774s  | 598.774s  |   0.000s  | 0.0%|
|38347_525a1ca0331f2bcbf520_54_QF_UFNIA.smt2                                                 | 599.540s  | 599.540s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_44_QF_UFDTLIA.smt2                                               |   3.005s  |   3.005s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_44_QF_UFDTNIA.smt2                                               |  16.338s  |  16.338s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_44_QF_UFLIA.smt2                                                 |  15.358s  |  15.358s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_44_QF_UFNIA.smt2                                                 | 596.535s  | 596.535s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_45_QF_UFDTLIA.smt2                                               |   3.015s  |   3.015s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_45_QF_UFDTNIA.smt2                                               |  22.060s  |  22.060s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_45_QF_UFLIA.smt2                                                 |  12.440s  |  12.440s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_45_QF_UFNIA.smt2                                                 | 599.154s  | 599.154s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_46_QF_UFDTLIA.smt2                                               |   3.698s  |   3.698s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_46_QF_UFDTNIA.smt2                                               |  16.031s  |  16.031s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_46_QF_UFLIA.smt2                                                 |  24.009s  |  24.009s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_46_QF_UFNIA.smt2                                                 | 599.569s  | 599.569s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_47_QF_UFDTLIA.smt2                                               |  28.963s  |  28.963s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_47_QF_UFDTNIA.smt2                                               |   0.324s  |   0.324s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_47_QF_UFLIA.smt2                                                 | 186.454s  | 186.454s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_47_QF_UFNIA.smt2                                                 |   4.825s  |   4.825s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_48_QF_UFDTLIA.smt2                                               |   2.109s  |   2.109s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_48_QF_UFDTNIA.smt2                                               |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_48_QF_UFLIA.smt2                                                 |  40.036s  |  40.036s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_48_QF_UFNIA.smt2                                                 |  18.776s  |  18.776s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_61_QF_UFDTLIA.smt2                                               | 144.353s  | 144.353s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_61_QF_UFDTNIA.smt2                                               | 599.808s  | 599.808s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_61_QF_UFLIA.smt2                                                 | 598.677s  | 598.677s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_61_QF_UFNIA.smt2                                                 |   2.690s  |   2.690s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_62_QF_UFDTLIA.smt2                                               |  14.996s  |  14.996s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_62_QF_UFDTNIA.smt2                                               | 599.381s  | 599.381s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_62_QF_UFLIA.smt2                                                 |  15.206s  |  15.206s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_62_QF_UFNIA.smt2                                                 | 316.011s  | 316.011s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_63_QF_UFDTLIA.smt2                                               |   3.229s  |   3.229s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_63_QF_UFDTNIA.smt2                                               | 108.294s  | 108.294s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_63_QF_UFLIA.smt2                                                 |   5.640s  |   5.640s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_63_QF_UFNIA.smt2                                                 |  69.936s  |  69.936s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_59_QF_UFDTLIA.smt2                                               |   1.540s  |   1.540s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_59_QF_UFDTNIA.smt2                                               |   0.412s  |   0.412s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_59_QF_UFLIA.smt2                                                 | 164.316s  | 164.316s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_59_QF_UFNIA.smt2                                                 | 195.194s  | 195.194s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_60_QF_UFDTLIA.smt2                                               |   0.949s  |   0.949s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_60_QF_UFDTNIA.smt2                                               |   0.467s  |   0.467s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_60_QF_UFLIA.smt2                                                 |  17.599s  |  17.599s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_60_QF_UFNIA.smt2                                                 |   3.772s  |   3.772s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_14_QF_UFDTLIA.smt2                                               |   2.059s  |   2.059s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_14_QF_UFDTNIA.smt2                                               |   2.066s  |   2.066s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_14_QF_UFLIA.smt2                                                 |  44.966s  |  44.966s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_14_QF_UFNIA.smt2                                                 | 599.623s  | 599.623s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_15_QF_UFDTLIA.smt2                                               |  11.341s  |  11.341s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_15_QF_UFDTNIA.smt2                                               |   6.943s  |   6.943s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_15_QF_UFLIA.smt2                                                 | 518.528s  | 518.528s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_15_QF_UFNIA.smt2                                                 | 286.148s  | 286.148s  |   0.000s  | 0.0%|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFDTLIA.smt2                                   |  29.353s  |  29.353s  |   0.000s  | 0.0%|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFDTNIA.smt2                                   | 599.169s  | 599.169s  |   0.000s  | 0.0%|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFLIA.smt2                                     | 599.590s  | 599.590s  |   0.000s  | 0.0%|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFNIA.smt2                                     | 599.780s  | 599.780s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_17_QF_UFDTLIA.smt2                                               |   2.468s  |   2.468s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_17_QF_UFDTNIA.smt2                                               |   2.802s  |   2.802s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_17_QF_UFLIA.smt2                                                 |  19.991s  |  19.991s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_17_QF_UFNIA.smt2                                                 | 599.387s  | 599.387s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_18_QF_UFDTLIA.smt2                                               |   2.735s  |   2.735s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_18_QF_UFDTNIA.smt2                                               |   3.549s  |   3.549s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_18_QF_UFLIA.smt2                                                 |   9.843s  |   9.843s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_18_QF_UFNIA.smt2                                                 | 599.809s  | 599.809s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_34_QF_UFDTLIA.smt2                                               |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_34_QF_UFDTNIA.smt2                                               | 599.611s  | 599.611s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_34_QF_UFLIA.smt2                                                 |   0.246s  |   0.246s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_34_QF_UFNIA.smt2                                                 |  29.233s  |  29.233s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_35_QF_UFDTLIA.smt2                                               |   0.882s  |   0.882s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_35_QF_UFDTNIA.smt2                                               | 599.781s  | 599.781s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_35_QF_UFLIA.smt2                                                 |   1.229s  |   1.229s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_35_QF_UFNIA.smt2                                                 | 599.628s  | 599.628s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_36_QF_UFDTLIA.smt2                                               | 178.314s  | 178.314s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_36_QF_UFDTNIA.smt2                                               | 599.432s  | 599.432s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_36_QF_UFLIA.smt2                                                 |  43.640s  |  43.640s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_36_QF_UFNIA.smt2                                                 | 599.839s  | 599.839s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFDTLIA.smt2                                   |   0.532s  |   0.532s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFDTNIA.smt2                                   |   0.475s  |   0.475s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFLIA.smt2                                     |  38.541s  |  38.541s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFNIA.smt2                                     | 599.559s  | 599.559s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFDTLIA.smt2                                   |   0.719s  |   0.719s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFDTNIA.smt2                                   |   0.844s  |   0.844s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFLIA.smt2                                     |  37.322s  |  37.322s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFNIA.smt2                                     | 599.224s  | 599.224s  |   0.000s  | 0.0%|
|52759_b3ecd2335fd16ec2eee2_9_UFDTLIA.smt2                                                   |  39.734s  |  39.734s  |   0.000s  | 0.0%|
|52759_b3ecd2335fd16ec2eee2_9_UFDTNIA.smt2                                                   | 340.946s  | 340.946s  |   0.000s  | 0.0%|
|52759_b3ecd2335fd16ec2eee2_9_UFLIA.smt2                                                     |  68.316s  |  68.316s  |   0.000s  | 0.0%|
|52759_b3ecd2335fd16ec2eee2_9_UFNIA.smt2                                                     | 343.495s  | 343.495s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFDTLIA.smt2                                   |  67.187s  |  67.187s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFDTNIA.smt2                                   |  53.749s  |  53.749s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFLIA.smt2                                     | 600.002s  | 600.002s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFNIA.smt2                                     | 599.134s  | 599.134s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFDTLIA.smt2                                   |  23.382s  |  23.382s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFDTNIA.smt2                                   |   2.429s  |   2.429s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFLIA.smt2                                     | 599.768s  | 599.768s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFNIA.smt2                                     | 599.572s  | 599.572s  |   0.000s  | 0.0%|
|63058_55d6bef5390186355f11_26_QF_UFDTLIA.smt2                                               |   3.820s  |   3.820s  |   0.000s  | 0.0%|
|63058_55d6bef5390186355f11_26_QF_UFDTNIA.smt2                                               |   4.275s  |   4.275s  |   0.000s  | 0.0%|
|63058_55d6bef5390186355f11_26_QF_UFLIA.smt2                                                 | 599.438s  | 599.438s  |   0.000s  | 0.0%|
|63058_55d6bef5390186355f11_26_QF_UFNIA.smt2                                                 | 599.420s  | 599.420s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_22_QF_UFDTLIA.smt2                                               |   4.756s  |   4.756s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_22_QF_UFDTNIA.smt2                                               |   7.056s  |   7.056s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_22_QF_UFLIA.smt2                                                 | 599.050s  | 599.050s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_22_QF_UFNIA.smt2                                                 | 599.033s  | 599.033s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_23_QF_UFDTLIA.smt2                                               |   4.305s  |   4.305s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_23_QF_UFDTNIA.smt2                                               |   7.751s  |   7.751s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_23_QF_UFLIA.smt2                                                 | 599.381s  | 599.381s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_23_QF_UFNIA.smt2                                                 | 599.698s  | 599.698s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_24_QF_UFDTLIA.smt2                                               |  13.058s  |  13.058s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_24_QF_UFDTNIA.smt2                                               |   4.083s  |   4.083s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_24_QF_UFLIA.smt2                                                 | 599.662s  | 599.662s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_24_QF_UFNIA.smt2                                                 | 599.626s  | 599.626s  |   0.000s  | 0.0%|
|63058_aa742630eef64f949de269382c1f9035_25_UFDTLIA.smt2                                      |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|63058_aa742630eef64f949de269382c1f9035_25_UFDTNIA.smt2                                      |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|63058_aa742630eef64f949de269382c1f9035_25_UFLIA.smt2                                        |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|63058_aa742630eef64f949de269382c1f9035_25_UFNIA.smt2                                        |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_5_QF_UFDTLIA.smt2                                                | 599.066s  | 599.066s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_5_QF_UFDTNIA.smt2                                                | 599.630s  | 599.630s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_5_QF_UFLIA.smt2                                                  | 599.713s  | 599.713s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_6_QF_UFDTLIA.smt2                                                |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_6_QF_UFDTNIA.smt2                                                |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_6_QF_UFLIA.smt2                                                  |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_6_QF_UFNIA.smt2                                                  |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_7_QF_UFDTLIA.smt2                                                |   0.488s  |   0.488s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_7_QF_UFDTNIA.smt2                                                |   6.375s  |   6.375s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_7_QF_UFLIA.smt2                                                  |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_7_QF_UFNIA.smt2                                                  |   1.252s  |   1.252s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_8_QF_UFDTLIA.smt2                                                |   0.547s  |   0.547s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_8_QF_UFDTNIA.smt2                                                |   1.174s  |   1.174s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_8_QF_UFLIA.smt2                                                  |   0.592s  |   0.592s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_8_QF_UFNIA.smt2                                                  |   0.645s  |   0.645s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_72_QF_UFDTLIA.smt2                                               |   5.982s  |   5.982s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_72_QF_UFDTNIA.smt2                                               |   6.082s  |   6.082s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_72_QF_UFLIA.smt2                                                 |  22.566s  |  22.566s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                                                 | 351.568s  | 351.568s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_73_QF_UFDTLIA.smt2                                               | 599.556s  | 599.556s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_73_QF_UFDTNIA.smt2                                               |   6.628s  |   6.628s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_73_QF_UFLIA.smt2                                                 | 599.397s  | 599.397s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_73_QF_UFNIA.smt2                                                 | 598.610s  | 598.610s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_74_QF_UFDTLIA.smt2                                               |  19.410s  |  19.410s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_74_QF_UFDTNIA.smt2                                               | 599.607s  | 599.607s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_74_QF_UFLIA.smt2                                                 | 599.389s  | 599.389s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_74_QF_UFNIA.smt2                                                 | 599.445s  | 599.445s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_75_QF_UFDTLIA.smt2                                               |  20.509s  |  20.509s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_75_QF_UFDTNIA.smt2                                               |  22.389s  |  22.389s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_75_QF_UFLIA.smt2                                                 | 599.080s  | 599.080s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_75_QF_UFNIA.smt2                                                 | 598.774s  | 598.774s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_76_QF_UFDTLIA.smt2                                               |  28.542s  |  28.542s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_76_QF_UFDTNIA.smt2                                               |  64.632s  |  64.632s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_76_QF_UFLIA.smt2                                                 |  88.426s  |  88.426s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_76_QF_UFNIA.smt2                                                 | 599.871s  | 599.871s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_70_QF_UFDTLIA.smt2                                               |   1.686s  |   1.686s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_70_QF_UFDTNIA.smt2                                               | 599.888s  | 599.888s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_70_QF_UFLIA.smt2                                                 |  12.902s  |  12.902s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_70_QF_UFNIA.smt2                                                 | 599.553s  | 599.553s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_71_QF_UFDTLIA.smt2                                               | 599.281s  | 599.281s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_71_QF_UFDTNIA.smt2                                               | 597.225s  | 597.225s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_71_QF_UFLIA.smt2                                                 | 599.457s  | 599.457s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_71_QF_UFNIA.smt2                                                 | 599.523s  | 599.523s  |   0.000s  | 0.0%|
|72771_f9d228efc97cf1458e38_64_QF_UFDTLIA.smt2                                               |   4.635s  |   4.635s  |   0.000s  | 0.0%|
|72771_f9d228efc97cf1458e38_64_QF_UFDTNIA.smt2                                               |   0.480s  |   0.480s  |   0.000s  | 0.0%|
|72771_f9d228efc97cf1458e38_64_QF_UFLIA.smt2                                                 |  55.479s  |  55.479s  |   0.000s  | 0.0%|
|72771_f9d228efc97cf1458e38_64_QF_UFNIA.smt2                                                 |  10.099s  |  10.099s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_0_UFDTLIA.smt2                                                   |  12.289s  |  12.289s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_0_UFDTNIA.smt2                                                   |   1.577s  |   1.577s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_0_UFLIA.smt2                                                     | 599.836s  | 599.836s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_0_UFNIA.smt2                                                     |   0.604s  |   0.604s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_1_UFDTLIA.smt2                                                   | 599.631s  | 599.631s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_1_UFDTNIA.smt2                                                   |  20.766s  |  20.766s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_1_UFLIA.smt2                                                     | 599.171s  | 599.171s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_1_UFNIA.smt2                                                     |  12.233s  |  12.233s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_2_UFDTLIA.smt2                                                   | 599.595s  | 599.595s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_2_UFDTNIA.smt2                                                   |  34.372s  |  34.372s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_2_UFLIA.smt2                                                     | 599.158s  | 599.158s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_2_UFNIA.smt2                                                     | 599.613s  | 599.613s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_3_UFDTLIA.smt2                                                   | 355.424s  | 355.424s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_3_UFDTNIA.smt2                                                   | 242.429s  | 242.429s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_3_UFLIA.smt2                                                     | 598.122s  | 598.122s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_3_UFNIA.smt2                                                     | 599.209s  | 599.209s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_4_UFDTLIA.smt2                                                   | 599.548s  | 599.548s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_4_UFDTNIA.smt2                                                   | 599.051s  | 599.051s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_4_UFLIA.smt2                                                     | 599.633s  | 599.633s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_4_UFNIA.smt2                                                     | 599.789s  | 599.789s  |   0.000s  | 0.0%|
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFDTLIA.smt2                                   | 160.499s  | 160.499s  |   0.000s  | 0.0%|
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFDTNIA.smt2                                   |  75.263s  |  75.263s  |   0.000s  | 0.0%|
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFLIA.smt2                                     | 599.305s  | 599.305s  |   0.000s  | 0.0%|
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFNIA.smt2                                     | 599.817s  | 599.817s  |   0.000s  | 0.0%|
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFDTLIA.smt2                                   |  68.857s  |  68.857s  |   0.000s  | 0.0%|
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFDTNIA.smt2                                   |  10.070s  |  10.070s  |   0.000s  | 0.0%|
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFLIA.smt2                                     | 235.122s  | 235.122s  |   0.000s  | 0.0%|
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFNIA.smt2                                     |  40.319s  |  40.319s  |   0.000s  | 0.0%|
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFDTLIA.smt2                                   | 599.232s  | 599.232s  |   0.000s  | 0.0%|
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFDTNIA.smt2                                   | 595.546s  | 595.546s  |   0.000s  | 0.0%|
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFLIA.smt2                                     | 599.546s  | 599.546s  |   0.000s  | 0.0%|
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFNIA.smt2                                     | 599.455s  | 599.455s  |   0.000s  | 0.0%|
|93493_5990a6bf5f2740164f77_50_QF_UFDTLIA.smt2                                               | 358.723s  | 358.723s  |   0.000s  | 0.0%|
|93493_5990a6bf5f2740164f77_50_QF_UFDTNIA.smt2                                               | 599.659s  | 599.659s  |   0.000s  | 0.0%|
|93493_5990a6bf5f2740164f77_50_QF_UFLIA.smt2                                                 | 599.224s  | 599.224s  |   0.000s  | 0.0%|
|93493_5990a6bf5f2740164f77_50_QF_UFNIA.smt2                                                 | 599.169s  | 599.169s  |   0.000s  | 0.0%|
|93493_798593962ee29ad45ac8_52_QF_UFDTLIA.smt2                                               | 599.016s  | 599.016s  |   0.000s  | 0.0%|
|93493_798593962ee29ad45ac8_52_QF_UFDTNIA.smt2                                               | 599.721s  | 599.721s  |   0.000s  | 0.0%|
|93493_798593962ee29ad45ac8_52_QF_UFLIA.smt2                                                 | 599.640s  | 599.640s  |   0.000s  | 0.0%|
|93493_798593962ee29ad45ac8_52_QF_UFNIA.smt2                                                 | 598.972s  | 598.972s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_29_QF_UFDTLIA.smt2                                                 | 599.403s  | 599.403s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_29_QF_UFDTNIA.smt2                                                 | 599.609s  | 599.609s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_29_QF_UFLIA.smt2                                                   | 599.373s  | 599.373s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_29_QF_UFNIA.smt2                                                   | 599.267s  | 599.267s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_30_QF_UFDTLIA.smt2                                                 | 599.515s  | 599.515s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_30_QF_UFDTNIA.smt2                                                 | 599.260s  | 599.260s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_30_QF_UFLIA.smt2                                                   | 599.554s  | 599.554s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_30_QF_UFNIA.smt2                                                   | 427.389s  | 427.389s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_31_QF_UFDTLIA.smt2                                                 |  40.170s  |  40.170s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_31_QF_UFDTNIA.smt2                                                 | 599.720s  | 599.720s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_31_QF_UFLIA.smt2                                                   | 599.099s  | 599.099s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_31_QF_UFNIA.smt2                                                   |   5.698s  |   5.698s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_32_QF_UFDTLIA.smt2                                                 | 599.039s  | 599.039s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_32_QF_UFDTNIA.smt2                                                 | 599.880s  | 599.880s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_32_QF_UFLIA.smt2                                                   | 599.597s  | 599.597s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_32_QF_UFNIA.smt2                                                   | 153.891s  | 153.891s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_33_QF_UFDTLIA.smt2                                                 | 598.889s  | 598.889s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_33_QF_UFDTNIA.smt2                                                 | 599.461s  | 599.461s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_33_QF_UFLIA.smt2                                                   | 599.578s  | 599.578s  |   0.000s  | 0.0%|
</details>
