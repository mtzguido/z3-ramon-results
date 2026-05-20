# .

* SAT 0
* UNSAT 24
* TIMEOUT 0
* UNKNOWN 0

* UNSET 0

* ERROR 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: UFBVDTLIA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/UFBVDTLIA.tar.zst?download=1
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
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._03.smt2 |    0.024s | 19.856MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.get_retire_expire._01.smt2 |    0.024s | 19.648MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._32.smt2 |    0.025s | 19.892MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_is_committed._01.smt2 |    0.027s | 19.812MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_retire_expire._02.smt2 |    0.031s | 20.8MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._04.smt2 |    0.032s | 19.624MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._01.smt2 |    0.033s | 19.644MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_is_zero_init._03.smt2 |    0.033s | 20.86MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_in_full._01.smt2 |    0.033s | 20.912MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._03.smt2 |    0.034s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._06.smt2 |    0.034s | 20.344MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2pa._01.smt2 |    0.034s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._01.smt2 |    0.034s | 19.868MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._01.smt2 |    0.035s | 20.116MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._06.smt2 |    0.035s | 20.872MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._05.smt2 |    0.035s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_is_committed._02.smt2 |    0.035s | 20.844MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._25.smt2 |    0.041s | 21.396MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._12.smt2 |    0.042s | 20.904MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._07.smt2 |    0.052s | 20.116MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._16.smt2 |    0.054s | 20.624MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._05.smt2 |    0.060s | 21.172MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._35.smt2 |    0.061s | 21.12MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTLIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_auto._01.smt2 |    0.067s | 21.392MiB| unsat | 0 |  |  |
