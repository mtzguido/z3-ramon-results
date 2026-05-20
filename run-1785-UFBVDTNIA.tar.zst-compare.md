Comparing data and data


# SUMMARY
- LHS tests = 157
- RHS tests = 157
- LHS success = 157  (100.0%)
- RHS success = 157  (100.0%)


## METADATA

<details><summary>METADATA</summary>

# LHS
<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: UFBVDTNIA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/UFBVDTNIA.tar.zst?download=1
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
Job tag: UFBVDTNIA.tar.zst
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: bc6c38e7d3424b88a505cacba4b268d0774d4547
Z3 branch: master
Z3 options: "-T:20"
Z3 inputs: https://zenodo.org/records/16740866/files/UFBVDTNIA.tar.zst?download=1
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
|non-incremental/UFBVDTNIA/20241211-verus/atmosphere/util__page_ptr_util_ulib_util.page_ptr_util_u.v2l3index._01.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/atmosphere/util__page_ptr_util_ulib_util.page_ptr_util_u.v2l4index._01.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/allocator__bit_pverismo_allocator.bit_p.lemma_get_low_bits_via_bit_op._02.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/arch__pgtable__entry_pverismo_arch.pgtable.entry_p.impl_%0.lemma_size_offset._01.smt2  |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/arch__pgtable__entry_pverismo_arch.pgtable.entry_p.lemma_pt_entry_count._01.smt2  |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/debug__ghcb_printverismo_debug.ghcb_print.int2bytes._01.smt2  |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/security__memverismo_security.mem.impl_%16.empty._01.smt2  |   0.445s  |   0.445s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__gdtverismo_snp.cpu.gdt.impl_%16.empty._01.smt2  |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__vmsaverismo_snp.cpu.vmsa.impl_%16.empty._01.smt2  |   0.431s  |   0.431s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._02.smt2  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._11.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._17.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._19.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._21.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._28.smt2  |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._30.smt2  |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._34.smt2  |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._41.smt2  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._45.smt2  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._46.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME INCREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME INCREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFBVDTNIA/20241211-verus/atmosphere/util__page_ptr_util_ulib_util.page_ptr_util_u.v2l3index._01.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/atmosphere/util__page_ptr_util_ulib_util.page_ptr_util_u.v2l4index._01.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/allocator__bit_pverismo_allocator.bit_p.lemma_get_low_bits_via_bit_op._02.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/arch__pgtable__entry_pverismo_arch.pgtable.entry_p.impl_%0.lemma_size_offset._01.smt2  |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/arch__pgtable__entry_pverismo_arch.pgtable.entry_p.lemma_pt_entry_count._01.smt2  |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/debug__ghcb_printverismo_debug.ghcb_print.int2bytes._01.smt2  |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/security__memverismo_security.mem.impl_%16.empty._01.smt2  |   0.445s  |   0.445s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__gdtverismo_snp.cpu.gdt.impl_%16.empty._01.smt2  |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__vmsaverismo_snp.cpu.vmsa.impl_%16.empty._01.smt2  |   0.431s  |   0.431s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._02.smt2  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._11.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._17.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._19.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._21.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._28.smt2  |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._30.smt2  |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._34.smt2  |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._41.smt2  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._45.smt2  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._46.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE

<details><summary>TOP 20 RUNTIME DECREASE</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFBVDTNIA/20241211-verus/atmosphere/util__page_ptr_util_ulib_util.page_ptr_util_u.v2l3index._01.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/atmosphere/util__page_ptr_util_ulib_util.page_ptr_util_u.v2l4index._01.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/allocator__bit_pverismo_allocator.bit_p.lemma_get_low_bits_via_bit_op._02.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/arch__pgtable__entry_pverismo_arch.pgtable.entry_p.impl_%0.lemma_size_offset._01.smt2  |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/arch__pgtable__entry_pverismo_arch.pgtable.entry_p.lemma_pt_entry_count._01.smt2  |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/debug__ghcb_printverismo_debug.ghcb_print.int2bytes._01.smt2  |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/security__memverismo_security.mem.impl_%16.empty._01.smt2  |   0.445s  |   0.445s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__gdtverismo_snp.cpu.gdt.impl_%16.empty._01.smt2  |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__vmsaverismo_snp.cpu.vmsa.impl_%16.empty._01.smt2  |   0.431s  |   0.431s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._02.smt2  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._11.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._17.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._19.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._21.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._28.smt2  |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._30.smt2  |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._34.smt2  |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._41.smt2  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._45.smt2  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._46.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
</details>


