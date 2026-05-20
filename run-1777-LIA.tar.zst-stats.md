# .

* SAT 155
* UNSAT 230
* TIMEOUT 105
* UNKNOWN 0

* UNSET 46

* ERROR 46

# Meta data

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


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1758.smt2 |    0.021s | 19.604MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_785.smt2 |    0.022s | 20.796MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_537.smt2 |    0.025s | 19.592MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1370.smt2 |    0.025s | 20.612MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1786.smt2 |    0.027s | 20.552MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/163.smt2                           |    0.028s | 21.136MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_2.smt2 |    0.029s | 20.876MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/s3_srvr_2_true-unreach-call_true-no-overflow_false-termination.BV.c.cil.c_0.smt2 |    0.029s | 20.608MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_775.smt2 |    0.029s | 19.608MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_2207.smt2 |    0.029s | 21.036MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/018.smt2                           |    0.029s | 20.88MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1437.smt2 |    0.030s | 20.86MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/118.smt2                           |    0.030s | 21.356MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/164.smt2                           |    0.030s | 21.368MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_780.smt2 |    0.031s | 20.792MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_14.smt2 |    0.032s | 20.96MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_5.smt2 |    0.032s | 20.776MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1789.smt2 |    0.033s | 20.336MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_6.smt2 |    0.035s | 20.912MiB| unsat | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_2_3.smt2          |    0.035s | 21.02MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/178.smt2                           |    0.035s | 21.112MiB| sat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_4.smt2 |    0.036s | 20.708MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_1.smt2 |    0.036s | 20.996MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/016.smt2                           |    0.036s | 22.028MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/134.smt2                           |    0.037s | 21.896MiB| sat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_5.smt2 |    0.038s | 20.768MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_14.smt2 |    0.039s | 20.896MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/126.smt2                           |    0.040s | 22.0MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_8.smt2 |    0.042s | 20.896MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/081.smt2                           |    0.043s | 22.076MiB| sat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_0.smt2 |    0.044s | 21.164MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_12.smt2 |    0.044s | 20.912MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_575.smt2 |    0.044s | 20.672MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_11.smt2 |    0.045s | 21.124MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_4.smt2 |    0.045s | 20.92MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_2.smt2 |    0.046s | 20.864MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/104.smt2                           |    0.049s | 20.792MiB| sat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_7.smt2 |    0.050s | 20.876MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/031.smt2                           |    0.050s | 21.9MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_720.smt2 |    0.052s | 19.632MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_12.smt2 |    0.053s | 21.188MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1792.smt2 |    0.053s | 19.748MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_497.smt2 |    0.055s | 19.644MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1379.smt2 |    0.055s | 19.6MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_187.smt2 |    0.055s | 20.796MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1847.smt2 |    0.055s | 20.692MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/066.smt2                           |    0.055s | 21.148MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1371.smt2 |    0.056s | 20.66MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_9.smt2 |    0.057s | 20.98MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_8.smt2 |    0.057s | 20.724MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_6_true-unreach-call_true-no-overflow_false-termination.i_15.smt2 |    0.057s | 20.952MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1875.smt2 |    0.057s | 19.592MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/011.smt2                           |    0.057s | 20.876MiB| sat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_3.smt2 |    0.058s | 20.64MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_6.smt2 |    0.058s | 20.996MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1107.smt2 |    0.058s | 20.308MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_3227.smt2 |    0.058s | 19.86MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/168.smt2                           |    0.058s | 21.36MiB| sat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_10.smt2 |    0.059s | 20.772MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_670.smt2 |    0.059s | 21.088MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1736.smt2 |    0.059s | 19.708MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1479.smt2 |    0.059s | 20.636MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/012.smt2                           |    0.059s | 21.076MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/151.smt2                           |    0.059s | 21.144MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/017.smt2                           |    0.059s | 20.844MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/113.smt2                           |    0.059s | 21.384MiB| sat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_7.smt2 |    0.060s | 21.16MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1317.smt2 |    0.060s | 20.62MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/159.smt2                           |    0.060s | 21.284MiB| sat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_10.smt2 |    0.061s | 20.908MiB| unsat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_9.smt2 |    0.061s | 20.892MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/107.smt2                           |    0.061s | 21.132MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/156.smt2                           |    0.061s | 20.988MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/068.smt2                           |    0.062s | 21.432MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/145.smt2                           |    0.062s | 21.136MiB| sat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_2_true-unreach-call_true-no-overflow_false-termination.i_13.smt2 |    0.063s | 20.904MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_378.smt2 |    0.063s | 20.624MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1677.smt2 |    0.063s | 20.436MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_1657.smt2 |    0.063s | 19.52MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/194.smt2                           |    0.063s | 21.576MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_755.smt2 |    0.064s | 20.836MiB| unsat | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_3_5.smt2          |    0.064s | 21.228MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/109.smt2                           |    0.064s | 20.884MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/072.smt2                           |    0.064s | 21.984MiB| sat | 0 |  |  |
|non-incremental/LIA/20190429-UltimateAutomizerSvcomp2019/jain_7_true-unreach-call_true-no-overflow_false-termination.i_3.smt2 |    0.065s | 20.94MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_573.smt2 |    0.065s | 19.724MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_73.smt2 |    0.065s | 20.944MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/028.smt2                           |    0.065s | 22.116MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/162.smt2                           |    0.065s | 20.892MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/037.smt2                           |    0.065s | 21.76MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_798.smt2 |    0.066s | 19.872MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/154.smt2                           |    0.066s | 21.132MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_657.smt2 |    0.067s | 20.876MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_173.smt2 |    0.067s | 20.684MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_357.smt2 |    0.067s | 20.804MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1676.smt2 |    0.067s | 19.568MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1337.smt2 |    0.067s | 19.596MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/172.smt2                           |    0.067s | 21.216MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1777.smt2 |    0.068s | 20.964MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1764.smt2 |    0.068s | 20.616MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_597.smt2 |    0.069s | 20.824MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1761.smt2 |    0.069s | 20.04MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_927.smt2 |    0.069s | 20.66MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_673.smt2 |    0.070s | 19.492MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_707.smt2 |    0.071s | 20.908MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1897.smt2 |    0.071s | 20.868MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_3872.smt2 |    0.071s | 20.608MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/160.smt2                           |    0.072s | 21.388MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_728.smt2 |    0.073s | 20.628MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_753.smt2 |    0.073s | 19.564MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1726.smt2 |    0.073s | 19.604MiB| unsat | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_2_3_5.smt2        |    0.073s | 21.076MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/193.smt2                           |    0.073s | 21.136MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_2715.smt2 |    0.074s | 20.772MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_870.smt2 |    0.074s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_847.smt2 |    0.074s | 19.596MiB| unsat | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_3_5_7.smt2        |    0.074s | 21.364MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/175.smt2                           |    0.074s | 20.864MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/135.smt2                           |    0.074s | 21.676MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/023.smt2                           |    0.074s | 21.108MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1720.smt2 |    0.075s | 20.72MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_1735.smt2 |    0.075s | 20.616MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_876.smt2 |    0.075s | 20.604MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1578.smt2 |    0.075s | 19.876MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_367.smt2 |    0.075s | 20.82MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested6_true-unreach-call.i_7.smt2 |    0.075s | 20.624MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/170.smt2                           |    0.076s | 20.88MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_703.smt2 |    0.077s | 19.652MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1729.smt2 |    0.077s | 20.608MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_671.smt2 |    0.077s | 20.076MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/044.smt2                           |    0.077s | 22.42MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/067.smt2                           |    0.077s | 21.076MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1752.smt2 |    0.078s | 19.624MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_725.smt2 |    0.078s | 20.624MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/155.smt2                           |    0.078s | 21.324MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1703.smt2 |    0.079s | 20.768MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_746.smt2 |    0.080s | 20.776MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/063.smt2                           |    0.080s | 21.0MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1471.smt2 |    0.081s | 20.652MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_278.smt2 |    0.081s | 20.632MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1172.smt2 |    0.081s | 19.652MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1755.smt2 |    0.081s | 19.548MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_766.smt2 |    0.081s | 21.064MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_947.smt2 |    0.082s | 20.68MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1748.smt2 |    0.082s | 19.596MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1732.smt2 |    0.083s | 20.868MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1879.smt2 |    0.083s | 19.844MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_470.smt2 |    0.083s | 20.948MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_637.smt2 |    0.083s | 20.612MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/056.smt2                           |    0.083s | 22.396MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/049.smt2                           |    0.083s | 22.404MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/006.smt2                           |    0.083s | 21.912MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_473.smt2 |    0.084s | 20.66MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/124.smt2                           |    0.084s | 21.64MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_175.smt2 |    0.085s | 20.912MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_713.smt2 |    0.086s | 20.868MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/MADWiFi-encode_ie_ok_true-unreach-call.i_7.smt2 |    0.086s | 20.62MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/001.smt2                           |    0.086s | 20.66MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/035.smt2                           |    0.087s | 22.156MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/108.smt2                           |    0.087s | 20.876MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1817.smt2 |    0.088s | 20.732MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/077.smt2                           |    0.088s | 22.028MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/173.smt2                           |    0.088s | 21.692MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_237.smt2 |    0.089s | 19.476MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/036.smt2                           |    0.089s | 21.988MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/048.smt2                           |    0.090s | 22.16MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1072.smt2 |    0.091s | 20.616MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_597.smt2 |    0.092s | 19.644MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/030.smt2                           |    0.092s | 21.76MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/005.smt2                           |    0.092s | 21.052MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_187.smt2 |    0.093s | 19.664MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1357.smt2 |    0.093s | 20.596MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1307.smt2 |    0.093s | 19.492MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/112.smt2                           |    0.093s | 21.856MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_287.smt2 |    0.095s | 19.656MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_788.smt2 |    0.096s | 19.672MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_507.smt2 |    0.096s | 20.464MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1070.smt2 |    0.096s | 20.692MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/166.smt2                           |    0.096s | 21.2MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1874.smt2 |    0.097s | 20.66MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1749.smt2 |    0.097s | 20.624MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/047.smt2                           |    0.097s | 21.908MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/176.smt2                           |    0.097s | 20.888MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/111.smt2                           |    0.097s | 21.648MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/082.smt2                           |    0.099s | 22.416MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/013.smt2                           |    0.099s | 21.148MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/158.smt2                           |    0.099s | 21.108MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1477.smt2 |    0.100s | 20.736MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/074.smt2                           |    0.100s | 21.708MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/152.smt2                           |    0.101s | 21.636MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1887.smt2 |    0.102s | 20.636MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/071.smt2                           |    0.102s | 22.156MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/147.smt2                           |    0.102s | 21.072MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/027.smt2                           |    0.102s | 21.556MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/167.smt2                           |    0.102s | 21.192MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1117.smt2 |    0.103s | 20.8MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_71.smt2 |    0.103s | 20.748MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/190.smt2                           |    0.103s | 21.668MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/080.smt2                           |    0.103s | 21.992MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_2317.smt2 |    0.104s | 20.62MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_887.smt2 |    0.104s | 19.848MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/025.smt2                           |    0.104s | 21.392MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/188.smt2                           |    0.105s | 21.276MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_807.smt2 |    0.106s | 20.8MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/119.smt2                           |    0.107s | 21.376MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/098.smt2                           |    0.107s | 22.156MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1878.smt2 |    0.108s | 20.868MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/061.smt2                           |    0.108s | 20.64MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/034.smt2                           |    0.108s | 21.904MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/057.smt2                           |    0.109s | 22.216MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/093.smt2                           |    0.110s | 22.208MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/106.smt2                           |    0.112s | 21.148MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1781.smt2 |    0.113s | 20.892MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/043.smt2                           |    0.113s | 21.996MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/032.smt2                           |    0.113s | 21.948MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/097.smt2                           |    0.113s | 22.128MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/161.smt2                           |    0.114s | 21.144MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/095.smt2                           |    0.114s | 22.312MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1723.smt2 |    0.115s | 20.844MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/149.smt2                           |    0.115s | 21.388MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_127.smt2 |    0.116s | 20.072MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/022.smt2                           |    0.116s | 21.404MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/116.smt2                           |    0.116s | 21.888MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/142.smt2                           |    0.117s | 21.436MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/132.smt2                           |    0.117s | 21.112MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/055.smt2                           |    0.117s | 22.408MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/MADWiFi-encode_ie_ok_true-unreach-call.i_17.smt2 |    0.118s | 21.108MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/020.smt2                           |    0.120s | 21.368MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/125.smt2                           |    0.120s | 21.904MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/169.smt2                           |    0.120s | 21.136MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1679.smt2 |    0.121s | 19.832MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_179.smt2 |    0.123s | 19.888MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_678.smt2 |    0.125s | 19.512MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/185.smt2                           |    0.125s | 21.648MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1739.smt2 |    0.126s | 19.836MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_670.smt2 |    0.126s | 19.828MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1575.smt2 |    0.126s | 19.9MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_2175.smt2 |    0.126s | 19.844MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/177.smt2                           |    0.126s | 21.108MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_627.smt2 |    0.127s | 20.892MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_379.smt2 |    0.127s | 20.616MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1741.smt2 |    0.127s | 19.6MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_2147.smt2 |    0.127s | 20.844MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_762.smt2 |    0.127s | 19.88MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/180.smt2                           |    0.127s | 20.648MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/058.smt2                           |    0.128s | 22.476MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/079.smt2                           |    0.128s | 22.384MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1798.smt2 |    0.129s | 19.616MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/008.smt2                           |    0.129s | 21.752MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_763.smt2 |    0.130s | 20.72MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/042.smt2                           |    0.131s | 22.388MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/174.smt2                           |    0.131s | 21.656MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1738.smt2 |    0.132s | 20.624MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1778.smt2 |    0.133s | 21.06MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/065.smt2                           |    0.133s | 20.908MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/014.smt2                           |    0.133s | 21.52MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/157.smt2                           |    0.134s | 21.14MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/101.smt2                           |    0.134s | 22.448MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/127.smt2                           |    0.134s | 21.148MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/181.smt2                           |    0.134s | 20.892MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/002.smt2                           |    0.135s | 20.624MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/021.smt2                           |    0.135s | 20.872MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1770.smt2 |    0.136s | 20.872MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_277.smt2 |    0.136s | 21.096MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/120.smt2                           |    0.137s | 21.384MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/117.smt2                           |    0.137s | 21.908MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1707.smt2 |    0.139s | 20.66MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_817.smt2 |    0.139s | 20.908MiB| unsat | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_5_7.smt2          |    0.139s | 21.424MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/007.smt2                           |    0.139s | 21.452MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/075.smt2                           |    0.139s | 21.952MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/146.smt2                           |    0.139s | 21.368MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/091.smt2                           |    0.140s | 21.76MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1375.smt2 |    0.141s | 20.624MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/092.smt2                           |    0.141s | 22.188MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/137.smt2                           |    0.141s | 22.576MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/143.smt2                           |    0.141s | 21.62MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_2746.smt2 |    0.142s | 20.632MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/054.smt2                           |    0.143s | 22.532MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/073.smt2                           |    0.143s | 21.832MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/105.smt2                           |    0.143s | 21.14MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/076.smt2                           |    0.144s | 21.904MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1784.smt2 |    0.145s | 19.628MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1427.smt2 |    0.146s | 20.672MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/094.smt2                           |    0.147s | 22.152MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/195.smt2                           |    0.147s | 21.584MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/039.smt2                           |    0.148s | 22.092MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/062.smt2                           |    0.148s | 21.152MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_7.smt2 |    0.149s | 20.88MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_276.smt2 |    0.150s | 20.876MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/070.smt2                           |    0.150s | 21.412MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_17.smt2 |    0.151s | 20.848MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_557.smt2 |    0.151s | 19.62MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_751.smt2 |    0.151s | 20.076MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/088.smt2                           |    0.151s | 22.272MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/038.smt2                           |    0.151s | 22.168MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/123.smt2                           |    0.152s | 21.184MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_447.smt2 |    0.154s | 20.876MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1785.smt2 |    0.154s | 20.38MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/050.smt2                           |    0.154s | 22.384MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/024.smt2                           |    0.155s | 21.136MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1877.smt2 |    0.157s | 21.236MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/130.smt2                           |    0.157s | 21.608MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/003.smt2                           |    0.158s | 20.884MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/019.smt2                           |    0.158s | 21.14MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/131.smt2                           |    0.158s | 21.136MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/122.smt2                           |    0.159s | 21.248MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/148.smt2                           |    0.160s | 21.644MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/139.smt2                           |    0.160s | 20.928MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_1478.smt2 |    0.161s | 20.62MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/115.smt2                           |    0.161s | 21.396MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/089.smt2                           |    0.161s | 22.428MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/103.smt2                           |    0.163s | 21.124MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/085.smt2                           |    0.163s | 22.452MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_527.smt2 |    0.164s | 19.832MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/144.smt2                           |    0.164s | 21.168MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/187.smt2                           |    0.165s | 21.136MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/078.smt2                           |    0.165s | 22.1MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/110.smt2                           |    0.166s | 21.388MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/141.smt2                           |    0.167s | 21.148MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/171.smt2                           |    0.167s | 21.368MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/129.smt2                           |    0.168s | 21.544MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/064.smt2                           |    0.169s | 21.328MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_1757.smt2 |    0.171s | 20.848MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/015.smt2                           |    0.171s | 21.604MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/102.smt2                           |    0.172s | 22.368MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/026.smt2                           |    0.174s | 21.512MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1767.smt2 |    0.175s | 19.984MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/136.smt2                           |    0.176s | 23.148MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/Primes_true-unreach-call.c_297.smt2 |    0.177s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/121.smt2                           |    0.177s | 21.892MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/033.smt2                           |    0.177s | 22.408MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1597.smt2 |    0.178s | 20.652MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_744.smt2 |    0.179s | 20.828MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1728.smt2 |    0.181s | 21.116MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/196.smt2                           |    0.181s | 21.852MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/099.smt2                           |    0.182s | 22.3MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/040.smt2                           |    0.182s | 21.996MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/189.smt2                           |    0.183s | 21.392MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1722.smt2 |    0.184s | 20.64MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/128.smt2                           |    0.184s | 21.54MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/051.smt2                           |    0.184s | 22.44MiB| sat | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_5_7_11.smt2       |    0.185s | 21.612MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/069.smt2                           |    0.186s | 21.164MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/150.smt2                           |    0.187s | 21.616MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/083.smt2                           |    0.188s | 22.484MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/096.smt2                           |    0.188s | 22.636MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/090.smt2                           |    0.191s | 22.156MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/029.smt2                           |    0.192s | 21.68MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/053.smt2                           |    0.193s | 22.492MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/009.smt2                           |    0.194s | 20.9MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/052.smt2                           |    0.194s | 22.636MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/087.smt2                           |    0.205s | 22.112MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_874.smt2 |    0.208s | 19.616MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1170.smt2 |    0.213s | 19.844MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1475.smt2 |    0.214s | 20.884MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/010.smt2                           |    0.214s | 20.888MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1737.smt2 |    0.215s | 20.648MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/153.smt2                           |    0.215s | 20.912MiB| sat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/recHanoi03_true-unreach-call_true-termination.c_73.smt2 |    0.216s | 19.632MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/179.smt2                           |    0.216s | 21.112MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_1795.smt2 |    0.217s | 20.912MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/114.smt2                           |    0.218s | 21.512MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/004.smt2                           |    0.218s | 21.196MiB| unsat | 0 |  |  |
|non-incremental/LIA/UltimateAutomizer/nested9_true-unreach-call.i_574.smt2 |    0.219s | 20.376MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/140.smt2                           |    0.221s | 20.872MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/133.smt2                           |    0.222s | 21.78MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/186.smt2                           |    0.222s | 20.848MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/100.smt2                           |    0.224s | 22.344MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/165.smt2                           |    0.230s | 21.632MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/086.smt2                           |    0.243s | 22.376MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/138.smt2                           |    0.244s | 22.728MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/045.smt2                           |    0.248s | 22.292MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/084.smt2                           |    0.262s | 22.2MiB| sat | 0 |  |  |
|non-incremental/LIA/psyco/046.smt2                           |    0.267s | 22.408MiB| unsat | 0 |  |  |
|non-incremental/LIA/psyco/041.smt2                           |    0.283s | 22.036MiB| sat | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_7_11_13.smt2      |    0.331s | 22.06MiB| sat | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_7_11.smt2         |    0.459s | 22.3MiB| sat | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_11_13.smt2        |    0.822s | 23.288MiB| sat | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_11_13_17.smt2     |    2.029s | 24.444MiB| sat | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_13_17_19.smt2     |    4.197s | 25.236MiB| sat | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_13_17.smt2        |    7.347s | 26.548MiB| sat | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_17_19_23.smt2     |    9.003s | 27.104MiB| sat | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_19_23_29.smt2     |   15.845s | 29.736MiB| sat | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_17_19.smt2        |   16.650s | 30.592MiB| sat | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_251_257_263.smt2  |   20.012s | 33.028MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_47_53.smt2        |   20.012s | 33.716MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_257_263_269.smt2  |   20.013s | 29.996MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_53_59.smt2        |   20.013s | 33.712MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_191_193_197.smt2  |   20.013s | 34.74MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_277_281.smt2      |   20.014s | 29.448MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_109_113_127.smt2  |   20.014s | 33.612MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_241_251_257.smt2  |   20.016s | 38.468MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_131_137_139.smt2  |   20.016s | 35.044MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_59_61_67.smt2     |   20.016s | 36.204MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_23_29.smt2        |   20.016s | 30.812MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_31_37_41.smt2     |   20.016s | 30.4MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_83_89.smt2        |   20.018s | 35.6MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_79_83_89.smt2     |   20.018s | 33.988MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_127_131_137.smt2  |   20.019s | 36.564MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_179_181_191.smt2  |   20.020s | 30.808MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_73_79_83.smt2     |   20.020s | 36.664MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_197_199_211.smt2  |   20.021s | 31.496MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_29_31.smt2        |   20.022s | 31.716MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_23_29_31.smt2     |   20.022s | 31.192MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_53_59_61.smt2     |   20.023s | 31.44MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_73_79.smt2        |   20.023s | 30.86MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_223_227_229.smt2  |   20.024s | 30.204MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_277_281_283.smt2  |   20.024s | 28.912MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_271_277.smt2      |   20.025s | 30.148MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_71_73.smt2        |   20.025s | 32.604MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_241_251.smt2      |   20.026s | 46.584MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_193_197_199.smt2  |   20.026s | 35.236MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_281_283_293.smt2  |   20.027s | 32.084MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_113_127.smt2      |   20.027s | 35.484MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_239_241_251.smt2  |   20.027s | 33.896MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_131_137.smt2      |   20.028s | 33.932MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_19_23.smt2        |   20.028s | 31.58MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_109_113.smt2      |   20.029s | 27.524MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_257_263.smt2      |   20.029s | 37.44MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_233_239.smt2      |   20.029s | 32.392MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_263_269_271.smt2  |   20.029s | 32.544MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_43_47_53.smt2     |   20.029s | 32.732MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_157_163.smt2      |   20.029s | 28.904MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_149_151.smt2      |   20.030s | 33.82MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_89_97_101.smt2    |   20.030s | 38.416MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_227_229_233.smt2  |   20.030s | 33.704MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_61_67_71.smt2     |   20.030s | 33.296MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_223_227.smt2      |   20.031s | 36.408MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_79_83.smt2        |   20.031s | 29.772MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_239_241.smt2      |   20.031s | 39.156MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_197_199.smt2      |   20.031s | 35.888MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_37_41.smt2        |   20.032s | 29.192MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_211_223.smt2      |   20.032s | 32.352MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_229_233.smt2      |   20.032s | 29.724MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_139_149.smt2      |   20.032s | 37.276MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_157_163_167.smt2  |   20.032s | 39.852MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_61_67.smt2        |   20.033s | 29.976MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_233_239_241.smt2  |   20.034s | 33.144MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_281_283.smt2      |   20.035s | 39.532MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_149_151_157.smt2  |   20.036s | 37.868MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_163_167_173.smt2  |   20.036s | 32.62MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_137_139_149.smt2  |   20.036s | 35.9MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_211_223_227.smt2  |   20.036s | 33.46MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_139_149_151.smt2  |   20.036s | 34.756MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_151_157.smt2      |   20.036s | 29.824MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_107_109.smt2      |   20.040s | 35.588MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_43_47.smt2        |   20.040s | 32.756MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_37_41_43.smt2     |   20.040s | 33.5MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_199_211_223.smt2  |   20.042s | 32.96MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_193_197.smt2      |   20.043s | 32.484MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_101_103.smt2      |   20.043s | 34.704MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_263_269.smt2      |   20.043s | 34.096MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_179_181.smt2      |   20.044s | 35.64MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_97_101.smt2       |   20.044s | 31.4MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_269_271_277.smt2  |   20.044s | 33.228MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_227_229.smt2      |   20.044s | 37.068MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_29_31_37.smt2     |   20.044s | 32.624MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_113_127_131.smt2  |   20.045s | 38.204MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_67_71_73.smt2     |   20.045s | 30.696MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_71_73_79.smt2     |   20.046s | 33.608MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_107_109_113.smt2  |   20.069s | 32.732MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_41_43.smt2        |   20.075s | 32.264MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_269_271.smt2      |   20.083s | 38.48MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_103_107_109.smt2  |   20.084s | 33.852MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_163_167.smt2      |   20.088s | 30.384MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_59_61.smt2        |   20.088s | 33.172MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_251_257.smt2      |   20.105s | 37.296MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_191_193.smt2      |   20.107s | 36.512MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_101_103_107.smt2  |   20.111s | 35.2MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_67_71.smt2        |   20.111s | 33.48MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_83_89_97.smt2     |   20.112s | 34.396MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_127_131.smt2      |   20.112s | 29.844MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_181_191.smt2      |   20.113s | 31.36MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_199_211.smt2      |   20.114s | 36.148MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_271_277_281.smt2  |   20.116s | 38.608MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_229_233_239.smt2  |   20.117s | 34.584MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_173_179.smt2      |   20.119s | 35.512MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_167_173_179.smt2  |   20.119s | 31.528MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_181_191_193.smt2  |   20.119s | 39.988MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_31_37.smt2        |   20.120s | 31.832MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_137_139.smt2      |   20.123s | 37.156MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_103_107.smt2      |   20.132s | 34.384MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_89_97.smt2        |   20.142s | 30.968MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_167_173.smt2      |   20.145s | 40.908MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_47_53_59.smt2     |   20.148s | 33.872MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_97_101_103.smt2   |   20.148s | 35.736MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_41_43_47.smt2     |   20.149s | 33.22MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_151_157_163.smt2  |   20.149s | 36.292MiB| timeout | 0 |  |  |
|non-incremental/LIA/20250213-Frobenius/fcp_173_179_181.smt2  |   20.153s | 31.724MiB| timeout | 0 |  |  |
|non-incremental/LIA/tptp/ARI045=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/NUM868=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/ARI005=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/NUM893=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/ARI039=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/ARI040=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/ARI013=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/NUM870=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/NUM874=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/NUM865=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/NUM889=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/NUM915=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/ARI031=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/ARI018=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/ARI032=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/ARI572=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/NUM897=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/ARI044=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/NUM899=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/ARI052=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/ARI054=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/ARI012=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/NUM917=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/NUM918=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/NUM875=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/ARI011=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/NUM869=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/ARI591=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/ARI025=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/NUM864=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/ARI083=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/ARI056=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/NUM898=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/ARI017=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/ARI053=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/ARI027=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/ARI592=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/NUM896=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/NUM916=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/NUM871=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/ARI079=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/ARI004=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/ARI590=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/NUM895=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/ARI026=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
|non-incremental/LIA/tptp/ARI038=1.smt2                       | 1000.000s | -1B| unset | -1 |  |  |
