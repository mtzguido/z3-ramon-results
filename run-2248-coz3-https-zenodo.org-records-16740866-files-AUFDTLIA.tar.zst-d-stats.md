# .

* SAT 46
* UNSAT 697
* TIMEOUT 52
* UNKNOWN 0

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/AUFDTLIA.tar.zst?download=1 | Source list: quantifier_benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-AUFDTLIA.tar.zst-d
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: c3f5365a95a7eac2419a2f95ff240909f275cc08
Z3 branch: c3f5365a95a7eac2419a2f95ff240909f275cc08
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/AUFDTLIA.tar.zst?download=1
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
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree30.smt2 |    0.013s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german117.smt2 |    0.014s | 18.984MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german4.smt2 |    0.014s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german104.smt2 |    0.014s | 19.064MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german52.smt2 |    0.014s | 19.08MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german76.smt2 |    0.014s | 18.84MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german31.smt2 |    0.014s | 19.08MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german68.smt2 |    0.014s | 18.968MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german106.smt2 |    0.014s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german14.smt2 |    0.014s | 19.096MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german3.smt2 |    0.014s | 18.94MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german107.smt2 |    0.014s | 19.036MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german84.smt2 |    0.014s | 18.976MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german88.smt2 |    0.014s | 19.116MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree159.smt2 |    0.014s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree183.smt2 |    0.014s | 18.952MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree239.smt2 |    0.014s | 19.04MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree289.smt2 |    0.014s | 19.144MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree452.smt2 |    0.014s | 19.108MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree72.smt2 |    0.014s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree71.smt2 |    0.014s | 19.188MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree237.smt2 |    0.014s | 19.036MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree7.smt2 |    0.014s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree181.smt2 |    0.014s | 19.128MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german19.smt2 |    0.015s | 19.008MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german78.smt2 |    0.015s | 19.024MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german49.smt2 |    0.015s | 18.956MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german87.smt2 |    0.015s | 18.896MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german81.smt2 |    0.015s | 18.964MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german9.smt2 |    0.015s | 18.856MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german24.smt2 |    0.015s | 18.968MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german93.smt2 |    0.015s | 18.892MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german29.smt2 |    0.015s | 18.936MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german18.smt2 |    0.015s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german15.smt2 |    0.015s | 18.884MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german2.smt2 |    0.015s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german22.smt2 |    0.015s | 19.012MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german41.smt2 |    0.015s | 19.0MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german10.smt2 |    0.015s | 18.992MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german5.smt2 |    0.015s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german119.smt2 |    0.015s | 18.948MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german122.smt2 |    0.015s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german77.smt2 |    0.015s | 18.868MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german25.smt2 |    0.015s | 18.848MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german26.smt2 |    0.015s | 19.02MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german95.smt2 |    0.015s | 19.02MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german20.smt2 |    0.015s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german94.smt2 |    0.015s | 19.024MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german164.smt2 |    0.015s | 19.568MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german56.smt2 |    0.015s | 19.004MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german135.smt2 |    0.015s | 18.868MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german55.smt2 |    0.015s | 18.888MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german6.smt2 |    0.015s | 18.868MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german72.smt2 |    0.015s | 18.924MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree149.smt2 |    0.015s | 19.024MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree515.smt2 |    0.015s | 19.14MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree24.smt2 |    0.015s | 19.12MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree35.smt2 |    0.015s | 19.116MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree318.smt2 |    0.015s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree518.smt2 |    0.015s | 19.196MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree326.smt2 |    0.015s | 19.148MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree297.smt2 |    0.015s | 18.944MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree290.smt2 |    0.015s | 19.06MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree219.smt2 |    0.015s | 19.184MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree155.smt2 |    0.015s | 18.984MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree175.smt2 |    0.015s | 19.176MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree28.smt2 |    0.015s | 19.012MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree460.smt2 |    0.015s | 19.02MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree55.smt2 |    0.015s | 18.972MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree191.smt2 |    0.015s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree85.smt2 |    0.015s | 18.948MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree157.smt2 |    0.015s | 18.936MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree70.smt2 |    0.015s | 19.076MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree281.smt2 |    0.015s | 19.052MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree320.smt2 |    0.015s | 19.076MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree53.smt2 |    0.015s | 19.152MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree211.smt2 |    0.015s | 19.136MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree420.smt2 |    0.015s | 19.0MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree79.smt2 |    0.015s | 19.032MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree372.smt2 |    0.015s | 18.916MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree487.smt2 |    0.015s | 18.92MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree294.smt2 |    0.015s | 19.16MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree524.smt2 |    0.015s | 18.952MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree118.smt2 |    0.015s | 19.1MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree245.smt2 |    0.015s | 19.14MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree146.smt2 |    0.015s | 19.024MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree370.smt2 |    0.015s | 18.956MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree500.smt2 |    0.015s | 19.152MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree283.smt2 |    0.015s | 19.136MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree5.smt2 |    0.015s | 19.076MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree308.smt2 |    0.015s | 19.188MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree75.smt2 |    0.015s | 19.096MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree413.smt2 |    0.015s | 19.012MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree422.smt2 |    0.015s | 19.204MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree223.smt2 |    0.015s | 19.2MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree8.smt2 |    0.015s | 18.972MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree23.smt2 |    0.015s | 19.084MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree231.smt2 |    0.015s | 19.032MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree82.smt2 |    0.015s | 19.056MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree54.smt2 |    0.015s | 18.956MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree216.smt2 |    0.015s | 19.184MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree439.smt2 |    0.015s | 19.196MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree272.smt2 |    0.015s | 19.188MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree198.smt2 |    0.015s | 19.136MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree73.smt2 |    0.015s | 19.124MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree386.smt2 |    0.015s | 19.172MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree61.smt2 |    0.015s | 19.184MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree300.smt2 |    0.015s | 19.14MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree339.smt2 |    0.015s | 19.156MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree322.smt2 |    0.015s | 18.968MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree3.smt2 |    0.015s | 19.092MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree331.smt2 |    0.015s | 19.024MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree205.smt2 |    0.015s | 18.996MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree312.smt2 |    0.015s | 19.16MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree309.smt2 |    0.015s | 19.204MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree45.smt2 |    0.015s | 19.152MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree115.smt2 |    0.015s | 19.044MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree446.smt2 |    0.015s | 19.188MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree479.smt2 |    0.015s | 18.964MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree521.smt2 |    0.015s | 19.148MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree243.smt2 |    0.015s | 19.204MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree86.smt2 |    0.015s | 19.172MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree20.smt2 |    0.015s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree423.smt2 |    0.015s | 19.14MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree116.smt2 |    0.015s | 19.024MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree178.smt2 |    0.015s | 18.94MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree83.smt2 |    0.015s | 19.12MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree50.smt2 |    0.015s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree246.smt2 |    0.015s | 18.944MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree63.smt2 |    0.015s | 18.944MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree59.smt2 |    0.015s | 19.232MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree388.smt2 |    0.015s | 19.112MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree444.smt2 |    0.015s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree167.smt2 |    0.015s | 19.116MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree186.smt2 |    0.015s | 19.16MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree511.smt2 |    0.015s | 19.016MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree278.smt2 |    0.015s | 19.036MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree93.smt2 |    0.015s | 19.064MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree471.smt2 |    0.015s | 19.108MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree473.smt2 |    0.015s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree421.smt2 |    0.015s | 19.052MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree125.smt2 |    0.015s | 19.036MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree58.smt2 |    0.015s | 19.088MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree100.smt2 |    0.015s | 18.988MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree140.smt2 |    0.015s | 18.964MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german120.smt2 |    0.016s | 18.84MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german42.smt2 |    0.016s | 18.904MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german82.smt2 |    0.016s | 19.02MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german80.smt2 |    0.016s | 18.936MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german17.smt2 |    0.016s | 18.964MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german43.smt2 |    0.016s | 19.004MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german130.smt2 |    0.016s | 19.02MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german54.smt2 |    0.016s | 19.064MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german35.smt2 |    0.016s | 19.796MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german143.smt2 |    0.016s | 18.996MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german132.smt2 |    0.016s | 18.908MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german65.smt2 |    0.016s | 19.008MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german16.smt2 |    0.016s | 19.084MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german21.smt2 |    0.016s | 19.504MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german75.smt2 |    0.016s | 19.644MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german44.smt2 |    0.016s | 18.888MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german32.smt2 |    0.016s | 18.88MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german57.smt2 |    0.016s | 18.864MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german133.smt2 |    0.016s | 19.076MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree295.smt2 |    0.016s | 19.18MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree489.smt2 |    0.016s | 19.112MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree468.smt2 |    0.016s | 19.008MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree514.smt2 |    0.016s | 19.212MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree103.smt2 |    0.016s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree311.smt2 |    0.016s | 18.956MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree9.smt2 |    0.016s | 19.188MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree516.smt2 |    0.016s | 19.012MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree4.smt2 |    0.016s | 19.14MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree202.smt2 |    0.016s | 19.056MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree98.smt2 |    0.016s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree87.smt2 |    0.016s | 19.016MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree285.smt2 |    0.016s | 19.108MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree362.smt2 |    0.016s | 19.112MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree306.smt2 |    0.016s | 18.976MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree120.smt2 |    0.016s | 19.156MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree69.smt2 |    0.016s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree296.smt2 |    0.016s | 18.972MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree264.smt2 |    0.016s | 18.992MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree449.smt2 |    0.016s | 19.008MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree438.smt2 |    0.016s | 19.112MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree273.smt2 |    0.016s | 19.044MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree286.smt2 |    0.016s | 18.996MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree238.smt2 |    0.016s | 19.088MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree112.smt2 |    0.016s | 19.16MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree133.smt2 |    0.016s | 19.032MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree348.smt2 |    0.016s | 19.16MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree213.smt2 |    0.016s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree96.smt2 |    0.016s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree476.smt2 |    0.016s | 19.168MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree346.smt2 |    0.016s | 19.152MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree21.smt2 |    0.016s | 19.16MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree74.smt2 |    0.016s | 19.108MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree56.smt2 |    0.016s | 19.036MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree497.smt2 |    0.016s | 19.064MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree104.smt2 |    0.016s | 19.096MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree457.smt2 |    0.016s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree404.smt2 |    0.016s | 19.064MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree51.smt2 |    0.016s | 19.124MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree39.smt2 |    0.016s | 18.94MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree171.smt2 |    0.016s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree484.smt2 |    0.016s | 19.004MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree143.smt2 |    0.016s | 19.092MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree34.smt2 |    0.016s | 19.048MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree92.smt2 |    0.016s | 19.076MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree256.smt2 |    0.016s | 19.024MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree44.smt2 |    0.016s | 19.004MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree179.smt2 |    0.016s | 19.236MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree52.smt2 |    0.016s | 19.204MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree148.smt2 |    0.016s | 18.952MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree57.smt2 |    0.016s | 19.388MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree80.smt2 |    0.016s | 19.128MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree301.smt2 |    0.016s | 19.256MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree293.smt2 |    0.016s | 19.248MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree528.smt2 |    0.016s | 18.972MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree337.smt2 |    0.016s | 18.956MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree47.smt2 |    0.016s | 19.016MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree94.smt2 |    0.016s | 19.356MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree113.smt2 |    0.016s | 19.036MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree270.smt2 |    0.016s | 18.96MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree68.smt2 |    0.016s | 19.084MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree240.smt2 |    0.016s | 19.192MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree31.smt2 |    0.016s | 19.064MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree396.smt2 |    0.016s | 19.144MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree305.smt2 |    0.016s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree193.smt2 |    0.016s | 18.952MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree505.smt2 |    0.016s | 18.98MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree204.smt2 |    0.016s | 19.18MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree495.smt2 |    0.016s | 19.112MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree150.smt2 |    0.016s | 19.136MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree329.smt2 |    0.016s | 19.0MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree196.smt2 |    0.016s | 19.108MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree102.smt2 |    0.016s | 19.2MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree78.smt2 |    0.016s | 19.04MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree215.smt2 |    0.016s | 19.1MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree6.smt2 |    0.016s | 19.008MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree235.smt2 |    0.016s | 19.108MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree65.smt2 |    0.016s | 19.08MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree280.smt2 |    0.016s | 19.076MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree14.smt2 |    0.016s | 19.032MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree455.smt2 |    0.016s | 18.964MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree127.smt2 |    0.016s | 19.032MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree207.smt2 |    0.016s | 18.988MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree43.smt2 |    0.016s | 19.08MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree332.smt2 |    0.016s | 19.204MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree174.smt2 |    0.016s | 18.972MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree229.smt2 |    0.016s | 19.064MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree292.smt2 |    0.016s | 19.0MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree481.smt2 |    0.016s | 19.1MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree230.smt2 |    0.016s | 18.952MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree465.smt2 |    0.016s | 19.044MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree165.smt2 |    0.016s | 19.096MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree48.smt2 |    0.016s | 19.172MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree262.smt2 |    0.016s | 19.052MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree232.smt2 |    0.016s | 19.18MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree255.smt2 |    0.016s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree356.smt2 |    0.016s | 19.18MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount29.smt2 |    0.016s | 19.048MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german67.smt2 |    0.017s | 19.08MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german89.smt2 |    0.017s | 19.648MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german66.smt2 |    0.017s | 19.684MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german83.smt2 |    0.017s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german45.smt2 |    0.017s | 19.616MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german144.smt2 |    0.017s | 19.764MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german134.smt2 |    0.017s | 19.764MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german51.smt2 |    0.017s | 19.604MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german102.smt2 |    0.017s | 19.768MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german103.smt2 |    0.017s | 19.764MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german1.smt2 |    0.017s | 19.624MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german61.smt2 |    0.017s | 19.788MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german101.smt2 |    0.017s | 19.656MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german69.smt2 |    0.017s | 18.888MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german23.smt2 |    0.017s | 19.744MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german40.smt2 |    0.017s | 19.792MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german79.smt2 |    0.017s | 19.744MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german127.smt2 |    0.017s | 19.684MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german128.smt2 |    0.017s | 19.68MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german147.smt2 |    0.017s | 19.644MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german99.smt2 |    0.017s | 19.776MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german50.smt2 |    0.017s | 19.724MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german13.smt2 |    0.017s | 19.648MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german121.smt2 |    0.017s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german96.smt2 |    0.017s | 18.872MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german53.smt2 |    0.017s | 19.572MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german145.smt2 |    0.017s | 19.712MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german126.smt2 |    0.017s | 19.732MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree263.smt2 |    0.017s | 19.172MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree123.smt2 |    0.017s | 19.184MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree141.smt2 |    0.017s | 19.008MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree147.smt2 |    0.017s | 19.084MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree402.smt2 |    0.017s | 19.032MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree323.smt2 |    0.017s | 19.024MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree529.smt2 |    0.017s | 19.136MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree40.smt2 |    0.017s | 19.08MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree33.smt2 |    0.017s | 19.056MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree187.smt2 |    0.017s | 19.036MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree37.smt2 |    0.017s | 19.128MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree18.smt2 |    0.017s | 19.2MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree463.smt2 |    0.017s | 19.184MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree188.smt2 |    0.017s | 19.192MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree279.smt2 |    0.017s | 19.0MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree17.smt2 |    0.017s | 19.012MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree90.smt2 |    0.017s | 19.188MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree433.smt2 |    0.017s | 19.048MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree317.smt2 |    0.017s | 19.084MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree19.smt2 |    0.017s | 19.164MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree436.smt2 |    0.017s | 19.116MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree418.smt2 |    0.017s | 18.956MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree314.smt2 |    0.017s | 19.612MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree156.smt2 |    0.017s | 19.096MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree182.smt2 |    0.017s | 19.196MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree172.smt2 |    0.017s | 19.136MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree2.smt2 |    0.017s | 19.192MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree170.smt2 |    0.017s | 19.044MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree173.smt2 |    0.017s | 19.136MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree310.smt2 |    0.017s | 19.12MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree503.smt2 |    0.017s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree135.smt2 |    0.017s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree164.smt2 |    0.017s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree84.smt2 |    0.017s | 19.204MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree222.smt2 |    0.017s | 19.076MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree428.smt2 |    0.017s | 19.192MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree29.smt2 |    0.017s | 19.024MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree190.smt2 |    0.017s | 19.16MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree36.smt2 |    0.017s | 19.024MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree330.smt2 |    0.017s | 18.972MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree25.smt2 |    0.017s | 18.952MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree95.smt2 |    0.017s | 19.044MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree411.smt2 |    0.017s | 18.96MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree66.smt2 |    0.017s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree117.smt2 |    0.017s | 18.968MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree492.smt2 |    0.017s | 19.004MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree32.smt2 |    0.017s | 19.016MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree526.smt2 |    0.017s | 19.192MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree284.smt2 |    0.017s | 18.972MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree527.smt2 |    0.017s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree13.smt2 |    0.017s | 19.044MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree62.smt2 |    0.017s | 19.024MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree180.smt2 |    0.017s | 19.088MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree214.smt2 |    0.017s | 19.044MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree447.smt2 |    0.017s | 19.06MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree76.smt2 |    0.017s | 19.012MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree88.smt2 |    0.017s | 19.16MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree197.smt2 |    0.017s | 19.116MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree10.smt2 |    0.017s | 19.04MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree77.smt2 |    0.017s | 19.1MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree364.smt2 |    0.017s | 18.972MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount38.smt2 |    0.017s | 19.648MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german11.smt2 |    0.018s | 19.76MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german113.smt2 |    0.018s | 19.712MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german38.smt2 |    0.018s | 19.776MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german129.smt2 |    0.018s | 19.748MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german74.smt2 |    0.018s | 19.676MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german34.smt2 |    0.018s | 19.632MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german110.smt2 |    0.018s | 19.808MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german152.smt2 |    0.018s | 20.088MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german137.smt2 |    0.018s | 19.644MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german28.smt2 |    0.018s | 18.948MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german12.smt2 |    0.018s | 19.772MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german141.smt2 |    0.018s | 19.616MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german112.smt2 |    0.018s | 19.748MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german178.smt2 |    0.018s | 20.176MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german136.smt2 |    0.018s | 19.776MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german60.smt2 |    0.018s | 19.664MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german98.smt2 |    0.018s | 19.808MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german118.smt2 |    0.018s | 19.8MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german100.smt2 |    0.018s | 19.728MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german7.smt2 |    0.018s | 19.8MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german39.smt2 |    0.018s | 19.74MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german142.smt2 |    0.018s | 19.616MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german37.smt2 |    0.018s | 19.588MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german71.smt2 |    0.018s | 19.632MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german48.smt2 |    0.018s | 19.764MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german64.smt2 |    0.018s | 19.704MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german36.smt2 |    0.018s | 19.76MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german116.smt2 |    0.018s | 19.644MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german139.smt2 |    0.018s | 19.724MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german47.smt2 |    0.018s | 19.796MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german63.smt2 |    0.018s | 19.664MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german62.smt2 |    0.018s | 19.8MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german175.smt2 |    0.018s | 20.216MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german27.smt2 |    0.018s | 19.612MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree46.smt2 |    0.018s | 18.976MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree26.smt2 |    0.018s | 19.032MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree151.smt2 |    0.018s | 19.144MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree298.smt2 |    0.018s | 19.552MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree394.smt2 |    0.018s | 19.168MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree448.smt2 |    0.018s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree458.smt2 |    0.018s | 19.112MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree16.smt2 |    0.018s | 19.16MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree271.smt2 |    0.018s | 19.144MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree199.smt2 |    0.018s | 19.14MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree508.smt2 |    0.018s | 19.144MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree221.smt2 |    0.018s | 19.144MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree357.smt2 |    0.018s | 19.5MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree206.smt2 |    0.018s | 19.008MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree108.smt2 |    0.018s | 19.0MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree378.smt2 |    0.018s | 18.992MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree389.smt2 |    0.018s | 19.472MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree189.smt2 |    0.018s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree99.smt2 |    0.018s | 19.188MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree442.smt2 |    0.018s | 19.464MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree106.smt2 |    0.018s | 19.136MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree441.smt2 |    0.018s | 19.036MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree12.smt2 |    0.018s | 19.056MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree519.smt2 |    0.018s | 19.016MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree64.smt2 |    0.018s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount25.smt2 |    0.018s | 19.66MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount2.smt2 |    0.018s | 19.812MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount43.smt2 |    0.018s | 19.82MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount3.smt2 |    0.018s | 19.656MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount44.smt2 |    0.018s | 19.664MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german109.smt2 |    0.019s | 19.708MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german161.smt2 |    0.019s | 20.284MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german91.smt2 |    0.019s | 19.66MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german149.smt2 |    0.019s | 20.2MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german46.smt2 |    0.019s | 19.792MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german140.smt2 |    0.019s | 19.612MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german123.smt2 |    0.019s | 19.572MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german181.smt2 |    0.019s | 20.388MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german111.smt2 |    0.019s | 19.888MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german108.smt2 |    0.019s | 19.792MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german131.smt2 |    0.019s | 19.684MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german162.smt2 |    0.019s | 20.288MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german166.smt2 |    0.019s | 20.324MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german33.smt2 |    0.019s | 19.728MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german97.smt2 |    0.019s | 19.56MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german150.smt2 |    0.019s | 20.34MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german73.smt2 |    0.019s | 19.704MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german90.smt2 |    0.019s | 19.628MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german115.smt2 |    0.019s | 19.56MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german8.smt2 |    0.019s | 19.832MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german167.smt2 |    0.019s | 20.336MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german172.smt2 |    0.019s | 20.256MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german156.smt2 |    0.019s | 20.28MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german85.smt2 |    0.019s | 19.756MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german165.smt2 |    0.019s | 20.236MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german171.smt2 |    0.019s | 20.308MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german163.smt2 |    0.019s | 20.308MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german58.smt2 |    0.019s | 19.784MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree349.smt2 |    0.019s | 19.608MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree15.smt2 |    0.019s | 19.016MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree302.smt2 |    0.019s | 19.012MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree107.smt2 |    0.019s | 19.24MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree417.smt2 |    0.019s | 19.096MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree136.smt2 |    0.019s | 19.504MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree163.smt2 |    0.019s | 19.128MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree168.smt2 |    0.019s | 19.44MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree128.smt2 |    0.019s | 19.568MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree42.smt2 |    0.019s | 19.052MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree194.smt2 |    0.019s | 19.096MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree139.smt2 |    0.019s | 19.124MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree321.smt2 |    0.019s | 19.144MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree414.smt2 |    0.019s | 19.5MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree431.smt2 |    0.019s | 18.992MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree340.smt2 |    0.019s | 19.46MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount15.smt2 |    0.019s | 19.776MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount26.smt2 |    0.019s | 19.64MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount21.smt2 |    0.019s | 19.832MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount39.smt2 |    0.019s | 19.76MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount12.smt2 |    0.019s | 19.756MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount8.smt2 |    0.019s | 19.608MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount5.smt2 |    0.019s | 19.692MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german151.smt2 |    0.020s | 20.204MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german70.smt2 |    0.020s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german105.smt2 |    0.020s | 19.6MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german177.smt2 |    0.020s | 20.22MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german157.smt2 |    0.020s | 20.356MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german186.smt2 |    0.020s | 20.468MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german86.smt2 |    0.020s | 19.804MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german59.smt2 |    0.020s | 19.864MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german187.smt2 |    0.020s | 20.488MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german124.smt2 |    0.020s | 19.816MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german184.smt2 |    0.020s | 20.408MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german154.smt2 |    0.020s | 20.404MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german180.smt2 |    0.020s | 20.228MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german173.smt2 |    0.020s | 20.32MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german182.smt2 |    0.020s | 20.384MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german168.smt2 |    0.020s | 20.328MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german114.smt2 |    0.020s | 19.552MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german174.smt2 |    0.020s | 20.232MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree250.smt2 |    0.020s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree124.smt2 |    0.020s | 18.948MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree462.smt2 |    0.020s | 19.852MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree401.smt2 |    0.020s | 19.912MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree435.smt2 |    0.020s | 19.848MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree122.smt2 |    0.020s | 19.936MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree38.smt2 |    0.020s | 19.208MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree445.smt2 |    0.020s | 20.032MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree67.smt2 |    0.020s | 19.212MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree145.smt2 |    0.020s | 19.884MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree226.smt2 |    0.020s | 19.812MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree217.smt2 |    0.020s | 19.792MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree160.smt2 |    0.020s | 19.58MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree405.smt2 |    0.020s | 19.564MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree109.smt2 |    0.020s | 18.992MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree265.smt2 |    0.020s | 19.16MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree381.smt2 |    0.020s | 19.704MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree105.smt2 |    0.020s | 19.184MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree397.smt2 |    0.020s | 19.464MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree325.smt2 |    0.020s | 19.932MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree426.smt2 |    0.020s | 19.78MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree129.smt2 |    0.020s | 19.908MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount9.smt2 |    0.020s | 19.748MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount30.smt2 |    0.020s | 19.844MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount31.smt2 |    0.020s | 19.716MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount11.smt2 |    0.020s | 19.684MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount17.smt2 |    0.020s | 19.616MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount18.smt2 |    0.020s | 19.72MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-noinv-f5.ucl-property_correspondence-vobj-0002.smt2 |    0.021s | 19.288MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german30.smt2 |    0.021s | 19.1MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german92.smt2 |    0.021s | 19.756MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german160.smt2 |    0.021s | 20.256MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german189.smt2 |    0.021s | 20.468MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german183.smt2 |    0.021s | 20.136MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german176.smt2 |    0.021s | 20.192MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german138.smt2 |    0.021s | 19.884MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree398.smt2 |    0.021s | 19.884MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree275.smt2 |    0.021s | 19.804MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree138.smt2 |    0.021s | 20.028MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree496.smt2 |    0.021s | 19.844MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree241.smt2 |    0.021s | 19.812MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree1.smt2 |    0.021s | 19.728MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree324.smt2 |    0.021s | 19.896MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree249.smt2 |    0.021s | 19.864MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree315.smt2 |    0.021s | 20.028MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree228.smt2 |    0.021s | 20.0MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree395.smt2 |    0.021s | 20.068MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree437.smt2 |    0.021s | 20.044MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree510.smt2 |    0.021s | 19.796MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree478.smt2 |    0.021s | 19.928MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree208.smt2 |    0.021s | 19.76MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree469.smt2 |    0.021s | 19.844MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree144.smt2 |    0.021s | 19.652MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree247.smt2 |    0.021s | 19.084MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree121.smt2 |    0.021s | 19.732MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree419.smt2 |    0.021s | 19.892MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree282.smt2 |    0.021s | 20.064MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree209.smt2 |    0.021s | 19.824MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree131.smt2 |    0.021s | 20.044MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree22.smt2 |    0.021s | 18.988MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree424.smt2 |    0.021s | 19.98MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree234.smt2 |    0.021s | 19.704MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree517.smt2 |    0.021s | 19.924MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree338.smt2 |    0.021s | 19.968MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree154.smt2 |    0.021s | 20.104MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree257.smt2 |    0.021s | 19.204MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree60.smt2 |    0.021s | 19.116MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount20.smt2 |    0.021s | 19.824MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount23.smt2 |    0.021s | 19.768MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount4.smt2 |    0.021s | 19.708MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount14.smt2 |    0.021s | 19.856MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount33.smt2 |    0.021s | 19.824MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount7.smt2 |    0.021s | 19.828MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount34.smt2 |    0.021s | 19.668MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german159.smt2 |    0.022s | 20.336MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german170.smt2 |    0.022s | 20.404MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german153.smt2 |    0.022s | 20.396MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german179.smt2 |    0.022s | 20.16MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german169.smt2 |    0.022s | 20.404MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german158.smt2 |    0.022s | 20.256MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german185.smt2 |    0.022s | 20.472MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german190.smt2 |    0.022s | 20.412MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree130.smt2 |    0.022s | 20.016MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree114.smt2 |    0.022s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree162.smt2 |    0.022s | 20.1MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree260.smt2 |    0.022s | 20.04MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree132.smt2 |    0.022s | 20.064MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree409.smt2 |    0.022s | 19.964MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree501.smt2 |    0.022s | 20.004MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree201.smt2 |    0.022s | 19.696MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree81.smt2 |    0.022s | 19.84MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree11.smt2 |    0.022s | 19.828MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree110.smt2 |    0.022s | 19.184MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree200.smt2 |    0.022s | 19.744MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree391.smt2 |    0.022s | 19.94MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree316.smt2 |    0.022s | 19.872MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree252.smt2 |    0.022s | 19.992MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree470.smt2 |    0.022s | 20.0MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree425.smt2 |    0.022s | 19.94MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree379.smt2 |    0.022s | 19.972MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree291.smt2 |    0.022s | 19.092MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree451.smt2 |    0.022s | 19.704MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree334.smt2 |    0.022s | 19.836MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree254.smt2 |    0.022s | 19.076MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree373.smt2 |    0.022s | 19.696MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree236.smt2 |    0.022s | 20.056MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree195.smt2 |    0.022s | 20.008MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree365.smt2 |    0.022s | 19.528MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree354.smt2 |    0.022s | 19.036MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree233.smt2 |    0.022s | 19.972MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree504.smt2 |    0.022s | 19.832MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree512.smt2 |    0.022s | 19.964MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree502.smt2 |    0.022s | 19.908MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree403.smt2 |    0.022s | 20.016MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree406.smt2 |    0.022s | 19.936MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree454.smt2 |    0.022s | 19.984MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree327.smt2 |    0.022s | 20.14MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree380.smt2 |    0.022s | 19.172MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount10.smt2 |    0.022s | 19.904MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount19.smt2 |    0.022s | 19.776MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount1.smt2 |    0.022s | 19.716MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount45.smt2 |    0.022s | 19.876MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-noinv-f5.ucl-property_correspondence-vobj-0002.smt2 |    0.023s | 19.376MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-coninv-f5.ucl-property_correspondence-vobj-0002.smt2 |    0.023s | 19.276MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-umem-coninv-f5.ucl-property_correspondence-vobj-0002.smt2 |    0.023s | 19.256MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german188.smt2 |    0.023s | 20.436MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german146.smt2 |    0.023s | 20.28MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german155.smt2 |    0.023s | 20.22MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german148.smt2 |    0.023s | 20.324MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree520.smt2 |    0.023s | 20.08MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree126.smt2 |    0.023s | 19.972MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree408.smt2 |    0.023s | 20.02MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree493.smt2 |    0.023s | 19.832MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree225.smt2 |    0.023s | 19.896MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree400.smt2 |    0.023s | 19.944MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree251.smt2 |    0.023s | 20.028MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree456.smt2 |    0.023s | 19.896MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree137.smt2 |    0.023s | 19.896MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree486.smt2 |    0.023s | 19.968MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree367.smt2 |    0.023s | 19.796MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree416.smt2 |    0.023s | 19.932MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree430.smt2 |    0.023s | 19.988MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree203.smt2 |    0.023s | 20.116MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree427.smt2 |    0.023s | 19.18MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree376.smt2 |    0.023s | 20.308MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree227.smt2 |    0.023s | 19.176MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree276.smt2 |    0.023s | 20.132MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree399.smt2 |    0.023s | 20.048MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree453.smt2 |    0.023s | 20.06MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree513.smt2 |    0.023s | 18.984MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree383.smt2 |    0.023s | 19.84MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree480.smt2 |    0.023s | 19.836MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree523.smt2 |    0.023s | 19.896MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree368.smt2 |    0.023s | 20.26MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount41.smt2 |    0.023s | 19.82MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-umem-noinv-f5.ucl-property_correspondence-vobj-0002.smt2 |    0.024s | 19.376MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-noinv-f5.ucl-property_correspondence-vobj-0002.smt2 |    0.024s | 19.376MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-coninv-f5.ucl-property_correspondence-vobj-0002.smt2 |    0.024s | 19.276MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-coninv-f5.ucl-property_correspondence-vobj-0002.smt2 |    0.024s | 19.388MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree392.smt2 |    0.024s | 20.272MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree333.smt2 |    0.024s | 19.984MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree412.smt2 |    0.024s | 20.16MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree336.smt2 |    0.024s | 19.964MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree253.smt2 |    0.024s | 20.236MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree304.smt2 |    0.024s | 20.056MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree494.smt2 |    0.024s | 19.812MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree224.smt2 |    0.024s | 19.06MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree328.smt2 |    0.024s | 19.836MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree472.smt2 |    0.024s | 19.788MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree287.smt2 |    0.024s | 19.076MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree385.smt2 |    0.025s | 19.98MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree440.smt2 |    0.025s | 19.16MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree344.smt2 |    0.025s | 20.3MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree27.smt2 |    0.025s | 19.228MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree248.smt2 |    0.025s | 19.04MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree434.smt2 |    0.025s | 20.176MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree360.smt2 |    0.025s | 20.268MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree319.smt2 |    0.025s | 20.272MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree268.smt2 |    0.025s | 20.164MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree488.smt2 |    0.025s | 19.792MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree288.smt2 |    0.026s | 20.164MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree429.smt2 |    0.026s | 20.128MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree530.smt2 |    0.026s | 20.368MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree134.smt2 |    0.026s | 19.88MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree377.smt2 |    0.026s | 19.86MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree363.smt2 |    0.026s | 19.82MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/german/german125.smt2 |    0.027s | 19.728MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree464.smt2 |    0.027s | 19.9MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree352.smt2 |    0.027s | 20.204MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree522.smt2 |    0.027s | 20.228MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree432.smt2 |    0.027s | 20.236MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree384.smt2 |    0.027s | 20.212MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree269.smt2 |    0.028s | 20.264MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree152.smt2 |    0.029s | 20.788MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree335.smt2 |    0.029s | 20.068MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount13.smt2 |    0.032s | 18.916MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount16.smt2 |    0.033s | 19.824MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount6.smt2 |    0.034s | 19.816MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree353.smt2 |    0.035s | 19.92MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree142.smt2 |    0.035s | 20.04MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-umem-coninv-f5.ucl-property_correspondence-vobj-0003.smt2 |    0.042s | 20.148MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-noinv-f5.ucl-property_correspondence-vobj-0003.smt2 |    0.042s | 19.828MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-coninv-f5.ucl-property_correspondence-vobj-0003.smt2 |    0.043s | 20.108MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree415.smt2 |    0.043s | 21.3MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-coninv-f5.ucl-property_correspondence-vobj-0003.smt2 |    0.045s | 20.104MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-umem-noinv-f5.ucl-property_correspondence-vobj-0003.smt2 |    0.045s | 19.88MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-coninv-f5.ucl-property_correspondence-vobj-0003.smt2 |    0.046s | 20.104MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree525.smt2 |    0.049s | 21.816MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-noinv-f5.ucl-property_correspondence-vobj-0003.smt2 |    0.053s | 19.804MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-noinv-f5.ucl-property_correspondence-vobj-0003.smt2 |    0.057s | 19.916MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-coninv-f5.ucl-property_correspondence-vobj-0004.smt2 |    0.062s | 20.36MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-noinv-f5.ucl-property_correspondence-vobj-0004.smt2 |    0.062s | 20.356MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-noinv-f5.ucl-property_correspondence-vobj-0004.smt2 |    0.062s | 20.428MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-coninv-f5.ucl-property_correspondence-vobj-0004.smt2 |    0.063s | 20.372MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-umem-coninv-f5.ucl-property_correspondence-vobj-0004.smt2 |    0.063s | 20.428MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-umem-noinv-f5.ucl-property_correspondence-vobj-0004.smt2 |    0.063s | 20.372MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-coninv-f5.ucl-property_correspondence-vobj-0004.smt2 |    0.063s | 20.508MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-noinv-f5.ucl-property_correspondence-vobj-0004.smt2 |    0.079s | 20.3MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-noinv-f5.ucl-property_correspondence-vobj-0005.smt2 |    0.083s | 20.912MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-coninv-f5.ucl-property_correspondence-vobj-0005.smt2 |    0.084s | 20.592MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-noinv-f5.ucl-property_correspondence-vobj-0005.smt2 |    0.084s | 20.532MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-coninv-f5.ucl-property_correspondence-vobj-0005.smt2 |    0.086s | 20.556MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-coninv-f5.ucl-property_correspondence-vobj-0005.smt2 |    0.088s | 20.632MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-umem-coninv-f5.ucl-property_correspondence-vobj-0005.smt2 |    0.089s | 20.704MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-noinv-f5.ucl-property_correspondence-vobj-0006.smt2 |    0.101s | 21.096MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-noinv-f5.ucl-property_correspondence-vobj-0005.smt2 |    0.102s | 20.664MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-coninv-f5.ucl-property_correspondence-vobj-0006.smt2 |    0.103s | 21.356MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-noinv-f5.ucl-property_correspondence-vobj-0006.smt2 |    0.105s | 21.188MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-coninv-f5.ucl-property_correspondence-vobj-0006.smt2 |    0.105s | 21.364MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-noinv-f5.ucl-property_correspondence-vobj-0006.smt2 |    0.105s | 21.292MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-coninv-f5.ucl-property_correspondence-vobj-0006.smt2 |    0.107s | 21.292MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-umem-coninv-f5.ucl-property_correspondence-vobj-0006.smt2 |    0.121s | 21.164MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-noinv-f5.ucl-property_correspondence-vobj-0007.smt2 |    0.121s | 21.476MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-coninv-f5.ucl-property_correspondence-vobj-0007.smt2 |    0.123s | 21.656MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-noinv-f5.ucl-property_correspondence-vobj-0007.smt2 |    0.124s | 21.624MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-umem-coninv-f5.ucl-property_correspondence-vobj-0007.smt2 |    0.129s | 21.48MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-coninv-f5.ucl-property_correspondence-vobj-0007.smt2 |    0.135s | 21.66MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-coninv-f5.ucl-property_correspondence-vobj-0007.smt2 |    0.139s | 21.636MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-coninv-f5.ucl-property_correspondence-vobj-0008.smt2 |    0.140s | 21.868MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-noinv-f5.ucl-property_correspondence-vobj-0008.smt2 |    0.141s | 21.712MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-noinv-f5.ucl-property_correspondence-vobj-0008.smt2 |    0.143s | 21.716MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-noinv-f5.ucl-property_correspondence-vobj-0008.smt2 |    0.143s | 21.7MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-noinv-f5.ucl-property_correspondence-vobj-0007.smt2 |    0.148s | 21.644MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-coninv-f5.ucl-property_correspondence-vobj-0008.smt2 |    0.149s | 21.756MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-coninv-f5.ucl-property_correspondence-vobj-0008.smt2 |    0.150s | 21.816MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-noinv-f5.ucl-property_correspondence-vobj-0009.smt2 |    0.158s | 22.128MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-umem-coninv-f5.ucl-property_correspondence-vobj-0008.smt2 |    0.161s | 21.82MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree341.smt2 |    0.164s | 26.088MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-noinv-f5.ucl-property_correspondence-vobj-0009.smt2 |    0.165s | 21.952MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-coninv-f5.ucl-property_correspondence-vobj-0009.smt2 |    0.168s | 22.092MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-coninv-f5.ucl-property_correspondence-vobj-0009.smt2 |    0.168s | 22.168MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-umem-coninv-f5.ucl-property_correspondence-vobj-0009.smt2 |    0.169s | 22.184MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-noinv-f5.ucl-property_correspondence-vobj-0009.smt2 |    0.180s | 22.192MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-coninv-f5.ucl-property_correspondence-vobj-0009.smt2 |    0.186s | 22.34MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount24.smt2 |    1.293s | 41.792MiB| sat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-umem-coninv-f5.ucl-property_correspondence-vobj-0010.smt2 |   11.145s | 34.844MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-coninv-f5.ucl-property_correspondence-vobj-0010.smt2 |   14.129s | 36.544MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-thrualu-amem-noinv-f5.ucl-property_correspondence-vobj-0010.smt2 |   17.165s | 38.208MiB| unsat | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-coninv-f5.ucl-property_correspondence-vobj-0010.smt2 |   20.007s | 38.904MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-amem-noinv-f5.ucl-property_correspondence-vobj-0010.smt2 |   20.008s | 37.076MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree466.smt2 |   20.009s | 68.244MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree345.smt2 |   20.009s | 84.0MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree410.smt2 |   20.009s | 77.512MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree498.smt2 |   20.010s | 84.548MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree393.smt2 |   20.010s | 93.372MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree355.smt2 |   20.010s | 86.024MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree192.smt2 |   20.010s | 99.524MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree277.smt2 |   20.011s | 89.236MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree361.smt2 |   20.011s | 79.08MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree176.smt2 |   20.011s | 97.52MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree158.smt2 |   20.011s | 121.0MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree490.smt2 |   20.011s | 83.96MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree450.smt2 |   20.011s | 101.0MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree375.smt2 |   20.011s | 126.0MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree482.smt2 |   20.011s | 88.048MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree343.smt2 |   20.011s | 78.756MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree184.smt2 |   20.012s | 80.852MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree477.smt2 |   20.012s | 129.0MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree387.smt2 |   20.012s | 89.432MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree101.smt2 |   20.012s | 80.972MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree359.smt2 |   20.012s | 80.424MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree111.smt2 |   20.013s | 110.0MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree461.smt2 |   20.013s | 124.0MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree267.smt2 |   20.013s | 137.0MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree506.smt2 |   20.013s | 153.0MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree485.smt2 |   20.013s | 128.0MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree313.smt2 |   20.013s | 131.0MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree351.smt2 |   20.014s | 95.96MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree259.smt2 |   20.014s | 160.0MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree220.smt2 |   20.015s | 188.0MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree261.smt2 |   20.015s | 182.0MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree474.smt2 |   20.015s | 88.092MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree371.smt2 |   20.015s | 162.0MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree166.smt2 |   20.016s | 245.0MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount36.smt2 |   20.016s | 230.0MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree347.smt2 |   20.017s | 163.0MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount40.smt2 |   20.017s | 239.0MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount35.smt2 |   20.017s | 236.0MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount46.smt2 |   20.017s | 233.0MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree369.smt2 |   20.018s | 81.404MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree212.smt2 |   20.018s | 201.0MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree119.smt2 |   20.018s | 77.356MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-coninv-f5.ucl-property_correspondence-vobj-0010.smt2 |   20.019s | 36.892MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/refcount/refcount28.smt2 |   20.019s | 219.0MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree303.smt2 |   20.020s | 137.0MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-uhbexamples/uhb_quantifiers.smt2 |   20.020s | 319.0MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree509.smt2 |   20.022s | 187.0MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree244.smt2 |   20.023s | 242.0MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20210304-Y86/run-btfnt-idata-fullalu-umem-noinv-f5.ucl-property_correspondence-vobj-0010.smt2 |   20.025s | 36.404MiB| timeout | 0 |  |  |
|non-incremental/AUFDTLIA/20172804-Barrett/fmf-cav2013/agreement/agree91.smt2 |   20.031s | 272.0MiB| timeout | 0 |  |  |
