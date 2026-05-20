Comparing data and data


# SUMMARY
- LHS tests = 1583
- RHS tests = 1583
- LHS success = 1583  (100.0%)
- RHS success = 1583  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: UFDTLIA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/UFDTLIA.tar.zst?download=1
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
Job tag: UFDTLIA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/UFDTLIA.tar.zst?download=1
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
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal1.smt2                |  20.235s  |  20.235s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal10.smt2               |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal11.smt2               |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal12.smt2               |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal13.smt2               |  20.064s  |  20.064s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal14.smt2               |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal15.smt2               |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal16.smt2               |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal17.smt2               |  20.175s  |  20.175s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal18.smt2               |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal19.smt2               |  20.109s  |  20.109s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal2.smt2                |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal20.smt2               |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal21.smt2               |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal22.smt2               |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal23.smt2               |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal24.smt2               |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal25.smt2               |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal26.smt2               |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal27.smt2               |  20.054s  |  20.054s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal1.smt2                |  20.235s  |  20.235s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal10.smt2               |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal11.smt2               |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal12.smt2               |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal13.smt2               |  20.064s  |  20.064s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal14.smt2               |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal15.smt2               |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal16.smt2               |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal17.smt2               |  20.175s  |  20.175s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal18.smt2               |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal19.smt2               |  20.109s  |  20.109s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal2.smt2                |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal20.smt2               |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal21.smt2               |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal22.smt2               |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal23.smt2               |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal24.smt2               |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal25.smt2               |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal26.smt2               |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal27.smt2               |  20.054s  |  20.054s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal1.smt2                |  20.235s  |  20.235s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal10.smt2               |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal11.smt2               |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal12.smt2               |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal13.smt2               |  20.064s  |  20.064s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal14.smt2               |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal15.smt2               |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal16.smt2               |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal17.smt2               |  20.175s  |  20.175s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal18.smt2               |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal19.smt2               |  20.109s  |  20.109s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal2.smt2                |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal20.smt2               |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal21.smt2               |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal22.smt2               |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal23.smt2               |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal24.smt2               |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal25.smt2               |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal26.smt2               |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal27.smt2               |  20.054s  |  20.054s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal1.smt2                |  20.235s  |  20.235s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal10.smt2               |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal11.smt2               |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal12.smt2               |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal13.smt2               |  20.064s  |  20.064s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal14.smt2               |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal15.smt2               |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal16.smt2               |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal17.smt2               |  20.175s  |  20.175s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal18.smt2               |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal19.smt2               |  20.109s  |  20.109s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal2.smt2                |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal20.smt2               |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal21.smt2               |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal22.smt2               |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal23.smt2               |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal24.smt2               |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal25.smt2               |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal26.smt2               |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal27.smt2               |  20.054s  |  20.054s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal84.smt2        |  21.478s |3172.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal85.smt2        |  21.335s |2302.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal12.smt2         |  21.240s |3093.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal4.smt2          |  21.204s |2943.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal7.smt2          |  21.194s |2974.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal2.smt2          |  21.189s |2891.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal9.smt2          |  21.189s |2996.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal1.smt2          |  21.185s |2819.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal10.smt2         |  21.182s |2868.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal11.smt2         |  21.178s |2902.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal15.smt2 |  21.175s |3001.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal3.smt2          |  21.149s |2299.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal6.smt2          |  21.144s |2317.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal13.smt2 |  21.054s |1942.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/nichomachus-goal5.smt2 |  21.045s |2366.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/nichomachus-goal9.smt2 |  21.034s |2179.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/nichomachus-goal8.smt2 |  21.011s |2051.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/nichomachus-goal8.smt2 |  21.010s |2127.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/nichomachus-goal4.smt2 |  21.000s |2259.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/nichomachus-goal3.smt2 |  20.995s |2360.0MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal84.smt2        |  21.478s |3172.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal85.smt2        |  21.335s |2302.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal12.smt2         |  21.240s |3093.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal4.smt2          |  21.204s |2943.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal7.smt2          |  21.194s |2974.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal2.smt2          |  21.189s |2891.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal9.smt2          |  21.189s |2996.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal1.smt2          |  21.185s |2819.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal10.smt2         |  21.182s |2868.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal11.smt2         |  21.178s |2902.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal15.smt2 |  21.175s |3001.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal3.smt2          |  21.149s |2299.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal6.smt2          |  21.144s |2317.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal13.smt2 |  21.054s |1942.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/nichomachus-goal5.smt2 |  21.045s |2366.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/nichomachus-goal9.smt2 |  21.034s |2179.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/nichomachus-goal8.smt2 |  21.011s |2051.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/nichomachus-goal8.smt2 |  21.010s |2127.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/nichomachus-goal4.smt2 |  21.000s |2259.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/nichomachus-goal3.smt2 |  20.995s |2360.0MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal1.smt2                |1915.0MiB|1915.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal10.smt2               |299.0MiB|299.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal11.smt2               |313.0MiB|313.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal12.smt2               |320.0MiB|320.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal13.smt2               |314.0MiB|314.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal14.smt2               |154.0MiB|154.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal15.smt2               |20.956MiB|20.956MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal16.smt2               |346.0MiB|346.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal17.smt2               |175.0MiB|175.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal18.smt2               |180.0MiB|180.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal19.smt2               |337.0MiB|337.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal2.smt2                |53.0MiB|53.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal20.smt2               |58.344MiB|58.344MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal21.smt2               |191.0MiB|191.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal22.smt2               |52.328MiB|52.328MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal23.smt2               |231.0MiB|231.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal24.smt2               |21.44MiB|21.44MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal25.smt2               |105.0MiB|105.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal26.smt2               |34.776MiB|34.776MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal27.smt2               |294.0MiB|294.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal1.smt2                |1915.0MiB|1915.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal10.smt2               |299.0MiB|299.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal11.smt2               |313.0MiB|313.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal12.smt2               |320.0MiB|320.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal13.smt2               |314.0MiB|314.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal14.smt2               |154.0MiB|154.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal15.smt2               |20.956MiB|20.956MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal16.smt2               |346.0MiB|346.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal17.smt2               |175.0MiB|175.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal18.smt2               |180.0MiB|180.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal19.smt2               |337.0MiB|337.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal2.smt2                |53.0MiB|53.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal20.smt2               |58.344MiB|58.344MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal21.smt2               |191.0MiB|191.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal22.smt2               |52.328MiB|52.328MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal23.smt2               |231.0MiB|231.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal24.smt2               |21.44MiB|21.44MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal25.smt2               |105.0MiB|105.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal26.smt2               |34.776MiB|34.776MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal27.smt2               |294.0MiB|294.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal1.smt2                |1915.0MiB|1915.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal10.smt2               |299.0MiB|299.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal11.smt2               |313.0MiB|313.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal12.smt2               |320.0MiB|320.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal13.smt2               |314.0MiB|314.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal14.smt2               |154.0MiB|154.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal15.smt2               |20.956MiB|20.956MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal16.smt2               |346.0MiB|346.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal17.smt2               |175.0MiB|175.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal18.smt2               |180.0MiB|180.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal19.smt2               |337.0MiB|337.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal2.smt2                |53.0MiB|53.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal20.smt2               |58.344MiB|58.344MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal21.smt2               |191.0MiB|191.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal22.smt2               |52.328MiB|52.328MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal23.smt2               |231.0MiB|231.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal24.smt2               |21.44MiB|21.44MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal25.smt2               |105.0MiB|105.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal26.smt2               |34.776MiB|34.776MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal27.smt2               |294.0MiB|294.0MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal1.smt2                |1915.0MiB|1915.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal10.smt2               |299.0MiB|299.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal11.smt2               |313.0MiB|313.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal12.smt2               |320.0MiB|320.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal13.smt2               |314.0MiB|314.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal14.smt2               |154.0MiB|154.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal15.smt2               |20.956MiB|20.956MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal16.smt2               |346.0MiB|346.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal17.smt2               |175.0MiB|175.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal18.smt2               |180.0MiB|180.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal19.smt2               |337.0MiB|337.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal2.smt2                |53.0MiB|53.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal20.smt2               |58.344MiB|58.344MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal21.smt2               |191.0MiB|191.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal22.smt2               |52.328MiB|52.328MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal23.smt2               |231.0MiB|231.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal24.smt2               |21.44MiB|21.44MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal25.smt2               |105.0MiB|105.0MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal26.smt2               |34.776MiB|34.776MiB|0B| 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal27.smt2               |294.0MiB|294.0MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal84.smt2        |  21.478s |3172.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg1.smt2         |  20.422s |3148.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal12.smt2         |  21.240s |3093.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal15.smt2 |  21.175s |3001.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal9.smt2          |  21.189s |2996.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal7.smt2          |  21.194s |2974.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal4.smt2          |  21.204s |2943.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal11.smt2         |  21.178s |2902.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal2.smt2          |  21.189s |2891.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal10.smt2         |  21.182s |2868.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal1.smt2          |  21.185s |2819.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg4.smt2         |  20.290s |2379.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/nichomachus-goal5.smt2 |  21.045s |2366.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/nichomachus-goal3.smt2 |  20.995s |2360.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal6.smt2          |  21.144s |2317.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal85.smt2        |  21.335s |2302.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal3.smt2          |  21.149s |2299.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/nichomachus-goal4.smt2 |  21.000s |2259.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal59.smt2        |  20.373s |2219.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/nichomachus-goal9.smt2 |  21.034s |2179.0MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal84.smt2        |  21.478s |3172.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg1.smt2         |  20.422s |3148.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal12.smt2         |  21.240s |3093.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal15.smt2 |  21.175s |3001.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal9.smt2          |  21.189s |2996.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal7.smt2          |  21.194s |2974.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal4.smt2          |  21.204s |2943.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal11.smt2         |  21.178s |2902.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal2.smt2          |  21.189s |2891.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal10.smt2         |  21.182s |2868.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal1.smt2          |  21.185s |2819.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg4.smt2         |  20.290s |2379.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/nichomachus-goal5.smt2 |  21.045s |2366.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/nichomachus-goal3.smt2 |  20.995s |2360.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal6.smt2          |  21.144s |2317.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal85.smt2        |  21.335s |2302.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal3.smt2          |  21.149s |2299.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/nichomachus-goal4.smt2 |  21.000s |2259.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal59.smt2        |  20.373s |2219.0MiB|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/nichomachus-goal9.smt2 |  21.034s |2179.0MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal1.smt2                |  20.235s  |  20.235s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal10.smt2               |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal11.smt2               |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal12.smt2               |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal13.smt2               |  20.064s  |  20.064s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal14.smt2               |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal15.smt2               |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal16.smt2               |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal17.smt2               |  20.175s  |  20.175s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal18.smt2               |  20.058s  |  20.058s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal19.smt2               |  20.109s  |  20.109s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal2.smt2                |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal20.smt2               |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal21.smt2               |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal22.smt2               |  20.019s  |  20.019s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal23.smt2               |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal24.smt2               |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal25.smt2               |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal26.smt2               |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal27.smt2               |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal28.smt2               |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal29.smt2               |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal3.smt2                |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal30.smt2               |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal31.smt2               |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal32.smt2               |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal33.smt2               |  20.025s  |  20.025s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal34.smt2               |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal35.smt2               |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal36.smt2               |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal37.smt2               |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal38.smt2               |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal39.smt2               |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal4.smt2                |  20.129s  |  20.129s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal45.smt2               |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal46.smt2               |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal47.smt2               |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal48.smt2               |  20.047s  |  20.047s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal49.smt2               |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal5.smt2                |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal50.smt2               |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal51.smt2               |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal52.smt2               |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal53.smt2               |  20.106s  |  20.106s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal54.smt2               |  20.040s  |  20.040s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal55.smt2               |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal56.smt2               |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal57.smt2               |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal58.smt2               |  20.083s  |  20.083s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal59.smt2               |  20.109s  |  20.109s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal6.smt2                |  20.136s  |  20.136s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal60.smt2               |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal61.smt2               |  20.020s  |  20.020s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal62.smt2               |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal63.smt2               |  20.081s  |  20.081s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal64.smt2               |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal65.smt2               |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal66.smt2               |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal67.smt2               |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal68.smt2               |  20.108s  |  20.108s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal69.smt2               |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal7.smt2                |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal70.smt2               |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal71.smt2               |  20.069s  |  20.069s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal72.smt2               |  20.023s  |  20.023s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal73.smt2               |  20.040s  |  20.040s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal74.smt2               |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal75.smt2               |  20.118s  |  20.118s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal76.smt2               |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal77.smt2               |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal78.smt2               |  20.137s  |  20.137s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal8.smt2                |  20.070s  |  20.070s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal81.smt2               |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal82.smt2               |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal84.smt2               |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal85.smt2               |  20.074s  |  20.074s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal86.smt2               |  20.097s  |  20.097s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal9.smt2                |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg1.smt2          |  20.422s  |  20.422s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg10.smt2         |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg11.smt2         |  20.085s  |  20.085s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg12.smt2         |  20.050s  |  20.050s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg13.smt2         |  20.087s  |  20.087s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg14.smt2         |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg15.smt2         |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg16.smt2         |  20.102s  |  20.102s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg17.smt2         |  20.066s  |  20.066s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg18.smt2         |  20.180s  |  20.180s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg19.smt2         |  20.086s  |  20.086s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg2.smt2          |  20.022s  |  20.022s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg20.smt2         |  20.021s  |  20.021s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg21.smt2         |  20.146s  |  20.146s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg22.smt2         |  20.061s  |  20.061s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg23.smt2         |  20.054s  |  20.054s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg24.smt2         |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg25.smt2         |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg26.smt2         |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg27.smt2         |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg28.smt2         |  20.197s  |  20.197s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg29.smt2         |   0.040s  |   0.040s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg3.smt2          |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg30.smt2         |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg31.smt2         |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg32.smt2         |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg33.smt2         |  10.642s  |  10.642s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg34.smt2         |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg35.smt2         |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg4.smt2          |  20.290s  |  20.290s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg48.smt2         |  20.028s  |  20.028s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg49.smt2         |  20.027s  |  20.027s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg5.smt2          |  20.063s  |  20.063s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg50.smt2         |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg6.smt2          |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg7.smt2          |  20.039s  |  20.039s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg75.smt2         |  20.284s  |  20.284s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg76.smt2         |  20.242s  |  20.242s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg77.smt2         |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg78.smt2         |  20.087s  |  20.087s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg79.smt2         |  20.069s  |  20.069s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg8.smt2          |  20.073s  |  20.073s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg80.smt2         |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg81.smt2         |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg82.smt2         |  20.047s  |  20.047s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg83.smt2         |  20.187s  |  20.187s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg84.smt2         |  20.232s  |  20.232s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg85.smt2         |  20.118s  |  20.118s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg86.smt2         |  20.255s  |  20.255s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg9.smt2          |  20.037s  |  20.037s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/nichomachus-goal1.smt2  |  20.888s  |  20.888s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/nichomachus-goal2.smt2  |  20.793s  |  20.793s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/nichomachus-goal3.smt2  |  20.976s  |  20.976s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/nichomachus-goal4.smt2  |  21.000s  |  21.000s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/nichomachus-goal5.smt2  |  21.045s  |  21.045s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/nichomachus-goal6.smt2  |  20.979s  |  20.979s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/nichomachus-goal7.smt2  |  20.919s  |  20.919s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/nichomachus-goal8.smt2  |  21.011s  |  21.011s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/nichomachus-goal9.smt2  |  21.034s  |  21.034s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rev-equiv-goal1.smt2   |  20.118s  |  20.118s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rev-equiv-goal2.smt2   |  20.119s  |  20.119s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rev-equiv-goal3.smt2   |  20.146s  |  20.146s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rev-equiv-goal4.smt2   |  20.132s  |  20.132s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rev-equiv-goal5.smt2   |  20.149s  |  20.149s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rev-equiv-goal6.smt2   |  20.150s  |  20.150s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rev-equiv-goal7.smt2   |  20.161s  |  20.161s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rev-equiv-goal8.smt2   |  20.142s  |  20.142s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rotate-goal1.smt2      |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rotate-goal2.smt2      |  20.106s  |  20.106s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rotate-goal3.smt2      |  20.107s  |  20.107s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rotate-goal4.smt2      |  20.119s  |  20.119s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rotate-goal5.smt2      |  20.153s  |  20.153s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rotate-goal6.smt2      |  20.083s  |  20.083s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rotate-goal7.smt2      |  20.048s  |  20.048s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rotate-goal8.smt2      |  20.127s  |  20.127s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rotate-goal9.smt2      |  20.076s  |  20.076s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/nichomachus-goal2.smt2  |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/nichomachus-goal3.smt2  |  20.995s  |  20.995s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/nichomachus-goal4.smt2  |  20.875s  |  20.875s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/nichomachus-goal5.smt2  |  20.994s  |  20.994s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/nichomachus-goal6.smt2  |  20.968s  |  20.968s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/nichomachus-goal7.smt2  |  20.875s  |  20.875s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/nichomachus-goal8.smt2  |  21.010s  |  21.010s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/nichomachus-goal9.smt2  |  20.929s  |  20.929s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/rev-equiv-goal3.smt2  |  20.533s  |  20.533s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/rev-equiv-goal6.smt2  |  20.521s  |  20.521s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/rev-equiv-goal7.smt2  |  20.290s  |  20.290s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/rev-equiv-goal8.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/rotate-goal4.smt2   |  20.527s  |  20.527s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/rotate-goal7.smt2   |  20.033s  |  20.033s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/rotate-goal8.smt2   |  20.550s  |  20.550s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/rotate-goal9.smt2   |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal1.smt2          |  20.551s  |  20.551s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal10.smt2         |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal11.smt2         |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal12.smt2         |  20.166s  |  20.166s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal13.smt2         |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal14.smt2         |  20.820s  |  20.820s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal15.smt2         |  20.123s  |  20.123s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal16.smt2         |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal17.smt2         |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal18.smt2         |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal19.smt2         |  20.105s  |  20.105s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal2.smt2          |  20.044s  |  20.044s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal20.smt2         |  20.152s  |  20.152s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal21.smt2         |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal22.smt2         |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal23.smt2         |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal24.smt2         |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal25.smt2         |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal26.smt2         |  20.085s  |  20.085s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal27.smt2         |  20.075s  |  20.075s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal28.smt2         |  20.038s  |  20.038s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal29.smt2         |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal3.smt2          |  20.045s  |  20.045s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal30.smt2         |  20.097s  |  20.097s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal31.smt2         |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal32.smt2         |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal33.smt2         |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal34.smt2         |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal35.smt2         |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal36.smt2         |  20.079s  |  20.079s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal37.smt2         |  20.177s  |  20.177s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal38.smt2         |  20.084s  |  20.084s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal39.smt2         |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal4.smt2          |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal40.smt2         |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal41.smt2         |  20.103s  |  20.103s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal42.smt2         |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal43.smt2         |  20.396s  |  20.396s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal44.smt2         |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal45.smt2         |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal46.smt2         |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal47.smt2         |  20.064s  |  20.064s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal48.smt2         |  20.430s  |  20.430s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal49.smt2         |  20.381s  |  20.381s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal5.smt2          |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal50.smt2         |  20.414s  |  20.414s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal51.smt2         |  20.520s  |  20.520s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal52.smt2         |  20.113s  |  20.113s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal53.smt2         |  20.107s  |  20.107s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal54.smt2         |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal55.smt2         |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal56.smt2         |  20.133s  |  20.133s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal57.smt2         |  20.106s  |  20.106s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal58.smt2         |  20.126s  |  20.126s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal59.smt2         |  20.373s  |  20.373s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal6.smt2          |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal60.smt2         |  20.082s  |  20.082s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal61.smt2         |  20.059s  |  20.059s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal62.smt2         |  20.120s  |  20.120s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal63.smt2         |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal64.smt2         |  20.167s  |  20.167s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal65.smt2         |  20.137s  |  20.137s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal66.smt2         |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal67.smt2         |  20.289s  |  20.289s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal68.smt2         |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal69.smt2         |  20.156s  |  20.156s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal7.smt2          |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal70.smt2         |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal71.smt2         |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal72.smt2         |  20.134s  |  20.134s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal73.smt2         |  20.079s  |  20.079s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal74.smt2         |  20.118s  |  20.118s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal75.smt2         |  20.183s  |  20.183s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal76.smt2         |  20.386s  |  20.386s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal77.smt2         |  20.076s  |  20.076s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal78.smt2         |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal79.smt2         |  20.145s  |  20.145s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal8.smt2          |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal80.smt2         |  20.086s  |  20.086s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal81.smt2         |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal82.smt2         |  20.104s  |  20.104s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal83.smt2         |  20.187s  |  20.187s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal84.smt2         |  21.478s  |  21.478s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal85.smt2         |  21.335s  |  21.335s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal86.smt2         |  20.290s  |  20.290s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal87.smt2         |  20.181s  |  20.181s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal9.smt2          |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal1.smt2  |  20.227s  |  20.227s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal10.smt2  |  20.415s  |  20.415s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal11.smt2  |   9.854s  |   9.854s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal12.smt2  |   1.222s  |   1.222s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal13.smt2  |  21.054s  |  21.054s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal14.smt2  |  17.707s  |  17.707s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal15.smt2  |  21.175s  |  21.175s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal2.smt2  |  20.279s  |  20.279s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal3.smt2  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal4.smt2  |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal5.smt2  |  20.315s  |  20.315s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal6.smt2  |   7.562s  |   7.562s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal7.smt2  |  20.351s  |  20.351s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal8.smt2  |  20.852s  |  20.852s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal9.smt2  |  20.372s  |  20.372s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal1.smt2   |  20.234s  |  20.234s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal10.smt2  |  20.250s  |  20.250s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal11.smt2  |  20.100s  |  20.100s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal12.smt2  |  20.537s  |  20.537s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal13.smt2  |  20.933s  |  20.933s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal14.smt2  |  20.265s  |  20.265s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal15.smt2  |  20.897s  |  20.897s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal16.smt2  |  20.110s  |  20.110s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal17.smt2  |  20.462s  |  20.462s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal18.smt2  |  20.088s  |  20.088s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal2.smt2   |  20.139s  |  20.139s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal3.smt2   |  20.127s  |  20.127s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal4.smt2   |  20.148s  |  20.148s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal5.smt2   |  20.586s  |  20.586s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal6.smt2   |  20.923s  |  20.923s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal7.smt2   |  20.922s  |  20.922s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal8.smt2   |  20.507s  |  20.507s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal9.smt2   |  20.830s  |  20.830s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal1.smt2           |  21.185s  |  21.185s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal10.smt2          |  21.182s  |  21.182s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal11.smt2          |  21.178s  |  21.178s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal12.smt2          |  21.240s  |  21.240s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal13.smt2          |  20.855s  |  20.855s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal2.smt2           |  21.189s  |  21.189s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal3.smt2           |  21.149s  |  21.149s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal4.smt2           |  21.204s  |  21.204s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal5.smt2           |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal6.smt2           |  21.144s  |  21.144s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal7.smt2           |  21.194s  |  21.194s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal8.smt2           |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal9.smt2           |  21.189s  |  21.189s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/2019-Gleiss/hamming-weight/1-hw-equal-arrays.spec.smt2              |  20.100s  |  20.100s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/2019-Gleiss/hamming-weight/2-hw-last-position-swapped.spec.smt2     |  20.270s  |  20.270s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/2019-Gleiss/hamming-weight/3-hw-swap-and-two-arrays.spec.smt2       |  20.073s  |  20.073s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/2019-Gleiss/hamming-weight/4-hw-swap-in-array-full.spec.smt2        |  20.274s  |  20.274s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/2019-Gleiss/hamming-weight/4-hw-swap-in-array-lemma.spec.smt2       |  20.241s  |  20.241s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/2019-Gleiss/non-interference/1-ni-assign-to-high.spec.smt2          |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/2019-Gleiss/non-interference/2-ni-branch-on-high-twice.spec.smt2    |   0.055s  |   0.055s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/2019-Gleiss/non-interference/3-ni-high-guard-equal-branches.spec.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/2019-Gleiss/non-interference/4-ni-branch-on-high-twice-prop2.spec.smt2  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/2019-Gleiss/non-interference/5-ni-temp-impl-flow.spec.smt2          |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/2019-Gleiss/non-interference/6-ni-branch-assign-equal-val.spec.smt2  |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/2019-Gleiss/non-interference/7-ni-explicit-flow.spec.smt2           |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/2019-Gleiss/non-interference/8-ni-explicit-flow-while.spec.smt2     |   0.416s  |   0.416s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/2019-Gleiss/non-interference/9-ni-equal-output.spec.smt2            |  16.495s  |  16.495s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/2019-Gleiss/sensitivity/1-sens-equal-sums.spec.smt2                 |  20.299s  |  20.299s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/2019-Gleiss/sensitivity/10-sens-equal-k.spec.smt2                   |   9.842s  |   9.842s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/2019-Gleiss/sensitivity/11-sens-equal-k-twice.spec.smt2             |  13.391s  |  13.391s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/2019-Gleiss/sensitivity/12-sens-diff-up-to-forall-k.spec.smt2       |   0.543s  |   0.543s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/2019-Gleiss/sensitivity/2-sens-equal-sums-two-arrays.spec.smt2      |  20.812s  |  20.812s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/2019-Gleiss/sensitivity/5-sens-two-arrays-equal-k.spec.smt2         |  20.595s  |  20.595s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/2019-Gleiss/sensitivity/6-sens-diff-up-to-explicit-k.spec.smt2      |  20.878s  |  20.878s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/2019-Gleiss/sensitivity/7-sens-diff-up-to-explicit-k-sum.spec.smt2  |   5.790s  |   5.790s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/2019-Gleiss/sensitivity/8-sens-explicit-swap.spec.smt2              |   9.045s  |   9.045s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/2019-Gleiss/sensitivity/9-sens-explicit-swap-prop2.spec.smt2        |  20.745s  |  20.745s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20230314-Jaroslav-Bendik-Certora/52759_b3ecd2335fd16ec2eee2_9_UFDTLIA.smt2  |  20.055s  |  20.055s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__reconciler.3.smt2  |   1.373s  |   1.373s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__reconciler.6.smt2  |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__reconciler.8.smt2  |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__reconciler.9.smt2  |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__resource__common.1.smt2  |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__resource__common.2.smt2  |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__resource__common.3.smt2  |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__resource__daemon_set.4.smt2  |   0.686s  |   0.686s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__resource__daemon_set.6.smt2  |   0.344s  |   0.344s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__resource__role.1.smt2  |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__resource__role.5.smt2  |   0.279s  |   0.279s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__resource__role_binding.5.smt2  |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__resource__service.6.smt2  |   0.260s  |   0.260s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__resource__service.7.smt2  |   0.393s  |   0.393s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__resource__service.8.smt2  |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__resource__service_account.4.smt2  |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__resource__service_account.5.smt2  |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__resource__service_account.8.smt2  |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__helper_invariants__proof__lemma_always_no_update_status_request_msg_not_from_bc_in_flight_of_daemon_set.smt2  |  20.068s  |  20.068s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__helper_invariants__proof__lemma_always_resource_object_create_or_update_request_msg_has_one_controller_ref_and_no_finalizers.smt2  |  20.092s  |  20.092s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__helper_invariants__proof__lemma_eventually_always_every_resource_update_request_implies_at_after_update_resource_step.smt2  |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__helper_invariants__proof__make_fluentbit_pod_spec_determined_by_spec_and_name.smt2  |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__helper_invariants__unchangeable.1.smt2  |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__helper_invariants__unchangeable.4.smt2  |  20.090s  |  20.090s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__daemon_set_match.2.smt2  |   0.732s  |   0.732s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__daemon_set_match__lemma_daemon_set_state_matches_at_after_update_daemon_set_step.smt2  |  20.078s  |  20.078s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__daemon_set_match__lemma_from_after_get_daemon_set_step_to_after_update_daemon_set_step.smt2  |  20.091s  |  20.091s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__daemon_set_match__lemma_from_key_exists_to_receives_ok_resp_at_after_get_daemon_set_step.smt2  |  20.075s  |  20.075s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__proof.1.smt2  |  20.073s  |  20.073s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__proof.12.smt2  |   0.361s  |   0.361s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__proof.3.smt2  |  20.063s  |  20.063s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__proof.9.smt2  |   0.688s  |   0.688s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__resource_match.1.smt2  |  20.109s  |  20.109s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__resource_match.7.smt2  |  20.064s  |  20.064s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__resource_match__lemma_from_after_get_resource_step_to_after_create_resource_step.smt2  |  20.051s  |  20.051s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__resource_match__lemma_from_key_not_exists_to_receives_not_found_resp_at_after_get_resource_step.smt2  |  20.073s  |  20.073s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__spec.10.smt2  |   0.443s  |   0.443s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__spec.2.smt2  |   0.564s  |   0.564s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__spec.3.smt2  |   0.665s  |   0.665s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__spec.4.smt2  |   0.314s  |   0.314s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__spec.9.smt2  |   0.362s  |   0.362s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__terminate.1.smt2  |  19.646s  |  19.646s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__trusted__spec_types.2.smt2  |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__exec__reconciler.7.smt2  |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__exec__resource__secret.2.smt2  |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__exec__resource__secret.8.smt2  |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__proof__helper_invariants__owner_ref.2.smt2  |  20.024s  |  20.024s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__proof__helper_invariants__proof__lemma_always_no_update_status_request_msg_in_flight.smt2  |  20.087s  |  20.087s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__proof__helper_invariants__proof__lemma_always_resource_object_create_or_update_request_msg_has_one_controller_ref_and_no_finalizers.smt2  |  20.043s  |  20.043s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__proof__helper_invariants__proof__lemma_always_response_at_after_get_resource_step_is_resource_get_response.smt2  |  20.053s  |  20.053s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__proof__helper_invariants__proof__lemma_resource_create_or_update_request_msg_implies_key_in_reconcile_equals.smt2  |  20.068s  |  20.068s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__proof__liveness__proof.2.smt2  |  20.106s  |  20.106s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__proof__liveness__proof.4.smt2  |   0.437s  |   0.437s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__proof__liveness__proof.5.smt2  |  20.063s  |  20.063s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__proof__liveness__proof.9.smt2  |   0.305s  |   0.305s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__proof__liveness__resource_match.1.smt2  |  20.079s  |  20.079s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__proof__liveness__resource_match.4.smt2  |  20.068s  |  20.068s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__proof__liveness__resource_match.6.smt2  |  20.036s  |  20.036s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__proof__liveness__spec.1.smt2  |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__proof__liveness__spec.2.smt2  |   0.392s  |   0.392s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__proof__liveness__spec.5.smt2  |   0.351s  |   0.351s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__proof__liveness__terminate.1.smt2  |   5.558s  |   5.558s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__trusted__spec_types.2.smt2  |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__trusted__spec_types.3.smt2  |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__trusted__spec_types.5.smt2  |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__AbstractCrashAwareSystemRefinement_v.11.smt2  |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__AbstractCrashAwareSystemRefinement_v.13.smt2  |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__AbstractCrashAwareSystemRefinement_v.15.smt2  |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__AbstractCrashAwareSystemRefinement_v.25.smt2  |   2.771s  |   2.771s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__AbstractCrashAwareSystemRefinement_v.26.smt2  |   0.348s  |   0.348s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__AbstractCrashAwareSystemRefinement_v.29.smt2  |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__AbstractCrashAwareSystemRefinement_v.3.smt2  |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__AbstractJournal_v__AbstractJournal.2.smt2  |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__MsgHistory_v.10.smt2  |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__MsgHistory_v.11.smt2  |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__MsgHistory_v.14.smt2  |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__MsgHistory_v.16.smt2  |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__MsgHistory_v.18.smt2  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__MsgHistory_v.21.smt2  |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__MsgHistory_v.23.smt2  |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__MsgHistory_v.26.smt2  |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__MsgHistory_v.27.smt2  |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__MsgHistory_v.30.smt2  |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__MsgHistory_v.5.smt2  |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__MsgHistory_v.8.smt2  |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__StampedMap_v.3.smt2  |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationCrashAwareJournalRefinement_v.3.smt2  |   0.412s  |   0.412s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationCrashAwareJournalRefinement_v.6.smt2  |   0.962s  |   0.962s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationCrashAwareJournalRefinement_v.7.smt2  |   0.580s  |   0.580s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationCrashAwareJournal_v.2.smt2  |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationCrashAwareJournal_v__AllocationCrashAwareJournal.11.smt2  |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationCrashAwareJournal_v__AllocationCrashAwareJournal.4.smt2  |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationCrashAwareJournal_v__AllocationCrashAwareJournal.6.smt2  |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationCrashAwareJournal_v__AllocationCrashAwareJournal.7.smt2  |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournalRefinement_v.3.smt2  |   0.302s  |   0.302s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournalRefinement_v.5.smt2  |   7.860s  |   7.860s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournalRefinement_v.6.smt2  |   1.223s  |   1.223s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournalRefinement_v.8.smt2  |   2.119s  |   2.119s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v.1.smt2  |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v.13.smt2  |   0.274s  |   0.274s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v.14.smt2  |   0.273s  |   0.273s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v.16.smt2  |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v.21.smt2  |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v.22.smt2  |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v.27.smt2  |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v.28.smt2  |   1.648s  |   1.648s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v.29.smt2  |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v.42.smt2  |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v.43.smt2  |  20.088s  |  20.088s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v.44.smt2  |   0.662s  |   0.662s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v.46.smt2  |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v.6.smt2  |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v__AllocationJournal.1.smt2  |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v__AllocationJournal.11.smt2  |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v__AllocationJournal.12.smt2  |  12.571s  |  12.571s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v__AllocationJournal.16.smt2  |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v__AllocationJournal.7.smt2  |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesBetree_v.1.smt2  |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesBetree_v.14.smt2  |   0.370s  |   0.370s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesBetree_v.15.smt2  |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesBetree_v.17.smt2  |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesBetree_v.18.smt2  |   0.369s  |   0.369s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesBetree_v.19.smt2  |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesBetree_v.4.smt2  |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesBetree_v.9.smt2  |   0.286s  |   0.286s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesBetree_v__LikesBetree.5.smt2  |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesBetree_v__LikesBetree.6.smt2  |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesBetree_v__LikesBetree.7.smt2  |   0.327s  |   0.327s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesBetree_v__LikesBetree.8.smt2  |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournalRefinement_v.3.smt2  |   0.730s  |   0.730s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v.10.smt2  |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v.12.smt2  |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v.13.smt2  |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v.15.smt2  |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v.16.smt2  |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v.18.smt2  |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v.2.smt2  |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v.22.smt2  |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v.27.smt2  |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v.31.smt2  |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v.5.smt2  |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v.8.smt2  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v.9.smt2  |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v__LikesJournal.11.smt2  |   0.386s  |   0.386s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v__LikesJournal.2.smt2  |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v__LikesJournal.3.smt2  |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v__LikesJournal.4.smt2  |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__MiniAllocator_v.12.smt2  |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__MiniAllocator_v.13.smt2  |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__MiniAllocator_v.14.smt2  |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__MiniAllocator_v.15.smt2  |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__MiniAllocator_v.17.smt2  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__MiniAllocator_v.20.smt2  |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__MiniAllocator_v.3.smt2  |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__MiniAllocator_v.4.smt2  |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__UnifiedCrashAwareJournalRefinement_v.3.smt2  |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__UnifiedCrashAwareJournal_v.11.smt2  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__UnifiedCrashAwareJournal_v.12.smt2  |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__UnifiedCrashAwareJournal_v.14.smt2  |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__UnifiedCrashAwareJournal_v.15.smt2  |   0.470s  |   0.470s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__UnifiedCrashAwareJournal_v__UnifiedCrashAwareJournal.3.smt2  |   0.437s  |   0.437s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__UnifiedCrashAwareJournal_v__UnifiedCrashAwareJournal.4.smt2  |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__BufferDisk_v.2.smt2     |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__BufferDisk_v.7.smt2     |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__BufferOffsets_v.2.smt2  |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__BufferOffsets_v.4.smt2  |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__BufferOffsets_v.5.smt2  |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__BufferOffsets_v.7.smt2  |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__BufferSeq_v.12.smt2     |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__BufferSeq_v.5.smt2      |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__BufferSeq_v.9.smt2      |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__Buffer_v.10.smt2        |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__Buffer_v.11.smt2        |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__Buffer_v.12.smt2        |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__Buffer_v.14.smt2        |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__Buffer_v.15.smt2        |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__Buffer_v.2.smt2         |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__Buffer_v.3.smt2         |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__Buffer_v.5.smt2         |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__Domain_v.3.smt2         |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__Domain_v.5.smt2         |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetreeRefinement_v.14.smt2  |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetreeRefinement_v.20.smt2  |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetreeRefinement_v.21.smt2  |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetreeRefinement_v.23.smt2  |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetreeRefinement_v.29.smt2  |   0.261s  |   0.261s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetreeRefinement_v.3.smt2  |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetreeRefinement_v.30.smt2  |   9.593s  |   9.593s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetreeRefinement_v.32.smt2  |   0.541s  |   0.541s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetreeRefinement_v.33.smt2  |   0.598s  |   0.598s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetreeRefinement_v.5.smt2  |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetreeRefinement_v.6.smt2  |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetreeRefinement_v.8.smt2  |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetreeRefinement_v.9.smt2  |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetree_v.19.smt2  |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetree_v.20.smt2  |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetree_v.21.smt2  |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetree_v.23.smt2  |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetree_v.26.smt2  |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetree_v.30.smt2  |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetree_v.32.smt2  |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetree_v.34.smt2  |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetree_v.35.smt2  |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetree_v.37.smt2  |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetree_v.38.smt2  |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetree_v.41.smt2  |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetree_v.6.smt2  |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetree_v.9.smt2  |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.10.smt2  |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.100.smt2  |   0.267s  |   0.267s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.105.smt2  |   0.425s  |   0.425s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.108.smt2  |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.11.smt2  |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.111.smt2  |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.112.smt2  |  20.142s  |  20.142s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.16.smt2  |   0.175s  |   0.175s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.18.smt2  |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.24.smt2  |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.26.smt2  |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.30.smt2  |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.32.smt2  |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.35.smt2  |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.39.smt2  |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.40.smt2  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.43.smt2  |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.44.smt2  |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.47.smt2  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.5.smt2   |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.52.smt2  |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.55.smt2  |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.57.smt2  |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.59.smt2  |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.6.smt2   |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.60.smt2  |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.62.smt2  |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.65.smt2  |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.70.smt2  |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.72.smt2  |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.74.smt2  |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.75.smt2  |   0.163s  |   0.163s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.76.smt2  |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.83.smt2  |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.86.smt2  |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.87.smt2  |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.89.smt2  |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.9.smt2   |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.90.smt2  |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v__LinkedBetreeVars.2.smt2  |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v__LinkedBetreeVars.5.smt2  |   0.695s  |   0.695s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v__LinkedBetreeVars.6.smt2  |   1.818s  |   1.818s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v__LinkedBetreeVars.8.smt2  |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.1.smt2   |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.12.smt2  |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.13.smt2  |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.16.smt2  |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.19.smt2  |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.20.smt2  |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.21.smt2  |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.23.smt2  |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.24.smt2  |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.27.smt2  |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.31.smt2  |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.35.smt2  |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.37.smt2  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.38.smt2  |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.39.smt2  |   0.368s  |   0.368s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.40.smt2  |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.44.smt2  |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.47.smt2  |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.5.smt2   |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.51.smt2  |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.52.smt2  |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.54.smt2  |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.57.smt2  |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.61.smt2  |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.62.smt2  |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.64.smt2  |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.8.smt2   |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v__Refinement_v.1.smt2  |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v__Refinement_v.13.smt2  |   0.350s  |   0.350s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v__Refinement_v.16.smt2  |   0.426s  |   0.426s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v__Refinement_v.21.smt2  |   0.406s  |   0.406s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v__Refinement_v.22.smt2  |   0.422s  |   0.422s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v__Refinement_v.23.smt2  |   0.479s  |   0.479s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v__Refinement_v.24.smt2  |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v__Refinement_v.29.smt2  |   0.405s  |   0.405s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v__Refinement_v.34.smt2  |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v__Refinement_v.35.smt2  |   1.114s  |   1.114s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v__Refinement_v.37.smt2  |   0.968s  |   0.968s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v__Refinement_v.9.smt2  |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedSeq_v.4.smt2      |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedSeq_v.6.smt2      |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedSeq_v.7.smt2      |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__Memtable_v.3.smt2       |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__Memtable_v.6.smt2       |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__Memtable_v.8.smt2       |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetreeRefinement_v.1.smt2  |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetreeRefinement_v.10.smt2  |   0.747s  |   0.747s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetreeRefinement_v.20.smt2  |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetreeRefinement_v.21.smt2  |   0.448s  |   0.448s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetreeRefinement_v.24.smt2  |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetreeRefinement_v.25.smt2  |   0.444s  |   0.444s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetreeRefinement_v.29.smt2  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetreeRefinement_v.34.smt2  |   0.442s  |   0.442s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetreeRefinement_v.4.smt2  |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetreeRefinement_v.6.smt2  |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetreeRefinement_v.7.smt2  |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetree_v.10.smt2   |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetree_v.11.smt2   |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetree_v.12.smt2   |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetree_v.16.smt2   |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetree_v.19.smt2   |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetree_v.2.smt2    |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetree_v.20.smt2   |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetree_v.21.smt2   |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetree_v.22.smt2   |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetree_v.26.smt2   |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetree_v.31.smt2   |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetree_v.32.smt2   |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetree_v.35.smt2   |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetree_v.7.smt2    |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetree_v.9.smt2    |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetreeRefinement_v.10.smt2  |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetreeRefinement_v.13.smt2  |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetreeRefinement_v.17.smt2  |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetreeRefinement_v.2.smt2  |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetreeRefinement_v.20.smt2  |   0.289s  |   0.289s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetreeRefinement_v.23.smt2  |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetreeRefinement_v.25.smt2  |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetreeRefinement_v.28.smt2  |  20.111s  |  20.111s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetreeRefinement_v.29.smt2  |  20.052s  |  20.052s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetree_v.1.smt2    |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetree_v.17.smt2   |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetree_v.20.smt2   |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetree_v.22.smt2   |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetree_v.26.smt2   |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetree_v.27.smt2   |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetree_v.31.smt2   |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetree_v.33.smt2   |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetree_v.34.smt2   |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetree_v.36.smt2   |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetree_v.4.smt2    |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetree_v.40.smt2   |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetree_v.43.smt2   |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetree_v.8.smt2    |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetree_v.9.smt2    |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBranchRefinement_v.11.smt2  |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBranchRefinement_v.17.smt2  |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBranchRefinement_v.18.smt2  |   0.241s  |   0.241s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBranchRefinement_v.21.smt2  |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBranchRefinement_v.4.smt2  |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBranchRefinement_v.7.smt2  |   1.282s  |   1.282s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBranchRefinement_v.9.smt2  |   0.820s  |   0.820s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBranch_v.1.smt2    |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBranch_v.16.smt2   |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBranch_v.21.smt2   |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBranch_v.25.smt2   |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBranch_v.30.smt2   |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBranch_v.31.smt2   |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBranch_v.32.smt2   |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBranch_v.5.smt2    |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBranch_v.7.smt2    |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotTable_v.10.smt2    |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotTable_v.7.smt2     |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotTable_v.8.smt2     |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__SplitRequest_v.smt2     |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__Utils_v.1.smt2          |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__Utils_v.3.smt2          |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-disk__GenericDisk_v.8.smt2      |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-exec__Cache_v.1.smt2            |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-exec__Cache_v__Cache.2.smt2     |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-exec__Cache_v__Cache.4.smt2     |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-exec__MiniAllocator_v.1.smt2    |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-exec__MiniAllocator_v.11.smt2   |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-exec__MiniAllocator_v.2.smt2    |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-exec__MiniAllocator_v.3.smt2    |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournalRefinement_v.16.smt2  |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournalRefinement_v.19.smt2  |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournalRefinement_v.2.smt2  |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournalRefinement_v.21.smt2  |   0.215s  |   0.215s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournalRefinement_v.23.smt2  |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournalRefinement_v.27.smt2  |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournalRefinement_v.29.smt2  |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournalRefinement_v.5.smt2  |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournalRefinement_v.9.smt2  |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.10.smt2  |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.11.smt2  |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.12.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.15.smt2  |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.19.smt2  |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.20.smt2  |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.21.smt2  |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.29.smt2  |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.3.smt2  |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.34.smt2  |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.37.smt2  |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.4.smt2  |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.40.smt2  |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.42.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.50.smt2  |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.51.smt2  |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.9.smt2  |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v__LinkedJournal.11.smt2  |   0.330s  |   0.330s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v__LinkedJournal.2.smt2  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournalRefinement_v.1.smt2  |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournalRefinement_v.10.smt2  |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournalRefinement_v.11.smt2  |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournalRefinement_v.12.smt2  |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournalRefinement_v.15.smt2  |   0.324s  |   0.324s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournalRefinement_v.16.smt2  |   0.465s  |   0.465s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournalRefinement_v.17.smt2  |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournalRefinement_v.19.smt2  |   0.234s  |   0.234s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournalRefinement_v.2.smt2  |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournalRefinement_v.22.smt2  |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournalRefinement_v.24.smt2  |   0.393s  |   0.393s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournalRefinement_v.25.smt2  |   0.420s  |   0.420s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournalRefinement_v.4.smt2  |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournalRefinement_v.6.smt2  |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournalRefinement_v.9.smt2  |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournal_v.12.smt2  |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournal_v.13.smt2  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournal_v.14.smt2  |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournal_v.15.smt2  |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournal_v.16.smt2  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournal_v.18.smt2  |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournal_v.19.smt2  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournal_v.2.smt2  |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournal_v.20.smt2  |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournal_v.21.smt2  |   0.171s  |   0.171s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournal_v.27.smt2  |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournal_v.29.smt2  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournal_v.3.smt2  |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournal_v.4.smt2  |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournal_v.6.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.16.smt2  |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.18.smt2  |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.19.smt2  |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.22.smt2  |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.24.smt2  |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.25.smt2  |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.27.smt2  |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.29.smt2  |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.3.smt2  |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.30.smt2  |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.31.smt2  |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.35.smt2  |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.38.smt2  |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.49.smt2  |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.5.smt2  |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.51.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.6.smt2  |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.8.smt2  |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.9.smt2  |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__Slice_v.1.smt2     |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__Slice_v.5.smt2     |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-spec__AppIO_t.1.smt2            |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__reconciler.1.smt2  |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__reconciler.3.smt2  |   2.239s  |   2.239s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__reconciler.5.smt2  |   0.390s  |   0.390s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__reconciler.7.smt2  |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__reconciler.8.smt2  |   0.231s  |   0.231s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__reconciler.9.smt2  |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__common.2.smt2  |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__config_map.1.smt2  |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__config_map.4.smt2  |   0.704s  |   0.704s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__config_map.6.smt2  |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__config_map.8.smt2  |   0.319s  |   0.319s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__default_user_secret.4.smt2  |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__default_user_secret.6.smt2  |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__default_user_secret.7.smt2  |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__erlang_cookie.1.smt2  |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__erlang_cookie.2.smt2  |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__erlang_cookie.5.smt2  |   0.404s  |   0.404s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__erlang_cookie.7.smt2  |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__headless_service.2.smt2  |   0.413s  |   0.413s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__headless_service.3.smt2  |   0.863s  |   0.863s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__headless_service.5.smt2  |   0.389s  |   0.389s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__headless_service.6.smt2  |   0.508s  |   0.508s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__headless_service.7.smt2  |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__headless_service.8.smt2  |   0.400s  |   0.400s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__rabbitmq_plugins.2.smt2  |   0.296s  |   0.296s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__rabbitmq_plugins.5.smt2  |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__rabbitmq_plugins.7.smt2  |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__rabbitmq_plugins.8.smt2  |   0.315s  |   0.315s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__role.2.smt2  |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__role.4.smt2  |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__role.7.smt2  |   0.388s  |   0.388s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__role_binding.10.smt2  |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__role_binding.6.smt2  |   0.320s  |   0.320s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__role_binding.9.smt2  |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__service.2.smt2  |   0.264s  |   0.264s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__service.6.smt2  |   0.328s  |   0.328s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__service.7.smt2  |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__service_account.1.smt2  |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__service_account.6.smt2  |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__stateful_set.10.smt2  |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__helper_invariants__proof.10.smt2  |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__helper_invariants__proof.12.smt2  |  20.064s  |  20.064s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__helper_invariants__proof.13.smt2  |   0.421s  |   0.421s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__helper_invariants__proof.4.smt2  |  20.101s  |  20.101s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__helper_invariants__proof.7.smt2  |   0.424s  |   0.424s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__helper_invariants__proof__lemma_always_cm_rv_stays_unchanged.smt2  |  20.096s  |  20.096s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__helper_invariants__proof__lemma_eventually_always_every_resource_create_request_implies_at_after_create_resource_step.smt2  |  20.049s  |  20.049s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__helper_invariants__proof__lemma_eventually_always_every_resource_update_request_implies_at_after_update_resource_step.smt2  |  20.093s  |  20.093s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__helper_invariants__proof__lemma_resource_update_request_msg_implies_key_in_reconcile_equals.smt2  |  20.119s  |  20.119s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__helper_invariants__unchangeable.3.smt2  |  20.077s  |  20.077s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__helper_invariants__validation__lemma_always_object_in_resource_update_request_msg_has_smaller_rv_than_etcd.smt2  |  20.064s  |  20.064s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__liveness__proof.1.smt2  |  20.063s  |  20.063s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__liveness__proof.4.smt2  |   0.801s  |   0.801s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__liveness__proof.6.smt2  |  20.060s  |  20.060s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__liveness__proof.7.smt2  |  13.457s  |  13.457s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__liveness__proof.9.smt2  |   0.621s  |   0.621s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__liveness__resource_match.7.smt2  |  20.082s  |  20.082s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__liveness__spec.10.smt2  |   0.461s  |   0.461s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__liveness__spec.13.smt2  |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__liveness__spec.15.smt2  |  11.279s  |  11.279s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__liveness__spec.4.smt2  |   0.376s  |   0.376s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__liveness__stateful_set_match.1.smt2  |  20.108s  |  20.108s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__liveness__stateful_set_match.2.smt2  |   0.741s  |   0.741s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__liveness__stateful_set_match__lemma_from_key_exists_to_receives_ok_resp_at_after_get_stateful_set_step.smt2  |  20.087s  |  20.087s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__trusted__spec_types.3.smt2  |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__trusted__spec_types.4.smt2  |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__trusted__spec_types.6.smt2  |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__reconciler.1.smt2  |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__reconciler.11.smt2  |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__reconciler.12.smt2  |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__reconciler.16.smt2  |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__reconciler.19.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__reconciler.2.smt2  |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__reconciler.3.smt2  |   1.717s  |   1.717s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__reconciler.6.smt2  |   0.301s  |   0.301s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__reconciler.7.smt2  |   0.292s  |   0.292s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__admin_server_service.1.smt2  |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__admin_server_service.5.smt2  |   0.285s  |   0.285s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__client_service.1.smt2  |   0.225s  |   0.225s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__client_service.3.smt2  |   0.404s  |   0.404s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__client_service.6.smt2  |   0.301s  |   0.301s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__client_service.7.smt2  |   0.298s  |   0.298s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__client_service.8.smt2  |   0.240s  |   0.240s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__common.1.smt2  |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__common.3.smt2  |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__common.4.smt2  |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__config_map.1.smt2  |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__config_map.2.smt2  |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__config_map.4.smt2  |   0.191s  |   0.191s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__config_map.5.smt2  |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__config_map.7.smt2  |   0.241s  |   0.241s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__config_map.8.smt2  |   0.284s  |   0.284s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__headless_service.4.smt2  |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__headless_service.6.smt2  |   0.273s  |   0.273s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__headless_service.7.smt2  |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__stateful_set.1.smt2  |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__stateful_set.2.smt2  |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__stateful_set.4.smt2  |   2.707s  |   2.707s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__stateful_set.8.smt2  |   0.226s  |   0.226s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__proof.11.smt2  |   0.422s  |   0.422s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__proof.14.smt2  |   0.528s  |   0.528s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__proof.2.smt2  |  20.074s  |  20.074s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__proof.7.smt2  |   0.437s  |   0.437s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__proof.8.smt2  |   0.675s  |   0.675s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__proof.9.smt2  |   0.697s  |   0.697s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__proof__lemma_always_no_update_status_request_msg_in_flight_of_except_stateful_set.smt2  |  20.085s  |  20.085s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__proof__lemma_always_no_update_status_request_msg_not_from_bc_in_flight_of_stateful_set.smt2  |  20.094s  |  20.094s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__proof__lemma_eventually_always_every_resource_create_request_implies_at_after_create_resource_step.smt2  |  20.130s  |  20.130s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__proof__lemma_eventually_always_every_resource_update_request_implies_at_after_update_resource_step.smt2  |  20.123s  |  20.123s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__proof__lemma_eventually_always_no_delete_resource_request_msg_in_flight.smt2  |  20.123s  |  20.123s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__proof__lemma_eventually_always_object_in_response_at_after_update_resource_step_is_same_as_etcd.smt2  |  20.109s  |  20.109s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__proof__lemma_resource_create_or_update_request_msg_implies_key_in_reconcile_equals.smt2  |  20.102s  |  20.102s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__unchangeable.3.smt2  |  20.119s  |  20.119s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__unchangeable.5.smt2  |  20.086s  |  20.086s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__zookeeper_api__lemma_eventually_always_every_zk_create_node_request_implies_at_after_create_zk_node_step.smt2  |  20.120s  |  20.120s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__zookeeper_api__lemma_zk_request_implies_step_helper.smt2  |  20.062s  |  20.062s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__proof.1.smt2  |  20.094s  |  20.094s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__proof.11.smt2  |   0.487s  |   0.487s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__proof.5.smt2  |  20.090s  |  20.090s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__proof.6.smt2  |  20.162s  |  20.162s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__proof.7.smt2  |  11.740s  |  11.740s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__proof.9.smt2  |   0.477s  |   0.477s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__resource_match.1.smt2  |  20.109s  |  20.109s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__resource_match.2.smt2  |  20.090s  |  20.090s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__resource_match.4.smt2  |  20.042s  |  20.042s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__resource_match.5.smt2  |  20.065s  |  20.065s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__resource_match.7.smt2  |  20.097s  |  20.097s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__resource_match.8.smt2  |  20.034s  |  20.034s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__resource_match.9.smt2  |   0.947s  |   0.947s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__spec.1.smt2  |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__spec.10.smt2  |   0.410s  |   0.410s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__spec.11.smt2  |   0.419s  |   0.419s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__spec.15.smt2  |   2.097s  |   2.097s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__spec.18.smt2  |   2.123s  |   2.123s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__stateful_set_match.5.smt2  |   0.822s  |   0.822s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__terminate.1.smt2  |  20.118s  |  20.118s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__terminate.2.smt2  |  20.096s  |  20.096s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__zookeeper_api.1.smt2  |  20.148s  |  20.148s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__zookeeper_api.12.smt2  |  20.096s  |  20.096s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__zookeeper_api.15.smt2  |  20.122s  |  20.122s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__zookeeper_api.16.smt2  |  20.094s  |  20.094s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__trusted__spec_types.1.smt2  |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__trusted__spec_types.3.smt2  |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__trusted__spec_types.5.smt2  |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__trusted__spec_types.6.smt2  |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/array.2.smt2                              |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/array.5.smt2                              |   0.268s  |   0.268s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/array.7.smt2                              |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/array_set.3.smt2                          |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/array_set.4.smt2                          |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/array_set.7.smt2                          |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/array_vec.2.smt2                          |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/array_vec.6.smt2                          |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/define.1.smt2                             |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/define.3.smt2                             |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/define.5.smt2                             |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/pagetable__entry.1.smt2                   |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/pagetable__entry.4.smt2                   |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/pagetable__entry.8.smt2                   |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/pagetable__pagemap.4.smt2                 |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/pagetable__pagemap.5.smt2                 |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/pagetable__pagemap_util_t.1.smt2          |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/process_manager__container_tree_spec_impl.10.smt2  |   0.336s  |   0.336s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/process_manager__container_tree_spec_impl.12.smt2  |   0.950s  |   0.950s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/process_manager__container_tree_spec_impl.14.smt2  |   1.149s  |   1.149s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/process_manager__container_tree_spec_impl.16.smt2  |   0.980s  |   0.980s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/process_manager__container_tree_spec_impl.4.smt2  |   0.322s  |   0.322s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/process_manager__container_tree_spec_impl.6.smt2  |   0.333s  |   0.333s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/process_manager__container_tree_spec_impl.7.smt2  |   0.239s  |   0.239s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/process_manager__endpoint_util_t.smt2     |   0.263s  |   0.263s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/process_manager__thread.2.smt2            |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/process_manager__thread.3.smt2            |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/slinkedlist__spec_impl_u.1.smt2           |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/slinkedlist__spec_impl_u.6.smt2           |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/trap.1.smt2                               |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/trap.2.smt2                               |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/trap.6.smt2                               |   0.219s  |   0.219s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/atmosphere/trap.9.smt2                               |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__AbstractCrashAwareSystemRefinement_v.11.smt2  |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__AbstractCrashAwareSystemRefinement_v.13.smt2  |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__AbstractCrashAwareSystemRefinement_v.15.smt2  |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__AbstractCrashAwareSystemRefinement_v.17.smt2  |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__AbstractCrashAwareSystemRefinement_v.19.smt2  |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__AbstractCrashAwareSystemRefinement_v.21.smt2  |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__AbstractCrashAwareSystemRefinement_v.22.smt2  |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__AbstractCrashAwareSystemRefinement_v.23.smt2  |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__AbstractCrashAwareSystemRefinement_v.29.smt2  |   0.297s  |   0.297s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__AbstractCrashAwareSystemRefinement_v.3.smt2  |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__AbstractCrashAwareSystemRefinement_v.4.smt2  |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__AbstractCrashAwareSystemRefinement_v.6.smt2  |   0.238s  |   0.238s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__AbstractCrashAwareSystemRefinement_v.8.smt2  |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__AbstractJournal_v__AbstractJournal.1.smt2  |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__AbstractJournal_v__AbstractJournal.2.smt2  |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__MsgHistory_v.1.smt2      |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__MsgHistory_v.10.smt2     |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__MsgHistory_v.13.smt2     |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__MsgHistory_v.16.smt2     |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__MsgHistory_v.2.smt2      |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__MsgHistory_v.20.smt2     |   0.145s  |   0.145s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__MsgHistory_v.21.smt2     |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__MsgHistory_v.22.smt2     |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__MsgHistory_v.25.smt2     |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__MsgHistory_v.26.smt2     |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__MsgHistory_v.29.smt2     |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__MsgHistory_v.4.smt2      |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__MsgHistory_v.5.smt2      |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__MsgHistory_v.9.smt2      |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__StampedMap_v.3.smt2      |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__StampedMap_v.4.smt2      |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationCrashAwareJournalRefinement_v.1.smt2  |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationCrashAwareJournalRefinement_v.4.smt2  |   0.427s  |   0.427s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationCrashAwareJournal_v.1.smt2  |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationCrashAwareJournal_v__AllocationCrashAwareJournal.2.smt2  |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationCrashAwareJournal_v__AllocationCrashAwareJournal.3.smt2  |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationCrashAwareJournal_v__AllocationCrashAwareJournal.6.smt2  |   0.269s  |   0.269s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationCrashAwareJournal_v__AllocationCrashAwareJournal.9.smt2  |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournalRefinement_v.3.smt2  |   0.299s  |   0.299s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.10.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.12.smt2  |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.14.smt2  |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.18.smt2  |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.2.smt2  |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.20.smt2  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.21.smt2  |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.22.smt2  |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.23.smt2  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.26.smt2  |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.27.smt2  |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.3.smt2  |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.33.smt2  |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.34.smt2  |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.36.smt2  |   0.480s  |   0.480s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.38.smt2  |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.41.smt2  |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.42.smt2  |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.43.smt2  |  20.160s  |  20.160s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.47.smt2  |   0.442s  |   0.442s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.6.smt2  |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.7.smt2  |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.8.smt2  |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.9.smt2  |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v__AllocationJournal.11.smt2  |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v__AllocationJournal.4.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v__AllocationJournal.6.smt2  |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v__AllocationJournal.7.smt2  |   0.212s  |   0.212s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v__AllocationJournal.8.smt2  |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesBetree_v.12.smt2   |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesBetree_v.13.smt2   |   0.632s  |   0.632s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesBetree_v.14.smt2   |   0.324s  |   0.324s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesBetree_v.6.smt2    |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesBetree_v__LikesBetree.2.smt2  |   8.797s  |   8.797s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesBetree_v__LikesBetree.4.smt2  |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesBetree_v__LikesBetree.5.smt2  |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesBetree_v__LikesBetree.6.smt2  |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesBetree_v__LikesBetree.7.smt2  |   0.270s  |   0.270s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournalRefinement_v.2.smt2  |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournalRefinement_v.3.smt2  |   0.674s  |   0.674s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournalRefinement_v.4.smt2  |   0.605s  |   0.605s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v.12.smt2  |   0.272s  |   0.272s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v.13.smt2  |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v.16.smt2  |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v.17.smt2  |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v.18.smt2  |   0.285s  |   0.285s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v.2.smt2   |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v.21.smt2  |   0.218s  |   0.218s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v.24.smt2  |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v.27.smt2  |   0.300s  |   0.300s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v.30.smt2  |   0.442s  |   0.442s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v.7.smt2   |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v.8.smt2   |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v__LikesJournal.1.smt2  |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v__LikesJournal.10.smt2  |   0.341s  |   0.341s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v__LikesJournal.2.smt2  |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v__LikesJournal.5.smt2  |   0.337s  |   0.337s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v__LikesJournal.8.smt2  |   0.409s  |   0.409s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__MiniAllocator_v.11.smt2  |   0.143s  |   0.143s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__MiniAllocator_v.16.smt2  |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__MiniAllocator_v.20.smt2  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__MiniAllocator_v.21.smt2  |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__MiniAllocator_v.3.smt2  |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__MiniAllocator_v.5.smt2  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__MiniAllocator_v.8.smt2  |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__MiniAllocator_v.9.smt2  |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__UnifiedCrashAwareJournalRefinement_v.3.smt2  |   0.303s  |   0.303s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__UnifiedCrashAwareJournalRefinement_v.7.smt2  |   6.362s  |   6.362s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__UnifiedCrashAwareJournalRefinement_v.8.smt2  |   9.930s  |   9.930s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__UnifiedCrashAwareJournal_v.10.smt2  |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__UnifiedCrashAwareJournal_v.14.smt2  |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__UnifiedCrashAwareJournal_v.3.smt2  |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__UnifiedCrashAwareJournal_v.4.smt2  |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__UnifiedCrashAwareJournal_v__UnifiedCrashAwareJournal.11.smt2  |   0.253s  |   0.253s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__UnifiedCrashAwareJournal_v__UnifiedCrashAwareJournal.7.smt2  |   6.676s  |   6.676s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferDisk_v.10.smt2              |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferDisk_v.12.smt2              |   0.144s  |   0.144s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferDisk_v.14.smt2              |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferDisk_v.2.smt2               |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferDisk_v.3.smt2               |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferDisk_v.4.smt2               |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferDisk_v.7.smt2               |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferDisk_v.8.smt2               |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferOffsets_v.3.smt2            |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferOffsets_v.5.smt2            |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferOffsets_v.6.smt2            |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferSeq_v.1.smt2                |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferSeq_v.12.smt2               |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferSeq_v.16.smt2               |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferSeq_v.20.smt2               |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferSeq_v.21.smt2               |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferSeq_v.5.smt2                |   0.174s  |   0.174s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferSeq_v.6.smt2                |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferSeq_v.7.smt2                |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__Buffer_v.10.smt2                  |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__Buffer_v.13.smt2                  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__Buffer_v.15.smt2                  |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__Buffer_v.16.smt2                  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__Buffer_v.3.smt2                   |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__Buffer_v.4.smt2                   |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__Buffer_v.7.smt2                   |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__Buffer_v.9.smt2                   |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__Domain_v.4.smt2                   |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__Domain_v.5.smt2                   |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetreeRefinement_v.11.smt2  |   0.259s  |   0.259s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetreeRefinement_v.14.smt2  |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetreeRefinement_v.15.smt2  |   0.303s  |   0.303s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetreeRefinement_v.19.smt2  |   0.187s  |   0.187s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetreeRefinement_v.21.smt2  |   0.223s  |   0.223s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetreeRefinement_v.22.smt2  |   0.330s  |   0.330s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetreeRefinement_v.25.smt2  |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetreeRefinement_v.5.smt2  |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetreeRefinement_v.6.smt2  |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetreeRefinement_v.9.smt2  |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.1.smt2           |   0.132s  |   0.132s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.13.smt2          |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.15.smt2          |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.16.smt2          |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.17.smt2          |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.19.smt2          |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.2.smt2           |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.22.smt2          |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.23.smt2          |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.29.smt2          |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.3.smt2           |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.30.smt2          |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.32.smt2          |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.37.smt2          |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.41.smt2          |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.7.smt2           |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.9.smt2           |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v__FilteredBetree.smt2  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.1.smt2             |   0.156s  |   0.156s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.102.smt2           |   0.317s  |   0.317s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.105.smt2           |   0.343s  |   0.343s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.107.smt2           |   0.372s  |   0.372s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.108.smt2           |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.109.smt2           |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.111.smt2           |   0.427s  |   0.427s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.15.smt2            |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.17.smt2            |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.19.smt2            |   0.140s  |   0.140s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.20.smt2            |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.21.smt2            |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.24.smt2            |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.25.smt2            |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.31.smt2            |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.33.smt2            |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.38.smt2            |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.40.smt2            |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.41.smt2            |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.42.smt2            |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.43.smt2            |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.44.smt2            |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.45.smt2            |   0.230s  |   0.230s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.56.smt2            |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.59.smt2            |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.6.smt2             |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.67.smt2            |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.68.smt2            |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.72.smt2            |   0.258s  |   0.258s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.75.smt2            |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.76.smt2            |   0.168s  |   0.168s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.81.smt2            |   0.267s  |   0.267s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.82.smt2            |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.83.smt2            |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.85.smt2            |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.86.smt2            |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.89.smt2            |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.93.smt2            |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.94.smt2            |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.96.smt2            |   0.399s  |   0.399s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v__LinkedBetreeVars.2.smt2  |   0.339s  |   0.339s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v__LinkedBetreeVars.3.smt2  |   0.653s  |   0.653s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v__LinkedBetreeVars.6.smt2  |   1.043s  |   1.043s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v__LinkedBetreeVars.7.smt2  |   0.412s  |   0.412s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.10.smt2            |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.14.smt2            |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.16.smt2            |   0.182s  |   0.182s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.2.smt2             |   0.051s  |   0.051s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.23.smt2            |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.27.smt2            |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.28.smt2            |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.29.smt2            |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.3.smt2             |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.30.smt2            |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.32.smt2            |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.38.smt2            |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.39.smt2            |   0.327s  |   0.327s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.44.smt2            |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.48.smt2            |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.50.smt2            |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.58.smt2            |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.62.smt2            |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.67.smt2            |   0.131s  |   0.131s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.9.smt2             |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v__Refinement_v.1.smt2  |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v__Refinement_v.14.smt2  |   0.300s  |   0.300s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v__Refinement_v.18.smt2  |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v__Refinement_v.2.smt2  |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v__Refinement_v.22.smt2  |   0.406s  |   0.406s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v__Refinement_v.26.smt2  |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v__Refinement_v.3.smt2  |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v__Refinement_v.31.smt2  |   0.345s  |   0.345s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v__Refinement_v.32.smt2  |   1.003s  |   1.003s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v__Refinement_v.34.smt2  |   0.237s  |   0.237s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedSeq_v.3.smt2                |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__Memtable_v.12.smt2                |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__Memtable_v.5.smt2                 |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__Memtable_v.7.smt2                 |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__OffsetMap_v.2.smt2                |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__OffsetMap_v.4.smt2                |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetreeRefinement_v.12.smt2   |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetreeRefinement_v.17.smt2   |   0.248s  |   0.248s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetreeRefinement_v.19.smt2   |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetreeRefinement_v.25.smt2   |   0.436s  |   0.436s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetreeRefinement_v.3.smt2    |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetreeRefinement_v.30.smt2   |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetreeRefinement_v.35.smt2   |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetree_v.1.smt2              |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetree_v.10.smt2             |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetree_v.12.smt2             |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetree_v.13.smt2             |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetree_v.18.smt2             |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetree_v.19.smt2             |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetree_v.2.smt2              |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetree_v.22.smt2             |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetree_v.23.smt2             |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetree_v.24.smt2             |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetree_v.7.smt2              |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetreeRefinement_v.10.smt2   |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetreeRefinement_v.12.smt2   |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetreeRefinement_v.17.smt2   |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetreeRefinement_v.18.smt2   |   0.327s  |   0.327s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetreeRefinement_v.2.smt2    |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetreeRefinement_v.25.smt2   |   0.179s  |   0.179s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetreeRefinement_v.28.smt2   |  20.126s  |  20.126s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetreeRefinement_v.4.smt2    |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetreeRefinement_v.6.smt2    |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetreeRefinement_v.7.smt2    |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetreeRefinement_v.9.smt2    |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetree_v.12.smt2             |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetree_v.14.smt2             |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetree_v.16.smt2             |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetree_v.24.smt2             |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetree_v.29.smt2             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetree_v.32.smt2             |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetree_v.33.smt2             |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetree_v.38.smt2             |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetree_v.40.smt2             |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetree_v.42.smt2             |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetree_v.43.smt2             |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetree_v__PivotBetree.smt2   |   0.262s  |   0.262s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBranchRefinement_v.10.smt2   |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBranchRefinement_v.16.smt2   |   0.800s  |   0.800s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBranchRefinement_v.18.smt2   |   0.232s  |   0.232s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBranchRefinement_v.19.smt2   |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBranchRefinement_v.21.smt2   |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBranchRefinement_v.22.smt2   |   1.214s  |   1.214s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBranchRefinement_v.8.smt2    |   0.232s  |   0.232s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBranchRefinement_v.9.smt2    |   0.620s  |   0.620s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBranch_v.1.smt2              |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBranch_v.11.smt2             |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBranch_v.12.smt2             |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBranch_v.26.smt2             |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBranch_v.30.smt2             |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBranch_v.6.smt2              |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotTable_v.5.smt2               |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotTable_v.9.smt2               |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__Utils_v.5.smt2                    |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/disk__GenericDisk_v.10.smt2               |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/disk__GenericDisk_v.5.smt2                |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/disk__GenericDisk_v.6.smt2                |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/exec__Cache_v__Cache.1.smt2               |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/exec__Cache_v__Cache.10.smt2              |   0.177s  |   0.177s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/exec__Cache_v__Cache.5.smt2               |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/exec__Cache_v__Cache.6.smt2               |  20.098s  |  20.098s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/exec__Cache_v__Cache.9.smt2               |   0.189s  |   0.189s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/exec__MiniAllocator_v.11.smt2             |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/exec__MiniAllocator_v.12.smt2             |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/exec__MiniAllocator_v.6.smt2              |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournalRefinement_v.12.smt2  |   0.222s  |   0.222s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournalRefinement_v.16.smt2  |   0.276s  |   0.276s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournalRefinement_v.17.smt2  |   0.254s  |   0.254s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournalRefinement_v.18.smt2  |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournalRefinement_v.2.smt2  |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournalRefinement_v.24.smt2  |   0.375s  |   0.375s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournalRefinement_v.28.smt2  |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournalRefinement_v.30.smt2  |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournalRefinement_v.8.smt2  |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.1.smt2           |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.10.smt2          |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.11.smt2          |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.12.smt2          |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.17.smt2          |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.19.smt2          |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.2.smt2           |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.24.smt2          |   0.252s  |   0.252s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.25.smt2          |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.27.smt2          |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.37.smt2          |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.4.smt2           |   0.105s  |   0.105s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.42.smt2          |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.47.smt2          |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.48.smt2          |   0.134s  |   0.134s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.49.smt2          |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.55.smt2          |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.7.smt2           |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.8.smt2           |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v__LinkedJournal.2.smt2  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v__LinkedJournal.4.smt2  |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournalRefinement_v.11.smt2  |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournalRefinement_v.18.smt2  |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournalRefinement_v.19.smt2  |   0.324s  |   0.324s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournalRefinement_v.2.smt2  |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournalRefinement_v.21.smt2  |   0.232s  |   0.232s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournalRefinement_v.22.smt2  |   0.133s  |   0.133s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournalRefinement_v.25.smt2  |   0.397s  |   0.397s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournalRefinement_v.5.smt2  |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournalRefinement_v.7.smt2  |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournal_v.1.smt2            |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournal_v.11.smt2           |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournal_v.12.smt2           |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournal_v.15.smt2           |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournal_v.2.smt2            |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournal_v.27.smt2           |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournal_v.28.smt2           |   0.185s  |   0.185s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournal_v.3.smt2            |   0.167s  |   0.167s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournal_v.31.smt2           |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournal_v.32.smt2           |   0.138s  |   0.138s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournal_v.33.smt2           |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournal_v.8.smt2            |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournal_v__PagedJournal.3.smt2  |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.11.smt2  |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.14.smt2  |   0.204s  |   0.204s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.15.smt2  |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.21.smt2  |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.23.smt2  |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.25.smt2  |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.26.smt2  |   0.155s  |   0.155s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.29.smt2  |   0.214s  |   0.214s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.3.smt2  |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.30.smt2  |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.31.smt2  |   0.108s  |   0.108s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.32.smt2  |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.39.smt2  |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.40.smt2  |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.41.smt2  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.48.smt2  |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.53.smt2  |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.55.smt2  |   0.125s  |   0.125s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.6.smt2  |   0.161s  |   0.161s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.8.smt2  |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.9.smt2  |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__SeqMarshalling_v.1.smt2      |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__SeqMarshalling_v.3.smt2      |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/splinterdb/spec__AppIO_t.3.smt2                      |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-args_t.2.smt2                     |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-cmessage_v.10.smt2                |   0.124s  |   0.124s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-cmessage_v.17.smt2                |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-cmessage_v.2.smt2                 |   0.629s  |   0.629s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-cmessage_v.5.smt2                 |   0.800s  |   0.800s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.1.smt2           |   0.118s  |   0.118s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.11.smt2          |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.12.smt2          |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.2.smt2           |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.24.smt2          |   0.136s  |   0.136s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.28.smt2          |   0.154s  |   0.154s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.31.smt2          |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.32.smt2          |   0.235s  |   0.235s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.34.smt2          |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.37.smt2          |   0.622s  |   0.622s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.38.smt2          |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.4.smt2           |   0.255s  |   0.255s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.41.smt2          |   1.395s  |   1.395s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.42.smt2          |   0.158s  |   0.158s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.43.smt2          |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.44.smt2          |   0.247s  |   0.247s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.48.smt2          |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.52.smt2          |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.53.smt2          |  20.100s  |  20.100s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.54.smt2          |   0.244s  |   0.244s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.7.smt2           |   0.205s  |   0.205s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-endpoint_hashmap_t.smt2           |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_impl_t.1.smt2                |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_impl_v.1.smt2                |   0.165s  |   0.165s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_impl_v.10.smt2               |   0.567s  |   0.567s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_impl_v.4.smt2                |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_protocol_t.11.smt2           |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_protocol_t.13.smt2           |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_protocol_t.17.smt2           |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_protocol_t.18.smt2           |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_protocol_t.20.smt2           |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_protocol_t.22.smt2           |   0.129s  |   0.129s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_protocol_t.25.smt2           |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_protocol_t.27.smt2           |   0.159s  |   0.159s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_protocol_t.3.smt2            |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_protocol_t.30.smt2           |   0.074s  |   0.074s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_protocol_t.31.smt2           |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_protocol_t.6.smt2            |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_protocol_t.7.smt2            |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_protocol_t.8.smt2            |   0.135s  |   0.135s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-io_t.4.smt2                       |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-keys_t.3.smt2                     |   0.217s  |   0.217s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-keys_t.5.smt2                     |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-keys_t.6.smt2                     |   0.188s  |   0.188s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-keys_t.7.smt2                     |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_ironsht_specific_v.18.smt2  |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_ironsht_specific_v.19.smt2  |   0.114s  |   0.114s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_ironsht_specific_v.2.smt2  |   0.192s  |   0.192s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_ironsht_specific_v.3.smt2  |   0.198s  |   0.198s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_ironsht_specific_v.32.smt2  |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_ironsht_specific_v.33.smt2  |   0.207s  |   0.207s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_ironsht_specific_v.36.smt2  |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_ironsht_specific_v.39.smt2  |   0.130s  |   0.130s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_ironsht_specific_v.45.smt2  |   0.274s  |   0.274s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_ironsht_specific_v.46.smt2  |  17.559s  |  17.559s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_ironsht_specific_v.8.smt2  |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_ironsht_specific_v.9.smt2  |   0.208s  |   0.208s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.1.smt2                  |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.10.smt2                 |   0.287s  |   0.287s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.11.smt2                 |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.13.smt2                 |   0.329s  |   0.329s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.19.smt2                 |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.23.smt2                 |   0.151s  |   0.151s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.29.smt2                 |   0.148s  |   0.148s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.31.smt2                 |   0.229s  |   0.229s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.32.smt2                 |   0.433s  |   0.433s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.34.smt2                 |   0.509s  |   0.509s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.35.smt2                 |   0.139s  |   0.139s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.36.smt2                 |   0.274s  |   0.274s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.37.smt2                 |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.42.smt2                 |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.44.smt2                 |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.45.smt2                 |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.46.smt2                 |   0.199s  |   0.199s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.47.smt2                 |   0.193s  |   0.193s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.48.smt2                 |   0.209s  |   0.209s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.5.smt2                  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.52.smt2                 |   0.280s  |   0.280s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.6.smt2                  |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.7.smt2                  |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-seq_is_unique_v.11.smt2           |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-seq_is_unique_v.2.smt2            |   0.141s  |   0.141s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-seq_is_unique_v.5.smt2            |   0.224s  |   0.224s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-seq_is_unique_v.6.smt2            |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-seq_is_unique_v.7.smt2            |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-single_delivery_model_v.1.smt2    |   0.669s  |   0.669s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-single_delivery_model_v.2.smt2    |   0.328s  |   0.328s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-single_delivery_model_v.3.smt2    |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-single_delivery_model_v.7.smt2    |   1.686s  |   1.686s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-single_delivery_state_v.15.smt2   |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-single_delivery_state_v.5.smt2    |   0.249s  |   0.249s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-single_delivery_state_v.8.smt2    |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-single_delivery_state_v.9.smt2    |   0.245s  |   0.245s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-single_delivery_t.1.smt2          |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-single_delivery_t.10.smt2         |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-single_delivery_t.9.smt2          |   0.112s  |   0.112s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-verus_extra__seq_lib_v.1.smt2     |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-verus_extra__seq_lib_v.10.smt2    |   0.210s  |   0.210s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-verus_extra__seq_lib_v.7.smt2     |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-verus_extra__seq_lib_v.8.smt2     |   0.162s  |   0.162s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-verus_extra__set_lib_ext_v.14.smt2  |   0.121s  |   0.121s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-verus_extra__set_lib_ext_v.18.smt2  |   0.115s  |   0.115s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-verus_extra__set_lib_ext_v.19.smt2  |   0.178s  |   0.178s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-verus_extra__set_lib_ext_v.21.smt2  |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-verus_extra__set_lib_ext_v.23.smt2  |   0.203s  |   0.203s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-verus_extra__set_lib_ext_v.24.smt2  |   0.277s  |   0.277s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-verus_extra__set_lib_ext_v.4.smt2  |   0.228s  |   0.228s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-verus_extra__set_lib_ext_v.7.smt2  |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-verus_extra__set_lib_ext_v.8.smt2  |   0.183s  |   0.183s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/mimalloc-smt-config.2.smt2                   |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/mimalloc-smt-config.4.smt2                   |   0.103s  |   0.103s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/mimalloc-smt-flags.5.smt2                    |   0.194s  |   0.194s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/mimalloc-smt-flags.6.smt2                    |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/mimalloc-smt-flags.8.smt2                    |   0.186s  |   0.186s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/mimalloc-smt-linked_list__StuffAgree.1.smt2  |   0.127s  |   0.127s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/mimalloc-smt-pigeonhole.1.smt2               |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/mimalloc-smt-pigeonhole.2.smt2               |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/mimalloc-smt-pigeonhole.6.smt2               |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/mimalloc-smt-tokens.1.smt2                   |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/mimalloc-smt-types__BoolAgree.2.smt2         |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-exec__context.4.smt2             |   0.371s  |   0.371s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-exec__context.5.smt2             |   0.323s  |   0.323s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-exec__rwlock.1.smt2              |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-exec__rwlock.10.smt2             |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-exec__rwlock.2.smt2              |   0.286s  |   0.286s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-exec__rwlock.5.smt2              |   0.227s  |   0.227s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-exec__rwlock.7.smt2              |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-exec__rwlock.9.smt2              |   0.119s  |   0.119s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-exec__utils.4.smt2               |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-root.1.smt2                      |   0.251s  |   0.251s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-root.3.smt2                      |   0.170s  |   0.170s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__flat_combiner__FlatCombiner.13.smt2  |   0.172s  |   0.172s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__flat_combiner__FlatCombiner.14.smt2  |   0.318s  |   0.318s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__flat_combiner__FlatCombiner.2.smt2  |   0.206s  |   0.206s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__flat_combiner__FlatCombiner.5.smt2  |   0.236s  |   0.236s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__flat_combiner__FlatCombiner.7.smt2  |   0.153s  |   0.153s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__flat_combiner__FlatCombiner.8.smt2  |   0.166s  |   0.166s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__linearization.1.smt2       |   0.279s  |   0.279s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__linearization.2.smt2       |   0.195s  |   0.195s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__linearization.8.smt2       |   0.116s  |   0.116s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__linearization.9.smt2       |   0.289s  |   0.289s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__rwlock__RwLockSpec.10.smt2  |   0.349s  |   0.349s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__rwlock__RwLockSpec.12.smt2  |   0.310s  |   0.310s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__rwlock__RwLockSpec.19.smt2  |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__rwlock__RwLockSpec.3.smt2  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__rwlock__RwLockSpec.6.smt2  |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__rwlock__RwLockSpec.7.smt2  |   0.150s  |   0.150s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__simple_log.smt2            |   0.181s  |   0.181s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__simple_log__SimpleLog.1.smt2  |   0.312s  |   0.312s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__simple_log__SimpleLog.5.smt2  |   0.128s  |   0.128s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__simple_log__SimpleLog.7.smt2  |   0.242s  |   0.242s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__simple_log__SimpleLog.8.smt2  |   0.160s  |   0.160s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log.13.smt2      |   0.386s  |   0.386s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log.15.smt2      |   0.243s  |   0.243s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log.16.smt2      |   0.202s  |   0.202s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log.18.smt2      |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log.2.smt2       |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log.4.smt2       |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log.6.smt2       |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log.7.smt2       |   0.216s  |   0.216s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log__UnboundedLog.13.smt2  |   0.635s  |   0.635s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log__UnboundedLog.15.smt2  |   0.146s  |   0.146s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log__UnboundedLog.16.smt2  |   0.680s  |   0.680s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log__UnboundedLog.17.smt2  |   0.176s  |   0.176s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log__UnboundedLog.19.smt2  |   0.363s  |   0.363s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log__UnboundedLog.2.smt2  |   0.583s  |   0.583s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log__UnboundedLog.20.smt2  |   0.481s  |   0.481s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log__UnboundedLog.22.smt2  |   1.667s  |   1.667s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log__UnboundedLog.27.smt2  |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log__UnboundedLog.3.smt2  |   0.173s  |   0.173s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log__UnboundedLog.30.smt2  |   0.684s  |   0.684s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log__UnboundedLog.4.smt2  |   0.458s  |   0.458s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log__UnboundedLog.8.smt2  |   0.500s  |   0.500s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log_refines_simplelog.7.smt2  |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log_refines_simplelog.9.smt2  |   0.142s  |   0.142s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-logimpl_v.3.smt2  |   0.169s  |   0.169s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-logimpl_v.5.smt2  |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-logimpl_v.6.smt2  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-pmemspec_t.1.smt2  |   0.180s  |   0.180s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-kv__inv_v.1.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-kv__kvimpl_t.1.smt2  |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-kv__kvimpl_t.11.smt2  |   0.122s  |   0.122s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-kv__kvimpl_t.14.smt2  |   0.250s  |   0.250s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-kv__kvimpl_t.4.smt2  |   0.126s  |   0.126s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-kv__kvimpl_t.6.smt2  |   0.211s  |   0.211s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-kv__kvimpl_t.7.smt2  |   0.200s  |   0.200s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-kv__kvimpl_t.9.smt2  |   0.213s  |   0.213s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-kv__kvimpl_v.12.smt2  |   0.184s  |   0.184s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-kv__kvimpl_v.14.smt2  |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-kv__kvimpl_v.15.smt2  |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-kv__kvimpl_v.4.smt2  |   0.560s  |   0.560s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-kv__kvimpl_v.9.smt2  |   0.101s  |   0.101s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-kv__kvspec_t.1.smt2  |   0.266s  |   0.266s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__layout_v.3.smt2  |   0.221s  |   0.221s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__layout_v.4.smt2  |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-pmem__linux_pmemfile_t.3.smt2  |   0.220s  |   0.220s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-pmem__linux_pmemfile_t.4.smt2  |   0.197s  |   0.197s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-pmem__traits_t.1.smt2  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/verismo/arch__addr_s__def_s.1.smt2                   |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/verismo/arch__addr_s__def_s.2.smt2                   |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/verismo/arch__rmp__def_s.1.smt2                      |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/verismo/arch__rmp__def_s.3.smt2                      |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/verismo/arch__rmp__def_s.4.smt2                      |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/verismo/snp__percpu__def_s.1.smt2                    |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/verismo/snp__percpu__def_s.2.smt2                    |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/verismo/tspec__map_lib.1.smt2                        |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/verismo/tspec__math__cond_bound.1.smt2               |   0.190s  |   0.190s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/verismo/tspec__range_set.5.smt2                      |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/verismo/tspec__seqlib__seq_multiset.4.smt2           |   0.123s  |   0.123s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/verismo/tspec__seqlib__subseq.1.smt2                 |   0.104s  |   0.104s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/verismo/tspec__setlib.4.smt2                         |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/verismo/tspec__setlib.5.smt2                         |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/verismo/tspec_e__array__array_e.10.smt2              |   0.096s  |   0.096s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/verismo/tspec_e__array__array_e.2.smt2               |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/verismo/tspec_e__array__array_e.4.smt2               |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/verismo/tspec_e__array__array_utils.3.smt2           |   0.111s  |   0.111s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/verismo/tspec_e__array__array_utils.5.smt2           |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/verismo/tspec_e__array__sort.5.smt2                  |   0.379s  |   0.379s  |   0.000s  | 0.0%|
|non-incremental/UFDTLIA/20241211-verus/verismo/tspec_e__array__sort.7.smt2                  |   1.632s  |   1.632s  |   0.000s  | 0.0%|
</details>
