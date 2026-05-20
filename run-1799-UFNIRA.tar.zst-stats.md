# .

* SAT 15
* UNSAT 95
* TIMEOUT 150
* UNKNOWN 6

* UNSET 0

* ERROR 0

# Meta data

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


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U72_sol1.smt2 |    0.026s | 20.012MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U17.smt2 |    0.029s | 20.4MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U1.smt2 |    0.031s | 20.892MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U72.smt2 |    0.034s | 20.512MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U81.smt2 |    0.035s | 20.468MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C4_sol1.smt2 |    0.037s | 20.036MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U42_sol1.smt2 |    0.038s | 20.0MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U9_sol1.smt2 |    0.044s | 20.288MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U57.smt2 |    0.045s | 20.328MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U72_sol2.smt2 |    0.046s | 19.904MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C13_sol1.smt2 |    0.047s | 20.424MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C5.smt2 |    0.050s | 20.62MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U75.smt2 |    0.055s | 20.628MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U44_sol1.smt2 |    0.057s | 20.756MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U66.smt2 |    0.057s | 21.072MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U89.smt2 |    0.067s | 20.852MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U66_sol1.smt2 |    0.068s | 20.14MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U82_sol1.smt2 |    0.070s | 20.628MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U62_sol1.smt2 |    0.070s | 20.372MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U54_sol2.smt2 |    0.071s | 20.348MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U90_sol1.smt2 |    0.072s | 20.408MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U46_sol2.smt2 |    0.072s | 20.432MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U41_sol2.smt2 |    0.073s | 19.904MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U48.smt2 |    0.073s | 21.064MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U2_sol1.smt2 |    0.074s | 20.156MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U64_sol1.smt2 |    0.075s | 19.988MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U89_sol1.smt2 |    0.075s | 20.24MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U56_sol2.smt2 |    0.075s | 20.144MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U20.smt2 |    0.077s | 20.632MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U71_sol1.smt2 |    0.080s | 20.144MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U50_sol1.smt2 |    0.080s | 20.048MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U68_sol1.smt2 |    0.082s | 20.336MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U91_sol2.smt2 |    0.083s | 19.892MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U23_sol1.smt2 |    0.087s | 20.372MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U20_sol2.smt2 |    0.088s | 20.356MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U11_sol1.smt2 |    0.091s | 20.832MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U23.smt2 |    0.091s | 21.368MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U44_sol2.smt2 |    0.092s | 20.804MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U87_sol2.smt2 |    0.094s | 20.02MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C12_sol1.smt2 |    0.094s | 20.148MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U67_sol1.smt2 |    0.094s | 20.364MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U66_sol2.smt2 |    0.096s | 20.008MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C2_sol1.smt2 |    0.096s | 20.104MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U24_sol1.smt2 |    0.096s | 20.144MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U87_sol1.smt2 |    0.096s | 20.104MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C9_sol1.smt2 |    0.097s | 20.648MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U6_sol1.smt2 |    0.097s | 20.584MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U49_sol2.smt2 |    0.098s | 20.124MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U62.smt2 |    0.098s | 20.864MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U41_sol3.smt2 |    0.099s | 20.4MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U56_sol1.smt2 |    0.099s | 20.124MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U5_sol1.smt2 |    0.099s | 19.928MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U25_sol1.smt2 |    0.099s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C6_sol1.smt2 |    0.100s | 20.14MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U53_sol1.smt2 |    0.100s | 20.324MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C3_sol1.smt2 |    0.100s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U92_sol1.smt2 |    0.100s | 20.104MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U48_sol1.smt2 |    0.100s | 19.916MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U51_sol1.smt2 |    0.100s | 20.148MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U45_sol1.smt2 |    0.100s | 20.136MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U10_sol1.smt2 |    0.100s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U49_sol1.smt2 |    0.100s | 20.016MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U46_sol1.smt2 |    0.100s | 20.304MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U51.smt2 |    0.100s | 20.896MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U41_sol1.smt2 |    0.101s | 20.116MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U48_sol2.smt2 |    0.101s | 19.908MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U68.smt2 |    0.101s | 20.868MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U57_sol1.smt2 |    0.103s | 20.744MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U81_sol1.smt2 |    0.103s | 20.408MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U76_sol1.smt2 |    0.104s | 20.476MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U8_sol1.smt2 |    0.104s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U37_sol1.smt2 |    0.105s | 21.248MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U14_sol1.smt2 |    0.105s | 20.62MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U26_sol2.smt2 |    0.106s | 20.84MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U75_sol2.smt2 |    0.106s | 20.136MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U93_sol1.smt2 |    0.109s | 20.628MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U13_sol1.smt2 |    0.116s | 20.268MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C10.smt2 |    0.116s | 20.124MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U3_sol1.smt2 |    0.117s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U45_sol2.smt2 |    0.117s | 19.888MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U20_sol3.smt2 |    0.117s | 20.024MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C9a_sol1.smt2 |    0.117s | 20.092MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U20_sol1.smt2 |    0.118s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U75_sol1.smt2 |    0.118s | 20.124MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U39_sol1.smt2 |    0.118s | 20.152MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U19_sol1.smt2 |    0.118s | 20.352MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U7_sol1.smt2 |    0.119s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U25_sol2.smt2 |    0.119s | 20.368MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C10_sol1.smt2 |    0.120s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U50_sol3.smt2 |    0.121s | 20.116MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U46.smt2 |    0.121s | 20.756MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U41.smt2 |    0.121s | 20.62MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U71.smt2 |    0.121s | 20.676MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C1_sol1.smt2 |    0.122s | 20.352MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U50_sol2.smt2 |    0.123s | 19.916MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U91_sol1.smt2 |    0.124s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U8_sol2.smt2 |    0.127s | 20.032MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U27_sol1.smt2 |    0.127s | 20.68MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U4_sol1.smt2 |    0.127s | 20.836MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U17_sol1.smt2 |    0.131s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U26_sol1.smt2 |    0.133s | 20.124MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U61_sol1.smt2 |    0.136s | 20.876MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U54_sol1.smt2 |    0.137s | 21.092MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U11.smt2 |    0.143s | 20.584MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U26.smt2 |    0.143s | 22.404MiB| sat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C5_sol1.smt2 |    0.144s | 20.62MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U4.smt2 |    0.146s | 21.244MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U79.smt2 |    0.147s | 32.372MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U12_sol1.smt2 |    0.231s | 20.656MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C6.smt2 |    4.924s | 45.288MiB| unknown | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U7.smt2 |    5.812s | 26.58MiB| unknown | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U14.smt2 |    6.571s | 30.392MiB| unknown | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U14.smt2 |    7.476s | 29.872MiB| unknown | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U16_sol1.smt2 |    9.796s | 33.108MiB| unknown | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U17.smt2 |    9.819s | 143.0MiB| unknown | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U40_sol1.smt2 |   11.689s | 21.344MiB| unsat | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C8_sol1.smt2 |   20.021s | 40.132MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C9a.smt2 |   20.024s | 74.276MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U12.smt2 |   20.027s | 28.864MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U38.smt2 |   20.028s | 39.728MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U53.smt2 |   20.040s | 49.6MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C5.smt2 |   20.047s | 22.904MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C9.smt2 |   20.048s | 38.144MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U34.smt2 |   20.049s | 84.092MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U93.smt2 |   20.052s | 27.752MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U10.smt2 |   20.057s | 104.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C4.smt2 |   20.058s | 104.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U26.smt2 |   20.060s | 33.172MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U39.smt2 |   20.070s | 66.08MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U93.smt2 |   20.070s | 28.552MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U76.smt2 |   20.072s | 28.04MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U88.smt2 |   20.074s | 36.992MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U45.smt2 |   20.074s | 28.516MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U90.smt2 |   20.075s | 99.844MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U11.smt2 |   20.076s | 56.56MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U12.smt2 |   20.077s | 33.164MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U87.smt2 |   20.077s | 70.752MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C7.smt2 |   20.083s | 29.148MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U30.smt2 |   20.084s | 23.952MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U76.smt2 |   20.086s | 27.592MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C7_sol1.smt2 |   20.087s | 32.9MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C6.smt2 |   20.089s | 38.352MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U27.smt2 |   20.090s | 25.392MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U1.smt2 |   20.094s | 24.06MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U4.smt2 |   20.095s | 545.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U6.smt2 |   20.095s | 123.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U57.smt2 |   20.097s | 152.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C9.smt2 |   20.100s | 55.928MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U27.smt2 |   20.102s | 23.292MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C9a.smt2 |   20.104s | 42.984MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U15_sol1.smt2 |   20.116s | 29.596MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U45.smt2 |   20.119s | 229.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C3.smt2 |   20.125s | 65.336MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U23.smt2 |   20.129s | 47.6MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U7.smt2 |   20.130s | 61.74MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U1_sol1.smt2 |   20.131s | 26.656MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U10.smt2 |   20.131s | 298.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U66.smt2 |   20.133s | 32.612MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U81.smt2 |   20.135s | 56.832MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C3.smt2 |   20.136s | 92.936MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U47.smt2 |   20.137s | 27.884MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U53.smt2 |   20.141s | 48.96MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U39.smt2 |   20.141s | 335.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C7.smt2 |   20.144s | 28.664MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C13.smt2 |   20.148s | 266.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U33.smt2 |   20.151s | 172.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U44.smt2 |   20.156s | 41.868MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U90.smt2 |   20.156s | 96.668MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U9.smt2 |   20.156s | 153.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U28.smt2 |   20.181s | 312.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C10.smt2 |   20.193s | 265.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U33.smt2 |   20.198s | 175.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U6.smt2 |   20.202s | 191.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U44.smt2 |   20.222s | 579.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C13.smt2 |   20.227s | 239.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U33_sol1.smt2 |   20.241s | 610.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U16.smt2 |   20.245s | 267.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U9.smt2 |   20.262s | 285.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C4.smt2 |   20.264s | 298.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C2.smt2 |   20.267s | 551.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U72.smt2 |   20.299s | 302.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U16.smt2 |   20.322s | 986.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C8.smt2 |   20.379s | 480.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U19.smt2 |   20.394s | 725.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C8.smt2 |   20.406s | 1462.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U68.smt2 |   20.423s | 481.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U70.smt2 |   20.449s | 582.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U37.smt2 |   20.482s | 1875.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U91.smt2 |   20.532s | 631.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U5.smt2 |   20.556s | 1289.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U91.smt2 |   20.582s | 1333.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U71.smt2 |   20.651s | 737.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U21.smt2 |   20.665s | 3520.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U92.smt2 |   20.750s | 4296.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U51.smt2 |   20.783s | 1404.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U43.smt2 |   20.978s | 1988.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U92.smt2 |   20.990s | 1530.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U8.smt2 |   21.077s | 2399.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U54.smt2 |   21.091s | 2844.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C11.smt2 |   21.096s | 2367.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U56.smt2 |   21.106s | 2869.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U87.smt2 |   21.124s | 1800.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U29.smt2 |   21.151s | 3093.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U19.smt2 |   21.167s | 2010.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U37.smt2 |   21.172s | 2587.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U67.smt2 |   21.181s | 2262.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U48.smt2 |   21.203s | 2553.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C12.smt2 |   21.231s | 2784.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U15.smt2 |   21.232s | 2744.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U41.smt2 |   21.262s | 2750.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U3.smt2 |   21.263s | 2813.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U21_sol1.smt2 |   21.275s | 3096.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U56.smt2 |   21.288s | 2894.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U50.smt2 |   21.304s | 2983.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C11.smt2 |   21.316s | 2331.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C12.smt2 |   21.321s | 2711.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U67.smt2 |   21.326s | 2966.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C1.smt2 |   21.330s | 3847.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U15.smt2 |   21.358s | 3520.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U22_sol1.smt2 |   21.365s | 2360.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U21.smt2 |   21.365s | 3521.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U62.smt2 |   21.371s | 2483.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U40.smt2 |   21.386s | 2339.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U22.smt2 |   21.389s | 2393.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U73.smt2 |   21.394s | 4414.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U54.smt2 |   21.413s | 3336.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U13.smt2 |   21.420s | 3257.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U43.smt2 |   21.422s | 2422.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U73_sol1.smt2 |   21.427s | 3540.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U61.smt2 |   21.436s | 2606.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U61.smt2 |   21.462s | 2498.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U22.smt2 |   21.467s | 2478.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U42.smt2 |   21.524s | 4472.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U73.smt2 |   21.529s | 4382.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U29.smt2 |   21.533s | 3043.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U31.smt2 |   21.561s | 3069.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U3.smt2 |   21.567s | 4225.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U46.smt2 |   21.583s | 3236.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_C11_sol1.smt2 |   21.616s | 2971.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U24.smt2 |   21.616s | 3728.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U25.smt2 |   21.617s | 3310.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U49.smt2 |   21.636s | 3493.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_C2.smt2 |   21.636s | 3923.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U50.smt2 |   21.643s | 3229.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U82.smt2 |   21.645s | 4042.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U75.smt2 |   21.652s | 7980.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U29_sol1.smt2 |   21.658s | 4575.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U20.smt2 |   21.660s | 2927.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U65.smt2 |   21.674s | 3707.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U40.smt2 |   21.674s | 4024.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U2.smt2 |   21.682s | 4478.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U8.smt2 |   21.707s | 3127.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U82.smt2 |   21.718s | 3899.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U49.smt2 |   21.718s | 4072.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U64.smt2 |   21.742s | 4530.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U25.smt2 |   21.748s | 4260.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_C1.smt2 |   21.825s | 7344.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U15_sol2.smt2 |   21.835s | 3523.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/prove/problem_U89.smt2 |   21.839s | 7370.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U2.smt2 |   21.891s | 4308.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/check/problem_U43_sol1.smt2 |   21.953s | 4849.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U64.smt2 |   21.971s | 3768.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U24.smt2 |   22.063s | 4013.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U13.smt2 |   22.119s | 4438.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U5.smt2 |   22.125s | 4750.0MiB| timeout | 0 |  |  |
|non-incremental/UFNIRA/20240414-funcprobs/find/problem_U42.smt2 |   22.205s | 4781.0MiB| timeout | 0 |  |  |
