Comparing data and data


# SUMMARY
- LHS tests = 1683
- RHS tests = 1683
- LHS success = 1683  (100.0%)
- RHS success = 1683  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: AUFBVDTLIA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/AUFBVDTLIA.tar.zst?download=1
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
Job tag: AUFBVDTLIA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/AUFBVDTLIA.tar.zst?download=1
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
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-14.smt2-1.smt2  |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-14.smt2-2.smt2  |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-14.smt2-3.smt2  |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-17.smt2-1.smt2  |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-17.smt2-2.smt2  |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-17.smt2-3.smt2  |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-2.smt2-1.smt2  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-2.smt2-2.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-2.smt2-3.smt2  |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-24.smt2-1.smt2  |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-24.smt2-2.smt2  |  20.083s  |  20.083s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-24.smt2-3.smt2  |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-27.smt2-1.smt2  |  20.103s  |  20.103s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-27.smt2-2.smt2  |  20.137s  |  20.137s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-27.smt2-3.smt2  |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-4.smt2-1.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-4.smt2-2.smt2  |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-4.smt2-3.smt2  |  20.067s  |  20.067s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-13.smt2-1.smt2  |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-13.smt2-2.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-14.smt2-1.smt2  |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-14.smt2-2.smt2  |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-14.smt2-3.smt2  |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-17.smt2-1.smt2  |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-17.smt2-2.smt2  |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-17.smt2-3.smt2  |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-2.smt2-1.smt2  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-2.smt2-2.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-2.smt2-3.smt2  |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-24.smt2-1.smt2  |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-24.smt2-2.smt2  |  20.083s  |  20.083s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-24.smt2-3.smt2  |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-27.smt2-1.smt2  |  20.103s  |  20.103s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-27.smt2-2.smt2  |  20.137s  |  20.137s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-27.smt2-3.smt2  |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-4.smt2-1.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-4.smt2-2.smt2  |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-4.smt2-3.smt2  |  20.067s  |  20.067s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-13.smt2-1.smt2  |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-13.smt2-2.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-14.smt2-1.smt2  |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-14.smt2-2.smt2  |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-14.smt2-3.smt2  |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-17.smt2-1.smt2  |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-17.smt2-2.smt2  |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-17.smt2-3.smt2  |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-2.smt2-1.smt2  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-2.smt2-2.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-2.smt2-3.smt2  |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-24.smt2-1.smt2  |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-24.smt2-2.smt2  |  20.083s  |  20.083s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-24.smt2-3.smt2  |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-27.smt2-1.smt2  |  20.103s  |  20.103s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-27.smt2-2.smt2  |  20.137s  |  20.137s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-27.smt2-3.smt2  |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-4.smt2-1.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-4.smt2-2.smt2  |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-4.smt2-3.smt2  |  20.067s  |  20.067s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-13.smt2-1.smt2  |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-13.smt2-2.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-14.smt2-1.smt2  |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-14.smt2-2.smt2  |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-14.smt2-3.smt2  |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-17.smt2-1.smt2  |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-17.smt2-2.smt2  |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-17.smt2-3.smt2  |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-2.smt2-1.smt2  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-2.smt2-2.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-2.smt2-3.smt2  |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-24.smt2-1.smt2  |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-24.smt2-2.smt2  |  20.083s  |  20.083s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-24.smt2-3.smt2  |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-27.smt2-1.smt2  |  20.103s  |  20.103s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-27.smt2-2.smt2  |  20.137s  |  20.137s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-27.smt2-3.smt2  |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-4.smt2-1.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-4.smt2-2.smt2  |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-4.smt2-3.smt2  |  20.067s  |  20.067s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-13.smt2-1.smt2  |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-13.smt2-2.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-111.smt2 |  21.712s |4361.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-AVLTree.scala-27.smt2 |  21.548s |3604.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Compiler.scala-7.smt2 |  21.469s |3183.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-81.smt2-3.smt2 |  21.467s |3859.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-5.smt2 |  21.341s |3316.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-5.smt2-1.smt2 |  21.325s |3434.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-HeapSort.scala-9.smt2 |  21.294s |3180.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-81.smt2 |  21.285s |2924.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-113.smt2-2.smt2 |  21.197s |2936.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-36.smt2 |  21.161s |2399.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-9.smt2-3.smt2 |  21.160s |3456.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-116.smt2-1.smt2 |  21.151s |3063.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-25.smt2-3.smt2 |  21.141s |3552.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-89.smt2 |  21.103s |4353.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-105.smt2 |  21.079s |2510.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-112.smt2 |  21.066s |4305.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-69.smt2-3.smt2 |  21.059s |2243.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-36.smt2-2.smt2 |  21.052s |2472.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-AVLTree.scala-24.smt2 |  21.032s |3395.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-9.smt2 |  20.993s |1806.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-111.smt2 |  21.712s |4361.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-AVLTree.scala-27.smt2 |  21.548s |3604.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Compiler.scala-7.smt2 |  21.469s |3183.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-81.smt2-3.smt2 |  21.467s |3859.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-5.smt2 |  21.341s |3316.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-5.smt2-1.smt2 |  21.325s |3434.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-HeapSort.scala-9.smt2 |  21.294s |3180.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-81.smt2 |  21.285s |2924.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-113.smt2-2.smt2 |  21.197s |2936.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-36.smt2 |  21.161s |2399.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-9.smt2-3.smt2 |  21.160s |3456.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-116.smt2-1.smt2 |  21.151s |3063.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-25.smt2-3.smt2 |  21.141s |3552.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-89.smt2 |  21.103s |4353.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-105.smt2 |  21.079s |2510.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-112.smt2 |  21.066s |4305.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-69.smt2-3.smt2 |  21.059s |2243.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-36.smt2-2.smt2 |  21.052s |2472.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-AVLTree.scala-24.smt2 |  21.032s |3395.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-9.smt2 |  20.993s |1806.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-14.smt2-1.smt2  |107.0MiB|107.0MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-14.smt2-2.smt2  |92.216MiB|92.216MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-14.smt2-3.smt2  |142.0MiB|142.0MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-17.smt2-1.smt2  |98.208MiB|98.208MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-17.smt2-2.smt2  |89.804MiB|89.804MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-17.smt2-3.smt2  |113.0MiB|113.0MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-2.smt2-1.smt2  |20.636MiB|20.636MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-2.smt2-2.smt2  |53.388MiB|53.388MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-2.smt2-3.smt2  |50.312MiB|50.312MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-24.smt2-1.smt2  |235.0MiB|235.0MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-24.smt2-2.smt2  |327.0MiB|327.0MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-24.smt2-3.smt2  |172.0MiB|172.0MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-27.smt2-1.smt2  |497.0MiB|497.0MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-27.smt2-2.smt2  |500.0MiB|500.0MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-27.smt2-3.smt2  |87.492MiB|87.492MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-4.smt2-1.smt2  |20.66MiB|20.66MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-4.smt2-2.smt2  |87.016MiB|87.016MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-4.smt2-3.smt2  |90.62MiB|90.62MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-13.smt2-1.smt2  |58.46MiB|58.46MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-13.smt2-2.smt2  |60.944MiB|60.944MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-14.smt2-1.smt2  |107.0MiB|107.0MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-14.smt2-2.smt2  |92.216MiB|92.216MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-14.smt2-3.smt2  |142.0MiB|142.0MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-17.smt2-1.smt2  |98.208MiB|98.208MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-17.smt2-2.smt2  |89.804MiB|89.804MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-17.smt2-3.smt2  |113.0MiB|113.0MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-2.smt2-1.smt2  |20.636MiB|20.636MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-2.smt2-2.smt2  |53.388MiB|53.388MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-2.smt2-3.smt2  |50.312MiB|50.312MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-24.smt2-1.smt2  |235.0MiB|235.0MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-24.smt2-2.smt2  |327.0MiB|327.0MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-24.smt2-3.smt2  |172.0MiB|172.0MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-27.smt2-1.smt2  |497.0MiB|497.0MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-27.smt2-2.smt2  |500.0MiB|500.0MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-27.smt2-3.smt2  |87.492MiB|87.492MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-4.smt2-1.smt2  |20.66MiB|20.66MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-4.smt2-2.smt2  |87.016MiB|87.016MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-4.smt2-3.smt2  |90.62MiB|90.62MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-13.smt2-1.smt2  |58.46MiB|58.46MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-13.smt2-2.smt2  |60.944MiB|60.944MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-14.smt2-1.smt2  |107.0MiB|107.0MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-14.smt2-2.smt2  |92.216MiB|92.216MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-14.smt2-3.smt2  |142.0MiB|142.0MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-17.smt2-1.smt2  |98.208MiB|98.208MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-17.smt2-2.smt2  |89.804MiB|89.804MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-17.smt2-3.smt2  |113.0MiB|113.0MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-2.smt2-1.smt2  |20.636MiB|20.636MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-2.smt2-2.smt2  |53.388MiB|53.388MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-2.smt2-3.smt2  |50.312MiB|50.312MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-24.smt2-1.smt2  |235.0MiB|235.0MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-24.smt2-2.smt2  |327.0MiB|327.0MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-24.smt2-3.smt2  |172.0MiB|172.0MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-27.smt2-1.smt2  |497.0MiB|497.0MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-27.smt2-2.smt2  |500.0MiB|500.0MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-27.smt2-3.smt2  |87.492MiB|87.492MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-4.smt2-1.smt2  |20.66MiB|20.66MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-4.smt2-2.smt2  |87.016MiB|87.016MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-4.smt2-3.smt2  |90.62MiB|90.62MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-13.smt2-1.smt2  |58.46MiB|58.46MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-13.smt2-2.smt2  |60.944MiB|60.944MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-14.smt2-1.smt2  |107.0MiB|107.0MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-14.smt2-2.smt2  |92.216MiB|92.216MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-14.smt2-3.smt2  |142.0MiB|142.0MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-17.smt2-1.smt2  |98.208MiB|98.208MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-17.smt2-2.smt2  |89.804MiB|89.804MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-17.smt2-3.smt2  |113.0MiB|113.0MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-2.smt2-1.smt2  |20.636MiB|20.636MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-2.smt2-2.smt2  |53.388MiB|53.388MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-2.smt2-3.smt2  |50.312MiB|50.312MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-24.smt2-1.smt2  |235.0MiB|235.0MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-24.smt2-2.smt2  |327.0MiB|327.0MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-24.smt2-3.smt2  |172.0MiB|172.0MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-27.smt2-1.smt2  |497.0MiB|497.0MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-27.smt2-2.smt2  |500.0MiB|500.0MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-27.smt2-3.smt2  |87.492MiB|87.492MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-4.smt2-1.smt2  |20.66MiB|20.66MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-4.smt2-2.smt2  |87.016MiB|87.016MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-4.smt2-3.smt2  |90.62MiB|90.62MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-13.smt2-1.smt2  |58.46MiB|58.46MiB|0B| 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-13.smt2-2.smt2  |60.944MiB|60.944MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-112.smt2-3.smt2 |  20.740s |4625.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-111.smt2-3.smt2 |  20.773s |4479.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-36.smt2-1.smt2 |  20.793s |4432.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-111.smt2 |  21.712s |4361.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-89.smt2 |  21.103s |4353.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-112.smt2-1.smt2 |  20.841s |4349.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-111.smt2-1.smt2 |  20.832s |4318.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-111.smt2-2.smt2 |  20.630s |4318.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-112.smt2 |  21.066s |4305.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Compiler.scala-7.smt2 |  20.504s |3998.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-89.smt2-2.smt2 |  20.572s |3996.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-81.smt2-3.smt2 |  21.467s |3859.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-8.smt2-2.smt2 |  20.607s |3667.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-9.smt2-1.smt2 |  20.955s |3666.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-89.smt2-1.smt2 |  20.708s |3651.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-27.smt2-1.smt2 |  20.963s |3608.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-AVLTree.scala-27.smt2 |  21.548s |3604.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-27.smt2-2.smt2 |  20.689s |3596.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-27.smt2-3.smt2 |  20.753s |3591.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-25.smt2-3.smt2 |  21.141s |3552.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-112.smt2-3.smt2 |  20.740s |4625.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-111.smt2-3.smt2 |  20.773s |4479.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-36.smt2-1.smt2 |  20.793s |4432.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-111.smt2 |  21.712s |4361.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-89.smt2 |  21.103s |4353.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-112.smt2-1.smt2 |  20.841s |4349.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-111.smt2-1.smt2 |  20.832s |4318.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-111.smt2-2.smt2 |  20.630s |4318.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-112.smt2 |  21.066s |4305.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Compiler.scala-7.smt2 |  20.504s |3998.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-89.smt2-2.smt2 |  20.572s |3996.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-81.smt2-3.smt2 |  21.467s |3859.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-8.smt2-2.smt2 |  20.607s |3667.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-9.smt2-1.smt2 |  20.955s |3666.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-89.smt2-1.smt2 |  20.708s |3651.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-27.smt2-1.smt2 |  20.963s |3608.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-AVLTree.scala-27.smt2 |  21.548s |3604.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-27.smt2-2.smt2 |  20.689s |3596.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-27.smt2-3.smt2 |  20.753s |3591.0MiB|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-25.smt2-3.smt2 |  21.141s |3552.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-14.smt2-1.smt2  |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-14.smt2-2.smt2  |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-14.smt2-3.smt2  |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-17.smt2-1.smt2  |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-17.smt2-2.smt2  |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-17.smt2-3.smt2  |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-2.smt2-1.smt2  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-2.smt2-2.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-2.smt2-3.smt2  |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-24.smt2-1.smt2  |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-24.smt2-2.smt2  |  20.083s  |  20.083s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-24.smt2-3.smt2  |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-27.smt2-1.smt2  |  20.103s  |  20.103s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-27.smt2-2.smt2  |  20.137s  |  20.137s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-27.smt2-3.smt2  |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-4.smt2-1.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-4.smt2-2.smt2  |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-4.smt2-3.smt2  |  20.067s  |  20.067s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-13.smt2-1.smt2  |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-13.smt2-2.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-13.smt2-3.smt2  |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-4.smt2-1.smt2  |  20.440s  |  20.440s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-4.smt2-2.smt2  |  20.171s  |  20.171s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-4.smt2-3.smt2  |  20.152s  |  20.152s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-6.smt2-1.smt2  |  20.593s  |  20.593s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-6.smt2-2.smt2  |  20.369s  |  20.369s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-6.smt2-3.smt2  |  20.290s  |  20.290s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AmortizedQueue.scala-1.smt2-1.smt2  |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AmortizedQueue.scala-1.smt2-2.smt2  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AmortizedQueue.scala-1.smt2-3.smt2  |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ArrayBinarySearch.scala-1.smt2-1.smt2  |  20.603s  |  20.603s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ArrayBinarySearch.scala-1.smt2-2.smt2  |  20.290s  |  20.290s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ArrayBinarySearch.scala-1.smt2-3.smt2  |  20.523s  |  20.523s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BinarySearchTree.scala-1.smt2-1.smt2  |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BinarySearchTree.scala-1.smt2-2.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BinarySearchTree.scala-1.smt2-3.smt2  |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BinaryTrie.scala-1.smt2-1.smt2  |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BinaryTrie.scala-1.smt2-2.smt2  |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BinaryTrie.scala-1.smt2-3.smt2  |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BinaryTrie.scala-3.smt2-1.smt2  |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BinaryTrie.scala-3.smt2-2.smt2  |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BinaryTrie.scala-3.smt2-3.smt2  |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BinaryTrie.scala-5.smt2-1.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BinaryTrie.scala-5.smt2-2.smt2  |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BinaryTrie.scala-5.smt2-3.smt2  |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BinaryTrie.scala-9.smt2-1.smt2  |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BinaryTrie.scala-9.smt2-2.smt2  |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-13.smt2-1.smt2  |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-13.smt2-2.smt2  |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-13.smt2-3.smt2  |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-14.smt2-1.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-18.smt2-1.smt2  |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-18.smt2-2.smt2  |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-18.smt2-3.smt2  |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-19.smt2-1.smt2  |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-19.smt2-2.smt2  |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-19.smt2-3.smt2  |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-7.smt2-1.smt2  |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-7.smt2-2.smt2  |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-7.smt2-3.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-8.smt2-1.smt2  |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-8.smt2-2.smt2  |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-8.smt2-3.smt2  |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Compiler.scala-7.smt2-1.smt2  |  20.570s  |  20.570s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Compiler.scala-7.smt2-2.smt2  |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Compiler.scala-7.smt2-3.smt2  |  20.538s  |  20.538s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-10.smt2-1.smt2  |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-10.smt2-2.smt2  |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-10.smt2-3.smt2  |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-11.smt2-1.smt2  |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-13.smt2-1.smt2  |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-13.smt2-2.smt2  |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-13.smt2-3.smt2  |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-16.smt2-2.smt2  |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-16.smt2-3.smt2  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-17.smt2-1.smt2  |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-17.smt2-3.smt2  |  20.089s  |  20.089s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-18.smt2-1.smt2  |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-18.smt2-2.smt2  |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-18.smt2-3.smt2  |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-19.smt2-1.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-19.smt2-2.smt2  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-19.smt2-3.smt2  |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-2.smt2-1.smt2  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-2.smt2-2.smt2  |  20.067s  |  20.067s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-2.smt2-3.smt2  |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-20.smt2-1.smt2  |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-20.smt2-2.smt2  |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-20.smt2-3.smt2  |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-22.smt2-1.smt2  |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-22.smt2-2.smt2  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-22.smt2-3.smt2  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-4.smt2-1.smt2  |  20.074s  |  20.074s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-4.smt2-2.smt2  |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-4.smt2-3.smt2  |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-5.smt2-1.smt2  |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-5.smt2-2.smt2  |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-5.smt2-3.smt2  |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-8.smt2-1.smt2  |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-9.smt2-1.smt2  |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-9.smt2-2.smt2  |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-9.smt2-3.smt2  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-1.smt2-1.smt2  |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-1.smt2-2.smt2  |   2.224s  |   2.224s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-1.smt2-3.smt2  |   1.820s  |   1.820s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-14.smt2-1.smt2  |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-14.smt2-2.smt2  |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-14.smt2-3.smt2  |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-19.smt2-1.smt2  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-19.smt2-2.smt2  |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-19.smt2-3.smt2  |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-21.smt2-1.smt2  |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-21.smt2-2.smt2  |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-21.smt2-3.smt2  |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-25.smt2-1.smt2  |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-25.smt2-2.smt2  |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-25.smt2-3.smt2  |  20.047s  |  20.047s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-5.smt2-1.smt2  |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-5.smt2-2.smt2  |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-5.smt2-3.smt2  |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-9.smt2-1.smt2  |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-9.smt2-2.smt2  |  20.081s  |  20.081s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-9.smt2-3.smt2  |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-InsertionSort.scala-1.smt2-1.smt2  |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-InsertionSort.scala-1.smt2-2.smt2  |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-InsertionSort.scala-1.smt2-3.smt2  |   7.306s  |   7.306s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Interpreter.scala-3.smt2-1.smt2  |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Interpreter.scala-3.smt2-2.smt2  |  20.083s  |  20.083s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Interpreter.scala-3.smt2-3.smt2  |  20.061s  |  20.061s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LambdaEval.scala-20.smt2-1.smt2  |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LambdaEval.scala-20.smt2-2.smt2  |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LambdaEval.scala-20.smt2-3.smt2  |  20.047s  |  20.047s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LambdaEval.scala-6.smt2-1.smt2  |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LambdaEval.scala-6.smt2-2.smt2  |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LambdaEval.scala-6.smt2-3.smt2  |  20.047s  |  20.047s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LeftistHeap.scala-1.smt2-1.smt2  |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LeftistHeap.scala-1.smt2-2.smt2  |   1.950s  |   1.950s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LeftistHeap.scala-1.smt2-3.smt2  |   1.894s  |   1.894s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LeftistHeap.scala-13.smt2-1.smt2  |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LeftistHeap.scala-13.smt2-2.smt2  |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LeftistHeap.scala-13.smt2-3.smt2  |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LeftistHeap.scala-5.smt2-1.smt2  |  20.110s  |  20.110s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LeftistHeap.scala-5.smt2-2.smt2  |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LeftistHeap.scala-5.smt2-3.smt2  |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LeftistHeap.scala-8.smt2-1.smt2  |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LeftistHeap.scala-8.smt2-2.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LeftistHeap.scala-8.smt2-3.smt2  |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-1.smt2-1.smt2  |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-1.smt2-2.smt2  |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-1.smt2-3.smt2  |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-10.smt2-1.smt2  |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-10.smt2-2.smt2  |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-10.smt2-3.smt2  |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-16.smt2-1.smt2  |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-16.smt2-2.smt2  |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-16.smt2-3.smt2  |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-3.smt2-1.smt2  |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-3.smt2-2.smt2  |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-3.smt2-3.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-5.smt2-1.smt2  |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-5.smt2-2.smt2  |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-5.smt2-3.smt2  |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Lists5.scala-4.smt2-1.smt2  |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Lists5.scala-4.smt2-2.smt2  |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Lists5.scala-4.smt2-3.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Map.scala-1.smt2-1.smt2  |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Map.scala-1.smt2-2.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Map.scala-1.smt2-3.smt2  |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Map.scala-2.smt2-1.smt2  |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Map.scala-2.smt2-2.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Map.scala-2.smt2-3.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-MutuallyRecursive.scala-1.smt2-1.smt2  |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-MutuallyRecursive.scala-1.smt2-2.smt2  |  20.340s  |  20.340s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-MutuallyRecursive.scala-1.smt2-3.smt2  |  20.117s  |  20.117s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-10.smt2-1.smt2  |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-10.smt2-2.smt2  |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-10.smt2-3.smt2  |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-11.smt2-1.smt2  |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-11.smt2-2.smt2  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-11.smt2-3.smt2  |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-12.smt2-1.smt2  |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-12.smt2-2.smt2  |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-12.smt2-3.smt2  |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-13.smt2-1.smt2  |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-13.smt2-2.smt2  |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-13.smt2-3.smt2  |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-14.smt2-1.smt2  |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-14.smt2-2.smt2  |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-14.smt2-3.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-2.smt2-1.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-3.smt2-1.smt2  |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-3.smt2-2.smt2  |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-3.smt2-3.smt2  |   0.472s  |   0.472s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-5.smt2-1.smt2  |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-5.smt2-2.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-5.smt2-3.smt2  |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-6.smt2-1.smt2  |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-6.smt2-2.smt2  |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-6.smt2-3.smt2  |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-7.smt2-1.smt2  |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-7.smt2-2.smt2  |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-7.smt2-3.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-9.smt2-1.smt2  |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-9.smt2-2.smt2  |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-9.smt2-3.smt2  |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Parser.scala-1.smt2-1.smt2  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Parser.scala-1.smt2-2.smt2  |   1.514s  |   1.514s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Parser.scala-1.smt2-3.smt2  |   1.613s  |   1.613s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Parser.scala-3.smt2-1.smt2  |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Parser.scala-3.smt2-2.smt2  |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Parser.scala-3.smt2-3.smt2  |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Parser.scala-5.smt2-1.smt2  |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Parser.scala-5.smt2-2.smt2  |  20.105s  |  20.105s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Parser.scala-5.smt2-3.smt2  |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Parser.scala-9.smt2-1.smt2  |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PositiveMap.scala-2.smt2-1.smt2  |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PositiveMap.scala-2.smt2-2.smt2  |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PositiveMap.scala-2.smt2-3.smt2  |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-1.smt2-1.smt2  |  20.096s  |  20.096s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-1.smt2-2.smt2  |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-1.smt2-3.smt2  |  20.085s  |  20.085s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-15.smt2-1.smt2  |  20.070s  |  20.070s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-15.smt2-2.smt2  |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-15.smt2-3.smt2  |  20.094s  |  20.094s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-16.smt2-1.smt2  |  20.066s  |  20.066s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-16.smt2-2.smt2  |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-16.smt2-3.smt2  |  20.087s  |  20.087s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-17.smt2-1.smt2  |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-17.smt2-2.smt2  |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-17.smt2-3.smt2  |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-18.smt2-1.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-18.smt2-2.smt2  |  20.102s  |  20.102s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-18.smt2-3.smt2  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-19.smt2-1.smt2  |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-19.smt2-2.smt2  |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-19.smt2-3.smt2  |  20.075s  |  20.075s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-20.smt2-1.smt2  |  20.069s  |  20.069s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-20.smt2-2.smt2  |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-20.smt2-3.smt2  |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-21.smt2-1.smt2  |  20.138s  |  20.138s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-21.smt2-2.smt2  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-21.smt2-3.smt2  |  20.099s  |  20.099s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-22.smt2-1.smt2  |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-22.smt2-2.smt2  |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-23.smt2-1.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-23.smt2-2.smt2  |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-24.smt2-1.smt2  |  20.068s  |  20.068s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-24.smt2-2.smt2  |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-24.smt2-3.smt2  |  20.089s  |  20.089s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-25.smt2-1.smt2  |  20.121s  |  20.121s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-25.smt2-2.smt2  |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-25.smt2-3.smt2  |  20.125s  |  20.125s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-26.smt2-1.smt2  |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-26.smt2-2.smt2  |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-26.smt2-3.smt2  |  20.115s  |  20.115s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-27.smt2-1.smt2  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-27.smt2-2.smt2  |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-28.smt2-1.smt2  |  20.075s  |  20.075s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-28.smt2-2.smt2  |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-29.smt2-1.smt2  |  20.087s  |  20.087s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-29.smt2-2.smt2  |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-29.smt2-3.smt2  |  20.116s  |  20.116s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-4.smt2-1.smt2  |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-4.smt2-2.smt2  |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-4.smt2-3.smt2  |  20.149s  |  20.149s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-13.smt2-1.smt2  |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-13.smt2-2.smt2  |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-13.smt2-3.smt2  |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-14.smt2-1.smt2  |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-14.smt2-2.smt2  |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-14.smt2-3.smt2  |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-17.smt2-1.smt2  |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-17.smt2-2.smt2  |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-17.smt2-3.smt2  |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-18.smt2-1.smt2  |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-18.smt2-2.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-18.smt2-3.smt2  |   2.688s  |   2.688s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-21.smt2-1.smt2  |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-21.smt2-2.smt2  |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-21.smt2-3.smt2  |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-22.smt2-1.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-22.smt2-2.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-22.smt2-3.smt2  |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-24.smt2-1.smt2  |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-24.smt2-2.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-24.smt2-3.smt2  |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-25.smt2-1.smt2  |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-25.smt2-2.smt2  |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-25.smt2-3.smt2  |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-27.smt2-1.smt2  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-27.smt2-2.smt2  |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-27.smt2-3.smt2  |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-28.smt2-1.smt2  |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-28.smt2-2.smt2  |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-28.smt2-3.smt2  |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-29.smt2-1.smt2  |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-29.smt2-2.smt2  |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-29.smt2-3.smt2  |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-30.smt2-1.smt2  |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-30.smt2-2.smt2  |  20.067s  |  20.067s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-30.smt2-3.smt2  |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-31.smt2-1.smt2  |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-31.smt2-2.smt2  |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-31.smt2-3.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-32.smt2-1.smt2  |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-32.smt2-2.smt2  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-32.smt2-3.smt2  |   2.276s  |   2.276s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SearchLinkedList.scala-1.smt2-1.smt2  |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SearchLinkedList.scala-1.smt2-2.smt2  |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SearchLinkedList.scala-1.smt2-3.smt2  |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SearchLinkedList.scala-4.smt2-1.smt2  |  20.040s  |  20.040s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SearchLinkedList.scala-4.smt2-2.smt2  |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SearchLinkedList.scala-4.smt2-3.smt2  |  20.091s  |  20.091s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SearchLinkedList.scala-7.smt2-1.smt2  |  20.096s  |  20.096s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SearchLinkedList.scala-7.smt2-2.smt2  |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SearchLinkedList.scala-7.smt2-3.smt2  |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SecondsToTime.scala-1.smt2-1.smt2  |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SecondsToTime.scala-1.smt2-2.smt2  |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SecondsToTime.scala-1.smt2-3.smt2  |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SecondsToTime.scala-3.smt2-1.smt2  |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SecondsToTime.scala-3.smt2-2.smt2  |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SecondsToTime.scala-3.smt2-3.smt2  |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SecondsToTime.scala-5.smt2-1.smt2  |   7.649s  |   7.649s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SecondsToTime.scala-5.smt2-2.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SecondsToTime.scala-5.smt2-3.smt2  |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SecondsToTime.scala-8.smt2-1.smt2  |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SecondsToTime.scala-8.smt2-2.smt2  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SecondsToTime.scala-8.smt2-3.smt2  |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-1.smt2-1.smt2  |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-1.smt2-2.smt2  |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-1.smt2-3.smt2  |  20.097s  |  20.097s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-10.smt2-1.smt2  |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-10.smt2-2.smt2  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-10.smt2-3.smt2  |  20.095s  |  20.095s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-12.smt2-1.smt2  |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-12.smt2-2.smt2  |  20.077s  |  20.077s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-12.smt2-3.smt2  |  20.104s  |  20.104s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-13.smt2-1.smt2  |  20.069s  |  20.069s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-13.smt2-2.smt2  |  20.116s  |  20.116s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-13.smt2-3.smt2  |  20.074s  |  20.074s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-14.smt2-1.smt2  |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-14.smt2-2.smt2  |  20.097s  |  20.097s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-14.smt2-3.smt2  |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-15.smt2-1.smt2  |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-15.smt2-2.smt2  |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-15.smt2-3.smt2  |  20.087s  |  20.087s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-2.smt2-1.smt2  |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-2.smt2-2.smt2  |  20.075s  |  20.075s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-2.smt2-3.smt2  |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-3.smt2-1.smt2  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-3.smt2-2.smt2  |  20.040s  |  20.040s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-3.smt2-3.smt2  |  20.067s  |  20.067s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-7.smt2-1.smt2  |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-7.smt2-2.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-7.smt2-3.smt2  |  20.097s  |  20.097s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-8.smt2-1.smt2  |  20.078s  |  20.078s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-8.smt2-2.smt2  |  20.088s  |  20.088s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-8.smt2-3.smt2  |  20.085s  |  20.085s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-9.smt2-1.smt2  |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-9.smt2-2.smt2  |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-9.smt2-3.smt2  |  20.067s  |  20.067s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SimpInterpret.scala-3.smt2-1.smt2  |  20.064s  |  20.064s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SimpInterpret.scala-3.smt2-2.smt2  |  20.063s  |  20.063s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SimpInterpret.scala-3.smt2-3.smt2  |  20.075s  |  20.075s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SortedList.scala-1.smt2-1.smt2  |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SortedList.scala-1.smt2-2.smt2  |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SortedList.scala-1.smt2-3.smt2  |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SortedNDList.scala-2.smt2-1.smt2  |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SortedNDList.scala-2.smt2-2.smt2  |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SortedNDList.scala-2.smt2-3.smt2  |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SortedNDList.scala-3.smt2-1.smt2  |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SortedNDList.scala-3.smt2-2.smt2  |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SortedNDList.scala-3.smt2-3.smt2  |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SumAndMax.scala-4.smt2-1.smt2  |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SumAndMax.scala-4.smt2-2.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SumAndMax.scala-4.smt2-3.smt2  |   7.296s  |   7.296s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SumAndMax.scala-7.smt2-1.smt2  |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SumAndMax.scala-7.smt2-2.smt2  |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SumAndMax.scala-7.smt2-3.smt2  |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Sync.scala-1.smt2-1.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Sync.scala-1.smt2-2.smt2  |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Sync.scala-1.smt2-3.smt2  |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-TwoSizeFunctions.scala-1.smt2-1.smt2  |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-TwoSizeFunctions.scala-1.smt2-2.smt2  |   1.046s  |   1.046s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-TwoSizeFunctions.scala-1.smt2-3.smt2  |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-TwoSizeFunctions.scala-4.smt2-1.smt2  |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-TwoSizeFunctions.scala-4.smt2-2.smt2  |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-TwoSizeFunctions.scala-4.smt2-3.smt2  |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-muDot2.scala-41.smt2-1.smt2  |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-muDot2.scala-41.smt2-2.smt2  |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-muDot2.scala-41.smt2-3.smt2  |  20.079s  |  20.079s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-muDot2.scala-43.smt2-1.smt2  |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-muDot2.scala-43.smt2-2.smt2  |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-muDot2.scala-43.smt2-3.smt2  |  20.047s  |  20.047s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-100.smt2-1.smt2  |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-100.smt2-2.smt2  |  20.094s  |  20.094s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-100.smt2-3.smt2  |   0.367s  |   0.367s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-101.smt2-1.smt2  |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-101.smt2-2.smt2  |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-101.smt2-3.smt2  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-102.smt2-1.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-102.smt2-2.smt2  |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-102.smt2-3.smt2  |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-103.smt2-1.smt2  |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-103.smt2-2.smt2  |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-103.smt2-3.smt2  |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-104.smt2-1.smt2  |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-104.smt2-2.smt2  |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-104.smt2-3.smt2  |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-105.smt2-1.smt2  |  20.063s  |  20.063s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-105.smt2-2.smt2  |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-105.smt2-3.smt2  |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-106.smt2-1.smt2  |  20.104s  |  20.104s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-106.smt2-2.smt2  |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-106.smt2-3.smt2  |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-107.smt2-1.smt2  |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-107.smt2-2.smt2  |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-107.smt2-3.smt2  |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-108.smt2-1.smt2  |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-108.smt2-2.smt2  |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-108.smt2-3.smt2  |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-109.smt2-1.smt2  |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-110.smt2-1.smt2  |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-110.smt2-2.smt2  |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-110.smt2-3.smt2  |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-111.smt2-1.smt2  |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-111.smt2-2.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-111.smt2-3.smt2  |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-112.smt2-1.smt2  |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-112.smt2-2.smt2  |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-112.smt2-3.smt2  |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-113.smt2-1.smt2  |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-113.smt2-2.smt2  |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-113.smt2-3.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-114.smt2-1.smt2  |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-114.smt2-2.smt2  |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-114.smt2-3.smt2  |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-115.smt2-1.smt2  |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-115.smt2-2.smt2  |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-115.smt2-3.smt2  |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-116.smt2-1.smt2  |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-116.smt2-2.smt2  |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-116.smt2-3.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-36.smt2-1.smt2  |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-36.smt2-2.smt2  |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-36.smt2-3.smt2  |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-37.smt2-1.smt2  |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-37.smt2-2.smt2  |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-37.smt2-3.smt2  |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-38.smt2-1.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-38.smt2-2.smt2  |  20.069s  |  20.069s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-38.smt2-3.smt2  |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-39.smt2-1.smt2  |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-39.smt2-2.smt2  |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-39.smt2-3.smt2  |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-40.smt2-1.smt2  |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-40.smt2-2.smt2  |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-40.smt2-3.smt2  |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-41.smt2-1.smt2  |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-41.smt2-2.smt2  |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-41.smt2-3.smt2  |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-42.smt2-1.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-42.smt2-2.smt2  |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-42.smt2-3.smt2  |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-43.smt2-1.smt2  |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-43.smt2-2.smt2  |  20.068s  |  20.068s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-43.smt2-3.smt2  |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-44.smt2-1.smt2  |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-44.smt2-2.smt2  |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-44.smt2-3.smt2  |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-45.smt2-1.smt2  |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-46.smt2-1.smt2  |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-47.smt2-1.smt2  |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-47.smt2-2.smt2  |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-47.smt2-3.smt2  |  20.067s  |  20.067s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-48.smt2-1.smt2  |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-48.smt2-2.smt2  |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-48.smt2-3.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-49.smt2-1.smt2  |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-50.smt2-1.smt2  |   0.383s  |   0.383s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-50.smt2-2.smt2  |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-50.smt2-3.smt2  |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-51.smt2-1.smt2  |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-51.smt2-2.smt2  |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-51.smt2-3.smt2  |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-52.smt2-1.smt2  |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-52.smt2-2.smt2  |  20.040s  |  20.040s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-52.smt2-3.smt2  |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-53.smt2-1.smt2  |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-54.smt2-1.smt2  |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-54.smt2-2.smt2  |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-54.smt2-3.smt2  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-55.smt2-1.smt2  |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-55.smt2-2.smt2  |   0.246s  |   0.246s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-55.smt2-3.smt2  |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-56.smt2-1.smt2  |   0.281s  |   0.281s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-56.smt2-3.smt2  |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-57.smt2-1.smt2  |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-57.smt2-2.smt2  |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-57.smt2-3.smt2  |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-58.smt2-1.smt2  |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-58.smt2-2.smt2  |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-58.smt2-3.smt2  |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-59.smt2-1.smt2  |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-59.smt2-2.smt2  |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-59.smt2-3.smt2  |   0.693s  |   0.693s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-60.smt2-1.smt2  |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-60.smt2-2.smt2  |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-60.smt2-3.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-61.smt2-1.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-61.smt2-2.smt2  |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-61.smt2-3.smt2  |   0.641s  |   0.641s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-62.smt2-1.smt2  |   1.685s  |   1.685s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-63.smt2-1.smt2  |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-64.smt2-1.smt2  |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-64.smt2-2.smt2  |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-64.smt2-3.smt2  |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-65.smt2-1.smt2  |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-65.smt2-3.smt2  |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-66.smt2-1.smt2  |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-66.smt2-2.smt2  |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-66.smt2-3.smt2  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-67.smt2-1.smt2  |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-67.smt2-2.smt2  |  15.414s  |  15.414s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-67.smt2-3.smt2  |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-68.smt2-1.smt2  |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-68.smt2-2.smt2  |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-69.smt2-1.smt2  |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-69.smt2-2.smt2  |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-69.smt2-3.smt2  |  20.096s  |  20.096s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-70.smt2-1.smt2  |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-70.smt2-2.smt2  |  20.067s  |  20.067s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-70.smt2-3.smt2  |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-71.smt2-1.smt2  |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-72.smt2-1.smt2  |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-72.smt2-2.smt2  |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-72.smt2-3.smt2  |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-73.smt2-1.smt2  |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-73.smt2-2.smt2  |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-73.smt2-3.smt2  |   1.180s  |   1.180s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-76.smt2-1.smt2  |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-76.smt2-2.smt2  |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-76.smt2-3.smt2  |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-78.smt2-1.smt2  |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-79.smt2-1.smt2  |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-79.smt2-2.smt2  |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-79.smt2-3.smt2  |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-80.smt2-1.smt2  |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-80.smt2-2.smt2  |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-80.smt2-3.smt2  |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-81.smt2-1.smt2  |   3.828s  |   3.828s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-81.smt2-2.smt2  |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-81.smt2-3.smt2  |   0.309s  |   0.309s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-82.smt2-1.smt2  |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-82.smt2-2.smt2  |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-82.smt2-3.smt2  |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-83.smt2-1.smt2  |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-83.smt2-2.smt2  |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-83.smt2-3.smt2  |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-84.smt2-1.smt2  |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-84.smt2-2.smt2  |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-84.smt2-3.smt2  |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-85.smt2-1.smt2  |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-85.smt2-2.smt2  |   0.565s  |   0.565s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-85.smt2-3.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-86.smt2-1.smt2  |  20.066s  |  20.066s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-86.smt2-2.smt2  |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-87.smt2-1.smt2  |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-87.smt2-2.smt2  |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-87.smt2-3.smt2  |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-88.smt2-1.smt2  |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-88.smt2-2.smt2  |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-88.smt2-3.smt2  |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-89.smt2-1.smt2  |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-89.smt2-2.smt2  |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-89.smt2-3.smt2  |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-90.smt2-1.smt2  |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-90.smt2-2.smt2  |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-90.smt2-3.smt2  |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-91.smt2-1.smt2  |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-92.smt2-1.smt2  |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-92.smt2-2.smt2  |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-92.smt2-3.smt2  |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-93.smt2-1.smt2  |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-93.smt2-2.smt2  |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-93.smt2-3.smt2  |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-94.smt2-1.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-94.smt2-2.smt2  |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-94.smt2-3.smt2  |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-95.smt2-1.smt2  |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-95.smt2-2.smt2  |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-95.smt2-3.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-96.smt2-1.smt2  |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-96.smt2-2.smt2  |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-96.smt2-3.smt2  |  20.061s  |  20.061s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-97.smt2-1.smt2  |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-97.smt2-2.smt2  |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-97.smt2-3.smt2  |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-98.smt2-1.smt2  |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-98.smt2-2.smt2  |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-98.smt2-3.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-99.smt2-1.smt2  |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-99.smt2-2.smt2  |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-99.smt2-3.smt2  |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-14.smt2  |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-17.smt2  |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-2.smt2  |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-24.smt2  |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-27.smt2  |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-4.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-13.smt2  |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-4.smt2  |  20.124s  |  20.124s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-6.smt2  |  20.096s  |  20.096s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-AmortizedQueue.scala-1.smt2  |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ArrayBinarySearch.scala-1.smt2  |  20.359s  |  20.359s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-BinarySearchTree.scala-1.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-BinaryTrie.scala-1.smt2  |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-BinaryTrie.scala-3.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-BinaryTrie.scala-5.smt2  |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-BinaryTrie.scala-9.smt2  |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-13.smt2  |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-14.smt2  |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-18.smt2  |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-19.smt2  |  16.198s  |  16.198s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-3.smt2  |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-5.smt2  |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-7.smt2  |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-8.smt2  |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Compiler.scala-7.smt2  |  20.504s  |  20.504s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Fibonacci.scala-3.smt2  |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-10.smt2  |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-11.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-12.smt2  |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-13.smt2  |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-16.smt2  |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-17.smt2  |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-18.smt2  |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-19.smt2  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-2.smt2  |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-20.smt2  |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-21.smt2  |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-22.smt2  |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-4.smt2  |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-5.smt2  |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-7.smt2  |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-8.smt2  |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-9.smt2  |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-1.smt2  |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-14.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-19.smt2  |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-21.smt2  |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-25.smt2  |  20.047s  |  20.047s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-29.smt2  |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-5.smt2  |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-9.smt2  |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-InsertionSort.scala-1.smt2  |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Interpreter.scala-3.smt2  |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Interpreter.scala-4.smt2  |   0.665s  |   0.665s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-LambdaEval.scala-20.smt2  |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-LambdaEval.scala-6.smt2  |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-LambdaEval.scala-60.smt2  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-LeftistHeap.scala-1.smt2  |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-LeftistHeap.scala-13.smt2  |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-LeftistHeap.scala-5.smt2  |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-LeftistHeap.scala-8.smt2  |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-1.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-10.smt2  |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-13.smt2  |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-16.smt2  |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-3.smt2  |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-5.smt2  |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Lists5.scala-4.smt2  |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Map.scala-1.smt2  |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Map.scala-2.smt2  |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-MergeSort.scala-5.smt2  |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-MergeSort.scala-7.smt2  |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-MutuallyRecursive.scala-1.smt2  |  20.141s  |  20.141s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-10.smt2  |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-11.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-12.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-13.smt2  |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-14.smt2  |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-2.smt2  |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-3.smt2  |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-4.smt2  |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-5.smt2  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-6.smt2  |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-7.smt2  |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-8.smt2  |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-9.smt2  |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Parser.scala-1.smt2  |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Parser.scala-3.smt2  |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Parser.scala-5.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Parser.scala-9.smt2  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PositiveMap.scala-2.smt2  |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-1.smt2  |  20.066s  |  20.066s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-15.smt2  |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-16.smt2  |  20.076s  |  20.076s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-17.smt2  |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-18.smt2  |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-19.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-20.smt2  |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-21.smt2  |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-22.smt2  |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-23.smt2  |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-24.smt2  |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-25.smt2  |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-26.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-27.smt2  |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-28.smt2  |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-29.smt2  |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-4.smt2  |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-13.smt2  |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-14.smt2  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-17.smt2  |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-18.smt2  |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-21.smt2  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-22.smt2  |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-24.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-25.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-27.smt2  |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-28.smt2  |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-29.smt2  |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-30.smt2  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-31.smt2  |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-32.smt2  |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SearchLinkedList.scala-1.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SearchLinkedList.scala-4.smt2  |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SearchLinkedList.scala-7.smt2  |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SecondsToTime.scala-1.smt2  |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SecondsToTime.scala-3.smt2  |  18.552s  |  18.552s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SecondsToTime.scala-5.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SecondsToTime.scala-8.smt2  |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-1.smt2  |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-10.smt2  |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-12.smt2  |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-13.smt2  |  20.073s  |  20.073s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-14.smt2  |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-15.smt2  |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-2.smt2  |  20.070s  |  20.070s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-3.smt2  |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-4.smt2  |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-7.smt2  |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-8.smt2  |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-9.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SimpInterpret.scala-3.smt2  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SimpInterpret.scala-4.smt2  |   0.786s  |   0.786s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SortedList.scala-1.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SortedNDList.scala-2.smt2  |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SortedNDList.scala-3.smt2  |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SumAndMax.scala-4.smt2  |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SumAndMax.scala-7.smt2  |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Sync.scala-1.smt2  |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-TwoSizeFunctions.scala-1.smt2  |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-TwoSizeFunctions.scala-4.smt2  |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-TwoSizeFunctions.scala-7.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-muDot2.scala-41.smt2  |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-muDot2.scala-43.smt2  |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-100.smt2  |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-101.smt2  |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-102.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-103.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-104.smt2  |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-105.smt2  |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-106.smt2  |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-107.smt2  |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-108.smt2  |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-109.smt2  |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-110.smt2  |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-111.smt2  |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-112.smt2  |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-113.smt2  |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-114.smt2  |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-115.smt2  |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-116.smt2  |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-36.smt2  |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-37.smt2  |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-38.smt2  |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-39.smt2  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-40.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-41.smt2  |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-42.smt2  |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-43.smt2  |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-44.smt2  |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-45.smt2  |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-46.smt2  |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-47.smt2  |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-48.smt2  |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-49.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-50.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-51.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-52.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-53.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-54.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-55.smt2  |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-56.smt2  |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-57.smt2  |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-58.smt2  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-59.smt2  |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-60.smt2  |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-61.smt2  |  20.040s  |  20.040s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-62.smt2  |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-63.smt2  |  20.040s  |  20.040s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-64.smt2  |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-65.smt2  |  20.040s  |  20.040s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-66.smt2  |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-67.smt2  |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-68.smt2  |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-69.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-70.smt2  |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-71.smt2  |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-72.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-73.smt2  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-76.smt2  |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-77.smt2  |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-78.smt2  |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-79.smt2  |  20.015s  |  20.015s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-80.smt2  |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-81.smt2  |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-82.smt2  |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-83.smt2  |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-84.smt2  |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-85.smt2  |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-86.smt2  |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-87.smt2  |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-88.smt2  |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-89.smt2  |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-90.smt2  |  20.017s  |  20.017s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-91.smt2  |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-92.smt2  |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-93.smt2  |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-94.smt2  |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-95.smt2  |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-96.smt2  |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-97.smt2  |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-98.smt2  |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-99.smt2  |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-14.smt2-1.smt2  |  20.089s  |  20.089s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-14.smt2-2.smt2  |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-14.smt2-3.smt2  |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-17.smt2-1.smt2  |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-17.smt2-2.smt2  |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-17.smt2-3.smt2  |  20.111s  |  20.111s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-2.smt2-1.smt2  |  20.102s  |  20.102s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-2.smt2-2.smt2  |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-2.smt2-3.smt2  |  20.124s  |  20.124s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-24.smt2-1.smt2  |  20.676s  |  20.676s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-24.smt2-2.smt2  |  20.722s  |  20.722s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-24.smt2-3.smt2  |  20.682s  |  20.682s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-27.smt2-1.smt2  |  20.963s  |  20.963s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-27.smt2-2.smt2  |  20.689s  |  20.689s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-27.smt2-3.smt2  |  20.753s  |  20.753s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-4.smt2-1.smt2  |  20.078s  |  20.078s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-4.smt2-2.smt2  |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-4.smt2-3.smt2  |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AbsFun.scala-13.smt2-1.smt2  |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AbsFun.scala-13.smt2-2.smt2  |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AbsFun.scala-13.smt2-3.smt2  |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AbsFun.scala-4.smt2-1.smt2  |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AbsFun.scala-4.smt2-2.smt2  |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AbsFun.scala-4.smt2-3.smt2  |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AbsFun.scala-6.smt2-1.smt2  |  20.234s  |  20.234s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AbsFun.scala-6.smt2-2.smt2  |  20.064s  |  20.064s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AbsFun.scala-6.smt2-3.smt2  |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AmortizedQueue.scala-1.smt2-1.smt2  |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AmortizedQueue.scala-1.smt2-2.smt2  |  20.064s  |  20.064s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AmortizedQueue.scala-1.smt2-3.smt2  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ArrayBinarySearch.scala-1.smt2-1.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ArrayBinarySearch.scala-1.smt2-2.smt2  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ArrayBinarySearch.scala-1.smt2-3.smt2  |   0.280s  |   0.280s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BinarySearchTree.scala-1.smt2-1.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BinarySearchTree.scala-1.smt2-2.smt2  |  20.097s  |  20.097s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BinarySearchTree.scala-1.smt2-3.smt2  |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-1.smt2-1.smt2  |  20.094s  |  20.094s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-1.smt2-2.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-1.smt2-3.smt2  |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-3.smt2-1.smt2  |  20.126s  |  20.126s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-3.smt2-2.smt2  |  20.090s  |  20.090s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-3.smt2-3.smt2  |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-5.smt2-1.smt2  |  21.325s  |  21.325s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-5.smt2-2.smt2  |  20.550s  |  20.550s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-5.smt2-3.smt2  |  20.712s  |  20.712s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-9.smt2-1.smt2  |  20.709s  |  20.709s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-9.smt2-2.smt2  |  20.699s  |  20.699s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-1.smt2-1.smt2  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-1.smt2-2.smt2  |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-1.smt2-3.smt2  |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-13.smt2-1.smt2  |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-13.smt2-2.smt2  |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-13.smt2-3.smt2  |  20.071s  |  20.071s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-14.smt2-1.smt2  |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-18.smt2-1.smt2  |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-18.smt2-2.smt2  |  20.090s  |  20.090s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-18.smt2-3.smt2  |  20.123s  |  20.123s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-19.smt2-1.smt2  |  20.201s  |  20.201s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-19.smt2-2.smt2  |  20.160s  |  20.160s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-19.smt2-3.smt2  |  20.095s  |  20.095s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-2.smt2-1.smt2  |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-2.smt2-2.smt2  |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-2.smt2-3.smt2  |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-7.smt2-1.smt2  |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-7.smt2-2.smt2  |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-7.smt2-3.smt2  |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-8.smt2-1.smt2  |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-8.smt2-2.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-8.smt2-3.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Compiler.scala-7.smt2-1.smt2  |  20.953s  |  20.953s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Compiler.scala-7.smt2-2.smt2  |  20.751s  |  20.751s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Compiler.scala-7.smt2-3.smt2  |  20.603s  |  20.603s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-10.smt2-1.smt2  |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-10.smt2-2.smt2  |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-10.smt2-3.smt2  |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-11.smt2-1.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-13.smt2-1.smt2  |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-13.smt2-2.smt2  |  20.091s  |  20.091s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-13.smt2-3.smt2  |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-16.smt2-2.smt2  |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-16.smt2-3.smt2  |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-17.smt2-1.smt2  |  20.069s  |  20.069s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-17.smt2-3.smt2  |  20.080s  |  20.080s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-18.smt2-1.smt2  |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-18.smt2-2.smt2  |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-18.smt2-3.smt2  |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-19.smt2-1.smt2  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-19.smt2-2.smt2  |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-19.smt2-3.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-2.smt2-1.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-2.smt2-2.smt2  |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-2.smt2-3.smt2  |  20.089s  |  20.089s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-20.smt2-1.smt2  |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-20.smt2-2.smt2  |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-20.smt2-3.smt2  |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-22.smt2-1.smt2  |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-22.smt2-2.smt2  |  20.085s  |  20.085s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-22.smt2-3.smt2  |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-4.smt2-1.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-4.smt2-2.smt2  |  20.067s  |  20.067s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-4.smt2-3.smt2  |  20.061s  |  20.061s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-5.smt2-1.smt2  |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-5.smt2-2.smt2  |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-5.smt2-3.smt2  |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-8.smt2-1.smt2  |  20.075s  |  20.075s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-9.smt2-1.smt2  |  20.087s  |  20.087s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-9.smt2-2.smt2  |  20.088s  |  20.088s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-9.smt2-3.smt2  |  20.092s  |  20.092s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-1.smt2-1.smt2  |  20.079s  |  20.079s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-1.smt2-2.smt2  |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-1.smt2-3.smt2  |  20.069s  |  20.069s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-14.smt2-1.smt2  |  20.182s  |  20.182s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-14.smt2-2.smt2  |  20.123s  |  20.123s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-14.smt2-3.smt2  |  20.087s  |  20.087s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-19.smt2-1.smt2  |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-19.smt2-2.smt2  |  20.179s  |  20.179s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-19.smt2-3.smt2  |  20.214s  |  20.214s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-21.smt2-1.smt2  |  20.201s  |  20.201s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-21.smt2-2.smt2  |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-21.smt2-3.smt2  |  20.184s  |  20.184s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-25.smt2-1.smt2  |  20.372s  |  20.372s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-25.smt2-2.smt2  |  20.222s  |  20.222s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-25.smt2-3.smt2  |  21.141s  |  21.141s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-5.smt2-1.smt2  |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-5.smt2-2.smt2  |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-5.smt2-3.smt2  |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-9.smt2-1.smt2  |  20.955s  |  20.955s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-9.smt2-2.smt2  |  20.574s  |  20.574s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-9.smt2-3.smt2  |  21.160s  |  21.160s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-InsertionSort.scala-1.smt2-1.smt2  |  20.040s  |  20.040s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-InsertionSort.scala-1.smt2-2.smt2  |  20.077s  |  20.077s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-InsertionSort.scala-1.smt2-3.smt2  |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Interpreter.scala-3.smt2-1.smt2  |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Interpreter.scala-3.smt2-2.smt2  |  20.085s  |  20.085s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Interpreter.scala-3.smt2-3.smt2  |  20.082s  |  20.082s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LambdaEval.scala-20.smt2-1.smt2  |  20.288s  |  20.288s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LambdaEval.scala-20.smt2-2.smt2  |  20.108s  |  20.108s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LambdaEval.scala-20.smt2-3.smt2  |  20.092s  |  20.092s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LambdaEval.scala-6.smt2-1.smt2  |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LambdaEval.scala-6.smt2-2.smt2  |  20.142s  |  20.142s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LambdaEval.scala-6.smt2-3.smt2  |  20.076s  |  20.076s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-1.smt2-1.smt2  |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-1.smt2-2.smt2  |  20.040s  |  20.040s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-1.smt2-3.smt2  |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-13.smt2-1.smt2  |  20.291s  |  20.291s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-13.smt2-2.smt2  |  20.095s  |  20.095s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-13.smt2-3.smt2  |  20.440s  |  20.440s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-5.smt2-1.smt2  |  20.113s  |  20.113s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-5.smt2-2.smt2  |  20.084s  |  20.084s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-5.smt2-3.smt2  |  20.126s  |  20.126s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-8.smt2-1.smt2  |  20.586s  |  20.586s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-8.smt2-2.smt2  |  20.607s  |  20.607s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-8.smt2-3.smt2  |  20.491s  |  20.491s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ListOperations.scala-1.smt2-1.smt2  |  20.084s  |  20.084s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ListOperations.scala-1.smt2-2.smt2  |  20.087s  |  20.087s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ListOperations.scala-1.smt2-3.smt2  |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ListOperations.scala-10.smt2-1.smt2  |  20.075s  |  20.075s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ListOperations.scala-10.smt2-2.smt2  |  20.113s  |  20.113s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ListOperations.scala-10.smt2-3.smt2  |  20.061s  |  20.061s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ListOperations.scala-16.smt2-1.smt2  |  20.587s  |  20.587s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ListOperations.scala-16.smt2-2.smt2  |  20.229s  |  20.229s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ListOperations.scala-16.smt2-3.smt2  |  20.208s  |  20.208s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ListOperations.scala-3.smt2-1.smt2  |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ListOperations.scala-3.smt2-2.smt2  |  20.047s  |  20.047s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ListOperations.scala-3.smt2-3.smt2  |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ListOperations.scala-5.smt2-1.smt2  |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ListOperations.scala-5.smt2-2.smt2  |  20.074s  |  20.074s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ListOperations.scala-5.smt2-3.smt2  |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Lists5.scala-4.smt2-1.smt2  |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Lists5.scala-4.smt2-2.smt2  |  20.078s  |  20.078s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Lists5.scala-4.smt2-3.smt2  |  20.070s  |  20.070s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Map.scala-1.smt2-1.smt2  |  20.076s  |  20.076s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Map.scala-1.smt2-2.smt2  |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Map.scala-1.smt2-3.smt2  |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Map.scala-2.smt2-1.smt2  |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Map.scala-2.smt2-2.smt2  |  20.103s  |  20.103s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Map.scala-2.smt2-3.smt2  |  20.089s  |  20.089s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-MutuallyRecursive.scala-1.smt2-1.smt2  |  20.163s  |  20.163s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-MutuallyRecursive.scala-1.smt2-2.smt2  |  20.160s  |  20.160s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-MutuallyRecursive.scala-1.smt2-3.smt2  |  20.153s  |  20.153s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-10.smt2-1.smt2  |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-10.smt2-2.smt2  |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-10.smt2-3.smt2  |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-11.smt2-1.smt2  |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-11.smt2-2.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-11.smt2-3.smt2  |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-12.smt2-1.smt2  |  20.094s  |  20.094s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-12.smt2-2.smt2  |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-12.smt2-3.smt2  |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-13.smt2-1.smt2  |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-13.smt2-2.smt2  |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-13.smt2-3.smt2  |  20.069s  |  20.069s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-14.smt2-1.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-14.smt2-2.smt2  |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-14.smt2-3.smt2  |  20.138s  |  20.138s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-2.smt2-1.smt2  |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-3.smt2-1.smt2  |  20.079s  |  20.079s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-3.smt2-2.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-3.smt2-3.smt2  |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-5.smt2-1.smt2  |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-5.smt2-2.smt2  |  20.063s  |  20.063s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-5.smt2-3.smt2  |  20.108s  |  20.108s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-6.smt2-1.smt2  |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-6.smt2-2.smt2  |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-6.smt2-3.smt2  |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-7.smt2-1.smt2  |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-7.smt2-2.smt2  |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-7.smt2-3.smt2  |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-9.smt2-1.smt2  |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-9.smt2-2.smt2  |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-9.smt2-3.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Parser.scala-1.smt2-1.smt2  |  20.108s  |  20.108s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Parser.scala-1.smt2-2.smt2  |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Parser.scala-1.smt2-3.smt2  |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Parser.scala-3.smt2-1.smt2  |  20.068s  |  20.068s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Parser.scala-3.smt2-2.smt2  |  20.116s  |  20.116s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Parser.scala-3.smt2-3.smt2  |  20.066s  |  20.066s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Parser.scala-5.smt2-1.smt2  |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Parser.scala-5.smt2-2.smt2  |  20.091s  |  20.091s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Parser.scala-5.smt2-3.smt2  |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Parser.scala-9.smt2-1.smt2  |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PositiveMap.scala-2.smt2-1.smt2  |  20.106s  |  20.106s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PositiveMap.scala-2.smt2-2.smt2  |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PositiveMap.scala-2.smt2-3.smt2  |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-1.smt2-1.smt2  |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-1.smt2-2.smt2  |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-1.smt2-3.smt2  |  20.127s  |  20.127s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-15.smt2-1.smt2  |  20.093s  |  20.093s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-15.smt2-2.smt2  |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-15.smt2-3.smt2  |  20.139s  |  20.139s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-16.smt2-1.smt2  |  20.134s  |  20.134s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-16.smt2-2.smt2  |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-16.smt2-3.smt2  |  20.103s  |  20.103s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-17.smt2-1.smt2  |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-17.smt2-2.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-17.smt2-3.smt2  |  20.143s  |  20.143s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-18.smt2-1.smt2  |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-18.smt2-2.smt2  |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-18.smt2-3.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-19.smt2-1.smt2  |  20.140s  |  20.140s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-19.smt2-2.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-19.smt2-3.smt2  |  20.134s  |  20.134s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-20.smt2-1.smt2  |  20.079s  |  20.079s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-20.smt2-2.smt2  |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-20.smt2-3.smt2  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-21.smt2-1.smt2  |  20.149s  |  20.149s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-21.smt2-2.smt2  |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-21.smt2-3.smt2  |  20.125s  |  20.125s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-22.smt2-1.smt2  |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-22.smt2-2.smt2  |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-23.smt2-1.smt2  |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-23.smt2-2.smt2  |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-24.smt2-1.smt2  |  20.090s  |  20.090s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-24.smt2-2.smt2  |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-24.smt2-3.smt2  |  20.099s  |  20.099s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-25.smt2-1.smt2  |  20.166s  |  20.166s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-25.smt2-2.smt2  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-25.smt2-3.smt2  |  20.084s  |  20.084s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-26.smt2-1.smt2  |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-26.smt2-2.smt2  |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-26.smt2-3.smt2  |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-27.smt2-1.smt2  |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-27.smt2-2.smt2  |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-28.smt2-1.smt2  |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-28.smt2-2.smt2  |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-29.smt2-1.smt2  |  20.097s  |  20.097s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-29.smt2-2.smt2  |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-29.smt2-3.smt2  |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-4.smt2-1.smt2  |  20.111s  |  20.111s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-4.smt2-2.smt2  |  20.157s  |  20.157s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-4.smt2-3.smt2  |  20.225s  |  20.225s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-13.smt2-1.smt2  |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-13.smt2-2.smt2  |  20.119s  |  20.119s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-13.smt2-3.smt2  |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-14.smt2-1.smt2  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-14.smt2-2.smt2  |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-14.smt2-3.smt2  |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-17.smt2-1.smt2  |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-17.smt2-2.smt2  |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-17.smt2-3.smt2  |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-18.smt2-1.smt2  |  20.235s  |  20.235s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-18.smt2-2.smt2  |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-18.smt2-3.smt2  |  20.152s  |  20.152s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-21.smt2-1.smt2  |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-21.smt2-2.smt2  |  20.103s  |  20.103s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-21.smt2-3.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-22.smt2-1.smt2  |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-22.smt2-2.smt2  |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-22.smt2-3.smt2  |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-24.smt2-1.smt2  |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-24.smt2-2.smt2  |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-24.smt2-3.smt2  |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-25.smt2-1.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-25.smt2-2.smt2  |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-25.smt2-3.smt2  |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-27.smt2-1.smt2  |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-27.smt2-2.smt2  |  20.071s  |  20.071s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-27.smt2-3.smt2  |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-28.smt2-1.smt2  |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-28.smt2-2.smt2  |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-28.smt2-3.smt2  |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-29.smt2-1.smt2  |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-29.smt2-2.smt2  |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-29.smt2-3.smt2  |  20.066s  |  20.066s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-30.smt2-1.smt2  |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-30.smt2-2.smt2  |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-30.smt2-3.smt2  |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-31.smt2-1.smt2  |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-31.smt2-2.smt2  |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-31.smt2-3.smt2  |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-32.smt2-1.smt2  |  20.104s  |  20.104s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-32.smt2-2.smt2  |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-32.smt2-3.smt2  |  20.096s  |  20.096s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SearchLinkedList.scala-1.smt2-1.smt2  |  20.102s  |  20.102s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SearchLinkedList.scala-1.smt2-2.smt2  |  20.079s  |  20.079s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SearchLinkedList.scala-1.smt2-3.smt2  |  20.102s  |  20.102s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SearchLinkedList.scala-4.smt2-1.smt2  |  20.064s  |  20.064s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SearchLinkedList.scala-4.smt2-2.smt2  |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SearchLinkedList.scala-4.smt2-3.smt2  |  20.068s  |  20.068s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SearchLinkedList.scala-7.smt2-1.smt2  |  20.094s  |  20.094s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SearchLinkedList.scala-7.smt2-2.smt2  |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SearchLinkedList.scala-7.smt2-3.smt2  |  20.127s  |  20.127s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SecondsToTime.scala-1.smt2-1.smt2  |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SecondsToTime.scala-1.smt2-2.smt2  |  20.136s  |  20.136s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SecondsToTime.scala-1.smt2-3.smt2  |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SecondsToTime.scala-3.smt2-1.smt2  |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SecondsToTime.scala-3.smt2-2.smt2  |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SecondsToTime.scala-3.smt2-3.smt2  |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SecondsToTime.scala-5.smt2-1.smt2  |  20.061s  |  20.061s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SecondsToTime.scala-5.smt2-2.smt2  |  20.073s  |  20.073s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SecondsToTime.scala-5.smt2-3.smt2  |  20.040s  |  20.040s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SecondsToTime.scala-8.smt2-1.smt2  |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SecondsToTime.scala-8.smt2-2.smt2  |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SecondsToTime.scala-8.smt2-3.smt2  |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-1.smt2-1.smt2  |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-1.smt2-2.smt2  |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-1.smt2-3.smt2  |  20.047s  |  20.047s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-10.smt2-1.smt2  |  20.128s  |  20.128s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-10.smt2-2.smt2  |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-10.smt2-3.smt2  |  20.111s  |  20.111s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-12.smt2-1.smt2  |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-12.smt2-2.smt2  |  20.231s  |  20.231s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-12.smt2-3.smt2  |  20.100s  |  20.100s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-13.smt2-1.smt2  |  20.207s  |  20.207s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-13.smt2-2.smt2  |  20.116s  |  20.116s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-13.smt2-3.smt2  |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-14.smt2-1.smt2  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-14.smt2-2.smt2  |  20.095s  |  20.095s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-14.smt2-3.smt2  |  20.136s  |  20.136s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-15.smt2-1.smt2  |  20.094s  |  20.094s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-15.smt2-2.smt2  |  20.167s  |  20.167s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-15.smt2-3.smt2  |  20.161s  |  20.161s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-2.smt2-1.smt2  |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-2.smt2-2.smt2  |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-2.smt2-3.smt2  |  20.114s  |  20.114s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-3.smt2-1.smt2  |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-3.smt2-2.smt2  |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-3.smt2-3.smt2  |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-7.smt2-1.smt2  |  20.113s  |  20.113s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-7.smt2-2.smt2  |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-7.smt2-3.smt2  |  20.220s  |  20.220s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-8.smt2-1.smt2  |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-8.smt2-2.smt2  |  20.096s  |  20.096s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-8.smt2-3.smt2  |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-9.smt2-1.smt2  |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-9.smt2-2.smt2  |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-9.smt2-3.smt2  |  20.145s  |  20.145s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SimpInterpret.scala-3.smt2-1.smt2  |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SimpInterpret.scala-3.smt2-2.smt2  |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SimpInterpret.scala-3.smt2-3.smt2  |  20.087s  |  20.087s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SortedList.scala-1.smt2-1.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SortedList.scala-1.smt2-2.smt2  |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SortedList.scala-1.smt2-3.smt2  |  20.129s  |  20.129s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SortedNDList.scala-2.smt2-1.smt2  |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SortedNDList.scala-2.smt2-2.smt2  |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SortedNDList.scala-2.smt2-3.smt2  |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SortedNDList.scala-3.smt2-1.smt2  |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SortedNDList.scala-3.smt2-2.smt2  |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SortedNDList.scala-3.smt2-3.smt2  |  20.070s  |  20.070s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SumAndMax.scala-4.smt2-1.smt2  |  20.079s  |  20.079s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SumAndMax.scala-4.smt2-2.smt2  |  20.078s  |  20.078s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SumAndMax.scala-4.smt2-3.smt2  |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SumAndMax.scala-7.smt2-1.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SumAndMax.scala-7.smt2-2.smt2  |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SumAndMax.scala-7.smt2-3.smt2  |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Sync.scala-1.smt2-1.smt2  |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Sync.scala-1.smt2-2.smt2  |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Sync.scala-1.smt2-3.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-TwoSizeFunctions.scala-1.smt2-1.smt2  |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-TwoSizeFunctions.scala-1.smt2-2.smt2  |  20.076s  |  20.076s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-TwoSizeFunctions.scala-1.smt2-3.smt2  |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-TwoSizeFunctions.scala-4.smt2-1.smt2  |  20.085s  |  20.085s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-TwoSizeFunctions.scala-4.smt2-2.smt2  |  20.115s  |  20.115s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-TwoSizeFunctions.scala-4.smt2-3.smt2  |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-muDot2.scala-41.smt2-1.smt2  |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-muDot2.scala-41.smt2-2.smt2  |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-muDot2.scala-41.smt2-3.smt2  |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-muDot2.scala-43.smt2-1.smt2  |  20.109s  |  20.109s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-muDot2.scala-43.smt2-2.smt2  |  20.143s  |  20.143s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-muDot2.scala-43.smt2-3.smt2  |  20.076s  |  20.076s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-100.smt2-1.smt2  |  20.171s  |  20.171s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-100.smt2-2.smt2  |  20.167s  |  20.167s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-100.smt2-3.smt2  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-101.smt2-1.smt2  |  20.222s  |  20.222s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-101.smt2-2.smt2  |  20.682s  |  20.682s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-101.smt2-3.smt2  |  20.712s  |  20.712s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-102.smt2-1.smt2  |  20.203s  |  20.203s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-102.smt2-2.smt2  |  20.277s  |  20.277s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-102.smt2-3.smt2  |  20.206s  |  20.206s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-103.smt2-1.smt2  |  20.218s  |  20.218s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-103.smt2-2.smt2  |  20.197s  |  20.197s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-103.smt2-3.smt2  |  20.177s  |  20.177s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-104.smt2-1.smt2  |  20.637s  |  20.637s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-104.smt2-2.smt2  |  20.525s  |  20.525s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-104.smt2-3.smt2  |  20.826s  |  20.826s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-105.smt2-1.smt2  |  20.418s  |  20.418s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-105.smt2-2.smt2  |  20.669s  |  20.669s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-105.smt2-3.smt2  |  20.742s  |  20.742s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-106.smt2-1.smt2  |  20.121s  |  20.121s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-106.smt2-2.smt2  |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-106.smt2-3.smt2  |  20.040s  |  20.040s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-107.smt2-1.smt2  |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-107.smt2-2.smt2  |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-107.smt2-3.smt2  |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-108.smt2-1.smt2  |  20.174s  |  20.174s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-108.smt2-2.smt2  |  20.123s  |  20.123s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-108.smt2-3.smt2  |  20.077s  |  20.077s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-109.smt2-1.smt2  |  20.114s  |  20.114s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-110.smt2-1.smt2  |  20.137s  |  20.137s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-110.smt2-2.smt2  |  20.116s  |  20.116s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-110.smt2-3.smt2  |  20.086s  |  20.086s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-111.smt2-1.smt2  |  20.832s  |  20.832s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-111.smt2-2.smt2  |  20.630s  |  20.630s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-111.smt2-3.smt2  |  20.773s  |  20.773s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-112.smt2-1.smt2  |  20.841s  |  20.841s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-112.smt2-2.smt2  |  20.798s  |  20.798s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-112.smt2-3.smt2  |  20.740s  |  20.740s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-113.smt2-1.smt2  |  20.531s  |  20.531s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-113.smt2-2.smt2  |  21.197s  |  21.197s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-113.smt2-3.smt2  |  20.754s  |  20.754s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-114.smt2-1.smt2  |  20.418s  |  20.418s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-114.smt2-2.smt2  |  20.595s  |  20.595s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-114.smt2-3.smt2  |  20.697s  |  20.697s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-115.smt2-1.smt2  |  20.730s  |  20.730s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-115.smt2-2.smt2  |  20.819s  |  20.819s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-115.smt2-3.smt2  |  20.350s  |  20.350s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-116.smt2-1.smt2  |  21.151s  |  21.151s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-116.smt2-2.smt2  |  20.827s  |  20.827s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-116.smt2-3.smt2  |  20.563s  |  20.563s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-36.smt2-1.smt2  |  20.793s  |  20.793s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-36.smt2-2.smt2  |  21.052s  |  21.052s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-36.smt2-3.smt2  |  20.722s  |  20.722s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-37.smt2-1.smt2  |  20.378s  |  20.378s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-37.smt2-2.smt2  |  20.080s  |  20.080s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-37.smt2-3.smt2  |  20.229s  |  20.229s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-38.smt2-1.smt2  |  20.124s  |  20.124s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-38.smt2-2.smt2  |  20.206s  |  20.206s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-38.smt2-3.smt2  |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-39.smt2-1.smt2  |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-39.smt2-2.smt2  |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-39.smt2-3.smt2  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-40.smt2-1.smt2  |  20.100s  |  20.100s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-40.smt2-2.smt2  |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-40.smt2-3.smt2  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-41.smt2-1.smt2  |  20.094s  |  20.094s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-41.smt2-2.smt2  |  20.080s  |  20.080s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-41.smt2-3.smt2  |  20.114s  |  20.114s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-42.smt2-1.smt2  |  20.161s  |  20.161s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-42.smt2-2.smt2  |  20.163s  |  20.163s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-42.smt2-3.smt2  |  20.154s  |  20.154s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-43.smt2-1.smt2  |  20.227s  |  20.227s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-43.smt2-2.smt2  |  20.075s  |  20.075s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-43.smt2-3.smt2  |  20.188s  |  20.188s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-44.smt2-1.smt2  |  20.155s  |  20.155s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-44.smt2-2.smt2  |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-44.smt2-3.smt2  |  20.077s  |  20.077s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-45.smt2-1.smt2  |  20.176s  |  20.176s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-46.smt2-1.smt2  |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-47.smt2-1.smt2  |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-47.smt2-2.smt2  |  20.121s  |  20.121s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-47.smt2-3.smt2  |  20.131s  |  20.131s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-48.smt2-1.smt2  |  20.370s  |  20.370s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-48.smt2-2.smt2  |  20.386s  |  20.386s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-48.smt2-3.smt2  |  20.400s  |  20.400s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-49.smt2-1.smt2  |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-50.smt2-1.smt2  |  20.247s  |  20.247s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-50.smt2-2.smt2  |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-50.smt2-3.smt2  |  20.264s  |  20.264s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-51.smt2-1.smt2  |  20.218s  |  20.218s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-51.smt2-2.smt2  |  20.465s  |  20.465s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-51.smt2-3.smt2  |  20.084s  |  20.084s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-52.smt2-1.smt2  |  20.093s  |  20.093s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-52.smt2-2.smt2  |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-52.smt2-3.smt2  |  20.143s  |  20.143s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-53.smt2-1.smt2  |  20.741s  |  20.741s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-54.smt2-1.smt2  |  20.121s  |  20.121s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-54.smt2-2.smt2  |  20.131s  |  20.131s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-54.smt2-3.smt2  |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-55.smt2-1.smt2  |  20.061s  |  20.061s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-55.smt2-2.smt2  |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-55.smt2-3.smt2  |  20.088s  |  20.088s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-56.smt2-1.smt2  |  20.095s  |  20.095s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-56.smt2-3.smt2  |  20.121s  |  20.121s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-57.smt2-1.smt2  |  20.726s  |  20.726s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-57.smt2-2.smt2  |  20.355s  |  20.355s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-57.smt2-3.smt2  |  20.257s  |  20.257s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-58.smt2-1.smt2  |  20.598s  |  20.598s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-58.smt2-2.smt2  |  20.335s  |  20.335s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-58.smt2-3.smt2  |  20.369s  |  20.369s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-59.smt2-1.smt2  |  20.175s  |  20.175s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-59.smt2-2.smt2  |  20.120s  |  20.120s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-59.smt2-3.smt2  |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-60.smt2-1.smt2  |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-60.smt2-2.smt2  |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-60.smt2-3.smt2  |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-61.smt2-1.smt2  |  20.251s  |  20.251s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-61.smt2-2.smt2  |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-61.smt2-3.smt2  |  20.068s  |  20.068s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-62.smt2-1.smt2  |  20.108s  |  20.108s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-63.smt2-1.smt2  |  20.216s  |  20.216s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-64.smt2-1.smt2  |  20.149s  |  20.149s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-64.smt2-2.smt2  |  20.181s  |  20.181s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-64.smt2-3.smt2  |  20.106s  |  20.106s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-65.smt2-1.smt2  |  20.106s  |  20.106s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-65.smt2-3.smt2  |  20.155s  |  20.155s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-66.smt2-1.smt2  |  20.076s  |  20.076s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-66.smt2-2.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-66.smt2-3.smt2  |  20.079s  |  20.079s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-67.smt2-1.smt2  |  20.183s  |  20.183s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-67.smt2-2.smt2  |  20.750s  |  20.750s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-67.smt2-3.smt2  |  20.433s  |  20.433s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-68.smt2-1.smt2  |  20.130s  |  20.130s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-68.smt2-2.smt2  |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-69.smt2-1.smt2  |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-69.smt2-2.smt2  |  20.146s  |  20.146s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-69.smt2-3.smt2  |  21.059s  |  21.059s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-70.smt2-1.smt2  |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-70.smt2-2.smt2  |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-70.smt2-3.smt2  |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-71.smt2-1.smt2  |  20.519s  |  20.519s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-72.smt2-1.smt2  |  20.540s  |  20.540s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-72.smt2-2.smt2  |  20.677s  |  20.677s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-72.smt2-3.smt2  |  20.464s  |  20.464s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-73.smt2-1.smt2  |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-73.smt2-2.smt2  |  20.090s  |  20.090s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-73.smt2-3.smt2  |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-76.smt2-1.smt2  |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-76.smt2-2.smt2  |  20.063s  |  20.063s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-76.smt2-3.smt2  |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-78.smt2-1.smt2  |  20.157s  |  20.157s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-79.smt2-1.smt2  |  20.150s  |  20.150s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-79.smt2-2.smt2  |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-79.smt2-3.smt2  |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-80.smt2-1.smt2  |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-80.smt2-2.smt2  |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-80.smt2-3.smt2  |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-81.smt2-1.smt2  |  20.850s  |  20.850s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-81.smt2-2.smt2  |  20.546s  |  20.546s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-81.smt2-3.smt2  |  21.467s  |  21.467s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-82.smt2-1.smt2  |  20.158s  |  20.158s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-82.smt2-2.smt2  |  20.040s  |  20.040s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-82.smt2-3.smt2  |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-83.smt2-1.smt2  |  20.132s  |  20.132s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-83.smt2-2.smt2  |  20.119s  |  20.119s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-83.smt2-3.smt2  |  20.284s  |  20.284s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-84.smt2-1.smt2  |  20.190s  |  20.190s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-84.smt2-2.smt2  |  20.101s  |  20.101s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-84.smt2-3.smt2  |  20.156s  |  20.156s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-85.smt2-1.smt2  |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-85.smt2-2.smt2  |  20.150s  |  20.150s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-85.smt2-3.smt2  |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-86.smt2-1.smt2  |  20.094s  |  20.094s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-86.smt2-2.smt2  |  20.100s  |  20.100s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-87.smt2-1.smt2  |  20.174s  |  20.174s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-87.smt2-2.smt2  |  20.094s  |  20.094s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-87.smt2-3.smt2  |  20.149s  |  20.149s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-88.smt2-1.smt2  |  20.079s  |  20.079s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-88.smt2-2.smt2  |  20.080s  |  20.080s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-88.smt2-3.smt2  |  20.069s  |  20.069s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-89.smt2-1.smt2  |  20.708s  |  20.708s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-89.smt2-2.smt2  |  20.572s  |  20.572s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-89.smt2-3.smt2  |  20.835s  |  20.835s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-90.smt2-1.smt2  |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-90.smt2-2.smt2  |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-90.smt2-3.smt2  |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-91.smt2-1.smt2  |  20.068s  |  20.068s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-92.smt2-1.smt2  |  20.084s  |  20.084s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-92.smt2-2.smt2  |  20.092s  |  20.092s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-92.smt2-3.smt2  |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-93.smt2-1.smt2  |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-93.smt2-2.smt2  |  20.197s  |  20.197s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-93.smt2-3.smt2  |  10.553s  |  10.553s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-94.smt2-1.smt2  |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-94.smt2-2.smt2  |  20.085s  |  20.085s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-94.smt2-3.smt2  |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-95.smt2-1.smt2  |  20.159s  |  20.159s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-95.smt2-2.smt2  |  20.061s  |  20.061s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-95.smt2-3.smt2  |  20.170s  |  20.170s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-96.smt2-1.smt2  |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-96.smt2-2.smt2  |  20.083s  |  20.083s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-96.smt2-3.smt2  |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-97.smt2-1.smt2  |  20.141s  |  20.141s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-97.smt2-2.smt2  |  20.943s  |  20.943s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-97.smt2-3.smt2  |  20.248s  |  20.248s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-98.smt2-1.smt2  |  20.130s  |  20.130s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-98.smt2-2.smt2  |  20.112s  |  20.112s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-98.smt2-3.smt2  |  20.122s  |  20.122s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-99.smt2-1.smt2  |  20.151s  |  20.151s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-99.smt2-2.smt2  |  20.183s  |  20.183s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-99.smt2-3.smt2  |  20.182s  |  20.182s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-AVLTree.scala-14.smt2  |  20.099s  |  20.099s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-AVLTree.scala-17.smt2  |  20.139s  |  20.139s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-AVLTree.scala-2.smt2  |  20.085s  |  20.085s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-AVLTree.scala-24.smt2  |  21.032s  |  21.032s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-AVLTree.scala-27.smt2  |  21.548s  |  21.548s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-AVLTree.scala-4.smt2  |  20.127s  |  20.127s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-AbsFun.scala-13.smt2  |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-AbsFun.scala-4.smt2  |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-AbsFun.scala-6.smt2  |  20.201s  |  20.201s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-AmortizedQueue.scala-1.smt2  |  20.139s  |  20.139s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ArrayBinarySearch.scala-1.smt2  |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BinarySearchTree.scala-1.smt2  |  20.138s  |  20.138s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-1.smt2  |  20.069s  |  20.069s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-3.smt2  |  20.091s  |  20.091s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-5.smt2  |  21.341s  |  21.341s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-9.smt2  |  20.993s  |  20.993s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BitsTricks.scala-1.smt2  |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BitsTricks.scala-13.smt2  |  20.071s  |  20.071s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BitsTricks.scala-14.smt2  |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BitsTricks.scala-18.smt2  |  20.106s  |  20.106s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BitsTricks.scala-19.smt2  |  16.310s  |  16.310s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BitsTricks.scala-2.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BitsTricks.scala-3.smt2  |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BitsTricks.scala-5.smt2  |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BitsTricks.scala-7.smt2  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BitsTricks.scala-8.smt2  |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BitsTricks.scala-9.smt2  |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Compiler.scala-7.smt2  |  21.469s  |  21.469s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Fibonacci.scala-3.smt2  |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-10.smt2  |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-11.smt2  |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-12.smt2  |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-13.smt2  |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-16.smt2  |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-17.smt2  |  20.095s  |  20.095s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-18.smt2  |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-19.smt2  |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-2.smt2  |  20.115s  |  20.115s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-20.smt2  |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-21.smt2  |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-22.smt2  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-4.smt2  |  20.097s  |  20.097s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-5.smt2  |  20.102s  |  20.102s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-7.smt2  |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-8.smt2  |  20.162s  |  20.162s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-9.smt2  |   3.180s  |   3.180s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-HeapSort.scala-1.smt2  |  20.138s  |  20.138s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-HeapSort.scala-14.smt2  |  20.182s  |  20.182s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-HeapSort.scala-19.smt2  |  20.085s  |  20.085s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-HeapSort.scala-21.smt2  |  20.151s  |  20.151s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-HeapSort.scala-25.smt2  |  20.607s  |  20.607s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-HeapSort.scala-29.smt2  |  20.120s  |  20.120s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-HeapSort.scala-5.smt2  |  20.099s  |  20.099s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-HeapSort.scala-9.smt2  |  21.294s  |  21.294s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-InsertionSort.scala-1.smt2  |  20.359s  |  20.359s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Interpreter.scala-3.smt2  |  20.107s  |  20.107s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Interpreter.scala-4.smt2  |   0.536s  |   0.536s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-LambdaEval.scala-20.smt2  |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-LambdaEval.scala-6.smt2  |  20.121s  |  20.121s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-LambdaEval.scala-60.smt2  |  20.147s  |  20.147s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-1.smt2  |  20.194s  |  20.194s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-13.smt2  |  20.763s  |  20.763s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-5.smt2  |  20.520s  |  20.520s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-8.smt2  |  20.064s  |  20.064s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ListOperations.scala-1.smt2  |  20.201s  |  20.201s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ListOperations.scala-10.smt2  |  20.229s  |  20.229s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ListOperations.scala-13.smt2  |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ListOperations.scala-16.smt2  |  20.436s  |  20.436s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ListOperations.scala-3.smt2  |  20.097s  |  20.097s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ListOperations.scala-5.smt2  |  20.175s  |  20.175s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Lists5.scala-4.smt2  |  20.095s  |  20.095s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Map.scala-1.smt2  |  20.102s  |  20.102s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Map.scala-2.smt2  |  20.088s  |  20.088s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-MergeSort.scala-5.smt2  |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-MergeSort.scala-7.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-MutuallyRecursive.scala-1.smt2  |  20.147s  |  20.147s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Naturals.scala-10.smt2  |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Naturals.scala-11.smt2  |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Naturals.scala-12.smt2  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Naturals.scala-13.smt2  |  20.080s  |  20.080s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Naturals.scala-14.smt2  |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Naturals.scala-2.smt2  |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Naturals.scala-3.smt2  |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Naturals.scala-4.smt2  |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Naturals.scala-5.smt2  |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Naturals.scala-6.smt2  |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Naturals.scala-7.smt2  |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Naturals.scala-8.smt2  |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Naturals.scala-9.smt2  |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Parser.scala-1.smt2  |  20.094s  |  20.094s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Parser.scala-3.smt2  |  20.133s  |  20.133s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Parser.scala-5.smt2  |  20.124s  |  20.124s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Parser.scala-9.smt2  |  20.184s  |  20.184s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PositiveMap.scala-2.smt2  |  20.097s  |  20.097s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-1.smt2  |  20.179s  |  20.179s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-15.smt2  |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-16.smt2  |  20.095s  |  20.095s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-17.smt2  |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-18.smt2  |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-19.smt2  |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-20.smt2  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-21.smt2  |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-22.smt2  |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-23.smt2  |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-24.smt2  |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-25.smt2  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-26.smt2  |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-27.smt2  |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-28.smt2  |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-29.smt2  |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-4.smt2  |  20.193s  |  20.193s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-QuickSort.scala-13.smt2  |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-QuickSort.scala-14.smt2  |   0.635s  |   0.635s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-QuickSort.scala-17.smt2  |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-QuickSort.scala-18.smt2  |   0.357s  |   0.357s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-QuickSort.scala-21.smt2  |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-QuickSort.scala-22.smt2  |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-QuickSort.scala-24.smt2  |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-QuickSort.scala-25.smt2  |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-QuickSort.scala-27.smt2  |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-QuickSort.scala-28.smt2  |  20.094s  |  20.094s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-QuickSort.scala-29.smt2  |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-QuickSort.scala-30.smt2  |  20.100s  |  20.100s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-QuickSort.scala-31.smt2  |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-QuickSort.scala-32.smt2  |  20.141s  |  20.141s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SearchLinkedList.scala-1.smt2  |  20.110s  |  20.110s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SearchLinkedList.scala-4.smt2  |  20.091s  |  20.091s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SearchLinkedList.scala-7.smt2  |  20.179s  |  20.179s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SecondsToTime.scala-1.smt2  |  20.151s  |  20.151s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SecondsToTime.scala-3.smt2  |  20.109s  |  20.109s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SecondsToTime.scala-5.smt2  |  20.134s  |  20.134s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SecondsToTime.scala-8.smt2  |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-1.smt2  |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-10.smt2  |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-12.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-13.smt2  |  20.108s  |  20.108s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-14.smt2  |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-15.smt2  |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-2.smt2  |  20.161s  |  20.161s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-3.smt2  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-4.smt2  |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-7.smt2  |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-8.smt2  |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-9.smt2  |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SimpInterpret.scala-3.smt2  |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SimpInterpret.scala-4.smt2  |   0.419s  |   0.419s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SortedList.scala-1.smt2  |  20.097s  |  20.097s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SortedNDList.scala-2.smt2  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SortedNDList.scala-3.smt2  |  20.204s  |  20.204s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SumAndMax.scala-4.smt2  |  20.238s  |  20.238s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SumAndMax.scala-7.smt2  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Sync.scala-1.smt2  |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-TwoSizeFunctions.scala-1.smt2  |  20.116s  |  20.116s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-TwoSizeFunctions.scala-4.smt2  |  20.180s  |  20.180s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-TwoSizeFunctions.scala-7.smt2  |  20.161s  |  20.161s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-muDot2.scala-41.smt2  |  20.068s  |  20.068s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-muDot2.scala-43.smt2  |  20.113s  |  20.113s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-100.smt2  |  20.235s  |  20.235s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-101.smt2  |  20.871s  |  20.871s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-102.smt2  |  20.272s  |  20.272s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-103.smt2  |  20.225s  |  20.225s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-104.smt2  |  20.829s  |  20.829s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-105.smt2  |  21.079s  |  21.079s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-106.smt2  |  20.214s  |  20.214s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-107.smt2  |  20.096s  |  20.096s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-108.smt2  |  20.268s  |  20.268s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-109.smt2  |  20.269s  |  20.269s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-110.smt2  |  20.120s  |  20.120s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-111.smt2  |  21.712s  |  21.712s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-112.smt2  |  21.066s  |  21.066s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-113.smt2  |  20.410s  |  20.410s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-114.smt2  |  20.477s  |  20.477s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-115.smt2  |  20.738s  |  20.738s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-116.smt2  |  20.880s  |  20.880s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-36.smt2  |  21.161s  |  21.161s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-37.smt2  |  20.127s  |  20.127s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-38.smt2  |  20.094s  |  20.094s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-39.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-40.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-41.smt2  |  20.166s  |  20.166s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-42.smt2  |  20.109s  |  20.109s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-43.smt2  |  20.139s  |  20.139s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-44.smt2  |  20.170s  |  20.170s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-45.smt2  |  20.210s  |  20.210s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-46.smt2  |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-47.smt2  |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-48.smt2  |  20.475s  |  20.475s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-49.smt2  |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-50.smt2  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-51.smt2  |  20.480s  |  20.480s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-52.smt2  |  20.179s  |  20.179s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-53.smt2  |  20.519s  |  20.519s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-54.smt2  |  20.182s  |  20.182s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-55.smt2  |  20.133s  |  20.133s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-56.smt2  |  20.104s  |  20.104s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-57.smt2  |  20.572s  |  20.572s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-58.smt2  |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-59.smt2  |  20.468s  |  20.468s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-60.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-61.smt2  |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-62.smt2  |  20.100s  |  20.100s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-63.smt2  |  20.200s  |  20.200s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-64.smt2  |  20.114s  |  20.114s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-65.smt2  |  20.231s  |  20.231s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-66.smt2  |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-67.smt2  |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-68.smt2  |  20.112s  |  20.112s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-69.smt2  |  20.172s  |  20.172s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-70.smt2  |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-71.smt2  |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-72.smt2  |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-73.smt2  |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-76.smt2  |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-77.smt2  |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-78.smt2  |  20.259s  |  20.259s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-79.smt2  |  20.264s  |  20.264s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-80.smt2  |  20.144s  |  20.144s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-81.smt2  |  21.285s  |  21.285s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-82.smt2  |  20.104s  |  20.104s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-83.smt2  |  20.188s  |  20.188s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-84.smt2  |  20.232s  |  20.232s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-85.smt2  |  20.117s  |  20.117s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-86.smt2  |  20.120s  |  20.120s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-87.smt2  |  20.158s  |  20.158s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-88.smt2  |  20.114s  |  20.114s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-89.smt2  |  21.103s  |  21.103s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-90.smt2  |  20.101s  |  20.101s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-91.smt2  |  20.128s  |  20.128s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-92.smt2  |  20.172s  |  20.172s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-93.smt2  |  20.174s  |  20.174s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-94.smt2  |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-95.smt2  |  20.245s  |  20.245s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-96.smt2  |  20.248s  |  20.248s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-97.smt2  |  20.241s  |  20.241s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-98.smt2  |  20.169s  |  20.169s  |   0.000s  | 0.0%|
</details>
