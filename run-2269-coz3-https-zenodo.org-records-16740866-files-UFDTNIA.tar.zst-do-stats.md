# .

* SAT 0
* UNSAT 977
* TIMEOUT 31
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/UFDTNIA.tar.zst?download=1 | Source list: quantifier_benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-UFDTNIA.tar.zst-do
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: c3f5365a95a7eac2419a2f95ff240909f275cc08
Z3 branch: c3f5365a95a7eac2419a2f95ff240909f275cc08
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFDTNIA.tar.zst?download=1
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
|non-incremental/UFDTNIA/20241211-verus/atmosphere/define.20.smt2 |    0.016s | 19.284MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-constants.3.smt2 |    0.017s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-extra.1.smt2 |    0.017s | 19.264MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-extralib_extra.mult_leq_mono2._01.smt2 |    0.019s | 19.364MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/define.22.smt2 |    0.020s | 19.404MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_u.1.smt2 |    0.020s | 19.472MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l0.14.smt2 |    0.021s | 19.564MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-spec_t__hardware.2.smt2 |    0.021s | 19.56MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-spec_t__hardware.7.smt2 |    0.021s | 19.468MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/define.29.smt2 |    0.022s | 19.36MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_t.20.smt2 |    0.022s | 19.464MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_t.25.smt2 |    0.022s | 19.376MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/define.37.smt2 |    0.023s | 19.744MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/util__page_ptr_util_u.13.smt2 |    0.023s | 19.488MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-constants.8.smt2 |    0.023s | 20.02MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-spec_t__hardware.1.smt2 |    0.024s | 19.464MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-config.17.smt2 |    0.025s | 19.592MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-config.21.smt2 |    0.025s | 19.804MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-config.18.smt2 |    0.025s | 19.748MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-config.27.smt2 |    0.026s | 19.736MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-config.22.smt2 |    0.026s | 19.72MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layout__two_mul_with_bit1.smt2 |    0.026s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-config.24.smt2 |    0.026s | 19.62MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-config.32.smt2 |    0.026s | 19.612MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/splinterdb/marshalling__math_v.smt2 |    0.027s | 20.18MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-math.2.smt2 |    0.027s | 20.268MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-constants.6.smt2 |    0.027s | 20.064MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layout__align_downlib_layout.align_down._02.smt2 |    0.027s | 20.456MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-config.36.smt2 |    0.028s | 19.7MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_impl__PT.1.smt2 |    0.029s | 19.92MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/define.19.smt2 |    0.030s | 19.332MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__addr_s__def_s.3.smt2 |    0.030s | 19.864MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__indexinglib_impl_u.indexing.lemma_entry_base_from_index._01.smt2 |    0.030s | 20.596MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-math.5.smt2 |    0.031s | 20.352MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_impl__PT.5.smt2 |    0.031s | 19.764MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-spec_t__hardware.6.smt2 |    0.031s | 19.424MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__math_vlib_marshalling.math_v.distribute_left._01.smt2 |    0.031s | 20.748MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__indexinglib_impl_u.indexing.lemma_entry_base_from_index_support._02.smt2 |    0.032s | 20.308MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_t.18.smt2 |    0.032s | 19.396MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-mathmain_math.lemma_small_mod._01.smt2 |    0.032s | 20.34MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-mathmain_math.lemma_fundamental_div_mod_converse_helper_2._01.smt2 |    0.032s | 20.204MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-math.16.smt2 |    0.032s | 20.564MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/define.23.smt2 |    0.033s | 19.284MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/define.16.smt2 |    0.033s | 19.484MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-extralib_extra.lemma_aligned_iff_eq_mul_div._02.smt2 |    0.033s | 21.152MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-extralib_extra.lemma_aligned_iff_eq_mul_div._01.smt2 |    0.033s | 21.164MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-os_alloc.6.smt2 |    0.033s | 19.98MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/define.39.smt2 |    0.034s | 19.412MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-spec_t__hardware.4.smt2 |    0.034s | 19.672MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-mathmain_math.lemma_mul_is_distributive_add._01.smt2 |    0.034s | 20.676MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-extra.3.smt2 |    0.035s | 21.084MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-extralib_extra.mod_less_eq._01.smt2 |    0.035s | 20.884MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-mathmain_math.lemma_mul_is_distributive_sub_other_way._01.smt2 |    0.035s | 20.632MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/define.43.smt2 |    0.036s | 21.092MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l0.6.smt2 |    0.036s | 19.404MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/splinterdb/marshalling__math_vlib_marshalling.math_v.distribute_left._01.smt2 |    0.037s | 20.812MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-extralib_extra.mul_commute._01.smt2 |    0.037s | 20.816MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-spec_t__hardware.17.smt2 |    0.038s | 19.436MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-extralib_extra.mod_mult_zero_implies_mod_zero._01.smt2 |    0.038s | 21.108MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-math.20.smt2 |    0.038s | 20.724MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__math__align_sverismo_tspec.math.align_s.proof_align_down._01.smt2 |    0.039s | 20.484MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__stream__basic.1.smt2 |    0.040s | 20.7MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-config.38.smt2 |    0.041s | 19.812MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/vcell__vcell.smt2 |    0.042s | 20.12MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/ironkv-smt-verus_extra__seq_lib_vlib_verus_extra.seq_lib_v.lemma_seq_fold_left_sum_le._01.smt2 |    0.043s | 21.06MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.4.smt2 |    0.044s | 20.296MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.2.smt2 |    0.044s | 20.508MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l0.5.smt2 |    0.044s | 20.992MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__indexinglib_impl_u.indexing.lemma_index_from_base_and_addr._01.smt2 |    0.044s | 20.92MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-extralib_extra.aligned_transitive._02.smt2 |    0.045s | 21.368MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__math__bits_p.4.smt2 |    0.046s | 19.336MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_t.15.smt2 |    0.046s | 21.296MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-bin_sizeslib_bin_sizes.mod8._01.smt2 |    0.046s | 21.256MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_t.11.smt2 |    0.046s | 21.02MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-alloc_generic.2.smt2 |    0.046s | 21.148MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layout.27.smt2 |    0.046s | 19.968MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__math__pow_p.1.smt2 |    0.047s | 20.024MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-math.28.smt2 |    0.047s | 22.28MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_impl.14.smt2 |    0.047s | 21.34MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_s.9.smt2 |    0.048s | 20.716MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_s.2.smt2 |    0.048s | 20.764MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_list.32.smt2 |    0.048s | 20.776MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__indexinglib_impl_u.indexing.lemma_entry_base_from_index._05.smt2 |    0.048s | 20.84MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_t.22.smt2 |    0.048s | 21.4MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-bin_sizes.10.smt2 |    0.048s | 20.404MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_s.22.smt2 |    0.049s | 20.736MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_s.24.smt2 |    0.049s | 20.808MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_t.13.smt2 |    0.049s | 21.06MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/define.44.smt2 |    0.050s | 21.052MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_s.13.smt2 |    0.050s | 20.732MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_s.3.smt2 |    0.050s | 20.76MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-bin_sizes.1.smt2 |    0.050s | 20.692MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_s.25.smt2 |    0.051s | 20.768MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-mathmain_math.lemma_fundamental_div_mod_converse_helper_1._01.smt2 |    0.051s | 20.072MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__math_v.smt2 |    0.051s | 20.24MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_s.10.smt2 |    0.052s | 20.76MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_ulib_definitions_u.impl_%2.index_for_vaddr._01.smt2 |    0.052s | 21.348MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__stream__basic.2.smt2 |    0.053s | 20.992MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_t.24.smt2 |    0.053s | 21.552MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-mathmain_math.lemma_mul_is_associative._01.smt2 |    0.053s | 20.66MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-logimpl_v.10.smt2 |    0.054s | 21.616MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-mathmain_math.lemma_mul_left_inequality._01.smt2 |    0.055s | 20.772MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-os_alloc.8.smt2 |    0.055s | 20.048MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/splinterdb/marshalling__KVPairFormat_v.7.smt2 |    0.056s | 21.532MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-bin_sizeslib_bin_sizes.lemma_div_is_ordered._01.smt2 |    0.056s | 21.568MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/allocator__bit_p.smt2 |    0.057s | 22.696MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__pgtable__memmap_p.5.smt2 |    0.057s | 21.644MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/splinterdb/marshalling__KVPairFormat_v.1.smt2 |    0.057s | 21.84MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1.3.smt2 |    0.057s | 21.348MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.2.smt2 |    0.057s | 21.876MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/allocator__buddy.3.smt2 |    0.058s | 20.848MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-extralib_extra.mult_less_mono_both2._01.smt2 |    0.058s | 21.248MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_ulib_definitions_u.overflow_bounds._02.smt2 |    0.059s | 22.388MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/allocator__buddy.2.smt2 |    0.060s | 21.088MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1.12.smt2 |    0.060s | 21.672MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l0.24.smt2 |    0.060s | 21.596MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page.15.smt2 |    0.061s | 21.224MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-extralib_extra.mult_leq_mono_both._01.smt2 |    0.061s | 21.092MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.5.smt2 |    0.061s | 22.164MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__addr_s__page.1.smt2 |    0.062s | 21.68MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_s.23.smt2 |    0.062s | 20.672MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/splinterdb/marshalling__UniformSizedSeq_v.2.smt2 |    0.062s | 22.08MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1.13.smt2 |    0.062s | 21.616MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/va_range.2.smt2 |    0.063s | 21.736MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1.10.smt2 |    0.063s | 21.564MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-bin_sizes.40.smt2 |    0.063s | 21.572MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/lock__spincell_e.6.smt2 |    0.064s | 20.912MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__math__bits_p.7.smt2 |    0.064s | 23.636MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l0.19.smt2 |    0.064s | 22.992MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-bin_sizes.12.smt2 |    0.064s | 23.748MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-mathmain_math.lemma_mul_div_equal._01.smt2 |    0.064s | 20.992MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/trusted_hacl__stub.7.smt2 |    0.065s | 21.132MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l0.15.smt2 |    0.065s | 21.536MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-math.15.smt2 |    0.065s | 21.4MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-spec_t__hardware.19.smt2 |    0.065s | 21.992MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-spec_t__hardware.21.smt2 |    0.065s | 21.972MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-config.28.smt2 |    0.065s | 23.096MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layout__two_mul_with_bit1lib_layout.two_mul_with_bit1._01.smt2 |    0.066s | 20.884MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-extra.7.smt2 |    0.066s | 20.82MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__layout_v.27.smt2 |    0.066s | 21.968MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-init.10.smt2 |    0.067s | 21.048MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_impl.1.smt2 |    0.067s | 21.656MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/splinterdb/marshalling__UniformSizedSeq_v.5.smt2 |    0.068s | 22.228MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_ulib_definitions_u.impl_%2.next_entry_base._02.smt2 |    0.068s | 21.344MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_s.5.smt2 |    0.069s | 20.668MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-commit_mask.2.smt2 |    0.069s | 22.204MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/define.33.smt2 |    0.070s | 21.104MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__layout_v.30.smt2 |    0.070s | 22.092MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-init.1.smt2 |    0.070s | 21.228MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_s.27.smt2 |    0.071s | 20.844MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_s.26.smt2 |    0.071s | 20.832MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1.20.smt2 |    0.072s | 21.9MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-bin_sizes.42.smt2 |    0.072s | 22.208MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__snp__rmp__rmp_t.7.smt2 |    0.073s | 21.876MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__pgtable__memmap_p.3.smt2 |    0.073s | 23.656MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-mathmain_math.lemma_mul_one_to_one._01.smt2 |    0.073s | 20.944MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/util__page_ptr_util_u.8.smt2 |    0.074s | 21.68MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layout.4.smt2 |    0.074s | 23.228MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__snp__rmp__rmp_t.2.smt2 |    0.075s | 21.876MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_s.18.smt2 |    0.075s | 20.68MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1.7.smt2 |    0.075s | 21.604MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__inv_v.1.smt2 |    0.075s | 22.272MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-extra.8.smt2 |    0.075s | 21.192MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__ResizableUniformSizedSeq_v.4.smt2 |    0.075s | 22.588MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security.9.smt2 |    0.076s | 21.732MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__layout_v.26.smt2 |    0.076s | 21.788MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_s.31.smt2 |    0.077s | 20.62MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-os_alloc.3.smt2 |    0.077s | 22.44MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-config.15.smt2 |    0.077s | 22.336MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layoutlib_layout.calculate_slice_page_ptr_from_block._01.smt2 |    0.077s | 23.364MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security.10.smt2 |    0.078s | 21.504MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-mathmain_math.lemma_mul_is_distributive._01.smt2 |    0.078s | 21.016MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-root.smt2 |    0.078s | 23.304MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_u.11.smt2 |    0.078s | 22.072MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_ulib_definitions_u.impl_%3.lemma_entry_sizes_increase._01.smt2 |    0.079s | 22.324MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layoutlib_layout.calculate_page_block_at._02.smt2 |    0.079s | 23.404MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layout.6.smt2 |    0.079s | 23.52MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-config.23.smt2 |    0.079s | 22.7MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-logimpl_v.24.smt2 |    0.080s | 22.232MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/lemma__lemma_u.1.smt2 |    0.081s | 21.108MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__math__bits_p.8.smt2 |    0.081s | 26.852MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layout.26.smt2 |    0.081s | 23.336MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.1.smt2 |    0.081s | 22.004MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-pmem__pmcopy_t.3.smt2 |    0.083s | 21.76MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__pgtable__entry_p.3.smt2 |    0.085s | 24.724MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layoutlib_layout.bitand_with_mask_gives_rounding._09.smt2 |    0.087s | 23.844MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-logimpl_v.34.smt2 |    0.087s | 23.028MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security.2.smt2 |    0.088s | 21.604MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_ulib_definitions_u.impl_%2.next_entry_base._01.smt2 |    0.088s | 22.636MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__setlib.12.smt2 |    0.089s | 21.452MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1.27.smt2 |    0.089s | 22.084MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layout.22.smt2 |    0.089s | 23.616MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-main_t.7.smt2 |    0.090s | 22.304MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__inv_v.7.smt2 |    0.091s | 22.064MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__snp__rmp__rmp_t.6.smt2 |    0.092s | 21.776MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpuid.2.smt2 |    0.092s | 22.18MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1.33.smt2 |    0.092s | 22.432MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l0.23.smt2 |    0.092s | 23.648MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/mshyper.7.smt2 |    0.093s | 22.488MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-spec__cyclicbuffer.5.smt2 |    0.093s | 22.508MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__snp__rmp__rmp_t.8.smt2 |    0.094s | 21.884MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-commit_mask.27.smt2 |    0.094s | 24.012MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-logimpl_v.38.smt2 |    0.094s | 22.584MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-spec__cyclicbuffer.4.smt2 |    0.094s | 22.76MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layout.13.smt2 |    0.094s | 23.796MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-commit_mask.23.smt2 |    0.094s | 24.132MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpuid.13.smt2 |    0.095s | 22.2MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__snp__rmp__rmp_t.5.smt2 |    0.095s | 21.772MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/ironkv-smt-verus_extra__seq_lib_v.15.smt2 |    0.095s | 21.656MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/mshyper.17.smt2 |    0.097s | 22.408MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-commit_mask.13.smt2 |    0.097s | 24.4MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__setlib.11.smt2 |    0.098s | 21.704MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security.3.smt2 |    0.098s | 21.824MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__math__bits_p.9.smt2 |    0.098s | 29.272MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-commit_mask.5.smt2 |    0.098s | 23.936MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_impl.5.smt2 |    0.098s | 22.592MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layout.12.smt2 |    0.098s | 23.896MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__idt__def.3.smt2 |    0.099s | 21.808MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/mshyper.15.smt2 |    0.099s | 22.352MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/mshyper.1.smt2 |    0.099s | 22.488MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security.6.smt2 |    0.100s | 21.428MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-logimpl_v.15.smt2 |    0.100s | 23.204MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/mshyper.6.smt2 |    0.101s | 22.464MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/mshyper.14.smt2 |    0.103s | 22.36MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__math__integer.2.smt2 |    0.103s | 24.752MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpuid.5.smt2 |    0.105s | 22.288MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-commit_mask.1.smt2 |    0.105s | 23.752MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_ulib_definitions_u.impl_%2.entry_base._01.smt2 |    0.107s | 22.832MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpuid.11.smt2 |    0.109s | 22.236MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1lib_impl_u.l1.impl_%1.lemma_ranges_disjoint_interp_aux_interp_of_entry._01.smt2 |    0.110s | 23.508MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/util__page_ptr_util_u.14.smt2 |    0.111s | 21.848MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/mshyper.5.smt2 |    0.111s | 22.488MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_impl__PT.8.smt2 |    0.114s | 24.456MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/lemma__lemma_u.2.smt2 |    0.115s | 23.644MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__ptram__ptram_s.smt2 |    0.118s | 24.888MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__ptram__ptram_u.smt2 |    0.119s | 25.06MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/mshyper.11.smt2 |    0.119s | 22.32MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__params.5.smt2 |    0.121s | 23.328MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-commit_mask.6.smt2 |    0.121s | 24.116MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__layout_v.31.smt2 |    0.123s | 24.112MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/primitives_e__seq.2.smt2 |    0.126s | 24.964MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1.22.smt2 |    0.126s | 24.192MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__multilogimpl_v.1.smt2 |    0.126s | 24.268MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__cast.2.smt2 |    0.130s | 24.72MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-logimpl_v.17.smt2 |    0.130s | 22.584MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__params.8.smt2 |    0.131s | 23.332MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-bin_sizes.31.smt2 |    0.137s | 23.176MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/memory_manager__spec_impl.2.smt2 |    0.138s | 24.868MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1lib_impl_u.l1.impl_%1.lemma_interp_of_entries_disjoint._04.smt2 |    0.140s | 24.908MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__pgtable__entry_p.7.smt2 |    0.142s | 23.172MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__size_s.4.smt2 |    0.142s | 25.58MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-bin_sizes.35.smt2 |    0.142s | 24.992MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.4.smt2 |    0.142s | 22.652MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.1.smt2 |    0.145s | 24.32MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-logimpl_v.51.smt2 |    0.145s | 24.308MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-math.10.smt2 |    0.145s | 21.052MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-commit_mask.4.smt2 |    0.147s | 24.096MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_listlib_linked_list.impl_%2.prepend_contiguous_blocks._09.smt2 |    0.147s | 25.728MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-bin_sizes.14.smt2 |    0.147s | 23.176MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-spec__cyclicbuffer__CyclicBuffer.5.smt2 |    0.147s | 24.416MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_listlib_linked_list.impl_%2.prepend_contiguous_blocks._03.smt2 |    0.148s | 25.696MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_listlib_linked_list.impl_%2.prepend_contiguous_blocks._08.smt2 |    0.149s | 25.712MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layout.19.smt2 |    0.150s | 24.74MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec__replica.1.smt2 |    0.150s | 25.608MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-main_t.4.smt2 |    0.150s | 24.88MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__addr_s__def_s.8.smt2 |    0.151s | 25.692MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-logimpl_v.42.smt2 |    0.152s | 24.3MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-spec__cyclicbuffer__CyclicBuffer.3.smt2 |    0.152s | 24.864MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_listlib_linked_list.impl_%2.prepend_contiguous_blocks._05.smt2 |    0.154s | 25.824MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-spec__cyclicbuffer__CyclicBuffer.16.smt2 |    0.154s | 24.948MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-os_mem_util.3.smt2 |    0.155s | 25.332MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__layout_v.32.smt2 |    0.155s | 25.104MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec__log.7.smt2 |    0.156s | 25.724MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-root.5.smt2 |    0.156s | 25.46MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-os_mem_util.5.smt2 |    0.158s | 25.32MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1.45.smt2 |    0.159s | 25.188MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-spec__cyclicbuffer__CyclicBuffer.11.smt2 |    0.159s | 25.044MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-bin_sizes.41.smt2 |    0.160s | 22.84MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_list.9.smt2 |    0.161s | 25.976MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/registers__msr_t.3.smt2 |    0.164s | 26.208MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/registers__msr_t.7.smt2 |    0.164s | 26.084MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/splinterdb/marshalling__ResizableUniformSizedSeq_v.9.smt2 |    0.164s | 24.724MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-spec__cyclicbufferlib_spec.cyclicbuffer.log_entry_alive_value_wrap_around._01.smt2 |    0.164s | 22.932MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec_e__size_e.smt2 |    0.165s | 26.628MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__def_s.2.smt2 |    0.165s | 25.96MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_list.26.smt2 |    0.165s | 26.216MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/process_manager__spec_impl.12.smt2 |    0.166s | 26.368MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_list.39.smt2 |    0.166s | 25.86MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/memory_manager__spec_impl.8.smt2 |    0.167s | 25.152MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__ResizableUniformSizedSeq_v.9.smt2 |    0.167s | 24.7MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-spec__cyclicbuffer__CyclicBuffer.30.smt2 |    0.169s | 25.116MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-spec__cyclicbuffer__CyclicBuffer.32.smt2 |    0.169s | 25.172MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/memory_manager__spec_impl.9.smt2 |    0.170s | 25.292MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.2.smt2 |    0.170s | 26.132MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_listlib_linked_list.impl_%2.prepend_contiguous_blocks._06.smt2 |    0.170s | 25.728MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__logimpl_v.12.smt2 |    0.171s | 25.856MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-commit_mask.17.smt2 |    0.172s | 25.7MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-spec__cyclicbuffer__CyclicBuffer.28.smt2 |    0.173s | 25.28MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-alloc_generic__page_free_list_extendlib_alloc_generic.page_free_list_extend._07.smt2 |    0.173s | 25.812MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-os_mem_utillib_os_mem_util.preserves_mem_chunk_good_except._01.smt2 |    0.175s | 27.596MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec__replica.19.smt2 |    0.175s | 26.22MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/registers__msr_t.2.smt2 |    0.176s | 26.124MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/primitives_e__vec.1.smt2 |    0.177s | 26.752MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.3.smt2 |    0.177s | 26.076MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.13.smt2 |    0.178s | 26.62MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec.4.smt2 |    0.178s | 26.52MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-alloc_fast.4.smt2 |    0.178s | 26.06MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-alloc_generic__page_free_list_extendlib_alloc_generic.page_free_list_extend._05.smt2 |    0.178s | 27.212MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec__log.16.smt2 |    0.179s | 25.832MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.6.smt2 |    0.180s | 26.556MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec.3.smt2 |    0.183s | 27.672MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.20.smt2 |    0.185s | 26.656MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__cast.5.smt2 |    0.187s | 26.44MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-os_mem_utillib_os_mem_util.preserves_mem_chunk_good_on_transfer_to_capacity._02.smt2 |    0.187s | 27.896MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_list.11.smt2 |    0.187s | 28.248MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-alloc_generic__page_free_list_extendlib_alloc_generic.page_free_list_extend._04.smt2 |    0.188s | 25.956MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-alloc_generic__page_free_list_extendlib_alloc_generic.page_free_list_extend._09.smt2 |    0.188s | 27.316MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/primitives_e__vec.2.smt2 |    0.189s | 26.72MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layout__align_down.smt2 |    0.189s | 21.36MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/registers__msr_t.11.smt2 |    0.190s | 26.2MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.61.smt2 |    0.191s | 27.228MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.35.smt2 |    0.191s | 26.848MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec__log.1.smt2 |    0.192s | 26.696MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.23.smt2 |    0.193s | 26.736MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.4.smt2 |    0.193s | 26.08MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec__replica.6.smt2 |    0.193s | 27.256MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/process_manager__spec_impl.1.smt2 |    0.194s | 32.22MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.42.smt2 |    0.194s | 26.616MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.26.smt2 |    0.195s | 28.344MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/process_manager__spec_impl.19.smt2 |    0.196s | 32.608MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/process_manager__spec_impl.6.smt2 |    0.197s | 31.744MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_refinement.1.smt2 |    0.198s | 27.196MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.19.smt2 |    0.198s | 28.392MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec__log.3.smt2 |    0.198s | 26.324MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__cast.6.smt2 |    0.199s | 27.612MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1.35.smt2 |    0.199s | 25.568MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-segment__segment_alloclib_segment.segment_alloc._02.smt2 |    0.200s | 27.916MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__snp__snp_u.2.smt2 |    0.201s | 27.164MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.15.smt2 |    0.201s | 28.492MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-bin_sizes.30.smt2 |    0.201s | 24.248MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/splinterdb/marshalling__ResizableUniformSizedSeq_v.3.smt2 |    0.202s | 23.848MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.17.smt2 |    0.204s | 27.564MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__def.7.smt2 |    0.205s | 28.032MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1.42.smt2 |    0.205s | 27.368MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_s.41.smt2 |    0.206s | 28.232MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec__log.20.smt2 |    0.206s | 26.74MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-alloc_generic__page_free_list_extendlib_alloc_generic.page_free_list_extend._03.smt2 |    0.207s | 28.008MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__cast.7.smt2 |    0.209s | 27.728MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec__replica.4.smt2 |    0.209s | 27.764MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__inv_v.16.smt2 |    0.209s | 25.048MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/process_manager__spec_impl.24.smt2 |    0.210s | 32.084MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/process_manager__spec_impl.2.smt2 |    0.210s | 33.268MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_s.43.smt2 |    0.210s | 27.988MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.24.smt2 |    0.210s | 27.576MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layout.17.smt2 |    0.210s | 24.608MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-logimpl_v.32.smt2 |    0.211s | 25.432MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-bin_sizes.19.smt2 |    0.212s | 24.196MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.36.smt2 |    0.212s | 26.852MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_list.24.smt2 |    0.212s | 26.72MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/addr_e__range_interface.5.smt2 |    0.213s | 27.264MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-spec__cyclicbuffer__CyclicBuffer.22.smt2 |    0.215s | 26.224MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-commit_mask.35.smt2 |    0.216s | 25.18MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__cast.4.smt2 |    0.218s | 26.876MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/addr_e__addr_interface.11.smt2 |    0.218s | 28.916MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.40.smt2 |    0.219s | 26.76MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-os_mem_util.11.smt2 |    0.219s | 28.244MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.51.smt2 |    0.219s | 28.536MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/pagetable__pagetable_spec_impl.10.smt2 |    0.221s | 33.36MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.38.smt2 |    0.221s | 28.124MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-init.11.smt2 |    0.221s | 29.008MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.11.smt2 |    0.223s | 29.96MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.60.smt2 |    0.225s | 29.236MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__snp__snp_u.8.smt2 |    0.229s | 27.668MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.48.smt2 |    0.230s | 29.836MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec__log.8.smt2 |    0.230s | 27.288MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/process_manager__spec_impl.8.smt2 |    0.231s | 33.408MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__vram__vram_p.12.smt2 |    0.231s | 29.072MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-pagelib_page.page_init._02.smt2 |    0.232s | 28.528MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.34.smt2 |    0.235s | 28.4MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__addr_s__page.6.smt2 |    0.236s | 23.256MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__inv_v.10.smt2 |    0.236s | 26.032MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/addr_e__range_interface.7.smt2 |    0.237s | 28.188MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.32.smt2 |    0.237s | 29.924MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.41.smt2 |    0.237s | 28.52MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_ulib_definitions_u.x86_arch_inv._01.smt2 |    0.237s | 23.536MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__snp__snp_u.13.smt2 |    0.238s | 30.048MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.49.smt2 |    0.238s | 28.328MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.50.smt2 |    0.238s | 29.88MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype_test.8.smt2 |    0.239s | 29.124MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.32.smt2 |    0.240s | 25.896MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.8.smt2 |    0.240s | 26.156MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-segment__segments_page_find_and_allocate.3.smt2 |    0.241s | 32.956MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/process_manager__spec_impl.13.smt2 |    0.242s | 34.84MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.33.smt2 |    0.242s | 27.108MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.6.smt2 |    0.243s | 29.676MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype_test.1.smt2 |    0.243s | 28.92MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.98.smt2 |    0.244s | 29.24MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/splinterdb/marshalling__ResizableUniformSizedSeq_v.10.smt2 |    0.244s | 24.236MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec.1.smt2 |    0.244s | 26.228MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/addr_e__addr_interface.3.smt2 |    0.245s | 28.308MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.66.smt2 |    0.245s | 28.548MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/process_manager__spec_impl.14.smt2 |    0.246s | 35.7MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/lock__spincell_e.1.smt2 |    0.246s | 37.484MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.8.smt2 |    0.247s | 29.752MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.3.smt2 |    0.247s | 28.768MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.72.smt2 |    0.248s | 30.144MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.102.smt2 |    0.248s | 29.192MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/process_manager__spec_impl.7.smt2 |    0.249s | 31.6MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.18.smt2 |    0.249s | 30.916MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/addr_e__addr_interface.16.smt2 |    0.250s | 28.848MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__ResizableUniformSizedSeq_v.7.smt2 |    0.250s | 25.268MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.39.smt2 |    0.251s | 28.604MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.130.smt2 |    0.251s | 29.592MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/addr_e__addr_interface.10.smt2 |    0.251s | 28.896MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.21.smt2 |    0.252s | 28.404MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-init.12.smt2 |    0.252s | 29.164MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.85.smt2 |    0.253s | 30.436MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page.8.smt2 |    0.253s | 32.344MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/process_manager__spec_impl.21.smt2 |    0.254s | 34.192MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.95.smt2 |    0.255s | 30.216MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.108.smt2 |    0.255s | 30.496MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/addr_e__addr_interface.13.smt2 |    0.256s | 28.836MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.5.smt2 |    0.256s | 29.448MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec__replica.12.smt2 |    0.256s | 27.6MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.81.smt2 |    0.257s | 30.344MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.28.smt2 |    0.258s | 27.292MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-logimpl_v.33.smt2 |    0.258s | 25.768MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.45.smt2 |    0.260s | 28.476MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.97.smt2 |    0.261s | 30.424MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.9.smt2 |    0.262s | 30.264MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.64.smt2 |    0.262s | 27.256MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.165.smt2 |    0.264s | 30.112MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.155.smt2 |    0.265s | 29.936MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.99.smt2 |    0.265s | 29.18MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/process_manager__spec_impl.20.smt2 |    0.266s | 32.664MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-alloc_generic__page_free_list_extendlib_alloc_generic.page_free_list_extend._06.smt2 |    0.266s | 28.028MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.11.smt2 |    0.266s | 30.136MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/process_manager__spec_impl.3.smt2 |    0.267s | 35.332MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.5.smt2 |    0.267s | 30.372MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.44.smt2 |    0.267s | 32.432MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/addr_e__addr_interface.2.smt2 |    0.268s | 28.044MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.53.smt2 |    0.269s | 30.416MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.115.smt2 |    0.271s | 31.292MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/pagetable__pagetable_spec_impl.11.smt2 |    0.272s | 34.316MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__def.32.smt2 |    0.272s | 29.128MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.119.smt2 |    0.272s | 31.3MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.52.smt2 |    0.272s | 30.188MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec__log.14.smt2 |    0.272s | 27.324MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.140.smt2 |    0.273s | 29.832MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__def.26.smt2 |    0.273s | 29.16MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-math.7.smt2 |    0.273s | 22.912MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec_e__math__bits_e.1.smt2 |    0.275s | 32.644MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.54.smt2 |    0.275s | 29.62MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.40.smt2 |    0.277s | 30.02MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__def.34.smt2 |    0.278s | 29.324MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-os_mem_util.15.smt2 |    0.280s | 29.08MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__def.42.smt2 |    0.285s | 31.264MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.27.smt2 |    0.285s | 29.644MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.51.smt2 |    0.285s | 29.96MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.178.smt2 |    0.288s | 31.224MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__def.20.smt2 |    0.288s | 29.136MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.19.smt2 |    0.289s | 29.416MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/addr_e__range_interface.13.smt2 |    0.291s | 31.652MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__def.44.smt2 |    0.293s | 31.172MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/addr_e__range_interface.10.smt2 |    0.293s | 31.036MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-logimpl_v.18.smt2 |    0.294s | 22.388MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.209.smt2 |    0.296s | 30.596MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__math__integer.8.smt2 |    0.296s | 23.504MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.16.smt2 |    0.300s | 27.676MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-math.18.smt2 |    0.300s | 21.42MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.56.smt2 |    0.301s | 30.024MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_impl__PT.10.smt2 |    0.302s | 28.796MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/pagetable__pagetable_spec_impl.6.smt2 |    0.304s | 34.572MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__mshyper__param_e.5.smt2 |    0.305s | 31.444MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.199.smt2 |    0.308s | 30.452MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.162.smt2 |    0.308s | 31.116MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.184.smt2 |    0.308s | 31.96MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.109.smt2 |    0.309s | 32.408MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.27.smt2 |    0.314s | 33.476MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-segment.5.smt2 |    0.314s | 30.112MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/addr_e__exe.1.smt2 |    0.316s | 30.976MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security.11.smt2 |    0.319s | 34.804MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.83.smt2 |    0.321s | 28.684MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.239.smt2 |    0.322s | 30.672MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__snp__snp_u.15.smt2 |    0.323s | 32.14MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.282.smt2 |    0.325s | 31.272MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.39.smt2 |    0.326s | 33.528MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.22.smt2 |    0.327s | 28.792MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/anvil/splinterdb-smt-marshalling__UniformSizedSeq_v.6.smt2 |    0.329s | 24.24MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec_e__math__bits_e.5.smt2 |    0.330s | 32.608MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.71.smt2 |    0.330s | 27.836MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.88.smt2 |    0.331s | 29.344MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/ironkv-smt-verus_extra__seq_lib_v.5.smt2 |    0.331s | 21.924MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.121.smt2 |    0.334s | 32.58MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.17.smt2 |    0.335s | 30.616MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-alloc_fast.3.smt2 |    0.336s | 34.404MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-alloc_generic.9.smt2 |    0.337s | 34.72MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.186.smt2 |    0.338s | 31.896MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.53.smt2 |    0.340s | 29.656MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/linkedlist.11.smt2 |    0.343s | 32.68MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security.19.smt2 |    0.343s | 35.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__pgtable__entry_p.4.smt2 |    0.343s | 26.324MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.175.smt2 |    0.344s | 33.12MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.40.smt2 |    0.345s | 32.564MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__logimpl_v.7.smt2 |    0.348s | 27.392MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.307.smt2 |    0.350s | 31.528MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.69.smt2 |    0.350s | 31.26MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.55.smt2 |    0.350s | 31.808MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.51.smt2 |    0.352s | 32.04MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.46.smt2 |    0.352s | 32.068MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.297.smt2 |    0.353s | 31.292MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_e.15.smt2 |    0.355s | 33.612MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/debug__ghcb_print.28.smt2 |    0.355s | 32.94MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security.21.smt2 |    0.356s | 33.796MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.26.smt2 |    0.357s | 32.84MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.58.smt2 |    0.360s | 31.8MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.216.smt2 |    0.360s | 32.4MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.124.smt2 |    0.360s | 34.064MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.336.smt2 |    0.361s | 31.772MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-bin_sizes.47.smt2 |    0.362s | 25.704MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/debug__ghcb_print.6.smt2 |    0.364s | 32.812MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__idt__dummy.2.smt2 |    0.364s | 33.444MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.31.smt2 |    0.364s | 31.548MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/memory_manager__spec_impl.12.smt2 |    0.367s | 24.968MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.45.smt2 |    0.368s | 32.212MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_list.4.smt2 |    0.368s | 31.164MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.47.smt2 |    0.368s | 30.744MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.30.smt2 |    0.370s | 32.476MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.348.smt2 |    0.372s | 31.844MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_e.12.smt2 |    0.372s | 34.24MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.144.smt2 |    0.373s | 34.452MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.32.smt2 |    0.373s | 29.4MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.56.smt2 |    0.373s | 27.776MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.363.smt2 |    0.374s | 32.04MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.225.smt2 |    0.375s | 34.148MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.106.smt2 |    0.375s | 32.632MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__vram__vram_p.26.smt2 |    0.375s | 33.868MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.172.smt2 |    0.377s | 33.216MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_list.21.smt2 |    0.377s | 33.192MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security.12.smt2 |    0.378s | 37.132MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.220.smt2 |    0.382s | 34.192MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.49.smt2 |    0.382s | 32.14MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__logimpl_v.10.smt2 |    0.383s | 29.028MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.338.smt2 |    0.384s | 31.676MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.149.smt2 |    0.385s | 34.424MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1.41.smt2 |    0.386s | 27.08MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.256.smt2 |    0.387s | 33.932MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__multilogimpl_v.12.smt2 |    0.387s | 30.852MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.391.smt2 |    0.391s | 32.3MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_e.13.smt2 |    0.391s | 34.352MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.366.smt2 |    0.393s | 32.012MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.393.smt2 |    0.394s | 32.428MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.388.smt2 |    0.396s | 32.128MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.403.smt2 |    0.397s | 32.412MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.152.smt2 |    0.398s | 33.084MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.371.smt2 |    0.398s | 32.896MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.213.smt2 |    0.400s | 35.372MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.73.smt2 |    0.401s | 32.604MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.408.smt2 |    0.402s | 32.508MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.30.smt2 |    0.402s | 32.508MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.413.smt2 |    0.403s | 32.416MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.198.smt2 |    0.405s | 34.972MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.418.smt2 |    0.406s | 32.652MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.370.smt2 |    0.406s | 32.896MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.77.smt2 |    0.406s | 32.376MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.398.smt2 |    0.406s | 32.436MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.202.smt2 |    0.406s | 33.788MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.151.smt2 |    0.407s | 33.76MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/allocator__buddy.6.smt2 |    0.407s | 34.228MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__pte.2.smt2 |    0.408s | 35.54MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec_e__math__bits_e.3.smt2 |    0.408s | 31.6MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_e.20.smt2 |    0.408s | 34.536MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.68.smt2 |    0.408s | 29.24MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__mshyper__param_e.1.smt2 |    0.410s | 34.924MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.122.smt2 |    0.412s | 32.688MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.20.smt2 |    0.413s | 32.352MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-os_mem_util.2.smt2 |    0.413s | 27.272MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.231.smt2 |    0.414s | 33.78MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.57.smt2 |    0.414s | 29.556MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.226.smt2 |    0.414s | 33.824MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec_e__math__bits_e.8.smt2 |    0.416s | 30.84MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.235.smt2 |    0.416s | 34.756MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.38.smt2 |    0.416s | 32.832MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.86.smt2 |    0.416s | 32.684MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-spec__cyclicbuffer__CyclicBuffer.23.smt2 |    0.416s | 27.148MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-os_commit.2.smt2 |    0.416s | 25.092MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.206.smt2 |    0.418s | 33.86MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-spec__cyclicbuffer__CyclicBuffer.6.smt2 |    0.418s | 27.216MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.381.smt2 |    0.420s | 33.944MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.380.smt2 |    0.421s | 32.944MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__pte.3.smt2 |    0.422s | 36.06MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.19.smt2 |    0.422s | 27.72MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-spec__cyclicbuffer__CyclicBuffer.10.smt2 |    0.423s | 27.2MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.233.smt2 |    0.424s | 35.12MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.221.smt2 |    0.424s | 33.716MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layout.21.smt2 |    0.425s | 24.1MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.423.smt2 |    0.426s | 32.504MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__vram__vram_p.18.smt2 |    0.427s | 35.104MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.193.smt2 |    0.430s | 34.78MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.196.smt2 |    0.431s | 33.712MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.208.smt2 |    0.433s | 35.424MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.240.smt2 |    0.434s | 34.496MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.261.smt2 |    0.435s | 34.312MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.324.smt2 |    0.435s | 34.492MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.283.smt2 |    0.436s | 35.084MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security.18.smt2 |    0.436s | 36.864MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.91.smt2 |    0.436s | 32.708MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.78.smt2 |    0.437s | 29.588MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.265.smt2 |    0.438s | 34.684MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.309.smt2 |    0.440s | 34.54MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/addr_e__range_interface.15.smt2 |    0.444s | 32.356MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/pagetable__pagetable_spec_impl.7.smt2 |    0.445s | 36.38MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.328.smt2 |    0.445s | 34.684MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__os_refinement.1.smt2 |    0.445s | 30.488MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.306.smt2 |    0.447s | 35.856MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.325.smt2 |    0.449s | 34.524MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.350.smt2 |    0.451s | 33.684MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/allocator__linkedlist.3.smt2 |    0.452s | 33.168MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.148.smt2 |    0.454s | 33.256MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.176.smt2 |    0.456s | 33.296MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.281.smt2 |    0.457s | 35.812MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-spec__cyclicbuffer__CyclicBuffer.1.smt2 |    0.457s | 26.74MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-os_mem_util.9.smt2 |    0.457s | 32.792MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__snp__snp_u.16.smt2 |    0.460s | 34.436MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-segment__segment_span_allocate.1.smt2 |    0.460s | 33.464MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.168.smt2 |    0.461s | 33.636MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.364.smt2 |    0.461s | 35.516MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__ptram__ptram_p.6.smt2 |    0.463s | 32.7MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-pagelib_page.page_init._01.smt2 |    0.463s | 29.904MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1.53.smt2 |    0.463s | 27.412MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.308.smt2 |    0.465s | 34.904MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.27.smt2 |    0.465s | 30.552MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.274.smt2 |    0.471s | 34.36MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__vram__vram_p.22.smt2 |    0.475s | 33.304MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/debug__slice_print.3.smt2 |    0.476s | 47.872MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__snp__snp_s.smt2 |    0.481s | 36.856MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.237.smt2 |    0.482s | 34.096MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.222.smt2 |    0.486s | 33.92MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.341.smt2 |    0.488s | 35.152MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec__replica.13.smt2 |    0.489s | 30.36MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-os_mem_util.16.smt2 |    0.489s | 29.424MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/debug__ghcb_print.2.smt2 |    0.490s | 38.508MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_list.3.smt2 |    0.492s | 31.76MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.342.smt2 |    0.493s | 36.244MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.4.smt2 |    0.498s | 28.924MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.56.smt2 |    0.499s | 33.796MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.395.smt2 |    0.499s | 35.492MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.201.smt2 |    0.505s | 33.604MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-os_mem_util.19.smt2 |    0.506s | 30.052MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.51.smt2 |    0.506s | 31.372MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.63.smt2 |    0.507s | 30.796MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.362.smt2 |    0.508s | 36.424MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__vram__vram_p.21.smt2 |    0.512s | 34.112MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.7.smt2 |    0.512s | 29.1MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.321.smt2 |    0.516s | 34.58MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__params.23.smt2 |    0.517s | 39.06MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpuid.14.smt2 |    0.523s | 40.24MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.414.smt2 |    0.526s | 36.064MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.390.smt2 |    0.526s | 35.56MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype_test.5.smt2 |    0.526s | 30.66MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.389.smt2 |    0.529s | 35.632MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.5.smt2 |    0.529s | 29.34MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.37.smt2 |    0.536s | 35.048MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/allocator__linkedlist.11.smt2 |    0.538s | 41.324MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.372.smt2 |    0.539s | 35.42MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.417.smt2 |    0.541s | 36.972MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.329.smt2 |    0.541s | 36.068MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/debug__ghcb_print.10.smt2 |    0.543s | 39.128MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec__log.10.smt2 |    0.543s | 29.8MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.412.smt2 |    0.544s | 36.956MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.286.smt2 |    0.549s | 35.772MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.368.smt2 |    0.553s | 35.36MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__ptram__ptram_p.10.smt2 |    0.557s | 35.172MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.392.smt2 |    0.559s | 35.928MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.67.smt2 |    0.560s | 30.392MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__pte.29.smt2 |    0.563s | 39.98MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.346.smt2 |    0.566s | 35.2MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.394.smt2 |    0.568s | 35.888MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpuid.16.smt2 |    0.569s | 41.864MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-os_mem_util.10.smt2 |    0.569s | 39.22MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.415.smt2 |    0.573s | 35.756MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__secret.1.smt2 |    0.573s | 50.82MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__params.14.smt2 |    0.583s | 44.72MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__logimpl_v.3.smt2 |    0.583s | 27.392MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_list.16.smt2 |    0.589s | 29.608MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__pte.8.smt2 |    0.590s | 41.26MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.183.smt2 |    0.590s | 33.312MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.25.smt2 |    0.590s | 29.984MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.28.smt2 |    0.599s | 56.38MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/linkedlist.16.smt2 |    0.603s | 39.596MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.8.smt2 |    0.604s | 29.852MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.7.smt2 |    0.604s | 29.876MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__multilogimpl_v.9.smt2 |    0.605s | 32.7MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-exec__replica.11.smt2 |    0.610s | 29.772MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__pte.26.smt2 |    0.613s | 40.36MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec_e__math__align_e.1.smt2 |    0.613s | 32.096MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__linux.34.smt2 |    0.619s | 50.964MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__idt__dummy.3.smt2 |    0.620s | 41.8MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__pte.7.smt2 |    0.629s | 41.388MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__pte.9.smt2 |    0.630s | 41.432MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_e.2.smt2 |    0.639s | 40.012MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/noderep-smt-spec__cyclicbuffer__CyclicBuffer.17.smt2 |    0.639s | 29.8MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__pcr.8.smt2 |    0.642s | 50.68MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.5.smt2 |    0.642s | 30.268MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.121.smt2 |    0.646s | 51.476MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__mem.49.smt2 |    0.646s | 50.844MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_impl__PT.15.smt2 |    0.646s | 33.14MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__idt__dummy.5.smt2 |    0.651s | 42.776MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/mshyper__wakeup.1.smt2 |    0.651s | 50.568MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_list.14.smt2 |    0.653s | 30.92MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/mshyper__hypercall.2.smt2 |    0.655s | 50.656MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.1.smt2 |    0.656s | 29.992MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__linux.40.smt2 |    0.657s | 50.944MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_impl.17.smt2 |    0.658s | 55.504MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__secret.17.smt2 |    0.658s | 50.144MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.34.smt2 |    0.662s | 51.228MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.44.smt2 |    0.662s | 51.436MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__mem.25.smt2 |    0.663s | 50.784MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__params.12.smt2 |    0.663s | 49.336MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.58.smt2 |    0.665s | 56.24MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__linux.36.smt2 |    0.667s | 50.728MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__raw_ptr_s.1.smt2 |    0.667s | 43.936MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.64.smt2 |    0.671s | 56.204MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__security__sectype.138.smt2 |    0.674s | 33.448MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__monitor_params.smt2 |    0.675s | 38.816MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/memory_manager__spec_impl.5.smt2 |    0.676s | 29.368MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/debug__ghcb_print.7.smt2 |    0.678s | 39.26MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__vram__vram_p.7.smt2 |    0.679s | 34.3MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_list.22.smt2 |    0.686s | 35.9MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__linux.35.smt2 |    0.687s | 56.016MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__pcr.2.smt2 |    0.690s | 58.488MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_refinement.5.smt2 |    0.699s | 32.84MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__vram__vram_p.1.smt2 |    0.707s | 36.82MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/addr_e__range_interface.14.smt2 |    0.709s | 35.592MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__linux.1.smt2 |    0.709s | 58.736MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__init__mshv_fmt.1.smt2 |    0.711s | 46.496MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.13.smt2 |    0.713s | 58.316MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.6.smt2 |    0.723s | 32.404MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/kernel__create_and_map_pages.1.smt2 |    0.724s | 37.024MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/splinterdb/marshalling__KVPairFormat_v.3.smt2 |    0.727s | 26.864MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__linux.37.smt2 |    0.731s | 55.612MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-bin_sizes.45.smt2 |    0.735s | 29.136MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__linux.11.smt2 |    0.738s | 59.32MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__vram__vram_p.15.smt2 |    0.738s | 37.512MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__inv_v.9.smt2 |    0.738s | 31.184MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.5.smt2 |    0.744s | 58.672MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.7.smt2 |    0.744s | 58.624MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.39.smt2 |    0.745s | 30.956MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__init__init_e.2.smt2 |    0.751s | 61.1MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__layout_v.30.smt2 |    0.757s | 29.672MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.16.smt2 |    0.759s | 34.652MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_impl.27.smt2 |    0.762s | 57.148MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_impl.11.smt2 |    0.763s | 59.648MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.48.smt2 |    0.768s | 30.844MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__linux.20.smt2 |    0.769s | 59.56MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-bin_sizes.33.smt2 |    0.773s | 28.98MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__linux.8.smt2 |    0.776s | 63.192MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.11.smt2 |    0.778s | 59.516MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.5.smt2 |    0.785s | 58.112MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page.16.smt2 |    0.789s | 35.788MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__mem.28.smt2 |    0.793s | 60.364MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__linux.43.smt2 |    0.810s | 61.188MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.117.smt2 |    0.814s | 57.072MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.14.smt2 |    0.814s | 61.62MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.138.smt2 |    0.819s | 56.38MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__inv_v.3.smt2 |    0.819s | 31.984MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.10.smt2 |    0.820s | 62.26MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.29.smt2 |    0.822s | 31.44MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.19.smt2 |    0.824s | 64.336MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.4.smt2 |    0.829s | 62.64MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/debug__ghcb_print.23.smt2 |    0.836s | 66.64MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.37.smt2 |    0.838s | 59.78MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/kernel__mem_util.2.smt2 |    0.839s | 37.316MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/linkedlist.14.smt2 |    0.843s | 37.328MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__params.16.smt2 |    0.845s | 65.14MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__init__mshv_alloc.3.smt2 |    0.846s | 63.86MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_impl.4.smt2 |    0.850s | 63.128MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.93.smt2 |    0.857s | 58.164MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.94.smt2 |    0.857s | 34.224MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__pte.11.smt2 |    0.859s | 42.544MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__mem__mem_p.11.smt2 |    0.861s | 36.692MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__inv_v.2.smt2 |    0.863s | 32.844MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.12.smt2 |    0.868s | 61.756MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.79.smt2 |    0.870s | 31.956MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.27.smt2 |    0.871s | 64.448MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.71.smt2 |    0.877s | 63.788MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/debug__ghcb_print.25.smt2 |    0.877s | 66.728MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__mem__mem_p.16.smt2 |    0.879s | 38.776MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__linux.44.smt2 |    0.880s | 64.096MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.16.smt2 |    0.881s | 65.288MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.89.smt2 |    0.882s | 63.228MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.126.smt2 |    0.888s | 70.076MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.26.smt2 |    0.890s | 65.316MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.2.smt2 |    0.891s | 65.352MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.10.smt2 |    0.896s | 65.46MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__secret.6.smt2 |    0.896s | 64.632MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__pte.16.smt2 |    0.905s | 42.756MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/debug__ghcb_print.26.smt2 |    0.907s | 67.012MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.8.smt2 |    0.908s | 65.328MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.70.smt2 |    0.912s | 65.084MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__trackedcore__snpmulticore.1.smt2 |    0.913s | 68.02MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.30.smt2 |    0.913s | 65.26MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__vram__vram_p.28.smt2 |    0.914s | 36.844MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.14.smt2 |    0.914s | 65.464MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.4.smt2 |    0.914s | 65.476MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__mem.10.smt2 |    0.918s | 67.42MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.31.smt2 |    0.921s | 60.144MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.38.smt2 |    0.921s | 69.9MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-queues.3.smt2 |    0.921s | 33.5MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.18.smt2 |    0.926s | 65.468MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_impl.7.smt2 |    0.928s | 62.348MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.102.smt2 |    0.929s | 65.112MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.73.smt2 |    0.931s | 65.64MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__secret.24.smt2 |    0.933s | 63.384MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__secret.9.smt2 |    0.934s | 64.068MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.31.smt2 |    0.938s | 64.192MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.110.smt2 |    0.947s | 65.704MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_impl.6.smt2 |    0.947s | 63.524MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.69.smt2 |    0.949s | 65.132MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-commit_segment.6.smt2 |    0.951s | 37.088MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__mem.42.smt2 |    0.952s | 64.308MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.107.smt2 |    0.954s | 65.696MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-types.45.smt2 |    0.954s | 36.444MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.127.smt2 |    0.955s | 69.656MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__linux.30.smt2 |    0.955s | 61.708MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.20.smt2 |    0.961s | 38.488MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.63.smt2 |    0.963s | 70.284MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.103.smt2 |    0.965s | 64.944MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_impl.25.smt2 |    0.966s | 63.772MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.25.smt2 |    0.968s | 65.376MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__mem.50.smt2 |    0.980s | 65.04MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.6.smt2 |    0.986s | 66.076MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/allocator__linkedlist.13.smt2 |    0.987s | 48.508MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.104.smt2 |    1.006s | 64.048MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.88.smt2 |    1.010s | 64.64MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_impl.21.smt2 |    1.015s | 65.176MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__vram__vram_p.2.smt2 |    1.016s | 38.508MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.94.smt2 |    1.029s | 65.028MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__linux.22.smt2 |    1.033s | 61.956MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_impl.28.smt2 |    1.039s | 60.32MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.35.smt2 |    1.051s | 34.488MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/kernel__create_and_share_pages.4.smt2 |    1.070s | 69.644MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.81.smt2 |    1.087s | 65.972MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.85.smt2 |    1.088s | 66.184MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_impl.13.smt2 |    1.088s | 63.772MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.26.smt2 |    1.089s | 38.896MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.91.smt2 |    1.100s | 64.912MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.42.smt2 |    1.111s | 31.144MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__mem.20.smt2 |    1.116s | 66.312MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/kernel__create_and_map_pages.6.smt2 |    1.125s | 49.2MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.68.smt2 |    1.131s | 65.748MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-tokens__Mim.39.smt2 |    1.131s | 39.204MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__ptr_e.9.smt2 |    1.133s | 39.92MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/kernel__schedule_idle_cpu.smt2 |    1.137s | 45.376MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.83.smt2 |    1.140s | 66.092MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.48.smt2 |    1.145s | 65.224MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__secret.22.smt2 |    1.154s | 61.612MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_impl.10.smt2 |    1.154s | 29.004MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-linked_list.13.smt2 |    1.158s | 38.148MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__inv_v.12.smt2 |    1.175s | 32.356MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__raw_ptr_s.3.smt2 |    1.188s | 44.016MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__secret.18.smt2 |    1.232s | 66.612MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_e.19.smt2 |    1.251s | 67.168MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.96.smt2 |    1.254s | 64.124MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.9.smt2 |    1.262s | 68.264MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.98.smt2 |    1.268s | 64.088MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-init.13.smt2 |    1.271s | 39.632MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/pagetable__pagetable_spec_impl.5.smt2 |    1.294s | 36.816MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__def.36.smt2 |    1.295s | 38.196MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.112.smt2 |    1.296s | 66.64MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__inv_v.17.smt2 |    1.299s | 34.372MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.67.smt2 |    1.309s | 69.408MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.41.smt2 |    1.313s | 74.132MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.45.smt2 |    1.314s | 38.892MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/tspec__math__align_s.5.smt2 |    1.324s | 32.4MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__def.39.smt2 |    1.349s | 37.808MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.18.smt2 |    1.359s | 60.368MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1__impl_%1__lemma_resolve_refines.smt2 |    1.365s | 35.776MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.38.smt2 |    1.435s | 63.548MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/mshyper__wakeup.5.smt2 |    1.467s | 149.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__mem.45.smt2 |    1.478s | 65.656MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_impl.22.smt2 |    1.479s | 68.152MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-alloc_generic.5.smt2 |    1.490s | 44.388MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.50.smt2 |    1.504s | 65.392MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.17.smt2 |    1.530s | 67.84MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.49.smt2 |    1.534s | 63.644MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_impl.20.smt2 |    1.547s | 66.276MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__mem.27.smt2 |    1.552s | 66.78MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-free.6.smt2 |    1.572s | 63.924MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.40.smt2 |    1.588s | 31.128MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.32.smt2 |    1.601s | 75.176MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.66.smt2 |    1.606s | 81.328MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__def.16.smt2 |    1.615s | 37.444MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__pte.25.smt2 |    1.621s | 43.032MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-free.3.smt2 |    1.627s | 44.796MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_impl.26.smt2 |    1.632s | 66.332MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/process_manager__spec_impl.26.smt2 |    1.668s | 65.656MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.32.smt2 |    1.681s | 63.808MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/kernel__syscall_receive_empty.2.smt2 |    1.741s | 66.744MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_impl.10.smt2 |    1.741s | 73.028MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__def.31.smt2 |    1.750s | 37.764MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/process_manager__spec_impl.33.smt2 |    1.760s | 69.084MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.44.smt2 |    1.803s | 63.616MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__linux.13.smt2 |    1.816s | 85.108MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/allocator__buddy.4.smt2 |    1.879s | 72.84MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1__impl_%1__lemma_interp_of_entry_contains_mapping_implies_interp_aux_contains_mapping.smt2 |    1.947s | 39.4MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/addr_e__range_interface.17.smt2 |    1.963s | 45.028MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__mem__mem_p.13.smt2 |    1.978s | 42.8MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/lock__spincell_e.5.smt2 |    2.031s | 72.14MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.65.smt2 |    2.049s | 38.5MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__def_s.smt2 |    2.151s | 94.48MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__inv_v.18.smt2 |    2.197s | 37.028MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__logimpl_v.9.smt2 |    2.198s | 39.16MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layoutlib_layout.align_up._02.smt2 |    2.259s | 26.036MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__gdt.19.smt2 |    2.334s | 31.54MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__x64__x64_p.2.smt2 |    2.374s | 46.828MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-commit_segment.1.smt2 |    2.435s | 32.624MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__logimpl_v.4.smt2 |    2.437s | 40.68MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.134.smt2 |    2.546s | 79.232MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-root.smt2 |    2.566s | 69.588MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__start_v.2.smt2 |    2.595s | 36.532MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-page_organization__PageOrg.60.smt2 |    2.601s | 37.908MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__mem__mem_p.4.smt2 |    2.621s | 44.152MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__inv_v.15.smt2 |    2.874s | 39.988MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/vbox__vbox.6.smt2 |    2.908s | 140.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__inv_v.15.smt2 |    2.998s | 39.272MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/debug__ghcb_print.12.smt2 |    3.120s | 76.744MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/kernel__create_and_share_pages.3.smt2 |    3.130s | 68.764MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/linkedlist.7.smt2 |    3.485s | 81.344MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__linux.17.smt2 |    3.500s | 74.212MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/debug__ghcb_print.5.smt2 |    3.557s | 77.392MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/vbox__vbox.2.smt2 |    3.599s | 128.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-commit_mask.11.smt2 |    3.825s | 31.156MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/allocator__locked.1.smt2 |    4.182s | 101.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/lock__spin_perm_s.3.smt2 |    4.382s | 86.948MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/allocator__buddy.7.smt2 |    4.528s | 79.296MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layout__block_ptr_aligned_to_word.smt2 |    4.529s | 25.548MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__snp__rmp__rmp_e.7.smt2 |    4.589s | 76.424MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__init__init_s.smt2 |    4.781s | 144.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_e.18.smt2 |    4.923s | 74.832MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_impl.15.smt2 |    4.972s | 167.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/kernel__syscall_send_endpoint.smt2 |    5.113s | 121.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.20.smt2 |    5.149s | 45.74MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_impl__internal.2.smt2 |    5.152s | 130.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__mem.37.smt2 |    6.275s | 139.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.10.smt2 |    6.908s | 48.196MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-logimpl_v.37.smt2 |    7.030s | 55.22MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1.34.smt2 |    7.655s | 43.304MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/allocator__buddy.9.smt2 |    7.671s | 74.356MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/allocator__linkedlist.6.smt2 |    8.042s | 98.568MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__pte.23.smt2 |    8.461s | 145.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__mem.38.smt2 |    8.540s | 267.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.23.smt2 |    8.978s | 69.344MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__ghcb__proto_page.140.smt2 |    9.014s | 181.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/linkedlist.9.smt2 |    9.654s | 75.46MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/allocator__page_allocator_spec_impl.15.smt2 |   10.321s | 69.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/mshyper.19.smt2 |   10.335s | 264.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1.47.smt2 |   10.341s | 65.156MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/kernel__syscall_send_pages.smt2 |   10.835s | 122.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-logimpl_v.50.smt2 |   11.013s | 50.348MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/allocator__linkedlist.10.smt2 |   11.054s | 72.172MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.1.smt2 |   11.491s | 195.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/vbox__vbox.7.smt2 |   11.498s | 129.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/pgtable_e__pte.22.smt2 |   11.866s | 266.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/vbox__vbox.3.smt2 |   12.093s | 185.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-segment__segment_page_clear.smt2 |   12.808s | 112.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/debug__ghcb_print.8.smt2 |   12.892s | 61.644MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-layout__align_downlib_layout.align_down._03.smt2 |   13.167s | 23.4MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/linkedlist.13.smt2 |   13.240s | 86.532MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__snp__rmp__rmp_e.3.smt2 |   14.150s | 134.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-segment__segment_span_free_coalesce_before.smt2 |   14.586s | 86.724MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_impl__PT.28.smt2 |   14.893s | 70.28MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/mshyper__wakeup.7.smt2 |   15.362s | 262.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__os_refinement.10.smt2 |   16.752s | 93.672MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__pcr.5.smt2 |   17.614s | 266.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/linkedlist.4.smt2 |   18.200s | 141.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-queues__page_queue_push.smt2 |   18.263s | 117.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/allocator__buddy.11.smt2 |   20.008s | 50.32MiB| timeout | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-definitions_ulib_definitions_u.impl_%3.lemma_entry_sizes_aligned._02.smt2 |   20.008s | 27.38MiB| timeout | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l1__impl_%1__lemma_no_mapping_in_interp_of_entry_implies_no_mapping_in_interp.smt2 |   20.010s | 69.588MiB| timeout | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-queues__page_queue_push_back.smt2 |   20.011s | 116.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/arch__vram__vram_p.9.smt2 |   20.014s | 80.556MiB| timeout | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/linkedlist.12.smt2 |   20.014s | 135.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/allocator__buddy.13.smt2 |   20.014s | 146.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.14.smt2 |   20.015s | 179.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.15.smt2 |   20.015s | 186.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.12.smt2 |   20.016s | 167.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.10.smt2 |   20.017s | 173.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/boot__idt__def.4.smt2 |   20.023s | 308.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-segment__segment_slice_split.smt2 |   20.024s | 94.664MiB| timeout | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/linkedlist.6.smt2 |   20.026s | 138.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__multilogimpl_v.5.smt2 |   20.026s | 81.176MiB| timeout | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/kernel__syscall_new_proc.smt2 |   20.027s | 121.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/atmosphere/pagetable__pagetable_spec_impl.1.smt2 |   20.027s | 336.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/allocator__buddy.15.smt2 |   20.027s | 91.584MiB| timeout | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_impl__PT.18.smt2 |   20.027s | 96.972MiB| timeout | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__append_v.2.smt2 |   20.029s | 79.788MiB| timeout | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.16.smt2 |   20.030s | 167.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_refinement.3.smt2 |   20.030s | 90.876MiB| timeout | 0 |  |  |
|non-incremental/UFDTNIA/20230314-Jaroslav-Bendik-Certora/52759_b3ecd2335fd16ec2eee2_9_UFDTNIA.smt2 |   20.030s | 41.204MiB| timeout | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/page-table-smt-impl_u__l2_refinement.4.smt2 |   20.031s | 119.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__monitor.24.smt2 |   20.035s | 152.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/ptr__snp__rmp__rmp_e.5.smt2 |   20.036s | 241.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/snp__cpu__vmsa.2.smt2 |   20.039s | 518.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/verismo/security__secret.13.smt2 |   20.041s | 269.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/mimalloc-smt-commit_mask.31.smt2 |   20.046s | 567.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTNIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-multilog__setup_v.6.smt2 |   20.053s | 590.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTNIA/2019-Gleiss/non-interference/10-ni-rsa-exponentiation.spec.smt2 |   20.190s | 2288.0MiB| timeout | 0 |  |  |