## TOP 20 RUNTIME DECREASE (RELATIVE)

<details><summary>TOP 20 RUNTIME DECREASE (RELATIVE)</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFBVDTNIA/20241211-verus/atmosphere/util__page_ptr_util_ulib_util.page_ptr_util_u.v2l3index._01.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/atmosphere/util__page_ptr_util_ulib_util.page_ptr_util_u.v2l4index._01.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/allocator__bit_pverismo_allocator.bit_p.lemma_get_low_bits_via_bit_op._02.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/arch__pgtable__entry_pverismo_arch.pgtable.entry_p.impl_%0.lemma_size_offset._01.smt2  |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/arch__pgtable__entry_pverismo_arch.pgtable.entry_p.lemma_pt_entry_count._01.smt2  |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/debug__ghcb_printverismo_debug.ghcb_print.int2bytes._01.smt2  |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/security__memverismo_security.mem.impl_%16.empty._01.smt2  |   0.445s  |   0.445s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__gdtverismo_snp.cpu.gdt.impl_%16.empty._01.smt2  |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__vmsaverismo_snp.cpu.vmsa.impl_%16.empty._01.smt2  |   0.431s  |   0.431s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._02.smt2  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._11.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._17.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._19.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._21.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._28.smt2  |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._30.smt2  |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._34.smt2  |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._41.smt2  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._45.smt2  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._46.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
</details>


## TOP 20 LHS FILES, BY RUNTIME

<details><summary>TOP 20 LHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_property_auto._01.smt2 |   0.647s |25.508MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/security__memverismo_security.mem.impl_%16.empty._01.smt2 |   0.445s |49.592MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.proof_align_down._03.smt2 |   0.433s |22.712MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__vmsaverismo_snp.cpu.vmsa.impl_%16.empty._01.smt2 |   0.431s |39.248MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.lemma_bitmask_to_is_bit_set._02.smt2 |   0.321s |24.88MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-bin_sizeslib_bin_sizes.shift_is_div._02.smt2 |   0.307s |23.02MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__gdtverismo_snp.cpu.gdt.impl_%16.empty._01.smt2 |   0.201s |26.912MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.masked_ptr_delay_set_ptr._02.smt2 |   0.164s |26.144MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-freelib_free.free_block_mt._01.smt2 |   0.157s |27.508MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.masked_ptr_delay_set_freeing._01.smt2 |   0.152s |26.544MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.masked_ptr_delay_get_ptr._01.smt2 |   0.149s |26.4MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/debug__ghcb_printverismo_debug.ghcb_print.int2bytes._01.smt2 |   0.147s |22.72MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.impl_%8.take._01.smt2 |   0.137s |25.944MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_fill_ones._06.smt2 |   0.120s |22.376MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._56.smt2 |   0.120s |20.876MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_1._08.smt2 |   0.117s |23.636MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_2._12.smt2 |   0.116s |23.984MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_fill_ones_bit_step._03.smt2 |   0.113s |21.388MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._56.smt2 |   0.110s |19.844MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_prev_power_of_two._02.smt2 |   0.109s |21.68MiB|
</details>


## TOP 20 RHS FILES, BY RUNTIME

