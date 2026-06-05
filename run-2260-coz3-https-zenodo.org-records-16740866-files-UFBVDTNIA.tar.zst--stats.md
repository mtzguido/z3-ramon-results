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
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/UFBVDTNIA.tar.zst?download=1 | Source list: quantifier_benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-UFBVDTNIA.tar.zst-
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: c3f5365a95a7eac2419a2f95ff240909f275cc08
Z3 branch: c3f5365a95a7eac2419a2f95ff240909f275cc08
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFBVDTNIA.tar.zst?download=1
Z3 commit message: Update generation number of already-internalized enodes (#9628)

Below are the effects on Mariposa's unsat core:

| Query | Unsats before | Unknowns before | Timeouts before | Unsats
after | Unknowns after | Timeouts after | Delta Unsat | Delta Unknown |
Delta Timeout |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|
|
d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2
| 94 | 5 | 1 | 99 | 0 | 1 | +5 | -5 | +0 |
|
d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2
| 41 | 0 | 59 | 44 | 0 | 56 | +3 | +0 | -3 |
|
d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2
| 75 | 25 | 0 | 99 | 1 | 0 | +24 | -24 | +0 |
|
d_fvbkv-Impl-FlushPolicyImpl.i.dfy.Impl__FlushPolicyImpl.__default.runFlushPolicy.smt2
| 12 | 0 | 88 | 6 | 0 | 94 | -6 | +0 | +6 |
| d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2 |
84 | 0 | 16 | 81 | 0 | 19 | -3 | +0 | +3 |
|
d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.append.smt2
| 88 | 12 | 0 | 99 | 1 | 0 | +11 | -11 | +0 |
|
d_fvbkv-Impl-QueryImpl.i.dfy.Impl__QueryImpl.__default.queryIterate.smt2
| 48 | 0 | 52 | 43 | 0 | 57 | -5 | +0 | +5 |
|
d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__0__self__uint64.smt2
| 100 | 0 | 0 | 100 | 0 | 0 | +0 | +0 | +0 |
|
d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__1__self__uint64.smt2
| 100 | 0 | 0 | 100 | 0 | 0 | +0 | +0 | +0 |
|
d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IndexFillDpkv.smt2
| 42 | 0 | 58 | 41 | 0 | 59 | -1 | +0 | +1 |
|
d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2
| 78 | 5 | 17 | 92 | 1 | 7 | +14 | -4 | -10 |
|
d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2
| 100 | 0 | 0 | 100 | 0 | 0 | +0 | +0 | +0 |
|
d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.WFpsaSubSeq.smt2
| 90 | 1 | 9 | 82 | 0 | 18 | -8 | -1 | +9 |
|
d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2
| 8 | 0 | 92 | 9 | 0 | 91 | +1 | +0 | -1 |
|
d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2
| 92 | 5 | 3 | 97 | 0 | 3 | +5 | -5 | +0 |
|
d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2
| 44 | 28 | 28 | 50 | 2 | 48 | +6 | -26 | +20 |
|
d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubReprLowerBound.smt2
| 96 | 4 | 0 | 98 | 2 | 0 | +2 | -2 | +0 |
|
d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2
| 46 | 54 | 0 | 76 | 24 | 0 | +30 | -30 | +0 |
|
d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2
| 81 | 19 | 0 | 96 | 3 | 1 | +15 | -16 | +1 |
|
d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2
| 85 | 15 | 0 | 95 | 5 | 0 | +10 | -10 | +0 |
|
d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__2toX.smt2
| 74 | 26 | 0 | 100 | 0 | 0 | +26 | -26 | +0 |
|
d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__denominator.smt2
| 93 | 0 | 7 | 99 | 0 | 1 | +6 | +0 | -6 |
|
d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall2.smt2
| 67 | 0 | 33 | 67 | 0 | 33 | +0 | +0 | +0 |
|
d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall.smt2
| 0 | 0 | 100 | 0 | 0 | 100 | +0 | +0 | +0 |
|
d_fvbkv-lib-Math-mul.i.dfy.Impl__Math____mul__i.__default.lemma__mul__nonnegative.smt2
| 0 | 0 | 100 | 0 | 0 | 100 | +0 | +0 | +0 |
|
d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__l1ptesmatch.smt2
| 59 | 0 | 41 | 68 | 0 | 32 | +9 | +0 | -9 |
|
d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__initL2PTable__loweq__pdb.smt2
| 81 | 0 | 19 | 85 | 0 | 15 | +4 | +0 | -4 |
|
d_komodo-verified-sha-sha256-body-00-15.gen.dfyImpl___module.__default.va__refined__Body__00__15UnrolledRecursive.smt2
| 0 | 0 | 100 | 0 | 0 | 100 | +0 | +0 | +0 |
|
d_komodo-verified-sha-sha256-body-16-xx.gen.dfyImpl___module.__default.va__refined__Body__16__XXUnroller.smt2
| 8 | 0 | 92 | 9 | 0 | 91 | +1 | +0 | -1 |
|
d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__SHA256FinalHelper1.smt2
| 95 | 0 | 5 | 95 | 1 | 4 | +0 | +1 | -1 |
|
d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify__inner_k.smt2
| 9 | 0 | 91 | 6 | 0 | 94 | -3 | +0 | +3 |
|
d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify__inner.smt2
| 69 | 0 | 31 | 61 | 0 | 39 | -8 | +0 | +8 |
|
d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify.smt2
| 85 | 0 | 15 | 78 | 0 | 22 | -7 | +0 | +7 |
|
d_lvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenComposeIsCompose.smt2
| 53 | 0 | 47 | 53 | 0 | 47 | +0 | +0 | +0 |
|
d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.append.smt2
| 93 | 4 | 3 | 96 | 0 | 4 | +3 | -4 | +1 |
|
d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.strictlySortedPivotsToVal.smt2
| 5 | 0 | 95 | 0 | 0 | 100 | -5 | +0 | +5 |
|
d_lvbkv-lib-Base-total_order_impl.i.dfy.Impl__Total__Order__Impl.__default.ArrayLargestLtePlus1Linear.smt2
| 48 | 52 | 0 | 99 | 1 | 0 | +51 | -51 | +0 |
|
d_lvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperSplitBucketInList.smt2
| 39 | 22 | 39 | 40 | 15 | 45 | +1 | -7 | +6 |
|
d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.DynamicPkv.Append.smt2
| 80 | 0 | 20 | 80 | 0 | 20 | +0 | +0 | +0 |
|
d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2
| 15 | 5 | 80 | 11 | 0 | 89 | -4 | -5 | +9 |
|
d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.psaCanAppendI.smt2
| 61 | 0 | 39 | 70 | 0 | 30 | +9 | +0 | -9 |
|
d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.DynamicPsa.AppendSeq.smt2
| 2 | 0 | 98 | 4 | 0 | 96 | +2 | +0 | -2 |
|
d_lvbkv-lib-Checksums-BitLemmas.i.dfy.Impl__BitLemmas.__default.eq__from__unpack__LittleEndian__Uint32__eq.smt2
| 99 | 0 | 1 | 99 | 0 | 1 | +0 | +0 | +0 |
|
d_lvbkv-lib-DataStructures-LinearContentMutableMap.i.dfy.Impl__LinearContentMutableMap.__default.Realloc.smt2
| 1 | 0 | 99 | 0 | 0 | 100 | -1 | +0 | +1 |
|
d_lvbkv-lib-DataStructures-LinearDList.i.dfy.Impl__DList.DList.InsertAfter.smt2
| 0 | 0 | 100 | 0 | 0 | 100 | +0 | +0 | +0 |
|
d_lvbkv-lib-DataStructures-LinearDList.i.dfy.Impl__DList.DList.InsertBefore.smt2
| 0 | 2 | 98 | 0 | 1 | 99 | +0 | -1 | +1 |
|
d_lvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__LMutableBtree.__default.InsertIndex.smt2
| 98 | 0 | 2 | 83 | 0 | 17 | -15 | +0 | +15 |
|
d_lvbkv-lib-Lang-LinearSequence.i.dfy.Impl__LinearSequence__i.__default.AllocAndMoveLseq.smt2
| 97 | 3 | 0 | 100 | 0 | 0 | +3 | -3 | +0 |
|
d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2
| 79 | 21 | 0 | 77 | 23 | 0 | -2 | +2 | +0 |
|
d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallByteArrayInterior.smt2
| 100 | 0 | 0 | 100 | 0 | 0 | +0 | +0 | +0 |
|
d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallByteArray.smt2
| 94 | 6 | 0 | 98 | 2 | 0 | +4 | -4 | +0 |
|
d_lvbkv-lib-Math-Nonlinear.i.dfy.Impl__NonlinearLemmas.__default.div__denom__ge__1.smt2
| 91 | 9 | 0 | 97 | 3 | 0 | +6 | -6 | +0 |
|
d_lvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.RefinesReplay.smt2
| 69 | 0 | 31 | 66 | 0 | 34 | -3 | +0 | +3 |
|
d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.SplitChildrenConsistent.smt2
| 31 | 0 | 69 | 28 | 0 | 72 | -3 | +0 | +3 |
|
d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.ValidSplitWritesInvNodes.smt2
| 100 | 0 | 0 | 99 | 0 | 1 | -1 | +0 | +1 |
| fs_dice-queries-ASN1.Low.Base-3.smt2 | 1 | 32 | 0 | 1 | 32 | 0 | +0 |
+0 | +0 |
| fs_dice-queries-L0.X509.AliasKeyTBS.Issuer-7.smt2 | 33 | 0 | 0 | 33 |
0 | 0 | +0 | +0 | +0 |
| fs_dice-queries-L0.X509.AliasKeyTBS.Subject-7.smt2 | 33 | 0 | 0 | 33 |
0 | 0 | +0 | +0 | +0 |
| s_komodo-1504.4.smt2 | 0 | 0 | 100 | 0 | 0 | 100 | +0 | +0 | +0 |

---------

Co-authored-by: Can Cebeci <t-cancebeci@microsoft.com>
Co-authored-by: Nikolaj Bjorner <nbjorner@microsoft.com>

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._17.smt2 |    0.015s | 19.324MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._62.smt2 |    0.016s | 19.264MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_impllib_impl_u.l2_impl.impl_%0.lemma_zero_entry_facts._03.smt2 |    0.016s | 19.456MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_impllib_impl_u.l2_impl.impl_%0.lemma_zero_entry_facts._02.smt2 |    0.016s | 19.404MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._48.smt2 |    0.017s | 19.324MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._07.smt2 |    0.017s | 19.424MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._49.smt2 |    0.017s | 19.224MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._28.smt2 |    0.017s | 19.364MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._01.smt2 |    0.017s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._47.smt2 |    0.017s | 19.336MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._27.smt2 |    0.017s | 19.16MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._12.smt2 |    0.017s | 19.272MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/atmosphere/util__page_ptr_util_ulib_util.page_ptr_util_u.v2l4index._01.smt2 |    0.018s | 19.78MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._04.smt2 |    0.018s | 19.332MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._14.smt2 |    0.018s | 19.34MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._56.smt2 |    0.018s | 19.444MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._36.smt2 |    0.018s | 19.136MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._07.smt2 |    0.018s | 19.284MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._55.smt2 |    0.018s | 19.324MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._05.smt2 |    0.019s | 19.392MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._34.smt2 |    0.019s | 19.46MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._13.smt2 |    0.019s | 19.288MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._40.smt2 |    0.019s | 19.384MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._49.smt2 |    0.019s | 19.292MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._27.smt2 |    0.019s | 19.324MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._14.smt2 |    0.019s | 19.32MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._59.smt2 |    0.019s | 19.328MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._31.smt2 |    0.019s | 19.24MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._57.smt2 |    0.020s | 19.296MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._57.smt2 |    0.020s | 19.348MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._07.smt2 |    0.020s | 19.296MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._26.smt2 |    0.020s | 19.388MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._02.smt2 |    0.020s | 19.312MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._18.smt2 |    0.020s | 19.328MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._02.smt2 |    0.020s | 19.224MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._30.smt2 |    0.020s | 19.432MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._44.smt2 |    0.020s | 19.316MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._10.smt2 |    0.020s | 19.392MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._22.smt2 |    0.020s | 19.244MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._34.smt2 |    0.020s | 19.336MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._55.smt2 |    0.020s | 19.324MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-bin_sizeslib_bin_sizes.bin._04.smt2 |    0.020s | 19.444MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._33.smt2 |    0.021s | 19.324MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._19.smt2 |    0.021s | 19.224MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._24.smt2 |    0.021s | 19.292MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._58.smt2 |    0.021s | 19.324MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._50.smt2 |    0.021s | 19.276MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._11.smt2 |    0.021s | 19.364MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._30.smt2 |    0.021s | 19.356MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._36.smt2 |    0.021s | 19.216MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._45.smt2 |    0.021s | 19.256MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._17.smt2 |    0.021s | 19.316MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._56.smt2 |    0.021s | 19.328MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._11.smt2 |    0.021s | 19.22MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._49.smt2 |    0.021s | 19.288MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._06.smt2 |    0.021s | 19.296MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/arch__pgtable__entry_pverismo_arch.pgtable.entry_p.lemma_pt_entry_count._01.smt2 |    0.022s | 19.436MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._58.smt2 |    0.022s | 19.32MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._32.smt2 |    0.022s | 19.44MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._38.smt2 |    0.022s | 19.344MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._19.smt2 |    0.022s | 19.292MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._02.smt2 |    0.022s | 19.336MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._35.smt2 |    0.022s | 19.344MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._44.smt2 |    0.023s | 19.312MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._45.smt2 |    0.023s | 19.284MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._64.smt2 |    0.023s | 19.292MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._28.smt2 |    0.023s | 19.312MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._14.smt2 |    0.024s | 19.132MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.lemma_obtain_bit_index_3_aux._02.smt2 |    0.024s | 19.892MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-layoutlib_layout.bitand_with_mask_gives_rounding._07.smt2 |    0.024s | 19.988MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._46.smt2 |    0.025s | 19.288MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._03.smt2 |    0.025s | 19.16MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._54.smt2 |    0.025s | 19.132MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.lemma_obtain_bit_index_3_aux._01.smt2 |    0.025s | 19.94MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._19.smt2 |    0.026s | 19.432MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._39.smt2 |    0.026s | 19.436MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._21.smt2 |    0.026s | 19.396MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._60.smt2 |    0.026s | 19.268MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._33.smt2 |    0.026s | 19.324MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._44.smt2 |    0.027s | 19.256MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__security__sectype_test__pverismo_tspec.security.sectype_test.p.proof_test_bits2._01.smt2 |    0.028s | 20.004MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_2._05.smt2 |    0.028s | 20.148MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_1._05.smt2 |    0.028s | 19.92MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._52.smt2 |    0.029s | 19.332MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._54.smt2 |    0.029s | 19.252MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._12.smt2 |    0.029s | 19.36MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._23.smt2 |    0.029s | 19.372MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._25.smt2 |    0.029s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._04.smt2 |    0.029s | 20.156MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_1._02.smt2 |    0.029s | 20.016MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._55.smt2 |    0.030s | 20.28MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._52.smt2 |    0.030s | 19.328MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._06.smt2 |    0.030s | 20.228MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._05.smt2 |    0.030s | 20.124MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._50.smt2 |    0.030s | 19.208MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._41.smt2 |    0.031s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._48.smt2 |    0.031s | 20.224MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._58.smt2 |    0.031s | 19.288MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._31.smt2 |    0.031s | 19.24MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._37.smt2 |    0.031s | 20.304MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._56.smt2 |    0.031s | 20.264MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._40.smt2 |    0.031s | 20.2MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._24.smt2 |    0.031s | 20.144MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._51.smt2 |    0.031s | 19.268MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._27.smt2 |    0.032s | 20.156MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__pow_pverismo_tspec.math.pow_p.proof_pow2_to_bits._02.smt2 |    0.032s | 20.392MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.lemma_bit_and_mod_rel._56.smt2 |    0.032s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._11.smt2 |    0.033s | 19.352MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._25.smt2 |    0.033s | 20.212MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/arch__pgtable__entry_pverismo_arch.pgtable.entry_p.impl_%0.lemma_size_offset._01.smt2 |    0.034s | 19.532MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shr_div_rel._61.smt2 |    0.034s | 19.276MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_1._03.smt2 |    0.034s | 20.136MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_prev_power_of_two._03.smt2 |    0.035s | 19.332MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_fill_ones._02.smt2 |    0.035s | 19.436MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._16.smt2 |    0.037s | 19.212MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._04.smt2 |    0.037s | 19.312MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._23.smt2 |    0.037s | 20.288MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/atmosphere/util__page_ptr_util_ulib_util.page_ptr_util_u.v2l3index._01.smt2 |    0.038s | 19.52MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_clear_set_property._01.smt2 |    0.038s | 20.816MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit64_and_rel_mod._62.smt2 |    0.038s | 19.372MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.proof_bit_usize_and_rel_mod._34.smt2 |    0.038s | 19.404MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._62.smt2 |    0.039s | 20.344MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/allocator__bit_pverismo_allocator.bit_p.lemma_get_low_bits_via_bit_op._02.smt2 |    0.040s | 20.448MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._11.smt2 |    0.041s | 20.216MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._38.smt2 |    0.042s | 20.236MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._18.smt2 |    0.043s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._51.smt2 |    0.045s | 20.284MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._19.smt2 |    0.048s | 20.164MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._28.smt2 |    0.048s | 20.216MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_fill_ones_bit_step._03.smt2 |    0.050s | 20.848MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_shl_mul_rel._59.smt2 |    0.050s | 20.152MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_prev_power_of_two._02.smt2 |    0.053s | 21.3MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.impl_%0.next_run._02.smt2 |    0.062s | 22.408MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.impl_%0.next_run._10.smt2 |    0.064s | 22.416MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-layoutlib_layout.bitand_with_mask_gives_rounding._08.smt2 |    0.064s | 22.828MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_next_power_of_two._02.smt2 |    0.065s | 21.348MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.lemma_obtain_bit_index_1_aux._03.smt2 |    0.065s | 23.564MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_prev_power_of_two._01.smt2 |    0.067s | 21.036MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.impl_%0.next_run._05.smt2 |    0.067s | 22.532MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__integerverismo_tspec.math.integer.lemma_fill_ones._06.smt2 |    0.079s | 21.74MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_2._12.smt2 |    0.080s | 23.4MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-layoutlib_layout.calculate_segment_ptr_from_block._01.smt2 |    0.080s | 22.96MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_1._08.smt2 |    0.081s | 23.224MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/page-table-smt-impl_u__l2_refinementlib_impl_u.l2_refinement.lemma_page_table_walk_interp_aux_2._07.smt2 |    0.085s | 23.096MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/debug__ghcb_printverismo_debug.ghcb_print.int2bytes._01.smt2 |    0.096s | 22.168MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.impl_%8.take._01.smt2 |    0.124s | 25.236MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.masked_ptr_delay_get_ptr._01.smt2 |    0.129s | 25.86MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.masked_ptr_delay_set_freeing._01.smt2 |    0.135s | 25.732MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__gdtverismo_snp.cpu.gdt.impl_%16.empty._01.smt2 |    0.140s | 26.452MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-linked_listlib_linked_list.masked_ptr_delay_set_ptr._02.smt2 |    0.140s | 25.76MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-freelib_free.free_block_mt._01.smt2 |    0.156s | 26.98MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-bin_sizeslib_bin_sizes.shift_is_div._02.smt2 |    0.272s | 22.476MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verussystems/mimalloc-smt-commit_masklib_commit_mask.lemma_bitmask_to_is_bit_set._02.smt2 |    0.308s | 24.276MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.proof_align_down._03.smt2 |    0.395s | 22.32MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/snp__cpu__vmsaverismo_snp.cpu.vmsa.impl_%16.empty._01.smt2 |    0.415s | 38.848MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/security__memverismo_security.mem.impl_%16.empty._01.smt2 |    0.464s | 49.008MiB| unsat | 0 |  |  |
|non-incremental/UFBVDTNIA/20241211-verus/verismo/tspec__math__bits_pverismo_tspec.math.bits_p.bit64_property_auto._01.smt2 |    0.601s | 24.896MiB| unsat | 0 |  |  |
