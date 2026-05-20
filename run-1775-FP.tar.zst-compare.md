Comparing data and data


# SUMMARY
- LHS tests = 2504
- RHS tests = 2504
- LHS success = 2504  (100.0%)
- RHS success = 2504  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: FP.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/FP.tar.zst?download=1
Z3 commit message: [code-simplifier] Simplify `api_ast.cpp` by removing unreachable branch and stray comment (#9570)

This change simplifies recently touched API code in
`src/api/api_ast.cpp` without altering semantics. It removes an
unreachable error path in `Z3_get_index_value` and deletes an empty
comment in `Z3_mk_rec_func_decl`.

- **`Z3_get_index_value`: remove dead branch**
- After validating `a` is non-null and of kind `AST_VAR`, the conversion
to `var*` is already guaranteed by existing AST casting invariants.
- The redundant null-check/error-return branch was removed, leaving a
direct index return.

- **`Z3_mk_rec_func_decl`: remove noise**
  - Deleted a stray empty `//` line.

```cpp
// before
var* va = to_var(_a);
if (va) {
    return va->get_idx();
}
SET_ERROR_CODE(Z3_INVALID_ARG, nullptr);
return 0;

// after
var* va = to_var(_a);
return va->get_idx();
```

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

</pre>
# RHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: FP.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/FP.tar.zst?download=1
Z3 commit message: [code-simplifier] Simplify `api_ast.cpp` by removing unreachable branch and stray comment (#9570)

This change simplifies recently touched API code in
`src/api/api_ast.cpp` without altering semantics. It removes an
unreachable error path in `Z3_get_index_value` and deletes an empty
comment in `Z3_mk_rec_func_decl`.

- **`Z3_get_index_value`: remove dead branch**
- After validating `a` is non-null and of kind `AST_VAR`, the conversion
to `var*` is already guaranteed by existing AST casting invariants.
- The redundant null-check/error-return branch was removed, leaving a
direct index return.

- **`Z3_mk_rec_func_decl`: remove noise**
  - Deleted a stray empty `//` line.

```cpp
// before
var* va = to_var(_a);
if (va) {
    return va->get_idx();
}
SET_ERROR_CODE(Z3_INVALID_ARG, nullptr);
return 0;

// after
var* va = to_var(_a);
return va->get_idx();
```

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: NikolajBjorner <3085284+NikolajBjorner@users.noreply.github.com>

</pre>
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/FP/20170501-Heizmann-UltimateAutomizer/float-to-double1_true-unreach-call.i_270.smt2  |   6.227s  |   6.227s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_distinct.smt2                              |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.geq.smt2                                |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.gt.smt2                                 |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isInfinite.smt2                         |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isNaN.smt2                              |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isNegative.smt2                         |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isNormal.smt2                           |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isPositive.smt2                         |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isSubnormal.smt2                        |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isZero.smt2                             |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.leq.smt2                                |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.lt.smt2                                 |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_distinct.smt2                              |   7.100s  |   7.100s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.geq.smt2                                |   0.988s  |   0.988s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.gt.smt2                                 |   7.754s  |   7.754s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isInfinite.smt2                         |   0.805s  |   0.805s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isNaN.smt2                              |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isNegative.smt2                         |  12.458s  |  12.458s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isNormal.smt2                           |   4.098s  |   4.098s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/FP/20170501-Heizmann-UltimateAutomizer/float-to-double1_true-unreach-call.i_270.smt2  |   6.227s  |   6.227s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_distinct.smt2                              |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.geq.smt2                                |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.gt.smt2                                 |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isInfinite.smt2                         |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isNaN.smt2                              |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isNegative.smt2                         |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isNormal.smt2                           |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isPositive.smt2                         |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isSubnormal.smt2                        |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isZero.smt2                             |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.leq.smt2                                |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.lt.smt2                                 |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_distinct.smt2                              |   7.100s  |   7.100s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.geq.smt2                                |   0.988s  |   0.988s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.gt.smt2                                 |   7.754s  |   7.754s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isInfinite.smt2                         |   0.805s  |   0.805s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isNaN.smt2                              |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isNegative.smt2                         |  12.458s  |  12.458s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isNormal.smt2                           |   4.098s  |   4.098s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/FP/20170501-Heizmann-UltimateAutomizer/float-to-double1_true-unreach-call.i_270.smt2  |   6.227s  |   6.227s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_distinct.smt2                              |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.geq.smt2                                |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.gt.smt2                                 |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isInfinite.smt2                         |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isNaN.smt2                              |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isNegative.smt2                         |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isNormal.smt2                           |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isPositive.smt2                         |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isSubnormal.smt2                        |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isZero.smt2                             |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.leq.smt2                                |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.lt.smt2                                 |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_distinct.smt2                              |   7.100s  |   7.100s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.geq.smt2                                |   0.988s  |   0.988s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.gt.smt2                                 |   7.754s  |   7.754s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isInfinite.smt2                         |   0.805s  |   0.805s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isNaN.smt2                              |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isNegative.smt2                         |  12.458s  |  12.458s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isNormal.smt2                           |   4.098s  |   4.098s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/FP/20170501-Heizmann-UltimateAutomizer/float-to-double1_true-unreach-call.i_270.smt2  |   6.227s  |   6.227s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_distinct.smt2                              |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.geq.smt2                                |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.gt.smt2                                 |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isInfinite.smt2                         |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isNaN.smt2                              |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isNegative.smt2                         |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isNormal.smt2                           |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isPositive.smt2                         |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isSubnormal.smt2                        |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isZero.smt2                             |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.leq.smt2                                |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.lt.smt2                                 |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_distinct.smt2                              |   7.100s  |   7.100s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.geq.smt2                                |   0.988s  |   0.988s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.gt.smt2                                 |   7.754s  |   7.754s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isInfinite.smt2                         |   0.805s  |   0.805s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isNaN.smt2                              |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isNegative.smt2                         |  12.458s  |  12.458s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isNormal.smt2                           |   4.098s  |   4.098s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.rem_fp.leq0.smt2                              |  20.338s |1615.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_fp.leq0.smt2                              |  20.322s |1615.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.rem_fp.isZero0.smt2                           |  20.312s |1621.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_fp.isPositive0.smt2                       |  20.285s |1621.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_fp.isNegative0.smt2                       |  20.276s |1621.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sqrt_fp.lt.smt2                               |  20.272s |899.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.rem_fp.isSubnormal1.smt2                      |  20.265s |1682.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_fp.isSubnormal1.smt2                      |  20.262s |1682.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_fp.isNegative1.smt2                       |  20.261s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_fp.isNegative0.smt2                       |  20.261s |1621.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.rem_fp.isZero0.smt2                           |  20.250s |1621.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_fp.isInfinite1.smt2                       |  20.250s |1621.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.rem_fp.isNaN0.smt2                            |  20.245s |1614.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.rem_fp.isInfinite0.smt2                       |  20.241s |1621.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_distinct0.smt2                            |  20.236s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_fp.isSubnormal1.smt2                      |  20.234s |1682.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.rem_distinct1.smt2                            |  20.232s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.rem_fp.isZero1.smt2                           |  20.226s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sqrt_fp.geq.smt2                              |  20.224s |434.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.rem_fp.isNegative0.smt2                       |  20.224s |1621.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.rem_fp.leq0.smt2                              |  20.338s |1615.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_fp.leq0.smt2                              |  20.322s |1615.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.rem_fp.isZero0.smt2                           |  20.312s |1621.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_fp.isPositive0.smt2                       |  20.285s |1621.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_fp.isNegative0.smt2                       |  20.276s |1621.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sqrt_fp.lt.smt2                               |  20.272s |899.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.rem_fp.isSubnormal1.smt2                      |  20.265s |1682.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_fp.isSubnormal1.smt2                      |  20.262s |1682.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_fp.isNegative1.smt2                       |  20.261s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_fp.isNegative0.smt2                       |  20.261s |1621.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.rem_fp.isZero0.smt2                           |  20.250s |1621.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_fp.isInfinite1.smt2                       |  20.250s |1621.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.rem_fp.isNaN0.smt2                            |  20.245s |1614.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.rem_fp.isInfinite0.smt2                       |  20.241s |1621.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_distinct0.smt2                            |  20.236s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_fp.isSubnormal1.smt2                      |  20.234s |1682.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.rem_distinct1.smt2                            |  20.232s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.rem_fp.isZero1.smt2                           |  20.226s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sqrt_fp.geq.smt2                              |  20.224s |434.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.rem_fp.isNegative0.smt2                       |  20.224s |1621.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/FP/20170501-Heizmann-UltimateAutomizer/float-to-double1_true-unreach-call.i_270.smt2  |47.856MiB|47.856MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_distinct.smt2                              |20.936MiB|20.936MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.geq.smt2                                |23.124MiB|23.124MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.gt.smt2                                 |22.856MiB|22.856MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isInfinite.smt2                         |21.164MiB|21.164MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isNaN.smt2                              |20.856MiB|20.856MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isNegative.smt2                         |20.06MiB|20.06MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isNormal.smt2                           |20.836MiB|20.836MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isPositive.smt2                         |20.772MiB|20.772MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isSubnormal.smt2                        |20.972MiB|20.972MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isZero.smt2                             |20.788MiB|20.788MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.leq.smt2                                |21.384MiB|21.384MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.lt.smt2                                 |21.664MiB|21.664MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_distinct.smt2                              |41.92MiB|41.92MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.geq.smt2                                |37.9MiB|37.9MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.gt.smt2                                 |51.692MiB|51.692MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isInfinite.smt2                         |34.468MiB|34.468MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isNaN.smt2                              |20.956MiB|20.956MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isNegative.smt2                         |76.34MiB|76.34MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isNormal.smt2                           |48.72MiB|48.72MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/FP/20170501-Heizmann-UltimateAutomizer/float-to-double1_true-unreach-call.i_270.smt2  |47.856MiB|47.856MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_distinct.smt2                              |20.936MiB|20.936MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.geq.smt2                                |23.124MiB|23.124MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.gt.smt2                                 |22.856MiB|22.856MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isInfinite.smt2                         |21.164MiB|21.164MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isNaN.smt2                              |20.856MiB|20.856MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isNegative.smt2                         |20.06MiB|20.06MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isNormal.smt2                           |20.836MiB|20.836MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isPositive.smt2                         |20.772MiB|20.772MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isSubnormal.smt2                        |20.972MiB|20.972MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isZero.smt2                             |20.788MiB|20.788MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.leq.smt2                                |21.384MiB|21.384MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.lt.smt2                                 |21.664MiB|21.664MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_distinct.smt2                              |41.92MiB|41.92MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.geq.smt2                                |37.9MiB|37.9MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.gt.smt2                                 |51.692MiB|51.692MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isInfinite.smt2                         |34.468MiB|34.468MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isNaN.smt2                              |20.956MiB|20.956MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isNegative.smt2                         |76.34MiB|76.34MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isNormal.smt2                           |48.72MiB|48.72MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/FP/20170501-Heizmann-UltimateAutomizer/float-to-double1_true-unreach-call.i_270.smt2  |47.856MiB|47.856MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_distinct.smt2                              |20.936MiB|20.936MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.geq.smt2                                |23.124MiB|23.124MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.gt.smt2                                 |22.856MiB|22.856MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isInfinite.smt2                         |21.164MiB|21.164MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isNaN.smt2                              |20.856MiB|20.856MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isNegative.smt2                         |20.06MiB|20.06MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isNormal.smt2                           |20.836MiB|20.836MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isPositive.smt2                         |20.772MiB|20.772MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isSubnormal.smt2                        |20.972MiB|20.972MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isZero.smt2                             |20.788MiB|20.788MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.leq.smt2                                |21.384MiB|21.384MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.lt.smt2                                 |21.664MiB|21.664MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_distinct.smt2                              |41.92MiB|41.92MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.geq.smt2                                |37.9MiB|37.9MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.gt.smt2                                 |51.692MiB|51.692MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isInfinite.smt2                         |34.468MiB|34.468MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isNaN.smt2                              |20.956MiB|20.956MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isNegative.smt2                         |76.34MiB|76.34MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isNormal.smt2                           |48.72MiB|48.72MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/FP/20170501-Heizmann-UltimateAutomizer/float-to-double1_true-unreach-call.i_270.smt2  |47.856MiB|47.856MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_distinct.smt2                              |20.936MiB|20.936MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.geq.smt2                                |23.124MiB|23.124MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.gt.smt2                                 |22.856MiB|22.856MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isInfinite.smt2                         |21.164MiB|21.164MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isNaN.smt2                              |20.856MiB|20.856MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isNegative.smt2                         |20.06MiB|20.06MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isNormal.smt2                           |20.836MiB|20.836MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isPositive.smt2                         |20.772MiB|20.772MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isSubnormal.smt2                        |20.972MiB|20.972MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isZero.smt2                             |20.788MiB|20.788MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.leq.smt2                                |21.384MiB|21.384MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.lt.smt2                                 |21.664MiB|21.664MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_distinct.smt2                              |41.92MiB|41.92MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.geq.smt2                                |37.9MiB|37.9MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.gt.smt2                                 |51.692MiB|51.692MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isInfinite.smt2                         |34.468MiB|34.468MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isNaN.smt2                              |20.956MiB|20.956MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isNegative.smt2                         |76.34MiB|76.34MiB|0B| 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isNormal.smt2                           |48.72MiB|48.72MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.rem_fp.isSubnormal1.smt2                      |  20.265s |1682.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_fp.isSubnormal1.smt2                      |  20.262s |1682.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_fp.isSubnormal1.smt2                      |  20.234s |1682.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.rem_fp.isSubnormal1.smt2                      |  20.198s |1682.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.rem_fp.isSubnormal1.smt2                      |  20.185s |1682.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_fp.isNegative1.smt2                       |  20.261s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_distinct0.smt2                            |  20.236s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.rem_distinct1.smt2                            |  20.232s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.rem_fp.isZero1.smt2                           |  20.226s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_distinct1.smt2                            |  20.217s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.rem_fp.isNormal1.smt2                         |  20.207s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.rem_fp.isPositive1.smt2                       |  20.205s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_distinct1.smt2                            |  20.197s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.rem_distinct1.smt2                            |  20.194s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.rem_distinct1.smt2                            |  20.188s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.rem_distinct0.smt2                            |  20.188s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.rem_fp.isPositive1.smt2                       |  20.186s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_fp.isNegative1.smt2                       |  20.183s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.rem_fp.isNormal1.smt2                         |  20.180s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_fp.isNormal1.smt2                         |  20.180s |1622.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.rem_fp.isSubnormal1.smt2                      |  20.265s |1682.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_fp.isSubnormal1.smt2                      |  20.262s |1682.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_fp.isSubnormal1.smt2                      |  20.234s |1682.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.rem_fp.isSubnormal1.smt2                      |  20.198s |1682.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.rem_fp.isSubnormal1.smt2                      |  20.185s |1682.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_fp.isNegative1.smt2                       |  20.261s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_distinct0.smt2                            |  20.236s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.rem_distinct1.smt2                            |  20.232s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.rem_fp.isZero1.smt2                           |  20.226s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_distinct1.smt2                            |  20.217s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.rem_fp.isNormal1.smt2                         |  20.207s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.rem_fp.isPositive1.smt2                       |  20.205s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_distinct1.smt2                            |  20.197s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.rem_distinct1.smt2                            |  20.194s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.rem_distinct1.smt2                            |  20.188s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.rem_distinct0.smt2                            |  20.188s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.rem_fp.isPositive1.smt2                       |  20.186s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_fp.isNegative1.smt2                       |  20.183s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.rem_fp.isNormal1.smt2                         |  20.180s |1622.0MiB|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_fp.isNormal1.smt2                         |  20.180s |1622.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/FP/20170501-Heizmann-UltimateAutomizer/float-to-double1_true-unreach-call.i_270.smt2  |   6.227s  |   6.227s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_distinct.smt2                              |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.geq.smt2                                |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.gt.smt2                                 |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isInfinite.smt2                         |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isNaN.smt2                              |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isNegative.smt2                         |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isNormal.smt2                           |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isPositive.smt2                         |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isSubnormal.smt2                        |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.isZero.smt2                             |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.leq.smt2                                |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.abs_fp.lt.smt2                                 |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_distinct.smt2                              |   7.100s  |   7.100s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.geq.smt2                                |   0.988s  |   0.988s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.gt.smt2                                 |   7.754s  |   7.754s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isInfinite.smt2                         |   0.805s  |   0.805s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isNaN.smt2                              |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isNegative.smt2                         |  12.458s  |  12.458s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isNormal.smt2                           |   4.098s  |   4.098s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isPositive.smt2                         |  18.258s  |  18.258s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isSubnormal.smt2                        |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.isZero.smt2                             |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.leq.smt2                                |   9.989s  |   9.989s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.add_fp.lt.smt2                                 |   0.768s  |   0.768s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.div_distinct0.smt2                             |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.div_distinct1.smt2                             |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.div_fp.geq0.smt2                               |  20.070s  |  20.070s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.div_fp.geq1.smt2                               |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.div_fp.gt0.smt2                                |  20.069s  |  20.069s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.div_fp.gt1.smt2                                |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.div_fp.isInfinite0.smt2                        |  20.081s  |  20.081s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.div_fp.isInfinite1.smt2                        |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.div_fp.isNaN0.smt2                             |   3.164s  |   3.164s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.div_fp.isNaN1.smt2                             |  16.282s  |  16.282s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.div_fp.isNegative0.smt2                        |  20.088s  |  20.088s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.div_fp.isNegative1.smt2                        |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.div_fp.isNormal0.smt2                          |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.div_fp.isNormal1.smt2                          |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.div_fp.isPositive0.smt2                        |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.div_fp.isPositive1.smt2                        |  20.061s  |  20.061s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.div_fp.isSubnormal0.smt2                       |  20.085s  |  20.085s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.div_fp.isSubnormal1.smt2                       |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.div_fp.isZero0.smt2                            |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.div_fp.isZero1.smt2                            |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.div_fp.leq0.smt2                               |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.div_fp.leq1.smt2                               |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.div_fp.lt0.smt2                                |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.div_fp.lt1.smt2                                |  20.095s  |  20.095s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.fma_fp.isInfinite0.smt2                        |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.fma_fp.isInfinite2.smt2                        |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.fma_fp.isNaN0.smt2                             |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.fma_fp.isNaN2.smt2                             |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.fma_fp.isNegative0.smt2                        |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.fma_fp.isNegative2.smt2                        |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.fma_fp.isNormal0.smt2                          |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.fma_fp.isNormal2.smt2                          |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.fma_fp.isPositive0.smt2                        |  20.064s  |  20.064s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.fma_fp.isPositive2.smt2                        |  20.073s  |  20.073s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.fma_fp.isZero0.smt2                            |  20.061s  |  20.061s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.fma_fp.isZero2.smt2                            |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.mul_distinct.smt2                              |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.mul_fp.geq.smt2                                |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.mul_fp.gt.smt2                                 |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.mul_fp.isInfinite.smt2                         |  14.375s  |  14.375s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.mul_fp.isNaN.smt2                              |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.mul_fp.isNegative.smt2                         |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.mul_fp.isNormal.smt2                           |  20.075s  |  20.075s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.mul_fp.isPositive.smt2                         |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.mul_fp.isSubnormal.smt2                        |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.mul_fp.isZero.smt2                             |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.mul_fp.leq.smt2                                |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.mul_fp.lt.smt2                                 |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.neg_distinct.smt2                              |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.neg_fp.geq.smt2                                |   4.886s  |   4.886s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.neg_fp.gt.smt2                                 |   0.848s  |   0.848s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.neg_fp.isInfinite.smt2                         |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.neg_fp.isNaN.smt2                              |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.neg_fp.isNegative.smt2                         |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.neg_fp.isNormal.smt2                           |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.neg_fp.isPositive.smt2                         |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.neg_fp.isSubnormal.smt2                        |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.neg_fp.isZero.smt2                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.neg_fp.leq.smt2                                |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.neg_fp.lt.smt2                                 |   0.496s  |   0.496s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.rem_distinct0.smt2                             |  20.163s  |  20.163s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.rem_distinct1.smt2                             |  20.194s  |  20.194s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.rem_fp.geq0.smt2                               |  20.161s  |  20.161s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.rem_fp.isInfinite0.smt2                        |  20.155s  |  20.155s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.rem_fp.isInfinite1.smt2                        |  20.213s  |  20.213s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.rem_fp.isNaN0.smt2                             |  20.202s  |  20.202s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.rem_fp.isNaN1.smt2                             |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.rem_fp.isNegative0.smt2                        |  20.165s  |  20.165s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.rem_fp.isNegative1.smt2                        |  20.177s  |  20.177s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.rem_fp.isNormal0.smt2                          |  20.175s  |  20.175s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.rem_fp.isNormal1.smt2                          |  20.207s  |  20.207s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.rem_fp.isPositive0.smt2                        |  20.207s  |  20.207s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.rem_fp.isPositive1.smt2                        |  20.205s  |  20.205s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.rem_fp.isSubnormal0.smt2                       |  20.184s  |  20.184s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.rem_fp.isSubnormal1.smt2                       |  20.185s  |  20.185s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.rem_fp.isZero0.smt2                            |  20.312s  |  20.312s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.rem_fp.isZero1.smt2                            |  20.226s  |  20.226s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.rem_fp.leq0.smt2                               |  20.194s  |  20.194s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.roundToIntegral_distinct.smt2                  |   0.319s  |   0.319s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.roundToIntegral_fp.geq.smt2                    |   2.111s  |   2.111s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.roundToIntegral_fp.gt.smt2                     |   1.005s  |   1.005s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.roundToIntegral_fp.isInfinite.smt2             |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.roundToIntegral_fp.isNaN.smt2                  |   0.816s  |   0.816s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.roundToIntegral_fp.isNegative.smt2             |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.roundToIntegral_fp.isNormal.smt2               |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.roundToIntegral_fp.isPositive.smt2             |   0.324s  |   0.324s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.roundToIntegral_fp.isSubnormal.smt2            |   0.511s  |   0.511s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.roundToIntegral_fp.isZero.smt2                 |   0.350s  |   0.350s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.roundToIntegral_fp.leq.smt2                    |   0.305s  |   0.305s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.roundToIntegral_fp.lt.smt2                     |   0.842s  |   0.842s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sqrt_distinct.smt2                             |  20.118s  |  20.118s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sqrt_fp.geq.smt2                               |  20.177s  |  20.177s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sqrt_fp.gt.smt2                                |  20.092s  |  20.092s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sqrt_fp.isInfinite.smt2                        |   6.160s  |   6.160s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sqrt_fp.isNaN.smt2                             |  20.168s  |  20.168s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sqrt_fp.isNegative.smt2                        |   3.656s  |   3.656s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sqrt_fp.isNormal.smt2                          |  20.081s  |  20.081s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sqrt_fp.isPositive.smt2                        |  20.185s  |  20.185s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sqrt_fp.isSubnormal.smt2                       |  20.083s  |  20.083s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sqrt_fp.isZero.smt2                            |  20.107s  |  20.107s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sqrt_fp.leq.smt2                               |  20.141s  |  20.141s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sqrt_fp.lt.smt2                                |  20.098s  |  20.098s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sub_distinct0.smt2                             |   0.726s  |   0.726s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sub_distinct1.smt2                             |   3.370s  |   3.370s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sub_fp.geq0.smt2                               |   2.507s  |   2.507s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sub_fp.geq1.smt2                               |  10.915s  |  10.915s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sub_fp.gt0.smt2                                |   1.416s  |   1.416s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sub_fp.gt1.smt2                                |   5.047s  |   5.047s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sub_fp.isInfinite0.smt2                        |   0.596s  |   0.596s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sub_fp.isInfinite1.smt2                        |   0.689s  |   0.689s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sub_fp.isNaN0.smt2                             |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sub_fp.isNaN1.smt2                             |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sub_fp.isNegative0.smt2                        |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sub_fp.isNegative1.smt2                        |   3.062s  |   3.062s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sub_fp.isNormal0.smt2                          |   4.209s  |   4.209s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sub_fp.isNormal1.smt2                          |   4.248s  |   4.248s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sub_fp.isPositive0.smt2                        |  14.131s  |  14.131s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sub_fp.isPositive1.smt2                        |   0.366s  |   0.366s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sub_fp.isSubnormal0.smt2                       |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sub_fp.isSubnormal1.smt2                       |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sub_fp.isZero0.smt2                            |   1.195s  |   1.195s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sub_fp.isZero1.smt2                            |   1.299s  |   1.299s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sub_fp.leq0.smt2                               |   2.008s  |   2.008s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sub_fp.leq1.smt2                               |   6.163s  |   6.163s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sub_fp.lt0.smt2                                |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNA_fp.sub_fp.lt1.smt2                                |   1.880s  |   1.880s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.abs_distinct.smt2                              |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.abs_fp.geq.smt2                                |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.abs_fp.gt.smt2                                 |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.abs_fp.isInfinite.smt2                         |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.abs_fp.isNaN.smt2                              |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.abs_fp.isNegative.smt2                         |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.abs_fp.isNormal.smt2                           |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.abs_fp.isPositive.smt2                         |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.abs_fp.isSubnormal.smt2                        |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.abs_fp.isZero.smt2                             |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.abs_fp.leq.smt2                                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.abs_fp.lt.smt2                                 |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.add_distinct.smt2                              |   0.997s  |   0.997s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.add_fp.geq.smt2                                |   1.474s  |   1.474s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.add_fp.gt.smt2                                 |   2.433s  |   2.433s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.add_fp.isInfinite.smt2                         |   0.802s  |   0.802s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.add_fp.isNaN.smt2                              |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.add_fp.isNegative.smt2                         |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.add_fp.isNormal.smt2                           |   5.988s  |   5.988s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.add_fp.isPositive.smt2                         |   3.708s  |   3.708s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.add_fp.isSubnormal.smt2                        |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.add_fp.isZero.smt2                             |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.add_fp.leq.smt2                                |   2.588s  |   2.588s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.add_fp.lt.smt2                                 |  13.889s  |  13.889s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.div_distinct0.smt2                             |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.div_distinct1.smt2                             |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.div_fp.geq0.smt2                               |  20.047s  |  20.047s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.div_fp.geq1.smt2                               |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.div_fp.gt0.smt2                                |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.div_fp.gt1.smt2                                |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.div_fp.isInfinite0.smt2                        |  20.069s  |  20.069s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.div_fp.isInfinite1.smt2                        |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.div_fp.isNaN0.smt2                             |   8.884s  |   8.884s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.div_fp.isNaN1.smt2                             |  11.339s  |  11.339s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.div_fp.isNegative0.smt2                        |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.div_fp.isNegative1.smt2                        |  20.105s  |  20.105s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.div_fp.isNormal0.smt2                          |  20.083s  |  20.083s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.div_fp.isNormal1.smt2                          |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.div_fp.isPositive0.smt2                        |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.div_fp.isPositive1.smt2                        |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.div_fp.isSubnormal0.smt2                       |  20.168s  |  20.168s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.div_fp.isSubnormal1.smt2                       |  20.068s  |  20.068s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.div_fp.isZero0.smt2                            |   8.571s  |   8.571s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.div_fp.isZero1.smt2                            |  17.231s  |  17.231s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.div_fp.leq0.smt2                               |  20.063s  |  20.063s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.div_fp.leq1.smt2                               |  20.084s  |  20.084s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.div_fp.lt0.smt2                                |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.div_fp.lt1.smt2                                |  20.064s  |  20.064s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.fma_fp.isInfinite0.smt2                        |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.fma_fp.isInfinite2.smt2                        |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.fma_fp.isNaN0.smt2                             |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.fma_fp.isNaN2.smt2                             |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.fma_fp.isNegative0.smt2                        |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.fma_fp.isNegative2.smt2                        |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.fma_fp.isNormal0.smt2                          |  20.073s  |  20.073s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.fma_fp.isNormal2.smt2                          |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.fma_fp.isPositive0.smt2                        |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.fma_fp.isPositive2.smt2                        |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.fma_fp.isZero0.smt2                            |  20.063s  |  20.063s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.fma_fp.isZero2.smt2                            |  20.066s  |  20.066s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.mul_distinct.smt2                              |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.mul_fp.geq.smt2                                |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.mul_fp.gt.smt2                                 |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.mul_fp.isInfinite.smt2                         |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.mul_fp.isNaN.smt2                              |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.mul_fp.isNegative.smt2                         |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.mul_fp.isNormal.smt2                           |  20.040s  |  20.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.mul_fp.isPositive.smt2                         |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.mul_fp.isSubnormal.smt2                        |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.mul_fp.isZero.smt2                             |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.mul_fp.leq.smt2                                |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.mul_fp.lt.smt2                                 |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.neg_distinct.smt2                              |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.neg_fp.geq.smt2                                |   4.683s  |   4.683s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.neg_fp.gt.smt2                                 |   0.971s  |   0.971s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.neg_fp.isInfinite.smt2                         |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.neg_fp.isNaN.smt2                              |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.neg_fp.isNegative.smt2                         |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.neg_fp.isNormal.smt2                           |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.neg_fp.isPositive.smt2                         |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.neg_fp.isSubnormal.smt2                        |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.neg_fp.isZero.smt2                             |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.neg_fp.leq.smt2                                |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.neg_fp.lt.smt2                                 |   0.517s  |   0.517s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.rem_distinct0.smt2                             |  20.168s  |  20.168s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.rem_distinct1.smt2                             |  20.232s  |  20.232s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.rem_fp.geq0.smt2                               |  20.195s  |  20.195s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.rem_fp.isInfinite0.smt2                        |  20.241s  |  20.241s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.rem_fp.isInfinite1.smt2                        |  20.162s  |  20.162s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.rem_fp.isNaN0.smt2                             |  20.245s  |  20.245s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.rem_fp.isNaN1.smt2                             |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.rem_fp.isNegative0.smt2                        |  20.163s  |  20.163s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.rem_fp.isNegative1.smt2                        |  20.178s  |  20.178s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.rem_fp.isNormal0.smt2                          |  20.180s  |  20.180s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.rem_fp.isNormal1.smt2                          |  20.193s  |  20.193s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.rem_fp.isPositive0.smt2                        |  20.176s  |  20.176s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.rem_fp.isPositive1.smt2                        |  20.165s  |  20.165s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.rem_fp.isSubnormal0.smt2                       |  20.202s  |  20.202s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.rem_fp.isSubnormal1.smt2                       |  20.265s  |  20.265s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.rem_fp.isZero0.smt2                            |  20.250s  |  20.250s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.rem_fp.isZero1.smt2                            |  20.197s  |  20.197s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.rem_fp.leq0.smt2                               |  20.206s  |  20.206s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.roundToIntegral_distinct.smt2                  |   0.284s  |   0.284s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.roundToIntegral_fp.geq.smt2                    |   0.806s  |   0.806s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.roundToIntegral_fp.gt.smt2                     |   3.059s  |   3.059s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.roundToIntegral_fp.isInfinite.smt2             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.roundToIntegral_fp.isNaN.smt2                  |   0.505s  |   0.505s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.roundToIntegral_fp.isNegative.smt2             |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.roundToIntegral_fp.isNormal.smt2               |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.roundToIntegral_fp.isPositive.smt2             |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.roundToIntegral_fp.isSubnormal.smt2            |   0.476s  |   0.476s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.roundToIntegral_fp.isZero.smt2                 |   0.469s  |   0.469s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.roundToIntegral_fp.leq.smt2                    |   0.356s  |   0.356s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.roundToIntegral_fp.lt.smt2                     |   1.004s  |   1.004s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sqrt_distinct.smt2                             |  20.092s  |  20.092s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sqrt_fp.geq.smt2                               |  20.093s  |  20.093s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sqrt_fp.gt.smt2                                |  20.104s  |  20.104s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sqrt_fp.isInfinite.smt2                        |  20.075s  |  20.075s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sqrt_fp.isNaN.smt2                             |  20.178s  |  20.178s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sqrt_fp.isNegative.smt2                        |   3.927s  |   3.927s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sqrt_fp.isNormal.smt2                          |  20.111s  |  20.111s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sqrt_fp.isPositive.smt2                        |  20.090s  |  20.090s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sqrt_fp.isSubnormal.smt2                       |  20.080s  |  20.080s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sqrt_fp.isZero.smt2                            |  20.105s  |  20.105s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sqrt_fp.leq.smt2                               |  20.095s  |  20.095s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sqrt_fp.lt.smt2                                |  20.085s  |  20.085s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sub_distinct0.smt2                             |   1.269s  |   1.269s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sub_distinct1.smt2                             |   1.018s  |   1.018s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sub_fp.geq0.smt2                               |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sub_fp.geq1.smt2                               |  10.192s  |  10.192s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sub_fp.gt0.smt2                                |   4.223s  |   4.223s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sub_fp.gt1.smt2                                |   1.106s  |   1.106s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sub_fp.isInfinite0.smt2                        |   1.365s  |   1.365s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sub_fp.isInfinite1.smt2                        |   1.968s  |   1.968s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sub_fp.isNaN0.smt2                             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sub_fp.isNaN1.smt2                             |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sub_fp.isNegative0.smt2                        |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sub_fp.isNegative1.smt2                        |   0.450s  |   0.450s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sub_fp.isNormal0.smt2                          |   2.062s  |   2.062s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sub_fp.isNormal1.smt2                          |   5.072s  |   5.072s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sub_fp.isPositive0.smt2                        |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sub_fp.isPositive1.smt2                        |  12.160s  |  12.160s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sub_fp.isSubnormal0.smt2                       |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sub_fp.isSubnormal1.smt2                       |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sub_fp.isZero0.smt2                            |   1.914s  |   1.914s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sub_fp.isZero1.smt2                            |   1.375s  |   1.375s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sub_fp.leq0.smt2                               |  10.671s  |  10.671s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sub_fp.leq1.smt2                               |   0.887s  |   0.887s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sub_fp.lt0.smt2                                |   4.262s  |   4.262s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RNE_fp.sub_fp.lt1.smt2                                |   3.066s  |   3.066s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.abs_distinct.smt2                              |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.abs_fp.geq.smt2                                |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.abs_fp.gt.smt2                                 |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.abs_fp.isInfinite.smt2                         |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.abs_fp.isNaN.smt2                              |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.abs_fp.isNegative.smt2                         |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.abs_fp.isNormal.smt2                           |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.abs_fp.isPositive.smt2                         |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.abs_fp.isSubnormal.smt2                        |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.abs_fp.isZero.smt2                             |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.abs_fp.leq.smt2                                |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.abs_fp.lt.smt2                                 |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.add_distinct.smt2                              |   3.697s  |   3.697s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.add_fp.geq.smt2                                |   8.524s  |   8.524s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.add_fp.gt.smt2                                 |   3.473s  |   3.473s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.add_fp.isInfinite.smt2                         |   0.620s  |   0.620s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.add_fp.isNaN.smt2                              |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.add_fp.isNegative.smt2                         |   2.475s  |   2.475s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.add_fp.isNormal.smt2                           |   9.497s  |   9.497s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.add_fp.isPositive.smt2                         |  20.095s  |  20.095s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.add_fp.isSubnormal.smt2                        |  20.047s  |  20.047s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.add_fp.isZero.smt2                             |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.add_fp.leq.smt2                                |   0.623s  |   0.623s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.add_fp.lt.smt2                                 |  10.163s  |  10.163s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.div_distinct0.smt2                             |  20.067s  |  20.067s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.div_distinct1.smt2                             |  20.064s  |  20.064s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.div_fp.geq0.smt2                               |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.div_fp.geq1.smt2                               |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.div_fp.gt0.smt2                                |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.div_fp.gt1.smt2                                |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.div_fp.isInfinite0.smt2                        |  20.105s  |  20.105s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.div_fp.isInfinite1.smt2                        |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.div_fp.isNaN0.smt2                             |   1.842s  |   1.842s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.div_fp.isNaN1.smt2                             |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.div_fp.isNegative0.smt2                        |  20.066s  |  20.066s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.div_fp.isNegative1.smt2                        |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.div_fp.isNormal0.smt2                          |  20.078s  |  20.078s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.div_fp.isNormal1.smt2                          |  20.096s  |  20.096s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.div_fp.isPositive0.smt2                        |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.div_fp.isPositive1.smt2                        |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.div_fp.isSubnormal0.smt2                       |  20.071s  |  20.071s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.div_fp.isSubnormal1.smt2                       |  20.126s  |  20.126s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.div_fp.isZero0.smt2                            |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.div_fp.isZero1.smt2                            |  20.069s  |  20.069s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.div_fp.leq0.smt2                               |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.div_fp.leq1.smt2                               |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.div_fp.lt0.smt2                                |  20.131s  |  20.131s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.div_fp.lt1.smt2                                |  20.079s  |  20.079s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.fma_fp.isInfinite0.smt2                        |  20.070s  |  20.070s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.fma_fp.isInfinite2.smt2                        |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.fma_fp.isNaN0.smt2                             |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.fma_fp.isNaN2.smt2                             |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.fma_fp.isNegative0.smt2                        |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.fma_fp.isNegative2.smt2                        |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.fma_fp.isNormal0.smt2                          |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.fma_fp.isNormal2.smt2                          |  20.040s  |  20.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.fma_fp.isPositive0.smt2                        |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.fma_fp.isPositive2.smt2                        |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.fma_fp.isZero0.smt2                            |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.fma_fp.isZero2.smt2                            |  20.040s  |  20.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.mul_distinct.smt2                              |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.mul_fp.geq.smt2                                |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.mul_fp.gt.smt2                                 |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.mul_fp.isInfinite.smt2                         |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.mul_fp.isNaN.smt2                              |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.mul_fp.isNegative.smt2                         |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.mul_fp.isNormal.smt2                           |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.mul_fp.isPositive.smt2                         |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.mul_fp.isSubnormal.smt2                        |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.mul_fp.isZero.smt2                             |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.mul_fp.leq.smt2                                |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.mul_fp.lt.smt2                                 |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.neg_distinct.smt2                              |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.neg_fp.geq.smt2                                |   4.683s  |   4.683s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.neg_fp.gt.smt2                                 |   0.863s  |   0.863s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.neg_fp.isInfinite.smt2                         |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.neg_fp.isNaN.smt2                              |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.neg_fp.isNegative.smt2                         |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.neg_fp.isNormal.smt2                           |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.neg_fp.isPositive.smt2                         |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.neg_fp.isSubnormal.smt2                        |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.neg_fp.isZero.smt2                             |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.neg_fp.leq.smt2                                |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.neg_fp.lt.smt2                                 |   0.514s  |   0.514s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_distinct0.smt2                             |  20.236s  |  20.236s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_distinct1.smt2                             |  20.217s  |  20.217s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_fp.geq0.smt2                               |  20.187s  |  20.187s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_fp.isInfinite0.smt2                        |  20.168s  |  20.168s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_fp.isInfinite1.smt2                        |  20.210s  |  20.210s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_fp.isNaN0.smt2                             |  20.178s  |  20.178s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_fp.isNaN1.smt2                             |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_fp.isNegative0.smt2                        |  20.261s  |  20.261s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_fp.isNegative1.smt2                        |  20.183s  |  20.183s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_fp.isNormal0.smt2                          |  20.204s  |  20.204s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_fp.isNormal1.smt2                          |  20.168s  |  20.168s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_fp.isPositive0.smt2                        |  20.285s  |  20.285s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_fp.isPositive1.smt2                        |  20.170s  |  20.170s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_fp.isSubnormal0.smt2                       |  20.170s  |  20.170s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_fp.isSubnormal1.smt2                       |  20.262s  |  20.262s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_fp.isZero0.smt2                            |  20.146s  |  20.146s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_fp.isZero1.smt2                            |  20.176s  |  20.176s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.rem_fp.leq0.smt2                               |  20.322s  |  20.322s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.roundToIntegral_distinct.smt2                  |   0.357s  |   0.357s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.roundToIntegral_fp.geq.smt2                    |   0.837s  |   0.837s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.roundToIntegral_fp.gt.smt2                     |   0.363s  |   0.363s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.roundToIntegral_fp.isInfinite.smt2             |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.roundToIntegral_fp.isNaN.smt2                  |   0.555s  |   0.555s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.roundToIntegral_fp.isNegative.smt2             |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.roundToIntegral_fp.isNormal.smt2               |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.roundToIntegral_fp.isPositive.smt2             |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.roundToIntegral_fp.isSubnormal.smt2            |   0.444s  |   0.444s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.roundToIntegral_fp.isZero.smt2                 |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.roundToIntegral_fp.leq.smt2                    |   0.980s  |   0.980s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.roundToIntegral_fp.lt.smt2                     |   0.892s  |   0.892s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sqrt_distinct.smt2                             |  20.097s  |  20.097s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sqrt_fp.geq.smt2                               |  20.116s  |  20.116s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sqrt_fp.gt.smt2                                |  20.116s  |  20.116s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sqrt_fp.isInfinite.smt2                        |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sqrt_fp.isNaN.smt2                             |  20.090s  |  20.090s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sqrt_fp.isNegative.smt2                        |   2.920s  |   2.920s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sqrt_fp.isNormal.smt2                          |  20.081s  |  20.081s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sqrt_fp.isPositive.smt2                        |  20.086s  |  20.086s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sqrt_fp.isSubnormal.smt2                       |  20.084s  |  20.084s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sqrt_fp.isZero.smt2                            |  20.103s  |  20.103s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sqrt_fp.leq.smt2                               |  20.096s  |  20.096s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sqrt_fp.lt.smt2                                |  20.113s  |  20.113s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sub_distinct0.smt2                             |   2.466s  |   2.466s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sub_distinct1.smt2                             |   3.716s  |   3.716s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sub_fp.geq0.smt2                               |   4.239s  |   4.239s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sub_fp.geq1.smt2                               |   8.017s  |   8.017s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sub_fp.gt0.smt2                                |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sub_fp.gt1.smt2                                |   7.602s  |   7.602s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sub_fp.isInfinite0.smt2                        |   1.115s  |   1.115s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sub_fp.isInfinite1.smt2                        |   0.664s  |   0.664s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sub_fp.isNaN0.smt2                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sub_fp.isNaN1.smt2                             |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sub_fp.isNegative0.smt2                        |  19.681s  |  19.681s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sub_fp.isNegative1.smt2                        |   2.872s  |   2.872s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sub_fp.isNormal0.smt2                          |   8.445s  |   8.445s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sub_fp.isNormal1.smt2                          |   3.195s  |   3.195s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sub_fp.isPositive0.smt2                        |  20.064s  |  20.064s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sub_fp.isPositive1.smt2                        |   2.493s  |   2.493s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sub_fp.isSubnormal0.smt2                       |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sub_fp.isSubnormal1.smt2                       |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sub_fp.isZero0.smt2                            |   0.902s  |   0.902s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sub_fp.isZero1.smt2                            |   1.099s  |   1.099s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sub_fp.leq0.smt2                               |   3.424s  |   3.424s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sub_fp.leq1.smt2                               |   3.730s  |   3.730s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sub_fp.lt0.smt2                                |   9.492s  |   9.492s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTN_fp.sub_fp.lt1.smt2                                |   0.749s  |   0.749s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.abs_distinct.smt2                              |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.abs_fp.geq.smt2                                |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.abs_fp.gt.smt2                                 |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.abs_fp.isInfinite.smt2                         |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.abs_fp.isNaN.smt2                              |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.abs_fp.isNegative.smt2                         |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.abs_fp.isNormal.smt2                           |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.abs_fp.isPositive.smt2                         |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.abs_fp.isSubnormal.smt2                        |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.abs_fp.isZero.smt2                             |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.abs_fp.leq.smt2                                |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.abs_fp.lt.smt2                                 |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.add_distinct.smt2                              |   2.166s  |   2.166s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.add_fp.geq.smt2                                |   3.165s  |   3.165s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.add_fp.gt.smt2                                 |   0.760s  |   0.760s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.add_fp.isInfinite.smt2                         |   0.680s  |   0.680s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.add_fp.isNaN.smt2                              |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.add_fp.isNegative.smt2                         |  20.164s  |  20.164s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.add_fp.isNormal.smt2                           |   6.466s  |   6.466s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.add_fp.isPositive.smt2                         |  11.193s  |  11.193s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.add_fp.isSubnormal.smt2                        |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.add_fp.isZero.smt2                             |  20.074s  |  20.074s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.add_fp.leq.smt2                                |   6.068s  |   6.068s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.add_fp.lt.smt2                                 |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.div_distinct0.smt2                             |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.div_distinct1.smt2                             |  20.100s  |  20.100s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.div_fp.geq0.smt2                               |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.div_fp.geq1.smt2                               |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.div_fp.gt0.smt2                                |  20.129s  |  20.129s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.div_fp.gt1.smt2                                |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.div_fp.isInfinite0.smt2                        |  20.040s  |  20.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.div_fp.isInfinite1.smt2                        |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.div_fp.isNaN0.smt2                             |  10.156s  |  10.156s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.div_fp.isNaN1.smt2                             |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.div_fp.isNegative0.smt2                        |  20.063s  |  20.063s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.div_fp.isNegative1.smt2                        |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.div_fp.isNormal0.smt2                          |  20.104s  |  20.104s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.div_fp.isNormal1.smt2                          |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.div_fp.isPositive0.smt2                        |  20.071s  |  20.071s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.div_fp.isPositive1.smt2                        |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.div_fp.isSubnormal0.smt2                       |  20.073s  |  20.073s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.div_fp.isSubnormal1.smt2                       |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.div_fp.isZero0.smt2                            |  20.061s  |  20.061s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.div_fp.isZero1.smt2                            |  20.086s  |  20.086s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.div_fp.leq0.smt2                               |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.div_fp.leq1.smt2                               |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.div_fp.lt0.smt2                                |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.div_fp.lt1.smt2                                |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.fma_fp.isInfinite0.smt2                        |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.fma_fp.isInfinite2.smt2                        |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.fma_fp.isNaN0.smt2                             |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.fma_fp.isNaN2.smt2                             |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.fma_fp.isNegative0.smt2                        |  20.117s  |  20.117s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.fma_fp.isNegative2.smt2                        |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.fma_fp.isNormal0.smt2                          |  20.085s  |  20.085s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.fma_fp.isNormal2.smt2                          |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.fma_fp.isPositive0.smt2                        |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.fma_fp.isPositive2.smt2                        |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.fma_fp.isZero0.smt2                            |  20.106s  |  20.106s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.fma_fp.isZero2.smt2                            |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.mul_distinct.smt2                              |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.mul_fp.geq.smt2                                |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.mul_fp.gt.smt2                                 |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.mul_fp.isInfinite.smt2                         |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.mul_fp.isNaN.smt2                              |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.mul_fp.isNegative.smt2                         |  19.442s  |  19.442s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.mul_fp.isNormal.smt2                           |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.mul_fp.isPositive.smt2                         |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.mul_fp.isSubnormal.smt2                        |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.mul_fp.isZero.smt2                             |  17.077s  |  17.077s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.mul_fp.leq.smt2                                |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.mul_fp.lt.smt2                                 |  20.111s  |  20.111s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.neg_distinct.smt2                              |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.neg_fp.geq.smt2                                |   4.914s  |   4.914s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.neg_fp.gt.smt2                                 |   0.841s  |   0.841s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.neg_fp.isInfinite.smt2                         |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.neg_fp.isNaN.smt2                              |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.neg_fp.isNegative.smt2                         |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.neg_fp.isNormal.smt2                           |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.neg_fp.isPositive.smt2                         |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.neg_fp.isSubnormal.smt2                        |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.neg_fp.isZero.smt2                             |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.neg_fp.leq.smt2                                |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.neg_fp.lt.smt2                                 |   0.469s  |   0.469s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_distinct0.smt2                             |  20.157s  |  20.157s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_distinct1.smt2                             |  20.197s  |  20.197s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_fp.geq0.smt2                               |  20.165s  |  20.165s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_fp.isInfinite0.smt2                        |  20.200s  |  20.200s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_fp.isInfinite1.smt2                        |  20.250s  |  20.250s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_fp.isNaN0.smt2                             |  20.143s  |  20.143s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_fp.isNaN1.smt2                             |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_fp.isNegative0.smt2                        |  20.276s  |  20.276s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_fp.isNegative1.smt2                        |  20.261s  |  20.261s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_fp.isNormal0.smt2                          |  20.220s  |  20.220s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_fp.isNormal1.smt2                          |  20.180s  |  20.180s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_fp.isPositive0.smt2                        |  20.165s  |  20.165s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_fp.isPositive1.smt2                        |  20.149s  |  20.149s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_fp.isSubnormal0.smt2                       |  20.144s  |  20.144s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_fp.isSubnormal1.smt2                       |  20.234s  |  20.234s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_fp.isZero0.smt2                            |  20.180s  |  20.180s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_fp.isZero1.smt2                            |  20.200s  |  20.200s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.rem_fp.leq0.smt2                               |  20.162s  |  20.162s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.roundToIntegral_distinct.smt2                  |   0.506s  |   0.506s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.roundToIntegral_fp.geq.smt2                    |   0.961s  |   0.961s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.roundToIntegral_fp.gt.smt2                     |   1.153s  |   1.153s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.roundToIntegral_fp.isInfinite.smt2             |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.roundToIntegral_fp.isNaN.smt2                  |   0.592s  |   0.592s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.roundToIntegral_fp.isNegative.smt2             |   0.329s  |   0.329s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.roundToIntegral_fp.isNormal.smt2               |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.roundToIntegral_fp.isPositive.smt2             |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.roundToIntegral_fp.isSubnormal.smt2            |   0.374s  |   0.374s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.roundToIntegral_fp.isZero.smt2                 |   0.605s  |   0.605s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.roundToIntegral_fp.leq.smt2                    |   0.657s  |   0.657s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.roundToIntegral_fp.lt.smt2                     |   0.301s  |   0.301s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sqrt_distinct.smt2                             |  20.095s  |  20.095s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sqrt_fp.geq.smt2                               |  20.090s  |  20.090s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sqrt_fp.gt.smt2                                |  20.091s  |  20.091s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sqrt_fp.isInfinite.smt2                        |  20.100s  |  20.100s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sqrt_fp.isNaN.smt2                             |  20.085s  |  20.085s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sqrt_fp.isNegative.smt2                        |   3.736s  |   3.736s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sqrt_fp.isNormal.smt2                          |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sqrt_fp.isPositive.smt2                        |  20.109s  |  20.109s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sqrt_fp.isSubnormal.smt2                       |  20.090s  |  20.090s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sqrt_fp.isZero.smt2                            |  20.083s  |  20.083s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sqrt_fp.leq.smt2                               |  20.098s  |  20.098s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sqrt_fp.lt.smt2                                |  20.103s  |  20.103s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sub_distinct0.smt2                             |   1.012s  |   1.012s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sub_distinct1.smt2                             |   1.596s  |   1.596s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sub_fp.geq0.smt2                               |   0.676s  |   0.676s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sub_fp.geq1.smt2                               |   1.388s  |   1.388s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sub_fp.gt0.smt2                                |   5.562s  |   5.562s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sub_fp.gt1.smt2                                |   0.629s  |   0.629s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sub_fp.isInfinite0.smt2                        |   1.107s  |   1.107s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sub_fp.isInfinite1.smt2                        |   0.902s  |   0.902s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sub_fp.isNaN0.smt2                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sub_fp.isNaN1.smt2                             |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sub_fp.isNegative0.smt2                        |  18.786s  |  18.786s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sub_fp.isNegative1.smt2                        |   0.555s  |   0.555s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sub_fp.isNormal0.smt2                          |   3.750s  |   3.750s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sub_fp.isNormal1.smt2                          |   5.198s  |   5.198s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sub_fp.isPositive0.smt2                        |   4.972s  |   4.972s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sub_fp.isPositive1.smt2                        |  17.045s  |  17.045s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sub_fp.isSubnormal0.smt2                       |  20.081s  |  20.081s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sub_fp.isSubnormal1.smt2                       |  20.047s  |  20.047s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sub_fp.isZero0.smt2                            |   1.382s  |   1.382s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sub_fp.isZero1.smt2                            |   1.089s  |   1.089s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sub_fp.leq0.smt2                               |   2.684s  |   2.684s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sub_fp.leq1.smt2                               |   1.527s  |   1.527s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sub_fp.lt0.smt2                                |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTP_fp.sub_fp.lt1.smt2                                |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.abs_distinct.smt2                              |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.abs_fp.geq.smt2                                |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.abs_fp.gt.smt2                                 |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.abs_fp.isInfinite.smt2                         |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.abs_fp.isNaN.smt2                              |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.abs_fp.isNegative.smt2                         |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.abs_fp.isNormal.smt2                           |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.abs_fp.isPositive.smt2                         |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.abs_fp.isSubnormal.smt2                        |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.abs_fp.isZero.smt2                             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.abs_fp.leq.smt2                                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.abs_fp.lt.smt2                                 |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.add_distinct.smt2                              |   1.364s  |   1.364s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.add_fp.geq.smt2                                |  19.746s  |  19.746s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.add_fp.gt.smt2                                 |   0.999s  |   0.999s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.add_fp.isInfinite.smt2                         |   0.321s  |   0.321s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.add_fp.isNaN.smt2                              |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.add_fp.isNegative.smt2                         |   0.905s  |   0.905s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.add_fp.isNormal.smt2                           |   1.406s  |   1.406s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.add_fp.isPositive.smt2                         |   5.295s  |   5.295s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.add_fp.isSubnormal.smt2                        |  20.107s  |  20.107s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.add_fp.isZero.smt2                             |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.add_fp.leq.smt2                                |   2.626s  |   2.626s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.add_fp.lt.smt2                                 |  11.893s  |  11.893s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.div_distinct0.smt2                             |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.div_distinct1.smt2                             |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.div_fp.geq0.smt2                               |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.div_fp.geq1.smt2                               |  20.083s  |  20.083s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.div_fp.gt0.smt2                                |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.div_fp.gt1.smt2                                |  20.088s  |  20.088s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.div_fp.isInfinite0.smt2                        |   5.203s  |   5.203s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.div_fp.isInfinite1.smt2                        |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.div_fp.isNaN0.smt2                             |   2.931s  |   2.931s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.div_fp.isNaN1.smt2                             |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.div_fp.isNegative0.smt2                        |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.div_fp.isNegative1.smt2                        |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.div_fp.isNormal0.smt2                          |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.div_fp.isNormal1.smt2                          |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.div_fp.isPositive0.smt2                        |  14.847s  |  14.847s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.div_fp.isPositive1.smt2                        |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.div_fp.isSubnormal0.smt2                       |  20.131s  |  20.131s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.div_fp.isSubnormal1.smt2                       |  20.075s  |  20.075s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.div_fp.isZero0.smt2                            |   7.386s  |   7.386s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.div_fp.isZero1.smt2                            |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.div_fp.leq0.smt2                               |  20.068s  |  20.068s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.div_fp.leq1.smt2                               |  20.040s  |  20.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.div_fp.lt0.smt2                                |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.div_fp.lt1.smt2                                |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.fma_fp.isInfinite0.smt2                        |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.fma_fp.isInfinite2.smt2                        |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.fma_fp.isNaN0.smt2                             |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.fma_fp.isNaN2.smt2                             |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.fma_fp.isNegative0.smt2                        |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.fma_fp.isNegative2.smt2                        |  20.102s  |  20.102s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.fma_fp.isNormal0.smt2                          |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.fma_fp.isNormal2.smt2                          |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.fma_fp.isPositive0.smt2                        |  20.077s  |  20.077s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.fma_fp.isPositive2.smt2                        |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.fma_fp.isZero0.smt2                            |  20.175s  |  20.175s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.fma_fp.isZero2.smt2                            |  20.152s  |  20.152s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.mul_distinct.smt2                              |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.mul_fp.geq.smt2                                |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.mul_fp.gt.smt2                                 |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.mul_fp.isInfinite.smt2                         |  19.184s  |  19.184s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.mul_fp.isNaN.smt2                              |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.mul_fp.isNegative.smt2                         |  20.083s  |  20.083s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.mul_fp.isNormal.smt2                           |  20.095s  |  20.095s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.mul_fp.isPositive.smt2                         |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.mul_fp.isSubnormal.smt2                        |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.mul_fp.isZero.smt2                             |  13.773s  |  13.773s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.mul_fp.leq.smt2                                |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.mul_fp.lt.smt2                                 |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.neg_distinct.smt2                              |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.neg_fp.geq.smt2                                |   4.949s  |   4.949s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.neg_fp.gt.smt2                                 |   0.879s  |   0.879s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.neg_fp.isInfinite.smt2                         |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.neg_fp.isNaN.smt2                              |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.neg_fp.isNegative.smt2                         |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.neg_fp.isNormal.smt2                           |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.neg_fp.isPositive.smt2                         |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.neg_fp.isSubnormal.smt2                        |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.neg_fp.isZero.smt2                             |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.neg_fp.leq.smt2                                |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.neg_fp.lt.smt2                                 |   0.573s  |   0.573s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.rem_distinct0.smt2                             |  20.188s  |  20.188s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.rem_distinct1.smt2                             |  20.188s  |  20.188s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.rem_fp.geq0.smt2                               |  20.180s  |  20.180s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.rem_fp.isInfinite0.smt2                        |  20.208s  |  20.208s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.rem_fp.isInfinite1.smt2                        |  20.223s  |  20.223s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.rem_fp.isNaN0.smt2                             |  20.204s  |  20.204s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.rem_fp.isNaN1.smt2                             |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.rem_fp.isNegative0.smt2                        |  20.224s  |  20.224s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.rem_fp.isNegative1.smt2                        |  20.148s  |  20.148s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.rem_fp.isNormal0.smt2                          |  20.188s  |  20.188s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.rem_fp.isNormal1.smt2                          |  20.180s  |  20.180s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.rem_fp.isPositive0.smt2                        |  20.180s  |  20.180s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.rem_fp.isPositive1.smt2                        |  20.186s  |  20.186s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.rem_fp.isSubnormal0.smt2                       |  20.199s  |  20.199s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.rem_fp.isSubnormal1.smt2                       |  20.198s  |  20.198s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.rem_fp.isZero0.smt2                            |  20.159s  |  20.159s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.rem_fp.isZero1.smt2                            |  20.204s  |  20.204s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.rem_fp.leq0.smt2                               |  20.338s  |  20.338s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.roundToIntegral_distinct.smt2                  |   0.304s  |   0.304s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.roundToIntegral_fp.geq.smt2                    |   1.789s  |   1.789s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.roundToIntegral_fp.gt.smt2                     |   2.716s  |   2.716s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.roundToIntegral_fp.isInfinite.smt2             |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.roundToIntegral_fp.isNaN.smt2                  |   0.342s  |   0.342s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.roundToIntegral_fp.isNegative.smt2             |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.roundToIntegral_fp.isNormal.smt2               |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.roundToIntegral_fp.isPositive.smt2             |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.roundToIntegral_fp.isSubnormal.smt2            |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.roundToIntegral_fp.isZero.smt2                 |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.roundToIntegral_fp.leq.smt2                    |   0.316s  |   0.316s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.roundToIntegral_fp.lt.smt2                     |   0.909s  |   0.909s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sqrt_distinct.smt2                             |  20.084s  |  20.084s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sqrt_fp.geq.smt2                               |  20.224s  |  20.224s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sqrt_fp.gt.smt2                                |  20.090s  |  20.090s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sqrt_fp.isInfinite.smt2                        |  20.080s  |  20.080s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sqrt_fp.isNaN.smt2                             |  20.127s  |  20.127s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sqrt_fp.isNegative.smt2                        |   3.666s  |   3.666s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sqrt_fp.isNormal.smt2                          |  20.068s  |  20.068s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sqrt_fp.isPositive.smt2                        |  20.159s  |  20.159s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sqrt_fp.isSubnormal.smt2                       |  20.177s  |  20.177s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sqrt_fp.isZero.smt2                            |  20.100s  |  20.100s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sqrt_fp.leq.smt2                               |  20.108s  |  20.108s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sqrt_fp.lt.smt2                                |  20.272s  |  20.272s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sub_distinct0.smt2                             |   1.713s  |   1.713s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sub_distinct1.smt2                             |   4.863s  |   4.863s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sub_fp.geq0.smt2                               |   5.856s  |   5.856s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sub_fp.geq1.smt2                               |   8.412s  |   8.412s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sub_fp.gt0.smt2                                |   0.777s  |   0.777s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sub_fp.gt1.smt2                                |  13.597s  |  13.597s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sub_fp.isInfinite0.smt2                        |   0.430s  |   0.430s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sub_fp.isInfinite1.smt2                        |   1.302s  |   1.302s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sub_fp.isNaN0.smt2                             |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sub_fp.isNaN1.smt2                             |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sub_fp.isNegative0.smt2                        |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sub_fp.isNegative1.smt2                        |   0.981s  |   0.981s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sub_fp.isNormal0.smt2                          |   8.734s  |   8.734s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sub_fp.isNormal1.smt2                          |   3.812s  |   3.812s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sub_fp.isPositive0.smt2                        |   0.475s  |   0.475s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sub_fp.isPositive1.smt2                        |   0.821s  |   0.821s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sub_fp.isSubnormal0.smt2                       |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sub_fp.isSubnormal1.smt2                       |  20.069s  |  20.069s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sub_fp.isZero0.smt2                            |   0.641s  |   0.641s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sub_fp.isZero1.smt2                            |   5.481s  |   5.481s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sub_fp.leq0.smt2                               |   0.935s  |   0.935s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sub_fp.leq1.smt2                               |   3.590s  |   3.590s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sub_fp.lt0.smt2                                |   1.580s  |   1.580s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/11_53_RTZ_fp.sub_fp.lt1.smt2                                |   5.750s  |   5.750s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.abs_distinct.smt2                                |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.abs_fp.geq.smt2                                  |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.abs_fp.gt.smt2                                   |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.abs_fp.isInfinite.smt2                           |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.abs_fp.isNaN.smt2                                |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.abs_fp.isNegative.smt2                           |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.abs_fp.isNormal.smt2                             |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.abs_fp.isPositive.smt2                           |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.abs_fp.isSubnormal.smt2                          |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.abs_fp.isZero.smt2                               |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.abs_fp.leq.smt2                                  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.abs_fp.lt.smt2                                   |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.add_distinct.smt2                                |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.add_fp.geq.smt2                                  |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.add_fp.gt.smt2                                   |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.add_fp.isInfinite.smt2                           |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.add_fp.isNaN.smt2                                |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.add_fp.isNegative.smt2                           |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.add_fp.isNormal.smt2                             |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.add_fp.isPositive.smt2                           |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.add_fp.isSubnormal.smt2                          |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.add_fp.isZero.smt2                               |  20.047s  |  20.047s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.add_fp.leq.smt2                                  |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.add_fp.lt.smt2                                   |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.div_distinct0.smt2                               |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.div_distinct1.smt2                               |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.div_fp.geq0.smt2                                 |   0.585s  |   0.585s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.div_fp.geq1.smt2                                 |   0.301s  |   0.301s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.div_fp.gt0.smt2                                  |   2.836s  |   2.836s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.div_fp.gt1.smt2                                  |   0.376s  |   0.376s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.div_fp.isInfinite0.smt2                          |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.div_fp.isInfinite1.smt2                          |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.div_fp.isNaN0.smt2                               |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.div_fp.isNaN1.smt2                               |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.div_fp.isNegative0.smt2                          |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.div_fp.isNegative1.smt2                          |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.div_fp.isNormal0.smt2                            |   0.402s  |   0.402s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.div_fp.isNormal1.smt2                            |   0.444s  |   0.444s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.div_fp.isPositive0.smt2                          |   0.267s  |   0.267s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.div_fp.isPositive1.smt2                          |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.div_fp.isSubnormal0.smt2                         |   1.091s  |   1.091s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.div_fp.isSubnormal1.smt2                         |   2.856s  |   2.856s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.div_fp.isZero0.smt2                              |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.div_fp.isZero1.smt2                              |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.div_fp.leq0.smt2                                 |   0.591s  |   0.591s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.div_fp.leq1.smt2                                 |   0.273s  |   0.273s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.div_fp.lt0.smt2                                  |   0.570s  |   0.570s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.div_fp.lt1.smt2                                  |   0.303s  |   0.303s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.fma_fp.isInfinite0.smt2                          |   0.322s  |   0.322s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.fma_fp.isInfinite2.smt2                          |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.fma_fp.isNaN0.smt2                               |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.fma_fp.isNaN2.smt2                               |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.fma_fp.isNegative0.smt2                          |   1.453s  |   1.453s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.fma_fp.isNegative2.smt2                          |   0.725s  |   0.725s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.fma_fp.isNormal0.smt2                            |   6.392s  |   6.392s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.fma_fp.isNormal2.smt2                            |   2.639s  |   2.639s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.fma_fp.isPositive0.smt2                          |   1.978s  |   1.978s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.fma_fp.isPositive2.smt2                          |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.fma_fp.isZero0.smt2                              |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.fma_fp.isZero2.smt2                              |   7.447s  |   7.447s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.mul_distinct.smt2                                |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.mul_fp.geq.smt2                                  |   0.728s  |   0.728s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.mul_fp.gt.smt2                                   |   0.329s  |   0.329s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.mul_fp.isInfinite.smt2                           |   0.267s  |   0.267s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.mul_fp.isNaN.smt2                                |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.mul_fp.isNegative.smt2                           |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.mul_fp.isNormal.smt2                             |   0.417s  |   0.417s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.mul_fp.isPositive.smt2                           |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.mul_fp.isSubnormal.smt2                          |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.mul_fp.isZero.smt2                               |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.mul_fp.leq.smt2                                  |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.mul_fp.lt.smt2                                   |   0.321s  |   0.321s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.neg_distinct.smt2                                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.neg_fp.geq.smt2                                  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.neg_fp.gt.smt2                                   |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.neg_fp.isInfinite.smt2                           |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.neg_fp.isNaN.smt2                                |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.neg_fp.isNegative.smt2                           |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.neg_fp.isNormal.smt2                             |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.neg_fp.isPositive.smt2                           |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.neg_fp.isSubnormal.smt2                          |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.neg_fp.isZero.smt2                               |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.neg_fp.leq.smt2                                  |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.neg_fp.lt.smt2                                   |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.rem_distinct0.smt2                               |   0.433s  |   0.433s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.rem_distinct1.smt2                               |   0.447s  |   0.447s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.rem_fp.geq0.smt2                                 |  11.767s  |  11.767s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.rem_fp.isInfinite0.smt2                          |   0.556s  |   0.556s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.rem_fp.isInfinite1.smt2                          |   0.577s  |   0.577s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.rem_fp.isNaN0.smt2                               |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.rem_fp.isNaN1.smt2                               |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.rem_fp.isNegative0.smt2                          |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.rem_fp.isNegative1.smt2                          |  11.744s  |  11.744s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.rem_fp.isNormal0.smt2                            |   1.465s  |   1.465s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.rem_fp.isNormal1.smt2                            |   2.884s  |   2.884s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.rem_fp.isPositive0.smt2                          |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.rem_fp.isPositive1.smt2                          |  15.362s  |  15.362s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.rem_fp.isSubnormal0.smt2                         |   2.337s  |   2.337s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.rem_fp.isSubnormal1.smt2                         |   1.508s  |   1.508s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.rem_fp.isZero0.smt2                              |   0.283s  |   0.283s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.rem_fp.isZero1.smt2                              |   1.327s  |   1.327s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.rem_fp.leq0.smt2                                 |   7.442s  |   7.442s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.roundToIntegral_distinct.smt2                    |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.roundToIntegral_fp.geq.smt2                      |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.roundToIntegral_fp.gt.smt2                       |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.roundToIntegral_fp.isInfinite.smt2               |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.roundToIntegral_fp.isNaN.smt2                    |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.roundToIntegral_fp.isNegative.smt2               |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.roundToIntegral_fp.isNormal.smt2                 |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.roundToIntegral_fp.isPositive.smt2               |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.roundToIntegral_fp.isSubnormal.smt2              |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.roundToIntegral_fp.isZero.smt2                   |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.roundToIntegral_fp.leq.smt2                      |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.roundToIntegral_fp.lt.smt2                       |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sqrt_distinct.smt2                               |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sqrt_fp.geq.smt2                                 |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sqrt_fp.gt.smt2                                  |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sqrt_fp.isInfinite.smt2                          |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sqrt_fp.isNaN.smt2                               |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sqrt_fp.isNegative.smt2                          |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sqrt_fp.isNormal.smt2                            |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sqrt_fp.isPositive.smt2                          |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sqrt_fp.isSubnormal.smt2                         |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sqrt_fp.isZero.smt2                              |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sqrt_fp.leq.smt2                                 |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sqrt_fp.lt.smt2                                  |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sub_distinct0.smt2                               |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sub_distinct1.smt2                               |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sub_fp.geq0.smt2                                 |   0.370s  |   0.370s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sub_fp.geq1.smt2                                 |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sub_fp.gt0.smt2                                  |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sub_fp.gt1.smt2                                  |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sub_fp.isInfinite0.smt2                          |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sub_fp.isInfinite1.smt2                          |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sub_fp.isNaN0.smt2                               |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sub_fp.isNaN1.smt2                               |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sub_fp.isNegative0.smt2                          |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sub_fp.isNegative1.smt2                          |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sub_fp.isNormal0.smt2                            |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sub_fp.isNormal1.smt2                            |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sub_fp.isPositive0.smt2                          |   0.274s  |   0.274s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sub_fp.isPositive1.smt2                          |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sub_fp.isSubnormal0.smt2                         |   2.849s  |   2.849s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sub_fp.isSubnormal1.smt2                         |   1.025s  |   1.025s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sub_fp.isZero0.smt2                              |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sub_fp.isZero1.smt2                              |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sub_fp.leq0.smt2                                 |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sub_fp.leq1.smt2                                 |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sub_fp.lt0.smt2                                  |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNA_fp.sub_fp.lt1.smt2                                  |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.abs_distinct.smt2                                |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.abs_fp.geq.smt2                                  |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.abs_fp.gt.smt2                                   |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.abs_fp.isInfinite.smt2                           |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.abs_fp.isNaN.smt2                                |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.abs_fp.isNegative.smt2                           |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.abs_fp.isNormal.smt2                             |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.abs_fp.isPositive.smt2                           |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.abs_fp.isSubnormal.smt2                          |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.abs_fp.isZero.smt2                               |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.abs_fp.leq.smt2                                  |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.abs_fp.lt.smt2                                   |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.add_distinct.smt2                                |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.add_fp.geq.smt2                                  |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.add_fp.gt.smt2                                   |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.add_fp.isInfinite.smt2                           |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.add_fp.isNaN.smt2                                |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.add_fp.isNegative.smt2                           |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.add_fp.isNormal.smt2                             |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.add_fp.isPositive.smt2                           |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.add_fp.isSubnormal.smt2                          |  20.152s  |  20.152s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.add_fp.isZero.smt2                               |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.add_fp.leq.smt2                                  |   0.352s  |   0.352s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.add_fp.lt.smt2                                   |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.div_distinct0.smt2                               |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.div_distinct1.smt2                               |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.div_fp.geq0.smt2                                 |   0.389s  |   0.389s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.div_fp.geq1.smt2                                 |   0.387s  |   0.387s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.div_fp.gt0.smt2                                  |   0.427s  |   0.427s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.div_fp.gt1.smt2                                  |   0.288s  |   0.288s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.div_fp.isInfinite0.smt2                          |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.div_fp.isInfinite1.smt2                          |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.div_fp.isNaN0.smt2                               |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.div_fp.isNaN1.smt2                               |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.div_fp.isNegative0.smt2                          |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.div_fp.isNegative1.smt2                          |   0.295s  |   0.295s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.div_fp.isNormal0.smt2                            |   0.423s  |   0.423s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.div_fp.isNormal1.smt2                            |   0.619s  |   0.619s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.div_fp.isPositive0.smt2                          |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.div_fp.isPositive1.smt2                          |   0.369s  |   0.369s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.div_fp.isSubnormal0.smt2                         |   1.049s  |   1.049s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.div_fp.isSubnormal1.smt2                         |   1.083s  |   1.083s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.div_fp.isZero0.smt2                              |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.div_fp.isZero1.smt2                              |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.div_fp.leq0.smt2                                 |   0.774s  |   0.774s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.div_fp.leq1.smt2                                 |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.div_fp.lt0.smt2                                  |   0.591s  |   0.591s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.div_fp.lt1.smt2                                  |   0.332s  |   0.332s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.fma_fp.isInfinite0.smt2                          |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.fma_fp.isInfinite2.smt2                          |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.fma_fp.isNaN0.smt2                               |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.fma_fp.isNaN2.smt2                               |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.fma_fp.isNegative0.smt2                          |   3.027s  |   3.027s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.fma_fp.isNegative2.smt2                          |   0.975s  |   0.975s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.fma_fp.isNormal0.smt2                            |  10.054s  |  10.054s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.fma_fp.isNormal2.smt2                            |   2.956s  |   2.956s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.fma_fp.isPositive0.smt2                          |   1.111s  |   1.111s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.fma_fp.isPositive2.smt2                          |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.fma_fp.isZero0.smt2                              |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.fma_fp.isZero2.smt2                              |   8.797s  |   8.797s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.mul_distinct.smt2                                |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.mul_fp.geq.smt2                                  |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.mul_fp.gt.smt2                                   |   0.997s  |   0.997s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.mul_fp.isInfinite.smt2                           |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.mul_fp.isNaN.smt2                                |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.mul_fp.isNegative.smt2                           |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.mul_fp.isNormal.smt2                             |   0.455s  |   0.455s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.mul_fp.isPositive.smt2                           |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.mul_fp.isSubnormal.smt2                          |   0.453s  |   0.453s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.mul_fp.isZero.smt2                               |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.mul_fp.leq.smt2                                  |   0.534s  |   0.534s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.mul_fp.lt.smt2                                   |   0.506s  |   0.506s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.neg_distinct.smt2                                |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.neg_fp.geq.smt2                                  |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.neg_fp.gt.smt2                                   |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.neg_fp.isInfinite.smt2                           |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.neg_fp.isNaN.smt2                                |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.neg_fp.isNegative.smt2                           |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.neg_fp.isNormal.smt2                             |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.neg_fp.isPositive.smt2                           |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.neg_fp.isSubnormal.smt2                          |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.neg_fp.isZero.smt2                               |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.neg_fp.leq.smt2                                  |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.neg_fp.lt.smt2                                   |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.rem_distinct0.smt2                               |   0.463s  |   0.463s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.rem_distinct1.smt2                               |   0.435s  |   0.435s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.rem_fp.geq0.smt2                                 |  12.327s  |  12.327s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.rem_fp.isInfinite0.smt2                          |   0.523s  |   0.523s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.rem_fp.isInfinite1.smt2                          |   0.565s  |   0.565s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.rem_fp.isNaN0.smt2                               |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.rem_fp.isNaN1.smt2                               |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.rem_fp.isNegative0.smt2                          |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.rem_fp.isNegative1.smt2                          |  13.707s  |  13.707s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.rem_fp.isNormal0.smt2                            |   2.641s  |   2.641s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.rem_fp.isNormal1.smt2                            |   2.645s  |   2.645s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.rem_fp.isPositive0.smt2                          |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.rem_fp.isPositive1.smt2                          |  15.443s  |  15.443s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.rem_fp.isSubnormal0.smt2                         |   2.267s  |   2.267s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.rem_fp.isSubnormal1.smt2                         |   1.797s  |   1.797s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.rem_fp.isZero0.smt2                              |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.rem_fp.isZero1.smt2                              |   1.459s  |   1.459s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.rem_fp.leq0.smt2                                 |   6.897s  |   6.897s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.roundToIntegral_distinct.smt2                    |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.roundToIntegral_fp.geq.smt2                      |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.roundToIntegral_fp.gt.smt2                       |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.roundToIntegral_fp.isInfinite.smt2               |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.roundToIntegral_fp.isNaN.smt2                    |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.roundToIntegral_fp.isNegative.smt2               |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.roundToIntegral_fp.isNormal.smt2                 |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.roundToIntegral_fp.isPositive.smt2               |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.roundToIntegral_fp.isSubnormal.smt2              |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.roundToIntegral_fp.isZero.smt2                   |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.roundToIntegral_fp.leq.smt2                      |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.roundToIntegral_fp.lt.smt2                       |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sqrt_distinct.smt2                               |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sqrt_fp.geq.smt2                                 |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sqrt_fp.gt.smt2                                  |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sqrt_fp.isInfinite.smt2                          |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sqrt_fp.isNaN.smt2                               |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sqrt_fp.isNegative.smt2                          |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sqrt_fp.isNormal.smt2                            |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sqrt_fp.isPositive.smt2                          |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sqrt_fp.isSubnormal.smt2                         |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sqrt_fp.isZero.smt2                              |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sqrt_fp.leq.smt2                                 |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sqrt_fp.lt.smt2                                  |   0.286s  |   0.286s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sub_distinct0.smt2                               |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sub_distinct1.smt2                               |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sub_fp.geq0.smt2                                 |   0.415s  |   0.415s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sub_fp.geq1.smt2                                 |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sub_fp.gt0.smt2                                  |   0.426s  |   0.426s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sub_fp.gt1.smt2                                  |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sub_fp.isInfinite0.smt2                          |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sub_fp.isInfinite1.smt2                          |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sub_fp.isNaN0.smt2                               |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sub_fp.isNaN1.smt2                               |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sub_fp.isNegative0.smt2                          |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sub_fp.isNegative1.smt2                          |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sub_fp.isNormal0.smt2                            |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sub_fp.isNormal1.smt2                            |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sub_fp.isPositive0.smt2                          |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sub_fp.isPositive1.smt2                          |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sub_fp.isSubnormal0.smt2                         |   2.426s  |   2.426s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sub_fp.isSubnormal1.smt2                         |   1.849s  |   1.849s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sub_fp.isZero0.smt2                              |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sub_fp.isZero1.smt2                              |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sub_fp.leq0.smt2                                 |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sub_fp.leq1.smt2                                 |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sub_fp.lt0.smt2                                  |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RNE_fp.sub_fp.lt1.smt2                                  |   0.365s  |   0.365s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.abs_distinct.smt2                                |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.abs_fp.geq.smt2                                  |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.abs_fp.gt.smt2                                   |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.abs_fp.isInfinite.smt2                           |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.abs_fp.isNaN.smt2                                |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.abs_fp.isNegative.smt2                           |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.abs_fp.isNormal.smt2                             |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.abs_fp.isPositive.smt2                           |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.abs_fp.isSubnormal.smt2                          |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.abs_fp.isZero.smt2                               |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.abs_fp.leq.smt2                                  |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.abs_fp.lt.smt2                                   |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.add_distinct.smt2                                |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.add_fp.geq.smt2                                  |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.add_fp.gt.smt2                                   |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.add_fp.isInfinite.smt2                           |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.add_fp.isNaN.smt2                                |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.add_fp.isNegative.smt2                           |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.add_fp.isNormal.smt2                             |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.add_fp.isPositive.smt2                           |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.add_fp.isSubnormal.smt2                          |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.add_fp.isZero.smt2                               |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.add_fp.leq.smt2                                  |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.add_fp.lt.smt2                                   |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.div_distinct0.smt2                               |   0.287s  |   0.287s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.div_distinct1.smt2                               |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.div_fp.geq0.smt2                                 |   0.670s  |   0.670s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.div_fp.geq1.smt2                                 |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.div_fp.gt0.smt2                                  |   0.447s  |   0.447s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.div_fp.gt1.smt2                                  |   0.455s  |   0.455s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.div_fp.isInfinite0.smt2                          |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.div_fp.isInfinite1.smt2                          |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.div_fp.isNaN0.smt2                               |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.div_fp.isNaN1.smt2                               |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.div_fp.isNegative0.smt2                          |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.div_fp.isNegative1.smt2                          |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.div_fp.isNormal0.smt2                            |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.div_fp.isNormal1.smt2                            |   0.457s  |   0.457s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.div_fp.isPositive0.smt2                          |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.div_fp.isPositive1.smt2                          |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.div_fp.isSubnormal0.smt2                         |   1.739s  |   1.739s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.div_fp.isSubnormal1.smt2                         |   1.026s  |   1.026s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.div_fp.isZero0.smt2                              |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.div_fp.isZero1.smt2                              |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.div_fp.leq0.smt2                                 |   0.463s  |   0.463s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.div_fp.leq1.smt2                                 |   0.287s  |   0.287s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.div_fp.lt0.smt2                                  |   0.645s  |   0.645s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.div_fp.lt1.smt2                                  |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.fma_fp.isInfinite0.smt2                          |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.fma_fp.isInfinite2.smt2                          |   0.424s  |   0.424s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.fma_fp.isNaN0.smt2                               |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.fma_fp.isNaN2.smt2                               |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.fma_fp.isNegative0.smt2                          |   4.776s  |   4.776s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.fma_fp.isNegative2.smt2                          |   0.994s  |   0.994s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.fma_fp.isNormal0.smt2                            |   9.030s  |   9.030s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.fma_fp.isNormal2.smt2                            |   2.976s  |   2.976s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.fma_fp.isPositive0.smt2                          |   0.378s  |   0.378s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.fma_fp.isPositive2.smt2                          |   1.262s  |   1.262s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.fma_fp.isZero0.smt2                              |  20.095s  |  20.095s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.fma_fp.isZero2.smt2                              |   8.716s  |   8.716s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.mul_distinct.smt2                                |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.mul_fp.geq.smt2                                  |   0.894s  |   0.894s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.mul_fp.gt.smt2                                   |   0.503s  |   0.503s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.mul_fp.isInfinite.smt2                           |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.mul_fp.isNaN.smt2                                |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.mul_fp.isNegative.smt2                           |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.mul_fp.isNormal.smt2                             |   0.441s  |   0.441s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.mul_fp.isPositive.smt2                           |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.mul_fp.isSubnormal.smt2                          |   0.387s  |   0.387s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.mul_fp.isZero.smt2                               |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.mul_fp.leq.smt2                                  |   0.274s  |   0.274s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.mul_fp.lt.smt2                                   |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.neg_distinct.smt2                                |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.neg_fp.geq.smt2                                  |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.neg_fp.gt.smt2                                   |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.neg_fp.isInfinite.smt2                           |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.neg_fp.isNaN.smt2                                |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.neg_fp.isNegative.smt2                           |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.neg_fp.isNormal.smt2                             |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.neg_fp.isPositive.smt2                           |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.neg_fp.isSubnormal.smt2                          |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.neg_fp.isZero.smt2                               |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.neg_fp.leq.smt2                                  |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.neg_fp.lt.smt2                                   |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.rem_distinct0.smt2                               |   0.506s  |   0.506s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.rem_distinct1.smt2                               |   0.413s  |   0.413s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.rem_fp.geq0.smt2                                 |   9.596s  |   9.596s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.rem_fp.isInfinite0.smt2                          |   0.556s  |   0.556s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.rem_fp.isInfinite1.smt2                          |   0.396s  |   0.396s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.rem_fp.isNaN0.smt2                               |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.rem_fp.isNaN1.smt2                               |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.rem_fp.isNegative0.smt2                          |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.rem_fp.isNegative1.smt2                          |  12.357s  |  12.357s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.rem_fp.isNormal0.smt2                            |   2.508s  |   2.508s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.rem_fp.isNormal1.smt2                            |   3.091s  |   3.091s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.rem_fp.isPositive0.smt2                          |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.rem_fp.isPositive1.smt2                          |  15.842s  |  15.842s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.rem_fp.isSubnormal0.smt2                         |   2.138s  |   2.138s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.rem_fp.isSubnormal1.smt2                         |   1.659s  |   1.659s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.rem_fp.isZero0.smt2                              |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.rem_fp.isZero1.smt2                              |   1.106s  |   1.106s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.rem_fp.leq0.smt2                                 |   7.012s  |   7.012s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.roundToIntegral_distinct.smt2                    |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.roundToIntegral_fp.geq.smt2                      |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.roundToIntegral_fp.gt.smt2                       |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.roundToIntegral_fp.isInfinite.smt2               |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.roundToIntegral_fp.isNaN.smt2                    |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.roundToIntegral_fp.isNegative.smt2               |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.roundToIntegral_fp.isNormal.smt2                 |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.roundToIntegral_fp.isPositive.smt2               |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.roundToIntegral_fp.isSubnormal.smt2              |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.roundToIntegral_fp.isZero.smt2                   |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.roundToIntegral_fp.leq.smt2                      |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.roundToIntegral_fp.lt.smt2                       |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sqrt_distinct.smt2                               |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sqrt_fp.geq.smt2                                 |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sqrt_fp.gt.smt2                                  |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sqrt_fp.isInfinite.smt2                          |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sqrt_fp.isNaN.smt2                               |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sqrt_fp.isNegative.smt2                          |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sqrt_fp.isNormal.smt2                            |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sqrt_fp.isPositive.smt2                          |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sqrt_fp.isSubnormal.smt2                         |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sqrt_fp.isZero.smt2                              |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sqrt_fp.leq.smt2                                 |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sqrt_fp.lt.smt2                                  |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sub_distinct0.smt2                               |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sub_distinct1.smt2                               |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sub_fp.geq0.smt2                                 |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sub_fp.geq1.smt2                                 |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sub_fp.gt0.smt2                                  |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sub_fp.gt1.smt2                                  |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sub_fp.isInfinite0.smt2                          |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sub_fp.isInfinite1.smt2                          |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sub_fp.isNaN0.smt2                               |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sub_fp.isNaN1.smt2                               |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sub_fp.isNegative0.smt2                          |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sub_fp.isNegative1.smt2                          |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sub_fp.isNormal0.smt2                            |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sub_fp.isNormal1.smt2                            |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sub_fp.isPositive0.smt2                          |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sub_fp.isPositive1.smt2                          |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sub_fp.isSubnormal0.smt2                         |   1.337s  |   1.337s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sub_fp.isSubnormal1.smt2                         |   1.367s  |   1.367s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sub_fp.isZero0.smt2                              |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sub_fp.isZero1.smt2                              |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sub_fp.leq0.smt2                                 |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sub_fp.leq1.smt2                                 |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sub_fp.lt0.smt2                                  |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTN_fp.sub_fp.lt1.smt2                                  |   0.358s  |   0.358s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.abs_distinct.smt2                                |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.abs_fp.geq.smt2                                  |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.abs_fp.gt.smt2                                   |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.abs_fp.isInfinite.smt2                           |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.abs_fp.isNaN.smt2                                |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.abs_fp.isNegative.smt2                           |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.abs_fp.isNormal.smt2                             |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.abs_fp.isPositive.smt2                           |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.abs_fp.isSubnormal.smt2                          |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.abs_fp.isZero.smt2                               |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.abs_fp.leq.smt2                                  |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.abs_fp.lt.smt2                                   |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.add_distinct.smt2                                |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.add_fp.geq.smt2                                  |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.add_fp.gt.smt2                                   |   0.705s  |   0.705s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.add_fp.isInfinite.smt2                           |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.add_fp.isNaN.smt2                                |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.add_fp.isNegative.smt2                           |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.add_fp.isNormal.smt2                             |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.add_fp.isPositive.smt2                           |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.add_fp.isSubnormal.smt2                          |  19.962s  |  19.962s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.add_fp.isZero.smt2                               |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.add_fp.leq.smt2                                  |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.add_fp.lt.smt2                                   |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.div_distinct0.smt2                               |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.div_distinct1.smt2                               |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.div_fp.geq0.smt2                                 |   1.033s  |   1.033s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.div_fp.geq1.smt2                                 |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.div_fp.gt0.smt2                                  |   0.303s  |   0.303s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.div_fp.gt1.smt2                                  |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.div_fp.isInfinite0.smt2                          |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.div_fp.isInfinite1.smt2                          |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.div_fp.isNaN0.smt2                               |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.div_fp.isNaN1.smt2                               |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.div_fp.isNegative0.smt2                          |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.div_fp.isNegative1.smt2                          |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.div_fp.isNormal0.smt2                            |   0.371s  |   0.371s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.div_fp.isNormal1.smt2                            |   0.356s  |   0.356s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.div_fp.isPositive0.smt2                          |   0.435s  |   0.435s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.div_fp.isPositive1.smt2                          |   0.257s  |   0.257s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.div_fp.isSubnormal0.smt2                         |   1.186s  |   1.186s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.div_fp.isSubnormal1.smt2                         |   1.042s  |   1.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.div_fp.isZero0.smt2                              |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.div_fp.isZero1.smt2                              |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.div_fp.leq0.smt2                                 |   0.438s  |   0.438s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.div_fp.leq1.smt2                                 |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.div_fp.lt0.smt2                                  |   1.143s  |   1.143s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.div_fp.lt1.smt2                                  |   0.479s  |   0.479s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.fma_fp.isInfinite0.smt2                          |   0.503s  |   0.503s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.fma_fp.isInfinite2.smt2                          |   0.284s  |   0.284s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.fma_fp.isNaN0.smt2                               |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.fma_fp.isNaN2.smt2                               |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.fma_fp.isNegative0.smt2                          |   1.881s  |   1.881s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.fma_fp.isNegative2.smt2                          |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.fma_fp.isNormal0.smt2                            |   9.401s  |   9.401s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.fma_fp.isNormal2.smt2                            |   3.983s  |   3.983s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.fma_fp.isPositive0.smt2                          |   5.307s  |   5.307s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.fma_fp.isPositive2.smt2                          |   1.885s  |   1.885s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.fma_fp.isZero0.smt2                              |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.fma_fp.isZero2.smt2                              |   8.110s  |   8.110s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.mul_distinct.smt2                                |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.mul_fp.geq.smt2                                  |   1.171s  |   1.171s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.mul_fp.gt.smt2                                   |   1.037s  |   1.037s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.mul_fp.isInfinite.smt2                           |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.mul_fp.isNaN.smt2                                |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.mul_fp.isNegative.smt2                           |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.mul_fp.isNormal.smt2                             |   0.347s  |   0.347s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.mul_fp.isPositive.smt2                           |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.mul_fp.isSubnormal.smt2                          |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.mul_fp.isZero.smt2                               |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.mul_fp.leq.smt2                                  |   1.004s  |   1.004s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.mul_fp.lt.smt2                                   |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.neg_distinct.smt2                                |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.neg_fp.geq.smt2                                  |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.neg_fp.gt.smt2                                   |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.neg_fp.isInfinite.smt2                           |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.neg_fp.isNaN.smt2                                |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.neg_fp.isNegative.smt2                           |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.neg_fp.isNormal.smt2                             |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.neg_fp.isPositive.smt2                           |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.neg_fp.isSubnormal.smt2                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.neg_fp.isZero.smt2                               |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.neg_fp.leq.smt2                                  |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.neg_fp.lt.smt2                                   |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.rem_distinct0.smt2                               |   0.412s  |   0.412s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.rem_distinct1.smt2                               |   0.437s  |   0.437s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.rem_fp.geq0.smt2                                 |  11.823s  |  11.823s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.rem_fp.isInfinite0.smt2                          |   0.527s  |   0.527s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.rem_fp.isInfinite1.smt2                          |   0.589s  |   0.589s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.rem_fp.isNaN0.smt2                               |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.rem_fp.isNaN1.smt2                               |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.rem_fp.isNegative0.smt2                          |   0.271s  |   0.271s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.rem_fp.isNegative1.smt2                          |  11.862s  |  11.862s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.rem_fp.isNormal0.smt2                            |   2.892s  |   2.892s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.rem_fp.isNormal1.smt2                            |   3.287s  |   3.287s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.rem_fp.isPositive0.smt2                          |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.rem_fp.isPositive1.smt2                          |  17.181s  |  17.181s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.rem_fp.isSubnormal0.smt2                         |   2.330s  |   2.330s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.rem_fp.isSubnormal1.smt2                         |   0.988s  |   0.988s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.rem_fp.isZero0.smt2                              |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.rem_fp.isZero1.smt2                              |   1.583s  |   1.583s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.rem_fp.leq0.smt2                                 |   7.930s  |   7.930s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.roundToIntegral_distinct.smt2                    |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.roundToIntegral_fp.geq.smt2                      |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.roundToIntegral_fp.gt.smt2                       |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.roundToIntegral_fp.isInfinite.smt2               |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.roundToIntegral_fp.isNaN.smt2                    |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.roundToIntegral_fp.isNegative.smt2               |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.roundToIntegral_fp.isNormal.smt2                 |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.roundToIntegral_fp.isPositive.smt2               |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.roundToIntegral_fp.isSubnormal.smt2              |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.roundToIntegral_fp.isZero.smt2                   |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.roundToIntegral_fp.leq.smt2                      |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.roundToIntegral_fp.lt.smt2                       |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sqrt_distinct.smt2                               |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sqrt_fp.geq.smt2                                 |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sqrt_fp.gt.smt2                                  |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sqrt_fp.isInfinite.smt2                          |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sqrt_fp.isNaN.smt2                               |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sqrt_fp.isNegative.smt2                          |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sqrt_fp.isNormal.smt2                            |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sqrt_fp.isPositive.smt2                          |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sqrt_fp.isSubnormal.smt2                         |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sqrt_fp.isZero.smt2                              |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sqrt_fp.leq.smt2                                 |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sqrt_fp.lt.smt2                                  |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sub_distinct0.smt2                               |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sub_distinct1.smt2                               |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sub_fp.geq0.smt2                                 |   0.315s  |   0.315s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sub_fp.geq1.smt2                                 |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sub_fp.gt0.smt2                                  |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sub_fp.gt1.smt2                                  |   0.390s  |   0.390s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sub_fp.isInfinite0.smt2                          |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sub_fp.isInfinite1.smt2                          |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sub_fp.isNaN0.smt2                               |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sub_fp.isNaN1.smt2                               |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sub_fp.isNegative0.smt2                          |   0.297s  |   0.297s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sub_fp.isNegative1.smt2                          |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sub_fp.isNormal0.smt2                            |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sub_fp.isNormal1.smt2                            |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sub_fp.isPositive0.smt2                          |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sub_fp.isPositive1.smt2                          |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sub_fp.isSubnormal0.smt2                         |   1.622s  |   1.622s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sub_fp.isSubnormal1.smt2                         |   3.285s  |   3.285s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sub_fp.isZero0.smt2                              |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sub_fp.isZero1.smt2                              |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sub_fp.leq0.smt2                                 |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sub_fp.leq1.smt2                                 |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sub_fp.lt0.smt2                                  |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTP_fp.sub_fp.lt1.smt2                                  |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.abs_distinct.smt2                                |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.abs_fp.geq.smt2                                  |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.abs_fp.gt.smt2                                   |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.abs_fp.isInfinite.smt2                           |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.abs_fp.isNaN.smt2                                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.abs_fp.isNegative.smt2                           |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.abs_fp.isNormal.smt2                             |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.abs_fp.isPositive.smt2                           |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.abs_fp.isSubnormal.smt2                          |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.abs_fp.isZero.smt2                               |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.abs_fp.leq.smt2                                  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.abs_fp.lt.smt2                                   |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.add_distinct.smt2                                |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.add_fp.geq.smt2                                  |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.add_fp.gt.smt2                                   |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.add_fp.isInfinite.smt2                           |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.add_fp.isNaN.smt2                                |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.add_fp.isNegative.smt2                           |   0.349s  |   0.349s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.add_fp.isNormal.smt2                             |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.add_fp.isPositive.smt2                           |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.add_fp.isSubnormal.smt2                          |  20.140s  |  20.140s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.add_fp.isZero.smt2                               |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.add_fp.leq.smt2                                  |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.add_fp.lt.smt2                                   |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.div_distinct0.smt2                               |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.div_distinct1.smt2                               |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.div_fp.geq0.smt2                                 |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.div_fp.geq1.smt2                                 |   0.483s  |   0.483s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.div_fp.gt0.smt2                                  |   0.766s  |   0.766s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.div_fp.gt1.smt2                                  |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.div_fp.isInfinite0.smt2                          |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.div_fp.isInfinite1.smt2                          |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.div_fp.isNaN0.smt2                               |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.div_fp.isNaN1.smt2                               |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.div_fp.isNegative0.smt2                          |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.div_fp.isNegative1.smt2                          |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.div_fp.isNormal0.smt2                            |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.div_fp.isNormal1.smt2                            |   0.742s  |   0.742s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.div_fp.isPositive0.smt2                          |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.div_fp.isPositive1.smt2                          |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.div_fp.isSubnormal0.smt2                         |   1.083s  |   1.083s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.div_fp.isSubnormal1.smt2                         |   2.173s  |   2.173s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.div_fp.isZero0.smt2                              |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.div_fp.isZero1.smt2                              |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.div_fp.leq0.smt2                                 |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.div_fp.leq1.smt2                                 |   0.431s  |   0.431s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.div_fp.lt0.smt2                                  |   0.504s  |   0.504s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.div_fp.lt1.smt2                                  |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.fma_fp.isInfinite0.smt2                          |   0.316s  |   0.316s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.fma_fp.isInfinite2.smt2                          |   0.385s  |   0.385s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.fma_fp.isNaN0.smt2                               |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.fma_fp.isNaN2.smt2                               |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.fma_fp.isNegative0.smt2                          |   2.782s  |   2.782s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.fma_fp.isNegative2.smt2                          |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.fma_fp.isNormal0.smt2                            |   6.562s  |   6.562s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.fma_fp.isNormal2.smt2                            |   1.498s  |   1.498s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.fma_fp.isPositive0.smt2                          |   1.277s  |   1.277s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.fma_fp.isPositive2.smt2                          |   0.820s  |   0.820s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.fma_fp.isZero0.smt2                              |  20.084s  |  20.084s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.fma_fp.isZero2.smt2                              |   7.595s  |   7.595s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.mul_distinct.smt2                                |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.mul_fp.geq.smt2                                  |   0.595s  |   0.595s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.mul_fp.gt.smt2                                   |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.mul_fp.isInfinite.smt2                           |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.mul_fp.isNaN.smt2                                |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.mul_fp.isNegative.smt2                           |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.mul_fp.isNormal.smt2                             |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.mul_fp.isPositive.smt2                           |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.mul_fp.isSubnormal.smt2                          |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.mul_fp.isZero.smt2                               |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.mul_fp.leq.smt2                                  |   0.529s  |   0.529s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.mul_fp.lt.smt2                                   |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.neg_distinct.smt2                                |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.neg_fp.geq.smt2                                  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.neg_fp.gt.smt2                                   |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.neg_fp.isInfinite.smt2                           |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.neg_fp.isNaN.smt2                                |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.neg_fp.isNegative.smt2                           |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.neg_fp.isNormal.smt2                             |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.neg_fp.isPositive.smt2                           |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.neg_fp.isSubnormal.smt2                          |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.neg_fp.isZero.smt2                               |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.neg_fp.leq.smt2                                  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.neg_fp.lt.smt2                                   |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.rem_distinct0.smt2                               |   0.444s  |   0.444s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.rem_distinct1.smt2                               |   0.449s  |   0.449s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.rem_fp.geq0.smt2                                 |   9.899s  |   9.899s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.rem_fp.isInfinite0.smt2                          |   0.587s  |   0.587s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.rem_fp.isInfinite1.smt2                          |   0.407s  |   0.407s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.rem_fp.isNaN0.smt2                               |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.rem_fp.isNaN1.smt2                               |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.rem_fp.isNegative0.smt2                          |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.rem_fp.isNegative1.smt2                          |  13.368s  |  13.368s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.rem_fp.isNormal0.smt2                            |   1.946s  |   1.946s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.rem_fp.isNormal1.smt2                            |   2.699s  |   2.699s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.rem_fp.isPositive0.smt2                          |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.rem_fp.isPositive1.smt2                          |  15.228s  |  15.228s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.rem_fp.isSubnormal0.smt2                         |   2.771s  |   2.771s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.rem_fp.isSubnormal1.smt2                         |   1.569s  |   1.569s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.rem_fp.isZero0.smt2                              |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.rem_fp.isZero1.smt2                              |   1.424s  |   1.424s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.rem_fp.leq0.smt2                                 |   7.829s  |   7.829s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.roundToIntegral_distinct.smt2                    |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.roundToIntegral_fp.geq.smt2                      |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.roundToIntegral_fp.gt.smt2                       |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.roundToIntegral_fp.isInfinite.smt2               |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.roundToIntegral_fp.isNaN.smt2                    |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.roundToIntegral_fp.isNegative.smt2               |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.roundToIntegral_fp.isNormal.smt2                 |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.roundToIntegral_fp.isPositive.smt2               |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.roundToIntegral_fp.isSubnormal.smt2              |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.roundToIntegral_fp.isZero.smt2                   |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.roundToIntegral_fp.leq.smt2                      |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.roundToIntegral_fp.lt.smt2                       |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sqrt_distinct.smt2                               |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sqrt_fp.geq.smt2                                 |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sqrt_fp.gt.smt2                                  |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sqrt_fp.isInfinite.smt2                          |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sqrt_fp.isNaN.smt2                               |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sqrt_fp.isNegative.smt2                          |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sqrt_fp.isNormal.smt2                            |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sqrt_fp.isPositive.smt2                          |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sqrt_fp.isSubnormal.smt2                         |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sqrt_fp.isZero.smt2                              |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sqrt_fp.leq.smt2                                 |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sqrt_fp.lt.smt2                                  |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sub_distinct0.smt2                               |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sub_distinct1.smt2                               |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sub_fp.geq0.smt2                                 |   0.315s  |   0.315s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sub_fp.geq1.smt2                                 |   0.241s  |   0.241s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sub_fp.gt0.smt2                                  |   0.363s  |   0.363s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sub_fp.gt1.smt2                                  |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sub_fp.isInfinite0.smt2                          |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sub_fp.isInfinite1.smt2                          |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sub_fp.isNaN0.smt2                               |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sub_fp.isNaN1.smt2                               |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sub_fp.isNegative0.smt2                          |   0.257s  |   0.257s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sub_fp.isNegative1.smt2                          |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sub_fp.isNormal0.smt2                            |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sub_fp.isNormal1.smt2                            |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sub_fp.isPositive0.smt2                          |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sub_fp.isPositive1.smt2                          |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sub_fp.isSubnormal0.smt2                         |   2.185s  |   2.185s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sub_fp.isSubnormal1.smt2                         |   1.631s  |   1.631s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sub_fp.isZero0.smt2                              |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sub_fp.isZero1.smt2                              |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sub_fp.leq0.smt2                                 |   0.377s  |   0.377s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sub_fp.leq1.smt2                                 |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sub_fp.lt0.smt2                                  |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/3_5_RTZ_fp.sub_fp.lt1.smt2                                  |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.abs_distinct.smt2                               |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.abs_fp.geq.smt2                                 |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.abs_fp.gt.smt2                                  |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.abs_fp.isInfinite.smt2                          |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.abs_fp.isNaN.smt2                               |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.abs_fp.isNegative.smt2                          |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.abs_fp.isNormal.smt2                            |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.abs_fp.isPositive.smt2                          |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.abs_fp.isSubnormal.smt2                         |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.abs_fp.isZero.smt2                              |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.abs_fp.leq.smt2                                 |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.abs_fp.lt.smt2                                  |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.add_distinct.smt2                               |   0.772s  |   0.772s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.add_fp.geq.smt2                                 |   1.761s  |   1.761s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.add_fp.gt.smt2                                  |   0.233s  |   0.233s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.add_fp.isInfinite.smt2                          |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.add_fp.isNaN.smt2                               |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.add_fp.isNegative.smt2                          |   1.956s  |   1.956s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.add_fp.isNormal.smt2                            |   1.893s  |   1.893s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.add_fp.isPositive.smt2                          |   1.342s  |   1.342s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.add_fp.isSubnormal.smt2                         |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.add_fp.isZero.smt2                              |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.add_fp.leq.smt2                                 |   4.565s  |   4.565s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.add_fp.lt.smt2                                  |   0.576s  |   0.576s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.div_distinct0.smt2                              |   8.728s  |   8.728s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.div_distinct1.smt2                              |   8.275s  |   8.275s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.div_fp.geq0.smt2                                |  20.134s  |  20.134s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.div_fp.geq1.smt2                                |  10.447s  |  10.447s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.div_fp.gt0.smt2                                 |  18.130s  |  18.130s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.div_fp.gt1.smt2                                 |  20.075s  |  20.075s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.div_fp.isInfinite0.smt2                         |  11.386s  |  11.386s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.div_fp.isInfinite1.smt2                         |   7.536s  |   7.536s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.div_fp.isNaN0.smt2                              |   0.977s  |   0.977s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.div_fp.isNaN1.smt2                              |   1.861s  |   1.861s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.div_fp.isNegative0.smt2                         |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.div_fp.isNegative1.smt2                         |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.div_fp.isNormal0.smt2                           |  20.087s  |  20.087s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.div_fp.isNormal1.smt2                           |  12.307s  |  12.307s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.div_fp.isPositive0.smt2                         |   3.999s  |   3.999s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.div_fp.isPositive1.smt2                         |  18.027s  |  18.027s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.div_fp.isSubnormal0.smt2                        |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.div_fp.isSubnormal1.smt2                        |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.div_fp.isZero0.smt2                             |   1.660s  |   1.660s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.div_fp.isZero1.smt2                             |   4.010s  |   4.010s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.div_fp.leq0.smt2                                |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.div_fp.leq1.smt2                                |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.div_fp.lt0.smt2                                 |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.div_fp.lt1.smt2                                 |  14.160s  |  14.160s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.fma_fp.isInfinite0.smt2                         |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.fma_fp.isInfinite2.smt2                         |  12.081s  |  12.081s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.fma_fp.isNaN0.smt2                              |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.fma_fp.isNaN2.smt2                              |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.fma_fp.isNegative0.smt2                         |  20.082s  |  20.082s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.fma_fp.isNegative2.smt2                         |  20.143s  |  20.143s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.fma_fp.isNormal0.smt2                           |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.fma_fp.isNormal2.smt2                           |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.fma_fp.isPositive0.smt2                         |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.fma_fp.isPositive2.smt2                         |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.fma_fp.isZero0.smt2                             |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.fma_fp.isZero2.smt2                             |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.mul_distinct.smt2                               |   3.133s  |   3.133s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.mul_fp.geq.smt2                                 |  20.068s  |  20.068s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.mul_fp.gt.smt2                                  |   4.122s  |   4.122s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.mul_fp.isInfinite.smt2                          |   0.873s  |   0.873s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.mul_fp.isNaN.smt2                               |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.mul_fp.isNegative.smt2                          |   1.943s  |   1.943s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.mul_fp.isNormal.smt2                            |  17.179s  |  17.179s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.mul_fp.isPositive.smt2                          |   2.676s  |   2.676s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.mul_fp.isSubnormal.smt2                         |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.mul_fp.isZero.smt2                              |   0.556s  |   0.556s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.mul_fp.leq.smt2                                 |   4.039s  |   4.039s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.mul_fp.lt.smt2                                  |   2.563s  |   2.563s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.neg_distinct.smt2                               |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.neg_fp.geq.smt2                                 |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.neg_fp.gt.smt2                                  |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.neg_fp.isInfinite.smt2                          |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.neg_fp.isNaN.smt2                               |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.neg_fp.isNegative.smt2                          |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.neg_fp.isNormal.smt2                            |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.neg_fp.isPositive.smt2                          |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.neg_fp.isSubnormal.smt2                         |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.neg_fp.isZero.smt2                              |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.neg_fp.leq.smt2                                 |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.neg_fp.lt.smt2                                  |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.rem_distinct0.smt2                              |  20.095s  |  20.095s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.rem_distinct1.smt2                              |  20.070s  |  20.070s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.rem_fp.geq0.smt2                                |  20.081s  |  20.081s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.rem_fp.isInfinite0.smt2                         |  20.107s  |  20.107s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.rem_fp.isInfinite1.smt2                         |  20.070s  |  20.070s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.rem_fp.isNaN0.smt2                              |   1.915s  |   1.915s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.rem_fp.isNaN1.smt2                              |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.rem_fp.isNegative0.smt2                         |  20.064s  |  20.064s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.rem_fp.isNegative1.smt2                         |  20.144s  |  20.144s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.rem_fp.isNormal0.smt2                           |  20.069s  |  20.069s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.rem_fp.isNormal1.smt2                           |  20.095s  |  20.095s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.rem_fp.isPositive0.smt2                         |  20.091s  |  20.091s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.rem_fp.isPositive1.smt2                         |  20.140s  |  20.140s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.rem_fp.isSubnormal0.smt2                        |  20.166s  |  20.166s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.rem_fp.isSubnormal1.smt2                        |  20.085s  |  20.085s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.rem_fp.isZero0.smt2                             |  20.083s  |  20.083s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.rem_fp.isZero1.smt2                             |  20.089s  |  20.089s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.rem_fp.leq0.smt2                                |  20.147s  |  20.147s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.roundToIntegral_distinct.smt2                   |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.roundToIntegral_fp.geq.smt2                     |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.roundToIntegral_fp.gt.smt2                      |   0.412s  |   0.412s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.roundToIntegral_fp.isInfinite.smt2              |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.roundToIntegral_fp.isNaN.smt2                   |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.roundToIntegral_fp.isNegative.smt2              |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.roundToIntegral_fp.isNormal.smt2                |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.roundToIntegral_fp.isPositive.smt2              |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.roundToIntegral_fp.isSubnormal.smt2             |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.roundToIntegral_fp.isZero.smt2                  |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.roundToIntegral_fp.leq.smt2                     |   0.313s  |   0.313s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.roundToIntegral_fp.lt.smt2                      |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sqrt_distinct.smt2                              |   6.489s  |   6.489s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sqrt_fp.geq.smt2                                |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sqrt_fp.gt.smt2                                 |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sqrt_fp.isInfinite.smt2                         |   5.162s  |   5.162s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sqrt_fp.isNaN.smt2                              |   1.876s  |   1.876s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sqrt_fp.isNegative.smt2                         |   0.428s  |   0.428s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sqrt_fp.isNormal.smt2                           |   3.595s  |   3.595s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sqrt_fp.isPositive.smt2                         |   6.202s  |   6.202s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sqrt_fp.isSubnormal.smt2                        |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sqrt_fp.isZero.smt2                             |  14.880s  |  14.880s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sqrt_fp.leq.smt2                                |  20.040s  |  20.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sqrt_fp.lt.smt2                                 |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sub_distinct0.smt2                              |   1.552s  |   1.552s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sub_distinct1.smt2                              |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sub_fp.geq0.smt2                                |   1.374s  |   1.374s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sub_fp.geq1.smt2                                |   0.856s  |   0.856s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sub_fp.gt0.smt2                                 |   1.348s  |   1.348s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sub_fp.gt1.smt2                                 |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sub_fp.isInfinite0.smt2                         |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sub_fp.isInfinite1.smt2                         |   0.232s  |   0.232s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sub_fp.isNaN0.smt2                              |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sub_fp.isNaN1.smt2                              |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sub_fp.isNegative0.smt2                         |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sub_fp.isNegative1.smt2                         |   1.227s  |   1.227s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sub_fp.isNormal0.smt2                           |   2.093s  |   2.093s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sub_fp.isNormal1.smt2                           |   0.756s  |   0.756s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sub_fp.isPositive0.smt2                         |   0.578s  |   0.578s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sub_fp.isPositive1.smt2                         |   0.910s  |   0.910s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sub_fp.isSubnormal0.smt2                        |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sub_fp.isSubnormal1.smt2                        |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sub_fp.isZero0.smt2                             |   0.493s  |   0.493s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sub_fp.isZero1.smt2                             |   0.508s  |   0.508s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sub_fp.leq0.smt2                                |   0.805s  |   0.805s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sub_fp.leq1.smt2                                |   2.701s  |   2.701s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sub_fp.lt0.smt2                                 |   0.875s  |   0.875s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNA_fp.sub_fp.lt1.smt2                                 |   0.315s  |   0.315s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.abs_distinct.smt2                               |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.abs_fp.geq.smt2                                 |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.abs_fp.gt.smt2                                  |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.abs_fp.isInfinite.smt2                          |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.abs_fp.isNaN.smt2                               |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.abs_fp.isNegative.smt2                          |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.abs_fp.isNormal.smt2                            |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.abs_fp.isPositive.smt2                          |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.abs_fp.isSubnormal.smt2                         |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.abs_fp.isZero.smt2                              |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.abs_fp.leq.smt2                                 |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.abs_fp.lt.smt2                                  |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.add_distinct.smt2                               |   1.361s  |   1.361s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.add_fp.geq.smt2                                 |   4.221s  |   4.221s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.add_fp.gt.smt2                                  |   1.826s  |   1.826s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.add_fp.isInfinite.smt2                          |   0.634s  |   0.634s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.add_fp.isNaN.smt2                               |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.add_fp.isNegative.smt2                          |   0.284s  |   0.284s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.add_fp.isNormal.smt2                            |   1.735s  |   1.735s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.add_fp.isPositive.smt2                          |  16.919s  |  16.919s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.add_fp.isSubnormal.smt2                         |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.add_fp.isZero.smt2                              |  20.082s  |  20.082s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.add_fp.leq.smt2                                 |   2.803s  |   2.803s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.add_fp.lt.smt2                                  |   0.627s  |   0.627s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.div_distinct0.smt2                              |   4.163s  |   4.163s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.div_distinct1.smt2                              |  11.068s  |  11.068s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.div_fp.geq0.smt2                                |  14.778s  |  14.778s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.div_fp.geq1.smt2                                |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.div_fp.gt0.smt2                                 |  13.327s  |  13.327s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.div_fp.gt1.smt2                                 |  13.613s  |  13.613s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.div_fp.isInfinite0.smt2                         |   5.139s  |   5.139s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.div_fp.isInfinite1.smt2                         |   3.813s  |   3.813s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.div_fp.isNaN0.smt2                              |   0.306s  |   0.306s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.div_fp.isNaN1.smt2                              |   2.165s  |   2.165s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.div_fp.isNegative0.smt2                         |  15.985s  |  15.985s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.div_fp.isNegative1.smt2                         |  11.046s  |  11.046s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.div_fp.isNormal0.smt2                           |  20.115s  |  20.115s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.div_fp.isNormal1.smt2                           |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.div_fp.isPositive0.smt2                         |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.div_fp.isPositive1.smt2                         |  11.544s  |  11.544s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.div_fp.isSubnormal0.smt2                        |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.div_fp.isSubnormal1.smt2                        |  20.102s  |  20.102s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.div_fp.isZero0.smt2                             |   1.270s  |   1.270s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.div_fp.isZero1.smt2                             |   1.450s  |   1.450s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.div_fp.leq0.smt2                                |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.div_fp.leq1.smt2                                |  18.060s  |  18.060s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.div_fp.lt0.smt2                                 |  20.063s  |  20.063s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.div_fp.lt1.smt2                                 |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.fma_fp.isInfinite0.smt2                         |  11.742s  |  11.742s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.fma_fp.isInfinite2.smt2                         |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.fma_fp.isNaN0.smt2                              |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.fma_fp.isNaN2.smt2                              |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.fma_fp.isNegative0.smt2                         |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.fma_fp.isNegative2.smt2                         |   3.973s  |   3.973s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.fma_fp.isNormal0.smt2                           |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.fma_fp.isNormal2.smt2                           |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.fma_fp.isPositive0.smt2                         |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.fma_fp.isPositive2.smt2                         |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.fma_fp.isZero0.smt2                             |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.fma_fp.isZero2.smt2                             |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.mul_distinct.smt2                               |   2.016s  |   2.016s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.mul_fp.geq.smt2                                 |   4.651s  |   4.651s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.mul_fp.gt.smt2                                  |   6.640s  |   6.640s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.mul_fp.isInfinite.smt2                          |   0.836s  |   0.836s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.mul_fp.isNaN.smt2                               |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.mul_fp.isNegative.smt2                          |   2.521s  |   2.521s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.mul_fp.isNormal.smt2                            |  18.453s  |  18.453s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.mul_fp.isPositive.smt2                          |   1.356s  |   1.356s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.mul_fp.isSubnormal.smt2                         |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.mul_fp.isZero.smt2                              |   3.346s  |   3.346s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.mul_fp.leq.smt2                                 |  17.721s  |  17.721s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.mul_fp.lt.smt2                                  |   7.454s  |   7.454s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.neg_distinct.smt2                               |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.neg_fp.geq.smt2                                 |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.neg_fp.gt.smt2                                  |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.neg_fp.isInfinite.smt2                          |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.neg_fp.isNaN.smt2                               |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.neg_fp.isNegative.smt2                          |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.neg_fp.isNormal.smt2                            |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.neg_fp.isPositive.smt2                          |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.neg_fp.isSubnormal.smt2                         |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.neg_fp.isZero.smt2                              |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.neg_fp.leq.smt2                                 |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.neg_fp.lt.smt2                                  |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.rem_distinct0.smt2                              |  20.068s  |  20.068s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.rem_distinct1.smt2                              |  20.070s  |  20.070s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.rem_fp.geq0.smt2                                |  20.082s  |  20.082s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.rem_fp.isInfinite0.smt2                         |  20.063s  |  20.063s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.rem_fp.isInfinite1.smt2                         |  20.175s  |  20.175s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.rem_fp.isNaN0.smt2                              |   1.825s  |   1.825s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.rem_fp.isNaN1.smt2                              |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.rem_fp.isNegative0.smt2                         |  20.071s  |  20.071s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.rem_fp.isNegative1.smt2                         |  20.087s  |  20.087s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.rem_fp.isNormal0.smt2                           |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.rem_fp.isNormal1.smt2                           |  20.102s  |  20.102s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.rem_fp.isPositive0.smt2                         |  20.111s  |  20.111s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.rem_fp.isPositive1.smt2                         |  20.081s  |  20.081s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.rem_fp.isSubnormal0.smt2                        |  20.136s  |  20.136s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.rem_fp.isSubnormal1.smt2                        |  20.112s  |  20.112s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.rem_fp.isZero0.smt2                             |  20.105s  |  20.105s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.rem_fp.isZero1.smt2                             |  20.084s  |  20.084s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.rem_fp.leq0.smt2                                |  20.139s  |  20.139s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.roundToIntegral_distinct.smt2                   |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.roundToIntegral_fp.geq.smt2                     |   0.303s  |   0.303s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.roundToIntegral_fp.gt.smt2                      |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.roundToIntegral_fp.isInfinite.smt2              |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.roundToIntegral_fp.isNaN.smt2                   |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.roundToIntegral_fp.isNegative.smt2              |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.roundToIntegral_fp.isNormal.smt2                |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.roundToIntegral_fp.isPositive.smt2              |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.roundToIntegral_fp.isSubnormal.smt2             |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.roundToIntegral_fp.isZero.smt2                  |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.roundToIntegral_fp.leq.smt2                     |   0.462s  |   0.462s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.roundToIntegral_fp.lt.smt2                      |   0.496s  |   0.496s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sqrt_distinct.smt2                              |   8.930s  |   8.930s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sqrt_fp.geq.smt2                                |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sqrt_fp.gt.smt2                                 |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sqrt_fp.isInfinite.smt2                         |   2.908s  |   2.908s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sqrt_fp.isNaN.smt2                              |   2.272s  |   2.272s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sqrt_fp.isNegative.smt2                         |   0.415s  |   0.415s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sqrt_fp.isNormal.smt2                           |   4.703s  |   4.703s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sqrt_fp.isPositive.smt2                         |   3.728s  |   3.728s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sqrt_fp.isSubnormal.smt2                        |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sqrt_fp.isZero.smt2                             |  12.405s  |  12.405s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sqrt_fp.leq.smt2                                |  19.866s  |  19.866s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sqrt_fp.lt.smt2                                 |  18.394s  |  18.394s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sub_distinct0.smt2                              |   0.427s  |   0.427s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sub_distinct1.smt2                              |   1.289s  |   1.289s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sub_fp.geq0.smt2                                |   0.391s  |   0.391s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sub_fp.geq1.smt2                                |   0.576s  |   0.576s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sub_fp.gt0.smt2                                 |   0.241s  |   0.241s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sub_fp.gt1.smt2                                 |   0.468s  |   0.468s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sub_fp.isInfinite0.smt2                         |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sub_fp.isInfinite1.smt2                         |   0.537s  |   0.537s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sub_fp.isNaN0.smt2                              |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sub_fp.isNaN1.smt2                              |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sub_fp.isNegative0.smt2                         |   7.725s  |   7.725s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sub_fp.isNegative1.smt2                         |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sub_fp.isNormal0.smt2                           |   1.420s  |   1.420s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sub_fp.isNormal1.smt2                           |   0.781s  |   0.781s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sub_fp.isPositive0.smt2                         |   2.970s  |   2.970s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sub_fp.isPositive1.smt2                         |   0.552s  |   0.552s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sub_fp.isSubnormal0.smt2                        |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sub_fp.isSubnormal1.smt2                        |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sub_fp.isZero0.smt2                             |   0.486s  |   0.486s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sub_fp.isZero1.smt2                             |   0.430s  |   0.430s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sub_fp.leq0.smt2                                |   1.152s  |   1.152s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sub_fp.leq1.smt2                                |   1.029s  |   1.029s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sub_fp.lt0.smt2                                 |   6.482s  |   6.482s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RNE_fp.sub_fp.lt1.smt2                                 |   0.334s  |   0.334s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.abs_distinct.smt2                               |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.abs_fp.geq.smt2                                 |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.abs_fp.gt.smt2                                  |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.abs_fp.isInfinite.smt2                          |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.abs_fp.isNaN.smt2                               |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.abs_fp.isNegative.smt2                          |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.abs_fp.isNormal.smt2                            |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.abs_fp.isPositive.smt2                          |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.abs_fp.isSubnormal.smt2                         |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.abs_fp.isZero.smt2                              |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.abs_fp.leq.smt2                                 |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.abs_fp.lt.smt2                                  |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.add_distinct.smt2                               |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.add_fp.geq.smt2                                 |   0.657s  |   0.657s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.add_fp.gt.smt2                                  |   1.044s  |   1.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.add_fp.isInfinite.smt2                          |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.add_fp.isNaN.smt2                               |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.add_fp.isNegative.smt2                          |   7.703s  |   7.703s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.add_fp.isNormal.smt2                            |   1.792s  |   1.792s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.add_fp.isPositive.smt2                          |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.add_fp.isSubnormal.smt2                         |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.add_fp.isZero.smt2                              |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.add_fp.leq.smt2                                 |  16.606s  |  16.606s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.add_fp.lt.smt2                                  |   0.395s  |   0.395s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.div_distinct0.smt2                              |   8.809s  |   8.809s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.div_distinct1.smt2                              |   3.150s  |   3.150s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.div_fp.geq0.smt2                                |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.div_fp.geq1.smt2                                |   7.113s  |   7.113s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.div_fp.gt0.smt2                                 |  15.821s  |  15.821s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.div_fp.gt1.smt2                                 |  17.939s  |  17.939s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.div_fp.isInfinite0.smt2                         |  10.639s  |  10.639s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.div_fp.isInfinite1.smt2                         |   5.984s  |   5.984s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.div_fp.isNaN0.smt2                              |   0.723s  |   0.723s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.div_fp.isNaN1.smt2                              |   2.654s  |   2.654s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.div_fp.isNegative0.smt2                         |  11.134s  |  11.134s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.div_fp.isNegative1.smt2                         |   5.879s  |   5.879s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.div_fp.isNormal0.smt2                           |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.div_fp.isNormal1.smt2                           |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.div_fp.isPositive0.smt2                         |   6.063s  |   6.063s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.div_fp.isPositive1.smt2                         |  19.175s  |  19.175s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.div_fp.isSubnormal0.smt2                        |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.div_fp.isSubnormal1.smt2                        |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.div_fp.isZero0.smt2                             |   4.941s  |   4.941s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.div_fp.isZero1.smt2                             |   1.059s  |   1.059s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.div_fp.leq0.smt2                                |   8.709s  |   8.709s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.div_fp.leq1.smt2                                |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.div_fp.lt0.smt2                                 |  13.477s  |  13.477s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.div_fp.lt1.smt2                                 |  20.047s  |  20.047s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.fma_fp.isInfinite0.smt2                         |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.fma_fp.isInfinite2.smt2                         |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.fma_fp.isNaN0.smt2                              |   1.326s  |   1.326s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.fma_fp.isNaN2.smt2                              |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.fma_fp.isNegative0.smt2                         |  20.074s  |  20.074s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.fma_fp.isNegative2.smt2                         |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.fma_fp.isNormal0.smt2                           |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.fma_fp.isNormal2.smt2                           |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.fma_fp.isPositive0.smt2                         |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.fma_fp.isPositive2.smt2                         |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.fma_fp.isZero0.smt2                             |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.fma_fp.isZero2.smt2                             |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.mul_distinct.smt2                               |   3.860s  |   3.860s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.mul_fp.geq.smt2                                 |   8.261s  |   8.261s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.mul_fp.gt.smt2                                  |   3.666s  |   3.666s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.mul_fp.isInfinite.smt2                          |   0.833s  |   0.833s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.mul_fp.isNaN.smt2                               |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.mul_fp.isNegative.smt2                          |   0.836s  |   0.836s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.mul_fp.isNormal.smt2                            |  20.064s  |  20.064s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.mul_fp.isPositive.smt2                          |   1.609s  |   1.609s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.mul_fp.isSubnormal.smt2                         |  19.660s  |  19.660s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.mul_fp.isZero.smt2                              |   0.396s  |   0.396s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.mul_fp.leq.smt2                                 |   5.988s  |   5.988s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.mul_fp.lt.smt2                                  |   7.352s  |   7.352s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.neg_distinct.smt2                               |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.neg_fp.geq.smt2                                 |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.neg_fp.gt.smt2                                  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.neg_fp.isInfinite.smt2                          |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.neg_fp.isNaN.smt2                               |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.neg_fp.isNegative.smt2                          |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.neg_fp.isNormal.smt2                            |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.neg_fp.isPositive.smt2                          |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.neg_fp.isSubnormal.smt2                         |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.neg_fp.isZero.smt2                              |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.neg_fp.leq.smt2                                 |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.neg_fp.lt.smt2                                  |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.rem_distinct0.smt2                              |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.rem_distinct1.smt2                              |  20.076s  |  20.076s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.rem_fp.geq0.smt2                                |  20.107s  |  20.107s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.rem_fp.isInfinite0.smt2                         |  20.101s  |  20.101s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.rem_fp.isInfinite1.smt2                         |  20.069s  |  20.069s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.rem_fp.isNaN0.smt2                              |   1.572s  |   1.572s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.rem_fp.isNaN1.smt2                              |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.rem_fp.isNegative0.smt2                         |  20.103s  |  20.103s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.rem_fp.isNegative1.smt2                         |  20.082s  |  20.082s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.rem_fp.isNormal0.smt2                           |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.rem_fp.isNormal1.smt2                           |  20.083s  |  20.083s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.rem_fp.isPositive0.smt2                         |  20.092s  |  20.092s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.rem_fp.isPositive1.smt2                         |  20.090s  |  20.090s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.rem_fp.isSubnormal0.smt2                        |  20.124s  |  20.124s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.rem_fp.isSubnormal1.smt2                        |  20.092s  |  20.092s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.rem_fp.isZero0.smt2                             |  20.111s  |  20.111s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.rem_fp.isZero1.smt2                             |  20.077s  |  20.077s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.rem_fp.leq0.smt2                                |  20.161s  |  20.161s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.roundToIntegral_distinct.smt2                   |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.roundToIntegral_fp.geq.smt2                     |   0.357s  |   0.357s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.roundToIntegral_fp.gt.smt2                      |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.roundToIntegral_fp.isInfinite.smt2              |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.roundToIntegral_fp.isNaN.smt2                   |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.roundToIntegral_fp.isNegative.smt2              |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.roundToIntegral_fp.isNormal.smt2                |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.roundToIntegral_fp.isPositive.smt2              |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.roundToIntegral_fp.isSubnormal.smt2             |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.roundToIntegral_fp.isZero.smt2                  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.roundToIntegral_fp.leq.smt2                     |   0.279s  |   0.279s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.roundToIntegral_fp.lt.smt2                      |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sqrt_distinct.smt2                              |   3.769s  |   3.769s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sqrt_fp.geq.smt2                                |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sqrt_fp.gt.smt2                                 |  20.071s  |  20.071s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sqrt_fp.isInfinite.smt2                         |   5.745s  |   5.745s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sqrt_fp.isNaN.smt2                              |   6.673s  |   6.673s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sqrt_fp.isNegative.smt2                         |   0.513s  |   0.513s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sqrt_fp.isNormal.smt2                           |   3.158s  |   3.158s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sqrt_fp.isPositive.smt2                         |   3.427s  |   3.427s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sqrt_fp.isSubnormal.smt2                        |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sqrt_fp.isZero.smt2                             |   4.709s  |   4.709s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sqrt_fp.leq.smt2                                |  17.957s  |  17.957s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sqrt_fp.lt.smt2                                 |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sub_distinct0.smt2                              |   2.249s  |   2.249s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sub_distinct1.smt2                              |   0.397s  |   0.397s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sub_fp.geq0.smt2                                |   1.876s  |   1.876s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sub_fp.geq1.smt2                                |   0.778s  |   0.778s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sub_fp.gt0.smt2                                 |   1.810s  |   1.810s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sub_fp.gt1.smt2                                 |   0.936s  |   0.936s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sub_fp.isInfinite0.smt2                         |   0.366s  |   0.366s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sub_fp.isInfinite1.smt2                         |   0.280s  |   0.280s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sub_fp.isNaN0.smt2                              |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sub_fp.isNaN1.smt2                              |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sub_fp.isNegative0.smt2                         |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sub_fp.isNegative1.smt2                         |   2.349s  |   2.349s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sub_fp.isNormal0.smt2                           |   1.297s  |   1.297s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sub_fp.isNormal1.smt2                           |   1.048s  |   1.048s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sub_fp.isPositive0.smt2                         |   0.734s  |   0.734s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sub_fp.isPositive1.smt2                         |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sub_fp.isSubnormal0.smt2                        |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sub_fp.isSubnormal1.smt2                        |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sub_fp.isZero0.smt2                             |   0.355s  |   0.355s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sub_fp.isZero1.smt2                             |   0.406s  |   0.406s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sub_fp.leq0.smt2                                |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sub_fp.leq1.smt2                                |   0.553s  |   0.553s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sub_fp.lt0.smt2                                 |   2.627s  |   2.627s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTN_fp.sub_fp.lt1.smt2                                 |  11.577s  |  11.577s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.abs_distinct.smt2                               |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.abs_fp.geq.smt2                                 |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.abs_fp.gt.smt2                                  |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.abs_fp.isInfinite.smt2                          |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.abs_fp.isNaN.smt2                               |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.abs_fp.isNegative.smt2                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.abs_fp.isNormal.smt2                            |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.abs_fp.isPositive.smt2                          |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.abs_fp.isSubnormal.smt2                         |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.abs_fp.isZero.smt2                              |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.abs_fp.leq.smt2                                 |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.abs_fp.lt.smt2                                  |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.add_distinct.smt2                               |   1.715s  |   1.715s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.add_fp.geq.smt2                                 |   0.432s  |   0.432s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.add_fp.gt.smt2                                  |   1.261s  |   1.261s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.add_fp.isInfinite.smt2                          |   0.507s  |   0.507s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.add_fp.isNaN.smt2                               |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.add_fp.isNegative.smt2                          |   0.994s  |   0.994s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.add_fp.isNormal.smt2                            |   1.856s  |   1.856s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.add_fp.isPositive.smt2                          |   0.739s  |   0.739s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.add_fp.isSubnormal.smt2                         |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.add_fp.isZero.smt2                              |  20.102s  |  20.102s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.add_fp.leq.smt2                                 |   1.210s  |   1.210s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.add_fp.lt.smt2                                  |   5.021s  |   5.021s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.div_distinct0.smt2                              |   7.358s  |   7.358s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.div_distinct1.smt2                              |   0.923s  |   0.923s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.div_fp.geq0.smt2                                |  13.259s  |  13.259s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.div_fp.geq1.smt2                                |  16.616s  |  16.616s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.div_fp.gt0.smt2                                 |  15.826s  |  15.826s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.div_fp.gt1.smt2                                 |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.div_fp.isInfinite0.smt2                         |   4.008s  |   4.008s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.div_fp.isInfinite1.smt2                         |   5.882s  |   5.882s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.div_fp.isNaN0.smt2                              |   0.977s  |   0.977s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.div_fp.isNaN1.smt2                              |   2.049s  |   2.049s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.div_fp.isNegative0.smt2                         |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.div_fp.isNegative1.smt2                         |  20.078s  |  20.078s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.div_fp.isNormal0.smt2                           |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.div_fp.isNormal1.smt2                           |  20.163s  |  20.163s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.div_fp.isPositive0.smt2                         |  15.638s  |  15.638s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.div_fp.isPositive1.smt2                         |  11.480s  |  11.480s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.div_fp.isSubnormal0.smt2                        |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.div_fp.isSubnormal1.smt2                        |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.div_fp.isZero0.smt2                             |   3.738s  |   3.738s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.div_fp.isZero1.smt2                             |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.div_fp.leq0.smt2                                |   6.648s  |   6.648s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.div_fp.leq1.smt2                                |   9.971s  |   9.971s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.div_fp.lt0.smt2                                 |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.div_fp.lt1.smt2                                 |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.fma_fp.isInfinite0.smt2                         |  20.067s  |  20.067s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.fma_fp.isInfinite2.smt2                         |   5.066s  |   5.066s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.fma_fp.isNaN0.smt2                              |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.fma_fp.isNaN2.smt2                              |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.fma_fp.isNegative0.smt2                         |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.fma_fp.isNegative2.smt2                         |  20.098s  |  20.098s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.fma_fp.isNormal0.smt2                           |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.fma_fp.isNormal2.smt2                           |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.fma_fp.isPositive0.smt2                         |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.fma_fp.isPositive2.smt2                         |  12.113s  |  12.113s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.fma_fp.isZero0.smt2                             |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.fma_fp.isZero2.smt2                             |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.mul_distinct.smt2                               |   6.013s  |   6.013s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.mul_fp.geq.smt2                                 |  14.342s  |  14.342s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.mul_fp.gt.smt2                                  |   3.669s  |   3.669s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.mul_fp.isInfinite.smt2                          |   0.524s  |   0.524s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.mul_fp.isNaN.smt2                               |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.mul_fp.isNegative.smt2                          |   0.888s  |   0.888s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.mul_fp.isNormal.smt2                            |  13.447s  |  13.447s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.mul_fp.isPositive.smt2                          |   1.926s  |   1.926s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.mul_fp.isSubnormal.smt2                         |  10.290s  |  10.290s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.mul_fp.isZero.smt2                              |   1.210s  |   1.210s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.mul_fp.leq.smt2                                 |  10.142s  |  10.142s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.mul_fp.lt.smt2                                  |  17.132s  |  17.132s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.neg_distinct.smt2                               |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.neg_fp.geq.smt2                                 |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.neg_fp.gt.smt2                                  |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.neg_fp.isInfinite.smt2                          |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.neg_fp.isNaN.smt2                               |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.neg_fp.isNegative.smt2                          |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.neg_fp.isNormal.smt2                            |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.neg_fp.isPositive.smt2                          |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.neg_fp.isSubnormal.smt2                         |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.neg_fp.isZero.smt2                              |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.neg_fp.leq.smt2                                 |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.neg_fp.lt.smt2                                  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.rem_distinct0.smt2                              |  20.099s  |  20.099s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.rem_distinct1.smt2                              |  20.077s  |  20.077s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.rem_fp.geq0.smt2                                |  20.130s  |  20.130s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.rem_fp.isInfinite0.smt2                         |  20.061s  |  20.061s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.rem_fp.isInfinite1.smt2                         |  20.079s  |  20.079s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.rem_fp.isNaN0.smt2                              |   1.802s  |   1.802s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.rem_fp.isNaN1.smt2                              |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.rem_fp.isNegative0.smt2                         |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.rem_fp.isNegative1.smt2                         |  20.076s  |  20.076s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.rem_fp.isNormal0.smt2                           |  20.095s  |  20.095s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.rem_fp.isNormal1.smt2                           |  20.078s  |  20.078s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.rem_fp.isPositive0.smt2                         |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.rem_fp.isPositive1.smt2                         |  20.092s  |  20.092s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.rem_fp.isSubnormal0.smt2                        |  20.172s  |  20.172s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.rem_fp.isSubnormal1.smt2                        |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.rem_fp.isZero0.smt2                             |  20.092s  |  20.092s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.rem_fp.isZero1.smt2                             |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.rem_fp.leq0.smt2                                |  20.133s  |  20.133s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.roundToIntegral_distinct.smt2                   |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.roundToIntegral_fp.geq.smt2                     |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.roundToIntegral_fp.gt.smt2                      |   0.690s  |   0.690s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.roundToIntegral_fp.isInfinite.smt2              |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.roundToIntegral_fp.isNaN.smt2                   |   0.271s  |   0.271s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.roundToIntegral_fp.isNegative.smt2              |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.roundToIntegral_fp.isNormal.smt2                |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.roundToIntegral_fp.isPositive.smt2              |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.roundToIntegral_fp.isSubnormal.smt2             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.roundToIntegral_fp.isZero.smt2                  |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.roundToIntegral_fp.leq.smt2                     |   0.291s  |   0.291s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.roundToIntegral_fp.lt.smt2                      |   0.301s  |   0.301s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sqrt_distinct.smt2                              |   4.666s  |   4.666s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sqrt_fp.geq.smt2                                |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sqrt_fp.gt.smt2                                 |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sqrt_fp.isInfinite.smt2                         |   1.280s  |   1.280s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sqrt_fp.isNaN.smt2                              |   4.798s  |   4.798s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sqrt_fp.isNegative.smt2                         |   0.385s  |   0.385s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sqrt_fp.isNormal.smt2                           |   1.748s  |   1.748s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sqrt_fp.isPositive.smt2                         |   4.251s  |   4.251s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sqrt_fp.isSubnormal.smt2                        |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sqrt_fp.isZero.smt2                             |  14.030s  |  14.030s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sqrt_fp.leq.smt2                                |   6.696s  |   6.696s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sqrt_fp.lt.smt2                                 |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sub_distinct0.smt2                              |   1.402s  |   1.402s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sub_distinct1.smt2                              |   0.545s  |   0.545s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sub_fp.geq0.smt2                                |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sub_fp.geq1.smt2                                |   1.499s  |   1.499s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sub_fp.gt0.smt2                                 |   5.536s  |   5.536s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sub_fp.gt1.smt2                                 |   0.500s  |   0.500s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sub_fp.isInfinite0.smt2                         |   0.271s  |   0.271s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sub_fp.isInfinite1.smt2                         |   0.400s  |   0.400s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sub_fp.isNaN0.smt2                              |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sub_fp.isNaN1.smt2                              |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sub_fp.isNegative0.smt2                         |   2.630s  |   2.630s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sub_fp.isNegative1.smt2                         |  13.916s  |  13.916s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sub_fp.isNormal0.smt2                           |   1.575s  |   1.575s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sub_fp.isNormal1.smt2                           |   0.897s  |   0.897s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sub_fp.isPositive0.smt2                         |   0.442s  |   0.442s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sub_fp.isPositive1.smt2                         |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sub_fp.isSubnormal0.smt2                        |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sub_fp.isSubnormal1.smt2                        |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sub_fp.isZero0.smt2                             |   0.334s  |   0.334s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sub_fp.isZero1.smt2                             |   0.579s  |   0.579s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sub_fp.leq0.smt2                                |   4.083s  |   4.083s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sub_fp.leq1.smt2                                |   0.985s  |   0.985s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sub_fp.lt0.smt2                                 |   2.524s  |   2.524s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTP_fp.sub_fp.lt1.smt2                                 |   0.607s  |   0.607s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.abs_distinct.smt2                               |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.abs_fp.geq.smt2                                 |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.abs_fp.gt.smt2                                  |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.abs_fp.isInfinite.smt2                          |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.abs_fp.isNaN.smt2                               |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.abs_fp.isNegative.smt2                          |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.abs_fp.isNormal.smt2                            |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.abs_fp.isPositive.smt2                          |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.abs_fp.isSubnormal.smt2                         |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.abs_fp.isZero.smt2                              |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.abs_fp.leq.smt2                                 |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.abs_fp.lt.smt2                                  |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.add_distinct.smt2                               |   0.347s  |   0.347s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.add_fp.geq.smt2                                 |   0.676s  |   0.676s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.add_fp.gt.smt2                                  |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.add_fp.isInfinite.smt2                          |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.add_fp.isNaN.smt2                               |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.add_fp.isNegative.smt2                          |   3.211s  |   3.211s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.add_fp.isNormal.smt2                            |   0.714s  |   0.714s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.add_fp.isPositive.smt2                          |  15.843s  |  15.843s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.add_fp.isSubnormal.smt2                         |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.add_fp.isZero.smt2                              |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.add_fp.leq.smt2                                 |   0.673s  |   0.673s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.add_fp.lt.smt2                                  |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.div_distinct0.smt2                              |   5.433s  |   5.433s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.div_distinct1.smt2                              |   2.705s  |   2.705s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.div_fp.geq0.smt2                                |  18.583s  |  18.583s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.div_fp.geq1.smt2                                |   3.438s  |   3.438s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.div_fp.gt0.smt2                                 |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.div_fp.gt1.smt2                                 |   4.652s  |   4.652s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.div_fp.isInfinite0.smt2                         |   5.310s  |   5.310s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.div_fp.isInfinite1.smt2                         |   3.357s  |   3.357s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.div_fp.isNaN0.smt2                              |   0.400s  |   0.400s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.div_fp.isNaN1.smt2                              |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.div_fp.isNegative0.smt2                         |   3.681s  |   3.681s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.div_fp.isNegative1.smt2                         |   8.497s  |   8.497s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.div_fp.isNormal0.smt2                           |  16.604s  |  16.604s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.div_fp.isNormal1.smt2                           |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.div_fp.isPositive0.smt2                         |   2.304s  |   2.304s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.div_fp.isPositive1.smt2                         |  12.259s  |  12.259s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.div_fp.isSubnormal0.smt2                        |  20.064s  |  20.064s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.div_fp.isSubnormal1.smt2                        |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.div_fp.isZero0.smt2                             |   6.462s  |   6.462s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.div_fp.isZero1.smt2                             |   1.972s  |   1.972s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.div_fp.leq0.smt2                                |  20.066s  |  20.066s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.div_fp.leq1.smt2                                |  18.278s  |  18.278s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.div_fp.lt0.smt2                                 |   8.846s  |   8.846s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.div_fp.lt1.smt2                                 |  20.120s  |  20.120s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.fma_fp.isInfinite0.smt2                         |   5.515s  |   5.515s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.fma_fp.isInfinite2.smt2                         |   5.424s  |   5.424s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.fma_fp.isNaN0.smt2                              |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.fma_fp.isNaN2.smt2                              |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.fma_fp.isNegative0.smt2                         |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.fma_fp.isNegative2.smt2                         |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.fma_fp.isNormal0.smt2                           |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.fma_fp.isNormal2.smt2                           |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.fma_fp.isPositive0.smt2                         |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.fma_fp.isPositive2.smt2                         |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.fma_fp.isZero0.smt2                             |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.fma_fp.isZero2.smt2                             |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.mul_distinct.smt2                               |   0.616s  |   0.616s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.mul_fp.geq.smt2                                 |   1.370s  |   1.370s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.mul_fp.gt.smt2                                  |   4.626s  |   4.626s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.mul_fp.isInfinite.smt2                          |   1.139s  |   1.139s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.mul_fp.isNaN.smt2                               |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.mul_fp.isNegative.smt2                          |   3.052s  |   3.052s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.mul_fp.isNormal.smt2                            |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.mul_fp.isPositive.smt2                          |   1.117s  |   1.117s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.mul_fp.isSubnormal.smt2                         |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.mul_fp.isZero.smt2                              |   2.399s  |   2.399s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.mul_fp.leq.smt2                                 |   0.737s  |   0.737s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.mul_fp.lt.smt2                                  |   7.013s  |   7.013s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.neg_distinct.smt2                               |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.neg_fp.geq.smt2                                 |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.neg_fp.gt.smt2                                  |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.neg_fp.isInfinite.smt2                          |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.neg_fp.isNaN.smt2                               |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.neg_fp.isNegative.smt2                          |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.neg_fp.isNormal.smt2                            |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.neg_fp.isPositive.smt2                          |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.neg_fp.isSubnormal.smt2                         |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.neg_fp.isZero.smt2                              |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.neg_fp.leq.smt2                                 |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.neg_fp.lt.smt2                                  |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.rem_distinct0.smt2                              |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.rem_distinct1.smt2                              |  20.078s  |  20.078s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.rem_fp.geq0.smt2                                |  20.070s  |  20.070s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.rem_fp.isInfinite0.smt2                         |  20.127s  |  20.127s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.rem_fp.isInfinite1.smt2                         |  20.070s  |  20.070s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.rem_fp.isNaN0.smt2                              |   1.947s  |   1.947s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.rem_fp.isNaN1.smt2                              |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.rem_fp.isNegative0.smt2                         |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.rem_fp.isNegative1.smt2                         |  20.087s  |  20.087s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.rem_fp.isNormal0.smt2                           |  20.100s  |  20.100s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.rem_fp.isNormal1.smt2                           |  20.148s  |  20.148s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.rem_fp.isPositive0.smt2                         |  20.069s  |  20.069s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.rem_fp.isPositive1.smt2                         |  20.089s  |  20.089s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.rem_fp.isSubnormal0.smt2                        |  20.138s  |  20.138s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.rem_fp.isSubnormal1.smt2                        |  20.084s  |  20.084s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.rem_fp.isZero0.smt2                             |  20.069s  |  20.069s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.rem_fp.isZero1.smt2                             |  20.088s  |  20.088s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.rem_fp.leq0.smt2                                |  20.111s  |  20.111s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.roundToIntegral_distinct.smt2                   |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.roundToIntegral_fp.geq.smt2                     |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.roundToIntegral_fp.gt.smt2                      |   0.424s  |   0.424s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.roundToIntegral_fp.isInfinite.smt2              |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.roundToIntegral_fp.isNaN.smt2                   |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.roundToIntegral_fp.isNegative.smt2              |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.roundToIntegral_fp.isNormal.smt2                |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.roundToIntegral_fp.isPositive.smt2              |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.roundToIntegral_fp.isSubnormal.smt2             |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.roundToIntegral_fp.isZero.smt2                  |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.roundToIntegral_fp.leq.smt2                     |   0.275s  |   0.275s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.roundToIntegral_fp.lt.smt2                      |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sqrt_distinct.smt2                              |   7.882s  |   7.882s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sqrt_fp.geq.smt2                                |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sqrt_fp.gt.smt2                                 |  14.757s  |  14.757s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sqrt_fp.isInfinite.smt2                         |   3.704s  |   3.704s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sqrt_fp.isNaN.smt2                              |   5.330s  |   5.330s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sqrt_fp.isNegative.smt2                         |   0.507s  |   0.507s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sqrt_fp.isNormal.smt2                           |   3.417s  |   3.417s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sqrt_fp.isPositive.smt2                         |   4.277s  |   4.277s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sqrt_fp.isSubnormal.smt2                        |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sqrt_fp.isZero.smt2                             |  12.705s  |  12.705s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sqrt_fp.leq.smt2                                |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sqrt_fp.lt.smt2                                 |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sub_distinct0.smt2                              |   2.011s  |   2.011s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sub_distinct1.smt2                              |   0.732s  |   0.732s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sub_fp.geq0.smt2                                |   1.062s  |   1.062s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sub_fp.geq1.smt2                                |   1.131s  |   1.131s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sub_fp.gt0.smt2                                 |   0.550s  |   0.550s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sub_fp.gt1.smt2                                 |   1.193s  |   1.193s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sub_fp.isInfinite0.smt2                         |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sub_fp.isInfinite1.smt2                         |   0.409s  |   0.409s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sub_fp.isNaN0.smt2                              |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sub_fp.isNaN1.smt2                              |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sub_fp.isNegative0.smt2                         |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sub_fp.isNegative1.smt2                         |   3.769s  |   3.769s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sub_fp.isNormal0.smt2                           |   1.255s  |   1.255s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sub_fp.isNormal1.smt2                           |   2.334s  |   2.334s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sub_fp.isPositive0.smt2                         |   0.310s  |   0.310s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sub_fp.isPositive1.smt2                         |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sub_fp.isSubnormal0.smt2                        |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sub_fp.isSubnormal1.smt2                        |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sub_fp.isZero0.smt2                             |   0.302s  |   0.302s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sub_fp.isZero1.smt2                             |   0.353s  |   0.353s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sub_fp.leq0.smt2                                |   1.512s  |   1.512s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sub_fp.leq1.smt2                                |   2.584s  |   2.584s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sub_fp.lt0.smt2                                 |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|non-incremental/FP/2019-Preiner/8_24_RTZ_fp.sub_fp.lt1.smt2                                 |   2.071s  |   2.071s  |   0.000s  | 0.0%|
|non-incremental/FP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1122b_true-unreach-call.c_0.smt2  |  20.067s  |  20.067s  |   0.000s  | 0.0%|
|non-incremental/FP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1121a_true-unreach-call.c_0.smt2  |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/FP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1121a_true-unreach-call.c_2.smt2  |  15.982s  |  15.982s  |   0.000s  | 0.0%|
|non-incremental/FP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1121a_true-unreach-call.c_3.smt2  |  20.063s  |  20.063s  |   0.000s  | 0.0%|
|non-incremental/FP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1121a_true-unreach-call.c_4.smt2  |   7.145s  |   7.145s  |   0.000s  | 0.0%|
|non-incremental/FP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1122a_true-unreach-call.c_0.smt2  |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|non-incremental/FP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1122a_true-unreach-call.c_1.smt2  |   6.621s  |   6.621s  |   0.000s  | 0.0%|
|non-incremental/FP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1122a_true-unreach-call.c_2.smt2  |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599120907423257000.smt2                                   |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599120907521986000.smt2                                   |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599120907623486000.smt2                                   |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599120907730564000.smt2                                   |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599120907827191000.smt2                                   |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599120908941763000.smt2                                   |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599120911878125000.smt2                                   |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121684197507000.smt2                                   |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121684294608000.smt2                                   |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121684386621000.smt2                                   |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121684485720000.smt2                                   |  20.069s  |  20.069s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121684570103000.smt2                                   |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121684661950000.smt2                                   |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121684769900000.smt2                                   |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121687433299000.smt2                                   |  20.063s  |  20.063s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121861030829000.smt2                                   |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121861121772000.smt2                                   |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121861213096000.smt2                                   |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121861312738000.smt2                                   |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121861400243000.smt2                                   |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121861505053000.smt2                                   |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121861598833000.smt2                                   |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121861681555000.smt2                                   |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121861782445000.smt2                                   |  20.063s  |  20.063s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121861877445000.smt2                                   |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121861971556000.smt2                                   |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121862069129000.smt2                                   |  20.040s  |  20.040s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121862166527000.smt2                                   |  20.061s  |  20.061s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121862260881000.smt2                                   |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121862359721000.smt2                                   |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121862451262000.smt2                                   |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121862548830000.smt2                                   |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121862636658000.smt2                                   |  20.078s  |  20.078s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121862728382000.smt2                                   |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121862811443000.smt2                                   |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121862907643000.smt2                                   |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121862989283000.smt2                                   |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121863080353000.smt2                                   |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121863168768000.smt2                                   |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121863251848000.smt2                                   |  20.064s  |  20.064s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121863340291000.smt2                                   |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121863427130000.smt2                                   |  20.069s  |  20.069s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121863516148000.smt2                                   |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121863606566000.smt2                                   |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121863716808000.smt2                                   |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121863828455000.smt2                                   |  20.074s  |  20.074s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121863935976000.smt2                                   |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121866557308000.smt2                                   |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121886388280000.smt2                                   |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121886558934000.smt2                                   |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121889466982000.smt2                                   |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121899319109000.smt2                                   |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121899414336000.smt2                                   |  20.069s  |  20.069s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121899544143000.smt2                                   |  20.099s  |  20.099s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121899693718000.smt2                                   |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121899774132000.smt2                                   |  20.064s  |  20.064s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121899881173000.smt2                                   |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121900004520000.smt2                                   |  20.075s  |  20.075s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121900096175000.smt2                                   |  20.073s  |  20.073s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121900187205000.smt2                                   |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121900273325000.smt2                                   |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121900403516000.smt2                                   |  20.085s  |  20.085s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121900510420000.smt2                                   |  20.068s  |  20.068s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121900619976000.smt2                                   |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121900729947000.smt2                                   |  20.090s  |  20.090s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121900872164000.smt2                                   |  20.090s  |  20.090s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121900970205000.smt2                                   |  20.071s  |  20.071s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121901067306000.smt2                                   |  20.085s  |  20.085s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121901174413000.smt2                                   |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121901269744000.smt2                                   |  20.090s  |  20.090s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121901407706000.smt2                                   |  20.108s  |  20.108s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121901518364000.smt2                                   |  20.095s  |  20.095s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121901615231000.smt2                                   |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121901797110000.smt2                                   |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121901988004000.smt2                                   |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121902202958000.smt2                                   |  20.063s  |  20.063s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121902366918000.smt2                                   |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121902452574000.smt2                                   |  20.066s  |  20.066s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121902591046000.smt2                                   |  20.070s  |  20.070s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121902708585000.smt2                                   |  20.087s  |  20.087s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121902814153000.smt2                                   |  20.063s  |  20.063s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121902918501000.smt2                                   |  20.061s  |  20.061s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121903040197000.smt2                                   |  20.071s  |  20.071s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121903178242000.smt2                                   |  20.092s  |  20.092s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121903287695000.smt2                                   |  20.083s  |  20.083s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121903389077000.smt2                                   |  20.084s  |  20.084s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121903527582000.smt2                                   |  20.061s  |  20.061s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121903672288000.smt2                                   |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121903852178000.smt2                                   |  20.082s  |  20.082s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121903984549000.smt2                                   |  20.078s  |  20.078s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121904157540000.smt2                                   |  20.080s  |  20.080s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121904284892000.smt2                                   |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121904438360000.smt2                                   |  20.086s  |  20.086s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121904584556000.smt2                                   |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121904707933000.smt2                                   |  20.077s  |  20.077s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121904858758000.smt2                                   |  20.070s  |  20.070s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121905012938000.smt2                                   |  20.061s  |  20.061s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121905167785000.smt2                                   |  20.080s  |  20.080s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121905372123000.smt2                                   |  20.075s  |  20.075s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121905459054000.smt2                                   |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121905548152000.smt2                                   |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121905686872000.smt2                                   |  20.068s  |  20.068s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121905765223000.smt2                                   |  20.085s  |  20.085s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121905862292000.smt2                                   |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121906010363000.smt2                                   |  20.097s  |  20.097s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121906186018000.smt2                                   |  20.076s  |  20.076s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121906342128000.smt2                                   |  20.079s  |  20.079s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121909161127000.smt2                                   |  20.091s  |  20.091s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121976796044000.smt2                                   |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121976884841000.smt2                                   |  20.061s  |  20.061s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121976984175000.smt2                                   |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121977061095000.smt2                                   |  20.070s  |  20.070s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121977149076000.smt2                                   |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121977228638000.smt2                                   |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121977327114000.smt2                                   |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121977418548000.smt2                                   |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121977502656000.smt2                                   |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121977583285000.smt2                                   |  20.068s  |  20.068s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121977697389000.smt2                                   |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121977787050000.smt2                                   |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121977880178000.smt2                                   |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121977971569000.smt2                                   |  20.071s  |  20.071s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121978062026000.smt2                                   |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121978158346000.smt2                                   |  20.070s  |  20.070s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121978242031000.smt2                                   |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121978333413000.smt2                                   |  20.067s  |  20.067s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121978418966000.smt2                                   |  20.069s  |  20.069s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121978512070000.smt2                                   |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121978596730000.smt2                                   |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121978742338000.smt2                                   |  20.064s  |  20.064s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121978853448000.smt2                                   |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121978946861000.smt2                                   |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121979045849000.smt2                                   |  20.066s  |  20.066s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121979145443000.smt2                                   |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121979248520000.smt2                                   |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121979357127000.smt2                                   |  20.064s  |  20.064s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121979461337000.smt2                                   |  20.069s  |  20.069s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121979549010000.smt2                                   |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121979642652000.smt2                                   |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121979762607000.smt2                                   |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121979885688000.smt2                                   |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121979977683000.smt2                                   |  20.074s  |  20.074s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121980073596000.smt2                                   |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121980164940000.smt2                                   |  20.066s  |  20.066s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599121982759538000.smt2                                   |  20.074s  |  20.074s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122158631248000.smt2                                   |   6.227s  |   6.227s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122158699032000.smt2                                   |  20.068s  |  20.068s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122158769763000.smt2                                   |  12.953s  |  12.953s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122158834716000.smt2                                   |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122158904815000.smt2                                   |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122158975543000.smt2                                   |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122159046263000.smt2                                   |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122159111771000.smt2                                   |  20.071s  |  20.071s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122159186002000.smt2                                   |  20.063s  |  20.063s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122159261633000.smt2                                   |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122159332862000.smt2                                   |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122159403986000.smt2                                   |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122159481142000.smt2                                   |  20.067s  |  20.067s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122159562443000.smt2                                   |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122159634866000.smt2                                   |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122159710089000.smt2                                   |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122159785134000.smt2                                   |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122159854689000.smt2                                   |  20.069s  |  20.069s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122159949354000.smt2                                   |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122160074078000.smt2                                   |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122160147862000.smt2                                   |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122160226399000.smt2                                   |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122160302695000.smt2                                   |  20.066s  |  20.066s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122160369171000.smt2                                   |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122160438423000.smt2                                   |  20.068s  |  20.068s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122160509725000.smt2                                   |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122160586488000.smt2                                   |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122160659837000.smt2                                   |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122160768427000.smt2                                   |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122160842660000.smt2                                   |  20.061s  |  20.061s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122160916832000.smt2                                   |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122160993928000.smt2                                   |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122161070638000.smt2                                   |  20.064s  |  20.064s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122161143523000.smt2                                   |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122161218629000.smt2                                   |  20.073s  |  20.073s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122161305558000.smt2                                   |  20.064s  |  20.064s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122161380852000.smt2                                   |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122161453859000.smt2                                   |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122161536492000.smt2                                   |  20.069s  |  20.069s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122161624064000.smt2                                   |  20.067s  |  20.067s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122161694623000.smt2                                   |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122161770075000.smt2                                   |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122161845529000.smt2                                   |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122161915939000.smt2                                   |  20.066s  |  20.066s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122161984448000.smt2                                   |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122162061143000.smt2                                   |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122162138158000.smt2                                   |  20.081s  |  20.081s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122162216838000.smt2                                   |  20.071s  |  20.071s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122162296854000.smt2                                   |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122162385128000.smt2                                   |  20.066s  |  20.066s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122162478775000.smt2                                   |  20.073s  |  20.073s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122162578216000.smt2                                   |  20.040s  |  20.040s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122162693063000.smt2                                   |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122162825547000.smt2                                   |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122162923417000.smt2                                   |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122163021069000.smt2                                   |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122163112461000.smt2                                   |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122163200386000.smt2                                   |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122163295147000.smt2                                   |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122163387527000.smt2                                   |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122163491096000.smt2                                   |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122163613984000.smt2                                   |  20.063s  |  20.063s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122163692549000.smt2                                   |  20.076s  |  20.076s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122163795660000.smt2                                   |  20.061s  |  20.061s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122163867996000.smt2                                   |  20.068s  |  20.068s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122163942276000.smt2                                   |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122164033784000.smt2                                   |  20.063s  |  20.063s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122164120299000.smt2                                   |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122164194350000.smt2                                   |  20.070s  |  20.070s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122164271268000.smt2                                   |  20.071s  |  20.071s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122164343885000.smt2                                   |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122164409891000.smt2                                   |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122164478996000.smt2                                   |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122164566032000.smt2                                   |  20.069s  |  20.069s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122164642173000.smt2                                   |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122164722785000.smt2                                   |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122164820609000.smt2                                   |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122164900203000.smt2                                   |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122164976684000.smt2                                   |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122165059204000.smt2                                   |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122165149053000.smt2                                   |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122165229333000.smt2                                   |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122165335664000.smt2                                   |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122165448756000.smt2                                   |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122165532692000.smt2                                   |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122165617076000.smt2                                   |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122165689806000.smt2                                   |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122165758848000.smt2                                   |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122165833645000.smt2                                   |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122165903477000.smt2                                   |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122165975170000.smt2                                   |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122166063245000.smt2                                   |  20.073s  |  20.073s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122166142662000.smt2                                   |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122166216193000.smt2                                   |  20.071s  |  20.071s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122166293091000.smt2                                   |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122166364014000.smt2                                   |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122166446582000.smt2                                   |  20.061s  |  20.061s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122166534921000.smt2                                   |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/FP/20200911-Pine/1599122166616114000.smt2                                   |  20.054s  |  20.054s  |   0.000s  | 0.0%|
</details>