<details><summary>TOP 20 RHS FILES, BY RUNTIME</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_property_auto._01.smt2 |   0.647s |25.508MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/security__memverismo_security.mem.impl_%16.empty._01.smt2 |   0.445s |49.592MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.proof_align_down._03.smt2 |   0.433s |22.712MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__vmsaverismo_snp.cpu.vmsa.impl_%16.empty._01.smt2 |   0.431s |39.248MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.lemma_bitmask_to_is_bit_set._02.smt2 |   0.321s |24.88MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-bin_sizeslib_bin_sizes.shift_is_div._02.smt2 |   0.307s |23.02MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__gdtverismo_snp.cpu.gdt.impl_%16.empty._01.smt2 |   0.201s |26.912MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.masked_ptr_delay_set_ptr._02.smt2 |   0.164s |26.144MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-freelib_free.free_block_mt._01.smt2 |   0.157s |27.508MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.masked_ptr_delay_set_freeing._01.smt2 |   0.152s |26.544MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.masked_ptr_delay_get_ptr._01.smt2 |   0.149s |26.4MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/debug__ghcb_printverismo_debug.ghcb_print.int2bytes._01.smt2 |   0.147s |22.72MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.impl_%8.take._01.smt2 |   0.137s |25.944MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_fill_ones._06.smt2 |   0.120s |22.376MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._56.smt2 |   0.120s |20.876MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_1._08.smt2 |   0.117s |23.636MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_2._12.smt2 |   0.116s |23.984MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_fill_ones_bit_step._03.smt2 |   0.113s |21.388MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._56.smt2 |   0.110s |19.844MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_prev_power_of_two._02.smt2 |   0.109s |21.68MiB|
</details>


## TOP 20 MEMORY INCREASE

<details><summary>TOP 20 MEMORY INCREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFBVDTNIA/20241211-verus/atmosphere/util__page_ptr_util_ulib_util.page_ptr_util_u.v2l3index._01.smt2  |20.1MiB|20.1MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/atmosphere/util__page_ptr_util_ulib_util.page_ptr_util_u.v2l4index._01.smt2  |20.608MiB|20.608MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/allocator__bit_pverismo_allocator.bit_p.lemma_get_low_bits_via_bit_op._02.smt2  |20.988MiB|20.988MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/arch__pgtable__entry_pverismo_arch.pgtable.entry_p.impl_%0.lemma_size_offset._01.smt2  |20.352MiB|20.352MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/arch__pgtable__entry_pverismo_arch.pgtable.entry_p.lemma_pt_entry_count._01.smt2  |20.344MiB|20.344MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/debug__ghcb_printverismo_debug.ghcb_print.int2bytes._01.smt2  |22.72MiB|22.72MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/security__memverismo_security.mem.impl_%16.empty._01.smt2  |49.592MiB|49.592MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__gdtverismo_snp.cpu.gdt.impl_%16.empty._01.smt2  |26.912MiB|26.912MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__vmsaverismo_snp.cpu.vmsa.impl_%16.empty._01.smt2  |39.248MiB|39.248MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._02.smt2  |20.12MiB|20.12MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._11.smt2  |19.868MiB|19.868MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._17.smt2  |19.856MiB|19.856MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._19.smt2  |20.176MiB|20.176MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._21.smt2  |20.18MiB|20.18MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._28.smt2  |19.98MiB|19.98MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._30.smt2  |20.328MiB|20.328MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._34.smt2  |20.16MiB|20.16MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._41.smt2  |19.852MiB|19.852MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._45.smt2  |20.332MiB|20.332MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._46.smt2  |20.088MiB|20.088MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY INCREASE (RELATIVE)

<details><summary>TOP 20 MEMORY INCREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFBVDTNIA/20241211-verus/atmosphere/util__page_ptr_util_ulib_util.page_ptr_util_u.v2l3index._01.smt2  |20.1MiB|20.1MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/atmosphere/util__page_ptr_util_ulib_util.page_ptr_util_u.v2l4index._01.smt2  |20.608MiB|20.608MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/allocator__bit_pverismo_allocator.bit_p.lemma_get_low_bits_via_bit_op._02.smt2  |20.988MiB|20.988MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/arch__pgtable__entry_pverismo_arch.pgtable.entry_p.impl_%0.lemma_size_offset._01.smt2  |20.352MiB|20.352MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/arch__pgtable__entry_pverismo_arch.pgtable.entry_p.lemma_pt_entry_count._01.smt2  |20.344MiB|20.344MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/debug__ghcb_printverismo_debug.ghcb_print.int2bytes._01.smt2  |22.72MiB|22.72MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/security__memverismo_security.mem.impl_%16.empty._01.smt2  |49.592MiB|49.592MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__gdtverismo_snp.cpu.gdt.impl_%16.empty._01.smt2  |26.912MiB|26.912MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__vmsaverismo_snp.cpu.vmsa.impl_%16.empty._01.smt2  |39.248MiB|39.248MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._02.smt2  |20.12MiB|20.12MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._11.smt2  |19.868MiB|19.868MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._17.smt2  |19.856MiB|19.856MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._19.smt2  |20.176MiB|20.176MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._21.smt2  |20.18MiB|20.18MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._28.smt2  |19.98MiB|19.98MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._30.smt2  |20.328MiB|20.328MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._34.smt2  |20.16MiB|20.16MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._41.smt2  |19.852MiB|19.852MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._45.smt2  |20.332MiB|20.332MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._46.smt2  |20.088MiB|20.088MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE

