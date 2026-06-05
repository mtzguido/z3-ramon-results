# .

* SAT 109
* UNSAT 378
* TIMEOUT 1182
* UNKNOWN 14

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/AUFBVDTLIA.tar.zst?download=1 | Source list: quantifier_benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-AUFBVDTLIA.tar.zst
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: c3f5365a95a7eac2419a2f95ff240909f275cc08
Z3 branch: c3f5365a95a7eac2419a2f95ff240909f275cc08
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/AUFBVDTLIA.tar.zst?download=1
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
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BitsTricks.scala-9.smt2 |    0.014s | 19.06MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BitsTricks.scala-1.smt2 |    0.016s | 19.544MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SortedNDList.scala-3.smt2-2.smt2 |    0.017s | 18.9MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BitsTricks.scala-3.smt2 |    0.017s | 19.876MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-MergeSort.scala-7.smt2 |    0.017s | 19.168MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-49.smt2 |    0.017s | 19.652MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BitsTricks.scala-2.smt2 |    0.017s | 19.536MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-1.smt2-1.smt2 |    0.017s | 19.84MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-1.smt2-3.smt2 |    0.017s | 19.536MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-2.smt2-3.smt2 |    0.017s | 19.584MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-3.smt2 |    0.018s | 19.76MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-8.smt2 |    0.018s | 19.708MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-MergeSort.scala-7.smt2 |    0.018s | 19.044MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-12.smt2 |    0.018s | 19.6MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-46.smt2 |    0.018s | 19.588MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-7.smt2 |    0.018s | 19.624MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BinaryTrie.scala-1.smt2-1.smt2 |    0.018s | 20.072MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-2.smt2-1.smt2 |    0.018s | 19.756MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-11.smt2-1.smt2 |    0.018s | 19.576MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-25.smt2 |    0.018s | 19.556MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-58.smt2 |    0.018s | 19.672MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-47.smt2 |    0.018s | 19.648MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-15.smt2 |    0.018s | 19.844MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Sync.scala-1.smt2 |    0.018s | 19.788MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SumAndMax.scala-7.smt2-1.smt2 |    0.018s | 20.0MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-31.smt2-1.smt2 |    0.018s | 19.824MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-66.smt2-2.smt2 |    0.018s | 19.74MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-76.smt2-1.smt2 |    0.018s | 19.644MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-18.smt2-3.smt2 |    0.018s | 19.756MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-58.smt2 |    0.019s | 19.544MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-94.smt2 |    0.019s | 19.888MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-93.smt2-3.smt2 |    0.019s | 19.776MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-94.smt2-1.smt2 |    0.019s | 19.712MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-4.smt2-1.smt2 |    0.019s | 20.244MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-7.smt2-3.smt2 |    0.019s | 20.0MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-69.smt2-1.smt2 |    0.019s | 19.748MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-10.smt2 |    0.019s | 19.736MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-21.smt2 |    0.019s | 19.636MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-14.smt2 |    0.019s | 19.796MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-28.smt2 |    0.019s | 19.54MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Naturals.scala-11.smt2 |    0.019s | 19.604MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-29.smt2 |    0.019s | 19.8MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-46.smt2 |    0.019s | 20.308MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-19.smt2 |    0.019s | 19.612MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-11.smt2 |    0.019s | 19.708MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-50.smt2-2.smt2 |    0.019s | 20.216MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-13.smt2-1.smt2 |    0.019s | 20.052MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-19.smt2-3.smt2 |    0.019s | 19.792MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-32.smt2-2.smt2 |    0.019s | 20.336MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-24.smt2-2.smt2 |    0.019s | 19.748MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-27.smt2 |    0.020s | 19.82MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-5.smt2 |    0.020s | 19.876MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-11.smt2 |    0.020s | 19.644MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SortedNDList.scala-2.smt2 |    0.020s | 20.192MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-76.smt2 |    0.020s | 19.776MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-4.smt2 |    0.020s | 19.832MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-3.smt2 |    0.020s | 19.656MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-16.smt2-2.smt2 |    0.020s | 19.956MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-50.smt2-2.smt2 |    0.020s | 19.66MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-8.smt2-2.smt2 |    0.020s | 20.312MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-15.smt2-2.smt2 |    0.020s | 19.968MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-61.smt2-2.smt2 |    0.020s | 19.752MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-29.smt2-2.smt2 |    0.020s | 19.848MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-8.smt2-1.smt2 |    0.020s | 20.172MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Parser.scala-1.smt2-1.smt2 |    0.020s | 20.048MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-6.smt2-2.smt2 |    0.020s | 19.812MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-73.smt2 |    0.020s | 19.72MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-71.smt2 |    0.020s | 20.18MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-23.smt2 |    0.020s | 19.84MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-15.smt2 |    0.020s | 19.592MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-12.smt2 |    0.020s | 20.08MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Naturals.scala-3.smt2 |    0.020s | 19.532MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-QuickSort.scala-24.smt2 |    0.020s | 19.94MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SecondsToTime.scala-3.smt2-3.smt2 |    0.020s | 19.652MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-94.smt2-1.smt2 |    0.020s | 19.544MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-24.smt2-1.smt2 |    0.020s | 19.812MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-10.smt2-2.smt2 |    0.020s | 19.8MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-28.smt2-3.smt2 |    0.020s | 20.852MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-77.smt2 |    0.021s | 19.708MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-25.smt2 |    0.021s | 20.084MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-21.smt2 |    0.021s | 20.02MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SumAndMax.scala-7.smt2 |    0.021s | 19.888MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-25.smt2 |    0.021s | 19.776MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-6.smt2 |    0.021s | 19.804MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-5.smt2 |    0.021s | 19.808MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-73.smt2 |    0.021s | 19.836MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-49.smt2 |    0.021s | 19.764MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-29.smt2 |    0.021s | 19.856MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-18.smt2 |    0.021s | 20.052MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-18.smt2-2.smt2 |    0.021s | 20.472MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SecondsToTime.scala-3.smt2-3.smt2 |    0.021s | 19.828MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-19.smt2-1.smt2 |    0.021s | 20.028MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SecondsToTime.scala-1.smt2-3.smt2 |    0.021s | 19.78MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-39.smt2-2.smt2 |    0.021s | 19.836MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-11.smt2-2.smt2 |    0.021s | 19.696MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-49.smt2-1.smt2 |    0.021s | 19.68MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-7.smt2-1.smt2 |    0.021s | 19.96MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-30.smt2-1.smt2 |    0.021s | 19.892MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SortedNDList.scala-2.smt2-1.smt2 |    0.021s | 19.896MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-28.smt2-3.smt2 |    0.021s | 19.836MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-20.smt2-1.smt2 |    0.021s | 20.012MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-76.smt2-1.smt2 |    0.021s | 19.82MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-5.smt2-2.smt2 |    0.021s | 19.96MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Fibonacci.scala-3.smt2 |    0.021s | 19.796MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-26.smt2 |    0.021s | 19.732MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-12.smt2 |    0.021s | 19.82MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-QuickSort.scala-21.smt2 |    0.021s | 20.196MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Sync.scala-1.smt2-1.smt2 |    0.021s | 20.572MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-11.smt2-1.smt2 |    0.021s | 20.552MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-8.smt2-3.smt2 |    0.021s | 20.456MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-21.smt2-3.smt2 |    0.021s | 20.08MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SecondsToTime.scala-1.smt2-3.smt2 |    0.021s | 19.824MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-18.smt2-1.smt2 |    0.021s | 20.316MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-46.smt2-1.smt2 |    0.021s | 20.556MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-7.smt2-3.smt2 |    0.021s | 19.928MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-16.smt2 |    0.022s | 19.888MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-20.smt2 |    0.022s | 20.12MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-70.smt2 |    0.022s | 19.8MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-22.smt2 |    0.022s | 20.26MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-22.smt2 |    0.022s | 19.916MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-20.smt2 |    0.022s | 19.928MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-14.smt2-2.smt2 |    0.022s | 20.392MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SortedNDList.scala-2.smt2-2.smt2 |    0.022s | 19.944MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SecondsToTime.scala-1.smt2-1.smt2 |    0.022s | 20.308MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-27.smt2-2.smt2 |    0.022s | 19.668MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-25.smt2-1.smt2 |    0.022s | 20.348MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-16.smt2-3.smt2 |    0.022s | 19.9MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-1.smt2-1.smt2 |    0.022s | 20.108MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-20.smt2-2.smt2 |    0.022s | 20.056MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-31.smt2-1.smt2 |    0.022s | 20.224MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Sync.scala-1.smt2-3.smt2 |    0.022s | 20.824MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-50.smt2 |    0.022s | 20.308MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-18.smt2 |    0.022s | 19.628MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-7.smt2 |    0.022s | 19.892MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-8.smt2-2.smt2 |    0.022s | 20.656MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-30.smt2-3.smt2 |    0.022s | 20.608MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-19.smt2-2.smt2 |    0.022s | 19.64MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-5.smt2-2.smt2 |    0.022s | 19.74MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-18.smt2 |    0.023s | 19.9MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-12.smt2 |    0.023s | 19.884MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-15.smt2 |    0.023s | 20.188MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Sync.scala-1.smt2-1.smt2 |    0.023s | 20.632MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-20.smt2-2.smt2 |    0.023s | 19.908MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LeftistHeap.scala-1.smt2-1.smt2 |    0.023s | 20.008MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-25.smt2-2.smt2 |    0.023s | 19.832MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-27.smt2-1.smt2 |    0.023s | 20.372MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-19.smt2-2.smt2 |    0.023s | 19.828MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SecondsToTime.scala-8.smt2-1.smt2 |    0.023s | 20.656MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-17.smt2-3.smt2 |    0.023s | 19.816MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-24.smt2-1.smt2 |    0.023s | 20.008MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-28.smt2-2.smt2 |    0.023s | 19.788MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-15.smt2-1.smt2 |    0.023s | 20.024MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-19.smt2 |    0.023s | 19.812MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-7.smt2 |    0.023s | 20.188MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-24.smt2-3.smt2 |    0.023s | 20.052MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-22.smt2-2.smt2 |    0.023s | 20.428MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-16.smt2-2.smt2 |    0.023s | 20.476MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-7.smt2-1.smt2 |    0.023s | 19.684MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-12.smt2-1.smt2 |    0.023s | 19.804MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-3.smt2-2.smt2 |    0.023s | 19.524MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-17.smt2 |    0.024s | 19.856MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-31.smt2 |    0.024s | 20.524MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-22.smt2 |    0.024s | 20.096MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-19.smt2 |    0.024s | 20.6MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-27.smt2-1.smt2 |    0.024s | 19.796MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-18.smt2-1.smt2 |    0.024s | 20.224MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-23.smt2-1.smt2 |    0.024s | 20.308MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-28.smt2-1.smt2 |    0.024s | 20.036MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-29.smt2-1.smt2 |    0.024s | 20.428MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-12.smt2-1.smt2 |    0.024s | 20.74MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-14.smt2-1.smt2 |    0.024s | 20.784MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-14.smt2-1.smt2 |    0.024s | 20.756MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-9.smt2 |    0.024s | 20.312MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-16.smt2 |    0.024s | 20.768MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-22.smt2 |    0.024s | 20.592MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-61.smt2-2.smt2 |    0.024s | 20.548MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SortedNDList.scala-2.smt2-2.smt2 |    0.024s | 20.544MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-8.smt2-1.smt2 |    0.024s | 19.684MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-22.smt2-1.smt2 |    0.024s | 20.496MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-6.smt2-2.smt2 |    0.024s | 20.292MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-13.smt2 |    0.025s | 20.432MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-23.smt2 |    0.025s | 20.1MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-2.smt2-1.smt2 |    0.025s | 20.244MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-19.smt2-3.smt2 |    0.025s | 19.996MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-16.smt2-2.smt2 |    0.025s | 20.16MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-32.smt2-2.smt2 |    0.025s | 19.668MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-32.smt2-1.smt2 |    0.025s | 19.676MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-29.smt2-2.smt2 |    0.025s | 19.916MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-25.smt2-2.smt2 |    0.025s | 19.784MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-16.smt2-3.smt2 |    0.025s | 20.604MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SortedNDList.scala-2.smt2-1.smt2 |    0.025s | 20.672MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-24.smt2 |    0.026s | 20.052MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-94.smt2-3.smt2 |    0.026s | 19.628MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-22.smt2-2.smt2 |    0.026s | 19.976MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-13.smt2-2.smt2 |    0.026s | 20.112MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-24.smt2-2.smt2 |    0.026s | 20.048MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-10.smt2-2.smt2 |    0.026s | 20.056MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-31.smt2-3.smt2 |    0.026s | 20.1MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Naturals.scala-4.smt2 |    0.026s | 20.556MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-20.smt2 |    0.026s | 20.62MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-29.smt2-1.smt2 |    0.026s | 19.824MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-7.smt2 |    0.027s | 19.84MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-14.smt2 |    0.027s | 20.064MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-17.smt2-1.smt2 |    0.027s | 19.804MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SecondsToTime.scala-5.smt2-3.smt2 |    0.027s | 20.388MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-40.smt2-2.smt2 |    0.027s | 19.788MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-30.smt2-3.smt2 |    0.027s | 19.968MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-18.smt2-1.smt2 |    0.027s | 20.284MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-31.smt2-2.smt2 |    0.027s | 20.212MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-21.smt2-1.smt2 |    0.027s | 19.996MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-3.smt2-2.smt2 |    0.027s | 19.78MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-22.smt2-2.smt2 |    0.027s | 20.3MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-19.smt2-2.smt2 |    0.027s | 22.164MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-17.smt2-2.smt2 |    0.027s | 19.844MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-20.smt2-2.smt2 |    0.027s | 20.604MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-2.smt2-2.smt2 |    0.027s | 19.364MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-21.smt2 |    0.028s | 19.972MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-LambdaEval.scala-60.smt2 |    0.028s | 20.56MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-10.smt2 |    0.028s | 20.484MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-22.smt2-1.smt2 |    0.028s | 20.336MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-61.smt2-1.smt2 |    0.028s | 19.804MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-17.smt2-3.smt2 |    0.028s | 20.308MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-2.smt2-1.smt2 |    0.028s | 19.34MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-14.smt2-1.smt2 |    0.029s | 21.764MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-MutuallyRecursive.scala-1.smt2-1.smt2 |    0.029s | 21.916MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Sync.scala-1.smt2-2.smt2 |    0.029s | 21.096MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-22.smt2-1.smt2 |    0.029s | 19.976MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-3.smt2 |    0.029s | 20.3MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-QuickSort.scala-22.smt2 |    0.029s | 21.076MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-1.smt2 |    0.029s | 20.616MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-14.smt2-1.smt2 |    0.029s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-22.smt2-1.smt2 |    0.029s | 20.556MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AmortizedQueue.scala-1.smt2-2.smt2 |    0.030s | 21.32MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-19.smt2-1.smt2 |    0.030s | 20.008MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SortedList.scala-1.smt2-1.smt2 |    0.030s | 20.056MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-24.smt2 |    0.031s | 20.912MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SearchLinkedList.scala-1.smt2-3.smt2 |    0.031s | 21.412MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-77.smt2 |    0.031s | 20.256MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-QuickSort.scala-27.smt2 |    0.031s | 21.22MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Naturals.scala-2.smt2 |    0.031s | 20.776MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-20.smt2-2.smt2 |    0.031s | 19.648MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SortedNDList.scala-2.smt2-3.smt2 |    0.031s | 20.472MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-25.smt2-1.smt2 |    0.031s | 20.852MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-14.smt2-1.smt2 |    0.031s | 20.892MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-21.smt2-3.smt2 |    0.032s | 20.7MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SecondsToTime.scala-8.smt2-2.smt2 |    0.032s | 20.632MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-1.smt2-3.smt2 |    0.032s | 21.556MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-46.smt2-1.smt2 |    0.032s | 19.54MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-MergeSort.scala-5.smt2 |    0.032s | 19.016MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-MergeSort.scala-5.smt2 |    0.033s | 18.984MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-47.smt2 |    0.033s | 19.848MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-28.smt2 |    0.033s | 19.948MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-1.smt2 |    0.033s | 20.992MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-2.smt2 |    0.033s | 19.96MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-101.smt2-3.smt2 |    0.033s | 20.948MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AmortizedQueue.scala-1.smt2-3.smt2 |    0.033s | 21.448MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-22.smt2-3.smt2 |    0.033s | 19.824MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-1.smt2-1.smt2 |    0.033s | 20.868MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-40.smt2 |    0.033s | 20.868MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-QuickSort.scala-29.smt2 |    0.033s | 20.856MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SumAndMax.scala-7.smt2 |    0.033s | 19.584MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ArrayBinarySearch.scala-1.smt2-2.smt2 |    0.033s | 21.532MiB| unknown | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-3.smt2 |    0.034s | 21.344MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-4.smt2 |    0.034s | 19.776MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BinaryTrie.scala-3.smt2-1.smt2 |    0.034s | 20.056MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-26.smt2-1.smt2 |    0.034s | 19.86MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Naturals.scala-12.smt2 |    0.034s | 19.612MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-31.smt2-3.smt2 |    0.034s | 21.676MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-10.smt2 |    0.035s | 19.656MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-InsertionSort.scala-1.smt2-2.smt2 |    0.035s | 21.188MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-106.smt2-2.smt2 |    0.035s | 19.796MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-19.smt2-3.smt2 |    0.035s | 21.88MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BitsTricks.scala-5.smt2 |    0.035s | 19.524MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-76.smt2 |    0.035s | 19.988MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AbsFun.scala-4.smt2-2.smt2 |    0.035s | 22.68MiB| unknown | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-14.smt2 |    0.036s | 22.292MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-71.smt2 |    0.036s | 19.816MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-17.smt2 |    0.036s | 19.584MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-94.smt2-3.smt2 |    0.036s | 19.68MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-106.smt2-2.smt2 |    0.036s | 21.24MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-23.smt2-2.smt2 |    0.036s | 19.788MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SortedNDList.scala-3.smt2-2.smt2 |    0.036s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-28.smt2 |    0.037s | 20.1MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SearchLinkedList.scala-1.smt2-2.smt2 |    0.037s | 21.328MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-7.smt2-2.smt2 |    0.037s | 19.572MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-22.smt2-2.smt2 |    0.037s | 20.016MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-26.smt2-2.smt2 |    0.037s | 20.02MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-23.smt2-2.smt2 |    0.037s | 20.296MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Naturals.scala-9.smt2 |    0.037s | 19.54MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-AbsFun.scala-13.smt2 |    0.037s | 22.312MiB| unknown | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-1.smt2-2.smt2 |    0.037s | 19.544MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-20.smt2-1.smt2 |    0.037s | 20.668MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-50.smt2 |    0.038s | 20.032MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-12.smt2 |    0.038s | 20.652MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-19.smt2 |    0.038s | 19.788MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-7.smt2 |    0.038s | 22.312MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Sync.scala-1.smt2 |    0.038s | 19.844MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-101.smt2-2.smt2 |    0.038s | 21.28MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-20.smt2 |    0.038s | 19.784MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-23.smt2-1.smt2 |    0.038s | 19.788MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-49.smt2-1.smt2 |    0.038s | 19.688MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-73.smt2-1.smt2 |    0.038s | 20.084MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-28.smt2-2.smt2 |    0.038s | 19.56MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-29.smt2 |    0.039s | 21.116MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-39.smt2 |    0.039s | 20.068MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-72.smt2 |    0.039s | 19.776MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-66.smt2 |    0.039s | 19.792MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-13.smt2-1.smt2 |    0.039s | 20.148MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SumAndMax.scala-7.smt2-3.smt2 |    0.039s | 19.676MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-24.smt2 |    0.039s | 20.092MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Naturals.scala-7.smt2 |    0.039s | 21.26MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AbsFun.scala-13.smt2-2.smt2 |    0.039s | 22.7MiB| unknown | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-7.smt2 |    0.040s | 19.988MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-18.smt2-1.smt2 |    0.040s | 20.612MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-17.smt2-1.smt2 |    0.040s | 20.048MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-18.smt2-3.smt2 |    0.040s | 20.308MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BitsTricks.scala-7.smt2 |    0.040s | 19.828MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-16.smt2-2.smt2 |    0.040s | 19.58MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-14.smt2-1.smt2 |    0.040s | 20.668MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-9.smt2 |    0.041s | 19.588MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SumAndMax.scala-7.smt2-1.smt2 |    0.041s | 19.78MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SortedNDList.scala-2.smt2 |    0.041s | 20.58MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-94.smt2 |    0.041s | 20.028MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BitsTricks.scala-8.smt2 |    0.041s | 20.008MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-2.smt2-1.smt2 |    0.041s | 20.784MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-30.smt2 |    0.042s | 20.1MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SortedNDList.scala-2.smt2-3.smt2 |    0.042s | 20.04MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-22.smt2 |    0.042s | 20.072MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-18.smt2-1.smt2 |    0.042s | 19.788MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-31.smt2-2.smt2 |    0.042s | 20.708MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-18.smt2 |    0.043s | 20.496MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-3.smt2-3.smt2 |    0.043s | 22.752MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-24.smt2-3.smt2 |    0.043s | 20.928MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-21.smt2-2.smt2 |    0.043s | 20.648MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BitsTricks.scala-14.smt2 |    0.043s | 20.468MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-72.smt2 |    0.043s | 19.808MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-66.smt2 |    0.043s | 19.592MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-11.smt2-3.smt2 |    0.043s | 19.74MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-21.smt2-1.smt2 |    0.043s | 19.916MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-21.smt2-2.smt2 |    0.043s | 19.716MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-13.smt2-3.smt2 |    0.043s | 20.552MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-32.smt2 |    0.044s | 20.1MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-8.smt2-3.smt2 |    0.044s | 20.548MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-73.smt2-1.smt2 |    0.044s | 20.264MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-58.smt2-2.smt2 |    0.044s | 21.808MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-10.smt2 |    0.044s | 20.296MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-11.smt2-1.smt2 |    0.044s | 19.628MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Fibonacci.scala-3.smt2 |    0.045s | 20.556MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-10.smt2-1.smt2 |    0.045s | 20.548MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-101.smt2-1.smt2 |    0.045s | 21.068MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SumAndMax.scala-4.smt2-2.smt2 |    0.045s | 21.184MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-70.smt2 |    0.045s | 21.092MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-40.smt2 |    0.046s | 20.016MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-11.smt2-1.smt2 |    0.046s | 20.052MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-7.smt2-2.smt2 |    0.046s | 20.772MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-18.smt2 |    0.046s | 20.804MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-4.smt2 |    0.046s | 19.796MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-17.smt2-2.smt2 |    0.046s | 20.56MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-14.smt2 |    0.047s | 20.308MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-21.smt2 |    0.047s | 20.7MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-15.smt2 |    0.047s | 20.256MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-11.smt2 |    0.047s | 20.468MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-56.smt2-3.smt2 |    0.047s | 21.396MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SecondsToTime.scala-3.smt2-2.smt2 |    0.047s | 21.884MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Naturals.scala-10.smt2 |    0.047s | 20.44MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-26.smt2 |    0.048s | 20.032MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-27.smt2 |    0.048s | 21.296MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-8.smt2 |    0.048s | 20.264MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-25.smt2-2.smt2 |    0.048s | 20.376MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-1.smt2-2.smt2 |    0.048s | 21.492MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Naturals.scala-6.smt2 |    0.048s | 21.488MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-QuickSort.scala-31.smt2 |    0.048s | 20.336MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-QuickSort.scala-17.smt2 |    0.048s | 20.444MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Lists5.scala-4.smt2-1.smt2 |    0.048s | 20.812MiB| unknown | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-11.smt2-2.smt2 |    0.048s | 19.836MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-27.smt2-2.smt2 |    0.048s | 20.296MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-3.smt2-1.smt2 |    0.048s | 20.808MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-66.smt2-2.smt2 |    0.049s | 20.048MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-10.smt2 |    0.050s | 20.316MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-1.smt2-1.smt2 |    0.050s | 20.256MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-93.smt2-1.smt2 |    0.051s | 21.928MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-15.smt2-2.smt2 |    0.051s | 19.784MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-39.smt2-2.smt2 |    0.051s | 21.456MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ArrayBinarySearch.scala-1.smt2-1.smt2 |    0.052s | 23.428MiB| unknown | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-57.smt2-1.smt2 |    0.053s | 21.424MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-AbsFun.scala-4.smt2 |    0.053s | 22.688MiB| unknown | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-13.smt2 |    0.054s | 20.3MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Sync.scala-1.smt2-3.smt2 |    0.054s | 21.06MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-50.smt2-3.smt2 |    0.055s | 20.84MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-19.smt2-1.smt2 |    0.055s | 19.8MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-17.smt2-1.smt2 |    0.055s | 20.116MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-14.smt2-2.smt2 |    0.056s | 22.52MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SecondsToTime.scala-5.smt2-2.smt2 |    0.057s | 20.724MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-54.smt2-3.smt2 |    0.057s | 21.516MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-22.smt2-1.smt2 |    0.057s | 20.82MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-21.smt2 |    0.057s | 21.036MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-7.smt2-2.smt2 |    0.058s | 20.292MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Sync.scala-1.smt2-2.smt2 |    0.059s | 21.024MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-TwoSizeFunctions.scala-1.smt2-3.smt2 |    0.060s | 22.32MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-13.smt2 |    0.061s | 21.768MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-19.smt2-1.smt2 |    0.061s | 22.132MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-10.smt2-3.smt2 |    0.061s | 22.32MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-17.smt2-3.smt2 |    0.063s | 21.572MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Naturals.scala-5.smt2 |    0.063s | 19.524MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Naturals.scala-8.smt2 |    0.063s | 20.012MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-3.smt2-2.smt2 |    0.064s | 22.788MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PositiveMap.scala-2.smt2-2.smt2 |    0.064s | 22.188MiB| unknown | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AbsFun.scala-4.smt2-3.smt2 |    0.064s | 22.704MiB| unknown | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-9.smt2-2.smt2 |    0.064s | 20.188MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-9.smt2 |    0.065s | 22.728MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SecondsToTime.scala-3.smt2-1.smt2 |    0.065s | 20.272MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-58.smt2-1.smt2 |    0.065s | 21.424MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-7.smt2-2.smt2 |    0.065s | 23.704MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-9.smt2-2.smt2 |    0.066s | 24.52MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-3.smt2-1.smt2 |    0.067s | 20.964MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-13.smt2-3.smt2 |    0.067s | 21.336MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-66.smt2-3.smt2 |    0.067s | 21.708MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-82.smt2-1.smt2 |    0.068s | 22.076MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-25.smt2-2.smt2 |    0.068s | 22.104MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-17.smt2 |    0.070s | 21.544MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-66.smt2-1.smt2 |    0.070s | 21.596MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-40.smt2-2.smt2 |    0.070s | 20.86MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AbsFun.scala-4.smt2-1.smt2 |    0.070s | 22.644MiB| unknown | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-67.smt2-1.smt2 |    0.071s | 21.716MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-13.smt2-2.smt2 |    0.071s | 20.012MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SumAndMax.scala-7.smt2-3.smt2 |    0.072s | 19.628MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-7.smt2-2.smt2 |    0.073s | 20.336MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-39.smt2 |    0.075s | 21.572MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-22.smt2-3.smt2 |    0.076s | 24.604MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-QuickSort.scala-13.smt2 |    0.077s | 20.56MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-22.smt2-2.smt2 |    0.078s | 21.484MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-72.smt2-2.smt2 |    0.079s | 22.988MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AbsFun.scala-13.smt2-1.smt2 |    0.079s | 24.644MiB| unknown | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AbsFun.scala-13.smt2-3.smt2 |    0.079s | 22.628MiB| unknown | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-67.smt2-3.smt2 |    0.082s | 21.9MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-27.smt2 |    0.086s | 19.78MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-9.smt2 |    0.088s | 24.468MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-57.smt2-3.smt2 |    0.089s | 21.636MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-73.smt2-2.smt2 |    0.089s | 23.244MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-18.smt2-2.smt2 |    0.090s | 26.04MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SecondsToTime.scala-8.smt2-3.smt2 |    0.094s | 23.204MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-11.smt2-3.smt2 |    0.099s | 20.524MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-10.smt2-3.smt2 |    0.102s | 27.676MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-19.smt2-3.smt2 |    0.104s | 24.388MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SortedList.scala-1.smt2-3.smt2 |    0.104s | 24.416MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BinaryTrie.scala-1.smt2-3.smt2 |    0.104s | 24.268MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-65.smt2-3.smt2 |    0.106s | 22.048MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-27.smt2-1.smt2 |    0.108s | 19.804MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-68.smt2-2.smt2 |    0.115s | 22.272MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-7.smt2-2.smt2 |    0.119s | 22.288MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BinaryTrie.scala-1.smt2-2.smt2 |    0.122s | 25.984MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SortedList.scala-1.smt2-2.smt2 |    0.128s | 25.548MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-19.smt2-2.smt2 |    0.133s | 26.136MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-72.smt2-1.smt2 |    0.134s | 23.336MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-65.smt2-1.smt2 |    0.136s | 22.136MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-99.smt2-1.smt2 |    0.140s | 23.212MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-QuickSort.scala-25.smt2 |    0.141s | 24.408MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ArrayBinarySearch.scala-1.smt2 |    0.143s | 31.44MiB| unknown | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SecondsToTime.scala-1.smt2-2.smt2 |    0.150s | 25.112MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-69.smt2-1.smt2 |    0.162s | 23.252MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-QuickSort.scala-18.smt2 |    0.168s | 26.552MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-51.smt2-3.smt2 |    0.193s | 22.304MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-55.smt2-2.smt2 |    0.204s | 23.62MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ArrayBinarySearch.scala-1.smt2-3.smt2 |    0.205s | 31.896MiB| unknown | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-56.smt2-1.smt2 |    0.206s | 22.9MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-81.smt2-3.smt2 |    0.213s | 23.648MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-QuickSort.scala-14.smt2 |    0.225s | 25.976MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-100.smt2-3.smt2 |    0.248s | 22.504MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-93.smt2-3.smt2 |    0.268s | 22.704MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-50.smt2-1.smt2 |    0.315s | 23.0MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-3.smt2-3.smt2 |    0.320s | 23.056MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Interpreter.scala-4.smt2 |    0.325s | 27.48MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SimpInterpret.scala-4.smt2 |    0.375s | 27.388MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-85.smt2-2.smt2 |    0.432s | 23.36MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-61.smt2-3.smt2 |    0.435s | 23.432MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Interpreter.scala-4.smt2 |    0.490s | 37.44MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-59.smt2-3.smt2 |    0.503s | 23.892MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SimpInterpret.scala-4.smt2 |    0.541s | 47.732MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-TwoSizeFunctions.scala-1.smt2-2.smt2 |    0.661s | 25.592MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-73.smt2-3.smt2 |    0.714s | 25.148MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Parser.scala-1.smt2-2.smt2 |    1.017s | 25.908MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-9.smt2 |    1.017s | 84.664MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-1.smt2-3.smt2 |    1.159s | 30.408MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Parser.scala-1.smt2-3.smt2 |    1.168s | 25.752MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-58.smt2-3.smt2 |    1.212s | 24.576MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LeftistHeap.scala-1.smt2-3.smt2 |    1.216s | 30.46MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-62.smt2-1.smt2 |    1.217s | 24.644MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-32.smt2-3.smt2 |    1.354s | 29.648MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-1.smt2-2.smt2 |    1.448s | 30.252MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LeftistHeap.scala-1.smt2-2.smt2 |    1.476s | 30.132MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-18.smt2-3.smt2 |    1.673s | 34.32MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-17.smt2-1.smt2 |    1.882s | 88.212MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-64.smt2-2.smt2 |    2.098s | 29.288MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SecondsToTime.scala-5.smt2-1.smt2 |    4.795s | 46.152MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SumAndMax.scala-4.smt2-3.smt2 |    5.176s | 32.124MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-InsertionSort.scala-1.smt2-3.smt2 |    5.226s | 32.052MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BitsTricks.scala-19.smt2 |   11.636s | 30.288MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-67.smt2-2.smt2 |   12.665s | 144.0MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-19.smt2 |   12.743s | 29.22MiB| unsat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-30.smt2-2.smt2 |   15.964s | 39.02MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-45.smt2-1.smt2 |   16.038s | 29.752MiB| sat | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-108.smt2 |   20.008s | 28.244MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-36.smt2 |   20.008s | 27.924MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-44.smt2 |   20.008s | 33.664MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-111.smt2 |   20.008s | 28.268MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-85.smt2 |   20.008s | 32.056MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-98.smt2-2.smt2 |   20.008s | 32.828MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-69.smt2-2.smt2 |   20.008s | 31.472MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-87.smt2-1.smt2 |   20.008s | 31.788MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-83.smt2-2.smt2 |   20.008s | 30.316MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-83.smt2-1.smt2 |   20.008s | 30.632MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-97.smt2-2.smt2 |   20.008s | 34.264MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-105.smt2-1.smt2 |   20.008s | 31.916MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-84.smt2-1.smt2 |   20.008s | 31.304MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-113.smt2-3.smt2 |   20.008s | 29.056MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-99.smt2-2.smt2 |   20.008s | 30.828MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-102.smt2-1.smt2 |   20.008s | 27.28MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-76.smt2-2.smt2 |   20.008s | 32.188MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-108.smt2-2.smt2 |   20.008s | 28.7MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-43.smt2-1.smt2 |   20.008s | 30.54MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-98.smt2-3.smt2 |   20.008s | 33.08MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-48.smt2-1.smt2 |   20.008s | 27.672MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-60.smt2 |   20.009s | 37.984MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-13.smt2 |   20.009s | 36.836MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-106.smt2 |   20.009s | 54.904MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-99.smt2 |   20.009s | 33.208MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-38.smt2 |   20.009s | 30.18MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-112.smt2 |   20.009s | 28.608MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-42.smt2 |   20.009s | 35.1MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-69.smt2 |   20.009s | 30.04MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-80.smt2 |   20.009s | 29.668MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SearchLinkedList.scala-4.smt2 |   20.009s | 34.224MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-81.smt2 |   20.009s | 32.12MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-83.smt2 |   20.009s | 30.456MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SearchLinkedList.scala-7.smt2 |   20.009s | 34.688MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-103.smt2-1.smt2 |   20.009s | 27.172MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-TwoSizeFunctions.scala-4.smt2-2.smt2 |   20.009s | 37.864MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-115.smt2-1.smt2 |   20.009s | 31.972MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-10.smt2-1.smt2 |   20.009s | 31.208MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-41.smt2-2.smt2 |   20.009s | 31.016MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-39.smt2-3.smt2 |   20.009s | 31.236MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-111.smt2-1.smt2 |   20.009s | 28.056MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-13.smt2-1.smt2 |   20.009s | 31.5MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-76.smt2-3.smt2 |   20.009s | 31.98MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-92.smt2-3.smt2 |   20.009s | 31.36MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-90.smt2-3.smt2 |   20.009s | 29.78MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-36.smt2-2.smt2 |   20.009s | 30.54MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-99.smt2-3.smt2 |   20.009s | 32.98MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-37.smt2-3.smt2 |   20.009s | 27.024MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-89.smt2-3.smt2 |   20.009s | 30.324MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-86.smt2-1.smt2 |   20.009s | 33.3MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-90.smt2-1.smt2 |   20.009s | 29.652MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-21.smt2-2.smt2 |   20.009s | 43.744MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-87.smt2-2.smt2 |   20.009s | 28.776MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-52.smt2-2.smt2 |   20.009s | 30.396MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-106.smt2-3.smt2 |   20.009s | 35.012MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-71.smt2-1.smt2 |   20.009s | 29.488MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-44.smt2-3.smt2 |   20.009s | 35.732MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-44.smt2-2.smt2 |   20.009s | 32.424MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Parser.scala-3.smt2-3.smt2 |   20.009s | 35.068MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-QuickSort.scala-30.smt2 |   20.009s | 45.232MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-13.smt2 |   20.010s | 30.7MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-98.smt2 |   20.010s | 31.728MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-79.smt2 |   20.010s | 37.852MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-95.smt2 |   20.010s | 29.992MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-14.smt2 |   20.010s | 52.652MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-104.smt2 |   20.010s | 30.984MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-37.smt2 |   20.010s | 32.744MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-48.smt2 |   20.010s | 26.956MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-52.smt2 |   20.010s | 27.684MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-63.smt2 |   20.010s | 28.708MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-107.smt2 |   20.010s | 32.04MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-105.smt2 |   20.010s | 32.264MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Parser.scala-3.smt2-2.smt2 |   20.010s | 38.372MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-114.smt2-3.smt2 |   20.010s | 30.128MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-28.smt2-2.smt2 |   20.010s | 41.684MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-42.smt2-1.smt2 |   20.010s | 29.32MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-54.smt2-1.smt2 |   20.010s | 31.636MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-107.smt2-1.smt2 |   20.010s | 34.244MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Map.scala-2.smt2-1.smt2 |   20.010s | 64.68MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Map.scala-2.smt2-2.smt2 |   20.010s | 54.336MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-41.smt2-3.smt2 |   20.010s | 28.936MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-89.smt2-2.smt2 |   20.010s | 28.428MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-7.smt2-1.smt2 |   20.010s | 51.928MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-72.smt2-3.smt2 |   20.010s | 32.264MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-107.smt2-2.smt2 |   20.010s | 33.116MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-81.smt2-2.smt2 |   20.010s | 30.916MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-5.smt2-3.smt2 |   20.010s | 40.248MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-82.smt2-3.smt2 |   20.010s | 54.108MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-51.smt2-2.smt2 |   20.010s | 30.572MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-108.smt2-1.smt2 |   20.010s | 29.26MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-63.smt2-1.smt2 |   20.010s | 28.292MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-40.smt2-1.smt2 |   20.010s | 31.22MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-48.smt2-3.smt2 |   20.010s | 27.956MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-12.smt2-1.smt2 |   20.010s | 39.872MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SumAndMax.scala-7.smt2-2.smt2 |   20.010s | 37.264MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-84.smt2-2.smt2 |   20.010s | 30.704MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-90.smt2-2.smt2 |   20.010s | 31.316MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-85.smt2-3.smt2 |   20.010s | 29.304MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-7.smt2-3.smt2 |   20.010s | 56.12MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-92.smt2-1.smt2 |   20.010s | 31.74MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-39.smt2-1.smt2 |   20.010s | 31.188MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-37.smt2-1.smt2 |   20.010s | 31.556MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-27.smt2-3.smt2 |   20.010s | 39.784MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-104.smt2-1.smt2 |   20.010s | 33.664MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PositiveMap.scala-2.smt2-1.smt2 |   20.010s | 41.62MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-1.smt2 |   20.010s | 41.812MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Parser.scala-1.smt2 |   20.010s | 44.368MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-107.smt2 |   20.010s | 33.068MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-14.smt2-3.smt2 |   20.010s | 33.012MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-3.smt2-1.smt2 |   20.010s | 34.384MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Lists5.scala-4.smt2-3.smt2 |   20.010s | 38.556MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-94.smt2-2.smt2 |   20.010s | 55.348MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-4.smt2-1.smt2 |   20.010s | 59.852MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-13.smt2-2.smt2 |   20.010s | 49.172MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-12.smt2-3.smt2 |   20.010s | 45.62MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-86.smt2 |   20.011s | 39.552MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-67.smt2 |   20.011s | 83.092MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Map.scala-2.smt2 |   20.011s | 66.764MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-116.smt2 |   20.011s | 34.296MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SortedNDList.scala-3.smt2 |   20.011s | 46.424MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-LeftistHeap.scala-1.smt2 |   20.011s | 60.06MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-53.smt2 |   20.011s | 30.808MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-68.smt2 |   20.011s | 36.852MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-29.smt2-3.smt2 |   20.011s | 37.82MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-59.smt2-1.smt2 |   20.011s | 38.62MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-13.smt2-3.smt2 |   20.011s | 38.836MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-24.smt2-2.smt2 |   20.011s | 43.936MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-105.smt2-2.smt2 |   20.011s | 33.176MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-14.smt2-3.smt2 |   20.011s | 51.884MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-37.smt2-2.smt2 |   20.011s | 32.62MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-47.smt2-3.smt2 |   20.011s | 32.26MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-47.smt2-2.smt2 |   20.011s | 33.044MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-79.smt2-2.smt2 |   20.011s | 30.184MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-108.smt2-3.smt2 |   20.011s | 26.3MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-69.smt2-3.smt2 |   20.011s | 31.908MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-14.smt2-1.smt2 |   20.011s | 51.488MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-48.smt2-2.smt2 |   20.011s | 27.4MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BinarySearchTree.scala-1.smt2-2.smt2 |   20.011s | 57.7MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SearchLinkedList.scala-7.smt2-3.smt2 |   20.011s | 36.768MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-16.smt2-2.smt2 |   20.011s | 43.992MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-114.smt2-2.smt2 |   20.011s | 30.624MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-27.smt2-2.smt2 |   20.011s | 38.128MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-13.smt2-2.smt2 |   20.011s | 41.84MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-18.smt2-3.smt2 |   20.011s | 96.76MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-5.smt2-1.smt2 |   20.011s | 38.436MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-116.smt2-3.smt2 |   20.011s | 33.592MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-111.smt2-2.smt2 |   20.011s | 32.264MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-9.smt2-1.smt2 |   20.011s | 50.792MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-2.smt2-2.smt2 |   20.011s | 63.952MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-6.smt2-1.smt2 |   20.011s | 36.46MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-53.smt2-1.smt2 |   20.011s | 30.788MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-70.smt2-2.smt2 |   20.011s | 32.184MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-10.smt2-2.smt2 |   20.011s | 36.368MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-42.smt2-3.smt2 |   20.011s | 35.36MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Naturals.scala-13.smt2 |   20.011s | 52.128MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Map.scala-1.smt2 |   20.011s | 54.896MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BinarySearchTree.scala-1.smt2 |   20.011s | 47.132MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-68.smt2 |   20.011s | 33.312MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BinarySearchTree.scala-1.smt2-3.smt2 |   20.011s | 46.144MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-9.smt2-2.smt2 |   20.011s | 51.944MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BinarySearchTree.scala-1.smt2-2.smt2 |   20.011s | 47.088MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-70.smt2-1.smt2 |   20.011s | 37.064MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SumAndMax.scala-4.smt2-2.smt2 |   20.011s | 40.584MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ListOperations.scala-1.smt2-2.smt2 |   20.011s | 46.896MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-2.smt2-1.smt2 |   20.011s | 82.784MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-70.smt2-2.smt2 |   20.011s | 53.42MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-110.smt2 |   20.012s | 34.944MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Map.scala-1.smt2 |   20.012s | 59.78MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-114.smt2 |   20.012s | 31.728MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Lists5.scala-4.smt2 |   20.012s | 72.164MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-18.smt2 |   20.012s | 60.648MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SearchLinkedList.scala-1.smt2 |   20.012s | 86.348MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-54.smt2 |   20.012s | 88.948MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-105.smt2-3.smt2 |   20.012s | 30.14MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Parser.scala-3.smt2-1.smt2 |   20.012s | 37.308MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-muDot2.scala-43.smt2-1.smt2 |   20.012s | 75.956MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-84.smt2-3.smt2 |   20.012s | 30.516MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-112.smt2-1.smt2 |   20.012s | 28.588MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-91.smt2-1.smt2 |   20.012s | 91.124MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-38.smt2-2.smt2 |   20.012s | 31.048MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-6.smt2-3.smt2 |   20.012s | 33.876MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-55.smt2-3.smt2 |   20.012s | 90.444MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-2.smt2-3.smt2 |   20.012s | 68.048MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-92.smt2-2.smt2 |   20.012s | 36.572MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-14.smt2-3.smt2 |   20.012s | 38.884MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SearchLinkedList.scala-7.smt2-2.smt2 |   20.012s | 35.936MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-InsertionSort.scala-1.smt2-1.smt2 |   20.012s | 82.944MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-5.smt2-1.smt2 |   20.012s | 35.044MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Map.scala-2.smt2-3.smt2 |   20.012s | 60.592MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-12.smt2-3.smt2 |   20.012s | 31.08MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-54.smt2-2.smt2 |   20.012s | 30.684MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-4.smt2 |   20.012s | 72.724MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BitsTricks.scala-13.smt2 |   20.012s | 48.356MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-88.smt2 |   20.012s | 68.744MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-AVLTree.scala-2.smt2 |   20.012s | 48.028MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-80.smt2 |   20.012s | 53.924MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SearchLinkedList.scala-1.smt2-1.smt2 |   20.012s | 72.152MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-17.smt2-1.smt2 |   20.012s | 68.828MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SumAndMax.scala-7.smt2-2.smt2 |   20.012s | 55.344MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Map.scala-2.smt2-3.smt2 |   20.012s | 57.124MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-AmortizedQueue.scala-1.smt2 |   20.013s | 86.46MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-muDot2.scala-43.smt2 |   20.013s | 73.996MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-2.smt2 |   20.013s | 61.924MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-41.smt2 |   20.013s | 53.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-5.smt2-2.smt2 |   20.013s | 43.184MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SearchLinkedList.scala-1.smt2-1.smt2 |   20.013s | 86.032MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-43.smt2-2.smt2 |   20.013s | 31.804MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-5.smt2-2.smt2 |   20.013s | 40.652MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-36.smt2-1.smt2 |   20.013s | 28.332MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-100.smt2-2.smt2 |   20.013s | 31.064MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Lists5.scala-4.smt2-3.smt2 |   20.013s | 89.512MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SortedNDList.scala-3.smt2-1.smt2 |   20.013s | 61.04MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PositiveMap.scala-2.smt2-2.smt2 |   20.013s | 52.196MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-96.smt2-1.smt2 |   20.013s | 90.492MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-16.smt2-1.smt2 |   20.013s | 42.928MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-113.smt2-1.smt2 |   20.013s | 28.152MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-52.smt2-1.smt2 |   20.013s | 30.908MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LeftistHeap.scala-13.smt2-2.smt2 |   20.013s | 79.004MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-13.smt2-2.smt2 |   20.013s | 61.112MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-13.smt2-3.smt2 |   20.013s | 37.192MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Map.scala-2.smt2 |   20.013s | 54.544MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Naturals.scala-14.smt2 |   20.013s | 51.636MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Lists5.scala-4.smt2 |   20.013s | 42.82MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SimpInterpret.scala-3.smt2 |   20.013s | 50.816MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-5.smt2-3.smt2 |   20.013s | 59.948MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SecondsToTime.scala-8.smt2-2.smt2 |   20.013s | 98.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SortedList.scala-1.smt2-2.smt2 |   20.013s | 69.068MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-2.smt2-2.smt2 |   20.013s | 72.216MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ListOperations.scala-1.smt2-3.smt2 |   20.013s | 76.244MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-9.smt2-3.smt2 |   20.013s | 85.66MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-7.smt2-1.smt2 |   20.013s | 84.564MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-30.smt2-1.smt2 |   20.013s | 44.568MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-1.smt2-1.smt2 |   20.013s | 52.96MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-InsertionSort.scala-1.smt2-2.smt2 |   20.013s | 40.32MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-10.smt2-2.smt2 |   20.013s | 57.68MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SearchLinkedList.scala-7.smt2-2.smt2 |   20.013s | 81.864MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SecondsToTime.scala-8.smt2-3.smt2 |   20.013s | 96.632MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SimpInterpret.scala-3.smt2-1.smt2 |   20.013s | 73.208MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-107.smt2-3.smt2 |   20.013s | 52.9MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-LeftistHeap.scala-8.smt2 |   20.014s | 101.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-91.smt2 |   20.014s | 91.016MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-51.smt2 |   20.014s | 89.292MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-10.smt2-3.smt2 |   20.014s | 31.376MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-13.smt2-1.smt2 |   20.014s | 59.928MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-16.smt2-3.smt2 |   20.014s | 36.872MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-3.smt2-1.smt2 |   20.014s | 91.628MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LeftistHeap.scala-5.smt2-2.smt2 |   20.014s | 72.012MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-88.smt2-3.smt2 |   20.014s | 28.408MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-103.smt2-3.smt2 |   20.014s | 27.548MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Parser.scala-5.smt2-1.smt2 |   20.014s | 97.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-115.smt2-2.smt2 |   20.014s | 30.236MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Lists5.scala-4.smt2-2.smt2 |   20.014s | 82.696MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BinarySearchTree.scala-1.smt2-1.smt2 |   20.014s | 57.544MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Interpreter.scala-3.smt2 |   20.014s | 82.144MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-HeapSort.scala-5.smt2 |   20.014s | 81.156MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-37.smt2 |   20.014s | 86.408MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-17.smt2-2.smt2 |   20.014s | 108.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Parser.scala-3.smt2-1.smt2 |   20.014s | 75.404MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-19.smt2-1.smt2 |   20.014s | 50.724MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Map.scala-1.smt2-1.smt2 |   20.014s | 56.728MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-10.smt2-2.smt2 |   20.014s | 88.872MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Parser.scala-1.smt2-2.smt2 |   20.014s | 60.324MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-9.smt2-2.smt2 |   20.014s | 90.252MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-12.smt2-2.smt2 |   20.014s | 37.772MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-2.smt2-2.smt2 |   20.014s | 45.544MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-62.smt2 |   20.015s | 156.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AmortizedQueue.scala-1.smt2-1.smt2 |   20.015s | 85.976MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LeftistHeap.scala-13.smt2-3.smt2 |   20.015s | 99.292MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-78.smt2-1.smt2 |   20.015s | 97.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-14.smt2-2.smt2 |   20.015s | 111.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-110.smt2-1.smt2 |   20.015s | 36.28MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-4.smt2-2.smt2 |   20.015s | 110.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Lists5.scala-4.smt2-1.smt2 |   20.015s | 72.504MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-52.smt2-3.smt2 |   20.015s | 30.948MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-98.smt2-1.smt2 |   20.015s | 32.568MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BinaryTrie.scala-9.smt2-1.smt2 |   20.015s | 97.464MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-14.smt2-2.smt2 |   20.015s | 53.804MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-25.smt2-3.smt2 |   20.015s | 38.776MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-60.smt2-3.smt2 |   20.015s | 54.5MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Parser.scala-9.smt2-1.smt2 |   20.015s | 100.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-5.smt2 |   20.015s | 92.22MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SortedList.scala-1.smt2 |   20.015s | 41.796MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-AVLTree.scala-4.smt2 |   20.015s | 81.736MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AmortizedQueue.scala-1.smt2-1.smt2 |   20.015s | 77.6MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Interpreter.scala-3.smt2-3.smt2 |   20.015s | 102.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-62.smt2-1.smt2 |   20.015s | 69.732MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-76.smt2-3.smt2 |   20.015s | 87.856MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SortedList.scala-1.smt2-1.smt2 |   20.015s | 48.584MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-88.smt2-2.smt2 |   20.015s | 72.076MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Map.scala-2.smt2-2.smt2 |   20.015s | 58.42MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-22.smt2-3.smt2 |   20.015s | 111.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-4.smt2-2.smt2 |   20.015s | 75.056MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ListOperations.scala-5.smt2-1.smt2 |   20.015s | 94.948MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SearchLinkedList.scala-4.smt2-3.smt2 |   20.015s | 72.04MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-7.smt2-3.smt2 |   20.015s | 83.612MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-LeftistHeap.scala-5.smt2 |   20.016s | 119.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Parser.scala-1.smt2 |   20.016s | 152.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-19.smt2 |   20.016s | 88.504MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PositiveMap.scala-2.smt2 |   20.016s | 57.812MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-BinaryTrie.scala-9.smt2 |   20.016s | 96.356MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-55.smt2 |   20.016s | 145.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-64.smt2 |   20.016s | 157.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-17.smt2-2.smt2 |   20.016s | 125.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-25.smt2-1.smt2 |   20.016s | 100.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-14.smt2-3.smt2 |   20.016s | 100.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Parser.scala-5.smt2-2.smt2 |   20.016s | 98.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-8.smt2-1.smt2 |   20.016s | 92.748MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SearchLinkedList.scala-4.smt2-3.smt2 |   20.016s | 34.312MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-21.smt2-3.smt2 |   20.016s | 108.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SecondsToTime.scala-8.smt2 |   20.016s | 96.492MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SortedNDList.scala-3.smt2 |   20.016s | 84.736MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-106.smt2 |   20.016s | 90.196MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-5.smt2-2.smt2 |   20.016s | 142.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-2.smt2-1.smt2 |   20.016s | 36.12MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-10.smt2-1.smt2 |   20.016s | 37.276MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-39.smt2-3.smt2 |   20.016s | 50.724MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-30.smt2-2.smt2 |   20.016s | 105.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-14.smt2-1.smt2 |   20.016s | 84.248MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-18.smt2-3.smt2 |   20.016s | 116.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-21.smt2-2.smt2 |   20.016s | 116.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-10.smt2-1.smt2 |   20.016s | 97.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-18.smt2-3.smt2 |   20.016s | 71.664MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-InsertionSort.scala-1.smt2-1.smt2 |   20.016s | 103.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-TwoSizeFunctions.scala-4.smt2 |   20.017s | 32.816MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-BinaryTrie.scala-3.smt2 |   20.017s | 104.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-3.smt2 |   20.017s | 90.06MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SortedList.scala-1.smt2 |   20.017s | 88.652MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-4.smt2 |   20.017s | 111.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LeftistHeap.scala-5.smt2-3.smt2 |   20.017s | 99.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-86.smt2-2.smt2 |   20.017s | 32.08MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-81.smt2-1.smt2 |   20.017s | 32.068MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-muDot2.scala-43.smt2-3.smt2 |   20.017s | 106.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-5.smt2-3.smt2 |   20.017s | 95.088MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-18.smt2-1.smt2 |   20.017s | 165.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BinaryTrie.scala-3.smt2-2.smt2 |   20.017s | 109.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-10.smt2-2.smt2 |   20.017s | 31.008MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LeftistHeap.scala-8.smt2-2.smt2 |   20.017s | 130.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-97.smt2-1.smt2 |   20.017s | 34.272MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-60.smt2 |   20.017s | 33.164MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-muDot2.scala-41.smt2 |   20.017s | 109.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BitsTricks.scala-18.smt2 |   20.017s | 107.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ListOperations.scala-10.smt2 |   20.017s | 72.32MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-TwoSizeFunctions.scala-1.smt2 |   20.017s | 132.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-14.smt2-3.smt2 |   20.017s | 89.132MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-1.smt2-2.smt2 |   20.017s | 82.708MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SearchLinkedList.scala-4.smt2-2.smt2 |   20.017s | 147.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-106.smt2-1.smt2 |   20.017s | 90.248MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-13.smt2-3.smt2 |   20.017s | 76.036MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SecondsToTime.scala-3.smt2-2.smt2 |   20.017s | 97.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-26.smt2-3.smt2 |   20.017s | 179.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-6.smt2-3.smt2 |   20.017s | 153.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-28.smt2-1.smt2 |   20.017s | 143.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-18.smt2-2.smt2 |   20.017s | 63.576MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-5.smt2-1.smt2 |   20.017s | 70.14MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PositiveMap.scala-2.smt2-1.smt2 |   20.017s | 108.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-BinaryTrie.scala-5.smt2 |   20.018s | 130.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Interpreter.scala-3.smt2 |   20.018s | 134.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-61.smt2 |   20.018s | 158.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-101.smt2 |   20.018s | 151.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-2.smt2 |   20.018s | 153.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-14.smt2 |   20.018s | 147.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Compiler.scala-7.smt2-2.smt2 |   20.018s | 44.256MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-55.smt2-1.smt2 |   20.018s | 90.68MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-9.smt2-2.smt2 |   20.018s | 157.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-109.smt2-1.smt2 |   20.018s | 26.868MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-94.smt2-2.smt2 |   20.018s | 52.804MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-18.smt2-2.smt2 |   20.018s | 164.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Parser.scala-5.smt2-3.smt2 |   20.018s | 106.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-64.smt2-3.smt2 |   20.018s | 151.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Parser.scala-5.smt2 |   20.018s | 139.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-24.smt2-2.smt2 |   20.018s | 119.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SecondsToTime.scala-1.smt2-2.smt2 |   20.018s | 122.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-muDot2.scala-41.smt2-1.smt2 |   20.018s | 105.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-29.smt2-1.smt2 |   20.018s | 172.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Map.scala-1.smt2-2.smt2 |   20.018s | 55.524MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SecondsToTime.scala-1.smt2-1.smt2 |   20.018s | 99.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-9.smt2-1.smt2 |   20.018s | 95.084MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-5.smt2 |   20.019s | 134.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-78.smt2 |   20.019s | 99.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-14.smt2 |   20.019s | 143.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-5.smt2-3.smt2 |   20.019s | 159.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-3.smt2-1.smt2 |   20.019s | 159.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-88.smt2-2.smt2 |   20.019s | 34.784MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-4.smt2-3.smt2 |   20.019s | 100.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-17.smt2-3.smt2 |   20.019s | 148.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-95.smt2-3.smt2 |   20.019s | 31.752MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-107.smt2-3.smt2 |   20.019s | 32.372MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-17.smt2-3.smt2 |   20.019s | 159.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-5.smt2-2.smt2 |   20.019s | 97.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-29.smt2-3.smt2 |   20.019s | 117.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-9.smt2-3.smt2 |   20.019s | 94.904MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-1.smt2-1.smt2 |   20.019s | 46.852MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SearchLinkedList.scala-7.smt2-1.smt2 |   20.019s | 117.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Parser.scala-5.smt2-3.smt2 |   20.019s | 150.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-muDot2.scala-41.smt2-3.smt2 |   20.019s | 114.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-6.smt2-1.smt2 |   20.019s | 87.608MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ListOperations.scala-10.smt2-2.smt2 |   20.019s | 108.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ListOperations.scala-3.smt2-2.smt2 |   20.019s | 70.996MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-4.smt2-3.smt2 |   20.020s | 161.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-68.smt2-1.smt2 |   20.020s | 29.832MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-100.smt2-1.smt2 |   20.020s | 90.124MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-TwoSizeFunctions.scala-1.smt2-1.smt2 |   20.020s | 86.236MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LeftistHeap.scala-5.smt2-1.smt2 |   20.020s | 106.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-9.smt2-3.smt2 |   20.020s | 91.648MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-70.smt2-3.smt2 |   20.020s | 33.392MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LeftistHeap.scala-8.smt2-1.smt2 |   20.020s | 108.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-10.smt2-1.smt2 |   20.020s | 166.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-muDot2.scala-41.smt2-2.smt2 |   20.020s | 138.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-27.smt2-3.smt2 |   20.020s | 92.064MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SearchLinkedList.scala-7.smt2 |   20.020s | 112.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-5.smt2-1.smt2 |   20.020s | 83.732MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SecondsToTime.scala-5.smt2-2.smt2 |   20.020s | 111.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-4.smt2-2.smt2 |   20.020s | 79.236MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-1.smt2-2.smt2 |   20.020s | 82.264MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-29.smt2-2.smt2 |   20.020s | 119.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ListOperations.scala-3.smt2-1.smt2 |   20.020s | 84.404MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-73.smt2-3.smt2 |   20.020s | 96.776MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-18.smt2-2.smt2 |   20.020s | 79.616MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LambdaEval.scala-6.smt2-2.smt2 |   20.020s | 140.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-4.smt2 |   20.021s | 159.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-92.smt2 |   20.021s | 31.576MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-8.smt2 |   20.021s | 199.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-40.smt2-3.smt2 |   20.021s | 30.448MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-24.smt2-3.smt2 |   20.021s | 178.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-43.smt2-3.smt2 |   20.021s | 30.464MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-21.smt2-1.smt2 |   20.021s | 89.672MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-9.smt2-3.smt2 |   20.021s | 166.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SearchLinkedList.scala-7.smt2-1.smt2 |   20.021s | 34.5MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-38.smt2-1.smt2 |   20.021s | 29.268MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LambdaEval.scala-20.smt2-3.smt2 |   20.021s | 144.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ListOperations.scala-5.smt2 |   20.021s | 102.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-42.smt2 |   20.021s | 212.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-QuickSort.scala-28.smt2 |   20.021s | 143.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-20.smt2-3.smt2 |   20.021s | 65.732MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-MutuallyRecursive.scala-1.smt2-1.smt2 |   20.021s | 111.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-14.smt2-3.smt2 |   20.021s | 123.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-32.smt2-1.smt2 |   20.021s | 141.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-19.smt2-3.smt2 |   20.021s | 103.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-21.smt2 |   20.022s | 134.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-17.smt2-2.smt2 |   20.022s | 43.32MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-13.smt2-1.smt2 |   20.022s | 35.428MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-10.smt2-2.smt2 |   20.022s | 158.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-21.smt2-2.smt2 |   20.022s | 104.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-12.smt2-2.smt2 |   20.022s | 30.772MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-HeapSort.scala-14.smt2 |   20.022s | 164.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-25.smt2-1.smt2 |   20.022s | 172.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-39.smt2-1.smt2 |   20.022s | 40.452MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-5.smt2 |   20.023s | 164.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-17.smt2 |   20.023s | 155.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-5.smt2-1.smt2 |   20.023s | 101.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-36.smt2-3.smt2 |   20.023s | 31.856MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ListOperations.scala-13.smt2 |   20.023s | 115.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-90.smt2 |   20.023s | 172.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-muDot2.scala-43.smt2 |   20.023s | 179.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SearchLinkedList.scala-1.smt2 |   20.023s | 187.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-14.smt2-1.smt2 |   20.023s | 94.232MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-68.smt2-2.smt2 |   20.023s | 156.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PositiveMap.scala-2.smt2-3.smt2 |   20.023s | 181.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-52.smt2-1.smt2 |   20.023s | 210.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-3.smt2-3.smt2 |   20.023s | 35.848MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-88.smt2 |   20.024s | 35.3MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-BinarySearchTree.scala-1.smt2 |   20.024s | 56.976MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-43.smt2 |   20.024s | 32.372MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-85.smt2-1.smt2 |   20.024s | 31.784MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-96.smt2-2.smt2 |   20.024s | 37.304MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-64.smt2-1.smt2 |   20.024s | 153.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-9.smt2-1.smt2 |   20.024s | 145.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-29.smt2-2.smt2 |   20.024s | 39.432MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-97.smt2-3.smt2 |   20.024s | 30.816MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-70.smt2-1.smt2 |   20.024s | 31.82MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-89.smt2-1.smt2 |   20.024s | 28.624MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PositiveMap.scala-2.smt2 |   20.024s | 114.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-41.smt2 |   20.024s | 199.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-27.smt2-1.smt2 |   20.024s | 169.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-47.smt2-2.smt2 |   20.024s | 160.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-28.smt2-1.smt2 |   20.024s | 175.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-96.smt2-2.smt2 |   20.024s | 55.3MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-61.smt2-3.smt2 |   20.024s | 185.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-55.smt2-3.smt2 |   20.024s | 188.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-3.smt2-3.smt2 |   20.024s | 82.852MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-12.smt2-1.smt2 |   20.024s | 29.84MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-38.smt2-1.smt2 |   20.024s | 175.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-44.smt2-2.smt2 |   20.024s | 217.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-100.smt2 |   20.025s | 33.74MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-89.smt2 |   20.025s | 28.48MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-17.smt2 |   20.025s | 286.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-9.smt2 |   20.025s | 179.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SimpInterpret.scala-3.smt2 |   20.025s | 218.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SumAndMax.scala-4.smt2-1.smt2 |   20.025s | 145.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-14.smt2-3.smt2 |   20.025s | 150.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-13.smt2-3.smt2 |   20.025s | 158.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-93.smt2-2.smt2 |   20.025s | 31.672MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-15.smt2-2.smt2 |   20.025s | 212.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-9.smt2-1.smt2 |   20.025s | 168.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-TwoSizeFunctions.scala-4.smt2-3.smt2 |   20.025s | 36.356MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SimpInterpret.scala-3.smt2-1.smt2 |   20.025s | 215.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BitsTricks.scala-13.smt2-2.smt2 |   20.025s | 38.176MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-86.smt2 |   20.025s | 218.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-AmortizedQueue.scala-1.smt2 |   20.025s | 187.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-110.smt2 |   20.025s | 215.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-LambdaEval.scala-6.smt2 |   20.025s | 167.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-62.smt2 |   20.025s | 145.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-85.smt2 |   20.025s | 201.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-55.smt2-1.smt2 |   20.025s | 189.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-18.smt2-2.smt2 |   20.025s | 310.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-5.smt2-3.smt2 |   20.025s | 87.748MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-17.smt2-2.smt2 |   20.025s | 205.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-LambdaEval.scala-6.smt2 |   20.026s | 177.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-10.smt2 |   20.026s | 35.172MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-57.smt2 |   20.026s | 276.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-84.smt2 |   20.026s | 30.552MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BinarySearchTree.scala-1.smt2-3.smt2 |   20.026s | 57.44MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-79.smt2-3.smt2 |   20.026s | 32.688MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-83.smt2-3.smt2 |   20.026s | 30.944MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-114.smt2-1.smt2 |   20.026s | 30.532MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-2.smt2-1.smt2 |   20.026s | 155.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-25.smt2-3.smt2 |   20.026s | 98.736MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-104.smt2-3.smt2 |   20.026s | 30.348MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-muDot2.scala-41.smt2-3.smt2 |   20.026s | 235.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-16.smt2 |   20.026s | 176.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-43.smt2 |   20.026s | 211.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-55.smt2 |   20.026s | 324.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-64.smt2 |   20.026s | 188.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-1.smt2-1.smt2 |   20.026s | 166.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-4.smt2-3.smt2 |   20.026s | 84.872MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-MutuallyRecursive.scala-1.smt2-2.smt2 |   20.026s | 113.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-43.smt2-1.smt2 |   20.026s | 213.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-26.smt2-1.smt2 |   20.026s | 179.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SearchLinkedList.scala-1.smt2-3.smt2 |   20.026s | 214.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-8.smt2-2.smt2 |   20.026s | 290.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-60.smt2-3.smt2 |   20.026s | 299.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-56.smt2-1.smt2 |   20.026s | 189.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-42.smt2-3.smt2 |   20.026s | 225.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-15.smt2-1.smt2 |   20.026s | 268.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-5.smt2 |   20.027s | 41.048MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-4.smt2 |   20.027s | 279.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-65.smt2 |   20.027s | 277.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-TwoSizeFunctions.scala-1.smt2 |   20.027s | 85.956MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Interpreter.scala-3.smt2-3.smt2 |   20.027s | 249.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SearchLinkedList.scala-4.smt2-2.smt2 |   20.027s | 36.5MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-QuickSort.scala-22.smt2-3.smt2 |   20.027s | 40.88MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SimpInterpret.scala-3.smt2-3.smt2 |   20.027s | 232.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-80.smt2-2.smt2 |   20.027s | 28.512MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LambdaEval.scala-6.smt2-2.smt2 |   20.027s | 214.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LambdaEval.scala-20.smt2-2.smt2 |   20.027s | 140.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SecondsToTime.scala-1.smt2 |   20.027s | 197.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-2.smt2-2.smt2 |   20.027s | 261.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SumAndMax.scala-4.smt2-1.smt2 |   20.027s | 103.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SortedNDList.scala-3.smt2-3.smt2 |   20.027s | 56.74MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Parser.scala-3.smt2-3.smt2 |   20.027s | 57.424MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BinarySearchTree.scala-1.smt2-1.smt2 |   20.027s | 39.752MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-8.smt2 |   20.028s | 161.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-16.smt2 |   20.028s | 33.544MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-82.smt2 |   20.028s | 54.556MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-13.smt2 |   20.028s | 57.552MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-25.smt2-2.smt2 |   20.028s | 103.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-muDot2.scala-41.smt2-1.smt2 |   20.028s | 128.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-59.smt2-2.smt2 |   20.028s | 36.728MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-41.smt2-1.smt2 |   20.028s | 29.068MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-115.smt2-3.smt2 |   20.028s | 30.18MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-80.smt2-1.smt2 |   20.028s | 53.488MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-2.smt2-3.smt2 |   20.028s | 287.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SecondsToTime.scala-5.smt2 |   20.028s | 181.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-8.smt2 |   20.028s | 264.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-8.smt2-3.smt2 |   20.028s | 263.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-4.smt2-2.smt2 |   20.028s | 255.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-25.smt2-3.smt2 |   20.028s | 114.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SecondsToTime.scala-5.smt2-1.smt2 |   20.028s | 99.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-13.smt2-3.smt2 |   20.028s | 63.648MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-44.smt2-1.smt2 |   20.028s | 357.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-BinaryTrie.scala-1.smt2 |   20.029s | 88.344MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-102.smt2 |   20.029s | 28.06MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-1.smt2 |   20.029s | 86.516MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-96.smt2 |   20.029s | 92.532MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-TwoSizeFunctions.scala-7.smt2 |   20.029s | 47.132MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-97.smt2 |   20.029s | 34.152MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SecondsToTime.scala-1.smt2 |   20.029s | 98.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Parser.scala-5.smt2 |   20.029s | 106.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SearchLinkedList.scala-4.smt2-1.smt2 |   20.029s | 35.108MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-80.smt2-3.smt2 |   20.029s | 28.728MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-1.smt2-2.smt2 |   20.029s | 286.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-103.smt2-2.smt2 |   20.029s | 27.824MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-15.smt2-1.smt2 |   20.029s | 315.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-111.smt2-3.smt2 |   20.029s | 33.512MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-44.smt2-1.smt2 |   20.029s | 31.112MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ListOperations.scala-1.smt2 |   20.029s | 187.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-38.smt2 |   20.029s | 289.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-91.smt2 |   20.029s | 32.664MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SearchLinkedList.scala-1.smt2-2.smt2 |   20.029s | 64.004MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-79.smt2-3.smt2 |   20.029s | 170.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-64.smt2-1.smt2 |   20.029s | 189.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AbsFun.scala-6.smt2-2.smt2 |   20.029s | 161.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LambdaEval.scala-6.smt2-1.smt2 |   20.029s | 121.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-1.smt2-2.smt2 |   20.029s | 159.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SimpInterpret.scala-3.smt2-3.smt2 |   20.029s | 121.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-40.smt2-1.smt2 |   20.029s | 41.928MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-90.smt2-1.smt2 |   20.029s | 297.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-103.smt2 |   20.030s | 27.924MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-104.smt2-2.smt2 |   20.030s | 32.28MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PositiveMap.scala-2.smt2-3.smt2 |   20.030s | 57.064MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-14.smt2-1.smt2 |   20.030s | 103.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-113.smt2-2.smt2 |   20.030s | 30.696MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Interpreter.scala-3.smt2-2.smt2 |   20.030s | 298.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-87.smt2-3.smt2 |   20.030s | 29.644MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-102.smt2-3.smt2 |   20.030s | 28.676MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-19.smt2-1.smt2 |   20.030s | 283.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-2.smt2-3.smt2 |   20.030s | 283.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-60.smt2-1.smt2 |   20.030s | 33.196MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-10.smt2-1.smt2 |   20.030s | 32.452MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-102.smt2-2.smt2 |   20.030s | 28.952MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-67.smt2 |   20.030s | 239.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-HeapSort.scala-1.smt2 |   20.030s | 84.176MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-59.smt2-3.smt2 |   20.030s | 293.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-16.smt2-3.smt2 |   20.030s | 311.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Lists5.scala-4.smt2-2.smt2 |   20.030s | 38.896MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-13.smt2 |   20.031s | 56.168MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-1.smt2 |   20.031s | 302.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-96.smt2-3.smt2 |   20.031s | 36.464MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-2.smt2-1.smt2 |   20.031s | 191.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-110.smt2-3.smt2 |   20.031s | 33.616MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-87.smt2 |   20.031s | 316.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Parser.scala-9.smt2 |   20.031s | 157.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-TwoSizeFunctions.scala-4.smt2-2.smt2 |   20.031s | 95.88MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-10.smt2-1.smt2 |   20.031s | 332.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-19.smt2-2.smt2 |   20.031s | 65.272MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SearchLinkedList.scala-7.smt2-3.smt2 |   20.031s | 117.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-1.smt2-2.smt2 |   20.031s | 64.844MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-41.smt2-3.smt2 |   20.031s | 346.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-14.smt2-2.smt2 |   20.031s | 50.292MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-TwoSizeFunctions.scala-4.smt2-1.smt2 |   20.031s | 92.772MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-1.smt2-3.smt2 |   20.031s | 175.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Parser.scala-9.smt2-1.smt2 |   20.031s | 235.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-42.smt2-2.smt2 |   20.032s | 29.656MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-10.smt2-3.smt2 |   20.032s | 38.612MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LeftistHeap.scala-13.smt2-1.smt2 |   20.032s | 100.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-98.smt2 |   20.032s | 328.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SecondsToTime.scala-3.smt2 |   20.032s | 98.096MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-110.smt2-2.smt2 |   20.032s | 217.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Interpreter.scala-3.smt2-2.smt2 |   20.032s | 135.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-21.smt2-2.smt2 |   20.032s | 244.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-MutuallyRecursive.scala-1.smt2-3.smt2 |   20.032s | 230.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-5.smt2-1.smt2 |   20.032s | 85.168MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-9.smt2-1.smt2 |   20.032s | 326.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-13.smt2-2.smt2 |   20.032s | 88.056MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-93.smt2 |   20.033s | 32.548MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-InsertionSort.scala-1.smt2 |   20.033s | 146.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-1.smt2 |   20.033s | 43.06MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SumAndMax.scala-4.smt2 |   20.033s | 145.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-9.smt2-3.smt2 |   20.033s | 347.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-1.smt2-2.smt2 |   20.033s | 296.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ListOperations.scala-1.smt2-1.smt2 |   20.033s | 86.256MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-92.smt2 |   20.033s | 278.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SearchLinkedList.scala-4.smt2 |   20.033s | 107.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-84.smt2 |   20.033s | 333.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-1.smt2-1.smt2 |   20.033s | 52.816MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-25.smt2-3.smt2 |   20.033s | 171.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-110.smt2-1.smt2 |   20.033s | 214.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-10.smt2-3.smt2 |   20.033s | 54.28MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AmortizedQueue.scala-1.smt2-3.smt2 |   20.033s | 273.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-22.smt2-2.smt2 |   20.033s | 83.404MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ListOperations.scala-5.smt2-3.smt2 |   20.033s | 79.508MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-17.smt2-1.smt2 |   20.033s | 91.744MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-1.smt2-3.smt2 |   20.033s | 55.68MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-87.smt2 |   20.034s | 28.708MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-2.smt2-2.smt2 |   20.034s | 335.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-9.smt2-3.smt2 |   20.034s | 159.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-9.smt2-2.smt2 |   20.034s | 294.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-95.smt2-1.smt2 |   20.034s | 26.936MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-40.smt2-3.smt2 |   20.034s | 35.736MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-1.smt2-3.smt2 |   20.034s | 252.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-108.smt2-3.smt2 |   20.034s | 320.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-3.smt2-1.smt2 |   20.034s | 30.752MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-14.smt2-2.smt2 |   20.034s | 325.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-5.smt2-1.smt2 |   20.034s | 334.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-13.smt2-1.smt2 |   20.034s | 76.664MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-87.smt2-3.smt2 |   20.034s | 316.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-80.smt2-1.smt2 |   20.034s | 92.368MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Parser.scala-1.smt2-1.smt2 |   20.034s | 53.564MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-13.smt2-2.smt2 |   20.034s | 263.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-90.smt2-2.smt2 |   20.034s | 99.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-TwoSizeFunctions.scala-1.smt2-2.smt2 |   20.034s | 76.252MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SecondsToTime.scala-5.smt2 |   20.035s | 97.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-25.smt2 |   20.035s | 289.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-90.smt2 |   20.035s | 30.572MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-79.smt2-1.smt2 |   20.035s | 37.828MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SimpInterpret.scala-3.smt2-2.smt2 |   20.035s | 220.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BinaryTrie.scala-5.smt2-1.smt2 |   20.035s | 130.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-TwoSizeFunctions.scala-4.smt2-1.smt2 |   20.035s | 92.4MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-116.smt2-1.smt2 |   20.035s | 34.176MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Parser.scala-3.smt2 |   20.035s | 111.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-65.smt2 |   20.035s | 337.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-HeapSort.scala-19.smt2 |   20.035s | 41.7MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AbsFun.scala-6.smt2-1.smt2 |   20.035s | 293.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Parser.scala-3.smt2-2.smt2 |   20.035s | 183.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-37.smt2-2.smt2 |   20.035s | 159.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-47.smt2-3.smt2 |   20.035s | 103.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-85.smt2-1.smt2 |   20.035s | 201.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-54.smt2-1.smt2 |   20.035s | 316.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-73.smt2-2.smt2 |   20.035s | 147.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-86.smt2-1.smt2 |   20.035s | 352.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LambdaEval.scala-6.smt2-3.smt2 |   20.035s | 125.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-95.smt2-2.smt2 |   20.035s | 321.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Parser.scala-3.smt2 |   20.036s | 32.136MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-45.smt2 |   20.036s | 156.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Map.scala-1.smt2-3.smt2 |   20.036s | 62.436MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-5.smt2-2.smt2 |   20.036s | 90.968MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-muDot2.scala-43.smt2-2.smt2 |   20.036s | 83.268MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SortedNDList.scala-3.smt2-3.smt2 |   20.036s | 51.048MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-57.smt2-2.smt2 |   20.036s | 156.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-5.smt2-1.smt2 |   20.036s | 168.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-3.smt2 |   20.036s | 78.784MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-100.smt2 |   20.036s | 337.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-4.smt2 |   20.036s | 301.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-96.smt2-3.smt2 |   20.036s | 147.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-14.smt2-2.smt2 |   20.036s | 113.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-13.smt2-1.smt2 |   20.036s | 117.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SumAndMax.scala-4.smt2-3.smt2 |   20.036s | 98.492MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Parser.scala-1.smt2-3.smt2 |   20.036s | 64.664MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-InsertionSort.scala-1.smt2-3.smt2 |   20.036s | 42.452MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-38.smt2-2.smt2 |   20.036s | 350.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-103.smt2-2.smt2 |   20.036s | 363.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-102.smt2-1.smt2 |   20.036s | 304.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ListOperations.scala-1.smt2-1.smt2 |   20.036s | 79.252MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-80.smt2-2.smt2 |   20.036s | 302.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-65.smt2-3.smt2 |   20.036s | 177.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-65.smt2-1.smt2 |   20.036s | 355.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-85.smt2-3.smt2 |   20.036s | 201.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-54.smt2-2.smt2 |   20.036s | 182.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-113.smt2 |   20.037s | 31.444MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-115.smt2 |   20.037s | 31.964MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-14.smt2-1.smt2 |   20.037s | 144.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-112.smt2-3.smt2 |   20.037s | 27.168MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BinaryTrie.scala-9.smt2-2.smt2 |   20.037s | 102.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-51.smt2-1.smt2 |   20.037s | 31.248MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-60.smt2-2.smt2 |   20.037s | 33.56MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-AVLTree.scala-14.smt2 |   20.037s | 123.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-muDot2.scala-43.smt2-1.smt2 |   20.037s | 173.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-87.smt2-1.smt2 |   20.037s | 325.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SortedNDList.scala-3.smt2-1.smt2 |   20.037s | 94.536MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-13.smt2-1.smt2 |   20.037s | 87.028MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-8.smt2-1.smt2 |   20.037s | 63.692MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-38.smt2-3.smt2 |   20.037s | 299.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-4.smt2-1.smt2 |   20.037s | 74.416MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Parser.scala-9.smt2 |   20.038s | 102.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-13.smt2-3.smt2 |   20.038s | 354.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-1.smt2-1.smt2 |   20.038s | 310.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-13.smt2-1.smt2 |   20.038s | 160.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-20.smt2-3.smt2 |   20.038s | 163.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-38.smt2-3.smt2 |   20.038s | 32.532MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BinaryTrie.scala-3.smt2-3.smt2 |   20.038s | 98.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Interpreter.scala-3.smt2-1.smt2 |   20.038s | 228.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LeftistHeap.scala-8.smt2-3.smt2 |   20.038s | 97.44MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-AbsFun.scala-6.smt2 |   20.038s | 329.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-1.smt2 |   20.038s | 83.472MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-TwoSizeFunctions.scala-4.smt2 |   20.038s | 100.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-45.smt2 |   20.038s | 334.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-103.smt2-1.smt2 |   20.038s | 309.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ListOperations.scala-3.smt2-3.smt2 |   20.038s | 83.728MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-4.smt2-3.smt2 |   20.038s | 255.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-96.smt2-1.smt2 |   20.038s | 277.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-18.smt2-1.smt2 |   20.038s | 89.972MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-2.smt2-3.smt2 |   20.038s | 47.816MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-93.smt2-1.smt2 |   20.038s | 56.776MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-18.smt2-3.smt2 |   20.038s | 214.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-64.smt2-3.smt2 |   20.038s | 178.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-21.smt2-3.smt2 |   20.038s | 262.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-24.smt2 |   20.039s | 277.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-13.smt2 |   20.039s | 387.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-LambdaEval.scala-20.smt2 |   20.039s | 151.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LambdaEval.scala-20.smt2-1.smt2 |   20.039s | 138.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-112.smt2-2.smt2 |   20.039s | 27.44MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-8.smt2-1.smt2 |   20.039s | 359.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-106.smt2-1.smt2 |   20.039s | 34.076MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-4.smt2-2.smt2 |   20.039s | 157.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-5.smt2 |   20.039s | 259.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-63.smt2 |   20.039s | 191.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-4.smt2-3.smt2 |   20.039s | 78.848MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-18.smt2-1.smt2 |   20.039s | 189.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-68.smt2-1.smt2 |   20.039s | 98.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-1.smt2-3.smt2 |   20.039s | 89.092MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Interpreter.scala-3.smt2-1.smt2 |   20.039s | 89.964MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-10.smt2-3.smt2 |   20.039s | 346.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ListOperations.scala-10.smt2-1.smt2 |   20.039s | 116.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-109.smt2 |   20.040s | 29.124MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-4.smt2-3.smt2 |   20.040s | 365.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-17.smt2-1.smt2 |   20.040s | 182.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-47.smt2-1.smt2 |   20.040s | 31.648MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Map.scala-1.smt2-2.smt2 |   20.040s | 67.788MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-110.smt2-2.smt2 |   20.040s | 33.192MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-QuickSort.scala-32.smt2 |   20.040s | 143.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-100.smt2-2.smt2 |   20.040s | 185.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-107.smt2-1.smt2 |   20.040s | 37.612MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-27.smt2-2.smt2 |   20.040s | 118.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-107.smt2-2.smt2 |   20.040s | 54.112MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SecondsToTime.scala-8.smt2 |   20.041s | 75.872MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-56.smt2 |   20.041s | 158.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SecondsToTime.scala-3.smt2 |   20.041s | 154.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-13.smt2-3.smt2 |   20.041s | 59.996MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-18.smt2-2.smt2 |   20.041s | 166.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-16.smt2-1.smt2 |   20.041s | 321.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-42.smt2-1.smt2 |   20.041s | 330.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-93.smt2-2.smt2 |   20.041s | 295.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-92.smt2-3.smt2 |   20.041s | 40.276MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-98.smt2-3.smt2 |   20.041s | 320.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-106.smt2-3.smt2 |   20.041s | 83.188MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-59.smt2 |   20.042s | 57.44MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Naturals.scala-5.smt2-3.smt2 |   20.042s | 25.708MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-20.smt2-1.smt2 |   20.042s | 565.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BinaryTrie.scala-5.smt2-3.smt2 |   20.042s | 130.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-8.smt2 |   20.042s | 141.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-MutuallyRecursive.scala-1.smt2 |   20.042s | 145.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-InsertionSort.scala-1.smt2 |   20.042s | 347.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Map.scala-1.smt2-3.smt2 |   20.042s | 56.512MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-103.smt2-3.smt2 |   20.042s | 446.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-19.smt2-2.smt2 |   20.042s | 67.128MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-12.smt2-2.smt2 |   20.043s | 379.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Map.scala-1.smt2-1.smt2 |   20.043s | 76.56MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-7.smt2-3.smt2 |   20.043s | 428.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LambdaEval.scala-6.smt2-3.smt2 |   20.043s | 212.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-82.smt2-2.smt2 |   20.043s | 54.572MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-82.smt2 |   20.043s | 154.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-TwoSizeFunctions.scala-7.smt2 |   20.043s | 133.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-22.smt2-1.smt2 |   20.043s | 75.344MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-TwoSizeFunctions.scala-1.smt2-1.smt2 |   20.043s | 77.524MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Map.scala-2.smt2-1.smt2 |   20.043s | 64.588MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-82.smt2-3.smt2 |   20.043s | 87.316MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ListOperations.scala-10.smt2-3.smt2 |   20.043s | 100.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SimpInterpret.scala-3.smt2-2.smt2 |   20.043s | 151.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-17.smt2-3.smt2 |   20.043s | 124.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-muDot2.scala-41.smt2-2.smt2 |   20.043s | 107.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-92.smt2-1.smt2 |   20.043s | 278.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-2.smt2-3.smt2 |   20.043s | 60.796MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-LeftistHeap.scala-13.smt2 |   20.044s | 146.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-2.smt2 |   20.044s | 393.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-79.smt2 |   20.044s | 336.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-93.smt2 |   20.044s | 270.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-109.smt2 |   20.044s | 335.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-69.smt2-2.smt2 |   20.044s | 235.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-28.smt2-2.smt2 |   20.044s | 107.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-56.smt2-3.smt2 |   20.044s | 340.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-86.smt2-2.smt2 |   20.044s | 220.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-9.smt2-3.smt2 |   20.044s | 333.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-7.smt2-1.smt2 |   20.044s | 334.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-52.smt2-2.smt2 |   20.044s | 221.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-88.smt2-3.smt2 |   20.044s | 175.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-60.smt2-2.smt2 |   20.044s | 93.244MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-HeapSort.scala-29.smt2 |   20.045s | 143.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-BinaryTrie.scala-5.smt2-2.smt2 |   20.045s | 126.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-95.smt2-2.smt2 |   20.045s | 31.252MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-13.smt2-2.smt2 |   20.045s | 160.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-99.smt2 |   20.045s | 569.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-17.smt2 |   20.045s | 78.568MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-2.smt2 |   20.045s | 269.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-12.smt2-2.smt2 |   20.045s | 350.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-20.smt2-1.smt2 |   20.045s | 259.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-muDot2.scala-43.smt2-3.smt2 |   20.045s | 172.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-60.smt2-1.smt2 |   20.045s | 33.268MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-95.smt2-3.smt2 |   20.045s | 306.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-TwoSizeFunctions.scala-1.smt2-3.smt2 |   20.045s | 47.856MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-95.smt2-1.smt2 |   20.045s | 345.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-1.smt2-3.smt2 |   20.046s | 284.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-8.smt2-3.smt2 |   20.046s | 451.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-96.smt2 |   20.046s | 267.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SecondsToTime.scala-3.smt2-1.smt2 |   20.046s | 67.872MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SecondsToTime.scala-8.smt2-1.smt2 |   20.046s | 98.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AbsFun.scala-6.smt2-3.smt2 |   20.046s | 178.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-87.smt2-2.smt2 |   20.046s | 312.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-102.smt2-3.smt2 |   20.046s | 379.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-TwoSizeFunctions.scala-4.smt2-3.smt2 |   20.046s | 61.168MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-19.smt2-2.smt2 |   20.047s | 189.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-18.smt2-3.smt2 |   20.047s | 158.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-24.smt2-1.smt2 |   20.047s | 564.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-10.smt2-3.smt2 |   20.047s | 444.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-88.smt2-1.smt2 |   20.047s | 32.192MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-15.smt2-3.smt2 |   20.047s | 293.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-91.smt2-1.smt2 |   20.047s | 35.036MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-79.smt2-1.smt2 |   20.047s | 336.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-82.smt2-2.smt2 |   20.047s | 154.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-28.smt2-1.smt2 |   20.048s | 460.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-108.smt2 |   20.048s | 412.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-LambdaEval.scala-60.smt2 |   20.048s | 412.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ListOperations.scala-3.smt2 |   20.048s | 165.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-21.smt2-1.smt2 |   20.048s | 267.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-14.smt2-3.smt2 |   20.048s | 356.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-82.smt2-1.smt2 |   20.048s | 91.212MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-17.smt2-3.smt2 |   20.048s | 179.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-3.smt2-3.smt2 |   20.049s | 298.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-4.smt2-1.smt2 |   20.049s | 283.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-3.smt2-2.smt2 |   20.049s | 299.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-17.smt2-1.smt2 |   20.049s | 136.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-52.smt2 |   20.049s | 219.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-44.smt2 |   20.049s | 230.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-29.smt2-3.smt2 |   20.049s | 114.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ListOperations.scala-5.smt2-2.smt2 |   20.049s | 98.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-15.smt2-3.smt2 |   20.049s | 266.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Parser.scala-5.smt2-2.smt2 |   20.049s | 138.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-64.smt2-2.smt2 |   20.049s | 325.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-24.smt2-1.smt2 |   20.049s | 287.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-9.smt2-1.smt2 |   20.049s | 86.508MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-19.smt2-3.smt2 |   20.049s | 175.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-27.smt2-2.smt2 |   20.050s | 501.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SearchLinkedList.scala-4.smt2-1.smt2 |   20.050s | 67.756MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-4.smt2-1.smt2 |   20.050s | 257.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-44.smt2-3.smt2 |   20.050s | 218.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-14.smt2-2.smt2 |   20.051s | 135.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-without_inducts.scala-116.smt2-2.smt2 |   20.051s | 34.832MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-15.smt2-3.smt2 |   20.051s | 430.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-1.smt2-3.smt2 |   20.051s | 324.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-59.smt2 |   20.051s | 524.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-84.smt2-3.smt2 |   20.051s | 427.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-15.smt2-1.smt2 |   20.051s | 293.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-76.smt2-2.smt2 |   20.051s | 88.28MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-2.smt2-3.smt2 |   20.051s | 261.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-88.smt2-1.smt2 |   20.051s | 110.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-9.smt2-1.smt2 |   20.052s | 564.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-102.smt2 |   20.052s | 365.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-13.smt2-3.smt2 |   20.052s | 405.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-66.smt2-1.smt2 |   20.052s | 359.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-41.smt2-2.smt2 |   20.052s | 347.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SecondsToTime.scala-5.smt2-3.smt2 |   20.052s | 98.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-43.smt2-3.smt2 |   20.052s | 339.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-1.smt2-3.smt2 |   20.052s | 89.184MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-2.smt2-2.smt2 |   20.053s | 270.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-7.smt2-1.smt2 |   20.053s | 329.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-98.smt2-2.smt2 |   20.053s | 588.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-3.smt2-2.smt2 |   20.053s | 273.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-2.smt2-1.smt2 |   20.053s | 263.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LambdaEval.scala-20.smt2-3.smt2 |   20.053s | 393.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-27.smt2-1.smt2 |   20.054s | 526.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-20.smt2-3.smt2 |   20.054s | 540.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-95.smt2 |   20.054s | 345.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-51.smt2-3.smt2 |   20.054s | 336.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-19.smt2-1.smt2 |   20.054s | 296.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-45.smt2-1.smt2 |   20.054s | 307.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-14.smt2-2.smt2 |   20.055s | 354.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-4.smt2-1.smt2 |   20.055s | 273.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-13.smt2-3.smt2 |   20.055s | 82.324MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-muDot2.scala-43.smt2-2.smt2 |   20.055s | 181.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-84.smt2-1.smt2 |   20.055s | 244.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-32.smt2-3.smt2 |   20.055s | 107.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-63.smt2-1.smt2 |   20.055s | 414.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-26.smt2-2.smt2 |   20.055s | 119.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Parser.scala-5.smt2-1.smt2 |   20.055s | 27.58MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-14.smt2-3.smt2 |   20.056s | 338.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-MutuallyRecursive.scala-1.smt2-3.smt2 |   20.056s | 430.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-24.smt2-2.smt2 |   20.056s | 326.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SumAndMax.scala-4.smt2 |   20.056s | 347.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-109.smt2-1.smt2 |   20.056s | 308.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-110.smt2-3.smt2 |   20.056s | 357.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-muDot2.scala-41.smt2 |   20.057s | 389.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-13.smt2 |   20.057s | 254.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-AVLTree.scala-17.smt2 |   20.057s | 93.088MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-54.smt2 |   20.057s | 344.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-70.smt2-3.smt2 |   20.057s | 138.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-16.smt2 |   20.058s | 592.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-29.smt2-1.smt2 |   20.058s | 341.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-25.smt2-1.smt2 |   20.058s | 684.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-1.smt2 |   20.058s | 158.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-13.smt2-2.smt2 |   20.058s | 446.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-13.smt2-2.smt2 |   20.058s | 139.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-24.smt2-3.smt2 |   20.058s | 261.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-55.smt2-2.smt2 |   20.058s | 349.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-QuickSort.scala-27.smt2-3.smt2 |   20.058s | 109.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-12.smt2-3.smt2 |   20.059s | 718.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-LambdaEval.scala-20.smt2 |   20.059s | 394.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ForElimination.scala-2.smt2 |   20.059s | 83.248MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AmortizedQueue.scala-1.smt2-2.smt2 |   20.059s | 47.236MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-27.smt2 |   20.060s | 406.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-13.smt2-2.smt2 |   20.060s | 378.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-3.smt2-3.smt2 |   20.060s | 262.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LambdaEval.scala-20.smt2-1.smt2 |   20.061s | 352.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-80.smt2-3.smt2 |   20.061s | 520.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-12.smt2-3.smt2 |   20.061s | 565.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-41.smt2-1.smt2 |   20.061s | 326.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-103.smt2 |   20.062s | 365.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-84.smt2-2.smt2 |   20.062s | 462.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-78.smt2-1.smt2 |   20.063s | 544.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-13.smt2-1.smt2 |   20.063s | 266.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-29.smt2-3.smt2 |   20.064s | 642.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AVLTree.scala-24.smt2-1.smt2 |   20.064s | 293.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-18.smt2-2.smt2 |   20.064s | 753.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-108.smt2-2.smt2 |   20.064s | 362.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-16.smt2-1.smt2 |   20.064s | 178.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-LambdaEval.scala-6.smt2-1.smt2 |   20.065s | 196.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ForElimination.scala-9.smt2-2.smt2 |   20.065s | 162.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-21.smt2-3.smt2 |   20.065s | 562.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ForElimination.scala-17.smt2-3.smt2 |   20.065s | 72.216MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-47.smt2-1.smt2 |   20.066s | 175.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-8.smt2-2.smt2 |   20.068s | 487.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-42.smt2-2.smt2 |   20.068s | 325.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-83.smt2-2.smt2 |   20.069s | 629.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LambdaEval.scala-20.smt2-2.smt2 |   20.069s | 668.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-21.smt2-1.smt2 |   20.070s | 680.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-92.smt2-2.smt2 |   20.070s | 507.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-25.smt2-3.smt2 |   20.071s | 655.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-26.smt2-3.smt2 |   20.071s | 613.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-52.smt2-3.smt2 |   20.071s | 329.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-90.smt2-3.smt2 |   20.072s | 311.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-83.smt2-3.smt2 |   20.073s | 1139.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-21.smt2-3.smt2 |   20.073s | 537.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-43.smt2-2.smt2 |   20.074s | 324.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-98.smt2-1.smt2 |   20.074s | 591.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-PropositionalLogic.scala-20.smt2-3.smt2 |   20.074s | 252.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-8.smt2 |   20.075s | 901.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-14.smt2-2.smt2 |   20.075s | 613.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-14.smt2-3.smt2 |   20.075s | 630.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-24.smt2-3.smt2 |   20.076s | 626.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-83.smt2-1.smt2 |   20.076s | 508.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-SemanticsPreservation.scala-13.smt2-1.smt2 |   20.080s | 680.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-78.smt2 |   20.080s | 566.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-HeapSort.scala-29.smt2 |   20.083s | 606.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-97.smt2-1.smt2 |   20.083s | 651.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-66.smt2-3.smt2 |   20.083s | 392.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-6.smt2 |   20.084s | 560.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-15.smt2-3.smt2 |   20.084s | 674.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-85.smt2-2.smt2 |   20.084s | 343.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-19.smt2-1.smt2 |   20.084s | 1165.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-4.smt2-3.smt2 |   20.085s | 793.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-97.smt2 |   20.086s | 790.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-7.smt2-3.smt2 |   20.086s | 342.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-4.smt2-2.smt2 |   20.087s | 795.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-MutuallyRecursive.scala-1.smt2 |   20.088s | 897.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-54.smt2-3.smt2 |   20.088s | 349.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-99.smt2-3.smt2 |   20.089s | 675.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-4.smt2-2.smt2 |   20.090s | 293.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-21.smt2-1.smt2 |   20.092s | 564.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-108.smt2-1.smt2 |   20.094s | 412.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-16.smt2-3.smt2 |   20.096s | 626.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-51.smt2 |   20.097s | 1353.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-37.smt2-3.smt2 |   20.099s | 989.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-13.smt2-1.smt2 |   20.100s | 506.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-99.smt2-2.smt2 |   20.102s | 685.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-4.smt2 |   20.103s | 847.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-8.smt2-1.smt2 |   20.103s | 678.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-5.smt2-2.smt2 |   20.103s | 898.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-67.smt2-1.smt2 |   20.104s | 963.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-59.smt2-1.smt2 |   20.105s | 1305.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-HeapSort.scala-21.smt2 |   20.107s | 1185.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-100.smt2-3.smt2 |   20.108s | 1353.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-PropositionalLogic.scala-19.smt2-3.smt2 |   20.109s | 729.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-56.smt2 |   20.109s | 1319.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-48.smt2-2.smt2 |   20.109s | 714.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-61.smt2 |   20.110s | 1363.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-1.smt2-2.smt2 |   20.111s | 264.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-79.smt2-2.smt2 |   20.113s | 291.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-97.smt2-3.smt2 |   20.113s | 800.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ListOperations.scala-16.smt2-3.smt2 |   20.115s | 1079.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-51.smt2-1.smt2 |   20.115s | 626.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-69.smt2 |   20.116s | 296.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Naturals.scala-5.smt2-3.smt2 |   20.116s | 142.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-19.smt2-3.smt2 |   20.118s | 969.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-25.smt2-1.smt2 |   20.120s | 1185.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-67.smt2-3.smt2 |   20.120s | 973.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-50.smt2-3.smt2 |   20.124s | 1319.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-113.smt2 |   20.126s | 1343.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BitsTricks.scala-19.smt2-2.smt2 |   20.126s | 1204.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-13.smt2 |   20.128s | 1268.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-57.smt2 |   20.129s | 1371.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ListOperations.scala-16.smt2-1.smt2 |   20.129s | 1252.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-83.smt2 |   20.131s | 1319.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SortedList.scala-1.smt2-3.smt2 |   20.133s | 962.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-99.smt2-1.smt2 |   20.133s | 732.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-100.smt2-1.smt2 |   20.134s | 1329.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-3.smt2-2.smt2 |   20.135s | 81.164MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-50.smt2-1.smt2 |   20.140s | 1561.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-102.smt2-2.smt2 |   20.141s | 811.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-48.smt2-3.smt2 |   20.143s | 1398.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-13.smt2-3.smt2 |   20.144s | 1268.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-ListOperations.scala-16.smt2-2.smt2 |   20.145s | 1416.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-ListOperations.scala-16.smt2 |   20.146s | 1274.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-SemanticsPreservation.scala-15.smt2-2.smt2 |   20.148s | 400.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ArrayBinarySearch.scala-1.smt2-2.smt2 |   20.150s | 1704.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-25.smt2-3.smt2 |   20.153s | 890.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-53.smt2-1.smt2 |   20.154s | 1456.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-48.smt2 |   20.158s | 1337.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-58.smt2-2.smt2 |   20.158s | 1260.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-48.smt2-1.smt2 |   20.166s | 1364.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-101.smt2-1.smt2 |   20.171s | 1503.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-59.smt2-2.smt2 |   20.174s | 1924.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-6.smt2-2.smt2 |   20.183s | 1967.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-97.smt2-2.smt2 |   20.184s | 2460.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-53.smt2 |   20.187s | 2515.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-6.smt2-3.smt2 |   20.188s | 1719.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-9.smt2-2.smt2 |   20.205s | 1893.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-9.smt2-1.smt2 |   20.207s | 1843.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-57.smt2-1.smt2 |   20.222s | 2695.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-14.smt2-1.smt2 |   20.227s | 2263.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-8.smt2-3.smt2 |   20.229s | 2051.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-58.smt2-3.smt2 |   20.230s | 2545.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-58.smt2-1.smt2 |   20.236s | 2591.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-37.smt2-1.smt2 |   20.242s | 2670.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-57.smt2-3.smt2 |   20.244s | 2694.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-51.smt2-2.smt2 |   20.251s | 2218.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-101.smt2-3.smt2 |   20.252s | 2845.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-9.smt2 |   20.257s | 1890.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-101.smt2-2.smt2 |   20.257s | 2908.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-6.smt2-1.smt2 |   20.262s | 3099.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-101.smt2 |   20.278s | 2535.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-ArrayBinarySearch.scala-1.smt2 |   20.284s | 3348.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-AbsFun.scala-4.smt2-1.smt2 |   20.286s | 1969.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-61.smt2-1.smt2 |   20.294s | 2256.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-MutuallyRecursive.scala-1.smt2-2.smt2 |   20.295s | 3122.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-HeapSort.scala-25.smt2 |   20.302s | 3701.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-5.smt2-2.smt2 |   20.303s | 3120.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-67.smt2-2.smt2 |   20.318s | 3048.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-115.smt2 |   20.331s | 3723.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-36.smt2-2.smt2 |   20.332s | 2652.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-36.smt2 |   20.333s | 4797.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-89.smt2-2.smt2 |   20.335s | 4045.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-81.smt2-1.smt2 |   20.338s | 3339.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-114.smt2-1.smt2 |   20.339s | 3851.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ArrayBinarySearch.scala-1.smt2-3.smt2 |   20.340s | 3349.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-25.smt2-2.smt2 |   20.342s | 3553.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-116.smt2 |   20.349s | 3704.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-89.smt2 |   20.349s | 4352.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-HeapSort.scala-9.smt2 |   20.353s | 3794.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-5.smt2-3.smt2 |   20.358s | 3453.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-89.smt2-1.smt2 |   20.360s | 4522.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-36.smt2-1.smt2 |   20.361s | 4762.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-9.smt2-3.smt2 |   20.362s | 4059.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-81.smt2 |   20.364s | 4501.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-111.smt2-2.smt2 |   20.364s | 4317.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-71.smt2-1.smt2 |   20.365s | 4581.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-111.smt2-1.smt2 |   20.371s | 4316.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-ArrayBinarySearch.scala-1.smt2-1.smt2 |   20.378s | 3343.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-81.smt2-2.smt2 |   20.378s | 4439.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-69.smt2-3.smt2 |   20.380s | 4347.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Compiler.scala-7.smt2-3.smt2 |   20.386s | 4161.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-105.smt2-1.smt2 |   20.387s | 3806.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-116.smt2-3.smt2 |   20.390s | 3710.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-72.smt2-1.smt2 |   20.392s | 4797.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-81.smt2-3.smt2 |   20.392s | 4490.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-104.smt2-3.smt2 |   20.397s | 4262.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-112.smt2-2.smt2 |   20.400s | 4599.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-116.smt2-1.smt2 |   20.401s | 3938.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-104.smt2 |   20.404s | 3889.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-114.smt2 |   20.408s | 3985.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-105.smt2-2.smt2 |   20.411s | 3850.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-115.smt2-3.smt2 |   20.412s | 3811.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-115.smt2-2.smt2 |   20.412s | 3900.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-57.smt2-2.smt2 |   20.413s | 2692.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-116.smt2-2.smt2 |   20.423s | 5893.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-72.smt2-3.smt2 |   20.430s | 4724.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-111.smt2-3.smt2 |   20.430s | 4479.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-36.smt2-3.smt2 |   20.437s | 4765.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-5.smt2-3.smt2 |   20.439s | 4543.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-8.smt2-2.smt2 |   20.439s | 3667.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-105.smt2-3.smt2 |   20.443s | 4284.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-72.smt2-2.smt2 |   20.449s | 5099.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Compiler.scala-7.smt2-1.smt2 |   20.458s | 5710.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-AVLTree.scala-24.smt2 |   20.469s | 4915.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-114.smt2-2.smt2 |   20.472s | 5437.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-104.smt2-1.smt2 |   20.475s | 4533.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-105.smt2 |   20.482s | 3900.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-AVLTree.scala-27.smt2 |   20.489s | 4703.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-111.smt2 |   20.491s | 4452.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-27.smt2-3.smt2 |   20.500s | 4639.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-27.smt2-2.smt2 |   20.508s | 4590.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-113.smt2-3.smt2 |   20.512s | 5269.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-115.smt2-1.smt2 |   20.517s | 3723.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-9.smt2-1.smt2 |   20.527s | 4785.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-24.smt2-1.smt2 |   20.531s | 4640.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/wo_fd_vcs_wdf/2.5-cvc4-Compiler.scala-7.smt2 |   20.539s | 6096.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Compiler.scala-7.smt2-3.smt2 |   20.539s | 5549.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-104.smt2-2.smt2 |   20.542s | 3812.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-113.smt2-2.smt2 |   20.558s | 4877.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-24.smt2-2.smt2 |   20.569s | 4689.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-HeapSort.scala-9.smt2-2.smt2 |   20.580s | 7008.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-Compiler.scala-7.smt2 |   20.585s | 5710.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-113.smt2-1.smt2 |   20.586s | 5872.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-89.smt2-3.smt2 |   20.586s | 4659.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-Compiler.scala-7.smt2-2.smt2 |   20.606s | 5689.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo-wdf/mutant_wo_fd_vcs_wdf/2.5-cvc4-Compiler.scala-7.smt2-1.smt2 |   20.614s | 6176.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-LeftistHeap.scala-8.smt2-1.smt2 |   20.614s | 4749.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-24.smt2-3.smt2 |   20.615s | 4658.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-114.smt2-3.smt2 |   20.621s | 4190.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-5.smt2 |   20.633s | 6446.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-AVLTree.scala-27.smt2-1.smt2 |   20.643s | 4545.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-BinaryTrie.scala-5.smt2-1.smt2 |   20.693s | 6423.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-112.smt2-1.smt2 |   20.694s | 6543.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/mutant_wo_fd_vcs/2.5-cvc4-without_inducts.scala-112.smt2-3.smt2 |   20.705s | 6226.0MiB| timeout | 0 |  |  |
|non-incremental/AUFBVDTLIA/20172804-Barrett/rec-fun-ijcar2016/wo/wo_fd_vcs/2.5-cvc4-without_inducts.scala-112.smt2 |   20.750s | 7728.0MiB| timeout | 0 |  |  |
