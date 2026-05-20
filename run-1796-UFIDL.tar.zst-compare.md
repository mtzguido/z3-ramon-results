Comparing data and data


# SUMMARY
- LHS tests = 68
- RHS tests = 68
- LHS success = 68  (100.0%)
- RHS success = 68  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: UFIDL.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/UFIDL.tar.zst?download=1
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
Job tag: UFIDL.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/UFIDL.tar.zst?download=1
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
|non-incremental/UFIDL/Burns/burns0.smt2                                                     |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns1.smt2                                                     |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns10.smt2                                                    |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns11.smt2                                                    |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns12.smt2                                                    |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns13.smt2                                                    |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns2.smt2                                                     |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns3.smt2                                                     |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns4.smt2                                                     |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns5.smt2                                                     |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns6.smt2                                                     |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns7.smt2                                                     |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns8.smt2                                                     |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns9.smt2                                                     |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala0.smt2                                  |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala10.smt2                                 |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala11.smt2                                 |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala12.smt2                                 |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala13.smt2                                 |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala2.smt2                                  |   0.089s  |   0.089s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFIDL/Burns/burns0.smt2                                                     |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns1.smt2                                                     |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns10.smt2                                                    |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns11.smt2                                                    |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns12.smt2                                                    |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns13.smt2                                                    |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns2.smt2                                                     |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns3.smt2                                                     |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns4.smt2                                                     |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns5.smt2                                                     |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns6.smt2                                                     |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns7.smt2                                                     |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns8.smt2                                                     |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns9.smt2                                                     |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala0.smt2                                  |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala10.smt2                                 |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala11.smt2                                 |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala12.smt2                                 |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala13.smt2                                 |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala2.smt2                                  |   0.089s  |   0.089s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFIDL/Burns/burns0.smt2                                                     |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns1.smt2                                                     |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns10.smt2                                                    |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns11.smt2                                                    |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns12.smt2                                                    |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns13.smt2                                                    |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns2.smt2                                                     |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns3.smt2                                                     |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns4.smt2                                                     |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns5.smt2                                                     |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns6.smt2                                                     |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns7.smt2                                                     |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns8.smt2                                                     |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns9.smt2                                                     |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala0.smt2                                  |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala10.smt2                                 |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala11.smt2                                 |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala12.smt2                                 |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala13.smt2                                 |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala2.smt2                                  |   0.089s  |   0.089s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFIDL/Burns/burns0.smt2                                                     |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns1.smt2                                                     |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns10.smt2                                                    |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns11.smt2                                                    |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns12.smt2                                                    |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns13.smt2                                                    |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns2.smt2                                                     |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns3.smt2                                                     |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns4.smt2                                                     |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns5.smt2                                                     |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns6.smt2                                                     |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns7.smt2                                                     |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns8.smt2                                                     |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns9.smt2                                                     |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala0.smt2                                  |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala10.smt2                                 |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala11.smt2                                 |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala12.smt2                                 |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala13.smt2                                 |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala2.smt2                                  |   0.089s  |   0.089s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/UFIDL/sledgehammer/Fundamental_Theorem_Algebra/smtlib.1308248.smt2         |  20.597s |5037.0MiB|
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.976791.smt2                             |  20.491s |4037.0MiB|
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.976292.smt2                             |  20.486s |4083.0MiB|
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.962381.smt2                             |  20.445s |4087.0MiB|
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.968906.smt2                             |  20.391s |4049.0MiB|
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.697341.smt2                             |  20.307s |2834.0MiB|
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.683530.smt2                             |  20.273s |2761.0MiB|
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer_2.smt2                      |  20.072s |229.0MiB|
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer_3.smt2                      |  20.035s |228.0MiB|
|non-incremental/UFIDL/boogie/NestedVC_Q-vc_nested.smt2                                     |  20.035s |225.0MiB|
|non-incremental/UFIDL/boogie/Call_Foo-noinfer.smt2                                         |  20.030s |229.0MiB|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala2.smt2                                 |   0.089s |21.696MiB|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala11.smt2                                |   0.078s |21.956MiB|
|non-incremental/UFIDL/Burns/burns6.smt2                                                    |   0.070s |20.948MiB|
|non-incremental/UFIDL/Burns/burns8.smt2                                                    |   0.067s |20.608MiB|
|non-incremental/UFIDL/sledgehammer/QEpres/smtlib.858765.smt2                               |   0.066s |20.244MiB|
|non-incremental/UFIDL/Burns/burns13.smt2                                                   |   0.065s |21.412MiB|
|non-incremental/UFIDL/boogie/Arrays_Skip1-noinfer.smt2                                     |   0.065s |20.364MiB|
|non-incremental/UFIDL/sledgehammer/QEpres/smtlib.858843.smt2                               |   0.064s |21.18MiB|
|non-incremental/UFIDL/Burns/burns5.smt2                                                    |   0.064s |20.336MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/UFIDL/sledgehammer/Fundamental_Theorem_Algebra/smtlib.1308248.smt2         |  20.597s |5037.0MiB|
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.976791.smt2                             |  20.491s |4037.0MiB|
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.976292.smt2                             |  20.486s |4083.0MiB|
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.962381.smt2                             |  20.445s |4087.0MiB|
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.968906.smt2                             |  20.391s |4049.0MiB|
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.697341.smt2                             |  20.307s |2834.0MiB|
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.683530.smt2                             |  20.273s |2761.0MiB|
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer_2.smt2                      |  20.072s |229.0MiB|
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer_3.smt2                      |  20.035s |228.0MiB|
|non-incremental/UFIDL/boogie/NestedVC_Q-vc_nested.smt2                                     |  20.035s |225.0MiB|
|non-incremental/UFIDL/boogie/Call_Foo-noinfer.smt2                                         |  20.030s |229.0MiB|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala2.smt2                                 |   0.089s |21.696MiB|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala11.smt2                                |   0.078s |21.956MiB|
|non-incremental/UFIDL/Burns/burns6.smt2                                                    |   0.070s |20.948MiB|
|non-incremental/UFIDL/Burns/burns8.smt2                                                    |   0.067s |20.608MiB|
|non-incremental/UFIDL/sledgehammer/QEpres/smtlib.858765.smt2                               |   0.066s |20.244MiB|
|non-incremental/UFIDL/Burns/burns13.smt2                                                   |   0.065s |21.412MiB|
|non-incremental/UFIDL/boogie/Arrays_Skip1-noinfer.smt2                                     |   0.065s |20.364MiB|
|non-incremental/UFIDL/sledgehammer/QEpres/smtlib.858843.smt2                               |   0.064s |21.18MiB|
|non-incremental/UFIDL/Burns/burns5.smt2                                                    |   0.064s |20.336MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFIDL/Burns/burns0.smt2                                                     |20.548MiB|20.548MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns1.smt2                                                     |20.644MiB|20.644MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns10.smt2                                                    |20.932MiB|20.932MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns11.smt2                                                    |20.612MiB|20.612MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns12.smt2                                                    |20.588MiB|20.588MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns13.smt2                                                    |21.412MiB|21.412MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns2.smt2                                                     |20.384MiB|20.384MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns3.smt2                                                     |20.368MiB|20.368MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns4.smt2                                                     |20.932MiB|20.932MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns5.smt2                                                     |20.336MiB|20.336MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns6.smt2                                                     |20.948MiB|20.948MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns7.smt2                                                     |20.364MiB|20.364MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns8.smt2                                                     |20.608MiB|20.608MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns9.smt2                                                     |21.344MiB|21.344MiB|0B| 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala0.smt2                                  |20.876MiB|20.876MiB|0B| 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala10.smt2                                 |20.64MiB|20.64MiB|0B| 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala11.smt2                                 |21.956MiB|21.956MiB|0B| 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala12.smt2                                 |21.876MiB|21.876MiB|0B| 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala13.smt2                                 |21.292MiB|21.292MiB|0B| 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala2.smt2                                  |21.696MiB|21.696MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFIDL/Burns/burns0.smt2                                                     |20.548MiB|20.548MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns1.smt2                                                     |20.644MiB|20.644MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns10.smt2                                                    |20.932MiB|20.932MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns11.smt2                                                    |20.612MiB|20.612MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns12.smt2                                                    |20.588MiB|20.588MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns13.smt2                                                    |21.412MiB|21.412MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns2.smt2                                                     |20.384MiB|20.384MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns3.smt2                                                     |20.368MiB|20.368MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns4.smt2                                                     |20.932MiB|20.932MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns5.smt2                                                     |20.336MiB|20.336MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns6.smt2                                                     |20.948MiB|20.948MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns7.smt2                                                     |20.364MiB|20.364MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns8.smt2                                                     |20.608MiB|20.608MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns9.smt2                                                     |21.344MiB|21.344MiB|0B| 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala0.smt2                                  |20.876MiB|20.876MiB|0B| 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala10.smt2                                 |20.64MiB|20.64MiB|0B| 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala11.smt2                                 |21.956MiB|21.956MiB|0B| 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala12.smt2                                 |21.876MiB|21.876MiB|0B| 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala13.smt2                                 |21.292MiB|21.292MiB|0B| 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala2.smt2                                  |21.696MiB|21.696MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFIDL/Burns/burns0.smt2                                                     |20.548MiB|20.548MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns1.smt2                                                     |20.644MiB|20.644MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns10.smt2                                                    |20.932MiB|20.932MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns11.smt2                                                    |20.612MiB|20.612MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns12.smt2                                                    |20.588MiB|20.588MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns13.smt2                                                    |21.412MiB|21.412MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns2.smt2                                                     |20.384MiB|20.384MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns3.smt2                                                     |20.368MiB|20.368MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns4.smt2                                                     |20.932MiB|20.932MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns5.smt2                                                     |20.336MiB|20.336MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns6.smt2                                                     |20.948MiB|20.948MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns7.smt2                                                     |20.364MiB|20.364MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns8.smt2                                                     |20.608MiB|20.608MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns9.smt2                                                     |21.344MiB|21.344MiB|0B| 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala0.smt2                                  |20.876MiB|20.876MiB|0B| 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala10.smt2                                 |20.64MiB|20.64MiB|0B| 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala11.smt2                                 |21.956MiB|21.956MiB|0B| 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala12.smt2                                 |21.876MiB|21.876MiB|0B| 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala13.smt2                                 |21.292MiB|21.292MiB|0B| 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala2.smt2                                  |21.696MiB|21.696MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFIDL/Burns/burns0.smt2                                                     |20.548MiB|20.548MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns1.smt2                                                     |20.644MiB|20.644MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns10.smt2                                                    |20.932MiB|20.932MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns11.smt2                                                    |20.612MiB|20.612MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns12.smt2                                                    |20.588MiB|20.588MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns13.smt2                                                    |21.412MiB|21.412MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns2.smt2                                                     |20.384MiB|20.384MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns3.smt2                                                     |20.368MiB|20.368MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns4.smt2                                                     |20.932MiB|20.932MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns5.smt2                                                     |20.336MiB|20.336MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns6.smt2                                                     |20.948MiB|20.948MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns7.smt2                                                     |20.364MiB|20.364MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns8.smt2                                                     |20.608MiB|20.608MiB|0B| 0.0%|
|non-incremental/UFIDL/Burns/burns9.smt2                                                     |21.344MiB|21.344MiB|0B| 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala0.smt2                                  |20.876MiB|20.876MiB|0B| 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala10.smt2                                 |20.64MiB|20.64MiB|0B| 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala11.smt2                                 |21.956MiB|21.956MiB|0B| 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala12.smt2                                 |21.876MiB|21.876MiB|0B| 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala13.smt2                                 |21.292MiB|21.292MiB|0B| 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala2.smt2                                  |21.696MiB|21.696MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/UFIDL/sledgehammer/Fundamental_Theorem_Algebra/smtlib.1308248.smt2         |  20.597s |5037.0MiB|
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.962381.smt2                             |  20.445s |4087.0MiB|
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.976292.smt2                             |  20.486s |4083.0MiB|
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.968906.smt2                             |  20.391s |4049.0MiB|
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.976791.smt2                             |  20.491s |4037.0MiB|
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.697341.smt2                             |  20.307s |2834.0MiB|
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.683530.smt2                             |  20.273s |2761.0MiB|
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer_2.smt2                      |  20.072s |229.0MiB|
|non-incremental/UFIDL/boogie/Call_Foo-noinfer.smt2                                         |  20.030s |229.0MiB|
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer_3.smt2                      |  20.035s |228.0MiB|
|non-incremental/UFIDL/boogie/NestedVC_Q-vc_nested.smt2                                     |  20.035s |225.0MiB|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala11.smt2                                |   0.078s |21.956MiB|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala12.smt2                                |   0.053s |21.876MiB|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala7.smt2                                 |   0.061s |21.716MiB|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala2.smt2                                 |   0.089s |21.696MiB|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala8.smt2                                 |   0.062s |21.648MiB|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala5.smt2                                 |   0.061s |21.6MiB|
|non-incremental/UFIDL/Burns/burns13.smt2                                                   |   0.065s |21.412MiB|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala6.smt2                                 |   0.049s |21.372MiB|
|non-incremental/UFIDL/Burns/burns9.smt2                                                    |   0.034s |21.344MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/UFIDL/sledgehammer/Fundamental_Theorem_Algebra/smtlib.1308248.smt2         |  20.597s |5037.0MiB|
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.962381.smt2                             |  20.445s |4087.0MiB|
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.976292.smt2                             |  20.486s |4083.0MiB|
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.968906.smt2                             |  20.391s |4049.0MiB|
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.976791.smt2                             |  20.491s |4037.0MiB|
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.697341.smt2                             |  20.307s |2834.0MiB|
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.683530.smt2                             |  20.273s |2761.0MiB|
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer_2.smt2                      |  20.072s |229.0MiB|
|non-incremental/UFIDL/boogie/Call_Foo-noinfer.smt2                                         |  20.030s |229.0MiB|
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer_3.smt2                      |  20.035s |228.0MiB|
|non-incremental/UFIDL/boogie/NestedVC_Q-vc_nested.smt2                                     |  20.035s |225.0MiB|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala11.smt2                                |   0.078s |21.956MiB|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala12.smt2                                |   0.053s |21.876MiB|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala7.smt2                                 |   0.061s |21.716MiB|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala2.smt2                                 |   0.089s |21.696MiB|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala8.smt2                                 |   0.062s |21.648MiB|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala5.smt2                                 |   0.061s |21.6MiB|
|non-incremental/UFIDL/Burns/burns13.smt2                                                   |   0.065s |21.412MiB|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala6.smt2                                 |   0.049s |21.372MiB|
|non-incremental/UFIDL/Burns/burns9.smt2                                                    |   0.034s |21.344MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFIDL/Burns/burns0.smt2                                                     |   0.036s  |   0.036s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns1.smt2                                                     |   0.031s  |   0.031s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns10.smt2                                                    |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns11.smt2                                                    |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns12.smt2                                                    |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns13.smt2                                                    |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns2.smt2                                                     |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns3.smt2                                                     |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns4.smt2                                                     |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns5.smt2                                                     |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns6.smt2                                                     |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns7.smt2                                                     |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns8.smt2                                                     |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/Burns/burns9.smt2                                                     |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala0.smt2                                  |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala10.smt2                                 |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala11.smt2                                 |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala12.smt2                                 |   0.053s  |   0.053s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala13.smt2                                 |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala2.smt2                                  |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala3.smt2                                  |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala4.smt2                                  |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala5.smt2                                  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala6.smt2                                  |   0.049s  |   0.049s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala7.smt2                                  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala8.smt2                                  |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/RicartAgrawala/ricart-agrawala9.smt2                                  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/boogie/Arrays_P1-noinfer.smt2                                         |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/boogie/Arrays_Q1-noinfer.smt2                                         |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/boogie/Arrays_Skip0-noinfer.smt2                                      |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/boogie/Arrays_Skip1-noinfer.smt2                                      |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/boogie/AssumeEnsures_Caller0-noinfer.smt2                             |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer.smt2                         |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer_1.smt2                       |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer_2.smt2                       |  20.072s  |  20.072s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/boogie/Call_DifferentFormalNames-noinfer_3.smt2                       |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/boogie/Call_Foo-noinfer.smt2                                          |  20.030s  |  20.030s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/boogie/False_Test1-noinfer.smt2                                       |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/boogie/False_Test2-noinfer.smt2                                       |   0.058s  |   0.058s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/boogie/FormulaTerm_LESS-noinfer_3.smt2                                |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/boogie/FormulaTerm_less-noinfer_1.smt2                                |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/boogie/FormulaTerm_less-noinfer_2.smt2                                |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/boogie/FormulaTerm_or-noinfer.smt2                                    |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/boogie/NestedVC_P-vc_nested.smt2                                      |   0.050s  |   0.050s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/boogie/NestedVC_Q-vc_nested.smt2                                      |  20.035s  |  20.035s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/boogie/Old_SwapElems-noinfer.smt2                                     |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/boogie/Passification_Loop-noinfer.smt2                                |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/boogie/Passification_UnreachableBlock-noinfer.smt2                    |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/boogie/UnreachableBlocks_P-vc_nested.smt2                             |   0.048s  |   0.048s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/boogie/UnreachableBlocks_Q-vc_nested.smt2                             |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/boogie/UnreachableBlocks_R-vc_nested.smt2                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/boogie/equiv2_M-infer_e-vc_local.smt2                                 |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/boogie/equiv3_M-infer_e-vc_local.smt2                                 |   0.039s  |   0.039s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/boogie/heapsucc0_M-infer_eh-vc_local.smt2                             |   0.059s  |   0.059s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/boogie/heapsucc1_M-infer_eh-vc_local.smt2                             |   0.023s  |   0.023s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/boogie/loop0_M-infer_e-vc_local.smt2                                  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/sledgehammer/Fundamental_Theorem_Algebra/smtlib.1308248.smt2          |  20.597s  |  20.597s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/sledgehammer/QEpres/smtlib.858765.smt2                                |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/sledgehammer/QEpres/smtlib.858843.smt2                                |   0.064s  |   0.064s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/sledgehammer/QEpres/smtlib.858852.smt2                                |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/sledgehammer/QEpres/smtlib.858929.smt2                                |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.675311.smt2                              |   0.046s  |   0.046s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.683530.smt2                              |  20.273s  |  20.273s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.697341.smt2                              |  20.307s  |  20.307s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.962381.smt2                              |  20.445s  |  20.445s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.968906.smt2                              |  20.391s  |  20.391s  |   0.000s  | 0.0%|
|non-incremental/UFIDL/sledgehammer/TypeSafe/smtlib.976292.smt2                              |  20.486s  |  20.486s  |   0.000s  | 0.0%|
</details>
