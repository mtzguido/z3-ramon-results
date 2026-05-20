Comparing data and data


# SUMMARY
- LHS tests = 795
- RHS tests = 795
- LHS success = 795  (100.0%)
- RHS success = 795  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: AUFDTLIA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/AUFDTLIA.tar.zst?download=1
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
Job tag: AUFDTLIA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/AUFDTLIA.tar.zst?download=1
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
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree1.smt2                 |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree10.smt2                |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree100.smt2               |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree101.smt2               |  20.110s  |  20.110s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree102.smt2               |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree103.smt2               |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree104.smt2               |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree105.smt2               |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree106.smt2               |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree107.smt2               |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree108.smt2               |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree109.smt2               |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree11.smt2                |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree110.smt2               |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree111.smt2               |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree112.smt2               |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree113.smt2               |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree114.smt2               |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree115.smt2               |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree116.smt2               |   0.120s  |   0.120s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree1.smt2                 |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree10.smt2                |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree100.smt2               |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree101.smt2               |  20.110s  |  20.110s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree102.smt2               |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree103.smt2               |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree104.smt2               |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree105.smt2               |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree106.smt2               |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree107.smt2               |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree108.smt2               |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree109.smt2               |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree11.smt2                |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree110.smt2               |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree111.smt2               |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree112.smt2               |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree113.smt2               |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree114.smt2               |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree115.smt2               |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree116.smt2               |   0.120s  |   0.120s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree1.smt2                 |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree10.smt2                |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree100.smt2               |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree101.smt2               |  20.110s  |  20.110s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree102.smt2               |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree103.smt2               |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree104.smt2               |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree105.smt2               |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree106.smt2               |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree107.smt2               |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree108.smt2               |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree109.smt2               |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree11.smt2                |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree110.smt2               |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree111.smt2               |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree112.smt2               |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree113.smt2               |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree114.smt2               |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree115.smt2               |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree116.smt2               |   0.120s  |   0.120s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree1.smt2                 |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree10.smt2                |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree100.smt2               |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree101.smt2               |  20.110s  |  20.110s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree102.smt2               |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree103.smt2               |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree104.smt2               |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree105.smt2               |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree106.smt2               |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree107.smt2               |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree108.smt2               |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree109.smt2               |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree11.smt2                |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree110.smt2               |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree111.smt2               |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree112.smt2               |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree113.smt2               |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree114.smt2               |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree115.smt2               |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree116.smt2               |   0.120s  |   0.120s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount35.smt2             |  20.163s |235.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree267.smt2              |  20.158s |69.128MiB|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-coninv-f5.ucl-property_correspondence-vobj-0010.smt2 |  20.145s |39.904MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount46.smt2             |  20.139s |257.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree387.smt2              |  20.126s |61.5MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree158.smt2              |  20.120s |229.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree176.smt2              |  20.119s |126.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree450.smt2              |  20.118s |181.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree277.smt2              |  20.117s |114.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree184.smt2              |  20.117s |89.644MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree393.smt2              |  20.116s |76.26MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree244.smt2              |  20.116s |116.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree371.smt2              |  20.115s |99.42MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree410.smt2              |  20.113s |70.488MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree509.smt2              |  20.111s |87.852MiB|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-noinv-f5.ucl-property_correspondence-vobj-0010.smt2 |  20.110s |37.912MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree101.smt2              |  20.110s |81.188MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree351.smt2              |  20.103s |66.42MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree259.smt2              |  20.103s |118.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount40.smt2             |  20.101s |255.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount35.smt2             |  20.163s |235.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree267.smt2              |  20.158s |69.128MiB|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-coninv-f5.ucl-property_correspondence-vobj-0010.smt2 |  20.145s |39.904MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount46.smt2             |  20.139s |257.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree387.smt2              |  20.126s |61.5MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree158.smt2              |  20.120s |229.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree176.smt2              |  20.119s |126.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree450.smt2              |  20.118s |181.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree277.smt2              |  20.117s |114.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree184.smt2              |  20.117s |89.644MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree393.smt2              |  20.116s |76.26MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree244.smt2              |  20.116s |116.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree371.smt2              |  20.115s |99.42MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree410.smt2              |  20.113s |70.488MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree509.smt2              |  20.111s |87.852MiB|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-noinv-f5.ucl-property_correspondence-vobj-0010.smt2 |  20.110s |37.912MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree101.smt2              |  20.110s |81.188MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree351.smt2              |  20.103s |66.42MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree259.smt2              |  20.103s |118.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount40.smt2             |  20.101s |255.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree1.smt2                 |20.416MiB|20.416MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree10.smt2                |19.94MiB|19.94MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree100.smt2               |19.764MiB|19.764MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree101.smt2               |81.188MiB|81.188MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree102.smt2               |19.512MiB|19.512MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree103.smt2               |19.716MiB|19.716MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree104.smt2               |19.6MiB|19.6MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree105.smt2               |19.744MiB|19.744MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree106.smt2               |19.62MiB|19.62MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree107.smt2               |19.6MiB|19.6MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree108.smt2               |19.704MiB|19.704MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree109.smt2               |19.54MiB|19.54MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree11.smt2                |20.472MiB|20.472MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree110.smt2               |19.536MiB|19.536MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree111.smt2               |91.224MiB|91.224MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree112.smt2               |19.64MiB|19.64MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree113.smt2               |20.112MiB|20.112MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree114.smt2               |19.6MiB|19.6MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree115.smt2               |19.612MiB|19.612MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree116.smt2               |19.628MiB|19.628MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree1.smt2                 |20.416MiB|20.416MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree10.smt2                |19.94MiB|19.94MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree100.smt2               |19.764MiB|19.764MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree101.smt2               |81.188MiB|81.188MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree102.smt2               |19.512MiB|19.512MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree103.smt2               |19.716MiB|19.716MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree104.smt2               |19.6MiB|19.6MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree105.smt2               |19.744MiB|19.744MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree106.smt2               |19.62MiB|19.62MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree107.smt2               |19.6MiB|19.6MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree108.smt2               |19.704MiB|19.704MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree109.smt2               |19.54MiB|19.54MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree11.smt2                |20.472MiB|20.472MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree110.smt2               |19.536MiB|19.536MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree111.smt2               |91.224MiB|91.224MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree112.smt2               |19.64MiB|19.64MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree113.smt2               |20.112MiB|20.112MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree114.smt2               |19.6MiB|19.6MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree115.smt2               |19.612MiB|19.612MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree116.smt2               |19.628MiB|19.628MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree1.smt2                 |20.416MiB|20.416MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree10.smt2                |19.94MiB|19.94MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree100.smt2               |19.764MiB|19.764MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree101.smt2               |81.188MiB|81.188MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree102.smt2               |19.512MiB|19.512MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree103.smt2               |19.716MiB|19.716MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree104.smt2               |19.6MiB|19.6MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree105.smt2               |19.744MiB|19.744MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree106.smt2               |19.62MiB|19.62MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree107.smt2               |19.6MiB|19.6MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree108.smt2               |19.704MiB|19.704MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree109.smt2               |19.54MiB|19.54MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree11.smt2                |20.472MiB|20.472MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree110.smt2               |19.536MiB|19.536MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree111.smt2               |91.224MiB|91.224MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree112.smt2               |19.64MiB|19.64MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree113.smt2               |20.112MiB|20.112MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree114.smt2               |19.6MiB|19.6MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree115.smt2               |19.612MiB|19.612MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree116.smt2               |19.628MiB|19.628MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree1.smt2                 |20.416MiB|20.416MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree10.smt2                |19.94MiB|19.94MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree100.smt2               |19.764MiB|19.764MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree101.smt2               |81.188MiB|81.188MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree102.smt2               |19.512MiB|19.512MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree103.smt2               |19.716MiB|19.716MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree104.smt2               |19.6MiB|19.6MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree105.smt2               |19.744MiB|19.744MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree106.smt2               |19.62MiB|19.62MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree107.smt2               |19.6MiB|19.6MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree108.smt2               |19.704MiB|19.704MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree109.smt2               |19.54MiB|19.54MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree11.smt2                |20.472MiB|20.472MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree110.smt2               |19.536MiB|19.536MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree111.smt2               |91.224MiB|91.224MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree112.smt2               |19.64MiB|19.64MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree113.smt2               |20.112MiB|20.112MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree114.smt2               |19.6MiB|19.6MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree115.smt2               |19.612MiB|19.612MiB|0B| 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree116.smt2               |19.628MiB|19.628MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/AUFDTLIA/20210304-uhbexamples/uhb_quantifiers.smt2                         |  20.068s |324.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount28.smt2             |  20.101s |271.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount46.smt2             |  20.139s |257.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount40.smt2             |  20.101s |255.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount36.smt2             |  20.100s |251.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount35.smt2             |  20.163s |235.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree158.smt2              |  20.120s |229.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree313.smt2              |  20.099s |217.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree359.smt2              |  20.040s |207.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree450.smt2              |  20.118s |181.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree166.smt2              |  20.046s |148.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree212.smt2              |  20.050s |142.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree347.smt2              |  20.032s |136.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree485.smt2              |  20.042s |129.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree477.smt2              |  20.059s |128.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree303.smt2              |  20.054s |128.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree176.smt2              |  20.119s |126.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree220.smt2              |  20.048s |124.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree259.smt2              |  20.103s |118.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree461.smt2              |  20.056s |117.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/AUFDTLIA/20210304-uhbexamples/uhb_quantifiers.smt2                         |  20.068s |324.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount28.smt2             |  20.101s |271.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount46.smt2             |  20.139s |257.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount40.smt2             |  20.101s |255.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount36.smt2             |  20.100s |251.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount35.smt2             |  20.163s |235.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree158.smt2              |  20.120s |229.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree313.smt2              |  20.099s |217.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree359.smt2              |  20.040s |207.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree450.smt2              |  20.118s |181.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree166.smt2              |  20.046s |148.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree212.smt2              |  20.050s |142.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree347.smt2              |  20.032s |136.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree485.smt2              |  20.042s |129.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree477.smt2              |  20.059s |128.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree303.smt2              |  20.054s |128.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree176.smt2              |  20.119s |126.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree220.smt2              |  20.048s |124.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree259.smt2              |  20.103s |118.0MiB|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree461.smt2              |  20.056s |117.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree1.smt2                 |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree10.smt2                |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree100.smt2               |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree101.smt2               |  20.110s  |  20.110s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree102.smt2               |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree103.smt2               |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree104.smt2               |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree105.smt2               |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree106.smt2               |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree107.smt2               |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree108.smt2               |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree109.smt2               |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree11.smt2                |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree110.smt2               |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree111.smt2               |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree112.smt2               |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree113.smt2               |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree114.smt2               |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree115.smt2               |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree116.smt2               |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree117.smt2               |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree118.smt2               |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree119.smt2               |  20.097s  |  20.097s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree12.smt2                |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree120.smt2               |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree121.smt2               |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree122.smt2               |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree123.smt2               |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree124.smt2               |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree125.smt2               |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree126.smt2               |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree127.smt2               |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree128.smt2               |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree129.smt2               |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree13.smt2                |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree130.smt2               |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree131.smt2               |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree132.smt2               |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree133.smt2               |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree134.smt2               |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree135.smt2               |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree136.smt2               |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree137.smt2               |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree138.smt2               |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree139.smt2               |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree14.smt2                |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree140.smt2               |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree141.smt2               |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree142.smt2               |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree143.smt2               |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree144.smt2               |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree145.smt2               |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree146.smt2               |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree147.smt2               |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree148.smt2               |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree149.smt2               |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree15.smt2                |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree150.smt2               |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree151.smt2               |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree152.smt2               |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree154.smt2               |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree155.smt2               |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree156.smt2               |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree157.smt2               |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree158.smt2               |  20.120s  |  20.120s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree159.smt2               |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree16.smt2                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree160.smt2               |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree162.smt2               |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree163.smt2               |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree164.smt2               |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree165.smt2               |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree166.smt2               |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree167.smt2               |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree168.smt2               |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree17.smt2                |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree170.smt2               |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree171.smt2               |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree172.smt2               |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree173.smt2               |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree174.smt2               |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree175.smt2               |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree176.smt2               |  20.119s  |  20.119s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree178.smt2               |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree179.smt2               |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree18.smt2                |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree180.smt2               |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree181.smt2               |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree182.smt2               |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree183.smt2               |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree184.smt2               |  20.117s  |  20.117s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree186.smt2               |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree187.smt2               |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree188.smt2               |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree189.smt2               |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree19.smt2                |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree190.smt2               |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree191.smt2               |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree192.smt2               |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree193.smt2               |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree194.smt2               |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree195.smt2               |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree196.smt2               |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree197.smt2               |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree198.smt2               |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree199.smt2               |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree2.smt2                 |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree20.smt2                |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree200.smt2               |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree201.smt2               |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree202.smt2               |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree203.smt2               |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree204.smt2               |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree205.smt2               |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree206.smt2               |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree207.smt2               |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree208.smt2               |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree209.smt2               |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree21.smt2                |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree211.smt2               |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree212.smt2               |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree213.smt2               |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree214.smt2               |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree215.smt2               |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree216.smt2               |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree217.smt2               |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree219.smt2               |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree22.smt2                |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree220.smt2               |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree221.smt2               |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree222.smt2               |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree223.smt2               |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree224.smt2               |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree225.smt2               |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree226.smt2               |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree227.smt2               |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree228.smt2               |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree229.smt2               |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree23.smt2                |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree230.smt2               |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree231.smt2               |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree232.smt2               |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree233.smt2               |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree234.smt2               |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree235.smt2               |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree236.smt2               |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree237.smt2               |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree238.smt2               |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree239.smt2               |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree24.smt2                |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree240.smt2               |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree241.smt2               |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree243.smt2               |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree244.smt2               |  20.116s  |  20.116s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree245.smt2               |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree246.smt2               |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree247.smt2               |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree248.smt2               |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree249.smt2               |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree25.smt2                |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree250.smt2               |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree251.smt2               |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree252.smt2               |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree253.smt2               |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree254.smt2               |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree255.smt2               |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree256.smt2               |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree257.smt2               |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree259.smt2               |  20.103s  |  20.103s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree26.smt2                |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree260.smt2               |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree261.smt2               |  20.074s  |  20.074s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree262.smt2               |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree263.smt2               |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree264.smt2               |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree265.smt2               |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree267.smt2               |  20.158s  |  20.158s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree268.smt2               |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree269.smt2               |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree27.smt2                |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree270.smt2               |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree271.smt2               |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree272.smt2               |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree273.smt2               |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree275.smt2               |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree276.smt2               |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree277.smt2               |  20.117s  |  20.117s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree278.smt2               |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree279.smt2               |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree28.smt2                |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree280.smt2               |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree281.smt2               |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree282.smt2               |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree283.smt2               |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree284.smt2               |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree285.smt2               |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree286.smt2               |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree287.smt2               |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree288.smt2               |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree289.smt2               |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree29.smt2                |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree290.smt2               |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree291.smt2               |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree292.smt2               |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree293.smt2               |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree294.smt2               |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree295.smt2               |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree296.smt2               |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree297.smt2               |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree298.smt2               |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree3.smt2                 |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree30.smt2                |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree300.smt2               |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree301.smt2               |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree302.smt2               |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree303.smt2               |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree304.smt2               |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree305.smt2               |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree306.smt2               |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree308.smt2               |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree309.smt2               |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree31.smt2                |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree310.smt2               |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree311.smt2               |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree312.smt2               |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree313.smt2               |  20.099s  |  20.099s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree314.smt2               |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree315.smt2               |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree316.smt2               |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree317.smt2               |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree318.smt2               |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree319.smt2               |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree32.smt2                |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree320.smt2               |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree321.smt2               |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree322.smt2               |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree323.smt2               |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree324.smt2               |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree325.smt2               |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree326.smt2               |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree327.smt2               |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree328.smt2               |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree329.smt2               |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree33.smt2                |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree330.smt2               |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree331.smt2               |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree332.smt2               |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree333.smt2               |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree334.smt2               |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree335.smt2               |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree336.smt2               |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree337.smt2               |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree338.smt2               |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree339.smt2               |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree34.smt2                |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree340.smt2               |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree341.smt2               |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree343.smt2               |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree344.smt2               |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree345.smt2               |  20.095s  |  20.095s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree346.smt2               |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree347.smt2               |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree348.smt2               |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree349.smt2               |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree35.smt2                |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree351.smt2               |  20.103s  |  20.103s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree352.smt2               |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree353.smt2               |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree354.smt2               |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree355.smt2               |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree356.smt2               |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree357.smt2               |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree359.smt2               |  20.040s  |  20.040s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree36.smt2                |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree360.smt2               |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree361.smt2               |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree362.smt2               |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree363.smt2               |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree364.smt2               |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree365.smt2               |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree367.smt2               |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree368.smt2               |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree369.smt2               |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree37.smt2                |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree370.smt2               |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree371.smt2               |  20.115s  |  20.115s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree372.smt2               |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree373.smt2               |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree375.smt2               |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree376.smt2               |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree377.smt2               |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree378.smt2               |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree379.smt2               |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree38.smt2                |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree380.smt2               |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree381.smt2               |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree383.smt2               |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree384.smt2               |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree385.smt2               |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree386.smt2               |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree387.smt2               |  20.126s  |  20.126s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree388.smt2               |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree389.smt2               |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree39.smt2                |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree391.smt2               |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree392.smt2               |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree393.smt2               |  20.116s  |  20.116s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree394.smt2               |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree395.smt2               |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree396.smt2               |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree397.smt2               |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree398.smt2               |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree399.smt2               |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree4.smt2                 |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree40.smt2                |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree400.smt2               |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree401.smt2               |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree402.smt2               |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree403.smt2               |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree404.smt2               |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree405.smt2               |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree406.smt2               |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree408.smt2               |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree409.smt2               |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree410.smt2               |  20.113s  |  20.113s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree411.smt2               |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree412.smt2               |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree413.smt2               |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree414.smt2               |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree415.smt2               |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree416.smt2               |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree417.smt2               |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree418.smt2               |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree419.smt2               |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree42.smt2                |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree420.smt2               |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree421.smt2               |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree422.smt2               |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree423.smt2               |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree424.smt2               |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree425.smt2               |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree426.smt2               |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree427.smt2               |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree428.smt2               |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree429.smt2               |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree43.smt2                |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree430.smt2               |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree431.smt2               |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree432.smt2               |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree433.smt2               |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree434.smt2               |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree435.smt2               |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree436.smt2               |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree437.smt2               |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree438.smt2               |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree439.smt2               |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree44.smt2                |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree440.smt2               |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree441.smt2               |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree442.smt2               |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree444.smt2               |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree445.smt2               |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree446.smt2               |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree447.smt2               |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree448.smt2               |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree449.smt2               |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree45.smt2                |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree450.smt2               |  20.118s  |  20.118s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree451.smt2               |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree452.smt2               |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree453.smt2               |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree454.smt2               |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree455.smt2               |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree456.smt2               |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree457.smt2               |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree458.smt2               |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree46.smt2                |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree460.smt2               |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree461.smt2               |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree462.smt2               |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree463.smt2               |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree464.smt2               |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree465.smt2               |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree466.smt2               |  20.083s  |  20.083s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree468.smt2               |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree469.smt2               |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree47.smt2                |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree470.smt2               |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree471.smt2               |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree472.smt2               |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree473.smt2               |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree474.smt2               |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree476.smt2               |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree477.smt2               |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree478.smt2               |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree479.smt2               |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree48.smt2                |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree480.smt2               |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree481.smt2               |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree482.smt2               |  20.098s  |  20.098s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree484.smt2               |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree485.smt2               |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree486.smt2               |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree487.smt2               |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree488.smt2               |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree489.smt2               |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree490.smt2               |  20.087s  |  20.087s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree492.smt2               |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree493.smt2               |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree494.smt2               |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree495.smt2               |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree496.smt2               |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree497.smt2               |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree498.smt2               |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree5.smt2                 |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree50.smt2                |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree500.smt2               |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree501.smt2               |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree502.smt2               |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree503.smt2               |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree504.smt2               |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree505.smt2               |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree506.smt2               |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree508.smt2               |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree509.smt2               |  20.111s  |  20.111s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree51.smt2                |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree510.smt2               |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree511.smt2               |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree512.smt2               |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree513.smt2               |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree514.smt2               |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree515.smt2               |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree516.smt2               |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree517.smt2               |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree518.smt2               |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree519.smt2               |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree52.smt2                |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree520.smt2               |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree521.smt2               |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree522.smt2               |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree523.smt2               |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree524.smt2               |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree525.smt2               |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree526.smt2               |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree527.smt2               |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree528.smt2               |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree529.smt2               |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree53.smt2                |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree530.smt2               |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree54.smt2                |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree55.smt2                |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree56.smt2                |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree57.smt2                |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree58.smt2                |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree59.smt2                |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree6.smt2                 |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree60.smt2                |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree61.smt2                |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree62.smt2                |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree63.smt2                |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree64.smt2                |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree65.smt2                |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree66.smt2                |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree67.smt2                |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree68.smt2                |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree69.smt2                |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree7.smt2                 |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree70.smt2                |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree71.smt2                |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree72.smt2                |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree73.smt2                |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree74.smt2                |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree75.smt2                |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree76.smt2                |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree77.smt2                |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree78.smt2                |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree79.smt2                |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree8.smt2                 |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree80.smt2                |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree81.smt2                |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree82.smt2                |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree83.smt2                |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree84.smt2                |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree85.smt2                |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree86.smt2                |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree87.smt2                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree88.smt2                |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree9.smt2                 |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree90.smt2                |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree91.smt2                |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree92.smt2                |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree93.smt2                |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree94.smt2                |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree95.smt2                |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree96.smt2                |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree98.smt2                |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree99.smt2                |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german1.smt2                   |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german10.smt2                  |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german100.smt2                 |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german101.smt2                 |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german102.smt2                 |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german103.smt2                 |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german104.smt2                 |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german105.smt2                 |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german106.smt2                 |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german107.smt2                 |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german108.smt2                 |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german109.smt2                 |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german11.smt2                  |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german110.smt2                 |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german111.smt2                 |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german112.smt2                 |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german113.smt2                 |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german114.smt2                 |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german115.smt2                 |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german116.smt2                 |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german117.smt2                 |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german118.smt2                 |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german119.smt2                 |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german12.smt2                  |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german120.smt2                 |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german121.smt2                 |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german122.smt2                 |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german123.smt2                 |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german124.smt2                 |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german125.smt2                 |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german126.smt2                 |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german127.smt2                 |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german128.smt2                 |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german129.smt2                 |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german13.smt2                  |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german130.smt2                 |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german131.smt2                 |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german132.smt2                 |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german133.smt2                 |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german134.smt2                 |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german135.smt2                 |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german136.smt2                 |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german137.smt2                 |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german138.smt2                 |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german139.smt2                 |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german14.smt2                  |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german140.smt2                 |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german141.smt2                 |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german142.smt2                 |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german143.smt2                 |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german144.smt2                 |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german145.smt2                 |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german146.smt2                 |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german147.smt2                 |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german148.smt2                 |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german149.smt2                 |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german15.smt2                  |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german150.smt2                 |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german151.smt2                 |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german152.smt2                 |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german153.smt2                 |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german154.smt2                 |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german155.smt2                 |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german156.smt2                 |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german157.smt2                 |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german158.smt2                 |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german159.smt2                 |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german16.smt2                  |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german160.smt2                 |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german161.smt2                 |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german162.smt2                 |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german163.smt2                 |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german164.smt2                 |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german165.smt2                 |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german166.smt2                 |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german167.smt2                 |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german168.smt2                 |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german169.smt2                 |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german17.smt2                  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german170.smt2                 |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german171.smt2                 |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german172.smt2                 |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german173.smt2                 |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german174.smt2                 |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german175.smt2                 |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german176.smt2                 |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german177.smt2                 |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german178.smt2                 |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german179.smt2                 |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german18.smt2                  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german180.smt2                 |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german181.smt2                 |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german182.smt2                 |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german183.smt2                 |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german184.smt2                 |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german185.smt2                 |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german186.smt2                 |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german187.smt2                 |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german188.smt2                 |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german189.smt2                 |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german19.smt2                  |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german190.smt2                 |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german2.smt2                   |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german20.smt2                  |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german21.smt2                  |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german22.smt2                  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german23.smt2                  |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german24.smt2                  |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german25.smt2                  |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german26.smt2                  |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german27.smt2                  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german28.smt2                  |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german29.smt2                  |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german3.smt2                   |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german30.smt2                  |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german31.smt2                  |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german32.smt2                  |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german33.smt2                  |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german34.smt2                  |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german35.smt2                  |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german36.smt2                  |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german37.smt2                  |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german38.smt2                  |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german39.smt2                  |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german4.smt2                   |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german40.smt2                  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german41.smt2                  |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german42.smt2                  |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german43.smt2                  |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german44.smt2                  |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german45.smt2                  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german46.smt2                  |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german47.smt2                  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german48.smt2                  |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german49.smt2                  |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german5.smt2                   |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german50.smt2                  |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german51.smt2                  |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german52.smt2                  |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german53.smt2                  |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german54.smt2                  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german55.smt2                  |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german56.smt2                  |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german57.smt2                  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german58.smt2                  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german59.smt2                  |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german6.smt2                   |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german60.smt2                  |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german61.smt2                  |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german62.smt2                  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german63.smt2                  |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german64.smt2                  |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german65.smt2                  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german66.smt2                  |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german67.smt2                  |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german68.smt2                  |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german69.smt2                  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german7.smt2                   |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german70.smt2                  |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german71.smt2                  |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german72.smt2                  |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german73.smt2                  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german74.smt2                  |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german75.smt2                  |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german76.smt2                  |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german77.smt2                  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german78.smt2                  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german79.smt2                  |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german8.smt2                   |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german80.smt2                  |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german81.smt2                  |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german82.smt2                  |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german83.smt2                  |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german84.smt2                  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german85.smt2                  |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german86.smt2                  |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german87.smt2                  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german88.smt2                  |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german89.smt2                  |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german9.smt2                   |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german90.smt2                  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german91.smt2                  |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german92.smt2                  |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german93.smt2                  |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german94.smt2                  |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german95.smt2                  |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german96.smt2                  |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german97.smt2                  |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german98.smt2                  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german99.smt2                  |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount1.smt2               |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount10.smt2              |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount11.smt2              |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount12.smt2              |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount13.smt2              |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount14.smt2              |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount15.smt2              |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount16.smt2              |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount17.smt2              |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount18.smt2              |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount19.smt2              |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount2.smt2               |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount20.smt2              |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount21.smt2              |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount23.smt2              |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount24.smt2              |   2.164s  |   2.164s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount25.smt2              |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount26.smt2              |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount28.smt2              |  20.101s  |  20.101s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount29.smt2              |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount3.smt2               |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount30.smt2              |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount31.smt2              |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount33.smt2              |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount34.smt2              |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount35.smt2              |  20.163s  |  20.163s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount36.smt2              |  20.100s  |  20.100s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount38.smt2              |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount39.smt2              |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount4.smt2               |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount40.smt2              |  20.101s  |  20.101s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount41.smt2              |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount43.smt2              |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount44.smt2              |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount45.smt2              |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount46.smt2              |  20.139s  |  20.139s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount5.smt2               |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount6.smt2               |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount7.smt2               |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount8.smt2               |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount9.smt2               |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-coninv-f5.ucl-property_correspondence-vobj-0002.smt2  |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-coninv-f5.ucl-property_correspondence-vobj-0003.smt2  |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-coninv-f5.ucl-property_correspondence-vobj-0004.smt2  |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-coninv-f5.ucl-property_correspondence-vobj-0005.smt2  |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-coninv-f5.ucl-property_correspondence-vobj-0006.smt2  |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-coninv-f5.ucl-property_correspondence-vobj-0007.smt2  |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-coninv-f5.ucl-property_correspondence-vobj-0008.smt2  |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-coninv-f5.ucl-property_correspondence-vobj-0009.smt2  |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-coninv-f5.ucl-property_correspondence-vobj-0010.smt2  |  20.145s  |  20.145s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-noinv-f5.ucl-property_correspondence-vobj-0002.smt2  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-noinv-f5.ucl-property_correspondence-vobj-0003.smt2  |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-noinv-f5.ucl-property_correspondence-vobj-0004.smt2  |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-noinv-f5.ucl-property_correspondence-vobj-0005.smt2  |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-noinv-f5.ucl-property_correspondence-vobj-0006.smt2  |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-noinv-f5.ucl-property_correspondence-vobj-0007.smt2  |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-noinv-f5.ucl-property_correspondence-vobj-0008.smt2  |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-noinv-f5.ucl-property_correspondence-vobj-0009.smt2  |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-noinv-f5.ucl-property_correspondence-vobj-0010.smt2  |  20.088s  |  20.088s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-coninv-f5.ucl-property_correspondence-vobj-0002.smt2  |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-coninv-f5.ucl-property_correspondence-vobj-0003.smt2  |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-coninv-f5.ucl-property_correspondence-vobj-0004.smt2  |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-coninv-f5.ucl-property_correspondence-vobj-0005.smt2  |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-coninv-f5.ucl-property_correspondence-vobj-0006.smt2  |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-coninv-f5.ucl-property_correspondence-vobj-0007.smt2  |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-coninv-f5.ucl-property_correspondence-vobj-0008.smt2  |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-coninv-f5.ucl-property_correspondence-vobj-0009.smt2  |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-coninv-f5.ucl-property_correspondence-vobj-0010.smt2  |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-noinv-f5.ucl-property_correspondence-vobj-0002.smt2  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-noinv-f5.ucl-property_correspondence-vobj-0003.smt2  |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-noinv-f5.ucl-property_correspondence-vobj-0004.smt2  |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-noinv-f5.ucl-property_correspondence-vobj-0005.smt2  |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-noinv-f5.ucl-property_correspondence-vobj-0006.smt2  |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-noinv-f5.ucl-property_correspondence-vobj-0007.smt2  |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-noinv-f5.ucl-property_correspondence-vobj-0008.smt2  |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-noinv-f5.ucl-property_correspondence-vobj-0009.smt2  |   0.232s  |   0.232s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-noinv-f5.ucl-property_correspondence-vobj-0010.smt2  |  20.110s  |  20.110s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-coninv-f5.ucl-property_correspondence-vobj-0002.smt2  |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-coninv-f5.ucl-property_correspondence-vobj-0003.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-coninv-f5.ucl-property_correspondence-vobj-0004.smt2  |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-coninv-f5.ucl-property_correspondence-vobj-0005.smt2  |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-coninv-f5.ucl-property_correspondence-vobj-0006.smt2  |   0.196s  |   0.196s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-coninv-f5.ucl-property_correspondence-vobj-0007.smt2  |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-coninv-f5.ucl-property_correspondence-vobj-0008.smt2  |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-coninv-f5.ucl-property_correspondence-vobj-0009.smt2  |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-coninv-f5.ucl-property_correspondence-vobj-0010.smt2  |  11.800s  |  11.800s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-noinv-f5.ucl-property_correspondence-vobj-0002.smt2  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-noinv-f5.ucl-property_correspondence-vobj-0003.smt2  |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-noinv-f5.ucl-property_correspondence-vobj-0004.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-noinv-f5.ucl-property_correspondence-vobj-0005.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-noinv-f5.ucl-property_correspondence-vobj-0006.smt2  |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-noinv-f5.ucl-property_correspondence-vobj-0007.smt2  |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-noinv-f5.ucl-property_correspondence-vobj-0008.smt2  |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-noinv-f5.ucl-property_correspondence-vobj-0009.smt2  |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-noinv-f5.ucl-property_correspondence-vobj-0010.smt2  |  14.055s  |  14.055s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-umem-coninv-f5.ucl-property_correspondence-vobj-0002.smt2  |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-umem-coninv-f5.ucl-property_correspondence-vobj-0003.smt2  |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-umem-coninv-f5.ucl-property_correspondence-vobj-0004.smt2  |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-umem-coninv-f5.ucl-property_correspondence-vobj-0005.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-umem-coninv-f5.ucl-property_correspondence-vobj-0006.smt2  |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-umem-coninv-f5.ucl-property_correspondence-vobj-0007.smt2  |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-umem-coninv-f5.ucl-property_correspondence-vobj-0008.smt2  |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-umem-coninv-f5.ucl-property_correspondence-vobj-0009.smt2  |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-umem-coninv-f5.ucl-property_correspondence-vobj-0010.smt2  |   8.888s  |   8.888s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-umem-noinv-f5.ucl-property_correspondence-vobj-0002.smt2  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-umem-noinv-f5.ucl-property_correspondence-vobj-0003.smt2  |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-umem-noinv-f5.ucl-property_correspondence-vobj-0004.smt2  |   0.072s  |   0.072s  |   0.000s  | 0.0%|
</details>
