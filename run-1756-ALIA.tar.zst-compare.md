Comparing data and data


# SUMMARY
- LHS tests = 3098
- RHS tests = 3098
- LHS success = 3098  (100.0%)
- RHS success = 3098  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: ALIA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/ALIA.tar.zst?download=1
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
Job tag: ALIA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/ALIA.tar.zst?download=1
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
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_21.smt2      |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_24.smt2      |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_26.smt2      |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_4.smt2       |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_0.smt2      |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_10.smt2     |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_13.smt2     |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_15.smt2     |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_16.smt2     |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_18.smt2     |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_19.smt2     |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_2.smt2      |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_20.smt2     |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_21.smt2     |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_22.smt2     |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_24.smt2     |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_25.smt2     |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_26.smt2     |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_27.smt2     |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_28.smt2     |   0.059s  |   0.059s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_21.smt2      |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_24.smt2      |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_26.smt2      |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_4.smt2       |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_0.smt2      |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_10.smt2     |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_13.smt2     |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_15.smt2     |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_16.smt2     |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_18.smt2     |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_19.smt2     |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_2.smt2      |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_20.smt2     |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_21.smt2     |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_22.smt2     |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_24.smt2     |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_25.smt2     |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_26.smt2     |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_27.smt2     |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_28.smt2     |   0.059s  |   0.059s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_21.smt2      |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_24.smt2      |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_26.smt2      |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_4.smt2       |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_0.smt2      |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_10.smt2     |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_13.smt2     |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_15.smt2     |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_16.smt2     |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_18.smt2     |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_19.smt2     |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_2.smt2      |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_20.smt2     |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_21.smt2     |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_22.smt2     |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_24.smt2     |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_25.smt2     |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_26.smt2     |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_27.smt2     |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_28.smt2     |   0.059s  |   0.059s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_21.smt2      |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_24.smt2      |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_26.smt2      |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_4.smt2       |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_0.smt2      |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_10.smt2     |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_13.smt2     |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_15.smt2     |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_16.smt2     |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_18.smt2     |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_19.smt2     |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_2.smt2      |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_20.smt2     |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_21.smt2     |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_22.smt2     |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_24.smt2     |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_25.smt2     |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_26.smt2     |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_27.smt2     |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_28.smt2     |   0.059s  |   0.059s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree-2.i_0.smt2                  |  20.584s |3699.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_8.smt2          |  20.299s |1115.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_append_unequal.i_11.smt2   |  20.232s |1957.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_append_unequal.i_10.smt2   |  20.215s |1487.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_56.smt2               |  20.195s |1041.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_0.smt2          |  20.179s |1076.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_103.smt2      |  20.159s |68.124MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree-3.i_4.smt2                  |  20.156s |628.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_60.smt2            |  20.144s |85.416MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_2.smt2          |  20.140s |303.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_unequal.i_27.smt2   |  20.140s |482.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_10.smt2         |  20.139s |119.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_5.smt2          |  20.139s |312.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dancing.i_9.smt2                 |  20.136s |41.672MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_61.smt2               |  20.131s |620.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_equal.i_1.smt2      |  20.123s |54.884MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_98.smt2          |  20.122s |127.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_remove_all_reverse.i_6.smt2 |  20.121s |114.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dancing.i_7.smt2                 |  20.120s |68.804MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_31.smt2       |  20.117s |82.044MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree-2.i_0.smt2                  |  20.584s |3699.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_8.smt2          |  20.299s |1115.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_append_unequal.i_11.smt2   |  20.232s |1957.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_append_unequal.i_10.smt2   |  20.215s |1487.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_56.smt2               |  20.195s |1041.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_0.smt2          |  20.179s |1076.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_103.smt2      |  20.159s |68.124MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree-3.i_4.smt2                  |  20.156s |628.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_60.smt2            |  20.144s |85.416MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_2.smt2          |  20.140s |303.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_unequal.i_27.smt2   |  20.140s |482.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_10.smt2         |  20.139s |119.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_5.smt2          |  20.139s |312.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dancing.i_9.smt2                 |  20.136s |41.672MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_61.smt2               |  20.131s |620.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_equal.i_1.smt2      |  20.123s |54.884MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_98.smt2          |  20.122s |127.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_remove_all_reverse.i_6.smt2 |  20.121s |114.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dancing.i_7.smt2                 |  20.120s |68.804MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_31.smt2       |  20.117s |82.044MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_21.smt2      |20.784MiB|20.784MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_24.smt2      |20.872MiB|20.872MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_26.smt2      |21.0MiB|21.0MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_4.smt2       |20.88MiB|20.88MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_0.smt2      |21.068MiB|21.068MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_10.smt2     |20.66MiB|20.66MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_13.smt2     |20.86MiB|20.86MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_15.smt2     |20.852MiB|20.852MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_16.smt2     |20.868MiB|20.868MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_18.smt2     |21.14MiB|21.14MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_19.smt2     |20.94MiB|20.94MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_2.smt2      |20.864MiB|20.864MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_20.smt2     |20.624MiB|20.624MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_21.smt2     |20.64MiB|20.64MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_22.smt2     |20.652MiB|20.652MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_24.smt2     |20.932MiB|20.932MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_25.smt2     |20.816MiB|20.816MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_26.smt2     |20.636MiB|20.636MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_27.smt2     |21.096MiB|21.096MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_28.smt2     |20.912MiB|20.912MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_21.smt2      |20.784MiB|20.784MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_24.smt2      |20.872MiB|20.872MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_26.smt2      |21.0MiB|21.0MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_4.smt2       |20.88MiB|20.88MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_0.smt2      |21.068MiB|21.068MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_10.smt2     |20.66MiB|20.66MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_13.smt2     |20.86MiB|20.86MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_15.smt2     |20.852MiB|20.852MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_16.smt2     |20.868MiB|20.868MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_18.smt2     |21.14MiB|21.14MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_19.smt2     |20.94MiB|20.94MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_2.smt2      |20.864MiB|20.864MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_20.smt2     |20.624MiB|20.624MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_21.smt2     |20.64MiB|20.64MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_22.smt2     |20.652MiB|20.652MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_24.smt2     |20.932MiB|20.932MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_25.smt2     |20.816MiB|20.816MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_26.smt2     |20.636MiB|20.636MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_27.smt2     |21.096MiB|21.096MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_28.smt2     |20.912MiB|20.912MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_21.smt2      |20.784MiB|20.784MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_24.smt2      |20.872MiB|20.872MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_26.smt2      |21.0MiB|21.0MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_4.smt2       |20.88MiB|20.88MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_0.smt2      |21.068MiB|21.068MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_10.smt2     |20.66MiB|20.66MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_13.smt2     |20.86MiB|20.86MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_15.smt2     |20.852MiB|20.852MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_16.smt2     |20.868MiB|20.868MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_18.smt2     |21.14MiB|21.14MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_19.smt2     |20.94MiB|20.94MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_2.smt2      |20.864MiB|20.864MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_20.smt2     |20.624MiB|20.624MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_21.smt2     |20.64MiB|20.64MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_22.smt2     |20.652MiB|20.652MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_24.smt2     |20.932MiB|20.932MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_25.smt2     |20.816MiB|20.816MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_26.smt2     |20.636MiB|20.636MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_27.smt2     |21.096MiB|21.096MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_28.smt2     |20.912MiB|20.912MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_21.smt2      |20.784MiB|20.784MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_24.smt2      |20.872MiB|20.872MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_26.smt2      |21.0MiB|21.0MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_4.smt2       |20.88MiB|20.88MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_0.smt2      |21.068MiB|21.068MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_10.smt2     |20.66MiB|20.66MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_13.smt2     |20.86MiB|20.86MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_15.smt2     |20.852MiB|20.852MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_16.smt2     |20.868MiB|20.868MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_18.smt2     |21.14MiB|21.14MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_19.smt2     |20.94MiB|20.94MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_2.smt2      |20.864MiB|20.864MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_20.smt2     |20.624MiB|20.624MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_21.smt2     |20.64MiB|20.64MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_22.smt2     |20.652MiB|20.652MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_24.smt2     |20.932MiB|20.932MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_25.smt2     |20.816MiB|20.816MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_26.smt2     |20.636MiB|20.636MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_27.smt2     |21.096MiB|21.096MiB|0B| 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_28.smt2     |20.912MiB|20.912MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree-2.i_0.smt2                  |  20.584s |3699.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_append_unequal.i_11.smt2   |  20.232s |1957.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_append_unequal.i_10.smt2   |  20.215s |1487.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_8.smt2          |  20.299s |1115.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_0.smt2          |  20.179s |1076.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_56.smt2               |  20.195s |1041.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree-3.i_4.smt2                  |  20.156s |628.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_61.smt2               |  20.131s |620.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_unequal.i_27.smt2   |  20.140s |482.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_3.smt2          |  20.089s |442.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_1.smt2          |  20.068s |392.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_5.smt2          |  20.139s |312.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_2.smt2          |  20.140s |303.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-optional-1.i_18.smt2         |  20.093s |234.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree-2.i_1.smt2                  |  20.093s |229.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-queue-1.i_5.smt2             |  20.091s |220.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_29.smt2    |  20.107s |217.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_9.smt2          |  20.090s |216.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_equal.i_7.smt2      |  20.032s |179.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-optional-1.i_17.smt2         |  20.052s |157.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree-2.i_0.smt2                  |  20.584s |3699.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_append_unequal.i_11.smt2   |  20.232s |1957.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_append_unequal.i_10.smt2   |  20.215s |1487.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_8.smt2          |  20.299s |1115.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_0.smt2          |  20.179s |1076.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_56.smt2               |  20.195s |1041.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree-3.i_4.smt2                  |  20.156s |628.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_61.smt2               |  20.131s |620.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_unequal.i_27.smt2   |  20.140s |482.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_3.smt2          |  20.089s |442.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_1.smt2          |  20.068s |392.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_5.smt2          |  20.139s |312.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_2.smt2          |  20.140s |303.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-optional-1.i_18.smt2         |  20.093s |234.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree-2.i_1.smt2                  |  20.093s |229.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-queue-1.i_5.smt2             |  20.091s |220.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_29.smt2    |  20.107s |217.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_9.smt2          |  20.090s |216.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_equal.i_7.smt2      |  20.032s |179.0MiB|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-optional-1.i_17.smt2         |  20.052s |157.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_21.smt2      |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_24.smt2      |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_26.smt2      |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/alternating_list-1.i_4.smt2       |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_0.smt2      |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_10.smt2     |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_13.smt2     |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_15.smt2     |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_16.smt2     |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_18.smt2     |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_19.smt2     |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_2.smt2      |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_20.smt2     |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_21.smt2     |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_22.smt2     |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_24.smt2     |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_25.smt2     |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_26.smt2     |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_27.smt2     |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_28.smt2     |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_29.smt2     |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_3.smt2      |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_30.smt2     |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_31.smt2     |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_33.smt2     |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_34.smt2     |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_35.smt2     |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_38.smt2     |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_4.smt2      |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_41.smt2     |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_42.smt2     |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_43.smt2     |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_47.smt2     |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_5.smt2      |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_50.smt2     |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_52.smt2     |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_55.smt2     |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_56.smt2     |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_6.smt2      |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_62.smt2     |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_64.smt2     |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_65.smt2     |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_66.smt2     |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_67.smt2     |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_68.smt2     |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_7.smt2      |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_72.smt2     |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_73.smt2     |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_8.smt2      |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-1.i_9.smt2      |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_0.smt2      |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_1.smt2      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_10.smt2     |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_11.smt2     |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_115.smt2    |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_12.smt2     |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_13.smt2     |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_14.smt2     |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_15.smt2     |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_16.smt2     |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_17.smt2     |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_20.smt2     |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_21.smt2     |  20.075s  |  20.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_213.smt2    |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_214.smt2    |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_23.smt2     |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_24.smt2     |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_25.smt2     |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_26.smt2     |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_27.smt2     |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_28.smt2     |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_29.smt2     |  20.107s  |  20.107s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_30.smt2     |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_34.smt2     |  20.069s  |  20.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_4.smt2      |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_5.smt2      |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_7.smt2      |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_8.smt2      |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_9.smt2      |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_93.smt2     |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_95.smt2     |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/bubble_sort_linux-2.i_97.smt2     |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/calendar.i_3.smt2                 |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/calendar.i_4.smt2                 |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/calendar.i_7.smt2                 |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dancing.i_0.smt2                  |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dancing.i_10.smt2                 |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dancing.i_11.smt2                 |  20.116s  |  20.116s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dancing.i_2.smt2                  |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dancing.i_3.smt2                  |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dancing.i_4.smt2                  |  20.066s  |  20.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dancing.i_5.smt2                  |  20.110s  |  20.110s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dancing.i_6.smt2                  |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dancing.i_7.smt2                  |  20.120s  |  20.120s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dancing.i_8.smt2                  |  20.070s  |  20.070s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dancing.i_9.smt2                  |  20.136s  |  20.136s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-01-2.i_1.smt2                 |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-01-2.i_11.smt2                |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-01-2.i_13.smt2                |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-01-2.i_2.smt2                 |  20.082s  |  20.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-01-2.i_4.smt2                 |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-01-2.i_5.smt2                 |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-01-2.i_6.smt2                 |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-optional-1.i_0.smt2           |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-optional-1.i_1.smt2           |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-optional-1.i_12.smt2          |  20.109s  |  20.109s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-optional-1.i_13.smt2          |  20.089s  |  20.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-optional-1.i_14.smt2          |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-optional-1.i_15.smt2          |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-optional-1.i_16.smt2          |   6.002s  |   6.002s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-optional-1.i_17.smt2          |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-optional-1.i_18.smt2          |  20.093s  |  20.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-optional-1.i_19.smt2          |   9.699s  |   9.699s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-optional-1.i_2.smt2           |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-optional-1.i_3.smt2           |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-optional-1.i_6.smt2           |   5.135s  |   5.135s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-optional-1.i_7.smt2           |   0.360s  |   0.360s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-optional-1.i_8.smt2           |   0.947s  |   0.947s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-optional-1.i_9.smt2           |   0.360s  |   0.360s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-queue-1.i_11.smt2             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-queue-1.i_12.smt2             |  20.079s  |  20.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-queue-1.i_15.smt2             |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-queue-1.i_16.smt2             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-queue-1.i_17.smt2             |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-queue-1.i_18.smt2             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-queue-1.i_19.smt2             |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-queue-1.i_2.smt2              |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-queue-1.i_20.smt2             |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-queue-1.i_3.smt2              |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-queue-1.i_4.smt2              |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-queue-1.i_5.smt2              |  20.091s  |  20.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-queue-1.i_6.smt2              |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-queue-1.i_7.smt2              |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-rb-cnstr_1-1.i_2.smt2         |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-rb-cnstr_1-1.i_3.smt2         |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-rb-cnstr_1-2.i_1.smt2         |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-rb-cnstr_1-2.i_2.smt2         |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-rb-cnstr_1-2.i_4.smt2         |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-rb-cnstr_1-2.i_5.smt2         |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-rb-cnstr_1-2.i_6.smt2         |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-rb-cnstr_1-2.i_7.smt2         |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-rb-cnstr_1-2.i_8.smt2         |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-rb-cnstr_1-2.i_9.smt2         |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-rb-sentinel-1.i_0.smt2        |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-rb-sentinel-1.i_1.smt2        |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-rb-sentinel-1.i_2.smt2        |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-rb-sentinel-1.i_3.smt2        |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-reverse.i_12.smt2             |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-reverse.i_32.smt2             |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-reverse.i_39.smt2             |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-reverse.i_42.smt2             |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-reverse.i_43.smt2             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-reverse.i_44.smt2             |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-reverse.i_48.smt2             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-reverse.i_5.smt2              |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-reverse.i_50.smt2             |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-reverse.i_52.smt2             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-reverse.i_54.smt2             |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-sorted-2.i_1.smt2             |  20.113s  |  20.113s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-token-1.i_10.smt2             |   1.106s  |   1.106s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-token-1.i_11.smt2             |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-token-1.i_12.smt2             |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-token-1.i_13.smt2             |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-token-1.i_14.smt2             |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-token-1.i_15.smt2             |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-token-1.i_16.smt2             |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-token-1.i_17.smt2             |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-token-1.i_18.smt2             |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-token-1.i_19.smt2             |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-token-1.i_20.smt2             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-token-1.i_24.smt2             |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-token-1.i_25.smt2             |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-token-1.i_26.smt2             |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-token-1.i_27.smt2             |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-token-1.i_28.smt2             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-token-1.i_3.smt2              |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-token-1.i_4.smt2              |   0.334s  |   0.334s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-token-1.i_5.smt2              |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-token-1.i_6.smt2              |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-token-1.i_7.smt2              |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-token-1.i_8.smt2              |   0.657s  |   0.657s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll-token-1.i_9.smt2              |   1.290s  |   1.290s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_append_unequal.i_0.smt2     |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_append_unequal.i_10.smt2    |  20.215s  |  20.215s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_append_unequal.i_11.smt2    |  20.232s  |  20.232s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_append_unequal.i_13.smt2    |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_append_unequal.i_14.smt2    |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_append_unequal.i_15.smt2    |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_append_unequal.i_16.smt2    |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_append_unequal.i_17.smt2    |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_append_unequal.i_18.smt2    |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_append_unequal.i_2.smt2     |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_append_unequal.i_20.smt2    |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_append_unequal.i_21.smt2    |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_append_unequal.i_24.smt2    |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_append_unequal.i_25.smt2    |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_append_unequal.i_3.smt2     |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_append_unequal.i_4.smt2     |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_append_unequal.i_5.smt2     |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_append_unequal.i_6.smt2     |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_append_unequal.i_7.smt2     |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_append_unequal.i_8.smt2     |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_append_unequal.i_9.smt2     |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_1.smt2       |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_10.smt2      |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_100.smt2     |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_101.smt2     |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_102.smt2     |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_103.smt2     |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_105.smt2     |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_107.smt2     |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_108.smt2     |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_109.smt2     |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_11.smt2      |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_14.smt2      |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_15.smt2      |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_16.smt2      |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_17.smt2      |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_19.smt2      |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_2.smt2       |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_20.smt2      |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_21.smt2      |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_22.smt2      |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_23.smt2      |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_24.smt2      |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_25.smt2      |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_26.smt2      |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_27.smt2      |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_28.smt2      |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_29.smt2      |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_3.smt2       |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_30.smt2      |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_32.smt2      |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_33.smt2      |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_35.smt2      |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_37.smt2      |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_4.smt2       |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_43.smt2      |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_48.smt2      |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_49.smt2      |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_5.smt2       |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_55.smt2      |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_56.smt2      |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_57.smt2      |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_59.smt2      |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_6.smt2       |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_61.smt2      |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_62.smt2      |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_63.smt2      |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_64.smt2      |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_65.smt2      |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_66.smt2      |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_67.smt2      |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_68.smt2      |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_69.smt2      |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_7.smt2       |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_70.smt2      |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_71.smt2      |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_72.smt2      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_73.smt2      |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_74.smt2      |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_75.smt2      |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_76.smt2      |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_77.smt2      |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_78.smt2      |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_79.smt2      |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_8.smt2       |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_80.smt2      |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_82.smt2      |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_83.smt2      |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_84.smt2      |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_85.smt2      |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_86.smt2      |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_87.smt2      |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_88.smt2      |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_89.smt2      |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_9.smt2       |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_90.smt2      |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_91.smt2      |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_92.smt2      |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_93.smt2      |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_equal.i_97.smt2      |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_unequal.i_10.smt2    |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_unequal.i_12.smt2    |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_unequal.i_14.smt2    |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_unequal.i_2.smt2     |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_unequal.i_26.smt2    |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_unequal.i_3.smt2     |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_unequal.i_31.smt2    |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_unequal.i_32.smt2    |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_unequal.i_34.smt2    |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_unequal.i_35.smt2    |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_unequal.i_36.smt2    |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_unequal.i_4.smt2     |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_unequal.i_40.smt2    |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_unequal.i_41.smt2    |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_unequal.i_5.smt2     |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_unequal.i_50.smt2    |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_unequal.i_56.smt2    |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_unequal.i_59.smt2    |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_unequal.i_6.smt2     |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_unequal.i_60.smt2    |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_insert_unequal.i_61.smt2    |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_prepend_equal.i_0.smt2      |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_prepend_equal.i_1.smt2      |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_prepend_equal.i_11.smt2     |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_prepend_equal.i_12.smt2     |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_prepend_equal.i_13.smt2     |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_prepend_equal.i_14.smt2     |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_prepend_equal.i_2.smt2      |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_prepend_equal.i_3.smt2      |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_prepend_equal.i_4.smt2      |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_prepend_equal.i_5.smt2      |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_prepend_equal.i_6.smt2      |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_prepend_equal.i_7.smt2      |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_prepend_equal.i_9.smt2      |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_prepend_unequal.i_1.smt2    |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_prepend_unequal.i_3.smt2    |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_prepend_unequal.i_6.smt2    |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_prepend_unequal.i_7.smt2    |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_prepend_unequal.i_8.smt2    |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_prepend_unequal.i_9.smt2    |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_remove_all.i_0.smt2         |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_remove_all.i_1.smt2         |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_remove_all.i_10.smt2        |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_remove_all.i_11.smt2        |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_remove_all.i_12.smt2        |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_remove_all.i_13.smt2        |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_remove_all.i_15.smt2        |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_remove_all.i_16.smt2        |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_remove_all.i_17.smt2        |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_remove_all.i_18.smt2        |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_remove_all.i_19.smt2        |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_remove_all.i_2.smt2         |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_remove_all.i_20.smt2        |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_remove_all.i_21.smt2        |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_remove_all.i_22.smt2        |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_remove_all.i_23.smt2        |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_remove_all.i_24.smt2        |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_remove_all.i_3.smt2         |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_remove_all.i_4.smt2         |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_remove_all.i_5.smt2         |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_remove_all.i_6.smt2         |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_remove_all.i_7.smt2         |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_remove_all.i_8.smt2         |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_remove_all.i_9.smt2         |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all.i_0.smt2         |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all.i_1.smt2         |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all.i_10.smt2        |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all.i_11.smt2        |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all.i_12.smt2        |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all.i_2.smt2         |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all.i_20.smt2        |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all.i_21.smt2        |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all.i_22.smt2        |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all.i_24.smt2        |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all.i_30.smt2        |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all.i_32.smt2        |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all.i_33.smt2        |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all.i_40.smt2        |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all.i_7.smt2         |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all.i_9.smt2         |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_0.smt2  |  20.083s  |  20.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_1.smt2  |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_10.smt2  |  20.091s  |  20.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_100.smt2  |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_101.smt2  |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_11.smt2  |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_115.smt2  |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_116.smt2  |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_117.smt2  |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_118.smt2  |  20.108s  |  20.108s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_119.smt2  |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_12.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_120.smt2  |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_121.smt2  |  20.100s  |  20.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_122.smt2  |  20.093s  |  20.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_123.smt2  |  20.084s  |  20.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_124.smt2  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_125.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_126.smt2  |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_127.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_128.smt2  |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_13.smt2  |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_130.smt2  |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_131.smt2  |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_132.smt2  |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_133.smt2  |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_134.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_135.smt2  |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_136.smt2  |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_137.smt2  |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_138.smt2  |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_139.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_14.smt2  |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_140.smt2  |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_141.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_142.smt2  |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_143.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_144.smt2  |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_145.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_146.smt2  |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_147.smt2  |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_148.smt2  |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_15.smt2  |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_150.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_151.smt2  |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_152.smt2  |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_153.smt2  |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_154.smt2  |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_155.smt2  |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_156.smt2  |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_157.smt2  |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_159.smt2  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_16.smt2  |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_160.smt2  |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_161.smt2  |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_163.smt2  |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_164.smt2  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_165.smt2  |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_168.smt2  |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_178.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_18.smt2  |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_186.smt2  |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_187.smt2  |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_188.smt2  |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_189.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_19.smt2  |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_190.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_191.smt2  |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_194.smt2  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_195.smt2  |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_196.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_197.smt2  |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_198.smt2  |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_199.smt2  |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_2.smt2  |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_20.smt2  |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_200.smt2  |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_201.smt2  |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_202.smt2  |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_203.smt2  |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_204.smt2  |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_205.smt2  |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_207.smt2  |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_208.smt2  |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_209.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_21.smt2  |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_210.smt2  |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_211.smt2  |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_212.smt2  |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_213.smt2  |  20.067s  |  20.067s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_214.smt2  |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_215.smt2  |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_216.smt2  |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_217.smt2  |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_218.smt2  |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_219.smt2  |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_220.smt2  |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_221.smt2  |  20.110s  |  20.110s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_222.smt2  |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_223.smt2  |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_224.smt2  |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_225.smt2  |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_226.smt2  |  20.109s  |  20.109s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_227.smt2  |  20.078s  |  20.078s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_228.smt2  |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_23.smt2  |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_24.smt2  |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_25.smt2  |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_26.smt2  |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_27.smt2  |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_28.smt2  |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_29.smt2  |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_3.smt2  |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_30.smt2  |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_32.smt2  |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_33.smt2  |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_34.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_35.smt2  |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_37.smt2  |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_38.smt2  |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_4.smt2  |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_40.smt2  |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_41.smt2  |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_42.smt2  |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_43.smt2  |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_47.smt2  |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_5.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_51.smt2  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_54.smt2  |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_55.smt2  |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_57.smt2  |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_59.smt2  |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_6.smt2  |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_66.smt2  |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_67.smt2  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_7.smt2  |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_73.smt2  |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_8.smt2  |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_82.smt2  |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_83.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_84.smt2  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_85.smt2  |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_9.smt2  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_90.smt2  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2c_update_all_reverse.i_91.smt2  |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_0.smt2       |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_10.smt2      |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_11.smt2      |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_12.smt2      |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_13.smt2      |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_14.smt2      |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_15.smt2      |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_16.smt2      |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_17.smt2      |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_18.smt2      |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_19.smt2      |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_20.smt2      |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_21.smt2      |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_22.smt2      |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_23.smt2      |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_24.smt2      |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_25.smt2      |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_26.smt2      |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_27.smt2      |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_28.smt2      |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_29.smt2      |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_3.smt2       |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_32.smt2      |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_33.smt2      |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_35.smt2      |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_38.smt2      |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_4.smt2       |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_40.smt2      |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_41.smt2      |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_42.smt2      |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_43.smt2      |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_45.smt2      |   2.920s  |   2.920s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_47.smt2      |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_48.smt2      |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_49.smt2      |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_5.smt2       |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_50.smt2      |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_53.smt2      |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_55.smt2      |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_56.smt2      |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_57.smt2      |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_7.smt2       |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_8.smt2       |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_equal.i_9.smt2       |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_0.smt2     |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_1.smt2     |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_11.smt2    |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_12.smt2    |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_13.smt2    |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_14.smt2    |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_15.smt2    |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_17.smt2    |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_18.smt2    |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_19.smt2    |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_2.smt2     |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_20.smt2    |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_21.smt2    |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_22.smt2    |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_26.smt2    |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_29.smt2    |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_3.smt2     |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_30.smt2    |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_32.smt2    |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_39.smt2    |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_4.smt2     |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_42.smt2    |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_43.smt2    |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_47.smt2    |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_48.smt2    |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_49.smt2    |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_5.smt2     |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_51.smt2    |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_53.smt2    |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_54.smt2    |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_6.smt2     |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_63.smt2    |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_64.smt2    |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_65.smt2    |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_66.smt2    |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_67.smt2    |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_68.smt2    |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_69.smt2    |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_7.smt2     |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_71.smt2    |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_73.smt2    |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_74.smt2    |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_75.smt2    |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_76.smt2    |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_77.smt2    |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_78.smt2    |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_79.smt2    |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_8.smt2     |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_80.smt2    |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_append_unequal.i_9.smt2     |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_equal.i_0.smt2       |  20.112s  |  20.112s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_equal.i_1.smt2       |  20.123s  |  20.123s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_equal.i_2.smt2       |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_equal.i_4.smt2       |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_equal.i_5.smt2       |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_equal.i_6.smt2       |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_equal.i_7.smt2       |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_0.smt2     |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_1.smt2     |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_13.smt2    |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_14.smt2    |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_15.smt2    |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_16.smt2    |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_17.smt2    |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_18.smt2    |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_19.smt2    |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_2.smt2     |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_20.smt2    |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_21.smt2    |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_22.smt2    |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_23.smt2    |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_24.smt2    |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_25.smt2    |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_26.smt2    |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_27.smt2    |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_28.smt2    |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_29.smt2    |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_3.smt2     |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_30.smt2    |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_31.smt2    |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_32.smt2    |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_33.smt2    |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_34.smt2    |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_35.smt2    |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_36.smt2    |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_37.smt2    |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_38.smt2    |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_insert_unequal.i_4.smt2     |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_1.smt2    |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_10.smt2   |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_11.smt2   |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_12.smt2   |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_14.smt2   |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_15.smt2   |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_17.smt2   |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_18.smt2   |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_19.smt2   |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_2.smt2    |   0.457s  |   0.457s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_20.smt2   |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_21.smt2   |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_22.smt2   |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_23.smt2   |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_24.smt2   |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_25.smt2   |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_26.smt2   |   7.672s  |   7.672s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_27.smt2   |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_28.smt2   |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_29.smt2   |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_3.smt2    |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_30.smt2   |   0.362s  |   0.362s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_31.smt2   |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_32.smt2   |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_33.smt2   |   0.447s  |   0.447s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_34.smt2   |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_35.smt2   |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_36.smt2   |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_37.smt2   |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_38.smt2   |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_39.smt2   |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_40.smt2   |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_41.smt2   |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_42.smt2   |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_43.smt2   |   2.338s  |   2.338s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_44.smt2   |   1.723s  |   1.723s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_45.smt2   |   1.781s  |   1.781s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_46.smt2   |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_47.smt2   |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_48.smt2   |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_49.smt2   |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_50.smt2   |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_55.smt2   |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_56.smt2   |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_57.smt2   |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_58.smt2   |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_6.smt2    |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_60.smt2   |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_61.smt2   |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_62.smt2   |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_63.smt2   |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_64.smt2   |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_68.smt2   |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_69.smt2   |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_73.smt2   |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_74.smt2   |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_75.smt2   |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_76.smt2   |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_77.smt2   |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_78.smt2   |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_85.smt2   |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_86.smt2   |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_87.smt2   |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_88.smt2   |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_89.smt2   |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_90.smt2   |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_91.smt2   |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_prepend_unequal.i_92.smt2   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_remove_all.i_0.smt2         |  20.103s  |  20.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_remove_all.i_10.smt2        |   0.615s  |   0.615s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_remove_all.i_11.smt2        |   5.526s  |   5.526s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_remove_all.i_12.smt2        |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_remove_all.i_13.smt2        |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_remove_all.i_14.smt2        |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_remove_all.i_15.smt2        |   0.465s  |   0.465s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_remove_all.i_16.smt2        |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_remove_all.i_17.smt2        |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_remove_all.i_2.smt2         |  20.099s  |  20.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_remove_all.i_3.smt2         |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_remove_all.i_5.smt2         |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_remove_all.i_6.smt2         |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_remove_all.i_8.smt2         |   0.492s  |   0.492s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_remove_all.i_9.smt2         |   0.296s  |   0.296s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_remove_all_reverse.i_0.smt2  |   7.071s  |   7.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_remove_all_reverse.i_1.smt2  |   5.745s  |   5.745s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_remove_all_reverse.i_10.smt2  |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_remove_all_reverse.i_11.smt2  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_remove_all_reverse.i_12.smt2  |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_remove_all_reverse.i_2.smt2  |   6.734s  |   6.734s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_remove_all_reverse.i_3.smt2  |   6.597s  |   6.597s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_remove_all_reverse.i_4.smt2  |   7.862s  |   7.862s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_remove_all_reverse.i_5.smt2  |   6.820s  |   6.820s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_remove_all_reverse.i_6.smt2  |  20.121s  |  20.121s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_remove_all_reverse.i_7.smt2  |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_remove_all_reverse.i_8.smt2  |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_remove_all_reverse.i_9.smt2  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_update_all.i_10.smt2        |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_update_all.i_11.smt2        |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_update_all.i_12.smt2        |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_update_all.i_14.smt2        |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_update_all.i_16.smt2        |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_update_all.i_2.smt2         |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_update_all.i_3.smt2         |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_update_all.i_4.smt2         |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_update_all.i_5.smt2         |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_update_all.i_6.smt2         |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_update_all.i_7.smt2         |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_update_all.i_8.smt2         |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll2n_update_all.i_9.smt2         |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_1.smt2  |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_10.smt2  |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_100.smt2  |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_101.smt2  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_102.smt2  |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_103.smt2  |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_104.smt2  |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_105.smt2  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_106.smt2  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_107.smt2  |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_108.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_109.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_110.smt2  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_111.smt2  |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_112.smt2  |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_113.smt2  |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_114.smt2  |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_115.smt2  |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_116.smt2  |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_117.smt2  |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_118.smt2  |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_119.smt2  |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_12.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_120.smt2  |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_121.smt2  |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_122.smt2  |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_123.smt2  |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_124.smt2  |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_125.smt2  |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_126.smt2  |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_127.smt2  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_128.smt2  |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_129.smt2  |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_13.smt2  |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_14.smt2  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_142.smt2  |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_143.smt2  |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_144.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_145.smt2  |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_146.smt2  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_147.smt2  |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_148.smt2  |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_149.smt2  |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_15.smt2  |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_150.smt2  |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_151.smt2  |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_152.smt2  |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_153.smt2  |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_154.smt2  |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_155.smt2  |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_156.smt2  |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_157.smt2  |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_158.smt2  |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_159.smt2  |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_16.smt2  |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_160.smt2  |   0.278s  |   0.278s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_161.smt2  |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_162.smt2  |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_163.smt2  |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_164.smt2  |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_165.smt2  |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_166.smt2  |   0.373s  |   0.373s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_167.smt2  |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_17.smt2  |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_18.smt2  |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_19.smt2  |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_20.smt2  |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_21.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_22.smt2  |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_24.smt2  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_25.smt2  |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_26.smt2  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_29.smt2  |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_3.smt2  |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_30.smt2  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_31.smt2  |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_32.smt2  |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_33.smt2  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_34.smt2  |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_35.smt2  |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_36.smt2  |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_37.smt2  |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_38.smt2  |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_39.smt2  |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_4.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_40.smt2  |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_41.smt2  |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_42.smt2  |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_43.smt2  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_45.smt2  |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_46.smt2  |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_47.smt2  |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_48.smt2  |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_51.smt2  |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_53.smt2  |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_54.smt2  |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_56.smt2  |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_6.smt2  |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_62.smt2  |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_63.smt2  |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_64.smt2  |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_65.smt2  |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_66.smt2  |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_67.smt2  |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_69.smt2  |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_71.smt2  |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_72.smt2  |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_74.smt2  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_75.smt2  |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_76.smt2  |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_77.smt2  |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_78.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_79.smt2  |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_80.smt2  |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_89.smt2  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_9.smt2  |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_90.smt2  |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_91.smt2  |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_92.smt2  |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_93.smt2  |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_94.smt2  |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_95.smt2  |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_98.smt2  |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_circular_traversal-2.i_99.smt2  |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_nullified-1.i_10.smt2         |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_nullified-1.i_2.smt2          |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_nullified-1.i_6.smt2          |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_nullified-1.i_7.smt2          |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_nullified-2.i_12.smt2         |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_nullified-2.i_19.smt2         |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_nullified-2.i_20.smt2         |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_nullified-2.i_5.smt2          |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_nullified-2.i_6.smt2          |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_nullified-2.i_8.smt2          |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-1.i_11.smt2            |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-1.i_16.smt2            |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-1.i_19.smt2            |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-1.i_21.smt2            |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-1.i_23.smt2            |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-1.i_24.smt2            |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-1.i_27.smt2            |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-1.i_28.smt2            |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-1.i_29.smt2            |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-1.i_30.smt2            |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-1.i_31.smt2            |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-1.i_32.smt2            |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-1.i_34.smt2            |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-1.i_35.smt2            |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-1.i_39.smt2            |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-1.i_40.smt2            |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-1.i_48.smt2            |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-1.i_49.smt2            |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-1.i_50.smt2            |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-1.i_51.smt2            |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-1.i_52.smt2            |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-1.i_53.smt2            |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-1.i_54.smt2            |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-1.i_56.smt2            |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-1.i_8.smt2             |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-2.i_11.smt2            |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-2.i_14.smt2            |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-2.i_18.smt2            |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-2.i_23.smt2            |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-2.i_24.smt2            |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-2.i_25.smt2            |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-2.i_26.smt2            |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-2.i_28.smt2            |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-2.i_29.smt2            |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-2.i_30.smt2            |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-2.i_31.smt2            |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-2.i_32.smt2            |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-2.i_33.smt2            |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-2.i_35.smt2            |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-2.i_36.smt2            |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-2.i_37.smt2            |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-2.i_38.smt2            |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-2.i_5.smt2             |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-2.i_6.smt2             |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-2.i_7.smt2             |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/dll_of_dll-2.i_8.smt2             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_0.smt2              |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_1.smt2              |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_10.smt2             |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_100.smt2            |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_101.smt2            |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_11.smt2             |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_12.smt2             |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_129.smt2            |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_13.smt2             |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_130.smt2            |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_131.smt2            |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_132.smt2            |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_133.smt2            |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_134.smt2            |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_135.smt2            |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_136.smt2            |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_137.smt2            |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_138.smt2            |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_139.smt2            |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_14.smt2             |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_140.smt2            |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_141.smt2            |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_142.smt2            |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_146.smt2            |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_149.smt2            |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_150.smt2            |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_155.smt2            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_157.smt2            |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_16.smt2             |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_161.smt2            |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_164.smt2            |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_165.smt2            |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_166.smt2            |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_167.smt2            |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_168.smt2            |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_169.smt2            |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_17.smt2             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_170.smt2            |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_171.smt2            |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_172.smt2            |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_173.smt2            |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_174.smt2            |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_175.smt2            |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_176.smt2            |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_177.smt2            |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_178.smt2            |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_179.smt2            |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_18.smt2             |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_180.smt2            |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_181.smt2            |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_182.smt2            |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_183.smt2            |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_184.smt2            |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_185.smt2            |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_186.smt2            |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_187.smt2            |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_188.smt2            |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_189.smt2            |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_19.smt2             |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_190.smt2            |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_191.smt2            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_192.smt2            |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_193.smt2            |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_194.smt2            |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_195.smt2            |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_196.smt2            |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_197.smt2            |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_198.smt2            |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_199.smt2            |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_2.smt2              |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_20.smt2             |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_200.smt2            |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_201.smt2            |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_202.smt2            |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_203.smt2            |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_204.smt2            |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_205.smt2            |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_206.smt2            |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_207.smt2            |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_208.smt2            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_209.smt2            |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_21.smt2             |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_22.smt2             |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_23.smt2             |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_24.smt2             |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_25.smt2             |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_26.smt2             |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_27.smt2             |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_28.smt2             |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_29.smt2             |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_3.smt2              |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_30.smt2             |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_31.smt2             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_32.smt2             |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_33.smt2             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_34.smt2             |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_35.smt2             |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_36.smt2             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_37.smt2             |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_38.smt2             |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_39.smt2             |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_4.smt2              |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_40.smt2             |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_41.smt2             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_42.smt2             |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_43.smt2             |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_44.smt2             |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_45.smt2             |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_46.smt2             |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_47.smt2             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_48.smt2             |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_49.smt2             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_5.smt2              |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_50.smt2             |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_51.smt2             |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_52.smt2             |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_53.smt2             |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_54.smt2             |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_55.smt2             |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_56.smt2             |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_57.smt2             |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_58.smt2             |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_59.smt2             |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_6.smt2              |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_60.smt2             |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_61.smt2             |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_62.smt2             |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_63.smt2             |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_64.smt2             |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_65.smt2             |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_66.smt2             |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_67.smt2             |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_68.smt2             |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_69.smt2             |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_70.smt2             |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_71.smt2             |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_72.smt2             |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_73.smt2             |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_74.smt2             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_75.smt2             |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_76.smt2             |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_77.smt2             |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_78.smt2             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_79.smt2             |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_80.smt2             |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_81.smt2             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_82.smt2             |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_83.smt2             |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_84.smt2             |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_85.smt2             |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_87.smt2             |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_88.smt2             |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_89.smt2             |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_90.smt2             |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_91.smt2             |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_92.smt2             |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_93.smt2             |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_94.smt2             |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_95.smt2             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_96.smt2             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_97.smt2             |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/ex3_forlist.i_98.smt2             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/hash_fun.i_1.smt2                 |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_0.smt2          |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_1.smt2          |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_100.smt2        |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_101.smt2        |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_102.smt2        |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_103.smt2        |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_104.smt2        |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_105.smt2        |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_106.smt2        |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_107.smt2        |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_108.smt2        |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_109.smt2        |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_110.smt2        |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_111.smt2        |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_112.smt2        |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_113.smt2        |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_114.smt2        |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_115.smt2        |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_117.smt2        |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_118.smt2        |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_12.smt2         |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_120.smt2        |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_123.smt2        |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_124.smt2        |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_125.smt2        |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_126.smt2        |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_127.smt2        |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_129.smt2        |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_130.smt2        |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_131.smt2        |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_132.smt2        |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_133.smt2        |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_135.smt2        |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_136.smt2        |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_137.smt2        |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_138.smt2        |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_139.smt2        |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_140.smt2        |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_143.smt2        |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_144.smt2        |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_145.smt2        |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_147.smt2        |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_148.smt2        |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_149.smt2        |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_15.smt2         |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_150.smt2        |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_151.smt2        |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_152.smt2        |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_153.smt2        |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_154.smt2        |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_156.smt2        |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_157.smt2        |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_158.smt2        |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_159.smt2        |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_16.smt2         |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_160.smt2        |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_161.smt2        |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_162.smt2        |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_163.smt2        |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_164.smt2        |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_165.smt2        |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_166.smt2        |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_167.smt2        |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_168.smt2        |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_169.smt2        |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_17.smt2         |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_170.smt2        |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_171.smt2        |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_172.smt2        |  15.855s  |  15.855s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_173.smt2        |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_174.smt2        |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_175.smt2        |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_176.smt2        |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_177.smt2        |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_178.smt2        |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_179.smt2        |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_18.smt2         |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_180.smt2        |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_181.smt2        |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_182.smt2        |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_183.smt2        |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_184.smt2        |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_185.smt2        |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_186.smt2        |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_187.smt2        |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_188.smt2        |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_19.smt2         |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_190.smt2        |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_191.smt2        |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_192.smt2        |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_193.smt2        |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_194.smt2        |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_195.smt2        |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_196.smt2        |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_197.smt2        |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_198.smt2        |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_199.smt2        |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_2.smt2          |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_20.smt2         |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_200.smt2        |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_201.smt2        |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_202.smt2        |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_203.smt2        |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_204.smt2        |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_205.smt2        |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_206.smt2        |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_207.smt2        |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_208.smt2        |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_209.smt2        |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_21.smt2         |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_210.smt2        |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_211.smt2        |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_213.smt2        |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_214.smt2        |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_216.smt2        |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_218.smt2        |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_22.smt2         |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_223.smt2        |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_226.smt2        |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_23.smt2         |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_24.smt2         |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_26.smt2         |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_27.smt2         |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_28.smt2         |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_29.smt2         |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_3.smt2          |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_30.smt2         |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_32.smt2         |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_33.smt2         |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_34.smt2         |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_35.smt2         |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_36.smt2         |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_38.smt2         |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_39.smt2         |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_4.smt2          |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_41.smt2         |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_42.smt2         |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_43.smt2         |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_44.smt2         |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_45.smt2         |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_46.smt2         |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_47.smt2         |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_48.smt2         |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_5.smt2          |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_50.smt2         |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_51.smt2         |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_52.smt2         |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_53.smt2         |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_54.smt2         |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_55.smt2         |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_56.smt2         |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_58.smt2         |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_59.smt2         |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_6.smt2          |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_60.smt2         |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_61.smt2         |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_62.smt2         |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_63.smt2         |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_64.smt2         |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_65.smt2         |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_66.smt2         |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_67.smt2         |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_68.smt2         |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_69.smt2         |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_7.smt2          |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_70.smt2         |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_71.smt2         |  20.066s  |  20.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_72.smt2         |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_73.smt2         |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_74.smt2         |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_75.smt2         |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_76.smt2         |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_77.smt2         |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_78.smt2         |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_79.smt2         |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_8.smt2          |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_80.smt2         |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_81.smt2         |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_82.smt2         |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_83.smt2         |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_84.smt2         |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_85.smt2         |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_87.smt2         |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_88.smt2         |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_89.smt2         |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_90.smt2         |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_91.smt2         |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_92.smt2         |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_93.smt2         |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_94.smt2         |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_95.smt2         |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_96.smt2         |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_97.smt2         |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_98.smt2         |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-1.i_99.smt2         |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-2.i_133.smt2        |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-2.i_135.smt2        |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/length_test03-2.i_31.smt2         |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-1.i_11.smt2                  |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-1.i_14.smt2                  |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-1.i_16.smt2                  |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-1.i_18.smt2                  |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-1.i_38.smt2                  |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-1.i_42.smt2                  |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-1.i_52.smt2                  |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-1.i_59.smt2                  |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-1.i_61.smt2                  |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-1.i_64.smt2                  |  20.084s  |  20.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-1.i_65.smt2                  |  20.109s  |  20.109s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-1.i_66.smt2                  |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-1.i_67.smt2                  |  20.047s  |  20.047s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-1.i_70.smt2                  |  20.116s  |  20.116s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-1.i_73.smt2                  |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-1.i_75.smt2                  |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-1.i_76.smt2                  |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-1.i_77.smt2                  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-1.i_78.smt2                  |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-1.i_79.smt2                  |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-1.i_80.smt2                  |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-1.i_81.smt2                  |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-1.i_82.smt2                  |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-1.i_83.smt2                  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-1.i_84.smt2                  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-1.i_85.smt2                  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-1.i_86.smt2                  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-1.i_87.smt2                  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-1.i_88.smt2                  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-1.i_89.smt2                  |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-2.i_31.smt2                  |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-2.i_32.smt2                  |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-2.i_33.smt2                  |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-2.i_34.smt2                  |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-2.i_45.smt2                  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-2.i_60.smt2                  |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-2.i_73.smt2                  |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_1.i_21.smt2              |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_1.i_30.smt2              |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_1.i_39.smt2              |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_1.i_42.smt2              |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_1.i_43.smt2              |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_1.i_45.smt2              |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_1.i_46.smt2              |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_1.i_48.smt2              |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_1.i_49.smt2              |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_1.i_50.smt2              |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_1.i_56.smt2              |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_1.i_57.smt2              |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_1.i_58.smt2              |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_1.i_59.smt2              |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_1.i_6.smt2               |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_1.i_60.smt2              |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_1.i_61.smt2              |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_1.i_63.smt2              |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_1.i_66.smt2              |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_1.i_67.smt2              |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_1.i_70.smt2              |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_1.i_71.smt2              |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_100.smt2          |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_103.smt2          |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_104.smt2          |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_105.smt2          |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_106.smt2          |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_107.smt2          |   0.361s  |   0.361s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_108.smt2          |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_110.smt2          |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_111.smt2          |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_112.smt2          |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_113.smt2          |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_114.smt2          |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_115.smt2          |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_116.smt2          |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_117.smt2          |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_118.smt2          |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_119.smt2          |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_120.smt2          |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_13.smt2           |   0.851s  |   0.851s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_16.smt2           |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_22.smt2           |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_23.smt2           |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_24.smt2           |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_25.smt2           |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_28.smt2           |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_3.smt2            |   1.005s  |   1.005s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_37.smt2           |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_38.smt2           |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_4.smt2            |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_40.smt2           |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_43.smt2           |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_44.smt2           |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_53.smt2           |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_57.smt2           |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_58.smt2           |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_59.smt2           |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_60.smt2           |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_66.smt2           |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_67.smt2           |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_68.smt2           |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_69.smt2           |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_70.smt2           |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_71.smt2           |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_72.smt2           |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_74.smt2           |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_75.smt2           |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_76.smt2           |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_77.smt2           |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_79.smt2           |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_80.smt2           |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_81.smt2           |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_82.smt2           |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_83.smt2           |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_84.smt2           |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_86.smt2           |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_87.smt2           |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_88.smt2           |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_91.smt2           |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_92.smt2           |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_94.smt2           |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_96.smt2           |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_98.smt2           |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag.i_99.smt2           |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag_1.i_19.smt2         |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag_1.i_28.smt2         |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag_1.i_32.smt2         |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag_1.i_39.smt2         |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag_1.i_41.smt2         |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag_1.i_42.smt2         |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag_1.i_44.smt2         |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag_1.i_46.smt2         |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag_1.i_48.smt2         |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag_1.i_51.smt2         |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag_1.i_52.smt2         |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag_1.i_57.smt2         |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag_1.i_58.smt2         |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag_1.i_59.smt2         |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag_1.i_60.smt2         |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag_1.i_62.smt2         |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag_1.i_63.smt2         |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag_1.i_65.smt2         |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag_1.i_66.smt2         |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag_1.i_67.smt2         |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag_1.i_68.smt2         |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag_1.i_7.smt2          |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag_1.i_70.smt2         |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag_1.i_72.smt2         |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag_1.i_74.smt2         |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag_1.i_77.smt2         |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag_1.i_80.smt2         |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list-ext_flag_1.i_9.smt2          |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_11.smt2   |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_13.smt2   |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_15.smt2   |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_17.smt2   |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_18.smt2   |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_19.smt2   |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_20.smt2   |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_21.smt2   |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_23.smt2   |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_24.smt2   |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_25.smt2   |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_26.smt2   |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_28.smt2   |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_29.smt2   |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_30.smt2   |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_31.smt2   |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_32.smt2   |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_33.smt2   |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_34.smt2   |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_35.smt2   |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_36.smt2   |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_37.smt2   |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_38.smt2   |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_39.smt2   |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_4.smt2    |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_41.smt2   |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_42.smt2   |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_44.smt2   |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_45.smt2   |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_46.smt2   |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_47.smt2   |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_49.smt2   |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_50.smt2   |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_51.smt2   |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_52.smt2   |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_54.smt2   |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_55.smt2   |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_56.smt2   |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_57.smt2   |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_58.smt2   |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_59.smt2   |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_6.smt2    |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_60.smt2   |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_61.smt2   |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_62.smt2   |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_63.smt2   |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_64.smt2   |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_65.smt2   |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_66.smt2   |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_7.smt2    |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_80.smt2   |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-1.i_81.smt2   |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-2.i_23.smt2   |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-2.i_4.smt2    |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-2.i_45.smt2   |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-2.i_46.smt2   |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-2.i_47.smt2   |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-2.i_48.smt2   |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-2.i_49.smt2   |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-2.i_50.smt2   |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-2.i_53.smt2   |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-2.i_55.smt2   |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-2.i_56.smt2   |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-2.i_57.smt2   |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-2.i_58.smt2   |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-2.i_59.smt2   |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-2.i_60.smt2   |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-2.i_61.smt2   |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-2.i_62.smt2   |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-2.i_63.smt2   |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-2.i_64.smt2   |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-2.i_65.smt2   |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-2.i_67.smt2   |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-2.i_68.smt2   |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-2.i_69.smt2   |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-2.i_7.smt2    |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-2.i_70.smt2   |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-2.i_71.smt2   |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-2.i_72.smt2   |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-2.i_78.smt2   |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_and_tree_cnstr-2.i_83.smt2   |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_flag-2.i_14.smt2             |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_flag-2.i_15.smt2             |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_flag-2.i_16.smt2             |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_flag-2.i_19.smt2             |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_flag-2.i_22.smt2             |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_flag-2.i_29.smt2             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_flag-2.i_31.smt2             |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-1.i_10.smt2           |   1.423s  |   1.423s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-1.i_11.smt2           |   1.574s  |   1.574s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-1.i_12.smt2           |  20.076s  |  20.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-1.i_13.smt2           |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-1.i_14.smt2           |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-1.i_15.smt2           |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-1.i_16.smt2           |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-1.i_18.smt2           |  20.076s  |  20.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-1.i_19.smt2           |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-1.i_2.smt2            |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-1.i_20.smt2           |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-1.i_21.smt2           |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-1.i_22.smt2           |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-1.i_23.smt2           |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-1.i_24.smt2           |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-1.i_25.smt2           |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-1.i_3.smt2            |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-1.i_4.smt2            |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-1.i_5.smt2            |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-1.i_6.smt2            |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-1.i_8.smt2            |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-1.i_9.smt2            |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-2.i_0.smt2            |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-2.i_1.smt2            |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-2.i_12.smt2           |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-2.i_13.smt2           |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-2.i_14.smt2           |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-2.i_16.smt2           |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-2.i_18.smt2           |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-2.i_21.smt2           |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-2.i_22.smt2           |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-2.i_26.smt2           |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-2.i_27.smt2           |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-2.i_29.smt2           |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-2.i_3.smt2            |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-2.i_30.smt2           |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-2.i_31.smt2           |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-2.i_32.smt2           |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-2.i_33.smt2           |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-2.i_35.smt2           |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-2.i_37.smt2           |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-2.i_4.smt2            |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-2.i_5.smt2            |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/list_search-2.i_7.smt2            |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/max05-2.i_3.smt2                  |  20.077s  |  20.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/merge_sort-2.i_0.smt2             |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/merge_sort-2.i_3.smt2             |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/merge_sort-2.i_4.smt2             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/min_max.i_13.smt2                 |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/min_max.i_4.smt2                  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/min_max.i_8.smt2                  |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/min_max.i_9.smt2                  |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/packet_filter.i_0.smt2            |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/packet_filter.i_1.smt2            |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/packet_filter.i_12.smt2           |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/packet_filter.i_13.smt2           |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/packet_filter.i_15.smt2           |   0.320s  |   0.320s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/packet_filter.i_2.smt2            |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/packet_filter.i_3.smt2            |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/prefixsum_iter.c_0.smt2           |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/prefixsum_iter.c_10.smt2          |  20.075s  |  20.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/prefixsum_iter.c_14.smt2          |  20.075s  |  20.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/prefixsum_iter.c_4.smt2           |  20.079s  |  20.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/prefixsum_rec.c_0.smt2            |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/prefixsum_rec.c_1.smt2            |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/prefixsum_rec.c_10.smt2           |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/prefixsum_rec.c_13.smt2           |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/prefixsum_rec.c_14.smt2           |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/prefixsum_rec.c_15.smt2           |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/prefixsum_rec.c_16.smt2           |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/prefixsum_rec.c_17.smt2           |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/prefixsum_rec.c_18.smt2           |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/prefixsum_rec.c_19.smt2           |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/prefixsum_rec.c_2.smt2            |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/prefixsum_rec.c_20.smt2           |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/prefixsum_rec.c_21.smt2           |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/prefixsum_rec.c_22.smt2           |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/prefixsum_rec.c_23.smt2           |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/prefixsum_rec.c_24.smt2           |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/prefixsum_rec.c_3.smt2            |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/prefixsum_rec.c_32.smt2           |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/prefixsum_rec.c_33.smt2           |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/prefixsum_rec.c_4.smt2            |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/prefixsum_rec.c_8.smt2            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/prefixsum_rec.c_9.smt2            |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/process_queue.i_10.smt2           |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/process_queue.i_11.smt2           |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/process_queue.i_12.smt2           |   0.789s  |   0.789s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/process_queue.i_13.smt2           |   0.518s  |   0.518s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/process_queue.i_9.smt2            |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/running_example.i_0.smt2          |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/running_example.i_10.smt2         |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/running_example.i_11.smt2         |  20.076s  |  20.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/running_example.i_13.smt2         |  20.074s  |  20.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/running_example.i_5.smt2          |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/running_example.i_7.smt2          |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/running_example.i_8.smt2          |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_1.smt2              |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_10.smt2             |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_101.smt2            |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_102.smt2            |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_103.smt2            |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_104.smt2            |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_105.smt2            |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_108.smt2            |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_109.smt2            |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_11.smt2             |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_111.smt2            |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_112.smt2            |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_114.smt2            |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_115.smt2            |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_116.smt2            |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_118.smt2            |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_12.smt2             |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_13.smt2             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_14.smt2             |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_15.smt2             |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_16.smt2             |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_17.smt2             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_18.smt2             |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_19.smt2             |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_20.smt2             |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_21.smt2             |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_22.smt2             |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_23.smt2             |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_24.smt2             |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_25.smt2             |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_26.smt2             |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_27.smt2             |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_28.smt2             |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_29.smt2             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_30.smt2             |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_31.smt2             |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_32.smt2             |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_33.smt2             |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_34.smt2             |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_36.smt2             |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_37.smt2             |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_38.smt2             |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_4.smt2              |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_41.smt2             |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_42.smt2             |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_43.smt2             |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_44.smt2             |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_45.smt2             |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_47.smt2             |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_48.smt2             |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_49.smt2             |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_50.smt2             |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_53.smt2             |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_54.smt2             |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_55.smt2             |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_56.smt2             |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_57.smt2             |  20.092s  |  20.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_58.smt2             |  20.106s  |  20.106s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_6.smt2              |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_60.smt2             |  20.144s  |  20.144s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_61.smt2             |  20.063s  |  20.063s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_62.smt2             |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_63.smt2             |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_65.smt2             |  20.079s  |  20.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_66.smt2             |  20.086s  |  20.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_67.smt2             |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_68.smt2             |  20.075s  |  20.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_7.smt2              |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_71.smt2             |  20.080s  |  20.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_72.smt2             |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_75.smt2             |  20.108s  |  20.108s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_76.smt2             |  20.075s  |  20.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_77.smt2             |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_78.smt2             |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_8.smt2              |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_81.smt2             |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_82.smt2             |  20.094s  |  20.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_83.smt2             |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_84.smt2             |  20.103s  |  20.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_85.smt2             |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_86.smt2             |  20.081s  |  20.081s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_87.smt2             |  20.078s  |  20.078s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_88.smt2             |  20.100s  |  20.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_89.smt2             |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_9.smt2              |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_90.smt2             |  20.075s  |  20.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_91.smt2             |  20.103s  |  20.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_92.smt2             |  20.061s  |  20.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_93.smt2             |  20.083s  |  20.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_94.smt2             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_95.smt2             |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_96.smt2             |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/shared_mem1.i_97.smt2             |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_19.smt2                |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_20.smt2                |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_24.smt2                |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_25.smt2                |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_27.smt2                |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_36.smt2                |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_37.smt2                |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_38.smt2                |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_40.smt2                |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_41.smt2                |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_42.smt2                |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_43.smt2                |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_44.smt2                |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_45.smt2                |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_51.smt2                |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_52.smt2                |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_53.smt2                |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_54.smt2                |   2.244s  |   2.244s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_55.smt2                |   0.899s  |   0.899s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_56.smt2                |  20.195s  |  20.195s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_57.smt2                |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_58.smt2                |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_59.smt2                |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_60.smt2                |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_61.smt2                |  20.131s  |  20.131s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_62.smt2                |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-2.i_63.smt2                |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-ext_1.i_10.smt2            |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-ext_1.i_12.smt2            |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-ext_1.i_33.smt2            |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-ext_1.i_34.smt2            |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-ext_1.i_44.smt2            |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-ext_1.i_5.smt2             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-ext_1.i_6.smt2             |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-ext_1.i_7.smt2             |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple-ext_1.i_8.smt2             |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_11.smt2  |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_12.smt2  |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_14.smt2  |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_16.smt2  |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_18.smt2  |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_19.smt2  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_20.smt2  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_22.smt2  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_23.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_25.smt2  |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_27.smt2  |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_29.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_30.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_31.smt2  |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_32.smt2  |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_33.smt2  |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_34.smt2  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_35.smt2  |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_36.smt2  |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_37.smt2  |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_38.smt2  |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_39.smt2  |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_41.smt2  |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_42.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_43.smt2  |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_44.smt2  |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_45.smt2  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_46.smt2  |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_48.smt2  |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_49.smt2  |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_50.smt2  |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_51.smt2  |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_52.smt2  |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_53.smt2  |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_54.smt2  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_55.smt2  |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_56.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_57.smt2  |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_58.smt2  |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_59.smt2  |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_60.smt2  |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_61.smt2  |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_63.smt2  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_64.smt2  |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_65.smt2  |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_73.smt2  |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_75.smt2  |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_and_skiplist_2lvl-2.i_76.smt2  |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_10.smt2   |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_11.smt2   |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_12.smt2   |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_13.smt2   |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_15.smt2   |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_17.smt2   |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_18.smt2   |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_2.smt2    |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_20.smt2   |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_23.smt2   |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_24.smt2   |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_25.smt2   |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_26.smt2   |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_27.smt2   |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_29.smt2   |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_30.smt2   |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_32.smt2   |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_33.smt2   |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_35.smt2   |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_4.smt2    |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_40.smt2   |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_42.smt2   |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_43.smt2   |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_44.smt2   |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_46.smt2   |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_47.smt2   |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_48.smt2   |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_49.smt2   |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_50.smt2   |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_51.smt2   |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_53.smt2   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_54.smt2   |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_55.smt2   |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_56.smt2   |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_57.smt2   |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_58.smt2   |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_59.smt2   |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_60.smt2   |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_61.smt2   |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_62.smt2   |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_63.smt2   |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_64.smt2   |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_65.smt2   |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_66.smt2   |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_67.smt2   |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_68.smt2   |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_69.smt2   |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_70.smt2   |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_71.smt2   |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_72.smt2   |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_73.smt2   |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_75.smt2   |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_76.smt2   |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_77.smt2   |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_78.smt2   |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_built_from_end.i_79.smt2   |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_1.smt2    |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_11.smt2   |  16.493s  |  16.493s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_13.smt2   |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_15.smt2   |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_17.smt2   |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_2.smt2    |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_22.smt2   |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_29.smt2   |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_32.smt2   |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_33.smt2   |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_36.smt2   |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_37.smt2   |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_42.smt2   |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_43.smt2   |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_44.smt2   |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_45.smt2   |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_49.smt2   |  20.087s  |  20.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_52.smt2   |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_53.smt2   |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_55.smt2   |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_59.smt2   |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_61.smt2   |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_62.smt2   |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_63.smt2   |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_64.smt2   |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_65.smt2   |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_7.smt2    |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_70.smt2   |   1.420s  |   1.420s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_72.smt2   |  20.082s  |  20.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_74.smt2   |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_77.smt2   |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_8.smt2    |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_86.smt2   |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_89.smt2   |   0.297s  |   0.297s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/simple_search_value-1.i_91.smt2   |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_1.smt2            |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_100.smt2          |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_101.smt2          |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_102.smt2          |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_103.smt2          |  20.040s  |  20.040s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_104.smt2          |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_105.smt2          |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_106.smt2          |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_107.smt2          |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_108.smt2          |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_17.smt2           |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_18.smt2           |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_19.smt2           |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_22.smt2           |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_25.smt2           |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_26.smt2           |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_28.smt2           |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_31.smt2           |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_34.smt2           |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_35.smt2           |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_36.smt2           |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_37.smt2           |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_4.smt2            |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_41.smt2           |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_42.smt2           |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_43.smt2           |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_44.smt2           |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_45.smt2           |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_46.smt2           |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_47.smt2           |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_48.smt2           |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_49.smt2           |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_50.smt2           |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_51.smt2           |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_52.smt2           |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_53.smt2           |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_54.smt2           |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_55.smt2           |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_56.smt2           |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_57.smt2           |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_58.smt2           |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_59.smt2           |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_60.smt2           |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_61.smt2           |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_62.smt2           |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_63.smt2           |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_64.smt2           |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_65.smt2           |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_66.smt2           |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_67.smt2           |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_68.smt2           |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_69.smt2           |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_70.smt2           |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_71.smt2           |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_73.smt2           |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_74.smt2           |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_75.smt2           |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_76.smt2           |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_77.smt2           |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_78.smt2           |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_79.smt2           |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_80.smt2           |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_81.smt2           |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_82.smt2           |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_83.smt2           |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_85.smt2           |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_87.smt2           |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_88.smt2           |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_89.smt2           |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_91.smt2           |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_92.smt2           |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_93.smt2           |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_94.smt2           |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_95.smt2           |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_96.smt2           |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_97.smt2           |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/skiplist_3lvl.i_98.smt2           |  20.122s  |  20.122s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-buckets-2.i_1.smt2            |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-buckets-2.i_10.smt2           |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-buckets-2.i_11.smt2           |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-buckets-2.i_12.smt2           |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-buckets-2.i_13.smt2           |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-buckets-2.i_14.smt2           |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-buckets-2.i_15.smt2           |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-buckets-2.i_17.smt2           |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-buckets-2.i_19.smt2           |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-buckets-2.i_20.smt2           |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-buckets-2.i_23.smt2           |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-buckets-2.i_25.smt2           |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-buckets-2.i_6.smt2            |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-buckets-2.i_7.smt2            |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-buckets-2.i_8.smt2            |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-circular-1.i_3.smt2           |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-circular-1.i_4.smt2           |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-circular-1.i_6.smt2           |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-circular-1.i_7.smt2           |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_0.smt2           |  20.179s  |  20.179s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_1.smt2           |  20.068s  |  20.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_10.smt2          |  20.139s  |  20.139s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_2.smt2           |  20.140s  |  20.140s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_3.smt2           |  20.089s  |  20.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_5.smt2           |  20.139s  |  20.139s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_6.smt2           |  20.101s  |  20.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_7.smt2           |  20.113s  |  20.113s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_8.smt2           |  20.299s  |  20.299s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-optional-1.i_9.smt2           |  20.090s  |  20.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-reverse_simple.i_4.smt2       |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-simple-white-blue-1.i_2.smt2  |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-simple-white-blue-1.i_3.smt2  |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-1.i_1.smt2             |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-1.i_2.smt2             |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-1.i_7.smt2             |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-1.i_9.smt2             |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_100.smt2           |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_102.smt2           |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_103.smt2           |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_105.smt2           |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_106.smt2           |  20.103s  |  20.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_11.smt2            |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_16.smt2            |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_19.smt2            |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_20.smt2            |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_21.smt2            |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_22.smt2            |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_23.smt2            |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_24.smt2            |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_25.smt2            |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_27.smt2            |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_28.smt2            |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_31.smt2            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_32.smt2            |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_35.smt2            |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_36.smt2            |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_39.smt2            |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_40.smt2            |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_42.smt2            |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_43.smt2            |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_44.smt2            |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_45.smt2            |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_46.smt2            |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_48.smt2            |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_51.smt2            |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_53.smt2            |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_54.smt2            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_55.smt2            |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_57.smt2            |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_58.smt2            |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_6.smt2             |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_60.smt2            |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_61.smt2            |  20.090s  |  20.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_62.smt2            |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_63.smt2            |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_64.smt2            |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_65.smt2            |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_66.smt2            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_67.smt2            |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_68.smt2            |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_69.smt2            |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_7.smt2             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_71.smt2            |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_72.smt2            |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_74.smt2            |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_75.smt2            |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_76.smt2            |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_77.smt2            |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_79.smt2            |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_80.smt2            |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_82.smt2            |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_83.smt2            |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_84.smt2            |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_85.smt2            |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_87.smt2            |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_90.smt2            |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_91.smt2            |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_94.smt2            |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_95.smt2            |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_96.smt2            |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-sorted-2.i_97.smt2            |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-token-2.i_0.smt2              |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-token-2.i_2.smt2              |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-token-2.i_3.smt2              |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-token-2.i_5.smt2              |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-token-2.i_6.smt2              |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll-token-2.i_7.smt2              |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_0.smt2       |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_10.smt2      |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_11.smt2      |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_12.smt2      |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_13.smt2      |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_14.smt2      |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_15.smt2      |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_16.smt2      |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_17.smt2      |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_18.smt2      |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_19.smt2      |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_2.smt2       |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_20.smt2      |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_21.smt2      |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_22.smt2      |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_24.smt2      |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_25.smt2      |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_26.smt2      |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_27.smt2      |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_28.smt2      |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_29.smt2      |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_3.smt2       |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_30.smt2      |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_31.smt2      |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_32.smt2      |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_33.smt2      |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_34.smt2      |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_35.smt2      |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_36.smt2      |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_37.smt2      |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_38.smt2      |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_39.smt2      |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_4.smt2       |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_41.smt2      |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_42.smt2      |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_44.smt2      |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_45.smt2      |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_46.smt2      |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_47.smt2      |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_5.smt2       |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_52.smt2      |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_53.smt2      |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_54.smt2      |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_57.smt2      |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_58.smt2      |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_59.smt2      |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_61.smt2      |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_62.smt2      |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_63.smt2      |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_64.smt2      |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_65.smt2      |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_66.smt2      |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_68.smt2      |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_7.smt2       |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_71.smt2      |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_72.smt2      |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_8.smt2       |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_equal.i_9.smt2       |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_0.smt2     |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_1.smt2     |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_10.smt2    |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_13.smt2    |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_14.smt2    |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_15.smt2    |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_2.smt2     |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_23.smt2    |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_26.smt2    |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_27.smt2    |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_28.smt2    |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_3.smt2     |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_31.smt2    |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_32.smt2    |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_33.smt2    |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_34.smt2    |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_38.smt2    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_39.smt2    |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_4.smt2     |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_40.smt2    |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_44.smt2    |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_45.smt2    |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_46.smt2    |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_47.smt2    |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_48.smt2    |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_5.smt2     |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_50.smt2    |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_51.smt2    |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_52.smt2    |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_53.smt2    |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_54.smt2    |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_55.smt2    |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_56.smt2    |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_57.smt2    |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_58.smt2    |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_59.smt2    |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_60.smt2    |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_61.smt2    |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_63.smt2    |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_64.smt2    |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_65.smt2    |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_66.smt2    |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_67.smt2    |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_68.smt2    |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_69.smt2    |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_7.smt2     |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_70.smt2    |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_73.smt2    |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_74.smt2    |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_75.smt2    |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_76.smt2    |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_77.smt2    |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_78.smt2    |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_79.smt2    |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_8.smt2     |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_80.smt2    |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_81.smt2    |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_82.smt2    |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_83.smt2    |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_85.smt2    |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_86.smt2    |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_87.smt2    |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_88.smt2    |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_89.smt2    |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_9.smt2     |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_insert_unequal.i_90.smt2    |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_0.smt2      |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_1.smt2      |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_10.smt2     |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_12.smt2     |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_13.smt2     |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_14.smt2     |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_15.smt2     |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_16.smt2     |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_17.smt2     |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_18.smt2     |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_19.smt2     |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_2.smt2      |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_20.smt2     |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_21.smt2     |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_22.smt2     |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_23.smt2     |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_24.smt2     |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_25.smt2     |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_26.smt2     |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_28.smt2     |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_29.smt2     |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_3.smt2      |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_30.smt2     |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_31.smt2     |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_32.smt2     |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_33.smt2     |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_34.smt2     |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_35.smt2     |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_36.smt2     |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_37.smt2     |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_38.smt2     |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_39.smt2     |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_4.smt2      |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_45.smt2     |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_46.smt2     |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_5.smt2      |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_6.smt2      |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_equal.i_9.smt2      |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_1.smt2    |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_10.smt2   |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_100.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_101.smt2  |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_102.smt2  |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_103.smt2  |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_11.smt2   |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_12.smt2   |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_13.smt2   |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_14.smt2   |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_16.smt2   |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_17.smt2   |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_19.smt2   |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_2.smt2    |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_20.smt2   |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_21.smt2   |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_22.smt2   |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_23.smt2   |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_24.smt2   |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_26.smt2   |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_27.smt2   |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_28.smt2   |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_29.smt2   |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_31.smt2   |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_32.smt2   |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_33.smt2   |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_34.smt2   |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_35.smt2   |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_37.smt2   |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_38.smt2   |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_39.smt2   |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_4.smt2    |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_40.smt2   |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_41.smt2   |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_42.smt2   |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_43.smt2   |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_44.smt2   |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_45.smt2   |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_46.smt2   |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_47.smt2   |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_48.smt2   |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_49.smt2   |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_5.smt2    |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_50.smt2   |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_51.smt2   |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_52.smt2   |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_53.smt2   |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_54.smt2   |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_55.smt2   |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_56.smt2   |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_57.smt2   |   1.272s  |   1.272s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_58.smt2   |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_59.smt2   |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_6.smt2    |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_60.smt2   |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_61.smt2   |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_62.smt2   |   0.589s  |   0.589s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_63.smt2   |   0.725s  |   0.725s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_65.smt2   |   0.838s  |   0.838s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_66.smt2   |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_67.smt2   |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_68.smt2   |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_69.smt2   |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_7.smt2    |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_70.smt2   |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_71.smt2   |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_72.smt2   |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_74.smt2   |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_75.smt2   |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_77.smt2   |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_78.smt2   |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_79.smt2   |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_8.smt2    |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_80.smt2   |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_81.smt2   |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_82.smt2   |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_83.smt2   |   0.704s  |   0.704s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_84.smt2   |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_86.smt2   |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_87.smt2   |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_88.smt2   |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_90.smt2   |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_91.smt2   |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_92.smt2   |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_93.smt2   |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_94.smt2   |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_95.smt2   |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_96.smt2   |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_97.smt2   |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_98.smt2   |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_prepend_unequal.i_99.smt2   |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_remove_all.i_10.smt2        |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_remove_all.i_17.smt2        |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_remove_all.i_18.smt2        |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_remove_all.i_27.smt2        |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2c_remove_all.i_29.smt2        |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_equal.i_0.smt2       |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_equal.i_11.smt2      |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_equal.i_14.smt2      |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_equal.i_18.smt2      |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_equal.i_19.smt2      |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_equal.i_20.smt2      |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_equal.i_22.smt2      |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_equal.i_23.smt2      |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_equal.i_24.smt2      |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_equal.i_25.smt2      |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_equal.i_26.smt2      |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_equal.i_3.smt2       |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_equal.i_31.smt2      |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_equal.i_34.smt2      |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_equal.i_35.smt2      |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_equal.i_36.smt2      |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_equal.i_37.smt2      |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_equal.i_38.smt2      |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_equal.i_4.smt2       |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_equal.i_40.smt2      |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_equal.i_41.smt2      |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_equal.i_42.smt2      |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_equal.i_44.smt2      |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_equal.i_45.smt2      |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_equal.i_46.smt2      |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_equal.i_5.smt2       |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_equal.i_6.smt2       |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_equal.i_7.smt2       |  16.777s  |  16.777s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_equal.i_8.smt2       |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_unequal.i_0.smt2     |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_unequal.i_1.smt2     |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_unequal.i_10.smt2    |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_unequal.i_11.smt2    |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_unequal.i_12.smt2    |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_unequal.i_13.smt2    |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_unequal.i_14.smt2    |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_unequal.i_16.smt2    |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_unequal.i_17.smt2    |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_unequal.i_18.smt2    |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_unequal.i_21.smt2    |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_unequal.i_22.smt2    |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_unequal.i_23.smt2    |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_unequal.i_24.smt2    |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_unequal.i_25.smt2    |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_unequal.i_26.smt2    |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_unequal.i_27.smt2    |  20.140s  |  20.140s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_unequal.i_3.smt2     |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_unequal.i_5.smt2     |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_unequal.i_7.smt2     |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_unequal.i_8.smt2     |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_append_unequal.i_9.smt2     |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_equal.i_2.smt2       |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_equal.i_4.smt2       |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_0.smt2     |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_1.smt2     |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_10.smt2    |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_11.smt2    |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_12.smt2    |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_13.smt2    |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_14.smt2    |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_15.smt2    |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_16.smt2    |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_17.smt2    |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_19.smt2    |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_2.smt2     |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_21.smt2    |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_22.smt2    |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_26.smt2    |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_28.smt2    |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_29.smt2    |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_3.smt2     |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_30.smt2    |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_31.smt2    |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_32.smt2    |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_34.smt2    |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_35.smt2    |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_36.smt2    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_37.smt2    |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_38.smt2    |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_39.smt2    |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_4.smt2     |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_40.smt2    |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_41.smt2    |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_42.smt2    |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_44.smt2    |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_45.smt2    |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_46.smt2    |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_47.smt2    |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_48.smt2    |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_49.smt2    |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_5.smt2     |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_50.smt2    |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_51.smt2    |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_52.smt2    |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_53.smt2    |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_54.smt2    |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_55.smt2    |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_57.smt2    |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_59.smt2    |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_6.smt2     |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_60.smt2    |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_61.smt2    |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_62.smt2    |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_63.smt2    |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_67.smt2    |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_68.smt2    |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_69.smt2    |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_7.smt2     |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_70.smt2    |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_73.smt2    |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_81.smt2    |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_insert_unequal.i_85.smt2    |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_10.smt2     |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_11.smt2     |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_2.smt2      |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_26.smt2     |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_27.smt2     |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_28.smt2     |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_3.smt2      |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_31.smt2     |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_32.smt2     |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_33.smt2     |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_34.smt2     |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_35.smt2     |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_38.smt2     |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_39.smt2     |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_4.smt2      |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_40.smt2     |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_41.smt2     |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_43.smt2     |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_44.smt2     |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_45.smt2     |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_48.smt2     |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_49.smt2     |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_5.smt2      |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_50.smt2     |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_51.smt2     |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_53.smt2     |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_54.smt2     |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_55.smt2     |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_56.smt2     |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_57.smt2     |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_58.smt2     |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_8.smt2      |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_prepend_equal.i_9.smt2      |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_remove_all.i_14.smt2        |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_remove_all.i_9.smt2         |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_remove_all_reverse.i_0.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_remove_all_reverse.i_1.smt2  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_remove_all_reverse.i_2.smt2  |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all.i_19.smt2        |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all.i_20.smt2        |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all.i_21.smt2        |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all.i_22.smt2        |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all.i_24.smt2        |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all.i_26.smt2        |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all.i_30.smt2        |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all.i_32.smt2        |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all.i_34.smt2        |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all.i_39.smt2        |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all.i_45.smt2        |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all.i_46.smt2        |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all.i_47.smt2        |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all.i_48.smt2        |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all.i_49.smt2        |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all.i_5.smt2         |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all.i_50.smt2        |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all.i_51.smt2        |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all.i_55.smt2        |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all.i_56.smt2        |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all.i_58.smt2        |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all.i_68.smt2        |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all.i_9.smt2         |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all_reverse.i_0.smt2  |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all_reverse.i_11.smt2  |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all_reverse.i_12.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all_reverse.i_13.smt2  |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all_reverse.i_14.smt2  |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all_reverse.i_15.smt2  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all_reverse.i_16.smt2  |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all_reverse.i_18.smt2  |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all_reverse.i_19.smt2  |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all_reverse.i_2.smt2  |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all_reverse.i_21.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all_reverse.i_22.smt2  |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all_reverse.i_23.smt2  |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all_reverse.i_24.smt2  |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all_reverse.i_3.smt2  |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all_reverse.i_35.smt2  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all_reverse.i_38.smt2  |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all_reverse.i_4.smt2  |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all_reverse.i_55.smt2  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all_reverse.i_57.smt2  |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all_reverse.i_58.smt2  |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all_reverse.i_6.smt2  |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all_reverse.i_60.smt2  |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all_reverse.i_69.smt2  |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all_reverse.i_7.smt2  |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all_reverse.i_70.smt2  |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all_reverse.i_72.smt2  |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all_reverse.i_74.smt2  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all_reverse.i_76.smt2  |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll2n_update_all_reverse.i_8.smt2  |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_0.smt2  |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_1.smt2  |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_10.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_11.smt2  |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_12.smt2  |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_13.smt2  |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_14.smt2  |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_16.smt2  |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_17.smt2  |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_18.smt2  |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_19.smt2  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_20.smt2  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_24.smt2  |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_27.smt2  |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_28.smt2  |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_29.smt2  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_30.smt2  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_31.smt2  |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_32.smt2  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_33.smt2  |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_34.smt2  |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_35.smt2  |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_36.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_37.smt2  |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_38.smt2  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_39.smt2  |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_40.smt2  |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_41.smt2  |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_42.smt2  |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_43.smt2  |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_44.smt2  |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_45.smt2  |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_46.smt2  |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_47.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_48.smt2  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_49.smt2  |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_5.smt2  |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_50.smt2  |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_52.smt2  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_54.smt2  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_55.smt2  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_56.smt2  |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_57.smt2  |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_58.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_59.smt2  |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_6.smt2  |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_60.smt2  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_61.smt2  |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_62.smt2  |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_63.smt2  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_64.smt2  |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_65.smt2  |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_66.smt2  |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_67.smt2  |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_68.smt2  |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_69.smt2  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_7.smt2  |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_70.smt2  |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_71.smt2  |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_72.smt2  |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_73.smt2  |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_75.smt2  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_76.smt2  |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_77.smt2  |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-1.i_9.smt2  |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-2.i_0.smt2  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-2.i_1.smt2  |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-2.i_10.smt2  |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-2.i_2.smt2  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-2.i_3.smt2  |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_circular_traversal-2.i_7.smt2  |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_length_check-2.i_0.smt2       |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_of_sll_nondet_append-2.i_0.smt2  |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_16.smt2        |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_17.smt2        |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_2.smt2         |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_29.smt2        |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_3.smt2         |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_30.smt2        |  20.106s  |  20.106s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_31.smt2        |  20.117s  |  20.117s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_33.smt2        |  20.071s  |  20.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_34.smt2        |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_35.smt2        |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_36.smt2        |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_37.smt2        |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_40.smt2        |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_42.smt2        |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_43.smt2        |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_44.smt2        |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_46.smt2        |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_48.smt2        |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_49.smt2        |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_51.smt2        |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_52.smt2        |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_53.smt2        |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_54.smt2        |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_60.smt2        |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_66.smt2        |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_67.smt2        |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_68.smt2        |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_69.smt2        |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_7.smt2         |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_70.smt2        |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_71.smt2        |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_72.smt2        |   7.146s  |   7.146s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_73.smt2        |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_74.smt2        |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_75.smt2        |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_76.smt2        |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_77.smt2        |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_78.smt2        |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_79.smt2        |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_80.smt2        |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_81.smt2        |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_82.smt2        |   1.189s  |   1.189s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_83.smt2        |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_84.smt2        |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_85.smt2        |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_86.smt2        |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_87.smt2        |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-1.i_88.smt2        |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_1.smt2         |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_100.smt2       |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_101.smt2       |  20.083s  |  20.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_102.smt2       |  20.071s  |  20.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_103.smt2       |  20.159s  |  20.159s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_104.smt2       |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_105.smt2       |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_106.smt2       |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_107.smt2       |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_108.smt2       |  20.089s  |  20.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_109.smt2       |  20.077s  |  20.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_110.smt2       |  20.081s  |  20.081s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_111.smt2       |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_112.smt2       |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_113.smt2       |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_114.smt2       |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_115.smt2       |  20.075s  |  20.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_116.smt2       |  20.090s  |  20.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_117.smt2       |  20.089s  |  20.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_119.smt2       |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_12.smt2        |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_120.smt2       |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_121.smt2       |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_122.smt2       |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_123.smt2       |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_124.smt2       |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_125.smt2       |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_126.smt2       |  20.081s  |  20.081s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_127.smt2       |  20.070s  |  20.070s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_128.smt2       |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_129.smt2       |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_13.smt2        |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_130.smt2       |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_131.smt2       |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_135.smt2       |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_136.smt2       |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_14.smt2        |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_15.smt2        |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_16.smt2        |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_22.smt2        |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_23.smt2        |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_24.smt2        |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_25.smt2        |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_27.smt2        |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_28.smt2        |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_32.smt2        |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_33.smt2        |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_34.smt2        |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_36.smt2        |  20.109s  |  20.109s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_41.smt2        |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_42.smt2        |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_47.smt2        |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_48.smt2        |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_49.smt2        |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_5.smt2         |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_50.smt2        |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_51.smt2        |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_52.smt2        |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_53.smt2        |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_54.smt2        |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_58.smt2        |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_68.smt2        |  20.086s  |  20.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_69.smt2        |  20.077s  |  20.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_71.smt2        |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_72.smt2        |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_76.smt2        |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_80.smt2        |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_81.smt2        |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_82.smt2        |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_83.smt2        |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_84.smt2        |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_85.smt2        |  20.066s  |  20.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_86.smt2        |  20.102s  |  20.102s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_87.smt2        |  20.018s  |  20.018s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_88.smt2        |  20.078s  |  20.078s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_89.smt2        |  20.075s  |  20.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_90.smt2        |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_91.smt2        |  20.068s  |  20.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_92.smt2        |  20.096s  |  20.096s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_93.smt2        |  20.081s  |  20.081s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_94.smt2        |  20.083s  |  20.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_95.smt2        |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_96.smt2        |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_97.smt2        |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_98.smt2        |  20.077s  |  20.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sll_to_dll_rev-2.i_99.smt2        |  20.073s  |  20.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_100.smt2               |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_101.smt2               |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_102.smt2               |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_103.smt2               |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_104.smt2               |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_105.smt2               |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_106.smt2               |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_107.smt2               |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_108.smt2               |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_112.smt2               |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_114.smt2               |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_116.smt2               |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_121.smt2               |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_122.smt2               |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_123.smt2               |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_124.smt2               |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_125.smt2               |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_126.smt2               |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_127.smt2               |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_128.smt2               |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_19.smt2                |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_27.smt2                |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_35.smt2                |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_47.smt2                |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_49.smt2                |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_50.smt2                |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_51.smt2                |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_52.smt2                |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_53.smt2                |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_54.smt2                |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_55.smt2                |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_56.smt2                |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_57.smt2                |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_58.smt2                |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_59.smt2                |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_60.smt2                |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_61.smt2                |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_62.smt2                |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_63.smt2                |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_64.smt2                |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_65.smt2                |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_66.smt2                |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_68.smt2                |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_69.smt2                |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_71.smt2                |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_74.smt2                |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_75.smt2                |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_93.smt2                |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_94.smt2                |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_95.smt2                |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_96.smt2                |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_97.smt2                |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_98.smt2                |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/splice-2.i_99.smt2                |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/split_list_test05-2.i_0.smt2      |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/split_list_test05-2.i_1.smt2      |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/split_list_test05-2.i_10.smt2     |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/split_list_test05-2.i_12.smt2     |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/split_list_test05-2.i_16.smt2     |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/split_list_test05-2.i_2.smt2      |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/split_list_test05-2.i_3.smt2      |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/split_list_test05-2.i_8.smt2      |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/sum_array-2-2.i_3.smt2            |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_0.smt2              |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_1.smt2              |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_11.smt2             |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_12.smt2             |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_13.smt2             |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_14.smt2             |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_18.smt2             |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_25.smt2             |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_26.smt2             |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_29.smt2             |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_31.smt2             |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_32.smt2             |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_34.smt2             |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_40.smt2             |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_49.smt2             |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test-0234-1.i_6.smt2              |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test-0237.i_13.smt2               |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test-0237.i_5.smt2                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_10.smt2              |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_100.smt2             |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_101.smt2             |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_102.smt2             |  20.094s  |  20.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_103.smt2             |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_104.smt2             |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_105.smt2             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_106.smt2             |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_107.smt2             |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_108.smt2             |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_109.smt2             |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_11.smt2              |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_110.smt2             |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_12.smt2              |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_13.smt2              |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_14.smt2              |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_15.smt2              |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_16.smt2              |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_17.smt2              |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_19.smt2              |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_2.smt2               |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_20.smt2              |  20.107s  |  20.107s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_21.smt2              |  20.077s  |  20.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_22.smt2              |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_23.smt2              |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_24.smt2              |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_25.smt2              |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_26.smt2              |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_27.smt2              |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_28.smt2              |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_29.smt2              |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_31.smt2              |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_33.smt2              |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_34.smt2              |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_35.smt2              |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_36.smt2              |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_37.smt2              |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_39.smt2              |  20.077s  |  20.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_40.smt2              |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_41.smt2              |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_42.smt2              |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_43.smt2              |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_44.smt2              |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_45.smt2              |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_46.smt2              |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_47.smt2              |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_48.smt2              |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_49.smt2              |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_50.smt2              |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_51.smt2              |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_52.smt2              |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_53.smt2              |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_54.smt2              |  20.076s  |  20.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_55.smt2              |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_56.smt2              |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_57.smt2              |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_58.smt2              |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_72.smt2              |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_73.smt2              |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_74.smt2              |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_75.smt2              |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_76.smt2              |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_77.smt2              |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_78.smt2              |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_79.smt2              |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_8.smt2               |  20.095s  |  20.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_80.smt2              |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_82.smt2              |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_83.smt2              |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_84.smt2              |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_85.smt2              |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_86.smt2              |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_87.smt2              |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_88.smt2              |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_89.smt2              |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_9.smt2               |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_90.smt2              |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_91.smt2              |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_92.smt2              |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_93.smt2              |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_94.smt2              |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_95.smt2              |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_96.smt2              |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_97.smt2              |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_98.smt2              |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_add-2.i_99.smt2              |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_double_unlock.i_1.smt2  |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_double_unlock.i_11.smt2  |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_double_unlock.i_15.smt2  |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_double_unlock.i_19.smt2  |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_double_unlock.i_2.smt2  |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_double_unlock.i_20.smt2  |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_double_unlock.i_21.smt2  |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_double_unlock.i_22.smt2  |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_double_unlock.i_23.smt2  |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_double_unlock.i_24.smt2  |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_double_unlock.i_25.smt2  |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_double_unlock.i_26.smt2  |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_double_unlock.i_27.smt2  |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_double_unlock.i_28.smt2  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_double_unlock.i_29.smt2  |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_double_unlock.i_3.smt2  |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_double_unlock.i_30.smt2  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_double_unlock.i_31.smt2  |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_double_unlock.i_32.smt2  |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_double_unlock.i_33.smt2  |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_double_unlock.i_34.smt2  |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_double_unlock.i_35.smt2  |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_double_unlock.i_36.smt2  |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_double_unlock.i_37.smt2  |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_double_unlock.i_38.smt2  |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_double_unlock.i_39.smt2  |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_double_unlock.i_4.smt2  |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_double_unlock.i_40.smt2  |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_double_unlock.i_41.smt2  |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_double_unlock.i_42.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unbounded-1.i_0.smt2   |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unbounded-1.i_2.smt2   |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_0.smt2  |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_1.smt2  |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_10.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_11.smt2  |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_12.smt2  |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_13.smt2  |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_15.smt2  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_16.smt2  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_17.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_18.smt2  |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_2.smt2  |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_20.smt2  |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_21.smt2  |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_22.smt2  |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_23.smt2  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_24.smt2  |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_25.smt2  |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_26.smt2  |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_27.smt2  |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_28.smt2  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_3.smt2  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_30.smt2  |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_31.smt2  |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_33.smt2  |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_34.smt2  |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_35.smt2  |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_37.smt2  |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_38.smt2  |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_4.smt2  |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_40.smt2  |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_41.smt2  |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_43.smt2  |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_44.smt2  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_5.smt2  |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_6.smt2  |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_7.smt2  |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_8.smt2  |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/test_mutex_unlock_at_exit.i_9.smt2  |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree-2.i_0.smt2                   |  20.584s  |  20.584s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree-2.i_1.smt2                   |  20.093s  |  20.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree-3.i_0.smt2                   |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree-3.i_1.smt2                   |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree-3.i_2.smt2                   |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree-3.i_3.smt2                   |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree-3.i_4.smt2                   |  20.156s  |  20.156s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree-3.i_5.smt2                   |  20.104s  |  20.104s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_cnstr.i_0.smt2               |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_cnstr.i_1.smt2               |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_cnstr.i_10.smt2              |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_cnstr.i_11.smt2              |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_cnstr.i_12.smt2              |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_cnstr.i_15.smt2              |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_cnstr.i_2.smt2               |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_cnstr.i_23.smt2              |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_cnstr.i_43.smt2              |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_cnstr.i_5.smt2               |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_cnstr.i_7.smt2               |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_max.c_1.smt2                 |  20.061s  |  20.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_max.c_2.smt2                 |  20.076s  |  20.076s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_max.c_3.smt2                 |  20.094s  |  20.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_0.smt2            |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_11.smt2           |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_12.smt2           |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_16.smt2           |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_18.smt2           |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_2.smt2            |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_22.smt2           |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_23.smt2           |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_24.smt2           |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_25.smt2           |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_26.smt2           |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_27.smt2           |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_28.smt2           |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_29.smt2           |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_3.smt2            |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_30.smt2           |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_31.smt2           |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_33.smt2           |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_34.smt2           |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_35.smt2           |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_37.smt2           |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_38.smt2           |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_39.smt2           |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_40.smt2           |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_41.smt2           |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_42.smt2           |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_43.smt2           |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_44.smt2           |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_45.smt2           |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_46.smt2           |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_47.smt2           |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_48.smt2           |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_6.smt2            |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_7.smt2            |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_8.smt2            |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_of_cslls.i_9.smt2            |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_parent_ptr.i_0.smt2          |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_parent_ptr.i_1.smt2          |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_parent_ptr.i_2.smt2          |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_parent_ptr.i_3.smt2          |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_parent_ptr.i_4.smt2          |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_parent_ptr.i_5.smt2          |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_parent_ptr.i_6.smt2          |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_stack.i_0.smt2               |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_stack.i_1.smt2               |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_stack.i_2.smt2               |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_stack.i_21.smt2              |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_stack.i_23.smt2              |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_stack.i_3.smt2               |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_stack.i_4.smt2               |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_stack.i_40.smt2              |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/tree_stack.i_5.smt2               |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/ALIA/20230321-UltimateAutomizerSvcomp2023/vogal-2.i_0.smt2                  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_030ee9.smt2                                                  |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_098a89.smt2                                                  |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_0df790.smt2                                                  |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_0f7c6a.smt2                                                  |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_13de35.smt2                                                  |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_14672f.smt2                                                  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_2186b5.smt2                                                  |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_2551d7.smt2                                                  |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_3240b6.smt2                                                  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_3937a0.smt2                                                  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_5581bd.smt2                                                  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_577945.smt2                                                  |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_5cee0c.smt2                                                  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_600bf6.smt2                                                  |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_647bf6.smt2                                                  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_675f8a.smt2                                                  |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_67ff5c.smt2                                                  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_6c37d0.smt2                                                  |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_7f6962.smt2                                                  |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_849b63.smt2                                                  |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_8894c1.smt2                                                  |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_8a5f8d.smt2                                                  |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_8bed95.smt2                                                  |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_982830.sat.smt2                                              |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_982830.smt2                                                  |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_a04477.smt2                                                  |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_ac01b1.smt2                                                  |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_b124d6.smt2                                                  |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_b5f37c.smt2                                                  |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_bd0142.smt2                                                  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_bf055f.smt2                                                  |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_c0b5f5.smt2                                                  |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_c5a79f.smt2                                                  |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_c7166c.smt2                                                  |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_cdaaac.smt2                                                  |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_cfcef5.smt2                                                  |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_d91441.smt2                                                  |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_d9dcdb.smt2                                                  |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_dab5a0.smt2                                                  |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_deabd0.smt2                                                  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/ALIA/piVC/piVC_f8964d.smt2                                                  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
</details>
