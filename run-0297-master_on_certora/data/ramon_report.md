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
Job description: masterd on certora
Job tag: master_on_certora
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 8d81a2dcaf4de007ce587f396f1b48fbc29646dd
Z3 branch: 
Z3 options: "-T:600 -st smt.arith.lp.dio_eqs=false"
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
Job description: masterd on certora
Job tag: master_on_certora
Runner: lev-ripper
Z3 repo: Z3Prover/z3
Z3 commit: 8d81a2dcaf4de007ce587f396f1b48fbc29646dd
Z3 branch: 
Z3 options: "-T:600 -st smt.arith.lp.dio_eqs=false"
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
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |   1.319s  |   1.319s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |   0.988s  |   0.988s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |   1.974s  |   1.974s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   1.617s  |   1.617s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |   1.040s  |   1.040s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |   1.660s  |   1.660s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |   1.167s  |   1.167s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   0.943s  |   0.943s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |  18.494s  |  18.494s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |   2.227s  |   2.227s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 | 599.161s  | 599.161s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   3.851s  |   3.851s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               | 599.692s  | 599.692s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |  75.830s  |  75.830s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 | 599.674s  | 599.674s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  14.297s  |  14.297s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |   7.419s  |   7.419s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |  32.976s  |  32.976s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |   9.288s  |   9.288s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |   7.559s  |   7.559s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |   1.319s  |   1.319s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |   0.988s  |   0.988s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |   1.974s  |   1.974s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   1.617s  |   1.617s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |   1.040s  |   1.040s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |   1.660s  |   1.660s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |   1.167s  |   1.167s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   0.943s  |   0.943s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |  18.494s  |  18.494s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |   2.227s  |   2.227s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 | 599.161s  | 599.161s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   3.851s  |   3.851s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               | 599.692s  | 599.692s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |  75.830s  |  75.830s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 | 599.674s  | 599.674s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  14.297s  |  14.297s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |   7.419s  |   7.419s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |  32.976s  |  32.976s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |   9.288s  |   9.288s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |   7.559s  |   7.559s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |   1.319s  |   1.319s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |   0.988s  |   0.988s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |   1.974s  |   1.974s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   1.617s  |   1.617s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |   1.040s  |   1.040s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |   1.660s  |   1.660s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |   1.167s  |   1.167s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   0.943s  |   0.943s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |  18.494s  |  18.494s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |   2.227s  |   2.227s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 | 599.161s  | 599.161s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   3.851s  |   3.851s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               | 599.692s  | 599.692s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |  75.830s  |  75.830s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 | 599.674s  | 599.674s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  14.297s  |  14.297s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |   7.419s  |   7.419s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |  32.976s  |  32.976s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |   9.288s  |   9.288s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |   7.559s  |   7.559s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |   1.319s  |   1.319s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |   0.988s  |   0.988s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |   1.974s  |   1.974s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   1.617s  |   1.617s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |   1.040s  |   1.040s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |   1.660s  |   1.660s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |   1.167s  |   1.167s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   0.943s  |   0.943s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |  18.494s  |  18.494s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |   2.227s  |   2.227s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 | 599.161s  | 599.161s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   3.851s  |   3.851s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               | 599.692s  | 599.692s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |  75.830s  |  75.830s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 | 599.674s  | 599.674s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  14.297s  |  14.297s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |   7.419s  |   7.419s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |  32.976s  |  32.976s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |   9.288s  |   9.288s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |   7.559s  |   7.559s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFLIA.smt2                                    | 599.903s |441.0MiB|
|66603_accdadf23a1cf70ae043_73_QF_UFLIA.smt2                                                | 599.874s |792.0MiB|
|38347_092cc73601c78e45f4f9_57_QF_UFDTLIA.smt2                                              | 599.872s |33.16MiB|
|72658_63104dadde9c6026353f_71_QF_UFDTLIA.smt2                                              | 599.851s |404.0MiB|
|66603_accdadf23a1cf70ae043_73_QF_UFNIA.smt2                                                | 599.849s |786.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTLIA.smt2                                  | 599.831s |1217.0MiB|
|38347_525a1ca0331f2bcbf520_54_QF_UFLIA.smt2                                                | 599.823s |2235.0MiB|
|66603_accdadf23a1cf70ae043_74_QF_UFLIA.smt2                                                | 599.816s |580.0MiB|
|72658_63104dadde9c6026353f_71_QF_UFNIA.smt2                                                | 599.815s |48.34MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTNIA.smt2                                  | 599.810s |114.0MiB|
|65782_cd31513fdcd15701933b_5_QF_UFNIA.smt2                                                 | 599.809s |98.86MiB|
|83314_a702bf8b823398c9e37a_1_UFDTLIA.smt2                                                  | 599.807s |701.0MiB|
|66603_accdadf23a1cf70ae043_75_QF_UFNIA.smt2                                                | 599.803s |632.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFNIA.smt2                                    | 599.797s |99.384MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTLIA.smt2                                  | 599.789s |1420.0MiB|
|940_590f27b1c3c800d3243e_32_QF_UFDTLIA.smt2                                                | 599.786s |621.0MiB|
|940_590f27b1c3c800d3243e_29_QF_UFLIA.smt2                                                  | 599.784s |552.0MiB|
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFLIA.smt2                                    | 599.778s |269.0MiB|
|44788_1965f0d6d94d5d8054ba_35_QF_UFNIA.smt2                                                | 599.776s |76.696MiB|
|38347_525a1ca0331f2bcbf520_54_QF_UFNIA.smt2                                                | 599.770s |357.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFLIA.smt2                                    | 599.903s |441.0MiB|
|66603_accdadf23a1cf70ae043_73_QF_UFLIA.smt2                                                | 599.874s |792.0MiB|
|38347_092cc73601c78e45f4f9_57_QF_UFDTLIA.smt2                                              | 599.872s |33.16MiB|
|72658_63104dadde9c6026353f_71_QF_UFDTLIA.smt2                                              | 599.851s |404.0MiB|
|66603_accdadf23a1cf70ae043_73_QF_UFNIA.smt2                                                | 599.849s |786.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTLIA.smt2                                  | 599.831s |1217.0MiB|
|38347_525a1ca0331f2bcbf520_54_QF_UFLIA.smt2                                                | 599.823s |2235.0MiB|
|66603_accdadf23a1cf70ae043_74_QF_UFLIA.smt2                                                | 599.816s |580.0MiB|
|72658_63104dadde9c6026353f_71_QF_UFNIA.smt2                                                | 599.815s |48.34MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTNIA.smt2                                  | 599.810s |114.0MiB|
|65782_cd31513fdcd15701933b_5_QF_UFNIA.smt2                                                 | 599.809s |98.86MiB|
|83314_a702bf8b823398c9e37a_1_UFDTLIA.smt2                                                  | 599.807s |701.0MiB|
|66603_accdadf23a1cf70ae043_75_QF_UFNIA.smt2                                                | 599.803s |632.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFNIA.smt2                                    | 599.797s |99.384MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTLIA.smt2                                  | 599.789s |1420.0MiB|
|940_590f27b1c3c800d3243e_32_QF_UFDTLIA.smt2                                                | 599.786s |621.0MiB|
|940_590f27b1c3c800d3243e_29_QF_UFLIA.smt2                                                  | 599.784s |552.0MiB|
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFLIA.smt2                                    | 599.778s |269.0MiB|
|44788_1965f0d6d94d5d8054ba_35_QF_UFNIA.smt2                                                | 599.776s |76.696MiB|
|38347_525a1ca0331f2bcbf520_54_QF_UFNIA.smt2                                                | 599.770s |357.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |36.044MiB|36.044MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |28.468MiB|28.468MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |39.684MiB|39.684MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |30.788MiB|30.788MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |34.284MiB|34.284MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |27.372MiB|27.372MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |33.956MiB|33.956MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |27.016MiB|27.016MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |63.816MiB|63.816MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |23.316MiB|23.316MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 |182.0MiB|182.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |23.396MiB|23.396MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               |706.0MiB|706.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |37.28MiB|37.28MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 |621.0MiB|621.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |32.288MiB|32.288MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |66.3MiB|66.3MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |36.62MiB|36.62MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |72.588MiB|72.588MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |31.728MiB|31.728MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |36.044MiB|36.044MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |28.468MiB|28.468MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |39.684MiB|39.684MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |30.788MiB|30.788MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |34.284MiB|34.284MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |27.372MiB|27.372MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |33.956MiB|33.956MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |27.016MiB|27.016MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |63.816MiB|63.816MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |23.316MiB|23.316MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 |182.0MiB|182.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |23.396MiB|23.396MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               |706.0MiB|706.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |37.28MiB|37.28MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 |621.0MiB|621.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |32.288MiB|32.288MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |66.3MiB|66.3MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |36.62MiB|36.62MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |72.588MiB|72.588MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |31.728MiB|31.728MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |36.044MiB|36.044MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |28.468MiB|28.468MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |39.684MiB|39.684MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |30.788MiB|30.788MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |34.284MiB|34.284MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |27.372MiB|27.372MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |33.956MiB|33.956MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |27.016MiB|27.016MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |63.816MiB|63.816MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |23.316MiB|23.316MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 |182.0MiB|182.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |23.396MiB|23.396MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               |706.0MiB|706.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |37.28MiB|37.28MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 |621.0MiB|621.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |32.288MiB|32.288MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |66.3MiB|66.3MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |36.62MiB|36.62MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |72.588MiB|72.588MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |31.728MiB|31.728MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |36.044MiB|36.044MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |28.468MiB|28.468MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |39.684MiB|39.684MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |30.788MiB|30.788MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |34.284MiB|34.284MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |27.372MiB|27.372MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |33.956MiB|33.956MiB|0B| 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |27.016MiB|27.016MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |63.816MiB|63.816MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |23.316MiB|23.316MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 |182.0MiB|182.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |23.396MiB|23.396MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               |706.0MiB|706.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |37.28MiB|37.28MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 |621.0MiB|621.0MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |32.288MiB|32.288MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |66.3MiB|66.3MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |36.62MiB|36.62MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |72.588MiB|72.588MiB|0B| 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |31.728MiB|31.728MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|38347_525a1ca0331f2bcbf520_54_QF_UFLIA.smt2                                                | 599.823s |2235.0MiB|
|38347_525a1ca0331f2bcbf520_54_QF_UFDTLIA.smt2                                              | 599.697s |2127.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFLIA.smt2                                    | 599.733s |2059.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTLIA.smt2                                  | 599.520s |1931.0MiB|
|66603_accdadf23a1cf70ae043_76_QF_UFLIA.smt2                                                | 194.593s |1714.0MiB|
|66603_accdadf23a1cf70ae043_76_QF_UFNIA.smt2                                                | 599.757s |1545.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTLIA.smt2                                  | 599.789s |1420.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFLIA.smt2                                    | 599.494s |1345.0MiB|
|66603_accdadf23a1cf70ae043_75_QF_UFLIA.smt2                                                | 599.727s |1241.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTLIA.smt2                                  | 599.831s |1217.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFLIA.smt2                                    | 599.448s |1150.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFLIA.smt2                                    | 599.653s |970.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTLIA.smt2                                  | 599.745s |969.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 | 599.616s |958.0MiB|
|83314_a702bf8b823398c9e37a_3_UFDTLIA.smt2                                                  | 511.111s |851.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFLIA.smt2                                    | 599.531s |850.0MiB|
|66603_accdadf23a1cf70ae043_73_QF_UFLIA.smt2                                                | 599.874s |792.0MiB|
|83314_a702bf8b823398c9e37a_4_UFDTLIA.smt2                                                  | 598.545s |787.0MiB|
|66603_accdadf23a1cf70ae043_73_QF_UFNIA.smt2                                                | 599.849s |786.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTLIA.smt2                                  | 599.649s |746.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|38347_525a1ca0331f2bcbf520_54_QF_UFLIA.smt2                                                | 599.823s |2235.0MiB|
|38347_525a1ca0331f2bcbf520_54_QF_UFDTLIA.smt2                                              | 599.697s |2127.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFLIA.smt2                                    | 599.733s |2059.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTLIA.smt2                                  | 599.520s |1931.0MiB|
|66603_accdadf23a1cf70ae043_76_QF_UFLIA.smt2                                                | 194.593s |1714.0MiB|
|66603_accdadf23a1cf70ae043_76_QF_UFNIA.smt2                                                | 599.757s |1545.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTLIA.smt2                                  | 599.789s |1420.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFLIA.smt2                                    | 599.494s |1345.0MiB|
|66603_accdadf23a1cf70ae043_75_QF_UFLIA.smt2                                                | 599.727s |1241.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTLIA.smt2                                  | 599.831s |1217.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFLIA.smt2                                    | 599.448s |1150.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFLIA.smt2                                    | 599.653s |970.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTLIA.smt2                                  | 599.745s |969.0MiB|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                 | 599.616s |958.0MiB|
|83314_a702bf8b823398c9e37a_3_UFDTLIA.smt2                                                  | 511.111s |851.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFLIA.smt2                                    | 599.531s |850.0MiB|
|66603_accdadf23a1cf70ae043_73_QF_UFLIA.smt2                                                | 599.874s |792.0MiB|
|83314_a702bf8b823398c9e37a_4_UFDTLIA.smt2                                                  | 598.545s |787.0MiB|
|66603_accdadf23a1cf70ae043_73_QF_UFNIA.smt2                                                | 599.849s |786.0MiB|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTLIA.smt2                                  | 599.649s |746.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|11775_ad46e5b8db4748c51973_42_QF_UFDTLIA.smt2                                               |   1.319s  |   1.319s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFDTNIA.smt2                                               |   0.988s  |   0.988s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFLIA.smt2                                                 |   1.974s  |   1.974s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_42_QF_UFNIA.smt2                                                 |   1.617s  |   1.617s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTLIA.smt2                                               |   1.040s  |   1.040s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFDTNIA.smt2                                               |   1.660s  |   1.660s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFLIA.smt2                                                 |   1.167s  |   1.167s  |   0.000s  | 0.0%|
|11775_ad46e5b8db4748c51973_43_QF_UFNIA.smt2                                                 |   0.943s  |   0.943s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTLIA.smt2                                               |  18.494s  |  18.494s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFDTNIA.smt2                                               |   2.227s  |   2.227s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFLIA.smt2                                                 | 599.161s  | 599.161s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_19_QF_UFNIA.smt2                                                 |   3.851s  |   3.851s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTLIA.smt2                                               | 599.692s  | 599.692s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFDTNIA.smt2                                               |  75.830s  |  75.830s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFLIA.smt2                                                 | 599.674s  | 599.674s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_20_QF_UFNIA.smt2                                                 |  14.297s  |  14.297s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTLIA.smt2                                               |   7.419s  |   7.419s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFDTNIA.smt2                                               |  32.976s  |  32.976s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFLIA.smt2                                                 |   9.288s  |   9.288s  |   0.000s  | 0.0%|
|17512_5c1021b0faa6b6e1791b_21_QF_UFNIA.smt2                                                 |   7.559s  |   7.559s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTLIA.smt2                                   | 599.789s  | 599.789s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFDTNIA.smt2                                   | 599.426s  | 599.426s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFLIA.smt2                                     | 599.494s  | 599.494s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_65_QF_UFNIA.smt2                                     | 599.547s  | 599.547s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTLIA.smt2                                   | 599.831s  | 599.831s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFDTNIA.smt2                                   |  49.286s  |  49.286s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFLIA.smt2                                     | 599.448s  | 599.448s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_66_QF_UFNIA.smt2                                     | 599.726s  | 599.726s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTLIA.smt2                                   | 599.520s  | 599.520s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFDTNIA.smt2                                   | 599.810s  | 599.810s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFLIA.smt2                                     | 599.733s  | 599.733s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_67_QF_UFNIA.smt2                                     | 599.345s  | 599.345s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTLIA.smt2                                   | 599.745s  | 599.745s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFDTNIA.smt2                                   |  31.805s  |  31.805s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFLIA.smt2                                     | 599.531s  | 599.531s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_68_QF_UFNIA.smt2                                     | 599.797s  | 599.797s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTLIA.smt2                                   | 599.649s  | 599.649s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFDTNIA.smt2                                   |   4.654s  |   4.654s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFLIA.smt2                                     | 599.653s  | 599.653s  |   0.000s  | 0.0%|
|25959_5dee2e2f6ef44465a2bea4b085818948_69_QF_UFNIA.smt2                                     |   5.406s  |   5.406s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_27_QF_UFDTLIA.smt2                                               |  37.894s  |  37.894s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_27_QF_UFDTNIA.smt2                                               |  43.087s  |  43.087s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_27_QF_UFLIA.smt2                                                 | 245.688s  | 245.688s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_27_QF_UFNIA.smt2                                                 | 138.542s  | 138.542s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_28_QF_UFDTLIA.smt2                                               |  86.063s  |  86.063s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_28_QF_UFDTNIA.smt2                                               | 106.333s  | 106.333s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_28_QF_UFLIA.smt2                                                 | 207.360s  | 207.360s  |   0.000s  | 0.0%|
|30078_f817a923328f75af7e60_28_QF_UFNIA.smt2                                                 | 243.476s  | 243.476s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_38_QF_UFDTLIA.smt2                                                | 599.512s  | 599.512s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_38_QF_UFDTNIA.smt2                                                | 599.629s  | 599.629s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_38_QF_UFLIA.smt2                                                  | 599.559s  | 599.559s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_38_QF_UFNIA.smt2                                                  | 599.616s  | 599.616s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_39_QF_UFDTLIA.smt2                                                |  20.406s  |  20.406s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_39_QF_UFDTNIA.smt2                                                | 424.924s  | 424.924s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_39_QF_UFLIA.smt2                                                  | 135.274s  | 135.274s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_39_QF_UFNIA.smt2                                                  | 153.397s  | 153.397s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_40_QF_UFDTLIA.smt2                                                |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_40_QF_UFDTNIA.smt2                                                |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_40_QF_UFLIA.smt2                                                  |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_40_QF_UFNIA.smt2                                                  |   0.350s  |   0.350s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_41_QF_UFDTLIA.smt2                                                |   3.512s  |   3.512s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_41_QF_UFDTNIA.smt2                                                |   4.298s  |   4.298s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_41_QF_UFLIA.smt2                                                  |  12.298s  |  12.298s  |   0.000s  | 0.0%|
|3106_1c933134166dbad31f79_41_QF_UFNIA.smt2                                                  |  21.333s  |  21.333s  |   0.000s  | 0.0%|
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFDTLIA.smt2                                    |  35.063s  |  35.063s  |   0.000s  | 0.0%|
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFDTNIA.smt2                                    | 127.319s  | 127.319s  |   0.000s  | 0.0%|
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFLIA.smt2                                      | 599.502s  | 599.502s  |   0.000s  | 0.0%|
|3106_afb7bc55417e43d7a22790c3576f04fc_37_QF_UFNIA.smt2                                      | 121.671s  | 121.671s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_55_QF_UFDTLIA.smt2                                               | 221.407s  | 221.407s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_55_QF_UFDTNIA.smt2                                               | 599.326s  | 599.326s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_55_QF_UFLIA.smt2                                                 | 599.370s  | 599.370s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_55_QF_UFNIA.smt2                                                 | 599.576s  | 599.576s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_56_QF_UFDTLIA.smt2                                               | 599.623s  | 599.623s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_56_QF_UFDTNIA.smt2                                               |   4.362s  |   4.362s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_56_QF_UFLIA.smt2                                                 | 599.586s  | 599.586s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_56_QF_UFNIA.smt2                                                 |  24.090s  |  24.090s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_57_QF_UFDTLIA.smt2                                               | 599.872s  | 599.872s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_57_QF_UFDTNIA.smt2                                               | 599.450s  | 599.450s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_57_QF_UFLIA.smt2                                                 | 599.636s  | 599.636s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_57_QF_UFNIA.smt2                                                 | 599.648s  | 599.648s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_58_QF_UFDTLIA.smt2                                               |   1.835s  |   1.835s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_58_QF_UFDTNIA.smt2                                               |   1.528s  |   1.528s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_58_QF_UFLIA.smt2                                                 |   2.479s  |   2.479s  |   0.000s  | 0.0%|
|38347_092cc73601c78e45f4f9_58_QF_UFNIA.smt2                                                 |   2.696s  |   2.696s  |   0.000s  | 0.0%|
|38347_525a1ca0331f2bcbf520_54_QF_UFDTLIA.smt2                                               | 599.697s  | 599.697s  |   0.000s  | 0.0%|
|38347_525a1ca0331f2bcbf520_54_QF_UFDTNIA.smt2                                               | 597.614s  | 597.614s  |   0.000s  | 0.0%|
|38347_525a1ca0331f2bcbf520_54_QF_UFLIA.smt2                                                 | 599.823s  | 599.823s  |   0.000s  | 0.0%|
|38347_525a1ca0331f2bcbf520_54_QF_UFNIA.smt2                                                 | 599.770s  | 599.770s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_44_QF_UFDTLIA.smt2                                               |   4.312s  |   4.312s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_44_QF_UFDTNIA.smt2                                               |  13.364s  |  13.364s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_44_QF_UFLIA.smt2                                                 |  15.088s  |  15.088s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_44_QF_UFNIA.smt2                                                 | 274.395s  | 274.395s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_45_QF_UFDTLIA.smt2                                               |   3.906s  |   3.906s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_45_QF_UFDTNIA.smt2                                               |  32.470s  |  32.470s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_45_QF_UFLIA.smt2                                                 |   8.891s  |   8.891s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_45_QF_UFNIA.smt2                                                 | 292.750s  | 292.750s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_46_QF_UFDTLIA.smt2                                               |   2.677s  |   2.677s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_46_QF_UFDTNIA.smt2                                               |  22.093s  |  22.093s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_46_QF_UFLIA.smt2                                                 |  28.292s  |  28.292s  |   0.000s  | 0.0%|
|39657_1c7158801cd59dc13f05_46_QF_UFNIA.smt2                                                 | 222.877s  | 222.877s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_47_QF_UFDTLIA.smt2                                               |   5.551s  |   5.551s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_47_QF_UFDTNIA.smt2                                               |   1.363s  |   1.363s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_47_QF_UFLIA.smt2                                                 |  68.890s  |  68.890s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_47_QF_UFNIA.smt2                                                 |  56.347s  |  56.347s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_48_QF_UFDTLIA.smt2                                               |   3.261s  |   3.261s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_48_QF_UFDTNIA.smt2                                               |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_48_QF_UFLIA.smt2                                                 |  11.207s  |  11.207s  |   0.000s  | 0.0%|
|39657_2866defdd1f2434b69ab_48_QF_UFNIA.smt2                                                 |  15.034s  |  15.034s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_61_QF_UFDTLIA.smt2                                               | 206.832s  | 206.832s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_61_QF_UFDTNIA.smt2                                               | 599.535s  | 599.535s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_61_QF_UFLIA.smt2                                                 | 596.785s  | 596.785s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_61_QF_UFNIA.smt2                                                 |   2.048s  |   2.048s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_62_QF_UFDTLIA.smt2                                               |  25.373s  |  25.373s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_62_QF_UFDTNIA.smt2                                               | 599.540s  | 599.540s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_62_QF_UFLIA.smt2                                                 |  30.986s  |  30.986s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_62_QF_UFNIA.smt2                                                 | 599.619s  | 599.619s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_63_QF_UFDTLIA.smt2                                               |   3.396s  |   3.396s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_63_QF_UFDTNIA.smt2                                               | 208.596s  | 208.596s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_63_QF_UFLIA.smt2                                                 |   6.616s  |   6.616s  |   0.000s  | 0.0%|
|41958_32933c5a1384696720a2_63_QF_UFNIA.smt2                                                 | 599.408s  | 599.408s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_59_QF_UFDTLIA.smt2                                               |   1.424s  |   1.424s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_59_QF_UFDTNIA.smt2                                               |   0.500s  |   0.500s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_59_QF_UFLIA.smt2                                                 |  17.757s  |  17.757s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_59_QF_UFNIA.smt2                                                 |   6.663s  |   6.663s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_60_QF_UFDTLIA.smt2                                               |   1.031s  |   1.031s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_60_QF_UFDTNIA.smt2                                               |   0.455s  |   0.455s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_60_QF_UFLIA.smt2                                                 |   4.324s  |   4.324s  |   0.000s  | 0.0%|
|41958_45c688a4814eb926c254_60_QF_UFNIA.smt2                                                 |   3.408s  |   3.408s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_14_QF_UFDTLIA.smt2                                               |   2.610s  |   2.610s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_14_QF_UFDTNIA.smt2                                               |   1.999s  |   1.999s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_14_QF_UFLIA.smt2                                                 |  27.267s  |  27.267s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_14_QF_UFNIA.smt2                                                 |  17.266s  |  17.266s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_15_QF_UFDTLIA.smt2                                               |   9.584s  |   9.584s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_15_QF_UFDTNIA.smt2                                               |   7.897s  |   7.897s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_15_QF_UFLIA.smt2                                                 | 599.477s  | 599.477s  |   0.000s  | 0.0%|
|44289_4066055e0f64d96da11a_15_QF_UFNIA.smt2                                                 | 358.834s  | 358.834s  |   0.000s  | 0.0%|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFDTLIA.smt2                                   |  11.505s  |  11.505s  |   0.000s  | 0.0%|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFDTNIA.smt2                                   | 176.724s  | 176.724s  |   0.000s  | 0.0%|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFLIA.smt2                                     | 599.151s  | 599.151s  |   0.000s  | 0.0%|
|44289_b077fc096b3d41cba49f8628caff7fa5_16_QF_UFNIA.smt2                                     |  93.932s  |  93.932s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_17_QF_UFDTLIA.smt2                                               |   2.896s  |   2.896s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_17_QF_UFDTNIA.smt2                                               |   8.321s  |   8.321s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_17_QF_UFLIA.smt2                                                 |  18.816s  |  18.816s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_17_QF_UFNIA.smt2                                                 |  42.058s  |  42.058s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_18_QF_UFDTLIA.smt2                                               |   2.678s  |   2.678s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_18_QF_UFDTNIA.smt2                                               |   3.594s  |   3.594s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_18_QF_UFLIA.smt2                                                 |  14.272s  |  14.272s  |   0.000s  | 0.0%|
|44289_e5a2e5c780236919ee6a_18_QF_UFNIA.smt2                                                 |  21.685s  |  21.685s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_34_QF_UFDTLIA.smt2                                               |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_34_QF_UFDTNIA.smt2                                               |  11.752s  |  11.752s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_34_QF_UFLIA.smt2                                                 |   0.340s  |   0.340s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_34_QF_UFNIA.smt2                                                 |  10.475s  |  10.475s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_35_QF_UFDTLIA.smt2                                               |   0.918s  |   0.918s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_35_QF_UFDTNIA.smt2                                               | 599.525s  | 599.525s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_35_QF_UFLIA.smt2                                                 |   2.190s  |   2.190s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_35_QF_UFNIA.smt2                                                 | 599.776s  | 599.776s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_36_QF_UFDTLIA.smt2                                               | 248.867s  | 248.867s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_36_QF_UFDTNIA.smt2                                               | 599.591s  | 599.591s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_36_QF_UFLIA.smt2                                                 |  63.265s  |  63.265s  |   0.000s  | 0.0%|
|44788_1965f0d6d94d5d8054ba_36_QF_UFNIA.smt2                                                 | 599.541s  | 599.541s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFDTLIA.smt2                                   |   0.564s  |   0.564s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFDTNIA.smt2                                   |   0.271s  |   0.271s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFLIA.smt2                                     |  43.548s  |  43.548s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_12_QF_UFNIA.smt2                                     |  50.173s  |  50.173s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFDTLIA.smt2                                   |   0.745s  |   0.745s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFDTNIA.smt2                                   |   0.662s  |   0.662s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFLIA.smt2                                     |  31.442s  |  31.442s  |   0.000s  | 0.0%|
|52759_af0c476fe3b544b9a8507f3e42472c43_13_QF_UFNIA.smt2                                     |  83.584s  |  83.584s  |   0.000s  | 0.0%|
|52759_b3ecd2335fd16ec2eee2_9_UFDTLIA.smt2                                                   |  54.072s  |  54.072s  |   0.000s  | 0.0%|
|52759_b3ecd2335fd16ec2eee2_9_UFDTNIA.smt2                                                   | 363.368s  | 363.368s  |   0.000s  | 0.0%|
|52759_b3ecd2335fd16ec2eee2_9_UFLIA.smt2                                                     |  99.047s  |  99.047s  |   0.000s  | 0.0%|
|52759_b3ecd2335fd16ec2eee2_9_UFNIA.smt2                                                     | 599.541s  | 599.541s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFDTLIA.smt2                                   | 119.557s  | 119.557s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFDTNIA.smt2                                   |  66.391s  |  66.391s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFLIA.smt2                                     | 599.903s  | 599.903s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_10_QF_UFNIA.smt2                                     | 599.528s  | 599.528s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFDTLIA.smt2                                   |  32.612s  |  32.612s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFDTNIA.smt2                                   |   2.337s  |   2.337s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFLIA.smt2                                     | 599.520s  | 599.520s  |   0.000s  | 0.0%|
|52759_bec3a2272267494faeecb6bfaf253e3b_11_QF_UFNIA.smt2                                     |  48.624s  |  48.624s  |   0.000s  | 0.0%|
|63058_55d6bef5390186355f11_26_QF_UFDTLIA.smt2                                               |   3.092s  |   3.092s  |   0.000s  | 0.0%|
|63058_55d6bef5390186355f11_26_QF_UFDTNIA.smt2                                               |  16.570s  |  16.570s  |   0.000s  | 0.0%|
|63058_55d6bef5390186355f11_26_QF_UFLIA.smt2                                                 | 172.432s  | 172.432s  |   0.000s  | 0.0%|
|63058_55d6bef5390186355f11_26_QF_UFNIA.smt2                                                 | 128.378s  | 128.378s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_22_QF_UFDTLIA.smt2                                               |   4.900s  |   4.900s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_22_QF_UFDTNIA.smt2                                               |   8.684s  |   8.684s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_22_QF_UFLIA.smt2                                                 |  65.827s  |  65.827s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_22_QF_UFNIA.smt2                                                 | 117.869s  | 117.869s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_23_QF_UFDTLIA.smt2                                               |   4.759s  |   4.759s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_23_QF_UFDTNIA.smt2                                               |   6.984s  |   6.984s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_23_QF_UFLIA.smt2                                                 |  45.295s  |  45.295s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_23_QF_UFNIA.smt2                                                 | 127.467s  | 127.467s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_24_QF_UFDTLIA.smt2                                               |  13.057s  |  13.057s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_24_QF_UFDTNIA.smt2                                               |   4.054s  |   4.054s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_24_QF_UFLIA.smt2                                                 |  80.652s  |  80.652s  |   0.000s  | 0.0%|
|63058_64ab9a7ef7b6c3492507_24_QF_UFNIA.smt2                                                 | 599.522s  | 599.522s  |   0.000s  | 0.0%|
|63058_aa742630eef64f949de269382c1f9035_25_UFDTLIA.smt2                                      |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|63058_aa742630eef64f949de269382c1f9035_25_UFDTNIA.smt2                                      |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|63058_aa742630eef64f949de269382c1f9035_25_UFLIA.smt2                                        |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|63058_aa742630eef64f949de269382c1f9035_25_UFNIA.smt2                                        |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_5_QF_UFDTLIA.smt2                                                | 599.688s  | 599.688s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_5_QF_UFDTNIA.smt2                                                | 599.623s  | 599.623s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_5_QF_UFLIA.smt2                                                  | 599.185s  | 599.185s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_5_QF_UFNIA.smt2                                                  | 599.809s  | 599.809s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_6_QF_UFDTLIA.smt2                                                |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_6_QF_UFDTNIA.smt2                                                |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_6_QF_UFLIA.smt2                                                  |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_6_QF_UFNIA.smt2                                                  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_7_QF_UFDTLIA.smt2                                                |   0.429s  |   0.429s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_7_QF_UFDTNIA.smt2                                                |   9.451s  |   9.451s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_7_QF_UFLIA.smt2                                                  |   0.441s  |   0.441s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_7_QF_UFNIA.smt2                                                  |   4.599s  |   4.599s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_8_QF_UFDTLIA.smt2                                                |   0.550s  |   0.550s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_8_QF_UFDTNIA.smt2                                                |   1.761s  |   1.761s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_8_QF_UFLIA.smt2                                                  |   0.645s  |   0.645s  |   0.000s  | 0.0%|
|65782_cd31513fdcd15701933b_8_QF_UFNIA.smt2                                                  |   0.882s  |   0.882s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_72_QF_UFDTLIA.smt2                                               |   5.622s  |   5.622s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_72_QF_UFDTNIA.smt2                                               |   5.961s  |   5.961s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_72_QF_UFLIA.smt2                                                 |  41.590s  |  41.590s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_72_QF_UFNIA.smt2                                                 | 534.201s  | 534.201s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_73_QF_UFDTLIA.smt2                                               | 599.333s  | 599.333s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_73_QF_UFDTNIA.smt2                                               |   6.360s  |   6.360s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_73_QF_UFLIA.smt2                                                 | 599.874s  | 599.874s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_73_QF_UFNIA.smt2                                                 | 599.849s  | 599.849s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_74_QF_UFDTLIA.smt2                                               |  34.461s  |  34.461s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_74_QF_UFDTNIA.smt2                                               | 599.729s  | 599.729s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_74_QF_UFLIA.smt2                                                 | 599.816s  | 599.816s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_74_QF_UFNIA.smt2                                                 | 599.438s  | 599.438s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_75_QF_UFDTLIA.smt2                                               |  20.584s  |  20.584s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_75_QF_UFDTNIA.smt2                                               |  41.606s  |  41.606s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_75_QF_UFLIA.smt2                                                 | 599.727s  | 599.727s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_75_QF_UFNIA.smt2                                                 | 599.803s  | 599.803s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_76_QF_UFDTLIA.smt2                                               |  26.362s  |  26.362s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_76_QF_UFDTNIA.smt2                                               |  15.846s  |  15.846s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_76_QF_UFLIA.smt2                                                 | 194.593s  | 194.593s  |   0.000s  | 0.0%|
|66603_accdadf23a1cf70ae043_76_QF_UFNIA.smt2                                                 | 599.757s  | 599.757s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_70_QF_UFDTLIA.smt2                                               |   1.805s  |   1.805s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_70_QF_UFDTNIA.smt2                                               |   4.107s  |   4.107s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_70_QF_UFLIA.smt2                                                 |  16.429s  |  16.429s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_70_QF_UFNIA.smt2                                                 |  12.932s  |  12.932s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_71_QF_UFDTLIA.smt2                                               | 599.851s  | 599.851s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_71_QF_UFDTNIA.smt2                                               | 599.286s  | 599.286s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_71_QF_UFLIA.smt2                                                 | 599.585s  | 599.585s  |   0.000s  | 0.0%|
|72658_63104dadde9c6026353f_71_QF_UFNIA.smt2                                                 | 599.815s  | 599.815s  |   0.000s  | 0.0%|
|72771_f9d228efc97cf1458e38_64_QF_UFDTLIA.smt2                                               |   6.143s  |   6.143s  |   0.000s  | 0.0%|
|72771_f9d228efc97cf1458e38_64_QF_UFDTNIA.smt2                                               |   0.586s  |   0.586s  |   0.000s  | 0.0%|
|72771_f9d228efc97cf1458e38_64_QF_UFLIA.smt2                                                 |  32.956s  |  32.956s  |   0.000s  | 0.0%|
|72771_f9d228efc97cf1458e38_64_QF_UFNIA.smt2                                                 |   1.280s  |   1.280s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_0_UFDTLIA.smt2                                                   |  13.010s  |  13.010s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_0_UFDTNIA.smt2                                                   |   1.373s  |   1.373s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_0_UFLIA.smt2                                                     | 285.960s  | 285.960s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_0_UFNIA.smt2                                                     |   0.596s  |   0.596s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_1_UFDTLIA.smt2                                                   | 599.807s  | 599.807s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_1_UFDTNIA.smt2                                                   |  35.674s  |  35.674s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_1_UFLIA.smt2                                                     | 599.500s  | 599.500s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_1_UFNIA.smt2                                                     |  13.503s  |  13.503s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_2_UFDTLIA.smt2                                                   | 599.576s  | 599.576s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_2_UFDTNIA.smt2                                                   |  37.696s  |  37.696s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_2_UFLIA.smt2                                                     | 599.699s  | 599.699s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_2_UFNIA.smt2                                                     | 599.523s  | 599.523s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_3_UFDTLIA.smt2                                                   | 511.111s  | 511.111s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_3_UFDTNIA.smt2                                                   |  94.906s  |  94.906s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_3_UFLIA.smt2                                                     | 599.708s  | 599.708s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_3_UFNIA.smt2                                                     | 599.479s  | 599.479s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_4_UFDTLIA.smt2                                                   | 598.545s  | 598.545s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_4_UFDTNIA.smt2                                                   | 599.604s  | 599.604s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_4_UFLIA.smt2                                                     | 599.598s  | 599.598s  |   0.000s  | 0.0%|
|83314_a702bf8b823398c9e37a_4_UFNIA.smt2                                                     | 599.622s  | 599.622s  |   0.000s  | 0.0%|
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFDTLIA.smt2                                   |  39.830s  |  39.830s  |   0.000s  | 0.0%|
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFDTNIA.smt2                                   | 121.923s  | 121.923s  |   0.000s  | 0.0%|
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFLIA.smt2                                     | 599.586s  | 599.586s  |   0.000s  | 0.0%|
|93493_1fdb6cc8eb9c4363b5838af9eb8c7f1f_53_QF_UFNIA.smt2                                     |  97.946s  |  97.946s  |   0.000s  | 0.0%|
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFDTLIA.smt2                                   | 179.903s  | 179.903s  |   0.000s  | 0.0%|
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFDTNIA.smt2                                   |   9.491s  |   9.491s  |   0.000s  | 0.0%|
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFLIA.smt2                                     | 599.778s  | 599.778s  |   0.000s  | 0.0%|
|93493_27ab26d56d60426da02e50231269b6ff_51_QF_UFNIA.smt2                                     |  75.134s  |  75.134s  |   0.000s  | 0.0%|
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFDTLIA.smt2                                   | 599.618s  | 599.618s  |   0.000s  | 0.0%|
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFDTNIA.smt2                                   | 599.380s  | 599.380s  |   0.000s  | 0.0%|
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFLIA.smt2                                     | 599.643s  | 599.643s  |   0.000s  | 0.0%|
|93493_4ea6163ed03941199c785278ccc42812_49_QF_UFNIA.smt2                                     | 599.459s  | 599.459s  |   0.000s  | 0.0%|
|93493_5990a6bf5f2740164f77_50_QF_UFDTLIA.smt2                                               | 349.377s  | 349.377s  |   0.000s  | 0.0%|
|93493_5990a6bf5f2740164f77_50_QF_UFDTNIA.smt2                                               | 345.089s  | 345.089s  |   0.000s  | 0.0%|
|93493_5990a6bf5f2740164f77_50_QF_UFLIA.smt2                                                 | 599.442s  | 599.442s  |   0.000s  | 0.0%|
|93493_5990a6bf5f2740164f77_50_QF_UFNIA.smt2                                                 | 359.483s  | 359.483s  |   0.000s  | 0.0%|
|93493_798593962ee29ad45ac8_52_QF_UFDTLIA.smt2                                               | 599.634s  | 599.634s  |   0.000s  | 0.0%|
|93493_798593962ee29ad45ac8_52_QF_UFDTNIA.smt2                                               | 599.594s  | 599.594s  |   0.000s  | 0.0%|
|93493_798593962ee29ad45ac8_52_QF_UFLIA.smt2                                                 | 599.656s  | 599.656s  |   0.000s  | 0.0%|
|93493_798593962ee29ad45ac8_52_QF_UFNIA.smt2                                                 | 599.654s  | 599.654s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_29_QF_UFDTLIA.smt2                                                 | 599.579s  | 599.579s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_29_QF_UFDTNIA.smt2                                                 |  63.679s  |  63.679s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_29_QF_UFLIA.smt2                                                   | 599.784s  | 599.784s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_29_QF_UFNIA.smt2                                                   |  65.423s  |  65.423s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_30_QF_UFDTLIA.smt2                                                 | 599.118s  | 599.118s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_30_QF_UFDTNIA.smt2                                                 | 599.014s  | 599.014s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_30_QF_UFLIA.smt2                                                   | 599.512s  | 599.512s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_30_QF_UFNIA.smt2                                                   | 152.661s  | 152.661s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_31_QF_UFDTLIA.smt2                                                 | 599.515s  | 599.515s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_31_QF_UFDTNIA.smt2                                                 |  16.902s  |  16.902s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_31_QF_UFLIA.smt2                                                   | 599.279s  | 599.279s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_31_QF_UFNIA.smt2                                                   |  14.355s  |  14.355s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_32_QF_UFDTLIA.smt2                                                 | 599.786s  | 599.786s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_32_QF_UFDTNIA.smt2                                                 | 599.524s  | 599.524s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_32_QF_UFLIA.smt2                                                   | 599.738s  | 599.738s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_32_QF_UFNIA.smt2                                                   |  39.821s  |  39.821s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_33_QF_UFDTLIA.smt2                                                 | 599.123s  | 599.123s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_33_QF_UFDTNIA.smt2                                                 |  93.497s  |  93.497s  |   0.000s  | 0.0%|
|940_590f27b1c3c800d3243e_33_QF_UFLIA.smt2                                                   | 599.458s  | 599.458s  |   0.000s  | 0.0%|
</details>
