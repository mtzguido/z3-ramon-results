Comparing data and data


# SUMMARY
- LHS tests = 490
- RHS tests = 490
- LHS success = 490  (100.0%)
- RHS success = 490  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: LIA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/LIA.tar.zst?download=1
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
Job tag: LIA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/LIA.tar.zst?download=1
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
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_1.smt2  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_10.smt2  |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_11.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_12.smt2  |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_13.smt2  |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_14.smt2  |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_3.smt2  |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_4.smt2  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_5.smt2  |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_6.smt2  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_7.smt2  |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_8.smt2  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_9.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_12.smt2  |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_14.smt2  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_15.smt2  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_2.smt2  |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_0.smt2  |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_10.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_2.smt2  |   0.046s  |   0.046s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_1.smt2  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_10.smt2  |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_11.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_12.smt2  |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_13.smt2  |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_14.smt2  |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_3.smt2  |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_4.smt2  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_5.smt2  |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_6.smt2  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_7.smt2  |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_8.smt2  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_9.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_12.smt2  |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_14.smt2  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_15.smt2  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_2.smt2  |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_0.smt2  |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_10.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_2.smt2  |   0.046s  |   0.046s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_1.smt2  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_10.smt2  |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_11.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_12.smt2  |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_13.smt2  |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_14.smt2  |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_3.smt2  |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_4.smt2  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_5.smt2  |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_6.smt2  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_7.smt2  |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_8.smt2  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_9.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_12.smt2  |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_14.smt2  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_15.smt2  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_2.smt2  |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_0.smt2  |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_10.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_2.smt2  |   0.046s  |   0.046s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_1.smt2  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_10.smt2  |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_11.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_12.smt2  |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_13.smt2  |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_14.smt2  |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_3.smt2  |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_4.smt2  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_5.smt2  |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_6.smt2  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_7.smt2  |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_8.smt2  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_9.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_12.smt2  |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_14.smt2  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_15.smt2  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_2.smt2  |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_0.smt2  |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_10.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_2.smt2  |   0.046s  |   0.046s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/LIA/20250213-Frobenius/fcp_173_179_181.smt2                                |  20.153s |31.724MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_41_43_47.smt2                                   |  20.149s |33.22MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_151_157_163.smt2                                |  20.149s |36.292MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_97_101_103.smt2                                 |  20.148s |35.736MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_47_53_59.smt2                                   |  20.148s |33.872MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_167_173.smt2                                    |  20.145s |40.908MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_89_97.smt2                                      |  20.142s |30.968MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_103_107.smt2                                    |  20.132s |34.384MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_137_139.smt2                                    |  20.123s |37.156MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_31_37.smt2                                      |  20.120s |31.832MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_173_179.smt2                                    |  20.119s |35.512MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_167_173_179.smt2                                |  20.119s |31.528MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_181_191_193.smt2                                |  20.119s |39.988MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_229_233_239.smt2                                |  20.117s |34.584MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_271_277_281.smt2                                |  20.116s |38.608MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_199_211.smt2                                    |  20.114s |36.148MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_181_191.smt2                                    |  20.113s |31.36MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_83_89_97.smt2                                   |  20.112s |34.396MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_127_131.smt2                                    |  20.112s |29.844MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_67_71.smt2                                      |  20.111s |33.48MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/LIA/20250213-Frobenius/fcp_173_179_181.smt2                                |  20.153s |31.724MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_41_43_47.smt2                                   |  20.149s |33.22MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_151_157_163.smt2                                |  20.149s |36.292MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_97_101_103.smt2                                 |  20.148s |35.736MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_47_53_59.smt2                                   |  20.148s |33.872MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_167_173.smt2                                    |  20.145s |40.908MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_89_97.smt2                                      |  20.142s |30.968MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_103_107.smt2                                    |  20.132s |34.384MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_137_139.smt2                                    |  20.123s |37.156MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_31_37.smt2                                      |  20.120s |31.832MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_173_179.smt2                                    |  20.119s |35.512MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_167_173_179.smt2                                |  20.119s |31.528MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_181_191_193.smt2                                |  20.119s |39.988MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_229_233_239.smt2                                |  20.117s |34.584MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_271_277_281.smt2                                |  20.116s |38.608MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_199_211.smt2                                    |  20.114s |36.148MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_181_191.smt2                                    |  20.113s |31.36MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_83_89_97.smt2                                   |  20.112s |34.396MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_127_131.smt2                                    |  20.112s |29.844MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_67_71.smt2                                      |  20.111s |33.48MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_1.smt2  |20.996MiB|20.996MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_10.smt2  |20.772MiB|20.772MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_11.smt2  |21.124MiB|21.124MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_12.smt2  |20.912MiB|20.912MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_13.smt2  |20.904MiB|20.904MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_14.smt2  |20.896MiB|20.896MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_3.smt2  |20.64MiB|20.64MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_4.smt2  |20.708MiB|20.708MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_5.smt2  |20.768MiB|20.768MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_6.smt2  |20.912MiB|20.912MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_7.smt2  |20.876MiB|20.876MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_8.smt2  |20.724MiB|20.724MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_9.smt2  |20.892MiB|20.892MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_12.smt2  |21.188MiB|21.188MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_14.smt2  |20.96MiB|20.96MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_15.smt2  |20.952MiB|20.952MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_2.smt2  |20.876MiB|20.876MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_0.smt2  |21.164MiB|21.164MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_10.smt2  |20.908MiB|20.908MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_2.smt2  |20.864MiB|20.864MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_1.smt2  |20.996MiB|20.996MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_10.smt2  |20.772MiB|20.772MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_11.smt2  |21.124MiB|21.124MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_12.smt2  |20.912MiB|20.912MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_13.smt2  |20.904MiB|20.904MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_14.smt2  |20.896MiB|20.896MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_3.smt2  |20.64MiB|20.64MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_4.smt2  |20.708MiB|20.708MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_5.smt2  |20.768MiB|20.768MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_6.smt2  |20.912MiB|20.912MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_7.smt2  |20.876MiB|20.876MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_8.smt2  |20.724MiB|20.724MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_9.smt2  |20.892MiB|20.892MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_12.smt2  |21.188MiB|21.188MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_14.smt2  |20.96MiB|20.96MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_15.smt2  |20.952MiB|20.952MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_2.smt2  |20.876MiB|20.876MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_0.smt2  |21.164MiB|21.164MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_10.smt2  |20.908MiB|20.908MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_2.smt2  |20.864MiB|20.864MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_1.smt2  |20.996MiB|20.996MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_10.smt2  |20.772MiB|20.772MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_11.smt2  |21.124MiB|21.124MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_12.smt2  |20.912MiB|20.912MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_13.smt2  |20.904MiB|20.904MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_14.smt2  |20.896MiB|20.896MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_3.smt2  |20.64MiB|20.64MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_4.smt2  |20.708MiB|20.708MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_5.smt2  |20.768MiB|20.768MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_6.smt2  |20.912MiB|20.912MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_7.smt2  |20.876MiB|20.876MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_8.smt2  |20.724MiB|20.724MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_9.smt2  |20.892MiB|20.892MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_12.smt2  |21.188MiB|21.188MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_14.smt2  |20.96MiB|20.96MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_15.smt2  |20.952MiB|20.952MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_2.smt2  |20.876MiB|20.876MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_0.smt2  |21.164MiB|21.164MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_10.smt2  |20.908MiB|20.908MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_2.smt2  |20.864MiB|20.864MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_1.smt2  |20.996MiB|20.996MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_10.smt2  |20.772MiB|20.772MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_11.smt2  |21.124MiB|21.124MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_12.smt2  |20.912MiB|20.912MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_13.smt2  |20.904MiB|20.904MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_14.smt2  |20.896MiB|20.896MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_3.smt2  |20.64MiB|20.64MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_4.smt2  |20.708MiB|20.708MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_5.smt2  |20.768MiB|20.768MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_6.smt2  |20.912MiB|20.912MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_7.smt2  |20.876MiB|20.876MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_8.smt2  |20.724MiB|20.724MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_9.smt2  |20.892MiB|20.892MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_12.smt2  |21.188MiB|21.188MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_14.smt2  |20.96MiB|20.96MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_15.smt2  |20.952MiB|20.952MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_2.smt2  |20.876MiB|20.876MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_0.smt2  |21.164MiB|21.164MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_10.smt2  |20.908MiB|20.908MiB|0B| 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_2.smt2  |20.864MiB|20.864MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/LIA/20250213-Frobenius/fcp_241_251.smt2                                    |  20.026s |46.584MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_167_173.smt2                                    |  20.145s |40.908MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_181_191_193.smt2                                |  20.119s |39.988MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_157_163_167.smt2                                |  20.032s |39.852MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_281_283.smt2                                    |  20.035s |39.532MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_239_241.smt2                                    |  20.031s |39.156MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_271_277_281.smt2                                |  20.116s |38.608MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_269_271.smt2                                    |  20.083s |38.48MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_241_251_257.smt2                                |  20.016s |38.468MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_89_97_101.smt2                                  |  20.030s |38.416MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_113_127_131.smt2                                |  20.045s |38.204MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_149_151_157.smt2                                |  20.036s |37.868MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_257_263.smt2                                    |  20.029s |37.44MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_251_257.smt2                                    |  20.105s |37.296MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_139_149.smt2                                    |  20.032s |37.276MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_137_139.smt2                                    |  20.123s |37.156MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_227_229.smt2                                    |  20.044s |37.068MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_73_79_83.smt2                                   |  20.020s |36.664MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_127_131_137.smt2                                |  20.019s |36.564MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_191_193.smt2                                    |  20.107s |36.512MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/LIA/20250213-Frobenius/fcp_241_251.smt2                                    |  20.026s |46.584MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_167_173.smt2                                    |  20.145s |40.908MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_181_191_193.smt2                                |  20.119s |39.988MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_157_163_167.smt2                                |  20.032s |39.852MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_281_283.smt2                                    |  20.035s |39.532MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_239_241.smt2                                    |  20.031s |39.156MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_271_277_281.smt2                                |  20.116s |38.608MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_269_271.smt2                                    |  20.083s |38.48MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_241_251_257.smt2                                |  20.016s |38.468MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_89_97_101.smt2                                  |  20.030s |38.416MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_113_127_131.smt2                                |  20.045s |38.204MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_149_151_157.smt2                                |  20.036s |37.868MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_257_263.smt2                                    |  20.029s |37.44MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_251_257.smt2                                    |  20.105s |37.296MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_139_149.smt2                                    |  20.032s |37.276MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_137_139.smt2                                    |  20.123s |37.156MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_227_229.smt2                                    |  20.044s |37.068MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_73_79_83.smt2                                   |  20.020s |36.664MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_127_131_137.smt2                                |  20.019s |36.564MiB|
|non-incremental/LIA/20250213-Frobenius/fcp_191_193.smt2                                    |  20.107s |36.512MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_1.smt2  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_10.smt2  |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_11.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_12.smt2  |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_13.smt2  |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_14.smt2  |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_3.smt2  |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_4.smt2  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_5.smt2  |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_6.smt2  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_7.smt2  |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_8.smt2  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_9.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_12.smt2  |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_14.smt2  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_15.smt2  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_2.smt2  |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_0.smt2  |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_10.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_2.smt2  |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_3.smt2  |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_4.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_5.smt2  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_6.smt2  |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_7.smt2  |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_8.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_9.smt2  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/s3_srvr_2_true-unreach-call_true-no-overflow_false-termination.BV.c.cil.c_0.smt2  |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_101_103.smt2                                     |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_101_103_107.smt2                                 |  20.111s  |  20.111s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_103_107.smt2                                     |  20.132s  |  20.132s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_103_107_109.smt2                                 |  20.084s  |  20.084s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_107_109.smt2                                     |  20.040s  |  20.040s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_107_109_113.smt2                                 |  20.069s  |  20.069s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_109_113.smt2                                     |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_109_113_127.smt2                                 |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_113_127.smt2                                     |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_113_127_131.smt2                                 |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_11_13.smt2                                       |   0.822s  |   0.822s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_11_13_17.smt2                                    |   2.029s  |   2.029s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_127_131.smt2                                     |  20.112s  |  20.112s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_127_131_137.smt2                                 |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_131_137.smt2                                     |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_131_137_139.smt2                                 |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_137_139.smt2                                     |  20.123s  |  20.123s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_137_139_149.smt2                                 |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_139_149.smt2                                     |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_139_149_151.smt2                                 |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_13_17.smt2                                       |   7.347s  |   7.347s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_13_17_19.smt2                                    |   4.197s  |   4.197s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_149_151.smt2                                     |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_149_151_157.smt2                                 |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_151_157.smt2                                     |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_151_157_163.smt2                                 |  20.149s  |  20.149s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_157_163.smt2                                     |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_157_163_167.smt2                                 |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_163_167.smt2                                     |  20.088s  |  20.088s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_163_167_173.smt2                                 |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_167_173.smt2                                     |  20.145s  |  20.145s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_167_173_179.smt2                                 |  20.119s  |  20.119s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_173_179.smt2                                     |  20.119s  |  20.119s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_173_179_181.smt2                                 |  20.153s  |  20.153s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_179_181.smt2                                     |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_179_181_191.smt2                                 |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_17_19.smt2                                       |  16.650s  |  16.650s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_17_19_23.smt2                                    |   9.003s  |   9.003s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_181_191.smt2                                     |  20.113s  |  20.113s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_181_191_193.smt2                                 |  20.119s  |  20.119s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_191_193.smt2                                     |  20.107s  |  20.107s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_191_193_197.smt2                                 |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_193_197.smt2                                     |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_193_197_199.smt2                                 |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_197_199.smt2                                     |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_197_199_211.smt2                                 |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_199_211.smt2                                     |  20.114s  |  20.114s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_199_211_223.smt2                                 |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_19_23.smt2                                       |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_19_23_29.smt2                                    |  15.845s  |  15.845s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_211_223.smt2                                     |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_211_223_227.smt2                                 |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_223_227.smt2                                     |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_223_227_229.smt2                                 |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_227_229.smt2                                     |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_227_229_233.smt2                                 |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_229_233.smt2                                     |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_229_233_239.smt2                                 |  20.117s  |  20.117s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_233_239.smt2                                     |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_233_239_241.smt2                                 |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_239_241.smt2                                     |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_239_241_251.smt2                                 |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_23_29.smt2                                       |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_23_29_31.smt2                                    |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_241_251.smt2                                     |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_241_251_257.smt2                                 |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_251_257.smt2                                     |  20.105s  |  20.105s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_251_257_263.smt2                                 |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_257_263.smt2                                     |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_257_263_269.smt2                                 |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_263_269.smt2                                     |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_263_269_271.smt2                                 |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_269_271.smt2                                     |  20.083s  |  20.083s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_269_271_277.smt2                                 |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_271_277.smt2                                     |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_271_277_281.smt2                                 |  20.116s  |  20.116s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_277_281.smt2                                     |  20.014s  |  20.014s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_277_281_283.smt2                                 |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_281_283.smt2                                     |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_281_283_293.smt2                                 |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_29_31.smt2                                       |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_29_31_37.smt2                                    |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_2_3.smt2                                         |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_2_3_5.smt2                                       |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_31_37.smt2                                       |  20.120s  |  20.120s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_31_37_41.smt2                                    |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_37_41.smt2                                       |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_37_41_43.smt2                                    |  20.040s  |  20.040s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_3_5.smt2                                         |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_3_5_7.smt2                                       |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_41_43.smt2                                       |  20.075s  |  20.075s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_41_43_47.smt2                                    |  20.149s  |  20.149s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_43_47.smt2                                       |  20.040s  |  20.040s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_43_47_53.smt2                                    |  20.029s  |  20.029s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_47_53.smt2                                       |  20.012s  |  20.012s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_47_53_59.smt2                                    |  20.148s  |  20.148s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_53_59.smt2                                       |  20.013s  |  20.013s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_53_59_61.smt2                                    |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_59_61.smt2                                       |  20.088s  |  20.088s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_59_61_67.smt2                                    |  20.016s  |  20.016s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_5_7.smt2                                         |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_5_7_11.smt2                                      |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_61_67.smt2                                       |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_61_67_71.smt2                                    |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_67_71.smt2                                       |  20.111s  |  20.111s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_67_71_73.smt2                                    |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_71_73.smt2                                       |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_71_73_79.smt2                                    |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_73_79.smt2                                       |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_73_79_83.smt2                                    |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_79_83.smt2                                       |  20.031s  |  20.031s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_79_83_89.smt2                                    |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_7_11.smt2                                        |   0.459s  |   0.459s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_7_11_13.smt2                                     |   0.331s  |   0.331s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_83_89.smt2                                       |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_83_89_97.smt2                                    |  20.112s  |  20.112s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_89_97.smt2                                       |  20.142s  |  20.142s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_89_97_101.smt2                                   |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_97_101.smt2                                      |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/LIA/20250213-Frobenius/fcp_97_101_103.smt2                                  |  20.148s  |  20.148s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/MADWiFi-encode_ie_ok_true-unreach-call.i_17.smt2      |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/MADWiFi-encode_ie_ok_true-unreach-call.i_7.smt2       |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_127.smt2                   |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_1657.smt2                  |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_187.smt2                   |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_2207.smt2                  |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_2317.smt2                  |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_237.smt2                   |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_276.smt2                   |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_297.smt2                   |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_597.smt2                   |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_657.smt2                   |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_670.smt2                   |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_671.smt2                   |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_673.smt2                   |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_678.smt2                   |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_798.smt2                   |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested6_true-unreach-call.i_7.smt2                    |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1070.smt2                 |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1072.smt2                 |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1107.smt2                 |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1117.smt2                 |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1170.smt2                 |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1172.smt2                 |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1307.smt2                 |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1317.smt2                 |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1337.smt2                 |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1357.smt2                 |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1370.smt2                 |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1371.smt2                 |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1375.smt2                 |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1379.smt2                 |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1427.smt2                 |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1437.smt2                 |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1471.smt2                 |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1475.smt2                 |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1477.smt2                 |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1479.smt2                 |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1575.smt2                 |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1578.smt2                 |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1597.smt2                 |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1676.smt2                 |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1677.smt2                 |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1679.smt2                 |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_17.smt2                   |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1703.smt2                 |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1707.smt2                 |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1720.smt2                 |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1722.smt2                 |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1723.smt2                 |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1726.smt2                 |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1728.smt2                 |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1729.smt2                 |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_173.smt2                  |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1732.smt2                 |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1736.smt2                 |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1737.smt2                 |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1738.smt2                 |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1739.smt2                 |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1741.smt2                 |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1748.smt2                 |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1749.smt2                 |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_175.smt2                  |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1752.smt2                 |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1755.smt2                 |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1758.smt2                 |   0.021s  |   0.021s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1761.smt2                 |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1764.smt2                 |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1767.smt2                 |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1770.smt2                 |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1777.smt2                 |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1778.smt2                 |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1781.smt2                 |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1784.smt2                 |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1785.smt2                 |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1786.smt2                 |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1789.smt2                 |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_179.smt2                  |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1792.smt2                 |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1795.smt2                 |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1798.smt2                 |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1817.smt2                 |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1847.smt2                 |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_187.smt2                  |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1874.smt2                 |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1875.smt2                 |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1877.smt2                 |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1878.smt2                 |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1879.smt2                 |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1887.smt2                 |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1897.smt2                 |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_277.smt2                  |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_357.smt2                  |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_378.smt2                  |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_379.smt2                  |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_447.smt2                  |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_470.smt2                  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_473.smt2                  |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_497.smt2                  |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_507.smt2                  |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_527.smt2                  |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_537.smt2                  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_573.smt2                  |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_574.smt2                  |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_575.smt2                  |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_627.smt2                  |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_637.smt2                  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_670.smt2                  |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_7.smt2                    |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_703.smt2                  |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_707.smt2                  |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_71.smt2                   |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_713.smt2                  |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_720.smt2                  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_725.smt2                  |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_728.smt2                  |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_73.smt2                   |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_744.smt2                  |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_746.smt2                  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_751.smt2                  |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_753.smt2                  |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_755.smt2                  |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_762.smt2                  |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_763.smt2                  |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_766.smt2                  |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_775.smt2                  |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_780.smt2                  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_785.smt2                  |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_788.smt2                  |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_807.smt2                  |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_817.smt2                  |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_870.smt2                  |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_887.smt2                  |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_927.smt2                  |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_947.smt2                  |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_1478.smt2  |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_1735.smt2  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_1757.smt2  |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_2147.smt2  |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_2175.smt2  |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_2715.smt2  |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_2746.smt2  |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_278.smt2  |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_287.smt2  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_3227.smt2  |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_367.smt2  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_3872.smt2  |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_557.smt2  |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_597.smt2  |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_73.smt2  |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_847.smt2  |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_874.smt2  |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_876.smt2  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/001.smt2                                                          |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/002.smt2                                                          |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/003.smt2                                                          |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/004.smt2                                                          |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/005.smt2                                                          |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/006.smt2                                                          |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/007.smt2                                                          |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/008.smt2                                                          |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/009.smt2                                                          |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/010.smt2                                                          |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/011.smt2                                                          |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/012.smt2                                                          |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/013.smt2                                                          |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/014.smt2                                                          |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/015.smt2                                                          |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/016.smt2                                                          |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/017.smt2                                                          |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/018.smt2                                                          |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/019.smt2                                                          |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/020.smt2                                                          |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/021.smt2                                                          |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/022.smt2                                                          |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/023.smt2                                                          |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/024.smt2                                                          |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/025.smt2                                                          |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/026.smt2                                                          |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/027.smt2                                                          |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/028.smt2                                                          |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/029.smt2                                                          |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/030.smt2                                                          |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/031.smt2                                                          |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/032.smt2                                                          |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/033.smt2                                                          |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/034.smt2                                                          |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/035.smt2                                                          |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/036.smt2                                                          |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/037.smt2                                                          |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/038.smt2                                                          |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/039.smt2                                                          |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/040.smt2                                                          |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/041.smt2                                                          |   0.283s  |   0.283s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/042.smt2                                                          |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/043.smt2                                                          |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/044.smt2                                                          |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/045.smt2                                                          |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/046.smt2                                                          |   0.267s  |   0.267s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/047.smt2                                                          |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/048.smt2                                                          |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/049.smt2                                                          |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/050.smt2                                                          |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/051.smt2                                                          |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/052.smt2                                                          |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/053.smt2                                                          |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/054.smt2                                                          |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/055.smt2                                                          |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/056.smt2                                                          |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/057.smt2                                                          |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/058.smt2                                                          |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/061.smt2                                                          |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/062.smt2                                                          |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/063.smt2                                                          |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/064.smt2                                                          |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/065.smt2                                                          |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/066.smt2                                                          |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/067.smt2                                                          |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/068.smt2                                                          |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/069.smt2                                                          |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/070.smt2                                                          |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/071.smt2                                                          |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/072.smt2                                                          |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/073.smt2                                                          |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/074.smt2                                                          |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/075.smt2                                                          |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/076.smt2                                                          |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/077.smt2                                                          |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/078.smt2                                                          |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/079.smt2                                                          |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/080.smt2                                                          |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/081.smt2                                                          |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/082.smt2                                                          |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/083.smt2                                                          |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/084.smt2                                                          |   0.262s  |   0.262s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/085.smt2                                                          |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/086.smt2                                                          |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/087.smt2                                                          |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/088.smt2                                                          |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/089.smt2                                                          |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/090.smt2                                                          |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/091.smt2                                                          |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/092.smt2                                                          |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/093.smt2                                                          |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/094.smt2                                                          |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/095.smt2                                                          |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/096.smt2                                                          |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/097.smt2                                                          |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/098.smt2                                                          |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/099.smt2                                                          |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/100.smt2                                                          |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/101.smt2                                                          |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/102.smt2                                                          |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/103.smt2                                                          |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/104.smt2                                                          |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/105.smt2                                                          |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/106.smt2                                                          |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/107.smt2                                                          |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/108.smt2                                                          |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/109.smt2                                                          |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/110.smt2                                                          |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/111.smt2                                                          |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/112.smt2                                                          |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/113.smt2                                                          |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/114.smt2                                                          |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/115.smt2                                                          |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/116.smt2                                                          |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/117.smt2                                                          |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/118.smt2                                                          |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/119.smt2                                                          |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/120.smt2                                                          |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/121.smt2                                                          |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/122.smt2                                                          |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/123.smt2                                                          |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/124.smt2                                                          |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/125.smt2                                                          |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/126.smt2                                                          |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/127.smt2                                                          |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/128.smt2                                                          |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/129.smt2                                                          |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/130.smt2                                                          |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/131.smt2                                                          |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/132.smt2                                                          |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/133.smt2                                                          |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/134.smt2                                                          |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/135.smt2                                                          |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/136.smt2                                                          |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/137.smt2                                                          |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/138.smt2                                                          |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/139.smt2                                                          |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/140.smt2                                                          |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/141.smt2                                                          |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/142.smt2                                                          |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/143.smt2                                                          |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/144.smt2                                                          |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/145.smt2                                                          |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/146.smt2                                                          |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/147.smt2                                                          |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/148.smt2                                                          |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/149.smt2                                                          |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/150.smt2                                                          |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/151.smt2                                                          |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/152.smt2                                                          |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/153.smt2                                                          |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/154.smt2                                                          |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/155.smt2                                                          |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/156.smt2                                                          |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/157.smt2                                                          |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/158.smt2                                                          |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/159.smt2                                                          |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/160.smt2                                                          |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/161.smt2                                                          |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/162.smt2                                                          |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/163.smt2                                                          |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/164.smt2                                                          |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/165.smt2                                                          |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/166.smt2                                                          |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/167.smt2                                                          |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/168.smt2                                                          |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/169.smt2                                                          |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/170.smt2                                                          |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/171.smt2                                                          |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/172.smt2                                                          |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/173.smt2                                                          |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/174.smt2                                                          |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/175.smt2                                                          |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/176.smt2                                                          |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/177.smt2                                                          |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/178.smt2                                                          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/179.smt2                                                          |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/180.smt2                                                          |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/181.smt2                                                          |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/185.smt2                                                          |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/186.smt2                                                          |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/187.smt2                                                          |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/188.smt2                                                          |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/189.smt2                                                          |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/190.smt2                                                          |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/193.smt2                                                          |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/194.smt2                                                          |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/LIA/psyco/195.smt2                                                          |   0.147s  |   0.147s  |   0.000s  | 0.0%|
</details>
