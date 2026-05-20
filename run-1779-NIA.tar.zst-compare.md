Comparing data and data


# SUMMARY
- LHS tests = 248
- RHS tests = 248
- LHS success = 248  (100.0%)
- RHS success = 248  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: NIA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/NIA.tar.zst?download=1
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
Job tag: NIA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/NIA.tar.zst?download=1
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
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_0.smt2  |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_1.smt2  |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_10.smt2  |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_11.smt2  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_12.smt2  |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_13.smt2  |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_14.smt2  |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_15.smt2  |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_16.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_18.smt2  |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_19.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_2.smt2  |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_20.smt2  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_21.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_22.smt2  |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_23.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_24.smt2  |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_25.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_26.smt2  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_27.smt2  |   0.050s  |   0.050s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_0.smt2  |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_1.smt2  |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_10.smt2  |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_11.smt2  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_12.smt2  |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_13.smt2  |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_14.smt2  |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_15.smt2  |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_16.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_18.smt2  |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_19.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_2.smt2  |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_20.smt2  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_21.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_22.smt2  |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_23.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_24.smt2  |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_25.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_26.smt2  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_27.smt2  |   0.050s  |   0.050s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_0.smt2  |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_1.smt2  |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_10.smt2  |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_11.smt2  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_12.smt2  |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_13.smt2  |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_14.smt2  |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_15.smt2  |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_16.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_18.smt2  |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_19.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_2.smt2  |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_20.smt2  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_21.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_22.smt2  |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_23.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_24.smt2  |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_25.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_26.smt2  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_27.smt2  |   0.050s  |   0.050s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_0.smt2  |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_1.smt2  |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_10.smt2  |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_11.smt2  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_12.smt2  |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_13.smt2  |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_14.smt2  |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_15.smt2  |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_16.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_18.smt2  |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_19.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_2.smt2  |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_20.smt2  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_21.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_22.smt2  |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_23.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_24.smt2  |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_25.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_26.smt2  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_27.smt2  |   0.050s  |   0.050s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/gcd_2.c_2.smt2                    |  20.669s |6974.0MiB|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/gcd_2.c_1.smt2                    |  20.549s |4963.0MiB|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/gcd_2.c_0.smt2                    |  20.485s |4802.0MiB|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/modulus-1.c_8.smt2                |  20.478s |4325.0MiB|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/modulus-1.c_1.smt2                |  20.277s |2282.0MiB|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/modulus-1.c_0.smt2                |  20.250s |2244.0MiB|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/modulus-1.c_3.smt2                |  20.203s |1773.0MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_16.smt2 |  20.094s |73.7MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_0.smt2 |  20.092s |36.068MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_1.smt2 |  20.080s |35.1MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_10.smt2 |  20.080s |162.0MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_17.smt2 |  20.079s |88.24MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_12.smt2 |  20.078s |93.32MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_5.smt2 |  20.078s |136.0MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_9.smt2 |  20.077s |121.0MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_7.smt2 |  20.073s |144.0MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_5.smt2 |  20.070s |49.212MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_11.smt2 |  20.063s |31.5MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_8.smt2 |  20.063s |129.0MiB|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/jain_7-2.c_0.smt2                 |  20.063s |122.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/gcd_2.c_2.smt2                    |  20.669s |6974.0MiB|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/gcd_2.c_1.smt2                    |  20.549s |4963.0MiB|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/gcd_2.c_0.smt2                    |  20.485s |4802.0MiB|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/modulus-1.c_8.smt2                |  20.478s |4325.0MiB|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/modulus-1.c_1.smt2                |  20.277s |2282.0MiB|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/modulus-1.c_0.smt2                |  20.250s |2244.0MiB|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/modulus-1.c_3.smt2                |  20.203s |1773.0MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_16.smt2 |  20.094s |73.7MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_0.smt2 |  20.092s |36.068MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_1.smt2 |  20.080s |35.1MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_10.smt2 |  20.080s |162.0MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_17.smt2 |  20.079s |88.24MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_12.smt2 |  20.078s |93.32MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_5.smt2 |  20.078s |136.0MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_9.smt2 |  20.077s |121.0MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_7.smt2 |  20.073s |144.0MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_5.smt2 |  20.070s |49.212MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_11.smt2 |  20.063s |31.5MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_8.smt2 |  20.063s |129.0MiB|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/jain_7-2.c_0.smt2                 |  20.063s |122.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_0.smt2  |21.608MiB|21.608MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_1.smt2  |21.38MiB|21.38MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_10.smt2  |21.104MiB|21.104MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_11.smt2  |20.884MiB|20.884MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_12.smt2  |21.056MiB|21.056MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_13.smt2  |20.852MiB|20.852MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_14.smt2  |20.936MiB|20.936MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_15.smt2  |21.104MiB|21.104MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_16.smt2  |21.236MiB|21.236MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_18.smt2  |21.184MiB|21.184MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_19.smt2  |20.872MiB|20.872MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_2.smt2  |21.16MiB|21.16MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_20.smt2  |21.184MiB|21.184MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_21.smt2  |21.008MiB|21.008MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_22.smt2  |21.156MiB|21.156MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_23.smt2  |21.052MiB|21.052MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_24.smt2  |20.94MiB|20.94MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_25.smt2  |21.08MiB|21.08MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_26.smt2  |20.952MiB|20.952MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_27.smt2  |20.916MiB|20.916MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_0.smt2  |21.608MiB|21.608MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_1.smt2  |21.38MiB|21.38MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_10.smt2  |21.104MiB|21.104MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_11.smt2  |20.884MiB|20.884MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_12.smt2  |21.056MiB|21.056MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_13.smt2  |20.852MiB|20.852MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_14.smt2  |20.936MiB|20.936MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_15.smt2  |21.104MiB|21.104MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_16.smt2  |21.236MiB|21.236MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_18.smt2  |21.184MiB|21.184MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_19.smt2  |20.872MiB|20.872MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_2.smt2  |21.16MiB|21.16MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_20.smt2  |21.184MiB|21.184MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_21.smt2  |21.008MiB|21.008MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_22.smt2  |21.156MiB|21.156MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_23.smt2  |21.052MiB|21.052MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_24.smt2  |20.94MiB|20.94MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_25.smt2  |21.08MiB|21.08MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_26.smt2  |20.952MiB|20.952MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_27.smt2  |20.916MiB|20.916MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_0.smt2  |21.608MiB|21.608MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_1.smt2  |21.38MiB|21.38MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_10.smt2  |21.104MiB|21.104MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_11.smt2  |20.884MiB|20.884MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_12.smt2  |21.056MiB|21.056MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_13.smt2  |20.852MiB|20.852MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_14.smt2  |20.936MiB|20.936MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_15.smt2  |21.104MiB|21.104MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_16.smt2  |21.236MiB|21.236MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_18.smt2  |21.184MiB|21.184MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_19.smt2  |20.872MiB|20.872MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_2.smt2  |21.16MiB|21.16MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_20.smt2  |21.184MiB|21.184MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_21.smt2  |21.008MiB|21.008MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_22.smt2  |21.156MiB|21.156MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_23.smt2  |21.052MiB|21.052MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_24.smt2  |20.94MiB|20.94MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_25.smt2  |21.08MiB|21.08MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_26.smt2  |20.952MiB|20.952MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_27.smt2  |20.916MiB|20.916MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_0.smt2  |21.608MiB|21.608MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_1.smt2  |21.38MiB|21.38MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_10.smt2  |21.104MiB|21.104MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_11.smt2  |20.884MiB|20.884MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_12.smt2  |21.056MiB|21.056MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_13.smt2  |20.852MiB|20.852MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_14.smt2  |20.936MiB|20.936MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_15.smt2  |21.104MiB|21.104MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_16.smt2  |21.236MiB|21.236MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_18.smt2  |21.184MiB|21.184MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_19.smt2  |20.872MiB|20.872MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_2.smt2  |21.16MiB|21.16MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_20.smt2  |21.184MiB|21.184MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_21.smt2  |21.008MiB|21.008MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_22.smt2  |21.156MiB|21.156MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_23.smt2  |21.052MiB|21.052MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_24.smt2  |20.94MiB|20.94MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_25.smt2  |21.08MiB|21.08MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_26.smt2  |20.952MiB|20.952MiB|0B| 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_27.smt2  |20.916MiB|20.916MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/gcd_2.c_2.smt2                    |  20.669s |6974.0MiB|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/gcd_2.c_1.smt2                    |  20.549s |4963.0MiB|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/gcd_2.c_0.smt2                    |  20.485s |4802.0MiB|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/modulus-1.c_8.smt2                |  20.478s |4325.0MiB|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/modulus-1.c_1.smt2                |  20.277s |2282.0MiB|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/modulus-1.c_0.smt2                |  20.250s |2244.0MiB|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/modulus-1.c_3.smt2                |  20.203s |1773.0MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_10.smt2 |  20.080s |162.0MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_7.smt2 |  20.073s |144.0MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_5.smt2 |  20.078s |136.0MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_8.smt2 |  20.063s |129.0MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_11.smt2 |  20.047s |124.0MiB|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/jain_7-2.c_0.smt2                 |  20.063s |122.0MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_9.smt2 |  20.077s |121.0MiB|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/jain_7-2.c_1.smt2                 |  20.036s |117.0MiB|
|non-incremental/NIA/20240413-AutomizerLoopAcceleration/gsv2008.c.i.p+cfa-reducer.c_AllErrorsAtOnce_Iteration2_0.smt2 |  20.026s |109.0MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_12.smt2 |  20.078s |93.32MiB|
|non-incremental/NIA/20240413-AutomizerLoopAcceleration/in-de41.c_AllErrorsAtOnce_Iteration5_0.smt2 |  20.026s |92.436MiB|
|non-incremental/NIA/20240413-AutomizerLoopAcceleration/gsv2008.c.i.v+lhb-reducer.c_AllErrorsAtOnce_Iteration2_0.smt2 |  12.812s |90.664MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_17.smt2 |  20.079s |88.24MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/gcd_2.c_2.smt2                    |  20.669s |6974.0MiB|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/gcd_2.c_1.smt2                    |  20.549s |4963.0MiB|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/gcd_2.c_0.smt2                    |  20.485s |4802.0MiB|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/modulus-1.c_8.smt2                |  20.478s |4325.0MiB|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/modulus-1.c_1.smt2                |  20.277s |2282.0MiB|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/modulus-1.c_0.smt2                |  20.250s |2244.0MiB|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/modulus-1.c_3.smt2                |  20.203s |1773.0MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_10.smt2 |  20.080s |162.0MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_7.smt2 |  20.073s |144.0MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_5.smt2 |  20.078s |136.0MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_8.smt2 |  20.063s |129.0MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_11.smt2 |  20.047s |124.0MiB|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/jain_7-2.c_0.smt2                 |  20.063s |122.0MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_9.smt2 |  20.077s |121.0MiB|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/jain_7-2.c_1.smt2                 |  20.036s |117.0MiB|
|non-incremental/NIA/20240413-AutomizerLoopAcceleration/gsv2008.c.i.p+cfa-reducer.c_AllErrorsAtOnce_Iteration2_0.smt2 |  20.026s |109.0MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_12.smt2 |  20.078s |93.32MiB|
|non-incremental/NIA/20240413-AutomizerLoopAcceleration/in-de41.c_AllErrorsAtOnce_Iteration5_0.smt2 |  20.026s |92.436MiB|
|non-incremental/NIA/20240413-AutomizerLoopAcceleration/gsv2008.c.i.v+lhb-reducer.c_AllErrorsAtOnce_Iteration2_0.smt2 |  12.812s |90.664MiB|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_17.smt2 |  20.079s |88.24MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_0.smt2  |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_1.smt2  |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_10.smt2  |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_11.smt2  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_12.smt2  |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_13.smt2  |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_14.smt2  |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_15.smt2  |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_16.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_18.smt2  |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_19.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_2.smt2  |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_20.smt2  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_21.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_22.smt2  |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_23.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_24.smt2  |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_25.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_26.smt2  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_27.smt2  |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_28.smt2  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_29.smt2  |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_3.smt2  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_30.smt2  |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_31.smt2  |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_32.smt2  |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_33.smt2  |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_34.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_35.smt2  |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_36.smt2  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_37.smt2  |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_38.smt2  |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_39.smt2  |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_4.smt2  |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_40.smt2  |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_41.smt2  |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_42.smt2  |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_43.smt2  |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_44.smt2  |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_45.smt2  |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_46.smt2  |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_48.smt2  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_49.smt2  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_5.smt2  |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_55.smt2  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_58.smt2  |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_59.smt2  |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_6.smt2  |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_60.smt2  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_61.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_62.smt2  |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_63.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_64.smt2  |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_65.smt2  |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_66.smt2  |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_67.smt2  |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_68.smt2  |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_69.smt2  |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_7.smt2  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_70.smt2  |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_71.smt2  |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_72.smt2  |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_73.smt2  |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_74.smt2  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_75.smt2  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_76.smt2  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_77.smt2  |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_78.smt2  |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_79.smt2  |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_8.smt2  |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_80.smt2  |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_81.smt2  |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_82.smt2  |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_83.smt2  |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_84.smt2  |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_85.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_86.smt2  |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_87.smt2  |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_88.smt2  |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_89.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_9.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_90.smt2  |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_91.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_92.smt2  |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_93.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_94.smt2  |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_95.smt2  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_96.smt2  |   0.379s  |   0.379s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_97.smt2  |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem10_label59_true-unreach-call.c_98.smt2  |   0.379s  |   0.379s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_0.smt2  |  20.092s  |  20.092s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_1.smt2  |   3.327s  |   3.327s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_10.smt2  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_11.smt2  |  20.063s  |  20.063s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_12.smt2  |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_13.smt2  |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_14.smt2  |   0.439s  |   0.439s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_15.smt2  |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_16.smt2  |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_17.smt2  |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_18.smt2  |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_2.smt2  |   1.955s  |   1.955s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_3.smt2  |   3.050s  |   3.050s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_4.smt2  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_5.smt2  |  20.070s  |  20.070s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_6.smt2  |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_7.smt2  |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_8.smt2  |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem15_label00_false-unreach-call.c_9.smt2  |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_0.smt2  |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_1.smt2  |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_10.smt2  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_11.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_12.smt2  |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_13.smt2  |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_2.smt2  |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_3.smt2  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_4.smt2  |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_5.smt2  |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_6.smt2  |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_7.smt2  |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_8.smt2  |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem17_label54_false-unreach-call.c_9.smt2  |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_0.smt2  |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_1.smt2  |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_10.smt2  |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_11.smt2  |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_12.smt2  |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_13.smt2  |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_2.smt2  |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_3.smt2  |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_4.smt2  |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_5.smt2  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_6.smt2  |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_7.smt2  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_8.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/Problem18_label34_false-unreach-call.c_9.smt2  |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/byte_add_1_true-unreach-call_true-no-overflow_true-termination.i_0.smt2  |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/byte_add_1_true-unreach-call_true-no-overflow_true-termination.i_1.smt2  |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/byte_add_1_true-unreach-call_true-no-overflow_true-termination.i_2.smt2  |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/byte_add_1_true-unreach-call_true-no-overflow_true-termination.i_3.smt2  |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/gcd_2_true-unreach-call_true-no-overflow.i_0.smt2  |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/gcd_3_true-unreach-call_true-no-overflow.i_0.smt2  |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/gcd_3_true-unreach-call_true-no-overflow.i_1.smt2  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/gcd_3_true-unreach-call_true-no-overflow.i_2.smt2  |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/implicitunsignedconversion_true-unreach-call_true-termination.c_0.smt2  |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_0.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_16.smt2  |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_17.smt2  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_18.smt2  |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_19.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_2.smt2  |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_20.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_21.smt2  |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_22.smt2  |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_23.smt2  |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_24.smt2  |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_25.smt2  |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_0.smt2  |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_1.smt2  |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_10.smt2  |   2.793s  |   2.793s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_11.smt2  |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_13.smt2  |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_16.smt2  |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_17.smt2  |   0.609s  |   0.609s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_18.smt2  |   1.067s  |   1.067s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_3.smt2  |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_4.smt2  |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_5.smt2  |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_6.smt2  |   0.412s  |   0.412s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_7.smt2  |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_8.smt2  |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_9.smt2  |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_1.smt2  |  20.080s  |  20.080s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_11.smt2  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_12.smt2  |  20.078s  |  20.078s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_13.smt2  |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_14.smt2  |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_15.smt2  |   1.801s  |   1.801s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_16.smt2  |  20.094s  |  20.094s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_17.smt2  |  20.079s  |  20.079s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_18.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/pals_lcr-var-start-time.6_true-unreach-call.ufo.UNBOUNDED.pals.c_1.smt2  |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/sum02_false-unreach-call_true-no-overflow.c_0.smt2  |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/sum02_false-unreach-call_true-no-overflow.c_1.smt2  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_0.smt2  |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_1.smt2  |   0.581s  |   0.581s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_10.smt2  |  20.080s  |  20.080s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_11.smt2  |  20.047s  |  20.047s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_2.smt2  |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_3.smt2  |   0.386s  |   0.386s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_4.smt2  |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_5.smt2  |  20.078s  |  20.078s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_6.smt2  |   0.326s  |   0.326s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_7.smt2  |  20.073s  |  20.073s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_8.smt2  |  20.063s  |  20.063s  |   0.000s  | 0.0%|
|non-incremental/NIA/20190429-UltimateAutomizerSvcomp2019/verisec_sendmail__tTflag_arr_one_loop_false-unreach-call_true-termination.i_9.smt2  |  20.077s  |  20.077s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_0.smt2                |  19.190s  |  19.190s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_10.smt2               |   7.312s  |   7.312s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_11.smt2               |   7.664s  |   7.664s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_12.smt2               |   5.940s  |   5.940s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_13.smt2               |   6.197s  |   6.197s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_14.smt2               |   7.323s  |   7.323s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_15.smt2               |   7.554s  |   7.554s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_16.smt2               |   7.335s  |   7.335s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_17.smt2               |   7.527s  |   7.527s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_2.smt2                |   6.028s  |   6.028s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_3.smt2                |   6.209s  |   6.209s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_4.smt2                |   7.361s  |   7.361s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_5.smt2                |   6.166s  |   6.166s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_6.smt2                |   9.560s  |   9.560s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_7.smt2                |   7.741s  |   7.741s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_8.smt2                |   7.442s  |   7.442s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/byte_add-1.c_9.smt2                |   7.487s  |   7.487s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/dijkstra.c_0.smt2                  |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/dijkstra.c_1.smt2                  |  20.056s  |  20.056s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/dijkstra.c_3.smt2                  |   0.651s  |   0.651s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/dijkstra.c_6.smt2                  |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/dijkstra.c_7.smt2                  |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/egcd2-ll.c_0.smt2                  |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/egcd2-ll.c_1.smt2                  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/egcd2-ll.c_2.smt2                  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/gauss_sum.i_0.smt2                 |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/gcd_2.c_0.smt2                     |  20.485s  |  20.485s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/gcd_2.c_1.smt2                     |  20.549s  |  20.549s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/gcd_2.c_2.smt2                     |  20.669s  |  20.669s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/jain_4-2.c_0.smt2                  |   2.276s  |   2.276s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/jain_6-1.c_0.smt2                  |   6.449s  |   6.449s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/jain_6-1.c_2.smt2                  |  13.601s  |  13.601s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/jain_7-2.c_0.smt2                  |  20.063s  |  20.063s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/jain_7-2.c_1.smt2                  |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/jain_7-2.c_2.smt2                  |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/modulus-1.c_0.smt2                 |  20.250s  |  20.250s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/modulus-1.c_1.smt2                 |  20.277s  |  20.277s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/modulus-1.c_3.smt2                 |  20.203s  |  20.203s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/modulus-1.c_8.smt2                 |  20.478s  |  20.478s  |   0.000s  | 0.0%|
|non-incremental/NIA/20230321-UltimateAutomizerSvcomp2023/ps4-ll.c_1.smt2                    |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/NIA/20240413-AutomizerLoopAcceleration/gsv2008.c.i.p+cfa-reducer.c_AllErrorsAtOnce_Iteration2_0.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/NIA/20240413-AutomizerLoopAcceleration/gsv2008.c.i.v+lhb-reducer.c_AllErrorsAtOnce_Iteration2_0.smt2  |  12.812s  |  12.812s  |   0.000s  | 0.0%|
|non-incremental/NIA/20240413-AutomizerLoopAcceleration/in-de41.c_AllErrorsAtOnce_Iteration5_0.smt2  |  20.026s  |  20.026s  |   0.000s  | 0.0%|
|non-incremental/NIA/20240413-AutomizerLoopAcceleration/in-de51.c_AllErrorsAtOnce_Iteration8_0.smt2  |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|non-incremental/NIA/20240413-AutomizerLoopAcceleration/in-de61.c_AllErrorsAtOnce_Iteration6_0.smt2  |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/NIA/20240413-AutomizerLoopAcceleration/in-de62.c_AllErrorsAtOnce_Iteration8_0.smt2  |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/NIA/psyco/059.smt2                                                          |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/NIA/psyco/060.smt2                                                          |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/NIA/psyco/182.smt2                                                          |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/NIA/psyco/183.smt2                                                          |   0.074s  |   0.074s  |   0.000s  | 0.0%|
</details>
