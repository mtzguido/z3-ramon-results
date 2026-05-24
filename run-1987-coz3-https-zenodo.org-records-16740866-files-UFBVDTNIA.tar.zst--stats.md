# .

* SAT 0
* UNSAT 107
* TIMEOUT 0
* UNKNOWN 50

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/UFBVDTNIA.tar.zst?download=1 | Source list: benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-UFBVDTNIA.tar.zst-
Runner: rise-runner-2
Z3 repo: Z3Prover/z3
Z3 commit: 459629c662eb7abf25a010b7383431a9f729d234
Z3 branch: master
Z3 options: "-T:20 -v:2 -st tactic.default_tactic="(then simplify propagate-values solve-eqs simplify sls-smt)" model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFBVDTNIA.tar.zst?download=1
Z3 commit message: bugfixes to ho_matcher

Signed-off-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._54.smt2 |    0.026s | 20.404MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._04.smt2 |    0.027s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._45.smt2 |    0.033s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._56.smt2 |    0.035s | 20.052MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/arch__pgtable__entry_pverismo_arch.pgtable.entry_p.lemma_pt_entry_count._01.smt2 |    0.036s | 20.064MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._25.smt2 |    0.037s | 19.86MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._39.smt2 |    0.039s | 20.128MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._26.smt2 |    0.039s | 20.12MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__pow_pverismo_tspec.math.pow_p.proof_pow2_to_bits._02.smt2 |    0.039s | 20.14MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._49.smt2 |    0.039s | 20.056MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._48.smt2 |    0.040s | 20.152MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_next_power_of_two._02.smt2 |    0.040s | 20.412MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._04.smt2 |    0.040s | 20.016MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/allocator__bit_pverismo_allocator.bit_p.lemma_get_low_bits_via_bit_op._02.smt2 |    0.041s | 19.908MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._61.smt2 |    0.049s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.lemma_bitmask_to_is_bit_set._02.smt2 |    0.052s | 20.96MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._62.smt2 |    0.055s | 19.92MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._36.smt2 |    0.055s | 20.028MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._37.smt2 |    0.058s | 20.108MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._40.smt2 |    0.058s | 20.148MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._28.smt2 |    0.058s | 19.94MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._48.smt2 |    0.059s | 20.1MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._21.smt2 |    0.059s | 20.328MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._24.smt2 |    0.060s | 19.916MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._24.smt2 |    0.064s | 19.772MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._18.smt2 |    0.064s | 19.86MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._27.smt2 |    0.065s | 20.088MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._19.smt2 |    0.065s | 19.964MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._04.smt2 |    0.067s | 19.816MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._55.smt2 |    0.068s | 19.88MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._11.smt2 |    0.069s | 20.024MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._07.smt2 |    0.069s | 19.896MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._34.smt2 |    0.069s | 19.924MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_fill_ones._02.smt2 |    0.069s | 19.964MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._44.smt2 |    0.070s | 19.844MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._16.smt2 |    0.070s | 19.94MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._41.smt2 |    0.071s | 19.9MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._33.smt2 |    0.071s | 19.932MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._23.smt2 |    0.071s | 19.9MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._56.smt2 |    0.071s | 19.948MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._44.smt2 |    0.071s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._10.smt2 |    0.071s | 20.1MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._17.smt2 |    0.071s | 19.86MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._14.smt2 |    0.071s | 19.876MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._30.smt2 |    0.072s | 20.0MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._14.smt2 |    0.072s | 20.024MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._17.smt2 |    0.072s | 20.06MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._64.smt2 |    0.072s | 19.948MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._38.smt2 |    0.072s | 19.864MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._28.smt2 |    0.072s | 20.064MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._14.smt2 |    0.072s | 20.06MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._19.smt2 |    0.073s | 20.092MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._58.smt2 |    0.073s | 19.856MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._49.smt2 |    0.073s | 19.888MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/arch__pgtable__entry_pverismo_arch.pgtable.entry_p.impl_%0.lemma_size_offset._01.smt2 |    0.073s | 20.136MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._46.smt2 |    0.073s | 19.876MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._05.smt2 |    0.073s | 20.108MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._18.smt2 |    0.073s | 19.872MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._34.smt2 |    0.073s | 20.068MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._56.smt2 |    0.073s | 19.904MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._23.smt2 |    0.073s | 20.132MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._25.smt2 |    0.074s | 20.012MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._51.smt2 |    0.076s | 19.892MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_prev_power_of_two._01.smt2 |    0.078s | 20.188MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_fill_ones_bit_step._03.smt2 |    0.079s | 20.08MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_impllib_impl_u.l2_impl.impl_%0.lemma_zero_entry_facts._02.smt2 |    0.079s | 20.332MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-layoutlib_layout.calculate_segment_ptr_from_block._01.smt2 |    0.100s | 21.36MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._02.smt2 |    0.111s | 20.08MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._59.smt2 |    0.114s | 20.356MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._02.smt2 |    0.114s | 19.848MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._57.smt2 |    0.117s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-bin_sizeslib_bin_sizes.bin._04.smt2 |    0.118s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._07.smt2 |    0.120s | 20.068MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._31.smt2 |    0.121s | 20.288MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/atmosphere/util__page_ptr_util_ulib_util.page_ptr_util_u.v2l3index._01.smt2 |    0.122s | 20.152MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._34.smt2 |    0.123s | 20.34MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._22.smt2 |    0.123s | 20.08MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._62.smt2 |    0.124s | 19.9MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._11.smt2 |    0.124s | 20.1MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._40.smt2 |    0.124s | 19.88MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._05.smt2 |    0.125s | 19.864MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._36.smt2 |    0.125s | 19.9MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_prev_power_of_two._03.smt2 |    0.125s | 20.144MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._30.smt2 |    0.125s | 20.228MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_clear_set_property._01.smt2 |    0.127s | 20.112MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__gdtverismo_snp.cpu.gdt.impl_%16.empty._01.smt2 |    0.127s | 22.052MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__security__sectype_test__pverismo_tspec.security.sectype_test.p.proof_test_bits2._01.smt2 |    0.127s | 19.864MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._52.smt2 |    0.127s | 20.44MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._62.smt2 |    0.127s | 20.072MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._27.smt2 |    0.127s | 19.86MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._27.smt2 |    0.127s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._51.smt2 |    0.127s | 19.9MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.proof_align_down._03.smt2 |    0.128s | 20.288MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-layoutlib_layout.bitand_with_mask_gives_rounding._07.smt2 |    0.128s | 20.404MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-bin_sizeslib_bin_sizes.shift_is_div._02.smt2 |    0.128s | 20.112MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._03.smt2 |    0.130s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._59.smt2 |    0.130s | 20.332MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._38.smt2 |    0.131s | 20.02MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._32.smt2 |    0.132s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_1._05.smt2 |    0.134s | 20.76MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._55.smt2 |    0.137s | 19.904MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._47.smt2 |    0.137s | 20.116MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._44.smt2 |    0.140s | 20.052MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._58.smt2 |    0.140s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._01.smt2 |    0.141s | 20.348MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-freelib_free.free_block_mt._01.smt2 |    0.141s | 22.492MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.lemma_obtain_bit_index_1_aux._03.smt2 |    0.142s | 20.956MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.impl_%0.next_run._10.smt2 |    0.142s | 20.912MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/atmosphere/util__page_ptr_util_ulib_util.page_ptr_util_u.v2l4index._01.smt2 |    0.144s | 20.104MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_1._03.smt2 |    0.144s | 20.62MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._07.smt2 |    0.146s | 19.86MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._11.smt2 |    0.146s | 19.856MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._50.smt2 |    0.147s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._55.smt2 |    0.147s | 20.24MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._54.smt2 |    0.148s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._06.smt2 |    0.150s | 19.86MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._45.smt2 |    0.152s | 19.88MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.impl_%0.next_run._02.smt2 |    0.152s | 21.24MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._12.smt2 |    0.153s | 19.96MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._13.smt2 |    0.154s | 20.132MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._60.smt2 |    0.154s | 20.248MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._31.smt2 |    0.155s | 20.152MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._57.smt2 |    0.156s | 20.072MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._11.smt2 |    0.156s | 19.904MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._28.smt2 |    0.156s | 19.9MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._52.smt2 |    0.157s | 19.888MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._19.smt2 |    0.157s | 20.024MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._50.smt2 |    0.157s | 20.12MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._56.smt2 |    0.157s | 19.876MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._35.smt2 |    0.157s | 20.088MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_impllib_impl_u.l2_impl.impl_%0.lemma_zero_entry_facts._03.smt2 |    0.157s | 20.148MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._12.smt2 |    0.158s | 20.144MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._19.smt2 |    0.158s | 20.08MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._58.smt2 |    0.158s | 19.912MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._02.smt2 |    0.158s | 19.916MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._33.smt2 |    0.158s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._06.smt2 |    0.158s | 20.62MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._49.smt2 |    0.159s | 19.864MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_property_auto._01.smt2 |    0.161s | 19.972MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.lemma_obtain_bit_index_3_aux._01.smt2 |    0.163s | 20.704MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/debug__ghcb_printverismo_debug.ghcb_print.int2bytes._01.smt2 |    0.164s | 23.148MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.lemma_obtain_bit_index_3_aux._02.smt2 |    0.164s | 20.428MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_2._05.smt2 |    0.164s | 20.804MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_fill_ones._06.smt2 |    0.166s | 20.64MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_prev_power_of_two._02.smt2 |    0.167s | 20.42MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_1._02.smt2 |    0.167s | 20.592MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-layoutlib_layout.bitand_with_mask_gives_rounding._08.smt2 |    0.173s | 20.888MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.impl_%0.next_run._05.smt2 |    0.176s | 20.976MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_1._08.smt2 |    0.187s | 21.324MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_2._07.smt2 |    0.187s | 21.18MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_2._12.smt2 |    0.188s | 21.28MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.masked_ptr_delay_set_ptr._02.smt2 |    0.192s | 22.124MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.impl_%8.take._01.smt2 |    0.206s | 22.076MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.masked_ptr_delay_get_ptr._01.smt2 |    0.207s | 22.14MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.masked_ptr_delay_set_freeing._01.smt2 |    0.209s | 22.172MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/security__memverismo_security.mem.impl_%16.empty._01.smt2 |    0.297s | 27.152MiB| unknown | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__vmsaverismo_snp.cpu.vmsa.impl_%16.empty._01.smt2 |    0.320s | 26.7MiB| unknown | 0 |  |  |