<details><summary>TOP 20 MEMORY DECREASE</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFBVDTNIA/20241211-verus/atmosphere/util__page_ptr_util_ulib_util.page_ptr_util_u.v2l3index._01.smt2  |20.1MiB|20.1MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/atmosphere/util__page_ptr_util_ulib_util.page_ptr_util_u.v2l4index._01.smt2  |20.608MiB|20.608MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/allocator__bit_pverismo_allocator.bit_p.lemma_get_low_bits_via_bit_op._02.smt2  |20.988MiB|20.988MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/arch__pgtable__entry_pverismo_arch.pgtable.entry_p.impl_%0.lemma_size_offset._01.smt2  |20.352MiB|20.352MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/arch__pgtable__entry_pverismo_arch.pgtable.entry_p.lemma_pt_entry_count._01.smt2  |20.344MiB|20.344MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/debug__ghcb_printverismo_debug.ghcb_print.int2bytes._01.smt2  |22.72MiB|22.72MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/security__memverismo_security.mem.impl_%16.empty._01.smt2  |49.592MiB|49.592MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__gdtverismo_snp.cpu.gdt.impl_%16.empty._01.smt2  |26.912MiB|26.912MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__vmsaverismo_snp.cpu.vmsa.impl_%16.empty._01.smt2  |39.248MiB|39.248MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._02.smt2  |20.12MiB|20.12MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._11.smt2  |19.868MiB|19.868MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._17.smt2  |19.856MiB|19.856MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._19.smt2  |20.176MiB|20.176MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._21.smt2  |20.18MiB|20.18MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._28.smt2  |19.98MiB|19.98MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._30.smt2  |20.328MiB|20.328MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._34.smt2  |20.16MiB|20.16MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._41.smt2  |19.852MiB|19.852MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._45.smt2  |20.332MiB|20.332MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._46.smt2  |20.088MiB|20.088MiB|0B| 0.0%|
</details>


## TOP 20 MEMORY DECREASE (RELATIVE)

<details><summary>TOP 20 MEMORY DECREASE (RELATIVE)</summary>

|FILE                                                                                        |MEM_L         |MEM_R         |DIFF            |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFBVDTNIA/20241211-verus/atmosphere/util__page_ptr_util_ulib_util.page_ptr_util_u.v2l3index._01.smt2  |20.1MiB|20.1MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/atmosphere/util__page_ptr_util_ulib_util.page_ptr_util_u.v2l4index._01.smt2  |20.608MiB|20.608MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/allocator__bit_pverismo_allocator.bit_p.lemma_get_low_bits_via_bit_op._02.smt2  |20.988MiB|20.988MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/arch__pgtable__entry_pverismo_arch.pgtable.entry_p.impl_%0.lemma_size_offset._01.smt2  |20.352MiB|20.352MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/arch__pgtable__entry_pverismo_arch.pgtable.entry_p.lemma_pt_entry_count._01.smt2  |20.344MiB|20.344MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/debug__ghcb_printverismo_debug.ghcb_print.int2bytes._01.smt2  |22.72MiB|22.72MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/security__memverismo_security.mem.impl_%16.empty._01.smt2  |49.592MiB|49.592MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__gdtverismo_snp.cpu.gdt.impl_%16.empty._01.smt2  |26.912MiB|26.912MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__vmsaverismo_snp.cpu.vmsa.impl_%16.empty._01.smt2  |39.248MiB|39.248MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._02.smt2  |20.12MiB|20.12MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._11.smt2  |19.868MiB|19.868MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._17.smt2  |19.856MiB|19.856MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._19.smt2  |20.176MiB|20.176MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._21.smt2  |20.18MiB|20.18MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._28.smt2  |19.98MiB|19.98MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._30.smt2  |20.328MiB|20.328MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._34.smt2  |20.16MiB|20.16MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._41.smt2  |19.852MiB|19.852MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._45.smt2  |20.332MiB|20.332MiB|0B| 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._46.smt2  |20.088MiB|20.088MiB|0B| 0.0%|
</details>


