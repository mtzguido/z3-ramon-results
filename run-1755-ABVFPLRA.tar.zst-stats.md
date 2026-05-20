# .

* SAT 0
* UNSAT 0
* TIMEOUT 0
* UNKNOWN 0

* UNSET 77

* ERROR 77

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: ABVFPLRA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/ABVFPLRA.tar.zst?download=1
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
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0832_true-unreach-call.c_9.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0684a_true-unreach-call.c_12.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_8.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0684a_true-unreach-call.c_16.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0832_true-unreach-call.c_4.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0684a_true-unreach-call.c_10.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0684a_true-unreach-call.c_15.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0876_true-unreach-call.c_25.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0684a_true-unreach-call.c_5.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0684a_true-unreach-call.c_14.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0875_true-unreach-call.c_22.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_13.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621b_true-unreach-call.c_16.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0875_true-unreach-call.c_24.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621b_true-unreach-call.c_11.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0684a_true-unreach-call.c_6.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_10.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_1032d_true-unreach-call.c_0.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_6.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0832_true-unreach-call.c_5.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0684a_true-unreach-call.c_7.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_15.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_14.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_17.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621b_true-unreach-call.c_9.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0832_true-unreach-call.c_6.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0684a_true-unreach-call.c_17.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0875_true-unreach-call.c_21.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0833_true-unreach-call.c_18.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0684a_true-unreach-call.c_11.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0877_true-unreach-call.c_12.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_12.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621b_true-unreach-call.c_7.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0880_true-unreach-call.c_12.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_3.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0875_true-unreach-call.c_27.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0880_true-unreach-call.c_14.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621b_true-unreach-call.c_18.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_18.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621b_true-unreach-call.c_10.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0684a_true-unreach-call.c_8.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_7.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_9.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_4.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0880_true-unreach-call.c_13.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0880_true-unreach-call.c_11.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621b_true-unreach-call.c_17.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0876_true-unreach-call.c_22.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0875_true-unreach-call.c_29.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0876_true-unreach-call.c_23.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0876_true-unreach-call.c_21.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621b_true-unreach-call.c_13.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_5.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621b_true-unreach-call.c_12.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0877_true-unreach-call.c_13.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0684a_true-unreach-call.c_13.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621b_true-unreach-call.c_15.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_20.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0880_true-unreach-call.c_18.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621b_true-unreach-call.c_19.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0684a_true-unreach-call.c_9.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_19.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_11.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0833_true-unreach-call.c_15.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0880_true-unreach-call.c_15.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0833_true-unreach-call.c_8.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0877_true-unreach-call.c_11.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621b_true-unreach-call.c_14.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0682a_true-unreach-call.c_1.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0875_true-unreach-call.c_23.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621a_true-unreach-call.c_16.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621b_true-unreach-call.c_8.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0883_true-unreach-call.c_5.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0876_true-unreach-call.c_24.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0875_true-unreach-call.c_28.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20230321-UltimateAutomizerSvcomp2023/float_req_bl_0683a.c_5.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFPLRA/20230321-UltimateAutomizerSvcomp2023/float_req_bl_0683a.c_7.smt2 | 1000.000s | -1B| unset | -1 |  |  |
