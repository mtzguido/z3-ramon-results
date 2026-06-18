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
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: 9091df56cbb91c668c6ef3e26899d2839d38e8a5
Z3 branch: master
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFBVDTNIA.tar.zst?download=1
Z3 commit message: Fix instance of "flexible array member". (#9883)

This is another PR towards the goal of getting a clean build with clang,
using the compiler options used in building clang-tidy.

In https://github.com/Z3Prover/z3/pull/9800, we changed the build flags
to eliminate a warning for zero-length arrays. In that PR, I missed this
one: there was one instance of m_arr[] instead of m_arr[0]. In the
clang-tidy build, that gives warnings like:
```
/Users/daviddetlefs/llvm-project/build_dbg/_deps/z3-src/src/model/func_interp.h:43:12: warning: flexible array members are a C99 feature [-Wc99-extensions]
```

The PR fixes this, making it a zero-length array, the idiom used in all
the other similar cases. I also added the compiler flag that produced
this warning, so we can notice such changes in the future.

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._62.smt2 |    0.016s | 19.34MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_impllib_impl_u.l2_impl.impl_%0.lemma_zero_entry_facts._03.smt2 |    0.016s | 19.352MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._24.smt2 |    0.017s | 19.232MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._07.smt2 |    0.017s | 19.42MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._31.smt2 |    0.017s | 19.204MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_impllib_impl_u.l2_impl.impl_%0.lemma_zero_entry_facts._02.smt2 |    0.017s | 19.412MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._33.smt2 |    0.018s | 19.376MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._48.smt2 |    0.018s | 19.352MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._01.smt2 |    0.018s | 19.212MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._36.smt2 |    0.018s | 19.164MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._27.smt2 |    0.018s | 19.188MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._16.smt2 |    0.019s | 19.388MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._13.smt2 |    0.019s | 19.228MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._49.smt2 |    0.019s | 19.22MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._21.smt2 |    0.019s | 19.384MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._28.smt2 |    0.019s | 19.4MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._49.smt2 |    0.019s | 19.328MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._28.smt2 |    0.019s | 19.32MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._19.smt2 |    0.019s | 19.456MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._55.smt2 |    0.019s | 19.316MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._44.smt2 |    0.020s | 19.288MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._57.smt2 |    0.020s | 19.372MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._50.smt2 |    0.020s | 19.352MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._34.smt2 |    0.020s | 19.324MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._30.smt2 |    0.020s | 19.432MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._44.smt2 |    0.020s | 19.292MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._17.smt2 |    0.020s | 19.288MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._07.smt2 |    0.020s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._02.smt2 |    0.020s | 19.3MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._34.smt2 |    0.020s | 19.372MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._55.smt2 |    0.020s | 19.284MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._06.smt2 |    0.020s | 19.308MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-bin_sizeslib_bin_sizes.bin._04.smt2 |    0.020s | 19.472MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._58.smt2 |    0.021s | 19.308MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._18.smt2 |    0.021s | 19.368MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._47.smt2 |    0.021s | 19.12MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._38.smt2 |    0.021s | 19.32MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._45.smt2 |    0.021s | 19.288MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._10.smt2 |    0.021s | 19.436MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._14.smt2 |    0.021s | 19.432MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._56.smt2 |    0.021s | 19.308MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._57.smt2 |    0.022s | 19.296MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/arch__pgtable__entry_pverismo_arch.pgtable.entry_p.lemma_pt_entry_count._01.smt2 |    0.022s | 19.452MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._54.smt2 |    0.022s | 19.428MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._30.smt2 |    0.022s | 19.364MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._32.smt2 |    0.022s | 19.288MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._36.smt2 |    0.022s | 19.432MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._56.smt2 |    0.022s | 19.376MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._02.smt2 |    0.022s | 19.32MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._27.smt2 |    0.022s | 19.336MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._35.smt2 |    0.022s | 19.328MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._59.smt2 |    0.022s | 19.356MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._04.smt2 |    0.023s | 19.364MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._19.smt2 |    0.023s | 19.296MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._58.smt2 |    0.023s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._07.smt2 |    0.023s | 19.316MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._45.smt2 |    0.023s | 19.296MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._64.smt2 |    0.023s | 19.432MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._19.smt2 |    0.024s | 19.232MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._39.smt2 |    0.024s | 19.392MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._46.smt2 |    0.024s | 19.364MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._56.smt2 |    0.024s | 19.352MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._51.smt2 |    0.024s | 19.268MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._58.smt2 |    0.025s | 19.42MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-layoutlib_layout.bitand_with_mask_gives_rounding._07.smt2 |    0.025s | 19.932MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._40.smt2 |    0.026s | 19.416MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._11.smt2 |    0.026s | 19.328MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._33.smt2 |    0.026s | 19.376MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.lemma_obtain_bit_index_3_aux._02.smt2 |    0.026s | 19.904MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._26.smt2 |    0.027s | 19.352MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._61.smt2 |    0.027s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._04.smt2 |    0.027s | 19.312MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.lemma_obtain_bit_index_3_aux._01.smt2 |    0.027s | 20.056MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._62.smt2 |    0.028s | 19.32MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._05.smt2 |    0.028s | 19.336MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._03.smt2 |    0.028s | 19.12MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._60.smt2 |    0.028s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_1._05.smt2 |    0.029s | 20.016MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._11.smt2 |    0.030s | 19.312MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._24.smt2 |    0.030s | 20.088MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_1._02.smt2 |    0.030s | 20.064MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_2._05.smt2 |    0.030s | 20.128MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._55.smt2 |    0.031s | 20.164MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/arch__pgtable__entry_pverismo_arch.pgtable.entry_p.impl_%0.lemma_size_offset._01.smt2 |    0.031s | 19.536MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__pow_pverismo_tspec.math.pow_p.proof_pow2_to_bits._02.smt2 |    0.031s | 20.368MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._62.smt2 |    0.031s | 20.188MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._50.smt2 |    0.031s | 19.288MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._23.smt2 |    0.031s | 20.272MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._22.smt2 |    0.031s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._25.smt2 |    0.031s | 20.128MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/atmosphere/util__page_ptr_util_ulib_util.page_ptr_util_u.v2l4index._01.smt2 |    0.032s | 19.376MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/atmosphere/util__page_ptr_util_ulib_util.page_ptr_util_u.v2l3index._01.smt2 |    0.032s | 19.44MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._52.smt2 |    0.032s | 19.36MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._52.smt2 |    0.032s | 19.248MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._06.smt2 |    0.032s | 20.152MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._12.smt2 |    0.032s | 19.324MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._04.smt2 |    0.032s | 20.14MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_1._03.smt2 |    0.032s | 19.952MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._41.smt2 |    0.033s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._48.smt2 |    0.033s | 20.172MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._23.smt2 |    0.033s | 19.316MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._31.smt2 |    0.033s | 19.4MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._37.smt2 |    0.033s | 20.104MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._56.smt2 |    0.033s | 20.216MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._54.smt2 |    0.033s | 19.276MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._02.smt2 |    0.034s | 19.244MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._14.smt2 |    0.034s | 19.296MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._25.smt2 |    0.035s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_prev_power_of_two._03.smt2 |    0.035s | 19.472MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._38.smt2 |    0.035s | 20.176MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._11.smt2 |    0.036s | 20.132MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._44.smt2 |    0.037s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__security__sectype_test__pverismo_tspec.security.sectype_test.p.proof_test_bits2._01.smt2 |    0.037s | 20.008MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._14.smt2 |    0.037s | 19.312MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._12.smt2 |    0.038s | 19.336MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._40.smt2 |    0.038s | 20.128MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._49.smt2 |    0.038s | 19.228MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._27.smt2 |    0.039s | 20.2MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._11.smt2 |    0.039s | 19.456MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._05.smt2 |    0.039s | 20.34MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._34.smt2 |    0.039s | 19.4MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._28.smt2 |    0.039s | 20.3MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._59.smt2 |    0.040s | 20.144MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/allocator__bit_pverismo_allocator.bit_p.lemma_get_low_bits_via_bit_op._02.smt2 |    0.040s | 20.608MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_fill_ones._02.smt2 |    0.041s | 19.532MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._17.smt2 |    0.042s | 19.152MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._51.smt2 |    0.046s | 20.196MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._19.smt2 |    0.049s | 20.312MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_prev_power_of_two._01.smt2 |    0.052s | 21.084MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._18.smt2 |    0.054s | 20.192MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_clear_set_property._01.smt2 |    0.057s | 20.828MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-layoutlib_layout.bitand_with_mask_gives_rounding._08.smt2 |    0.063s | 22.592MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.impl_%0.next_run._02.smt2 |    0.063s | 22.264MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.impl_%0.next_run._05.smt2 |    0.065s | 22.484MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.impl_%0.next_run._10.smt2 |    0.065s | 22.544MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_fill_ones_bit_step._03.smt2 |    0.067s | 20.804MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.lemma_obtain_bit_index_1_aux._03.smt2 |    0.068s | 23.456MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_prev_power_of_two._02.smt2 |    0.071s | 21.196MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_next_power_of_two._02.smt2 |    0.072s | 21.212MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-layoutlib_layout.calculate_segment_ptr_from_block._01.smt2 |    0.079s | 23.108MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_2._12.smt2 |    0.081s | 23.508MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_1._08.smt2 |    0.082s | 23.064MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_fill_ones._06.smt2 |    0.084s | 21.944MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_2._07.smt2 |    0.084s | 23.28MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/debug__ghcb_printverismo_debug.ghcb_print.int2bytes._01.smt2 |    0.090s | 22.24MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.impl_%8.take._01.smt2 |    0.126s | 25.444MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.masked_ptr_delay_get_ptr._01.smt2 |    0.133s | 25.856MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__gdtverismo_snp.cpu.gdt.impl_%16.empty._01.smt2 |    0.137s | 26.54MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.masked_ptr_delay_set_freeing._01.smt2 |    0.137s | 25.668MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.masked_ptr_delay_set_ptr._02.smt2 |    0.141s | 25.804MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-freelib_free.free_block_mt._01.smt2 |    0.156s | 26.928MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-bin_sizeslib_bin_sizes.shift_is_div._02.smt2 |    0.277s | 22.472MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.lemma_bitmask_to_is_bit_set._02.smt2 |    0.297s | 24.28MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.proof_align_down._03.smt2 |    0.392s | 22.252MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__vmsaverismo_snp.cpu.vmsa.impl_%16.empty._01.smt2 |    0.411s | 38.792MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/security__memverismo_security.mem.impl_%16.empty._01.smt2 |    0.459s | 48.828MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_property_auto._01.smt2 |    0.629s | 24.944MiB| unsat | 0 |  |  |