## TOP 20 LHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 LHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/security__memverismo_security.mem.impl_%16.empty._01.smt2 |   0.445s |49.592MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__vmsaverismo_snp.cpu.vmsa.impl_%16.empty._01.smt2 |   0.431s |39.248MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-freelib_free.free_block_mt._01.smt2 |   0.157s |27.508MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__gdtverismo_snp.cpu.gdt.impl_%16.empty._01.smt2 |   0.201s |26.912MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.masked_ptr_delay_set_freeing._01.smt2 |   0.152s |26.544MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.masked_ptr_delay_get_ptr._01.smt2 |   0.149s |26.4MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.masked_ptr_delay_set_ptr._02.smt2 |   0.164s |26.144MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.impl_%8.take._01.smt2 |   0.137s |25.944MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_property_auto._01.smt2 |   0.647s |25.508MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.lemma_bitmask_to_is_bit_set._02.smt2 |   0.321s |24.88MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.lemma_obtain_bit_index_1_aux._03.smt2 |   0.091s |24.0MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_2._12.smt2 |   0.116s |23.984MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_2._07.smt2 |   0.109s |23.772MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_1._08.smt2 |   0.117s |23.636MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-layoutlib_layout.calculate_segment_ptr_from_block._01.smt2 |   0.094s |23.564MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-layoutlib_layout.bitand_with_mask_gives_rounding._08.smt2 |   0.083s |23.332MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.impl_%0.next_run._05.smt2 |   0.087s |23.2MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.impl_%0.next_run._10.smt2 |   0.091s |23.176MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-bin_sizeslib_bin_sizes.shift_is_div._02.smt2 |   0.307s |23.02MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.impl_%0.next_run._02.smt2 |   0.084s |22.996MiB|
</details>


## TOP 20 RHS FILES, BY PEAK MEMORY USAGE

<details><summary>TOP 20 RHS FILES, BY PEAK MEMORY USAGE</summary>

|FILE                                                                                       |TIME     |MEM        |
|------------|----------:|---------:|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/security__memverismo_security.mem.impl_%16.empty._01.smt2 |   0.445s |49.592MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__vmsaverismo_snp.cpu.vmsa.impl_%16.empty._01.smt2 |   0.431s |39.248MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-freelib_free.free_block_mt._01.smt2 |   0.157s |27.508MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__gdtverismo_snp.cpu.gdt.impl_%16.empty._01.smt2 |   0.201s |26.912MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.masked_ptr_delay_set_freeing._01.smt2 |   0.152s |26.544MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.masked_ptr_delay_get_ptr._01.smt2 |   0.149s |26.4MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.masked_ptr_delay_set_ptr._02.smt2 |   0.164s |26.144MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.impl_%8.take._01.smt2 |   0.137s |25.944MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_property_auto._01.smt2 |   0.647s |25.508MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.lemma_bitmask_to_is_bit_set._02.smt2 |   0.321s |24.88MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.lemma_obtain_bit_index_1_aux._03.smt2 |   0.091s |24.0MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_2._12.smt2 |   0.116s |23.984MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_2._07.smt2 |   0.109s |23.772MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_1._08.smt2 |   0.117s |23.636MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-layoutlib_layout.calculate_segment_ptr_from_block._01.smt2 |   0.094s |23.564MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-layoutlib_layout.bitand_with_mask_gives_rounding._08.smt2 |   0.083s |23.332MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.impl_%0.next_run._05.smt2 |   0.087s |23.2MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.impl_%0.next_run._10.smt2 |   0.091s |23.176MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-bin_sizeslib_bin_sizes.shift_is_div._02.smt2 |   0.307s |23.02MiB|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.impl_%0.next_run._02.smt2 |   0.084s |22.996MiB|
</details>


