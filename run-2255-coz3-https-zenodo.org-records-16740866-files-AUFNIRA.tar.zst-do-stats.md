# .

* SAT 5
* UNSAT 1019
* TIMEOUT 454
* UNKNOWN 2

* ERRORS 0

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: Triggered by CoZ3 Benchmark Runner | Benchmark suite: https://zenodo.org/records/16740866/files/AUFNIRA.tar.zst?download=1 | Source list: quantifier_benchmarks.txt
Job tag: coz3-https-zenodo.org-records-16740866-files-AUFNIRA.tar.zst-do
Runner: rise-runner-1
Z3 repo: Z3Prover/z3
Z3 commit: c3f5365a95a7eac2419a2f95ff240909f275cc08
Z3 branch: c3f5365a95a7eac2419a2f95ff240909f275cc08
Z3 options: "-T:20 model_validate=true"
Z3 inputs: https://zenodo.org/records/16740866/files/AUFNIRA.tar.zst?download=1
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
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1319.fof.smt2 |    0.013s | 19.08MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0243.fof.smt2 |    0.014s | 19.06MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0097.fof.smt2 |    0.014s | 19.232MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0785.fof.smt2 |    0.014s | 19.236MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0035.fof.smt2 |    0.014s | 19.096MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0283.fof.smt2 |    0.014s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0270.fof.smt2 |    0.014s | 19.024MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1102.fof.smt2 |    0.014s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0005.fof.smt2 |    0.014s | 19.1MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1347.fof.smt2 |    0.014s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0279.fof.smt2 |    0.014s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0019.fof.smt2 |    0.014s | 19.044MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0531.fof.smt2 |    0.014s | 19.236MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0006.fof.smt2 |    0.014s | 19.032MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0022.fof.smt2 |    0.014s | 19.12MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1354.fof.smt2 |    0.014s | 19.3MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1056.fof.smt2 |    0.014s | 19.264MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0004.fof.smt2 |    0.014s | 19.016MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0621.fof.smt2 |    0.014s | 19.256MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1047.fof.smt2 |    0.014s | 19.064MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0031.fof.smt2 |    0.014s | 19.164MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0555.fof.smt2 |    0.014s | 19.284MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1302.fof.smt2 |    0.014s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0040.fof.smt2 |    0.014s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1035.fof.smt2 |    0.014s | 19.2MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0045.fof.smt2 |    0.014s | 19.136MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1176.fof.smt2 |    0.014s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.629402.smt2               |    0.015s | 19.52MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.630048.smt2                   |    0.015s | 19.52MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0216.fof.smt2 |    0.015s | 19.036MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0112.fof.smt2 |    0.015s | 19.004MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0367.fof.smt2 |    0.015s | 19.212MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0256.fof.smt2 |    0.015s | 19.256MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0153.fof.smt2 |    0.015s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0133.fof.smt2 |    0.015s | 19.196MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0053.fof.smt2 |    0.015s | 19.208MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0212.fof.smt2 |    0.015s | 19.108MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0275.fof.smt2 |    0.015s | 19.076MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0199.fof.smt2 |    0.015s | 19.128MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0135.fof.smt2 |    0.015s | 19.108MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0163.fof.smt2 |    0.015s | 19.136MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0361.fof.smt2 |    0.015s | 19.1MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0125.fof.smt2 |    0.015s | 19.152MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0214.fof.smt2 |    0.015s | 19.128MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0127.fof.smt2 |    0.015s | 19.084MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0201.fof.smt2 |    0.015s | 19.08MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0170.fof.smt2 |    0.015s | 18.992MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0206.fof.smt2 |    0.015s | 19.032MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0030.fof.smt2 |    0.015s | 19.22MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0386.fof.smt2 |    0.015s | 19.176MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0358.fof.smt2 |    0.015s | 18.988MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0122.fof.smt2 |    0.015s | 19.156MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0141.fof.smt2 |    0.015s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0282.fof.smt2 |    0.015s | 19.004MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0016.fof.smt2 |    0.015s | 19.128MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0260.fof.smt2 |    0.015s | 19.212MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0276.fof.smt2 |    0.015s | 19.024MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0094.fof.smt2 |    0.015s | 19.208MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0090.fof.smt2 |    0.015s | 19.212MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0351.fof.smt2 |    0.015s | 19.036MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0293.fof.smt2 |    0.015s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0140.fof.smt2 |    0.015s | 19.0MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0205.fof.smt2 |    0.015s | 19.096MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0066.fof.smt2 |    0.015s | 19.1MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0372.fof.smt2 |    0.015s | 19.024MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0312.fof.smt2 |    0.015s | 19.236MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0015.fof.smt2 |    0.015s | 19.12MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0340.fof.smt2 |    0.015s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0248.fof.smt2 |    0.015s | 19.148MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0101.fof.smt2 |    0.015s | 19.244MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0067.fof.smt2 |    0.015s | 19.024MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0222.fof.smt2 |    0.015s | 19.132MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0334.fof.smt2 |    0.015s | 19.092MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/thruster_symm_0158.fof.smt2 |    0.015s | 19.012MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0155.fof.smt2 |    0.015s | 19.112MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0010.fof.smt2 |    0.015s | 19.016MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0319.fof.smt2 |    0.015s | 19.02MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0196.fof.smt2 |    0.015s | 19.108MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0003.fof.smt2 |    0.015s | 19.152MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0198.fof.smt2 |    0.015s | 19.192MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0193.fof.smt2 |    0.015s | 19.196MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0268.fof.smt2 |    0.015s | 19.2MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0254.fof.smt2 |    0.015s | 19.192MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0026.fof.smt2 |    0.015s | 19.24MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0336.fof.smt2 |    0.015s | 19.208MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0095.fof.smt2 |    0.015s | 19.2MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0088.fof.smt2 |    0.015s | 19.12MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0178.fof.smt2 |    0.015s | 19.232MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0272.fof.smt2 |    0.015s | 19.212MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0071.fof.smt2 |    0.015s | 19.148MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0017.fof.smt2 |    0.015s | 19.208MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0188.fof.smt2 |    0.015s | 19.212MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0013.fof.smt2 |    0.015s | 19.184MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0134.fof.smt2 |    0.015s | 19.032MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0123.fof.smt2 |    0.015s | 19.016MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array/thruster_symm_0161.fof.smt2 |    0.015s | 19.192MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0112.fof.smt2 |    0.015s | 18.94MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0005.fof.smt2 |    0.015s | 19.192MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0051.fof.smt2 |    0.015s | 19.124MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0024.fof.smt2 |    0.015s | 19.244MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1061.fof.smt2 |    0.015s | 19.188MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0889.fof.smt2 |    0.015s | 19.124MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0651.fof.smt2 |    0.015s | 19.284MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0422.fof.smt2 |    0.015s | 19.052MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0052.fof.smt2 |    0.015s | 19.096MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1040.fof.smt2 |    0.015s | 19.14MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0970.fof.smt2 |    0.015s | 19.124MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0275.fof.smt2 |    0.015s | 19.096MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0998.fof.smt2 |    0.015s | 19.22MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0332.fof.smt2 |    0.015s | 19.24MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0163.fof.smt2 |    0.015s | 19.188MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0294.fof.smt2 |    0.015s | 19.248MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0013.fof.smt2 |    0.015s | 19.172MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1317.fof.smt2 |    0.015s | 19.244MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1229.fof.smt2 |    0.015s | 19.252MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1049.fof.smt2 |    0.015s | 19.296MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0009.fof.smt2 |    0.015s | 19.048MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0311.fof.smt2 |    0.015s | 19.176MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1320.fof.smt2 |    0.015s | 19.144MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1148.fof.smt2 |    0.015s | 19.276MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0801.fof.smt2 |    0.015s | 19.272MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0804.fof.smt2 |    0.015s | 19.196MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0570.fof.smt2 |    0.015s | 19.076MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1309.fof.smt2 |    0.015s | 19.22MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0528.fof.smt2 |    0.015s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/thruster_symm_1614.fof.smt2 |    0.015s | 19.032MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1192.fof.smt2 |    0.015s | 19.536MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1074.fof.smt2 |    0.015s | 19.288MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0034.fof.smt2 |    0.015s | 19.076MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0034.fof.smt2 |    0.015s | 19.128MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1059.fof.smt2 |    0.015s | 19.192MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0010.fof.smt2 |    0.015s | 19.032MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0543.fof.smt2 |    0.015s | 19.124MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1111.fof.smt2 |    0.015s | 19.164MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0149.fof.smt2 |    0.015s | 19.02MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0110.fof.smt2 |    0.015s | 19.016MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0047.fof.smt2 |    0.015s | 19.132MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0066.fof.smt2 |    0.015s | 19.212MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1046.fof.smt2 |    0.015s | 19.216MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0718.fof.smt2 |    0.015s | 19.156MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0658.fof.smt2 |    0.015s | 19.332MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0436.fof.smt2 |    0.015s | 19.208MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0045.fof.smt2 |    0.015s | 19.188MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0261.fof.smt2 |    0.015s | 18.992MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0630.fof.smt2 |    0.015s | 19.124MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0032.fof.smt2 |    0.015s | 19.148MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0035.fof.smt2 |    0.015s | 18.992MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1065.fof.smt2 |    0.015s | 19.224MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0348.fof.smt2 |    0.015s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0263.fof.smt2 |    0.015s | 19.0MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0069.fof.smt2 |    0.015s | 19.056MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0269.fof.smt2 |    0.015s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0089.fof.smt2 |    0.015s | 19.124MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0755.fof.smt2 |    0.015s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0130.fof.smt2 |    0.015s | 19.108MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0078.fof.smt2 |    0.015s | 19.116MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1058.fof.smt2 |    0.015s | 19.252MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1323.fof.smt2 |    0.015s | 19.2MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0769.fof.smt2 |    0.015s | 19.176MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0725.fof.smt2 |    0.015s | 19.108MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0042.fof.smt2 |    0.015s | 19.172MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0933.fof.smt2 |    0.015s | 19.144MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0006.fof.smt2 |    0.015s | 18.944MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1280.fof.smt2 |    0.015s | 19.276MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0808.fof.smt2 |    0.015s | 19.292MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1332.fof.smt2 |    0.015s | 19.316MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0445.fof.smt2 |    0.015s | 19.12MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0268.fof.smt2 |    0.015s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1162.fof.smt2 |    0.015s | 19.244MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0244.fof.smt2 |    0.015s | 19.124MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/thruster_symm_1537.fof.smt2 |    0.015s | 18.976MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0037.fof.smt2 |    0.015s | 18.984MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/thruster_symm_1689.fof.smt2 |    0.015s | 19.196MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1259.fof.smt2 |    0.015s | 19.228MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0017.fof.smt2 |    0.015s | 19.048MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1050.fof.smt2 |    0.015s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0984.fof.smt2 |    0.015s | 19.096MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1311.fof.smt2 |    0.015s | 19.14MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0002.fof.smt2 |    0.015s | 18.936MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0452.fof.smt2 |    0.015s | 19.124MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0207.fof.smt2 |    0.015s | 19.324MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0014.fof.smt2 |    0.015s | 19.1MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1037.fof.smt2 |    0.015s | 19.192MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0108.fof.smt2 |    0.015s | 19.056MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0789.fof.smt2 |    0.015s | 19.144MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0628.fof.smt2 |    0.015s | 19.192MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0553.fof.smt2 |    0.015s | 19.3MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0517.fof.smt2 |    0.015s | 19.184MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0289.fof.smt2 |    0.015s | 19.272MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0813.fof.smt2 |    0.015s | 19.12MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0044.fof.smt2 |    0.015s | 19.032MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0033.fof.smt2 |    0.015s | 19.244MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0799.fof.smt2 |    0.015s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_prop/thruster_symm_0010.fof.smt2 |    0.015s | 19.192MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0013.fof.smt2 |    0.015s | 18.976MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.637378.smt2               |    0.016s | 19.796MiB| sat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0009.fof.smt2 |    0.016s | 19.108MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0084.fof.smt2 |    0.016s | 19.204MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0024.fof.smt2 |    0.016s | 19.132MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0292.fof.smt2 |    0.016s | 19.176MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0182.fof.smt2 |    0.016s | 19.0MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0106.fof.smt2 |    0.016s | 19.18MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0321.fof.smt2 |    0.016s | 19.168MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0259.fof.smt2 |    0.016s | 19.212MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/thruster_symm_0153.fof.smt2 |    0.016s | 19.164MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0085.fof.smt2 |    0.016s | 19.18MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0373.fof.smt2 |    0.016s | 19.1MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0156.fof.smt2 |    0.016s | 19.164MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0330.fof.smt2 |    0.016s | 19.024MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0288.fof.smt2 |    0.016s | 19.084MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0307.fof.smt2 |    0.016s | 19.024MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0204.fof.smt2 |    0.016s | 19.208MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0265.fof.smt2 |    0.016s | 19.132MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0104.fof.smt2 |    0.016s | 19.232MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0075.fof.smt2 |    0.016s | 19.236MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0326.fof.smt2 |    0.016s | 19.168MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0235.fof.smt2 |    0.016s | 19.184MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0012.fof.smt2 |    0.016s | 18.98MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0360.fof.smt2 |    0.016s | 19.168MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0239.fof.smt2 |    0.016s | 19.232MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0102.fof.smt2 |    0.016s | 19.2MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0323.fof.smt2 |    0.016s | 18.988MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0369.fof.smt2 |    0.016s | 19.224MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0294.fof.smt2 |    0.016s | 19.0MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0253.fof.smt2 |    0.016s | 19.24MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0190.fof.smt2 |    0.016s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0346.fof.smt2 |    0.016s | 19.164MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0008.fof.smt2 |    0.016s | 19.224MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0074.fof.smt2 |    0.016s | 19.084MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0325.fof.smt2 |    0.016s | 19.016MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/cl5_nebula_norm_0004.fof.smt2 |    0.016s | 19.132MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0176.fof.smt2 |    0.016s | 19.056MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0314.fof.smt2 |    0.016s | 19.076MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0225.fof.smt2 |    0.016s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0108.fof.smt2 |    0.016s | 19.18MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0366.fof.smt2 |    0.016s | 19.032MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0378.fof.smt2 |    0.016s | 19.132MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0309.fof.smt2 |    0.016s | 19.008MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0115.fof.smt2 |    0.016s | 19.108MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0069.fof.smt2 |    0.016s | 19.2MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0258.fof.smt2 |    0.016s | 19.128MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0164.fof.smt2 |    0.016s | 19.132MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0359.fof.smt2 |    0.016s | 18.988MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0226.fof.smt2 |    0.016s | 19.096MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0223.fof.smt2 |    0.016s | 19.204MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0337.fof.smt2 |    0.016s | 19.164MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0143.fof.smt2 |    0.016s | 19.156MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0124.fof.smt2 |    0.016s | 19.216MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0297.fof.smt2 |    0.016s | 19.14MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0060.fof.smt2 |    0.016s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0266.fof.smt2 |    0.016s | 19.224MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/cl5_nebula_norm_0008.fof.smt2 |    0.016s | 19.132MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0273.fof.smt2 |    0.016s | 19.224MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0130.fof.smt2 |    0.016s | 19.088MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0018.fof.smt2 |    0.016s | 19.236MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0335.fof.smt2 |    0.016s | 19.128MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0087.fof.smt2 |    0.016s | 19.22MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0034.fof.smt2 |    0.016s | 19.112MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0136.fof.smt2 |    0.016s | 19.224MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0047.fof.smt2 |    0.016s | 19.124MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0145.fof.smt2 |    0.016s | 19.208MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0324.fof.smt2 |    0.016s | 19.164MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0291.fof.smt2 |    0.016s | 19.22MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/cl5_nebula_norm_0010.fof.smt2 |    0.016s | 19.204MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0236.fof.smt2 |    0.016s | 19.188MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0023.fof.smt2 |    0.016s | 19.168MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0149.fof.smt2 |    0.016s | 19.148MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0118.fof.smt2 |    0.016s | 19.036MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0021.fof.smt2 |    0.016s | 19.132MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0037.fof.smt2 |    0.016s | 19.208MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0103.fof.smt2 |    0.016s | 19.18MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0287.fof.smt2 |    0.016s | 18.992MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0144.fof.smt2 |    0.016s | 19.196MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0375.fof.smt2 |    0.016s | 19.188MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0068.fof.smt2 |    0.016s | 19.168MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0237.fof.smt2 |    0.016s | 19.064MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0331.fof.smt2 |    0.016s | 19.164MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0211.fof.smt2 |    0.016s | 19.22MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0356.fof.smt2 |    0.016s | 18.992MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0137.fof.smt2 |    0.016s | 19.14MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0284.fof.smt2 |    0.016s | 19.208MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0046.fof.smt2 |    0.016s | 19.208MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0208.fof.smt2 |    0.016s | 19.152MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0045.fof.smt2 |    0.016s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0261.fof.smt2 |    0.016s | 19.092MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0279.fof.smt2 |    0.016s | 19.132MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0044.fof.smt2 |    0.016s | 19.24MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0388.fof.smt2 |    0.016s | 19.08MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0310.fof.smt2 |    0.016s | 19.24MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0286.fof.smt2 |    0.016s | 19.1MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0354.fof.smt2 |    0.016s | 18.988MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0234.fof.smt2 |    0.016s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0339.fof.smt2 |    0.016s | 19.164MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0056.fof.smt2 |    0.016s | 19.12MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0172.fof.smt2 |    0.016s | 19.156MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0342.fof.smt2 |    0.016s | 19.076MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0031.fof.smt2 |    0.016s | 19.244MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0065.fof.smt2 |    0.016s | 19.16MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/cl5_nebula_norm_0006.fof.smt2 |    0.016s | 19.076MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0347.fof.smt2 |    0.016s | 19.148MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0121.fof.smt2 |    0.016s | 19.12MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0203.fof.smt2 |    0.016s | 19.088MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0058.fof.smt2 |    0.016s | 19.208MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0022.fof.smt2 |    0.016s | 19.144MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0128.fof.smt2 |    0.016s | 19.064MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0224.fof.smt2 |    0.016s | 19.224MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0364.fof.smt2 |    0.016s | 19.112MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0139.fof.smt2 |    0.016s | 19.148MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0197.fof.smt2 |    0.016s | 19.008MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0061.fof.smt2 |    0.016s | 19.144MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0264.fof.smt2 |    0.016s | 19.012MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0051.fof.smt2 |    0.016s | 19.0MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0219.fof.smt2 |    0.016s | 19.208MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0304.fof.smt2 |    0.016s | 19.22MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0384.fof.smt2 |    0.016s | 19.188MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0036.fof.smt2 |    0.016s | 19.016MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0280.fof.smt2 |    0.016s | 19.092MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0318.fof.smt2 |    0.016s | 19.008MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0050.fof.smt2 |    0.016s | 19.216MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0329.fof.smt2 |    0.016s | 19.16MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0382.fof.smt2 |    0.016s | 19.18MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0091.fof.smt2 |    0.016s | 19.232MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0004.fof.smt2 |    0.016s | 19.144MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0271.fof.smt2 |    0.016s | 19.22MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0185.fof.smt2 |    0.016s | 19.152MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0054.fof.smt2 |    0.016s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0246.fof.smt2 |    0.016s | 19.188MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0217.fof.smt2 |    0.016s | 19.1MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0148.fof.smt2 |    0.016s | 19.12MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0006.fof.smt2 |    0.016s | 19.064MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0098.fof.smt2 |    0.016s | 19.18MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0316.fof.smt2 |    0.016s | 19.156MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0277.fof.smt2 |    0.016s | 19.232MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0011.fof.smt2 |    0.016s | 19.184MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0062.fof.smt2 |    0.016s | 19.064MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0159.fof.smt2 |    0.016s | 19.204MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0132.fof.smt2 |    0.016s | 19.016MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0126.fof.smt2 |    0.016s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0200.fof.smt2 |    0.016s | 19.24MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0244.fof.smt2 |    0.016s | 19.032MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0029.fof.smt2 |    0.016s | 19.052MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0027.fof.smt2 |    0.016s | 19.132MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0147.fof.smt2 |    0.016s | 19.124MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0168.fof.smt2 |    0.016s | 19.064MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0142.fof.smt2 |    0.016s | 19.08MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0381.fof.smt2 |    0.016s | 19.196MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0048.fof.smt2 |    0.016s | 19.22MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0100.fof.smt2 |    0.016s | 19.24MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0109.fof.smt2 |    0.016s | 19.1MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0220.fof.smt2 |    0.016s | 19.14MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0349.fof.smt2 |    0.016s | 19.132MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0002.fof.smt2 |    0.016s | 19.08MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0213.fof.smt2 |    0.016s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0207.fof.smt2 |    0.016s | 19.14MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0177.fof.smt2 |    0.016s | 19.184MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0038.fof.smt2 |    0.016s | 19.212MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0379.fof.smt2 |    0.016s | 19.128MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0353.fof.smt2 |    0.016s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0116.fof.smt2 |    0.016s | 19.132MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0039.fof.smt2 |    0.016s | 19.24MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0357.fof.smt2 |    0.016s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0154.fof.smt2 |    0.016s | 19.044MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0070.fof.smt2 |    0.016s | 19.212MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0114.fof.smt2 |    0.016s | 19.196MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0289.fof.smt2 |    0.016s | 19.18MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0221.fof.smt2 |    0.016s | 19.108MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0363.fof.smt2 |    0.016s | 19.136MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0387.fof.smt2 |    0.016s | 19.164MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0262.fof.smt2 |    0.016s | 19.224MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0295.fof.smt2 |    0.016s | 19.172MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0033.fof.smt2 |    0.016s | 19.132MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0371.fof.smt2 |    0.016s | 19.024MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array/thruster_symm_0162.fof.smt2 |    0.016s | 19.08MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1328.fof.smt2 |    0.016s | 19.272MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0489.fof.smt2 |    0.016s | 19.116MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0926.fof.smt2 |    0.016s | 19.036MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1081.fof.smt2 |    0.016s | 19.14MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0071.fof.smt2 |    0.016s | 19.044MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0064.fof.smt2 |    0.016s | 19.156MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0786.fof.smt2 |    0.016s | 19.092MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1482.fof.smt2 |    0.016s | 19.0MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0156.fof.smt2 |    0.016s | 19.216MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0265.fof.smt2 |    0.016s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0075.fof.smt2 |    0.016s | 19.056MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1043.fof.smt2 |    0.016s | 19.248MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0591.fof.smt2 |    0.016s | 19.172MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0524.fof.smt2 |    0.016s | 19.224MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0526.fof.smt2 |    0.016s | 19.172MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1169.fof.smt2 |    0.016s | 19.08MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1306.fof.smt2 |    0.016s | 19.056MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/thruster_symm_1735.fof.smt2 |    0.016s | 19.228MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0797.fof.smt2 |    0.016s | 19.064MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1183.fof.smt2 |    0.016s | 19.136MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1007.fof.smt2 |    0.016s | 19.248MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0008.fof.smt2 |    0.016s | 19.084MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0012.fof.smt2 |    0.016s | 18.968MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1301.fof.smt2 |    0.016s | 19.208MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0954.fof.smt2 |    0.016s | 19.296MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0077.fof.smt2 |    0.016s | 19.184MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0910.fof.smt2 |    0.016s | 19.148MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0030.fof.smt2 |    0.016s | 19.232MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/thruster_symm_1697.fof.smt2 |    0.016s | 19.192MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0688.fof.smt2 |    0.016s | 19.136MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0278.fof.smt2 |    0.016s | 19.044MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0223.fof.smt2 |    0.016s | 19.14MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1044.fof.smt2 |    0.016s | 19.116MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0538.fof.smt2 |    0.016s | 19.224MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0266.fof.smt2 |    0.016s | 18.992MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0267.fof.smt2 |    0.016s | 19.188MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0527.fof.smt2 |    0.016s | 19.2MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0829.fof.smt2 |    0.016s | 19.188MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0282.fof.smt2 |    0.016s | 19.092MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1146.fof.smt2 |    0.016s | 19.156MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1109.fof.smt2 |    0.016s | 19.148MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1326.fof.smt2 |    0.016s | 19.308MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1042.fof.smt2 |    0.016s | 19.088MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0016.fof.smt2 |    0.016s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1063.fof.smt2 |    0.016s | 19.164MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0291.fof.smt2 |    0.016s | 19.136MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1243.fof.smt2 |    0.016s | 19.128MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0809.fof.smt2 |    0.016s | 19.18MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0674.fof.smt2 |    0.016s | 18.98MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0519.fof.smt2 |    0.016s | 19.008MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1041.fof.smt2 |    0.016s | 18.964MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0037.fof.smt2 |    0.016s | 19.264MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0102.fof.smt2 |    0.016s | 19.02MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0237.fof.smt2 |    0.016s | 19.168MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1000.fof.smt2 |    0.016s | 19.172MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0520.fof.smt2 |    0.016s | 18.968MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0284.fof.smt2 |    0.016s | 19.172MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0880.fof.smt2 |    0.016s | 19.288MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1368.fof.smt2 |    0.016s | 19.284MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0681.fof.smt2 |    0.016s | 19.108MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0593.fof.smt2 |    0.016s | 19.124MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/thruster_symm_1628.fof.smt2 |    0.016s | 19.172MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0063.fof.smt2 |    0.016s | 18.992MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0251.fof.smt2 |    0.016s | 19.172MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1318.fof.smt2 |    0.016s | 19.204MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1062.fof.smt2 |    0.016s | 19.096MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0286.fof.smt2 |    0.016s | 19.308MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0584.fof.smt2 |    0.016s | 19.132MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0836.fof.smt2 |    0.016s | 19.136MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1053.fof.smt2 |    0.016s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0041.fof.smt2 |    0.016s | 19.0MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0537.fof.smt2 |    0.016s | 19.248MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/thruster_symm_1475.fof.smt2 |    0.016s | 19.092MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0541.fof.smt2 |    0.016s | 19.288MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0784.fof.smt2 |    0.016s | 19.14MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0082.fof.smt2 |    0.016s | 19.144MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1139.fof.smt2 |    0.016s | 19.236MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1088.fof.smt2 |    0.016s | 19.288MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1064.fof.smt2 |    0.016s | 19.088MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1068.fof.smt2 |    0.016s | 19.196MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1155.fof.smt2 |    0.016s | 19.16MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0072.fof.smt2 |    0.016s | 19.128MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0556.fof.smt2 |    0.016s | 19.088MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0695.fof.smt2 |    0.016s | 19.292MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0529.fof.smt2 |    0.016s | 19.228MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0803.fof.smt2 |    0.016s | 19.06MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0038.fof.smt2 |    0.016s | 19.172MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0281.fof.smt2 |    0.016s | 19.176MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0036.fof.smt2 |    0.016s | 19.16MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0025.fof.smt2 |    0.016s | 19.056MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0822.fof.smt2 |    0.016s | 19.06MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0459.fof.smt2 |    0.016s | 19.204MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0046.fof.smt2 |    0.016s | 19.076MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0550.fof.smt2 |    0.016s | 19.276MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0271.fof.smt2 |    0.016s | 19.096MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0003.fof.smt2 |    0.016s | 18.98MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0607.fof.smt2 |    0.016s | 19.244MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0496.fof.smt2 |    0.016s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1312.fof.smt2 |    0.016s | 19.172MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0532.fof.smt2 |    0.016s | 19.24MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0277.fof.smt2 |    0.016s | 19.184MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0011.fof.smt2 |    0.016s | 19.156MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0554.fof.smt2 |    0.016s | 19.128MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0814.fof.smt2 |    0.016s | 19.304MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0193.fof.smt2 |    0.016s | 19.016MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0552.fof.smt2 |    0.016s | 19.136MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0126.fof.smt2 |    0.016s | 19.012MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0147.fof.smt2 |    0.016s | 19.1MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0787.fof.smt2 |    0.016s | 19.228MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1298.fof.smt2 |    0.016s | 19.3MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1250.fof.smt2 |    0.016s | 19.224MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0791.fof.smt2 |    0.016s | 19.14MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0272.fof.smt2 |    0.016s | 19.14MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0480.fof.smt2 |    0.016s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0807.fof.smt2 |    0.016s | 19.128MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0525.fof.smt2 |    0.016s | 19.204MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1307.fof.smt2 |    0.016s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0065.fof.smt2 |    0.016s | 19.164MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1048.fof.smt2 |    0.016s | 19.112MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0739.fof.smt2 |    0.016s | 19.308MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0110.fof.smt2 |    0.016s | 19.064MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0547.fof.smt2 |    0.016s | 19.264MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0812.fof.smt2 |    0.016s | 19.312MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0977.fof.smt2 |    0.016s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0802.fof.smt2 |    0.016s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0415.fof.smt2 |    0.016s | 18.988MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0637.fof.smt2 |    0.016s | 19.14MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0408.fof.smt2 |    0.016s | 19.132MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0221.fof.smt2 |    0.016s | 19.084MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0103.fof.smt2 |    0.016s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0262.fof.smt2 |    0.016s | 19.188MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0542.fof.smt2 |    0.016s | 19.152MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0020.fof.smt2 |    0.016s | 19.108MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0017.fof.smt2 |    0.016s | 19.176MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1028.fof.smt2 |    0.016s | 19.092MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_prop/thruster_symm_0016.fof.smt2 |    0.016s | 19.172MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_prop/thruster_symm_0017.fof.smt2 |    0.016s | 19.144MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.637239.smt2               |    0.017s | 20.048MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.634265.smt2                   |    0.017s | 20.044MiB| sat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.637413.smt2               |    0.017s | 20.044MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0245.fof.smt2 |    0.017s | 19.212MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0390.fof.smt2 |    0.017s | 19.144MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0072.fof.smt2 |    0.017s | 18.992MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0035.fof.smt2 |    0.017s | 19.248MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0301.fof.smt2 |    0.017s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0338.fof.smt2 |    0.017s | 19.24MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0001.fof.smt2 |    0.017s | 19.2MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0096.fof.smt2 |    0.017s | 19.02MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0365.fof.smt2 |    0.017s | 19.124MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0073.fof.smt2 |    0.017s | 19.076MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0238.fof.smt2 |    0.017s | 19.1MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0138.fof.smt2 |    0.017s | 19.004MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0173.fof.smt2 |    0.017s | 19.196MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0252.fof.smt2 |    0.017s | 19.044MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0063.fof.smt2 |    0.017s | 19.064MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0040.fof.smt2 |    0.017s | 19.056MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0327.fof.smt2 |    0.017s | 19.0MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0240.fof.smt2 |    0.017s | 19.096MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0166.fof.smt2 |    0.017s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0283.fof.smt2 |    0.017s | 19.076MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0311.fof.smt2 |    0.017s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0328.fof.smt2 |    0.017s | 19.212MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0270.fof.smt2 |    0.017s | 19.22MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0186.fof.smt2 |    0.017s | 19.2MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0278.fof.smt2 |    0.017s | 19.16MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0233.fof.smt2 |    0.017s | 19.096MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0377.fof.smt2 |    0.017s | 18.984MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0113.fof.smt2 |    0.017s | 19.192MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0180.fof.smt2 |    0.017s | 19.24MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0215.fof.smt2 |    0.017s | 19.116MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0183.fof.smt2 |    0.017s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0086.fof.smt2 |    0.017s | 19.164MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0306.fof.smt2 |    0.017s | 19.092MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0355.fof.smt2 |    0.017s | 19.12MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0344.fof.smt2 |    0.017s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0119.fof.smt2 |    0.017s | 19.2MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0117.fof.smt2 |    0.017s | 19.156MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0171.fof.smt2 |    0.017s | 19.04MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0184.fof.smt2 |    0.017s | 19.144MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0077.fof.smt2 |    0.017s | 19.232MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0251.fof.smt2 |    0.017s | 19.1MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0032.fof.smt2 |    0.017s | 19.188MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0290.fof.smt2 |    0.017s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0343.fof.smt2 |    0.017s | 19.04MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0019.fof.smt2 |    0.017s | 19.216MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0131.fof.smt2 |    0.017s | 19.004MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0079.fof.smt2 |    0.017s | 19.236MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0042.fof.smt2 |    0.017s | 19.168MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0368.fof.smt2 |    0.017s | 19.188MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0308.fof.smt2 |    0.017s | 19.208MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0028.fof.smt2 |    0.017s | 19.22MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0383.fof.smt2 |    0.017s | 19.2MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0093.fof.smt2 |    0.017s | 19.232MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0055.fof.smt2 |    0.017s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0348.fof.smt2 |    0.017s | 19.164MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0263.fof.smt2 |    0.017s | 19.032MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0269.fof.smt2 |    0.017s | 19.18MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0089.fof.smt2 |    0.017s | 19.124MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0080.fof.smt2 |    0.017s | 19.22MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0341.fof.smt2 |    0.017s | 19.036MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0281.fof.smt2 |    0.017s | 19.048MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0300.fof.smt2 |    0.017s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0202.fof.smt2 |    0.017s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0129.fof.smt2 |    0.017s | 19.096MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0380.fof.smt2 |    0.017s | 18.992MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0250.fof.smt2 |    0.017s | 19.052MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0362.fof.smt2 |    0.017s | 19.22MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0150.fof.smt2 |    0.017s | 19.088MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0192.fof.smt2 |    0.017s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0247.fof.smt2 |    0.017s | 19.248MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0227.fof.smt2 |    0.017s | 18.984MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0049.fof.smt2 |    0.017s | 19.064MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0111.fof.smt2 |    0.017s | 19.176MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0229.fof.smt2 |    0.017s | 19.204MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0210.fof.smt2 |    0.017s | 19.212MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0374.fof.smt2 |    0.017s | 19.06MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0274.fof.smt2 |    0.017s | 19.2MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0157.fof.smt2 |    0.017s | 19.22MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0232.fof.smt2 |    0.017s | 19.04MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0230.fof.smt2 |    0.017s | 19.2MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0007.fof.smt2 |    0.017s | 19.016MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0160.fof.smt2 |    0.017s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0041.fof.smt2 |    0.017s | 19.016MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0020.fof.smt2 |    0.017s | 18.988MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0249.fof.smt2 |    0.017s | 19.02MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0167.fof.smt2 |    0.017s | 19.136MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0014.fof.smt2 |    0.017s | 19.216MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0076.fof.smt2 |    0.017s | 19.06MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0043.fof.smt2 |    0.017s | 18.988MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0317.fof.smt2 |    0.017s | 19.092MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0189.fof.smt2 |    0.017s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0376.fof.smt2 |    0.017s | 19.064MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0151.fof.smt2 |    0.017s | 19.124MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0161.fof.smt2 |    0.017s | 19.244MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0165.fof.smt2 |    0.017s | 19.176MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array/thruster_symm_0160.fof.smt2 |    0.017s | 19.172MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0009.fof.smt2 |    0.017s | 19.112MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1038.fof.smt2 |    0.017s | 19.3MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0096.fof.smt2 |    0.017s | 19.212MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0050.fof.smt2 |    0.017s | 19.168MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0369.fof.smt2 |    0.017s | 19.12MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0285.fof.smt2 |    0.017s | 19.084MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0018.fof.smt2 |    0.017s | 19.012MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1057.fof.smt2 |    0.017s | 19.06MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0399.fof.smt2 |    0.017s | 19.148MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0068.fof.smt2 |    0.017s | 19.08MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0503.fof.smt2 |    0.017s | 19.044MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0961.fof.smt2 |    0.017s | 19.096MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0378.fof.smt2 |    0.017s | 18.952MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1072.fof.smt2 |    0.017s | 19.192MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0101.fof.smt2 |    0.017s | 19.164MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0170.fof.smt2 |    0.017s | 19.212MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0473.fof.smt2 |    0.017s | 19.096MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0186.fof.smt2 |    0.017s | 19.18MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1329.fof.smt2 |    0.017s | 19.212MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1287.fof.smt2 |    0.017s | 19.212MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0049.fof.smt2 |    0.017s | 19.092MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0466.fof.smt2 |    0.017s | 19.168MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0548.fof.smt2 |    0.017s | 19.292MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0748.fof.smt2 |    0.017s | 19.024MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0018.fof.smt2 |    0.017s | 19.076MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0563.fof.smt2 |    0.017s | 19.192MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0852.fof.smt2 |    0.017s | 19.228MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1308.fof.smt2 |    0.017s | 19.192MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0260.fof.smt2 |    0.017s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0991.fof.smt2 |    0.017s | 19.244MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0811.fof.smt2 |    0.017s | 19.3MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0782.fof.smt2 |    0.017s | 19.156MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0917.fof.smt2 |    0.017s | 19.248MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0780.fof.smt2 |    0.017s | 19.136MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0023.fof.smt2 |    0.017s | 19.276MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1066.fof.smt2 |    0.017s | 19.308MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0947.fof.smt2 |    0.017s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1095.fof.smt2 |    0.017s | 19.18MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0296.fof.smt2 |    0.017s | 19.292MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0184.fof.smt2 |    0.017s | 19.172MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0019.fof.smt2 |    0.017s | 19.052MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0896.fof.smt2 |    0.017s | 18.976MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0810.fof.smt2 |    0.017s | 19.304MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0859.fof.smt2 |    0.017s | 19.228MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0011.fof.smt2 |    0.017s | 19.2MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0544.fof.smt2 |    0.017s | 19.224MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1060.fof.smt2 |    0.017s | 19.14MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0963.fof.smt2 |    0.017s | 19.228MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0031.fof.smt2 |    0.017s | 19.224MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0079.fof.smt2 |    0.017s | 18.984MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0545.fof.smt2 |    0.017s | 19.188MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0577.fof.smt2 |    0.017s | 19.148MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1054.fof.smt2 |    0.017s | 19.176MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0533.fof.smt2 |    0.017s | 18.96MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0028.fof.smt2 |    0.017s | 19.264MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1321.fof.smt2 |    0.017s | 19.188MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0644.fof.smt2 |    0.017s | 19.124MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0032.fof.smt2 |    0.017s | 19.016MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1296.fof.smt2 |    0.017s | 19.124MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0334.fof.smt2 |    0.017s | 19.172MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0873.fof.smt2 |    0.017s | 19.244MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0107.fof.smt2 |    0.017s | 19.204MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1067.fof.smt2 |    0.017s | 19.12MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1294.fof.smt2 |    0.017s | 19.296MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0043.fof.smt2 |    0.017s | 19.1MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0304.fof.smt2 |    0.017s | 19.2MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0341.fof.smt2 |    0.017s | 19.016MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0280.fof.smt2 |    0.017s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0800.fof.smt2 |    0.017s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0551.fof.smt2 |    0.017s | 19.208MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0539.fof.smt2 |    0.017s | 19.216MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0940.fof.smt2 |    0.017s | 19.24MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0540.fof.smt2 |    0.017s | 19.252MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0362.fof.smt2 |    0.017s | 19.252MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0667.fof.smt2 |    0.017s | 19.156MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1070.fof.smt2 |    0.017s | 19.16MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0100.fof.smt2 |    0.017s | 19.0MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0843.fof.smt2 |    0.017s | 19.212MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1313.fof.smt2 |    0.017s | 19.136MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1069.fof.smt2 |    0.017s | 19.14MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1333.fof.smt2 |    0.017s | 19.22MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0274.fof.smt2 |    0.017s | 19.22MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0230.fof.smt2 |    0.017s | 19.0MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0007.fof.smt2 |    0.017s | 19.188MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0026.fof.smt2 |    0.017s | 19.292MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0029.fof.smt2 |    0.017s | 19.272MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0530.fof.smt2 |    0.017s | 19.292MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0406.fof.smt2 |    0.017s | 19.172MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1125.fof.smt2 |    0.017s | 19.144MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0129.fof.smt2 |    0.017s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1361.fof.smt2 |    0.017s | 19.292MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0850.fof.smt2 |    0.017s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0020.fof.smt2 |    0.017s | 19.236MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0741.fof.smt2 |    0.017s | 19.02MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1206.fof.smt2 |    0.017s | 19.252MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0806.fof.smt2 |    0.017s | 19.176MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/thruster_symm_1620.fof.smt2 |    0.017s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0177.fof.smt2 |    0.017s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0038.fof.smt2 |    0.017s | 19.032MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/thruster_symm_1552.fof.smt2 |    0.017s | 19.116MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0796.fof.smt2 |    0.017s | 19.144MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0732.fof.smt2 |    0.017s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0392.fof.smt2 |    0.017s | 19.18MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0778.fof.smt2 |    0.017s | 19.148MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0600.fof.smt2 |    0.017s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0521.fof.smt2 |    0.017s | 19.004MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1236.fof.smt2 |    0.017s | 19.252MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0371.fof.smt2 |    0.017s | 19.056MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1331.fof.smt2 |    0.017s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0762.fof.smt2 |    0.017s | 19.212MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_prop/thruster_symm_0013.fof.smt2 |    0.017s | 19.172MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_prop/thruster_symm_0015.fof.smt2 |    0.017s | 19.176MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.629057.smt2               |    0.018s | 19.532MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0195.fof.smt2 |    0.018s | 19.124MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0064.fof.smt2 |    0.018s | 19.192MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0209.fof.smt2 |    0.018s | 19.052MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0052.fof.smt2 |    0.018s | 19.016MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0242.fof.smt2 |    0.018s | 19.16MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0181.fof.smt2 |    0.018s | 19.04MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0332.fof.smt2 |    0.018s | 18.98MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0194.fof.smt2 |    0.018s | 19.18MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0285.fof.smt2 |    0.018s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0146.fof.smt2 |    0.018s | 19.216MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0169.fof.smt2 |    0.018s | 19.132MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0333.fof.smt2 |    0.018s | 19.08MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0174.fof.smt2 |    0.018s | 19.092MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0350.fof.smt2 |    0.018s | 19.16MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0162.fof.smt2 |    0.018s | 19.156MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0107.fof.smt2 |    0.018s | 19.124MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0241.fof.smt2 |    0.018s | 18.984MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0152.fof.smt2 |    0.018s | 19.14MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0158.fof.smt2 |    0.018s | 19.116MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0191.fof.smt2 |    0.018s | 19.192MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0179.fof.smt2 |    0.018s | 19.232MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0385.fof.smt2 |    0.018s | 19.176MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0320.fof.smt2 |    0.018s | 19.16MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0099.fof.smt2 |    0.018s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0389.fof.smt2 |    0.018s | 19.08MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0105.fof.smt2 |    0.018s | 19.0MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0081.fof.smt2 |    0.018s | 19.008MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0231.fof.smt2 |    0.018s | 19.172MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0296.fof.smt2 |    0.018s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0005.fof.smt2 |    0.018s | 19.22MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0092.fof.smt2 |    0.018s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0082.fof.smt2 |    0.018s | 19.132MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0025.fof.smt2 |    0.018s | 19.164MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0313.fof.smt2 |    0.018s | 19.14MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0257.fof.smt2 |    0.018s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0078.fof.smt2 |    0.018s | 19.216MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0345.fof.smt2 |    0.018s | 19.156MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0218.fof.smt2 |    0.018s | 19.18MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0110.fof.smt2 |    0.018s | 19.148MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0059.fof.smt2 |    0.018s | 19.132MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0302.fof.smt2 |    0.018s | 19.204MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0083.fof.smt2 |    0.018s | 19.048MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0303.fof.smt2 |    0.018s | 19.212MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0175.fof.smt2 |    0.018s | 19.124MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0255.fof.smt2 |    0.018s | 19.1MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array/quaternion_ds1_symm_0418.fof.smt2 |    0.018s | 18.972MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array/thruster_symm_0164.fof.smt2 |    0.018s | 19.2MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0783.fof.smt2 |    0.018s | 19.172MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0001.fof.smt2 |    0.018s | 19.148MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0665.fof.smt2 |    0.018s | 19.132MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0073.fof.smt2 |    0.018s | 19.16MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0325.fof.smt2 |    0.018s | 19.276MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1220.fof.smt2 |    0.018s | 19.2MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1045.fof.smt2 |    0.018s | 19.2MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0776.fof.smt2 |    0.018s | 19.304MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0704.fof.smt2 |    0.018s | 19.232MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1324.fof.smt2 |    0.018s | 19.056MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1310.fof.smt2 |    0.018s | 19.308MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1185.fof.smt2 |    0.018s | 19.232MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0276.fof.smt2 |    0.018s | 19.132MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0535.fof.smt2 |    0.018s | 19.044MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1051.fof.smt2 |    0.018s | 19.132MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1303.fof.smt2 |    0.018s | 19.056MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0287.fof.smt2 |    0.018s | 19.14MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0903.fof.smt2 |    0.018s | 19.128MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0788.fof.smt2 |    0.018s | 19.24MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1340.fof.smt2 |    0.018s | 19.256MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0015.fof.smt2 |    0.018s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1021.fof.smt2 |    0.018s | 19.296MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0070.fof.smt2 |    0.018s | 19.084MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0290.fof.smt2 |    0.018s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1330.fof.smt2 |    0.018s | 19.184MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0792.fof.smt2 |    0.018s | 19.212MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1327.fof.smt2 |    0.018s | 19.14MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0781.fof.smt2 |    0.018s | 19.128MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1266.fof.smt2 |    0.018s | 19.26MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0318.fof.smt2 |    0.018s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0200.fof.smt2 |    0.018s | 19.168MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0866.fof.smt2 |    0.018s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0482.fof.smt2 |    0.018s | 19.112MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0059.fof.smt2 |    0.018s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1314.fof.smt2 |    0.018s | 19.22MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0295.fof.smt2 |    0.018s | 19.196MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_prop/thruster_symm_0014.fof.smt2 |    0.018s | 19.212MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.629335.smt2               |    0.019s | 19.332MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0315.fof.smt2 |    0.019s | 19.172MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0228.fof.smt2 |    0.019s | 19.204MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0352.fof.smt2 |    0.019s | 19.024MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0267.fof.smt2 |    0.019s | 19.228MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0120.fof.smt2 |    0.019s | 19.08MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0187.fof.smt2 |    0.019s | 19.22MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0057.fof.smt2 |    0.019s | 19.044MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0292.fof.smt2 |    0.019s | 19.168MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0523.fof.smt2 |    0.019s | 19.236MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1199.fof.smt2 |    0.019s | 19.152MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0805.fof.smt2 |    0.019s | 19.092MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0288.fof.smt2 |    0.019s | 19.176MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0795.fof.smt2 |    0.019s | 19.288MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1071.fof.smt2 |    0.019s | 19.14MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0790.fof.smt2 |    0.019s | 19.296MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0004.fof.smt2 |    0.019s | 19.016MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0273.fof.smt2 |    0.019s | 19.14MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1316.fof.smt2 |    0.019s | 19.064MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0443.fof.smt2 |    0.019s | 19.164MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0103.fof.smt2 |    0.019s | 19.112MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0355.fof.smt2 |    0.019s | 19.26MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0036.fof.smt2 |    0.019s | 19.148MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0815.fof.smt2 |    0.019s | 19.268MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1325.fof.smt2 |    0.019s | 19.084MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0887.fof.smt2 |    0.019s | 19.236MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0264.fof.smt2 |    0.019s | 19.088MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0010.fof.smt2 |    0.019s | 19.024MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1222.fof.smt2 |    0.019s | 19.136MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0027.fof.smt2 |    0.019s | 19.248MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0549.fof.smt2 |    0.019s | 19.072MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0522.fof.smt2 |    0.019s | 19.172MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0793.fof.smt2 |    0.019s | 19.068MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0702.fof.smt2 |    0.019s | 19.084MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0013.fof.smt2 |    0.019s | 19.164MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1052.fof.smt2 |    0.019s | 19.052MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1300.fof.smt2 |    0.019s | 19.016MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0711.fof.smt2 |    0.019s | 19.236MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1273.fof.smt2 |    0.019s | 19.264MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0076.fof.smt2 |    0.019s | 18.996MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0924.fof.smt2 |    0.019s | 19.272MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0305.fof.smt2 |    0.020s | 19.096MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0370.fof.smt2 |    0.020s | 19.212MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0021.fof.smt2 |    0.020s | 20.376MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1132.fof.smt2 |    0.020s | 19.128MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1055.fof.smt2 |    0.020s | 19.3MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0109.fof.smt2 |    0.020s | 19.196MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0510.fof.smt2 |    0.020s | 19.256MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0099.fof.smt2 |    0.020s | 20.396MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0429.fof.smt2 |    0.020s | 19.3MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0121.fof.smt2 |    0.020s | 19.128MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1305.fof.smt2 |    0.020s | 19.208MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1014.fof.smt2 |    0.020s | 19.284MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0122.fof.smt2 |    0.020s | 19.048MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0534.fof.smt2 |    0.020s | 19.164MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_prop/quaternion_ds1_symm_0005.fof.smt2 |    0.020s | 19.184MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/why/smtlibf37c88.smt2                |    0.021s | 19.272MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/why/smtlib5966a0.smt2                |    0.021s | 19.24MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0298.fof.smt2 |    0.021s | 19.124MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array/cl5_nebula_norm_0004.fof.smt2 |    0.021s | 20.368MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0012.fof.smt2 |    0.021s | 19.172MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0022.fof.smt2 |    0.021s | 20.388MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0794.fof.smt2 |    0.021s | 19.104MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0073.fof.smt2 |    0.021s | 20.5MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_prop/cl5_nebula_norm_0003.fof.smt2 |    0.021s | 20.336MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.638953.smt2               |    0.022s | 19.532MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/why/smtlib7a3a8e.smt2                |    0.022s | 19.396MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/cl5_nebula_norm_0005.fof.smt2 |    0.022s | 20.236MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/cl5_nebula_norm_0013.fof.smt2 |    0.022s | 20.488MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/cl5_nebula_norm_0009.fof.smt2 |    0.022s | 20.452MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0322.fof.smt2 |    0.022s | 18.968MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0080.fof.smt2 |    0.022s | 20.584MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0030.fof.smt2 |    0.022s | 20.356MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0112.fof.smt2 |    0.022s | 20.232MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0134.fof.smt2 |    0.022s | 20.392MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/thruster_symm_1658.fof.smt2 |    0.022s | 19.124MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0081.fof.smt2 |    0.022s | 20.456MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0104.fof.smt2 |    0.022s | 20.424MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0007.fof.smt2 |    0.022s | 20.528MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0131.fof.smt2 |    0.022s | 20.34MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0016.fof.smt2 |    0.022s | 20.428MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0032.fof.smt2 |    0.022s | 20.472MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0037.fof.smt2 |    0.022s | 20.372MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.640322.smt2               |    0.023s | 19.228MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/why/smtlibce35b2.smt2                |    0.023s | 19.304MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/cl5_nebula_norm_0003.fof.smt2 |    0.023s | 20.292MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/quaternion_ds1_symm_0299.fof.smt2 |    0.023s | 19.036MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/cl5_nebula_norm_0007.fof.smt2 |    0.023s | 20.548MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/cl5_nebula_norm_0014.fof.smt2 |    0.023s | 20.416MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array/cl5_nebula_norm_0003.fof.smt2 |    0.023s | 20.344MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array/cl5_nebula_norm_0023.fof.smt2 |    0.023s | 20.444MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array/cl5_nebula_norm_0024.fof.smt2 |    0.023s | 20.48MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0021.fof.smt2 |    0.023s | 19.172MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0123.fof.smt2 |    0.023s | 20.208MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0015.fof.smt2 |    0.023s | 20.412MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_prop/quaternion_ds1_symm_0001.fof.smt2 |    0.023s | 20.424MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_prop/cl5_nebula_norm_0004.fof.smt2 |    0.023s | 20.28MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_prop/cl5_nebula_norm_0006.fof.smt2 |    0.023s | 20.3MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_forall/cl5_nebula_norm_0029.fof.smt2 |    0.023s | 20.264MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify/thruster_symm_0187.fof.smt2 |    0.024s | 20.524MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_arithmetics/cl5_nebula_norm_0003.fof.smt2 |    0.024s | 20.292MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_arithmetics/cl5_nebula_norm_0006.fof.smt2 |    0.024s | 20.444MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0014.fof.smt2 |    0.024s | 20.512MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_prop/cl5_nebula_norm_0018.fof.smt2 |    0.024s | 20.484MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0039.fof.smt2 |    0.024s | 20.568MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_arithmetics/quaternion_ds1_symm_0001.fof.smt2 |    0.025s | 20.472MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_arithmetics/cl5_nebula_norm_0013.fof.smt2 |    0.025s | 20.428MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array/thruster_symm_0189.fof.smt2 |    0.025s | 20.708MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1257.fof.smt2 |    0.025s | 19.292MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0106.fof.smt2 |    0.025s | 20.46MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0126.fof.smt2 |    0.025s | 20.28MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0074.fof.smt2 |    0.025s | 20.332MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1118.fof.smt2 |    0.025s | 19.02MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1039.fof.smt2 |    0.025s | 19.2MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0798.fof.smt2 |    0.025s | 19.292MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_prop/thruster_symm_0031.fof.smt2 |    0.025s | 20.604MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0031.fof.smt2 |    0.025s | 20.492MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0066.fof.smt2 |    0.026s | 20.5MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0779.fof.smt2 |    0.026s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1073.fof.smt2 |    0.026s | 19.284MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0297.fof.smt2 |    0.026s | 19.064MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0140.fof.smt2 |    0.026s | 19.28MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0105.fof.smt2 |    0.026s | 20.376MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1315.fof.smt2 |    0.026s | 19.076MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/quaternion_ds1_symm_0001.fof.smt2 |    0.026s | 20.424MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0010.fof.smt2 |    0.026s | 20.484MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.637372.smt2               |    0.027s | 20.06MiB| sat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array/quaternion_ds1_symm_0423.fof.smt2 |    0.027s | 21.08MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0546.fof.smt2 |    0.027s | 19.064MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0385.fof.smt2 |    0.027s | 19.12MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0119.fof.smt2 |    0.027s | 19.08MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0536.fof.smt2 |    0.027s | 19.036MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1490.fof.smt2 |    0.027s | 21.068MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0014.fof.smt2 |    0.027s | 19.08MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0020.fof.smt2 |    0.027s | 20.624MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0214.fof.smt2 |    0.028s | 19.324MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/thruster_symm_1704.fof.smt2 |    0.028s | 19.196MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0293.fof.smt2 |    0.028s | 19.288MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/why/smtlibfe2816.smt2                |    0.029s | 19.384MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0133.fof.smt2 |    0.029s | 19.028MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1213.fof.smt2 |    0.029s | 19.228MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0258.fof.smt2 |    0.029s | 19.064MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1299.fof.smt2 |    0.030s | 19.196MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/thruster_symm_1765.fof.smt2 |    0.030s | 20.744MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0111.fof.smt2 |    0.030s | 20.364MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1297.fof.smt2 |    0.030s | 19.3MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_prop/quaternion_ds1_symm_0017.fof.smt2 |    0.030s | 21.056MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0011.fof.smt2 |    0.030s | 19.036MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array/thruster_symm_0155.fof.smt2 |    0.031s | 19.112MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1322.fof.smt2 |    0.031s | 19.288MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.627094.smt2                   |    0.032s | 19.796MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array/thruster_symm_0151.fof.smt2 |    0.032s | 19.056MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0033.fof.smt2 |    0.032s | 18.984MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_0614.fof.smt2 |    0.032s | 19.188MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/quaternion_ds1_symm_1304.fof.smt2 |    0.032s | 19.156MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.624862.smt2               |    0.033s | 20.032MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.625933.smt2                   |    0.034s | 19.696MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0052.fof.smt2 |    0.034s | 20.456MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/aviation/clash_alloc_why.smt2        |    0.035s | 19.976MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0005.fof.smt2 |    0.035s | 20.392MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/why/smtlib8e6000.smt2                |    0.037s | 19.964MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.629241.smt2               |    0.039s | 19.776MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/why/smtlibdba7a4.smt2                |    0.040s | 21.248MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/why/smtlib14c92b.smt2                |    0.040s | 21.244MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.951712.smt2                   |    0.041s | 21.648MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/why/smtlibfc99e2.smt2                |    0.041s | 21.4MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/why/smtlibdff996.smt2                |    0.041s | 21.244MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/why/smtlibb47bdc.smt2                |    0.041s | 21.46MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/aviation/bts6453_why.smt2            |    0.042s | 23.22MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/why/smtlibd85203.smt2                |    0.042s | 21.44MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/why/smtlibf3ad77.smt2                |    0.043s | 21.508MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.626115.smt2               |    0.044s | 19.576MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.629331.smt2               |    0.045s | 19.8MiB| sat | 0 |  |  |
|non-incremental/AUFNIRA/aviation/minusminus_why.smt2         |    0.047s | 23.248MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.641708.smt2                   |    0.047s | 19.376MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.630683.smt2               |    0.049s | 20.052MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.629149.smt2               |    0.050s | 19.468MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.631366.smt2                   |    0.051s | 20.34MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/aviation/conflict_why.smt2           |    0.054s | 23.12MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/aviation/consts_why.smt2             |    0.055s | 23.296MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/aviation/bts6364_why.smt2            |    0.055s | 23.428MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.951208.smt2                   |    0.055s | 22.544MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.549864.smt2                   |    0.055s | 21.272MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.951967.smt2                   |    0.059s | 21.068MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_arithmetics/cl5_nebula_norm_0005.fof.smt2 |    0.060s | 21.424MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_prop/cl5_nebula_norm_0005.fof.smt2 |    0.065s | 21.348MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/aviation/bts0071_why.smt2            |    0.069s | 25.416MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/aviation/bts0063_why.smt2            |    0.071s | 25.244MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.701134.smt2                   |    0.071s | 23.632MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.677614.smt2                   |    0.072s | 22.156MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.549916.smt2               |    0.078s | 23.368MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.701866.smt2                   |    0.078s | 22.096MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.624507.smt2                   |    0.080s | 26.26MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.676882.smt2                   |    0.082s | 23.632MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.634248.smt2                   |    0.083s | 20.172MiB| sat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.620661.smt2                   |    0.085s | 29.912MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_structure_prop/cl5_nebula_norm_0017.fof.smt2 |    0.087s | 21.632MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.620440.smt2               |    0.090s | 29.02MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.627369.smt2               |    0.090s | 28.32MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.628546.smt2                   |    0.091s | 26.272MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.623344.smt2               |    0.091s | 27.736MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_arithmetics/cl5_nebula_norm_0012.fof.smt2 |    0.091s | 21.548MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.637082.smt2               |    0.103s | 29.408MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.950232.smt2               |    0.111s | 26.812MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.950199.smt2                   |    0.113s | 25.584MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.622683.smt2                   |    0.127s | 25.824MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/thruster_symm_0001.fof.smt2 |    0.133s | 24.192MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.710024.smt2               |    0.148s | 32.668MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.709094.smt2                   |    0.226s | 39.824MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/quaternion_ds1_symm_0011.fof.smt2 |    0.229s | 30.752MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.622079.smt2               |    0.396s | 33.624MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.688983.smt2               |    0.777s | 91.664MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.689469.smt2                   |    0.891s | 105.0MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.700096.smt2               |    1.259s | 24.108MiB| unknown | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.674037.smt2               |    1.334s | 24.172MiB| unknown | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.622405.smt2                   |    1.514s | 522.0MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.638004.smt2                   |    2.933s | 548.0MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.640149.smt2                   |    4.580s | 1113.0MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.639724.smt2                   |    9.486s | 2421.0MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.637557.smt2                   |   10.525s | 2290.0MiB| unsat | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array/cl5_nebula_norm_0016.fof.smt2 |   20.007s | 38.796MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array/cl5_nebula_norm_0015.fof.smt2 |   20.007s | 26.004MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array/cl5_nebula_norm_0011.fof.smt2 |   20.008s | 32.28MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0012.fof.smt2 |   20.008s | 48.212MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0036.fof.smt2 |   20.008s | 33.632MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array/cl5_nebula_norm_0010.fof.smt2 |   20.009s | 50.216MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array/cl5_nebula_norm_0007.fof.smt2 |   20.009s | 55.436MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array/cl5_nebula_norm_0027.fof.smt2 |   20.009s | 58.156MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0019.fof.smt2 |   20.009s | 34.328MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0038.fof.smt2 |   20.009s | 26.308MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0021.fof.smt2 |   20.010s | 29.852MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array/cl5_nebula_norm_0025.fof.smt2 |   20.011s | 43.364MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0008.fof.smt2 |   20.011s | 55.492MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0006.fof.smt2 |   20.011s | 34.544MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array/cl5_nebula_norm_0008.fof.smt2 |   20.012s | 47.62MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0128.fof.smt2 |   20.013s | 58.16MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0048.fof.smt2 |   20.013s | 32.132MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0067.fof.smt2 |   20.013s | 25.996MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0075.fof.smt2 |   20.014s | 42.616MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0004.fof.smt2 |   20.015s | 169.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0120.fof.smt2 |   20.017s | 49.252MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0039.fof.smt2 |   20.022s | 64.212MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.675263.smt2                   |   20.025s | 28.3MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/nasa/fol_simplify_array_only/cl5_nebula_norm_0016.fof.smt2 |   20.029s | 44.412MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.692863.smt2                   |   20.030s | 186.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/nasa/vc_normalize_subst/cl5_nebula_norm_0015.fof.smt2 |   20.037s | 485.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.942623.smt2                   |   20.050s | 288.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.912497.smt2               |   20.059s | 323.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.659996.smt2                   |   20.063s | 436.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.921143.smt2               |   20.068s | 321.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.699515.smt2                   |   20.069s | 81.972MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.610121.smt2                   |   20.071s | 251.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.938815.smt2                   |   20.074s | 353.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.916820.smt2               |   20.081s | 323.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.908174.smt2               |   20.093s | 327.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.619415.smt2                   |   20.109s | 920.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.614416.smt2                   |   20.117s | 387.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/aviation/array_double_why.smt2       |   20.133s | 734.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.635554.smt2                   |   20.135s | 1162.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.707123.smt2               |   20.136s | 606.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.859684.smt2                   |   20.143s | 530.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.682065.smt2               |   20.146s | 1432.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.634210.smt2                   |   20.152s | 332.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.672518.smt2                   |   20.168s | 653.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.691631.smt2                   |   20.172s | 1188.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.667943.smt2                   |   20.177s | 1012.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.619057.smt2                   |   20.177s | 385.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.818028.smt2                   |   20.180s | 1350.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.867637.smt2                   |   20.192s | 2134.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.612263.smt2               |   20.197s | 760.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.864863.smt2               |   20.201s | 1582.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.616911.smt2               |   20.202s | 368.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.701996.smt2               |   20.203s | 1458.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.698880.smt2                   |   20.205s | 1264.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.675941.smt2               |   20.209s | 848.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.682088.smt2                   |   20.215s | 577.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.648629.smt2                   |   20.216s | 761.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.677987.smt2                   |   20.219s | 1919.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.647696.smt2               |   20.222s | 2387.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.849348.smt2               |   20.236s | 2225.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.861632.smt2                   |   20.243s | 1801.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.827926.smt2                   |   20.243s | 2156.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.831856.smt2                   |   20.249s | 2253.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.561727.smt2               |   20.249s | 585.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.763220.smt2                   |   20.249s | 2174.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.661347.smt2                   |   20.250s | 1142.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.758499.smt2                   |   20.250s | 2087.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.939774.smt2               |   20.253s | 2620.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.868686.smt2                   |   20.253s | 2053.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.665247.smt2               |   20.254s | 2107.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.649261.smt2                   |   20.255s | 2158.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.944272.smt2               |   20.257s | 2100.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.768674.smt2               |   20.259s | 2106.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.933657.smt2                   |   20.259s | 1551.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.678148.smt2                   |   20.261s | 2356.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.607667.smt2               |   20.266s | 355.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.649332.smt2                   |   20.269s | 2942.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.797178.smt2               |   20.270s | 2104.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.872699.smt2                   |   20.273s | 2346.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.881352.smt2                   |   20.275s | 2570.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.825916.smt2                   |   20.279s | 707.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.696723.smt2                   |   20.280s | 743.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.877834.smt2               |   20.283s | 2178.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.662227.smt2               |   20.285s | 2618.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.660068.smt2               |   20.290s | 2508.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.954082.smt2                   |   20.291s | 928.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.822925.smt2               |   20.294s | 2297.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.759134.smt2               |   20.298s | 2223.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.621785.smt2               |   20.299s | 3013.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.699383.smt2               |   20.301s | 2873.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.845575.smt2                   |   20.302s | 2799.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.655425.smt2                   |   20.304s | 2178.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.635015.smt2               |   20.305s | 2746.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.618374.smt2                   |   20.305s | 825.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.940633.smt2                   |   20.308s | 2455.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.956070.smt2                   |   20.309s | 2839.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.767657.smt2                   |   20.311s | 2570.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.628941.smt2               |   20.311s | 3009.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.914698.smt2                   |   20.317s | 2793.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.663700.smt2                   |   20.319s | 3133.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.714299.smt2                   |   20.320s | 379.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.647389.smt2                   |   20.320s | 3146.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.561423.smt2                   |   20.324s | 457.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.912508.smt2                   |   20.327s | 1623.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.698113.smt2               |   20.328s | 2739.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.647039.smt2                   |   20.335s | 3035.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.833776.smt2                   |   20.347s | 2098.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.845302.smt2               |   20.350s | 2675.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.954058.smt2               |   20.352s | 1276.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.788836.smt2               |   20.359s | 2849.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.856156.smt2                   |   20.359s | 1188.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.671569.smt2               |   20.360s | 3030.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.921280.smt2                   |   20.362s | 1624.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.634134.smt2                   |   20.364s | 3773.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.801381.smt2                   |   20.367s | 1594.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.666124.smt2                   |   20.367s | 2082.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.837455.smt2               |   20.370s | 2375.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.947491.smt2                   |   20.375s | 2666.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.782459.smt2                   |   20.381s | 1251.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.671895.smt2               |   20.384s | 3104.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.613729.smt2                   |   20.386s | 1016.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.853506.smt2               |   20.387s | 1581.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.806772.smt2               |   20.390s | 2538.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.751753.smt2               |   20.390s | 2810.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.560602.smt2               |   20.394s | 1348.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.663327.smt2                   |   20.396s | 1141.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.815818.smt2                   |   20.400s | 2305.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.801047.smt2                   |   20.401s | 2599.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.811946.smt2                   |   20.410s | 1618.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.825014.smt2                   |   20.411s | 2365.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.848054.smt2                   |   20.411s | 1705.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.821053.smt2                   |   20.414s | 2255.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.955132.smt2               |   20.415s | 2083.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/aviation/false2_why.smt2             |   20.420s | 2343.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.865646.smt2                   |   20.422s | 2468.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.876764.smt2               |   20.426s | 2112.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.763578.smt2                   |   20.427s | 2567.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.849188.smt2                   |   20.429s | 2368.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.609085.smt2                   |   20.435s | 1450.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.653587.smt2               |   20.440s | 4108.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.864684.smt2                   |   20.443s | 2441.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.918728.smt2                   |   20.445s | 4195.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.940390.smt2                   |   20.447s | 2325.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.673963.smt2               |   20.451s | 4340.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.780306.smt2               |   20.455s | 2242.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.919084.smt2                   |   20.459s | 2793.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.872800.smt2               |   20.459s | 2109.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.672054.smt2               |   20.463s | 3096.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.873326.smt2                   |   20.476s | 2621.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.810979.smt2               |   20.477s | 2569.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.669565.smt2                   |   20.479s | 2421.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.614780.smt2                   |   20.480s | 1895.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.746010.smt2                   |   20.480s | 2802.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.914342.smt2                   |   20.481s | 4020.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.673421.smt2                   |   20.482s | 2728.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.657075.smt2               |   20.486s | 2213.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.645472.smt2               |   20.492s | 2147.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.852276.smt2                   |   20.499s | 1702.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.654657.smt2                   |   20.500s | 2811.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.772111.smt2               |   20.505s | 1854.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/aviation/bug390_why.smt2             |   20.507s | 2829.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.809917.smt2                   |   20.509s | 1580.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.714183.smt2               |   20.510s | 1094.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.908122.smt2                   |   20.511s | 1823.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.673103.smt2                   |   20.513s | 1750.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.857393.smt2               |   20.516s | 2208.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.817734.smt2               |   20.517s | 2204.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.869659.smt2                   |   20.521s | 2516.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.743633.smt2               |   20.521s | 2050.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.845939.smt2                   |   20.525s | 4113.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/aviation/extern_why.smt2             |   20.526s | 2902.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.646409.smt2                   |   20.529s | 2407.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.711486.smt2               |   20.537s | 1400.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.865953.smt2               |   20.538s | 2469.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.792971.smt2               |   20.538s | 4185.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.805649.smt2                   |   20.542s | 1724.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.778229.smt2                   |   20.542s | 1570.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/aviation/quantified_pointer_why.smt2 |   20.548s | 3069.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.940561.smt2               |   20.548s | 3736.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.925667.smt2                   |   20.549s | 1774.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.632775.smt2               |   20.550s | 1103.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/aviation/jeannin_why.smt2            |   20.556s | 3093.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.633926.smt2                   |   20.557s | 3655.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.766657.smt2                   |   20.562s | 2073.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.958319.smt2               |   20.563s | 1700.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.835930.smt2                   |   20.565s | 2213.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/aviation/bts0199_why.smt2            |   20.567s | 3165.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.789955.smt2               |   20.567s | 4671.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.621866.smt2                   |   20.568s | 4490.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.958311.smt2                   |   20.572s | 4641.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.784698.smt2               |   20.572s | 1637.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.675189.smt2                   |   20.573s | 4646.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/aviation/bts0187_why.smt2            |   20.575s | 3193.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.853412.smt2                   |   20.575s | 2135.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.685296.smt2                   |   20.577s | 3137.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.916894.smt2                   |   20.578s | 1623.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.695462.smt2                   |   20.578s | 4243.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.788234.smt2                   |   20.579s | 3465.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.854640.smt2               |   20.584s | 2162.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.776019.smt2               |   20.592s | 2108.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.681188.smt2               |   20.596s | 1935.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.659901.smt2               |   20.598s | 3136.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.780093.smt2                   |   20.598s | 4081.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.955145.smt2                   |   20.598s | 2097.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/aviation/fs252_why.smt2              |   20.602s | 3514.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.696888.smt2               |   20.602s | 3036.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.659604.smt2               |   20.605s | 2400.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.697550.smt2               |   20.608s | 2608.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.711517.smt2                   |   20.616s | 1033.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.943708.smt2                   |   20.618s | 2406.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.607838.smt2                   |   20.620s | 1699.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.875663.smt2                   |   20.620s | 2198.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.699441.smt2                   |   20.623s | 4665.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.711170.smt2                   |   20.628s | 1806.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.640330.smt2                   |   20.630s | 3876.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.647483.smt2               |   20.632s | 2560.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.763357.smt2               |   20.633s | 2263.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.654080.smt2               |   20.634s | 2910.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.776249.smt2                   |   20.639s | 2850.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.944289.smt2                   |   20.651s | 2018.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.706995.smt2                   |   20.655s | 1890.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.757428.smt2                   |   20.657s | 2337.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.694291.smt2                   |   20.663s | 2614.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.813971.smt2               |   20.664s | 1311.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.747041.smt2                   |   20.666s | 1875.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.609741.smt2                   |   20.667s | 1449.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.702400.smt2                   |   20.669s | 2361.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.674628.smt2                   |   20.675s | 1262.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.946559.smt2                   |   20.677s | 1189.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.656050.smt2               |   20.678s | 1994.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.798358.smt2               |   20.679s | 2473.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.863623.smt2                   |   20.680s | 2245.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.808947.smt2                   |   20.693s | 2556.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.925543.smt2               |   20.696s | 2308.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.823496.smt2               |   20.698s | 2800.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/aviation/bts5878_why.smt2            |   20.699s | 4488.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/aviation/bts0073_why.smt2            |   20.702s | 4559.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.673310.smt2                   |   20.703s | 3416.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.750959.smt2                   |   20.706s | 2876.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.764451.smt2               |   20.707s | 2171.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.821986.smt2                   |   20.708s | 2765.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.686904.smt2                   |   20.711s | 1137.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.684910.smt2                   |   20.714s | 1137.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.560298.smt2                   |   20.716s | 1278.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.801385.smt2               |   20.719s | 2105.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.706191.smt2                   |   20.724s | 2156.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/aviation/axiomatic_why.smt2          |   20.726s | 4538.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.695337.smt2                   |   20.726s | 3333.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.909292.smt2                   |   20.730s | 2209.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.754420.smt2                   |   20.731s | 2803.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.876712.smt2                   |   20.736s | 2194.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.844945.smt2                   |   20.743s | 1387.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.881698.smt2                   |   20.745s | 2684.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/aviation/return_why.smt2             |   20.747s | 4870.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.942602.smt2               |   20.749s | 1181.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.797113.smt2                   |   20.750s | 1603.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.645715.smt2               |   20.750s | 2891.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.823996.smt2                   |   20.752s | 2148.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.788577.smt2                   |   20.762s | 2855.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.755420.smt2                   |   20.763s | 1585.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.697961.smt2               |   20.770s | 2568.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.647252.smt2                   |   20.774s | 2747.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.828944.smt2                   |   20.776s | 2112.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.805592.smt2               |   20.781s | 2106.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.881798.smt2               |   20.782s | 2141.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.858887.smt2               |   20.782s | 2742.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.664248.smt2               |   20.785s | 2709.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.714184.smt2                   |   20.785s | 1590.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.713843.smt2                   |   20.787s | 2431.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.661728.smt2                   |   20.790s | 3133.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.857642.smt2                   |   20.792s | 2886.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.746656.smt2                   |   20.793s | 2925.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.832874.smt2                   |   20.794s | 2232.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.946545.smt2               |   20.796s | 2412.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.880725.smt2                   |   20.797s | 2150.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.871650.smt2                   |   20.801s | 2177.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.762578.smt2                   |   20.812s | 2073.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.809799.smt2               |   20.814s | 2105.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.943691.smt2               |   20.815s | 2413.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.868836.smt2               |   20.817s | 2271.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.829638.smt2               |   20.820s | 2447.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.638801.smt2               |   20.824s | 3021.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.749181.smt2                   |   20.826s | 2351.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.783662.smt2                   |   20.831s | 2421.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.830659.smt2               |   20.832s | 2538.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.667166.smt2                   |   20.834s | 1888.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.761507.smt2                   |   20.836s | 2535.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.661260.smt2               |   20.840s | 3097.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.829528.smt2                   |   20.841s | 2455.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.633492.smt2                   |   20.845s | 2665.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.775888.smt2                   |   20.846s | 2450.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.858350.smt2               |   20.849s | 2273.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.918064.smt2                   |   20.850s | 2257.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.661781.smt2               |   20.855s | 2407.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.759141.smt2                   |   20.857s | 2540.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.753349.smt2                   |   20.858s | 2658.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.702239.smt2                   |   20.863s | 1916.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.857109.smt2                   |   20.866s | 2395.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.638333.smt2                   |   20.868s | 3830.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.938740.smt2               |   20.870s | 2843.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.713145.smt2                   |   20.875s | 3772.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.835099.smt2               |   20.881s | 2653.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.802565.smt2               |   20.883s | 2592.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.940318.smt2               |   20.887s | 2350.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.747589.smt2               |   20.892s | 2959.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.816994.smt2                   |   20.892s | 2682.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.644770.smt2               |   20.895s | 1954.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.857918.smt2                   |   20.895s | 2701.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.750318.smt2                   |   20.900s | 2845.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.955746.smt2                   |   20.901s | 2707.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.873870.smt2               |   20.909s | 2155.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.692368.smt2                   |   20.912s | 4674.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.796143.smt2                   |   20.913s | 2048.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.710520.smt2                   |   20.915s | 2559.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.770035.smt2                   |   20.916s | 1657.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.873672.smt2                   |   20.916s | 2741.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.712193.smt2               |   20.917s | 3041.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.820023.smt2                   |   20.918s | 1990.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.750595.smt2               |   20.926s | 2134.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.653905.smt2               |   20.926s | 2744.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.926856.smt2                   |   20.932s | 2190.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.922450.smt2                   |   20.934s | 2228.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.661994.smt2                   |   20.950s | 3567.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.923114.smt2                   |   20.953s | 4016.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.683368.smt2                   |   20.953s | 2771.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.846296.smt2               |   20.955s | 2973.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.833458.smt2                   |   20.957s | 2566.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.803504.smt2                   |   20.958s | 2553.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.826803.smt2               |   20.959s | 2341.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.809583.smt2                   |   20.960s | 2497.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.767299.smt2                   |   20.964s | 2683.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.913678.smt2                   |   20.965s | 2248.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.834515.smt2               |   20.968s | 2564.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.879676.smt2                   |   20.974s | 2202.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.617112.smt2                   |   20.975s | 2796.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.880728.smt2               |   20.975s | 2109.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.831243.smt2               |   20.976s | 2583.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.784716.smt2                   |   20.978s | 3036.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.687278.smt2                   |   20.980s | 3133.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.751341.smt2                   |   20.983s | 2257.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.774116.smt2                   |   20.984s | 2881.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.865313.smt2                   |   20.991s | 2488.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.860981.smt2               |   20.993s | 2773.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.659235.smt2                   |   20.994s | 3023.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.692734.smt2                   |   20.997s | 2449.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.869313.smt2                   |   20.997s | 3357.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.685476.smt2                   |   20.999s | 3193.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.760228.smt2               |   21.001s | 2114.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.929723.smt2               |   21.003s | 2571.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.561997.smt2                   |   21.005s | 5427.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.796779.smt2                   |   21.006s | 2113.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.780480.smt2                   |   21.006s | 2743.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.661907.smt2                   |   21.021s | 3193.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.821634.smt2                   |   21.025s | 2709.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.655748.smt2                   |   21.027s | 2521.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.821891.smt2               |   21.034s | 2143.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.746428.smt2               |   21.034s | 2054.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.711639.smt2                   |   21.035s | 3583.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.659732.smt2                   |   21.037s | 2170.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.829846.smt2                   |   21.043s | 2064.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.759499.smt2                   |   21.046s | 2660.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.754911.smt2               |   21.056s | 2812.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.786512.smt2                   |   21.062s | 2567.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.663869.smt2                   |   21.064s | 2934.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.659078.smt2               |   21.067s | 3083.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.645857.smt2               |   21.068s | 3796.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.790700.smt2                   |   21.087s | 2562.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.635849.smt2               |   21.088s | 2841.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.667685.smt2                   |   21.091s | 5227.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.939846.smt2                   |   21.099s | 2491.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.740747.smt2                   |   21.102s | 2489.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.838140.smt2                   |   21.103s | 2202.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.779430.smt2                   |   21.122s | 2760.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.777173.smt2               |   21.123s | 2491.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.861982.smt2               |   21.126s | 2342.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.640466.smt2                   |   21.129s | 3863.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.744873.smt2                   |   21.129s | 2433.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.807772.smt2                   |   21.134s | 2619.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.662069.smt2               |   21.135s | 2812.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.635953.smt2                   |   21.135s | 4395.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.827387.smt2               |   21.135s | 2581.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.775261.smt2                   |   21.137s | 2400.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.833494.smt2               |   21.149s | 2466.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.652843.smt2               |   21.151s | 3072.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.837770.smt2                   |   21.170s | 3153.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.647018.smt2               |   21.171s | 2955.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.699496.smt2                   |   21.171s | 7628.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.850480.smt2               |   21.172s | 2284.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.869906.smt2               |   21.173s | 2068.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.800411.smt2                   |   21.177s | 2353.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.714922.smt2               |   21.180s | 4336.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.655977.smt2                   |   21.182s | 3013.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.674024.smt2               |   21.191s | 5316.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.765586.smt2                   |   21.195s | 2396.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.838638.smt2               |   21.203s | 3220.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.784327.smt2                   |   21.205s | 2912.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.629976.smt2                   |   21.207s | 4709.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.817643.smt2                   |   21.209s | 2687.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.799236.smt2                   |   21.209s | 2426.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.792845.smt2                   |   21.216s | 2405.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.909956.smt2                   |   21.224s | 3982.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.910312.smt2                   |   21.224s | 2779.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.794968.smt2                   |   21.233s | 2262.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.675244.smt2                   |   21.235s | 7626.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.673324.smt2               |   21.240s | 2873.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.944599.smt2                   |   21.247s | 4122.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.697344.smt2                   |   21.258s | 2661.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.785903.smt2               |   21.259s | 2793.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.635501.smt2               |   21.263s | 2959.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.877339.smt2                   |   21.273s | 2600.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.682948.smt2                   |   21.319s | 2257.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.825782.smt2               |   21.327s | 2146.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.636136.smt2                   |   21.336s | 8226.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.805315.smt2                   |   21.363s | 2536.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.861289.smt2                   |   21.367s | 3052.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.843953.smt2                   |   21.369s | 2177.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.636226.smt2                   |   21.369s | 3441.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.781509.smt2               |   21.371s | 4101.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.860677.smt2                   |   21.372s | 2312.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.792511.smt2                   |   21.380s | 2850.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.712540.smt2               |   21.385s | 8374.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.695009.smt2                   |   21.398s | 3090.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.700083.smt2               |   21.401s | 5316.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.767580.smt2               |   21.406s | 2296.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.687448.smt2                   |   21.429s | 2868.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.612465.smt2                   |   21.450s | 2780.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.697561.smt2                   |   21.455s | 3306.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.649061.smt2                   |   21.460s | 2992.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.635732.smt2               |   21.462s | 2929.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.794151.smt2               |   21.471s | 3044.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.647637.smt2               |   21.471s | 7304.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.658206.smt2                   |   21.475s | 2876.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.877685.smt2                   |   21.513s | 2621.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.804679.smt2                   |   21.533s | 2539.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.756005.smt2               |   21.534s | 2821.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.633330.smt2               |   21.563s | 4679.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.929857.smt2                   |   21.574s | 3142.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.755062.smt2                   |   21.579s | 2949.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.791875.smt2                   |   21.585s | 2908.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.697673.smt2                   |   21.586s | 2877.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.700022.smt2               |   21.591s | 4387.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.923470.smt2                   |   21.597s | 2704.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.670862.smt2               |   21.601s | 2749.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.742487.smt2               |   21.621s | 2701.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.825598.smt2                   |   21.637s | 2728.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.787622.smt2                   |   21.767s | 2980.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.933524.smt2               |   21.817s | 3954.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.837129.smt2                   |   21.833s | 3179.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.818913.smt2               |   21.849s | 3310.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.663953.smt2                   |   21.854s | 3526.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.562301.smt2               |   21.923s | 5434.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/z3.638194.smt2                   |   22.003s | 3831.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.665768.smt2               |   22.023s | 4097.0MiB| timeout | 0 |  |  |
|non-incremental/AUFNIRA/FFT/smtlib.633611.smt2               |   22.757s | 7370.0MiB| timeout | 0 |  |  |
