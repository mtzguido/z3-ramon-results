Comparing data and data


# SUMMARY
- LHS tests = 24
- RHS tests = 24
- LHS success = 24  (100.0%)
- RHS success = 24  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
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
# RHS
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
</details>


## TOP 20 RUNTIME INCREASE

<details><summary>TOP 20 RUNTIME INCREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._01.smt2  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._05.smt2  |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._06.smt2  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._07.smt2  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._12.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._16.smt2  |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._25.smt2  |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._32.smt2  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._35.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2pa._01.smt2  |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._01.smt2  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._03.smt2  |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._04.smt2  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._05.smt2  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._01.smt2  |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._03.smt2  |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._06.smt2  |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_auto._01.smt2  |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.get_retire_expire._01.smt2  |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_in_full._01.smt2  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._01.smt2  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._05.smt2  |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._06.smt2  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._07.smt2  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._12.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._16.smt2  |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._25.smt2  |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._32.smt2  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._35.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2pa._01.smt2  |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._01.smt2  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._03.smt2  |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._04.smt2  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._05.smt2  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._01.smt2  |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._03.smt2  |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._06.smt2  |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_auto._01.smt2  |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.get_retire_expire._01.smt2  |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_in_full._01.smt2  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._01.smt2  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._05.smt2  |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._06.smt2  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._07.smt2  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._12.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._16.smt2  |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._25.smt2  |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._32.smt2  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._35.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2pa._01.smt2  |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._01.smt2  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._03.smt2  |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._04.smt2  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._05.smt2  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._01.smt2  |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._03.smt2  |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._06.smt2  |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_auto._01.smt2  |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.get_retire_expire._01.smt2  |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_in_full._01.smt2  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._01.smt2  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._05.smt2  |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._06.smt2  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._07.smt2  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._12.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._16.smt2  |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._25.smt2  |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._32.smt2  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._35.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2pa._01.smt2  |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._01.smt2  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._03.smt2  |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._04.smt2  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._05.smt2  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._01.smt2  |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._03.smt2  |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._06.smt2  |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_auto._01.smt2  |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.get_retire_expire._01.smt2  |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_in_full._01.smt2  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/UFBVDTLIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_auto._01.smt2 |   0.067s |21.392MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._35.smt2 |   0.061s |21.12MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._05.smt2 |   0.060s |21.172MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._16.smt2 |   0.054s |20.624MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._07.smt2 |   0.052s |20.116MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._12.smt2 |   0.042s |20.904MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._25.smt2 |   0.041s |21.396MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._01.smt2 |   0.035s |20.116MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._06.smt2 |   0.035s |20.872MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._05.smt2 |   0.035s |19.852MiB|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_is_committed._02.smt2 |   0.035s |20.844MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._06.smt2 |   0.034s |20.344MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2pa._01.smt2 |   0.034s |19.852MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._01.smt2 |   0.034s |19.868MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._03.smt2 |   0.034s |19.852MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._01.smt2 |   0.033s |19.644MiB|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_in_full._01.smt2 |   0.033s |20.912MiB|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_is_zero_init._03.smt2 |   0.033s |20.86MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._04.smt2 |   0.032s |19.624MiB|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_retire_expire._02.smt2 |   0.031s |20.8MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/UFBVDTLIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_auto._01.smt2 |   0.067s |21.392MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._35.smt2 |   0.061s |21.12MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._05.smt2 |   0.060s |21.172MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._16.smt2 |   0.054s |20.624MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._07.smt2 |   0.052s |20.116MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._12.smt2 |   0.042s |20.904MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._25.smt2 |   0.041s |21.396MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._01.smt2 |   0.035s |20.116MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._06.smt2 |   0.035s |20.872MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._05.smt2 |   0.035s |19.852MiB|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_is_committed._02.smt2 |   0.035s |20.844MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._06.smt2 |   0.034s |20.344MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2pa._01.smt2 |   0.034s |19.852MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._01.smt2 |   0.034s |19.868MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._03.smt2 |   0.034s |19.852MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._01.smt2 |   0.033s |19.644MiB|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_in_full._01.smt2 |   0.033s |20.912MiB|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_is_zero_init._03.smt2 |   0.033s |20.86MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._04.smt2 |   0.032s |19.624MiB|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_retire_expire._02.smt2 |   0.031s |20.8MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._01.smt2  |20.116MiB|20.116MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._05.smt2  |21.172MiB|21.172MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._06.smt2  |20.872MiB|20.872MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._07.smt2  |20.116MiB|20.116MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._12.smt2  |20.904MiB|20.904MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._16.smt2  |20.624MiB|20.624MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._25.smt2  |21.396MiB|21.396MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._32.smt2  |19.892MiB|19.892MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._35.smt2  |21.12MiB|21.12MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2pa._01.smt2  |19.852MiB|19.852MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._01.smt2  |19.644MiB|19.644MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._03.smt2  |19.852MiB|19.852MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._04.smt2  |19.624MiB|19.624MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._05.smt2  |19.852MiB|19.852MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._01.smt2  |19.868MiB|19.868MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._03.smt2  |19.856MiB|19.856MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._06.smt2  |20.344MiB|20.344MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_auto._01.smt2  |21.392MiB|21.392MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.get_retire_expire._01.smt2  |19.648MiB|19.648MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_in_full._01.smt2  |20.912MiB|20.912MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._01.smt2  |20.116MiB|20.116MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._05.smt2  |21.172MiB|21.172MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._06.smt2  |20.872MiB|20.872MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._07.smt2  |20.116MiB|20.116MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._12.smt2  |20.904MiB|20.904MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._16.smt2  |20.624MiB|20.624MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._25.smt2  |21.396MiB|21.396MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._32.smt2  |19.892MiB|19.892MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._35.smt2  |21.12MiB|21.12MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2pa._01.smt2  |19.852MiB|19.852MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._01.smt2  |19.644MiB|19.644MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._03.smt2  |19.852MiB|19.852MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._04.smt2  |19.624MiB|19.624MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._05.smt2  |19.852MiB|19.852MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._01.smt2  |19.868MiB|19.868MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._03.smt2  |19.856MiB|19.856MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._06.smt2  |20.344MiB|20.344MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_auto._01.smt2  |21.392MiB|21.392MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.get_retire_expire._01.smt2  |19.648MiB|19.648MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_in_full._01.smt2  |20.912MiB|20.912MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._01.smt2  |20.116MiB|20.116MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._05.smt2  |21.172MiB|21.172MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._06.smt2  |20.872MiB|20.872MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._07.smt2  |20.116MiB|20.116MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._12.smt2  |20.904MiB|20.904MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._16.smt2  |20.624MiB|20.624MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._25.smt2  |21.396MiB|21.396MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._32.smt2  |19.892MiB|19.892MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._35.smt2  |21.12MiB|21.12MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2pa._01.smt2  |19.852MiB|19.852MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._01.smt2  |19.644MiB|19.644MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._03.smt2  |19.852MiB|19.852MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._04.smt2  |19.624MiB|19.624MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._05.smt2  |19.852MiB|19.852MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._01.smt2  |19.868MiB|19.868MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._03.smt2  |19.856MiB|19.856MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._06.smt2  |20.344MiB|20.344MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_auto._01.smt2  |21.392MiB|21.392MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.get_retire_expire._01.smt2  |19.648MiB|19.648MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_in_full._01.smt2  |20.912MiB|20.912MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._01.smt2  |20.116MiB|20.116MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._05.smt2  |21.172MiB|21.172MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._06.smt2  |20.872MiB|20.872MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._07.smt2  |20.116MiB|20.116MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._12.smt2  |20.904MiB|20.904MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._16.smt2  |20.624MiB|20.624MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._25.smt2  |21.396MiB|21.396MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._32.smt2  |19.892MiB|19.892MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._35.smt2  |21.12MiB|21.12MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2pa._01.smt2  |19.852MiB|19.852MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._01.smt2  |19.644MiB|19.644MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._03.smt2  |19.852MiB|19.852MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._04.smt2  |19.624MiB|19.624MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._05.smt2  |19.852MiB|19.852MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._01.smt2  |19.868MiB|19.868MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._03.smt2  |19.856MiB|19.856MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._06.smt2  |20.344MiB|20.344MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_auto._01.smt2  |21.392MiB|21.392MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.get_retire_expire._01.smt2  |19.648MiB|19.648MiB|0B| 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_in_full._01.smt2  |20.912MiB|20.912MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._25.smt2 |   0.041s |21.396MiB|
|non-incremental/UFBVDTLIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_auto._01.smt2 |   0.067s |21.392MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._05.smt2 |   0.060s |21.172MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._35.smt2 |   0.061s |21.12MiB|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_in_full._01.smt2 |   0.033s |20.912MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._12.smt2 |   0.042s |20.904MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._06.smt2 |   0.035s |20.872MiB|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_is_zero_init._03.smt2 |   0.033s |20.86MiB|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_is_committed._02.smt2 |   0.035s |20.844MiB|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_retire_expire._02.smt2 |   0.031s |20.8MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._16.smt2 |   0.054s |20.624MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._06.smt2 |   0.034s |20.344MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._07.smt2 |   0.052s |20.116MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._01.smt2 |   0.035s |20.116MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._32.smt2 |   0.025s |19.892MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._01.smt2 |   0.034s |19.868MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._03.smt2 |   0.024s |19.856MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._05.smt2 |   0.035s |19.852MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2pa._01.smt2 |   0.034s |19.852MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._03.smt2 |   0.034s |19.852MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._25.smt2 |   0.041s |21.396MiB|
|non-incremental/UFBVDTLIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_auto._01.smt2 |   0.067s |21.392MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._05.smt2 |   0.060s |21.172MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._35.smt2 |   0.061s |21.12MiB|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_in_full._01.smt2 |   0.033s |20.912MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._12.smt2 |   0.042s |20.904MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._06.smt2 |   0.035s |20.872MiB|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_is_zero_init._03.smt2 |   0.033s |20.86MiB|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_is_committed._02.smt2 |   0.035s |20.844MiB|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_retire_expire._02.smt2 |   0.031s |20.8MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._16.smt2 |   0.054s |20.624MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._06.smt2 |   0.034s |20.344MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._07.smt2 |   0.052s |20.116MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._01.smt2 |   0.035s |20.116MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._32.smt2 |   0.025s |19.892MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._01.smt2 |   0.034s |19.868MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._03.smt2 |   0.024s |19.856MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._05.smt2 |   0.035s |19.852MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2pa._01.smt2 |   0.034s |19.852MiB|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._03.smt2 |   0.034s |19.852MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._01.smt2  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._05.smt2  |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._06.smt2  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._07.smt2  |   0.052s  |   0.052s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._12.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._16.smt2  |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._25.smt2  |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._32.smt2  |   0.025s  |   0.025s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.page_entry2usize._35.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2pa._01.smt2  |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._01.smt2  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._03.smt2  |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._04.smt2  |   0.032s  |   0.032s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.usize2page_entry_perm._05.smt2  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._01.smt2  |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._03.smt2  |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/atmosphere/pagetable__entrylib_pagetable.entry.zero_leads_is_empty_page_entry._06.smt2  |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_auto._01.smt2  |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.get_retire_expire._01.smt2  |   0.024s  |   0.024s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_in_full._01.smt2  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_is_committed._01.smt2  |   0.027s  |   0.027s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_is_committed._02.smt2  |   0.035s  |   0.035s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTLIA/20241211-verus/verussystems/mimalloc-smt-flagslib_flags.impl_%0.set_is_zero_init._03.smt2  |   0.033s  |   0.033s  |   0.000s  | 0.0%|
</details>