## FULL COMPARISON

<details><summary>FULL COMPARISON</summary>

|FILE                                                                                        |TIME_L     |TIME_R     |DIFF(s)    |DIFF(%)|
|-------------|-------------:|-------------:|--------------:|------------:|
|non-incremental/UFBVDTNIA/20241211-verus/atmosphere/util__page_ptr_util_ulib_util.page_ptr_util_u.v2l3index._01.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/atmosphere/util__page_ptr_util_ulib_util.page_ptr_util_u.v2l4index._01.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/allocator__bit_pverismo_allocator.bit_p.lemma_get_low_bits_via_bit_op._02.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/arch__pgtable__entry_pverismo_arch.pgtable.entry_p.impl_%0.lemma_size_offset._01.smt2  |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/arch__pgtable__entry_pverismo_arch.pgtable.entry_p.lemma_pt_entry_count._01.smt2  |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/debug__ghcb_printverismo_debug.ghcb_print.int2bytes._01.smt2  |   0.147s  |   0.147s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/security__memverismo_security.mem.impl_%16.empty._01.smt2  |   0.445s  |   0.445s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__gdtverismo_snp.cpu.gdt.impl_%16.empty._01.smt2  |   0.201s  |   0.201s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__vmsaverismo_snp.cpu.vmsa.impl_%16.empty._01.smt2  |   0.431s  |   0.431s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._02.smt2  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._11.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._17.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._19.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._21.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._28.smt2  |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._30.smt2  |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._34.smt2  |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._41.smt2  |   0.100s  |   0.100s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._45.smt2  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._46.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._49.smt2  |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._52.smt2  |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._56.smt2  |   0.110s  |   0.110s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._58.smt2  |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._59.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._60.smt2  |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._64.smt2  |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.proof_align_down._03.smt2  |   0.433s  |   0.433s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_property_auto._01.smt2  |   0.647s  |   0.647s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._04.smt2  |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._05.smt2  |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._06.smt2  |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._11.smt2  |   0.079s  |   0.079s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._18.smt2  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._19.smt2  |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._23.smt2  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._24.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._25.smt2  |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._27.smt2  |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._28.smt2  |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._37.smt2  |   0.068s  |   0.068s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._38.smt2  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._40.smt2  |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._48.smt2  |   0.041s  |   0.041s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._51.smt2  |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._55.smt2  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._56.smt2  |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._59.smt2  |   0.099s  |   0.099s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._62.smt2  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._01.smt2  |   0.065s  |   0.065s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._03.smt2  |   0.070s  |   0.070s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._04.smt2  |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._07.smt2  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._11.smt2  |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._13.smt2  |   0.073s  |   0.073s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._14.smt2  |   0.063s  |   0.063s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._17.smt2  |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._18.smt2  |   0.078s  |   0.078s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._22.smt2  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._24.smt2  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._25.smt2  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._27.smt2  |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._31.smt2  |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._33.smt2  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._34.smt2  |   0.045s  |   0.045s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._36.smt2  |   0.056s  |   0.056s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._44.smt2  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._47.smt2  |   0.071s  |   0.071s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._49.smt2  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._50.smt2  |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._52.smt2  |   0.097s  |   0.097s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._54.smt2  |   0.072s  |   0.072s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._55.smt2  |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._57.smt2  |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._61.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._62.smt2  |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._02.smt2  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._06.smt2  |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._07.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._10.smt2  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._12.smt2  |   0.092s  |   0.092s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._14.smt2  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._19.smt2  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._23.smt2  |   0.081s  |   0.081s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._26.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._27.smt2  |   0.098s  |   0.098s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._31.smt2  |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._32.smt2  |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._35.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._39.smt2  |   0.034s  |   0.034s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._44.smt2  |   0.060s  |   0.060s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._45.smt2  |   0.030s  |   0.030s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._48.smt2  |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._50.smt2  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._55.smt2  |   0.085s  |   0.085s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._56.smt2  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._57.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._58.smt2  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._62.smt2  |   0.089s  |   0.089s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_clear_set_property._01.smt2  |   0.088s  |   0.088s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._02.smt2  |   0.086s  |   0.086s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._04.smt2  |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._05.smt2  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._07.smt2  |   0.090s  |   0.090s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._11.smt2  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._12.smt2  |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._14.smt2  |   0.082s  |   0.082s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._16.smt2  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._19.smt2  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._28.smt2  |   0.076s  |   0.076s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._30.smt2  |   0.080s  |   0.080s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._33.smt2  |   0.102s  |   0.102s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._34.smt2  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._36.smt2  |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._38.smt2  |   0.093s  |   0.093s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._40.smt2  |   0.069s  |   0.069s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._44.smt2  |   0.077s  |   0.077s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._49.smt2  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._51.smt2  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._54.smt2  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._56.smt2  |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._58.smt2  |   0.067s  |   0.067s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_fill_ones._02.smt2  |   0.095s  |   0.095s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_fill_ones._06.smt2  |   0.120s  |   0.120s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_fill_ones_bit_step._03.smt2  |   0.113s  |   0.113s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_next_power_of_two._02.smt2  |   0.106s  |   0.106s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_prev_power_of_two._01.smt2  |   0.107s  |   0.107s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_prev_power_of_two._02.smt2  |   0.109s  |   0.109s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_prev_power_of_two._03.smt2  |   0.075s  |   0.075s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__pow_pverismo_tspec.math.pow_p.proof_pow2_to_bits._02.smt2  |   0.044s  |   0.044s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__security__sectype_test__pverismo_tspec.security.sectype_test.p.proof_test_bits2._01.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-bin_sizeslib_bin_sizes.bin._04.smt2  |   0.054s  |   0.054s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-bin_sizeslib_bin_sizes.shift_is_div._02.smt2  |   0.307s  |   0.307s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.impl_%0.next_run._02.smt2  |   0.084s  |   0.084s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.impl_%0.next_run._05.smt2  |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.impl_%0.next_run._10.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.lemma_bitmask_to_is_bit_set._02.smt2  |   0.321s  |   0.321s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.lemma_obtain_bit_index_1_aux._03.smt2  |   0.091s  |   0.091s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.lemma_obtain_bit_index_3_aux._01.smt2  |   0.062s  |   0.062s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.lemma_obtain_bit_index_3_aux._02.smt2  |   0.087s  |   0.087s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-freelib_free.free_block_mt._01.smt2  |   0.157s  |   0.157s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-layoutlib_layout.bitand_with_mask_gives_rounding._07.smt2  |   0.061s  |   0.061s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-layoutlib_layout.bitand_with_mask_gives_rounding._08.smt2  |   0.083s  |   0.083s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-layoutlib_layout.calculate_segment_ptr_from_block._01.smt2  |   0.094s  |   0.094s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.impl_%8.take._01.smt2  |   0.137s  |   0.137s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.masked_ptr_delay_get_ptr._01.smt2  |   0.149s  |   0.149s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.masked_ptr_delay_set_freeing._01.smt2  |   0.152s  |   0.152s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.masked_ptr_delay_set_ptr._02.smt2  |   0.164s  |   0.164s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_impllib_impl_u.l2_impl.impl_%0.lemma_zero_entry_facts._02.smt2  |   0.026s  |   0.026s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_impllib_impl_u.l2_impl.impl_%0.lemma_zero_entry_facts._03.smt2  |   0.047s  |   0.047s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_1._02.smt2  |   0.042s  |   0.042s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_1._03.smt2  |   0.066s  |   0.066s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_1._05.smt2  |   0.038s  |   0.038s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_1._08.smt2  |   0.117s  |   0.117s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_2._05.smt2  |   0.043s  |   0.043s  |   0.000s  | 0.0%|
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_2._07.smt2  |   0.109s  |   0.109s  |   0.000s  | 0.0%|
</details>
