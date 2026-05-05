# .

* SAT 0
* UNSAT 32
* TIMEOUT 0
* UNKNOWN 7

* UNSET 21

* ERROR 21

# Meta data

<pre>
Ramon benchmark for Z3
-
Job description: 
Job tag: gen-patch-mariposa-uc
Runner: rise-runner-1
Z3 repo: CanCebeci/z3
Z3 commit: aec453eb9bad24f44f4f6101b46004389bd16bb0
Z3 branch: master
Z3 options: "%OPTIONS2%"
Z3 inputs: inputs/mariposa/unstable_core
Z3 commit message: Enforce stickiness of max-generation

</pre>


# Statistics
|FILE                                                         |TIME     |MEM        | STATUS   | EXIT | STDOUT | STDERR | 
|------------|----------:|---------:|-------------:| ----------:|--------|--------| 
|d_lvbkv-lib-Math-Nonlinear.i.dfy.Impl__NonlinearLemmas.__default.div__denom__ge__1.smt2 |    0.061s | 21.324MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall2.smt2 |    0.084s | 22.816MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Checksums-BitLemmas.i.dfy.Impl__BitLemmas.__default.eq__from__unpack__LittleEndian__Uint32__eq.smt2 |    0.126s | 23.632MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__0__self__uint64.smt2 |    0.185s | 37.42MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Base-BitsetLemmas.i.dfy.Impl__BitsetLemmas.__default.set__bit__to__1__self__uint64.smt2 |    0.187s | 37.244MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Base-total_order_impl.i.dfy.Impl__Total__Order__Impl.__default.ArrayLargestLtePlus1Linear.smt2 |    0.236s | 27.8MiB| unknown | 0 |  |  |
|d_lvbkv-lib-Lang-LinearSequence.i.dfy.Impl__LinearSequence__i.__default.AllocAndMoveLseq.smt2 |    0.259s | 28.584MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__div__denominator.smt2 |    0.359s | 24.168MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.UniqueRepr.smt2 |    0.361s | 30.98MiB| unsat | 0 |  |  |
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubReprLowerBound.smt2 |    0.469s | 31.428MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallByteArray.smt2 |    0.520s | 36.932MiB| unsat | 0 |  |  |
|d_lvbkv-MapSpec-TSJMap_Refines_ThreeStateVersionedMap.i.dfy.Impl__TSJMap__Refines__ThreeStateVersionedMap.__default.RefinesReplay.smt2 |    0.554s | 36.232MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Marshalling-Math.i.dfy.Impl__Math.__default.lemma__2toX.smt2 |    0.684s | 57.988MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallByteArrayInterior.smt2 |    0.845s | 38.684MiB| unsat | 0 |  |  |
|d_fvbkv-Impl-JournalistModel.i.dfy.CheckWellformed__JournalistModel.__default.append.smt2 |    0.983s | 59.064MiB| unknown | 0 |  |  |
|d_lvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2 |    1.015s | 58.044MiB| unknown | 0 |  |  |
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint64Array.smt2 |    1.253s | 43.656MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallUint32Array.smt2 |    1.463s | 45.14MiB| unknown | 0 |  |  |
|d_lvbkv-PivotBetree-PivotBetreeSpecWFNodes.i.dfy.Impl__PivotBetreeSpecWFNodes.__default.ValidSplitWritesInvNodes.smt2 |    1.641s | 96.144MiB| unsat | 0 |  |  |
|d_fvbkv-ByteBlockCacheSystem-InterpretationDisk.i.dfy.Impl__InterpretationDisk.__default.RefinesProcessWrite.smt2 |    1.790s | 96.916MiB| unknown | 0 |  |  |
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__DynamicPkv.DynamicPkv.Append.smt2 |    2.006s | 61.968MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Marshalling-GenericMarshalling.i.dfy.Impl__GenericMarshalling.__default.MarshallArray.smt2 |    2.153s | 57.38MiB| unknown | 0 |  |  |
|d_lvbkv-Impl-JournalistImpl.i.dfy.Impl__JournalistImpl.Journalist.append.smt2 |    2.301s | 61.144MiB| unsat | 0 |  |  |
|d_komodo-verified-ptebits.i.dfyImpl___module.__default.lemma__l1ptesmatch.smt2 |    3.104s | 279.0MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2 |    3.325s | 63.684MiB| unsat | 0 |  |  |
|d_fvbkv-Betree-BetreeInv.i.dfy.Impl__BetreeInv.__default.FlushPreservesLookups.smt2 |    4.233s | 93.704MiB| unsat | 0 |  |  |
|d_lvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__LMutableBtree.__default.InsertIndex.smt2 |    6.594s | 100.0MiB| unsat | 0 |  |  |
|d_fvbkv-lib-DataStructures-MutableBtree.i.dfy.Impl__MutableBtree.__default.SubIndex.smt2 |   15.245s | 106.0MiB| unknown | 0 |  |  |
|d_fvbkv-Impl-IOImpl.i.dfy.Impl__IOImpl.__default.PageInNodeResp.smt2 |   17.873s | 172.0MiB| unsat | 0 |  |  |
|d_fvbkv-ByteBlockCacheSystem-ByteSystem.i.dfy.Impl__ByteSystem.__default.ReqWrite2StepPreservesInv.smt2 |   19.009s | 189.0MiB| unsat | 0 |  |  |
|d_fvbkv-lib-DataStructures-LruImpl.i.dfy.Impl__LruImpl.LruImplQueue.Use.smt2 |   21.079s | 171.0MiB| unsat | 0 |  |  |
|d_lvbkv-lib-Buckets-BucketsLib.i.dfy.Impl__BucketsLib.__default.WFProperSplitBucketInList.smt2 |   21.807s | 123.0MiB| unsat | 0 |  |  |
|d_fvbkv-lib-DataStructures-BtreeModel.i.dfy.Impl__BtreeModel.__default.SplitIndexAllKeys.smt2 |   24.069s | 206.0MiB| unsat | 0 |  |  |
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify.smt2 |   25.889s | 227.0MiB| unsat | 0 |  |  |
|d_komodo-verified-sha-sha256.i.dfyImpl___module.__default.lemma__SHA256FinalHelper1.smt2 |   28.674s | 2867.0MiB| unsat | 0 |  |  |
|d_lvbkv-PivotBetree-PivotBetreeSpecRefinement.i.dfy.Impl__PivotBetreeSpecRefinement.__default.SplitChildrenConsistent.smt2 |   31.720s | 202.0MiB| unsat | 0 |  |  |
|d_komodo-verified-secprop-conf_ni.i.dfyImpl___module.__default.lemma__initL2PTable__loweq__pdb.smt2 |   35.806s | 334.0MiB| unsat | 0 |  |  |
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify__inner.smt2 |   44.587s | 412.0MiB| unsat | 0 |  |  |
|d_fvbkv-lib-Buckets-KMBPKVOps.i.dfy.Impl__KMBPKVOps.__default.IndexFillDpkv.smt2 |   50.421s | 248.0MiB| unsat | 0 |  |  |
|s_komodo-1504.4.smt2                                         |   80.244s | 4076.0MiB| unset | 124 |  |  |
|s_komodo-1509.4.smt2                                         |   80.300s | 5430.0MiB| unset | 124 |  |  |
|d_fvbkv-Impl-FlushPolicyImpl.i.dfy.Impl__FlushPolicyImpl.__default.runFlushPolicy.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|fs_dice-queries-L0.X509.AliasKeyTBS.Subject-7.smt2           | 1000.000s | -1B| unset | -1 |  |  |
|d_lvbkv-Impl-BucketGeneratorModel.i.dfy.Impl__BucketGeneratorModel.__default.GenComposeIsCompose.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|d_komodo-verified-sha-sha256-body-16-xx.gen.dfyImpl___module.__default.va__refined__Body__16__XXUnroller.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|d_fvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.WFpsaSubSeq.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|d_komodo-verified-sha-sha256-body-00-15.gen.dfyImpl___module.__default.va__refined__Body__00__15UnrolledRecursive.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|d_komodo-verified-verify.gen.dfyImpl___module.__default.va__lemma__svc__returning__verify__inner_k.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|d_fvbkv-Impl-QueryImpl.i.dfy.Impl__QueryImpl.__default.queryIterate.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|d_fvbkv-lib-Math-mod_auto_proofs.i.dfy.Impl__Math____mod__auto__proofs__i.__default.lemma__mod__induction__forall.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|fs_dice-queries-ASN1.Low.Base-3.smt2                         | 1000.000s | -1B| unset | -1 |  |  |
|d_lvbkv-lib-DataStructures-LinearDList.i.dfy.Impl__DList.DList.InsertBefore.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|d_lvbkv-Impl-MarshallingImpl.i.dfy.Impl__MarshallingImpl.__default.strictlySortedPivotsToVal.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|d_lvbkv-lib-Buckets-PackedKV.i.dfy.Impl__PackedKV.__default.BinarySearchQuery.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.__default.psaCanAppendI.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|d_fvbkv-lib-Math-mul.i.dfy.Impl__Math____mul__i.__default.lemma__mul__nonnegative.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|d_lvbkv-lib-DataStructures-LinearDList.i.dfy.Impl__DList.DList.InsertAfter.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|d_lvbkv-lib-Buckets-PackedStringArray.i.dfy.Impl__PackedStringArray.DynamicPsa.AppendSeq.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|d_lvbkv-lib-DataStructures-LinearContentMutableMap.i.dfy.Impl__LinearContentMutableMap.__default.Realloc.smt2 | 1000.000s | -1B| unset | -1 |  |  |
|fs_dice-queries-L0.X509.AliasKeyTBS.Issuer-7.smt2            | 1000.000s | -1B| unset | -1 |  |  |
