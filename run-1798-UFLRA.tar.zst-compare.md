Comparing data and data


# SUMMARY
- LHS tests = 15
- RHS tests = 15
- LHS success = 15  (100.0%)
- RHS success = 15  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: UFLRA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/UFLRA.tar.zst?download=1
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
Job tag: UFLRA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/UFLRA.tar.zst?download=1
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
|non-incremental/UFLRA/FFT/smtlib.620487.smt2                                                |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.620535.smt2                                                |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623417.smt2                                                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623474.smt2                                                |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623531.smt2                                                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623597.smt2                                                |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627457.smt2                                                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627531.smt2                                                |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627605.smt2                                                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627688.smt2                                                |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/misc/list2.smt2                                                       |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/misc/set14.smt2                                                       |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/misc/set16.smt2                                                       |   1.652s  |   1.652s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/misc/set19.smt2                                                       |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/misc/set9.smt2                                                        |   2.661s  |   2.661s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFLRA/FFT/smtlib.620487.smt2                                                |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.620535.smt2                                                |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623417.smt2                                                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623474.smt2                                                |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623531.smt2                                                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623597.smt2                                                |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627457.smt2                                                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627531.smt2                                                |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627605.smt2                                                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627688.smt2                                                |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/misc/list2.smt2                                                       |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/misc/set14.smt2                                                       |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/misc/set16.smt2                                                       |   1.652s  |   1.652s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/misc/set19.smt2                                                       |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/misc/set9.smt2                                                        |   2.661s  |   2.661s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFLRA/FFT/smtlib.620487.smt2                                                |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.620535.smt2                                                |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623417.smt2                                                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623474.smt2                                                |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623531.smt2                                                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623597.smt2                                                |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627457.smt2                                                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627531.smt2                                                |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627605.smt2                                                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627688.smt2                                                |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/misc/list2.smt2                                                       |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/misc/set14.smt2                                                       |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/misc/set16.smt2                                                       |   1.652s  |   1.652s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/misc/set19.smt2                                                       |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/misc/set9.smt2                                                        |   2.661s  |   2.661s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFLRA/FFT/smtlib.620487.smt2                                                |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.620535.smt2                                                |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623417.smt2                                                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623474.smt2                                                |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623531.smt2                                                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623597.smt2                                                |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627457.smt2                                                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627531.smt2                                                |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627605.smt2                                                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627688.smt2                                                |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/misc/list2.smt2                                                       |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/misc/set14.smt2                                                       |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/misc/set16.smt2                                                       |   1.652s  |   1.652s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/misc/set19.smt2                                                       |  20.032s  |  20.032s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/misc/set9.smt2                                                        |   2.661s  |   2.661s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/UFLRA/misc/set14.smt2                                                      |  20.046s |143.0MiB|
|non-incremental/UFLRA/misc/list2.smt2                                                      |  20.041s |237.0MiB|
|non-incremental/UFLRA/misc/set19.smt2                                                      |  20.032s |129.0MiB|
|non-incremental/UFLRA/misc/set9.smt2                                                       |   2.661s |40.108MiB|
|non-incremental/UFLRA/misc/set16.smt2                                                      |   1.652s |33.008MiB|
|non-incremental/UFLRA/FFT/smtlib.623417.smt2                                               |   0.042s |20.608MiB|
|non-incremental/UFLRA/FFT/smtlib.627605.smt2                                               |   0.042s |20.112MiB|
|non-incremental/UFLRA/FFT/smtlib.623531.smt2                                               |   0.042s |20.612MiB|
|non-incremental/UFLRA/FFT/smtlib.627457.smt2                                               |   0.042s |20.108MiB|
|non-incremental/UFLRA/FFT/smtlib.623597.smt2                                               |   0.041s |20.108MiB|
|non-incremental/UFLRA/FFT/smtlib.620487.smt2                                               |   0.029s |20.116MiB|
|non-incremental/UFLRA/FFT/smtlib.627531.smt2                                               |   0.029s |20.352MiB|
|non-incremental/UFLRA/FFT/smtlib.627688.smt2                                               |   0.029s |20.4MiB|
|non-incremental/UFLRA/FFT/smtlib.620535.smt2                                               |   0.028s |20.092MiB|
|non-incremental/UFLRA/FFT/smtlib.623474.smt2                                               |   0.022s |20.364MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/UFLRA/misc/set14.smt2                                                      |  20.046s |143.0MiB|
|non-incremental/UFLRA/misc/list2.smt2                                                      |  20.041s |237.0MiB|
|non-incremental/UFLRA/misc/set19.smt2                                                      |  20.032s |129.0MiB|
|non-incremental/UFLRA/misc/set9.smt2                                                       |   2.661s |40.108MiB|
|non-incremental/UFLRA/misc/set16.smt2                                                      |   1.652s |33.008MiB|
|non-incremental/UFLRA/FFT/smtlib.623417.smt2                                               |   0.042s |20.608MiB|
|non-incremental/UFLRA/FFT/smtlib.627605.smt2                                               |   0.042s |20.112MiB|
|non-incremental/UFLRA/FFT/smtlib.623531.smt2                                               |   0.042s |20.612MiB|
|non-incremental/UFLRA/FFT/smtlib.627457.smt2                                               |   0.042s |20.108MiB|
|non-incremental/UFLRA/FFT/smtlib.623597.smt2                                               |   0.041s |20.108MiB|
|non-incremental/UFLRA/FFT/smtlib.620487.smt2                                               |   0.029s |20.116MiB|
|non-incremental/UFLRA/FFT/smtlib.627531.smt2                                               |   0.029s |20.352MiB|
|non-incremental/UFLRA/FFT/smtlib.627688.smt2                                               |   0.029s |20.4MiB|
|non-incremental/UFLRA/FFT/smtlib.620535.smt2                                               |   0.028s |20.092MiB|
|non-incremental/UFLRA/FFT/smtlib.623474.smt2                                               |   0.022s |20.364MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFLRA/FFT/smtlib.620487.smt2                                                |20.116MiB|20.116MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.620535.smt2                                                |20.092MiB|20.092MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623417.smt2                                                |20.608MiB|20.608MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623474.smt2                                                |20.364MiB|20.364MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623531.smt2                                                |20.612MiB|20.612MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623597.smt2                                                |20.108MiB|20.108MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627457.smt2                                                |20.108MiB|20.108MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627531.smt2                                                |20.352MiB|20.352MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627605.smt2                                                |20.112MiB|20.112MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627688.smt2                                                |20.4MiB|20.4MiB|0B| 0.0%|
|non-incremental/UFLRA/misc/list2.smt2                                                       |237.0MiB|237.0MiB|0B| 0.0%|
|non-incremental/UFLRA/misc/set14.smt2                                                       |143.0MiB|143.0MiB|0B| 0.0%|
|non-incremental/UFLRA/misc/set16.smt2                                                       |33.008MiB|33.008MiB|0B| 0.0%|
|non-incremental/UFLRA/misc/set19.smt2                                                       |129.0MiB|129.0MiB|0B| 0.0%|
|non-incremental/UFLRA/misc/set9.smt2                                                        |40.108MiB|40.108MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFLRA/FFT/smtlib.620487.smt2                                                |20.116MiB|20.116MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.620535.smt2                                                |20.092MiB|20.092MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623417.smt2                                                |20.608MiB|20.608MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623474.smt2                                                |20.364MiB|20.364MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623531.smt2                                                |20.612MiB|20.612MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623597.smt2                                                |20.108MiB|20.108MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627457.smt2                                                |20.108MiB|20.108MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627531.smt2                                                |20.352MiB|20.352MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627605.smt2                                                |20.112MiB|20.112MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627688.smt2                                                |20.4MiB|20.4MiB|0B| 0.0%|
|non-incremental/UFLRA/misc/list2.smt2                                                       |237.0MiB|237.0MiB|0B| 0.0%|
|non-incremental/UFLRA/misc/set14.smt2                                                       |143.0MiB|143.0MiB|0B| 0.0%|
|non-incremental/UFLRA/misc/set16.smt2                                                       |33.008MiB|33.008MiB|0B| 0.0%|
|non-incremental/UFLRA/misc/set19.smt2                                                       |129.0MiB|129.0MiB|0B| 0.0%|
|non-incremental/UFLRA/misc/set9.smt2                                                        |40.108MiB|40.108MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFLRA/FFT/smtlib.620487.smt2                                                |20.116MiB|20.116MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.620535.smt2                                                |20.092MiB|20.092MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623417.smt2                                                |20.608MiB|20.608MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623474.smt2                                                |20.364MiB|20.364MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623531.smt2                                                |20.612MiB|20.612MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623597.smt2                                                |20.108MiB|20.108MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627457.smt2                                                |20.108MiB|20.108MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627531.smt2                                                |20.352MiB|20.352MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627605.smt2                                                |20.112MiB|20.112MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627688.smt2                                                |20.4MiB|20.4MiB|0B| 0.0%|
|non-incremental/UFLRA/misc/list2.smt2                                                       |237.0MiB|237.0MiB|0B| 0.0%|
|non-incremental/UFLRA/misc/set14.smt2                                                       |143.0MiB|143.0MiB|0B| 0.0%|
|non-incremental/UFLRA/misc/set16.smt2                                                       |33.008MiB|33.008MiB|0B| 0.0%|
|non-incremental/UFLRA/misc/set19.smt2                                                       |129.0MiB|129.0MiB|0B| 0.0%|
|non-incremental/UFLRA/misc/set9.smt2                                                        |40.108MiB|40.108MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFLRA/FFT/smtlib.620487.smt2                                                |20.116MiB|20.116MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.620535.smt2                                                |20.092MiB|20.092MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623417.smt2                                                |20.608MiB|20.608MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623474.smt2                                                |20.364MiB|20.364MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623531.smt2                                                |20.612MiB|20.612MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623597.smt2                                                |20.108MiB|20.108MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627457.smt2                                                |20.108MiB|20.108MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627531.smt2                                                |20.352MiB|20.352MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627605.smt2                                                |20.112MiB|20.112MiB|0B| 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627688.smt2                                                |20.4MiB|20.4MiB|0B| 0.0%|
|non-incremental/UFLRA/misc/list2.smt2                                                       |237.0MiB|237.0MiB|0B| 0.0%|
|non-incremental/UFLRA/misc/set14.smt2                                                       |143.0MiB|143.0MiB|0B| 0.0%|
|non-incremental/UFLRA/misc/set16.smt2                                                       |33.008MiB|33.008MiB|0B| 0.0%|
|non-incremental/UFLRA/misc/set19.smt2                                                       |129.0MiB|129.0MiB|0B| 0.0%|
|non-incremental/UFLRA/misc/set9.smt2                                                        |40.108MiB|40.108MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/UFLRA/misc/list2.smt2                                                      |  20.041s |237.0MiB|
|non-incremental/UFLRA/misc/set14.smt2                                                      |  20.046s |143.0MiB|
|non-incremental/UFLRA/misc/set19.smt2                                                      |  20.032s |129.0MiB|
|non-incremental/UFLRA/misc/set9.smt2                                                       |   2.661s |40.108MiB|
|non-incremental/UFLRA/misc/set16.smt2                                                      |   1.652s |33.008MiB|
|non-incremental/UFLRA/FFT/smtlib.623531.smt2                                               |   0.042s |20.612MiB|
|non-incremental/UFLRA/FFT/smtlib.623417.smt2                                               |   0.042s |20.608MiB|
|non-incremental/UFLRA/FFT/smtlib.627688.smt2                                               |   0.029s |20.4MiB|
|non-incremental/UFLRA/FFT/smtlib.623474.smt2                                               |   0.022s |20.364MiB|
|non-incremental/UFLRA/FFT/smtlib.627531.smt2                                               |   0.029s |20.352MiB|
|non-incremental/UFLRA/FFT/smtlib.620487.smt2                                               |   0.029s |20.116MiB|
|non-incremental/UFLRA/FFT/smtlib.627605.smt2                                               |   0.042s |20.112MiB|
|non-incremental/UFLRA/FFT/smtlib.627457.smt2                                               |   0.042s |20.108MiB|
|non-incremental/UFLRA/FFT/smtlib.623597.smt2                                               |   0.041s |20.108MiB|
|non-incremental/UFLRA/FFT/smtlib.620535.smt2                                               |   0.028s |20.092MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/UFLRA/misc/list2.smt2                                                      |  20.041s |237.0MiB|
|non-incremental/UFLRA/misc/set14.smt2                                                      |  20.046s |143.0MiB|
|non-incremental/UFLRA/misc/set19.smt2                                                      |  20.032s |129.0MiB|
|non-incremental/UFLRA/misc/set9.smt2                                                       |   2.661s |40.108MiB|
|non-incremental/UFLRA/misc/set16.smt2                                                      |   1.652s |33.008MiB|
|non-incremental/UFLRA/FFT/smtlib.623531.smt2                                               |   0.042s |20.612MiB|
|non-incremental/UFLRA/FFT/smtlib.623417.smt2                                               |   0.042s |20.608MiB|
|non-incremental/UFLRA/FFT/smtlib.627688.smt2                                               |   0.029s |20.4MiB|
|non-incremental/UFLRA/FFT/smtlib.623474.smt2                                               |   0.022s |20.364MiB|
|non-incremental/UFLRA/FFT/smtlib.627531.smt2                                               |   0.029s |20.352MiB|
|non-incremental/UFLRA/FFT/smtlib.620487.smt2                                               |   0.029s |20.116MiB|
|non-incremental/UFLRA/FFT/smtlib.627605.smt2                                               |   0.042s |20.112MiB|
|non-incremental/UFLRA/FFT/smtlib.627457.smt2                                               |   0.042s |20.108MiB|
|non-incremental/UFLRA/FFT/smtlib.623597.smt2                                               |   0.041s |20.108MiB|
|non-incremental/UFLRA/FFT/smtlib.620535.smt2                                               |   0.028s |20.092MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFLRA/FFT/smtlib.620487.smt2                                                |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.620535.smt2                                                |   0.028s  |   0.028s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623417.smt2                                                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623474.smt2                                                |   0.022s  |   0.022s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623531.smt2                                                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.623597.smt2                                                |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627457.smt2                                                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627531.smt2                                                |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627605.smt2                                                |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/FFT/smtlib.627688.smt2                                                |   0.029s  |   0.029s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/misc/list2.smt2                                                       |  20.041s  |  20.041s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/misc/set14.smt2                                                       |  20.046s  |  20.046s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/misc/set16.smt2                                                       |   1.652s  |   1.652s  |   0.000s  | 0.0%|
|non-incremental/UFLRA/misc/set19.smt2                                                       |  20.032s  |  20.032s  |   0.000s  | 0.0%|
</details>
