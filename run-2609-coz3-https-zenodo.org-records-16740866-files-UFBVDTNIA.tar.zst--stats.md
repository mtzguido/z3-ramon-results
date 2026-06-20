# .

* SAT 0
* UNSAT 157
* TIMEOUT 0
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/UFBVDTNIA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-UFBVDTNIA.tar.zst-
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 881360db5a332d5551b40f75d7d603f55b52760d
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFBVDTNIA.tar.zst?download=1
Z3 commit message: Fix constant array UNSAT missed for small-domain store chains (#9907)

Z3 incorrectly returns SAT for formulas like `store(store(const(x), i0,
e0), i1, e1) = store(store(const(y), i0, e0), i1, e1) ∧ x ≠ y` when the
index sort has a small finite domain (e.g. `(_ BitVec 2)` = 4 elements).
The quantifier-based encoding of the same constraint correctly returns
UNSAT.

## Changes

### `src/sat/smt/array_solver.cpp` — `add_parent_lambda()`

When a store is added to an array's `m_parent_lambdas` after that array
already has `m_has_default = true` (i.e., a `default(array)` term
already exists in the e-graph), the default axiom for the new store was
silently dropped. This breaks the propagation chain:

```
default(const(x)) = x
  ↓ [via store default axiom]
default(store(const(x), i, v)) = x
  ↓ [via store default axiom]
default(store(store(const(x), ...), ...)) = x
  ↓ [EUF congruence from store equality]
x = y  →  contradiction
```

Fix: push `default_axiom(lambda)` in `add_parent_lambda` when
`m_has_default` is already set, so late-arriving stores still get their
default axioms instantiated.

```cpp
void solver::add_parent_lambda(theory_var v_child, euf::enode* lambda) {
    auto& d = get_var_data(find(v_child));
    ctx.push_vec(d.m_parent_lambdas, lambda);
    if (should_prop_upward(d))
        propagate_select_axioms(d, lambda);
    if (d.m_has_default)           // new: fire default axiom retroactively
        push_axiom(default_axiom(lambda));
}
```

### Known remaining gap

`mk_eq_core` in `array_rewriter.cpp` also has a related issue: the
unconditional store-chain expansion fires only when `domain_size >
num_lhs + num_rhs` (line 893), but the correct threshold is `domain_size
> max(num_lhs, num_rhs)`. With 4-element domain and 2 stores per side,
`2+2 = 4` equals the domain size so the expansion is skipped. The
variant gated by `m_expand_store_eq` already uses `max()` correctly
(line 911); the unconditional path needs the same fix.

---------

Co-authored-by: copilot-swe-agent[bot] <198982749+Copilot@users.noreply.github.com>
Co-authored-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._49.smt2 |    0.023s | 19.856MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._11.smt2 |    0.030s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._25.smt2 |    0.030s | 19.92MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._12.smt2 |    0.031s | 20.032MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._56.smt2 |    0.031s | 19.896MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._39.smt2 |    0.032s | 19.848MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._56.smt2 |    0.032s | 19.952MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._27.smt2 |    0.032s | 19.836MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._45.smt2 |    0.034s | 20.104MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/atmosphere/util__page_ptr_util_ulib_util.page_ptr_util_u.v2l3index._01.smt2 |    0.039s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._59.smt2 |    0.039s | 19.988MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__pow_pverismo_tspec.math.pow_p.proof_pow2_to_bits._02.smt2 |    0.041s | 20.936MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._12.smt2 |    0.041s | 20.1MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._48.smt2 |    0.042s | 20.884MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._54.smt2 |    0.042s | 19.824MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.lemma_obtain_bit_index_3_aux._02.smt2 |    0.043s | 20.352MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._16.smt2 |    0.044s | 19.784MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._46.smt2 |    0.044s | 19.96MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._34.smt2 |    0.044s | 20.252MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._45.smt2 |    0.045s | 19.816MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._60.smt2 |    0.045s | 20.152MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._07.smt2 |    0.047s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._18.smt2 |    0.047s | 19.844MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._19.smt2 |    0.048s | 20.876MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._49.smt2 |    0.048s | 19.984MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._14.smt2 |    0.049s | 19.876MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/allocator__bit_pverismo_allocator.bit_p.lemma_get_low_bits_via_bit_op._02.smt2 |    0.049s | 21.132MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._48.smt2 |    0.050s | 19.876MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._30.smt2 |    0.050s | 19.776MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._17.smt2 |    0.050s | 19.972MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._24.smt2 |    0.051s | 19.824MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._23.smt2 |    0.051s | 19.884MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._64.smt2 |    0.051s | 19.904MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._40.smt2 |    0.051s | 19.992MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._61.smt2 |    0.051s | 19.74MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._50.smt2 |    0.052s | 20.116MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._14.smt2 |    0.052s | 19.98MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._14.smt2 |    0.052s | 19.984MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._33.smt2 |    0.053s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._28.smt2 |    0.053s | 19.876MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._04.smt2 |    0.053s | 20.128MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._56.smt2 |    0.054s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._02.smt2 |    0.054s | 20.348MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._18.smt2 |    0.054s | 20.796MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._62.smt2 |    0.055s | 20.144MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._44.smt2 |    0.055s | 19.884MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._33.smt2 |    0.055s | 19.88MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._35.smt2 |    0.055s | 19.8MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_fill_ones._02.smt2 |    0.055s | 20.288MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._57.smt2 |    0.056s | 19.896MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._21.smt2 |    0.057s | 19.848MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._36.smt2 |    0.057s | 19.892MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._25.smt2 |    0.058s | 20.84MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._06.smt2 |    0.061s | 20.348MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__security__sectype_test__pverismo_tspec.security.sectype_test.p.proof_test_bits2._01.smt2 |    0.062s | 20.616MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._01.smt2 |    0.062s | 19.856MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_1._05.smt2 |    0.062s | 20.676MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._27.smt2 |    0.063s | 20.832MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._37.smt2 |    0.064s | 20.804MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._51.smt2 |    0.065s | 19.86MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._19.smt2 |    0.066s | 19.892MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._49.smt2 |    0.067s | 19.856MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._28.smt2 |    0.067s | 20.856MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._04.smt2 |    0.068s | 20.692MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._24.smt2 |    0.068s | 20.88MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-bin_sizeslib_bin_sizes.bin._04.smt2 |    0.068s | 19.98MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._52.smt2 |    0.069s | 20.12MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._19.smt2 |    0.069s | 19.9MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_fill_ones_bit_step._03.smt2 |    0.072s | 21.248MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._22.smt2 |    0.072s | 19.908MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._31.smt2 |    0.073s | 20.008MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._19.smt2 |    0.074s | 20.092MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._58.smt2 |    0.074s | 20.096MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/arch__pgtable__entry_pverismo_arch.pgtable.entry_p.impl_%0.lemma_size_offset._01.smt2 |    0.074s | 20.124MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._07.smt2 |    0.074s | 19.864MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._23.smt2 |    0.075s | 20.984MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._55.smt2 |    0.076s | 20.096MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._31.smt2 |    0.076s | 19.88MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._27.smt2 |    0.077s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._11.smt2 |    0.078s | 20.872MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_1._03.smt2 |    0.078s | 20.852MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._41.smt2 |    0.079s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._54.smt2 |    0.079s | 19.876MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_prev_power_of_two._01.smt2 |    0.080s | 21.648MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._34.smt2 |    0.080s | 19.856MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._02.smt2 |    0.080s | 19.86MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._58.smt2 |    0.081s | 20.188MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._11.smt2 |    0.081s | 19.924MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/atmosphere/util__page_ptr_util_ulib_util.page_ptr_util_u.v2l4index._01.smt2 |    0.084s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._52.smt2 |    0.084s | 20.132MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._30.smt2 |    0.084s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_prev_power_of_two._03.smt2 |    0.085s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._40.smt2 |    0.086s | 20.968MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._62.smt2 |    0.087s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._07.smt2 |    0.087s | 19.908MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._58.smt2 |    0.088s | 19.848MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_impllib_impl_u.l2_impl.impl_%0.lemma_zero_entry_facts._03.smt2 |    0.088s | 19.84MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._56.smt2 |    0.089s | 20.912MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._04.smt2 |    0.090s | 20.024MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._05.smt2 |    0.090s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._17.smt2 |    0.090s | 19.88MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.impl_%0.next_run._02.smt2 |    0.090s | 22.772MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._44.smt2 |    0.091s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._55.smt2 |    0.091s | 20.872MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._50.smt2 |    0.092s | 19.848MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._51.smt2 |    0.092s | 20.884MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._02.smt2 |    0.093s | 19.904MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._13.smt2 |    0.094s | 20.1MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._28.smt2 |    0.094s | 19.904MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._47.smt2 |    0.094s | 19.828MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._11.smt2 |    0.094s | 20.024MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._55.smt2 |    0.094s | 19.788MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._34.smt2 |    0.094s | 19.884MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._44.smt2 |    0.095s | 19.804MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._57.smt2 |    0.095s | 20.156MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._03.smt2 |    0.095s | 19.908MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._10.smt2 |    0.095s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-layoutlib_layout.bitand_with_mask_gives_rounding._07.smt2 |    0.095s | 20.4MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._36.smt2 |    0.096s | 20.08MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._26.smt2 |    0.096s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_impllib_impl_u.l2_impl.impl_%0.lemma_zero_entry_facts._02.smt2 |    0.096s | 20.156MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._32.smt2 |    0.097s | 19.86MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._38.smt2 |    0.097s | 19.892MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._05.smt2 |    0.097s | 20.872MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._59.smt2 |    0.097s | 20.876MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.impl_%0.next_run._05.smt2 |    0.097s | 23.192MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-layoutlib_layout.bitand_with_mask_gives_rounding._08.smt2 |    0.097s | 23.336MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/arch__pgtable__entry_pverismo_arch.pgtable.entry_p.lemma_pt_entry_count._01.smt2 |    0.099s | 20.132MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._06.smt2 |    0.099s | 20.9MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.lemma_obtain_bit_index_3_aux._01.smt2 |    0.099s | 20.616MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.impl_%0.next_run._10.smt2 |    0.099s | 22.992MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_clear_set_property._01.smt2 |    0.100s | 21.404MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.lemma_obtain_bit_index_1_aux._03.smt2 |    0.100s | 24.028MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._38.smt2 |    0.105s | 20.836MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_2._07.smt2 |    0.106s | 23.884MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._62.smt2 |    0.107s | 20.672MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-layoutlib_layout.calculate_segment_ptr_from_block._01.smt2 |    0.107s | 23.648MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_1._02.smt2 |    0.108s | 20.492MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_2._05.smt2 |    0.109s | 20.676MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_prev_power_of_two._02.smt2 |    0.122s | 21.796MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_next_power_of_two._02.smt2 |    0.126s | 21.74MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_1._08.smt2 |    0.126s | 23.732MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_fill_ones._06.smt2 |    0.128s | 22.372MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.masked_ptr_delay_set_freeing._01.smt2 |    0.142s | 26.364MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/debug__ghcb_printverismo_debug.ghcb_print.int2bytes._01.smt2 |    0.147s | 22.908MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_2._12.smt2 |    0.150s | 23.996MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.masked_ptr_delay_set_ptr._02.smt2 |    0.166s | 26.304MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.masked_ptr_delay_get_ptr._01.smt2 |    0.170s | 26.404MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-freelib_free.free_block_mt._01.smt2 |    0.180s | 27.552MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__gdtverismo_snp.cpu.gdt.impl_%16.empty._01.smt2 |    0.201s | 27.08MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.impl_%8.take._01.smt2 |    0.204s | 25.848MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-bin_sizeslib_bin_sizes.shift_is_div._02.smt2 |    0.297s | 23.0MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.lemma_bitmask_to_is_bit_set._02.smt2 |    0.309s | 24.908MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.proof_align_down._03.smt2 |    0.446s | 22.928MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__vmsaverismo_snp.cpu.vmsa.impl_%16.empty._01.smt2 |    0.448s | 39.456MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/security__memverismo_security.mem.impl_%16.empty._01.smt2 |    0.456s | 49.508MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_property_auto._01.smt2 |    0.643s | 25.512MiB| unsat | 0 |  |  |
