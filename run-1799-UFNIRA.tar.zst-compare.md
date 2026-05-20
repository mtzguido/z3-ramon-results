Comparing data and data


# SUMMARY
- LHS tests = 266
- RHS tests = 266
- LHS success = 266  (100.0%)
- RHS success = 266  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: UFNIRA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/UFNIRA.tar.zst?download=1
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
Job tag: UFNIRA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/UFNIRA.tar.zst?download=1
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
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C10_sol1.smt2                       |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C11_sol1.smt2                       |  21.616s  |  21.616s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C12_sol1.smt2                       |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C13_sol1.smt2                       |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C1_sol1.smt2                        |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C2_sol1.smt2                        |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C3_sol1.smt2                        |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C4_sol1.smt2                        |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C5_sol1.smt2                        |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C6_sol1.smt2                        |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C7_sol1.smt2                        |  20.087s  |  20.087s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C8_sol1.smt2                        |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C9_sol1.smt2                        |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C9a_sol1.smt2                       |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U10_sol1.smt2                       |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U11_sol1.smt2                       |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U12_sol1.smt2                       |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U13_sol1.smt2                       |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U14_sol1.smt2                       |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U15_sol1.smt2                       |  20.116s  |  20.116s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C10_sol1.smt2                       |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C11_sol1.smt2                       |  21.616s  |  21.616s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C12_sol1.smt2                       |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C13_sol1.smt2                       |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C1_sol1.smt2                        |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C2_sol1.smt2                        |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C3_sol1.smt2                        |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C4_sol1.smt2                        |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C5_sol1.smt2                        |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C6_sol1.smt2                        |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C7_sol1.smt2                        |  20.087s  |  20.087s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C8_sol1.smt2                        |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C9_sol1.smt2                        |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C9a_sol1.smt2                       |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U10_sol1.smt2                       |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U11_sol1.smt2                       |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U12_sol1.smt2                       |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U13_sol1.smt2                       |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U14_sol1.smt2                       |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U15_sol1.smt2                       |  20.116s  |  20.116s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C10_sol1.smt2                       |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C11_sol1.smt2                       |  21.616s  |  21.616s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C12_sol1.smt2                       |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C13_sol1.smt2                       |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C1_sol1.smt2                        |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C2_sol1.smt2                        |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C3_sol1.smt2                        |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C4_sol1.smt2                        |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C5_sol1.smt2                        |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C6_sol1.smt2                        |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C7_sol1.smt2                        |  20.087s  |  20.087s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C8_sol1.smt2                        |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C9_sol1.smt2                        |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C9a_sol1.smt2                       |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U10_sol1.smt2                       |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U11_sol1.smt2                       |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U12_sol1.smt2                       |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U13_sol1.smt2                       |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U14_sol1.smt2                       |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U15_sol1.smt2                       |  20.116s  |  20.116s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C10_sol1.smt2                       |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C11_sol1.smt2                       |  21.616s  |  21.616s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C12_sol1.smt2                       |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C13_sol1.smt2                       |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C1_sol1.smt2                        |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C2_sol1.smt2                        |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C3_sol1.smt2                        |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C4_sol1.smt2                        |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C5_sol1.smt2                        |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C6_sol1.smt2                        |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C7_sol1.smt2                        |  20.087s  |  20.087s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C8_sol1.smt2                        |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C9_sol1.smt2                        |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C9a_sol1.smt2                       |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U10_sol1.smt2                       |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U11_sol1.smt2                       |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U12_sol1.smt2                       |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U13_sol1.smt2                       |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U14_sol1.smt2                       |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U15_sol1.smt2                       |  20.116s  |  20.116s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U42.smt2                            |  22.205s |4781.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U5.smt2                             |  22.125s |4750.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U13.smt2                            |  22.119s |4438.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U24.smt2                            |  22.063s |4013.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U64.smt2                            |  21.971s |3768.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U43_sol1.smt2                      |  21.953s |4849.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U2.smt2                             |  21.891s |4308.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U89.smt2                           |  21.839s |7370.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U15_sol2.smt2                      |  21.835s |3523.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C1.smt2                            |  21.825s |7344.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U25.smt2                            |  21.748s |4260.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U64.smt2                           |  21.742s |4530.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U82.smt2                           |  21.718s |3899.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U49.smt2                            |  21.718s |4072.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U8.smt2                             |  21.707s |3127.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U2.smt2                            |  21.682s |4478.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U65.smt2                           |  21.674s |3707.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U40.smt2                            |  21.674s |4024.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U20.smt2                           |  21.660s |2927.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U29_sol1.smt2                      |  21.658s |4575.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U42.smt2                            |  22.205s |4781.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U5.smt2                             |  22.125s |4750.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U13.smt2                            |  22.119s |4438.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U24.smt2                            |  22.063s |4013.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U64.smt2                            |  21.971s |3768.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U43_sol1.smt2                      |  21.953s |4849.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U2.smt2                             |  21.891s |4308.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U89.smt2                           |  21.839s |7370.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U15_sol2.smt2                      |  21.835s |3523.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C1.smt2                            |  21.825s |7344.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U25.smt2                            |  21.748s |4260.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U64.smt2                           |  21.742s |4530.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U82.smt2                           |  21.718s |3899.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U49.smt2                            |  21.718s |4072.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U8.smt2                             |  21.707s |3127.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U2.smt2                            |  21.682s |4478.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U65.smt2                           |  21.674s |3707.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U40.smt2                            |  21.674s |4024.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U20.smt2                           |  21.660s |2927.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U29_sol1.smt2                      |  21.658s |4575.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C10_sol1.smt2                       |20.112MiB|20.112MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C11_sol1.smt2                       |2971.0MiB|2971.0MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C12_sol1.smt2                       |20.148MiB|20.148MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C13_sol1.smt2                       |20.424MiB|20.424MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C1_sol1.smt2                        |20.352MiB|20.352MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C2_sol1.smt2                        |20.104MiB|20.104MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C3_sol1.smt2                        |20.108MiB|20.108MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C4_sol1.smt2                        |20.036MiB|20.036MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C5_sol1.smt2                        |20.62MiB|20.62MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C6_sol1.smt2                        |20.14MiB|20.14MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C7_sol1.smt2                        |32.9MiB|32.9MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C8_sol1.smt2                        |40.132MiB|40.132MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C9_sol1.smt2                        |20.648MiB|20.648MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C9a_sol1.smt2                       |20.092MiB|20.092MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U10_sol1.smt2                       |20.108MiB|20.108MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U11_sol1.smt2                       |20.832MiB|20.832MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U12_sol1.smt2                       |20.656MiB|20.656MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U13_sol1.smt2                       |20.268MiB|20.268MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U14_sol1.smt2                       |20.62MiB|20.62MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U15_sol1.smt2                       |29.596MiB|29.596MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C10_sol1.smt2                       |20.112MiB|20.112MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C11_sol1.smt2                       |2971.0MiB|2971.0MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C12_sol1.smt2                       |20.148MiB|20.148MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C13_sol1.smt2                       |20.424MiB|20.424MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C1_sol1.smt2                        |20.352MiB|20.352MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C2_sol1.smt2                        |20.104MiB|20.104MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C3_sol1.smt2                        |20.108MiB|20.108MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C4_sol1.smt2                        |20.036MiB|20.036MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C5_sol1.smt2                        |20.62MiB|20.62MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C6_sol1.smt2                        |20.14MiB|20.14MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C7_sol1.smt2                        |32.9MiB|32.9MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C8_sol1.smt2                        |40.132MiB|40.132MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C9_sol1.smt2                        |20.648MiB|20.648MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C9a_sol1.smt2                       |20.092MiB|20.092MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U10_sol1.smt2                       |20.108MiB|20.108MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U11_sol1.smt2                       |20.832MiB|20.832MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U12_sol1.smt2                       |20.656MiB|20.656MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U13_sol1.smt2                       |20.268MiB|20.268MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U14_sol1.smt2                       |20.62MiB|20.62MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U15_sol1.smt2                       |29.596MiB|29.596MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C10_sol1.smt2                       |20.112MiB|20.112MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C11_sol1.smt2                       |2971.0MiB|2971.0MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C12_sol1.smt2                       |20.148MiB|20.148MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C13_sol1.smt2                       |20.424MiB|20.424MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C1_sol1.smt2                        |20.352MiB|20.352MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C2_sol1.smt2                        |20.104MiB|20.104MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C3_sol1.smt2                        |20.108MiB|20.108MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C4_sol1.smt2                        |20.036MiB|20.036MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C5_sol1.smt2                        |20.62MiB|20.62MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C6_sol1.smt2                        |20.14MiB|20.14MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C7_sol1.smt2                        |32.9MiB|32.9MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C8_sol1.smt2                        |40.132MiB|40.132MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C9_sol1.smt2                        |20.648MiB|20.648MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C9a_sol1.smt2                       |20.092MiB|20.092MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U10_sol1.smt2                       |20.108MiB|20.108MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U11_sol1.smt2                       |20.832MiB|20.832MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U12_sol1.smt2                       |20.656MiB|20.656MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U13_sol1.smt2                       |20.268MiB|20.268MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U14_sol1.smt2                       |20.62MiB|20.62MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U15_sol1.smt2                       |29.596MiB|29.596MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C10_sol1.smt2                       |20.112MiB|20.112MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C11_sol1.smt2                       |2971.0MiB|2971.0MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C12_sol1.smt2                       |20.148MiB|20.148MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C13_sol1.smt2                       |20.424MiB|20.424MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C1_sol1.smt2                        |20.352MiB|20.352MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C2_sol1.smt2                        |20.104MiB|20.104MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C3_sol1.smt2                        |20.108MiB|20.108MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C4_sol1.smt2                        |20.036MiB|20.036MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C5_sol1.smt2                        |20.62MiB|20.62MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C6_sol1.smt2                        |20.14MiB|20.14MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C7_sol1.smt2                        |32.9MiB|32.9MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C8_sol1.smt2                        |40.132MiB|40.132MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C9_sol1.smt2                        |20.648MiB|20.648MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C9a_sol1.smt2                       |20.092MiB|20.092MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U10_sol1.smt2                       |20.108MiB|20.108MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U11_sol1.smt2                       |20.832MiB|20.832MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U12_sol1.smt2                       |20.656MiB|20.656MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U13_sol1.smt2                       |20.268MiB|20.268MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U14_sol1.smt2                       |20.62MiB|20.62MiB|0B| 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U15_sol1.smt2                       |29.596MiB|29.596MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U75.smt2                           |  21.652s |7980.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U89.smt2                           |  21.839s |7370.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C1.smt2                            |  21.825s |7344.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U43_sol1.smt2                      |  21.953s |4849.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U42.smt2                            |  22.205s |4781.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U5.smt2                             |  22.125s |4750.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U29_sol1.smt2                      |  21.658s |4575.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U64.smt2                           |  21.742s |4530.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U2.smt2                            |  21.682s |4478.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U42.smt2                           |  21.524s |4472.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U13.smt2                            |  22.119s |4438.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U73.smt2                            |  21.394s |4414.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U73.smt2                           |  21.529s |4382.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U2.smt2                             |  21.891s |4308.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U92.smt2                            |  20.750s |4296.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U25.smt2                            |  21.748s |4260.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U3.smt2                             |  21.567s |4225.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U49.smt2                            |  21.718s |4072.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U82.smt2                            |  21.645s |4042.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U40.smt2                            |  21.674s |4024.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U75.smt2                           |  21.652s |7980.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U89.smt2                           |  21.839s |7370.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C1.smt2                            |  21.825s |7344.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U43_sol1.smt2                      |  21.953s |4849.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U42.smt2                            |  22.205s |4781.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U5.smt2                             |  22.125s |4750.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U29_sol1.smt2                      |  21.658s |4575.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U64.smt2                           |  21.742s |4530.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U2.smt2                            |  21.682s |4478.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U42.smt2                           |  21.524s |4472.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U13.smt2                            |  22.119s |4438.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U73.smt2                            |  21.394s |4414.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U73.smt2                           |  21.529s |4382.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U2.smt2                             |  21.891s |4308.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U92.smt2                            |  20.750s |4296.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U25.smt2                            |  21.748s |4260.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U3.smt2                             |  21.567s |4225.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U49.smt2                            |  21.718s |4072.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U82.smt2                            |  21.645s |4042.0MiB|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U40.smt2                            |  21.674s |4024.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C10_sol1.smt2                       |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C11_sol1.smt2                       |  21.616s  |  21.616s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C12_sol1.smt2                       |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C13_sol1.smt2                       |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C1_sol1.smt2                        |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C2_sol1.smt2                        |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C3_sol1.smt2                        |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C4_sol1.smt2                        |   0.037s  |   0.037s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C5_sol1.smt2                        |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C6_sol1.smt2                        |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C7_sol1.smt2                        |  20.087s  |  20.087s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C8_sol1.smt2                        |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C9_sol1.smt2                        |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C9a_sol1.smt2                       |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U10_sol1.smt2                       |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U11_sol1.smt2                       |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U12_sol1.smt2                       |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U13_sol1.smt2                       |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U14_sol1.smt2                       |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U15_sol1.smt2                       |  20.116s  |  20.116s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U15_sol2.smt2                       |  21.835s  |  21.835s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U16_sol1.smt2                       |   9.796s  |   9.796s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U17_sol1.smt2                       |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U19_sol1.smt2                       |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U1_sol1.smt2                        |  20.131s  |  20.131s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U20_sol1.smt2                       |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U20_sol2.smt2                       |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U20_sol3.smt2                       |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U21_sol1.smt2                       |  21.275s  |  21.275s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U22_sol1.smt2                       |  21.365s  |  21.365s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U23_sol1.smt2                       |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U24_sol1.smt2                       |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U25_sol1.smt2                       |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U25_sol2.smt2                       |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U26_sol1.smt2                       |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U26_sol2.smt2                       |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U27_sol1.smt2                       |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U29_sol1.smt2                       |  21.658s  |  21.658s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U2_sol1.smt2                        |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U33_sol1.smt2                       |  20.241s  |  20.241s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U37_sol1.smt2                       |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U39_sol1.smt2                       |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U3_sol1.smt2                        |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U40_sol1.smt2                       |  11.689s  |  11.689s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U41_sol1.smt2                       |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U41_sol2.smt2                       |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U41_sol3.smt2                       |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U42_sol1.smt2                       |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U43_sol1.smt2                       |  21.953s  |  21.953s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U44_sol1.smt2                       |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U44_sol2.smt2                       |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U45_sol1.smt2                       |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U45_sol2.smt2                       |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U46_sol1.smt2                       |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U46_sol2.smt2                       |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U48_sol1.smt2                       |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U48_sol2.smt2                       |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U49_sol1.smt2                       |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U49_sol2.smt2                       |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U4_sol1.smt2                        |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U50_sol1.smt2                       |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U50_sol2.smt2                       |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U50_sol3.smt2                       |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U51_sol1.smt2                       |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U53_sol1.smt2                       |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U54_sol1.smt2                       |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U54_sol2.smt2                       |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U56_sol1.smt2                       |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U56_sol2.smt2                       |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U57_sol1.smt2                       |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U5_sol1.smt2                        |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U61_sol1.smt2                       |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U62_sol1.smt2                       |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U64_sol1.smt2                       |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U66_sol1.smt2                       |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U66_sol2.smt2                       |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U67_sol1.smt2                       |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U68_sol1.smt2                       |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U6_sol1.smt2                        |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U71_sol1.smt2                       |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U72_sol1.smt2                       |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U72_sol2.smt2                       |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U73_sol1.smt2                       |  21.427s  |  21.427s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U75_sol1.smt2                       |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U75_sol2.smt2                       |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U76_sol1.smt2                       |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U7_sol1.smt2                        |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U81_sol1.smt2                       |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U82_sol1.smt2                       |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U87_sol1.smt2                       |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U87_sol2.smt2                       |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U89_sol1.smt2                       |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U8_sol1.smt2                        |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U8_sol2.smt2                        |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U90_sol1.smt2                       |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U91_sol1.smt2                       |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U91_sol2.smt2                       |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U92_sol1.smt2                       |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U93_sol1.smt2                       |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U9_sol1.smt2                        |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C1.smt2                              |  21.330s  |  21.330s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C10.smt2                             |  20.193s  |  20.193s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C11.smt2                             |  21.316s  |  21.316s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C12.smt2                             |  21.231s  |  21.231s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C13.smt2                             |  20.148s  |  20.148s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C2.smt2                              |  21.636s  |  21.636s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C3.smt2                              |  20.136s  |  20.136s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C4.smt2                              |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C5.smt2                              |  20.047s  |  20.047s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C6.smt2                              |   4.924s  |   4.924s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C7.smt2                              |  20.083s  |  20.083s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C8.smt2                              |  20.406s  |  20.406s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C9.smt2                              |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C9a.smt2                             |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U1.smt2                              |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U10.smt2                             |  20.057s  |  20.057s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U11.smt2                             |  20.076s  |  20.076s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U12.smt2                             |  20.077s  |  20.077s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U13.smt2                             |  22.119s  |  22.119s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U14.smt2                             |   7.476s  |   7.476s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U15.smt2                             |  21.358s  |  21.358s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U16.smt2                             |  20.322s  |  20.322s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U17.smt2                             |   9.819s  |   9.819s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U19.smt2                             |  20.394s  |  20.394s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U2.smt2                              |  21.891s  |  21.891s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U20.smt2                             |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U21.smt2                             |  20.665s  |  20.665s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U22.smt2                             |  21.467s  |  21.467s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U23.smt2                             |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U24.smt2                             |  22.063s  |  22.063s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U25.smt2                             |  21.748s  |  21.748s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U26.smt2                             |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U27.smt2                             |  20.102s  |  20.102s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U29.smt2                             |  21.151s  |  21.151s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U3.smt2                              |  21.567s  |  21.567s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U33.smt2                             |  20.151s  |  20.151s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U34.smt2                             |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U37.smt2                             |  20.482s  |  20.482s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U39.smt2                             |  20.141s  |  20.141s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U4.smt2                              |  20.095s  |  20.095s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U40.smt2                             |  21.674s  |  21.674s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U41.smt2                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U42.smt2                             |  22.205s  |  22.205s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U43.smt2                             |  21.422s  |  21.422s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U44.smt2                             |  20.222s  |  20.222s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U45.smt2                             |  20.119s  |  20.119s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U46.smt2                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U48.smt2                             |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U49.smt2                             |  21.718s  |  21.718s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U5.smt2                              |  22.125s  |  22.125s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U50.smt2                             |  21.643s  |  21.643s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U51.smt2                             |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U53.smt2                             |  20.040s  |  20.040s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U54.smt2                             |  21.091s  |  21.091s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U56.smt2                             |  21.106s  |  21.106s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U57.smt2                             |  20.097s  |  20.097s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U6.smt2                              |  20.095s  |  20.095s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U61.smt2                             |  21.462s  |  21.462s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U62.smt2                             |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U64.smt2                             |  21.971s  |  21.971s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U66.smt2                             |   0.057s  |   0.057s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U67.smt2                             |  21.181s  |  21.181s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U68.smt2                             |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U7.smt2                              |   5.812s  |   5.812s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U71.smt2                             |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U72.smt2                             |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U73.smt2                             |  21.394s  |  21.394s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U75.smt2                             |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U76.smt2                             |  20.086s  |  20.086s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U8.smt2                              |  21.707s  |  21.707s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U81.smt2                             |  20.135s  |  20.135s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U82.smt2                             |  21.645s  |  21.645s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U87.smt2                             |  20.077s  |  20.077s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U89.smt2                             |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U9.smt2                              |  20.156s  |  20.156s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U90.smt2                             |  20.075s  |  20.075s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U91.smt2                             |  20.582s  |  20.582s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U92.smt2                             |  20.750s  |  20.750s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U93.smt2                             |  20.070s  |  20.070s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C1.smt2                             |  21.825s  |  21.825s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C10.smt2                            |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C11.smt2                            |  21.096s  |  21.096s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C12.smt2                            |  21.321s  |  21.321s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C13.smt2                            |  20.227s  |  20.227s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C2.smt2                             |  20.267s  |  20.267s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C3.smt2                             |  20.125s  |  20.125s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C4.smt2                             |  20.264s  |  20.264s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C5.smt2                             |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C6.smt2                             |  20.089s  |  20.089s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C7.smt2                             |  20.144s  |  20.144s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C8.smt2                             |  20.379s  |  20.379s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C9.smt2                             |  20.100s  |  20.100s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C9a.smt2                            |  20.104s  |  20.104s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U1.smt2                             |  20.094s  |  20.094s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U10.smt2                            |  20.131s  |  20.131s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U11.smt2                            |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U12.smt2                            |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U13.smt2                            |  21.420s  |  21.420s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U14.smt2                            |   6.571s  |   6.571s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U15.smt2                            |  21.232s  |  21.232s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U16.smt2                            |  20.245s  |  20.245s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U17.smt2                            |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U19.smt2                            |  21.167s  |  21.167s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U2.smt2                             |  21.682s  |  21.682s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U20.smt2                            |  21.660s  |  21.660s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U21.smt2                            |  21.365s  |  21.365s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U22.smt2                            |  21.389s  |  21.389s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U23.smt2                            |  20.129s  |  20.129s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U24.smt2                            |  21.616s  |  21.616s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U25.smt2                            |  21.617s  |  21.617s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U26.smt2                            |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U27.smt2                            |  20.090s  |  20.090s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U28.smt2                            |  20.181s  |  20.181s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U29.smt2                            |  21.533s  |  21.533s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U3.smt2                             |  21.263s  |  21.263s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U30.smt2                            |  20.084s  |  20.084s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U31.smt2                            |  21.561s  |  21.561s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U33.smt2                            |  20.198s  |  20.198s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U37.smt2                            |  21.172s  |  21.172s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U38.smt2                            |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U39.smt2                            |  20.070s  |  20.070s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U4.smt2                             |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U40.smt2                            |  21.386s  |  21.386s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U41.smt2                            |  21.262s  |  21.262s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U42.smt2                            |  21.524s  |  21.524s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U43.smt2                            |  20.978s  |  20.978s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U44.smt2                            |  20.156s  |  20.156s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U45.smt2                            |  20.074s  |  20.074s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U46.smt2                            |  21.583s  |  21.583s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U47.smt2                            |  20.137s  |  20.137s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U48.smt2                            |  21.203s  |  21.203s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U49.smt2                            |  21.636s  |  21.636s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U5.smt2                             |  20.556s  |  20.556s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U50.smt2                            |  21.304s  |  21.304s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U51.smt2                            |  20.783s  |  20.783s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U53.smt2                            |  20.141s  |  20.141s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U54.smt2                            |  21.413s  |  21.413s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U56.smt2                            |  21.288s  |  21.288s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U57.smt2                            |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U6.smt2                             |  20.202s  |  20.202s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U61.smt2                            |  21.436s  |  21.436s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U62.smt2                            |  21.371s  |  21.371s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U64.smt2                            |  21.742s  |  21.742s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U65.smt2                            |  21.674s  |  21.674s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U66.smt2                            |  20.133s  |  20.133s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U67.smt2                            |  21.326s  |  21.326s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U68.smt2                            |  20.423s  |  20.423s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U7.smt2                             |  20.130s  |  20.130s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U70.smt2                            |  20.449s  |  20.449s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U71.smt2                            |  20.651s  |  20.651s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U72.smt2                            |  20.299s  |  20.299s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U73.smt2                            |  21.529s  |  21.529s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U75.smt2                            |  21.652s  |  21.652s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U76.smt2                            |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U79.smt2                            |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U8.smt2                             |  21.077s  |  21.077s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U81.smt2                            |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U82.smt2                            |  21.718s  |  21.718s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U87.smt2                            |  21.124s  |  21.124s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U88.smt2                            |  20.074s  |  20.074s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U89.smt2                            |  21.839s  |  21.839s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U9.smt2                             |  20.262s  |  20.262s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U90.smt2                            |  20.156s  |  20.156s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U91.smt2                            |  20.532s  |  20.532s  |   0.000s  | 0.0%|
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U92.smt2                            |  20.990s  |  20.990s  |   0.000s  | 0.0%|
</details>
