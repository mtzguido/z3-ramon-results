# .

* SAT 0
* UNSAT 1272
* TIMEOUT 311
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/UFDTLIA.tar.zst?download=1 | Source list: quantifier_benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-UFDTLIA.tar.zst-do
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: c3f5365a95a7eac2419a2f95ff240909f275cc08
Z3 branch: c3f5365a95a7eac2419a2f95ff240909f275cc08
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/UFDTLIA.tar.zst?download=1
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
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal33.smt2 |    0.014s | 19.792MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal4.smt2 |    0.015s | 19.796MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__Domain_v.4.smt2 |    0.016s | 19.088MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal21.smt2 |    0.016s | 19.796MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal70.smt2 |    0.016s | 19.796MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__OffsetMap_v.2.smt2 |    0.017s | 19.284MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__Buffer_v.4.smt2 |    0.017s | 19.324MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal55.smt2 |    0.017s | 19.796MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg31.smt2 |    0.017s | 19.788MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__Buffer_v.3.smt2 |    0.018s | 19.16MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__MiniAllocator_v.8.smt2 |    0.018s | 19.392MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/disk__GenericDisk_v.10.smt2 |    0.018s | 19.264MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedSeq_v.3.smt2 |    0.018s | 19.204MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__SplitRequest_v.smt2 |    0.018s | 19.124MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__Buffer_v.15.smt2 |    0.018s | 19.316MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__Buffer_v.3.smt2 |    0.018s | 19.212MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal42.smt2 |    0.018s | 19.692MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal66.smt2 |    0.018s | 20.048MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/define.1.smt2 |    0.019s | 19.444MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/define.3.smt2 |    0.019s | 19.636MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__Buffer_v.16.smt2 |    0.019s | 19.588MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/disk__GenericDisk_v.5.smt2 |    0.019s | 19.2MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__MsgHistory_v.10.smt2 |    0.019s | 19.444MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/disk__GenericDisk_v.6.smt2 |    0.019s | 19.32MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__Domain_v.5.smt2 |    0.019s | 19.084MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__Domain_v.5.smt2 |    0.019s | 19.264MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__Domain_v.3.smt2 |    0.019s | 19.288MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__Utils_v.1.smt2 |    0.019s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg15.smt2 |    0.019s | 19.828MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg30.smt2 |    0.019s | 20.056MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal55.smt2 |    0.019s | 19.792MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal5.smt2 |    0.019s | 19.78MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal18.smt2 |    0.019s | 19.872MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal45.smt2 |    0.019s | 19.636MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal25.smt2 |    0.019s | 19.708MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal35.smt2 |    0.019s | 19.824MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal40.smt2 |    0.019s | 19.62MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/verismo/arch__rmp__def_s.3.smt2 |    0.020s | 19.304MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.12.smt2 |    0.020s | 19.448MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.4.smt2 |    0.020s | 19.312MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferSeq_v.5.smt2 |    0.020s | 19.34MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__MsgHistory_v.4.smt2 |    0.020s | 19.412MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBranch_v.1.smt2 |    0.020s | 19.34MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__MiniAllocator_v.11.smt2 |    0.020s | 19.32MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-pmemspec_t.1.smt2 |    0.020s | 19.276MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-disk__GenericDisk_v.8.smt2 |    0.020s | 19.3MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__Memtable_v.8.smt2 |    0.020s | 19.452MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__MsgHistory_v.10.smt2 |    0.020s | 19.436MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__MiniAllocator_v.14.smt2 |    0.020s | 19.444MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__MsgHistory_v.18.smt2 |    0.020s | 19.3MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal5.smt2 |    0.020s | 19.692MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal23.smt2 |    0.020s | 19.84MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal10.smt2 |    0.020s | 19.68MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal32.smt2 |    0.020s | 19.824MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/2019-Gleiss/non-interference/1-ni-assign-to-high.spec.smt2 |    0.020s | 19.84MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferSeq_v.1.smt2 |    0.021s | 19.436MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__MiniAllocator_v.20.smt2 |    0.021s | 19.432MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__MsgHistory_v.1.smt2 |    0.021s | 19.316MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferDisk_v.10.smt2 |    0.021s | 19.536MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__MiniAllocator_v.15.smt2 |    0.021s | 19.252MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__Memtable_v.6.smt2 |    0.021s | 19.316MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__MiniAllocator_v.20.smt2 |    0.021s | 19.448MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__AbstractJournal_v__AbstractJournal.2.smt2 |    0.021s | 19.352MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__MiniAllocator_v.12.smt2 |    0.021s | 19.332MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournal_v.19.smt2 |    0.021s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__MsgHistory_v.5.smt2 |    0.021s | 19.296MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal78.smt2 |    0.021s | 20.336MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferDisk_v.12.smt2 |    0.022s | 19.476MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__MsgHistory_v.9.smt2 |    0.022s | 19.332MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__MiniAllocator_v.21.smt2 |    0.022s | 19.344MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.8.smt2 |    0.022s | 19.54MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournal_v__PagedJournal.3.smt2 |    0.022s | 19.556MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-single_delivery_t.9.smt2 |    0.022s | 19.528MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__MiniAllocator_v.17.smt2 |    0.022s | 19.364MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBranch_v.1.smt2 |    0.022s | 19.444MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.1.smt2 |    0.022s | 19.404MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.8.smt2 |    0.022s | 19.388MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg35.smt2 |    0.022s | 19.796MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal24.smt2 |    0.022s | 19.804MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal16.smt2 |    0.022s | 19.648MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/verismo/arch__rmp__def_s.1.smt2 |    0.023s | 19.58MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/verismo/arch__rmp__def_s.4.smt2 |    0.023s | 19.532MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__AbstractJournal_v__AbstractJournal.2.smt2 |    0.023s | 19.376MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__MsgHistory_v.13.smt2 |    0.023s | 19.448MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.37.smt2 |    0.023s | 19.368MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.27.smt2 |    0.023s | 19.684MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__Memtable_v.7.smt2 |    0.023s | 19.416MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__AbstractJournal_v__AbstractJournal.1.smt2 |    0.023s | 19.324MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-logimpl_v.5.smt2 |    0.023s | 19.384MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.20.smt2 |    0.023s | 19.52MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal74.smt2 |    0.023s | 20.864MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal3.smt2 |    0.023s | 20.496MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal44.smt2 |    0.023s | 19.832MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal17.smt2 |    0.023s | 19.8MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/verismo/tspec_e__math__minmax.1.smt2 |    0.024s | 19.972MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v.13.smt2 |    0.024s | 19.6MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetree_v.18.smt2 |    0.024s | 19.564MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v__LinkedJournal.2.smt2 |    0.024s | 19.524MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v.12.smt2 |    0.024s | 19.656MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-logimpl_v.3.smt2 |    0.024s | 19.612MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__Buffer_v.5.smt2 |    0.024s | 19.352MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.19.smt2 |    0.024s | 19.568MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v.13.smt2 |    0.024s | 19.676MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetree_v.16.smt2 |    0.024s | 19.54MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetree_v.19.smt2 |    0.024s | 19.576MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg34.smt2 |    0.024s | 20.024MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal81.smt2 |    0.024s | 19.836MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/2019-Gleiss/non-interference/2-ni-branch-on-high-twice.spec.smt2 |    0.024s | 20.068MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotTable_v.5.smt2 |    0.025s | 19.42MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__UnifiedCrashAwareJournal_v.10.smt2 |    0.025s | 19.712MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.3.smt2 |    0.025s | 19.488MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.2.smt2 |    0.025s | 19.8MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-pmem__traits_t.1.smt2 |    0.025s | 20.172MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.27.smt2 |    0.025s | 19.608MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v.5.smt2 |    0.025s | 19.636MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-exec__MiniAllocator_v.3.smt2 |    0.025s | 19.5MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetree_v.35.smt2 |    0.025s | 19.456MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__UnifiedCrashAwareJournal_v.11.smt2 |    0.025s | 19.672MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v.1.smt2 |    0.025s | 19.504MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal15.smt2 |    0.025s | 20.556MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/verismo/arch__addr_s__def_s.1.smt2 |    0.026s | 19.536MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v__LinkedJournal.4.smt2 |    0.026s | 19.72MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetree_v.32.smt2 |    0.026s | 19.796MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.50.smt2 |    0.026s | 19.572MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__layout_v.4.smt2 |    0.026s | 19.536MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournalRefinement_v.1.smt2 |    0.026s | 19.644MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal67.smt2 |    0.026s | 20.312MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg32.smt2 |    0.026s | 20.508MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal4.smt2 |    0.026s | 19.8MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal8.smt2 |    0.026s | 20.04MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__UnifiedCrashAwareJournal_v.14.smt2 |    0.027s | 19.572MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.29.smt2 |    0.027s | 19.828MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.23.smt2 |    0.027s | 19.72MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.21.smt2 |    0.027s | 19.544MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/mimalloc-smt-flags.5.smt2 |    0.027s | 20.508MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetree_v.43.smt2 |    0.028s | 19.744MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-exec__rwlock.1.smt2 |    0.028s | 20.128MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.47.smt2 |    0.028s | 19.672MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-exec__Cache_v.1.smt2 |    0.028s | 19.348MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetree_v.21.smt2 |    0.028s | 19.876MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetree_v.22.smt2 |    0.028s | 19.936MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal51.smt2 |    0.028s | 20.496MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal71.smt2 |    0.028s | 20.056MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v__LikesJournal.1.smt2 |    0.029s | 19.84MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_protocol_t.20.smt2 |    0.029s | 19.76MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__BufferSeq_v.12.smt2 |    0.029s | 19.46MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal39.smt2 |    0.029s | 20.264MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/trap.1.smt2 |    0.030s | 20.612MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/pagetable__entry.8.smt2 |    0.030s | 20.304MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__OffsetMap_v.4.smt2 |    0.030s | 20.504MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetree_v__PivotBetree.smt2 |    0.030s | 19.888MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-keys_t.5.smt2 |    0.030s | 20.444MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_protocol_t.13.smt2 |    0.030s | 19.864MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v__AllocationJournal.1.smt2 |    0.030s | 19.96MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/rev-equiv-goal8.smt2 |    0.030s | 19.588MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal34.smt2 |    0.030s | 19.844MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/2019-Gleiss/non-interference/5-ni-temp-impl-flow.spec.smt2 |    0.030s | 20.116MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.67.smt2 |    0.031s | 19.744MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/mimalloc-smt-pigeonhole.1.smt2 |    0.031s | 20.356MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_protocol_t.18.smt2 |    0.031s | 19.908MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetreeRefinement_v.6.smt2 |    0.031s | 20.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetree_v.43.smt2 |    0.031s | 19.812MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetreeRefinement_v.4.smt2 |    0.031s | 19.9MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg29.smt2 |    0.031s | 19.792MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__MsgHistory_v.2.smt2 |    0.032s | 19.356MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.41.smt2 |    0.032s | 20.116MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.38.smt2 |    0.033s | 19.948MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__Buffer_v.9.smt2 |    0.033s | 20.624MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v__FilteredBetree.smt2 |    0.033s | 20.04MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v__AllocationJournal.4.smt2 |    0.033s | 20.276MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__SeqMarshalling_v.1.smt2 |    0.033s | 20.508MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.31.smt2 |    0.033s | 19.928MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-keys_t.6.smt2 |    0.033s | 20.756MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetree_v.20.smt2 |    0.033s | 19.78MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.37.smt2 |    0.033s | 19.572MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedSeq_v.6.smt2 |    0.033s | 20.516MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg24.smt2 |    0.033s | 20.58MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/trap.2.smt2 |    0.034s | 20.784MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournal_v.1.smt2 |    0.034s | 20.528MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.33.smt2 |    0.034s | 19.992MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournal_v.2.smt2 |    0.034s | 20.532MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-kv__kvimpl_v.9.smt2 |    0.034s | 20.32MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-keys_t.7.smt2 |    0.034s | 20.712MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.35.smt2 |    0.034s | 19.956MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.47.smt2 |    0.034s | 20.124MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__BufferOffsets_v.2.smt2 |    0.034s | 20.224MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournal_v.6.smt2 |    0.034s | 20.556MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.4.smt2 |    0.034s | 19.42MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/2019-Gleiss/non-interference/3-ni-high-guard-equal-branches.spec.smt2 |    0.034s | 19.796MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/verismo/snp__percpu__def_s.2.smt2 |    0.035s | 19.016MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferOffsets_v.3.smt2 |    0.035s | 20.46MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.1.smt2 |    0.035s | 19.724MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferOffsets_v.6.smt2 |    0.035s | 20.452MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__Buffer_v.10.smt2 |    0.035s | 20.524MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournal_v.12.smt2 |    0.035s | 20.836MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.19.smt2 |    0.035s | 19.976MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__MiniAllocator_v.5.smt2 |    0.035s | 20.484MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_protocol_t.30.smt2 |    0.035s | 19.992MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-kv__kvimpl_v.15.smt2 |    0.035s | 20.056MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__Buffer_v.14.smt2 |    0.035s | 19.332MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournal_v.4.smt2 |    0.035s | 20.544MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v__LinkedJournal.2.smt2 |    0.035s | 19.38MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.30.smt2 |    0.035s | 20.1MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__UnifiedCrashAwareJournal_v.14.smt2 |    0.035s | 19.788MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.55.smt2 |    0.035s | 20.052MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__BufferSeq_v.5.smt2 |    0.035s | 19.324MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/verismo/snp__percpu__def_s.1.smt2 |    0.036s | 19.196MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetreeRefinement_v.12.smt2 |    0.036s | 20.212MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBranch_v.26.smt2 |    0.036s | 19.572MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__Buffer_v.11.smt2 |    0.036s | 20.676MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__BufferOffsets_v.5.smt2 |    0.036s | 20.472MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__Buffer_v.2.smt2 |    0.036s | 19.528MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__Slice_v.5.smt2 |    0.036s | 20.428MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournal_v.3.smt2 |    0.036s | 20.54MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal31.smt2 |    0.036s | 19.832MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/2019-Gleiss/non-interference/6-ni-branch-assign-equal-val.spec.smt2 |    0.036s | 19.68MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/2019-Gleiss/non-interference/4-ni-branch-on-high-twice-prop2.spec.smt2 |    0.036s | 20.816MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__SeqMarshalling_v.3.smt2 |    0.037s | 20.78MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetreeRefinement_v.10.smt2 |    0.037s | 20.128MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournal_v.3.smt2 |    0.037s | 20.648MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__MiniAllocator_v.3.smt2 |    0.037s | 20.552MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferSeq_v.12.smt2 |    0.037s | 19.46MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__StampedMap_v.3.smt2 |    0.037s | 20.784MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.32.smt2 |    0.037s | 20.1MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__MsgHistory_v.11.smt2 |    0.037s | 19.272MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.76.smt2 |    0.037s | 20.044MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__BufferOffsets_v.7.smt2 |    0.037s | 19.256MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.87.smt2 |    0.037s | 20.3MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/define.5.smt2 |    0.038s | 19.204MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v__AllocationJournal.6.smt2 |    0.038s | 20.144MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__Buffer_v.13.smt2 |    0.038s | 19.284MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBranch_v.11.smt2 |    0.038s | 19.484MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__Buffer_v.15.smt2 |    0.038s | 19.38MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/mimalloc-smt-linked_list__StuffAgree.1.smt2 |    0.038s | 21.108MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-endpoint_hashmap_t.smt2 |    0.038s | 20.648MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournal_v.14.smt2 |    0.038s | 20.744MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__MsgHistory_v.8.smt2 |    0.038s | 20.9MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__MiniAllocator_v.3.smt2 |    0.038s | 20.772MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/rotate-goal9.smt2 |    0.038s | 20.624MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal22.smt2 |    0.038s | 19.788MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.7.smt2 |    0.039s | 20.808MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.1.smt2 |    0.039s | 19.316MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.2.smt2 |    0.039s | 20.904MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__exec__reconciler.7.smt2 |    0.039s | 20.336MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournal_v.15.smt2 |    0.039s | 20.92MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedSeq_v.4.smt2 |    0.039s | 19.3MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__MsgHistory_v.5.smt2 |    0.040s | 19.284MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournal_v.11.smt2 |    0.040s | 19.42MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.48.smt2 |    0.040s | 19.684MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-verus_extra__set_lib_ext_v.7.smt2 |    0.040s | 20.592MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBranch_v.5.smt2 |    0.040s | 20.732MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.40.smt2 |    0.040s | 20.248MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/verismo/arch__addr_s__def_s.2.smt2 |    0.041s | 19.696MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/verismo/tspec_e__array__array_e.4.smt2 |    0.041s | 21.056MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.10.smt2 |    0.041s | 20.844MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.10.smt2 |    0.041s | 19.452MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__AbstractCrashAwareSystemRefinement_v.3.smt2 |    0.041s | 20.512MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__Memtable_v.5.smt2 |    0.041s | 19.448MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-single_delivery_t.10.smt2 |    0.041s | 19.568MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-log__layout_v.3.smt2 |    0.041s | 19.484MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__Memtable_v.3.smt2 |    0.041s | 20.908MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournal_v.20.smt2 |    0.041s | 20.64MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournal_v.16.smt2 |    0.041s | 20.836MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-exec__MiniAllocator_v.1.smt2 |    0.041s | 19.676MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetree_v.20.smt2 |    0.041s | 19.864MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.12.smt2 |    0.041s | 19.508MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournal_v.13.smt2 |    0.041s | 20.656MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferDisk_v.4.smt2 |    0.042s | 19.396MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-single_delivery_t.1.smt2 |    0.042s | 20.968MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-pmemlog-logimpl_v.6.smt2 |    0.042s | 19.532MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-seq_is_unique_v.11.smt2 |    0.042s | 21.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-args_t.2.smt2 |    0.042s | 20.724MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__StampedMap_v.3.smt2 |    0.042s | 20.684MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__MiniAllocator_v.4.smt2 |    0.042s | 19.296MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournal_v.21.smt2 |    0.042s | 20.904MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__UnifiedCrashAwareJournal_v.12.smt2 |    0.042s | 19.58MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.3.smt2 |    0.042s | 20.904MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.20.smt2 |    0.043s | 19.628MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferSeq_v.7.smt2 |    0.043s | 20.836MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__AbstractCrashAwareSystemRefinement_v.4.smt2 |    0.043s | 20.592MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetree_v.7.smt2 |    0.043s | 21.196MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__Buffer_v.7.smt2 |    0.043s | 19.328MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-verus_extra__seq_lib_v.10.smt2 |    0.043s | 20.588MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-verus_extra__set_lib_ext_v.18.smt2 |    0.043s | 21.072MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__Utils_v.3.smt2 |    0.043s | 20.668MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.9.smt2 |    0.043s | 20.988MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotTable_v.7.smt2 |    0.043s | 20.896MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetree_v.7.smt2 |    0.043s | 20.964MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/verismo/tspec_e__array__array_e.2.smt2 |    0.044s | 21.124MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.11.smt2 |    0.044s | 21.096MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.15.smt2 |    0.044s | 19.86MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetree_v.2.smt2 |    0.044s | 21.388MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__MiniAllocator_v.16.smt2 |    0.044s | 20.56MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__AbstractCrashAwareSystemRefinement_v.6.smt2 |    0.044s | 20.552MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__simple_log.smt2 |    0.044s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetree_v.31.smt2 |    0.044s | 19.508MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.44.smt2 |    0.044s | 19.536MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.11.smt2 |    0.044s | 21.036MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal66.smt2 |    0.044s | 20.78MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal24.smt2 |    0.044s | 20.56MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal57.smt2 |    0.044s | 19.944MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferDisk_v.7.smt2 |    0.045s | 20.908MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__MiniAllocator_v.9.smt2 |    0.045s | 19.384MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferSeq_v.16.smt2 |    0.045s | 21.036MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__AbstractCrashAwareSystemRefinement_v.19.smt2 |    0.045s | 20.52MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.9.smt2 |    0.045s | 19.376MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournal_v.32.smt2 |    0.045s | 20.92MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetree_v.19.smt2 |    0.045s | 19.324MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferDisk_v.2.smt2 |    0.045s | 21.192MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetreeRefinement_v.3.smt2 |    0.045s | 19.876MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.1.smt2 |    0.045s | 20.908MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-verus_extra__set_lib_ext_v.19.smt2 |    0.045s | 20.948MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__BufferDisk_v.2.smt2 |    0.045s | 21.056MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__MsgHistory_v.26.smt2 |    0.045s | 21.08MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-exec__MiniAllocator_v.2.smt2 |    0.045s | 19.728MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__BufferSeq_v.9.smt2 |    0.045s | 21.068MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetree_v.21.smt2 |    0.045s | 19.44MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/pagetable__entry.4.smt2 |    0.046s | 21.12MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetree_v.10.smt2 |    0.046s | 21.204MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.3.smt2 |    0.046s | 19.8MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__MsgHistory_v.20.smt2 |    0.046s | 20.936MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.25.smt2 |    0.046s | 21.24MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/mimalloc-smt-flags.6.smt2 |    0.046s | 20.412MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/mimalloc-smt-pigeonhole.6.smt2 |    0.046s | 20.792MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-verus_extra__set_lib_ext_v.24.smt2 |    0.046s | 21.12MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetree_v.11.smt2 |    0.046s | 21.072MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.52.smt2 |    0.046s | 19.54MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.19.smt2 |    0.047s | 20.972MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.28.smt2 |    0.047s | 19.604MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.27.smt2 |    0.047s | 21.276MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.44.smt2 |    0.047s | 19.724MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.42.smt2 |    0.047s | 20.312MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-spec__AppIO_t.1.smt2 |    0.047s | 21.692MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.15.smt2 |    0.047s | 20.992MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__MiniAllocator_v.13.smt2 |    0.047s | 21.036MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBranchRefinement_v.4.smt2 |    0.047s | 19.592MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.17.smt2 |    0.048s | 21.584MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetree_v.12.smt2 |    0.048s | 21.208MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetree_v.13.smt2 |    0.048s | 21.004MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/mimalloc-smt-flags.8.smt2 |    0.048s | 20.572MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_protocol_t.27.smt2 |    0.048s | 19.864MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v.21.smt2 |    0.048s | 19.784MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__MsgHistory_v.14.smt2 |    0.048s | 21.056MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log.2.smt2 |    0.049s | 20.852MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetree_v.9.smt2 |    0.049s | 21.08MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.34.smt2 |    0.049s | 21.012MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v.12.smt2 |    0.049s | 19.676MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetree_v.12.smt2 |    0.049s | 21.02MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationCrashAwareJournal_v.2.smt2 |    0.049s | 19.644MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/process_manager__thread.2.smt2 |    0.050s | 21.46MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.56.smt2 |    0.050s | 20.084MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.2.smt2 |    0.050s | 21.204MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.6.smt2 |    0.050s | 21.312MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournal_v.27.smt2 |    0.050s | 21.424MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.2.smt2 |    0.050s | 21.388MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetree_v.22.smt2 |    0.050s | 21.02MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.21.smt2 |    0.050s | 21.308MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBranch_v.21.smt2 |    0.050s | 20.92MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal13.smt2 |    0.050s | 19.796MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/trap.6.smt2 |    0.051s | 20.828MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/trap.9.smt2 |    0.051s | 20.436MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__MsgHistory_v.26.smt2 |    0.051s | 20.872MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.8.smt2 |    0.051s | 21.1MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/mimalloc-smt-types__BoolAgree.2.smt2 |    0.051s | 20.988MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_protocol_t.7.smt2 |    0.051s | 19.86MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.62.smt2 |    0.051s | 20.368MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__BufferOffsets_v.4.smt2 |    0.051s | 20.384MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal46.smt2 |    0.051s | 19.664MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/pagetable__entry.1.smt2 |    0.052s | 21.156MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.3.smt2 |    0.052s | 21.256MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.9.smt2 |    0.052s | 21.312MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetree_v.23.smt2 |    0.052s | 21.216MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-kv__kvimpl_v.14.smt2 |    0.052s | 20.036MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-io_t.4.smt2 |    0.052s | 21.428MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.13.smt2 |    0.052s | 21.248MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetreeRefinement_v.7.smt2 |    0.052s | 19.824MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournal_v.27.smt2 |    0.052s | 21.288MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v.6.smt2 |    0.052s | 21.204MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.5.smt2 |    0.052s | 21.672MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/verismo/tspec__seqlib__subseq.1.smt2 |    0.053s | 21.02MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetree_v.24.smt2 |    0.053s | 21.52MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferOffsets_v.5.smt2 |    0.053s | 20.408MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesBetree_v__LikesBetree.5.smt2 |    0.053s | 20.896MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournal_v.33.smt2 |    0.053s | 21.392MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-seq_is_unique_v.6.smt2 |    0.053s | 21.356MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.12.smt2 |    0.053s | 21.324MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetree_v.26.smt2 |    0.053s | 21.244MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.8.smt2 |    0.053s | 21.196MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournal_v.2.smt2 |    0.053s | 20.54MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/exec__Cache_v__Cache.1.smt2 |    0.054s | 21.388MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.40.smt2 |    0.054s | 19.872MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.15.smt2 |    0.054s | 21.312MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__UnifiedCrashAwareJournal_v.3.smt2 |    0.054s | 21.732MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__StampedMap_v.4.smt2 |    0.054s | 20.764MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.82.smt2 |    0.054s | 20.224MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-kv__kvimpl_v.12.smt2 |    0.054s | 20.148MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetree_v.32.smt2 |    0.054s | 21.324MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__Buffer_v.12.smt2 |    0.054s | 20.56MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal7.smt2 |    0.054s | 26.892MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.53.smt2 |    0.055s | 21.52MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.11.smt2 |    0.055s | 21.152MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournalRefinement_v.5.smt2 |    0.055s | 21.556MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v.2.smt2 |    0.055s | 21.552MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesBetree_v__LikesBetree.4.smt2 |    0.055s | 21.032MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournal_v.28.smt2 |    0.055s | 21.688MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBranch_v.31.smt2 |    0.055s | 21.08MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBranch_v.16.smt2 |    0.055s | 20.96MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesBetree_v__LikesBetree.6.smt2 |    0.055s | 20.968MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.83.smt2 |    0.055s | 20.044MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetree_v.8.smt2 |    0.055s | 21.376MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.24.smt2 |    0.055s | 21.364MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetree_v.1.smt2 |    0.055s | 21.436MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournal_v.29.smt2 |    0.055s | 21.436MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/2019-Gleiss/non-interference/7-ni-explicit-flow.spec.smt2 |    0.055s | 25.764MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournalRefinement_v.2.smt2 |    0.056s | 21.628MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesBetree_v__LikesBetree.6.smt2 |    0.056s | 20.9MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.23.smt2 |    0.056s | 21.356MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBranch_v.30.smt2 |    0.056s | 21.32MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v.16.smt2 |    0.056s | 21.464MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-verus_extra__seq_lib_v.7.smt2 |    0.056s | 21.28MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/mimalloc-smt-config.2.smt2 |    0.056s | 21.764MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.9.smt2 |    0.056s | 21.344MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.3.smt2 |    0.056s | 21.192MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesBetree_v__LikesBetree.5.smt2 |    0.056s | 20.872MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.16.smt2 |    0.056s | 21.252MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.18.smt2 |    0.056s | 21.476MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.19.smt2 |    0.056s | 21.28MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournal_v.15.smt2 |    0.057s | 21.096MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/mimalloc-smt-config.4.smt2 |    0.057s | 21.792MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.19.smt2 |    0.057s | 21.46MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.47.smt2 |    0.057s | 21.396MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.35.smt2 |    0.057s | 21.636MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetree_v.9.smt2 |    0.057s | 21.412MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__Buffer_v.10.smt2 |    0.057s | 20.768MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/verismo/tspec_e__array__array_e.10.smt2 |    0.058s | 21.14MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetree_v.16.smt2 |    0.058s | 21.48MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.42.smt2 |    0.058s | 21.668MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.31.smt2 |    0.058s | 21.3MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.23.smt2 |    0.058s | 21.812MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-exec__rwlock.7.smt2 |    0.058s | 20.044MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v.16.smt2 |    0.058s | 21.516MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBranch_v.25.smt2 |    0.058s | 21.296MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal11.smt2 |    0.058s | 19.776MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetree_v.12.smt2 |    0.059s | 21.432MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferDisk_v.3.smt2 |    0.059s | 20.836MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetree_v.42.smt2 |    0.059s | 19.712MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.83.smt2 |    0.059s | 20.244MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.30.smt2 |    0.059s | 21.792MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__UnifiedCrashAwareJournal_v.4.smt2 |    0.059s | 22.22MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferSeq_v.6.smt2 |    0.059s | 20.856MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.24.smt2 |    0.059s | 21.788MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournal_v.12.smt2 |    0.059s | 20.576MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournalRefinement_v.4.smt2 |    0.059s | 21.78MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.10.smt2 |    0.059s | 20.976MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/array.7.smt2 |    0.060s | 21.572MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.32.smt2 |    0.060s | 22.08MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.76.smt2 |    0.060s | 20.272MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-exec__utils.4.smt2 |    0.060s | 21.248MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.42.smt2 |    0.060s | 21.384MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.42.smt2 |    0.060s | 21.624MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v.15.smt2 |    0.060s | 21.388MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__MsgHistory_v.27.smt2 |    0.060s | 20.976MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.31.smt2 |    0.060s | 21.44MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.51.smt2 |    0.060s | 21.752MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/verismo/tspec_e__array__array_utils.5.smt2 |    0.061s | 21.092MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/verismo/tspec__map_lib.1.smt2 |    0.061s | 21.524MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.21.smt2 |    0.061s | 21.54MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.25.smt2 |    0.061s | 21.584MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournal_v.8.smt2 |    0.061s | 20.564MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-kv__kvspec_t.1.smt2 |    0.061s | 21.712MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.29.smt2 |    0.061s | 21.092MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-seq_is_unique_v.2.smt2 |    0.061s | 21.044MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.23.smt2 |    0.061s | 21.616MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v.10.smt2 |    0.061s | 21.9MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__MsgHistory_v.16.smt2 |    0.061s | 21.144MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetree_v.4.smt2 |    0.061s | 21.588MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__AbstractCrashAwareSystemRefinement_v.3.smt2 |    0.061s | 20.84MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetreeRefinement_v.10.smt2 |    0.061s | 20.088MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/array_vec.6.smt2 |    0.062s | 21.692MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.48.smt2 |    0.062s | 21.688MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetree_v.1.smt2 |    0.062s | 20.9MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.55.smt2 |    0.062s | 21.472MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__reconciler.9.smt2 |    0.062s | 21.164MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v.9.smt2 |    0.062s | 21.896MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.21.smt2 |    0.062s | 21.82MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBranch_v.30.smt2 |    0.062s | 21.42MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.30.smt2 |    0.062s | 21.924MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetree_v.20.smt2 |    0.062s | 21.956MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.19.smt2 |    0.062s | 21.128MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal54.smt2 |    0.062s | 28.336MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__AbstractCrashAwareSystemRefinement_v.8.smt2 |    0.063s | 20.724MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v.7.smt2 |    0.063s | 22.336MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-pmem__linux_pmemfile_t.4.smt2 |    0.063s | 21.464MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__MsgHistory_v.21.smt2 |    0.063s | 21.66MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.20.smt2 |    0.063s | 21.936MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/verismo/tspec_e__array__array_utils.3.smt2 |    0.064s | 21.316MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/verismo/tspec__setlib.5.smt2 |    0.064s | 21.86MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__Utils_v.5.smt2 |    0.064s | 21.224MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/exec__MiniAllocator_v.6.smt2 |    0.064s | 21.912MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.18.smt2 |    0.064s | 21.872MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetree_v.29.smt2 |    0.064s | 21.808MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.9.smt2 |    0.064s | 21.752MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_protocol_t.3.smt2 |    0.064s | 22.136MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.46.smt2 |    0.064s | 22.048MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_ironsht_specific_v.2.smt2 |    0.064s | 21.94MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_protocol_t.6.smt2 |    0.064s | 22.072MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__BufferDisk_v.7.smt2 |    0.064s | 20.888MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__trusted__spec_types.6.smt2 |    0.064s | 22.308MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v.16.smt2 |    0.064s | 21.668MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournalRefinement_v.11.smt2 |    0.064s | 21.776MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__Slice_v.1.smt2 |    0.064s | 20.444MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.27.smt2 |    0.064s | 21.888MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesBetree_v.1.smt2 |    0.064s | 21.624MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.22.smt2 |    0.065s | 21.724MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.30.smt2 |    0.065s | 22.3MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-verus_extra__seq_lib_v.1.smt2 |    0.065s | 20.92MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__trusted__spec_types.3.smt2 |    0.065s | 22.196MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__trusted__spec_types.5.smt2 |    0.065s | 21.94MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.35.smt2 |    0.065s | 21.684MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/process_manager__thread.3.smt2 |    0.066s | 21.272MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBranch_v.6.smt2 |    0.066s | 21.012MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetree_v.22.smt2 |    0.066s | 21.252MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.7.smt2 |    0.066s | 22.276MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferDisk_v.8.smt2 |    0.066s | 20.984MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/mimalloc-smt-pigeonhole.2.smt2 |    0.066s | 20.74MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBranch_v.7.smt2 |    0.066s | 21.044MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotTable_v.10.smt2 |    0.066s | 20.924MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournal_v.18.smt2 |    0.066s | 21.016MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.32.smt2 |    0.067s | 22.344MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__MsgHistory_v.16.smt2 |    0.067s | 21.04MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.16.smt2 |    0.067s | 21.352MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.15.smt2 |    0.067s | 22.128MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.19.smt2 |    0.067s | 22.172MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotTable_v.9.smt2 |    0.067s | 20.912MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-kv__inv_v.1.smt2 |    0.067s | 21.176MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.11.smt2 |    0.067s | 22.348MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-verus_extra__set_lib_ext_v.21.smt2 |    0.067s | 21.2MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.11.smt2 |    0.067s | 21.596MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetree_v.2.smt2 |    0.067s | 21.072MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetree_v.38.smt2 |    0.068s | 21.972MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesBetree_v.6.smt2 |    0.068s | 22.12MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.22.smt2 |    0.068s | 22.068MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.16.smt2 |    0.068s | 22.08MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.7.smt2 |    0.068s | 21.884MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.1.smt2 |    0.068s | 21.964MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.4.smt2 |    0.068s | 22.076MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetree_v.34.smt2 |    0.068s | 21.872MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.38.smt2 |    0.068s | 22.496MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetree_v.36.smt2 |    0.068s | 21.86MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__trusted__spec_types.6.smt2 |    0.068s | 21.948MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal63.smt2 |    0.068s | 20.048MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.26.smt2 |    0.069s | 21.708MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_ironsht_specific_v.19.smt2 |    0.069s | 21.652MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v.22.smt2 |    0.069s | 21.784MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetree_v.27.smt2 |    0.069s | 21.96MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.50.smt2 |    0.069s | 21.708MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.13.smt2 |    0.070s | 22.068MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__MsgHistory_v.25.smt2 |    0.070s | 21.088MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_protocol_t.8.smt2 |    0.070s | 22.608MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-kv__kvimpl_t.1.smt2 |    0.070s | 22.328MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-verus_extra__set_lib_ext_v.8.smt2 |    0.070s | 21.472MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.51.smt2 |    0.070s | 22.504MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetree_v.31.smt2 |    0.070s | 22.04MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__reconciler.2.smt2 |    0.070s | 21.608MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__trusted__spec_types.4.smt2 |    0.070s | 22.264MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__trusted__spec_types.1.smt2 |    0.070s | 22.324MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferDisk_v.14.smt2 |    0.071s | 21.792MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v__Refinement_v.3.smt2 |    0.071s | 22.14MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationCrashAwareJournal_v.1.smt2 |    0.071s | 21.828MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.26.smt2 |    0.071s | 21.364MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v__Refinement_v.2.smt2 |    0.071s | 22.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/mimalloc-smt-tokens.1.smt2 |    0.071s | 22.268MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_ironsht_specific_v.36.smt2 |    0.071s | 22.032MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.23.smt2 |    0.071s | 21.224MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetree_v.10.smt2 |    0.071s | 21.14MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBranch_v.32.smt2 |    0.071s | 21.376MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/spec__AppIO_t.3.smt2 |    0.072s | 21.32MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-verus_extra__set_lib_ext_v.23.smt2 |    0.072s | 21.296MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.7.smt2 |    0.072s | 21.76MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__trusted__spec_types.5.smt2 |    0.072s | 22.684MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/verismo/tspec__range_set.5.smt2 |    0.073s | 21.308MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/verismo/tspec__seqlib__seq_multiset.4.smt2 |    0.073s | 21.944MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__MsgHistory_v.21.smt2 |    0.073s | 21.42MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/exec__Cache_v__Cache.9.smt2 |    0.073s | 21.824MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-seq_is_unique_v.7.smt2 |    0.073s | 20.984MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__reconciler.16.smt2 |    0.073s | 21.728MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetree_v.6.smt2 |    0.073s | 22.176MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotTable_v.8.smt2 |    0.073s | 21.18MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.16.smt2 |    0.073s | 21.384MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetree_v.41.smt2 |    0.073s | 22.3MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.37.smt2 |    0.073s | 21.864MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg27.smt2 |    0.073s | 19.8MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.17.smt2 |    0.074s | 22.076MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__MsgHistory_v.29.smt2 |    0.074s | 21.628MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.14.smt2 |    0.074s | 21.756MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v.8.smt2 |    0.074s | 22.248MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.3.smt2 |    0.074s | 21.452MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.37.smt2 |    0.074s | 22.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v__Refinement_v.1.smt2 |    0.074s | 22.628MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log.4.smt2 |    0.074s | 22.132MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.45.smt2 |    0.074s | 21.548MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__MsgHistory_v.30.smt2 |    0.074s | 21.628MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__trusted__spec_types.2.smt2 |    0.074s | 22.408MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/pagetable__pagemap.4.smt2 |    0.075s | 22.38MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_ironsht_specific_v.3.smt2 |    0.075s | 21.684MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedSeq_v.7.smt2 |    0.075s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetree_v.26.smt2 |    0.075s | 22.224MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.5.smt2 |    0.075s | 22.716MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.29.smt2 |    0.075s | 21.192MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/slinkedlist__spec_impl_u.1.smt2 |    0.076s | 22.152MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.40.smt2 |    0.076s | 21.804MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.1.smt2 |    0.076s | 21.988MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.10.smt2 |    0.076s | 21.352MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.30.smt2 |    0.076s | 22.192MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_ironsht_specific_v.33.smt2 |    0.076s | 21.984MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-verus_extra__set_lib_ext_v.4.smt2 |    0.076s | 21.276MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__trusted__spec_types.3.smt2 |    0.076s | 22.492MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.54.smt2 |    0.076s | 22.212MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetree_v.34.smt2 |    0.076s | 22.132MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v__Refinement_v.1.smt2 |    0.076s | 22.82MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetree_v.19.smt2 |    0.076s | 22.204MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/array_set.3.smt2 |    0.077s | 22.412MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/array_set.4.smt2 |    0.077s | 22.268MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v.21.smt2 |    0.077s | 22.412MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.12.smt2 |    0.077s | 21.98MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.44.smt2 |    0.077s | 21.56MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.48.smt2 |    0.077s | 21.652MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-kv__kvimpl_t.4.smt2 |    0.077s | 22.176MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.64.smt2 |    0.077s | 22.04MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournalRefinement_v.2.smt2 |    0.077s | 21.5MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.24.smt2 |    0.077s | 21.984MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetree_v.35.smt2 |    0.077s | 22.16MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.25.smt2 |    0.077s | 21.796MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/pagetable__pagemap.5.smt2 |    0.078s | 21.588MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetree_v.14.smt2 |    0.078s | 21.692MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetree_v.33.smt2 |    0.078s | 22.352MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.29.smt2 |    0.078s | 22.132MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__simple_log__SimpleLog.1.smt2 |    0.078s | 22.712MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.9.smt2 |    0.078s | 22.528MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.11.smt2 |    0.078s | 22.496MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournalRefinement_v.9.smt2 |    0.078s | 22.832MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.57.smt2 |    0.078s | 22.024MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal6.smt2 |    0.078s | 27.436MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.62.smt2 |    0.079s | 22.36MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.14.smt2 |    0.079s | 21.356MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBranch_v.12.smt2 |    0.079s | 21.64MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_protocol_t.22.smt2 |    0.079s | 22.408MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log.16.smt2 |    0.079s | 22.12MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-keys_t.3.smt2 |    0.079s | 21.232MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.22.smt2 |    0.079s | 21.588MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v.2.smt2 |    0.079s | 21.652MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v.8.smt2 |    0.079s | 22.36MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__simple_log__SimpleLog.7.smt2 |    0.080s | 22.404MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetree_v.33.smt2 |    0.080s | 22.332MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetree_v.9.smt2 |    0.080s | 21.78MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.61.smt2 |    0.080s | 22.144MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.55.smt2 |    0.081s | 21.32MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v.17.smt2 |    0.081s | 21.684MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.41.smt2 |    0.081s | 22.484MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_protocol_t.25.smt2 |    0.081s | 22.448MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.43.smt2 |    0.081s | 22.316MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__simple_log__SimpleLog.5.smt2 |    0.081s | 22.404MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.62.smt2 |    0.081s | 22.232MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournalRefinement_v.2.smt2 |    0.081s | 22.748MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.10.smt2 |    0.081s | 22.596MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_ironsht_specific_v.32.smt2 |    0.082s | 22.076MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_protocol_t.31.smt2 |    0.082s | 22.344MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.28.smt2 |    0.082s | 22.54MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournalRefinement_v.5.smt2 |    0.082s | 22.376MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.18.smt2 |    0.082s | 22.6MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetree_v.26.smt2 |    0.082s | 21.832MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v.27.smt2 |    0.082s | 22.24MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__reconciler.9.smt2 |    0.082s | 21.628MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__reconciler.7.smt2 |    0.082s | 21.564MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournalRefinement_v.18.smt2 |    0.083s | 22.628MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.20.smt2 |    0.083s | 22.82MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournalRefinement_v.11.smt2 |    0.083s | 21.836MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.6.smt2 |    0.083s | 22.672MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.21.smt2 |    0.083s | 22.78MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__flat_combiner__FlatCombiner.2.smt2 |    0.083s | 22.876MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_ironsht_specific_v.39.smt2 |    0.083s | 22.14MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.48.smt2 |    0.083s | 22.408MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__common.1.smt2 |    0.083s | 22.632MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.41.smt2 |    0.084s | 22.952MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.48.smt2 |    0.084s | 22.78MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetree_v.24.smt2 |    0.084s | 22.228MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_ironsht_specific_v.9.smt2 |    0.084s | 22.044MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournalRefinement_v.10.smt2 |    0.084s | 22.196MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.6.smt2 |    0.084s | 22.936MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/array.2.smt2 |    0.085s | 21.84MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.58.smt2 |    0.085s | 22.484MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_protocol_t.11.smt2 |    0.085s | 22.308MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__reconciler.19.smt2 |    0.085s | 21.668MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetree_v.38.smt2 |    0.085s | 22.692MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__common.3.smt2 |    0.085s | 23.036MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournalRefinement_v.12.smt2 |    0.085s | 22.652MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.25.smt2 |    0.086s | 22.872MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/exec__MiniAllocator_v.12.smt2 |    0.086s | 21.928MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.34.smt2 |    0.086s | 23.124MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.38.smt2 |    0.086s | 22.456MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.5.smt2 |    0.086s | 21.688MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.40.smt2 |    0.086s | 21.744MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournalRefinement_v.22.smt2 |    0.086s | 22.4MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.17.smt2 |    0.087s | 22.66MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-pmem__linux_pmemfile_t.3.smt2 |    0.087s | 21.436MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__flat_combiner__FlatCombiner.7.smt2 |    0.087s | 22.848MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__simple_log__SimpleLog.8.smt2 |    0.087s | 23.028MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__resource__common.2.smt2 |    0.087s | 23.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal26.smt2 |    0.087s | 34.252MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.32.smt2 |    0.088s | 22.716MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournal_v.31.smt2 |    0.088s | 21.612MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__linearization.8.smt2 |    0.088s | 22.524MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.49.smt2 |    0.088s | 21.68MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.26.smt2 |    0.088s | 22.916MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetreeRefinement_v.1.smt2 |    0.088s | 22.648MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.40.smt2 |    0.088s | 21.98MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/exec__Cache_v__Cache.10.smt2 |    0.089s | 22.412MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__resource__common.3.smt2 |    0.089s | 23.036MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationCrashAwareJournal_v__AllocationCrashAwareJournal.4.smt2 |    0.090s | 23.424MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v__LikesJournal.3.smt2 |    0.090s | 23.668MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/process_manager__endpoint_util_t.smt2 |    0.091s | 22.396MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.41.smt2 |    0.091s | 21.512MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__MsgHistory_v.22.smt2 |    0.091s | 21.924MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.24.smt2 |    0.091s | 23.064MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.2.smt2 |    0.091s | 21.944MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.32.smt2 |    0.091s | 22.672MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetreeRefinement_v.24.smt2 |    0.091s | 23.028MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-kv__kvimpl_t.7.smt2 |    0.092s | 22.868MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/array_set.7.smt2 |    0.093s | 22.064MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-exec__rwlock.9.smt2 |    0.093s | 23.104MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.42.smt2 |    0.093s | 23.416MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournalRefinement_v.17.smt2 |    0.093s | 22.54MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.44.smt2 |    0.094s | 23.004MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.24.smt2 |    0.094s | 23.056MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v__LikesJournal.4.smt2 |    0.094s | 23.58MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.5.smt2 |    0.094s | 21.856MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetree_v.37.smt2 |    0.094s | 22.44MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-seq_is_unique_v.5.smt2 |    0.095s | 21.7MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_ironsht_specific_v.45.smt2 |    0.095s | 22.048MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__flat_combiner__FlatCombiner.14.smt2 |    0.095s | 22.876MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_ironsht_specific_v.18.smt2 |    0.095s | 21.992MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetree_v.32.smt2 |    0.095s | 22.736MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetree_v.17.smt2 |    0.095s | 21.608MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.49.smt2 |    0.096s | 22.484MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.45.smt2 |    0.096s | 23.044MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log.15.smt2 |    0.096s | 22.54MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBranchRefinement_v.11.smt2 |    0.096s | 22.776MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.31.smt2 |    0.097s | 22.712MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v__AllocationJournal.7.smt2 |    0.097s | 22.996MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/slinkedlist__spec_impl_u.6.smt2 |    0.098s | 22.86MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.27.smt2 |    0.098s | 22.26MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.34.smt2 |    0.098s | 22.82MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__trusted__spec_types.3.smt2 |    0.098s | 22.868MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBranchRefinement_v.19.smt2 |    0.099s | 22.52MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournalRefinement_v.18.smt2 |    0.099s | 23.02MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetree_v.23.smt2 |    0.100s | 22.636MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournalRefinement_v.2.smt2 |    0.100s | 22.612MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-exec__rwlock.10.smt2 |    0.100s | 23.072MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.37.smt2 |    0.100s | 22.3MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-kv__kvimpl_t.9.smt2 |    0.100s | 23.024MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-kv__kvimpl_t.11.smt2 |    0.100s | 22.752MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.12.smt2 |    0.101s | 22.08MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-verus_extra__seq_lib_v.8.smt2 |    0.101s | 22.208MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.16.smt2 |    0.101s | 23.484MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetreeRefinement_v.29.smt2 |    0.101s | 23.608MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournalRefinement_v.2.smt2 |    0.102s | 23.204MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournalRefinement_v.30.smt2 |    0.102s | 23.772MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.38.smt2 |    0.102s | 22.488MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.52.smt2 |    0.102s | 23.036MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-verus_extra__set_lib_ext_v.14.smt2 |    0.102s | 21.728MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.60.smt2 |    0.102s | 23.196MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetree_v.30.smt2 |    0.103s | 22.144MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.57.smt2 |    0.103s | 23.384MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v__LikesJournal.2.smt2 |    0.104s | 23.628MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-cmessage_v.10.smt2 |    0.104s | 22.688MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-kv__kvimpl_t.14.smt2 |    0.105s | 22.468MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log.6.smt2 |    0.105s | 22.732MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log.18.smt2 |    0.105s | 22.344MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.38.smt2 |    0.105s | 21.716MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetreeRefinement_v.4.smt2 |    0.106s | 23.604MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__flat_combiner__FlatCombiner.5.smt2 |    0.106s | 22.644MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__exec__resource__secret.2.smt2 |    0.106s | 23.408MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.68.smt2 |    0.107s | 23.352MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.44.smt2 |    0.107s | 22.876MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-single_delivery_state_v.8.smt2 |    0.107s | 22.66MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal9.smt2 |    0.107s | 29.304MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationCrashAwareJournal_v__AllocationCrashAwareJournal.2.smt2 |    0.108s | 23.76MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/exec__Cache_v__Cache.5.smt2 |    0.108s | 22.96MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.43.smt2 |    0.108s | 23.14MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-root.3.smt2 |    0.108s | 24.024MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__flat_combiner__FlatCombiner.13.smt2 |    0.108s | 23.14MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.72.smt2 |    0.109s | 23.392MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetreeRefinement_v.7.smt2 |    0.109s | 23.76MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__Memtable_v.12.smt2 |    0.109s | 22.092MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__flat_combiner__FlatCombiner.8.smt2 |    0.109s | 23.46MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__rwlock__RwLockSpec.3.smt2 |    0.109s | 23.016MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__common.2.smt2 |    0.109s | 22.596MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournalRefinement_v.6.smt2 |    0.109s | 22.108MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.72.smt2 |    0.109s | 23.584MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationCrashAwareJournal_v__AllocationCrashAwareJournal.9.smt2 |    0.110s | 25.424MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.7.smt2 |    0.110s | 23.836MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.10.smt2 |    0.110s | 22.452MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-kv__kvimpl_t.6.smt2 |    0.110s | 22.864MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesBetree_v.17.smt2 |    0.110s | 23.056MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournalRefinement_v.9.smt2 |    0.110s | 23.88MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesBetree_v.12.smt2 |    0.111s | 22.884MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v.31.smt2 |    0.111s | 22.764MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournal_v.47.smt2 |    0.112s | 22.868MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-exec__rwlock.5.smt2 |    0.112s | 23.488MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v.29.smt2 |    0.112s | 23.452MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__exec__resource__secret.8.smt2 |    0.112s | 23.704MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-exec__Cache_v__Cache.2.smt2 |    0.112s | 23.492MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__resource__common.1.smt2 |    0.112s | 23.36MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__trusted__spec_types.2.smt2 |    0.112s | 23.92MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v__LikesJournal.2.smt2 |    0.112s | 23.604MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournalRefinement_v.22.smt2 |    0.113s | 22.34MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.31.smt2 |    0.113s | 22.436MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBranchRefinement_v.10.smt2 |    0.115s | 22.712MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_protocol_t.17.smt2 |    0.115s | 22.72MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v.51.smt2 |    0.115s | 23.884MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesBetree_v.19.smt2 |    0.115s | 23.092MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.6.smt2 |    0.115s | 22.316MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-root.1.smt2 |    0.116s | 23.544MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__rwlock__RwLockSpec.7.smt2 |    0.116s | 23.132MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.31.smt2 |    0.116s | 22.516MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.74.smt2 |    0.116s | 23.816MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.89.smt2 |    0.116s | 23.836MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v__AllocationJournal.7.smt2 |    0.117s | 22.852MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.43.smt2 |    0.117s | 23.308MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__MsgHistory_v.23.smt2 |    0.117s | 21.784MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg26.smt2 |    0.117s | 36.904MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/process_manager__container_tree_spec_impl.6.smt2 |    0.118s | 27.556MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v__AllocationJournal.8.smt2 |    0.118s | 24.548MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v.24.smt2 |    0.118s | 22.692MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.24.smt2 |    0.118s | 23.128MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetreeRefinement_v.13.smt2 |    0.118s | 23.924MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v.27.smt2 |    0.119s | 23.76MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetreeRefinement_v.2.smt2 |    0.119s | 24.1MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetreeRefinement_v.9.smt2 |    0.119s | 24.312MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.89.smt2 |    0.119s | 23.832MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetreeRefinement_v.2.smt2 |    0.119s | 24.052MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log.7.smt2 |    0.120s | 22.812MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.65.smt2 |    0.120s | 24.276MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal8.smt2 |    0.120s | 37.104MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetreeRefinement_v.19.smt2 |    0.121s | 23.068MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__AbstractCrashAwareSystemRefinement_v.21.smt2 |    0.121s | 24.784MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v.27.smt2 |    0.121s | 23.66MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/pagetable__pagemap_util_t.1.smt2 |    0.122s | 24.192MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournalRefinement_v.7.smt2 |    0.122s | 22.828MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetree_v.23.smt2 |    0.122s | 22.596MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/nichomachus-goal2.smt2 |    0.122s | 37.216MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/array.5.smt2 |    0.123s | 22.412MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__AbstractCrashAwareSystemRefinement_v.23.smt2 |    0.123s | 24.732MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-single_delivery_state_v.15.smt2 |    0.123s | 23.528MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBranchRefinement_v.18.smt2 |    0.124s | 23.432MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.85.smt2 |    0.124s | 23.952MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v__LikesJournal.10.smt2 |    0.124s | 24.38MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_ironsht_specific_v.8.smt2 |    0.124s | 22.996MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log_refines_simplelog.7.smt2 |    0.124s | 23.588MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__common.4.smt2 |    0.124s | 24.796MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferSeq_v.21.smt2 |    0.125s | 22.9MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__AbstractCrashAwareSystemRefinement_v.11.smt2 |    0.125s | 24.996MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.6.smt2 |    0.125s | 22.224MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.54.smt2 |    0.125s | 23.316MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.35.smt2 |    0.125s | 22.884MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v__AllocationJournal.16.smt2 |    0.125s | 24.3MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.59.smt2 |    0.125s | 23.956MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetreeRefinement_v.6.smt2 |    0.126s | 23.512MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetree_v.40.smt2 |    0.126s | 22.532MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v__Refinement_v.9.smt2 |    0.126s | 23.408MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.59.smt2 |    0.127s | 23.98MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-single_delivery_state_v.5.smt2 |    0.127s | 23.844MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.8.smt2 |    0.128s | 24.092MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.90.smt2 |    0.128s | 25.032MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBranchRefinement_v.18.smt2 |    0.128s | 23.364MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetreeRefinement_v.9.smt2 |    0.129s | 24.168MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetree_v.40.smt2 |    0.129s | 22.68MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetreeRefinement_v.15.smt2 |    0.130s | 24.604MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-exec__rwlock.2.smt2 |    0.130s | 23.344MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-single_delivery_state_v.9.smt2 |    0.130s | 23.04MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/process_manager__container_tree_spec_impl.7.smt2 |    0.131s | 27.116MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetreeRefinement_v.30.smt2 |    0.131s | 23.86MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__linearization.1.smt2 |    0.131s | 24.092MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log_refines_simplelog.9.smt2 |    0.131s | 23.916MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__UnifiedCrashAwareJournal_v__UnifiedCrashAwareJournal.4.smt2 |    0.131s | 24.776MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetreeRefinement_v.5.smt2 |    0.132s | 24.492MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/verismo/tspec__setlib.4.smt2 |    0.133s | 22.16MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesBetree_v.4.smt2 |    0.133s | 22.74MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.75.smt2 |    0.134s | 24.676MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v__Refinement_v.14.smt2 |    0.135s | 24.056MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.67.smt2 |    0.135s | 23.824MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.9.smt2 |    0.135s | 23.64MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_impl_t.1.smt2 |    0.136s | 23.876MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournalRefinement_v.21.smt2 |    0.136s | 24.18MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v.22.smt2 |    0.136s | 23.204MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetreeRefinement_v.17.smt2 |    0.137s | 24.096MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.13.smt2 |    0.137s | 22.22MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__rwlock__RwLockSpec.19.smt2 |    0.137s | 23.4MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__rwlock__RwLockSpec.6.smt2 |    0.138s | 23.368MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.81.smt2 |    0.139s | 23.936MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetreeRefinement_v.20.smt2 |    0.139s | 24.44MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetreeRefinement_v.20.smt2 |    0.139s | 23.672MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.52.smt2 |    0.139s | 23.496MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetreeRefinement_v.6.smt2 |    0.140s | 24.696MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v.18.smt2 |    0.140s | 23.368MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetreeRefinement_v.3.smt2 |    0.140s | 24.672MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationCrashAwareJournal_v__AllocationCrashAwareJournal.7.smt2 |    0.141s | 26.112MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournalRefinement_v.8.smt2 |    0.142s | 24.472MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournalRefinement_v.23.smt2 |    0.142s | 24.424MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournalRefinement_v.19.smt2 |    0.143s | 24.392MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.75.smt2 |    0.143s | 24.568MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__AbstractCrashAwareSystemRefinement_v.22.smt2 |    0.144s | 25.348MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v.18.smt2 |    0.144s | 23.356MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetreeRefinement_v.14.smt2 |    0.146s | 24.708MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetreeRefinement_v.5.smt2 |    0.147s | 24.288MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.70.smt2 |    0.147s | 24.98MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.39.smt2 |    0.147s | 24.38MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetreeRefinement_v.9.smt2 |    0.147s | 24.164MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.109.smt2 |    0.148s | 24.884MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__AbstractCrashAwareSystemRefinement_v.11.smt2 |    0.148s | 24.912MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetreeRefinement_v.11.smt2 |    0.149s | 24.996MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log__UnboundedLog.3.smt2 |    0.150s | 24.976MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetreeRefinement_v.25.smt2 |    0.150s | 24.892MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetreeRefinement_v.12.smt2 |    0.151s | 24.136MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.52.smt2 |    0.151s | 22.84MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v__Refinement_v.18.smt2 |    0.152s | 24.668MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetreeRefinement_v.25.smt2 |    0.152s | 24.728MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__linearization.2.smt2 |    0.152s | 24.552MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__config_map.5.smt2 |    0.152s | 25.464MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationCrashAwareJournalRefinement_v.1.smt2 |    0.154s | 25.252MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.94.smt2 |    0.154s | 25.124MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetreeRefinement_v.19.smt2 |    0.155s | 25.116MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationCrashAwareJournal_v__AllocationCrashAwareJournal.6.smt2 |    0.155s | 26.86MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__config_map.4.smt2 |    0.155s | 25.544MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournalRefinement_v.12.smt2 |    0.157s | 24.368MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.86.smt2 |    0.157s | 25.18MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationCrashAwareJournal_v__AllocationCrashAwareJournal.6.smt2 |    0.158s | 26.9MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetreeRefinement_v.6.smt2 |    0.159s | 24.832MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_impl_v.1.smt2 |    0.160s | 25.468MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.86.smt2 |    0.160s | 25.108MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log__UnboundedLog.19.smt2 |    0.161s | 25.232MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__AbstractCrashAwareSystemRefinement_v.15.smt2 |    0.163s | 25.96MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__config_map.1.smt2 |    0.163s | 25.9MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__config_map.2.smt2 |    0.163s | 26.456MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesBetree_v.15.smt2 |    0.163s | 24.768MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__resource__role.1.smt2 |    0.163s | 25.92MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/exec__MiniAllocator_v.11.smt2 |    0.165s | 22.94MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__AbstractCrashAwareSystemRefinement_v.15.smt2 |    0.165s | 25.936MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__rwlock__RwLockSpec.10.smt2 |    0.167s | 23.64MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.33.smt2 |    0.168s | 24.316MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.14.smt2 |    0.168s | 23.3MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-exec__MiniAllocator_v.11.smt2 |    0.168s | 22.884MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-single_delivery_model_v.2.smt2 |    0.169s | 25.024MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__client_service.1.smt2 |    0.169s | 26.288MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__BufferSeq_v.20.smt2 |    0.171s | 22.588MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v.14.smt2 |    0.171s | 23.108MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetreeRefinement_v.23.smt2 |    0.171s | 25.232MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__AbstractCrashAwareSystemRefinement_v.17.smt2 |    0.172s | 26.144MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetreeRefinement_v.14.smt2 |    0.172s | 24.892MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.93.smt2 |    0.172s | 25.732MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__stateful_set.1.smt2 |    0.172s | 26.152MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__resource__role_binding.5.smt2 |    0.173s | 28.952MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationCrashAwareJournal_v__AllocationCrashAwareJournal.11.smt2 |    0.174s | 25.992MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetreeRefinement_v.35.smt2 |    0.175s | 23.444MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log__UnboundedLog.15.smt2 |    0.176s | 25.632MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.38.smt2 |    0.178s | 24.308MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournalRefinement_v.27.smt2 |    0.178s | 24.768MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesBetree_v.18.smt2 |    0.179s | 24.556MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__service_account.1.smt2 |    0.179s | 26.596MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log__UnboundedLog.17.smt2 |    0.180s | 25.404MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__resource__service_account.5.smt2 |    0.180s | 28.16MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.6.smt2 |    0.181s | 22.164MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__resource__service_account.4.smt2 |    0.181s | 27.068MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-cmessage_v.17.smt2 |    0.182s | 23.304MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesBetree_v__LikesBetree.7.smt2 |    0.183s | 26.572MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__stateful_set.2.smt2 |    0.184s | 26.696MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournalRefinement_v.21.smt2 |    0.185s | 24.744MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBranchRefinement_v.21.smt2 |    0.185s | 25.008MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_impl_v.4.smt2 |    0.185s | 26.232MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__reconciler.8.smt2 |    0.185s | 26.944MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__stateful_set.8.smt2 |    0.186s | 26.86MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__default_user_secret.4.smt2 |    0.186s | 26.64MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__UnifiedCrashAwareJournalRefinement_v.3.smt2 |    0.186s | 27.264MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetreeRefinement_v.21.smt2 |    0.187s | 25.708MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__admin_server_service.1.smt2 |    0.187s | 26.176MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.39.smt2 |    0.188s | 24.528MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetreeRefinement_v.25.smt2 |    0.188s | 25.864MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__headless_service.4.smt2 |    0.188s | 28.136MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log__UnboundedLog.27.smt2 |    0.189s | 25.652MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesBetree_v.9.smt2 |    0.189s | 24.16MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__config_map.1.smt2 |    0.189s | 26.992MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/array_vec.2.smt2 |    0.191s | 24.788MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-marshalling__IntegerMarshalling_v.29.smt2 |    0.191s | 24.544MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__UnifiedCrashAwareJournalRefinement_v.3.smt2 |    0.192s | 27.408MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__helper_invariants__proof__make_fluentbit_pod_spec_determined_by_spec_and_name.smt2 |    0.192s | 26.532MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBranchRefinement_v.21.smt2 |    0.192s | 25.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__role_binding.10.smt2 |    0.192s | 28.028MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__role.4.smt2 |    0.194s | 28.824MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationCrashAwareJournal_v__AllocationCrashAwareJournal.3.smt2 |    0.195s | 26.384MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__resource__service.6.smt2 |    0.195s | 26.572MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v__LinkedBetreeVars.8.smt2 |    0.195s | 26.172MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__AbstractCrashAwareSystemRefinement_v.29.smt2 |    0.195s | 28.164MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__config_map.7.smt2 |    0.195s | 28.616MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v__Refinement_v.26.smt2 |    0.196s | 25.752MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.107.smt2 |    0.196s | 26.748MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournalRefinement_v.29.smt2 |    0.196s | 24.992MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__client_service.7.smt2 |    0.196s | 28.396MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournalRefinement_v.17.smt2 |    0.197s | 25.068MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__AbstractCrashAwareSystemRefinement_v.29.smt2 |    0.197s | 27.928MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__rabbitmq_plugins.2.smt2 |    0.197s | 27.196MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-exec__Cache_v__Cache.4.smt2 |    0.197s | 24.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.102.smt2 |    0.198s | 26.284MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__erlang_cookie.1.smt2 |    0.198s | 26.908MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v__AllocationJournal.11.smt2 |    0.199s | 26.708MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__client_service.8.smt2 |    0.199s | 28.452MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.108.smt2 |    0.200s | 25.588MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__linearization.9.smt2 |    0.200s | 25.096MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetreeRefinement_v.21.smt2 |    0.200s | 25.628MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__reconciler.1.smt2 |    0.200s | 28.184MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/marshalling__IntegerMarshalling_v.29.smt2 |    0.201s | 24.656MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__role.2.smt2 |    0.204s | 26.744MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.108.smt2 |    0.204s | 25.544MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__reconciler.12.smt2 |    0.204s | 27.464MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v__Refinement_v.24.smt2 |    0.205s | 24.62MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__role_binding.6.smt2 |    0.205s | 27.912MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__reconciler.6.smt2 |    0.206s | 26.868MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__stateful_set.10.smt2 |    0.206s | 27.208MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v__LikesJournal.5.smt2 |    0.207s | 25.768MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesBetree_v__LikesBetree.7.smt2 |    0.209s | 26.616MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v__Refinement_v.34.smt2 |    0.210s | 25.396MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/verismo/tspec__math__cond_bound.1.smt2 |    0.211s | 20.316MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBranchRefinement_v.8.smt2 |    0.211s | 24.624MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-single_delivery_model_v.3.smt2 |    0.211s | 25.196MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__resource__role.5.smt2 |    0.212s | 27.048MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__role_binding.9.smt2 |    0.212s | 28.184MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__AbstractCrashAwareSystemRefinement_v.13.smt2 |    0.214s | 25.972MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-exec__context.5.smt2 |    0.215s | 24.04MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__rabbitmq_plugins.5.smt2 |    0.215s | 29.24MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v__Refinement_v.13.smt2 |    0.215s | 24.868MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournalRefinement_v.28.smt2 |    0.216s | 24.76MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__config_map.8.smt2 |    0.216s | 27.772MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v__Refinement_v.34.smt2 |    0.217s | 25.428MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__reconciler.11.smt2 |    0.218s | 27.448MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetreeRefinement_v.8.smt2 |    0.218s | 25.112MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v.13.smt2 |    0.221s | 23.352MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__resource__service_account.8.smt2 |    0.222s | 28.348MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__default_user_secret.6.smt2 |    0.222s | 29.66MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v__AllocationJournal.11.smt2 |    0.224s | 26.664MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesBetree_v__LikesBetree.8.smt2 |    0.224s | 26.904MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__reconciler.6.smt2 |    0.225s | 27.628MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.100.smt2 |    0.225s | 26.348MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__reconciler.1.smt2 |    0.225s | 28.684MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__erlang_cookie.2.smt2 |    0.226s | 27.456MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__resource__service.8.smt2 |    0.226s | 27.488MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__reconciler.5.smt2 |    0.227s | 27.916MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__reconciler.7.smt2 |    0.227s | 28.056MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetreeRefinement_v.23.smt2 |    0.227s | 26.98MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__AbstractCrashAwareSystemRefinement_v.26.smt2 |    0.228s | 27.916MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournalRefinement_v.15.smt2 |    0.229s | 24.86MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournalRefinement_v.25.smt2 |    0.229s | 24.836MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__FilteredBetreeRefinement_v.22.smt2 |    0.232s | 26.54MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/abstract_system__AbstractCrashAwareSystemRefinement_v.13.smt2 |    0.233s | 26.128MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.42.smt2 |    0.233s | 26.28MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__headless_service.7.smt2 |    0.236s | 28.656MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournalRefinement_v.25.smt2 |    0.238s | 24.832MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__rwlock__RwLockSpec.12.smt2 |    0.239s | 24.792MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v.42.smt2 |    0.239s | 26.236MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournalRefinement_v.3.smt2 |    0.239s | 25.692MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log.13.smt2 |    0.240s | 23.072MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__reconciler.8.smt2 |    0.240s | 29.032MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetreeRefinement_v.20.smt2 |    0.242s | 26.588MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetreeRefinement_v.29.smt2 |    0.242s | 27.284MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/process_manager__container_tree_spec_impl.10.smt2 |    0.244s | 29.792MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v.46.smt2 |    0.244s | 25.32MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournalRefinement_v.3.smt2 |    0.245s | 25.864MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__rabbitmq_plugins.7.smt2 |    0.245s | 28.876MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__service.2.smt2 |    0.246s | 28.12MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__headless_service.2.smt2 |    0.248s | 27.66MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__role.7.smt2 |    0.250s | 28.512MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournalRefinement_v.19.smt2 |    0.251s | 25.036MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__erlang_cookie.7.smt2 |    0.251s | 28.988MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__resource__daemon_set.6.smt2 |    0.252s | 31.396MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__rabbitmq_plugins.8.smt2 |    0.253s | 28.832MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__config_map.6.smt2 |    0.257s | 29.18MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournalRefinement_v.16.smt2 |    0.261s | 25.664MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__PagedJournalRefinement_v.19.smt2 |    0.262s | 25.084MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__service_account.6.smt2 |    0.262s | 27.8MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__service.7.smt2 |    0.263s | 29.58MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetreeRefinement_v.17.smt2 |    0.267s | 26.484MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournalRefinement_v.16.smt2 |    0.270s | 25.752MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournal_v__LikesJournal.11.smt2 |    0.272s | 26.42MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetreeRefinement_v.17.smt2 |    0.273s | 26.464MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__UnifiedCrashAwareJournal_v__UnifiedCrashAwareJournal.11.smt2 |    0.275s | 28.74MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__client_service.6.smt2 |    0.277s | 28.472MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__default_user_secret.7.smt2 |    0.278s | 29.088MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.111.smt2 |    0.279s | 26.892MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.111.smt2 |    0.279s | 27.048MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__config_map.8.smt2 |    0.280s | 29.428MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesBetree_v.14.smt2 |    0.281s | 25.936MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__headless_service.8.smt2 |    0.281s | 29.548MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__headless_service.6.smt2 |    0.282s | 29.02MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationCrashAwareJournalRefinement_v.4.smt2 |    0.292s | 29.804MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBranchRefinement_v.17.smt2 |    0.294s | 23.512MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__proof__liveness__spec.1.smt2 |    0.296s | 30.34MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetreeRefinement_v.18.smt2 |    0.302s | 26.824MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.44.smt2 |    0.303s | 23.536MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__headless_service.7.smt2 |    0.303s | 29.472MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesBetree_v.14.smt2 |    0.305s | 26.02MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__LinkedJournal_v__LinkedJournal.11.smt2 |    0.306s | 25.408MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.105.smt2 |    0.309s | 28.392MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v__LinkedBetreeVars.7.smt2 |    0.316s | 30.072MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.105.smt2 |    0.320s | 28.312MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournalRefinement_v.24.smt2 |    0.321s | 25.84MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v.39.smt2 |    0.323s | 22.768MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-exec__context.4.smt2 |    0.323s | 24.168MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-journal__PagedJournalRefinement_v.16.smt2 |    0.328s | 25.592MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__proof__liveness__spec.5.smt2 |    0.334s | 31.58MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__proof__liveness__proof.9.smt2 |    0.334s | 31.188MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.36.smt2 |    0.337s | 23.208MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v__LinkedBetreeVars.2.smt2 |    0.343s | 31.328MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v.39.smt2 |    0.344s | 22.632MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/process_manager__container_tree_spec_impl.4.smt2 |    0.351s | 29.128MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v__LinkedBetreeVars.2.smt2 |    0.353s | 31.288MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.34.smt2 |    0.363s | 24.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__headless_service.6.smt2 |    0.363s | 30.312MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__spec.9.smt2 |    0.366s | 32.988MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/2019-Gleiss/non-interference/8-ni-explicit-flow-while.spec.smt2 |    0.368s | 66.492MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__spec.4.smt2 |    0.369s | 32.932MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v__Refinement_v.29.smt2 |    0.371s | 25.516MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__spec.1.smt2 |    0.373s | 32.76MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__spec.10.smt2 |    0.374s | 32.908MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__service.6.smt2 |    0.378s | 30.312MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationCrashAwareJournalRefinement_v.3.smt2 |    0.379s | 30.612MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/journal__LinkedJournalRefinement_v.24.smt2 |    0.385s | 27.46MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__spec.10.smt2 |    0.397s | 33.952MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__admin_server_service.5.smt2 |    0.407s | 29.328MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v.96.smt2 |    0.409s | 26.248MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__proof.12.smt2 |    0.410s | 32.932MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__liveness__spec.4.smt2 |    0.412s | 33.524MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/verified-storage-smt-verified-storage-smt-storage-node-kv__kvimpl_v.4.smt2 |    0.416s | 25.66MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__spec.11.smt2 |    0.417s | 33.64MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__proof.11.smt2 |    0.425s | 33.828MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__client_service.3.smt2 |    0.427s | 28.384MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/verismo/tspec_e__array__sort.5.smt2 |    0.429s | 24.696MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__erlang_cookie.5.smt2 |    0.429s | 30.028MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetreeRefinement_v.10.smt2 |    0.435s | 25.156MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__helper_invariants__proof.10.smt2 |    0.438s | 34.168MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v__Refinement_v.21.smt2 |    0.442s | 26.072MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__liveness__spec.10.smt2 |    0.443s | 33.736MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__proof.11.smt2 |    0.447s | 36.548MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__resource__service.7.smt2 |    0.453s | 28.644MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetreeRefinement_v.34.smt2 |    0.455s | 26.28MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__helper_invariants__proof.7.smt2 |    0.457s | 37.02MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__proof.7.smt2 |    0.461s | 36.736MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v__Refinement_v.22.smt2 |    0.462s | 25.804MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v__Refinement_v.31.smt2 |    0.464s | 25.316MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.36.smt2 |    0.465s | 26.588MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__headless_service.5.smt2 |    0.465s | 31.288MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v__Refinement_v.22.smt2 |    0.468s | 25.876MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__proof.14.smt2 |    0.477s | 36.788MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v.30.smt2 |    0.479s | 25.148MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournal_v__LikesJournal.8.smt2 |    0.482s | 27.704MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__helper_invariants__proof.13.smt2 |    0.485s | 36.64MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/2019-Gleiss/sensitivity/12-sens-diff-up-to-forall-k.spec.smt2 |    0.485s | 65.212MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetreeRefinement_v.32.smt2 |    0.486s | 30.64MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v__Refinement_v.16.smt2 |    0.487s | 25.824MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__UnifiedCrashAwareJournal_v.15.smt2 |    0.495s | 26.512MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_v.32.smt2 |    0.501s | 23.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__proof__liveness__proof.4.smt2 |    0.508s | 31.444MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.37.smt2 |    0.515s | 25.452MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__proof.8.smt2 |    0.520s | 34.984MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__proof__liveness__spec.2.smt2 |    0.525s | 32.316MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__liveness__proof.9.smt2 |    0.540s | 36.428MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-single_delivery_model_v.1.smt2 |    0.547s | 27.276MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__UnifiedCrashAwareJournal_v__UnifiedCrashAwareJournal.3.smt2 |    0.565s | 30.184MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log__UnboundedLog.4.smt2 |    0.572s | 28.536MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.47.smt2 |    0.577s | 27.848MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v__Refinement_v.23.smt2 |    0.577s | 25.792MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-host_impl_v.10.smt2 |    0.578s | 30.092MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__proof.9.smt2 |    0.583s | 39.832MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__spec.2.smt2 |    0.588s | 33.38MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetreeRefinement_v.21.smt2 |    0.590s | 27.964MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationCrashAwareJournalRefinement_v.7.smt2 |    0.597s | 32.8MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__liveness__proof.4.smt2 |    0.609s | 34.224MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-cmessage_v.2.smt2 |    0.612s | 25.548MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log__UnboundedLog.20.smt2 |    0.614s | 29.792MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log__UnboundedLog.8.smt2 |    0.615s | 28.62MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log__UnboundedLog.2.smt2 |    0.619s | 28.66MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PagedBetreeRefinement_v.25.smt2 |    0.634s | 26.68MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBranchRefinement_v.9.smt2 |    0.645s | 26.544MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PagedBetreeRefinement_v.25.smt2 |    0.655s | 26.668MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log__UnboundedLog.13.smt2 |    0.656s | 29.848MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBranchRefinement_v.9.smt2 |    0.677s | 26.444MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__proof.9.smt2 |    0.683s | 37.916MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-abstract_system__AbstractCrashAwareSystemRefinement_v.25.smt2 |    0.688s | 31.1MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v__LinkedBetreeVars.5.smt2 |    0.696s | 34.672MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log__UnboundedLog.16.smt2 |    0.707s | 29.784MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__daemon_set_match.2.smt2 |    0.712s | 37.116MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__resource__daemon_set.4.smt2 |    0.712s | 30.18MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__liveness__stateful_set_match.2.smt2 |    0.722s | 38.56MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesBetree_v.13.smt2 |    0.737s | 27.268MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__spec.3.smt2 |    0.742s | 35.704MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal12.smt2 |    0.754s | 126.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log__UnboundedLog.30.smt2 |    0.772s | 31.772MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-cmessage_v.5.smt2 |    0.791s | 28.888MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournalRefinement_v.3.smt2 |    0.805s | 28.248MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesJournalRefinement_v.4.smt2 |    0.811s | 28.3MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v.44.smt2 |    0.814s | 29.316MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__config_map.4.smt2 |    0.815s | 30.824MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__LikesJournalRefinement_v.3.smt2 |    0.825s | 28.296MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__resource__headless_service.3.smt2 |    0.828s | 30.284MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v__LinkedBetreeVars.3.smt2 |    0.833s | 32.056MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v__Refinement_v.35.smt2 |    0.838s | 30.56MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetreeRefinement_v.33.smt2 |    0.877s | 32.48MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournalRefinement_v.8.smt2 |    0.892s | 32.272MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__proof.9.smt2 |    0.929s | 43.272MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBranchRefinement_v.16.smt2 |    0.982s | 28.656MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationCrashAwareJournalRefinement_v.6.smt2 |    1.046s | 34.732MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v.28.smt2 |    1.073s | 35.828MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__stateful_set_match.5.smt2 |    1.108s | 39.696MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBranch_v__Refinement_v.37.smt2 |    1.160s | 33.264MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBranchRefinement_v.7.smt2 |    1.161s | 28.768MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBranch_v__Refinement_v.32.smt2 |    1.228s | 30.992MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/process_manager__container_tree_spec_impl.16.smt2 |    1.233s | 45.5MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/process_manager__container_tree_spec_impl.12.smt2 |    1.255s | 46.136MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.41.smt2 |    1.281s | 31.08MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v__AllocationJournal.12.smt2 |    1.320s | 35.916MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournalRefinement_v.6.smt2 |    1.330s | 34.84MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__LinkedBetree_v__LinkedBetreeVars.6.smt2 |    1.356s | 39.512MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__resource_match.9.smt2 |    1.384s | 43.48MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v__LinkedBetreeVars.6.smt2 |    1.407s | 39.412MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/noderep-smt-spec__unbounded_log__UnboundedLog.22.smt2 |    1.442s | 37.192MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__spec.15.smt2 |    1.504s | 64.968MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/atmosphere/process_manager__container_tree_spec_impl.14.smt2 |    1.505s | 49.028MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__exec__reconciler.3.smt2 |    1.649s | 33.44MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__spec.18.smt2 |    1.741s | 64.488MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__reconciler.3.smt2 |    1.801s | 34.44MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-single_delivery_model_v.7.smt2 |    1.963s | 35.436MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/verismo/tspec_e__array__sort.7.smt2 |    2.161s | 36.14MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__FilteredBetreeRefinement_v.30.smt2 |    2.235s | 36.5MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__exec__reconciler.3.smt2 |    2.282s | 35.48MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__exec__resource__stateful_set.4.smt2 |    2.496s | 36.284MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBranchRefinement_v.22.smt2 |    2.595s | 35.008MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournalRefinement_v.5.smt2 |    3.013s | 41.752MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__UnifiedCrashAwareJournalRefinement_v.7.smt2 |    3.141s | 44.496MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/exec__Cache_v__Cache.6.smt2 |    3.789s | 57.22MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__proof__liveness__terminate.1.smt2 |    4.343s | 47.38MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal6.smt2 |    4.546s | 750.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/2019-Gleiss/sensitivity/7-sens-diff-up-to-explicit-k-sum.spec.smt2 |    4.846s | 449.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/2019-Gleiss/sensitivity/10-sens-equal-k.spec.smt2 |    4.941s | 256.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__LinkedBetree_v.112.smt2 |    5.021s | 44.356MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__liveness__spec.15.smt2 |    5.027s | 79.02MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/2019-Gleiss/sensitivity/8-sens-explicit-swap.spec.smt2 |    5.807s | 257.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal11.smt2 |    6.178s | 344.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/2019-Gleiss/sensitivity/11-sens-equal-k-twice.spec.smt2 |    6.294s | 376.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__proof.7.smt2 |    6.887s | 41.328MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-marshal_ironsht_specific_v.46.smt2 |    6.920s | 55.412MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/2019-Gleiss/non-interference/9-ni-equal-output.spec.smt2 |    7.856s | 176.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__UnifiedCrashAwareJournal_v__UnifiedCrashAwareJournal.7.smt2 |    8.531s | 62.896MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__liveness__proof.7.smt2 |    9.026s | 40.94MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/2019-Gleiss/sensitivity/9-sens-explicit-swap-prop2.spec.smt2 |    9.207s | 437.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-allocation_layer__AllocationJournal_v.43.smt2 |    9.935s | 53.288MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__AllocationJournal_v.43.smt2 |    9.976s | 53.336MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__LikesBetree_v__LikesBetree.2.smt2 |   10.680s | 74.04MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal14.smt2 |   10.839s | 1563.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/2019-Gleiss/sensitivity/5-sens-two-arrays-equal-k.spec.smt2 |   11.269s | 1309.0MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__terminate.1.smt2 |   14.559s | 88.748MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__proof__helper_invariants__proof__lemma_always_resource_object_create_or_update_request_msg_has_one_controller_ref_and_no_finalizers.smt2 |   16.455s | 51.34MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/betree__PivotBetreeRefinement_v.28.smt2 |   17.016s | 54.496MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetreeRefinement_v.29.smt2 |   17.561s | 54.976MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/splinterdb/allocation_layer__UnifiedCrashAwareJournalRefinement_v.8.smt2 |   17.798s | 79.624MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/splinterdb-smt-betree__PivotBetreeRefinement_v.28.smt2 |   18.613s | 54.476MiB| unsat | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/systems/ironkv-smt-delegation_map_v.53.smt2 |   20.009s | 39.604MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__helper_invariants__proof__lemma_always_no_update_status_request_msg_not_from_bc_in_flight_of_daemon_set.smt2 |   20.010s | 66.4MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__helper_invariants__proof__lemma_resource_update_request_msg_implies_key_in_reconcile_equals.smt2 |   20.011s | 65.8MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__proof__lemma_always_no_update_status_request_msg_not_from_bc_in_flight_of_stateful_set.smt2 |   20.011s | 68.004MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__zookeeper_api__lemma_zk_request_implies_step_helper.smt2 |   20.011s | 67.944MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__daemon_set_match__lemma_from_after_get_daemon_set_step_to_after_update_daemon_set_step.smt2 |   20.011s | 73.232MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__proof.1.smt2 |   20.011s | 66.396MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__proof.5.smt2 |   20.011s | 67.044MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__proof.6.smt2 |   20.011s | 72.44MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__proof__helper_invariants__proof__lemma_always_response_at_after_get_resource_step_is_resource_get_response.smt2 |   20.011s | 49.896MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__zookeeper_api.15.smt2 |   20.011s | 65.536MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__proof.3.smt2 |   20.011s | 72.992MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__resource_match.2.smt2 |   20.011s | 80.2MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal61.smt2 |   20.011s | 54.468MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal36.smt2 |   20.011s | 60.208MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__resource_match.7.smt2 |   20.012s | 73.82MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__helper_invariants__proof__lemma_eventually_always_every_resource_create_request_implies_at_after_create_resource_step.smt2 |   20.012s | 77.148MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__daemon_set_match__lemma_daemon_set_state_matches_at_after_update_daemon_set_step.smt2 |   20.012s | 74.492MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__proof__lemma_always_no_update_status_request_msg_in_flight_of_except_stateful_set.smt2 |   20.012s | 64.256MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__zookeeper_api__lemma_eventually_always_every_zk_create_node_request_implies_at_after_create_zk_node_step.smt2 |   20.012s | 66.596MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__liveness__proof.6.smt2 |   20.012s | 72.304MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__proof__lemma_resource_create_or_update_request_msg_implies_key_in_reconcile_equals.smt2 |   20.012s | 76.336MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal56.smt2 |   20.012s | 77.084MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal37.smt2 |   20.012s | 57.244MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal72.smt2 |   20.012s | 91.788MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal9.smt2 |   20.012s | 57.968MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal52.smt2 |   20.012s | 71.036MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal63.smt2 |   20.012s | 66.024MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal60.smt2 |   20.012s | 54.496MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__helper_invariants__proof__lemma_always_resource_object_create_or_update_request_msg_has_one_controller_ref_and_no_finalizers.smt2 |   20.013s | 73.912MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__liveness__resource_match.7.smt2 |   20.013s | 75.732MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__helper_invariants__proof__lemma_always_cm_rv_stays_unchanged.smt2 |   20.013s | 87.908MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__resource_match__lemma_from_after_get_resource_step_to_after_create_resource_step.smt2 |   20.013s | 66.776MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__proof__liveness__proof.5.smt2 |   20.013s | 66.88MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__zookeeper_api.16.smt2 |   20.013s | 80.904MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__resource_match.7.smt2 |   20.013s | 83.264MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__resource_match__lemma_from_key_not_exists_to_receives_not_found_resp_at_after_get_resource_step.smt2 |   20.013s | 75.64MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__liveness__proof.1.smt2 |   20.013s | 69.276MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__zookeeper_api.12.smt2 |   20.013s | 75.868MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__resource_match.1.smt2 |   20.013s | 76.2MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal54.smt2 |   20.013s | 64.116MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg9.smt2 |   20.013s | 61.044MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__proof__lemma_eventually_always_every_resource_update_request_implies_at_after_update_resource_step.smt2 |   20.014s | 82.752MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__helper_invariants__proof.4.smt2 |   20.014s | 72.028MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__proof.1.smt2 |   20.014s | 66.236MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__liveness__stateful_set_match__lemma_from_key_exists_to_receives_ok_resp_at_after_get_stateful_set_step.smt2 |   20.014s | 88.508MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__proof__helper_invariants__owner_ref.2.smt2 |   20.014s | 52.964MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__proof__liveness__resource_match.6.smt2 |   20.014s | 78.204MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg20.smt2 |   20.014s | 73.792MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal82.smt2 |   20.014s | 119.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__unchangeable.3.smt2 |   20.015s | 67.204MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__helper_invariants__unchangeable.3.smt2 |   20.015s | 67.428MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__helper_invariants__proof.12.smt2 |   20.015s | 66.536MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal22.smt2 |   20.015s | 47.76MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal50.smt2 |   20.015s | 75.04MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__helper_invariants__proof__lemma_eventually_always_every_resource_update_request_implies_at_after_update_resource_step.smt2 |   20.016s | 86.78MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__proof__liveness__resource_match.1.smt2 |   20.016s | 69.052MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal25.smt2 |   20.016s | 106.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal48.smt2 |   20.016s | 82.94MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg3.smt2 |   20.016s | 93.936MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal64.smt2 |   20.017s | 65.664MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal38.smt2 |   20.017s | 49.628MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal8.smt2 |   20.017s | 84.608MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal20.smt2 |   20.017s | 69.916MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal3.smt2 |   20.017s | 71.88MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__resource_match.5.smt2 |   20.018s | 83.716MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal69.smt2 |   20.018s | 155.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal65.smt2 |   20.018s | 62.456MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg33.smt2 |   20.018s | 70.832MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal33.smt2 |   20.019s | 113.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal34.smt2 |   20.019s | 91.404MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg22.smt2 |   20.019s | 53.356MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__proof__lemma_eventually_always_object_in_response_at_after_update_resource_step_is_same_as_etcd.smt2 |   20.020s | 158.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__proof__liveness__proof.2.smt2 |   20.020s | 66.064MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal68.smt2 |   20.020s | 142.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal71.smt2 |   20.020s | 108.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rotate-goal2.smt2 |   20.020s | 105.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal19.smt2 |   20.020s | 98.708MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal27.smt2 |   20.020s | 66.256MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal73.smt2 |   20.021s | 95.76MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg48.smt2 |   20.021s | 126.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg2.smt2 |   20.021s | 79.592MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal53.smt2 |   20.022s | 106.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg25.smt2 |   20.023s | 77.548MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal26.smt2 |   20.023s | 62.296MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/2019-Gleiss/hamming-weight/1-hw-equal-arrays.spec.smt2 |   20.023s | 255.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__unchangeable.5.smt2 |   20.024s | 146.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__proof__lemma_eventually_always_no_delete_resource_request_msg_in_flight.smt2 |   20.024s | 72.652MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__proof__liveness__resource_match.4.smt2 |   20.024s | 69.14MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal60.smt2 |   20.024s | 144.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal70.smt2 |   20.024s | 102.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__proof__helper_invariants__proof__lemma_always_no_update_status_request_msg_in_flight.smt2 |   20.025s | 66.624MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__daemon_set_match__lemma_from_key_exists_to_receives_ok_resp_at_after_get_daemon_set_step.smt2 |   20.025s | 81.176MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg12.smt2 |   20.025s | 220.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal3.smt2 |   20.025s | 232.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal47.smt2 |   20.026s | 175.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal2.smt2 |   20.026s | 53.964MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal4.smt2 |   20.026s | 218.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__resource_match.8.smt2 |   20.027s | 86.048MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__helper_invariants__unchangeable.1.smt2 |   20.027s | 70.264MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg14.smt2 |   20.027s | 147.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg7.smt2 |   20.027s | 218.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal86.smt2 |   20.028s | 78.976MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg81.smt2 |   20.028s | 232.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal2.smt2 |   20.028s | 51.96MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal77.smt2 |   20.028s | 51.18MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20230314-Jaroslav-Bendik-Certora/52759_b3ecd2335fd16ec2eee2_9_UFDTLIA.smt2 |   20.028s | 48.588MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__helper_invariants__validation__lemma_always_object_in_resource_update_request_msg_has_smaller_rv_than_etcd.smt2 |   20.029s | 70.46MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__zookeeper_api.1.smt2 |   20.029s | 69.496MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal38.smt2 |   20.029s | 65.032MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__helper_invariants__proof__lemma_eventually_always_every_resource_update_request_implies_at_after_update_resource_step.smt2 |   20.030s | 78.12MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal14.smt2 |   20.030s | 182.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal23.smt2 |   20.030s | 269.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal21.smt2 |   20.030s | 174.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal47.smt2 |   20.030s | 121.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal20.smt2 |   20.030s | 82.708MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__proof.2.smt2 |   20.031s | 65.228MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__helper_invariants__unchangeable.4.smt2 |   20.031s | 67.864MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__liveness__spec.13.smt2 |   20.031s | 73.56MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal39.smt2 |   20.031s | 148.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg78.smt2 |   20.031s | 359.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal3.smt2 |   20.031s | 84.712MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__helper_invariants__proof__lemma_eventually_always_every_resource_create_request_implies_at_after_create_resource_step.smt2 |   20.032s | 72.612MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit_config__proof__helper_invariants__proof__lemma_resource_create_or_update_request_msg_implies_key_in_reconcile_equals.smt2 |   20.032s | 70.484MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal35.smt2 |   20.032s | 98.688MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg11.smt2 |   20.032s | 279.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg82.smt2 |   20.032s | 258.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__resource_match.4.smt2 |   20.033s | 74.14MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal82.smt2 |   20.033s | 312.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal17.smt2 |   20.033s | 332.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal29.smt2 |   20.033s | 86.34MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal78.smt2 |   20.034s | 334.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg79.smt2 |   20.034s | 374.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal12.smt2 |   20.035s | 339.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal19.smt2 |   20.035s | 350.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal27.smt2 |   20.035s | 330.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg5.smt2 |   20.035s | 245.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal57.smt2 |   20.035s | 69.18MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__terminate.1.smt2 |   20.036s | 85.76MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal84.smt2 |   20.036s | 80.148MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal10.smt2 |   20.036s | 305.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg19.smt2 |   20.036s | 334.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/fluent-smt-fluent_controller__fluentbit__proof__liveness__resource_match.1.smt2 |   20.037s | 77.376MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal31.smt2 |   20.037s | 322.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal45.smt2 |   20.037s | 325.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal29.smt2 |   20.037s | 342.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal62.smt2 |   20.037s | 55.416MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal28.smt2 |   20.037s | 98.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal16.smt2 |   20.038s | 327.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal75.smt2 |   20.038s | 343.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg49.smt2 |   20.038s | 320.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rotate-goal8.smt2 |   20.038s | 189.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal69.smt2 |   20.038s | 159.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal6.smt2 |   20.039s | 314.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg80.smt2 |   20.039s | 223.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rotate-goal4.smt2 |   20.039s | 178.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal61.smt2 |   20.039s | 61.284MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal73.smt2 |   20.039s | 183.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-rabbitmq-smt-rabbitmq_controller__proof__liveness__stateful_set_match.1.smt2 |   20.040s | 81.72MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal5.smt2 |   20.040s | 345.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal30.smt2 |   20.040s | 325.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rotate-goal6.smt2 |   20.040s | 172.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal18.smt2 |   20.041s | 382.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal36.smt2 |   20.041s | 361.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20241211-verus/anvil/zookeeper-smt-zookeeper_controller__proof__liveness__terminate.2.smt2 |   20.042s | 489.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal81.smt2 |   20.042s | 335.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg23.smt2 |   20.042s | 224.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal56.smt2 |   20.042s | 87.92MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal59.smt2 |   20.043s | 350.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg13.smt2 |   20.044s | 423.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rotate-goal3.smt2 |   20.044s | 240.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/2019-Gleiss/hamming-weight/3-hw-swap-and-two-arrays.spec.smt2 |   20.044s | 490.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal32.smt2 |   20.045s | 177.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg18.smt2 |   20.046s | 267.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg77.smt2 |   20.046s | 396.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rotate-goal1.smt2 |   20.046s | 185.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/rotate-goal7.smt2 |   20.046s | 111.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal64.smt2 |   20.047s | 71.268MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg17.smt2 |   20.048s | 359.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal30.smt2 |   20.048s | 314.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rev-equiv-goal4.smt2 |   20.049s | 372.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal53.smt2 |   20.049s | 98.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal46.smt2 |   20.050s | 331.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal58.smt2 |   20.050s | 607.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg6.smt2 |   20.050s | 377.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal7.smt2 |   20.051s | 357.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg50.smt2 |   20.051s | 451.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg10.smt2 |   20.053s | 249.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal49.smt2 |   20.054s | 173.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal62.smt2 |   20.055s | 184.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal11.smt2 |   20.056s | 325.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal75.smt2 |   20.056s | 212.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal77.smt2 |   20.057s | 697.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg16.smt2 |   20.057s | 534.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal80.smt2 |   20.057s | 152.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal85.smt2 |   20.059s | 76.124MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal68.smt2 |   20.060s | 160.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg8.smt2 |   20.061s | 618.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg21.smt2 |   20.064s | 170.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal13.smt2 |   20.067s | 326.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal11.smt2 |   20.071s | 138.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal76.smt2 |   20.076s | 634.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal72.smt2 |   20.076s | 302.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal15.smt2 |   20.077s | 143.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal74.smt2 |   20.078s | 336.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rotate-goal5.smt2 |   20.083s | 311.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal12.smt2 |   20.091s | 441.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal83.smt2 |   20.092s | 462.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal1.smt2 |   20.094s | 150.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rotate-goal7.smt2 |   20.096s | 131.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg84.smt2 |   20.103s | 1092.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal52.smt2 |   20.105s | 347.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal58.smt2 |   20.105s | 1014.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg86.smt2 |   20.107s | 1188.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal43.smt2 |   20.107s | 717.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal65.smt2 |   20.109s | 1246.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal79.smt2 |   20.110s | 319.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rev-equiv-goal5.smt2 |   20.116s | 653.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal2.smt2 |   20.119s | 290.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal13.smt2 |   20.123s | 255.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal49.smt2 |   20.123s | 1219.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg85.smt2 |   20.134s | 1458.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rev-equiv-goal3.smt2 |   20.139s | 372.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rotate-goal9.smt2 |   20.147s | 180.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal12.smt2 |   20.154s | 273.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal16.smt2 |   20.155s | 192.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal7.smt2 |   20.157s | 139.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/2019-Gleiss/sensitivity/2-sens-equal-sums-two-arrays.spec.smt2 |   20.160s | 1599.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg83.smt2 |   20.164s | 1338.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal4.smt2 |   20.167s | 1036.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal17.smt2 |   20.180s | 253.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal76.smt2 |   20.184s | 626.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rev-equiv-goal2.smt2 |   20.190s | 695.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal5.smt2 |   20.194s | 223.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg75.smt2 |   20.199s | 1780.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal18.smt2 |   20.199s | 239.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal5.smt2 |   20.200s | 468.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal67.smt2 |   20.204s | 1281.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal37.smt2 |   20.207s | 746.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rev-equiv-goal8.smt2 |   20.209s | 315.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal87.smt2 |   20.221s | 1531.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal1.smt2 |   20.227s | 1915.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/2019-Gleiss/sensitivity/6-sens-diff-up-to-explicit-k.spec.smt2 |   20.227s | 2430.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal7.smt2 |   20.232s | 321.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal41.smt2 |   20.232s | 1664.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg28.smt2 |   20.236s | 2409.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rev-equiv-goal7.smt2 |   20.242s | 332.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg76.smt2 |   20.244s | 1880.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal86.smt2 |   20.250s | 807.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal6.smt2 |   20.251s | 452.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/2019-Gleiss/hamming-weight/4-hw-swap-in-array-lemma.spec.smt2 |   20.254s | 2687.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal1.smt2 |   20.263s | 543.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg4.smt2 |   20.266s | 2264.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal14.smt2 |   20.266s | 321.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/2019-Gleiss/sensitivity/1-sens-equal-sums.spec.smt2 |   20.272s | 2934.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/sg/goal-sg1.smt2 |   20.282s | 2991.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/2019-Gleiss/hamming-weight/2-hw-last-position-swapped.spec.smt2 |   20.285s | 2819.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/2019-Gleiss/hamming-weight/4-hw-swap-in-array-full.spec.smt2 |   20.293s | 2984.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal15.smt2 |   20.342s | 469.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/rev-equiv-goal7.smt2 |   20.362s | 543.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rev-equiv-goal1.smt2 |   20.364s | 320.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal14.smt2 |   20.385s | 1217.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal85.smt2 |   20.401s | 2384.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/clam/goal28.smt2 |   20.407s | 4490.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/rev-equiv-goal6.smt2 |   20.410s | 1332.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal51.smt2 |   20.420s | 1286.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal59.smt2 |   20.482s | 4153.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal48.smt2 |   20.527s | 3989.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal1.smt2 |   20.530s | 1621.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal8.smt2 |   20.531s | 850.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal10.smt2 |   20.571s | 1010.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal9.smt2 |   20.571s | 1210.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal9.smt2 |   20.576s | 1217.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/nichomachus-goal1.smt2 |   20.599s | 1849.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal50.smt2 |   20.619s | 2070.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/rev-equiv-goal6.smt2 |   20.626s | 1065.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/rotate-goal4.smt2 |   20.645s | 1224.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal8.smt2 |   20.653s | 1106.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/nichomachus-goal6.smt2 |   20.654s | 2118.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/nichomachus-goal3.smt2 |   20.657s | 2126.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/isaplanner/goal84.smt2 |   20.716s | 5025.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/rotate-goal8.smt2 |   20.723s | 1345.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/nichomachus-goal2.smt2 |   20.743s | 3007.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/rev-equiv-goal3.smt2 |   20.760s | 1357.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/nichomachus-goal9.smt2 |   20.783s | 3046.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal2.smt2 |   20.919s | 1837.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/nichomachus-goal7.smt2 |   20.950s | 1845.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/nichomachus-goal5.smt2 |   21.032s | 2365.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/nichomachus-goal7.smt2 |   21.056s | 2271.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/nichomachus-goal8.smt2 |   21.074s | 2072.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal13.smt2 |   21.075s | 2232.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/bsearch-tree-goal10.smt2 |   21.194s | 2942.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal13.smt2 |   21.330s | 3181.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal1.smt2 |   21.362s | 3287.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/nichomachus-goal3.smt2 |   21.373s | 3254.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/nichomachus-goal4.smt2 |   21.383s | 3104.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/amortize-queue-goal15.smt2 |   21.386s | 3336.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal12.smt2 |   21.388s | 3359.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/nichomachus-goal4.smt2 |   21.389s | 3915.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal3.smt2 |   21.398s | 3256.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/nichomachus-goal8.smt2 |   21.406s | 3316.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal6.smt2 |   21.411s | 3277.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/nichomachus-goal6.smt2 |   21.422s | 3347.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/nichomachus-goal5.smt2 |   21.425s | 3428.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/hipspec/sg/nichomachus-goal9.smt2 |   21.426s | 3393.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal2.smt2 |   21.426s | 3488.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal4.smt2 |   21.429s | 3571.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal10.smt2 |   21.443s | 3590.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal11.smt2 |   21.450s | 3666.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal9.smt2 |   21.450s | 3661.0MiB| timeout | 0 |  |  |
|non-incremental/UFDTLIA/20172804-Barrett/induction-vmcai2015/leon/heap-goal7.smt2 |   21.461s | 3675.0MiB| timeout | 0 |  |  |
