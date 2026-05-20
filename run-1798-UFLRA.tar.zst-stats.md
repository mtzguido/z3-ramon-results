# .

* SAT 2
* UNSAT 10
* TIMEOUT 3
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

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


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/UFLRA/FFT/smtlib.623474.smt2                 |    0.022s | 20.364MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.620535.smt2                 |    0.028s | 20.092MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.627688.smt2                 |    0.029s | 20.4MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.620487.smt2                 |    0.029s | 20.116MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.627531.smt2                 |    0.029s | 20.352MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.623597.smt2                 |    0.041s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.623417.smt2                 |    0.042s | 20.608MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.627605.smt2                 |    0.042s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.627457.smt2                 |    0.042s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/FFT/smtlib.623531.smt2                 |    0.042s | 20.612MiB| unsat | 0 |  |  |
|non-incremental/UFLRA/misc/set16.smt2                        |    1.652s | 33.008MiB| sat | 0 |  |  |
|non-incremental/UFLRA/misc/set9.smt2                         |    2.661s | 40.108MiB| sat | 0 |  |  |
|non-incremental/UFLRA/misc/set19.smt2                        |   20.032s | 129.0MiB| timeout | 0 |  |  |
|non-incremental/UFLRA/misc/list2.smt2                        |   20.041s | 237.0MiB| timeout | 0 |  |  |
|non-incremental/UFLRA/misc/set14.smt2                        |   20.046s | 143.0MiB| timeout | 0 |  |  |
