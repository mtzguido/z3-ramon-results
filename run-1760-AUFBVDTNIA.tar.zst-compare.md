Comparing data and data


# SUMMARY
- LHS tests = 8
- RHS tests = 8
- LHS success = 8  (100.0%)
- RHS success = 8  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: AUFBVDTNIA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/AUFBVDTNIA.tar.zst?download=1
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
Job tag: AUFBVDTNIA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/AUFBVDTNIA.tar.zst?download=1
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
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Prime.scala-2.smt2-3.smt2  |   4.530s  |   4.530s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SumAndMax.scala-10.smt2  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-1.smt2  |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-2.smt2  |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-3.smt2  |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Prime.scala-1.smt2  |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2  |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SumAndMax.scala-10.smt2  |   0.026s  |   0.026s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Prime.scala-2.smt2-3.smt2  |   4.530s  |   4.530s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SumAndMax.scala-10.smt2  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-1.smt2  |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-2.smt2  |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-3.smt2  |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Prime.scala-1.smt2  |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2  |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SumAndMax.scala-10.smt2  |   0.026s  |   0.026s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Prime.scala-2.smt2-3.smt2  |   4.530s  |   4.530s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SumAndMax.scala-10.smt2  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-1.smt2  |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-2.smt2  |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-3.smt2  |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Prime.scala-1.smt2  |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2  |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SumAndMax.scala-10.smt2  |   0.026s  |   0.026s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Prime.scala-2.smt2-3.smt2  |   4.530s  |   4.530s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SumAndMax.scala-10.smt2  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-1.smt2  |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-2.smt2  |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-3.smt2  |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Prime.scala-1.smt2  |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2  |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SumAndMax.scala-10.smt2  |   0.026s  |   0.026s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Prime.scala-1.smt2 |  20.042s |61.052MiB|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-1.smt2 |  20.021s |77.876MiB|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2 |  20.020s |48.42MiB|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-3.smt2 |  20.018s |49.692MiB|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-2.smt2 |  20.016s |38.944MiB|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Prime.scala-2.smt2-3.smt2 |   4.530s |38.524MiB|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SumAndMax.scala-10.smt2 |   0.026s |20.364MiB|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SumAndMax.scala-10.smt2 |   0.025s |20.864MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Prime.scala-1.smt2 |  20.042s |61.052MiB|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-1.smt2 |  20.021s |77.876MiB|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2 |  20.020s |48.42MiB|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-3.smt2 |  20.018s |49.692MiB|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-2.smt2 |  20.016s |38.944MiB|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Prime.scala-2.smt2-3.smt2 |   4.530s |38.524MiB|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SumAndMax.scala-10.smt2 |   0.026s |20.364MiB|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SumAndMax.scala-10.smt2 |   0.025s |20.864MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Prime.scala-2.smt2-3.smt2  |38.524MiB|38.524MiB|0B| 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SumAndMax.scala-10.smt2  |20.864MiB|20.864MiB|0B| 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-1.smt2  |77.876MiB|77.876MiB|0B| 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-2.smt2  |38.944MiB|38.944MiB|0B| 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-3.smt2  |49.692MiB|49.692MiB|0B| 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Prime.scala-1.smt2  |61.052MiB|61.052MiB|0B| 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2  |48.42MiB|48.42MiB|0B| 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SumAndMax.scala-10.smt2  |20.364MiB|20.364MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Prime.scala-2.smt2-3.smt2  |38.524MiB|38.524MiB|0B| 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SumAndMax.scala-10.smt2  |20.864MiB|20.864MiB|0B| 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-1.smt2  |77.876MiB|77.876MiB|0B| 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-2.smt2  |38.944MiB|38.944MiB|0B| 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-3.smt2  |49.692MiB|49.692MiB|0B| 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Prime.scala-1.smt2  |61.052MiB|61.052MiB|0B| 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2  |48.42MiB|48.42MiB|0B| 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SumAndMax.scala-10.smt2  |20.364MiB|20.364MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Prime.scala-2.smt2-3.smt2  |38.524MiB|38.524MiB|0B| 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SumAndMax.scala-10.smt2  |20.864MiB|20.864MiB|0B| 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-1.smt2  |77.876MiB|77.876MiB|0B| 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-2.smt2  |38.944MiB|38.944MiB|0B| 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-3.smt2  |49.692MiB|49.692MiB|0B| 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Prime.scala-1.smt2  |61.052MiB|61.052MiB|0B| 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2  |48.42MiB|48.42MiB|0B| 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SumAndMax.scala-10.smt2  |20.364MiB|20.364MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Prime.scala-2.smt2-3.smt2  |38.524MiB|38.524MiB|0B| 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SumAndMax.scala-10.smt2  |20.864MiB|20.864MiB|0B| 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-1.smt2  |77.876MiB|77.876MiB|0B| 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-2.smt2  |38.944MiB|38.944MiB|0B| 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-3.smt2  |49.692MiB|49.692MiB|0B| 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Prime.scala-1.smt2  |61.052MiB|61.052MiB|0B| 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2  |48.42MiB|48.42MiB|0B| 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SumAndMax.scala-10.smt2  |20.364MiB|20.364MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-1.smt2 |  20.021s |77.876MiB|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Prime.scala-1.smt2 |  20.042s |61.052MiB|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-3.smt2 |  20.018s |49.692MiB|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2 |  20.020s |48.42MiB|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-2.smt2 |  20.016s |38.944MiB|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Prime.scala-2.smt2-3.smt2 |   4.530s |38.524MiB|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SumAndMax.scala-10.smt2 |   0.025s |20.864MiB|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SumAndMax.scala-10.smt2 |   0.026s |20.364MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-1.smt2 |  20.021s |77.876MiB|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Prime.scala-1.smt2 |  20.042s |61.052MiB|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-3.smt2 |  20.018s |49.692MiB|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2 |  20.020s |48.42MiB|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-2.smt2 |  20.016s |38.944MiB|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Prime.scala-2.smt2-3.smt2 |   4.530s |38.524MiB|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SumAndMax.scala-10.smt2 |   0.025s |20.864MiB|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SumAndMax.scala-10.smt2 |   0.026s |20.364MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Prime.scala-2.smt2-3.smt2  |   4.530s  |   4.530s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SumAndMax.scala-10.smt2  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-1.smt2  |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-2.smt2  |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2-3.smt2  |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Prime.scala-1.smt2  |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/AUFBVDTNIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Prime.scala-2.smt2  |  20.020s  |  20.020s  |   0.000s  | 0.0%|
</details>
