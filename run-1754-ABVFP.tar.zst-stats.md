# .

* SAT 0
* UNSAT 0
* TIMEOUT 0
* UNKNOWN 0

* UNSET 60

* ERROR 60

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: ABVFP.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/ABVFP.tar.zst?download=1
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
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float22_true-unreach-call_true-termination.i_4.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0620b_true-unreach-call.c_6.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float22_true-unreach-call_true-termination.i_9.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0530b_true-unreach-call.c_5.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0530b_true-unreach-call.c_2.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float22_true-unreach-call_true-termination.i_8.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0530b_true-unreach-call.c_7.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float22_true-unreach-call_true-termination.i_2.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0682a_true-unreach-call.c_13.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float22_true-unreach-call_true-termination.i_1.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0684a_true-unreach-call.c_4.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0620a_true-unreach-call.c_1.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0320_true-unreach-call.c_4.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float22_true-unreach-call_true-termination.i_13.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0530a_true-unreach-call.c_4.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float22_true-unreach-call_true-termination.i_0.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float22_true-unreach-call_true-termination.i_6.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float22_true-unreach-call_true-termination.i_10.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0620a_true-unreach-call.c_3.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float22_true-unreach-call_true-termination.i_3.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0670_true-unreach-call.c_8.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float22_true-unreach-call_true-termination.i_5.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/double_req_bl_0670_true-unreach-call.c_5.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float22_true-unreach-call_true-termination.i_7.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0530b_true-unreach-call.c_8.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_0621b_true-unreach-call.c_1.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float22_true-unreach-call_true-termination.i_11.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float22_true-unreach-call_true-termination.i_12.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20190429-UltimateAutomizerSvcomp2019/float_req_bl_1210_false-unreach-call.c_0.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/double_req_bl_0663b.c_7.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float22.i_10.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float22.i_16.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float22.i_12.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float22.i_1.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float22.i_15.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/double_req_bl_0663b.c_9.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float_req_bl_1130a.c_0.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/double_req_bl_1300.c_1.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/double_req_bl_1300.c_2.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/list_search-2.i_34.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float22.i_0.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/test_mutex_unbounded-1.i_52.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float22.i_6.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float22.i_3.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/test_mutex_unbounded-2.i_63.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float22.i_14.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float22.i_2.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float22.i_4.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/sll2n_append_unequal.i_49.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/double_req_bl_1300.c_4.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float22.i_5.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/double_req_bl_1300.c_3.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/test_mutex_unbounded-1.i_53.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/test_mutex_unbounded-2.i_64.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/double_req_bl_0663b.c_8.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float22.i_13.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float22.i_17.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float_req_bl_1130a.c_1.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20230321-UltimateAutomizerSvcomp2023/float22.i_11.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/ABVFP/20170501-Heizmann-UltimateAutomizer/filter_iir_true-unreach-call.c_35.smt2 | 1000.000s | -1B| unset | -1 |  |  |
