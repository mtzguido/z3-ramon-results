# .

* SAT 37
* UNSAT 101
* TIMEOUT 55
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: UFBV.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/UFBV.tar.zst?download=1
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
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-seq-fixpoint-1.smt2 |    0.024s | 19.784MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-synabs-fixpoint-4.smt2 |    0.025s | 19.892MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/AR-fixpoint-4.smt2 |    0.026s | 20.384MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/AR-fixpoint-10.smt2 |    0.028s | 20.568MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap2-fixpoint-4.smt2 |    0.030s | 19.628MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/itc-b13-fixpoint-1.smt2 |    0.054s | 19.884MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/AR-fixpoint-9.smt2 |    0.055s | 20.524MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-dyn-partition-fixpoint-2.smt2 |    0.055s | 19.632MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap2-fixpoint-8.smt2 |    0.056s | 20.12MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-seq-fixpoint-3.smt2 |    0.057s | 19.792MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap2-fixpoint-2.smt2 |    0.057s | 19.808MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap2-fixpoint-5.smt2 |    0.057s | 20.036MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap1-fixpoint-4.smt2 |    0.059s | 19.84MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-synabs-fixpoint-3.smt2 |    0.059s | 19.7MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-synabs-fixpoint-2.smt2 |    0.060s | 19.62MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap1-fixpoint-9.smt2 |    0.061s | 19.832MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-synabs-fixpoint-8.smt2 |    0.063s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap1-fixpoint-10.smt2 |    0.065s | 20.1MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap1-fixpoint-1.smt2 |    0.065s | 20.084MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap1-fixpoint-3.smt2 |    0.067s | 20.108MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap2-fixpoint-9.smt2 |    0.072s | 19.852MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap2-fixpoint-3.smt2 |    0.072s | 19.852MiB| sat | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/easy0.smt2         |    0.076s | 23.528MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-dyn-partition-fixpoint-8.smt2 |    0.076s | 19.872MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-seq-fixpoint-9.smt2 |    0.078s | 20.08MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/itc-b13-fixpoint-2.smt2 |    0.078s | 20.244MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-synabs-fixpoint-7.smt2 |    0.080s | 19.84MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-seq-fixpoint-10.smt2 |    0.081s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap1-fixpoint-6.smt2 |    0.083s | 19.868MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-dyn-partition-fixpoint-1.smt2 |    0.083s | 19.844MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap1-fixpoint-5.smt2 |    0.083s | 19.864MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-seq-fixpoint-4.smt2 |    0.083s | 19.856MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2/gcc/231_gcc.smt2        |    0.084s | 21.644MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-dyn-partition-fixpoint-7.smt2 |    0.084s | 19.84MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/AR-fixpoint-3.smt2 |    0.086s | 20.364MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-seq-fixpoint-5.smt2 |    0.088s | 19.628MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/652_ph7.smt2 |    0.089s | 21.864MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-synabs-fixpoint-6.smt2 |    0.089s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-synabs-fixpoint-9.smt2 |    0.089s | 19.916MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-synabs-fixpoint-1.smt2 |    0.090s | 19.592MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/701_ph7.smt2 |    0.092s | 23.692MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/AR-fixpoint-6.smt2 |    0.092s | 20.404MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap2-fixpoint-1.smt2 |    0.092s | 19.604MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-pipeline-fixpoint-1.smt2 |    0.093s | 21.064MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/easy3.smt2         |    0.094s | 23.544MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/AR-fixpoint-5.smt2 |    0.094s | 20.22MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-dyn-partition-fixpoint-4.smt2 |    0.095s | 19.82MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-dyn-partition-fixpoint-5.smt2 |    0.095s | 20.0MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/AR-fixpoint-2.smt2 |    0.095s | 20.232MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-dyn-partition-fixpoint-3.smt2 |    0.096s | 19.86MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap1-fixpoint-2.smt2 |    0.097s | 20.108MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/AR-fixpoint-8.smt2 |    0.097s | 20.588MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/usb-phy-fixpoint-1.smt2 |    0.097s | 21.632MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-dyn-partition-fixpoint-9.smt2 |    0.097s | 20.104MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap2-fixpoint-6.smt2 |    0.098s | 20.068MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-seq-fixpoint-8.smt2 |    0.099s | 20.088MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-synabs-fixpoint-5.smt2 |    0.099s | 19.884MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap2-fixpoint-10.smt2 |    0.100s | 20.108MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-seq-fixpoint-2.smt2 |    0.100s | 19.632MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap2-fixpoint-7.smt2 |    0.101s | 19.644MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-dyn-partition-fixpoint-6.smt2 |    0.101s | 20.1MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap1-fixpoint-7.smt2 |    0.101s | 19.9MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-seq-fixpoint-7.smt2 |    0.102s | 19.88MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/sqlite3/776_sqlite3.smt2 |    0.103s | 22.144MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-synabs-fixpoint-10.smt2 |    0.103s | 19.908MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-swap1-fixpoint-8.smt2 |    0.103s | 19.852MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/AR-fixpoint-7.smt2 |    0.103s | 20.412MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/547_ph7.smt2 |    0.104s | 20.876MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-equiv-fixpoint-1.smt2 |    0.104s | 21.184MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-dyn-partition-fixpoint-10.smt2 |    0.106s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2/ph7/570_ph7.smt2        |    0.108s | 22.16MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/533_ph7.smt2 |    0.109s | 21.384MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/409_ph7.smt2 |    0.111s | 21.576MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-seq-fixpoint-6.smt2 |    0.114s | 19.856MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/AR-fixpoint-1.smt2 |    0.114s | 20.576MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/sdlx-fixpoint-1.smt2 |    0.118s | 20.42MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/408_ph7.smt2 |    0.119s | 20.944MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/cache-coherence-2-fixpoint-1.smt2 |    0.120s | 21.656MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/sqlite3/931_sqlite3.smt2 |    0.121s | 21.164MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/sqlite3/847_sqlite3.smt2 |    0.121s | 21.136MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/sdlx-fixpoint-2.smt2 |    0.121s | 22.276MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/473_ph7.smt2 |    0.122s | 22.18MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-pipeline-fixpoint-2.smt2 |    0.122s | 21.384MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/sqlite3/940_sqlite3.smt2 |    0.123s | 22.316MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/gcc/248_gcc.smt2 |    0.127s | 22.252MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-pipeline-fixpoint-3.smt2 |    0.127s | 22.212MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/itc-b13-fixpoint-3.smt2 |    0.128s | 21.012MiB| sat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/sqlite3/951_sqlite3.smt2 |    0.130s | 24.2MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/402_ph7.smt2 |    0.132s | 22.152MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/ethernet-fixpoint-1.smt2 |    0.136s | 22.908MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/pi-bus-fixpoint-1.smt2 |    0.139s | 23.728MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/cache-coherence-3-fixpoint-1.smt2 |    0.151s | 23.16MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/itc-b13-fixpoint-5.smt2 |    0.154s | 22.428MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/itc-b13-fixpoint-4.smt2 |    0.155s | 21.324MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/itc-b13-fixpoint-6.smt2 |    0.176s | 22.42MiB| sat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/gcc/131_gcc.smt2 |    0.177s | 24.448MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/sdlx-fixpoint-3.smt2 |    0.187s | 23.708MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/itc-b13-fixpoint-7.smt2 |    0.204s | 23.328MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/cache-coherence-2-fixpoint-2.smt2 |    0.227s | 25.32MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/usb-phy-fixpoint-2.smt2 |    0.228s | 26.088MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2/gzip/258_gzip.smt2      |    0.231s | 23.184MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/easy2.smt2         |    0.231s | 31.0MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/itc-b13-fixpoint-8.smt2 |    0.268s | 24.748MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/itc-b13-fixpoint-9.smt2 |    0.336s | 24.984MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/cache-coherence-3-fixpoint-2.smt2 |    0.403s | 30.26MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/itc-b13-fixpoint-10.smt2 |    0.408s | 25.78MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/sdlx-fixpoint-4.smt2 |    0.423s | 25.288MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/cache-coherence-2-fixpoint-3.smt2 |    0.444s | 30.688MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/ethernet-fixpoint-2.smt2 |    0.485s | 29.344MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/hard4.smt2         |    0.524s | 51.504MiB| sat | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/easy1.smt2         |    0.534s | 39.756MiB| sat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/678_ph7.smt2 |    0.538s | 28.928MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/pi-bus-fixpoint-2.smt2 |    0.589s | 32.136MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/492_ph7.smt2 |    0.590s | 65.024MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/easy4.smt2         |    0.641s | 48.136MiB| sat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/gcc/152_gcc.smt2 |    0.650s | 65.188MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/hard0.smt2         |    0.663s | 47.516MiB| sat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2/sqlite3/977_sqlite3.smt2 |    0.677s | 22.7MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/cache-coherence-2-fixpoint-4.smt2 |    0.771s | 37.444MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/usb-phy-fixpoint-3.smt2 |    0.822s | 40.872MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/cache-coherence-3-fixpoint-3.smt2 |    0.830s | 41.052MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/496_ph7.smt2 |    1.226s | 57.288MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/medium1.smt2       |    1.334s | 70.54MiB| sat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/cache-coherence-2-fixpoint-5.smt2 |    1.349s | 47.112MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/pi-bus-fixpoint-3.smt2 |    1.362s | 44.76MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/ethernet-fixpoint-3.smt2 |    1.439s | 43.9MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/medium5.smt2       |    1.529s | 53.128MiB| sat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/504_ph7.smt2 |    1.977s | 99.0MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2/oggenc/345_oggenc.smt2  |    2.223s | 89.692MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/gcc/212_gcc.smt2 |    2.318s | 179.0MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/usb-phy-fixpoint-4.smt2 |    2.362s | 59.264MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/cache-coherence-2-fixpoint-6.smt2 |    2.722s | 70.628MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/sqlite3/887_sqlite3.smt2 |    2.769s | 168.0MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/oggenc/379_oggenc.smt2 |    2.803s | 169.0MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/ethernet-fixpoint-4.smt2 |    3.086s | 60.352MiB| unsat | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/usb-phy-fixpoint-5.smt2 |    3.720s | 72.004MiB| unsat | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/medium2.smt2       |    4.535s | 55.86MiB| sat | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/hard1.smt2         |    7.953s | 147.0MiB| sat | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/hard3.smt2         |   20.030s | 85.368MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/medium4.smt2       |   20.036s | 132.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-pipeline-fixpoint-6.smt2 |   20.037s | 118.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/sdlx-fixpoint-9.smt2 |   20.037s | 296.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/sdlx-fixpoint-10.smt2 |   20.039s | 93.784MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/medium0.smt2       |   20.042s | 245.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_unsat/easy.smt2        |   20.054s | 137.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_unsat/hard.smt2        |   20.062s | 182.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-pipeline-fixpoint-8.smt2 |   20.067s | 98.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_unsat/medium.smt2      |   20.068s | 243.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-pipeline-fixpoint-10.smt2 |   20.076s | 99.176MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-equiv-fixpoint-6.smt2 |   20.078s | 177.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-equiv-fixpoint-5.smt2 |   20.084s | 168.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-equiv-fixpoint-8.smt2 |   20.086s | 166.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-pipeline-fixpoint-5.smt2 |   20.088s | 146.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/442_ph7.smt2 |   20.090s | 64.34MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-equiv-fixpoint-3.smt2 |   20.091s | 163.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-pipeline-fixpoint-9.smt2 |   20.099s | 108.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-equiv-fixpoint-2.smt2 |   20.099s | 31.24MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/668_ph7.smt2 |   20.105s | 44.028MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/oggenc/388_oggenc.smt2 |   20.112s | 67.24MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/613_ph7.smt2 |   20.113s | 86.784MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/hard2.smt2         |   20.115s | 126.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-equiv-fixpoint-4.smt2 |   20.115s | 166.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/medium3.smt2       |   20.121s | 241.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-pipeline-fixpoint-7.smt2 |   20.121s | 154.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/sdlx-fixpoint-8.smt2 |   20.122s | 547.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210330-PEak/uf_sat/easy5.smt2         |   20.130s | 245.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-equiv-fixpoint-10.smt2 |   20.133s | 206.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-pipeline-fixpoint-4.smt2 |   20.134s | 173.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/sdlx-fixpoint-6.smt2 |   20.135s | 561.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-equiv-fixpoint-7.smt2 |   20.136s | 192.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/small-equiv-fixpoint-9.smt2 |   20.145s | 235.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/sdlx-fixpoint-7.smt2 |   20.158s | 305.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/405_ph7.smt2 |   20.201s | 637.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20230314-Jaroslav-Bendik-Certora/52759_b3ecd2335fd16ec2eee2_9_UFBV.smt2 |   20.203s | 619.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/wintersteiger/fmsd13/fixpoint/sdlx-fixpoint-5.smt2 |   20.211s | 593.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2/gcc/108_gcc.smt2        |   20.351s | 1173.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/643_ph7.smt2 |   20.560s | 2719.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/445_ph7.smt2 |   20.571s | 2057.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/731_ph7.smt2 |   20.692s | 4491.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/oggenc/385_oggenc.smt2 |   20.746s | 4393.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/566_ph7.smt2 |   20.891s | 8353.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/sqlite3/935_sqlite3.smt2 |   20.923s | 4864.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/gcc/144_gcc.smt2 |   20.948s | 5263.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/sqlite3/808_sqlite3.smt2 |   20.955s | 4699.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/646_ph7.smt2 |   21.009s | 5874.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/617_ph7.smt2 |   21.085s | 8781.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/sqlite3/971_sqlite3.smt2 |   21.090s | 6132.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/sqlite3/783_sqlite3.smt2 |   21.112s | 8611.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/655_ph7.smt2 |   21.124s | 8781.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/oggenc/369_oggenc.smt2 |   21.131s | 8224.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/562_ph7.smt2 |   21.221s | 8199.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/gcc/095_gcc.smt2 |   21.331s | 7723.0MiB| timeout | 0 |  |  |
|non-incremental/UFBV/20210301-Alive2-partial-undef/ph7/491_ph7.smt2 |   21.368s | 8583.0MiB| timeout | 0 |  |  |
